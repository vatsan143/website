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
### CONTACT.HTML

```
<!-- contact.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact - Iron Flame</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white font-serif">
  <nav class="bg-gray-800 p-4 shadow-md fixed w-full z-20">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-red-500 font-bold text-2xl">Iron Flame</a>
      <ul class="flex space-x-6 text-white">
        <li><a href="index.html" class="hover:text-red-400">Home</a></li>
        <li><a href="menu.html" class="hover:text-red-400">Menu</a></li>
        <li><a href="about.html" class="hover:text-red-400">Our Story</a></li>
        <li><a href="contact.html" class="text-red-400">Contact</a></li>
        <li><a href="reserve.html" class="hover:text-red-400">Reservations</a></li>
        <li><a href="people.html" class="hover:text-red-400">Our Team</a></li>

      </ul>
    </div>
  </nav>

  <section class="pt-32 px-6 max-w-3xl mx-auto">
    <h1 class="text-4xl font-bold text-yellow-400 mb-8">Get In Touch</h1>
    <form class="space-y-6">
      <div>
        <label class="block mb-2">Name</label>
        <input type="text" class="w-full p-3 rounded bg-gray-800 text-white border border-gray-600" placeholder="Your name" />
      </div>
      <div>
        <label class="block mb-2">Email</label>
        <input type="email" class="w-full p-3 rounded bg-gray-800 text-white border border-gray-600" placeholder="you@example.com" />
      </div>
      <div>
        <label class="block mb-2">Message</label>
        <textarea class="w-full p-3 rounded bg-gray-800 text-white border border-gray-600" rows="5" placeholder="Your message..."></textarea>
      </div>
      <button type="submit" class="bg-red-500 hover:bg-red-600 text-white px-6 py-3 rounded font-semibold">Send Message</button>
    </form>
  </section>

  <footer class="py-6 mt-12 bg-gray-900 text-center text-gray-400">
    © 2025 Iron Flame Restaurant. All rights reserved.
  </footer>
</body>
</html>



```
### MENU.HTML

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Menu - Iron Flame</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    .menu-hero {
      background-image: url('hero.jpg'); /* Same roasted food image */
      background-size: cover;
      background-position: center;
    }
    .glass {
      background: rgba(0, 0, 0, 0.5);
      backdrop-filter: blur(6px);
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-serif">

  <!-- NAVBAR -->
  <nav class="bg-gray-800 p-4 shadow-md fixed w-full z-20">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-red-500 font-bold text-2xl">Iron Flame</a>
      <ul class="flex space-x-6 text-white">
        <li><a href="index.html" class="hover:text-red-400">Home</a></li>
        <li><a href="menu.html" class="hover:text-red-400 text-red-400">Menu</a></li>
        <li><a href="about.html" class="hover:text-red-400">Our Story</a></li>
        <li><a href="contact.html" class="hover:text-red-400">Contact</a></li>
        <li><a href="reserve.html" class="hover:text-red-400">Reservations</a></li>
        <li><a href="people.html" class="hover:text-red-400">Our Team</a></li>

      </ul>
    </div>
  </nav>

  <!-- MENU HERO -->
  <section class="menu-hero h-96 flex items-center justify-center relative pt-20">
    <div class="absolute inset-0 bg-black bg-opacity-60"></div>
    <div class="glass z-10 text-center p-10 rounded-xl max-w-2xl">
      <h1 class="text-5xl font-extrabold text-red-400">Our Menu</h1>
      <p class="text-xl text-gray-200 mt-4">Crafted by flame. Served with heart.</p>
    </div>
  </section>

  <!-- MENU GRID -->
  <section class="py-16 px-6 bg-gray-900">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-4xl font-bold text-center text-yellow-400 mb-12">Signature Dishes</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-10">

        <!-- Dish 1 -->
        <div class="bg-gray-800 rounded-lg overflow-hidden shadow-lg">
          <img src="citrus-greek-chicken-easy-healthy-dinner-recipe-14.jpg" alt="Smoked Chicken" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-2xl font-semibold text-red-400 mb-2">Smoked Citrus Chicken</h3>
            <p class="text-gray-300">Juicy whole roast infused with herbs, blood oranges & fire-roasted flavor.</p>
            <p class="text-yellow-400 mt-3 font-bold">$18.99</p>
          </div>
        </div>

        <!-- Dish 2 -->
        <div class="bg-gray-800 rounded-lg overflow-hidden shadow-lg">
          <img src="Easy-Grilled-VegetablesIMG_0768.jpg" alt="Veggies" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-2xl font-semibold text-red-400 mb-2">Grilled Garlic Veggies</h3>
            <p class="text-gray-300">Seasonal vegetables flame-kissed with garlic butter and balsamic drizzle.</p>
            <p class="text-yellow-400 mt-3 font-bold">$12.50</p>
          </div>
        </div>

        <!-- Dish 3 -->
        <div class="bg-gray-800 rounded-lg overflow-hidden shadow-lg">
          <img src="Grilled-lemon-Herb-Chicken-17.jpg" alt="Lemon Infusion" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-2xl font-semibold text-red-400 mb-2">Lemon Herb Infusion</h3>
            <p class="text-gray-300">Succulent grilled fillet glazed in lemon-thyme reduction.</p>
            <p class="text-yellow-400 mt-3 font-bold">$16.00</p>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="py-6 bg-gray-900 text-center text-gray-400">
    © 2025 Iron Flame Restaurant. All rights reserved.
  </footer>

</body>
</html>



```
### RESERVE.HTML


```
<!-- reserve.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Reservations - Iron Flame</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white font-serif">
  <nav class="bg-gray-800 p-4 shadow-md fixed w-full z-20">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-red-500 font-bold text-2xl">Iron Flame</a>
      <ul class="flex space-x-6 text-white">
        <li><a href="index.html" class="hover:text-red-400">Home</a></li>
        <li><a href="menu.html" class="hover:text-red-400">Menu</a></li>
        <li><a href="about.html" class="hover:text-red-400">Our Story</a></li>
        <li><a href="contact.html" class="hover:text-red-400">Contact</a></li>
        <li><a href="reserve.html" class="text-red-400">Reservations</a></li>
        <li><a href="people.html" class="hover:text-red-400">Our Team</a></li>

      </ul>
    </div>
  </nav>

  <section class="pt-32 px-6 max-w-3xl mx-auto">
    <h1 class="text-4xl font-bold text-yellow-400 mb-8">Book Your Table</h1>
    <form class="space-y-6">
      <div>
        <label class="block mb-2">Full Name</label>
        <input type="text" class="w-full p-3 rounded bg-gray-800 text-white border border-gray-600" placeholder="John Doe" />
      </div>
      <div>
        <label class="block mb-2">Date & Time</label>
        <input type="datetime-local" class="w-full p-3 rounded bg-gray-800 text-white border border-gray-600" />
      </div>
      <div>
        <label class="block mb-2">Guests</label>
        <input type="number" class="w-full p-3 rounded bg-gray-800 text-white border border-gray-600" placeholder="2" />
      </div>
      <div>
        <label class="block mb-2">Phone</label>
        <input type="tel" class="w-full p-3 rounded bg-gray-800 text-white border border-gray-600" placeholder="(123) 456-7890" />
      </div>
      <button type="submit" class="bg-red-500 hover:bg-red-600 text-white px-6 py-3 rounded font-semibold">Reserve Now</button>
    </form>
  </section>

  <footer class="py-6 mt-12 bg-gray-900 text-center text-gray-400">
    © 2025 Iron Flame Restaurant. All rights reserved.
  </footer>
</body>
</html>



```
### PEOPLE.HTML

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Menu - Iron Flame</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    .menu-hero {
      background-image: url('hero.jpg'); /* Same roasted food image */
      background-size: cover;
      background-position: center;
    }
    .glass {
      background: rgba(0, 0, 0, 0.5);
      backdrop-filter: blur(6px);
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-serif">

  <!-- NAVBAR -->
  <nav class="bg-gray-800 p-4 shadow-md fixed w-full z-20">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-red-500 font-bold text-2xl">Iron Flame</a>
      <ul class="flex space-x-6 text-white">
        <li><a href="index.html" class="hover:text-red-400">Home</a></li>
        <li><a href="menu.html" class="hover:text-red-400 text-red-400">Menu</a></li>
        <li><a href="about.html" class="hover:text-red-400">Our Story</a></li>
        <li><a href="contact.html" class="hover:text-red-400">Contact</a></li>
        <li><a href="reserve.html" class="hover:text-red-400">Reservations</a></li>
        <li><a href="people.html" class="hover:text-red-400">Our Team</a></li>

      </ul>
    </div>
  </nav>

  <!-- MENU HERO -->
  <section class="menu-hero h-96 flex items-center justify-center relative pt-20">
    <div class="absolute inset-0 bg-black bg-opacity-60"></div>
    <div class="glass z-10 text-center p-10 rounded-xl max-w-2xl">
      <h1 class="text-5xl font-extrabold text-red-400">Our Menu</h1>
      <p class="text-xl text-gray-200 mt-4">Crafted by flame. Served with heart.</p>
    </div>
  </section>

  <!-- MENU GRID -->
  <section class="py-16 px-6 bg-gray-900">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-4xl font-bold text-center text-yellow-400 mb-12">Signature Dishes</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-10">

        <!-- Dish 1 -->
        <div class="bg-gray-800 rounded-lg overflow-hidden shadow-lg">
          <img src="citrus-greek-chicken-easy-healthy-dinner-recipe-14.jpg" alt="Smoked Chicken" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-2xl font-semibold text-red-400 mb-2">Smoked Citrus Chicken</h3>
            <p class="text-gray-300">Juicy whole roast infused with herbs, blood oranges & fire-roasted flavor.</p>
            <p class="text-yellow-400 mt-3 font-bold">$18.99</p>
          </div>
        </div>

        <!-- Dish 2 -->
        <div class="bg-gray-800 rounded-lg overflow-hidden shadow-lg">
          <img src="Easy-Grilled-VegetablesIMG_0768.jpg" alt="Veggies" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-2xl font-semibold text-red-400 mb-2">Grilled Garlic Veggies</h3>
            <p class="text-gray-300">Seasonal vegetables flame-kissed with garlic butter and balsamic drizzle.</p>
            <p class="text-yellow-400 mt-3 font-bold">$12.50</p>
          </div>
        </div>

        <!-- Dish 3 -->
        <div class="bg-gray-800 rounded-lg overflow-hidden shadow-lg">
          <img src="Grilled-lemon-Herb-Chicken-17.jpg" alt="Lemon Infusion" class="w-full h-48 object-cover">
          <div class="p-6">
            <h3 class="text-2xl font-semibold text-red-400 mb-2">Lemon Herb Infusion</h3>
            <p class="text-gray-300">Succulent grilled fillet glazed in lemon-thyme reduction.</p>
            <p class="text-yellow-400 mt-3 font-bold">$16.00</p>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="py-6 bg-gray-900 text-center text-gray-400">
    © 2025 Iron Flame Restaurant. All rights reserved.
  </footer>

</body>
</html>



```
### ABOUT.HTML

```
<!-- about.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>About Us - Iron Flame</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white font-serif">

  <nav class="bg-gray-800 p-4 shadow-md fixed w-full z-20">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-red-500 font-bold text-2xl">Iron Flame</a>
      <ul class="flex space-x-6 text-white">
        <li><a href="index.html" class="hover:text-red-400">Home</a></li>
        <li><a href="menu.html" class="hover:text-red-400">Menu</a></li>
        <li><a href="about.html" class="text-red-400">Our Story</a></li>
        <li><a href="contact.html" class="hover:text-red-400">Contact</a></li>
        <li><a href="reserve.html" class="hover:text-red-400">Reservations</a></li>
        <li><a href="people.html" class="hover:text-red-400">Our Team</a></li>

      </ul>
    </div>
  </nav>

  <section class="pt-32 px-6 max-w-4xl mx-auto">
    <h1 class="text-5xl font-extrabold text-yellow-400 mb-6">Our Story</h1>
    <p class="text-gray-300 leading-relaxed mb-4">
      Iron Flame was born from a passion for bold flavors and rustic cooking traditions. What began as a backyard grilling experiment quickly evolved into a fire-forward dining experience unlike any other.
    </p>
    <p class="text-gray-300 leading-relaxed mb-4">
      Every dish is inspired by the heat of live flame and the essence of natural ingredients. Our chefs combine classical techniques with daring creativity to deliver every meal with unforgettable flavor.
    </p>
    <p class="text-gray-300 leading-relaxed">
      Whether you're enjoying a family dinner or a night out with friends, we welcome you to gather around the flame and enjoy our signature warmth—on and off the plate.
    </p>
  </section>

  <footer class="py-6 mt-12 bg-gray-900 text-center text-gray-400">
    © 2025 Iron Flame Restaurant. All rights reserved.
  </footer>
</body>
</html>



```

### STYLES.CSS

```
/* Reset & Base Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Georgia', serif;
  color: #2c2c2c;
  background-color: #fff8f0;
  line-height: 1.6;
}

/* Navbar */
nav {
  background-color: #3e2c24;
  padding: 1rem 2rem;
}
nav ul {
  list-style: none;
  display: flex;
  gap: 2rem;
  justify-content: center;
}
nav a {
  color: #fce5c0;
  text-decoration: none;
  font-weight: bold;
}
nav a:hover {
  color: #ffa552;
}

/* Header Banner */
.header {
  background: url('your-image.jpg') no-repeat center center/cover;
  height: 60vh;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
  text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.6);
  text-align: center;
}
.header h1 {
  font-size: 3rem;
  background: rgba(0, 0, 0, 0.5);
  padding: 1rem 2rem;
  border-radius: 10px;
}

/* Sections */
section {
  padding: 4rem 2rem;
  max-width: 1000px;
  margin: auto;
}
section h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  color: #3e2c24;
}

/* Menu Cards */
.menu-items {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 2rem;
}
.menu-item {
  background-color: #fff;
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}
.menu-item:hover {
  transform: translateY(-5px);
}
.menu-item h3 {
  color: #5c3b2e;
  margin-bottom: 0.5rem;
}

/* Contact & Reservation Forms */
form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
input, textarea {
  padding: 0.75rem;
  border-radius: 6px;
  border: 1px solid #ccc;
  font-size: 1rem;
}
button {
  padding: 0.75rem;
  background-color: #5c3b2e;
  color: white;
  border: none;
  border-radius: 6px;
  font-weight: bold;
  cursor: pointer;
}
button:hover {
  background-color: #ffa552;
}

/* Footer */
footer {
  background-color: #3e2c24;
  color: #fce5c0;
  text-align: center;
  padding: 1.5rem 0;
  margin-top: 2rem;
}

```



# OUTPUT:
![alt text](<Screenshot 2025-05-05 232438.png>)
![alt text](<Screenshot 2025-05-05 232503.png>)
![alt text](<Screenshot 2025-05-05 232524.png>)
![alt text](<Screenshot 2025-05-05 232542.png>)
![alt text](<Screenshot 2025-05-05 232601.png>)
![alt text](<Screenshot 2025-05-05 232624.png>)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
