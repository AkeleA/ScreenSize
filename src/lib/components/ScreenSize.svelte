<script lang="ts">
  let width = window.innerWidth;
  let height = window.innerHeight;

  function updateDimensions() {
    width = window.innerWidth;
    height = window.innerHeight;
  }

  window.addEventListener('resize', updateDimensions);
</script>

<div class=" flex flex-col gap-4 items-center justify-center m-auto text-2xl font-bold ">
  Screen size:
  <span class="text-4xl">
    {width} x {height}
  </span>
</div>