<script lang="ts">
  import Footer from "./lib/components/Footer.svelte";
  import Navbar from "./lib/components/Navbar.svelte";
  import Home from "./lib/sections/Home.svelte";
</script>

<div class="container mx-auto">
  <Navbar />
  
  <main>
    <Home />
  </main>

  <Footer />
</div>