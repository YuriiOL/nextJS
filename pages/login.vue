<template>
  <section>
    <form>
      <h1>Login Page</h1>
      <div class="from-group">
        <input type="text" class="form-control" />
        <p>
          <nuxt-link to="/">To home page</nuxt-link>
        </p>
        <button class="btn btn-primary" type="submit">Login</button>
      </div>
    </form>
  </section>
</template>

<script>
export default {
  layout: "empty"
};
</script>

<style scoped>
form {
  width: 500px;
  margin: 0 auto;
}
</style>
