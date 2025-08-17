<template>
    <div>
        <h1>Hello Vue a Laravelben 🎉</h1>
        <button @click="count++">Klikkelve: {{ count }}x</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            count: 0
        }
    }
}
</script>
