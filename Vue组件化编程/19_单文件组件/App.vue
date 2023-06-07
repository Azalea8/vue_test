<template>
  <div>
    <school></school>
    <student></student>
  </div>
</template>

<script>
  import Student from "./Student.vue";
  import School from "./School.vue";

  export default {
    name: 'App',
    components: {
      School,
      Student,
    }
  }
</script>

<style>

</style>