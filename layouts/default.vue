<template>
  <div>
    <header class="shadow-sm bg-slate-400">
      <nav class="container mx-auto p-4 flex justify-between">
        <NuxtLink
          to="/"
          class="font-bold text-2xl text-purple-700 rounded-sm mx-auto"
          >Nuxt Ecom</NuxtLink
        >
        <ul class="flex gap-4">
          <li>
            <NuxtLink to="/" class="btn">Home</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about" class="btn">About</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/products" class="btn">Products</NuxtLink>
          </li>
        </ul>
      </nav>
    </header>

    <div class="conatiner mx-auto p-4">
      <slot />
    </div>
  </div>
</template>
