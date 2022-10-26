<script>
    
    export default {
      name: 'Slogan',
      props: {
        title: String,
        caption: String,
    },
    
    }
    </script>
  
  <template>
    <div class="container row">
    <div class="col-md-9 section">
        <h1>{{title}}</h1>
        <p>{{caption}}</p>
        <button type="button" class="btn btn-primary btn-lg">Explore Marwa</button>
    </div>
</div>
  </template>
  
  <style scoped>
h1 {
    font-size: 3.5rem;
    color: white;
}
p {
    font-size: 20px;
    margin-top: 2rem;
    margin-bottom: 3rem;
   
}
.section {
    color: white;
    margin-top: 9%;
   
}
  </style>
  