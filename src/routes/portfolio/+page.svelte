<script lang="ts">
  import { Section, ContentWithImage } from 'flowbite-svelte-blocks';
  import { A, Breadcrumb, BreadcrumbItem } from 'flowbite-svelte';
  import dluhc from '$lib/assets/dluhc.png';
  import mars from '$lib/assets/mars.png';
  import tvg from '$lib/assets/tvg.jpg';
  import wcg from '$lib/assets/wcg.jpg';
</script>

<div class="place-self-center lg:col-span-12">
  <Breadcrumb aria-label="Breadcrumbs">
    <BreadcrumbItem href="/" home>Home</BreadcrumbItem>
    <BreadcrumbItem href="about">About</BreadcrumbItem>
    <BreadcrumbItem href="portfolio">Portfolio</BreadcrumbItem>
  </Breadcrumb>
</div>
<Section name="contentwithimg">
  <ContentWithImage>
    {#snippet h2()}Wheatley Care Group - Residata{/snippet}
    <p class="mb-4"><em>Tech Lead</em></p>
    <p class="mb-4">
      As architect/tech lead of a small team, I analysed and rebuilt a legacy Visual FoxPro desktop
      application as a modern accessible web app in Dotnet Core/Blazor, deployed to Azure
      Hybrid IaaS. Built in partnership with end-users with feature parity and the same database as
      the original.
    </p>
    {#snippet image()}
      <div>
        <img class="w-full rounded-lg" src={wcg} alt="Wheatley Care Group logo" />
      </div>
    {/snippet}
  </ContentWithImage>
  <ContentWithImage>
    {#snippet h2()}Cabinet Office - Voter card registration{/snippet}
    <p class="mb-4">
      <A
        href="https://www.gov.uk/register-to-vote"
        class="font-medium hover:underline"
        target="_blank">www.gov.uk/register-to-vote</A
      >
    </p>
    <p class="mb-4"><em>Architect</em></p>
    <p class="mb-4">
      As an architect on the voter cards programme, I contributed to the design the architecture of
      the platform, working closely with specialists on threat modelling and user experience. I
      owned the technical beta assessment for the overseas and absent voter registration website. I
      also developed the prototype.
    </p>

    {#snippet image()}
      <div class="bg-white">
        <img class="w-full rounded-lg" src={dluhc} alt="Cabinet office logo" />
      </div>
    {/snippet}
  </ContentWithImage>
  <ContentWithImage>
    {#snippet h2()}Mars, Inc. - Platform engineering{/snippet}
    <p class="mb-4">
      <A href="https://www.mms.com/en-gb" class="font-medium hover:underline" target="_blank"
        >www.mms.com</A
      >
    </p>
    <p class="mb-4"><em>Tech Lead</em></p>
    <p class="mb-4">
      I was tasked to set up a team, delivering coaching and tooling as needed. I increased
      predictability and productiveness through coaching of business and tech stakeholders,
      supporting a culture of continuous improvement, and developing tooling to support business
      users and feature teams.
    </p>
    {#snippet image()}
      <div class="bg-white">
        <img class="w-full rounded-lg" src={mars} alt="Cabinet office logo" />
      </div>
    {/snippet}
  </ContentWithImage>
  <ContentWithImage>
    {#snippet h2()}The Very Group - Conversational UI{/snippet}
    <p class="mb-4">
      <A href="https://www.theverygroup.com/" class="font-medium hover:underline" target="_blank"
        >www.theverygroup.com</A
      >
    </p>
    <p class="mb-4"><em>Engineering Manager</em></p>
    <p class="mb-4">
      I was asked to manage an internal team at TVG, during a period of major refactoring and
      unexpected changes. I supported a diverse team with their personal development whilst ensuring
      that the product owner's vision was delivered.
    </p>
    {#snippet image()}
      <div class="bg-white">
        <img class="w-full rounded-lg" src={tvg} alt="Cabinet office logo" />
      </div>
    {/snippet}
  </ContentWithImage>
  <div>
    <h2 class="mb-4 text-4xl font-extrabold tracking-tight text-gray-900 dark:text-white">
      Selected other clients
    </h2>
    <br />
    <p class="mb-4 font-light">
      ✈️ Civil Aviation Authority - Obstruction Management website - Developer <A
        href="https://www.caa.co.uk/commercial-industry/airspace/event-and-obstacle-notification/obstacle-notification/"
        class="font-medium hover:underline"
        target="_blank">ACOMS</A
      >
    </p>
    <p class="mb-4 font-light">
      🚉 Rail Delivery Group - National Rail Enquiries, Common Services - Architect <A
        href="https://www.nationalrail.co.uk/"
        class="font-medium hover:underline"
        target="_blank">www.nationalrail.co.uk</A
      >
    </p>
    <p class="mb-4 font-light">
      💹 Schroders Personal Wealth - Lead capture website - Tech Lead <A
        href="https://www.spw.com/"
        class="font-medium hover:underline"
        target="_blank">www.spw.com</A
      >
    </p>
    <p class="mb-4 font-light">
      📊 Euromonitor International - ETL Platform - Developer <A
        href="https://www.euromonitor.com/"
        class="font-medium hover:underline"
        target="_blank">www.euromonitor.com</A
      >
    </p>
    <p class="mb-4 font-light">
      ⚕️ BUPA - Test automation framework - Developer <A
        href="https://www.bupaglobal.com/en"
        class="font-medium hover:underline"
        target="_blank"
        >www.bupaglobal.com/en
      </A>
    </p>
    <p class="mb-4 font-light">🚢 Rolls Royce Marine - Ship-to-shore data platform - Tech Lead</p>
    <p class="mb-4 font-light">
      🚗 Toyota Financial Services - B2C private leasing platform - Tech Lead <A
        href="https://www.toyota.no/"
        class="font-medium hover:underline"
        target="_blank">www.toyota.no</A
      >
    </p>
    <p class="mb-4 font-light">
      🏥 NHS Business Services Authority - Patient preferences service - Developer (internal)
    </p>
    <p class="mb-4 font-light">
      🏫 Department for Education - National Apprenticeship programme - Developer <A
        href="https://www.gov.uk/apply-apprenticeship"
        class="font-medium hover:underline"
        target="_blank">www.gov.uk/apply-apprenticeship</A
      >
    </p>
    <p class="mb-4 font-light">
      🏨 DeVere - Venues Website - Developer <A
        href="https://www.devere.co.uk/"
        class="font-medium hover:underline"
        target="_blank">www.devere.co.uk</A
      >
    </p>
  </div>
</Section>
