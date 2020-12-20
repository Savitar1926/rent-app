<template>
  <div id="app" class="h-full w-full bg-white p-6">
    <router-view />
    <div
      id="nav"
      class="fixed bottom-5 p-2 font-semibold text-xl text-asphalt-700 w-10/12"
    >
      <div class="w-full flex justify-between">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="#">Home</router-link>
        <router-link to="#">About</router-link>
      </div>
    </div>
  </div>
</template>

<style>
#app {
  font-family: Poppins, sans-serif;
}

#nav a.router-link-exact-active {
  color: #ff5f35;
}
</style>
