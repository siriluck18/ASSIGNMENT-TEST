<template>
	<div id="app">
		<h2> Find n-th term of series 1, 3, 6, 10, 15, 2 </h2>
	<div class="form-inline alert alert-info">
	  <div class="form-group mx-sm-3 mb-2">
	    <label >Given a number n</label>
	  </div>
	  <div class="form-group mx-sm-3 mb-2">
	  	<button @click="one" type="button" class="btn btn-info"> 1 </button>
	  </div>
	  <div class="form-group mx-sm-3 mb-2">
	  	<button @click="two" type="button" class="btn btn-info"> 2 </button>
	  </div>
	  <div class="form-group mx-sm-3 mb-2">
	  	<button @click="three" type="button" class="btn btn-info"> 3 </button>
	  </div>
	  <div class="form-group mx-sm-3 mb-2">
	  	<button @click="four" type="button" class="btn btn-info"> 4 </button>
	  </div>
	  <div class="form-group mx-sm-3 mb-2">
	  	<button @click="five" type="button" class="btn btn-info"> 5 </button>
	  </div>
	  <div class="form-group mx-sm-3 mb-2">
	  	<button @click="six" type="button" class="btn btn-info"> 6 </button>
	  </div>
	</div>
	<div class="form-inline">
	  <div class="form-group mx-sm-3 mb-2">
	    <label >Given a number : </label>
	  </div>
	  <div class="form-group mx-sm-3 mb-2">
	  	<div class="display">{{ getnumbers }}</div>
	  </div>
	</div>
	</div>
</template>

<script>
	export default{
		data() {
			return {
				getnumbers :'',
			}
		},
		methods: {
			one(){
				this.getnumbers = '1';
			},
			two(){
				this.getnumbers = '3';
			},
			three(){
				this.getnumbers = '6';
			},
			four(){
				this.getnumbers = '10';
			},
			five(){
				this.getnumbers = '15';
			},
			six(){
				this.getnumbers = '12';
			}
		}
	}
</script>

<style lang="less">
	#app
	{
		h2{
			margin: 30px;
		}
	}
	#numbern{
		width: 100%;
	}
</style>
