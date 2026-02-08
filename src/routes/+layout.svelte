<script lang="ts">
  import './layout.css';
  import favicon from '$lib/assets/favicon.svg';

  let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<div class="drawer">
  <input id="my-drawer-2" type="checkbox" class="drawer-toggle" />
  <div class="drawer-content flex flex-col">
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
      <div class="mx-2 flex-1 px-2 tracking-wide"><a href="/">Ovais Oozeer</a></div>
      <div class="hidden flex-none lg:block">
        <ul class="menu menu-horizontal">
          <li><a href="cv tracking-wide">CV</a></li>
          <li><a href="blog tracking-wide">Blog</a></li>
          <li><a href="events tracking-wide">Events</a></li>
        </ul>
      </div>
    </div>
    <div class="m-8">
      {@render children()}
    </div>
    <footer class="footer bg-neutral p-10 text-neutral-content sm:footer-horizontal">
      <aside class="grid-flow-col items-center tracking-wide">
        <p>Copyright © {new Date().getFullYear()} Expertly Pragmatic Ltd - All right reserved</p>
      </aside>
      <nav>
        <h6 class="footer-title tracking-wide">Consultancy</h6>
        <a class="link tracking-wide link-hover" href="introduction">Introduction</a>
        <a class="link tracking-wide link-hover" href="types-of-work">Services</a>
        <a class="link tracking-wide link-hover" href="pricing">Pricing</a>
      </nav>
      <nav>
        <h6 class="footer-title tracking-wide">Community</h6>
        <a class="link tracking-wide link-hover" href="events">Events</a>
      </nav>
      <nav>
        <h6 class="footer-title tracking-wide">Info</h6>
        <a class="link tracking-wide link-hover" href="contact">Contact</a>
        <a
          class="link tracking-wide link-hover"
          href="https://find-and-update.company-information.service.gov.uk/company/16110928"
          >Expertly Pragmatic Ltd (VAT Registered)</a
        >
      </nav>
    </footer>
  </div>
  <div class="drawer-side">
    <label for="my-drawer-2" aria-label="close sidebar" class="drawer-overlay"></label>
    <ul class="menu min-h-full w-80 bg-base-200 p-4">
      <li><a href="/">Home</a></li>
      <li><a href="cv">CV</a></li>
      <li><a href="work">Work</a></li>
      <li><a href="about">About</a></li>
      <li><a href="blog">Blog</a></li>
      <li><a href="events">Events</a></li>
    </ul>
  </div>
</div>
