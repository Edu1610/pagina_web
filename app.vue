<template>
  <div class="relative h-screen flex text-black">

 <!-- barra lateral -->
    <div class="w-[13%] px-5 pt-6 bg-white g border  text-sm font-medium">
      <img src="C:\Users\brenn\Downloads\logos.jpg">

 
      <div class="mt-10 space-y-4">
        <button class="flex gap-x-3" >
          Inicio
          <img src="C:\Users\brenn\Downloads\inicio.png" width="25" height="20" >
        </button>
        <button class="flex gap-x-3">
          Buscar
          <img src="C:\Users\brenn\Downloads\lupa.png" width="25" height="20">
        </button>
        <button class="flex gap-x-3">
          Tu biblioteca
          <img src="C:\Users\brenn\Downloads\lista.jpg" width="25" height="20">
        </button>
        <button class="flex gap-x-4">
        nueva lista
        <img src="C:\Users\brenn\Downloads\mas.png" width="25" height="20" >
        </button>
      <button class="flex gap-x-4"> me encanta 
        <img src="C:\Users\brenn\Downloads\encanta.jpg" width="25" height="20">
      </button>
      </div>
 <!-- barra lateral  -->
      <hr class="mt-5 border-gray-700">

      <div class="mt-5 font-normal">
        <div>Español</div>
      </div>
    </div>

   <!-- contenido -->

   <div class="w-[87%] bg-white overflow-scroll">


  <div class="flex justify px-10 py-4 bg-amarillo-verdoso sticky top-0 z-10">

    <div class="space-x-2">
      <button><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5">
  <path fill-rule="evenodd" d="M17 4.25A2.25 2.25 0 0 0 14.75 2h-5.5A2.25 2.25 0 0 0 7 4.25v2a.75.75 0 0 0 1.5 0v-2a.75.75 0 0 1 .75-.75h5.5a.75.75 0 0 1 .75.75v11.5a.75.75 0 0 1-.75.75h-5.5a.75.75 0 0 1-.75-.75v-2a.75.75 0 0 0-1.5 0v2A2.25 2.25 0 0 0 9.25 18h5.5A2.25 2.25 0 0 0 17 15.75V4.25Z" clip-rule="evenodd" />
  <path fill-rule="evenodd" d="M14 10a.75.75 0 0 0-.75-.75H3.704l1.048-.943a.75.75 0 1 0-1.004-1.114l-2.5 2.25a.75.75 0 0 0 0 1.114l2.5 2.25a.75.75 0 1 0 1.004-1.114l-1.048-.943h9.546A.75.75 0 0 0 14 10Z" clip-rule="evenodd" />
       </svg>
       </button>
      <button ><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5">
  <path fill-rule="evenodd" d="M3 4.25A2.25 2.25 0 0 1 5.25 2h5.5A2.25 2.25 0 0 1 13 4.25v2a.75.75 0 0 1-1.5 0v-2a.75.75 0 0 0-.75-.75h-5.5a.75.75 0 0 0-.75.75v11.5c0 .414.336.75.75.75h5.5a.75.75 0 0 0 .75-.75v-2a.75.75 0 0 1 1.5 0v2A2.25 2.25 0 0 1 10.75 18h-5.5A2.25 2.25 0 0 1 3 15.75V4.25Z" clip-rule="evenodd" />
  <path fill-rule="evenodd" d="M6 10a.75.75 0 0 1 .75-.75h9.546l-1.048-.943a.75.75 0 1 1 1.004-1.114l2.5 2.25a.75.75 0 0 1 0 1.114l-2.5 2.25a.75.75 0 1 1-1.004-1.114l1.048-.943H6.75A.75.75 0 0 1 6 10Z" clip-rule="evenodd" />
       </svg>
       </button>
    </div>
    <div>

      <button class= "px-2 py-1 border-black hover:border-gray-400 rounded-full text-sm font-semibold hover:scale-105">Mejora tu cuenta</button>
      <button class="py-1  rounded-full text-sm font-semibold bg-neutral-500 hover:scale-105">
        <div></div>
        <div>Eduardo</div>
        <div></div>

      </button>

    </div>

  </div>


