<script lang="ts">
  import { Section, Faq, FaqItem, ContentWithImage, Content } from 'flowbite-svelte-blocks';
  import dluhc from '$lib/assets/dluhc.png';
  import mars from '$lib/assets/mars.png';
  import tvg from '$lib/assets/tvg.jpg';
</script>

<Section name="contentwithimg">
  <ContentWithImage>
    {#snippet h2()}Cabinet Office - Architect - Voter card registration{/snippet}
    <p class="mb-4">National infrastructure project architecture and service assessment</p>
    <p class="mb-4">
      As an architect on the voter cards programme, I had a hand in designing the architecture of
      the system, working closely with specialists on threat modelling and user experience. I owned
      the technical beta assessment for the overseas and absent voter registration route of the
      programme. I also developed the GDS design system prototype, re-using components of DVLA, Blue
      Badge, and HMPO sites.
    </p>

    {#snippet image()}
      <div class="bg-white">
        <img class="w-full rounded-lg" src={dluhc} alt="Cabinet office logo" />
      </div>
    {/snippet}
  </ContentWithImage>
  <ContentWithImage>
    {#snippet h2()}Mars, Inc. - Tech Lead - Platform engineering{/snippet}
    <p class="mb-4">National infrastructure project architecture and service assessment</p>
    <p class="mb-4">
      I was tasked to set up a platform engineering team, delivering coaching and tooling as needed
      within a hierarchical business unit. I helped the team to increase predictability and
      productiveness through coaching of business and tech stakeholders in a more product-aligned
      mindset, supporting a culture of continuous improvement, and developing tooling to support
      business users and feature teams.
    </p>
    {#snippet image()}
      <div class="bg-white">
        <img class="w-full rounded-lg" src={mars} alt="Cabinet office logo" />
      </div>
    {/snippet}
  </ContentWithImage>
  <ContentWithImage>
    {#snippet h2()}The Very Group - Engineering Manager - Conversational UI team{/snippet}
    <p class="mb-4">National infrastructure project architecture and service assessment</p>
    <p class="mb-4">
      I was asked to manage an internal team at TVG, during a period of major refactoring and
      unexpected changes of staff. I supported a diverse team with their personal development whilst
      ensuring that the product owner's vision was delivered.
    </p>
    {#snippet image()}
      <div class="bg-white">
        <img class="w-full rounded-lg" src={tvg} alt="Cabinet office logo" />
      </div>
    {/snippet}
  </ContentWithImage>
</Section>
<Section name="content">
  <Content>
    {#snippet h2()}Selected other projects and engagements{/snippet}

    <p class="mb-4 font-light"></p>
    <p class="mb-4 font-light">
      ✈️ Civil Aviation Authority - Obstruction Management website - Developer
    </p>
    <p class="mb-4 font-light">
      🚉 Rail Delivery Group - National Rail Enquiries, Common Services - Architect
    </p>
    <p class="mb-4 font-light">💹 Schroders Personal Wealth - Lead capture website - Tech Lead</p>
    <p class="mb-4 font-light">📊 Euromonitor International - ETL Platform - Developer</p>
    <p class="mb-4 font-light">⚕️ BUPA - Test automation framework - Developer</p>
    <p class="mb-4 font-light">🚢 Rolls Royce Marine - Ship-to-shore data platform - Tech Lead</p>
    <p class="mb-4 font-light">
      🚗 Toyota Financial Services - B2C private leasing platform - Tech Lead
    </p>
    <p class="mb-4 font-light">
      🏥 NHS Business Services Authority - Patient preferences service - Developer
    </p>
    <p class="mb-4 font-light">
      🏫 Skills Funding Agency - National Apprenticeship programme - Developer
    </p>
    <p class="mb-4 font-light">🏨 DeVere - Venues Website - Developer</p>
    <p class="mb-4 font-light">🎼 ABRSM - Aural trainer app - Developer</p>
  </Content>
</Section>
