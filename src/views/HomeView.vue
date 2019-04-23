<template>
  <div class="HomeView">
    <SectionPipa />
    <SectionProjects />
    <SectionCounters />
  </div>
</template>

<script>
import SectionPipa from '@/components/SectionPipa';
import SectionProjects from '@/components/SectionProjects';
import SectionCounters from '@/components/SectionCounters';

export default {
  components: {
    SectionPipa,
    SectionProjects,
    SectionCounters,
  }
}
</script>
