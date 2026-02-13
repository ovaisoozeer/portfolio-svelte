<script lang="ts">
  import { Section, Faq, FaqItem } from 'flowbite-svelte-blocks';
</script>

<Section name="faq">
  <h2 class="mb-8 text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white">
    Cabinet Office - Voter card registration
  </h2>
  <Faq>
    <div>
      <FaqItem>
        {#snippet h3()}Role{/snippet}
        <p class="text-gray-500 dark:text-gray-400">Architecture and Prototyping</p>
      </FaqItem>
      <FaqItem>
        {#snippet h3()}Task{/snippet}
        <p class="text-gray-500 dark:text-gray-400">
          National infrastructure project architecture and service assessment
        </p>
      </FaqItem>
    </div>
    <div>
      <FaqItem>
        {#snippet h3()}Description{/snippet}
        <p class="text-gray-500 dark:text-gray-400">
          As an architect on the voter cards programme, I had a hand in designing the architecture
          of the system, working closely with specialists on threat modelling and user experience. I
          owned the technical beta assessment for the overseas and absent voter registration route
          of the programme. I also developed the GDS design system prototype, re-using components of
          DVLA, Blue Badge, and HMPO sites.
        </p>
      </FaqItem>
    </div>
  </Faq>
  <h2 class="mb-8 text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white">
    Mars, Inc.
  </h2>
  <Faq>
    <div>
      <FaqItem>
        {#snippet h3()}Role{/snippet}
        <p class="text-gray-500 dark:text-gray-400">Tech Lead</p>
      </FaqItem>
      <FaqItem>
        {#snippet h3()}Task{/snippet}
        <p class="text-gray-500 dark:text-gray-400">
          Set up a platform engineering team, delivering coaching and tooling as needed within a
          hierarchical business
        </p>
      </FaqItem>
    </div>
    <div>
      <FaqItem>
        {#snippet h3()}Description{/snippet}
        <p class="text-gray-500 dark:text-gray-400">
          Coming in as Tech Lead, I helped the team to increase predictability and productiveness.
          This, through coaching of the business and tech stakeholders to have a more
          product-aligned mindset, supporting a culture of continuous improvement, and developing
          tooling to support business users and feature teams. The ways of working surmised in the
          book Team Topologies are very much in line with what I advocated here.
        </p>
      </FaqItem>
    </div>
  </Faq>
  <h2 class="mb-8 text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white">
    The Very Group
  </h2>
  <Faq>
    <div>
      <FaqItem>
        {#snippet h3()}Role{/snippet}
        <p class="text-gray-500 dark:text-gray-400">Engineering Manager (Conversational UI)</p>
      </FaqItem>
      <FaqItem>
        {#snippet h3()}Task{/snippet}
        <p class="text-gray-500 dark:text-gray-400">
          Reporting to the CTO, coaching an internal team, and overseeing architectural changes
        </p>
      </FaqItem>
    </div>
    <div>
      <FaqItem>
        {#snippet h3()}Description{/snippet}
        <p class="text-gray-500 dark:text-gray-400">
          I was asked to manage an internal team at TVG, during a period of major refactoring and
          unexpected changes of staff. I supported a diverse team with their personal development
          whilst ensuring that the product owner's vision was delivered.
        </p>
      </FaqItem>
    </div>
  </Faq>

  <h1 class="text-center">Selected other projects and engagements:</h1>
  <ul class="mb-16 w-full text-center">
    <li class="list-row mb-4">
      ✈️ Civil Aviation Authority - Obstruction Management website - Developer
    </li>
    <li class="list-row mb-4">
      🚉 Rail Delivery Group - National Rail Enquiries, Common Services - Architect
    </li>
    <li class="list-row mb-4">💹 Schroders Personal Wealth - Lead capture website - Tech Lead</li>
    <li class="list-row mb-4">📊 Euromonitor International - ETL Platform - Developer</li>
    <li class="list-row mb-4">⚕️ BUPA - Test automation framework - Developer</li>
    <li class="list-row mb-4">🚢 Rolls Royce Marine - Ship-to-shore data platform - Tech Lead</li>
    <li class="list-row mb-4">
      🚗 Toyota Financial Services - B2C private leasing platform - Tech Lead
    </li>
    <li class="list-row mb-4">
      🏥 NHS Business Services Authority - Patient preferences service - Developer
    </li>
    <li class="list-row mb-4">
      🏫 Skills Funding Agency - National Apprenticeship programme - Developer
    </li>
    <li class="list-row mb-4">🏨 DeVere - Venues Website - Developer</li>
    <li class="list-row mb-4">🎼 ABRSM - Aural trainer app - Developer</li>
  </ul>
</Section>
