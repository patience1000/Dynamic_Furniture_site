<script setup>
</script>

<template>
   <body style="background-color: #f2f2f2">
        <!-- Furniture slide -->
        <div class="Sale" style="background-image=">
            <marquee><h2>Buy at affordable prices</h2></marquee>
            <div class="switch-btn">
                <button class="sale2-btn" onclick="Show2()">Prev</button>
                <button class="sale1-btn" onclick="Show1()">Next</button>
            </div>
            <div id="div1">
                <div class="sale1">
                    <div class="sale1-section">
                        <img v-for="img in sale1" v-bind:src="img"/>
                        <h3>Palour Sofa</h3>
                        <p>Type: yellow sofa</p>
                        <p>Price: $350</p>
                        <p>Quantity: <input type="number" placeholder="0"></p>
                        <div class="line"></div>
                        <button><a href="#">Add to cart</a></button>
                    </div> 
        
                    <div class="sale1-section">
                        <img v-for="img in sale2" v-bind:src="img"/>
                        <h3>White Sofa</h3>
                        <p>Type: white sofa</p>
                        <p>Price: $450</p>
                        <p>Quantity: <input type="number" placeholder="0"></p>
                        <div class="line"></div>
                        <button><a href="#">Add to cart</a></button>
                    </div>
        
                    <div class="sale1-section">
                        <img v-for="img in sale3" v-bind:src="img"/>
                        <h3>Dinning Set </h3>
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
                        <img v-for="img in sale4" v-bind:src="img"/>
                        <h3>Lamp</h3>
                        <p>Type: yellow sofa</p>
                        <p>Price: $450</p>
                        <p>Quantity: <input type="number" placeholder="0"></p>
                        <div class="line"></div>
                        <button><a href="#">Add to cart</a></button>
                    </div> 
        
                    <div class="sale2-section">
                        <img v-for="img in sale5" v-bind:src="img"/>
                        <h3>Loxy Sofa</h3>
                        <p>Type: yellow sofa</p>
                        <p>Price: $450</p>
                        <p>Quantity: <input type="number" placeholder="0"></p>
                        <div class="line"></div>
                        <button><a href="#">Add to cart</a></button>
                    </div>
        
                    <div class="sale2-section">
                        <img v-for="img in sale6" v-bind:src="img"/>
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
            <img v-for="img in images" v-bind:src="img"/>
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
            images:['https://media.architecturaldigest.com/photos/5f4e9c54072307c75638c0f1/1:1/w_1280%2Cc_limit/Screen%2520Shot%25202020-09-01%2520at%25203.08.43%2520PM.png'],
            sale1:['https://images.pexels.com/photos/271648/pexels-photo-271648.jpeg?auto=compress&cs=tinysrgb&w=600'],
            sale2:['https://images.pexels.com/photos/1571472/pexels-photo-1571472.jpeg?auto=compress&cs=tinysrgb&w=600'],
            sale3:['https://images.pexels.com/photos/1571463/pexels-photo-1571463.jpeg?auto=compress&cs=tinysrgb&w=600'],
            sale4:['https://images.pexels.com/photos/1420902/pexels-photo-1420902.png?auto=compress&cs=tinysrgb&w=600'],
            sale5:['https://images.pexels.com/photos/1866149/pexels-photo-1866149.jpeg?auto=compress&cs=tinysrgb&w=600'],
            sale6:['https://images.pexels.com/photos/1420902/pexels-photo-1420902.png?auto=compress&cs=tinysrgb&w=600'],
            sale7:['https://images.pexels.com/photos/1008692/pexels-photo-1008692.jpeg?auto=compress&cs=tinysrgb&w=600']
        }
      }
}
  
</script>

