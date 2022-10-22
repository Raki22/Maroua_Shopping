<script>
    export default {
      name: 'Portfolio',
    }
    </script>
  
  <template>
   <div class="section container">
    <h1>Explore Marwa</h1>
    <p class="caption">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Dolor aenean sit feugiat ridiculus quam in.</p>
    <div class="row">
        <div class="col-md-4">
          <a href="#">       
              <div class="card company">
                  <img  src="https://raw.githubusercontent.com/HibaSetti/Maroua-shopping/main/public/images/company.png" class="card-img-top">
                  <div class="card-body">
                    <p class="card-text">Explore company</p>
                  </div>
                     
              </div>   
          </a>
        </div>
        <div class="col-md-4">
          <a href="#">       
              <div class="card services">
                  <img  src="https://raw.githubusercontent.com/HibaSetti/Maroua-shopping/main/public/images/services.png" class="card-img-top">
                  <div class="card-body">
                  <p class="card-text">Explore services</p>   
                  </div>
              </div>   
          </a>
        </div>
        <div class="col-md-4">
          <a href="#">       
              <div class="card future">
                  <img  src="https://raw.githubusercontent.com/HibaSetti/Maroua-shopping/main/public/images/future.png" class="card-img-top">
                  <div class="card-body">
                    <p class="card-text">Explore future</p>   
                  </div>
              </div>   
          </a>
        </div>
    </div>
</div>
  </template>
  
  <style scoped>
.section{
    margin-top: 4%;
}

.caption {
    width: 58%;
}
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
.company .card-body{
  background-color: #B692F6;
}
.services .card-body {
  background-color:#FDB022 ;
}
.future .card-body {
  background-color: #F97066;
}
.services:hover .card-body {
  background-color: #f9a202;
}
.company:hover .card-body {
  background-color: #7531f0;
}
.future:hover .card-body {
  background-color: #f41d0e;
}
  </style>
  