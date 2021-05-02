<stackLayout class="stack" on:tap={openWorkspace}>
    <image src="~/img/logo.png" width="100" height="100" />
    <label text="My Workspace" />
</stackLayout>

<script>

    import Workspace from "../views/Workspace.svelte";
    import { navigate } from "svelte-native";

    function openWorkspace() {
        navigate({ page: Workspace });
    }
</script>

<style>
    .stack {
        padding: 10;
        box-sizing: border-box;
    }
</style>