<script lang="ts">
  import { Section, HeroHeader } from 'flowbite-svelte-blocks';
  import { Button } from 'flowbite-svelte';
  import { ArrowRightOutline, VolumeUpOutline } from 'flowbite-svelte-icons';
</script>

<Section name="heroVisual">
  <div class="mr-auto place-self-center lg:col-span-7">
    <HeroHeader
      h1Class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl dark:text-white"
      pClass="text-left max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-400 sm:px-0 lg:px-0 xl:px-0"
    >
      {#snippet h1()}Hi, my name is Ovais{/snippet}
      {#snippet paragraph()}
        <VolumeUpOutline class="inline" /> əʊveɪs | he/him<br /><br />
        A platform-agnostic, hands-on tech lead who enjoys collaboration.<br />
        I build applications, services, and platforms for the public and private sector.<br />
      {/snippet}
      <a href="about">
        <Button color="light" size="xl" class="mr-3 inline-flex items-center justify-center">
          About
        </Button>
      </a>
      <a href="explore">
        <Button color="light" size="xl" class="mr-3 inline-flex items-center justify-center">
          Explore
        </Button>
      </a>
      <a href="brass-tacks">
        <Button size="xl" color="light" class="inline-flex items-center justify-center">
          Get down to brass tacks<ArrowRightOutline size="md" class="-mr-1 ml-2" />
        </Button>
      </a>
    </HeroHeader>
  </div>
  <!-- <div class="hidden lg:col-span-5 lg:mt-0 lg:flex">
    <img src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/hero/phone-mockup.png" alt="mockup" />
  </div> -->
</Section>
