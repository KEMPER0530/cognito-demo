<template>
  <div class="m-auto flex justify-center min-h-screen items-center text-center bg-black">
      <div>
        <div class="flex flex-col">
          <button class="py-4 px-8 mt-8 text-2xl text-gray-50 bg-red-500 hover:bg-red-600 focus:ring-red-600 focus:ring-offset-red-600 text-white transition ease-in duration-200 text-center font-semibold shadow-md focus:outline-none focus:ring-2 focus:ring-offset-2 rounded-full" @click.prevent="$auth.logout()">Logout</button>
        </div>
      </div>
  </div>
</template>
