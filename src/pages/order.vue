<template>
    <nav-header></nav-header>
    <router-view></router-view>
    <nav-footer></nav-footer>
</template>

<script type="text/ecmascript-6">
    import NavHeader from '../components/NavHeader'
    import NavFooter from "../components/NavFooter"

    export default {
        name:'order',
        components: {
            NavHeader,
            NavFooter
        }
    }
</script>
