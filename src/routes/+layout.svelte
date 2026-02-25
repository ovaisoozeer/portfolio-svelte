<script lang="ts">
  import './layout.css';
  import faviconoo from '$lib/assets/favicon-oo.png';
  import { DarkMode } from 'flowbite-svelte';
  import { Navbar, NavBrand, NavHamburger, NavUl, NavLi, Button } from 'flowbite-svelte';
  let { children } = $props();
</script>

<svelte:head><link rel="icon" href={faviconoo} /></svelte:head>

<header>
  <Navbar>
    <NavBrand href="/">
      <img src={faviconoo} class="mr-3 h-6 sm:h-9" alt="Logo" />
      <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-white">
        Ovais Oozeer
      </span>
    </NavBrand>
    <div class="flex items-center lg:order-2">
      <DarkMode />
    </div>
  </Navbar>
</header>
{@render children()}
