<template>
<div class="min-h-screen items-center justify-center bg-gray-50">
  <div class=" w-full">
    <div class="md:flex justify-center w-full">     
      <div class="md:flex items-center justify-center md:w-5/12 min-h-screen p-10">
        <form class="mt-8" action="#" method="POST">
              <input type="hidden" name="remember" value="true">

              <div class="text-md leading-8">
                <h2 class="mb-4 block text-2xl leading-8 text-gray-900 mb-8">Log In</h2>
              </div>
              <div class="rounded-md shadow-sm">
                <div>
                   <label for="email" class="m-4 ml-0 block text-sm leading-5 text-gray-900 ">
                    Email Address
                  </label>
                  <input aria-label="Email address" id="email" name="email" type="email" required class="appearance-none rounded-none relative block w-full px-3 py-2 border border-gray-300 placeholder-gray-500 text-gray-900 rounded-t-md focus:outline-none focus:shadow-outline-blue focus:border-blue-300 focus:z-10 sm:text-sm sm:leading-5" placeholder="Email address">
                </div>
                <div class="-mt-px">
                   <label for="password" class="m-4 ml-0 block text-sm leading-5 text-gray-900">
                    Password
                  </label>
                  <input aria-label="Password" id="password" name="password" type="password" required class="appearance-none rounded-none relative block w-full px-3 py-2 border border-gray-300 placeholder-gray-500 text-gray-900 rounded-b-md focus:outline-none focus:shadow-outline-blue focus:border-blue-300 focus:z-10 sm:text-sm sm:leading-5" placeholder="Password">
                </div>
              </div>              

              <div class="mt-6">
                <button type="submit" class="group relative w-full flex justify-center py-2 px-4 border border-transparent text-sm leading-5 font-medium rounded-md text-black bg-gray-400 hover:bg-gray-500 focus:outline-none focus:border-gray-700 focus:shadow-outline-gray active:bg-gray-700 transition duration-150 ease-in-out">
                  Log in
                </button>
              </div>

              <div class="mt-6 flex items-center justify-between">
                <div class="flex items-center">
                   <a href="#" class="text-sm pr-40  focus:outline-none focus:underline transition ease-in-out duration-150">
                    Create an account
                  </a>
                  <a href="#" class="text-sm  focus:outline-none focus:underline transition ease-in-out duration-150">
                    Forgot your password?
                  </a>
                </div>
              </div>

              <div class="mt-6 flex items-center justify-center mt-12">
                <div class="flex items-center">
                   <a href="#" class="text-sm  text-center focus:outline-none focus:underline transition ease-in-out duration-150">
                   Terms of Service & Privacy Policy
                  </a>                
                </div>
              </div>
            </form>
      </div>   
      <div class="flex md:w-7/12 min-h-screen bg-cover bg-loginBgImg items-center justify-center">
            <a href="#" class="text-2xl text-bold text-center text-white">
                   Test Login
              </a>   
      </div>
    </div>
  </div>
 </div>
</template>
