<template>
  <div class="bd-r">
    <div class="user-side user-creator-table">
      <div class="creator-table-header">
        <div class="table-header-left">
          <svg
            class="Zi Zi--Creator CreatorEntrance-creatorIcon"
            fill="currentColor"
            viewBox="0 0 24 24"
            width="20"
            height="20"
          >
            <path
              d="M15.075 15.388l-3.024 3.024a4.041 4.041 0 0 0-1.014 1.697l-.26.868C7.844 20.986 4.91 21 2 21c.026-3.325 0-3.304.59-3.956 1.237-1.368 6.251-.68 6.44-2.976.043-.518-.36-1.06-.725-1.69C6.285 8.87 5.512 2 11.5 2c5.988 0 5.15 7.072 3.246 10.378-.357.62-.795 1.217-.724 1.77.073.571.477.958 1.053 1.24zm5.402 1.672c.523.55.523.646.523 3.94a535.11 535.11 0 0 0-4.434-.028l3.911-3.912zm-7.88 2.699c.111-.37.312-.705.584-.978l4.76-4.76a.291.291 0 0 1 .412 0l1.626 1.626a.291.291 0 0 1 0 .411l-4.76 4.76c-.272.273-.608.474-.978.585l-1.96.588a.219.219 0 0 1-.272-.272l.589-1.96zm9.157-6.742a.839.839 0 0 1 0 1.187l-.94.94a.28.28 0 0 1-.395 0l-1.563-1.563a.28.28 0 0 1 0-.395l.94-.94a.839.839 0 0 1 1.187 0l.771.771z"
              fillRule="evenodd"
            />
          </svg>
          <span class="table-header-title">创作中心</span>
          <span class="table-header-level">Lv 2</span>
        </div>
        <div class="table-header-right">
          草稿箱(<span>3</span>)
        </div>
      </div>
      <div class="creator-table-body">
        <div class="table-body-unit">
          <button>
            <svg
              width="40"
              height="40"
              viewBox="0 0 40 40"
              class="GlobalWriteV2-navIcon"
              fill="currentColor"
            >
              <g
                fill="#06F"
                fillRule="evenodd"
              >
                <circle
                  cx="20"
                  cy="20"
                  r="20"
                  opacity=".12"
                />
                <path
                  d="M23.487 10.463c1.896 0 2.583.193 3.277.555a3.824 3.824 0 011.607 1.573c.371.678.569 1.35.569 3.206v8.472c0 1.855-.198 2.527-.569 3.205a3.824 3.824 0 01-1.607 1.573c-.694.363-1.381.556-3.277.556h-6.96c-1.895 0-2.583-.193-3.276-.556a3.824 3.824 0 01-1.608-1.573c-.37-.678-.568-1.35-.568-3.205v-8.472c0-1.855.197-2.528.568-3.206.37-.678.915-1.21 1.608-1.573.693-.362 1.38-.556 3.277-.556h6.959zm0 2.08h-6.96c-1.407 0-1.836.081-2.273.31a1.72 1.72 0 00-.735.72c-.234.427-.317.847-.317 2.224v8.472c0 1.377.083 1.796.317 2.224.172.316.412.551.735.72.437.229.866.31 2.274.31h6.959c1.407 0 1.836-.081 2.274-.31a1.72 1.72 0 00.735-.72c.234-.428.317-.847.317-2.224v-8.472c0-1.377-.083-1.797-.317-2.225a1.72 1.72 0 00-.735-.72c-.438-.228-.867-.309-2.274-.309zm-1.991 9.778v1.873h-5.955V22.32h5.955zm2.977-3.328v1.872h-8.932v-1.872h8.932zm0-3.33v1.873h-8.932v-1.872h8.932z"
                  fillRule="nonzero"
                />
              </g>
            </svg>
            <div class="table-body-unit-title">
              回答问题
            </div>
          </button>
        </div>
        <div class="table-body-unit">
          <button>
            <svg
              width="40"
              height="40"
              viewBox="0 0 40 40"
              class="GlobalWriteV2-navIcon"
              fill="currentColor"
            >
              <g
                fill="#FF9607"
                fillRule="evenodd"
              >
                <circle
                  cx="20"
                  cy="20"
                  r="20"
                  opacity=".12"
                />
                <path
                  d="M24.233 24.777v-9.555c0-.942-.748-1.706-1.67-1.706H13.61c-.922 0-1.67.764-1.67 1.707v9.554c0 .943.748 1.707 1.67 1.707h8.954c.921 0 1.669-.764 1.669-1.707zm3.478-10.349a2.302 2.302 0 013.297.243c.367.434.57.989.57 1.563v7.532c0 1.32-1.047 2.389-2.337 2.389a2.308 2.308 0 01-1.53-.583l-1.475-1.306v.512c0 2.073-1.644 3.753-3.672 3.753H13.61c-2.028 0-3.672-1.68-3.672-3.753v-9.555c0-2.074 1.644-3.754 3.672-3.754h8.954c2.028 0 3.672 1.68 3.672 3.754v.51l1.475-1.305zm-1.475 7.13l2.786 2.466a.33.33 0 00.219.083.338.338 0 00.334-.341v-7.532a.346.346 0 00-.082-.223.329.329 0 00-.47-.035l-2.787 2.466v3.116z"
                  fillRule="nonzero"
                />
              </g>
            </svg>
            <div class="table-body-unit-title">
              发视频
            </div>
          </button>
        </div>
        <div class="table-body-unit">
          <button>
            <svg
              width="40"
              height="40"
              viewBox="0 0 40 40"
              class="GlobalWriteV2-navIcon"
              fill="currentColor"
            >
              <g
                fill="none"
                fillRule="evenodd"
              >
                <circle
                  cx="20"
                  cy="20"
                  r="20"
                  fill="#F4C807"
                  opacity=".12"
                />
                <path d="M6 6h28v28H6z" />
                <path
                  fill="#F4C807"
                  d="M20.406 11.772l-2.172 2.176h-2.29c-1.438 0-1.875.085-2.322.324-.33.176-.575.422-.751.752-.24.448-.324.886-.324 2.326v7.12c0 1.44.085 1.878.324 2.326.176.33.421.576.75.752.421.225.834.314 2.08.323l7.35.001c1.438 0 1.876-.084 2.323-.324.33-.176.575-.422.751-.752.24-.448.324-.886.324-2.326v-4.905l2.172-2.175v7.08c0 1.94-.202 2.643-.58 3.352a3.95 3.95 0 01-1.643 1.645c-.708.379-1.41.58-3.346.58h-7.108c-1.936 0-2.639-.201-3.347-.58a3.95 3.95 0 01-1.642-1.645c-.378-.71-.58-1.413-.58-3.352v-7.12c0-1.94.202-2.643.58-3.352a3.95 3.95 0 011.642-1.645c.708-.379 1.41-.58 3.347-.58h4.462zm6.908-2.053c.384.116.747.338 1.168.759l.188.189c.42.421.642.785.758 1.17a1.98 1.98 0 010 1.163c-.116.385-.337.749-.758 1.17l-6.9 6.911c-.62.622-.827.81-1.078 1.004-.251.193-.496.34-.784.47-.288.131-.553.226-1.392.48l-1.088.332a1.303 1.303 0 01-1.625-1.629l.33-1.09c.255-.84.35-1.104.48-1.393.13-.29.277-.534.47-.785.193-.252.381-.46 1.001-1.081l6.9-6.911c.42-.421.784-.643 1.168-.76a1.97 1.97 0 011.162 0zm-3.204 4.096l-4.797 4.805c-.547.548-.709.723-.852.91-.112.146-.19.276-.265.443-.097.214-.175.44-.4 1.182l-.094.31.31-.095c.74-.225.965-.303 1.179-.4.167-.076.297-.154.442-.266.187-.143.361-.305.909-.853l4.797-4.805-1.23-1.23zm2.546-2.43c-.109.033-.23.11-.443.324l-.874.875 1.228 1.231.875-.876c.213-.213.29-.334.323-.444a.24.24 0 000-.153c-.033-.11-.11-.23-.323-.445l-.189-.188c-.213-.214-.334-.291-.443-.325a.238.238 0 00-.154 0z"
                  fillRule="nonzero"
                />
              </g>
            </svg>
            <div class="table-body-unit-title">
              写文章
            </div>
          </button>
        </div>
        <div class="table-body-unit">
          <button>
            <svg
              width="40"
              height="40"
              viewBox="0 0 40 40"
              class="GlobalWriteV2-navIcon"
              fill="currentColor"
            >
              <g
                fill="#26BFBF"
                fillRule="evenodd"
              >
                <circle
                  cx="20"
                  cy="20"
                  r="20"
                  opacity=".12"
                />
                <path
                  d="M21.987 11.686v2.169h-6.125c-1.43 0-1.863.064-2.297.306-.332.128-.574.383-.74.702-.255.447-.332.893-.332 2.297v7.018c0 1.442.09 1.876.332 2.297.166.345.408.587.74.766.434.23.868.319 2.297.319h7.018c1.43 0 1.863-.077 2.297-.32.345-.165.587-.408.766-.74.216-.408.296-.816.305-2.054l.001-6.316.025.025h2.17v6.074c0 1.914-.217 2.616-.587 3.318a3.92 3.92 0 01-1.634 1.62c-.689.383-1.403.575-3.317.575h-7.018c-1.915 0-2.616-.204-3.318-.575a3.891 3.891 0 01-1.62-1.62c-.384-.702-.575-1.404-.575-3.318v-7.018c0-1.914.204-2.629.574-3.318a3.996 3.996 0 011.62-1.633c.703-.383 1.404-.574 3.318-.574h6.1zm1.889 6.954c1.059 1.06 1.059 2.807 0 3.88l-.039.038a2.719 2.719 0 01-3.879 0l-2.45-2.553a.801.801 0 00-1.123 0l-.05.052c-.32.357-.32.893 0 1.212a.75.75 0 00.726.217c.51-.128 1.047.23 1.149.74a.946.946 0 01-.727 1.148 2.649 2.649 0 01-2.527-.74 2.796 2.796 0 010-3.905l.038-.025c1.098-1.085 2.808-1.085 3.892 0l2.463 2.488a.764.764 0 001.11 0l.038-.025a.855.855 0 000-1.187.876.876 0 00-.74-.217c-.51.128-1.02-.204-1.148-.727-.128-.51.204-1.021.727-1.149l.013-.013a2.703 2.703 0 012.527.766zm4.338-9.315v2.578h2.578v1.722h-2.578v2.59h-1.723v-2.602h-2.59v-1.71h2.59V9.325h1.723z"
                  fillRule="nonzero"
                />
              </g></svg>
            <div class="table-body-unit-title">
              写想法
            </div>
          </button>
        </div>
      </div>
      <div class="creator-table-slider">
        <div class="table-slider-unit table-slider-meta">
          <div class="slider-meta-left">
            <div class="slider-meta-header">
              今日阅读(播放)数
            </div>
            <div class="slider-meta-body">
              0
            </div>
            <div class="slider-meta-footer">
              昨日数据0
            </div>
          </div>
          <div class="slider-meta-right">
            <div class="slider-meta-header">
              今日赞同数
            </div>
            <div class="slider-meta-body">
              0
            </div>
            <div class="slider-meta-footer">
              昨日数据0
            </div>
          </div>
        </div>
        <div class="table-slider-unit table-slider-AD">
          <div class="slider-AD-left">
            <div class="slider-AD-title">
              《创作者》独家分享第二课：内容创作的价值
            </div>
            <div class="slider-AD-meta" />
          </div>
          <div class="slider-AD-right">
            <div class="slider-AD-right-mask">
              <span class="slider-AD-right-mask-round">
                <span class="slider-AD-right-mask-triangle" />
              </span>
            </div>
          </div>
        </div>
      </div>
      <div class="creator-table-footer">
        <button>进入创作中心</button>
      </div>
    </div>
    <div class="user-side user-side-bar">
      <div class="user-side-bar-unit side-bar-live">
        <svg
          class="Zi Zi--Live"
          fill="currentColor"
          viewBox="0 0 24 24"
          width="24"
          height="24"
        ><path d="M13.693 10.354l1.634-7.542c.195-.901-.16-1.083-.798-.39l-9.18 9.97c-.638.693-.377 1.254.582 1.254h5.376l-1.634 7.542c-.195.901.16 1.083.798.39l9.18-9.97c.638-.693.377-1.254-.582-1.254h-5.376z" /></svg>
        <div class="user-side-bar-unit-title side-bar-live-title">
          Live
        </div>
      </div>
      <div class="user-side-bar-unit side-bar-ebook">
        <svg
          class="Zi Zi--Ebook"
          fill="currentColor"
          viewBox="0 0 24 24"
          width="24"
          height="24"
        ><path
          d="M16 17.649V2.931a.921.921 0 0 0-.045-.283.943.943 0 0 0-1.182-.604L4.655 5.235A.932.932 0 0 0 4 6.122v14.947c0 .514.421.931.941.931H19.06c.52 0 .941-.417.941-.93V7.292a.936.936 0 0 0-.941-.931h-.773v12.834a.934.934 0 0 1-.83.924L6.464 21.416c-.02.002 2.94-.958 8.883-2.881a.932.932 0 0 0 .653-.886z"
          fillRule="evenodd"
        /></svg>
        <div class="user-side-bar-unit-title side-bar-ebook-title">
          书店
        </div>
      </div>
      <div class="user-side-bar-unit side-bar-org">
        <svg
          class="Zi Zi--Org"
          fill="currentColor"
          viewBox="0 0 24 24"
          width="24"
          height="24"
        ><path d="M10.786 8.41a8.938 8.938 0 0 0-3.968-2.528c-.305-1.719.814-3.337 2.442-3.741 1.221-.405 2.646.101 3.46 1.011 1.045 1.38.915 3.64.814 4.348-.102 1.315-1.221 3.034-1.323 3.135-.305-.809-.814-1.517-1.425-2.225zm-2.442 2.832c-1.526.202-3.052 1.01-4.171 2.123-1.12-.404-1.934-1.314-2.137-2.427-.316-2.427 1.526-3.64 2.849-3.842 1.628-.371 2.849.505 4.07 1.415 1.146 1.012 2.035 2.63 2.035 2.73-.916-.202-1.832-.1-2.646 0zm4.986.303c.509-.607.931-1.586 1.12-2.225.318-1.039.61-3.134.203-4.651 1.323-1.011 3.154-1.011 4.477.303 1.235 1.146 1.017 2.933.814 3.438-.663 1.581-1.933 2.326-3.256 2.832-1.221.404-3.256.303-3.358.303zm-2.645 1.011c-.51.607-.916 1.416-1.221 2.326-.407 1.314-.643 3.06-.102 4.55-1.323 1.011-3.256 1.011-4.477-.202-1.198-1.124-1.018-2.932-.814-3.438.599-1.605 1.933-2.326 3.256-2.831.916-.304 3.256-.405 3.358-.405zm9.259-1.82c1.017.404 1.933 1.315 2.035 2.427.233 2.57-1.526 3.64-2.849 3.842-1.526 0-2.85-.505-4.07-1.415-1.018-.81-2.035-2.528-2.035-2.63.916.203 1.831.102 2.645 0 1.628-.404 3.053-1.112 4.274-2.224zm-6.716 4.854c1.065 1.08 2.442 2.022 4.07 2.528.306 1.719-.814 3.235-2.442 3.741-1.22.405-2.645-.101-3.46-1.011-1.1-1.481-1.017-3.54-.915-4.247.102-1.315 1.221-3.034 1.323-3.135.305.708.721 1.44 1.424 2.124z" /></svg>
        <div class="user-side-bar-unit-title side-bar-org-title">
          圆桌
        </div>
      </div>
      <div class="user-side-bar-unit side-bar-edit">
        <svg
          class="Zi Zi--Edit"
          fill="currentColor"
          viewBox="0 0 24 24"
          width="24"
          height="24"
        ><path d="M4.076 16.966a4.19 4.19 0 0 1 1.05-1.76l8.568-8.569a.524.524 0 0 1 .741 0l2.928 2.927a.524.524 0 0 1 0 .74l-8.568 8.57c-.49.49-1.096.852-1.761 1.051l-3.528 1.058a.394.394 0 0 1-.49-.488l1.06-3.53zM20.558 4.83c.59.59.59 1.546 0 2.136l-1.693 1.692a.503.503 0 0 1-.712 0l-2.812-2.812a.504.504 0 0 1 0-.712l1.693-1.693a1.51 1.51 0 0 1 2.135 0l1.389 1.389z" /></svg>
        <div class="user-side-bar-unit-title side-bar-edit-title">
          专栏
        </div>
      </div>
      <div class="user-side-bar-unit side-bar-infinity">
        <svg
          class="Zi Zi--Infinity"
          fill="currentColor"
          viewBox="0 0 24 24"
          width="24"
          height="24"
        ><path d="M11.267 10.188h-2.69a.26.26 0 0 0-.261.26v.508c0 .149.117.26.262.26h2.896v1.54H8.578a.26.26 0 0 0-.262.259v.508c0 .15.117.26.262.26h2.896v2.31c0 .139.119.257.265.257h.522a.258.258 0 0 0 .265-.257v-2.31h2.896a.26.26 0 0 0 .262-.26v-.508a.257.257 0 0 0-.262-.26h-2.896v-1.54h2.896a.26.26 0 0 0 .262-.26v-.507a.257.257 0 0 0-.262-.26h-2.69l2.51-2.636a.26.26 0 0 0-.004-.366l-.423-.413a.253.253 0 0 0-.36.01L12 9.418 9.545 6.784a.248.248 0 0 0-.36-.011l-.423.413a.264.264 0 0 0-.004.366l2.509 2.636zM12 19.973c-1.101 0-2.16-.15-3.152-.43-.532.18-5.27 2.177-4.743 1.179.527-.998 1.58-2.746.806-3.25C3.11 15.936 2 13.822 2 11.486 2 6.8 6.477 3 12 3s10 3.8 10 8.487-4.477 8.486-10 8.486z" /></svg>
        <div class="user-side-bar-unit-title side-bar-infinity-title">
          付费咨询
        </div>
      </div>
      <div class="user-side-bar-unit side-bar-knowledgeBase">
        <svg
          class="Zi Zi--KnowledgeBase"
          fill="currentColor"
          viewBox="0 0 24 24"
          width="24"
          height="24"
        ><path d="M21 9.749v9.91c0 .74-.604 1.341-1.35 1.341H4.35C3.604 21 3 20.4 3 19.659V9.319c0-.503.283-.963.733-1.193l4.892-2.5V3.341c0-.74.604-1.341 1.35-1.341.267 0 .527.078.749.225l9.675 6.408c.375.249.601.668.601 1.116zM8.297 8.307L5.372 9.802A.223.223 0 0 0 5.25 10v8.54c0 .124.1.224.225.224h8.586a.223.223 0 1 0 .124-.41l-4.959-3.259a1.339 1.339 0 0 1-.601-1.116V8.506a.224.224 0 0 0-.328-.199z" /></svg>
        <div class="user-side-bar-unit-title side-bar-knowledgeBase-title">
          百科
        </div>
      </div>
    </div>
    <div class="user-side-AD">
      广告广告
    </div>
    <div class="user-side user-side-nav">
      <ul>
        <li>
          <svg
            class="Zi Zi--Star GlobalSideBar-navIcon"
            fill="currentColor"
            viewBox="0 0 24 24"
            width="18"
            height="18"
          ><path
            d="M5.515 19.64l.918-5.355-3.89-3.792c-.926-.902-.639-1.784.64-1.97L8.56 7.74l2.404-4.871c.572-1.16 1.5-1.16 2.072 0L15.44 7.74l5.377.782c1.28.186 1.566 1.068.64 1.97l-3.89 3.793.918 5.354c.219 1.274-.532 1.82-1.676 1.218L12 18.33l-4.808 2.528c-1.145.602-1.896.056-1.677-1.218z"
            fillRule="evenodd"
          /></svg>
          <span class="side-nav-title">我的收藏</span>
          <span class="side-nav-meta">0</span>
        </li>
        <li>
          <svg
            class="Zi Zi--HelpBubble GlobalSideBar-navIcon"
            fill="currentColor"
            viewBox="0 0 24 24"
            width="18"
            height="18"
          ><path
            d="M5.74 4h12.52c.961 0 1.74.775 1.74 1.73V16.27c0 .955-.779 1.73-1.74 1.73h-3.825l-1.658 2.044a1 1 0 0 1-1.554 0l-1.658-2.044H5.74C4.78 18 4 17.224 4 16.27V5.73C4 4.775 4.778 4 5.74 4zM12 16a.976.976 0 0 0 .705-.287.951.951 0 0 0 .295-.712.954.954 0 0 0-.295-.714A.976.976 0 0 0 12 14a.962.962 0 0 0-.705.295A.961.961 0 0 0 11 15c0 .284.098.522.295.713A.975.975 0 0 0 12 16zm1.278-4.924a36.81 36.81 0 0 0 1.023-.975c.19-.193.354-.422.492-.688.138-.266.207-.575.207-.928 0-.448-.12-.864-.363-1.246a2.517 2.517 0 0 0-1.029-.906C13.164 6.111 12.652 6 12.072 6c-.624 0-1.17.133-1.638.399-.468.265-.824.6-1.068 1.005-.244.405-.366.804-.366 1.2 0 .19.077.368.231.531a.747.747 0 0 0 .567.246c.38 0 .638-.234.774-.703.144-.449.32-.788.528-1.019.208-.23.532-.345.972-.345.376 0 .683.114.921.342.238.229.357.51.357.841 0 .17-.039.328-.117.473a1.782 1.782 0 0 1-.288.396c-.114.118-.3.294-.555.526a9.71 9.71 0 0 0-.696.688c-.172.194-.31.418-.414.673a2.391 2.391 0 0 0-.156.906c0 .278.071.488.213.63a.716.716 0 0 0 .525.211c.4 0 .638-.216.714-.648.044-.203.077-.345.099-.426.022-.081.053-.162.093-.243.04-.081.101-.17.183-.268.082-.098.191-.21.327-.34z"
            fillRule="evenodd"
          /></svg>
          <span class="side-nav-title">我关注的问题</span>
          <span class="side-nav-meta">12</span>
        </li>
        <li>
          <svg
            class="Zi Zi--Invite GlobalSideBar-navIcon"
            fill="currentColor"
            viewBox="0 0 24 24"
            width="18"
            height="18"
          ><path
            d="M4 10V8a1 1 0 1 1 2 0v2h2a1 1 0 0 1 0 2H6v2a1 1 0 0 1-2 0v-2H2a1 1 0 0 1 0-2h2zm10.455 2c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm-7 6c0-2.66 4.845-4 7.272-4C17.155 14 22 15.34 22 18v1.375c0 .345-.28.625-.625.625H8.08a.625.625 0 0 1-.625-.625V18z"
            fillRule="evenodd"
          /></svg>
          <span class="side-nav-title">我的邀请</span>
        </li>
        <li>
          <svg
            class="Zi Zi--Balance GlobalSideBar-navIcon"
            fill="currentColor"
            viewBox="0 0 24 24"
            width="18"
            height="18"
          ><path
            d="M19 19.5H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v10.5a2 2 0 0 1-2 2zm0-12a.5.5 0 0 0-.5-.5h-13a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5h3.75c1 0 1 2 2.75 2s1.75-2 2.75-2h3.75a.5.5 0 0 0 .5-.5v-2z"
            fillRule="evenodd"
          /></svg>
          <span class="side-nav-title">我的余额</span>
        </li>
        <li>
          <svg
            class="Zi Zi--Community GlobalSideBar-navIcon"
            fill="currentColor"
            viewBox="0 0 24 24"
            width="18"
            height="18"
          ><path
            d="M5.74 4h12.52c.961 0 1.74.775 1.74 1.73V16.27c0 .955-.779 1.73-1.74 1.73h-3.825l-1.658 2.044a1 1 0 0 1-1.554 0l-1.658-2.044H5.74C4.78 18 4 17.224 4 16.27V5.73C4 4.775 4.778 4 5.74 4zM7 8.98c0 .554.449.996 1.003.996h4.994A.992.992 0 0 0 14 8.981a.997.997 0 0 0-1.003-.995H8.003A.992.992 0 0 0 7 8.98zm0 4c0 .554.446.996.995.996h8.01a.993.993 0 0 0 .995-.995.993.993 0 0 0-.995-.995h-8.01A.993.993 0 0 0 7 12.98z"
            fillRule="evenodd"
          /></svg>
          <span class="side-nav-title">站务中心</span>
        </li>
        <li>
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            class="GlobalSideBar-navIcon"
            fill="currentColor"
          ><path
            d="M9 1.5c2.835 0 5.152 2.195 5.247 4.949l.003.176v.253A2.25 2.25 0 0115.75 9v2.25a2.25 2.25 0 01-1.5 2.122v.257c0 .547-.2 1.073-.557 1.482l-.102.109-1.06 1.06a.75.75 0 01-1.124-.99l.063-.07 1.06-1.061a.75.75 0 00.213-.432l.007-.098V13.5H12a.75.75 0 01-.75-.75V7.5a.75.75 0 01.75-.75h.75v-.125C12.75 4.628 11.076 3 9 3 6.98 3 5.34 4.541 5.254 6.464l-.004.286H6a.75.75 0 01.743.648l.007.102v5.25a.75.75 0 01-.648.743L6 13.5H4.5a2.25 2.25 0 01-2.245-2.096l-.005-.154V9c0-.98.626-1.814 1.5-2.122v-.253C3.75 3.79 6.105 1.5 9 1.5z"
            fillRule="evenodd"
          /></svg>
          <span class="side-nav-title">帮助中心</span>
        </li>
        <li>
          <svg
            class="Zi Zi--Copyright GlobalSideBar-navIcon"
            fill="currentColor"
            viewBox="0 0 24 24"
            width="18"
            height="18"
          ><path
            d="M16.517 15.815a5.871 5.871 0 0 1-4.481 2.078 5.865 5.865 0 0 1-5.859-5.857 5.865 5.865 0 0 1 5.859-5.859c1.63 0 3.204.7 4.319 1.919.085.093.24.432.209.797a1.086 1.086 0 0 1-.436.779c-.248.193-.516.29-.797.29-.402 0-.7-.198-.814-.314A3.473 3.473 0 0 0 12 8.575a3.464 3.464 0 0 0-3.46 3.461 3.464 3.464 0 0 0 3.46 3.46 3.63 3.63 0 0 0 2.654-1.181c.136-.152.458-.306.806-.306.274 0 .542.095.773.274.35.269.45.588.473.809.032.308-.072.585-.188.723m4.686-7.699C20.67 6.883 19.96 5.82 19.07 4.929c-.891-.89-1.954-1.601-3.188-2.133A9.728 9.728 0 0 0 12 2a9.733 9.733 0 0 0-3.883.796c-1.234.532-2.297 1.243-3.186 2.133-.891.891-1.602 1.954-2.134 3.187A9.713 9.713 0 0 0 2 12a9.752 9.752 0 0 0 .797 3.883c.531 1.233 1.242 2.296 2.134 3.186.89.891 1.953 1.602 3.186 2.134A9.725 9.725 0 0 0 12 22a9.72 9.72 0 0 0 3.883-.797c1.233-.532 2.296-1.243 3.188-2.134.89-.89 1.601-1.953 2.132-3.186A9.73 9.73 0 0 0 22 12a9.69 9.69 0 0 0-.797-3.884"
            fillRule="evenodd"
          /></svg>
          <span class="side-nav-title">版权服务中心</span>
        </li>
      </ul>
    </div>
    <div class="user-side-AD">
      广告广告
    </div>
    <div class="user-side-footer">
      <p>
        <router-link to="">
          刘看山
        </router-link>·
        <router-link to="">
          知乎指南
        </router-link>·
        <router-link to="">
          知乎协议
        </router-link>·
        <router-link to="">
          知乎隐私保护指引
        </router-link>
      </p>
      <p>
        <router-link to="">
          应用
        </router-link>·
        <router-link to="">
          工作
        </router-link>·
        <span>申请开通知乎机构号</span>
      </p>
      <p>
        <router-link to="">
          侵权举报
        </router-link>·
        <router-link to="">
          网上有害信息举报专区
        </router-link>
      </p>
      <p>
        <router-link to="">
          京 ICP 证 110745 号
        </router-link>
      </p>
      <p>
        <router-link to="">
          京 ICP 备 13052560 号 - 1
        </router-link>
      </p>
      <p>
        <img
          src="https://pic3.zhimg.com/80/v2-d0289dc0a46fc5b15b3363ffa78cf6c7.png"
          alt=""
        >
        <router-link to="">
          京公网安备 11010802020088 号
        </router-link>
      </p>
      <p>互联网药品信息服务资格证书</p>
      <p>（京）- 非经营性 - 2017 - 0067违法和不良信息举报：010-82716601</p>
      <p>
        <router-link to="">
          儿童色情信息举报专区
        </router-link>
      </p>
      <p>
        <router-link to="">
          信息安全漏洞反馈专区
        </router-link>
      </p>
      <p>
        <router-link to="">
          内容从业人员违法违规行为举报：zh-ygwfwgjb@zhihu.com
        </router-link>
      </p>
      <p>
        <router-link to="">
          证照中心
        </router-link>·
        <router-link to="">
          Investor Relations
        </router-link>
      </p>
      <p>
        <router-link to="">
          联系我们
        </router-link> © 2021 知乎
      </p>
    </div>
  </div>
