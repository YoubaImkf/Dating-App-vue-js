<template>
    <div class="img-top-nav">
      <nav>
        <ul>
          <li><router-link to="/" ><img alt="user logo" class="logo" src="@/assets/gridicons_user.svg"/></router-link></li>
          <li><router-link to=""><img alt="Vue logo" class="logo" src="@/assets/For-You.svg"  /></router-link></li>
          <li><router-link to=""><img alt="Vue logo" class="logo" src="@/assets/ion_chatbubble-ellipses.svg"  /></router-link></li>
        </ul>
      </nav>
    </div>
    <div class="container">
      <div class="home-img">
        <img src="../assets/cassette-bleu.jpg" alt="">
        <div class="bio-img">
          <div class="bio-span">
            <router-link to="/about">
            <span id="bio-name"> Melina Veronica, 23</span>
            <span id="bio-info"> Fashion Designer at Louis Vuitton</span>
            </router-link>
          </div>
        </div>
      </div>

      <section class="like-section">
          <button class="button-action">
            <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M18.6661 15.877L12.7861 10L18.6661 4.12295C18.8529 3.94223 19.002 3.72623 19.1046 3.48746C19.2076 3.24799 19.2618 2.99042 19.2641 2.72978C19.2663 2.46914 19.2166 2.21067 19.1179 1.96944C19.0191 1.72822 18.8732 1.50907 18.6888 1.3248C18.5044 1.14052 18.2851 0.994802 18.0437 0.896131C17.8024 0.797459 17.5438 0.74781 17.283 0.750074C17.0222 0.752338 16.7645 0.806471 16.5249 0.909319C16.286 1.01187 16.0698 1.16081 15.889 1.3475L10.0062 7.22396L4.12517 1.34751C3.9443 1.16082 3.72813 1.01187 3.48921 0.909319C3.2496 0.806471 2.99189 0.752338 2.73113 0.750074C2.47037 0.74781 2.21177 0.797459 1.97041 0.896131C1.72904 0.994802 1.50975 1.14052 1.32533 1.3248C1.14091 1.50908 0.995054 1.72822 0.896283 1.96944C0.797512 2.21067 0.747808 2.46914 0.750074 2.72978C0.752341 2.99042 0.806534 3.24799 0.909485 3.48746C1.01214 3.72625 1.16122 3.94227 1.34806 4.123L7.22885 9.99917L1.34807 15.877C1.16123 16.0577 1.01214 16.2737 0.909485 16.5125C0.806534 16.752 0.752341 17.0096 0.750074 17.2702C0.747808 17.5309 0.797512 17.7893 0.896283 18.0306C0.995054 18.2718 1.14091 18.4909 1.32533 18.6752C1.50975 18.8595 1.72904 19.0052 1.97041 19.1039C2.21177 19.2025 2.47037 19.2522 2.73113 19.2499C2.9919 19.2477 3.2496 19.1935 3.48921 19.0907C3.72814 18.9881 3.94431 18.8392 4.12519 18.6525L10.0062 12.776L15.889 18.6525C16.0698 18.8392 16.286 18.9881 16.5249 19.0907C16.7645 19.1935 17.0222 19.2477 17.283 19.2499C17.5438 19.2522 17.8024 19.2025 18.0437 19.1039C18.2851 19.0052 18.5044 18.8595 18.6888 18.6752C18.8732 18.4909 19.0191 18.2718 19.1179 18.0306C19.2166 17.7893 19.2663 17.5309 19.2641 17.2702C19.2618 17.0096 19.2076 16.752 19.1046 16.5125C19.002 16.2738 18.8529 16.0578 18.6661 15.877Z" fill="#A29FBE" stroke="#A29FBE" stroke-width="0.5"/>
            </svg>
          </button>  
          <button class="button-action">
            <svg width="19" height="18" viewBox="0 0 19 18" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M14.7112 17.9954C14.5596 17.996 14.4101 17.9602 14.2753 17.8912L9.44217 15.3629L4.60909 17.8912C4.45215 17.9736 4.2752 18.0105 4.09837 17.9974C3.92153 17.9844 3.7519 17.9221 3.60876 17.8175C3.46562 17.713 3.3547 17.5704 3.28863 17.406C3.22255 17.2415 3.20396 17.0619 3.23497 16.8875L4.18264 11.5563L0.278262 7.76863C0.156447 7.64716 0.0700337 7.49484 0.0282949 7.32802C-0.0134439 7.1612 -0.00893197 6.98616 0.0413464 6.82171C0.0962729 6.65342 0.197309 6.50388 0.33299 6.39006C0.468671 6.27625 0.633563 6.20271 0.808954 6.1778L6.21064 5.39186L8.58928 0.534167C8.66688 0.37407 8.78804 0.239052 8.93888 0.144579C9.08972 0.0501064 9.26415 0 9.44217 0C9.6202 0 9.79462 0.0501064 9.94547 0.144579C10.0963 0.239052 10.2175 0.37407 10.2951 0.534167L12.7021 5.38239L18.1038 6.16833C18.2792 6.19324 18.4441 6.26678 18.5798 6.38059C18.7155 6.49441 18.8165 6.64395 18.8714 6.81224C18.9217 6.97669 18.9262 7.15173 18.8845 7.31855C18.8427 7.48537 18.7563 7.63769 18.6345 7.75916L14.7301 11.5468L15.6778 16.878C15.7116 17.0555 15.6939 17.239 15.6268 17.4068C15.5596 17.5746 15.4458 17.7197 15.2987 17.8249C15.1271 17.9451 14.9205 18.005 14.7112 17.9954Z" fill="#4DD5FF"/>
            </svg>
          </button>  

          <button class="button-action">
            <svg width="27" height="25" viewBox="0 0 27 25" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M23.899 2.30419C23.1741 1.57473 22.3121 0.995633 21.3624 0.600198C20.4127 0.204763 19.3942 0.000787691 18.3654 0C16.4194 0.000317857 14.5445 0.730764 13.1118 2.04671C11.6793 0.730542 9.80427 6.11564e-05 7.85821 0C6.82819 0.00107157 5.80854 0.205669 4.85795 0.602018C3.90736 0.998366 3.0446 1.57864 2.31932 2.30945C-0.774202 5.41367 -0.772888 10.269 2.32195 13.3601L13.1118 24.1415L23.9017 13.3601C26.9965 10.269 26.9978 5.41367 23.899 2.30419Z" fill="#FF636B"/>
            </svg>
          </button>   
      </section>
    </div>
