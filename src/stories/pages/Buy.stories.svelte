<script>
    import '../../style/theme.scss'
    import {Meta, Template, Story} from "@storybook/addon-svelte-csf";
    import {viewportConfig} from '../util/config'
    import Buy from "../../pages/Buy.svelte";
</script>

<Meta title="Page/Buy" component={Buy} parameters={{
        layout: 'fullscreen',
        ...viewportConfig(true),
    }}
/>

<Template let:args>
    <Buy/>
</Template>

<Story name="Buy"/>