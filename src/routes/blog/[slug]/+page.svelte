<script lang="ts">
    export let data;
</script>

<div>
  {#each data.content as { name } }
    <div class="font-semibold">{name}</div>
  {/each}
</div>