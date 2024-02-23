<script setup>

</script>

<template>
  <container class="bg-slate-700 w-screen h-screen flex">
    <nav class="bg-red-500 w-[366px] h-full flex items-center flex-col">
      <logo class="bg-green-300 w-[100px] h-[100px] mt-[80px]"></logo>
      <nav-btn-all class="flex flex-col mt-[100px] w-[200px]">
        <nav-btn-1 class="bg-green-300 w-[200px] h-[50px] mb-[20px] text-center leading-[50px]">11111</nav-btn-1>
        <nav-btn-1 class="bg-green-300 w-[200px] h-[50px] mb-[20px] text-center leading-[50px]">22222</nav-btn-1>
        <nav-btn-1 class="bg-green-300 w-[200px] h-[50px] mb-[20px] text-center leading-[50px]">33333</nav-btn-1>
      </nav-btn-all>

    </nav>
    <contentall class="bg-amber-600 w-full h-full flex-1 flex justify-center items-center">
      <content class="bg-green-300 w-[957px] h-[570px]  max-w-screen-lg flex">
        <content-1 class="w-[calc(100%/3-(20px/3))] bg-amber-200 "></content-1>
        <content-1 class="w-[calc(100%/3-(20px/3))] bg-amber-200 ml-[10px] mr-[10px] "></content-1>
        <content-1 class="w-[calc(100%/3-(20px/3))] bg-amber-200 "></content-1>
      </content>
    </contentall>
  </container>
  <!-- <main></main> -->
  <!-- <div class="container">
        <div class="nav">
    漢堡menu的按鈕選擇器
        <input type="checkbox" id="ham-menu-switch" hidden>
    漢堡menu的按鈕本體
        <label for="ham-menu-switch" class="ham-menu-btn">
        <div id="line-1" class="line"></div>
        <div id="line-2" class="line"></div>
        <div id="line-3" class="line"></div>
        </label>

        <div class="logo"></div>
        <div class="nav-btn-all">
            <a href="https://www.youtube.com/watch?v=GqNB_mZGoxY&ab_channel=EricDuan" target="_blank" class="nav-btn nav-btn-1">山道猴子的一生(上集)</a>
            <a href="https://www.youtube.com/watch?v=xMbOOc7iH1I&ab_channel=EricDuan" target="_blank" class="nav-btn nav-btn-2">山道猴子的一生(下集)</a>
            <a href="https://www.youtube.com/"  target="_blank" class="nav-btn  nav-btn-3">YOUTUBE</a>
            </div>
        </div>
        <div class="content-all">
            <div class="content">
                <div class="img img-1"></div>
                <div class="img img-2"></div>
                <div class="img img-3"></div>
        </div>
        </div>
    </div> -->

    

</template>
