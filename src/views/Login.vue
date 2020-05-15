<template>
  <div class="row">
   <div class="col-lg-6">
       <Login></Login>
   </div>
   <div class="col-lg-6">
       <Register></Register>
   </div>
  </div>
</template>
<script>

import Login from '../components/Login';
import Register from '../components/Register';
export default {
  name: 'LoginView',
  components: {
    Login,
    Register
  }
}
</script>