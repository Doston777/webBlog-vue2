<template>
  <nav class="navbar sticky-top navbar-expand-sm text-white" id="navbar">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
      <i class="bi-list text-white" aria-hidden="true"></i>
    </button>
    <div class="collapse navbar-collapse" id="collapsibleNavbar">
      <div class="justify-content-sm-center">
        <ul class="navbar-nav">
          <li><a href="#header" class="nav-link">Home</a></li>
          <li><a href="#articles" class="nav-link">Articles</a></li>
          <li><a href="#about-me" class="nav-link">About</a></li>
          <li><a href="#contact" class="nav-link">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
	export default {
		name: 'Navbar'
	}
</script>

<style scoped>

</style>