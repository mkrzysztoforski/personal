<script>
</script>

<main>
	<div class="wrap">
		<h1>maciej krzysztoforski</h1>
		<span class="line_welcome"></span>
	</div>
	<a class="links" target="_blank" href="https://www.linkedin.com/in/mkrzysztoforski/">linkedin</a>
	<a class="links" target="_blank" href="https://github.com/mkrzysztoforski">github</a>
</main>

<style>
	.wrap {
		width: 300px;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-flow: column;
	}

	main {
		background: #13151a;
		width: 100%;
		height: 100vh;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-flow: column;
		font-family: 'Roboto', sans-serif;
	}

	h1 {
		color: #fafafa;
		font-weight: 300;
	}

	.line_welcome {
		display: block;
		height: 1px;
		width: 100px;
		background-color: #7f7f88;
		animation: animateLine 5s infinite;
		margin: 10px 0 25px 0;
	}

	.links {
		color: #fafafa;
		margin-top: 15px;
		letter-spacing: .5px;
		font-weight: 300;
		text-decoration: none;
	}

	.links:hover {
		transition: 420ms;
		color: #7f7f88;
		text-decoration: underline;
	}

	@keyframes animateLine {
		0% {
			width: 0;
		}
		25% {
			width: 100%;
			margin-left: 0;
		}
		75% {
			width: 100%;
			margin-left: 0;
		}
		100% {
			margin-left: 100%;
			width: 0;
		}
	}

</style>
