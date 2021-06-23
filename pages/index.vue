<template>
  <div class="grid md:grid-cols-12 lg:grid-cols-7 sm:grid-cols-12 flex h-screen">
    <div class="bg-white shadow-md rounded p-12 m-auto col-start-4 col-span-3">
      <div>
        <p class="text-3xl font-bold">Sign in</p>
        <p class="text-lg">New user? Create an account</p>
      </div>

      <div class="mb-4 space-y-12">
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
          Continue
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
      <p class="text-xs">
        Protected by reCAPTCHA and subject to the Google Privacy Policy and
        Terms of Service.
      </p>
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

body {
  background: url("https://images.unsplash.com/photo-1578836537282-3171d77f8632?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80");
}
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
