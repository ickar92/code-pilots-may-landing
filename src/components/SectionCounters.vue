<template>
  <div
    class="SectionCounters"
    style="border: 2px solid blue;"
  >
    <AppLayout>
      <template #left>
        <div class="content content-left" />
      </template>

      <template #center>
        <div class="content content-center">
          Counters section here
        </div>
      </template>
    </AppLayout>
  </div>
</template>

<script>
import AppLayout from '@/components/AppLayout.vue';

export default {
  components: {
    AppLayout,
  }
}
</script>

<style lang="scss" scoped>
.content {
  background-color: #0c81fd;
  height: 200px;
}
</style>
