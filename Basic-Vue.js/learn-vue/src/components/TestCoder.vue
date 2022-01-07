<template>
    <div>
        <p>Header</p>
        <slot name="header" :test="test"></slot>
        <p>Body</p>
        <slot></slot>        
        <p>footer</p>
    </div>
</template>

<script>
export default {
    props: {
        title: {
            type: String,
            default: 'default title'
        },
        name: {
            type: String,
            default: 'default name'
        }
    },
    data() {
        return {
            test: 'coder'
             // name: 'Test Coder',
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