<script lang="ts">
  import { Section, Cta } from 'flowbite-svelte-blocks';
</script>

<Section>
  <Cta ctatype="heading">
    {#snippet h2()}Content{/snippet}
    <p class="mb-6 font-light text-gray-500 md:text-lg dark:text-gray-400">
      Write-ups, developing ideas, and misc musings on my blog.
    </p>
    <a
      target="_blank"
      href="https://devgutfeel.substack.com"
      class="mb-2 rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:outline-none dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
    >
      Go to devgutfeel.substack.com
    </a>
  </Cta>
  <Cta ctatype="heading" class="mt-16">
    {#snippet h2()}Community{/snippet}
    <p class="font-light text-gray-500 md:text-lg dark:text-gray-400">
      Generalist World is a commmunity of polymaths.
    </p>
    <p class="mb-6 font-light text-gray-500 md:text-lg dark:text-gray-400">
      Ramen Club is a founders' community.
    </p>
    <a
      target="_blank"
      href="https://generalist.world/"
      class="mr-3 mb-2 rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:outline-none dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
    >
      Go to Generalist World
    </a>
    <a
      target="_blank"
      href="https://www.ramenclub.so/"
      class="mb-2 rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:outline-none dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
    >
      Go to Ramenclub
    </a>
  </Cta>
  <Cta ctatype="heading" class="mt-16">
    {#snippet h2()}Events{/snippet}
    <p class="mb-6 font-light text-gray-500 md:text-lg dark:text-gray-400">London-based meetups.</p>
    <a
      target="_blank"
      href="https://luma.com/devgutfeel"
      class="mb-2 rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:outline-none dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
    >
      Go to luma.com/devgutfeel
    </a>
  </Cta>
</Section>