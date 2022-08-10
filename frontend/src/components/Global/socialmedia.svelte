<script lang="ts">
    import {socialmedia} from "../../config.json"
    import tippy from 'tippy.js';
  </script>
  
  <div class="mt-4">
      <div class="grid grid-cols-5 sm:grid-cols-10 mt-3 space-x">
          {#each socialmedia as data}
          <div class="font-ultrabold">
            <a href="{data.link}">
              <img width="32px" height="32px" src={data.image} alt={data.name} use:tippy={{content: data.name}} class="duration-200 hover:scale-[1.2]">
            </a>
            </div>
         {/each}
      </div>
  </div>