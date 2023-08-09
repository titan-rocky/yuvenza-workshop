<script lang="ts">
    export let data: { data: Array<String> };
</script>

<div class="text-[20px] w-[80%]">
    {#each data.data as name, idx}
        <div>( {idx + 1} ) {name} 🎉</div>
    {/each}
</div>
