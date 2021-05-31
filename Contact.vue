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
                  <span class="sr-only"></span>
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
            <span class="block xl:inline">¡Conocenos un poco más!</span>
            <th></th>
            <span class="block text-blue-600 xl:inline">The Boat</span>
          </h1>
          <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
            Ponte en contacto con nosotros, descubre el mejor lugar para tus vacaciones
          </p>
        </div>
      </main>
    </div>
  </div>
  <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
    <img class="h-56 w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full" src="http://www.maiarealestate.mx/wp-content/uploads/2019/07/The_Boat_Rooftop_120817_OP1_206KB.jpg" alt="">
  </div>

</div>

<br>

<!--Social media cards /x -->   
<div class="flex flex-wrap">
			<div class="md:w-1/2 lg:w-1/3 py-4 px-4" >
				<div class=" ">
					<a href="/donee/donee-2">
						<div class="bg-white relative shadow p-2 rounded-lg text-gray-800 hover:shadow-lg">
							<div class="right-0 mt-4 rounded-l-full absolute text-center font-bold text-xs text-white px-2 py-1 bg-orange-500">
							</div>
							<img src="https://serivi-cell.webnode.es/_files/200000009-81f3f82ee7/facebook_blue_original.jpg" class="h-32 rounded-lg w-full object-cover">
							<div class="flex justify-center">
								<img src="https://i.ytimg.com/vi/KoEYrHIYgCo/maxresdefault.jpg" class="rounded-full -mt-6 border-4 object-center object-cover border-white mr-2 h-16 w-16">
							</div>
							<div class="py-2 px-2">
								<div class=" font-bold font-title text-center">Facebook</div>

								<div class="text-sm font-light text-center my-2">The Boat</div>
							</div>
						</div>
					</a>

				</div>
			</div>	


			<div class="md:w-1/2 lg:w-1/3 py-4 px-4">
				<div class=" ">
					<a href="/donee/donee-3">
						<div class="bg-white relative shadow p-2 rounded-lg text-gray-800 hover:shadow-lg">
							<div class="right-0 mt-4 rounded-l-full absolute text-center font-bold text-xs text-white px-2 py-1 bg-orange-500">
							</div>
							<img src="https://promocionmusical.es/wp-content/uploads/2020/05/instagram-logo.gif" class="h-32 rounded-lg w-full object-cover">
							<div class="flex justify-center">
								<img src="https://i.ytimg.com/vi/KoEYrHIYgCo/maxresdefault.jpg" class="rounded-full -mt-6 border-4 object-center object-cover border-white mr-2 h-16 w-16">
							</div>
							<div class="py-2 px-2">
								<div class=" font-bold font-title text-center">Instagram</div>

								<div class="text-sm font-light text-center my-2">The Boat</div>
							</div>
						</div>
					</a>

				</div>
			</div>	


			<div class="md:w-1/2 lg:w-1/3 py-4 px-4">
				<div class=" ">
					<a href="/donee/donee-1">
						<div class="bg-white relative shadow p-2 rounded-lg text-gray-800 hover:shadow-lg">
							<div class="right-0 mt-4 rounded-l-full absolute text-center font-bold text-xs text-white px-2 py-1 bg-orange-500">
							</div>
							<img src="https://socialgeek.co/wp-content/uploads/2017/11/logo-twitter.png" class="h-32 rounded-lg w-full object-cover">
							<div class="flex justify-center">
								<img src="https://i.ytimg.com/vi/KoEYrHIYgCo/maxresdefault.jpg" class="rounded-full -mt-6 border-4 object-center object-cover border-white mr-2 h-16 w-16">
							</div>
							<div class="py-2 px-2">
								<div class=" font-bold font-title text-center">Twitter</div>

								<div class="text-sm font-light text-center my-2">The Boat</div>
							</div>
						</div>
					</a>

				</div>
			</div>	

		</div>
  <br>
  <br>

  
  <!--Contact Form/x -->   


    <p class="text-6xl font-serif text-center">Contactanos</p>


  <div class="bg-gray-100 mx-auto max-w-6xl bg-white py-20 px-12 lg:px-24 shadow-xl mb-24">
    <form>
      <div class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4 flex flex-col">
        <div class="-mx-3 md:flex mb-6">
          <div class="md:w-1/2 px-3 mb-6 md:mb-0">
            <label class="uppercase tracking-wide text-black text-xs font-bold mb-2" for="name">
              Nombre completo*
            </label>
            <input class="w-full bg-gray-200 text-black border border-gray-200 rounded py-3 px-4 mb-3" id="nombre" type="text" placeholder="Gerardo">
            <div>
              <span class="text-red-500 text-xs italic">
                Porfavor agregue nombre completo.
              </span>
            </div>
          </div>
          <div class="md:w-1/2 px-3">
            <label class="uppercase tracking-wide text-black text-xs font-bold mb-2" for="Age">
              Edad*
            </label>
            <input class="w-full bg-gray-200 text-black border border-gray-200 rounded py-3 px-4 mb-3" id="Age" type="text" placeholder="18">
          </div>
        </div>
        <div class="-mx-3 md:flex mb-6">
          <div class="md:w-full px-3">
            <label class="uppercase tracking-wide text-black text-xs font-bold mb-2" for="">
              Dudas*
            </label>
            <input class="w-full bg-gray-200 text-black border border-gray-200 rounded py-3 px-4 mb-3" id="questions" type="text" placeholder="¿Cuales son las dudas que tiene?">
          </div>
        </div>
        <div class="-mx-3 md:flex mb-2">
          <div class="md:w-1/2 px-3 mb-6 md:mb-0">
            <label class="uppercase tracking-wide text-black text-xs font-bold mb-2" for="Pais">
              Pais*
            </label>
            <div>
              <select class="w-full bg-gray-200 border border-gray-200 text-black text-xs py-3 px-4 pr-8 mb-3 rounded" id="Pais">
                <option>Mexíco</option>
                <option>EUA</option>
                <option>Colombia</option>
                <option>Argentina</option>
                <option>Ecuador</option>
                <option>Bolivia</option>
              </select>
            </div>
          </div>
          
              
        </div>
        <div class="-mx-3 md:flex mt-2">
          <div class="md:w-full px-3">
            <button class="md:w-full bg-gray-900 text-white font-bold py-2 px-4 border-b-4 hover:border-b-2 border-gray-500 hover:border-gray-100 rounded-full">
              Enviar
            </button>
          </div>
        </div>
      </div>
    </form>
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