<template>
    <header>
        <span class="title"> Trello</span>
        <router-link class="btn-header" to="/">Mis paneles</router-link>
    </header>
</template>

<script>
export default {
    name: 'app-header'
}
</script>

<style scoped>
  header {
  box-sizing: border-box;
  background-color: #607d8b;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  margin: 0;
  padding: 1rem;
}
.title {
        align-self: center;
        color: #eceff1;
        font-size: 1.2rem;
        font-weight: bold;
        margin-right: 1rem;
    }

    .btn-header {
        background-color: #455a64;
        border: none;
        border-radius: 3px;
        color: #b0bec5;
        cursor: pointer;
        text-decoration: none;
        padding: 0.5rem;
        margin: 0 0.5rem;
    }
</style>