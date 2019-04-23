<template>
  <section
    class="AppLayout"
  >
    <div
      class="cell cell-left"
    >
      <slot name="left" />
    </div>

    <div
      class="cell cell-center"
    >
      <slot name="center" />
    </div>

    <div
      class="cell cell-right"
    >
      <slot name="right" />
    </div>
  </section>
</template>

<style lang="scss" scoped>
section {
  display: flex;
}

.cell {
  flex: 1;
  display: flex;
  flex-direction: column;

  &-center {
    flex: 8;
  }
}
</style>
