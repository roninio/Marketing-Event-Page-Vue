<template>
  <div class="home-container">
    <app-navigation></app-navigation>
    <div class="home-container1"></div>
    <main class="home-main">
      <div class="home-hero section-container">
        <div class="home-max-width max-content-container">
          <div class="home-content-container">
            <h1 class="home-text heading1">
              <span>
                Trust.AI
                <span v-html="raw784r"></span>
              </span>
              <span class="home-text02">Consorium</span>
              <span></span>
            </h1>
            <span class="home-text04">
              <span>
                bringingtrust to AI applications
                <span v-html="raw4po3"></span>
              </span>
              <br />
              <span>Colaboration between top Industry and academic groups</span>
            </span>
            <div class="home-btns-container">
              <button class="home-primary button-primary button-lg button">
                register now
              </button>
              <button class="button button-outline button-lg-border">
                learn more
              </button>
            </div>
          </div>
          <div class="home-video-container"></div>
        </div>
        <div class="home-blue-background"></div>
      </div>
      <div class="home-sponsors section-container">
        <div class="home-max-width1 max-content-container">
          <span class="home-text08"><span>Members</span></span>
          <div class="home-container2">
            <img
              alt="image"
              src="/playground_assets/kisspng-elbit-systems-nasdaq-eslt-company-stock-5b17e89cf3f357.8504019715282935329992-removebg-preview-1200w.png"
              class="home-image"
            />
            <img
              alt="image"
              src="/playground_assets/group%208-1200w.png"
              class="home-image1"
            />
            <img
              alt="image"
              src="/playground_assets/group%209-1200w.png"
              class="home-image2"
            />
            <img
              alt="image"
              src="/playground_assets/group%2010-1200w.png"
              class="home-image3"
            />
            <img
              alt="image"
              src="/playground_assets/group%2011-1200w.png"
              class="home-image4"
            />
            <img
              alt="image"
              src="/playground_assets/group%2012-1200w.png"
              class="home-image5"
            />
          </div>
        </div>
      </div>
      <div class="home-speakers section-container">
        <div class="home-max-width2 max-content-container">
          <div class="home-heading-container">
            <span class="home-text10">
              16 speakers from 7 countries and 3 continents
            </span>
            <h1 class="home-text11 heading2"><span>meet our Team</span></h1>
          </div>
          <div class="home-speakers-container">
            <speaker-card></speaker-card>
            <speaker-card
              role="Chairman"
              lastName="Ben-Yizhak"
              firstName="Eli "
              image_src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDF8fHBlb3BsZXxlbnwwfHx8fDE2NDM3MDU1MTE&amp;ixlib=rb-1.2.1&amp;h=300"
            ></speaker-card>
            <speaker-card
              role="VP OF Marketing @ BUZZFEED"
              lastName="tevlenko"
              firstName="alina"
              image_src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDZ8fHBlb3BsZXxlbnwwfHx8fDE2NDM3MDU1MTE&amp;ixlib=rb-1.2.1&amp;h=300"
            ></speaker-card>
            <speaker-card
              role="HEAD OF DIGITAL @ HUBSPOT"
              lastName="iprovich"
              firstName="gregor"
              image_src="https://images.unsplash.com/photo-1537511446984-935f663eb1f4?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDI5fHxwZW9wbGV8ZW58MHx8fHwxNjQzNzA1NTEx&amp;ixlib=rb-1.2.1&amp;h=300"
            ></speaker-card>
            <speaker-card
              role="marketing officer @ salesforce"
              lastName="daris"
              firstName="damian"
              image_src="https://images.unsplash.com/photo-1531427186611-ecfd6d936c79?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDExfHxwZW9wbGV8ZW58MHx8fHwxNjQzNzA1NTEx&amp;ixlib=rb-1.2.1&amp;h=300"
            ></speaker-card>
            <speaker-card
              role="social media manager @ vodafone"
              lastName="warren"
              firstName="matt"
              image_src="https://images.unsplash.com/photo-1531384441138-2736e62e0919?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDE0N3x8cGVvcGxlfGVufDB8fHx8MTY0MzcwODY5MQ&amp;ixlib=rb-1.2.1&amp;h=300"
            ></speaker-card>
            <speaker-card
              role="creative director @ BBDO"
              lastName="moore"
              firstName="kathie"
              image_src="https://images.unsplash.com/photo-1589156280159-27698a70f29e?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDE2OHx8cGVvcGxlfGVufDB8fHx8MTY0MzcwODY5MQ&amp;ixlib=rb-1.2.1&amp;h=300"
            ></speaker-card>
            <speaker-card
              role="CMO @ youtube Europe"
              lastName="chan"
              firstName="erick"
              image_src="https://images.unsplash.com/photo-1558222218-b7b54eede3f3?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDEwNHx8cGVvcGxlfGVufDB8fHx8MTY0MzcwODY4MQ&amp;ixlib=rb-1.2.1&amp;h=300"
            ></speaker-card>
          </div>
        </div>
      </div>
      <div class="home-numbers-banner section-container">
        <div class="home-container3 max-content-container">
          <div class="home-heading-container1">
            <span class="home-text13">
              Our 12-year conference history in sharing digital marketing insights
            </span>
            <h1 class="home-text14 heading2">
              <span>market1 SUMMIT IN NUMBERS</span>
            </h1>
          </div>
          <div class="home-numbers-container">
            <numbers-card></numbers-card>
            <numbers-card
              text="years"
              number="12"
              image_src="/playground_assets/interface%20time%20reset-200h.png"
            ></numbers-card>
            <numbers-card
              text="total events"
              number="64"
              image_src="/playground_assets/interface%20calendar%20favorite-200h.png"
            ></numbers-card>
            <numbers-card
              text="companies"
              number="15,070"
              image_src="/playground_assets/shopping%20bag%20suit%20case-200h.png"
            ></numbers-card>
            <numbers-card
              text="cities"
              number="14"
              image_src="/playground_assets/travel%20map%20location%20pin-200h.png"
            ></numbers-card>
            <numbers-card
              text="speakers"
              number="1,071"
              image_src="/playground_assets/computer%20voice%20mail-200h.png"
            ></numbers-card>
          </div>
        </div>
      </div>
      <div class="home-location">
        <img
          alt="image"
          src="https://images.unsplash.com/photo-1564347288827-3e4293543e07?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDE2fHxiZXJsaW58ZW58MHx8fHwxNjQzNzEzNjQ5&amp;ixlib=rb-1.2.1&amp;w=1500"
          class="home-image6"
        />
        <div class="home-content-container1 section-container">
          <div class="home-container4">
            <span class="home-text16">berlin, germany</span>
            <span class="home-text17">7-8 MARCH 2023</span>
            <div class="home-container5">
              <span class="home-text18"><span>— mob-x</span></span>
              <span class="home-text20"><span>conference</span></span>
              <span class="home-text22"><span>center</span></span>
            </div>
            <div class="home-container6">
              <span class="home-text24">beautiful, vibrant berlin</span>
              <span class="home-text25">
                <span>
                  Amet minim mollit non deserunt ullamco est sit aliqua dolor do
                  amet sint. Velit officia consequat duis enim velit mollit.
                  Exercitation veniam consequat sunt nostrud amet.
                </span>
                <br />
                <span></span>
                <br />
                <span>
                  Lorem Ipsum, Velit officia consequat duis enim velit mollit.
                  Exercitation veniam consequat sunt nostrud amet.
                </span>
              </span>
              <div class="home-btns-container1">
                <button class="button-secondary button button-md">
                  register
                </button>
                <button
                  class="home-learn-more button button-outline button-md-border"
                >
                  learn more
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="home-agenda section-container">
        <div class="home-max-width3 max-content-container">
          <div class="home-heading-container2">
            <h1 class="home-text29 heading2"><span>key events agenda</span></h1>
            <span class="home-text31">more announcements are coming soon</span>
          </div>
          <div class="home-events-container">
            <div class="home-column">
              <div class="home-column-header">
                <span class="home-text32"><span>tuesday - 7.03</span></span>
                <div class="home-line"></div>
              </div>
              <event-card></event-card>
              <event-card
                title="tik tok or what?"
                image_src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDF8fHBlb3BsZXxlbnwwfHx8fDE2NDM3MDU1MTE&amp;ixlib=rb-1.2.1&amp;h=300"
              ></event-card>
              <event-card
                title="sales + marketing duo"
                image_src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDZ8fHBlb3BsZXxlbnwwfHx8fDE2NDM3MDU1MTE&amp;ixlib=rb-1.2.1&amp;h=300"
              ></event-card>
              <event-card
                title="best practices for more
  data-driven results"
                image_src="https://images.unsplash.com/photo-1537511446984-935f663eb1f4?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDI5fHxwZW9wbGV8ZW58MHx8fHwxNjQzNzA1NTEx&amp;ixlib=rb-1.2.1&amp;h=300"
              ></event-card>
            </div>
            <div class="home-column1">
              <div class="home-column-header1">
                <span class="home-text34"><span>wednesday - 8.03</span></span>
                <div class="home-line1"></div>
              </div>
              <event-card
                title="digital marketing strategies"
                image_src="https://images.unsplash.com/photo-1531427186611-ecfd6d936c79?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDExfHxwZW9wbGV8ZW58MHx8fHwxNjQzNzA1NTEx&amp;ixlib=rb-1.2.1&amp;h=300"
              ></event-card>
              <event-card
                title="a new era of social media"
                image_src="https://images.unsplash.com/photo-1531384441138-2736e62e0919?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDE0N3x8cGVvcGxlfGVufDB8fHx8MTY0MzcwODY5MQ&amp;ixlib=rb-1.2.1&amp;h=300"
              ></event-card>
              <event-card
                title="growing a remote team"
                image_src="https://images.unsplash.com/photo-1589156280159-27698a70f29e?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDE2OHx8cGVvcGxlfGVufDB8fHx8MTY0MzcwODY5MQ&amp;ixlib=rb-1.2.1&amp;h=300"
              ></event-card>
              <event-card
                title="beyond the metaverse"
                image_src="https://images.unsplash.com/photo-1558222218-b7b54eede3f3?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDEwNHx8cGVvcGxlfGVufDB8fHx8MTY0MzcwODY4MQ&amp;ixlib=rb-1.2.1&amp;h=300"
              ></event-card>
            </div>
          </div>
        </div>
      </div>
      <div class="home-workshops">
        <div class="home-content-container2">
          <div class="home-container7">
            <h1 class="home-text36 heading2">
              <span>
                register for
                <span v-html="rawc8y5"></span>
              </span>
              <br />
              <span class="home-text39">super insightful</span>
              <span><span v-html="rawyhqz"></span></span>
              <br />
              <span>
                workshops for
                <span v-html="rawhld8"></span>
              </span>
              <br />
              <span>your team</span>
            </h1>
            <span class="home-text45">
              get early discounts and group discounts
            </span>
            <span class="home-text46">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
              sint. Velit officia consequat duis enim velit mollit. Exercitation
              veniam consequat sunt nostrud amet.
            </span>
            <button class="button button-md button-outline">learn more</button>
          </div>
        </div>
        <img
          alt="image"
          src="https://images.unsplash.com/photo-1556761175-5973dc0f32e7?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDIwfHxidXNpbmVzc3xlbnwwfHx8fDE2NDM3MzQ3MjI&amp;ixlib=rb-1.2.1&amp;w=1500"
          class="home-image7"
        />
      </div>
      <div class="home-previous-events section-container">
        <div class="home-max-width4 max-content-container">
          <div class="home-heading-container3">
            <h1 class="home-text47 heading2"><span>previous events</span></h1>
            <span class="home-text49">
              Take a tour of our previous conferences
            </span>
          </div>
        </div>
        <div data-type="slider" class="home-slider">
          <app-slide rootClassName="slide-root-class-name4"></app-slide>
          <app-slide
            heading="Slide #2"
            rootClassName="slide-root-class-name1"
          ></app-slide>
          <app-slide
            heading="Slide #3"
            rootClassName="slide-root-class-name"
          ></app-slide>
          <app-slide
            heading="Slide #4"
            rootClassName="slide-root-class-name3"
          ></app-slide>
          <app-slide
            heading="Slide #5"
            rootClassName="slide-root-class-name2"
          ></app-slide>
        </div>
        <div class="home-slider-controls">
          <div data-action="previousSlide" class="home-go-left">
            <svg viewBox="0 0 1024 1024" class="home-icon">
              <path d="M250 176l92-90 426 426-426 426-92-90 338-336z"></path>
            </svg>
          </div>
          <div data-action="nextSlide" class="home-go-right">
            <svg viewBox="0 0 1024 1024" class="home-icon2">
              <path d="M250 176l92-90 426 426-426 426-92-90 338-336z"></path>
            </svg>
          </div>
        </div>
      </div>
    </main>
    <app-footer rootClassName="footer-root-class-name"></app-footer>
  </div>
