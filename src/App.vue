<template>
<main>
  <navbar/>
  <sidebar/>
  <dashboard/>
</main>
</template>

<script>
import Sidebar from './components/Sidebar'
import Navbar from './components/Navbar'
const Dashboard = () => import('./components/Dashboard') 

export default {
  components: {
    Navbar,
    Sidebar,
    Dashboard
  }
}
</script>

<style>

</style>
