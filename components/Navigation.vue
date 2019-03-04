<template>
	<div>
	  <b-navbar toggleable="lg" type="dark" variant="info">
	    <b-navbar-brand href="#">Portfolio</b-navbar-brand>

	    <b-navbar-toggle target="nav_collapse" />

	    <b-collapse is-nav id="nav_collapse">
	     

	      <!-- Right aligned nav items -->
	      <b-navbar-nav class="ml-auto">
	       	<b-nav-item href="#">Home</b-nav-item>
	        

	        <b-nav-item-dropdown text="Portfolio" right>
	          <b-dropdown-item href="#">Laravel Projects</b-dropdown-item>
	          <b-dropdown-item href="#">Vue Projects</b-dropdown-item>
	          <b-dropdown-item href="#">React</b-dropdown-item>
	          <b-dropdown-item href="#">Template Impletmentation</b-dropdown-item>
	        </b-nav-item-dropdown>

	        
	      </b-navbar-nav>
	    </b-collapse>
	  </b-navbar>
</div>
</template>
<script>
	export default{
		name: 'MitauNavigation'
	}
</script>
