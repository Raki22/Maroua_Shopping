<script>
    
    export default {
      name: 'PortfolioItem',
      props: {
        image: String,
        caption: String,
        color: String,
    },
    computed: {
        cssVars () {
        return{
          /* variables you want to pass to css */
          '--color': this.color,
        }
    }
}
    
    
    }
    </script>
  
  <template>
    <a href="#">
        <div class="card">
            <img  :src=image class="card-img-top">
            <div class="card-body" :style="cssVars">
                <p class="card-text">{{caption}}</p>
            </div>
        </div>
    </a>
  </template>
  
  <style scoped>

.card-body{
    background-color: var(--color);
    text-align: center;
    border-bottom-right-radius: 10px;
    border-bottom-left-radius: 10px;
}
.card-body p{
    font-weight: 500;
    color: white;
   
}
.card {
    border-color: transparent;
   
}
.card img{
    border-top-right-radius: 10px;
    border-top-left-radius: 10px;
    
}
.card:hover{
     transform: scale(1.05);
}
.card:hover .card-body {
  background-color: #f9a202;
}
  </style>
  