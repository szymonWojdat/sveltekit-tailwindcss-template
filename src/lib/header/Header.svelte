<script>
	import logo from './svelte-logo.svg';
</script>

<header>
	<div class="corner">
		<a href="/">
			<img src={logo} alt="Logo" class="max-h-20"/>
		</a>
	</div>

	<nav>
		<ul>
			<li>
				<a href="/">Home</a>
			</li>
			<li>
				<a href="/about">About</a>
			</li>
		</ul>
	</nav>
</header>