<!-- contenido fin  -->

  <div class="px-10 pt-14 pb-28">
    <div class="flex justify-between">
      <h2 class="text-2xl font-bold">Escuchados recientemente</h2>
      <button class="font-bold text-black text-sm hover:underline">Mostrar todos</button>
    </div>
    

    <div class="grid grid-cols-5 gap-4">
      <!-- cuadro 1 inicio -->
      <div class="h-[17rem]  bg-amarillo-verdoso rounded">
        <div class=" group h-[17rem] bg-amarillo-verdoso rounded">
          <div class="relative">
          <img class="mx-auto mt-4 rounded-full" src="C:\Users\brenn\Downloads\santos.jpg">
          <button class="absolute right-4 bottom-19 opacity-0 group-hover:opacity-100 translate-y-5 group-hover:translate-y-0 transition"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10">
  <path stroke-linecap="round" stroke-linejoin="round" d="m12.75 15 3-3m0 0-3-3m3 3h-7.5M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
</svg>
</button>
          <div class="mx-5 mt-4">
            <h3 class="font-bold">Romeo Santos</h3>
            <p class="text-sm text-black">Artista</p>
          </div>
        </div>
      </div>
    </div>
      <!-- cuadro 1 fin -->

      <!-- cuadro 2 inicio -->
      <div class="h-[17rem] bg-amarillo-verdoso rounded">
  <div class="h-[17rem] bg-amarillo-verdoso rounded relative">
    <img class="mx-auto mt-4 rounded-full" src="C:\Users\brenn\Downloads\barrio.jpg">
    <button class="absolute right-4 bottom-19 opacity-0 group-hover:opacity-100 translate-y-5 group-hover:translate-y-0 transition">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="m12.75 15 3-3m0 0-3-3m3 3h-7.5M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
</svg>
</button>
    <div class="mx-5 mt-4">
      <h3 class="font-bold">Barrio Fino</h3>
      <p class="text-sm text-black">Album</p>
    </div>
  </div>
</div>
      <!-- cuadro 2 fin -->

      <!-- cuadro 3 inicio -->
      <div class="h-[17rem] bg-amarillo-verdoso rounded">
        <div class="h-[17rem] bg-amarillo-verdoso rounded">
          <div class="relative">
          <img class="mx-auto mt-4 rounded-full" src="C:\Users\brenn\Downloads\omar.jpg">
          <button class="absolute right-4 bottom-19 opacity-0 group-hover:opacity-100 translate-y-5 group-hover:translate-y-0 transition"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10">
  <path stroke-linecap="round" stroke-linejoin="round" d="m12.75 15 3-3m0 0-3-3m3 3h-7.5M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
</svg>
</button>
          <div class="mx-5 mt-4">
            <h3 class="font-bold">Don Omar</h3>
            <p class="text-sm text-black">Artista</p>
          </div>
        </div>
      </div>
    </div>
      <!-- cuadro 3 fin -->

      <!-- cuadro 4 inicio -->
      <div class="h-[17rem] bg-amarillo-verdoso rounded">
        <div class="h-[17rem] bg-amarillo-verdoso rounded">
          <div class="relative">
          <img class="mx-auto mt-4 rounded-full" src="C:\Users\brenn\Downloads\verano.jpg">
          <button class="absolute right-4 bottom-19 opacity-0 group-hover:opacity-100 translate-y-5 group-hover:translate-y-0 transition"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10">
  <path stroke-linecap="round" stroke-linejoin="round" d="m12.75 15 3-3m0 0-3-3m3 3h-7.5M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
</svg>
</button>
          <div class="mx-5 mt-4">
            <h3 class="font-bold">Verano sin ti</h3>
            <p class="text-sm text-black">Album</p>
          </div>
        </div>
      </div>
    </div>
      <!-- cuadro 4 fin -->

       <!-- cuadro 5 inicio -->
       <div class="h-[17rem] bg-amarillo-verdoso rounded">
        <div class="h-[17rem] bg-amarillo-verdoso rounded">
        <div class="relative">
          <img class="mx-auto mt-4 rounded-full" src="C:\Users\brenn\Downloads\50.jpg">
          <button class="absolute right-4 bottom-19 opacity-0 group-hover:opacity-100 translate-y-5 group-hover:translate-y-0 transition"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10">
  <path stroke-linecap="round" stroke-linejoin="round" d="m12.75 15 3-3m0 0-3-3m3 3h-7.5M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
</svg>
</button>
          <div class="mx-5 mt-4">
            <h3 class="font-bold">50cent</h3>
            <p class="text-sm text-black">Artista</p>
          </div>
        </div>
      </div>
    </div>
      <!-- cuadro 5 fin -->
    </div>
  </div>
</div>
  </div>
