# Gemas-Transport
<!DOCTYPE html>
<html lang="id" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gemas Trans - Travel, Carter & Cargo Kalimantan</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        emerald: {
                            800: '#064e3b',
                            900: '#022c22',
                            950: '#011711',
                        },
                        gold: {
                            400: '#facc15',
                            500: '#eab308',
                            600: '#ca8a04',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #022c22;
            background-image: radial-gradient(circle at 50% 0%, rgba(6, 78, 59, 0.8), rgba(1, 23, 17, 1));
            min-height: 100vh;
            color: #f3f4f6;
        }

        .glass-card {
            background: rgba(6, 78, 59, 0.35);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(250, 204, 21, 0.15);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
        }

        .gold-gradient-text {
            background: linear-gradient(135deg, #fef08a 0%, #facc15 50%, #ca8a04 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .gold-button {
            background: linear-gradient(135deg, #facc15 0%, #eab308 100%);
            color: #011711;
            font-weight: 700;
            transition: all 0.3s ease;
        }

        .gold-button:hover {
            background: linear-gradient(135deg, #fef08a 0%, #facc15 100%);
            box-shadow: 0 0 20px rgba(250, 204, 21, 0.4);
            transform: translateY(-1px);
        }

        .seat-radio:checked + label {
            border-color: #facc15;
            background-color: rgba(250, 204, 21, 0.15);
            color: #facc15;
            box-shadow: 0 0 12px rgba(250, 204, 21, 0.2);
        }
    </style>
</head>
<body class="flex flex-col min-h-screen antialiased selection:bg-gold-500 selection:text-emerald-950">

    <!-- Header Section -->
    <header class="sticky top-0 z-50 glass-card border-b border-gold-500/20 backdrop-blur-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-xl bg-gold-500/20 border border-gold-500/40 flex items-center justify-center text-gold-400">
                    <i class="fa-solid fa-route text-xl"></i>
                </div>
                <div>
                    <h1 class="text-xl font-extrabold tracking-tight text-white flex items-center gap-2">
                        <span>GEMAS TRANS</span>
                        <span class="text-[10px] bg-gold-500/20 text-gold-400 border border-gold-500/30 px-2 py-0.5 rounded-full font-bold uppercase">Kalimantan</span>
                    </h1>
                    <p class="text-[11px] text-gray-300">Bontang • Samarinda • Balikpapan</p>
                </div>
            </div>

            <!-- CS Contact Buttons Header -->
            <div class="hidden md:flex items-center space-x-3">
                <a href="https://wa.me/6281346277328" target="_blank" class="flex items-center space-x-2 bg-emerald-900/60 hover:bg-emerald-800/80 border border-gold-500/30 px-3 py-2 rounded-lg text-xs transition-all">
                    <i class="fa-brands fa-whatsapp text-emerald-400 text-base"></i>
                    <span>CS 1: 0813-4627-7328</span>
                </a>
                <a href="https://wa.me/6285156436097" target="_blank" class="flex items-center space-x-2 bg-emerald-900/60 hover:bg-emerald-800/80 border border-gold-500/30 px-3 py-2 rounded-lg text-xs transition-all">
                    <i class="fa-brands fa-whatsapp text-emerald-400 text-base"></i>
                    <span>CS 2: 0851-5643-6097</span>
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section with Silhouettes -->
    <section class="relative overflow-hidden py-10 sm:py-14 px-4">
        <div class="max-w-7xl mx-auto relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-7 space-y-5 text-center lg:text-left">
                    <div class="inline-flex items-center space-x-2 px-3 py-1.5 rounded-full bg-gold-500/10 border border-gold-500/30 text-gold-400 text-xs font-semibold uppercase tracking-wider">
                        <i class="fa-solid fa-shield-halved"></i>
                        <span>Layanan Perjalanan Eksekutif & Terpercaya</span>
                    </div>
                    <h2 class="text-3xl sm:text-5xl font-extrabold tracking-tight leading-tight">
                        Pilihan Utama Rute <br>
                        <span class="gold-gradient-text">Bontang — Samarinda — Balikpapan</span>
                    </h2>
                    <p class="text-gray-300 text-sm sm:text-base max-w-2xl leading-relaxed">
                        Nikmati perjalanan aman dan nyaman bersama armada **Innova Reborn** & **Innova Zenix**. Melayani Travel Reguler (Maksimal 4 Seat), Carter Privat 24 Jam (Tol & Non-Tol), serta Pengiriman Cargo Ekspres.
                    </p>

                    <!-- Badges -->
                    <div class="pt-2 flex flex-wrap justify-center lg:justify-start gap-3 text-xs font-medium text-emerald-200">
                        <span class="flex items-center space-x-2 bg-emerald-900/50 px-3 py-2 rounded-lg border border-emerald-700/50">
                            <i class="fa-solid fa-users text-gold-400"></i>
                            <span>Maksimal 4 Seat Reguler</span>
                        </span>
                        <span class="flex items-center space-x-2 bg-emerald-900/50 px-3 py-2 rounded-lg border border-emerald-700/50">
                            <i class="fa-solid fa-clock text-gold-400"></i>
                            <span>Carter Jam Bebas 24 Jam</span>
                        </span>
                        <span class="flex items-center space-x-2 bg-emerald-900/50 px-3 py-2 rounded-lg border border-emerald-700/50">
                            <i class="fa-solid fa-location-dot text-gold-400"></i>
                            <span>Shareloc GPS Google Maps</span>
                        </span>
                    </div>
                </div>

                <!-- Kalimantan Vector Visual -->
                <div class="lg:col-span-5 relative flex justify-center">
                    <div class="w-full max-w-md glass-card rounded-2xl p-6 relative overflow-hidden text-center border border-gold-500/30">
                        <svg class="w-full h-44 opacity-20 absolute inset-0 text-gold-400 pointer-events-none" viewBox="0 0 500 500" fill="currentColor">
                            <path d="M150 100 Q 200 80, 280 120 T 380 150 T 420 250 T 350 380 T 220 420 T 120 320 T 80 200 Z" />
                        </svg>
                        
                        <div class="relative z-10 space-y-4">
                            <div class="flex justify-around items-center text-gold-400 text-3xl">
                                <i class="fa-solid fa-car-side transform -scale-x-1"></i>
                                <i class="fa-solid fa-plane"></i>
                                <i class="fa-solid fa-ship"></i>
                            </div>
                            <h3 class="text-lg font-bold text-white">Armada Gemas Trans</h3>
                            <p class="text-xs text-gray-300">Toyota Innova Reborn & Toyota Innova Zenix</p>
                            
                            <div class="grid grid-cols-2 gap-2 text-xs pt-2">
                                <div class="bg-emerald-950/60 p-2.5 rounded-lg border border-gold-500/20">
                                    <div class="font-bold text-gold-400">Innova Reborn</div>
                                    <div class="text-[10px] text-gray-400">Nyaman & Tangguh</div>
                                </div>
                                <div class="bg-emerald-950/60 p-2.5 rounded-lg border border-gold-500/20">
                                    <div class="font-bold text-gold-400">Innova Zenix</div>
                                    <div class="text-[10px] text-gray-400">Mewah & Modern</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Main Booking Section -->
    <main class="flex-grow max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pb-16 w-full">
        
        <!-- Service Type Tabs -->
        <div class="flex justify-center mb-8">
            <div class="inline-flex p-1.5 rounded-2xl glass-card border border-gold-500/30 w-full max-w-lg">
                <button id="tab-reguler" onclick="switchService('reguler')" class="flex-1 py-3 px-4 rounded-xl text-xs sm:text-sm font-bold transition-all duration-300 flex items-center justify-center space-x-2 bg-gold-500 text-emerald-950 shadow-md">
                    <i class="fa-solid fa-chair"></i>
                    <span>Travel Reguler</span>
                </button>
                <button id="tab-carter" onclick="switchService('carter')" class="flex-1 py-3 px-4 rounded-xl text-xs sm:text-sm font-bold transition-all duration-300 flex items-center justify-center space-x-2 text-gray-300 hover:text-white">
                    <i class="fa-solid fa-car-rear"></i>
                    <span>Carter Privat</span>
                </button>
                <button id="tab-cargo" onclick="switchService('cargo')" class="flex-1 py-3 px-4 rounded-xl text-xs sm:text-sm font-bold transition-all duration-300 flex items-center justify-center space-x-2 text-gray-300 hover:text-white">
                    <i class="fa-solid fa-box font-bold"></i>
                    <span>Jasa Titip / Cargo</span>
                </button>
            </div>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8">
            
            <!-- Left Form Column -->
            <div class="lg:col-span-7">
                <div class="glass-card rounded-2xl p-6 sm:p-8 border border-gold-500/20 relative">
                    
                    <!-- Form Title & Header -->
                    <div class="flex items-center justify-between pb-6 mb-6 border-b border-emerald-800/80">
                        <div>
                            <h3 id="form-heading" class="text-xl font-bold text-white flex items-center gap-2">
                                <i class="fa-solid fa-sliders text-gold-400"></i>
                                <span>Pemesanan Travel Reguler</span>
                            </h3>
                            <p id="form-subheading" class="text-xs text-gray-400 mt-1">Lengkapi rute dan detail kursi pilihan Anda</p>
                        </div>
                        <div class="text-right">
                            <span id="capacityBadge" class="text-xs bg-gold-500/10 text-gold-400 px-3 py-1 rounded-full border border-gold-500/30 font-medium">Maksimal 4 Seat</span>
                        </div>
                    </div>

                    <form id="bookingForm" onsubmit="event.preventDefault();" class="space-y-6">
                        
                        <!-- Name & Date -->
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-semibold text-gray-300 mb-2">Nama Pemesan</label>
                                <div class="relative">
                                    <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-gray-400">
                                        <i class="fa-solid fa-user text-xs"></i>
                                    </span>
                                    <input type="text" id="custName" placeholder="Masukkan nama Anda" class="w-full bg-emerald-950/80 border border-emerald-800 focus:border-gold-400 rounded-xl pl-9 pr-4 py-2.5 text-sm text-white placeholder-gray-500 focus:outline-none transition-all" required oninput="calculateTotal()">
                                </div>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-gray-300 mb-2">Tanggal Keberangkatan</label>
                                <div class="relative">
                                    <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-gray-400">
                                        <i class="fa-solid fa-calendar-day text-xs"></i>
                                    </span>
                                    <input type="date" id="tripDate" class="w-full bg-emerald-950/80 border border-emerald-800 focus:border-gold-400 rounded-xl pl-9 pr-4 py-2.5 text-sm text-white focus:outline-none transition-all" required onchange="calculateTotal()">
                                </div>
                            </div>
                        </div>

                        <!-- Trip Type: Single vs Pulang Pergi (PP) -->
                        <div>
                            <label class="block text-xs font-semibold text-gray-300 mb-2">Tipe Perjalanan</label>
                            <div class="grid grid-cols-2 gap-3">
                                <label class="cursor-pointer">
                                    <input type="radio" name="tripType" value="single" class="peer hidden" checked onchange="handleTripTypeChange(); calculateTotal();">
                                    <div class="p-3 rounded-xl border border-emerald-800 bg-emerald-950/60 peer-checked:border-gold-400 peer-checked:bg-gold-500/20 text-center text-xs font-semibold text-gray-300 peer-checked:text-gold-400 transition-all flex items-center justify-center space-x-2">
                                        <i class="fa-solid fa-arrow-right-long"></i>
                                        <span>Sekali Jalan</span>
                                    </div>
                                </label>
                                <label class="cursor-pointer">
                                    <input type="radio" name="tripType" value="pp" class="peer hidden" onchange="handleTripTypeChange(); calculateTotal();">
                                    <div class="p-3 rounded-xl border border-emerald-800 bg-emerald-950/60 peer-checked:border-gold-400 peer-checked:bg-gold-500/20 text-center text-xs font-semibold text-gray-300 peer-checked:text-gold-400 transition-all flex items-center justify-center space-x-2">
                                        <i class="fa-solid fa-arrows-rotate"></i>
                                        <span>Pulang Pergi (PP)</span>
                                    </div>
                                </label>
                            </div>
                        </div>

                        <!-- Route Selection -->
                        <div>
                            <label class="block text-xs font-semibold text-gray-300 mb-2">Rute Perjalanan</label>
                            <div class="relative">
                                <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-gray-400">
                                    <i class="fa-solid fa-route text-xs"></i>
                                </span>
                                <select id="routeSelect" class="w-full bg-emerald-950/80 border border-emerald-800 focus:border-gold-400 rounded-xl pl-9 pr-4 py-2.5 text-sm text-white focus:outline-none transition-all" onchange="updateScheduleAndSeatOptions(); calculateTotal();">
                                    <option value="BTG-SMD">Bontang ↔ Samarinda</option>
                                    <option value="BTG-BPN">Bontang ↔ Balikpapan (Inc. Tol)</option>
                                    <option value="SMD-BPN">Samarinda ↔ Balikpapan (Inc. Tol)</option>
                                    <option value="SMD-BTG">Samarinda ↔ Bontang</option>
                                    <option value="BPN-BTG">Balikpapan ↔ Bontang (Inc. Tol)</option>
                                    <option value="BPN-SMD">Balikpapan ↔ Samarinda (Inc. Tol)</option>
                                </select>
                            </div>
                        </div>

                        <!-- Charter Specific Options -->
                        <div id="carterOptions" class="hidden space-y-4 border-t border-emerald-800/80 pt-4">
                            <div>
                                <label class="block text-xs font-semibold text-gray-300 mb-2">Pilihan Armada Carter</label>
                                <div class="grid grid-cols-2 gap-3" id="carterVehicleContainer">
                                    <label class="cursor-pointer">
                                        <input type="radio" name="carterVehicle" value="reborn" class="peer hidden" checked onchange="calculateTotal()">
                                        <div class="p-3 rounded-xl border border-emerald-800 bg-emerald-950/60 peer-checked:border-gold-400 peer-checked:bg-gold-500/20 text-center text-xs font-semibold text-gray-300 peer-checked:text-gold-400 transition-all">
                                            <div class="font-bold">Innova Reborn</div>
                                            <div class="text-[10px] text-gray-400 mt-1">Kapasitas Nyaman</div>
                                        </div>
                                    </label>
                                    <label class="cursor-pointer">
                                        <input type="radio" name="carterVehicle" value="zenix" class="peer hidden" onchange="calculateTotal()">
                                        <div class="p-3 rounded-xl border border-emerald-800 bg-emerald-950/60 peer-checked:border-gold-400 peer-checked:bg-gold-500/20 text-center text-xs font-semibold text-gray-300 peer-checked:text-gold-400 transition-all">
                                            <div class="font-bold">Innova Zenix</div>
                                            <div class="text-[10px] text-gray-400 mt-1">Kemewahan Eksekutif</div>
                                        </div>
                                    </label>
                                </div>
                            </div>

                            <!-- Non-Toll Option for Balikpapan Routes -->
                            <div id="tollOptionContainer" class="hidden bg-emerald-900/30 p-3.5 rounded-xl border border-gold-500/20">
                                <label class="block text-xs font-semibold text-gold-400 mb-2">Jalur Perjalanan (Khusus Carter Balikpapan)</label>
                                <div class="grid grid-cols-2 gap-3">
                                    <label class="cursor-pointer">
                                        <input type="radio" name="tollOption" value="include_tol" class="peer hidden" checked onchange="calculateTotal()">
                                        <div class="p-2.5 rounded-lg border border-emerald-800 bg-emerald-950/80 peer-checked:border-gold-400 peer-checked:bg-gold-500/20 text-center text-xs font-medium text-gray-300 peer-checked:text-gold-400 transition-all">
                                            <span>Lewat Jalan Tol</span>
                                        </div>
                                    </label>
                                    <label class="cursor-pointer">
                                        <input type="radio" name="tollOption" value="non_tol" class="peer hidden" onchange="calculateTotal()">
                                        <div class="p-2.5 rounded-lg border border-emerald-800 bg-emerald-950/80 peer-checked:border-gold-400 peer-checked:bg-gold-500/20 text-center text-xs font-medium text-gray-300 peer-checked:text-gold-400 transition-all">
                                            <span>Non-Tol (Rp 900.000)</span>
                                        </div>
                                    </label>
                                </div>
                            </div>
                        </div>

                        <!-- Reguler Seat Map Section -->
                        <div id="seatSelectionSection" class="space-y-3 border-t border-emerald-800/80 pt-4">
                            <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-1">
                                <label class="block text-xs font-semibold text-gray-300">Pilihan Posisi Seat (Maksimal 4 Seat)</label>
                                <span class="text-[11px] text-gold-400 font-mono" id="seatPriceBadge">Depan: Rp 250k | Tengah: Rp 200k | Belakang: Rp 150k</span>
                            </div>

                            <!-- Vehicle Seat Layout -->
                            <div class="bg-emerald-950/80 border border-emerald-800/80 rounded-2xl p-4">
                                <div class="text-center text-[10px] uppercase tracking-widest text-gray-500 mb-3 border-b border-emerald-800/50 pb-1">
                                    <i class="fa-solid fa-angle-up"></i> Depan Mobil (Driver)
                                </div>
                                
                                <div class="grid grid-cols-2 gap-3 mb-3">
                                    <div class="bg-emerald-900/40 p-2 rounded-lg text-center border border-dashed border-emerald-700/50 text-xs text-gray-500 flex items-center justify-center">
                                        <i class="fa-solid fa-user-gear mr-1"></i> Driver
                                    </div>
                                    <div>
                                        <input type="radio" id="seat-depan" name="seatPosition" value="Depan" class="seat-radio hidden" checked onchange="calculateTotal()">
                                        <label for="seat-depan" class="block text-center p-2.5 rounded-xl border border-emerald-800 bg-emerald-900/60 text-xs text-gray-300 cursor-pointer transition-all hover:border-gold-500/40">
                                            <div class="font-bold">Baris 1 - Depan</div>
                                            <div class="text-[10px] text-gold-400/80 mt-0.5" id="price-depan">Rp 250.000</div>
                                        </label>
                                    </div>
                                </div>

                                <div class="space-y-2">
                                    <div>
                                        <input type="radio" id="seat-tengah" name="seatPosition" value="Tengah" class="seat-radio hidden" onchange="calculateTotal()">
                                        <label for="seat-tengah" class="block text-center p-2.5 rounded-xl border border-emerald-800 bg-emerald-900/60 text-xs text-gray-300 cursor-pointer transition-all hover:border-gold-500/40">
                                            <div class="font-bold">Baris 2 - Tengah</div>
                                            <div class="text-[10px] text-gold-400/80 mt-0.5" id="price-tengah">Rp 200.000</div>
                                        </label>
                                    </div>
                                    <div>
                                        <input type="radio" id="seat-belakang" name="seatPosition" value="Belakang" class="seat-radio hidden" onchange="calculateTotal()">
                                        <label for="seat-belakang" class="block text-center p-2.5 rounded-xl border border-emerald-800 bg-emerald-900/60 text-xs text-gray-300 cursor-pointer transition-all hover:border-gold-500/40">
                                            <div class="font-bold">Baris 3 - Belakang (-50k)</div>
                                            <div class="text-[10px] text-gold-400/80 mt-0.5" id="price-belakang">Rp 150.000</div>
                                        </label>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Cargo Section Controls -->
                        <div id="cargoOptions" class="hidden space-y-4 border-t border-emerald-800/80 pt-4">
                            <div>
                                <label class="block text-xs font-semibold text-gray-300 mb-2">Jenis Titipan Barang</label>
                                <input type="text" id="cargoDescription" placeholder="Contoh: Dokumen, Koper, Kardus, Sparepart" class="w-full bg-emerald-950/80 border border-emerald-800 focus:border-gold-400 rounded-xl px-4 py-2.5 text-sm text-white placeholder-gray-500 focus:outline-none transition-all">
                            </div>
                            <div class="grid grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-semibold text-gray-300 mb-2">Estimasi Berat (Kg)</label>
                                    <input type="number" id="cargoWeight" value="5" min="1" class="w-full bg-emerald-950/80 border border-emerald-800 focus:border-gold-400 rounded-xl px-4 py-2.5 text-sm text-white focus:outline-none transition-all" oninput="calculateTotal()">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-gray-300 mb-2">Hitungan Tarif</label>
                                    <select id="cargoType" class="w-full bg-emerald-950/80 border border-emerald-800 focus:border-gold-400 rounded-xl px-3 py-2.5 text-sm text-white focus:outline-none transition-all" onchange="calculateTotal()">
                                        <option value="standard">Reguler Paket (Kg/Dimensi)</option>
                                        <option value="full_seat">Beli 1 Seat Utuh Paket</option>
                                    </select>
                                </div>
                            </div>
                        </div>

                        <!-- Schedule Selector -->
                        <div>
                            <label class="block text-xs font-semibold text-gray-300 mb-2">Jadwal Keberangkatan</label>
                            
                            <!-- Reguler Time Select -->
                            <div id="regulerTimeContainer" class="relative">
                                <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-gray-400">
                                    <i class="fa-regular fa-clock text-xs"></i>
                                </span>
                                <select id="timeSchedule" class="w-full bg-emerald-950/80 border border-emerald-800 focus:border-gold-400 rounded-xl pl-9 pr-4 py-2.5 text-sm text-white focus:outline-none transition-all" onchange="calculateTotal()">
                                </select>
                            </div>

                            <!-- Carter Custom 24H Picker -->
                            <div id="carterTimeContainer" class="hidden space-y-2">
                                <div class="relative">
                                    <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-gray-400">
                                        <i class="fa-solid fa-clock text-xs text-gold-400"></i>
                                    </span>
                                    <input type="time" id="carterCustomTime" value="08:00" class="w-full bg-emerald-950/80 border border-gold-500/50 focus:border-gold-400 rounded-xl pl-9 pr-4 py-2.5 text-sm text-white focus:outline-none transition-all" onchange="calculateTotal()">
                                </div>
                                <p class="text-[11px] text-gold-400"><i class="fa-solid fa-circle-info mr-1"></i> Khusus Carter: Bebas menentukan jam keberangkatan 24 jam.</p>
                            </div>
                        </div>

                        <!-- Pickup Location / Share Location Google Maps Integration -->
                        <div class="space-y-3 border-t border-emerald-800/80 pt-4">
                            <label class="block text-xs font-semibold text-gray-300">Alamat Penjemputan & Share Location Google Maps</label>
                            
                            <div class="flex flex-col sm:flex-row gap-2">
                                <button type="button" onclick="getCurrentGPSLocation()" class="flex-1 bg-emerald-900/80 hover:bg-emerald-800 border border-gold-500/40 text-gold-400 py-2.5 px-3 rounded-xl text-xs font-semibold flex items-center justify-center space-x-2 transition-all">
                                    <i class="fa-solid fa-location-crosshairs text-base"></i>
                                    <span>Gunakan Lokasi Saya (GPS)</span>
                                </button>
                                <a href="https://maps.google.com" target="_blank" class="flex-1 bg-emerald-950 border border-emerald-800 hover:border-gold-500/30 text-gray-300 py-2.5 px-3 rounded-xl text-xs font-semibold flex items-center justify-center space-x-2 transition-all">
                                    <i class="fa-solid fa-map-location-dot text-base text-gold-400"></i>
                                    <span>Buka Google Maps</span>
                                </a>
                            </div>

                            <input type="text" id="gmapsUrl" placeholder="Link Shareloc Google Maps (Opsional / Otomatis)" class="w-full bg-emerald-950/80 border border-emerald-800 focus:border-gold-400 rounded-xl px-4 py-2.5 text-xs text-gold-400 placeholder-gray-500 font-mono focus:outline-none transition-all">

                            <textarea id="notes" rows="2" placeholder="Detail Patokan Alamat Lengkap (Contoh: Depan Indomaret, Rumah Pagar Hijau)..." class="w-full bg-emerald-950/80 border border-emerald-800 focus:border-gold-400 rounded-xl px-4 py-2.5 text-sm text-white placeholder-gray-500 focus:outline-none transition-all" oninput="calculateTotal()"></textarea>
                        </div>

                        <!-- CS Selection -->
                        <div>
                            <label class="block text-xs font-semibold text-gray-300 mb-2">Pilih Admin WhatsApp CS</label>
                            <div class="grid grid-cols-2 gap-3">
                                <label class="cursor-pointer">
                                    <input type="radio" name="csTarget" value="CS1" class="peer hidden" checked>
                                    <div class="p-3 rounded-xl border border-emerald-800 bg-emerald-950/60 peer-checked:border-gold-400 peer-checked:bg-gold-500/20 text-center text-xs font-medium text-gray-300 peer-checked:text-gold-400 transition-all">
                                        <div class="font-bold">CS 1 (Utama)</div>
                                        <div class="text-[10px] text-emerald-400 font-mono mt-0.5">0813-4627-7328</div>
                                    </div>
                                </label>
                                <label class="cursor-pointer">
                                    <input type="radio" name="csTarget" value="CS2" class="peer hidden">
                                    <div class="p-3 rounded-xl border border-emerald-800 bg-emerald-950/60 peer-checked:border-gold-400 peer-checked:bg-gold-500/20 text-center text-xs font-medium text-gray-300 peer-checked:text-gold-400 transition-all">
                                        <div class="font-bold">CS 2 (Cadangan)</div>
                                        <div class="text-[10px] text-emerald-400 font-mono mt-0.5">0851-5643-6097</div>
                                    </div>
                                </label>
                            </div>
                        </div>

                    </form>
                </div>
            </div>

            <!-- Right Column - Receipt Preview & Submit -->
            <div class="lg:col-span-5 flex flex-col justify-between">
                <div class="glass-card rounded-2xl p-6 sm:p-8 border border-gold-500/30 sticky top-28 space-y-6">
                    
                    <div class="flex items-center justify-between border-b border-emerald-800/80 pb-4">
                        <h4 class="text-lg font-bold text-white flex items-center gap-2">
                            <i class="fa-solid fa-file-invoice-dollar text-gold-400"></i>
                            <span>Rincian Pemesanan</span>
                        </h4>
                        <span id="serviceBadge" class="bg-gold-500/20 text-gold-400 border border-gold-500/30 text-[10px] px-2.5 py-1 rounded-md font-bold uppercase">Reguler</span>
                    </div>

                    <!-- Calculated Receipt -->
                    <div class="space-y-3 text-sm">
                        <div class="flex justify-between text-gray-300">
                            <span class="text-xs">Rute Perjalanan:</span>
                            <span id="summaryRoute" class="font-semibold text-white text-right">Bontang ↔ Samarinda</span>
                        </div>
                        <div class="flex justify-between text-gray-300">
                            <span class="text-xs">Tipe Perjalanan:</span>
                            <span id="summaryTripType" class="font-semibold text-white">Sekali Jalan</span>
                        </div>
                        <div class="flex justify-between text-gray-300" id="summaryDetailRow">
                            <span class="text-xs" id="summaryDetailLabel">Posisi Seat:</span>
                            <span id="summaryDetailVal" class="font-semibold text-gold-400">Baris 1 - Depan</span>
                        </div>
                        <div class="flex justify-between text-gray-300">
                            <span class="text-xs">Jadwal Keberangkatan:</span>
                            <span id="summarySchedule" class="font-semibold text-white">06:00 - 07:00 WITA</span>
                        </div>
                        <div class="flex justify-between text-gray-300">
                            <span class="text-xs">Jalur / Tol:</span>
                            <span id="summaryToll" class="font-semibold text-emerald-400">Jalan Nasional</span>
                        </div>
                    </div>

                    <!-- Total Cost Banner -->
                    <div class="bg-emerald-950/90 rounded-xl p-4 border border-gold-500/30 text-center space-y-1">
                        <span class="text-xs text-gray-400 uppercase tracking-wider font-semibold">Total Estimasi Tarif</span>
                        <div id="totalPriceDisplay" class="text-3xl font-extrabold gold-gradient-text">
                            Rp 250.000
                        </div>
                        <p class="text-[10px] text-gray-400">*Tarif resmi Gemas Trans Kalimantan</p>
                    </div>

                    <!-- WhatsApp Submission Button -->
                    <button onclick="submitToWhatsApp()" class="w-full gold-button py-4 rounded-xl flex items-center justify-center space-x-3 text-base shadow-lg cursor-pointer">
                        <i class="fa-brands fa-whatsapp text-xl"></i>
                        <span>Kirim Pesanan via WhatsApp</span>
                    </button>

                    <div class="text-[11px] text-gray-400 text-center leading-relaxed">
                        <i class="fa-solid fa-circle-info text-gold-400/80 mr-1"></i>
                        Pesan Anda akan otomatis terformat dan langsung terhubung dengan Admin CS Gemas Trans.
                    </div>

                </div>
            </div>

        </div>

    </main>

    <footer class="mt-auto border-t border-emerald-800/60 bg-emerald-950/90 py-8 text-center text-xs text-gray-400">
        <div class="max-w-7xl mx-auto px-4 space-y-3">
            <div class="flex justify-center items-center space-x-2 text-gold-400 font-bold">
                <i class="fa-solid fa-car-side"></i>
                <span>GEMAS TRANS KALIMANTAN</span>
            </div>
            <p>Layanan Transportasi & Cargo Terpercaya Rute Bontang - Samarinda - Balikpapan (PP)</p>
            <p class="text-[10px] text-gray-500">&copy; 2026 Gemas Trans. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        let currentService = 'reguler';

        window.onload = function() {
            // Set default date to today
            const today = new Date().toISOString().split('T')[0];
            document.getElementById('tripDate').value = today;
            
            updateScheduleAndSeatOptions();
            calculateTotal();
        };

        // GPS Geolocation Handler
        function getCurrentGPSLocation() {
            if (navigator.geolocation) {
                const gmapsInput = document.getElementById('gmapsUrl');
                gmapsInput.value = "Mengambil koordinat GPS...";

                navigator.geolocation.getCurrentPosition(
                    (position) => {
                        const lat = position.coords.latitude;
                        const lng = position.coords.longitude;
                        const mapsUrl = `https://maps.google.com/?q=${lat},${lng}`;
                        gmapsInput.value = mapsUrl;
                    },
                    (error) => {
                        alert("Gagal mengambil lokasi GPS. Silakan pastikan izin GPS/Lokasi aktif di browser/HP Anda.");
                        gmapsInput.value = "";
                    }
                );
            } else {
                alert("Browser Anda tidak mendukung layanan Geolocation.");
            }
        }

        // Switch Tab Services (Reguler, Carter, Cargo)
        function switchService(service) {
            currentService = service;

            // Update Tab UI States
            const tabs = ['reguler', 'carter', 'cargo'];
            tabs.forEach(t => {
                const btn = document.getElementById(`tab-${t}`);
                if (t === service) {
                    btn.className = "flex-1 py-3 px-4 rounded-xl text-xs sm:text-sm font-bold transition-all duration-300 flex items-center justify-center space-x-2 bg-gold-500 text-emerald-950 shadow-md";
                } else {
                    btn.className = "flex-1 py-3 px-4 rounded-xl text-xs sm:text-sm font-bold transition-all duration-300 flex items-center justify-center space-x-2 text-gray-300 hover:text-white";
                }
            });

            // Toggle Form Sections
            const seatSection = document.getElementById('seatSelectionSection');
            const carterSection = document.getElementById('carterOptions');
            const cargoSection = document.getElementById('cargoOptions');
            const regulerTimeContainer = document.getElementById('regulerTimeContainer');
            const carterTimeContainer = document.getElementById('carterTimeContainer');
            const capacityBadge = document.getElementById('capacityBadge');

            if (service === 'reguler') {
                document.getElementById('form-heading').innerHTML = `<i class="fa-solid fa-sliders text-gold-400"></i><span>Pemesanan Travel Reguler</span>`;
                document.getElementById('form-subheading').innerText = "Lengkapi rute dan detail kursi pilihan Anda";
                document.getElementById('serviceBadge').innerText = "Reguler";
                capacityBadge.innerText = "Maksimal 4 Seat";

                seatSection.classList.remove('hidden');
                carterSection.classList.add('hidden');
                cargoSection.classList.add('hidden');
                regulerTimeContainer.classList.remove('hidden');
                carterTimeContainer.classList.add('hidden');

            } else if (service === 'carter') {
                document.getElementById('form-heading').innerHTML = `<i class="fa-solid fa-car-rear text-gold-400"></i><span>Pemesanan Carter Privat</span>`;
                document.getElementById('form-subheading').innerText = "Layanan sewa privat 1 mobil utuh dengan jam bebas (24 Jam)";
                document.getElementById('serviceBadge').innerText = "Carter";
                capacityBadge.innerText = "Privat 1 Mobil";

                seatSection.classList.add('hidden');
                carterSection.classList.remove('hidden');
                cargoSection.classList.add('hidden');
                regulerTimeContainer.classList.add('hidden');
                carterTimeContainer.classList.remove('hidden');

            } else if (service === 'cargo') {
                document.getElementById('form-heading').innerHTML = `<i class="fa-solid fa-box text-gold-400"></i><span>Jasa Titip Barang / Cargo</span>`;
                document.getElementById('form-subheading').innerText = "Pengiriman barang ekspres cepat dan terjamin";
                document.getElementById('serviceBadge').innerText = "Cargo";
                capacityBadge.innerText = "Barang / Titipan";

                seatSection.classList.add('hidden');
                carterSection.classList.add('hidden');
                cargoSection.classList.remove('hidden');
                regulerTimeContainer.classList.remove('hidden');
                carterTimeContainer.classList.add('hidden');
            }

            updateScheduleAndSeatOptions();
            calculateTotal();
        }

        function handleTripTypeChange() {
            updateScheduleAndSeatOptions();
            calculateTotal();
        }

        // Dynamic Schedule and Seat Pricing Mapping
        function updateScheduleAndSeatOptions() {
            const route = document.getElementById('routeSelect').value;
            const scheduleSelect = document.getElementById('timeSchedule');
            
            scheduleSelect.innerHTML = '';
            let schedules = [];

            if (route === 'BTG-SMD' || route === 'SMD-BTG') {
                schedules = [
                    "06:00 - 07:00 WITA (Sesi Pagi Utama)",
                    "09:00 - 10:00 WITA (Sesi Pagi Tambahan)",
                    "16:00 - 17:00 WITA (Sesi Sore)",
                    "22:00 - 23:00 WITA (Sesi Malam)"
                ];
            } else {
                schedules = [
                    "06:00 - 07:00 WITA (Sesi Pagi)",
                    "22:00 - 23:00 WITA (Sesi Malam Expres)"
                ];
            }

            schedules.forEach(sch => {
                const opt = document.createElement('option');
                opt.value = sch;
                opt.textContent = sch;
                scheduleSelect.appendChild(opt);
            });

            // Update Seat Prices Labels based on route
            const priceDepan = document.getElementById('price-depan');
            const priceTengah = document.getElementById('price-tengah');
            const priceBelakang = document.getElementById('price-belakang');
            const seatBadge = document.getElementById('seatPriceBadge');

            if (route === 'BTG-SMD' || route === 'SMD-BTG' || route === 'SMD-BPN' || route === 'BPN-SMD') {
                priceDepan.textContent = "Rp 250.000";
                priceTengah.textContent = "Rp 200.000";
                priceBelakang.textContent = "Rp 150.000";
                seatBadge.textContent = "Depan: Rp 250k | Tengah: Rp 200k | Belakang: Rp 150k";
            } else if (route === 'BTG-BPN' || route === 'BPN-BTG') {
                priceDepan.textContent = "Rp 400.000";
                priceTengah.textContent = "Rp 350.000";
                priceBelakang.textContent = "Rp 300.000";
                seatBadge.textContent = "Depan: Rp 400k | Tengah: Rp 350k | Belakang: Rp 300k";
            }

            // Show / Hide Non-Toll Container for Carter
            const tollContainer = document.getElementById('tollOptionContainer');
            if (currentService === 'carter' && (route.includes('BPN'))) {
                tollContainer.classList.remove('hidden');
            } else {
                tollContainer.classList.add('hidden');
            }
        }

        // Main Calculation Engine
        function calculateTotal() {
            const route = document.getElementById('routeSelect').value;
            const isPP = document.querySelector('input[name="tripType"]:checked').value === 'pp';
            const multiplier = isPP ? 2 : 1;

            let total = 0;
            let tollStatus = "Jalan Nasional";

            // Format Display Text
            let routeText = "";
            if (route === 'BTG-SMD') routeText = "Bontang ↔ Samarinda";
            if (route === 'SMD-BTG') routeText = "Samarinda ↔ Bontang";
            if (route === 'BTG-BPN') routeText = "Bontang ↔ Balikpapan";
            if (route === 'BPN-BTG') routeText = "Balikpapan ↔ Bontang";
            if (route === 'SMD-BPN') routeText = "Samarinda ↔ Balikpapan";
            if (route === 'BPN-SMD') routeText = "Balikpapan ↔ Samarinda";

            document.getElementById('summaryRoute').innerText = routeText;
            document.getElementById('summaryTripType').innerText = isPP ? "Pulang Pergi (PP)" : "Sekali Jalan";

            if (currentService === 'carter') {
                const timeVal = document.getElementById('carterCustomTime').value || "08:00";
                document.getElementById('summarySchedule').innerText = `${timeVal} WITA (Bebas Request)`;
            } else {
                document.getElementById('summarySchedule').innerText = document.getElementById('timeSchedule').value || "-";
            }

            if (currentService === 'reguler') {
                document.getElementById('summaryDetailLabel').innerText = "Posisi Seat:";
                const seatPos = document.querySelector('input[name="seatPosition"]:checked').value;
                document.getElementById('summaryDetailVal').innerText = `Baris - ${seatPos}`;

                let basePrice = 0;
                if (route === 'BTG-SMD' || route === 'SMD-BTG' || route === 'SMD-BPN' || route === 'BPN-SMD') {
                    if (seatPos === 'Depan') basePrice = 250000;
                    if (seatPos === 'Tengah') basePrice = 200000;
                    if (seatPos === 'Belakang') basePrice = 150000;
                } else if (route === 'BTG-BPN' || route === 'BPN-BTG') {
                    if (seatPos === 'Depan') basePrice = 400000;
                    if (seatPos === 'Tengah') basePrice = 350000;
                    if (seatPos === 'Belakang') basePrice = 300000;
                }

                total = basePrice * multiplier;
                tollStatus = route.includes('BPN') ? "Include Tol" : "Jalan Nasional";

            } else if (currentService === 'carter') {
                document.getElementById('summaryDetailLabel').innerText = "Armada Carter:";
                const carterVehicle = document.querySelector('input[name="carterVehicle"]:checked').value;
                const vehicleName = carterVehicle === 'reborn' ? 'Innova Reborn' : 'Innova Zenix';
                document.getElementById('summaryDetailVal').innerText = vehicleName;

                const tollOption = document.querySelector('input[name="tollOption"]:checked') ? document.querySelector('input[name="tollOption"]:checked').value : 'include_tol';

                if (route === 'BTG-SMD' || route === 'SMD-BTG') {
                    total = carterVehicle === 'reborn' ? 650000 : 700000;
                    total = total * multiplier;
                    tollStatus = "Jalan Nasional";

                } else if (route === 'SMD-BPN' || route === 'BPN-SMD') {
                    if (isPP) {
                        // Special PP rate Samarinda - Balikpapan
                        total = carterVehicle === 'reborn' ? 650000 : 750000;
                        tollStatus = "Include Tol (Khusus Tarif Spesial PP)";
                    } else {
                        if (tollOption === 'non_tol') {
                            total = 900000;
                            tollStatus = "Non-Tol";
                        } else {
                            total = carterVehicle === 'reborn' ? 1100000 : 1350000;
                            tollStatus = "Include Tol";
                        }
                    }
                } else if (route === 'BTG-BPN' || route === 'BPN-BTG') {
                    if (tollOption === 'non_tol') {
                        total = 900000 * multiplier;
                        tollStatus = "Non-Tol";
                    } else {
                        total = carterVehicle === 'reborn' ? 1100000 : 1350000;
                        total = total * multiplier;
                        tollStatus = "Include Tol";
                    }
                }

            } else if (currentService === 'cargo') {
                document.getElementById('summaryDetailLabel').innerText = "Tipe Titipan:";
                const cargoType = document.getElementById('cargoType').value;
                document.getElementById('summaryDetailVal').innerText = cargoType === 'full_seat' ? "1 Seat Utuh Paket" : "Reguler Paket";

                const weight = parseFloat(document.getElementById('cargoWeight').value) || 1;

                if (cargoType === 'full_seat') {
                    let seatCost = 200000;
                    if (route.includes('BPN')) seatCost = 350000;
                    total = seatCost * multiplier;
                } else {
                    let baseRate = 50000;
                    if (weight > 5) {
                        baseRate += (weight - 5) * 10000;
                    }
                    total = baseRate * multiplier;
                }
                tollStatus = route.includes('BPN') ? "Include Tol" : "Jalan Nasional";
            }

            document.getElementById('summaryToll').innerText = tollStatus;

            const formattedTotal = new Intl.NumberFormat('id-ID', { style: 'currency', currency: 'IDR', maximumFractionDigits: 0 }).format(total);
            document.getElementById('totalPriceDisplay').innerText = formattedTotal;
        }

        // WhatsApp Deep Linking Integration
        function submitToWhatsApp() {
            const custName = document.getElementById('custName').value.trim();
            const tripDate = document.getElementById('tripDate').value;

            if (!custName) {
                alert("Mohon masukkan nama pemesan.");
                document.getElementById('custName').focus();
                return;
            }

            if (!tripDate) {
                alert("Mohon masukkan tanggal keberangkatan.");
                document.getElementById('tripDate').focus();
                return;
            }

            const route = document.getElementById('summaryRoute').innerText;
            const tripType = document.getElementById('summaryTripType').innerText;
            const schedule = document.getElementById('summarySchedule').innerText;
            const detailLabel = document.getElementById('summaryDetailLabel').innerText;
            const detailVal = document.getElementById('summaryDetailVal').innerText;
            const tollStatus = document.getElementById('summaryToll').innerText;
            const totalPrice = document.getElementById('totalPriceDisplay').innerText;
            const gmapsUrl = document.getElementById('gmapsUrl').value.trim();
            const notes = document.getElementById('notes').value.trim() || "-";

            const csTarget = document.querySelector('input[name="csTarget"]:checked').value;
            const csPhone = csTarget === 'CS1' ? '6281346277328' : '6285156436097';

            let message = `Halo Admin *Gemas Trans*, saya ingin melakukan reservasi ${currentService.toUpperCase()}:\n\n`;
            message += `👤 *Nama Pemesan:* ${custName}\n`;
            message += `📅 *Tanggal:* ${tripDate}\n`;
            message += `🗺️ *Rute:* ${route}\n`;
            message += `🔄 *Tipe:* ${tripType}\n`;
            message += `🕒 *Jadwal Keberangkatan:* ${schedule}\n`;
            message += `🚗 *${detailLabel}* ${detailVal}\n`;
            message += `🛣️ *Jalur / Tol:* ${tollStatus}\n`;

            if (currentService === 'cargo') {
                const cargoDesc = document.getElementById('cargoDescription').value.trim() || "Paket / Barang";
                const weight = document.getElementById('cargoWeight').value;
                message += `📦 *Detail Barang:* ${cargoDesc} (~${weight} kg)\n`;
            }

            if (gmapsUrl) {
                message += `📍 *Link Shareloc GPS Google Maps:* ${gmapsUrl}\n`;
            }

            message += `🏠 *Alamat / Catatan:* ${notes}\n\n`;
            message += `💰 *Total Estimasi Tarif:* *${totalPrice}*\n\n`;
            message += `Mohon konfirmasi ketersediaan dan info pembayaran. Terima kasih!`;

            const encodedMessage = encodeURIComponent(message);
            window.open(`https://wa.me/${csPhone}?text=${encodedMessage}`, '_blank');
        }
    </script>
</body>
</html>
