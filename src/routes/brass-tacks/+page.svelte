<script lang="ts">
  import cvpdf from '$lib/assets/cv.pdf';
  import { Section, HeroHeader, FeatureDefault, FeatureItem } from 'flowbite-svelte-blocks';
  import {
    CalendarPlusOutline,
    DownloadOutline,
    MailBoxOutline,
    PersonChalkboardOutline,
    PhoneOutline
  } from 'flowbite-svelte-icons';
</script>

<Section name="feature">
  <HeroHeader
    class="mb-8 max-w-screen-md lg:mb-16"
    h2Class="mb-4 lg:mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white text-left"
    pClass="text-gray-500 sm:text-xl dark:text-gray-400 text-left sm:px-0 xl:px-0"
  >
    {#snippet h2()}Get down to brass tacks{/snippet}
    {#snippet paragraph()}What would you like to do?{/snippet}
  </HeroHeader>
  <FeatureDefault>
    <FeatureItem>
      {#snippet icon()}<DownloadOutline class="text-primary-600 dark:text-primary-300" />{/snippet}
      {#snippet h3()}CV{/snippet}
      {#snippet paragraph()}
        <a download="ovais-oozeer-cv.pdf" href={cvpdf}>Click here to download</a>
      {/snippet}
    </FeatureItem>
    <FeatureItem>
      {#snippet icon()}<PersonChalkboardOutline
          class="text-primary-600 dark:text-primary-300"
        />{/snippet}
      {#snippet h3()}Services{/snippet}
      {#snippet paragraph()}
        <a download="services" href={cvpdf}>Click here to explore services and pricing</a>
      {/snippet}
    </FeatureItem>
    <FeatureItem>
      {#snippet icon()}<MailBoxOutline class="text-primary-600 dark:text-primary-300" />{/snippet}
      {#snippet h3()}Email{/snippet}
      {#snippet paragraph()}
        Contact me at ovais@expertlypragmatic.com
      {/snippet}
    </FeatureItem>
    <FeatureItem>
      {#snippet icon()}<PhoneOutline class="text-primary-600 dark:text-primary-300" />{/snippet}
      {#snippet h3()}Phone{/snippet}
      {#snippet paragraph()}Call me on +44 (0)330 0430764
      {/snippet}
    </FeatureItem>
    <FeatureItem>
      {#snippet icon()}<CalendarPlusOutline
          class="text-primary-600 dark:text-primary-300"
        />{/snippet}
      {#snippet h3()}Book{/snippet}
      {#snippet paragraph()}
        <a target="_blank" href="https://calendar.app.google/PteCMAz5AeiBRbrp9" class="link">
          Schedule a meeting (opens gCal in new tab)
        </a>
      {/snippet}
    </FeatureItem>
  </FeatureDefault>
</Section>
