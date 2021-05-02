<page>
    <actionBar title="Vince's Paint Program">
        <actionItem text="Settings" android.position="right" on:tap={settings} />
    </actionBar>

    <scrollView>
        <wrapLayout>
            <!-- <label text="first" width="33%" height="33%" backgroundColor="#4383b8"/>
            <label text="second" width="33%" height="33%" backgroundColor="#1c486b"/>
            <label text="third" width="33%" height="33%" backgroundColor="#286290"/>
            <label text="fourth" width="33%" height="33%" backgroundColor="#286290"/>
            <label text="first" width="33%" height="33%" backgroundColor="#4383b8"/>
            <label text="second" width="33%" height="33%" backgroundColor="#1c486b"/>
            <label text="third" width="33%" height="33%" backgroundColor="#286290"/>
            <label text="fourth" width="33%" height="33%" backgroundColor="#286290"/> -->
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <PreviewCard />
            <!-- Copyright -->
            <label text="Copyright © 77Z 2021" class="copyright" width="100%" horizontalAlignment="center" />
        </wrapLayout>
    </scrollView>
</page>

<script>
    import Settings from './Settings.svelte';
    import { navigate } from 'svelte-native';
    import PreviewCard from '../shared/PreviewCard.svelte';

    function settings() {
        navigate({
            page: Settings
        })
    }

</script>

<style>
    .copyright {
        text-align: center;
        width: 100%;
    }
</style>