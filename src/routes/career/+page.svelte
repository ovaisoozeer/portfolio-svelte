<script lang="ts">
  import { Timeline, TimelineItem, Button, Breadcrumb, BreadcrumbItem } from 'flowbite-svelte';
  import { Section } from 'flowbite-svelte-blocks';
  import { ArrowRightOutline } from 'flowbite-svelte-icons';
</script>

<div class="place-self-center lg:col-span-12">
  <Breadcrumb aria-label="Breadcrumbs">
    <BreadcrumbItem href="/" home>Home</BreadcrumbItem>
    <BreadcrumbItem href="about">About</BreadcrumbItem>
    <BreadcrumbItem href="career">Career</BreadcrumbItem>
  </Breadcrumb>
</div>
<Section>
  <Timeline>
    <TimelineItem title="Student Developer in Petrochemical automation" date="2006-2007">
      <p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">
        During my sandwich degree , I completed a year as an onsite developer for Oilband Ltd based
        in Buxton. There, I developed features for their flagship desktop application, as well as
        testing hardware, and writing device drivers.
      </p>
    </TimelineItem>
    <TimelineItem title="Developer in Music/Media" date="2008-2014">
      <p class="text-base font-normal text-gray-500 dark:text-gray-400">
        My first graduate job was working under the mentorship of the technical director at Release
        Consulting Ltd. In my six years here I developed and ran several desktop and web application
        projects, database migrations, and native mobile apps.
      </p>
    </TimelineItem>
    <TimelineItem title="Senior Developer in Digital Marketing" date="2014-2015">
      <p class="text-base font-normal text-gray-500 dark:text-gray-400">
        A year of coaching the dotnet development team at Creator Digital. Set up ways of working
        between capability silos, and managed tasks in a matrix-managed organisation. Also developed
        several web apps, data pipelines and POCs for new clients.
      </p>
    </TimelineItem>
    <TimelineItem title="Senior Consultant at Valtech UK Ltd" date="2015-2024">
      <p class="text-base font-normal text-gray-500 dark:text-gray-400">
        Several years of architecture assessment, greenfield development, and leading teams.
        Completed over 20 projects. Led the development and architecture communities through
        acquisition and capability mapping.
      </p>
      <Button color="alternative">Learn more<ArrowRightOutline class="ms-2 h-5 w-5" /></Button>
    </TimelineItem>
    <TimelineItem title="Director at Expertly Pragmatic Ltd" date="2024-present">
      <p class="text-base font-normal text-gray-500 dark:text-gray-400">
        Fractional tech leadership, facilitation and coaching.
      </p>
    </TimelineItem>
  </Timeline>
</Section>
