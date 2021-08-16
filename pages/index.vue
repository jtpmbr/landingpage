<template>
  <div class="bg-gradient-to-b from-gray-500 to-gray-700 w-full h-screen">
    <div
      class="
        fixed
        bottom-0
        w-full
        bg-white
        h-30
        rounded-t-2xl
        justify-center
        items-center
        shadow-lg
        p-2
        flex flex-col
      "
    >
      <p class="text-lg">สั่งซื้อสินค้าผ่านไลน์</p>
      <button class="p-4 mt-5 bg-green-300 rounded-2xl text-green-50">
        @บริจาคโลงเย็นออนไลน์
      </button>
    </div>
    <video class="w-full" autoplay muted controls>
      <source
        src="https://res.cloudinary.com/dp1rjju7c/video/upload/v1629105275/Comp_1_cqhele.mp4"
        type="video/mp4"
      />
      Your browser does not support the video tag.
    </video>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
  mounted() {
    console.log()
  },
  computed: {},
  methods: {},
}
</script>
