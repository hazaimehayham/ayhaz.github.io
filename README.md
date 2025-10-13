# ayhaz.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MedComfy Supply Haven - Medical Comfort Products</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body class="bg-gray-50">
    <header class="bg-white shadow-sm">
        <div class="container mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <a href="index.html" class="text-2xl font-bold text-blue-600">MedComfy</a>
                <nav class="hidden md:flex space-x-8">
                    <a href="index.html" class="text-blue-600 font-medium">Home</a>
                    <a href="products.html" class="text-gray-600 hover:text-blue-600">Products</a>
                    <a href="about.html" class="text-gray-600 hover:text-blue-600">About</a>
                    <a href="contact.html" class="text-gray-600 hover:text-blue-600">Contact</a>
                </nav>
                <div class="flex items-center space-x-4">
                    <a href="#" class="text-gray-600 hover:text-blue-600"><i class="fas fa-search"></i></a>
                    <a href="cart.html" class="text-gray-600 hover:text-blue-600 relative">
                        <i class="fas fa-shopping-cart"></i>
                        <span id="cart-count" class="absolute -top-2 -right-2 bg-blue-600 text-white text-xs rounded-full h-5 w-5 flex items-center justify-center">0</span>
                    </a>
</div>
            </div>
        </div>
    </header>

    <main class="container mx-auto px-6 py-12">
        <section class="hero bg-blue-50 rounded-xl p-12 mb-16 text-center">
            <h1 class="text-4xl md:text-5xl font-bold text-blue-800 mb-6">Premium Medical Comfort Products</h1>
            <p class="text-xl text-gray-600 mb-8 max-w-2xl mx-auto">High-quality lab coats, scrubs, bandages, and memory foam comfort products designed for healthcare professionals.</p>
            <a href="products.html" class="bg-blue-600 text-white px-8 py-3 rounded-lg text-lg font-medium hover:bg-blue-700">Shop Now</a>
        </section>

        <section class="featured mb-16">
            <h2 class="text-3xl font-bold text-center mb-12">Featured Products</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <img src="http://static.photos/medical/640x360/7" alt="Medical Scrubs" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Medical Scrubs</h3>
                        <p class="text-gray-600 mb-4">Comfortable and durable scrubs for healthcare workers.</p>
                    </div>
                </div>
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <img src="http://static.photos/medical/640x360/8" alt="Memory Foam Pillow" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Memory Foam Pillow</h3>
                        <p class="text-gray-600 mb-4">Orthopedic support for better sleep and posture.</p>
                    </div>
                </div>
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <img src="http://static.photos/medical/640x360/9" alt="Medical Bandages" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Medical Bandages</h3>
                        <p class="text-gray-600 mb-4">High-quality wound care products.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="bg-blue-800 text-white rounded-xl p-12 text-center mb-16">
            <h2 class="text-3xl font-bold mb-4">Why Choose MedComfy?</h2>
            <p class="text-xl mb-8 max-w-2xl mx-auto">We combine medical-grade quality with exceptional comfort for professionals who need both.</p>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                    <div class="bg-blue-700 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-check text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Premium Quality</h3>
                    <p class="text-blue-200">Medical-grade materials that last</p>
                </div>
                <div>
                    <div class="bg-blue-700 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-truck text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Fast Shipping</h3>
                    <p class="text-blue-200">Delivered to your door in 2-3 days</p>
                </div>
                <div>
                    <div class="bg-blue-700 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-headset text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">24/7 Support</h3>
                    <p class="text-blue-200">Our team is always here to help</p>
                </div>
            </div>
        </section>
    </main>
    <script>
        // Update cart count on page load
        document.addEventListener('DOMContentLoaded', function() {
            const cartItems = JSON.parse(localStorage.getItem('cart')) || [];
            const cartCount = document.getElementById('cart-count');
            cartCount.textContent = cartItems.reduce((sum, item) => sum + item.quantity, 0);
        });
    </script>
<footer class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">MedComfy</h3>
                    <p class="text-gray-400">Quality medical and comfort products for professionals.</p>
                </div>
                <div>
                    <h4 class="font-semibold mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="index.html" class="text-gray-400 hover:text-white">Home</a></li>
                        <li><a href="products.html" class="text-gray-400 hover:text-white">Products</a></li>
                        <li><a href="about.html" class="text-gray-400 hover:text-white">About Us</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-semibold mb-4">Customer Service</h4>
                    <ul class="space-y-2">
                        <li><a href="contact.html" class="text-gray-400 hover:text-white">Contact Us</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">FAQs</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Shipping Policy</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-semibold mb-4">Connect With Us</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
                <p>© 2023 MedComfy Supply Haven. All rights reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>
