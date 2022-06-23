<script setup>
// import statements here

</script>

<template>
<!--adding two horizontal cards-->
<footer class="border-t border-gray-200  items-center bg-blue-50">
        
      <div class="container flex flex-col md:mx-[7%] flex-wrap px-4 py-16 mx-auto md:items-center  lg:items-start md:flex-row md:flex-nowrap md:gap-11 " >
        <!--col 1-->
        <div class="flex-shrink-0 w-48  md:mx-0 text-left ml-3" >
          <a class=" flex items-center justify-center text-4xl font-bold md:justify-start " >
            <img src="../assets/Frame 2.png" class= "h-5 m-2 object-fill relative">
          </a>
          <p class="mt-2 text-sm  text-gray-500">
            Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit. Exercitation veniam consequat sunt nostrud amet.
          </p>
          <div class="flex justify-start mt-4 lg:mt-6 gap-2">
            <a><!--facebook-->
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-auto h-6 text-blue-900" viewBox="0 0 24 24" >
                <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z" ></path>
              </svg>
            </a>
            <a class="ml-3"><!--linkedIn-->
              <svg fill="currentColor" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="0" class="w-auto h-6 text-blue-900" viewBox="0 0 24 24" >
                <path stroke="none" d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z" ></path>
                <circle cx="4" cy="4" r="2" stroke="none"></circle>
              </svg>
            </a>
            <a class="ml-3"><!--twitter-->
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-auto h-6 text-blue-900" viewBox="0 0 24 24" >
                <path
                  d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"
                ></path>
              </svg>
            </a>
            <a class="ml-3"><!--youtube-->
              <svg width="16" height="24" viewBox="0 0 16 12" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-auto h-6">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M13.456 0.758748C14.415 0.812748 14.886 0.954748 15.32 1.72675C15.772 2.49775 16 3.82575 16 6.16475V6.16775V6.17275C16 8.50075 15.772 9.83875 15.321 10.6017C14.887 11.3737 14.416 11.5137 13.457 11.5787C12.498 11.6337 10.089 11.6667 8.002 11.6667C5.911 11.6667 3.501 11.6337 2.543 11.5777C1.586 11.5127 1.115 11.3727 0.677 10.6007C0.23 9.83775 0 8.49975 0 6.17175V6.16975V6.16675V6.16375C0 3.82575 0.23 2.49775 0.677 1.72675C1.115 0.953748 1.587 0.812748 2.544 0.757748C3.501 0.693748 5.911 0.666748 8.002 0.666748C10.089 0.666748 12.498 0.693748 13.456 0.758748ZM11 6.16675L6 3.16675V9.16675L11 6.16675Z" fill="#001D6D"/>
                </svg>  
            </a>

            <a class="ml-3"><!--instagram-->
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-auto h-6 text-blue-900" viewBox="0 0 24 24" >
                <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01" ></path>
              </svg>
            </a>
            
            
          </div>
        </div>
        <!--col 2-->
        <div class="justify-between w-full mt-2 text-left lg:flex">
          <div class="w-full px-4 lg:w-1/3 md:w-1/2">
            <h2 class="mb-4 font-bold tracking-widest text-gray-900">
              SERVICES
            </h2>
            <ul class="mb-8 space-y-2 text-sm list-none">
              <li>
                <a class="text-gray-600 hover:text-gray-800">Events</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Webinars</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Blogs</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Customer Success</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Expert Services</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Data Insider</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">View All Resouces</a>
              </li>
            </ul>
          </div>
          <!--col 3-->
          <div class="w-full px-4 lg:w-1/3 md:w-1/2">
            <h2 class="mb-2 font-bold tracking-widest text-gray-900">
              RESOURCES
            </h2>
            <ul class="mb-8 space-y-2 text-sm list-none">
              <li>
                <a class="text-gray-600 hover:text-gray-800">Events</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Webinars</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Blogs</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Customer Success</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Expert Services</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Data Insider</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">View All Resouces</a>
              </li>
            </ul>
          </div>
          <!--col 4-->
          <div class="w-full px-4 lg:w-1/3 md:w-1/2">
            <h2 class="mb-2 font-bold tracking-widest text-gray-900">
              COMPANY
            </h2>
            <ul class="mb-8 space-y-2 text-sm list-none">
              <li>
                <a class="text-gray-600 hover:text-gray-800">About Rakuten Fuji</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Careers</a>
              </li>
              <li>
                <a class="text-gray-600 hover:text-gray-800">Leadership</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="flex justify-center bg-black h-[40px] items-center">
        <p class="text-base text-white">
          &#169 2021 Rakuten
        </p>
      </div>
    </footer>
</template>

<style scoped>
/*a {
  color: #42b983;
}*/
</style>