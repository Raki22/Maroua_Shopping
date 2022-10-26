<script>
    import TestimonialItem from './TestimonialItem.vue';
    export default {
      name: 'Testimonial',
      components: {
        TestimonialItem,
      }
    
    }
    </script>
  
  <template>
   <div class="section container">
         <div class="row col-md-8">
      
            <h1>Join Marwa</h1>
            <p class="caption">Homerun customers share a passion for culture,
            design and innovation. We all agree hiring can be more meaningful and personal.</p>
        </div>
<div id="myCarousel" class="carousel slide" data-ride="carousel">
	<!-- Carousel indicators -->
	<ol class="carousel-indicators">
		<li data-target="#myCarousel" data-slide-to="0" class="active"></li>
		<li data-target="#myCarousel" data-slide-to="1"></li>
		<li data-target="#myCarousel" data-slide-to="2"></li>
	</ol>   
	<!-- Wrapper for carousel items -->
	<div class="carousel-inner">		
		<TestimonialItem className="active"
         image="https://raw.githubusercontent.com/HibaSetti/Maroua-shopping/main/public/images/testimonial.png" 
         title="Lorem ipsum 1." caption="Lorem ipsum."
        paragraph="“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Accumsan, cursus id pellentesque volutpat. Et et vestibulum quisque imperdiet id.”"/>
        <TestimonialItem image="https://raw.githubusercontent.com/HibaSetti/Maroua-shopping/main/public/images/testimonial.png" title="Lorem ipsum 2." caption="Lorem ipsum."
        paragraph="“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Accumsan, cursus id pellentesque volutpat. Et et vestibulum quisque imperdiet id.”"/>
        <TestimonialItem image="https://raw.githubusercontent.com/HibaSetti/Maroua-shopping/main/public/images/testimonial.png" title="Lorem ipsum 3." caption="Lorem ipsum."
        paragraph="“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Accumsan, cursus id pellentesque volutpat. Et et vestibulum quisque imperdiet id.”"/>

    </div>
	<!-- Carousel controls -->
	<a class="carousel-control-prev" href="#myCarousel" data-slide="prev">
		<i class="fa fa-angle-left"></i>
	</a>
	<a class="carousel-control-next" href="#myCarousel" data-slide="next">
		<i class="fa fa-angle-right"></i>
	</a>
    </div>
    
</div>
  </template>
  
  <style scoped>
.section{
    margin-top: 3%;
    margin-bottom: 3%;
    background-color: #0F2A62;
    border-radius: 10px;
    padding-bottom: 130px;
    padding-right: 102px;
   
}
h1, p {
    color: white;
}
.caption {
    font-size: 1.25rem;
}
.row {
    padding-top: 3%;
    padding-left: 3%;
}
img {
    width: 100%;
    border-radius: 10px;
}
.btn {
    margin-top: 9%;
    font-size: 12px;
}
.col-md-5 {
    margin-left: 8%;
}
/************************************************** */
.carousel-inner {
    border-radius: 10px;
}
#myCarousel {
    margin-top: 40px;
    
}
.carousel-control-prev, .carousel-control-next {
	width: 30px;
	height: 30px;
	border-radius: 50%;
	text-shadow: none;
	top: 107%;
    right: 2%;
    border: 2px solid white;
    opacity: 1;
    
}
.carousel-control-prev i, .carousel-control-next i {
	font-size: 20px;
	margin-right: 2px;
}
.carousel-control-prev {
	left: 5%;
}
.carousel-control-next i {
	margin-right: -2px;
}
.carousel-indicators li, .carousel-indicators li.active {
	width: 11px;
	height: 11px;
	margin: 1px 5px;
	border-radius: 50%;
}
.carousel-indicators li {	
	background: #888;
	border: none;
}
.carousel-indicators li.active {		
	background: white;		
}
.carousel-indicators {
    top: 108%;
}
  </style>
  