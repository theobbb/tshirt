

<script>
    import Slide from './Slide.svelte'

    const products = [
        { id: 1, name: 'Tee 1', artiste: 'Jo le rigolo', date: '12 janvier 2012', stock: { S: 3, M: 2, L: 0 } },
        { id: 2, name: 'Tee 2', artiste: 'Jaja le pas rigolo', date: '13 janvier 2013', stock: { S: 1, M: 4, L: 7 } },
        { id: 3, name: 'Tee 2', artiste: 'Jaja le pas rigolo', date: '13 janvier 2013', stock: { S: 1, M: 4, L: 7 } },
    ];

</script>

<div class='slider'>

    {#each products as product}
        <Slide product={product} />
        
    {/each}
</div>

<style>
    .slide {
        
    }
</style>
