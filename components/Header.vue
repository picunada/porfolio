<script setup lang="ts">

</script>

<template>
  <nav w-full flex justify-center text-xl py4 px5 backdrop-blur-md bg-opacity-90>
    <div w-full max-w-1390px flex items-center justify-between>
      <div>
        <a class="m0" href="https://t.me/picunada" title="Home">
          <div animation icon-btn opacity-100 flex m0 class="md:text-30px lg:text-40px font-bold">
            Picu<p text-sky>
              nada
            </p>
            ?
          </div>
        </a>
      </div>
      <div flex gap3 items-center>
        <a i-carbon-email md:w5 md:h5 lg:w8 lg:h8 icon-btn href="mailto: xlaystgoku@gmail.com" />
        <a i-carbon-logo-github md:w5 md:h5 lg:w8 lg:h8 icon-btn href="https://github.com/picunada" target="_blank" />
        <a i-cib:linkedin md:w5 md:h5 lg:w8 lg:h8 icon-btn href="https://www.linkedin.com/in/daniil-bezuglov-4b1418234/" />
        <DarkToggle icon-btn />
      </div>
    </div>
  </nav>
</template>
