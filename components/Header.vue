<script setup lang="ts">

</script>

<template>
  <nav w-full flex justify-center text-xl py4 px5 backdrop-blur>
    <div w-full max-w-1390px flex items-center justify-between>
      <div>
        <RouterLink class="m0" to="/" title="Home">
          <div animation icon-btn opacity-100 flex m0 class="text-24px font-bold">
            Picun<p text-sky>
              ada
            </p>
          </div>
        </RouterLink>
      </div>
      <div flex gap3 items-center>
        <a i-carbon-logo-github icon-btn href="https://github.com/picunada" target="_blank" />
        <DarkToggle icon-btn />
      </div>
    </div>
  </nav>
</template>
