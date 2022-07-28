
<template>
<div class="info-details">
  <div class="image">
    <router-link to="/" class="button-action">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M16 19L9 12L16 5" stroke="#4E4B6F" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </router-link>
        <img src="../assets/cassette2.jpg" alt="https://i.pinimg.com/564x/e8/aa/60/e8aa609b8800a0d69a1aec21afb3b06f.jpg">
  </div>

  <div class="intro">
    <div class="name-color-connection">
      <span id="bio-name"> Melina Veronica, 23  </span> <div id="connection-color"></div>
    </div>
    <p>Fashion Designer at Louis Vuitton <br/>
    69m away</p>
  </div>


  <div class="about">
    <h1 class="title-section">about me</h1>
    <p>
      Hey guys, This is Malena. I’m here to find someone for hookup. I’m not interested in something serious. 
      I would love to hear your adventurous story.
    </p>
    <div class="interest">
      <h1 class="title-section">Interest</h1> 
    </div>
  </div>
</div>

</template>

<style scoped>

.info-details{
  width: 100%;
  display:flex;
  flex-direction: column;
  align-items: center;
  margin-inline: 15px;

}
.title-section{
  text-transform:uppercase;
  font-weight: 600;
  font-size: 18px;
  line-height: 21.92px;
  color:#4E4B6F;
  margin-bottom:12px;
}
.info-details .image .button-action{
  position: absolute;
  margin-left: 4px;
  top: 5%;
  z-index: 1;
  display:flex;
  align-items: center;
  width: 35px;
  height: 35px;
  border-radius:50%;
  border: none;
  background: #FFFFFF;
  box-shadow: 0px 8px 30px rgba(22, 18, 61, 0.12);  
  justify-content: center;

}
.info-details .image .button-action svg {
  width:100%;
}
.info-details .image img{
  width: 390px;
  height: 412px;
  right:0;
  display:flex;
  align-items:center;
  position: relative;
  z-index: 0;
  border-bottom-left-radius: 24px;
}
.intro{
  width:100%;
  max-width: 364px;
  display: flex;
  flex-direction: column;
  margin-top:24px;
  margin-bottom:36px;
  line-height: 29.23px;
  
}
.intro p{
    margin-bottom:8px;

  
}

.name-color-connection{
  display: flex;
  align-items: center;
  margin-bottom: 8px;

}
.intro #connection-color{
  background: #15D374;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  margin-left: 12px;
}

#bio-name{
  font-weight: 600;
  font-size: 24px;
  color: #16123D;
}
p{
  line-height:19.49px;
}
.about p{
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  justify-content:justify;
  max-width: 364px;
}
.about h1,p{
  color:#4E4B6F;
}

.interest{
  margin-top:36px;
}
</style>
