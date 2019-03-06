<template>
	<div class="container">
		<section>
		<h3>Project list</h3>
		
		<project></project>
	</section>
	</div>
	
</template>
<script>
	import 'bootstrap/dist/css/bootstrap.css';
	import 'bootstrap-vue/dist/bootstrap-vue.css';
	import Project from '~/components/Project.vue';
	export default{
		components:{
			Project
		}
	}
</script>