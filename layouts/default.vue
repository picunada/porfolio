<template>
  <main flex flex-col w-screen h-screen items-center relative overflow-auto>
    <Header sticky top-0 absolute />
    <div flex flex-col flex-1 w-full max-w-1390px>
      <slot />
    </div>

    <div class="p2 mb4 pt4 mx-auto text-center opacity-70 text-sm">
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
