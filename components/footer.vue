<template>
  <div>
    <svg viewBox="0 0 120 28" data-v-955b2896="">
      <defs data-v-955b2896="">
        <mask id="xxx" data-v-955b2896="">
          <circle cx="7" cy="12" r="40" fill="#fff" data-v-955b2896=""></circle>
        </mask>
        <filter id="goo" data-v-955b2896="">
          <feGaussianBlur
            in="SourceGraphic"
            stdDeviation="2"
            result="blur"
            data-v-955b2896=""
          ></feGaussianBlur>
          <feColorMatrix
            in="blur"
            mode="matrix"
            values="
         1 0 0 0 0  
         0 1 0 0 0  
         0 0 1 0 0  
         0 0 0 13 -9"
            result="goo"
            data-v-955b2896=""
          ></feColorMatrix>
          <feBlend in="SourceGraphic" in2="goo" data-v-955b2896=""></feBlend>
        </filter>
        <path
          id="wave"
          d="M 0,10 C 30,10 30,15 60,15 90,15 90,10 120,10 150,10 150,15 180,15 210,15 210,10 240,10 v 28 h -240 z"
          data-v-955b2896=""
        ></path>
      </defs>
      <use
        id="wave3"
        xlink:href="#wave"
        x="0"
        y="-2"
        class="wave"
        data-v-955b2896=""
      ></use>
      <use
        id="wave2"
        xlink:href="#wave"
        x="0"
        y="0"
        class="wave"
        data-v-955b2896=""
      ></use>
      <g class="gooeff" data-v-955b2896=""></g>
      <!-- <circle
        cx="20"
        cy="2"
        r="1.8"
        class="drop drop1"
        data-v-955b2896=""
      ></circle>
      <circle
        cx="25"
        cy="2.5"
        r="1.5"
        class="drop drop2"
        data-v-955b2896=""
      ></circle>
      <circle
        cx="16"
        cy="2.8"
        r="1.2"
        class="drop drop3"
        data-v-955b2896=""
      ></circle> -->
      <use
        id="wave1"
        xlink:href="#wave"
        x="0"
        y="1"
        class="wave"
        data-v-955b2896=""
      ></use>
    </svg>
    <footer class="lg:flex pb-10 md:pb-0">
      <div class="container">
        <div class="main-section grid lg:grid-cols-6 gap-10 px-6 md:px-0">
          <div class="company-profile">
            <div class="text-white bold text-2xl flex items-center">
              <img
                class="logo"
                height="60"
                width="60"
                src="/icon.png"
                style="filter: invert(1)"
              /><span class="ml-2 font-black">Rennec</span>
            </div>
            <p class="text-white text-sm pt-4 pb-16 pr-16 leading-6">
              Rediscover your Creative Self, Expand your Knowledge Vector,
              Interact with your Professional Peers. t is a long established
              fact that a reader will be distracted by the readable content of a
              page when looking at its layout.
            </p>
          </div>
          <div class="general-info info">
            <h4 class="text-white bold text-lg">Info</h4>
            <ul class="css-8d7dj1 e15vi8s017">
              <li>
                <nuxt-link to="/about">
                  <span>About Rennec</span>
                </nuxt-link>
              </li>
              <li>
                <a target="_blank" href="https://blog.rennec.com/">
                  <span>Blog</span>
                </a>
              </li>
            </ul>
          </div>
          <div class="general-info business">
            <h4 class="text-white bold text-lg">Contact</h4>
            <ul class="css-8d7dj1 e15vi8s017">
              <li>
                <a target="_blank" href="https://help.rennec.com/">
                  <span>Help & Support</span>
                </a>
              </li>
              <li>
                <a target="_blank" href="https://merchant.rennec.com/">
                  <span>Partner with us</span>
                </a>
              </li>
            </ul>
          </div>
          <!-- <div class="general-info support">
          <h4 class="text-white bold text-lg">Support</h4>
          <ul class="css-8d7dj1 e15vi8s017">
            <li>
              <a href="/about">
                <span>Customer Help</span>
              </a>
            </li>
            <li>
              <a href="/careers">
                <span>Business Help</span>
              </a>
            </li>
          </ul>
        </div> -->
          <div class="general-info more">
            <h4 class="text-white bold text-lg">Legal</h4>
            <ul class="css-8d7dj1 e15vi8s017">
              <li>
                <a
                  target="_blank"
                  href="https://legal.rennec.com/terms-conditions/"
                >
                  <span>Terms & Conditions</span>
                </a>
              </li>
              <!-- <li>
              <a
                target="_blank"
                href="https://legal.rennec.com/refund-cancellation/"
              >
                <span>Refund & Cancellation</span>
              </a>
            </li> -->
              <li>
                <a target="_blank" href="https://legal.rennec.com/privacy/">
                  <span>Privacy Policy</span>
                </a>
              </li>
              <li>
                <a target="_blank" href="https://legal.rennec.com/cookie/">
                  <span>Cookie Policy</span>
                </a>
              </li>
            </ul>
          </div>
          <div class="general-info follow-us">
            <h4 class="text-white bold text-lg">Follow Us</h4>
            <ul class="css-8d7dj1 e15vi8s017">
              <li>
                <a target="_blank" href="https://www.facebook.com/therennec/">
                  <span>Facebook</span>
                </a>
              </li>
              <li>
                <a target="_blank" href="https://www.instagram.com/therennec/">
                  <span>Instagram</span>
                </a>
              </li>
              <li>
                <a target="_blank" href="https://twitter.com/therennec">
                  <span>Twitter</span>
                </a>
              </li>
              <li>
                <a
                  target="_blank"
                  href="https://in.linkedin.com/company/rennec"
                >
                  <span>LinkedIn</span>
                </a>
              </li>
            </ul>
          </div>
        </div>
        <div class="py-10">
          <p class="text-white text-sm text-center">© 2021 Rennec</p>
        </div>
      </div>
    </footer>
  </div>
