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
    <div class="navbar-brand"></div>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
  
      <li class="nav-item dropdown">
          <a class="nav-link" aria-expanded="false">
            Explore our company
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">About us</a></li>
            <li><a class="dropdown-item" href="#">Where we are</a></li>
            <li><a class="dropdown-item" href="#">Founded story</a></li>
          </ul>
        </li>
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
  padding-top: 15px;
  padding-bottom: 15px;
}
.container-fluid {
  width: 96%;
}
.nav-link {
    font-size: 16px;
    color: white;
    cursor: pointer;
}
.dropdown:hover .dropdown-menu{
        display: block;
    }
.navbar:hover {
  background-color: white;
}

.navbar-brand {
  background-image: url('@/assets/logo.png');
  width: 87px;
  background-repeat: no-repeat;
  height: 58px;
}
.navbar:hover .navbar-brand{
  background-image: url('@/assets/logo2.png');
}
.navbar-collapse{
  margin-bottom: 9px;
}
.navbar:hover .btn {
  background-color: #2A6AE8;
  color: white;
}
</style>
    