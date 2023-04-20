<script>
    import img1 from '../img/spirit.png'
    import img2 from '../img/beer.png'
    import img3 from '../img/drink.png'
    import img4 from '../img/ice.png'
</script>


<footer class="bg-sky-950">
    <div class="container flex flex-col-reverse justify-between px-6 py-10 mx-auto space-y-8 md:flex-row md:space-y-0">
       <div class="flex flex-col-reverse items-center space-y-12 justify start md:flex-col md:space-y-0 md:items-start">
          <div>
             <img src="img/nike.png" class="h-8" alt="" srcset="">
          </div>
          <div class="flex mx-auto my-6 text-center text-white md:hidden">
             copyrigth &copy; 2023 All Rigth Reserved
          </div>
          <div class="flex flex-row justisfy-between">
             <a href="/bind:" ><img src="{img1}" alt="" srcset="" class="h-8 mr-2"></a>
             <a href="/" ><img src="{img2}" alt="" srcset="" class="h-8 mr-2"></a>
             <a href="/" ><img src="{img3}" alt="" srcset="" class="h-8 mr-2"></a>
             <a href="/" ><img src="{img4}" alt="" srcset="" class="h-8 mr-2"></a>
          </div>
       </div>
       <div class="flex justify-around space-x-32">
            <div class="flex flex-col space-y-3 text-white">
             <a href="/" class="hover:text-red-300">Home</a>
             <a href="/" class="hover:text-red-300">Product</a>
             <a href="/" class="hover:text-red-300">Career</a>
             <a href="/" class="hover:text-red-300">Community</a>
            </div>
            <div class="flex flex-col space-y-3 text-white">
             <a href="/" class="hover:text-red-300">About</a>
             <a href="/" class="hover:text-red-300">Contact</a>
             <a href="/" class="hover:text-red-300">Prices</a>
             
            </div>
       </div>
       <div class="flex flex-col justify-between">
          <form>
             <div class="flex space-x-3">
                <input type="text" class="flex-1 px-4 rounded-full focus:outline-none">
                <button class="px-6 py-2 text-white bg-red-600 rounded-full hover:bg-red-100 focus:outline-none">GO</button>
             </div>
          </form>
          <div class="hidden text-white md:block">
             copyrigth &copy; 2023 All Rigth Reserved
          </div>
       </div>
    </div>
   </footer>
  