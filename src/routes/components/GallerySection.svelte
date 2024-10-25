<script>
  import SvelteTooltip from "svelte-tooltip";
</script>
<div class="flex justify-center flex-col items-center">
<h1
  class="w-20 h-9 ml-24 mt-24 mb-10 font-serif font-bold text-2xl tracking-[0.3px]"
>
  Gallery
</h1>
<!-- gallery of the school -->
<div class="flex flex-row gap-8">
  <a href="home/carousel1.jpg" target="_blank">
    <SvelteTooltip tip="LSL Show" top color="#7FFF00">
      <img src="home/carousel1.jpg" alt="carousel1" class="w-80 h-72 ml-24" />
    </SvelteTooltip>
  </a>

  <a href="home/carousel2.jpg" target="_blank">
    <SvelteTooltip tip="LSL Show" top color="#7FFF00">
      <img src="home/carousel2.jpg" alt="carousel2" class="w-80 h-72" />
    </SvelteTooltip>
  </a>
  <a href="home/carousel3.jpg" target="_blank">
    <SvelteTooltip tip="Tug of War" top color="#7FFF00">
      <img src="home/carousel3.jpg" alt="carousel3" class="w-80 h-72" />
    </SvelteTooltip>
  </a>
</div>
<div class="flex flex-row gap-8 mt-8">
  <a href="home/gymnastics.jpg" target="_blank">
    <SvelteTooltip tip="Gymnastics" top color="#7FFF00">
      <img src="home/gymnastics.jpg" alt="gymnastics" class="w-80 h-72 ml-24" />
    </SvelteTooltip>
  </a>

  <a href="home/lifeskills.jpg" target="_blank">
    <SvelteTooltip tip="Washing Hands" top color="#7FFF00">
      <img src="home/lifeskills.jpg" alt="lifeskills" class="w-80 h-72" />
    </SvelteTooltip>
  </a>
  <a href="home/speakers.jpg" target="_blank">
    <SvelteTooltip tip="Public Speaking" top color="#7FFF00">
      <img src="home/speakers.jpg" alt="speakers" class="w-80 h-72" />
    </SvelteTooltip>
  </a>
</div>
<!-- "read more" button -->
<button
  type="button"
  class="text-white hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-bold text-sm px-5 py-2.5 me-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800 w-44 h-10 rounded bg-[#0193dc] ml-28 mt-10"
  >Read More</button
>
</div>