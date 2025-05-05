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
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Iron Pulse Gym</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    .hero {
      background-image: url('1111.jpg');
      background-size: cover;
      background-position: center;
    }
    .glass {
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(10px);
      border: 1px solid rgba(255, 255, 255, 0.2);
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-sans">

  <!-- NAVIGATION BAR -->
  <nav class="bg-gray-800 p-4 shadow-md fixed w-full z-20">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-yellow-400 font-bold text-2xl">Iron Pulse</a>
      <ul class="flex space-x-6 text-white">
        <li><a href="index.html" class="hover:text-yellow-400">Home</a></li>
        <li><a href="people.html" class="hover:text-yellow-400">Our People</a></li>
        <li><a href="contact.html" class="hover:text-yellow-400">Contact</a></li>
        <li><a href="signup.html" class="hover:text-yellow-400">Sign Up</a></li>
        <li><a href="product.html" class="hover:text-yellow-400">Products</a></li>
      </ul>
    </div>
  </nav>

  <!-- HERO SECTION -->
  <section class="hero h-screen flex items-center justify-center relative pt-20">
    <div class="absolute inset-0 bg-black bg-opacity-60"></div>
    <div class="glass z-10 text-center p-10 rounded-xl max-w-2xl">
      <h1 class="text-5xl font-extrabold mb-4">Iron Pulse Gym</h1>
      <p class="text-xl mb-6">Where Strength Meets Dedication</p>
      <a href="signup.html" class="bg-yellow-400 text-gray-900 font-semibold px-6 py-3 rounded-full hover:bg-yellow-500 transition">Join the Revolution</a>    </div>
  </section>

  <!-- FEATURES -->
  <section class="py-16 px-6 text-center bg-gray-800">
    <h2 class="text-4xl font-bold mb-4">Our Core Benefits</h2>
    <p class="text-gray-300 mb-10 max-w-2xl mx-auto">Unleash your potential with elite coaching, immersive workout zones, and 24/7 access to the best gear available.</p>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
      <div class="bg-gray-700 p-6 rounded-xl shadow-lg">
        <h3 class="text-2xl font-semibold mb-2">Pro Equipment</h3>
        <p>Top-tier machines & free weights for all training levels.</p>
      </div>
      <div class="bg-gray-700 p-6 rounded-xl shadow-lg">
        <h3 class="text-2xl font-semibold mb-2">Elite Trainers</h3>
        <p>Certified professionals focused on your transformation.</p>
      </div>
      <div class="bg-gray-700 p-6 rounded-xl shadow-lg">
        <h3 class="text-2xl font-semibold mb-2">Dynamic Classes</h3>
        <p>HIIT, yoga, strength & more with high energy atmosphere.</p>
      </div>
    </div>
  </section>

  <!-- CTA SECTION -->
  <section id="join" class="py-20 bg-gradient-to-r from-yellow-400 to-yellow-500 text-center text-gray-900">
    <h2 class="text-4xl font-extrabold mb-4">Start Your Fitness Journey Today</h2>
    <p class="text-lg mb-8">No contracts. No excuses. Just results.</p>
    <a href="signup.html" class="bg-gray-900 text-yellow-400 px-8 py-3 font-bold rounded-full hover:bg-gray-800 transition">Sign Up Now</a>
  </section>

  <!-- FOOTER -->
  <footer class="py-6 bg-gray-900 text-center text-gray-400">
    © 2025 Iron Pulse Gym. All rights reserved.
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
  <title>Contact Us - Iron Pulse</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white">
  <nav class="bg-gray-800 p-4 shadow-md">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-yellow-400 font-bold text-2xl">Iron Pulse</a>
      <ul class="flex space-x-6 text-white">
        <li><a href="index.html" class="hover:text-yellow-400">Home</a></li>
        <li><a href="people.html" class="hover:text-yellow-400">Our People</a></li>
        <li><a href="product.html" class="hover:text-yellow-400">Products</a></li>
        <li><a href="signup.html" class="hover:text-yellow-400">Sign Up</a></li>
      </ul>
    </div>
  </nav>

  <section class="py-20 px-6 text-center">
    <h1 class="text-4xl font-bold mb-6">Get in Touch</h1>
    <p class="text-gray-300 mb-8">Have questions? We're here to help you get started on your fitness journey.</p>
    <form class="max-w-xl mx-auto space-y-4">
      <input type="text" placeholder="Your Name" class="w-full p-3 rounded bg-gray-800 border border-gray-600" required />
      <input type="email" placeholder="Your Email" class="w-full p-3 rounded bg-gray-800 border border-gray-600" required />
      <textarea placeholder="Your Message" rows="4" class="w-full p-3 rounded bg-gray-800 border border-gray-600" required></textarea>
      <button type="submit" class="bg-yellow-400 text-gray-900 px-6 py-3 rounded-full hover:bg-yellow-500 transition">Send Message</button>
    </form>
  </section>

  <footer class="py-6 bg-gray-800 text-center text-gray-400">
    © 2025 Iron Pulse Gym. All rights reserved.
  </footer>
</body>
</html>


```

### PEOPLE.HTML


```
<!-- people.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Our People - Iron Pulse</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white">
  <nav class="bg-gray-800 p-4 shadow-md">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-yellow-400 font-bold text-2xl">Iron Pulse</a>
      <ul class="flex space-x-6 text-white">
        <li><a href="index.html" class="hover:text-yellow-400">Home</a></li>
        <li><a href="contact.html" class="hover:text-yellow-400">Contact</a></li>
        <li><a href="product.html" class="hover:text-yellow-400">Products</a></li>
        <li><a href="signup.html" class="hover:text-yellow-400">Sign Up</a></li>

      </ul>
    </div>
  </nav>

  <section class="py-20 px-6 text-center">
    <h1 class="text-4xl font-bold mb-8">Meet Our Team</h1>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-10 max-w-6xl mx-auto">
      
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <img src="bau.jpg" alt="Alex Strong" class="w-32 h-32 object-cover rounded-full mx-auto mb-4 border-4 border-yellow-400">
        <h3 class="text-2xl font-semibold mb-2">BAUDHI</h3>
        <p>Strength Coach</p>
      </div>
      
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <img src="vatsan.jpeg" alt="Jessie Flex" class="w-32 h-32 object-cover rounded-full mx-auto mb-4 border-4 border-yellow-400">
        <h3 class="text-2xl font-semibold mb-2">VATSAN</h3>
        <p>HIIT Specialist</p>
      </div>
      
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <img src="bhuvan.jpg" alt="Maya Zen" class="w-32 h-32 object-cover rounded-full mx-auto mb-4 border-4 border-yellow-400">
        <h3 class="text-2xl font-semibold mb-2">BHUVANESH</h3>
        <p>Yoga Trainer</p>
      </div>
      
    </div>
  </section>
  

  <footer class="py-6 bg-gray-800 text-center text-gray-400">
    © 2025 Iron Pulse Gym. All rights reserved.
  </footer>
</body>
</html>


```
### PRODUCT.HTML

```
<!-- product.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Iron Pulse Products</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white font-sans">

  <!-- NAVIGATION BAR -->
  <nav class="bg-gray-800 p-4 shadow-md fixed w-full z-20">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-yellow-400 font-bold text-2xl">Iron Pulse</a>
      <ul class="flex space-x-6 text-white">
        <li><a href="index.html" class="hover:text-yellow-400">Home</a></li>
        <li><a href="people.html" class="hover:text-yellow-400">Our People</a></li>
        <li><a href="contact.html" class="hover:text-yellow-400">Contact</a></li>
        <li><a href="signup.html" class="hover:text-yellow-400">Sign Up</a></li>
      </ul>
    </div>
  </nav>

  <main class="pt-24 pb-16 px-6">
    <h1 class="text-4xl font-bold text-center mb-8">Our Products</h1>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-10 max-w-6xl mx-auto">
      <!-- Product Card -->
      <div class="bg-gray-800 p-6 rounded-xl shadow-lg">
        <img src="1.0.jpg" alt="Performance Kit" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Performance Kit</h3>
        <p class="text-gray-300">Shirt, resistance bands, shaker & towel.</p>
        <p class="font-bold mt-2">$49.99</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow-lg">
        <img src="2.0.jpg" alt="Gym Backpack" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Gym Backpack</h3>
        <p class="text-gray-300">Spacious, durable, and water-resistant.</p>
        <p class="font-bold mt-2">$34.99</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow-lg">
        <img src="3.0.jpg" alt="Whey Protein" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Whey Protein</h3>
        <p class="text-gray-300">25g protein per scoop, chocolate flavor.</p>
        <p class="font-bold mt-2">$39.99</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow-lg">
        <img src="5.0.jpeg" alt="Training Gloves" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Training Gloves</h3>
        <p class="text-gray-300">Grip-enhanced, breathable mesh fabric.</p>
        <p class="font-bold mt-2">$14.99</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow-lg">
        <img src="4.0.jpg" alt="Workout Mat" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Workout Mat</h3>
        <p class="text-gray-300">Non-slip, high-density cushioning mat.</p>
        <p class="font-bold mt-2">$29.99</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow-lg">
        <img src="6.0.jpg" alt="Smart Bottle" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Smart Bottle</h3>
        <p class="text-gray-300">Tracks water intake, BPA-free, USB charging.</p>
        <p class="font-bold mt-2">$24.99</p>
      </div>
    </div>
  </main>

  <!-- FOOTER -->
  <footer class="py-6 bg-gray-900 text-center text-gray-400">
    © 2025 Iron Pulse Gym. All rights reserved.
  </footer>

</body>
</html>

```
### SIGNUP.HTML

```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sign Up - Iron Pulse</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white">
  <nav class="bg-gray-800 p-4 shadow-md">
    <div class="container mx-auto flex justify-between items-center">
      <a href="index.html" class="text-yellow-400 font-bold text-2xl">Iron Pulse</a>
      <ul class="flex space-x-6 text-white">
        <li><a href="index.html" class="hover:text-yellow-400">Home</a></li>
        <li><a href="people.html" class="hover:text-yellow-400">Our People</a></li>
        <li><a href="product.html" class="hover:text-yellow-400">Products</a></li>
        <li><a href="contact.html" class="hover:text-yellow-400">Contact</a></li>
      </ul>
    </div>
  </nav>

  <section class="py-20 px-6 text-center">
    <h1 class="text-4xl font-bold mb-6">Create Your Account</h1>
    <form class="max-w-xl mx-auto space-y-4">
      <input type="text" placeholder="Full Name" class="w-full p-3 rounded bg-gray-800 border border-gray-600" required />
      <input type="email" placeholder="Email Address" class="w-full p-3 rounded bg-gray-800 border border-gray-600" required />
      <input type="password" placeholder="Password" class="w-full p-3 rounded bg-gray-800 border border-gray-600" required />
      <button type="submit" class="bg-yellow-400 text-gray-900 px-6 py-3 rounded-full hover:bg-yellow-500 transition">Sign Up</button>
    </form>
  </section>

  <footer class="py-6 bg-gray-800 text-center text-gray-400">
    © 2025 Iron Pulse Gym. All rights reserved.
  </footer>
</body>
</html>



```

### STYLE.CSS

```

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #bb0e0e;
}

