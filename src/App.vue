<template>
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat&family=Poppins:wght@300&display=swap" rel="stylesheet">
  <h1> Rawr!</h1>
  <img alt="Adi dino" src="./assets/Adi-dino.png" />
  <div class="comeplay">
  <HelloWorld msg="My name is Adrian and I am a dinosaur!" />
</div>
  <div class="container-flex">
    <div>
  <img alt="Cute dragon" src="./assets/Dragon-cute.png" frameBorder="0"/>
  </div>
  <div>
    <iframe src="https://giphy.com/embed/eiScB95a2SM5th8Phy" width="340" height="100%" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>
  </div>
  <div>
  <iframe alt="dino" src="https://giphy.com/embed/Klksn4bTIvTmSLxw2u" width="420" height="420" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>
  </div>
  <div>
  <img alt="Tri Tops" src="./assets/Tri-tops.png" frameBorder="0"/>
  </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>

body {
  font-family: 'Poppins', sans-serif;
}

p {
  font-family: 'Poppins', sans-serif;
}

h1 {
  color: rgb(135, 35, 135);
  text-align: center;
  text-shadow: 8px 8px 8px rgba(28, 1, 15, 0.65);
  font-size: 42px;
  font-family: 'Poppins', sans-serif;
  
}

h2 {
  font-family: 'Poppins', sans-serif;
}

.First-sentence {
  color:brown;
  font-size: 17px;
}

.Second-sentence {
  color: green;
  font-size: 18px;
  font-weight: bold;
}

.comeplay {
  font-size: 24px;
}

button {
  cursor: pointer;
  font-size: 18px;
  color: white;
  background: rgb(123,19,234);
  background: radial-gradient(circle, rgba(123,19,234,1) 11%, rgba(227,42,204,1) 95%);  
  border-radius: 6px;
  line-height: 18px;
  padding: 8px;
  font-family: 'Poppins', sans-serif;
}

.container-flex {
  display: flex;
}

</style>
