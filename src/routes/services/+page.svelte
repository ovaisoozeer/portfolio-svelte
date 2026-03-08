<script lang="ts">
  import { Breadcrumb, BreadcrumbItem, Button } from 'flowbite-svelte';
  import { Faq, FaqItem, Section } from 'flowbite-svelte-blocks';
</script>

<div class="place-self-center lg:col-span-12">
  <Breadcrumb aria-label="Breadcrumbs">
    <BreadcrumbItem href="/" home>Home</BreadcrumbItem>
    <BreadcrumbItem href="about">About</BreadcrumbItem>
    <BreadcrumbItem href="services">Services</BreadcrumbItem>
  </Breadcrumb>
</div>
<Section>
  <h2 class="mb-8 text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white">
    Services and pricing
  </h2>
  <Faq>
    <FaqItem>
      {#snippet h3()}Types of work{/snippet}
      <p>
        <em>A: Leading/mentoring fractionally towards a long term goal </em>
      </p>
      <p class="text-gray-500 dark:text-gray-400">
        I apply my experience to deeply understand and steer teams. By working fractionally (one
        day or more per week), I am able to split the rest of my time between other clients and
        personal development - which you benefit from. I focus my insights and contributions on
        helping your organisation achieve its long term vision.
      </p>
      <p>
        <em>B: Contributing/coaching full time for a scoped project </em>
      </p>
      <p class="text-gray-500 dark:text-gray-400">
        I am a competent tech lead and can coach your team as a contributor. However, as this is
        highly demanding I do not commit to prolonged engagements.
      </p>
    </FaqItem>
    <FaqItem>
      {#snippet h3()}Pricing{/snippet}
      <p>
        This depends on whether the work is fractional vs full-time, leadership vs contributing, or
        outcome- vs output-based.
      </p>
      <p class="text-gray-500 dark:text-gray-400">
        Get in touch on the button below for a conversation :)
      </p>
      <Button
        href="contact"
        size="xl"
        color="light"
        class="inline-flex items-center justify-center rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
      >
        Contact
      </Button>
    </FaqItem>
  </Faq>
</Section>
