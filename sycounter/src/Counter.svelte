<script>
    import { Label } from "@smui/button";
    export let type = "salmon";

    let count = 0;

    function Counter() {
        count += 1;
    }
</script>

<button class={type} on:click={Counter}>
    <Label>
        Clicked {count}
        {count === 1 ? "time" : "times"}</Label
    >
</button>

<style>
    .primary {
        background-color: #fa8072;
        border: 0;
        border-radius: 8px;
        margin: 2 1rem 1rem 0;
        padding: 0.7rem;
        color: white;
    }
</style>
