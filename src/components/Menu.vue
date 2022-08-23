<template>
        <div class="menu">
            <a href="/" class="floatingMenu">
                <i class="fa-solid fa-house"></i>
            </a>

            <a href="/skill" class="floatingMenu">
                <i class="fa-solid fa-list"></i>
            </a>
        </div>
</template>

<script>
    export default {
        name: "Menu",
    };
</script>

<style>
    .menu {
        position: fixed;
        z-index: 1;
        display: flex;
        flex-direction: column;
        gap: 12px;
        margin-left: 23px;
        text-align: center;
        margin-top: -200px;
    }

    .menu a {
        border-radius: 50%;
        font-size: 25px;
        color: black;
        border: 1px solid black;
        padding: 6px 12px;
    }
</style>