<template>
  <div
    class="SectionProjects"
    style="border: 2px solid red;"
  >
    <AppLayout>
      <template #center>
        Project section here
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
