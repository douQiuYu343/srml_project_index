<template>
  <div class="flex justify-center bg-blue-900 text-white ">
    <nav class="self-center w-full max-w-7xl  ">
      <div class="flex md:flex-row flex-col  justify-between items-center md:items-start">
        <h1 class=" py-4 text-2xl font-sans font-bold px-10">SRML</h1>
        <ul class="flex justify-center my-4  items-center text-sm md:text-[18px] font-bold  md:px-10">
          <li
              class="hover:underline  underline-offset-4 decoration-2 decoration-white py-2 rounded-lg px-2 md:px-5">
            <a href="#">主页</a>
          </li>
          <li
              class="hover:underline underline-offset-4 decoration-2 decoration-white py-2 rounded-lg px-2 md:px-5">
            <a href="#">兵种树</a>
          </li>
          <li
              class="hover:underline underline-offset-4 decoration-2 decoration-white py-2 rounded-lg px-2 md:px-5">
            <a href="#">下载</a>
          </li>
          <li
              class="hover:underline underline-offset-4 decoration-2 decoration-white py-2 rounded-lg px-2 md:px-5">
            <a href="#">关于</a>
          </li>

        </ul>

      </div>
    </nav>
  </div>

  <div class="flex justify-center  bg-blue-900 p-5 md:p-16 lg:p-28">
    <div class="flex flex-col justify-center  max-w-7xl  text-white">
      <h1 class="text-base font-medium tracking-wider ">欢迎来到 SRML 主页</h1>
      <span class="underline underline-offset-2 text-white -mt-3"> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
                                                    &nbsp; </span>
      <div class="flex flex-col text-white mt-5">
        <h1 class="text-4xl md:text-[50px] font-semibold"> 赛 瑞 米 林 </h1>
        <p class="text-xl mt-2 md:mt-4 tracking-wide">战 斗 - N P C - 辎 重</p>
      </div>
      <p class="mt-4 text-sm md:w-[52%] tracking-wide leading-7">随 着 伽 兰 帝 国 最 后 一 批 顽 固 分 子 的 消 失 ，冰 雪 大 陆 终 于 完 全 纳 入 了 净 空 的 世 界 。次 日 凌 晨 ，繁 星 闪 烁 ，海 面 上 升 起 了 轻 柔 的 薄 纱 ，路 伦 斯 的 人 们 还 沉 溺 于 甘 甜 的 睡 梦 中 。在 睡 梦 中 ，在 繁 星 下 ，一 支 庞 大 的 舰 队 悄 然 而 至 ，警 报 声 响 彻 整 个 叶 里 库 特 岛 的 北 岸 。一 片 朦 胧 中 ， 你 看 到 一 个 疲 倦 的 战 士 拖 着 刀 奔 向 了 前 线 。 你 明 白 ， 他 是 在 保 护 他 的 祖 国 ， 还 有 他 的 ……</p>
      <div class="flex mt-10 space-x-5">
        <button class="bg-white text-blue-600 px-6 py-2 hover:brightness-105 font-semibold">前往官方博客</button>
        <button class="bg-blue-900 text-white border-2 border-white px-6 py-2 hover:brightness-105 font-semibold">转中文站论坛</button>
      </div>
    </div>
  </div>

  <section class="text-gray-600 body-font">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-wrap -m-4">
        <div class="lg:w-1/3 lg:mb-0 mb-6 p-4">
          <div class="h-full text-center">
            <img alt="testimonial" class="w-20 h-20 mb-8 object-cover object-center rounded-full inline-block border-2 border-gray-200 bg-gray-100" src="https://dummyimage.com/302x302">
            <p class="leading-relaxed">test test test test test test test test test</p>
            <span class="inline-block h-1 w-10 rounded bg-indigo-500 mt-6 mb-4"></span>
            <h2 class="text-gray-900 font-medium title-font tracking-wider text-sm">隶属于</h2>
            <p class="text-gray-500">博主A</p>
          </div>
        </div>
        <div class="lg:w-1/3 lg:mb-0 mb-6 p-4">
          <div class="h-full text-center">
            <img alt="testimonial" class="w-20 h-20 mb-8 object-cover object-center rounded-full inline-block border-2 border-gray-200 bg-gray-100" src="https://dummyimage.com/300x300">
            <p class="leading-relaxed">test test test test test test test test test</p>
            <span class="inline-block h-1 w-10 rounded bg-indigo-500 mt-6 mb-4"></span>
            <h2 class="text-gray-900 font-medium title-font tracking-wider text-sm">隶属于</h2>
            <p class="text-gray-500">博主B</p>
          </div>
        </div>
        <div class="lg:w-1/3 lg:mb-0 p-4">
          <div class="h-full text-center">
            <img alt="testimonial" class="w-20 h-20 mb-8 object-cover object-center rounded-full inline-block border-2 border-gray-200 bg-gray-100" src="https://dummyimage.com/305x305">
            <p class="leading-relaxed">test test test test test test test test test</p>
            <span class="inline-block h-1 w-10 rounded bg-indigo-500 mt-6 mb-4"></span>
            <h2 class="text-gray-900 font-medium title-font tracking-wider text-sm">隶属于</h2>
            <p class="text-gray-500">作者</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="text-gray-600 body-font">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-col text-center w-full mb-20">
        <h1 class="sm:text-3xl text-2xl font-medium title-font mb-4 text-gray-900">各 项 数 据</h1>
        <p class="lg:w-2/3 mx-auto leading-relaxed text-base">感谢各位对赛瑞米林的支持，为了让大家了解mod的基本传播情况，我做了个简单的数据显示，再一次感谢您们！！！</p>
      </div>
      <div class="flex flex-wrap -m-4 text-center">
        <div class="p-4 md:w-1/4 sm:w-1/2 w-full">
          <div class="border-2 border-gray-200 px-4 py-6 rounded-lg">
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="text-indigo-500 w-12 h-12 mb-3 inline-block" viewBox="0 0 24 24">
              <path d="M8 17l4 4 4-4m-4-5v9"></path>
              <path d="M20.88 18.09A5 5 0 0018 9h-1.26A8 8 0 103 16.29"></path>
            </svg>
            <h2 class="title-font font-medium text-3xl text-gray-900">2.7K</h2>
            <p class="leading-relaxed">Downloads</p>
          </div>
        </div>
        <div class="p-4 md:w-1/4 sm:w-1/2 w-full">
          <div class="border-2 border-gray-200 px-4 py-6 rounded-lg">
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="text-indigo-500 w-12 h-12 mb-3 inline-block" viewBox="0 0 24 24">
              <path d="M17 21v-2a4 4 0 00-4-4H5a4 4 0 00-4 4v2"></path>
              <circle cx="9" cy="7" r="4"></circle>
              <path d="M23 21v-2a4 4 0 00-3-3.87m-4-12a4 4 0 010 7.75"></path>
            </svg>
            <h2 class="title-font font-medium text-3xl text-gray-900">1.3K</h2>
            <p class="leading-relaxed">Users</p>
          </div>
        </div>
        <div class="p-4 md:w-1/4 sm:w-1/2 w-full">
          <div class="border-2 border-gray-200 px-4 py-6 rounded-lg">
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="text-indigo-500 w-12 h-12 mb-3 inline-block" viewBox="0 0 24 24">
              <path d="M3 18v-6a9 9 0 0118 0v6"></path>
              <path d="M21 19a2 2 0 01-2 2h-1a2 2 0 01-2-2v-3a2 2 0 012-2h3zM3 19a2 2 0 002 2h1a2 2 0 002-2v-3a2 2 0 00-2-2H3z"></path>
            </svg>
            <h2 class="title-font font-medium text-3xl text-gray-900">74</h2>
            <p class="leading-relaxed">Files</p>
          </div>
        </div>
        <div class="p-4 md:w-1/4 sm:w-1/2 w-full">
          <div class="border-2 border-gray-200 px-4 py-6 rounded-lg">
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="text-indigo-500 w-12 h-12 mb-3 inline-block" viewBox="0 0 24 24">
              <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path>
            </svg>
            <h2 class="title-font font-medium text-3xl text-gray-900">46</h2>
            <p class="leading-relaxed">Places</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="text-gray-600 body-font">
    <div class="container px-5 py-8 mx-auto flex items-center sm:flex-row flex-col">
      <a class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
          <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
        </svg>
        <span class="ml-3 text-xl">SRML</span>
      </a>
      <p class="text-sm text-gray-500 sm:ml-4 sm:pl-4 sm:border-l-2 sm:border-gray-200 sm:py-2 sm:mt-0 mt-4">© 2023 赛瑞米林 —
        <a href="#" class="text-gray-600 ml-1" rel="noopener noreferrer" target="_blank">@SRML官方博客区</a>
      </p>
      <span class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start">
      <a class="text-gray-500">
        <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
          <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"></path>
        </svg>
      </a>
      <a class="ml-3 text-gray-500">
        <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
          <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"></path>
        </svg>
      </a>
      <a class="ml-3 text-gray-500">
        <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
          <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
          <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
        </svg>
      </a>
      <a class="ml-3 text-gray-500">
        <svg fill="currentColor" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="0" class="w-5 h-5" viewBox="0 0 24 24">
          <path stroke="none" d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"></path>
          <circle cx="4" cy="4" r="2" stroke="none"></circle>
        </svg>
      </a>
    </span>
    </div>
  </footer>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HelloWorld from '@/components/HelloWorld.vue';

@Options({
  components: {
    HelloWorld,
  },
})

export default class HomeView extends Vue {}
</script>
