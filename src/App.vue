<template>
  <div id="app" class="h-full w-full bg-asphalt-900 p-6">
    <div
      id="nav"
      class="fixed bottom-4 flex items-center p-2 font-semibold text-xl text-white"
    >
      <router-link to="/" class="mr-10">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>
    <router-view class="mt-10" />
  </div>
</template>

<style>
#app {
  font-family: Poppins, sans-serif;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
