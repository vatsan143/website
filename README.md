# Ex.07 Restaurant Website
# Date:05-04-2025

# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:


### INDEX.HTML

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Iron Flame Restaurant</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    .hero {
      background-image: url("1.jpeg"); /* Use your food image */
      background-size: cover;
      background-position: center;
    }
    .glass {
      background: rgba(238, 136, 4, 0.15);
      backdrop-filter: blur(12px);
      border: 1px solid rgba(238, 234, 7, 0.2);
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-serif">

  <!-- NAVIGATION BAR -->
  <nav class="bg-gray-800 p-4 shadow-md fixed w-full z-20">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-red-500 font-bold text-2xl">Iron Flame</a>
      <ul class="flex space-x-6 text-white">
        <li><a href="index.html" class="hover:text-red-400">Home</a></li>
        <li><a href="menu.html" class="hover:text-red-400">Menu</a></li>
        <li><a href="about.html" class="hover:text-red-400">Our Story</a></li>
        <li><a href="contact.html" class="hover:text-red-400">Contact</a></li>
        <li><a href="reserve.html" class="hover:text-red-400">Reservations</a></li>
        <li><a href="people.html" class="hover:text-red-400">Our Team</a></li>

      </ul>
    </div>
  </nav>

  <!-- HERO SECTION -->
  <section class="hero h-screen flex items-center justify-center relative pt-20">
    <div class="absolute inset-0 bg-black bg-opacity-60"></div>
    <div class="glass z-10 text-center p-10 rounded-xl max-w-2xl text-white">
      <h1 class="text-5xl font-extrabold mb-4 text-red-400">Iron Flame</h1>
      <p class="text-xl mb-6 italic">Where Fire Meets Flavor</p>
      <a href="menu.html" class="bg-red-500 text-white font-semibold px-6 py-3 rounded-full hover:bg-red-600 transition">Explore the Menu</a>
    </div>
  </section>

  <!-- FEATURES / SIGNATURE DISHES -->
  <section class="py-16 px-6 text-center bg-gray-800">
    <h2 class="text-4xl font-bold mb-4 text-red-400">Our Signature Flavors</h2>
    <p class="text-gray-300 mb-10 max-w-2xl mx-auto">Crafted with passion, spiced with tradition, and roasted to perfection.</p>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
      <div class="bg-gray-700 p-6 rounded-xl shadow-lg">
        <h3 class="text-2xl font-semibold mb-2 text-yellow-400">Smoked Citrus Chicken</h3>
        <p class="text-gray-300">Our hero dish — marinated with herbs, grilled to golden perfection, and kissed with blood orange zest.</p>
      </div>
      <div class="bg-gray-700 p-6 rounded-xl shadow-lg">
        <h3 class="text-2xl font-semibold mb-2 text-yellow-400">Fire-Grilled Garlic Veggies</h3>
        <p class="text-gray-300">Fresh market vegetables roasted in garlic butter over flame for intense depth.</p>
      </div>
      <div class="bg-gray-700 p-6 rounded-xl shadow-lg">
        <h3 class="text-2xl font-semibold mb-2 text-yellow-400">Lemon Herb Infusion</h3>
        <p class="text-gray-300">Aromatic lemon glaze with thyme and basil — the soul of our roast cuisine.</p>
      </div>
    </div>
  </section>

  <!-- RESERVATION CTA -->
  <section class="py-20 bg-gradient-to-r from-red-500 to-yellow-400 text-center text-gray-900">
    <h2 class="text-4xl font-extrabold mb-4">Book Your Table Today</h2>
    <p class="text-lg mb-8">An experience of heat, heart, and heavenly flavors awaits.</p>
    <a href="reserve.html" class="bg-gray-900 text-yellow-400 px-8 py-3 font-bold rounded-full hover:bg-gray-800 transition">Reserve Now</a>
  </section>

  <!-- FOOTER -->
  <footer class="py-6 bg-gray-900 text-center text-gray-400">
    © 2025 Iron Flame Restaurant. All rights reserved.
  </footer>

</body>
</html>


```





# OUTPUT:
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
