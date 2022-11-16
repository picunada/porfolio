<template>
  <main flex flex-col w-screen h-screen>
    <div flex flex-auto w-full>
      <slot />
    </div>

    <div class="p2 mx-auto text-center opacity-70 text-sm">
      <ul flex gap2 items-center>
        <li>@Daniil Bezuglov</li>
        <li flex items-center icon-btn>
          <a href="https://t.me/picunada" flex items-center>
            <div i-cib:telegram-plane mr1 />@picunada
          </a>
        </li>
      </ul>
    </div>
  </main>
</template>
