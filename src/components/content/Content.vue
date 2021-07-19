<template>
    <div id="content">
        <sidebar />
        <table-content />
    </div>
</template>

<script>
    import sidebar from './Sidebar.vue';
    import tableContent from './TableContent.vue';

    export default {
        components: {
            sidebar,
            tableContent
        }
    }
</script>

<style lang="scss" scoped>
    #content {
        display: grid;
        grid-template-columns: 224px 1fr;
    }
</style>