header {
  background-color: #09a9b4;
  color: rgb(33, 3, 102);
  padding: 10px;
  text-align: center;
}

#searchBar {
  margin: 10px;
  padding: 5px;
  width: 200px;
}

nav {
  background-color: #c7760c;
  padding: 10px 0;
}

.nav-links {
  list-style: none;
  display: flex;
  justify-content: center;
  margin: 0;
  padding: 0;
}

.nav-links li {
  margin: 0 15px;
}

.nav-links a {
  color: rgb(58, 13, 182);
  text-decoration: none;
  font-weight: bold;
  padding: 6px 12px;
  border-radius: 4px;
}

.nav-links a:hover {
  background-color: #c8dbae;
}

main {
  margin: 20px;
}

form {
  max-width: 500px;
  margin: 20px auto;
  background: white;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

label {
  display: block;
  margin-top: 10px;
}

input, textarea {
  width: 100%;
  padding: 8px;
  margin-top: 5px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

button {
  margin-top: 15px;
  padding: 10px;
  background-color: #4CAF50;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

button:hover {
  background-color: #45a049;
}

ul {
  list-style: none;
  padding: 0;
  margin: 20px auto;
  max-width: 600px;
}

li {
  background: white;
  margin-bottom: 10px;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
  display: flex;
  gap: 15px;
  align-items: center;
}

li img {
  border-radius: 50%;
  width: 80px;
  height: 80px;
}


```

# OUTPUT:
![alt text](<Screenshot 2025-05-05 214239.png>)
![alt text](<Screenshot 2025-05-05 214855.png>)
![alt text](<Screenshot 2025-05-05 214106.png>)
![alt text](<Screenshot 2025-05-05 214134.png>)
![alt text](<Screenshot 2025-05-05 214216.png>)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
