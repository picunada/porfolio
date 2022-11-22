<script setup lang="ts">
</script>

<template>
  <div px5>
    <div grid md:grid-cols-1 lg:grid-cols-2 gap10>
      <div>
        <div title1 mt10>
          Daniil Bezuglov
        </div>
        <div caption mt3>
          21 y.o fullstack developer currently working at <a href="https://lockerbot.io/" text-sky icon-btn>Lockerbot.io</a>
        </div>
        <div caption mt3>
          I'm a fast learner. In July I've participated in telegram team <a href="https://ton.org/en/hack-a-ton-1" text-sky icon-btn>hackathon</a>, where in 3 days i wrote an application in a language that is new to me and using new crypto technology we took 2d place with my team(I was responsible for the code).
          Also at my current place of work I implemented new technologies aimed at optimizing business processes and user experience of a product that my hand has touched, I've written a couple of microservices(Vue 3 + Django(DRF)/FastAPI + postgresql stack) myself from start to finish with tips from the team lead.
          At the moment I am passionate in mobile development on iOS(Swift UI, Combine), on my initiative to optimize my company's product we switched from hybrid stack(capacitor.js + Nuxt 3) to native stack(Swift, Swift UI, CoreBluetooth, Combine), in a few weeks i learned new technologies stack and made an mvp application, after that i felled in love with IOS Development.
        </div>
      </div>
      <div flex items-center justify-center mt10>
        <img shadow-xl h-90 rounded-10 src="/photo.jpg">
      </div>
      <div>
        <div title1 mt10>
          Experience
        </div>
        <div>
          <div caption>
            Digital-Spirit
          </div>
          <div caption text-neutral4>
            <h2>
              QA Engineer, 2021/09 - 2022/04
            </h2>
          </div>
          <div text-20px mt3>
            Was testing the bus inside the interbank system, worked with Postman, IBM, Swagger, JS.
          </div>
        </div>
        <div mt5>
          <div caption>
            Lockerbot.io
          </div>
          <div caption text-neutral4>
            <h2>
              Fullstack developer, 2022/04 - Up to now
            </h2>
          </div>
          <div text-20px>
            <p text-neutral4>
              Outsource:
            </p>
            <ul ml3>
              <li>Created an exchange telegram bot (Python, aiogram, postgresql).</li>
              <li>Worked on the backend of the marketplace for private investigators(Django, DRF).</li>
              <li>Created an admin dashboard for billing with RSA signing messages logic, using Vue 3 + Django(DRF) stack.</li>
            </ul>
            <p text-neutral4>
              At company product:
            </p>
            <ul ml3>
              <li>Worked on hybrid mobile app for home postal terminals(Capacitor, Firebase, nuxt.js)</li>
              <li>Creating native IOS app for home postal terminals(SwiftUI, Combine, CoreBluetooth BLE, Firebase)</li>
            </ul>
          </div>
        </div>
      </div>
      <div>
        <div title1 mt10>
          Skills
        </div>
        <div caption>
          <ul>
            <li>Fast learner</li>
            <li>Like when things done in efficient way, when code optimized</li>
            <li text-neutral4>
              My stack:
            </li>
            <ul ml3>
              <li>Python - Django, DRF, Fastapi, Tortoise ORM, aiogram</li>
              <li>JS - Typescript, Vue 3(script setup), Nuxt 3, Pinia or Vuex, Tailwind CSS</li>
              <li>IOS - Swift, SwiftUI, Combine</li>
              <li>VCS - Git</li>
              <li>Others: Postman, Swagger, Docker</li>
            </ul>
          </ul>
        </div>
      </div>
    </div>
    <div title1 mt10>
      Education
    </div>
    <div caption text-neutral4>
      Synergy University, Information security, 2020 - Up to now
    </div>
    <div title1 mt10>
      Side projects
    </div>
    <div caption flex flex-col>
      <span>CSV Generator for purchases information (with fields choice).</span>
      <span>Used Python(FastAPI) for generating csv files.</span>
      <span>Nuxt 3 for frontend.</span>
      Project maintained by myself.
      <span icon-btn text-sky>
        <a href="https://zakupki-data-export.multitender.ru">Project</a>
      </span>
      <span icon-btn text-sky>
        <a href="https://github.com/picunada/zakupki-data-generate">GitHub</a>
      </span>
    </div>
  </div>
</template>
