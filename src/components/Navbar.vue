<template>
  <div class="nav-container">
    <img class="logo" src="@/assets/logo.png" alt="Workflow" />
    <h1 class="name">Mohamed Omar</h1>
    <span class="w-8"></span>
    <nav class="nav">
      <ul>
        <li>
          <router-link to="/">Home</router-link>
        </li>
        <li>
          <router-link to="/blog">Blog</router-link>
        </li>
        <li>
          <router-link class="text-gray-600" to="/">Contact</router-link>
        </li>
      </ul>
    </nav>
  </div>
</template>

<style>
.nav-container {
  @apply p-5 mt-0 flex items-end justify-between gap-4 border-b border-gray-200;
}

.nav {
  @apply right-0 absolute justify-end tracking-wide mr-4;
}

.nav ul {
  @apply flex gap-4;
}

.nav li {
  @apply inline font-sans hover:underline;
}

.logo {
  @apply h-8 w-auto sm:h-10;
}

.name {
  @apply text-black font-extrabold text-2xl;
}
</style>