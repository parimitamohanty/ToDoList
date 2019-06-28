<template>
  <div class="about">
    <h1>To Do List of {{ their_name }}, So many things to do!</h1>
    <p>This is Parimita Mohanty’s To Do list developed in Vue.Js to learn Vue.Js.</p>
  </div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>