<script context="module">
  export const prerender = true;
</script>

<script lang="ts">
  import Header from '$lib/components/Header.svelte';
</script>

<Header title="About Us" />

<main class="p-6 max-w-xl mx-auto">
  <h1 class="text-4xl font-bold mb-4">About Us</h1>
  <p class="text-xl">
    This is the about page of our website. Here you can learn more about our company and our mission.
  </p>
</main>