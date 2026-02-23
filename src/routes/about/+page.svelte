<script lang="ts">
  import { Section, Cta } from 'flowbite-svelte-blocks';
</script>

<Section>
  <Cta ctatype="heading">
    {#snippet h2()}Breadth and depth{/snippet}
    <p class="mb-6 font-light text-gray-500 md:text-lg dark:text-gray-400">
      Read about some of my previous work
    </p>
    <a
      href="portfolio"
      class="mr-2 mb-2 rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:outline-none dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
    >
      Review portfolio
    </a>
  </Cta>
  <Cta ctatype="heading" class="mt-16">
    {#snippet h2()}Working in the open{/snippet}
    <p class="mb-6 font-light text-gray-500 md:text-lg dark:text-gray-400">
      I prefer candour to confidentiality.
    </p>
    <a
      href="services"
      class="mr-2 mb-2 rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:outline-none dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
    >
      Check out my pricing
    </a>
    <a
      target="_blank"
      href="https://github.com/ovaisoozeer"
      class="mr-2 mb-2 rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:outline-none dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
    >
      GitHub
    </a>
  </Cta>
  <Cta ctatype="heading" class="mt-16">
    {#snippet h2()}Start with why{/snippet}
    <p class="mb-6 font-light text-gray-500 md:text-lg dark:text-gray-400">
      I enjoy collaborating with others on clear goals.
    </p>
    <a
      href="links"
      class="mr-2 mb-2 rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:outline-none dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
    >
      Content, Community, and Events
    </a>
  </Cta>
</Section>
