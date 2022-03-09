<template>
    <nav class="navbar navbar-dark bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand">{{title}}</a>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="поиск..." aria-label="Search">
          <button class="btn btn-outline-light" type="submit">Все</button>
        </form>
      </div>
    </nav>

</template>

<script>
    export default {
        name: "AppHeader",
        props: ['title'],
        data() {
            return {
            }
        },
    }
</script>

<style scoped>

</style>
