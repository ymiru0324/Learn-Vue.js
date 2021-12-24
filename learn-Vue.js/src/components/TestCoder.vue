<template>
    <div>
        <p>{{ name }}</p><br>
        <button @click="updateName">Change Name</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
             name: 'Test Coder',
        }
    },

    methods: {
        updateName() {
            this.name = 'Test Coder Updated';
        }
    }
}
</script>

<style scoped>

</style>