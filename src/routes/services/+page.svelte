<script lang="ts">
  import { Button } from 'flowbite-svelte';
  import { Faq, FaqItem, Section } from 'flowbite-svelte-blocks';
</script>

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
        My experience enables me to deeply understand and steer existing teams. By doing a
        fractional role (1/2 a day or more per week), I am able to invest the rest of my time into
        other clients, and personal development - which you benefit from. Over time my influence can
        help the wider organisation achieve its wider goals.
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
      {#snippet h3()}Billing{/snippet}
      <p>
        At the time of writing this my rate begins at £500/day.
      </p>
      <p class="text-gray-500 dark:text-gray-400">
        Get in touch on the button below for a conversation :)
      </p>
      <a href="contact">
        <Button
          size="xl"
          color="light"
          class="inline-flex items-center justify-center rounded-lg bg-primary-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-primary-800 dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
        >
          Contact
        </Button>
      </a>
    </FaqItem>
  </Faq>
</Section>
