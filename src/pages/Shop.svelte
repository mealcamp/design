<script lang="ts">
    import Container from "../components/Container.svelte";
    import Header from "../components/Header/index.svelte";
    import List from "../components/List/index.svelte";
    import ListBody from "../components/List/example/Menu.svelte";
    import Footer from "../components/Footer/index.svelte";
    import FooterBody from "../components/Footer/item/Shop.svelte";
    import Margin from "../components/Margin.svelte";
</script>

<Container>
    <Header subtitle="풀빛마루" back/>
    <main>
        <h2>풀빛마루</h2>
        <h2 style="font-weight: 400;margin-left: 0;">에서</h2>
        <br/>
        <h1>뭐를 먹을까요?</h1>
        <Margin size="20"/>

        <h2>추천</h2>
        <Margin size="5"/>
        <List>
            <ListBody/>
        </List>
        <Margin size="15"/>

        <h2>모든 메뉴</h2>
        <Margin size="5"/>
        <List>
            <ListBody/>
        </List>
        <Margin size="15"/>

        <h2>지금 시킬 수 없는 메뉴</h2>
        <Margin size="5"/>
        <List>
            <ListBody/>
        </List>
        <Margin size="15"/>
    </main>
    <Footer>
        <FooterBody/>
    </Footer>
</Container>