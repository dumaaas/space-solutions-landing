<template>
  <div class="w-full pt-[100px] relative">
    <div class="container mx-auto px-[20px]">
      <h3
        class="mb-[46px] text-center font-semibold font-tertiary md:text-[48px] text-[36px] leading-[52px] md:leading-[60xp] bg-clip-text text-transparent bg-gradient-to-r from-[#6F95FE] to-[#AA6DFE]"
      >
        Blog
      </h3>
      <div class="flex lg:flex-row flex-col gap-[31px] items-center">
        <div
          class="cursor-pointer rounded-[40px] flex-[25%] border-y-[1.5px] border-r-[1.5px] border-purple-900 bg-gradient-to-r from-gray-700/25 via-gray-800-500/25 to-gray-900/25 shadow-xl bg-opacity-40"
        >
          <div
            class="h-[231px] rounded-tl-[40px] rounded-tr-[40px] w-full bg-no-repeat bg-center bg-cover"
            :style="`background-image: url(${require('@/assets/blog1.png')})`"
          ></div>
          <div class="flex flex-col gap-[9px] p-[29px]">
            <span
              class="text-[#6F95FE] font-tertiary font-semibold text-[14px] leading-[17.5px]"
            >
              28.3.2023
            </span>
            <p
              class="font-semibold font-primary md:text-[24px] md:leading-[29px] text-[20px] leading-[26px] text-white"
            >
              Lorem ipsum dolor sit amet, consectetur adipiscing elit
            </p>
          </div>
        </div>
        <div
          class="cursor-pointer rounded-[40px] flex-[25%] border-y-[1.5px] border-r-[1.5px] border-purple-900 bg-gradient-to-r from-gray-700/25 via-gray-800-500/25 to-gray-900/25 shadow-xl bg-opacity-40"
        >
          <div
            class="lg:h-[276px] h-[231px] rounded-tl-[40px] rounded-tr-[40px] w-full bg-no-repeat bg-center bg-cover"
            :style="`background-image: url(${require('@/assets/blog2.png')})`"
          ></div>
          <div class="flex flex-col gap-[9px] p-[29px] lg:p-[36px]">
            <span
              class="text-[#6F95FE] font-tertiary font-semibold text-[14px] leading-[17.5px]"
            >
              28.3.2023
            </span>
            <p
              class="font-semibold font-primary md:text-[24px] md:leading-[29px] text-[20px] leading-[26px] text-white"
            >
              Lorem ipsum dolor sit amet, consectetur adipiscing elit
            </p>
          </div>
        </div>
        <div
          class="cursor-pointer rounded-[40px] flex-[25%] border-y-[1.5px] border-r-[1.5px] border-purple-900 bg-gradient-to-r from-gray-700/25 via-gray-800-500/25 to-gray-900/25 shadow-xl bg-opacity-40"
        >
          <div
            class="h-[231px] rounded-tl-[40px] rounded-tr-[40px] w-full bg-no-repeat bg-center bg-cover"
            :style="`background-image: url(${require('@/assets/blog3.png')})`"
          ></div>
          <div class="flex flex-col gap-[9px] p-[29px]">
            <span
              class="text-[#6F95FE] font-tertiary font-semibold text-[14px] leading-[17.5px]"
            >
              28.3.2023
            </span>
            <p
              class="font-semibold font-primary md:text-[24px] md:leading-[29px] text-[20px] leading-[26px] text-white"
            >
              Lorem ipsum dolor sit amet, consectetur adipiscing elit
            </p>
          </div>
        </div>
      </div>

      <div
        class="relative mx-auto mt-[40px] px-[2px] py-[2px] md:w-[244px] w-[200px]"
      >
        <div
          class="absolute inset-0 bg-gradient-to-r from-[#5E16F9] to-[#7958EF] opacity-90 rounded-[70px]"
        ></div>

        <button
          class="block text-center relative py-[12px] md:py-[14px] px-[18.5px] rounded-[70px] w-full md:text-[20px] md:leading-[24.4px] text-[16px] leading-[24px] font-semibold font-primary bg-[#131429] text-white"
        >
          Zobraziť viac
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
</style>