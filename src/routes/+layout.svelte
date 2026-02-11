<script lang="ts">
  import './layout.css';
  import favicon from '$lib/assets/favicon.svg';
  import { DarkMode } from 'flowbite-svelte';
  import { Navbar, NavBrand, NavHamburger, NavUl, NavLi, Button } from 'flowbite-svelte';
  let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<header>
  <Navbar>
    <NavBrand href="/">
      <img src={favicon} class="mr-3 h-6 sm:h-9" alt="Logo" />
      <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-white">
        Ovais Oozeer
      </span>
    </NavBrand>
    <div class="flex items-center lg:order-2">
      <NavHamburger />
      <DarkMode />
    </div>
    <NavUl>
      <NavLi href="/">Home</NavLi>
      <NavLi href="about">About</NavLi>
      <NavLi href="services">Services & Pricing</NavLi>
    </NavUl>
  </Navbar>
</header>
<div class="md:mx-8 w-full">
  {@render children()}
</div>
