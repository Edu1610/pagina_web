<template>
    <div class="w-[87%] bg-dark-darker overflow-scroll">
      <div class="flex justify-between px-10 py-4 bg-black sticky top-0 z-20">
        <div class="flex gap-x-5 items-center">
          <div class="space-x-2">
            <button class="p-[0.20rem] bg-dark-light rounded-full">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6"
              >
                <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5L8.25 12l7.5-7.5" />
              </svg>
            </button>
            <button class="p-[0.20rem] bg-dark-light rounded-full">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6"
              >
                <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
              </svg>
            </button>
          </div>
          <div class="relative">
            <input
              class="w-72 pl-10 pr-5 outline-none rounded-full h-10 text-black"
              type="text"
              placeholder="¿Qué quieres escuchar?"
            />
            <div class="absolute top-2 left-3 text-black">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z"
                />
              </svg>
            </div>
          </div>
        </div>
        <div class="flex gap-x-2">
          <button class="button-bordered">
            Mejora tu cuenta
          </button>
          <button
            class="h-8 flex items-center gap-x-1 pr-3 pl-[0.18rem] rounded-full text-sm font-semibold bg-dark hover:bg-neutral-900"
          >
            <div class="w-7 h-7 rounded-full overflow-hidden">
              <img src="C:\Users\brenn\Downloads\santos.jpg" alt="" />
            </div>
            <div>Romeo Santos</div>
            <div>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-4 h-4"
              >
                <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5" />
              </svg>
            </div>
          </button>
        </div>
      </div>
  
      <div class="px-10 pt-14 pb-28">
        <div class="flex justify-between">
          <h2>
            <a href="#" class="text-light-primary text-2xl font-bold hover:underline">Búsquedas recientes</a>
          </h2>
          <button class="font-bold text-light-secondary text-sm hover:underline">Mostrar todos</button>
        </div>
  
        <div class="mt-8 grid grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 2xl:grid-cols-6 3xl:grid-cols-8 gap-x-5">
          <Tile title="Romeo Santos" sub-title="Artista" image="C:\Users\brenn\Downloads\santos.jpg" />
          <Tile title="Bad bunny" sub-title="Album" image="C:\Users\brenn\Downloads\verano.jpg" />
          <Tile title="50cent" sub-title="Artista" image="C:\Users\brenn\Downloads\50.jpg"/>
        </div>
  
        <div class="mt-5 flex justify-between">
          <h2>
            <a href="#" class="text-light-primary text-2xl font-bold hover:underline">Búsquedas recientes</a>
          </h2>
          <button class="font-bold text-light-secondary text-sm hover:underline">Mostrar todos</button>
        </div>
  
        <div class="mt-4 grid grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 2xl:grid-cols-6 3xl:grid-cols-8 grid-rows-6 gap-3">
          <!-- Contenido omitido por brevedad -->
        </div>
      </div>
    </div>
  </template>
  
<script setup>
import Tile from '../components/Tile.vue'; // Corregir la ruta para importar el componente Tile
</script>
  