<!-- cuadro 4 fin -->


   <!-- fin de contenido -->  

  <!-- playback bar -->
    <div class="absolute w-full bg-amarillo-verdoso bottom-0 h-24 border-t border-green-50">
  <!-- playback bar -->
  <div class="px-4 flexh justify-between items-center h-full">
    <!-- info de la canción -->
    <div class="flex items-center gap-x-4">
      <div><img src="C:\Users\brenn\Downloads\romeo.jpeg" width="25" height="30"></div>
      <div>
        <button class="text-sm hover:underline block">Odio</button>
        <button class="text-xs hover:underline block">Romeo Santos</button>
      </div>
      <div>
        <button><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12Z" />
          </svg>
        </button>
      </div>
    </div>
    <!-- controles -->
    <div class="w-2/5 flex justify-center items-center">
      <div class="mt-2 flex justify-center gap-x-5 items-center text-black">
        <button><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M7.5 21 3 16.5m0 0L7.5 12M3 16.5h13.5m0-13.5L21 7.5m0 0L16.5 12M21 7.5H7.5" />
          </svg>
        </button>
        <button><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 15.75 3 12m0 0 3.75-3.75M3 12h18" />
          </svg>
        </button>
        <button><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M5.25 5.653c0-.856.917-1.398 1.667-.986l11.54 6.347a1.125 1.125 0 0 1 0 1.972l-11.54 6.347a1.125 1.125 0 0 1-1.667-.986V5.653Z" />
          </svg>
        </button>
        <button><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25 21 12m0 0-3.75 3.75M21 12H3" />
          </svg>
        </button>
        <button><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 12c0-1.232-.046-2.453-.138-3.662a4.006 4.006 0 0 0-3.7-3.7 48.678 48.678 0 0 0-7.324 0 4.006 4.006 0 0 0-3.7 3.7c-.017.22-.032.441-.046.662M19.5 12l3-3m-3 3-3-3m-12 3c0 1.232.046 2.453.138 3.662a4.006 4.006 0 0 0 3.7 3.7 48.656 48.656 0 0 0 7.324 0 4.006 4.006 0 0 0 3.7-3.7c.017-.22.032-.441.046-.662M4.5 12l3 3m-3-3-3 3" />
          </svg>
        </button>
      </div>
      <!-- barra de progreso -->
      <div class="flex-grow bg-black h-1 mt-2">
        <div class="relative w-[25%] bg-white group-hover:bg-purple-500 h-1 rounded">
          <div class="absolute hidden group-hover:block right-0 -bottom-full -top-full w-3 h-3 bg-white rounded"></div>
        </div>
      </div>
      <!-- fin de barra de progreso -->
    </div>
    <!-- controles fin -->
    <!-- complementos -->
    <div class="border">
      <div class="flex items-center gap-x-5 h-full text-black">
        <button><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M19.114 5.636a9 9 0 0 1 0 12.728M16.463 8.288a5.25 5.25 0 0 1 0 7.424M6.75 8.25l4.72-4.72a.75.75 0 0 1 1.28.53v15.88a.75.75 0 0 1-1.28.53l-4.72-4.72H4.51c-.88 0-1.704-.507-1.938-1.354A9.009 9.009 0 0 1 2.25 12c0-.83.112-1.633.322-2.396C2.806 8.756 3.63 8.25 4.51 8.25H6.75Z" />
          </svg>
        </button>
        <button><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M10.5 1.5H8.25A2.25 2.25 0 0 0 6 3.75v16.5a2.25 2.25 0 0 0 2.25 2.25h7.5A2.25 2.25 0 0 0 18 20.25V3.75a2.25 2.25 0 0 0-2.25-2.25H13.5m-3 0V3h3V1.5m-3 0h3m-3 18.75h3" />
          </svg>
        </button>
        <button><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M10.5 6h9.75M10.5 6a1.5 1.5 0 1 1-3 0m3 0a1.5 1.5 0 1 0-3 0M3.75 6H7.5m3 12h9.75m-9.75 0a1.5 1.5 0 0 1-3 0m3 0a1.5 1.5 0 0 0-3 0m-3.75 0H7.5m9-6h3.75m-3.75 0a1.5 1.5 0 0 1-3 0m3 0a1.5 1.5 0 0 0-3 0m-9.75 0h9.75" />
          </svg>
        </button>
        <button><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" />
          </svg>
        </button>
        <div class="w-24">
          <div class="group w-full bg-gray-500 h-1 rounded">
            <div class="relative w-[25%] bg-white group-hover:bg-purple-500 h-1 rounded">
              <div class="absolute hidden group-hover:block right-0 -bottom-full -top-full w-3 h-3 bg-white rounded"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- complementos fin -->
  </div>
</div>

</template>

<script>

</script>
