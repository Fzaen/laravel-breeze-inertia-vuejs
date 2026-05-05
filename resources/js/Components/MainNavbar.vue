<template>
  <nav class="flex justify-center items-center min-h-screen bg-black">
    <div class="flex items-center px-6 py-2 rounded-full border border-gray-700 shadow-lg bg-black/80 backdrop-blur-md"
         style="box-shadow: 0 0 24px 2px #fff2, 0 0 0 1px #222 inset;">
      <!-- Logo -->
      <div class="mr-8 flex items-center">
        <div class="w-8 h-8 flex flex-col justify-center items-center">
          <div class="w-2 h-2 bg-white rounded-full mb-1"></div>
          <div class="flex space-x-1">
            <div class="w-2 h-2 bg-white rounded-full"></div>
            <div class="w-2 h-2 bg-white rounded-full"></div>
          </div>
          <div class="w-2 h-2 bg-white rounded-full mt-1"></div>
        </div>
      </div>
      <!-- Main Nav Links -->
      <ul class="flex items-center space-x-6 text-white font-medium">
        <li class="relative group">
          <button class="focus:outline-none">Products</button>
          <ul class="absolute left-0 top-full mt-2 w-40 bg-black border border-gray-700 rounded-lg shadow-lg opacity-0 group-hover:opacity-100 group-hover:visible invisible transition-all z-20">
            <li class="px-4 py-2 hover:bg-gray-800 cursor-pointer relative group">
              Product A
              <ul class="absolute left-full top-0 mt-0 ml-2 w-40 bg-black border border-gray-700 rounded-lg shadow-lg opacity-0 group-hover:opacity-100 group-hover:visible invisible transition-all z-30">
                <li class="px-4 py-2 hover:bg-gray-800 cursor-pointer">Sub Product A1</li>
                <li class="px-4 py-2 hover:bg-gray-800 cursor-pointer">Sub Product A2</li>
              </ul>
            </li>
            <li class="px-4 py-2 hover:bg-gray-800 cursor-pointer">Product B</li>
          </ul>
        </li>
        <li class="relative group">
          <button class="focus:outline-none">Stories</button>
          <ul class="absolute left-0 top-full mt-2 w-40 bg-black border border-gray-700 rounded-lg shadow-lg opacity-0 group-hover:opacity-100 group-hover:visible invisible transition-all z-20">
            <li class="px-4 py-2 hover:bg-gray-800 cursor-pointer">Story 1</li>
            <li class="px-4 py-2 hover:bg-gray-800 cursor-pointer">Story 2</li>
          </ul>
        </li>
        <li class="relative group">
          <button class="focus:outline-none">Pricing</button>
          <ul class="absolute left-0 top-full mt-2 w-40 bg-black border border-gray-700 rounded-lg shadow-lg opacity-0 group-hover:opacity-100 group-hover:visible invisible transition-all z-20">
            <li class="px-4 py-2 hover:bg-gray-800 cursor-pointer">Basic</li>
            <li class="px-4 py-2 hover:bg-gray-800 cursor-pointer">Pro</li>
          </ul>
        </li>
        <li class="relative group">
          <button class="focus:outline-none">Docs</button>
          <ul class="absolute left-0 top-full mt-2 w-40 bg-black border border-gray-700 rounded-lg shadow-lg opacity-0 group-hover:opacity-100 group-hover:visible invisible transition-all z-20">
            <li class="px-4 py-2 hover:bg-gray-800 cursor-pointer">API</li>
            <li class="px-4 py-2 hover:bg-gray-800 cursor-pointer">Guides</li>
          </ul>
        </li>
      </ul>
      <!-- Spacer -->
      <div class="flex-1"></div>
      <!-- Contact & Get Started -->
      <div class="flex items-center space-x-3 ml-8">
        <button class="px-6 py-2 rounded-full border border-gray-700 text-white bg-black/80 hover:bg-gray-900 transition">Contact</button>
        <button class="px-6 py-2 rounded-full bg-white text-black font-semibold shadow-lg focus:outline-none" style="box-shadow: 0 0 16px 2px #fff5;">Get Started</button>
      </div>
    </div>
  </nav>
</template>

<script setup>
// No logic for now, just static nav
</script>
