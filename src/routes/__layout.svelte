<script>
  import Header from "./../components/layouts/header.svelte"
  import Sidebar from "./../components/layouts/sidebar.svelte"
  import "../app.postcss";
</script>

<div class="root__layout">
  <Header />
  <main>
    <Sidebar />
    <div class="content">
      <slot>
      
      </slot>
    </div>
  </main>
</div>