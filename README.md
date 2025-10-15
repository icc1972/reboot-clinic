# reboot-clinic
My Personnel HTML Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>B & S Body Reboot Clinic | Medical Weight Loss Chennai</title>
    <link rel="icon" type="image/x-icon" href="/static/favicon.ico">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        teal: {
                            500: '#008080',
                            600: '#006666',
                        },
                        seagreen: {
                            400: '#3CB371',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
        }
        .hero-gradient {
            background: linear-gradient(135deg, rgba(0,128,128,0.9) 0%, rgba(60,179,113,0.8) 100%);
        }
        .hover-scale {
            transition: transform 0.3s ease;
        }
        .hover-scale:hover {
            transform: scale(1.03);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-3">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-4">
                    <i data-feather="activity" class="text-teal-500"></i>
                    <span class="text-xl font-bold text-gray-800">B & S Body Reboot</span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#" class="text-teal-600 font-medium">Home</a>
                    <a href="about.html" class="text-gray-600 hover:text-teal-600">About Us</a>
                    <a href="programs.html" class="text-gray-600 hover:text-teal-600">Our Programs</a>
                    <a href="success.html" class="text-gray-600 hover:text-teal-600">Success Stories</a>
                    <a href="blog.html" class="text-gray-600 hover:text-teal-600">Health Tips</a>
                    <a href="contact.html" class="text-gray-600 hover:text-teal-600">Contact</a>
                </div>
                <button class="md:hidden focus:outline-none">
                    <i data-feather="menu"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-gradient text-white">
        <div class="container mx-auto px-6 py-20 md:py-32">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-5xl font-bold leading-tight mb-4">Lose Weight the Healthy Way</h1>
                    <p class="text-xl mb-8">Supervised by Chennai's Leading Medical Experts</p>
                    <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-4">
                        <a href="appointment.html" class="bg-white text-teal-600 hover:bg-gray-100 px-8 py-3 rounded-full font-bold text-center hover-scale">Book Free Consultation</a>
                        <a href="tel:+919876543210" class="border-2 border-white text-white hover:bg-white hover:text-teal-600 px-8 py-3 rounded-full font-bold text-center hover-scale">
                            <i data-feather="phone" class="inline mr-2"></i>+91 98765 43210
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <img src="http://static.photos/wellness/1024x576/10" alt="Happy patient with doctor" class="rounded-lg shadow-xl max-w-md w-full">
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="bg-white py-16">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="p-6">
                    <div class="text-4xl font-bold text-teal-600 mb-2">1000+</div>
                    <div class="text-gray-600">Patients Transformed</div>
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-teal-600 mb-2">15+</div>
                    <div class="text-gray-600">Years Experience</div>
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-teal-600 mb-2">98%</div>
                    <div class="text-gray-600">Success Rate</div>
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-teal-600 mb-2">100%</div>
                    <div class="text-gray-600">Medical Supervision</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Us -->
    <section class="bg-gray-50 py-16">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">Why Choose Our Medical Weight Loss Program?</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-lg shadow-md hover-scale">
                    <div class="text-teal-600 mb-4">
                        <i data-feather="shield" class="w-12 h-12"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Doctor Supervised</h3>
                    <p class="text-gray-600">Our weight loss plans are designed and monitored by certified medical professionals to ensure safety and effectiveness.</p>
                </div>
                <div class="bg-white p-8 rounded-lg shadow-md hover-scale">
                    <div class="text-teal-600 mb-4">
                        <i data-feather="users" class="w-12 h-12"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Personalized Plans</h3>
                    <p class="text-gray-600">We create customized programs based on your body composition, metabolism, and health conditions.</p>
                </div>
                <div class="bg-white p-8 rounded-lg shadow-md hover-scale">
                    <div class="text-teal-600 mb-4">
                        <i data-feather="trending-up" class="w-12 h-12"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Sustainable Results</h3>
                    <p class="text-gray-600">Our focus is on long-term weight management through lifestyle changes rather than quick fixes.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Programs Preview -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">Our Weight Loss Programs</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="rounded-lg overflow-hidden shadow-lg hover-scale">
                    <img src="http://static.photos/medical/640x360/1" alt="Nutrition Counseling" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">Diet & Nutrition Counseling</h3>
                        <p class="text-gray-600 mb-4">Personalized meal plans crafted by our nutritionists to help you lose weight without deprivation.</p>
                        <a href="programs.html#nutrition" class="text-teal-600 font-medium flex items-center">
                            Learn More <i data-feather="arrow-right" class="ml-2 w-4 h-4"></i>
                        </a>
                    </div>
                </div>
                <div class="rounded-lg overflow-hidden shadow-lg hover-scale">
                    <img src="http://static.photos/technology/640x360/2" alt="Metabolic Testing" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">Metabolic Testing</h3>
                        <p class="text-gray-600 mb-4">Scientific analysis of your metabolism to create the most effective weight loss strategy.</p>
                        <a href="programs.html#metabolic" class="text-teal-600 font-medium flex items-center">
                            Learn More <i data-feather="arrow-right" class="ml-2 w-4 h-4"></i>
                        </a>
                    </div>
                </div>
                <div class="rounded-lg overflow-hidden shadow-lg hover-scale">
                    <img src="http://static.photos/wellness/640x360/3" alt="Body Contouring" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">Non-Surgical Body Contouring</h3>
                        <p class="text-gray-600 mb-4">Advanced treatments to shape and tone problem areas without surgery or downtime.</p>
                        <a href="programs.html#contouring" class="text-teal-600 font-medium flex items-center">
                            Learn More <i data-feather="arrow-right" class="ml-2 w-4 h-4"></i>
                        </a>
                    </div>
                </div>
            </div>
            <div class="text-center mt-12">
                <a href="programs.html" class="bg-teal-600 hover:bg-teal-700 text-white px-8 py-3 rounded-full font-bold inline-block hover-scale">
                    View All Programs
                </a>
            </div>
        </div>
    </section>

    <!-- Testimonial Section -->
    <section class="bg-teal-600 text-white py-16">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">Success Stories</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-teal-500 p-8 rounded-lg">
                    <div class="flex mb-4">
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300"></i>
                    </div>
                    <p class="italic mb-6">"Lost 18 kg in 4 months with the doctor's guidance. The nutrition plan was easy to follow even with my busy schedule."</p>
                    <div class="font-bold">- R.K. (Chennai)</div>
                </div>
                <div class="bg-teal-500 p-8 rounded-lg">
                    <div class="flex mb-4">
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300"></i>
                    </div>
                    <p class="italic mb-6">"After trying many diets, this medical program finally helped me lose weight and keep it off. The metabolic testing was eye-opening!"</p>
                    <div class="font-bold">- S.P. (Chennai)</div>
                </div>
                <div class="bg-teal-500 p-8 rounded-lg">
                    <div class="flex mb-4">
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                        <i data-feather="star" class="text-yellow-300 mr-1"></i>
                    </div>
                    <p class="italic mb-6">"The body contouring treatments helped me get rid of stubborn belly fat after pregnancy. Highly recommend!"</p>
                    <div class="font-bold">- A.M. (Chennai)</div>
                </div>
            </div>
            <div class="text-center mt-12">
                <a href="success.html" class="bg-white hover:bg-gray-100 text-teal-600 px-8 py-3 rounded-full font-bold inline-block hover-scale">
                    View More Success Stories
                </a>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="bg-white py-16">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-6">Ready to Start Your Weight Loss Journey?</h2>
            <p class="text-xl text-gray-600 mb-8 max-w-2xl mx-auto">Our medical team is ready to help you achieve your health goals safely and effectively.</p>
            <div class="flex flex-col sm:flex-row justify-center space-y-3 sm:space-y-0 sm:space-x-4">
                <a href="appointment.html" class="bg-teal-600 hover:bg-teal-700 text-white px-8 py-3 rounded-full font-bold inline-block hover-scale">
                    Book Free Consultation
                </a>
                <a href="tel:+919876543210" class="border-2 border-teal-600 text-teal-600 hover:bg-teal-50 px-8 py-3 rounded-full font-bold inline-block hover-scale">
                    <i data-feather="phone" class="inline mr-2"></i>Call Now
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white pt-12 pb-6">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-4 gap-8 mb-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">B & S Body Reboot</h3>
                    <p class="text-gray-400">Chennai's leading medical weight loss clinic providing doctor-supervised programs for safe and effective results.</p>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="about.html" class="text-gray-400 hover:text-white">About Us</a></li>
                        <li><a href="programs.html" class="text-gray-400 hover:text-white">Our Programs</a></li>
                        <li><a href="success.html" class="text-gray-400 hover:text-white">Success Stories</a></li>
                        <li><a href="blog.html" class="text-gray-400 hover:text-white">Health Tips</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Contact Us</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-center">
                            <i data-feather="map-pin" class="mr-2 w-4 h-4"></i> 
                            <span>123 Health Street, Chennai</span>
                        </li>
                        <li class="flex items-center">
                            <i data-feather="phone" class="mr-2 w-4 h-4"></i> 
                            <span>+91 98765 43210</span>
                        </li>
                        <li class="flex items-center">
                            <i data-feather="mail" class="mr-2 w-4 h-4"></i> 
                            <span>info@bsbodyreboot.com</span>
                        </li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Opening Hours</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li>Monday - Friday: 9AM - 7PM</li>
                        <li>Saturday: 9AM - 2PM</li>
                        <li>Sunday: Closed</li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-700 pt-6 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 mb-4 md:mb-0">© 2023 B & S Body Reboot Clinic. All rights reserved.</p>
                <div class="flex space-x-4">
                    <a href="#" class="text-gray-400 hover:text-white">
                        <i data-feather="facebook" class="w-5 h-5"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white">
                        <i data-feather="instagram" class="w-5 h-5"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white">
                        <i data-feather="twitter" class="w-5 h-5"></i>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        feather.replace();
    </script>
</body>
</html>
