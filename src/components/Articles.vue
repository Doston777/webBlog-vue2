<template>
  <section class="row articles" id="articles">
    <h2>Articles</h2>
    <div class="col-md-6 article" v-for="n in 8" v-bind:key="n">
      <img :src="`img/articles/article-${n}.jpg`" alt="">
      <h2>Lorem ipsum dolor sit amet.</h2>
      <p>Nullam sit amet accumsan lacus. Integer tincidunt, diam at tempus porttitor, lacus diam euismod purus, aliquet
        accumsan massa purus non lectus. Mauris fermentum libero mauris, ac semper ex pellentesque molestie. Quisque ac
        diam fermentum, consequat enim sed, elementum magna. Vestibulum ut tellus id quam malesuada interdum at ut urna.
        Integer semper erat nisl, in faucibus enim rutrum eu. Vestibulum posuere, elit eu aliquam venenatis, orci nibh
        fringilla mi, nec tristique lacus purus quis quam. Aliquam elementum faucibus nunc eu dictum. Ut tincidunt
        consectetur leo, in dignissim dolor condimentum eu. Phasellus a ornare ipsum. Quisque eu cursus diam, id posuere
        nulla. Curabitur tincidunt, nibh et iaculis hendrerit, sapien turpis pretium orci, nec volutpat magna velit eu
        quam. Sed efficitur felis tempus eros ullamcorper pretium. Nam eleifend ex mi, et auctor est condimentum sit
        amet. Quisque ullamcorper elementum lorem ut laoreet.</p>
      <span><a href="#">Read more...</a></span>
    </div>
  </section>
</template>

<script>
	export default {
		data() {
			return {
				src: 'img/articles/article-'
			}
		},
		name: 'Articles'
	}
</script>

<style scoped>

</style>