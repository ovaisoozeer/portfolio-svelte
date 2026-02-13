<script lang="ts">
  import { Section, Portfolio, PortfolioItem } from 'flowbite-svelte-blocks';

  const portfolios = [
    {
      customer: 'Department for Levelling Up, Housing and Communities',
      title: 'Architecture and prototyping',
      description: 'Voter Cards website development and service assessment',
      href: 'portfolio/dluhc',
      linkTitle: 'View case study'
    },
    {
      customer: 'Mars, Inc. ',
      title: 'Platform engineering',
      description: 'Infrastructure, multiple workstreams, and competing goals.',
      href: 'portfolio/mars',
      linkTitle: 'View case study'
    },
    {
      customer: 'The Very Group',
      title: 'Engineering management',
      description: 'Long term transformation',
      href: 'portfolio/tvg',
      linkTitle: 'View case study'
    }
  ];
</script>

<Section name="portfolio" sectionClass="antialiased">
  <Portfolio
    title="Case studies"
    subtitle="Three diistinct examples"
  >
    {#each portfolios as item}
      <PortfolioItem {item} />
    {/each}
  </Portfolio>
</Section>

<p class="text-center">Selected other projects and engagements:</p>
<ul class="w-full text-center">
  <li class="list-row">✈️ Civil Aviation Authority - Obstruction Management website - Developer</li>
  <li class="list-row">
    🚉 Rail Delivery Group - National Rail Enquiries, Common Services - Architect
  </li>
  <li class="list-row">💹 Schroders Personal Wealth - Lead capture website - Tech Lead</li>
  <li class="list-row">📊 Euromonitor International - ETL Platform - Developer</li>
  <li class="list-row">⚕️ BUPA - Test automation framework - Developer</li>
  <li class="list-row">🚢 Rolls Royce Marine - Ship-to-shore data platform - Tech Lead</li>
  <li class="list-row">🚗 Toyota Financial Services - B2C private leasing platform - Tech Lead</li>
  <li class="list-row">
    🏥 NHS Business Services Authority - Patient preferences service - Developer
  </li>
  <li class="list-row">🏫 Skills Funding Agency - National Apprenticeship programme - Developer</li>
  <li class="list-row">🏨 DeVere - Venues Website - Developer</li>
  <li class="list-row">🎼 ABRSM - Aural trainer app - Developer</li>
</ul>