</template>

<script lang="ts">
export default {

}
</script>

<style>
.bd-r{
  width: 296px;
}
.user-side{
  display: block;
  box-shadow: 0 1px 1px #e1e1e1,0 2px 1px #f5f5f5;
  margin-bottom: 10px;
  background-color: white;
}
.user-creator-table{
  padding: 15px;
}
.creator-table-header{
  display: flex;
  justify-content: space-between;
}
.Zi--Creator{

}
.table-header-level{
  color: #0066ff;
}
.table-header-right{
  font-size: 12px;
  color: #76839b;
}
.creator-table-body{
  display: flex;
  justify-content: space-between;
  margin-top: 10px;
}
.table-body-unit button{
  border: none;
  background-color: transparent;
}
.creator-table-slider{
  overflow: hidden;
  margin: 15px 0;
}
.table-slider-unit{
  background-color: rgba(0,102,255,.1);
  font-size: 12px;
  color: #76839b;
}
.table-slider-meta{
  height: 80px;
  display: flex;
  justify-content: space-between;
  padding: 10px;
}
.slider-meta-left{
  display: flex;
  flex: 1;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  border-right: 1px solid rgba(18,18,18,.1);
}
.slider-meta-right{
  display: flex;
  flex: 1;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
}
.slider-meta-body{
  font-weight: 600;
  color: #000000;
  margin: 6px 0;
}
.table-slider-AD{
  display: flex;
  justify-content: space-between;
  flex-wrap: nowrap;
}
.slider-AD-left{
  flex: 1;
}
.slider-AD-right{
  position: relative;
  width: 60px;
  height: 60px;
  border-radius: 4px;
}
.slider-AD-right-mask{
  position: absolute;
  width: 60px;
  height: 60px;
  left: 0;
  top: 0;
  background-color:rgba(0,102,255,.1);
}
.slider-AD-right-mask-round{
  position: absolute;
  display: block;
  width: 30px;
  height: 30px;
  background-color:white;
  z-index: 10;
  border-radius: 999px;
  transform: translate(50%,50%);
}
.slider-AD-right-mask-triangle{
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  z-index: 15;
  transform: translate(50%,50%);
  border-width: 8px 10px 8px 12px;
  border-style: solid;
  border-color: transparent transparent transparent black;
}
.creator-table-footer button{
  width: 100%;
  height: 40px;
  border: 1px solid #0066ff;
  background-color: #fff;
  color: #0066ff;
  cursor: pointer;
}
.user-side-footer>p{
  display: flex;
  justify-content: flex-start;
}

