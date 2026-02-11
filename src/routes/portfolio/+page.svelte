<script lang="ts">
  import dluhcImg from '$lib/assets/dluhc.png';
  import marsImg from '$lib/assets/mars.png';
  import tvgImg from '$lib/assets/tvg.jpg';

  const projects = [
    {
      slug: 'dluhc',
      title: 'DLUHC',
      description:
        'Department for Levelling Up, Housing and Communities — delivery and product leadership.',
      image: dluhcImg,
      href: '/portfolio/dluhc'
    },
    {
      slug: 'mars',
      title: 'Mars',
      description: 'Product and delivery consultancy for global brand programmes.',
      image: marsImg,
      href: '/portfolio/mars'
    },
    {
      slug: 'tvg',
      title: 'TVG',
      description: 'Strategy and delivery for digital transformation.',
      image: tvgImg,
      href: '/portfolio/tvg'
    }
  ];
</script>

<div class="mb-8 flex w-full flex-col">
  <h2 class="m-4 text-center text-4xl tracking-wide">Case studies</h2>
  <p class="mx-auto mb-10 max-w-2xl text-center text-lg tracking-wide text-base-content/80">
    Some recent case studies:
  </p>
</div>

<div class="mb-8 grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-3">
  {#each projects as project}
    <a href={project.href} class="group">
      <div class="card bg-base-200 shadow-xl transition-shadow hover:shadow-2xl">
        <figure class="overflow-hidden">
          <img
            src={project.image}
            alt={project.title}
            class="h-48 w-full object-cover transition-transform duration-300 group-hover:scale-105"
          />
        </figure>
        <div class="card-body">
          <h3 class="card-title tracking-wide">{project.title}</h3>
          <p class="line-clamp-3 text-sm tracking-wide text-base-content/80">
            {project.description}
          </p>
          <div class="mt-2 card-actions justify-end">
            <span class="link text-sm font-medium link-hover">View case study →</span>
          </div>
        </div>
      </div>
    </a>
  {/each}
</div>

<p class="mx-auto mb-10 max-w-2xl text-center text-lg tracking-wide text-base-content/80">
  Selected other projects and engagements:
</p>
<ul class="list items-center rounded-box bg-base-100 shadow-md">
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
