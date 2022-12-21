<script setup>
</script>

<template>
   <body style="background-color: #f2f2f2">
        <!-- Furniture slide -->
        <div class="Sale">
            <marquee><h2>Buy at affordable prices</h2></marquee>
            <div class="switch-btn">
                <button class="sale2-btn" onclick="Show2()">Prev</button>
                <button class="sale1-btn" onclick="Show1()">Next</button>
            </div>
            <div id="div1">
                <div class="sale1">
                    <div class="sale1-section">
                        <img src="images/images (8).jfif">
                        <h3>Palour Sofa</h3>
                        <p>Type: yellow sofa</p>
                        <p>Price: $350</p>
                        <p>Quantity: <input type="number" placeholder="0"></p>
                        <div class="line"></div>
                        <button><a href="#">Add to cart</a></button>
                    </div> 
        
                    <div class="sale1-section">
                        <img src="images/pexels-vecislavas-popa-1571470.jpg">
                        <h3>White Sofa</h3>
                        <p>Type: white sofa</p>
                        <p>Price: $450</p>
                        <p>Quantity: <input type="number" placeholder="0"></p>
                        <div class="line"></div>
                        <button><a href="#">Add to cart</a></button>
                    </div>
        
                    <div class="sale1-section">
                        <img src="images/download (9).jfif">
                        <h3>Blue Sofa</h3>
                        <p>Type: yellow sofa</p>
                        <p>Price: $450</p>
                        <p>Quantity: <input type="number" placeholder="0"></p>
                        <div class="line"></div>
                        <button><a href="#">Add to cart</a></button>
                    </div>    
                </div>    
            </div>

            <div id="div2">
                <div class="sale2">
                    <div class="sale2-section">
                        <img src="src\assets\pexels-eneida-nieves-1112598.jpg" alt="">
                        <h3>Lamp</h3>
                        <p>Type: yellow sofa</p>
                        <p>Price: $450</p>
                        <p>Quantity: <input type="number" placeholder="0"></p>
                        <div class="line"></div>
                        <button><a href="#">Add to cart</a></button>
                    </div> 
        
                    <div class="sale2-section">
                        <img src="src\assets\pexels-houzlook-com-3356416.jpg" alt="">
                        <h3>Loxy Sofa</h3>
                        <p>Type: yellow sofa</p>
                        <p>Price: $450</p>
                        <p>Quantity: <input type="number" placeholder="0"></p>
                        <div class="line"></div>
                        <button><a href="#">Add to cart</a></button>
                    </div>
        
                    <div class="sale2-section">
                        <img src="src\assets\pexels-eneida-nieves-1112598.jpg" alt="">
                        <h3>Ankara Sofa</h3>    
                        <p>Type: yellow sofa</p>
                        <p>Price: $450</p>
                        <p>Quantity: <input type="number" placeholder="0"></p>
                        <div class="line"></div>
                        <button><a href="#">Add to cart</a></button>
                    </div>
                </div>
            </div>  
        </div>
        <div id="about-section">
        <div class="abt-txt">
            <h1>About Us</h1>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eum quos dicta,min<br>Da ipsam ut tenetur doloremque suscipit consequatur nobis quis.</p>
            <div class="point">
               
                <div class="points">
                    <div class="circle">P</div>
                    <h4>PROFFESIONAL TEAM</h4>
                </div>
                <p>Lorem ipsum,dolor sit amet consectetur adipisicing <br> consequatur nobis.</p>

                <div class="points">
                    <div class="circle">E</div>
                    <h4>EXPERT ADVICE</h4>
                </div>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing <br> consequatur nobis.</p>
                
                <div class="points">
                    <div class="circle">C</div>
                    <h4>CREATIVE IDEAS</h4>
                </div>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing <br> consequatur nobis.</p>

            </div>
            
        </div>
        <div class="abt-img">
            <img v-bind:src="AppImage">
        </div>          
      </div>          
   </body>
</template>
  
<script>
    export default {
      name: "App",
      data(){
        return{
            App: '',
            AppImage: require("../assets/Images/pexels-lisa-fotios-1957477.jpg/pexels-lisa-fotios-1957477.jpg")
        }
      }
}
  
</script>

