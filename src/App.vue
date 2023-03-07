<script setup lang="ts">
import "vue3-carousel/dist/carousel.css";
import { Carousel, Slide, Pagination, Navigation } from "vue3-carousel";
</script>

<template>
  <div
    class="flex flex-col bg-no-repeat bg-cover w-full stars bg-[#FFF6ED] text-[#194027] text-base min-h-full font-raleway lg:items-center"
  >
    <div
      class="all-content flex flex-col max-w-5xl lg:max-w-7xl md:mx-28 p-12 lg:p-24 fade-in font-light"
    >
      <div class="flex flex-col lg:flex-row my-20 items-center">
        <div
          class="my-name flex uppercase text-4xl sm:text-3xl md:text-8xl mb-10 mx-auto text-center font-medium"
        >
          Dahlia <br />
          Salem
        </div>
        <div class="my-image flex">
          <img
            src="@/assets/pic.jpg"
            class="mx-auto sm:max-w-md lg:max-w-xl rounded-t-full object-contain"
          />
        </div>
      </div>
      <div
        class="flex flex-col lg:flex-row justify-around content-center border-t-2 border-[#194027] pt-10 border-opacity-40 mb-60"
      >
        <div class="my-name flex uppercase font-extrabold pr-10 pb-4 lg;pb-0">
          About Dahlia
        </div>
        <div
          class="my-image flex text-xl sm:text-3xl sm:leading-relaxed flex-wrap"
        >
          I am an ex-Google Engineer with more than 4 years of silicon valley
          industry experience, I bring a unique mixture of excellent technical
          ability and excellent communication skills that guarantee the success
          of any project.
        </div>
      </div>
      <div class="flex flex-col lg:flex-row justify-between mb-80">
        <div
          class="my-name flex flex-wrap text-xl sm:text-2xl p-4 lg:w-3/5 lg:mr-8 order-2 lg:order-none"
        >
          At the United Nations, <br /><br />
          I led the first nation-wide initiative to advance STEM education
          across 6 distinct districts in Egypt.<br /><br />
          Under my leadership the ILO was able to deliver a 4-tiered program to
          target weaknesses in the STEM education pipeline at every step of the
          way including high school, college and the ultimate transition to the
          workforce.<br /><br />
          I successfully managed and delivered the 1 million GBP program along
          with powerful stakeholders such as Ministry of Higher Education in
          Egypt and the Foreign, Commonwealth and Development Office in Britain.
        </div>
        <div class="my-image flex p-4 lg:w-2/5 order-1 lg:order-none">
          <img
            src="@/assets/unlogo.png"
            class="object-contain"
            width="400px"
            height="400px"
          />
        </div>
      </div>
      <div class="flex flex-col lg:flex-row justify-between mb-80">
        <div class="my-image flex text-2xl pr-8 lg:w-2/5 lg:mr-8">
          <img
            src="@/assets/google.png"
            class="object-contain"
            width="400px"
            height="400px"
          />
        </div>
        <div
          class="my-name flex flex-wrap text-xl sm:text-2xl max-w-3xl p-4 lg:w-3/5"
        >
          At Google, <br /><br />
          I contributed to the success of two different product teams by
          immediately making strong technical and system design
          contributions.<br /><br />
          At Google Hire I built the backend infrastructure required to reveal
          important data insights to customers as well the backend
          infrastructure responsible for integrating third party tools such as
          HackerRank & Codility. <br /><br />
          At Firebase hosting I built the middleware infrastructure needed to
          create a version-controlled system knows as “Preview Channels” which
          became the fundamental abstraction customers used to interact with the
          service.
        </div>
      </div>
      <div class="flex flex-col lg:flex-row justify-between mb-80">
        <div
          class="my-name flex flex-wrap text-xl sm:text-2xl max-w-3xl p-8 lg:w-3/5 order-2 lg:order-none"
        >
          <p>
            At Yup, <br /><br />
            I was employee number 5 who built the foundational processes
            necessary to hire and manage the schedules of hundreds of online
            tutors distributed around the globe.<br /><br />
            I transitioned into a software engineering role where I co-lead the
            effort to transform our entire web technology stack to from our
            legacy system of backbone.js to a modern and robust stack using
            <a href="https://vuejs.org/" target="_blank" class="underline"
              >Vue Js</a
            >
            and
            <a href="https://webpack.js.org/" target="_blank" class="underline"
              >Webpack</a
            ><br /><br />
            In addition, I designed and implemnted the building blocks of the
            company's reporting infrastructure using AWS and Chartio.
          </p>
        </div>
        <div class="my-image flex text-2xl p-4 lg:w-2/5 order-1 lg:order-none">
          <img
            src="@/assets/yup.svg"
            class="object-contain"
            width="400px"
            height="400px"
          />
        </div>
      </div>
      <div class="flex flex-col lg:flex-row justify-between mb-80">
        <div class="my-image flex text-2xl p-4 lg:w-3/5 rounded-lg">
          <a href="https://planets-proj.vercel.app/" target="_blank">
            <img
              src="@/assets/planet-site-img.png"
              class="object-contain rounded-lg"
            />
          </a>
        </div>
        <div
          class="my-name flex flex-wrap text-xl sm:text-2xl max-w-3xl p-8 lg:w-2/5"
        >
          <span class="font-bold">Planet Facts Site,</span>
          I built a beautiful responsive website to display the latest facts
          about the planets in our universe. <br /><br />
          I used the best in class front-end technologies available.
          <br />
          <p>
            Some of the technoclogies used are:
            <a href="https://vuejs.org/" target="_blank" class="underline"
              >Vue Js</a
            >,
            <a
              href="https://www.typescriptlang.org/"
              target="_blank"
              class="underline"
              >Typescript</a
            >,
            <a
              href="https://tailwindcss.com/docs/installation"
              target="_blank"
              class="underline"
              >Tailwind</a
            >,
            <a href="https://vitejs.dev/" target="_blank" class="underline"
              >Vite</a
            >,
            <a href="https://pinia.vuejs.org/" target="_blank" class="underline"
              >Pinia</a
            >,
            <a
              href="https://router.vuejs.org/"
              target="_blank"
              class="underline"
              >Vue Router</a
            >
          </p>
          <p>
            Checkout the live site:
            <a
              href="https://planets-proj.vercel.app/"
              target="_blank"
              class="underline"
              >here</a
            >
            <br />
            And view the source code:
            <a
              href="https://github.com/dahliasalem/planets-proj#readme"
              target="_blank"
              class="underline"
              >here</a
            >
          </p>
        </div>
      </div>
      <div
        class="carousel-area mb-20 border-t-2 border-[#194027] pt-20 border-opacity-40"
      >
        <div class="text-4xl text-center pb-10">
          What colleagues have to say
        </div>
        <carousel
          :items-to-show="1"
          :items-to-scroll="1"
          :autoplay="3000"
          :pause-autoplay-on-hover="true"
          :wrap-around="true"
        >
          <slide :key="1">
            <div class="flex flex-col p-14">
              <div class="flex image-area pb-10">
                <img
                  src="@/assets/vijay.jpeg"
                  alt=""
                  class="w-24 h-24 rounded-full"
                />
              </div>
              <div class="flex text-xl text-start pb-6">
                Dahlia added tremendous value at Yup by quickly ramping up,
                participating and eventually co-leading some projects such as
                the migration to Vue js as well as the company-wide
                reporting/analytics systems. I was impressed by her ability to
                learn new technologies, versatility with technology, as well as
                working closely with her teammates. I would definitely work with
                her again
              </div>
              <div class="flex title-area">
                Vijaykumar Krishnaswamy - Engineering Manager @ Yup
              </div>
            </div>
          </slide>
          <slide :key="2">
            <div class="flex flex-col p-14">
              <div class="flex image-area pb-10">
                <img
                  src="@/assets/ziyad.jpeg"
                  alt=""
                  class="w-24 h-24 rounded-full"
                />
              </div>
              <div class="flex text-xl text-start pb-6">
                Dahlia was a amazing contributor on our team, in terms of her
                direct technical contributions but also in terms of her indirect
                effect she had on the surrounding team. Her teammates felt her
                enthusiasm, positive attitude and willingness to ship which in
                turn led to productivity improvements for surrounding engineers.
              </div>
              <div class="flex title-area">
                Ziyad Mir- Senior Engineer @ Google
              </div>
            </div>
          </slide>
          <slide :key="3">
            <div class="flex flex-col p-14">
              <div class="flex image-area pb-10">
                <img
                  src="@/assets/aaron.jpeg"
                  alt=""
                  class="w-24 h-24 rounded-full"
                />
              </div>
              <div class="flex text-xl text-start pb-6">
                Dahlia joined Yup when she was only 18 years old and worked
                under my supervision on the tutor operations team. Despite being
                the youngest person on the team, she was one of our strongest
                early hires due to both her eagerness to contribute as well as
                her hunger to learn. Over the years, Dahlia made impactful
                contributions to our tutor scheduling system and our tutor
                hiring process, which we still use till today. We were very sad
                to let her go to Google but incredibly proud of her impressive
                growth and numerous achievements.
              </div>
              <div class="flex title-area">Aaron Price - CEO @ Yup</div>
            </div>
          </slide>
          <slide :key="4">
            <div class="flex flex-col p-14">
              <div class="flex image-area pb-10">
                <img
                  src="@/assets/bleigh.jpeg"
                  alt=""
                  class="w-24 h-24 rounded-full"
                />
              </div>
              <div class="flex text-xl text-start pb-6">
                Dahlia ramped up quickly and was a solid contributor to our
                team. She asked incisive questions about both technical and
                product issues that helped us identify potential issues, and
                worked collaboratively with her colleagues. I'd definitely work
                with Dahlia again!
              </div>
              <div class="flex title-area">
                Michael Bleigh - Engineering Manager @ Google
              </div>
            </div>
          </slide>

          <template #addons>
            <navigation />
            <pagination />
          </template>
        </carousel>
      </div>
      <div
        class="flex flex-col contact info border-t-2 border-[#194027] py-32 border-opacity-40"
      >
        <div class="text-5xl text-center pb-10">Get in touch.</div>
        <p class="text-xl text-center break-words">dahliaosalem@gmail.com</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.fade-in {
  animation: fadeIn 2s;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
