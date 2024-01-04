<script>
	import '../app.css';
</script>

<nav class="shadow slideIn">
	<div class="container flex items-center justify-center p-3 mx-auto text-gray-50">
		<h1 class="ml-2 text-md font-bold mt-2">Universidade Lusófona do Porto - Jornalismo Visual e de Dados</h1>
	</div>
</nav>

<slot />

<style>
	nav {
		background-color: #0000CD;
		position: fixed;
		top: 0;
		left: 0;
		right: 0;
		z-index: 100;
		width: 100%;
	}

	.slideIn {
		animation: slideIn ease 1s;
		-webkit-animation: slideIn ease 1s;
		-moz-animation: slideIn ease 1s;
		-o-animation: slideIn ease 1s;
		-ms-animation: slideIn ease 1s;
	}

	@keyframes slideIn {
		0% {
			transform: translateY(-100%);
		}
		100% {
			transform: translateY(0%);
		}
	}
</style>
