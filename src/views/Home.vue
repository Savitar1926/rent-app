<template>
  <div class="bg-white h-full w-full px-2 mt-6">
    <form>
      <div>
        <label for="" class="text-asphalt-700">Name:</label>
        <input
          type="text"
          placeholder="John Doe"
          class="bg-gray-50 w-full rounded-xl px-10 py-2 text-xl mt-5 focus:shadow-md focus:text-rent-500"
        />
      </div>
      <div class="mt-5">
        <label for="" class="text-asphalt-700">Model Car:</label>
        <input
          type="text"
          class="bg-gray-50 w-full rounded-xl px-10 py-2 text-xl mt-5 focus:shadow-md focus:text-rent-500"
        />
      </div>
      <div class="mt-5">
        <label for="" class="text-asphalt-700">Plate Number:</label>
        <input
          type="text"
          class="bg-gray-50 w-full rounded-xl px-10 py-2 text-xl mt-5 focus:shadow-md focus:text-rent-500"
        />
      </div>
      <div class="mt-5">
        <label for="" class="text-asphalt-700">Route Available:</label>
        <input
          type="text"
          class="bg-gray-50 w-full rounded-xl px-10 py-2 text-xl mt-5 focus:shadow-md focus:text-rent-500"
        />
      </div>
      <div class="mt-5">
        <button
          class="bg-rent-500 text-white w-full rounded-xl px-10 py-2 text-xl mt-5 active:bg-asphalt-700 "
        >
          Submit
        </button>
      </div>
    </form>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