</template>


<style lang="scss" scoped>
footer {
  background-color: #151515;
  // padding-top: 20px;
}
// .container {
//   width: 1024px !important;
// }

@media screen and (min-width: 768px) {
  .main-section {
    margin-bottom: 0;
  }
}
.main-section {
  display: grid;
  // grid-template-areas:
  //   "profile profile . info business"
  //   "profile profile .  more follow-us";
  grid-template-areas: "profile profile info more business  follow-us";
}

.info {
  grid-area: info;
}

.more {
  grid-area: more;
}

.follow-us {
  grid-area: follow-us;
}

.support {
  grid-area: support;
}

.business {
  grid-area: business;
}

.company-profile {
  grid-area: profile;
}

@media only screen and (max-width: 769px) {
  .main-section {
    display: grid;
    grid-template-areas:
      "profile profile profile profile"
      "info info business business"
      "more more follow-us follow-us";
  }
}

.main-section {
  border-bottom: 1px solid rgba(151, 151, 151, 0.21);
  .general-info {
    color: white;
  }

  li {
    padding: 10px 0 0 0;
    a {
      color: #8f95a3;
      font-size: 13px;
    }
  }
}

.logo {
  width: 60px;
  height: 100%;
}
svg[data-v-955b2896] {
  width: 100%;
}

.arrow[data-v-955b2896] {
  stroke-width: 0.3px;
  stroke: #ff0;
}

.topball[data-v-955b2896] {
  -webkit-animation: ball-data-v-955b2896 1.5s ease-in-out;
  animation: ball-data-v-955b2896 1.5s ease-in-out;
  -webkit-animation-iteration-count: infinite;
  animation-iteration-count: infinite;
  -webkit-animation-direction: alternate;
  animation-direction: alternate;
  -webkit-animation-delay: 0.3s;
  animation-delay: 0.3s;
  cursor: pointer;
}

.wave[data-v-955b2896] {
  -webkit-animation: wave-data-v-955b2896 3s linear;
  animation: wave-data-v-955b2896 3s linear;
  -webkit-animation-iteration-count: infinite;
  animation-iteration-count: infinite;
  fill: #151515;
}

.drop[data-v-955b2896] {
  fill: transparent;
  -webkit-animation: drop-data-v-955b2896 5s ease infinite normal;
  animation: drop-data-v-955b2896 5s ease infinite normal;
  stroke: #4478e3;
  stroke-width: 0.5;
  opacity: 0.6;
  transform: translateY(80%);
}

.drop1[data-v-955b2896] {
  transform-origin: 20px 3px;
}

.drop2[data-v-955b2896] {
  -webkit-animation-delay: 3s;
  animation-delay: 3s;
  -webkit-animation-duration: 3s;
  animation-duration: 3s;
  transform-origin: 25px 3px;
}

.drop3[data-v-955b2896] {
  -webkit-animation-delay: -2s;
  animation-delay: -2s;
  -webkit-animation-duration: 3.4s;
  animation-duration: 3.4s;
  transform-origin: 16px 3px;
}

.gooeff[data-v-955b2896] {
  -webkit-filter: url(#goo);
  filter: url(#goo);
}

#wave2[data-v-955b2896] {
  -webkit-animation-duration: 5s;
  animation-duration: 5s;
  animation-direction: reverse;
  opacity: 0.6;
}

#wave3[data-v-955b2896] {
  -webkit-animation-duration: 7s;
  animation-duration: 7s;
  opacity: 0.3;
}

@-webkit-keyframes drop-data-v-955b2896 {
  0% {
    transform: translateY(80%);
    opacity: 0.6;
  }

  80% {
    transform: translateY(80%);
    opacity: 0.6;
  }

  90% {
    transform: translateY(10%);
    opacity: 0.6;
  }

  to {
    transform: translateY(0) scale(1.5);
    stroke-width: 0.2;
    opacity: 0;
  }
}

@keyframes drop-data-v-955b2896 {
  0% {
    transform: translateY(80%);
    opacity: 0.6;
  }

  80% {
    transform: translateY(80%);
    opacity: 0.6;
  }

  90% {
    transform: translateY(10%);
    opacity: 0.6;
  }

  to {
    transform: translateY(0) scale(1.5);
    stroke-width: 0.2;
    opacity: 0;
  }
}

@-webkit-keyframes wave-data-v-955b2896 {
  to {
    transform: translateX(-100%);
  }
}

@keyframes wave-data-v-955b2896 {
  to {
    transform: translateX(-100%);
  }
}

@-webkit-keyframes ball-data-v-955b2896 {
  to {
    transform: translateY(20%);
  }
}

@keyframes ball-data-v-955b2896 {
  to {
    transform: translateY(20%);
  }
}
</style>
