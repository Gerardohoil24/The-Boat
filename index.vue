<template>
 <div>

   <!--Page menu/x -->
   <div class="relative bg-white overflow-hidden">
  <div class="max-w-7xl mx-auto">
    <div class="relative z-10 pb-8 bg-white sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:pb-28 xl:pb-32">
      <svg class="hidden lg:block absolute right-0 inset-y-0 h-full w-48 text-white transform translate-x-1/2" fill="currentColor" viewBox="0 0 100 100" preserveAspectRatio="none" aria-hidden="true">
        <polygon points="50,0 100,0 50,100 0,100" />
      </svg>

      <div>
        <div class="relative pt-6 px-4 sm:px-6 lg:px-8">
          <nav class="relative flex items-center justify-between sm:h-10 lg:justify-start" aria-label="Global">
            <div class="flex items-center flex-grow flex-shrink-0 lg:flex-grow-0">
              <div class="flex items-center justify-between w-full md:w-auto">
                <a href="#">
                  <span class="sr-only">Workflow</span>
                  <img class="h-8 w-auto sm:h-10" src="">
                </a>
                <div class="-mr-2 flex items-center md:hidden">
                  <button type="button" class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500" aria-expanded="false">
                    <span class="sr-only">Open main menu</span>
               

                    <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                  </button>
                </div>
              </div>
            </div>
            <div class="hidden md:block md:ml-10 md:pr-4 md:space-x-8">
              <a href="http://localhost:3000/" class="font-medium text-gray-500 hover:text-gray-900">Inicio</a>

              <a href="http://localhost:3000/home" class="font-medium text-gray-500 hover:text-gray-900">Galeria de fotos</a>

              <a href="http://localhost:3000/contact" class="font-medium text-gray-500 hover:text-gray-900">Contactanos</a>

              <a href="http://localhost:3000/login" class="font-medium text-blue-600 hover:text-indigo-500">Inicio de seccion</a>
            </div>
          </nav>
        </div>

 
        <div class="absolute top-0 inset-x-0 p-2 transition transform origin-top-right md:hidden">
          <div class="rounded-lg shadow-md bg-white ring-1 ring-black ring-opacity-5 overflow-hidden">
            <div class="px-5 pt-4 flex items-center justify-between">
              <div>
                <img class="h-8 w-auto" src="https://tailwindui.com/img/logos/workflow-mark-indigo-600.svg" alt="">
              </div>
              <div class="-mr-2">
                <button type="button" class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500">
                  <span class="sr-only">Close main menu</span>
                  
                  <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                  </svg>
                </button>
              </div>
            </div>
            <a href="#" class="block w-full px-5 py-3 text-center font-medium text-indigo-600 bg-gray-50 hover:bg-gray-100">
              Log in
            </a>
          </div>
        </div>
      </div>
      <main class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
        <div class="sm:text-center lg:text-left">
          <h1 class="text-5xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl">
            <span class="block xl:inline">La mejor inviercion de su vida</span>
            <th></th>
            <span class="block text-blue-600 xl:inline">The Boat</span>
          </h1>
          <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
            Ofrecemos una inversión que podrás gozar de inmediato con tus seres queridos, creando memorias inolvidables al mismo tiempo en el que creces tu patrimonio
          </p>
          <div class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start">
            <div class="rounded-md shadow">
              <a href="" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-blue-600 hover:bg-blue-300 md:py-4 md:text-lg md:px-10">
                Ver mas
              </a>
            </div>
          
          </div>
        </div>
      </main>
    </div>
  </div>
  <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
    <img class="h-56 w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full" src="https://pdc-2df4.kxcdn.com/wp-content/uploads/2020/08/the-boat-fachada-playa-del-carmen2-scaled.jpg" alt="">
  </div>

</div>


<!--header/x -->

 <div class="bg-brand  leading-loose px-20 py-20" style="background: url(https://www.imer.mx/tropicalisima/wp-content/uploads/sites/19/mar.jpg)">
      <p class="text-center text-black font-bold text-3xl m-12">
        No arriesgues tu dinero en inversiones impredecibles como la bolsa, el banco o propiedades que aún no están construidas
      </p>
  </div>

<!--Room cards/x -->

 <div class="grid gap-x-8 gap-y-4 grid-cols-3">
  <div>
