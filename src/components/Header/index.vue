<template>
  <header class="header">
    <div class="wrap">
      <Logo title="Marvel" />
    </div>
  </header>
</template>

<script>
import Logo from '@/components/Logo';

export default {
  name: 'Header',
  components: {
    Logo
  }
};
</script>

<style scoped>
.header {
  display: block;
  width: 100%;
}
</style>
