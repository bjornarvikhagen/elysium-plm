<script>
    import ProjectCard from './ProjectCard.svelte';
  </script>
  
  <section class="flex-grow p-4">
    <h1 class="text-3xl font-bold mb-4">Welcome to Elysium</h1>
    <p class="mb-4">Your comprehensive and adaptable PLM system.</p>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
      <ProjectCard title="Vard" details="Hiring a new engineer" />
      <ProjectCard title="Vard" details="Designing a new ship" />
      <ProjectCard title="Vard" details="Deploying a new PLM system." />
    </div>
  </section>