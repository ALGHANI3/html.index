#<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Al Ghani Fragrances - Order Now</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f3f4f6; /* Light gray background fallback */
            color: #374151; /* Dark gray text */
            /* Updated background image styles */
            background-image: url('https://i.postimg.cc/zb9yLzPx/Screenshot-2024-05-05-151302.png'); /* Your new background image */
            background-size: cover; /* Cover the entire viewport */
            background-position: center; /* Center the background image */
            background-attachment: fixed; /* Fix the background image so it doesn't scroll */
            background-repeat: no-repeat; /* Do not repeat the background image */
        }
        /* Custom styles for smoother scrolling */
        html {
            scroll-behavior: smooth;
        }
        /* Style for the message box (instead of alert) */
        .message-box {
            position: fixed;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            background-color: #4CAF50; /* Green background */
            color: white;
            padding: 15px 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            z-index: 1000;
            opacity: 0;
            transition: opacity 0.5s ease-in-out;
        }
        .message-box.show {
            opacity: 1;
        }
        /* Added a semi-transparent overlay to improve text readability on the background image */
        .content-overlay {
            background-color: rgba(255, 255, 255, 0.8); /* White with 80% opacity */
            padding: 1rem; /* Add some padding */
            border-radius: 0.5rem; /* Rounded corners */
            position: relative; /* Needed for absolute positioning of logo if desired, but flex/grid is better */
        }
         /* Style for the logo container to position it top right */
        .logo-container {
            position: absolute; /* Position absolutely within the content-overlay */
            top: 1rem; /* 1rem from the top */
            right: 1rem; /* 1rem from the right */
            z-index: 10; /* Ensure it's above other content */
        }

         /* Adjust margin for the main heading to prevent overlap with logo */
        .main-heading {
            margin-top: 4rem; /* Add top margin to push content below logo */
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">
    <div class="container mx-auto p-4 sm:p-6 lg:p-8 max-w-screen-lg">
        <div class="content-overlay">
            <div class="logo-container">
                <img src="https://i.postimg.cc/LqWtTMb1/Screenshot-2024-05-05-152628.png" alt="Al Ghani Fragrances Logo" class="h-20 w-auto"> </div>

            <h1 class="main-heading text-3xl sm:text-4xl font-bold text-center mb-8 text-purple-800">Al Ghani Fragrances</h1>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300">
                    <img src="https://i.postimg.cc/Q9FRBvMX/Screenshot-2024-05-06-104520.png" alt="Kids Special Perfume" class="w-full h-48 object-cover mb-4 rounded-md border border-gray-200">
                    <h2 class="text-xl font-semibold text-gray-900 mb-2">Kids Special</h2>
                    <p class="text-green-600 font-bold text-lg mb-4">Rs. 1000</p>
                    <button onclick="orderNow('Kids Special')" class="w-full bg-blue-600 text-white px-4 py-2 rounded-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50 transition-colors duration-300">Order Now</button>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300">
                    <img src="https://i.postimg.cc/68zSMB2W/Screenshot-2024-05-06-104759.png" alt="For Women Perfume" class="w-full h-48 object-cover mb-4 rounded-md border border-gray-200">
                    <h2 class="text-xl font-semibold text-gray-900 mb-2">For Women</h2>
                    <p class="text-green-600 font-bold text-lg mb-4">Rs. 1800</p>
                    <button onclick="orderNow('For Women')" class="w-full bg-blue-600 text-white px-4 py-2 rounded-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50 transition-colors duration-300">Order Now</button>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300">
                    <img src="https://i.postimg.cc/ZCt1R7zS/Screenshot-2024-05-06-104709.png" alt="For Men Perfume" class="w-full h-48 object-cover mb-4 rounded-md border border-gray-200">
                    <h2 class="text-xl font-semibold text-gray-900 mb-2">For Men</h2>
                    <p class="text-green-600 font-bold text-lg mb-4">Rs. 1200</p>
                    <button onclick="orderNow('For Men')" class="w-full bg-blue-600 text-white px-4 py-2 rounded-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50 transition-colors duration-300">Order Now</button>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300">
                    <img src="https://i.postimg.cc/hJQzKQ2X/Screenshot-2024-05-05-152909.png" alt="Special Al Ghani Perfume" class="w-full h-48 object-cover mb-4 rounded-md border border-gray-200">
                    <h2 class="text-xl font-semibold text-gray-900 mb-2">Special Al Ghani</h2>
                    <p class="text-green-600 font-bold text-lg mb-4">Rs. 2000</p>
                    <button onclick="orderNow('Special Al Ghani')" class="w-full bg-blue-600 text-white px-4 py-2 rounded-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50 transition-colors duration-300">Order Now</button>
                </div>
            </div>

            <div class="mt-12 bg-white p-6 rounded-lg shadow-md text-center">
                <h2 class="text-2xl font-bold mb-4 text-purple-800">✨ Key Features ✨</h2>
                <img src="https://i.postimg.cc/FsBFmNfy/Untitled-design-2.png" alt="Al Ghani Fragrances Key Features" class="mx-auto w-full max-w-lg rounded-md border border-gray-200">
            </div>


            <div id="order-form-section" class="mt-12 bg-white p-6 rounded-lg shadow-md">
                <h2 class="text-2xl font-bold mb-4 text-purple-800">📝 Order Form</h2>
                <form id="orderForm" onsubmit="return sendOrder(event)">
                    <div class="mb-4">
                        <label for="name" class="block text-gray-700 text-sm font-bold mb-2">Your Name:</label>
                        <input type="text" id="name" placeholder="Enter your name" class="w-full p-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500" required>
                    </div>
                    <div class="mb-4">
                         <label for="address" class="block text-gray-700 text-sm font-bold mb-2">Your Address:</label>
                         <input type="text" id="address" placeholder="Enter your address" class="w-full p-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500" required>
                    </div>
                    <div class="mb-4">
                         <label for="phone" class="block text-gray-700 text-sm font-bold mb-2">Your Phone:</label>
                         <input type="tel" id="phone" placeholder="Enter your phone number" class="w-full p-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500" required>
                    </div>
                     <div class="mb-6">
                         <label for="product" class="block text-gray-700 text-sm font-bold mb-2">Selected Perfume:</label>
                         <input type="text" id="product" placeholder="Select a perfume from above" class="w-full p-3 border border-gray-300 rounded-md bg-gray-100 cursor-not-allowed" readonly required>
                    </div>
                    <button type="submit" class="w-full bg-green-600 text-white px-4 py-3 rounded-md font-semibold hover:bg-green-700 focus:outline-none focus:ring-2 focus:ring-green-500 focus:ring-opacity-50 transition-colors duration-300">Submit Order</button>
                </form>
            </div>

            <footer class="mt-12 text-center text-sm text-gray-600">
                📞 Contact us: <strong class="text-blue-700">03442128439</strong> | WhatsApp your orders anytime.
            </footer>
        </div>
    </div>

    <div id="messageBox" class="message-box"></div>

    <script>
        /**
         * Function to populate the selected perfume in the order form
         * and smoothly scroll to the form section.
         * @param {string} perfume - The name of the selected perfume.
         */
        function orderNow(perfume) {
            // Set the value of the product input field
            document.getElementById('product').value = perfume;

            // Scroll smoothly to the order form section
            const orderFormSection = document.getElementById('order-form-section');
            if (orderFormSection) {
                orderFormSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
        }

        /**
         * Function to handle the form submission and send the order via WhatsApp.
         * Prevents the default form submission.
         * @param {Event} event - The form submission event.
         * @returns {boolean} - Returns false to prevent default form submission.
         */
        function sendOrder(event) {
            // Prevent the default form submission
            event.preventDefault();

            // Get form values
            const name = document.getElementById('name').value.trim();
            const address = document.getElementById('address').value.trim();
            const phone = document.getElementById('phone').value.trim();
            const product = document.getElementById('product').value.trim();

            // Basic validation
            if (!name || !address || !phone || !product) {
                showMessage("Please fill in all fields.", 'error');
                return false;
            }

            // Construct the WhatsApp message
            const message = `Hi, I want to order ${product}.\nName: ${name}\nAddress: ${address}\nPhone: ${phone}`;
            const encodedMessage = encodeURIComponent(message);

            // Your WhatsApp number (replace with your actual number)
            const whatsappNumber = '923442128439'; // Updated WhatsApp number

            // Open WhatsApp chat in a new tab
            window.open(`https://wa.me/${whatsappNumber}?text=${encodedMessage}`, '_blank');

            // Optionally, clear the form after submission
            document.getElementById('orderForm').reset();
            // Clear the readonly product field separately
             document.getElementById('product').value = '';


            // Show a success message
            showMessage("Order initiated! Please complete the order on WhatsApp.", 'success');

            return false; // Prevent default form submission
        }

        /**
         * Function to display a message box.
         * @param {string} message - The message to display.
         * @param {string} type - The type of message ('success' or 'error').
         */
        function showMessage(message, type) {
            const messageBox = document.getElementById('messageBox');
            messageBox.textContent = message;

            // Set background color based on message type
            if (type === 'success') {
                messageBox.style.backgroundColor = '#4CAF50'; // Green
            } else if (type === 'error') {
                messageBox.style.backgroundColor = '#f44336'; // Red
            }

            messageBox.classList.add('show');

            // Hide the message box after 5 seconds
            setTimeout(() => {
                messageBox.classList.remove('show');
            }, 5000);
        }
    </script>
</body>
</html>
