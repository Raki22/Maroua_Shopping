<script>
    export default {
      name: 'WaitingFor',
     
    
    }
    </script>
  
  <template>
   <div class="section">
    <h1>What are you waiting for?</h1>
    <div class="wrapper">
        
        <div class="col-md-2">
            <div class="card">
                <img  src="/images/doc1.png" class="card-img-top">
           
                <p class="card-text">Lorem ipsum dolor.</p>
            
            </div>

        </div>
        <div class="col-md-2">
            <div class="card">
                <img  src="/images/doc2.png" class="card-img-top">
           
                <p class="card-text">Lorem ipsum dolor.</p>
            
            </div>
        </div>
        <div class="col-md-2">
            <div class="card" style="border-right:0;">
                <img  src="/images/doc3.png" class="card-img-top">
           
                <p class="card-text">Lorem ipsum dolor.</p>
            
            </div>
        </div>
    </div>
    <div class="col-md-3">
        <button type="button" class="btn btn-primary btn-lg">Come to join us</button>
    </div>
   
    </div>
  </template>
  
  <style scoped>
.section{
    background-color: #F9FAFB;
    padding-bottom: 100px;
}
.wrapper {
    display: inline-flex;
    justify-content: center;
    width: 100%;
    padding-top: 6%;
}
.card {
    border-color: transparent;
    background-color: transparent;
   text-align: center;
   border-right: 2px solid #98A2B3;
    border-radius: 0;
}
.card img {
    width: 35%;
    margin: 0 auto;
}
.col-md-2 {
    margin-right: 9%;
}
.card-text {
    font-weight: 600;
}
h1 {
    text-align: center;
    padding-top: 5%;
}
.btn {
    margin-top: 25%;
    font-size: 18px;
}
.col-md-3 {
    margin: 0 auto;
    text-align: center;
}
  </style>
  