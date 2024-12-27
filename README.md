<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academic Writing Services</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 text-gray-800">
    <!-- Navbar -->
    <nav class="bg-blue-800 text-white px-6 py-4 shadow-md sticky top-0 z-50">
        <div class="container mx-auto flex justify-between items-center">
            <a href="#" class="text-2xl font-bold">AcademicWritePro</a>
            <ul class="flex space-x-6">
                <li><a href="#services" class="hover:text-gray-300">Services</a></li>
                <li><a href="#pricing" class="hover:text-gray-300">Pricing</a></li>
                <li><a href="#resources" class="hover:text-gray-300">Resources</a></li>
                <li><a href="#contact" class="hover:text-gray-300">Contact</a></li>
                <li><a href="#register-writer" class="hover:text-gray-300">Register as a Writer</a></li>
            </ul>
            <a href="#" class="bg-blue-600 px-4 py-2 rounded-md hover:bg-blue-700">Get Started</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="bg-blue-900 text-white py-20 text-center">
        <div class="container mx-auto">
            <h1 class="text-4xl font-bold mb-4">Your Academic Success Starts Here</h1>
            <p class="text-lg mb-8">Professional writing, editing, and proofreading services tailored to your needs.</p>
            <a href="#services" class="bg-blue-600 px-6 py-3 rounded-md text-white hover:bg-blue-700">Explore Services</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 bg-gray-100">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-8">Our Services</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-6 shadow-lg rounded-lg">
                    <h3 class="text-xl font-semibold mb-4">Academic Writing</h3>
                    <p class="mb-4">Essays, research papers, dissertations, and more crafted by experts.</p>
                    <a href="#" class="text-blue-600 hover:underline">Learn More</a>
                </div>
                <div class="bg-white p-6 shadow-lg rounded-lg">
                    <h3 class="text-xl font-semibold mb-4">Editing & Proofreading</h3>
                    <p class="mb-4">Polish your work with expert grammar and style improvements.</p>
                    <a href="#" class="text-blue-600 hover:underline">Learn More</a>
                </div>
                <div class="bg-white p-6 shadow-lg rounded-lg">
                    <h3 class="text-xl font-semibold mb-4">Formatting Services</h3>
                    <p class="mb-4">Ensure perfect citations and adherence to academic styles.</p>
                    <a href="#" class="text-blue-600 hover:underline">Learn More</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="py-16 bg-blue-50">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-8">Affordable Pricing</h2>
            <p class="mb-8">Use our pricing calculator to get an instant quote based on your project.</p>
            <a href="#" class="bg-blue-600 px-6 py-3 rounded-md text-white hover:bg-blue-700">Try the Calculator</a>
        </div>
    </section>

    <!-- Resources Section -->
    <section id="resources" class="py-16 bg-gray-100">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-8">Resources</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-6 shadow-lg rounded-lg">
                    <h3 class="text-xl font-semibold mb-4">Citation Guides</h3>
                    <p class="mb-4">Master APA, MLA, and Chicago styles with our detailed guides.</p>
                    <a href="#" class="text-blue-600 hover:underline">Access Now</a>
                </div>
                <div class="bg-white p-6 shadow-lg rounded-lg">
                    <h3 class="text-xl font-semibold mb-4">Writing Tips</h3>
                    <p class="mb-4">Improve your academic writing with expert advice and tricks.</p>
                    <a href="#" class="text-blue-600 hover:underline">Read More</a>
                </div>
                <div class="bg-white p-6 shadow-lg rounded-lg">
                    <h3 class="text-xl font-semibold mb-4">Templates</h3>
                    <p class="mb-4">Download free templates for essays, reports, and theses.</p>
                    <a href="#" class="text-blue-600 hover:underline">Download</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-blue-900 text-white">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-8">Contact Us</h2>
            <p class="mb-8">Have questions? Reach out to our support team 24/7.</p>
            <form class="max-w-lg mx-auto">
                <div class="mb-4">
                    <input type="text" placeholder="Your Name" class="w-full p-3 rounded-md">
                </div>
                <div class="mb-4">
                    <input type="email" placeholder="Your Email" class="w-full p-3 rounded-md">
                </div>
                <div class="mb-4">
                    <textarea placeholder="Your Message" class="w-full p-3 rounded-md"></textarea>
                </div>
                <button type="submit" class="bg-blue-600 px-6 py-3 rounded-md hover:bg-blue-700">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Register as a Writer Section -->
    <section id="register-writer" class="py-16 bg-white">
        <div class="container mx-auto max-w-lg">
            <h1 class="text-3xl font-bold mb-8 text-center">Register as a Writer</h1>
            <form class="space-y-6">
                <div>
                    <label for="first-name" class="block text-sm font-medium">First Name</label>
                    <input type="text" id="first-name" class="w-full p-3 border border-gray-300 rounded-md" placeholder="Your First Name">
                </div>
                <div>
                    <label for="last-name" class="block text-sm font-medium">Last Name</label>
                    <input type="text" id="last-name" class="w-full p-3 border border-gray-300 rounded-md" placeholder="Your Last Name">
                </div>
                <div>
                    <label for="email" class="block text-sm font-medium">Email Address</label>
                    <input type="email" id="email" class="w-full p-3 border border-gray-300 rounded-md" placeholder="Your Email">
                </div>
                <div>
                    <label for="country" class="block text-sm font-medium">Country</label>
                    <input type="text" id="country" class="w-full p-3 border border-gray-300 rounded-md" placeholder="Your Country">
                </div>
                <div>
                    <label for="phone-number" class="block text-sm font-medium">Phone Number</label>
                    <input type="tel" id="phone-number" class="w-full p-3 border border-gray-300 rounded-md" placeholder="Your Phone Number">
                </div>
                <div>
                    <label for="verification-code" class="block text-sm font-medium">Verification Code</label>
                    <input type="text" id="verification-code" class="w-full p-3 border border-gray-300 rounded-md" placeholder="Enter Verification Code">
                </div>
                <div>
                    <label for="grammar-test" class="block text-sm font-medium">Grammar Test</label>
                    <p class="text-sm text-gray-600">Complete the grammar test below. You have 15 minutes.</p>
                    <textarea id="grammar-test" class="w-full p-3 border border-gray-300 rounded-md" rows="10" placeholder="Please answer the questions here..."></textarea>
                    <p class="text-sm text-red-600">Time remaining: <span id="timer">15:00</span></p>
                    <script>
                        // Timer script for 15-minute countdown
                        let timerElement = document.getElementById('timer');
                        let time = 15 * 60;

                        function updateTimer() {
                            const minutes = Math.floor(time / 60);
                            const seconds = time % 60;
                            timerElement.textContent = `${minutes}:${seconds.toString().padStart(2, '0')}`;
                            if (time > 0) {
                                time--;
                            } else {
                                alert('Time is up! Please submit your answers.');
                            }
                        }

                        setInterval(updateTimer, 1000);
                    </script>
                </div>
                <button type="submit" class="bg-blue-600 px-6 py-3 rounded-md hover:bg-blue-700 w-full">Submit</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-6">
        <div class="container mx-auto text-center">
            <p>&copy; 2024 AcademicWritePro. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
