<template>
    <main>
        <h2>This is main</h2>
        <CardComponent />
    </main>
</template>

<script>
import CardComponent from './CardComponent.vue';
    export default {
        name: 'MainComponent',
        components: {
            CardComponent
        }
    }
</script>

<style lang="scss" scoped>

</style>