<script>
import TodoBlock from '@/components/TodoBlock.vue';

export default {
  components: { TodoBlock }
};
</script>

<template>
  <main class="app">
    <TodoBlock />
  </main>
</template>

<style scoped>
.app {
  max-width: 1440px;
  width: 100%;
  display: flex;
  justify-content: center;
  padding: 90px 0;
  background: linear-gradient(
    to top left,
    rgba(215, 190, 252, 1),
    rgba(188, 177, 252, 1),
    rgba(161, 174, 252, 1),
    rgba(148, 189, 252, 1)
  );
}
</style>
