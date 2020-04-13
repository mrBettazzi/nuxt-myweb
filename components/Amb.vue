<template>
	<article class="amb">
		<div class="thumbnail" :style="{backgroundImage: 'url(' + thumbnail + ')'}"></div>
		<h1>{{ title }}</h1>
		<p>{{ previewText }}</p>
	</article>
</template>

<scripts>
export default {
	props: ["thumbnail", "title", "previewText"];
};
</scripts>

<style scoped>
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