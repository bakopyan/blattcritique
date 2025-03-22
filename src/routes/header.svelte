<script lang="ts">
	import * as config from '$lib/config'
</script>

<nav>
	<a href="/" class="title">
		<b>{config.title}</b>
	</a>
</nav>

<style>
	nav {
		padding-block: var(--size-7);

		@media (min-width: 768px) {
			display: flex;
			justify-content: space-between;
		}

		a {
			color: inherit;
			text-decoration: none;
		}

		a.title {
			font-family: 'Basteleur Moonlight', sans-serif;
  			font-size: 34px;
  			font-weight: bold;
		}
	}
</style>
