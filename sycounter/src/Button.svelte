<script>
    import Button from "@smui/button";

    let count = 0;

    function Counter() {
        count += 1;
    }
</script>

<Button color="#fa8072" variant="unelevated" on:click={Counter}>
    <Label>
        Clicked {count}
        {count === 1 ? "time" : "times"}</Label
    >
</Button>
