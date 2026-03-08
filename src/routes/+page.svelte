<script lang="ts">
  import { Section, HeroHeader } from 'flowbite-svelte-blocks';
  import { Button } from 'flowbite-svelte';
  import { VolumeUpOutline } from 'flowbite-svelte-icons';
</script>

<Section name="heroVisual">
  <div class="place-self-center lg:col-span-12">
    <HeroHeader
      h1Class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl dark:text-white text-center"
      pClass="text-center max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-400 sm:px-0 lg:px-0 xl:px-0"
    >
      {#snippet h1()}Hi, my name is Ovais{/snippet}
      {#snippet paragraph()}
        <VolumeUpOutline class="inline" /> əʊveɪs | he/him<br /><br />
        A framework-agnostic, hands-on tech lead.<br /><br />
        I deliver applications, facilitate conversations, and help teams collaborate.<br /><br />
        I also give back to the community.<br />
      {/snippet}
    </HeroHeader>
    <div class="place-self-center lg:col-span-12 text-center">
      <Button
        href="about"
        size="xl"
        color="light"
        class="mr-3 inline-flex items-center justify-center rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
      >
        About
      </Button>
      <Button
        href="contact"
        size="xl"
        color="light"
        class="inline-flex items-center justify-center rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
      >
        Contact
      </Button>
    </div>
  </div>
  <!-- <div class="hidden lg:col-span-5 lg:mt-0 lg:flex">
    <img src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/hero/phone-mockup.png" alt="mockup" />
  </div> -->
</Section>
