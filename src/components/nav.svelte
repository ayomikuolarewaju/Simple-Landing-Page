<script>
    import logo from '../img/nike.png'
    import revy from '../img/menu.png'
    let rev = false;
    const reveler = ()=>{
        rev = !rev;
    }
</script>



<div class=" bg-red-600">
    <nav class="container relative p-6 mx-auto ">
        <div class="flex items-center justify-between">
           <div class="pt-2">
            <img src="{logo}" alt="get images" srcset="" width="50" height="50">
           </div>
           <div class="hidden space-x-6 md:flex">

            <a href="/" class="hover:text-gray-300" >Pricing</a>
            <a href="/" class="hover:text-gray-300">Product</a>
            <a href="/" class="hover:text-gray-300">Contact</a>
            <a href="/" class="hover:text-gray-300">Career</a>
            <a href="/" class="hover:text-gray-300">Communities</a>
           </div> 
           <div class=" space-y-6 md:hidden flex flex-col">
            <div on:click={reveler} on:keydown={reveler}>
                <img src="{revy}" alt="menu" width="20" height="20" class="hover:text-gray-300">
            </div>
            {#if rev == true}
            <div class=" flex flex-col">
            <a href="/" class="hover:text-gray-300" >Pricing</a>
            <a href="/" class="hover:text-gray-300">Product</a>
            <a href="/" class="hover:text-gray-300">Contact</a>
            <a href="/" class="hover:text-gray-300">Career</a>
            <a href="/" class="hover:text-gray-300">Communities</a>
            </div>
            {/if}
           </div>
           <a href="/" class="hidden p-2 px-3 pt-2 text-white bg-red-500 rounded-full md:block bg-red baseline hover:bg-red-100">Get Started</a>
        </div>
     </nav>
</div>