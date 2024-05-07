<script>
    let count = 1;
    let color = "black";
    const add = () => {
        count = count++;
        color = "blue";
    };
</script>

<main>
    <p>{count}</p>
    <p>{color}</p>
    <button on:click={add}> click </button>
</main>
