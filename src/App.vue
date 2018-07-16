<template>
 <div class="wrap">
  <Header></Header>
   <div class="body">
     <!--<menu></menu>-->
     <!--<router-view></router-view>-->
   </div>
 </div>
</template>

<script>
  import Body from './components/Body'
  import Header from './components/Header'
  import menu from './components/menu'

export default {
  name: 'App',
  components:{
    Header,
    Body,
    menu
  }

}
</script>

<style scoped>
  @import "./styles/main.css"
 @import './assets/css/animate.css'
 @import './assets/css/font-awesome.min.css'
.wrap{
  display:flex;
  /*flex-wrap: nowrap;*/
  flex-direction: column;
  justify-content: flex-start;
  /*align-items:flex-start;*/
}
Header{

}
 .body{
    display: flex;
  }
</style>
