<template>
  <div>
    <header class="shadow-sm bg-slate-400">
      <nav class="container mx-auto p-4 flex justify-between">
        <NuxtLink
          to="/"
          class="font-bold text-2xl text-purple-700 rounded-sm mx-auto"
          >Nuxt Ecom</NuxtLink
        >
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
      </nav>
    </header>
    <div class="conatiner mx-auto p-4">
      <slot />
    </div>
  </div>
</template>
