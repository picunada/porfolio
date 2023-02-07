<script setup lang="ts">
</script>

<template>
  <div xl:flex md:grid md:grid-cols-1 gap-5 p4>
    <div grid grid-cols-1 items-start>
      <div flex items-center justify-center mt10>
        <img shadow-xl h-70 rounded-6 src="/photo.jpeg">
      </div>
      <div>
        <div title1 mt10>
          Daniil Bezuglov
        </div>
        <div caption>
          21 y.o fullstack developer currently working at <a href="https://lockerbot.io/" text-sky icon-btn font-bold>Lockerbot.io</a>
        </div>
        <div title1 mt3>
          Career objective
        </div>
        <div caption>
          Problem solver eager to grow as software engineer in emerging company. Motivated to advance and expand my skill set through mentorship and challenging projects.
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

    <div grid md:grid-cols-1 lg:grid-cols-2 gap10>
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
              QA Engineer, 2020/09 - 2021/04
            </h2>
          </div>
          <div mt3>
            Tested the code for Interbank Bus System.
          </div>
          <div>
            Cooperated with the development team to improve system resilience.
          </div>
          <div>
            Worked with creating mock data classes for testing environment.
          </div>
        </div>
        <div mt5>
          <div caption1>
            Lockerbot.io
          </div>
          <div text-neutral4>
            <h2>
              Fullstack developer, 2021/04 - Up to now
            </h2>
          </div>
          <div mt3>
            <div>
              Worked in a startup team where I brought projects from start to finish. Participated in all stages of development. Cooperated with the team to improve the quality of the product.
            </div>

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
          Education
        </div>
        <div caption1>
          Synergy University, B.S Computer Science, 2020 - Up to now
        </div>
        <div title1 mt3>
          Projects
        </div>
        <div flex flex-col>
          <span caption2>CSV Generator for purchases information (with fields choice).</span>
          <ul ml3 text-neutral4>
            <li>Used Python(FastAPI) for generating csv files.</li>
            <li>Nuxt 3 for frontend.</li>
          </ul>
          Project maintained by myself.
          <span icon-btn text-sky font-bold>
            <a href="https://zakupki-data-export.multitender.ru">Project</a>
          </span>
          <span icon-btn text-sky font-bold>
            <a href="https://github.com/picunada/zakupki-data-generate">GitHub</a>
          </span>
        </div>
        <div title1 mt3>
          Additional achievements
        </div>
        <div flex flex-col>
          <a caption2 font-bold icon-btn text-sky href="https://ton.org/en/hack-a-ton-1">TON Foundation hackathon 2nd place 10K$ award.</a>
          <div caption2 text-sky font-bold>
            (Tetrapak team)
          </div>
          <div>Have done great work with main objective of hackathon. We have perfectly identified the main advantages of the new TON technology and implemented it in our project. I put the idea of our project into the code.  </div>
        </div>
      </div>
    </div>
  </div>
</template>
