<template>
  <body>   
    <div class="home" id="home">
     <h5 >Hi there, I am</h5>
     <h1>Lindokuhle Mgoqi</h1>
     <button type="button" id="#about" class="btn btn-outline-light">About</button>
    </div>
    <div class="about" id="about">
      <div class="col">
<img class="abt-img" src="https://i.postimg.cc/L8PtvR4W/My-project-1-45.png" alt="">
      </div>
      <div class="col me">
        <h6>About</h6>
        <p> I was born in 2002 on the 25 of December, I was born and raised in Cape Town, South Africa.
          I am a Web Development Student currently studying at Life Choices Academy and I matriculated in 2021 at Maitland High School.
          I am a humble young man who was raised by a single mother, living with my uncle and aunt. In my spare time, I love drawing and I'm also a music
          producer. I am a passionate individual who is always up and ready to find new innovative ideas and ways to better
          my craft and as we all know, Technology is the future so our job is to find new, better ways to come out on top!
</p>
      </div>
    </div>
    <div class="resume" id="resume">

    </div>
  </body>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
body{
  font-family: 'Archivo Narrow', sans-serif;
  background-image: url(https://i.postimg.cc/8cf8Rnvd/pexels-adrien-olichon-2387793.jpg);
  background-size: cover; 
  background-position: center;
  color: white;
}
.home{
height: 100vh;
}
.about{
  height: 100vh;
 
  display: flex;
  background-color: rgba(255, 255, 255, 0.436);
  width: 100vw;
}
.me{
}
.abt-img{
width: 35rem;
margin: auto;

}
h5{
  width: 200px;
  margin-top: 200px;
  margin-left: 436px;
}
h6{
  font-size: 85px;
  margin-top: 150px;
  text-align: start;
  color: rgba(49, 47, 47, 0.384);
}
h1{
  font-size: 85px;
}
p{
  width: 40rem;
  font-size: 20px;
  color: black;
  word-wrap: break-word;
}
button{
  margin-top: 2rem;
  width: 7rem;
  height: 2.5rem;
}
.resume{
  height: 100vh;
}
</style>
