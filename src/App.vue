<template>
  <div>
    <img src="./assets/logo.png" alt="logo">
    <School/>
    <Student/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyList from './components/MyList.vue'
import MyFooter from './components/MyFooter.vue'
export default {
    name:'App',
    components:{
        MyHeader,
        MyList,
        MyFooter
    }
}
</script>

<style>

</style>