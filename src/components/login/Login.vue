<template>
  <div class="login-container">
    <el-form
      :model="form"
      label-width="120px"
      size="large"
    >
      <el-form-item label="账号：">
        <el-input v-model="form.username" />
      </el-form-item>
      <el-form-item label="密码：">
        <el-input v-model="form.pwd" />
      </el-form-item>
      <el-form-item label="">
        <el-checkbox-group v-model="form.remeberMe">
          <el-checkbox
            label="记住我"
            name="remeberMe"
          />
        </el-checkbox-group>
      </el-form-item>
      <el-form-item>
        <el-button
          type="primary"
          @click="onSubmit"
        >
          登录
        </el-button>
        <el-button>去注册</el-button>
      </el-form-item>
    </el-form>
  </div>
</template>

<script lang="ts" setup>
import api from '@/api'
import { reactive } from 'vue'
import { useRouter } from 'vue-router'
import { SET_USER } from '@/store/constant'
import { userInfoStore } from '@/store/store'

const router = useRouter()

// do not use same name with ref
const form = reactive({
  username: '',
  pwd: '',
  remeberMe: ['false']
})

const onSubmit = () => {
  api.login(form).then(res => {
    localStorage.clear()
    localStorage.setItem('token', JSON.stringify(res.data.data.token))
    const store = userInfoStore()
    console.log(store.getUserInfo)
    store[SET_USER](res.data.data.userInfo)
    router.push({ path: '/', replace: true })
  })
}
</script>

<style>
.login-container{
  width: 400px;
  margin: 0 auto;
  margin-top: 300px;
}
</style>
