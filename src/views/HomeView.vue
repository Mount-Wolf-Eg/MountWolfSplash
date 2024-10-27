<template>
  <div class="splash-screen">
    <div class="mw-box row">
      <div class="mw-software col-6">
        <div class="image d-flex align-items-end justify-content-center w-100">
          <img
            src="/src/assets/splash/Component 12.png"
            style="width: 18.9rem; height: 19.2rem"
            alt="mount wolf developer"
          />
        </div>
        <button
          @click="emits('closeModal')"
          style="justify-self: flex-end !important"
        >
          <a target="_blank" href="sw.mount-wolf.com"> Visit Website </a>
          <svg
            style="width: 0.8rem; height: 0.8rem"
            viewBox="0 0 8 8"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M5.73975 3.58334L3.40641 1.25001L4.00016 0.666678L7.3335 4.00001L4.00016 7.33334L3.40641 6.75001L5.73975 4.41668L0.666829 4.41668L0.666829 3.58334L5.73975 3.58334Z"
              fill="#FEF7FF"
            />
          </svg>
        </button>
      </div>
      <div class="mw-marketing col-6">
        <div class="image d-flex align-items-end justify-content-center w-100">
          <img
            style="width: 27.8rem; height: 8.6rem"
            src="/src/assets/splash/Component 13.png"
            alt="mount wolf marketing"
          />
        </div>
        <button
          @click="emits('closeModal')"
          style="justify-self: flex-end !important"
        >
          <a target="_blank" href="dig.mount-wolf.com"> Visit Website </a>
          <svg
            style="width: 0.8rem; height: 0.8rem"
            viewBox="0 0 8 8"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M5.73975 3.58334L3.40641 1.25001L4.00016 0.666678L7.3335 4.00001L4.00016 7.33334L3.40641 6.75001L5.73975 4.41668L0.666829 4.41668L0.666829 3.58334L5.73975 3.58334Z"
              fill="#FEF7FF"
            />
          </svg>
        </button>
      </div>
    </div>
  </div>
</template>

<script setup>
const emits = defineEmits(["closeModal"]);
</script>

<style lang="scss" scoped></style>
