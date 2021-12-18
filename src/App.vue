<template>
<body class="text-gray-600 font-serif">

    <div class="grid grid-cols-3">
        <!--content wrapper-->
        <div class="col-span-1">
            <nav>
                <div>
                    <h1 class="font-bold uppercase p-4 border-b border-gray-100">
                        <a href="/" class="text-sm md:text">Food Ninja</a>
                    </h1>
                </div>
                <ul>
                    <li class="text-gray-900 font-bold">
                        <a href="#">
                            <span>Home</span>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <span>About</span>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <span>Contact</span>
                        </a>
                    </li>

                </ul>
            </nav>
        </div>
        <!--end of nav-->
        <main class="px-16 py-6 bg-gray-100 col-span-2">
            <div class="flex justify-center md:justify-end">
                <a href="#" class="text-primary">Log in</a>
                <a href="#" class="text-primary ml-2">Sign Up</a>
            </div>

            <header>
                <h2 class="text-gray-700 text-6xl font-semibold">Recipes</h2>
                <h3 class="text-2xl">For Ninjas</h3>
            </header>

            <div>
                <h4 class="font-bold mt-12 border-b border-gray-200">Latest Recipes</h4>

                <div class="mt-8 grid md:grid-cols-2 lg:grid-cols-3 gap-10">
                    <!--cards go here-->
                    <div class="card">
                        <img src="../src/assets/img/stew.jpg" alt="stew" class="w-full h-32 sm:h-48 object-cover">
                        <div class="m-4">
                            <span>5 Bean chilli Stew</span>
                            <span class="block text-gray-500 text-sm">Recipes by Mario</span>
                        </div>
                        <div class="badge">
                            <span>25 min</span>
                        </div>
                    </div>
                    <div class="card">
                        <img src="../src/assets/img/noodles.jpg" alt="noodles" class="w-full h-32 sm:h-48 object-cover">
                        <div class="m-4">
                            <span>Veg Noodles</span>
                            <span class="block text-gray-500 text-sm">Recipes by Mario</span>
                        </div>
                        <div class="badge">
                            <span>25 min</span>
                        </div>
                    </div>
                    <div class="card">
                        <img src="../src/assets/img/curry.jpg" alt="curry" class="w-full h-32 sm:h-48 object-cover">
                        <div class="m-4">
                            <span>Tofu Curry</span>
                            <span class="block text-gray-500 text-sm">Recipes by Mario</span>
                        </div>
                        <div class="badge">
                            <span>25 min</span>
                        </div>
                    </div>
                </div>  

                <h4 class="font-bold mt-12 pb-2 border-b border-gray-200">most Popular</h4>

                <div class="mt-8">
                    <!-- cards go here -->
                </div>

                <div class="flex justify-center">
                    <div class="bg-secondary-100 text-secondary-200">Load More</div>
                </div>
            </div>
        </main>
    </div>

</body>

</template>
