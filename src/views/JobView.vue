<template>
    <router-link 
        class="job__back-link"
        title="CAREERS"
        to="/"
    >
        <svg width="21" height="13" viewBox="0 0 21 13" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M8.40234 11.6133L2.96094 6.39063L8.40234 1.16797L7.36328 0.101563L0.800781 6.39063L7.36328 12.6797L8.40234 11.6133ZM20.625 5.65234L20.625 7.12891L19.1484 7.12891L19.1484 5.65234L20.625 5.65234ZM17.6445 5.65234L17.6445 7.12891L16.1406 7.12891L16.1406 5.65234L17.6445 5.65234ZM14.6367 5.65234L14.6367 7.12891L13.1328 7.12891L13.1328 5.65234L14.6367 5.65234ZM11.6289 5.65234L11.6289 7.12891L10.125 7.12891L10.125 5.65234L11.6289 5.65234ZM8.64844 5.65234L8.64844 7.12891L7.14453 7.12891L7.14453 5.65234L8.64844 5.65234ZM5.64063 5.65234L5.64063 7.12891L4.13672 7.12891L4.13672 5.65234L5.64063 5.65234Z" fill="white"/>
        </svg>
        <span>CAREERS</span>
    </router-link>
    <MajTitle is="h1" class="job__title" >
        <span style="color: #000000;">Careers </span><br> WordPress Developer
    </MajTitle>
    <div class="job__menu-icon">
        <svg viewBox="0 0 23 21" fill="none" xmlns="http://www.w3.org/2000/svg">
            <line x1="0.726562" y1="1.5" x2="22.5007" y2="1.5" stroke="white" stroke-width="2"/>
            <line x1="0.726562" y1="10.6433" x2="14.4015" y2="10.6433" stroke="white" stroke-width="2"/>
            <line x1="0.726562" y1="19.7871" x2="18.6642" y2="19.7871" stroke="white" stroke-width="2"/>
        </svg>
    </div>
    <div class="job__line-hide"></div>
    <MajContainer vertical class="job" centerX>
        <div class="job__desc">
            <div class="job__desc-line"></div>
            <p>SPRD.digital is looking for a motivated WordPress developer to join our team! We invite anyone who is great at programming and who thrive on developing cleanly written code for websites and who enjoy improving existing sites.</p>
        </div>
        <MajContainer class="job__overview">
            <section class="job__overview-left">
                <p>As a developer you will be working closely with our whole development team and our CTO, so that the projects you work on will be completed on time and with an impressive level of quality.</p>
                <br>
                <p>As a company we strive to provide all employees with a peaceful working environment, with unlimited access to coffee, tea, juice, fruit, and other snacks. This job is not remote, but at the office of our sister company, Zabec.net, in Ljubljana.</p>
            </section>
            <MajContainer vertical class="job__overview-right">
                <div class="job__overview-divider"></div>
                <h5 class="job__overview-right-title">contract type</h5>
                <p class="job__overview-right-value">Full-Time</p>
                <h5 class="job__overview-right-title">location</h5>
                <p class="job__overview-right-value">Ljubljana, Slovenia</p>
                <h5 class="job__overview-right-title">Open Until</h5>
                <p class="job__overview-right-value">12.12.2022 (4 days left)</p>
            </MajContainer> 
        </MajContainer>
        <MajContainer class="job__overview">
            <section class="job__overview-left">
                <MajTitle is="h3">
                    What We Expect
                </MajTitle>
                <div class="job__overview-divider"></div>
                <ul>
                    <li>Extensive knowledge of WordPress</li>
                    <li>Precision, dependability, and clear, regular documentation</li>
                    <li>Extensive knowledge of GIT</li>
                    <li>Basic knowledge of HTML/CSS</li>
                    <li>Knowledge of Javascript</li>
                    <li>Knowledge of integration and maintenance for a variety of API connections</li>
                    <li>Quick thinking and reacting in solving problems and bugs that come up on projects</li>
                    <li>Team player, “no problem too big” attitude, time-effective, fluency in English</li>
                </ul>
            </section>
        </MajContainer>
        <MajContainer class="job__overview">
            <section class="job__overview-left">
                <MajTitle is="h3">
                    What We Offer
                </MajTitle>
                <div class="job__overview-divider"></div>
                <ul>
                    <li>Budget for in-house services</li>
                    <li>Budget for continued education</li>
                    <li>Full-time employment</li>
                    <li>Great working environment</li>
                    <li>Your own computer with multiple screens</li>
                    <li>Chances to test new technologies</li>
                    <li>Collaboration on Slovenian and international projects</li>
                </ul>
            </section>
        </MajContainer>
        <MajContainer centerY class="job__bluebox">
            <div class="job__bluebox-bg"></div>
            <MajContainer class="job__bluebox-container">
                <MajContainer vertical class="job__bluebox-container-2">
                    <MajTitle is="h1">
                        Is this You?
                    </MajTitle>
                    <div class="job__bluebox-divider"></div>
                    <p>Lorem ipsum dolor sit amet consectetur. Viverra dictumst diam placerat faucibus tempus dui feugiat volutpat. Lorem ipsum dolor sit amet consectetur. Viverra dictumst diam placerat faucibus tempus dui feugiat volutpat.</p>
                    <button class="job__bluebox-button"><span>APPLY VIA EMAIL</span></button>
                </MajContainer>
            </MajContainer>
        </MajContainer> 
    </MajContainer>
