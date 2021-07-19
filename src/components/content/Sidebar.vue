<template>
    <div id="sidebar">
        <h2 class="sidebar__text">sidebar</h2>
    </div>
</template>

<style lang="scss" scoped>
    #sidebar {
        background-color: #e2e3e4;
        min-height: calc(100vh - 256px); // Высота всей страницы без учета высот хэдера и футера

        display: flex;
        justify-content: center;
        align-items: center;

        .sidebar__text {
            color: #707070;
            font-size: 36px;
            line-height: 44px;
            font-weight: normal;
            font-style: normal;
            font-family: 'Citymobil_v0-2';
        }
    }
</style>