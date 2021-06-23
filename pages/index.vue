<template>
  <div class="container mx-auto"  style="background-image: url('~assets/background.jpg')">
    <div class="grid grid-cols-6 gap-4">
      <!-- <div class="col-start-2 col-span-4 ..."> -->
      <div
        class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4 flex flex-col"
       
      >
        <div class="mb-4">
          <label
            class="block text-grey-darker text-sm font-bold mb-2"
            for="username"
          >
            Username
          </label>
          <input
            class="
              shadow
              appearance-none
              border
              rounded
              w-full
              py-2
              px-3
              text-grey-darker
            "
            id="username"
            type="text"
            placeholder="Username"
          />
        </div>
        <div class="mb-6">
          <label
            class="block text-grey-darker text-sm font-bold mb-2"
            for="password"
          >
            Password
          </label>
          <input
            class="
              shadow
              appearance-none
              border border-red
              rounded
              w-full
              py-2
              px-3
              text-grey-darker
              mb-3
            "
            id="password"
            type="password"
            placeholder="******************"
          />
          <p class="text-red text-xs italic">Please choose a password.</p>
        </div>
        <div class="flex items-center justify-between">
          <button
            class="
              bg-blue
              hover:bg-blue-dark
              text-white
              font-bold
              py-2
              px-4
              rounded
            "
            type="button"
          >
            Sign In
          </button>
          <a
            class="
              inline-block
              align-baseline
              font-bold
              text-sm text-blue
              hover:text-blue-darker
            "
            href="#"
          >
            Forgot Password?
          </a>
        </div>
        <!-- </div> -->
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
