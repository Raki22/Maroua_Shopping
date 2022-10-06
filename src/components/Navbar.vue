<script>
   import NavbarItem from './NavbarItem.vue';
   export default {
      name: 'Navbar',
      components: {
        NavbarItem
    },
    
    }
</script>
    
    <template>
  <nav class="navbar navbar-expand-lg">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"><img src="@/assets/logo.png" alt=""></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
      <NavbarItem title="Explore our company"/>
      <NavbarItem title="Services"/>
      <NavbarItem title="How it works"/>
      <NavbarItem title="Resources"/>
      <NavbarItem title="Blog"/>
      <NavbarItem title="Help"/>
      <NavbarItem title="Contact Us"/>

      
      </ul>
      <form class="d-flex">
        
        <button type="button" class="btn btn-light">Log in</button>
      </form>
    </div>
  </div>
</nav>
    </template>
<style scoped>  
.btn {
  color: #2A6AE8;
    font-size: 16px;
    font-weight: 600;
} 
.btn:hover {
  background-color: #2A6AE8;
  color: white;
  border-color: #2A6AE8;
}
.navbar-nav {
  margin-left: 19px;
}
.navbar {
  padding-top: 20px;
}
.container-fluid {
  width: 96%;
}
</style>
    