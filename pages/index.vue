<template>
  <div>
    <div id="header" class="bg-[url('/hero-bg.jpg')] px-20">
      <div id="menu" class="grid grid-cols-2 py-5">
        <div id="menu-left">
          <img src="logo.png" class="w-[150px]" alt="" />
        </div>

        <div id="menu-right">
          <ul class="grid grid-cols-4 text-lg font-oswald text-white uppercase pt-5">
            <li>About Us</li>
            <li>Our Menu</li>
            <li>Locations</li>
            <li>Contacts</li>
          </ul>
        </div>
      </div>

      <div class="grid grid-cols-2 pb-20 pt-10">
        <img src="hero-burger.png" class="pr-8 mt-10" alt="" />
        <div>
          <h1 class="text-8xl text-white text-center font-lilita uppercase">
            Classic Burger
          </h1>
          <h2 class="text-6xl text-white text-center font-lilita uppercase my-5">
            With Onion
          </h2>
          <p class="text-white font-roboto font-light text-center">
            Our signature burger now comes with onion and chesse. You can customize it to your likings.
            Freshly made to order, all in a Brioche style bun.
          </p>
        </div>
      </div>
    </div>

    <div id="section-1" class="text-center bg-[url('/three-burgers.jpg')] pb-80 bg-cover">
      <h1 class="text-6xl uppercase font-oswald pt-20 px-24">
        The burger tastes better when you eat it with family
      </h1>
      <p class="font-roboto font-light text-gray-500 text-lg py-6 px-28">
        Spend quality time with your family and eat an affordable, nutritious and delicious meal together.
        Not all burgers are fast foods. All our burgers are handmade to order for your family members to enjoy.
      </p>
      <button class="font-oswald uppercase bg-red-500 text-white py-3 px-8">
        Explore Full Menu
      </button>
    </div>

    <div id="section-2" class="bg-yellow-500 py-10 px-20">
      <div class="grid grid-cols-3 text-center text-neutral-900 xl:px-52">
        <div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-20 w-20 stroke-1 block mx-auto"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z"
            />
          </svg>
          <p class="font-medium font-oswald text-2xl uppercase my-5">Original Recipes</p>
          <p class="font-light font-roboto px-5">
            We use our secret recipes with only the best ingredients to make our burgers.
            Starting from patties, sauces, and even buns.
          </p>
        </div>
        <div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-20 w-20 block mx-auto"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="1"
              d="M21 15.546c-.523 0-1.046.151-1.5.454a2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.701 2.701 0 00-1.5-.454M9 6v2m3-2v2m3-2v2M9 3h.01M12 3h.01M15 3h.01M21 21v-7a2 2 0 00-2-2H5a2 2 0 00-2 2v7h18zm-3-9v-2a2 2 0 00-2-2H8a2 2 0 00-2 2v2h12z"
            />
          </svg>
          <p class="font-medium font-oswald text-2xl uppercase my-5">Quality Foods</p>
          <p class="font-light font-roboto px-5">
            We purchase our ingredients from the best suppliers daily, to ensure the
            freshest quality of our burgers.
          </p>
        </div>
        <div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-20 w-20 block mx-auto"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="1"
              d="M13 10V3L4 14h7v7l9-11h-7z"
            />
          </svg>
          <p class="font-medium font-oswald text-2xl uppercase my-5">Fastest Delivery</p>
          <p class="font-light font-roboto px-5">
            Burgers are best served while it's hot. We deliver to your door with our
            speedy delivery partners from the nearest outlet.
          </p>
        </div>
      </div>
    </div>

    <div id="section-3">
      <div class="text-center py-20 mx-40">
        <h2 class="text-6xl font-oswald text-red-500 font-medium uppercase">
          Our Crazy Burgers
        </h2>
        <p class="font-roboto font-light mt-10 mb-10 text-xl text-gray-500">
          Whether you are looking for the classics, our specialties, or just wraps,
          salads, and fries. We have it all. We always have something that rewards your
          tastebud.
        </p>
      </div>

      <div class="grid grid-cols-2 px-40 gap-5">
        <div id="left-item-column">
          <Item />
        </div>
        <div id="right-item-column">
          <Item />
        </div>
      </div>
    </div>
  </div>
</template>
