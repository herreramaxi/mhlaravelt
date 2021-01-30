<script>
    import { onMount } from "svelte";
    import HelloWorld from "./HelloWorld.svelte";
    import Ra from "./RA.svelte";

    onMount(() => {
        console.log("the component has mounted");
    });
</script>

// App.svelte
<main>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Example Component</div>
                    <div class="card-body">I'm an example component.</div>
                    <HelloWorld />
                    <Ra />
                </div>
            </div>
        </div>
    </div>
</main>
