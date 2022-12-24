<script setup lang="ts">
</script>

<template>
  <div px5>
    <div grid md:grid-cols-1 lg:grid-cols-2 gap10>
      <div>
        <div title1 mt10>
          Daniil Bezuglov
        </div>
        <div caption2 mt3>
          21 y.o fullstack developer currently working at <a href="https://lockerbot.io/" text-sky icon-btn>Lockerbot.io</a>
        </div>
        <div title1 mt3>
          About me
        </div>
        <div caption2 mt3>
          I started studying computer science 2 years ago, for a very long time I could not find a job due to lack of experience in commercial development. My first job was as a QA engineer, but half a year later I realized I wanted to be a developer. Luckily I was able to get into a small startup team.
        </div>
        <div caption2 mt3>
          I worked on the outsource and the projects of the team, and at first I used a development stack that the head of the team demanded. But with the experience I gained and my interest in development, I started making decisions about the development stack in our projects. When I had the task to make a mobile app for our startup the choice fell on the hybrid stack, I got interested and dug deeper into articles on mobile development. After reading the material, I insisted on switching to a native stack. In 3 months I was able to write an app in a language and development environment that was new to me. I really enjoyed IOS development, so I want to become a full-fledged IOS developer.
        </div>
        <div caption2 mt3>
          I'm a fast learner. I adapt quickly to new technologies, in a 3 day <a href="https://ton.org/en/hack-a-ton-1" text-sky icon-btn>hackathon</a> using new technologies I took second place. I am not afraid to ask when I don't know something. Not knowing is just a state that needs to be changed.
        </div>
      </div>
      <div flex items-center justify-center mt10>
        <img shadow-xl h-110 rounded-10 src="/photo.jpeg">
      </div>
      <div>
        <div title1 mt10>
          Experience
        </div>
        <div>
          <div caption1>
            Digital-Spirit
          </div>
          <div caption text-neutral4>
            <h2>
              QA Engineer, 2021/09 - 2022/04
            </h2>
          </div>
          <div mt3>
            Was testing the bus inside the interbank system, worked with Postman, IBM, Swagger, JS.
          </div>
        </div>
        <div mt5>
          <div caption1>
            Lockerbot.io
          </div>
          <div text-neutral4>
            <h2>
              Fullstack developer, 2022/04 - Up to now
            </h2>
          </div>
          <div mt3>
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
    <div caption1>
      Synergy University, Information security, 2020 - Up to now
    </div>
    <div title1 mt10>
      Side projects
    </div>
    <div caption2 flex flex-col>
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
