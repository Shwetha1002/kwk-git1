<script>
	let name = "Shwetha";
	let bio = "I'm a rising sophmore at Syracuse University, I love baking, art and math";
	let hobbies = ["Baking", "Working Out", "Math"];
</script>

<style>
	.about-container {
		max-width: 600px;
		margin: 2rem auto;
		padding: 1.5rem;
		border: 1px solid #ccc;
		border-radius: 8px;
		font-family: sans-serif;
		box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
	}
	h1 {
		margin-bottom: 0.5rem;
	}
	.avatar {
		width: 120px;
		height: 120px;
		border-radius: 50%;
		object-fit: cover;
		margin-bottom: 1rem;
	}
</style>

<div class="about-container">
	
	<img class="avatar" src="pic_of_me.jpg" alt="Profile Photo" />

	<h1>Hi, I'm {name} 👋</h1>
	<p>{bio}</p>

	<h2>Things I enjoy:</h2>
	<ul>
		{#each hobbies as hobby}
			<li>{hobby}</li>
		{/each}
	</ul>
</div>
