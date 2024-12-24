<template>
    <div>
        <h2>Simple Interpolation</h2>
        <p>{{ message }}</p>
        <p>{{ contador }}</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            message: 'Hello, Vue 3!',
            contador:2
        };
    }
}
</script>