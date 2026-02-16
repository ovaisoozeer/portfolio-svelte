<script lang="ts">
  import { Section, Cta } from 'flowbite-svelte-blocks';
</script>

<Section>
  <Cta ctatype="heading">
    {#snippet h2()}Change over Planning{/snippet}
    <p class="mb-6 font-light text-gray-500 md:text-lg dark:text-gray-400">
      Optimise outcomes with minimal waste. Review portfolio.
    </p>
    <a
      href="portfolio"
      class="mr-2 mb-2 rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:outline-none dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
    >
      Portfolio
    </a>
  </Cta>
  <Cta ctatype="heading" class="mt-16">
    {#snippet h2()}Transparency over Guardedness{/snippet}
    <p class="mb-6 font-light text-gray-500 md:text-lg dark:text-gray-400">
      Psychological safety promotes healthy discussion. Peruse pricing.
    </p>
    <a
      href="services"
      class="mr-2 mb-2 rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:outline-none dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
    >
      Services & Pricing
    </a>
  </Cta>
  <Cta ctatype="heading" class="mt-16">
    {#snippet h2()}Autonomy over Hierarchy{/snippet}
    <p class="mb-6 font-light text-gray-500 md:text-lg dark:text-gray-400">
      Trust in contributors with clear boundaries. Explore collaborations.
    </p>
    <a
      href="explore"
      class="mr-2 mb-2 rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 focus:outline-none dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
    >
      Content, Community, and Events
    </a>
  </Cta>
</Section>
