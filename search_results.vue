<template>
    <div class="w-[87%] bg-dark-darker overflow-scroll">
      <!-- Encabezado -->
      <div class="flex justify-between px-10 py-4 bg-black sticky top-0 z-20">
        <!-- Barra de búsqueda -->
        <div class="flex gap-x-5 items-center">
          <!-- Botones de navegación -->
          <div class="space-x-2">
            <button class="p-[0.20rem] bg-dark-light rounded-full">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5L8.25 12l7.5-7.5" />
              </svg>
            </button>
            <button class="p-[0.20rem] bg-dark-light rounded-full">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
              </svg>
            </button>
          </div>
          <!-- Barra de búsqueda -->
          <div class="relative">
            <input class="w-72 pl-10 pr-5 outline-none rounded-full h-10 text-black" type="text" placeholder="¿Qué quieres escuchar?">
            <div class="absolute top-2 left-3 text-black">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
              </svg>
            </div>
          </div>
        </div>
        <!-- Botones de mejora de cuenta -->
        <div class="flex gap-x-2">
          <button class="button-bordered">
            Mejora tu cuenta
          </button>
          <button class="h-8 flex items-center gap-x-1 pr-3 pl-[0.18rem] rounded-full text-sm font-semibold bg-dark hover:bg-neutral-900">
            <div class="w-7 h-7 rounded-full overflow-hidden"><img src="/images/avatar.jpeg" alt=""></div>
            <div>Jairo</div>
            <div>
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5" />
              </svg>
            </div>
          </button>
        </div>
      </div>
      <!-- Contenido principal -->
      <div class="px-10 pt-8 pb-28">
        <!-- Filtros -->
        <div class="flex gap-x-1">
          <div class="px-3 py-1 bg-light-primary text-black rounded-full">
            Todo
          </div>
          <div class="px-3 py-1 bg-dark-light rounded-full">
            Artista
          </div>
          <div class="px-3 py-1 bg-dark-light rounded-full">
            Género
          </div>
          <div class="px-3 py-1 bg-dark-light rounded-full">
            Álbumes
          </div>
        </div>
        <!-- Resultados -->
        <div class="flex flex-col lg:flex-row gap-x-5 gap-y-5 mt-5">
          <!-- Resultado principal -->
          <div class="w-full lg:w-2/5 ">
            <h2 class="text-light-primary text-2xl font-bold">
              Resultado principal
            </h2>
            <div class="mt-5 p-4 space-y-5 bg-dark-lighter rounded">
              <div>
                <img class="w-28 rounded-rounded-full" src="C:\Users\brenn\Downloads\santos.jpg" alt="">
              </div>
              <div>
                <h2 class="text-light-primary text-3xl font-bold">Romeo Santos</h2>
              </div>
              <div class="flex">
                <div class="px-3 py-1 font-semibold bg-dark-light rounded-full">
                  Artista
                </div>
              </div>
            </div>
          </div>
          <!-- Lista de canciones -->
          <div class="w-full lg:w-3/5">
            <h2 class="text-light-primary text-2xl font-bold">
              Canciones
            </h2>
            <div class="mt-5">
              <!-- Ejemplo de lista de canciones -->
              <!-- Debes agregar aquí tu lógica para mostrar las canciones -->
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  import Like from '../components/Like.vue';
  </script>
  
