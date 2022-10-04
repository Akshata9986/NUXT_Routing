<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <NuxtLink to="/" class="navbar-brand">Navbar</NuxtLink>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <NuxtLink to="/" class="nav-link"
            >Home <span class="sr-only">(current)</span>
          </NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink to="/login" class="nav-link">Login</NuxtLink>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style>
.nav-link {
  cursor: pointer;
}
</style>