<template>
  <nav class="bg-slate-900 h-20 text-white">
    <RouterLink :to="{name: 'Home'}">Home</RouterLink>
    <RouterLink :to="{name: 'Other'}">Other</RouterLink>
    <RouterLink :to="{name: 'LoginPage'}">Login</RouterLink>
    <RouterLink :to="{name: 'SettingsPage'}">Settings</RouterLink>
    
  </nav>
</template>

<style lang="postcss" scoped>
nav {
  @apply flex justify-center space-x-4;

  & .router-link-active {
    @apply underline underline-offset-4;
  }
}
</style>