</template>

<script>
import AppNavigation from '../components/navigation'
import SpeakerCard from '../components/speaker-card'
import NumbersCard from '../components/numbers-card'
import EventCard from '../components/event-card'
import AppSlide from '../components/slide'
import AppFooter from '../components/footer'

export default {
  name: 'Home',
  components: {
    AppNavigation,
    SpeakerCard,
    NumbersCard,
    EventCard,
    AppSlide,
    AppFooter,
  },

  data() {
    return {
      raw784r: ' ',
      raw4po3: ' ',
      rawc8y5: ' ',
      rawyhqz: ' ',
      rawhld8: ' ',
    }
  },

  metaInfo: {
    title: 'Marketing Event Page',
    meta: [
      {
        property: 'og:title',
        content: 'Marketing Event Page',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  position: relative;
  min-height: 100vh;
  overflow-x: hidden;
  align-items: center;
  flex-direction: column;
}
.home-container1 {
  flex: 0 0 auto;
  width: 100%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: 100px;
  display: flex;
  align-items: flex-start;
}
.home-main {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-hero {
  position: relative;
  padding-top: 128px;
}
.home-max-width {
  z-index: 1;
  align-items: stretch;
}
.home-content-container {
  flex: 1;
  display: flex;
  max-width: 45%;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-text {
  margin-bottom: var(--dl-space-space-unit);
}
.home-text02 {
  color: var(--dl-color-scheme-pink);
}
.home-text04 {
  font-style: normal;
  font-weight: 500;
  margin-bottom: 42px;
}
.home-btns-container {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
}
.home-primary {
  margin-right: var(--dl-space-space-oneandhalfunits);
}
.home-video-container {
  flex: 1;
  width: 200px;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: 100px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-blue-background {
  top: 0px;
  right: 0px;
  width: 47%;
  height: 100px;
  position: absolute;
  min-height: 80%;
  background-size: cover;
  background-image: url("/playground_assets/blue-background-1500w.png");
  background-repeat: no-repeat;
}
.home-sponsors {
  height: 258px;
  display: flex;
  padding-top: var(--dl-space-space-oneandhalfunits);
  border-color: rgba(144, 149, 167, 0.1);
  border-width: 0px;
  flex-direction: column;
  border-bottom-width: 1px;
}
.home-max-width1 {
  flex-direction: column;
}
.home-text08 {
  color: var(--dl-color-scheme-darkgray);
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  margin-bottom: var(--dl-space-space-twounits);
  letter-spacing: 0.25em;
}
.home-container2 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.home-image {
  height: 80px;
  object-fit: cover;
}
.home-image1 {
  height: 80px;
  object-fit: cover;
}
.home-image2 {
  height: 80px;
  object-fit: cover;
}
.home-image3 {
  height: 80px;
  object-fit: cover;
}
.home-image4 {
  height: 80px;
  object-fit: cover;
}
.home-image5 {
  height: 80px;
  object-fit: cover;
}
.home-speakers {
  display: flex;
  padding-top: var(--dl-space-space-fiveunits);
  flex-direction: column;
}
.home-max-width2 {
  flex-direction: column;
}
.home-heading-container {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: column;
}
.home-text10 {
  color: var(--dl-color-scheme-darkgray);
  font-style: normal;
  text-align: center;
  font-weight: 500;
}
.home-text11 {
  text-align: center;
}
.home-speakers-container {
  width: 100%;
  display: grid;
  grid-row-gap: var(--dl-space-space-fourunits);
  grid-column-gap: 30px;
  grid-template-columns: 1fr 1fr 1fr 1fr;
}
.home-numbers-banner {
  display: flex;
  padding-top: var(--dl-space-space-fiveunits);
  flex-direction: column;
  background-size: cover;
  background-image: url("/playground_assets/group%2029-1500w.png");
}
.home-container3 {
  flex-direction: column;
}
.home-heading-container1 {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: column;
}
.home-text13 {
  color: var(--dl-color-scheme-white);
  font-style: normal;
  text-align: center;
  font-weight: 500;
}
.home-text14 {
  color: var(--dl-color-scheme-white);
  text-align: center;
}
.home-numbers-container {
  width: 100%;
  display: grid;
  grid-row-gap: var(--dl-space-space-fourunits);
  grid-column-gap: 30px;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
}
.home-location {
  width: 100%;
  display: flex;
  align-items: stretch;
  flex-direction: row;
}
.home-image6 {
  width: 55%;
  max-height: 950px;
  object-fit: cover;
}
.home-content-container1 {
  flex: 1;
  display: flex;
  align-items: stretch;
  padding-top: 100px;
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: row;
  background-color: var(--dl-color-scheme-black);
}
.home-container4 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text16 {
  color: var(--dl-color-scheme-white);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: -100px;
  padding-top: 4px;
  padding-left: 18px;
  margin-bottom: 6px;
  padding-right: 11px;
  padding-bottom: 6px;
  background-color: var(--dl-color-scheme-lightblue);
}
.home-text17 {
  color: var(--dl-color-scheme-white);
  font-size: 56px;
  font-style: normal;
  font-weight: 300;
  line-height: 1.1;
}
.home-container5 {
  display: flex;
  align-items: flex-end;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: column;
}
.home-text18 {
  color: var(--dl-color-scheme-pink);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: var(--dl-space-space-fiveunits);
}
.home-text20 {
  color: var(--dl-color-scheme-pink);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: -36px;
}
.home-text22 {
  color: var(--dl-color-scheme-pink);
  font-size: 56px;
  font-style: normal;
  font-weight: 600;
  line-height: 1.1;
  margin-left: var(--dl-space-space-fiveunits);
}
.home-container6 {
  flex: 1;
  width: 100%;
  display: flex;
  max-width: 350px;
  align-items: flex-start;
  margin-left: 124px;
  flex-direction: column;
}
.home-text24 {
  color: var(--dl-color-scheme-white);
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text25 {
  color: var(--dl-color-scheme-white);
  margin-bottom: var(--dl-space-space-twounits);
  text-transform: none;
}
.home-btns-container1 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
}
.home-learn-more {
  color: var(--dl-color-scheme-white);
  transition: 0.3s;
  border-color: var(--dl-color-scheme-white);
}
.home-learn-more:hover {
  border-color: var(--dl-color-scheme-pink);
}
.home-agenda {
  display: flex;
  flex-direction: column;
  padding-bottom: 100px;
}
.home-max-width3 {
  flex-direction: column;
}
.home-heading-container2 {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: column;
}
.home-text29 {
  text-align: center;
}
.home-text31 {
  color: var(--dl-color-scheme-darkgray);
  font-style: normal;
  text-align: center;
  font-weight: 500;
}
.home-events-container {
  width: 100%;
  display: grid;
  grid-row-gap: var(--dl-space-space-fourunits);
  grid-column-gap: 30px;
  grid-template-columns: 1fr 1fr;
}
.home-column {
  width: 100%;
  display: grid;
  grid-gap: 30px;
  grid-template-columns: 1fr;
}
.home-column-header {
  width: 100%;
  display: flex;
  align-items: center;
}
.home-text32 {
  color: var(--dl-color-scheme-darkgray);
  font-size: 24px;
  font-style: normal;
  font-weight: 500;
  line-height: 1.1;
  margin-right: 21px;
}
.home-line {
  flex: 1;
  height: 1px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: rgba(144, 149, 167, 0.2);
}
.home-column1 {
  width: 100%;
  display: grid;
  grid-gap: 30px;
  grid-template-columns: 1fr;
}
.home-column-header1 {
  width: 100%;
  display: flex;
  align-items: center;
}
.home-text34 {
  color: var(--dl-color-scheme-darkgray);
  font-size: 24px;
  font-style: normal;
  font-weight: 500;
  line-height: 1.1;
  margin-right: 21px;
}
.home-line1 {
  flex: 1;
  height: 1px;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: rgba(144, 149, 167, 0.2);
}
.home-workshops {
  flex: 1;
  width: 100%;
  display: flex;
  flex-direction: row;
}
.home-content-container2 {
  flex: 1;
  display: flex;
  align-items: flex-end;
  flex-direction: column;
  justify-content: center;
  background-color: rgba(144, 149, 167, 0.08);
}
.home-container7 {
  flex: 0 0 auto;
  display: flex;
  max-width: 366px;
  align-items: flex-start;
  margin-right: 107px;
  flex-direction: column;
}
.home-text36 {
  margin-bottom: 42px;
}
.home-text39 {
  color: var(--dl-color-scheme-pink);
}
.home-text45 {
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-text46 {
  margin-bottom: var(--dl-space-space-threeunits);
  text-transform: none;
}
.home-image7 {
  width: 55%;
  min-height: 880px;
  object-fit: cover;
  object-position: bottom;
}
.home-previous-events {
  display: flex;
  position: relative;
  flex-direction: column;
  padding-bottom: 150px;
}
.home-max-width4 {
  flex-direction: column;
}
.home-heading-container3 {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-fourunits);
  flex-direction: column;
}
.home-text47 {
  text-align: center;
}
.home-text49 {
  color: var(--dl-color-scheme-darkgray);
  font-style: normal;
  text-align: center;
  font-weight: 500;
}
.home-slider {
  flex: 0 0 auto;
  width: 100%;
  height: 420px;
  display: flex;
  position: relative;
  transition: 0.5s;
  align-items: stretch;
  flex-direction: row;
  justify-content: center;
}
.home-slider-controls {
  top: calc(50% + 24px);
  width: calc(60% + 48px);
  height: 48px;
  display: flex;
  position: absolute;
  align-self: center;
  justify-content: space-between;
}
.home-go-left {
  flex: 0 0 auto;
  width: 48px;
  cursor: pointer;
  height: 48px;
  display: flex;
  z-index: 1;
  transition: 0.3s;
  align-items: center;
  border-color: rgba(144, 149, 167, 0.24);
  border-width: 1px;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-scheme-white);
}
.home-go-left:hover {
  border-color: var(--dl-color-scheme-lightblue);
  background-color: var(--dl-color-scheme-white80);
}
.home-icon {
  width: 24px;
  height: 24px;
  transform: rotate(180deg);
}
.home-go-right {
  flex: 0 0 auto;
  width: 48px;
  cursor: pointer;
  height: 48px;
  display: flex;
  z-index: 1;
  transition: 0.3s;
  align-items: center;
  border-color: rgba(144, 149, 167, 0.24);
  border-width: 1px;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-scheme-white);
}
.home-go-right:hover {
  border-color: var(--dl-color-scheme-lightblue);
  background-color: var(--dl-color-scheme-white80);
}
.home-icon2 {
  width: 24px;
  height: 24px;
}
@media(max-width: 991px) {
  .home-max-width {
    flex-direction: column;
  }
  .home-content-container {
    max-width: 100%;
    margin-bottom: 42px;
  }
  .home-blue-background {
    top: auto;
    width: 100%;
    bottom: 0px;
    min-height: 40%;
  }
  .home-speakers-container {
    grid-template-columns: 1fr 1fr 1fr;
  }
  .home-numbers-container {
    grid-template-columns: 1fr 1fr 1fr;
  }
  .home-location {
    flex-direction: column;
  }
  .home-image6 {
    width: 100%;
  }
  .home-content-container1 {
    padding-top: 0px;
    padding-left: var(--dl-space-space-threeunits);
  }
  .home-container4 {
    margin-top: -100px;
    align-items: center;
  }
  .home-container6 {
    max-width: 100%;
    margin-left: 0px;
  }
  .home-events-container {
    grid-template-columns: 1fr;
  }
  .home-container7 {
    margin-right: var(--dl-space-space-unit);
  }
  .home-image7 {
    width: 50%;
    object-position: left;
  }
  .home-slider-controls {
    width: calc(75% + 48px);
  }
}
@media(max-width: 767px) {
  .home-text {
    font-size: 48px;
  }
  .home-speakers-container {
    grid-template-columns: 1fr 1fr;
  }
  .home-numbers-container {
    grid-template-columns: 1fr 1fr;
  }
  .home-image6 {
    max-height: 100%;
  }
  .home-content-container1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-text16 {
    margin-left: -24px;
  }
  .home-btns-container1 {
    width: 100%;
    align-items: stretch;
    flex-direction: column;
  }
  .home-workshops {
    flex-direction: column-reverse;
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-container7 {
    max-width: 100%;
    padding-top: var(--dl-space-space-twounits);
    margin-right: 0px;
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-image7 {
    width: 100%;
  }
  .home-previous-events {
    padding-bottom: var(--dl-space-space-sixunits);
  }
  .home-slider-controls {
    width: calc(80% + 48px);
  }
}
@media(max-width: 479px) {
  .home-container2 {
    justify-content: center;
  }
  .home-speakers-container {
    grid-template-columns: 1fr;
  }
}
</style>
