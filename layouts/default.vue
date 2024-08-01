<script lang="ts" setup></script>

<template>
  <section class="grid" style="min-height: 100vh">
    <aside>Sidebar</aside>
    <div>
      <slot />
    </div>
  </section>
</template>

<style scoped>
grid {
  display: grid;
}
</style>
