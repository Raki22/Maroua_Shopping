<script>
    
    export default {
      name: 'NewsItem',
      props: {
        image: String,
        caption: String,
    },

    
    
    }
    </script>
  
  <template>
    <a href="#">
        
            <div class="card">
            <img  :src=image class="card-img-top">
           
                <p class="card-text">{{caption}}</p>
            
        
        </div>
        
    </a>
  </template>
  
  <style scoped>
.card {
    border-color: transparent;
   
}
.card img{
    border-radius: 10px;
    height: 230px;
}

.card-text {
    color: black;
    font-weight: 600;
    padding-top: 3%;
}
  </style>
  