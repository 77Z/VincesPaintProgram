<page actionBarHidden="{true}">
    <gridLayout>
        <image src="~/img/logo.png" horizontalAlignment="center" verticalAlignment="middle" stretch="none" />
    </gridLayout>
</page>

<script>
    import Explorer from './Explorer.svelte';
    import { navigate } from 'svelte-native';

    setTimeout(function() {
        navigate({
            page: Explorer
        });
    }, 2000);
</script>
