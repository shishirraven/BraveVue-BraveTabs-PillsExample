<template>
  <div>
    <div class="flex justify-center pb-5">
      <BraveThemeSwitcher />
    </div>
    <main class="container mx-auto lg:px-32 mt-5">
      <HorizontalPillTabs />
    </main>
  </div>
</template>
<script>
import HorizontalPillTabs from './components/HorizontalPillTabs.vue';
import BraveThemeSwitcher from './components/BraveThemeSwitcher.vue';
export default {
  components: { HorizontalPillTabs, BraveThemeSwitcher },
};
</script>
