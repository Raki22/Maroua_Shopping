<script>
    import PortfolioItem from './PortfolioItem.vue';
    export default {
      name: 'Portfolio',
      components:{
        PortfolioItem
      },
      props: {
        title: String,
        caption: String,
    },
    
    }
    </script>
  
  <template>
   <div class="section container">
    <h1>Explore Marwa</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Dolor aenean sit feugiat ridiculus quam in.</p>
    <div class="row">
        <div class="col-md-4">
            <PortfolioItem image="src/assets/images/company.png" caption="Explore company" color="#B692F6"/>
        </div>
        <div class="col-md-4">
            <PortfolioItem image="src/assets/images/services.png" caption="Explore services" color="#FDB022"/>
        </div>
        <div class="col-md-4">
            <PortfolioItem image="src/assets/images/future.png" caption="Explore future" color="#F97066"/>
        </div>
    </div>
</div>
  </template>
  
  <style scoped>
.section{
    margin-top: 4%;
}
h1 {
    color: #040C1C;
    font-weight: 700;
}
p {
    width: 58%;
}

  </style>
  