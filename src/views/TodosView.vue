<template>
  <div class="container">
    <h2>Todo Edit</h2>
    <TodoForm :editing="true" />
  </div>
</template>

<script>
import TodoForm from "@/components/TodoForm.vue";
export default {
  components: {
    TodoForm,
  },
  setup() {
    return {};
  },
};
</script>

<style></style>
