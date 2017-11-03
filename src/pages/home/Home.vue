<template>
  <div class="hello">
  	<index-header />
  	<index-banner />
  </div>
</template>

<script>
	import header from "./header";
	import banner from "./banner";
	export default {
	  name: 'HelloWorld',
	  data () {
	    return {
	      msg: 'Welcome to Your Vue.js App'
	    }
	  },
	  components:{
	  	"index-header":header,
	  	"index-banner":banner
	  }
	  
	}
</script>
<style scoped>
</style>
