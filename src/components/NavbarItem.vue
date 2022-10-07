<script>
    
    export default {
      name: 'NavbarItem',
      props: {
        title: String,
        link: String,
    },
    
    }
    </script>
  
  <template>
    <li class="nav-item">
          <a class="nav-link" href="#">{{title}}</a>
    </li>
  </template>
  
  <style scoped>
.nav-link {
    font-size: 16px;
    color: white;
}


  </style>
  