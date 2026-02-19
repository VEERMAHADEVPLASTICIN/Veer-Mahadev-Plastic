<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>वीर महादेव प्लास्टिक | Premium Disposable Shop</title>
    <style>
        /* कलर थीम */
        :root {
            --pistachio: #B2D3C2;
            --light-pink: #FFD1DC;
            --dark-text: #333;
            --white: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            color: var(--dark-text);
            line-height: 1.6;
        }

        /* हेडर */
        header {
            background-color: var(--light-pink);
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        header h1 {
            margin: 0;
            color: #444;
            font-size: 28px;
        }

        /* हीरो सेक्शन */
        .hero {
            background-color: var(--pistachio);
            padding: 60px 20px;
            text-align: center;
        }

        .hero h2 {
            font-size: 36px;
            margin-bottom: 10px;
        }

        .btn-catalog {
            background-color: var(--light-pink);
            padding: 12px 25px;
            border: none;
            border-radius: 25px;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            margin-top: 20px;
            color: #333;
        }

        /* कैटलॉग सेक्शन */
        .catalog {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .product-card {
            border: 2px solid var(--pistachio);
            border-radius: 15px;
            padding: 20px;
            text-align: center;
            background: var(--white);
        }

        /* लोकेशन और कांटेक्ट */
        .contact-info {
            background-color: #f9f9f9;
            padding: 40px 20px;
            text-align: center;
            border-top: 5px solid var(--pistachio);
        }

        .whatsapp-float {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #25D366;
            color: white;
            padding: 15px 20px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.2);
        }

        footer {
            background: var(--dark-text);
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>वीर महादेव प्लास्टिक</h1>
        <p>रबारी कॉलोनी, अहमदाबाद</p>
    </header>

    <section class="hero">
        <h2>Premium Quality Disposable & Plastic Products</h2>
        <p>अब आपके रबारी कॉलोनी में सबसे बेहतरीन रेट्स पर।</p>
        <a href="#catalog" class="btn-catalog">हमारा कैटलॉग देखें</a>
    </section>

    <div class="catalog" id="catalog">
        <div class="product-card">
            <h3>कंटेनर्स</h3>
            <p>लीक-प्रूफ और मजबूत क्वालिटी</p>
        </div>
        <div class="product-card">
            <h3>ग्लास और कप</h3>
            <p>हर साइज में उपलब्ध</p>
        </div>
        <div class="product-card">
            <h3>प्लेट्स और चम्मच</h3>
            <p>पार्टी और इवेंट्स के लिए बेस्ट</p>
        </div>
    </div>

    <section class="contact-info">
        <h3>📍 हमारी दुकान यहाँ है</h3>
        <p>रबारी कॉलोनी, मेट्रो पिलर नंबर 74 के सामने,</p>
        <p>रेस्टोरेंट वीर महादेव प्लास्टिक, अहमदाबाद - 382415</p>
        <p><strong>संपर्क:</strong> [अपना नंबर यहाँ लिखें]</p>
        
        <div style="margin-top: 20px; background: #ddd; height: 200px; display: flex; align-items: center; justify-content: center;">
            गूगल मैप यहाँ दिखाई देगा
        </div>
    </section>

    <a href="https://wa.me/YOURNUMBERHERE" class="whatsapp-float" target="_blank">
        💬 ऑर्डर के लिए मैसेज करें
    </a>

    <footer>
        <p>&copy; 2026 वीर महादेव प्लास्टिक - सर्वाधिकार सुरक्षित</p>
    </footer>

</body>
</html>
<section id="products" class="container mx-auto px-4 py-12">
    <h2 class="text-3xl font-bold text-center mb-10 text-gray-800 underline decoration-red-500">Our Premium Collection</h2>
    
    <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
        
        <div class="bg-white p-4 rounded-xl shadow product-card border border-gray-100">
            <img src="https://via.placeholder.com/400x400.png?text=13-Inch+Buffer+Plate" class="w-full h-40 object-cover rounded-lg mb-4" alt="Buffer Plate">
            <h3 class="font-bold text-gray-800">13" Buffer Plate</h3>
            <p class="text-xs text-gray-500 mb-2">Heavy Duty - Wholesale Rate</p>
            <button onclick="addToCart('13 Inch Buffer Plate')" class="w-full bg-red-600 text-white py-2 rounded-lg text-sm font-bold"><i class="fa fa-cart-plus"></i> Add to Cart</button>
        </div>

        <div class="bg-white p-4 rounded-xl shadow product-card border border-gray-100">
            <img src="https://via.placeholder.com/400x400.png?text=Ripple+Tea+Cup" class="w-full h-40 object-cover rounded-lg mb-4" alt="Ripple Tea Cup">
            <h3 class="font-bold text-gray-800">Ripple Tea Cup</h3>
            <p class="text-xs text-gray-500 mb-2">Premium Insulation - All Sizes</p>
            <button onclick="addToCart('Ripple Tea Cup')" class="w-full bg-red-600 text-white py-2 rounded-lg text-sm font-bold"><i class="fa fa-cart-plus"></i> Add to Cart</button>
        </div>

        <div class="bg-white p-4 rounded-xl shadow product-card border border-gray-100">
            <img src="https://via.placeholder.com/400x400.png?text=Aluminium+Foil+Roll" class="w-full h-40 object-cover rounded-lg mb-4" alt="Foil Roll">
            <h3 class="font-bold text-gray-800">Aluminium Foil Roll</h3>
            <p class="text-xs text-gray-500 mb-2">High Micron - Food Grade</p>
            <button onclick="addToCart('Aluminium Foil Paper Roll')" class="w-full bg-red-600 text-white py-2 rounded-lg text-sm font-bold"><i class="fa fa-cart-plus"></i> Add to Cart</button>
        </div>

        <div class="bg-white p-4 rounded-xl shadow product-card border border-gray-100">
            <img src="https://via.placeholder.com/400x400.png?text=Food+Container" class="w-full h-40 object-cover rounded-lg mb-4" alt="Food Container">
            <h3 class="font-bold text-gray-800">Transparent Container</h3>
            <p class="text-xs text-gray-500 mb-2">Leak Proof - Microwave Safe</p>
            <button onclick="addToCart('Transparent Food Container')" class="w-full bg-red-600 text-white py-2 rounded-lg text-sm font-bold"><i class="fa fa-cart-plus"></i> Add to Cart</button>
        </div>

        <div class="bg-white p-4 rounded-xl shadow product-card border border-gray-100">
            <img src="https://via.placeholder.com/400x400.png?text=Bio+Spoons" class="w-full h-40 object-cover rounded-lg mb-4" alt="Bio Spoons">
            <h3 class="font-bold text-gray-800">Biodegradable Spoons</h3>
            <p class="text-xs text-gray-500 mb-2">Eco-Friendly - Strong Grip</p>
            <button onclick="addToCart('Biodegradable Spoons')" class="w-full bg-red-600 text-white py-2 rounded-lg text-sm font-bold"><i class="fa fa-cart-plus"></i> Add to Cart</button>
        </div>

        <div class="bg-white p-4 rounded-xl shadow product-card border border-gray-100">
            <img src="https://via.placeholder.com/400x400.png?text=Bio+Knife" class="w-full h-40 object-cover rounded-lg mb-4" alt="Bio Knife">
            <h3 class="font-bold text-gray-800">Biodegradable Knife</h3>
            <p class="text-xs text-gray-500 mb-2">Eco-Friendly Cutlery</p>
            <button onclick="addToCart('Biodegradable Knife')" class="w-full bg-red-600 text-white py-2 rounded-lg text-sm font-bold"><i class="fa fa-cart-plus"></i> Add to Cart</button>
        </div>

        <div class="bg-white p-4 rounded-xl shadow product-card border border-gray-100">
            <img src="https://via.placeholder.com/400x400.png?text=Disposable+Glasses" class="w-full h-40 object-cover rounded-lg mb-4" alt="Glasses">
            <h3 class="font-bold text-gray-800">Premium Glasses</h3>
            <p class="text-xs text-gray-500 mb-2">Crystal Clear - All Sizes</p>
            <button onclick="addToCart('Premium Glasses')" class="w-full bg-red-600 text-white py-2 rounded-lg text-sm font-bold"><i class="fa fa-cart-plus"></i> Add to Cart</button>
        </div>

    </div>
</section>
