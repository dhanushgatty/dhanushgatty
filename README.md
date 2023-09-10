<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Snooker Club</title>
    <!-- Include the Tailwind CSS CDN link here -->
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.15/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 font-sans">
    <!-- Header Section -->
    <header class="bg-green-600 p-4">
        <div class="container mx-auto">
            <h1 class="text-4xl text-white font-semibold">Snooker Club</h1>
            <p class="text-white mt-2">Welcome to the best snooker club in town!</p>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="py-16">
        <div class="container mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div>
                    <h2 class="text-3xl font-semibold mb-4">Play Snooker Like a Pro</h2>
                    <p class="text-gray-700">Join our snooker club and sharpen your skills with the best players in town.</p>
                    <a href="#contact" class="mt-4 inline-block bg-green-600 text-white py-2 px-6 rounded-full hover:bg-green-700 transition duration-300">Join Now</a>
                </div>
                <div>
                    <img src="snooker-table.jpg" alt="Snooker Table" class="rounded-lg shadow-lg">
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-gray-200 py-16">
        <div class="container mx-auto">
            <h2 class="text-3xl font-semibold text-center mb-8">Contact Us</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div>
                    <h3 class="text-xl font-semibold">Get in Touch</h3>
                    <p class="text-gray-700">Have any questions or want to join our club? Contact us now!</p>
                </div>
                <div>
                    <form>
                        <div class="mb-4">
                            <label for="name" class="block text-gray-600">Your Name</label>
                            <input type="text" id="name" name="name" class="w-full rounded-lg border-gray-300 focus:border-green-600 focus:ring focus:ring-green-200 py-2 px-4">
                        </div>
                        <div class="mb-4">
                            <label for="email" class="block text-gray-600">Email Address</label>
                            <input type="email" id="email" name="email" class="w-full rounded-lg border-gray-300 focus:border-green-600 focus:ring focus:ring-green-200 py-2 px-4">
                        </div>
                        <div class="mb-4">
                            <label for="message" class="block text-gray-600">Message</label>
                            <textarea id="message" name="message" rows="4" class="w-full rounded-lg border-gray-300 focus:border-green-600 focus:ring focus:ring-green-200 py-2 px-4"></textarea>
                        </div>
                        <button type="submit" class="bg-green-600 text-white py-2 px-6 rounded-full hover:bg-green-700 transition duration-300">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto text-center">
            <p>&copy; 2023 Snooker Club. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
<!-- Membership Section -->
<section class="bg-white py-16">
    <div class="container mx-auto">
        <h2 class="text-3xl font-semibold text-center mb-8">Membership Plans</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div class="bg-green-100 p-6 rounded-lg">
                <h3 class="text-2xl font-semibold mb-2">Standard Membership</h3>
                <p class="text-gray-700">Enjoy unlimited access to our snooker tables during regular hours.</p>
                <p class="text-gray-700 mt-2">Price: $50/month</p>
            </div>
            <div class="bg-blue-100 p-6 rounded-lg">
                <h3 class="text-2xl font-semibold mb-2">Premium Membership</h3>
                <p class="text-gray-700">Get 24/7 access to our club, exclusive events, and free equipment rental.</p>
                <p class="text-gray-700 mt-2">Price: $80/month</p>
            </div>
        </div>
    </div>
</section>

<!-- Testimonials Section -->
<section class="bg-gray-200 py-16">
    <div class="container mx-auto">
        <h2 class="text-3xl font-semibold text-center mb-8">What Our Members Say</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div class="bg-white p-6 rounded-lg shadow-lg">
                <blockquote class="text-gray-700">
                    "I love being a part of the Snooker Club! It's the perfect place to unwind and improve my skills."
                </blockquote>
                <p class="text-gray-600 mt-4">- John Doe</p>
            </div>
            <div class="bg-white p-6 rounded-lg shadow-lg">
                <blockquote class="text-gray-700">
                    "The club's atmosphere is fantastic, and the staff is always friendly and helpful."
                </blockquote>
                <p class="text-gray-600 mt-4">- Jane Smith</p>
            </div>
        </div>
    </div>
</section>
<div class="bg-green-100 p-6 rounded-lg">
    <img src="standard-membership.jpg" alt="Standard Membership" class="mb-4">
    <h3 class="text-2xl font-semibold mb-2">Standard Membership</h3>
    <p class="text-gray-700">Enjoy unlimited access to our snooker tables during regular hours.</p>
    <p class="text-gray-700 mt-2">Price: $50/month</p>
</div>
<div class="bg-white p-6 rounded-lg shadow-lg">
    <blockquote class="text-gray-700">
        "I love being a part of the Snooker Club! It's the perfect place to unwind and improve my skills."
    </blockquote>
    <p class="text-gray-600 mt-4">- John Doe</p>
    <img src="john-doe-photo.jpg" alt="John Doe Photo" class="mt-4 rounded-full w-16 h-16 mx-auto">
</div>
