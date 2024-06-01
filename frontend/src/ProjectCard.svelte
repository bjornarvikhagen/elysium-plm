<script>
    export let title = '';
    export let details = '';
    
    const containerClasses = "bg-white dark:bg-zinc-800 p-4 rounded shadow";
    const textClasses = "text-zinc-700 dark:text-zinc-300";
  </script>
  
  <div class={containerClasses}>
    <h2 class="text-xl font-semibold mb-2">{title}</h2>
    <p class={textClasses}>{details}</p>
  </div>