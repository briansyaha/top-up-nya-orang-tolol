# top-up-nya-orang-tolol<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GameTopUpID - Top Up Game Termurah</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        :root {
            --primary: #4f46e5;
            --dark: #1e293b;
            --light: #f8fafc;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f1f5f9;
            color: var(--dark);
        }
        
        .game-card {
            transition: all 0.3s ease;
            transform: translateY(0);
        }
        
        .game-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        
        .nav-item {
            position: relative;
        }
        
        .nav-item::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: 0;
            left: 0;
            background-color: var(--primary);
            transition: width 0.3s ease;
        }
        
        .nav-item:hover::after {
            width: 100%;
        }
        
        .pulse {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.05);
            }
            100% {
                transform: scale(1);
            }
        }
        
        @media (max-width: 768px) {
            .game-list {
                grid-template-columns: repeat(2, 1fr);
            }
        }
        
        @media (max-width: 480px) {
            .game-list {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header/Navbar -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <img src="https://placehold.co/40x40" alt="Logo GameTopUpID berupa ilustrasi game controller dengan gradien ungu" class="w-10 h-10">
                <h1 class="text-xl font-bold text-indigo-600">GameTopUpID</h1>
            </div>
            
            <nav class="hidden md:flex space-x-6">
                <a href="#" class="nav-item font-medium text-slate-700 hover:text-indigo-600">Beranda</a>
                <a href="#games" class="nav-item font-medium text-slate-700 hover:text-indigo-600">Game</a>
                <a href="#promo" class="nav-item font-medium text-slate-700 hover:text-indigo-600">Promo</a>
                <a href="#testimoni" class="nav-item font-medium text-slate-700 hover:text-indigo-600">Testimoni</a>
                <a href="#faq" class="nav-item font-medium text-slate-700 hover:text-indigo-600">FAQ</a>
            </nav>
            
            <div class="flex items-center space-x-4">
                <button class="md:hidden text-slate-700">
                    <i class="fas fa-bars text-xl"></i>
                </button>
                <button class="hidden md:flex items-center space-x-2 bg-indigo-600 text-white px-4 py-2 rounded-full hover:bg-indigo-700 transition">
                    <i class="fas fa-user"></i>
                    <span>Masuk</span>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative bg-gradient-to-r from-indigo-500 to-purple-600 text-white py-16 md:py-24">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-8 md:mb-0">
                <h2 class="text-3xl md:text-5xl font-bold mb-4">Top Up Game<br><span class="text-amber-300">Murah & Cepat</span></h2>
                <p class="text-lg mb-6 opacity-90">Dapatkan diamond, V-Bucks, dan mata uang game lainnya dengan harga termurah dan proses instan!</p>
                <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-4">
                    <button class="bg-amber-400 hover:bg-amber-500 text-slate-900 font-bold py-3 px-6 rounded-full transition flex items-center justify-center">
                        <span>Top Up Sekarang</span>
                        <i class="fas fa-arrow-right ml-2"></i>
                    </button>
                    <button class="border border-white hover:bg-white hover:text-indigo-600 font-bold py-3 px-6 rounded-full transition flex items-center justify-center">
                        <span>Lihat Promo</span>
                    </button>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <img src="https://placehold.co/600x400" alt="Ilustrasi karakter game sedang melakukan top up di ponsel dengan latar belakang efek digital" class="rounded-lg shadow-xl pulse max-w-full h-auto">
            </div>
        </div>
    </section>

    <!-- Game List Section -->
    <section id="games" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">Top Up Game Populer</h2>
                <p class="text-slate-600 max-w-2xl mx-auto">Pilih game favorit Anda untuk melakukan top up dengan harga spesial</p>
            </div>
            
            <div class="game-list grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                <!-- Game Card 1 -->
                <div class="game-card bg-white rounded-xl overflow-hidden shadow-md cursor-pointer">
                    <div class="relative pt-[70%]">
                        <img src="https://placehold.co/300x300" alt="Mobile Legends Bang Bang - Logo game dengan karakter Alucard" class="absolute top-0 left-0 w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-lg mb-2">Mobile Legends</h3>
                        <div class="flex flex-wrap gap-2">
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">Diamond</button>
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">Starlight</button>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 2 -->
                <div class="game-card bg-white rounded-xl overflow-hidden shadow-md cursor-pointer">
                    <div class="relative pt-[70%]">
                        <img src="https://placehold.co/300x300" alt="Free Fire - Logo game with karakter Chrono" class="absolute top-0 left-0 w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-lg mb-2">Free Fire</h3>
                        <div class="flex flex-wrap gap-2">
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">Diamond</button>
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">Elite Pass</button>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 3 -->
                <div class="game-card bg-white rounded-xl overflow-hidden shadow-md cursor-pointer">
                    <div class="relative pt-[70%]">
                        <img src="https://placehold.co/300x300" alt="PUBG Mobile - Logo game dengan karakter panah target" class="absolute top-0 left-0 w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-lg mb-2">PUBG Mobile</h3>
                        <div class="flex flex-wrap gap-2">
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">UC</button>
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">RP</button>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 4 -->
                <div class="game-card bg-white rounded-xl overflow-hidden shadow-md cursor-pointer">
                    <div class="relative pt-[70%]">
                        <img src="https://placehold.co/300x300" alt="Genshin Impact - Logo game dengan karakter Paimon" class="absolute top-0 left-0 w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-lg mb-2">Genshin Impact</h3>
                        <div class="flex flex-wrap gap-2">
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">Genesis Crystal</button>
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">Welkin Moon</button>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 5 -->
                <div class="game-card bg-white rounded-xl overflow-hidden shadow-md cursor-pointer">
                    <div class="relative pt-[70%]">
                        <img src="https://placehold.co/300x300" alt="Valorant - Logo game V dengan ornamen api" class="absolute top-0 left-0 w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-lg mb-2">Valorant</h3>
                        <div class="flex flex-wrap gap-2">
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">VP</button>
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">Skin</button>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 6 -->
                <div class="game-card bg-white rounded-xl overflow-hidden shadow-md cursor-pointer">
                    <div class="relative pt-[70%]">
                        <img src="https://placehold.co/300x300" alt="Call of Duty Mobile - Logo game dengan ikon sniper" class="absolute top-0 left-0 w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-lg mb-2">COD Mobile</h3>
                        <div class="flex flex-wrap gap-2">
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">CP</button>
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">Battle Pass</button>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 7 -->
                <div class="game-card bg-white rounded-xl overflow-hidden shadow-md cursor-pointer">
                    <div class="relative pt-[70%]">
                        <img src="https://placehold.co/300x300" alt="Fortnite - Logo game dengan shield dan bendera" class="absolute top-0 left-0 w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-lg mb-2">Fortnite</h3>
                        <div class="flex flex-wrap gap-2">
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">V-Bucks</button>
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">Skin Bundle</button>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 8 -->
                <div class="game-card bg-white rounded-xl overflow-hidden shadow-md cursor-pointer">
                    <div class="relative pt-[70%]">
                        <img src="https://placehold.co/300x300" alt="Apex Legends Mobile - Logo game dengan karakter apex predator" class="absolute top-0 left-0 w-full h-full object-cover">
                    </div>
                    <div class="p-4">
                        <h3 class="font-bold text-lg mb-2">Apex Legends</h3>
                        <div class="flex flex-wrap gap-2">
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">Apex Coins</button>
                            <button class="text-xs bg-slate-100 hover:bg-indigo-100 text-indigo-600 px-3 py-1 rounded-full">Legend Tokens</button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-10">
                <button class="border border-indigo-600 text-indigo-600 hover:bg-indigo-600 hover:text-white font-medium py-3 px-6 rounded-full transition">
                    Lihat Semua Game
                </button>
            </div>
        </div>
    </section>

    <!-- Promo Section -->
    <section id="promo" class="py-16 bg-slate-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">Promo Spesial</h2>
                <p class="text-slate-600 max-w-2xl mx-auto">Diskon dan bonus menarik untuk top up game Anda</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Promo Card 1 -->
                <div class="bg-white rounded-xl overflow-hidden shadow-md">
                    <div class="relative pt-[50%]">
                        <img src="https://placehold.co/600x400" alt="Promo Flash Sale dengan desain neon dan jam berjalan" class="absolute top-0 left-0 w-full h-full object-cover">
                        <div class="absolute top-4 right-4 bg-amber-400 text-slate-900 font-bold px-3 py-1 rounded-full text-xs">
                            FLASH SALE
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-2">Diskon 20% Diamond MLBB</h3>
                        <p class="text-slate-600 mb-4">Hanya hari ini, dapatkan diamond Mobile Legends dengan harga spesial!</p>
                        <div class="flex justify-between items-center">
                            <span class="text-sm text-slate-500">Berakhir dalam: 03:24:15</span>
                            <button class="bg-indigo-600 hover:bg-indigo-700 text-white px-4 py-2 rounded-full text-sm font-medium">Klaim Sekarang</button>
                        </div>
                    </div>
                </div>
                
                <!-- Promo Card 2 -->
                <div class="bg-white rounded-xl overflow-hidden shadow-md">
                    <div class="relative pt-[50%]">
                        <img src="https://placehold.co/600x400" alt="Bundling voucher game dengan ilustrasi kotak hadiah" class="absolute top-0 left-0 w-full h-full object-cover">
                        <div class="absolute top-4 right-4 bg-purple-600 text-white font-bold px-3 py-1 rounded-full text-xs">
                            BUNDLE
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-2">Bonus Double Diamond</h3>
                        <p class="text-slate-600 mb-4">Top Up minimal Rp100.000 dan dapatkan bonus diamond tambahan 100%!</p>
                        <div class="flex justify-between items-center">
                            <span class="text-sm text-slate-500">Sampai 31 Desember</span>
                            <button class="bg-indigo-600 hover:bg-indigo-700 text-white px-4 py-2 rounded-full text-sm font-medium">Klaim Sekarang</button>
                        </div>
                    </div>
                </div>
                
                <!-- Promo Card 3 -->
                <div class="bg-white rounded-xl overflow-hidden shadow-md">
                    <div class="relative pt-[50%]">
                        <img src="https://placehold.co/600x400" alt="Giveaway mingguan dengan ilustrasi piala emas" class="absolute top-0 left-0 w-full h-full object-cover">
                        <div class="absolute top-4 right-4 bg-green-500 text-white font-bold px-3 py-1 rounded-full text-xs">
                            GIVEAWAY
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-2">Giveaway Mingguan</h3>
                        <p class="text-slate-600 mb-4">Setiap minggu kita memberikan hadiah diamond senilai Rp500.000 untuk 5 pemenang!</p>
                        <div class="flex justify-between items-center">
                            <span class="text-sm text-slate-500">Selama bulan Juni</span>
                            <button class="bg-indigo-600 hover:bg-indigo-700 text-white px-4 py-2 rounded-full text-sm font-medium">Ikut Sekarang</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How To Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">Cara Top Up Game</h2>
                <p class="text-slate-600 max-w-2xl mx-auto">Hanya dalam 3 langkah mudah, diamond akan langsung masuk ke akun Anda</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Step 1 -->
                <div class="text-center">
                    <div class="flex justify-center mb-6">
                        <div class="flex items-center justify-center w-16 h-16 rounded-full bg-indigo-100 text-indigo-600 text-2xl font-bold">
                            1
                        </div>
                    </div>
                    <h3 class="font-bold text-xl mb-3">Pilih Game & Produk</h3>
                    <p class="text-slate-600">Temukan game favorit Anda dan pilih produk yang ingin dibeli (diamond, voucher, dll)</p>
                </div>
                
                <!-- Step 2 -->
                <div class="text-center">
                    <div class="flex justify-center mb-6">
                        <div class="flex items-center justify-center w-16 h-16 rounded-full bg-indigo-100 text-indigo-600 text-2xl font-bold">
                            2
                        </div>
                    </div>
                    <h3 class="font-bold text-xl mb-3">Masukkan ID Game</h3>
                    <p class="text-slate-600">Masukkan User ID atau nickname Anda di game yang dituju</p>
                </div>
                
                <!-- Step 3 -->
                <div class="text-center">
                    <div class="flex justify-center mb-6">
                        <div class="flex items-center justify-center w-16 h-16 rounded-full bg-indigo-100 text-indigo-600 text-2xl font-bold">
                            3
                        </div>
                    </div>
                    <h3 class="font-bold text-xl mb-3">Bayar & Selesai</h3>
                    <p class="text-slate-600">Pilih metode pembayaran favorit dan selesaikan pembayaran</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonial Section -->
    <section id="testimoni" class="py-16 bg-slate-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">Testimoni Pelanggan</h2>
                <p class="text-slate-600 max-w-2xl mx-auto">Apa kata mereka tentang pengalaman top up di GameTopUpID</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <img src="https://placehold.co/40x40" alt="Foto profil pelanggan bernama Rudi" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Rudi</h4>
                            <div class="flex text-amber-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-slate-600">"Top up diamond ML cepat banget masuknya, cuma 1 menit langsung bisa dipakai. Harganya juga lebih murah dibanding tempat lain."</p>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <img src="https://placehold.co/40x40" alt="Foto profil pelanggan bernama Ani" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Ani</h4>
                            <div class="flex text-amber-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-slate-600">"CS-nya ramah dan membantu banget pas aku salah masukin ID. Proses refund cepat dan bisa top up ulang tanpa masalah. Recomended!"</p>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <img src="https://placehold.co/40x40" alt="Foto profil pelanggan bernama Dika" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold">Dika</h4>
                            <div class="flex text-amber-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-slate-600">"Gue sering top up Valorant disini karena ada promo-promo keren. Terakhir bisa dapet bonus 30% VP karena pakai metode bayar tertentu."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold mb-4">Pertanyaan Umum</h2>
                <p class="text-slate-600 max-w-2xl mx-auto">Temukan jawaban untuk pertanyaan yang sering diajukan</p>
            </div>
            
            <div class="max-w-3xl mx-auto">
                <!-- FAQ Item 1 -->
                <div class="mb-4 border-b border-slate-200 pb-4">
                    <button class="faq-btn flex justify-between items-center w-full text-left font-medium text-lg hover:text-indigo-600 transition">
                        <span>Berapa lama waktu proses top up?</span>
                        <i class="fas fa-plus"></i>
                    </button>
                    <div class="faq-content hidden mt-2 text-slate-600">
                        Proses top up di GameTopUpID biasanya selesai dalam waktu 1-5 menit setelah pembayaran dikonfirmasi. Namun, waktu bisa berbeda tergantung kondisi server game dan jumlah transaksi yang sedang berlangsung.
                    </div>
                </div>
                
                <!-- FAQ Item 2 -->
                <div class="mb-4 border-b border-slate-200 pb-4">
                    <button class="faq-btn flex justify-between items-center w-full text-left font-medium text-lg hover:text-indigo-600 transition">
                        <span>Apakah ada biaya tambahan?</span>
                        <i class="fas fa-plus"></i>
                    </button>
                    <div class="faq-content hidden mt-2 text-slate-600">
                        Tidak ada biaya tambahan. Harga yang tertera sudah final. Kami hanya menambahkan biaya pajak jika dibebankan oleh penyedia game.
                    </div>
                </div>
                
                <!-- FAQ Item 3 -->
                <div class="mb-4 border-b border-slate-200 pb-4">
                    <button class="faq-btn flex justify-between items-center w-full text-left font-medium text-lg hover:text-indigo-600 transition">
                        <span>Bagaimana jika diamond tidak masuk?</span>
                        <i class="fas fa-plus"></i>
                    </button>
                    <div class="faq-content hidden mt-2 text-slate-600">
                        Jika diamond belum masuk dalam 10 menit, silakan hubungi Customer Service kami melalui live chat dengan menyertakan bukti pembayaran. Tim kami akan segera memproses keluhan Anda.
                    </div>
                </div>
                
                <!-- FAQ Item 4 -->
                <div class="mb-4 border-b border-slate-200 pb-4">
                    <button class="faq-btn flex justify-between items-center w-full text-left font-medium text-lg hover:text-indigo-600 transition">
                        <span>Metode pembayaran apa saja yang tersedia?</span>
                        <i class="fas fa-plus"></i>
                    </button>
                    <div class="faq-content hidden mt-2 text-slate-600">
                        Kami menyediakan berbagai metode pembayaran seperti Transfer Bank (BCA, BRI, Mandiri, BNI), E-Wallet (OVO, Dana, GoPay, Shopeepay), QRIS, Alfamart/Indomaret, dan pulsa (untuk operator tertentu).
                    </div>
                </div>
                
                <!-- FAQ Item 5 -->
                <div class="mb-4 border-b border-slate-200 pb-4">
                    <button class="faq-btn flex justify-between items-center w-full text-left font-medium text-lg hover:text-indigo-600 transition">
                        <span>Apakah ada batasan jumlah top up per hari?</span>
                        <i class="fas fa-plus"></i>
                    </button>
                    <div class="faq-content hidden mt-2 text-slate-600">
                        Batasan top up tergantung dari kebijakan masing-masing game. Untuk game seperti Mobile Legends umumnya tidak ada batasan, namun untuk game seperti PUBG Mobile ada batas harian untuk menghindari trading ilegal.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-16 bg-indigo-600 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-6">Siap Untuk Top Up Game Favorit Anda?</h2>
            <p class="text-lg mb-8 max-w-2xl mx-auto opacity-90">Gabung dengan ribuan gamers puas lainnya dan nikmati pengalaman top up terbaik</p>
            <div class="flex flex-col sm:flex-row justify-center space-y-3 sm:space-y-0 sm:space-x-4">
                <button class="bg-amber-400 hover:bg-amber-500 text-slate-900 font-bold py-3 px-8 rounded-full transition">
                    Top Up Sekarang
                </button>
                <button class="border border-white hover:bg-white hover:text-indigo-600 font-bold py-3 px-8 rounded-full transition">
                    Hubungi Kami
                </button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-900 text-slate-400 pt-12 pb-6">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-4 gap-8 mb-8">
                <!-- Column 1 -->
                <div>
                    <div class="flex items-center mb-4">
                        <img src="https://placehold.co/40x40" alt="Logo GameTopUpID versi putih" class="w-10 h-10">
                        <h3 class="text-white ml-2 text-xl font-bold">GameTopUpID</h3>
                    </div>
                    <p class="mb-4">Platform top up game termurah dan tercepat di Indonesia dengan proses instan.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-white hover:text-indigo-400"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-white hover:text-indigo-400"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-white hover:text-indigo-400"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-white hover:text-indigo-400"><i class="fab fa-discord"></i></a>
                    </div>
                </div>
                
                <!-- Column 2 -->
                <div>
                    <h4 class="text-white font-bold mb-4">Layanan</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:text-white transition">Top Up Game</a></li>
                        <li><a href="#" class="hover:text-white transition">Promo Spesial</a></li>
                        <li><a href="#" class="hover:text-white transition">Kelola Akun</a></li>
                        <li><a href="#" class="hover:text-white transition">Voucher Game</a></li>
                        <li><a href="#" class="hover:text-white transition">Skin Trading</a></li>
                    </ul>
                </div>
                
                <!-- Column 3 -->
                <div>
                    <h4 class="text-white font-bold mb-4">Perusahaan</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:text-white transition">Tentang Kami</a></li>
                        <li><a href="#" class="hover:text-white transition">Karir</a></li>
                        <li><a href="#" class="hover:text-white transition">Blog</a></li>
                        <li><a href="#" class="hover:text-white transition">Partner</a></li>
                        <li><a href="#" class="hover:text-white transition">Kebijakan Privasi</a></li>
                    </ul>
                </div>
                
                <!-- Column 4 -->
                <div>
                    <h4 class="text-white font-bold mb-4">Hubungi Kami</h4>
                    <ul class="space-y-2">
                        <li class="flex items-center">
                            <i class="fas fa-envelope mr-2"></i>
                            <span>cs@gametopupid.com</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-phone-alt mr-2"></i>
                            <span>+62 123 4567 8910</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-map-marker-alt mr-2"></i>
                            <span>Jakarta Selatan, Indonesia</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-slate-800 pt-6 text-center">
                <p>&copy; 2023 GameTopUpID. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Mobile Menu -->
    <div id="mobile-menu" class="fixed inset-0 bg-black bg-opacity-75 z-50 hidden">
        <div class="bg-white w-4/5 h-full ml-auto p-6">
            <div class="flex justify-between items-center mb-8">
                <h2 class="text-xl font-bold text-indigo-600">GameTopUpID</h2>
                <button id="close-menu" class="text-slate-700">
                    <i class="fas fa-times text-xl"></i>
                </button>
            </div>
            
            <nav class="space-y-4">
                <a href="#" class="block font-medium text-slate-700 hover:text-indigo-600">Beranda</a>
                <a href="#games" class="block font-medium text-slate-700 hover:text-indigo-600">Game</a>
                <a href="#promo" class="block font-medium text-slate-700 hover:text-indigo-600">Promo</a>
                <a href="#testimoni" class="block font-medium text-slate-700 hover:text-indigo-600">Testimoni</a>
                <a href="#faq" class="block font-medium text-slate-700 hover:text-indigo-600">FAQ</a>
                
                <button class="w-full bg-indigo-600 text-white px-4 py-3 rounded-lg font-bold mt-8 flex items-center justify-center space-x-2">
                    <i class="fas fa-user"></i>
                    <span>Masuk</span>
                </button>
            </nav>
        </div>
    </div>

    <script>
        // Mobile Menu Toggle
        document.querySelector('header button').addEventListener('click', function() {
            document.getElementById('mobile-menu').classList.remove('hidden');
        });
        
        document.getElementById('close-menu').addEventListener('click', function() {
            document.getElementById('mobile-menu').classList.add('hidden');
        });
        
        // FAQ Accordion
        const faqBtns = document.querySelectorAll('.faq-btn');
        faqBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                const content = btn.nextElementSibling;
                const icon = btn.querySelector('i');
                
                // Toggle content
                content.classList.toggle('hidden');
                
                // Toggle icon
                if (content.classList.contains('hidden')) {
                    icon.classList.remove('fa-minus');
                    icon.classList.add('fa-plus');
                } else {
                    icon.classList.remove('fa-plus');
                    icon.classList.add('fa-minus');
                }
            });
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.getElementById('mobile-menu').classList.add('hidden');
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
