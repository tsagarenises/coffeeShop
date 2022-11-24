<template>
  <div class="bodycontent">
    <div class="carousel">
      <div class="carousel-inner"  v-show="currentSlide===index"> 
        <div class="carousel-item" v-for="(slide,index) in slides" 
          :slide="slide" 
          :key="`item-${index}`" 
          :current-slide="currentSlide" 
          :index="index"
          >
          <img :src="slide"/>
        </div>
        </div>
      </div>
    
    </div>
</template>
<script>

export default {
  name:'SliderComponent',
  data(){
    
    return {
      index:0,
      currentSlide:0,
      slideInterval:null,
      slides:[
        "https://www.pumpernickels.ca/fck_upload/banners/banner-20210929110210-82.jpg",
        "https://www.pumpernickels.ca//fck_upload/banners/banner-20210922142240-94.jpg",
        // "https://www.pumpernickels.ca/fck_upload/banners/banner-20211206120031-89.jpg",
    ]
    }
    
  },

  methods:{
     setCurrentSlide(index){
      this.currentSlide=index;
    }
  },
  mounted(){
    this.slideInterval = setInterval(()=>{
      const index = this.currentSlide < this.slides.length -1 ? this.currentSlide +1 : 0;
      this.setCurrentSlide(index);
    }, 2000)
  },
  beforeUnmount(){
    clearInterval(this.slideInterval);
  }
  
}

</script>
<style >
.carousel{
  background:url(https://www.pumpernickels.ca/images/back_body.jpg) repeat;
  display: flex;
  justify-content: center;
  width:100%;
  height: 900px;
 }  
 .carousel-inner{
  position: relative;
  width:100%;
  height: 900px;
  overflow: hidden;
}
.carousel-item{
  position: absolute;
  top:0;
  bottom: 0;
  left: 0;
  right: 0;
}
/* slider end */

</style>