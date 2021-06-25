<template>
  <div
    class="grid md:grid-cols-12 lg:grid-cols-7 sm:grid-cols-12 flex h-screen"
  >
    <div class="bg-white shadow-md rounded p-16 m-auto lg:col-start-4 lg:col-span-3 sm:col-span-11 ">
      <div>
        <p class="text-3xl font-bold mb-2">Sign in</p>
      </div>
      <div class="flex space-x-3">
        <div><p class="text-lg">New user?</p></div>
        <div>
          <a
            class="createLink inline-block text-sm font-semibold align-text-bottom"
            href="#"
            rel=""
          >
            Create an account
          </a>
        </div>
      </div>
      <div class="mb-4 space-y-1">
        <p class="text-xs py-8 pb-0 emailLabel">Email address</p>
        <input
          class="
            border
            rounded-b-none
            w-full
            py-0
            pb-0
            px-3
            text-grey-darker
            emailInput
          "
          id="email"
          type="text"
        />
      </div>

      <div class="flex  justify-end">
        <a
          href=""
          class="text-xs bg-blue-500 rounded-full font-bold text-white px-4 py-2 my-10 transition duration-300 ease-in-out hover:bg-blue-600"
        >
          Continue
        </a>
      </div>
      <div>
        <h2><span>Or</span></h2>
      </div>
      <div class="flex flex-col ...">
        <div class="flex justify-center my-2 ">
          <button
            class=" w-full bg-white hover:bg-gray-100 text-gray-800 text-sm font-semibold py-4 px-4 border border-gray-400 rounded-full inline-flex justify-center"
          >
          <img class="icons w-4 h-1 mr-3" :src="require(`~/assets/google.png`)" />
            <span>continue with Google </span>
          </button>
        </div>
        <div class="flex my-2 content-center">
          <button
            class=" w-full bg-blue-500 hover:bg-blue-700 text-white text-sm font-bold py-4 px-4 inline-flex rounded-full justify-center "
          >
            <img class="icons w-4 h-1 mr-3" :src="require(`~/assets/facebook.png`)" />
            <span>Continue with Facebook</span>
          </button>
        </div>
        <div class="flex justify-center my-2">
          <button
            class=" w-full bg-black hover:bg-gray-500 text-white text-sm font-semibold py-4 px-4 border border-gray-400 inline-flex rounded-full justify-center"
          >
            <img class="icons w-4 h-1 mr-3" :src="require(`~/assets/apple.png`)" />
            <span>Continue with Apple</span>
          </button>
        </div>
      </div>

      <p class="text-xs my-5">
        Protected by reCAPTCHA and subject to the Google
        <a class="text-blue-500" href="http://link">Privacy Policy</a> and
        <a class="text-blue-500" href="http://link">Terms of service.</a>
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
.createLink {
  color: #1473e6;
}
.emailInput {
  border: 0;
  outline: 0;
  background: transparent;
  border-bottom: 1px solid rgb(202, 202, 202);
}
.emailLabel {
  color: rgb(129, 129, 129);
}
h2 {
  width: 100%;
  text-align: center;
  border-bottom: 1px solid rgb(202, 202, 202);
  line-height: 0.1em;
  margin: 10px 0 20px;
}

h2 span {
  background: #fff;
  padding: 0 10px;
  color: rgb(87, 87, 87);
}
.icons{
  width: 16px;
  height: 16px;
  margin-top: 3.5px;
  }
</style>
