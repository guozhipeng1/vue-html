<template>
  <div id="app">
    <<home></home>
    <router-view/>
  </div>
</template>
<script>
	import home from './views/home.vue'
	export default{
		components:{
			home:home
		}
	}
</script>

<style lang="scss">
 
</style>
