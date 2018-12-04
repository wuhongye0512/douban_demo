<template>
    <div class="home-view">
        <sub-nav mold="quickNav"></sub-nav>
    </div>
</template>
<script>
import SubNav from '../components/SubNav'
export default {
    name: 'home-view',
    components: { SubNav },
    data() {
        return {}
    },
    created() {
        console.log('home-view')
    }
}
</script>
<style lang="scss" scoped>
    .home-view {
        margin-top: 4.8rem;
    }
</style>


