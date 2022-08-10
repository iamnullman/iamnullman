<script lang="ts">
  import {technologies} from "../../config.json"
  import tippy from 'tippy.js';
</script>

<div class="mt-4">
    <p class="text-3xl font-bold"><span class="text-pink-500">Technologies</span> I use 💻</p> 
    <div class="grid grid-cols-5 sm:grid-cols-10 gap-5 mt-3 space-x-4">
        {#each technologies as tech}
        <div class="font-ultrabold">
            <img src={tech.image} alt={tech.name} use:tippy={{content: tech.name}} class="duration-200 hover:scale-[1.2]">
         </div>
       {/each}
    </div>
</div>