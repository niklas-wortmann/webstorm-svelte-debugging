<script>

    export let counter = 0;
</script>

<main>
    <button on:click={() => counter--}>Decrease</button>
    <span>{counter}</span>
    <button on:click={() => counter++}>Increase</button>
</main>

<style>
    main {
        text-align: center;
        padding: 1em;
        max-width: 240px;
        margin: 0 auto;
    }
</style>