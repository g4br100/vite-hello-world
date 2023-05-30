<script>
export default (await import('vue')).defineComponent({
    name: "AppTitle"
})


</script>

<template>
    <h1>La mia prima app con Vite!</h1>

    <p>
        Check out
        <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank">create-vue</a>, the official Vue + Vite
        starter
    </p>
    <p>
        Install
        <a href="https://github.com/vuejs/language-tools" target="_blank">Volar</a>
        in your IDE for a better DX
    </p>
    <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
</template>

<style scoped>
h1 {
    color: red;
}
</style>
