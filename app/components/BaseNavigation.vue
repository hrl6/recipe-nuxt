<template>
  <header class="container">
    <nav class="flex justify-between items-center py-2">
      <NuxtLink to="/">
        <NuxtImg width="96px" src="/logo-v2-makan-kitchen.png" alt="Logo" densities="x1" format="webp" />
      </NuxtLink>
      <ul class="flex gap-4 font-bold">
        <li>
          <NuxtLink to="/">
            Home
          </NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about">
            About
          </NuxtLink>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script setup lang="ts">

</script>