</template>

<style scoped> 
.img-top-nav nav ul{
  display:flex;
  justify-content: space-between;
  margin-inline: 26px;
  margin-top: 40px;
}

.container{
  width:100%;
  display:flex;
  flex-direction:column;
}

.home-img {
  width:100%;
  display:flex;
  flex-direction: column;
  align-items: center;
}
.home-img img{
  display: flex;
  max-width: 366px;
  max-height: 622px;
  border-radius: 24px;
  margin-inline: 26px; /*bug stay on left when resize*/
  margin-top: 48px;
  position: relative;
  align-items: center;
}

.bio-img{
  background-color: #ffffffad;
  width: 342px;
  height: 104px;
  border-top-left-radius:  24px;
  border-bottom-left-radius: 24px;
  position: absolute;
  margin-left: 64px;
  top: 73%;
} 
.bio-img span{
  line-height: 29px;
  display: flex;
  flex-direction: column;
  margin-left:24px;
}
.bio-span{
  margin-top:24px;
}

#bio-name {
  font-size: 24px;
  font-weight: 600px;
  color: #16123D;
}
#bio-info{
  color: #4E4B6F;
}
.like-section {
  width: 100%;
  top: 88%;
  /* margin-top: 20px;
  margin-bottom:40px; */
  display: flex;
  justify-content:space-around;
  position: absolute;
}
.button-action{
  display:flex;
  align-items: center;
  width: 64px;
  height: 64px;
  border-radius:50%;
  border: none;
  background: #FFFFFF;
  box-shadow: 0px 8px 30px rgba(22, 18, 61, 0.12);  
}
.button-action svg{
  width:100%;
}
.button-action:hover{
  cursor:pointer;
}
</style>

