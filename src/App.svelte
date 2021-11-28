<script>
	let name = 'world';
	import Slider from './Slider.svelte'
</script>

<header>

	<div class="titles">
		<h2>514 tshirt</h2>
		<div>
			<h3>1 : 20$</h3>
			<h3>2 : 37$</h3>
			<h3>3 : 50$</h3>
		</div>
	</div>

	


	
	<!--
	<div class="vendre">
		<h3>Vendre!!??</h3>
		<p>Eh oui, vous pouvez vendre vos designs et faire 50% de comission!<br/>
		Apprenez en plus ici.</p>
	</div>
	-->
</header>

<Slider />



<style>
	header {
		padding: 12px;
		position: fixed;
		top: 0;
		left: 0;
		display: flex;
		width: 100%;
		justify-content: space-between;
	}

	.vendre {
		padding: 8px 12px;
		max-width: 400px;
	}

	.vendre:hover {
		background: rgba(0, 0, 0, 0.055);
	}

	h1 {
		
	}
</style>