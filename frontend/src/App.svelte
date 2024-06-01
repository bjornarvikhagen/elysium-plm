<script>
  import Header from './Header.svelte';
  import Sidebar from './Sidebar.svelte';
  import Content from './Content.svelte';
</script>

<div class="min-h-screen text-zinc-900 dark:text-zinc-100 flex flex-col">
  <Header />
  <main class="flex flex-grow">
    <Sidebar />
    <Content />
  </main>
</div>