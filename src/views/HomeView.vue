<template>
  <div class="HomeView">
    <SectionHeader />
    <SectionProjects />
    <SectionCounters />
  </div>
</template>

<script>
import SectionHeader from '@/components/SectionHeader';
import SectionProjects from '@/components/SectionProjects';
import SectionCounters from '@/components/SectionCounters';

export default {
  components: {
    SectionHeader,
    SectionProjects,
    SectionCounters,
  }
}
</script>
