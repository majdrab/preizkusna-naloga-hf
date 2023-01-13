<template>
    <router-link 
        class="home__back-link"
        title="COMPANY"
        to="/"
    >
        company
    </router-link>
    <MajTitle is="h1" class="home__title">
        Careers
    </MajTitle>
    <MajContainer vertical class="home" centerX>
        <div class="home__desc"><p>We’re a dynamic group enjoying healthy growth. As a fast-growing group, it regularly needs to add a member to its workforce. As a result there are jobs available regularly, both to full-time employees and to students seeking internships. We offer a unique glimpse into the world of development, marketing, technology, IT, and servers.</p></div>
        <MajContainer class="home__job-overview">
            <section class="home__job-overview-left">
                <router-link 
                    title="WordPress developer"
                    to="/job"
                >
                    <MajTitle is="h3">
                        WordPress developer
                    </MajTitle>
                    
                </router-link>
                <p>Humanfrog is looking for a motivated WordPress developer to join our team! We invite anyone who is great at programming and who thrive on developing cleanly written code and who enjoy improving existing sites.</p>
                <router-link
                    class="home__job-link"
                    title="WordPress developer"
                    to="/job"
                >
                    <svg width="26" height="7" viewBox="0 0 26 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M25.1074 3.78125L20.1074 0.894499V6.668L25.1074 3.78125ZM0.689453 4.28125H20.6074V3.28125H0.689453V4.28125Z"/>
                    </svg>
                    <span>READ MORE</span>
                    
                </router-link>
            </section>
            <MajContainer vertical class="home__job-overview-right">
                <h5 class="home__job-overview-right-title">contract type</h5>
                <p class="home__job-overview-right-value">Full-Time</p>
                <h5 class="home__job-overview-right-title">location</h5>
                <p class="home__job-overview-right-value">Ljubljana, Slovenia <br>Hybrid <br>Remote</p>
                <h5 class="home__job-overview-right-title">Open Until</h5>
                <p class="home__job-overview-right-value">12.12.2022 (4 days left)</p>
            </MajContainer> 
        </MajContainer>
        <MajContainer class="home__job-overview">
            <section class="home__job-overview-left">
                <router-link 
                    title="WordPress developer"
                    to="/job"
                >
                    <MajTitle is="h3">
                        WordPress developer
                    </MajTitle>
                    
                </router-link>
                <p>Humanfrog is looking for a motivated WordPress developer to join our team! We invite anyone who is great at programming and who thrive on developing cleanly written code and who enjoy improving existing sites.</p>
                <router-link
                    class="home__job-link"
                    title="WordPress developer"
                    to="/job"
                >
                    <svg width="26" height="7" viewBox="0 0 26 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M25.1074 3.78125L20.1074 0.894499V6.668L25.1074 3.78125ZM0.689453 4.28125H20.6074V3.28125H0.689453V4.28125Z"/>
                    </svg>
                    <span>READ MORE</span>
                    
                </router-link>
            </section>
            <MajContainer vertical class="home__job-overview-right">
                <h5 class="home__job-overview-right-title">contract type</h5>
                <p class="home__job-overview-right-value">Full-Time</p>
                <h5 class="home__job-overview-right-title">location</h5>
                <p class="home__job-overview-right-value">Ljubljana, Slovenia <br>Hybrid <br>Remote</p>
                <h5 class="home__job-overview-right-title">Open Until</h5>
                <p class="home__job-overview-right-value">12.12.2022 (4 days left)</p>
            </MajContainer> 
        </MajContainer>
        <MajContainer class="home__job-overview">
            <section class="home__job-overview-left">
                <router-link 
                    title="WordPress developer"
                    to="/job"
                >
                    <MajTitle is="h3">
                        WordPress developer
                    </MajTitle>
                    
                </router-link>
                <p>Humanfrog is looking for a motivated WordPress developer to join our team! We invite anyone who is great at programming and who thrive on developing cleanly written code and who enjoy improving existing sites.</p>
                <router-link
                    class="home__job-link"
                    title="WordPress developer"
                    to="/job"
                >
                    <svg width="26" height="7" viewBox="0 0 26 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M25.1074 3.78125L20.1074 0.894499V6.668L25.1074 3.78125ZM0.689453 4.28125H20.6074V3.28125H0.689453V4.28125Z"/>
                    </svg>
                    <span>READ MORE</span>
                    
                </router-link>
            </section>
            <MajContainer vertical class="home__job-overview-right">
                <h5 class="home__job-overview-right-title">contract type</h5>
                <p class="home__job-overview-right-value">Full-Time</p>
                <h5 class="home__job-overview-right-title">location</h5>
                <p class="home__job-overview-right-value">Ljubljana, Slovenia <br>Hybrid <br>Remote</p>
                <h5 class="home__job-overview-right-title">Open Until</h5>
                <p class="home__job-overview-right-value">12.12.2022 (4 days left)</p>
            </MajContainer> 
        </MajContainer>
    </MajContainer>
</template>

<script>

export default {
  name: "HomeView",
}
</script>

<style lang="scss">
.home {
  width: 100vw;
  // height: 572.6px;
  margin-top: 29%;
  flex-grow: 1;
  position: relative;
  &__back-link {
    position: absolute;
    left: 0;
    top: 0;
    margin: 7.6% 6%;

    display: inline-block;
    padding: 2px 0;
    border-bottom: 1px dashed #FFFFFF;
    font-size: 12px;
    letter-spacing: 0.15em;
    line-height: 120%;
    color: #FFFFFF;
    cursor: pointer;
    text-transform: uppercase;
    &:hover {
      color: #DDDFDF;
      border-bottom: 1px dashed #DDDFDF;
    }
  }
  &__title {
    position: absolute;
    left: 0;
    top: 0;
    color: #FFFFFF;
    margin: 13.5% 2.7%;
  }
  &__desc {
    width: 1032.68px;
    padding: 18.39px 0;
    max-width: calc(100% - 5.4%);
    p {
      font-size: 22px;
      line-height: 130%;
      color: #FFFFFF;
      width: 665px;
    }
  }
  &__job-overview {
    width: 1032.68px;
    padding: 18.39px 0;
    max-width: calc(100% - 5.4%);
    border-top: 1px solid #707070;
    &:last-of-type {
      border-bottom: 1px solid #707070;
    }
    &-left {
      width: 63.4%;
      margin-right: 6.7%;

      h3.maj-title {
        display: inline-block;
        padding: 2px 0;
        margin-bottom: 20px;
        border-bottom: 1px dashed #FFFFFF;
        cursor: pointer;
        
        &:hover {
          color: #DDDFDF;
          border-bottom: 1px dashed #DDDFDF;
        }
      }
      p {
        font-size: 17px;
        line-height: 150%;
        color: #DDDFDF;
      }
      .home__job-link {
        cursor: pointer;
        span {
          display: inline-block;
          padding: 2px 0;
          margin-top: 12px;
          margin-left: 9px;
          border-bottom: 1px dashed #FFFFFF;
          font-size: 12px;
          line-height: 120%;
          letter-spacing: 0.15em;
          color: #FFFFFF;
        }
        svg {
          fill: #FFFFFF;
        }
        &:hover {
          span {
            color: #DDDFDF;
            border-bottom: 1px dashed #DDDFDF;
          }
          svg {
            fill: #DDDFDF;
          }
        }
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

        &:last-of-type {
          margin-bottom: 0;
        }
      }
    }
  }
} 
</style>