</template>

<script>

export default {
  name: "JobView",
}
</script>

<style lang="scss">
.job {
  width: 100vw;
  margin-top: 29%;
  flex-grow: 1;
  position: relative;
  &__back-link {
    position: absolute;
    left: 0;
    top: 0;
    margin: 7.6% 4%;
    cursor: pointer;
    span {
      display: inline-block;
      padding: 2px 0;
      margin-left: 9px;
      border-bottom: 1px dashed #FFFFFF;
      font-size: 12px;
      line-height: 120%;
      letter-spacing: 0.15em;
      color: #FFFFFF;
      text-transform: uppercase;
    }
    // svg {
    //   margin-top: 3px;
    // }
    &:hover {
      span {
        color: #DDDFDF;
        border-bottom: 1px dashed #DDDFDF;
      }
    }
  }
  &__title {
    position: absolute;
    left: 0;
    top: 0;
    margin: 13.5% 2.8%;
  }
  &__menu-icon {
    position: absolute;
    aspect-ratio: 23/21;
    margin-top: 2.7%;
    margin-right: 2.7%;
    width: 1.4%;
    right: 0;
    top: 0;
    cursor: pointer;
  }
  &__line-hide {
    position: absolute;
    left: 0;
    top: 0;
    height: 600px;
    width: 2.7%;
    background: $bg;
    z-index: 1;
  }
  &__desc {
    width: 1032.68px;
    padding: 18.39px 0;
    max-width: calc(100% - 5.4%);
    position: relative;
    p {
      font-size: 22px;
      line-height: 130%;
      color: #FFFFFF;
      width: 63.4%;
    }
    &-line {
      position: absolute;
      right: 102%;
      margin-left: 2.7%;
      margin-top: 12px;
      width: 35.6%;
      // width: 19.4%;
      border-bottom: 1px solid #FFFFFF;
    }
  }
  &__overview {
    width: 1032.68px;
    padding: 18.39px 0;
    max-width: calc(100% - 5.4%);
    &-divider {
      width: 124px;
      height: 0px;
      border-bottom: 1px solid #34eac9;
      margin-bottom: 15px;
    }
    &-left {
      width: 63.4%;
      margin-right: 6.7%;

      h3.maj-title {
        display: inline-block;
        padding: 2px 0;
        margin-bottom: 20px;
      }
      p, li {
        font-size: 17px;
        line-height: 150%;
        color: #DDDFDF;
      }
      li {
        list-style-type: disc;
        margin-left: 18px;
      }
    }
    &-right {
      &-title {
        font-style: normal;
        font-weight: 400;
        font-size: 12px;
        line-height: 120%;
        letter-spacing: 0.15em;
        text-transform: uppercase;
        color: #DDDFDF;
        
      }
      &-value {
        font-style: normal;
        font-weight: 400;
        font-size: 17px;
        line-height: 150%;
        color: #FFFFFF;
        margin-bottom: 15px;
       
      }
    }
  }
  &__bluebox {
    width: 100vw;
    height: 326.7px;
    position: relative;
    margin-top: 50px;
    &-bg {
      position: absolute;
      width: 100%;
      height: 100%;
      background: linear-gradient(108.05deg, #00C9A5 -1.97%, #000F59 119.17%);
      transform: matrix(1, 0, 0, -1, 0, 0);
    }
    &-container {
      width: 1032.69px;
      margin-top: 38.84px;
      max-width: calc(100% - 5.4%);
    }
    &-container-2 {
      width: 661.64px;
      gap: 15px;
      * {
        z-index: 1;
      }
      p {
        font-size: 17px;
        line-height: 150%;
        color: #FFFFFF;
      }
    }
    &-divider {
      width: 124px;
      height: 0px;
      border-bottom: 1px solid #34eac9;
    }
    &-button {
      width: 246px;
      height: 48px;
      background: #FFFFFF;
      border: 1px solid #FFFFFF;
      border-radius: 24px;
      transition: all 0.2s;
      span {
        font-family: 'Gotham_KTR--bold';
        font-style: normal;
        font-weight: 700;
        font-size: 12px;
        line-height: 100%;
        text-align: center;
        letter-spacing: 0.15em;
        text-transform: uppercase;
        color: #1B2626;
        transition: all 0.2s;
      }
      &:hover {
        background: transparent;
        span {
          color: #FFFFFF;
        }
      }
    }
  }
} 
</style>
