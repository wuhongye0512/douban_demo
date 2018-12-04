<template>
    <div class="list">

    </div>
</template>

<script>
export default {
    name: 'list',
    prop: {
        mold: {
            type: String,
            default: 'basic'
        },
        items: {
            type: Array,
            required: true
        }
    },
    created() {
        console.log(this.items, 'items')
    }
}
</script>

<style lang="scss" scoped>

</style>
