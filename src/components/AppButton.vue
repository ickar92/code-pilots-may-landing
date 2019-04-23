<template>
  <button
    class="AppButton"
    :class="{ accent }"
  >
    <slot />
  </button>
</template>

<script>
export default {
    props: {
        accent: {
            type: Boolean
        }
    }
}
</script>

<style>
.AppButton {
    background-color: #ebebeb;
    text-transform: uppercase;
    padding: 20px;
    border: none;
    cursor: pointer;
}

.AppButton.accent {
    background-color: #0c81fd;
    color: white;
}
</style>
