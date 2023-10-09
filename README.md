# Microsoft-clone
# You must install the node js to run the tailwind css
<!DOCTYPE html>
<html lang="en">
   <head>
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <link rel="stylesheet" href="style.css" />
      <title>Microsoft – Cloud, Computers, Apps &amp; Gaming</title>
   </head>
   <body>
      <!-- Navbar -->
      <div class="container mx-auto">
         <div class="navbar flex justify-between items-center p-4">
            <div class="flex justify-center items-center md:order-2">
               <div class="hamburger inline-block p-4 cursor-pointer md:hidden">
                  <div class="line h-0.5 w-6 my-1 bg-black"></div>
                  <div class="line h-0.5 w-6 my-1 bg-black"></div>
                  <div class="line h-0.5 w-6 my-1 bg-black"></div>
               </div>
               <div class="search md:hidden w-4 mr-6">
                  <img src="assets/search.svg" alt="" />
               </div>
            </div>
            <div class="logo text-center flex md:order-1">
               <div class="p-4 flex justify-center">
                  <img class="w-[50%]" src="assets/mslogo.png" alt="" />
               </div>
               <div
                  class="features absolute w-fit md:static md:w-auto bg-gray-200 md:bg-white inset-0 md:flex 
                  md:items-center   md:mx-4 md:space-x-6 -translate-x-96 md:-translate-x-0"
               >
                  <div class="fitem hover:underline hover:underline-offset-8 cursor-pointer">Microsoft 365</div>
                  <div class="fitem hover:underline hover:underline-offset-8 cursor-pointer">Office</div>
                  <div class="fitem hover:underline hover:underline-offset-8 cursor-pointer">Windows</div>
                  <div class="fitem hover:underline hover:underline-offset-8 cursor-pointer">Surface</div>
                  <div class="fitem hover:underline hover:underline-offset-8 cursor-pointer">Xbox</div>
                  <div class="fitem hover:underline hover:underline-offset-8 cursor-pointer">Support</div>
               </div>
            </div>
            <div class="cart text-center md:order-3 flex">
               <div class="search hidden md:block mr-6">All Microsoft</div>
               <div class="mx-2">Search</div>
               <img class="w-4 mr-6" src="assets/search.svg" alt="" />
               <div class="flex pt-1">
                  <img
                     class="w-4 h-4 mr-4"
                     src="assets/iconmonstr-shopping-cart-3.svg"
                     alt=""
                  />
                  <img
                     class="w-4 h-4 mr-4"
                     src="assets/iconmonstr-user-circle-thin.svg"
                     alt=""
                  />
               </div>
            </div>
         </div>

         <div class="slider flex flex-col-reverse md:flex-row bg-[#f2f2f2] mx-2">
            <div
               class="left flex flex-col justify-center items-center md:items-baseline py-12 ml-32 space-y-2"
            >
               <h1 class="text-2xl font-medium md:text-4xl mx-5">Surface Laptop Go 3</h1>
               <p class="w-3/4 mx-5 text-center md:text-left">
                  An ultraportable, everyday laptop with the performance and battery life
                  you need to get it all done.
               </p>
               <button class="text-white bg-black px-4 py-2 my-6 font-bold">
                  Shop Now
               </button>
            </div>
            <div class="right">
               <img
                  id="img-highlight-uid6a3b"
                  src="https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/Highlight-Surface-Laptop-Go-3-CONS-M001-1:VP2-859x540"
                  class="card-img w-100"
                  data-automation-test-id="HighlightImage-highlight-uid6a3b"
                  alt="A front view of a Surface Laptop Go 3 and a back view of a Surface Laptop Go 3."
               />
            </div>
         </div>

         <div class="promo space-y-6 flex flex-col lg:flex-row justify-center">
         <div class="promo space-y-6 flex flex-col lg:flex-row justify-center">
            <div class="item flex items-center mt-6 mx-4 space-x-2 md:flex-col">
               <img src="assets/ic1.png" alt="" />
               <span class="font-medium w-[8rem]  md:text-center text-sm my-4">Choose your Microsoft 365</span>
            </div>
            <div class="item flex items-center mx-4 space-x-2 md:flex-col">
               <img src="assets/ic2.webp" alt="" />
               <span class="font-medium w-[8rem] md:text-center text-sm my-4">Explore Surface devices</span>
            </div>
            <div class="item flex items-center mx-4 space-x-2 md:flex-col">
               <img src="assets/ic3.png" alt="" />
               <span class="font-medium w-[8rem] md:text-center text-sm my-4">Buy Xbox games</span>
            </div>
            <div class="item flex items-center mx-4 space-x-2 md:flex-col">
               <img src="assets/ic4.png" alt="" />
               <span class="font-medium w-[8rem] md:text-center text-sm my-4">Get Windows 11</span>
            </div>
         </div>
      </div>
   </body>
</html>
