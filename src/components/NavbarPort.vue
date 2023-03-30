<template>
    <nav class="navbar navbar-expand-lg p-0">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><img src="https://i.postimg.cc/Z5gRZr5Q/My-project-1-43.png" alt=""></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav m-auto">
              <li class="nav-item"><router-link :to="{path: '/', hash: '#home'}">Home</router-link></li>
              <li class="nav-item"><router-link :to="{path: '/', hash: '#about'}">About</router-link></li>
              <li class="nav-item"><router-link :to="{path: '/', hash: '#resume'}">Resume</router-link></li>
              <li class="nav-item"><router-link :to="{path: '/', hash: '#projects'}">Projects</router-link></li>
              <li class="nav-item"><router-link :to="{path: '/', hash: '#testimonials'}">Testimonials</router-link></li>             
              <li class="nav-item"><router-link :to="{path: '/', hash: '#contact'}">Contact</router-link></li>
                  
            </div>
          </div>
        </div>
      </nav>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
img{

  width: 3.5rem;
  margin: auto;
}
.container-fluid{
background-color: rgba(0, 0, 0, 0.918);
}
.navbar-nav a{
text-decoration: none;
}
.button{
 color: white;
}
.nav-item{
 margin-left: 12px;
 
}
.nav-item:hover{
color: rgb(215, 217, 247);
}
</style>