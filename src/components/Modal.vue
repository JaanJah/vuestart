<template>
    <div class="modal" :class="{'is-active': open}">
        <div class="modal-background"></div>
        <div class="modal-content">
            <p class="image is-4by3">
                <img src="https://bulma.io/images/placeholders/1280x960.png" alt="">
            </p>
        </div>
        <button class="modal-close is-large" aria-label="close"></button>
    </div>
</template>

<script>
    export default {
        name: "Modal",
        props: ['open']
    }
</script>

<style scoped>
</style>