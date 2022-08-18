<template>
    <div id="app">
        <home-head></home-head>
        <home-body></home-body>
    </div>
</template>

<script>
import HomeHead from "./components/HomeHead.vue";
import HomeBody from "./components/HomeBody.vue";
export default {
    components: {
        'HomeHead':HomeHead,
        'HomeBody':HomeBody
    }
}
</script>

<style></style>