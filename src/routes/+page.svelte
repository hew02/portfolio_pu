<script>
	import { base } from '$app/paths';
</script>

<header>
	<h1>Juan Diego Mora</h1>
	<h2>Composition Portfolio</h2>
</header>
<main>
	<div class="video_container">
		<iframe
			class="video"
			width="560"
			height="315"
			src="https://www.youtube.com/embed/i9ZQBw6s90A?si=JZ2RC1t7n7-efHI9"
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
			referrerpolicy="strict-origin-when-cross-origin"
			allowfullscreen
		>
		</iframe>
		<p class="description">
			Title and some more info. <a
				class="link"
				href="https://drive.google.com/file/d/1Va2jMdLojAUctrXoQ_l2I5Z4Jho3K0oX/view?usp=sharing"
				target="_blank">Score Here</a
			>
		</p>
	</div>

	<div></div>
</main>
<footer></footer>

<!-- TO DEPLOY ON GH PAGES USE = npm run deploy-->

<style>
	@import url('https://fonts.googleapis.com/css2?family=Lora:wght@400..700&display=swap');

	:global(body) {
		background-color: #121212;
		margin: 0;
		padding: 0;
		overflow: auto;
		scrollbar-width: none; /* Firefox */
		-ms-overflow-style: none; /* IE 10 */
	}

	:gobal(body)::-webkit-scrollbar {
		display: none; /* Chrome, Safari, Edge */
	}

	header {
		color: rgb(255, 255, 247);
		font-family: 'Lora', serif;
		font-weight: 500; /* value from 400 to 700 */
		margin: 50px 0px 85px 50px;
	}

	h1 {
		font-size: 60px;
		padding: 0px;
		margin: 0px;
	}

	h2 {
		font-size: 30px;
		padding: 0px;
		margin: 0px;
	}

	.video {
		width: 100%;
		height: auto;
		aspect-ratio: 16/9;
		border: none;
	}

	.video_container {
		margin: 0 10% 10% 10%;
		max-width: 100%;
	}

	.description {
		color: rgb(255, 255, 247);
		text-align: center;
		font-family: 'Lora', serif;
		font-size: clamp(0.5rem, 2vw, 3rem); /* automatically resize with limits */
		font-weight: 400;
	}

	.link {
		color: rgb(255, 255, 247);
		font-family: 'Lora', serif;
		text-decoration: none; /* remove underline from links */
		font-size: clamp(0.5rem, 2vw, 3rem);
		font-weight: 400;
	}

	.link:hover {
		color: #ffff00;
	}
</style>
