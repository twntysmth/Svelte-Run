<script>
    import SiteHeader from "../lib/components/base/SiteHeader.svelte";
    import SiteFooter from "../lib/components/base/SiteFooter.svelte";

    // import styles
    import "../lib/scss/styles.scss"
</script>

<SiteHeader />
    <main>
        <slot />
    </main>
<SiteFooter />