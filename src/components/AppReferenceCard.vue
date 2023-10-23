<template>
  <div class="flex flex-col gap-[20px] items-center justify-center">
    <!-- <div
      class="w-[108px] h-[108px] border-[4px] border-purple-500 rounded-full"
    ></div> -->
    <div class="outer_circle ">
      <div
        class="inner_circle shadow-xl"
        style="box-shadow: 0 0 40px 0 rgba(96, 21, 255, 0.56)"
      ></div>
    </div>
    <h4
      class="pt-[5px] text-white font-primary font-semibold text-[28px] leading-[34px] text-center"
    >
      {{ title }}
    </h4>
    <p
      class="max-w-[347px] text-center font-primary text-[16px] leading-[19.5px] text-[#C9D4F0]"
    >
      {{ description }}
    </p>
  </div>
</template>

<script>
export default {
  props: ["title", "description"],
};
</script>

<style>
.outer_circle {
  position: relative;
  width: 108px;
  height: 108px;
  border-radius: 50%;
  background: #100f25;
}

.inner_circle {
  background-image: linear-gradient(
    to bottom,
    rgb(93, 24, 242) 100%,
    rgb(121, 88, 239) 3%
  );
  content: "";
  position: absolute;
  top: -4px;
  bottom: -4px;
  right: -4px;
  left: -4px;
  z-index: -1;
  border-radius: inherit;
}
</style>