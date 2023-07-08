<script>
    import Product from "./Product.svelte";
</script>

<div class="bg-white">
    <div class="mx-auto max-w-2xl px-4 py-16 sm:px-6 sm:py-24 lg:max-w-7xl lg:px-8">
      <div class="md:flex md:items-center md:justify-between">
        <h2 class="text-2xl font-bold tracking-tight text-gray-900">Trending products</h2>
        <a href="#" class="hidden text-sm font-medium text-indigo-600 hover:text-indigo-500 md:block">
          Shop the collection
          <span aria-hidden="true"> &rarr;</span>
        </a>
      </div>
  
      <div class="mt-6 grid grid-cols-2 gap-x-4 gap-y-10 sm:gap-x-6 md:grid-cols-4 md:gap-y-0 lg:gap-x-8">
       
        <Product 
            name="Dongs"
            style="Big"
            price="$33"
            src="https://yt3.googleusercontent.com/ZYFLtxe4QYSQPNbTvgZ7kjHyyjGHOeSZTzW-blSx7o2b51mOFGYT8iCUMwOopBhvuJ37jJvdFw=s900-c-k-c0x00ffffff-no-rj"
            alt="Biggus Dickus"
            link="https://www.google.com"
        />

        <Product />

        <Product />

        <Product />

      </div>
  
      <div class="mt-8 text-sm md:hidden">
        <a href="#" class="font-medium text-indigo-600 hover:text-indigo-500">
          Shop the collection
          <span aria-hidden="true"> &rarr;</span>
        </a>
      </div>
    </div>
  </div>
  