<div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
  <div class="md:flex">
    <div class="md:flex-shrink-0">
      <img class="h-48 w-full object-cover md:h-full md:w-48" src="https://bienesraicesquintanaroo.mx/wp-content/uploads/2017/12/7a.jpg" alt="Man looking at item at a store">
    </div>
    <div class="p-8">
      <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Gimnasio</div>
      <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Contamos con un gimnasio completo</a>
      <p class="mt-2 text-gray-500">El gimnasio cuenta con todo lo necesario, no tendra ninguna molestia ya que el lugar es amplio, cuenta con caminadoras, pesas, bicicletas, etc</p>
    </div>
  </div>
</div></div>
  <div>

<div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
  <div class="md:flex">
    <div class="md:flex-shrink-0">
      <img class="h-48 w-full object-cover md:h-full md:w-48" src="https://moskito.mx/es/wp-content/uploads/sites/2/2020/05/a-playa-del-carmen-real-estate-the-boat-twobdrm-living-scaled.jpg" alt="Man looking at item at a store">
    </div>
    <div class="p-8">
      <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Sala de estar</div>
      <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Contamos con una sala de estar con todo</a>
      <p class="mt-2 text-gray-500">La sala de estar cuenta con todo lo necesario,la television, la sala de estar, ademas de un exelente espacio para unas cuantas personas y sobre todo comodo.</p>
    </div>
  </div>
</div></div>
  <div>

<div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
  <div class="md:flex">
    <div class="md:flex-shrink-0">
      <img class="h-48 w-full object-cover md:h-full md:w-48" src="https://moskito.mx/es/wp-content/uploads/sites/2/2020/05/b-playa-del-carmen-real-estate-the-boat-twobdrm-kitchen-scaled.jpg" alt="Man looking at item at a store">
    </div>
    <div class="p-8">
      <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Area de cocina</div>
      <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Contamos con el area de cocina con todo lo requerido</a>
      <p class="mt-2 text-gray-500">El area de la cocina de igual manera cuenta con lo necesario, estufa, lavaplatos, el espacio suficiente para cocinar y las alacenas.</p>
    </div>
  </div>
</div></div>
  <div>

<div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
  <div class="md:flex">
    <div class="md:flex-shrink-0">
      <img class="h-48 w-full object-cover md:h-full md:w-48" src="https://moskito.mx/es/wp-content/uploads/sites/2/2020/05/l-playa-del-carmen-real-estate-the-boat-studio-space-scaled.jpg" alt="Man looking at item at a store">
    </div>
    <div class="p-8">
      <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Habitación</div>
      <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Contamos con las mejores habitacaciones</a>
      <p class="mt-2 text-gray-500">Nuestras habitaciones son sumamente comodas, contamos con todo lo necesario. dentro de la habitacion podemos encontrar mesas de noche, una o dos camas, ademas de una television.</p>
    </div>
  </div>
</div></div>
  <div>

<div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
  <div class="md:flex">
    <div class="md:flex-shrink-0">
      <img class="h-48 w-full object-cover md:h-full md:w-48" src="https://a0.muscache.com/im/pictures/fd25e84a-1f5d-4abd-ad48-b79f0f947cd6.jpg?im_w=720" alt="Man looking at item at a store">
    </div>
    <div class="p-8">
      <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Exterior</div>
      <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Contamos con un bonito exterior</a>
      <p class="mt-2 text-gray-500">El exterior tiene una vista maravillosa hacia el mar, ademas contamos con una piscina para pasar un rato agradable en companía de amigos o solo.</p>
    </div>
  </div>
</div></div>
  <div>
<div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
  <div class="md:flex">
    <div class="md:flex-shrink-0">
      <img class="h-48 w-full object-cover md:h-full md:w-48" src="https://www.preferredrealestate.com.mx/wp-content/uploads/2019/02/90060540.jpg" alt="Man looking at item at a store">
    </div>
    <div class="p-8">
      <div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Entretenimiento</div>
      <a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Contamos con un area de entretenimiento</a>
      <p class="mt-2 text-gray-500">El area de entrenimiento es un lugar increible ya que cuenta con un espacio amplio, ademas de que cuenta con otros aspectos como una bar y sonido de musica.</p>
    </div>
  </div>
</div></div>
</div>


