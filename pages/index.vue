<template>
  <!--<div class="background" :style="{ backgroundImage: `url(${backgroundUrl})` }">-->
  <div>
    <Nav>
    </Nav>
    <div class="main-body">
    <h1 class="home-title">I'm Seppe</h1>
    <h2 class="home-title">A young FullStack Developer & Electronics Engineer</h2>
    <h1 class="home-title">Welcome to my page.</h1>
    </div>
    <div class="download-resume-button-div">
      <b-button class="download-resume-button" variant="outline-light" size="lg">Download Resume</b-button>
    </div>
    <div class="social-media-div">
       <h4 class="social-media-title">Find me on</h4>    
    </div>
    <div class="social-media-icons-div">       
        <a class="social-media-icon" href="https://www.linkedin.com/in/seppe-geerinckx-30b236156/">
          <font-awesome-icon :icon="{ prefix: 'fab', iconName: 'linkedin' }" style="color: #0072b1; font-size: 72px;"/>
        </a>
        <a class="social-media-icon" href="https://github.com/ClumsyPenguin">
          <font-awesome-icon :icon="{ prefix: 'fab', iconName: 'github' }" style="color: #FFFFFF; font-size: 72px;"/>
        </a>
        <a class="social-media-icon" href="https://gitlab.com/ClumsyPenguin">
          <font-awesome-icon :icon="{ prefix: 'fab', iconName: 'gitlab' }" style="color: #FC6D26; font-size: 72px;"/>
        </a>
       </div>
       <div class="download-resume-button-div">
         <b-button class="download-resume-button" variant="outline-light" style= "margin-top: 2em;" size="lg"><a style= "color: white" href="mailto:geerinckxseppe@gmail.com">HIRE ME</a></b-button>
       </div>
  </div>
</template>

<script>
import backgroundUrl from '~/assets/back.jpg'
export default {
  data() {
    return { backgroundUrl }
  }
}
</script>

<style>
.social-media-icon{
  margin-right: 1em;
}
.social-media-icons-div{
  margin-top: 2em;
  display: flex;
  justify-content: center;
  
}
.social-media-div{
  display: flex;
  justify-content: center;
  margin-top: 6em;
}
.social-media-title{
  color: white;
}
  .home-title{
    display: flex;
    justify-content: center;
    color: white;
  }
.background-image{
  opacity: 0.3;
}
.download-resume-button-div{
   display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 2em;
}
</style>
