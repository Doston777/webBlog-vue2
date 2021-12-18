<template>
  <div id="app">
    <Welcome/>
    <Navbar />
    <SocLinks />
    <Articles />
    <About />
    <Contact />
    <Footer />
  </div>
</template>

<script>
	import Welcome from './components/Welcome'
	import Navbar from './components/Navbar'
  import SocLinks from './components/SocLinks.vue'
  import Articles from './components/Articles'
  import About from './components/About'
  import Contact from './components/Contact'
  import Footer from './components/Footer'
  
	export default {
		name: 'App',
		components: {
			Welcome,
			Navbar,
      SocLinks,
      Articles,
      About,
      Contact,
      Footer
		}
	}
</script>

<style>

</style>
