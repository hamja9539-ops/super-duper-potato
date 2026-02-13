<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kadam Network | Global Ad Network</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        .hero-gradient { background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%); }
    </style>
</head>
<body class="bg-gray-50">

    <!-- Navbar -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-blue-600">Kadam <span class="text-gray-800">Network</span></a>
            <div class="hidden md:flex space-x-8 text-gray-600 font-medium">
                <a href="#home" class="hover:text-blue-600 transition">হোম</a>
                <a href="#services" class="hover:text-blue-600 transition">সার্ভিস</a>
                <a href="#advertisers" class="hover:text-blue-600 transition">অ্যাডভার্টাইজার</a>
                <a href="#publishers" class="hover:text-blue-600 transition">পাবলিশার</a>
                <a href="#contact" class="hover:text-blue-600 transition">যোগাযোগ</a>
            </div>
            <a href="#" class="bg-blue-600 text-white px-6 py-2 rounded-full font-bold hover:bg-blue-700 transition">লগইন</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-gradient text-white py-20 px-6">
        <div class="container mx-auto flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-6xl font-bold leading-tight mb-6">আপনার ব্যবসার সঠিক ট্রাফিক নিশ্চিত করুন</h1>
                <p class="text-lg mb-8 text-blue-100">কদম নেটওয়ার্কের মাধ্যমে সারাবিশ্বের রিয়েল অডিয়েন্সের কাছে পৌঁছে যান। আমরা অফার করি প্রিমিয়াম অ্যাড ফরম্যাট এবং স্মার্ট টার্গেটিং।</p>
                <div class="flex space-x-4">
                    <button class="bg-white text-blue-600 px-8 py-3 rounded-lg font-bold shadow-lg">শুরু করুন</button>
                    <button class="border border-white text-white px-8 py-3 rounded-lg font-bold hover:bg-white hover:text-blue-600 transition">আরও জানুন</button>
                </div>
            </div>
            <div class="md:w-1/2">
                <img src="https://via.placeholder.com/600x400/ffffff/3b82f6?text=Ad+Network+Interface" alt="Analytics" class="rounded-xl shadow-2xl">
            </div>
        </div>
    </section>

    <!-- Stats -->
    <section class="py-12 bg-white border-b">
        <div class="container mx-auto px-6 grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
            <div>
                <h3 class="text-3xl font-bold text-blue-600">৪০B+</h3>
                <p class="text-gray-500">প্রতিদিন ইমপ্রেশন</p>
            </div>
            <div>
                <h3 class="text-3xl font-bold text-blue-600">১৯৫+</h3>
                <p class="text-gray-500">দেশ কাভারেজ</p>
            </div>
            <div>
                <h3 class="text-3xl font-bold text-blue-600">৮০K+</h3>
                <p class="text-gray-500">অ্যাডভার্টাইজার</p>
            </div>
            <div>
                <h3 class="text-3xl font-bold text-blue-600">২৪/৭</h3>
                <p class="text-gray-500">সাপোর্ট</p>
            </div>
        </div>
    </section>

    <!-- Services / Formats -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-16 text-gray-800">আমাদের অ্যাড ফরম্যাটসমূহ</h2>
            <div class="grid md:grid-cols-3 gap-10">
                <div class="bg-white p-8 rounded-xl shadow-sm hover:shadow-md transition">
                    <i class="fas fa-bell text-4xl text-blue-600 mb-6"></i>
                    <h4 class="text-xl font-bold mb-4">পুশ নোটিফিকেশন</h4>
                    <p class="text-gray-600 text-sm">সরাসরি ইউজারের ডিভাইসে মেসেজ পাঠিয়ে কনভার্সন বৃদ্ধি করুন।</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-sm hover:shadow-md transition">
                    <i class="fas fa-image text-4xl text-blue-600 mb-6"></i>
                    <h4 class="text-xl font-bold mb-4">নেটিভ অ্যাডস</h4>
                    <p class="text-gray-600 text-sm">ওয়েবসাইটের কন্টেন্টের সাথে সামঞ্জস্য রেখে ন্যাচারাল বিজ্ঞাপন।</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-sm hover:shadow-md transition">
                    <i class="fas fa-mouse-pointer text-4xl text-blue-600 mb-6"></i>
                    <h4 class="text-xl font-bold mb-4">পপআন্ডার (Popunder)</h4>
                    <p class="text-gray-600 text-sm">হাই-ভলিউম ট্রাফিক পাওয়ার সবচেয়ে জনপ্রিয় এবং কার্যকরী মাধ্যম।</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="container mx-auto px-6 max-w-4xl">
            <div class="bg-blue-600 rounded-2xl p-12 text-white text-center">
                <h2 class="text-3xl font-bold mb-6">আজই কদম নেটওয়ার্কে যোগ দিন</h2>
                <p class="mb-10 text-blue-100">আপনার ইনকাম অথবা সেলস বাড়ানোর এখনই সময়। আমাদের সাপোর্ট টিম আপনাকে সাহায্য করতে প্রস্তুত।</p>
                <form class="flex flex-col md:flex-row space-y-4 md:space-y-0 md:space-x-4 justify-center">
                    <input type="email" placeholder="আপনার ইমেইল দিন" class="px-6 py-3 rounded-lg text-gray-800 focus:outline-none w-full md:w-80">
                    <button class="bg-yellow-400 text-blue-900 px-8 py-3 rounded-lg font-bold hover:bg-yellow-300 transition">রেজিস্ট্রেশন করুন</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-12 px-6">
        <div class="container mx-auto grid md:grid-cols-4 gap-12">
            <div class="col-span-1 md:col-span-1">
                <a href="#" class="text-2xl font-bold text-white mb-6 block">Kadam Network</a>
                <p class="text-sm">একটি গ্লোবাল ডিজিটাল অ্যাডভার্টাইজিং প্ল্যাটফর্ম যা পাবলিশার এবং অ্যাডভার্টাইজারদের মেলবন্ধন ঘটায়।</p>
            </div>
            <div>
                <h5 class="text-white font-bold mb-4">লিঙ্কস</h5>
                <ul class="space-y-2 text-sm">
                    <li><a href="#" class="hover:text-white">অ্যাডভার্টাইজার</a></li>
                    <li><a href="#" class="hover:text-white">পাবলিশার</a></li>
                    <li><a href="#" class="hover:text-white">অ্যাফিলিয়েট</a></li>
                </ul>
            </div>
            <div>
                <h5 class="text-white font-bold mb-4">কোম্পানি</h5>
                <ul class="space-y-2 text-sm">
                    <li><a href="#" class="hover:text-white">আমাদের সম্পর্কে</a></li>
                    <li><a href="#" class="hover:text-white">ব্লগ</a></li>
                    <li><a href="#" class="hover:text-white">প্রাইভেসি পলিসি</a></li>
                </ul>
            </div>
            <div>
                <h5 class="text-white font-bold mb-4">যোগাযোগ</h5>
                <p class="text-sm">ইমেইল: support@kadam.net</p>
                <div class="flex space-x-4 mt-4">
                    <a href="#" class="text-xl hover:text-white"><i class="fab fa-facebook"></i></a>
                    <a href="#" class="text-xl hover:text-white"><i class="fab fa-linkedin"></i></a>
                    <a href="#" class="text-xl hover:text-white"><i class="fab fa-twitter"></i></a>
                </div>
            </div>
        </div>
        <div class="text-center mt-12 pt-8 border-t border-gray-800 text-sm">
            &copy; 2025 Kadam Network. All rights reserved.
        </div>
    </footer>

</body>
</html>