.user-creator-center{}
.user-side-bar{
  display: flex;
  justify-content: flex-start;
  flex-wrap: wrap;
}
.user-side-bar-unit{
  width: 98px;
  height: 80px;
  display:flex;
  flex-direction: column;
  justify-content:center;
  align-items:center;
  cursor: pointer;
}
.Zi--Live{
  color: rgb(255, 207, 0);
}
.side-bar-live:hover .side-bar-live-title{
  color: rgb(255, 207, 0);
}
.Zi--Ebook{
  color: rgb(67, 212, 128);
}
.side-bar-ebook:hover .side-bar-ebook-title{
  color: rgb(67, 212, 128);
}
.Zi--Org{
  color: rgb(0, 102, 255);
}
.side-bar-org:hover .side-bar-org-title{
  color: rgb(0, 102, 255);
}
.Zi--Edit{
  color: rgb(15, 136, 235);
}
.side-bar-edit:hover .side-bar-edit-title{
  color: rgb(15, 136, 235);
}
.Zi--Infinity{
  color: rgb(84, 120, 240);
}
.side-bar-infinity:hover .side-bar-infinity-title{
  color: rgb(84, 120, 240);
}
.Zi--KnowledgeBase{
  color: rgb(88, 104, 209);
}
.side-bar-knowledgeBase:hover .side-bar-knowledgeBase-title{
  color: rgb(88, 104, 209);
}
.user-side-bar-unit-title{
  margin-top: 10px;
  color: #76839b;
}
.user-side-AD{}
.user-side-nav{
  color: #76839b;
  padding: 10px 0;
}
.user-side-nav ul li{
  display: flex;
  justify-content: space-between;
  height: 40px;
  font-size: 13px;
  align-items: center;
  padding: 0 20px;
  cursor: pointer;
}
.user-side-nav ul li:hover{
  background-color: rgba(18,18,18,.1);
}
.side-nav-title{
  flex: 1 1;
}
.user-side-footer{
  font-size: 13px;
  color: #76839b;
}
.user-side-footer a{
  font-size: 13px;
  color: #76839b;
}
.user-side-footer a:hover{
  color: #175199;
}
</style>
