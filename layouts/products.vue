<template>
  <div>
    <header class="shadow-sm bg-slate-400">
      <nav class="container mx-auto p-4 flex justify-between">
        <NuxtLink
          to="/"
          class="font-bold text-2xl text-purple-700 rounded-sm mx-auto"
          >Nuxt Ecom</NuxtLink
        >
      </nav>
    </header>

    <div class="conatiner mx-auto p-4">
      <slot />
    </div>

    <footer class="container mx-auto p-4 flex justify-between border-t-2">
      <ul class="flex gap-4 text-purple-700">
        <li>
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about">About</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/products">Products</NuxtLink>
        </li>
      </ul>
    </footer>
  </div>
</template>
