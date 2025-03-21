<script lang="ts">
	import * as config from '$lib/config'
</script>

<footer>
	<p>{config.title} &copy {new Date().getFullYear()}</p>
    <ul class="links">
		<li>
			<a href="/about">About</a>
		</li>
		<!-- <li>
			<a href="/contact">Contact</a>
		</li> -->
	</ul>
</footer>

<style>
	footer {
		padding-block: var(--size-7);
		border-top: 1px solid var(--border);
		@media (min-width: 768px) {
			display: flex;
			justify-content: space-between;
		}

		a {
			color: inherit;
			text-decoration: none;
		}

		p {
			color: var(--text-2);
		}
	}

    .links {
			margin-block: var(--size-7);

			@media (min-width: 768px) {
				display: flex;
				gap: var(--size-7);
				margin-block: 0;
			}
		}
</style>
