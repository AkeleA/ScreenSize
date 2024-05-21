<!-- <h1>Welcome to screen size</h1> -->
<script context="module">
  export const prerender = true;
</script>

<script lang="ts">
  import Header from '$lib/components/Header.svelte';
  import ScreenSize from '$lib/components/ScreenSize.svelte';
</script>

<Header title="Are you curious about your screen size?" />

<main class="p-6 max-w-3xl flex flex-col justify-center items-center m-auto">
  <p class="text-xl font-mono">
    As a web developer, knowing screen sizes is an essential tool for delivering modern, reponsive and funcitonal web applications
  </p>
  <ScreenSize/>
</main>