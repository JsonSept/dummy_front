<template>

    <nav class="navbar fixed-top navbar-light bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Fixed top</a>
  </div>
  <div class="container-fluid">
    <router-link to="/signup">Signup</router-link> |
           <router-link to="/login">Login</router-link> |
          <router-link to="/">Home</router-link> |
          <router-link to="/about">About</router-link> |
          <router-link to="/store">Store</router-link> |
          <router-link to="/productAdmin">product Admin</router-link> |
           <router-link to="/userAdmin">User Admin</router-link> |
            <router-link to="/editUser">Edit User</router-link> |
            <router-link to="/cart">Cart</router-link> |
          <router-link to="/contact">Contact</router-link> 
  </div>
</nav>


    <!-- <div class="main"> -->
    <!-- <div class="nav1"> -->
        <!-- <nav>
          <router-link to="/signup">Signup</router-link> |
          <router-link to="/login">Login</router-link> |
          <router-link to="/">Home</router-link> |
          <router-link to="/about">About</router-link> |
          <router-link to="/store">Store</router-link> |
          <router-link to="/productAdmin">product Admin</router-link> |
          <router-link to="/userAdmin">User Admin</router-link> |
           <router-link to="/editUser">Edit User</router-link> |
           <router-link to="/cart">Cart</router-link> |
          <router-link to="/contact">Contact</router-link> 
        </nav> -->
    <!-- </div> -->
    <!-- <div class="nav2"> -->
        <!-- <svg id="cart" xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="currentColor" class="bi bi-cart-fill" viewBox="0 0 16 16">
          <path d="M0 1.5A.5.5 0 0 1 .5 1H2a.5.5 0 0 1 .485.379L2.89 3H14.5a.5.5 0 0 1 .491.592l-1.5 8A.5.5 0 0 1 13 12H4a.5.5 0 0 1-.491-.408L2.01 3.607 1.61 2H.5a.5.5 0 0 1-.5-.5M5 12a2 2 0 1 0 0 4 2 2 0 0 0 0-4m7 0a2 2 0 1 0 0 4 2 2 0 0 0 0-4m-7 1a1 1 0 1 1 0 2 1 1 0 0 1 0-2m7 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2"/>
        </svg> -->
    <!-- </div> -->
<!-- </div> -->
</template>
<script>
export default {
    
}
</script>
<style>
body {
    padding-top: 10%;
}
.navbar {
    flex-wrap: nowrap;

}
    /* .offcanvas {
        backdrop-filter: blur(0px) saturate(200%);
    -webkit-backdrop-filter: blur(0px) saturate(200%);
    background-color: rgba(17, 25, 40, 0.83);
    border-radius: 12px;
    border: 1px solid rgba(255, 255, 255, 0.125);
    } */

    .main {
        display:flex;
        text-align: center;
    }
    
#cart {

}
</style>