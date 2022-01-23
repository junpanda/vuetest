<template>
  <div>
    <div class="bg-light">
      <a href="#" class="text-dark">회원가입시 5,000원 할인쿠폰 지급!</a>
    </div>
    <nav class="d-flex justify-content-between pt-2">
      <div>
        <ul class="nav">
          <li class="nav-item">
             <a href="#" class="nav-link text-secondary">Brand</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link text-secondary">+Bookmark</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link text-secondary">+PCIcon</a>
          </li>
        </ul>
      </div>
      <div>
        <ul class="nav">
          <li class="nav-item">
            <a href="#" class="nav-link text-secondary">Login</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link text-secondary">Join</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link text-secondary">Mypage</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link text-secondary">Order</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link text-secondary">Cart</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link text-secondary">Icon</a>
          </li>
        </ul>
      </div>
    </nav>
    <header class="pt-3 pb-2">
      <a href="#">
        <img src="./assets/ALIGN.png">
      </a>
    </header>
    <hr style="border:0; height:3px; background: #ccc; ">
    <nav>
      <ul class="nav nav-fill">
        <li class="nav-item">
            <a href="#" class="nav-link text-dark">Vest</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link text-dark">Bottoms</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link text-dark">Tops</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link text-dark">Accessory</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link text-dark">Event</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link text-dark">Best Item</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link text-dark">New Item</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link text-dark">Community</a>
        </li>
      </ul>
    </nav>
    <hr style="border:0; height:2px; background: #ccc; ">
    <section>
      <div>
        <a href="#">
          <img src="./assets/mainImg1.jpg" id="bannerImage">
        </a>
      </div>
      <div class="d-flex justify-content-center pt-3">
        <div>
          <a href="#">
            <img src="./assets/mainBanner1.jpg" >
          </a>
        </div>
        <div>
          <a href="#">
            <img src="./assets/mainBanner2.jpg" >
          </a>
        </div>
        <div>
          <a href="#">
            <img src="./assets/mainBanner3.jpg" >
          </a>
        </div>
      </div>
      <div class="pt-4">
        <div>WEEKLY ITEM</div>
        <div>
          <ul class="nav justify-content-center">
            <li class="nav-item">
              <a href="#" class="nav-link text-dark">Outer</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link text-dark">Knit</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link text-dark">Top</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link text-dark">Bottom</a>
            </li>
          </ul>
        </div>
        <div class="d-flex justify-content-center">
          <div >
            <img src="./assets/03.jpg" style="width:200px" >
          </div>
          <div >
            <img src="./assets/04.jpg" style="width:200px">
          </div> 
          <div >
            <img src="./assets/05.jpg" style="width:200px" >  
          </div> 
          <div >
            <img src="./assets/06.jpg" style="width:200px" >  
          </div> 
          <div >
            <img src="./assets/07.jpg" style="width:200px">  
          </div>  

        </div>
      </div>
    </section>
    <footer></footer>
  </div>

  
</template>

<script>


export default {
  name: 'App',
  data(){
    return{
    }
  },
  components: {
  
  }

//   methods:{
//     change() {
//   var bannerImages = ['./assets/mainImg1.jpg','./assets/mainImg2.jpg','./assets/mainImg3.jpg'];
//   var i = 0; 
//   var bannerImage_id = document.getElementById("bannerImage");
// 0
//   bannerImage_id.setAttribute("src","bannerImages[i]");
//   i++;
//   if(i == 3) {
//     i = 0;
//   }
// },
// setInterval(change,3000){}

//   }
}



</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
</style>
