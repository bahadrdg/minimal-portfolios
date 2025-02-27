<script setup></script>

<template>
  <div class="flex pt-[145px] max-lg:flex-col">
    <div class="w-1/3 max-lg:w-full">
      <h1
        class="text-[32px] font-handlee font-bold bg-[#FFC9F0] w-fit  max-lg:mt-[50px] max-sm:mt-[30px]"
      >
        Contact Here
      </h1>
      <img
        src="/images/arrow3.svg"
        alt="arrow"
        class="pl-10 pt-2 max-w-full h-auto"
      />
      <p class="text-[24px] max-sm:text-[20px] font-inter">
        Have a project idea? just say me Hi.
      </p>
    </div>
    <div class="w-full md:w-2/3">
      <div class="flex flex-col gap-4 md:gap-6">
        <div class="flex flex-col md:flex-row gap-2 md:gap-0">
          <label for="" class="text-[18px] md:text-[24px] font-handlee font-bold bg-[#FFC9F0] md:w-48 w-full flex-shrink-0 border-l-2 border-black pl-2 whitespace-nowrap">Name</label>
          <input type="text" class="border-b-2 border-black w-full md:pl-4" placeholder="Zainab Nisa">
        </div>
        
        <div class="flex flex-col md:flex-row gap-2 md:gap-0">
          <label for="" class="text-[18px] md:text-[24px] font-handlee font-bold bg-[#FFE68C] md:w-48 w-full flex-shrink-0 border-l-2 border-black pl-2 whitespace-nowrap">Your Email</label>
          <input type="email" class="border-b-2 border-black w-full md:pl-4" placeholder="zainab123@gmail.com">
        </div>
        
        <div class="flex flex-col md:flex-row gap-2 md:gap-0">
          <label for="" class="text-[18px] md:text-[24px] font-handlee font-bold bg-[#9DDCFF] md:w-48 w-full flex-shrink-0 border-l-2 border-black pl-2 whitespace-nowrap">About Project</label>
          <input type="text" class="border-b-2 border-black w-full md:pl-4" placeholder=" I want to discuss you about .......">
        </div>
        
        <button class="text-white text-[18px] md:text-[24px] font-inter p-3 md:p-5 bg-black w-fit ml-auto">Send Here</button>
      </div>
    </div>
  </div>
</template>
