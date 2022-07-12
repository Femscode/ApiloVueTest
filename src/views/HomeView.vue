<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <Signin v-if='!ShowS' @signIn = 'Chatroom'/>

    <p v-if='!ShowS'>Registered already? <span @click="ShowS = !ShowS" class="red">Click here</span> to log in</p>
   
    <Login v-if='ShowS' @login="Chatroom"/>
  
  
    <p v-if='ShowS'>Yet to register ? <span @click="ShowS = !ShowS" class="red">Click here</span> to sign up</p>
   
  
  </div>
</template>

<script>
// @ is an alias to /src
import Signin from '@/components/Signin.vue'
import Login from '@/components/Login.vue'
import { ref } from '@vue/reactivity'
import { useRouter } from 'vue-router'
export default {
  name: 'HomeView',
  components: {
    Signin,
    Login,
  
},
setup() {
  const ShowS = ref(true)
  const router = useRouter()
  const Chatroom = () => {
    router.push({name:'chatroom'})
  }
  
  return { ShowS, Chatroom }
}
}
</script>
<style>
.red {
  color:red;
  cursor:pointer;
}
</style>
