<template>
    <div class="sub-nav">
        <div class="quickNav">
            <ul class="quick-nav">
                <li>
                    <router-link to="" >影院热映</router-link>
                </li>
                <li>
                    <router-link to="" >欧美新碟版</router-link>
                </li>
                <li>
                    <router-link to="" >注册账号</router-link>
                </li>
                <li>
                    <router-link to="" >登录豆瓣</router-link>
                </li>
            </ul>
        </div>
    </div>
</template>
<script>
export default {
    name: 'sub-nav',
    data() {
        return {}
    },
    created() {
        console.log('kk')
    }
}
</script>
<style lang="scss" scoped>
.sub-nav {
    margin:0 1.8rem;
    padding-top: .2rem;
    .quickNav {
        ul {
            overflow: hidden;
            margin: 1rem 0 0 0;
            padding-top: .6rem;
        }

        li {
            float: left;
            width: 50%;
            padding: .3rem;
            box-sizing: border-box;
            font-size: 1.5rem;
        }

        a {
            display: block;
            max-width: 100%;
            padding: 1.2rem 0;
            line-height: 2rem;
            text-align: center;
            background-color:#f6f6f6;
            color: #494949;
            border-radius: .2rem;
            overflow: hidden;
            text-decoration: none;
            white-space: nowrap;
            word-wrap: normal;
        }
    }
}
</style>



