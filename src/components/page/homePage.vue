<template>
<div class="container">
    <div class="sidebar">
        <sidebar/>
    </div>
    <div class="content"><contentPage/></div>
    <div class="profile">profile</div>
</div>

</template>

<script>
import sidebar from '../component/sideBar.vue'
import contentPage from '../component/contentPage.vue'

export default {
 components:{
    sidebar,
    contentPage
 }
}
</script>

<style src="../css/style.css">

</style>