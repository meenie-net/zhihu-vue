<template>
  <div class="loading-box">
    <div class="loading-box-inner">
      <span class="loading-dot first-dot" />
      <span class="loading-dot second-dot" />
      <span class="loading-dot third-dot" />
      <span class="loading-dot fourth-dot" />
    </div>
  </div>
</template>

<script lang="ts" setup>

</script>

<style lang="less">
@keyframes Bounce{
    0%,100%{
        transform:translateY(-100%);
    }
    50%{
        transform:translateY(100%);
    }
}
.loading-box{
    display: flex;
    justify-content: center;
    .loading-box-inner{
        width: 70px;
        height: 80px;
        position: relative;
        .loading-dot{
            width: 6px;
            height: 6px;
            top: 40px;
            position: absolute;
            background-color: rgb(38, 134, 245);
            border-radius: 50%;
            animation-duration: 0.8s;
            animation-name: Bounce;
            animation-timing-function: ease-in-out;
            animation-fill-mode: both;
            transform-origin: center;
            animation-iteration-count: infinite;
        }
        .first-dot{
            animation-delay: 0;
        }
        .second-dot{
            left: 18px;
            animation-delay: -0.1s;
        }
        .third-dot{
            left: 39px;
            animation-delay: -0.2s;
        }
        .fourth-dot{
            left: 60px;
            animation-delay: -0.3s;
        }
    }
}
</style>
