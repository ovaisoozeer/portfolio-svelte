<script lang="ts">
  import cvpdf from '$lib/assets/cv.pdf';
  import { Section, HeroHeader, FeatureDefault, FeatureItem } from 'flowbite-svelte-blocks';
  import { CalendarPlusOutline, DownloadOutline, InboxOutline } from 'flowbite-svelte-icons';
</script>

<Section>
  <HeroHeader
    class="mb-8 max-w-screen-md lg:mb-16"
    h2Class="mb-4 lg:mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white text-left"
    pClass="text-gray-500 sm:text-xl dark:text-gray-400 text-left sm:px-0 xl:px-0"
  >
    {#snippet h2()}Get down to brass tacks{/snippet}
    {#snippet paragraph()}{/snippet}
  </HeroHeader>
  <FeatureDefault>
    <FeatureItem>
      {#snippet icon()}<InboxOutline class="text-primary-600 dark:text-primary-300" />{/snippet}
      {#snippet h3()}Say Hello 👋🏽{/snippet}
      {#snippet paragraph()}
        <a href="mailto:ovais@expertlypragmatic.com"><u>Email</u></a> ovais@expertlypragmatic.com<br />
        <a href="tel:+443300430764"><u>Call</u></a> 0330 0430764
      {/snippet}
    </FeatureItem>
    <FeatureItem>
      {#snippet icon()}<DownloadOutline class="text-primary-600 dark:text-primary-300" />{/snippet}
      {#snippet h3()}Download my CV{/snippet}
      {#snippet paragraph()}
        Click <a download="ovais-oozeer-cv.pdf" href={cvpdf}><u>here</u> </a> for a PDF
      {/snippet}
    </FeatureItem>
    <FeatureItem>
      {#snippet icon()}<CalendarPlusOutline
          class="text-primary-600 dark:text-primary-300"
        />{/snippet}
      {#snippet h3()}No Strings Attached{/snippet}
      {#snippet paragraph()}
        Click <a target="_blank" href="https://calendar.app.google/PteCMAz5AeiBRbrp9">
          <u>here</u>
        </a> to book an intro call
      {/snippet}
    </FeatureItem>
  </FeatureDefault>
</Section>
