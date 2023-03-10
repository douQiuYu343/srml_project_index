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
        <h1 class="text-4xl md:text-[50px] font-semibold">赛 睿 米 林</h1>
        <p class="text-xl mt-2 md:mt-4 tracking-wide">战 斗 - N P C - 辎 重</p>
      </div>
      <p class="mt-4 text-sm md:w-[52%] tracking-wide leading-7">test tes1 test tes1test tes1 test tes1test tes1test tes1 test tes1test tes1test tes1test tes1 test tes1test tes1test tes1test tes1test tes1test tes1test tes1test tes1 test tes1test tes1 test tes1test tes1test tes1 test tes1test tes1test tes1test tes1 test tes1test tes1test tes1test tes1test tes1test tes1test tes1 </p>
      <div class="space-x-3 mt-6 md:mt-4">
        <a href="#"> <i
            class="fa-brands fa-facebook-f bg-blue-600 hover:text-blue-500 hover:bg-white rounded-full px-3 py-[11px] w-9 h-9 text-center "></i>
        </a>
        <a href="#"> <i
            class="fa-brands fa-twitter bg-blue-600 hover:text-red-500 hover:bg-white rounded-full px-[10px] py-[11px] w-9 h-9 text-center"></i>
        </a>
        <a href="#"> <i
            class="fa-brands fa-linkedin bg-blue-600 hover:text-yellow-500 hover:bg-white rounded-full px-3 py-[11px] w-9 h-9 text-center"></i>
        </a>
        <a href="#"> <i
            class="fa-brands fa-chrome bg-blue-600 hover:text-indigo-600 hover:bg-white rounded-full px-[10px] py-[11px] w-9 h-9 text-center"></i>
        </a>

      </div>
      <div class="flex mt-10 space-x-5">
        <button class="bg-white text-blue-600 px-6 py-2 hover:brightness-105 font-semibold">Read More</button>
        <button
            class="bg-blue-900 text-white border-2 border-white px-6 py-2 hover:brightness-105 font-semibold">Contact
          Me</button>

      </div>
    </div>
  </div>
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
