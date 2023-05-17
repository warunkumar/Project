<template>
  <BankDashboard/>
  <CustomerRegistration/>
</template>

<script>
import BankDashboard from './components/BankDashboard.vue'
import Login from './components/Login.vue'
import CustomerRegistration from './components/CustomerRegistration.vue'

export default {
  name: 'App',
  components: {
    BankDashboard,
    Login,
    CustomerRegistration
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
