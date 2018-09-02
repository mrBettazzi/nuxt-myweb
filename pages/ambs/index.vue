<template>
	<section class="ambs">
		<article class="amb">
			<div class="thumbnail" style="background-image: url(https://www.drivespark.com/img/2017/12/19-1513667806-vintage-cars-exempted-from-ban-ngt-india-5.jpg)"></div>
			<h1>Title</h1>
			<p>Some nice preview text here</p>
		</article>
		<article class="amb">
			<div class="thumbnail" style="background-image: url(https://www.drivespark.com/img/2017/12/19-1513667814-vintage-cars-exempted-from-ban-ngt-india-6.jpg"></div>
			<h1>Title</h1>
			<p>Some nice preview text here</p>
		</article>
		<article class="amb">
			<div class="thumbnail" style="background-image: url(https://1hu9t72zwflj44abyp2h0pfe-wpengine.netdna-ssl.com/wp-content/uploads/2017/05/Antique-black-car.jpg"></div>
			<h1>Title</h1>
			<p>Some nice preview text here</p>
		</article>
		<article class="amb">
			<div class="thumbnail" style="background-image: url(https://1hu9t72zwflj44abyp2h0pfe-wpengine.netdna-ssl.com/wp-content/uploads/2017/05/Antique-car.jpg"></div>
			<h1>Title</h1>
			<p>Some nice preview text here</p>
		</article>
		<article class="amb">
			<div class="thumbnail" style="background-image: url(https://hips.hearstapps.com/toc.h-cdn.co/assets/16/14/3200x1600/landscape-1459816624-1954-mercedes-300sl-gullwing-a.jpg?resize=480:*"></div>
			<h1>Title</h1>
			<p>Some nice preview text here</p>
		</article>
		<article class="amb">
			<div class="thumbnail" style="background-image: url(https://lmdigianetti.it/it/images/vintage-car/Porsche-356.jpg"></div>
			<h1>Title</h1>
			<p>Some nice preview text here</p>
		</article>
	</section>
</template>

<style scoped>
.ambs {
	display: flex;
	flex-flow: row wrap;
	justify-content: left;
	align-items: center;
}
.amb {
	box-sizing: border-box;
	width: 280px;
	padding: 8px;
	border: 1px solid #ccc;
	box-shadow: 0 2px 2px #aaa;
	margin: 10px;	
}
.thumbnail {
	background-position: center;
	background-size: cover;
	width: 100%;
	height: 200px;	
}
</style>