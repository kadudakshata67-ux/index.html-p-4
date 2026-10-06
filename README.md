<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Product Showcase</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-50 text-gray-900">

  <!-- Header -->
  <header class="bg-white border-b">
    <div class="max-w-7xl mx-auto px-6 py-5
                flex flex-col sm:flex-row
                items-center justify-between gap-4">

      <h1 class="text-2xl font-bold text-indigo-600">
        TechStore
      </h1>

      <nav class="flex items-center gap-6 text-sm font-medium">
        <a href="#" class="hover:text-indigo-600">Home</a>
        <a href="#" class="hover:text-indigo-600">Products</a>
        <a href="#" class="hover:text-indigo-600">About</a>
      </nav>
    </div>
  </header>

  <!-- Product Showcase -->
  <main class="max-w-7xl mx-auto px-6 py-10 lg:py-16">

    <div class="flex flex-col lg:flex-row items-center gap-10 lg:gap-16">

      <!-- Product Image -->
      <div class="w-full lg:w-1/2">
        <div class="bg-white rounded-3xl shadow-lg p-6 sm:p-10
                    flex items-center justify-center">

          <img
            src="https://images.unsplash.com/photo-1593642532400-2682810df593?auto=format&fit=crop&w=1000&q=80"
            alt="Premium laptop"
            class="w-full max-w-lg rounded-2xl object-cover
                   hover:scale-105 transition duration-500"
          />
        </div>
      </div>

      <!-- Product Details -->
      <div class="w-full lg:w-1/2">

        <span class="inline-block bg-indigo-100 text-indigo-700
                     px-4 py-2 rounded-full text-sm font-semibold mb-5">
          New Arrival
        </span>

        <h2 class="text-4xl sm:text-5xl font-bold leading-tight mb-5">
          UltraBook Pro
        </h2>

        <p class="text-gray-600 text-lg leading-relaxed mb-6">
          Experience powerful performance in a sleek, lightweight design.
          The UltraBook Pro is built for productivity, creativity, and
          everything in between.
        </p>

        <!-- Features -->
        <div class="flex flex-col sm:flex-row sm:flex-wrap gap-3 mb-8">
          <div class="bg-white rounded-xl px-4 py-3 shadow-sm">
            ⚡ Fast Performance
          </div>

          <div class="bg-white rounded-xl px-4 py-3 shadow-sm">
            🔋 18h Battery
          </div>

          <div class="bg-white rounded-xl px-4 py-3 shadow-sm">
            💻 16GB RAM
          </div>

          <div class="bg-white rounded-xl px-4 py-3 shadow-sm">
            💾 512GB SSD
          </div>
        </div>

        <!-- Price & CTA -->
        <div class="flex flex-col sm:flex-row sm:items-center gap-5">
          <div>
            <p class="text-sm text-gray-500">Starting at</p>
            <p class="text-3xl font-bold text-gray-900">$1,299</p>
          </div>

          <button
            class="bg-indigo-600 text-white px-8 py-4 rounded-xl
                   font-semibold hover:bg-indigo-700
                   transition shadow-md hover:shadow-lg
                   w-full sm:w-auto">
            Buy Now
          </button>
        </div>

      </div>
    </div>

    <!-- Additional Products -->
    <section class="mt-20">
      <h3 class="text-2xl font-bold mb-8 text-center">
        You May Also Like
      </h3>

      <div class="flex flex-col sm:flex-row gap-6">

        <div class="bg-white rounded-2xl shadow-md p-5 flex-1">
          <img
            src="https://images.unsplash.com/photo-1541807084-5c52b6b3adef?auto=format&fit=crop&w=600&q=80"
            alt="Laptop"
            class="w-full h-48 object-cover rounded-xl mb-4"
          />
          <h4 class="font-bold text-lg">Everyday Laptop</h4>
          <p class="text-gray-500 mt-1">$899</p>
        </div>

        <div class="bg-white rounded-2xl shadow-md p-5 flex-1">
          <img
            src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?auto=format&fit=crop&w=600&q=80"
            alt="Smart watch"
            class="w-full h-48 object-cover rounded-xl mb-4"
          />
          <h4 class="font-bold text-lg">Smart Watch</h4>
          <p class="text-gray-500 mt-1">$249</p>
        </div>

        <div class="bg-white rounded-2xl shadow-md p-5 flex-1">
          <img
            src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&w=600&q=80"
            alt="Wireless headphones"
            class="w-full h-48 object-cover rounded-xl mb-4"
          />
          <h4 class="font-bold text-lg">Wireless Headphones</h4>
          <p class="text-gray-500 mt-1">$199</p>
        </div>

      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-400 text-center py-6 mt-10">
    <p>&copy; 2026 TechStore. All rights reserved.</p>
  </footer>

</body>
</html>
