<script>
    import NewsItem from './NewsItem.vue';
    export default {
      name: 'News',
    components: {
        NewsItem
    }
    }
    </script>
  
  <template>
   <div class="section ">
        <div class="row container">
            <h1>Latest News and Events</h1>
            <a class="seeAll" href="#">See all <i class="fa fa-long-arrow-right" aria-hidden="true"></i></a>
            <div class="col-md-5">
                <img src="src/assets/images/news-cover.png"/>
            </div>
            <div class="col-md-6">
                <h4>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc euismod condimentum gravida aliquet venenatis suspendisse pulvinar tortor sed. Et,
                    hac ac at nisl sed nullam sit gravida. Quam tempus elit, consectetur nibh sodales sed arcu.</p>
        
            </div>
        <hr>
        </div>
        <div class ="row container">
            <div class="col-md-4">
                <NewsItem image="src/assets/images/newsItem1.png" caption="Lorem ipsum dolor sit amet, consectetur adipiscing elit." />

            </div>
            <div class="col-md-4">
                <NewsItem image="src/assets/images/newsItem2.png" caption="Lorem ipsum dolor sit amet, consectetur adipiscing elit." />

            </div>
            <div class="col-md-4">
                <NewsItem image="src/assets/images/newsItem3.png" caption="Lorem ipsum dolor sit amet, consectetur adipiscing elit." />
            </div>
        </div>
    
    </div>
  </template>
  
  <style scoped>
.section {
    padding-bottom: 6%;
}
h4 {
    color: #040C1C;
    font-weight: 500;
    padding-top: 2%;
    padding-bottom: 6%;
}
p {
    color: #475467;
}
.row {
    padding-top: 3%;

}
img {
    width: 100%;
    border-radius: 10px;
}
h1 {
    padding-bottom: 5%;
    width: 50%;
}
.seeAll {
    width: 50%;
    text-align: right;
    padding-top: 20px;
    height: 40px;
}
.seeAll:hover {
    text-decoration: underline;
}
.col-md-6 {
    padding-left: 6%;
}
hr {
    border-top-width: 2px;
    margin-top: 5%;
}

  </style>
  