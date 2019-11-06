<script>
	import Header from "./components/Header.svelte"

</script>

<style>

	.wrapper {
		background-image: url('img/bg-min.jpg');
		height: 95vh;
		min-height: 950px;
		max-height: 1936px;
		background-position: 50% 30%;
		text-align: center;
		
	}
	.bumper {
		height: 20px;
		background-color: #383737;
	}

	.caption {
		position: absolute;
		left: 50%;
		top: 50%;
		transform: translate(-50%, 0%);
		width: 86%;
		color: #F5F3F1;
	}

	.caption h1 {
		font-size: 60px;
    	padding: 0 10%;
    	font-weight: 900;
	}

	.date-location {
		margin-top: 80px;
	}

	.date-location p {
		font-weight: 300;
    	font-size: 30px;
	}
	
	.book-now {
		display: flex;
		height: 80px;
		align-items: center;
		justify-content: center;
	}
</style>



<section class="wrapper">
	<Header />
	<div class="bumper"></div>
	<div class="caption">
		<h1>Frank's Bowling's First Major Retrospective</h1>
		<div class="date-location">
			<p><strong>Tate Britan, London</strong></p>
			<p style="margin: 30px">31 May - 26 August 2019</p>
		</div>
	</div>
</section>

<main>
	<section class="book-now"><h2>BOOK NOW</h2></section>
	<section class="gallery"></section>
</main>


