<template>
	<div class="bg">
	<SectionPreloader />
	<SectionHeader />
	<div class="wrapper">
		<SectionStartSlider />
		<SectionServices />
		<SectionMenuDoces />
		<SectionMenuSalgados />
		<SectionMenuConveniencia />
		<SectionMenuRestaurante />
		<SectionAbout />
		<SectionChoose />
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
import SectionMenuConveniencia from './components/section_menu_conveniencia.vue';
import SectionMenuRestaurante from './components/section_menu_restaurante.vue';
import SectionMenuDoces from './components/section_menu_doces.vue';
import SectionMenuSalgados from './components/section_menu_salgados.vue';
import SectionChoose from './components/section_choose.vue';
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
		SectionMenuConveniencia,
		SectionMenuRestaurante,
		SectionMenuDoces,
		SectionMenuSalgados,
		SectionChoose,
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
}
}
</script>