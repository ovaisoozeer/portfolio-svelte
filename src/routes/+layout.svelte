<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<div class="drawer">
	<input id="my-drawer-2" type="checkbox" class="drawer-toggle" />
	<div class="drawer-content flex flex-col">
		<!-- Navbar -->
		<div class="navbar w-full bg-base-300">
			<div class="flex-none lg:hidden">
				<label for="my-drawer-2" aria-label="open sidebar" class="btn btn-square btn-ghost">
					<svg
						xmlns="http://www.w3.org/2000/svg"
						fill="none"
						viewBox="0 0 24 24"
						class="inline-block h-6 w-6 stroke-current"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							d="M4 6h16M4 12h16M4 18h16"
						></path>
					</svg>
				</label>
			</div>
			<div class="mx-2 flex-1 px-2"><a href="/">Ovais Oozeer</a></div>
			<div class="hidden flex-none lg:block">
				<ul class="menu menu-horizontal">
					<!-- Navbar menu content here -->
					<li><a href="/">Home</a></li>
					<li><a href="cv">CV</a></li>
					<li><a href="work">Work</a></li>
					<li><a href="about">About</a></li>
					<li><a href="blog">Blog</a></li>
					<li><a href="events">Events</a></li>
				</ul>
			</div>
		</div>
		<!-- Page content here -->
		{@render children()}
	</div>
	<div class="drawer-side">
		<label for="my-drawer-2" aria-label="close sidebar" class="drawer-overlay"></label>
		<ul class="menu min-h-full w-80 bg-base-200 p-4">
			<!-- Sidebar content here -->
			<li><a href="/">Home</a></li>
			<li><a href="cv">CV</a></li>
			<li><a href="work">Work</a></li>
			<li><a href="about">About</a></li>
			<li><a href="blog">Blog</a></li>
			<li><a href="events">Events</a></li>
		</ul>
	</div>
</div>
