<script lang="ts">
	import { SiGithub } from '@icons-pack/svelte-simple-icons';
</script>

<div class="navbar bg-neutral">
	<a role="button" class="btn btn-ghost btn-circle" href="https://github.com/Nertaicon">
		<SiGithub />
	</a>
</div>

<div class="main">
	<div class="flex min-h-screen items-center justify-center">
		<article class="prose prose-2xl">
			<h1>Nertaicon</h1>
		</article>
	</div>
</div>

<style>
	.navbar {
		display: flex;
		justify-content: flex-end;
	}

	.main {
		background: radial-gradient(
			circle,
			var(--color-base-100) 0%,
			var(--color-base-200) 50%,
			var(--color-base-300) 100%
		);
	}

	h1 {
		background: linear-gradient(to right, var(--color-primary), var(--color-accent));
		background-clip: text;
		color: transparent;
	}
</style>