<!--Header/x -->


 <div class="bg-brand  leading-loose px-20 py-20" style="background: url(https://images.pexels.com/photos/706484/pexels-photo-706484.png?cs=srgb&dl=pexels-peter-brown-706484.jpg&fm=jpg)">
      <p class="text-center text-black font-bold text-3xl m-12">
        Después de este 2021... 🦠😷
      </p>
       <p class="text-center text-black font-bold text-3xl m-12">
        ¿Cuánto tiempo nos queda para disfrutar la vida?
      </p>
      <br>
      <br>
      <div data-v-4946ab98="" class="v-image v-responsive footer-logo theme--light" style="height: 200px; width: 200px;"><div class="v-responsive__sizer" style="padding-bottom: 58%;"></div><div class="v-image__image v-image__image--contain" style="background-image: url(logo.png); background-position: center center;"></div><div class="v-responsive__content" style="width: 200px;"></div></div>
  </div>


   <!--Footer /x -->   

  <footer class="footer-1 bg-gray-100 py-8 sm:py-12">
  <div class="container mx-auto px-4">
    <div class="sm:flex sm:flex-wrap sm:-mx-4 md:py-4">
      <div class="px-4 sm:w-1/2 md:w-1/4 xl:w-1/6">
        <h5 class="text-xl font-bold mb-6">No te pierdas de la mejor experiencia</h5>
        <ul class="list-none footer-links">
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Habitaciones</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Entretimiento</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Exteriores</a>
          </li>
        </ul>
      </div>
      <div class="px-4 sm:w-1/2 md:w-1/4 xl:w-1/6 mt-8 sm:mt-0">
        <h5 class="text-xl font-bold mb-6">¿Todavia no sabes donde invertir?</h5>
        <ul class="list-none footer-links">
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Seguro</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Innovador</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Lo mejor del mercado</a>
          </li>
        </ul>
      </div>
      <div class="px-4 sm:w-1/2 md:w-1/4 xl:w-1/6 mt-8 md:mt-0">
        <h5 class="text-xl font-bold mb-6">Ayuda</h5>
        <ul class="list-none footer-links">
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Apoyo</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Centro de ayuda</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Contáctenos</a>
          </li>
        </ul>
      </div>
      <div class="px-4 mt-4 sm:w-1/3 xl:w-1/6 sm:mx-auto xl:mt-0 xl:ml-auto">
        <h5 class="text-xl font-bold mb-6 sm:text-center xl:text-left">Redes Sociales</h5>
        <div class="flex sm:justify-center xl:justify-start">
          <a href="" class="w-8 h-8 border border-2 border-gray-400 rounded-full text-center py-1 text-gray-600 hover:text-white hover:bg-blue-600 hover:border-blue-600">
            <i class="fab fa-facebook"></i>
          </a>
          <a href="" class="w-8 h-8 border border-2 border-gray-400 rounded-full text-center py-1 ml-2 text-gray-600 hover:text-white hover:bg-blue-400 hover:border-blue-400">
            <i class="fab fa-twitter"></i>
          </a>
          <a href="" class="w-8 h-8 border border-2 border-gray-400 rounded-full text-center py-1 ml-2 text-gray-600 hover:text-white hover:bg-red-600 hover:border-red-600">
            <i class="fab fa-google-plus-g"></i>
          </a>
        </div>
      </div>
    </div>

    <div class="sm:flex sm:flex-wrap sm:-mx-4 mt-6 pt-6 sm:mt-12 sm:pt-12 border-t">
      <div class="sm:w-full px-4 md:w-1/6">
        <strong>The boat</strong>
      </div>
      <div class="px-4 sm:w-1/2 md:w-1/4 mt-4 md:mt-0">
        <h6 class="font-bold mb-2">Dirección</h6>
        <address class="not-italic mb-4 text-sm">
          Av. Calle 14 Nte 171, Gonzalo Guerrero, 77720 Playa del Carmen, Quintana Rooo.<br>
          <br>
          Tel: +52 984 164 28 44
        </address>
      </div>
      <div class="px-4 sm:w-1/2 md:w-1/4 mt-4 md:mt-0">
        <p class="mb-4 text-sm"><strong>2021 — The Boat Playa del Carmen</strong>.<br>
        </p>
      </div>
    </div>
  </div>
</footer>

 </div>



 
</template>