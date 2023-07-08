<script>
    export let name = "Leather Long Wallet";
    export let style = "Natural";
    export let price = "$75";
    export let src = "https://tailwindui.com/img/ecommerce-images/home-page-04-trending-product-02.jpg";
    export let alt = "Hand stitched, orange leather long wallet.";
    export let link = "#"
</script>

<div class="group relative">
    <div class="h-56 w-full overflow-hidden rounded-md bg-gray-200 group-hover:opacity-75 lg:h-72 xl:h-80">
      <img {src} alt={alt} class="h-full w-full object-cover object-center">
    </div>
    <h3 class="mt-4 text-sm text-gray-700">
      <a href={link}>
        <span class="absolute inset-0"></span>
        {name}
      </a>
    </h3>
    <p class="mt-1 text-sm text-gray-500">{style}</p>
    <p class="mt-1 text-sm font-medium text-gray-900">{price}</p>
  </div>