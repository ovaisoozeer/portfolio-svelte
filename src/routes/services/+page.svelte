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
      <p class="text-gray-500 dark:text-gray-400">
        The things I value are my time, experience and commitment
      </p>
      <p class="text-gray-500 dark:text-gray-400">Consider the following types of engagement:</p>
      <p class="text-gray-500 dark:text-gray-400">
        (A) Contributing/coaching full time for a scoped project
      </p>
      <p class="text-gray-500 dark:text-gray-400">
        (B) Leading/mentoring fractionally towards a long term goal
      </p>
      <p class="text-gray-500 dark:text-gray-400">
        <em>Why choose B?</em>
      </p>
      <p class="text-gray-500 dark:text-gray-400">
        My experience means I can understand and steer existing teams. By doing a fractional role
        (1/2 a day or more per week), I am able to invest the rest of my time into other clients,
        and personal development which you benefit from. And over time I tend to influence others,
        which optimises the wider organisation in achieving its outcomes.
      </p>
      <p class="text-gray-500 dark:text-gray-400">
        If you do need A, I am a competent tech lead and can coach your team as a contributor.
        However, as this is highly demanding I do not commit to prolonged engagements.
      </p>
    </FaqItem>
    <FaqItem>
      {#snippet h3()}Billing{/snippet}
      <p class="text-gray-500 dark:text-gray-400">
        The type of work I prefer translates to an hourly/daily rate (rather than fixed price). I am
        open to a retainer or fixed term contracts.
      </p>
      <p class="text-gray-500 dark:text-gray-400">
        Not all work is as well defined as this, and I'll increment/decrement depending on the
        engagement.
      </p>
      <p class="text-gray-500 dark:text-gray-400">
        Get in touch on the button below and we'll have a chat :)
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
