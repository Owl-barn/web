<script lang="ts">
    let { children } = $props();
</script>

{@render children()}

<svelte:head>
    <meta name="theme-color" content="#bf8d50" />
</svelte:head>

<style lang="scss" global>
    @import "styles/global.scss";
</style>
