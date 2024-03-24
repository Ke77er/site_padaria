<template>
	<div class="bg">
	<SectionPreloader />
	<SectionHeader />
	<div class="wrapper">
		<SectionStartSlider />
		<SectionAbout />
		<SectionServices />
		<SectionMenu />
		<SectionChoose />
		<SectionTestimonials />
		<SectionBlog />
		<SectionCTA />
	</div>
	<SectionFooter />
	</div>
</template>



<script>

import SectionPreloader from './components/section_preloader.vue';
import SectionHeader from './components/section_header.vue';
import SectionStartSlider from './components/section_startslider.vue';
import SectionAbout from './components/section_about.vue';
import SectionServices from './components/section_services.vue';
import SectionMenu from './components/section_menu.vue';
import SectionChoose from './components/section_choose.vue';
import SectionTestimonials from './components/section_testimonials.vue';
import SectionBlog from './components/section_blog.vue';
import SectionCTA from './components/section_cta.vue';
import SectionFooter from './components/section_footer.vue';
export default {
	name: 'app',
	components: {
		SectionPreloader,
		SectionHeader,
		SectionStartSlider,
		SectionAbout,
		SectionServices,
		SectionMenu,
		SectionChoose,
		SectionTestimonials,
		SectionBlog,
		SectionCTA,
		SectionFooter,

	},

	data() {
		return {


		};
	},

	methods: {
	

	},

	mounted() {
		window.dataLayer = window.dataLayer || [];
	  function gtag(){dataLayer.push(arguments);}
	  gtag('js', new Date());

	  gtag('config', 'UA-125314689-11');
	},
};
</script>
<style>
@import url('../src/assets/styles/bootstrap.css');
@import url('../src/assets/fonts/font-awesome/css/font-awesome.css');
@import url('../src/assets/fonts/font-awesome/css/line-awesome.css');
@import url('../src/assets/styles/animate.css');
@import url('../src/assets/styles/magnific-popup.css');
@import url('../src/assets/styles/splitting.css');
@import url('../src/assets/styles/swiper.css');
@import url('../src/assets/style.css');
</style>
