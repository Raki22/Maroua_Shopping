<script>
    
    export default {
      name: 'TestimonialItem',
      props: {
        image: String,
        title: String,
        paragraph: String,
        caption: String,
        className: String,
    },

    
    
    }
    </script>
  
  <template>
    
        <div class="carousel-item" :class="className">
            <div class="row">
                <div class="col-md-6">
               <img class="img-box" :src=image />
            </div>
            <div class="col-md-6 rightBloc">
                <h5 class="testimonial">{{title}}</h5>
                <h5 class="overview">{{caption}}</h5>
                <h4 class="paragraph">{{paragraph}}</h4>
                <button type="button" class="btn btn-outline-primary">Read story</button>
            </div>
            </div>
           
         
    
    </div>
        			
		
  </template>
  
  <style scoped>

.paragraph {
    margin-top: 27px;
}
.btn {
    border-color: white;
    color: white;
    margin-top: 32px;
    font-size:12px;
}
.carousel-item {
	color: white;
	font-size: 14px;
	text-align: center;
	overflow: hidden;
	min-height: 340px;

}

.img-box  {
	width: 100%;
    height: 100%;
    border-top-left-radius: 10px;
    border-bottom-left-radius: 10px;
	
}

.testimonial {	
	padding: 30px 0 10px;
}
.carousel .overview {	
	padding-bottom: 5px;
    font-weight: 200;
}

.col-md-6 {
    padding: 0;
}
.rightBloc {
background-color: #47B1A4;
padding-left: 34px;
text-align: left;
border-top-right-radius: 10px;
border-bottom-right-radius: 10px;
padding-bottom: 5%;
}
  </style>
  