<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Huy Hoàng Piano - Kho Đàn Piano Cơ, Piano Điện, Organ, Guitar Nhập Khẩu Nhật Bản</title>
    <meta name="description" content="Huy Hoàng Piano (huyhoangpiano.com) - Tổng kho đàn Piano cơ, Piano điện, Organ, Guitar nhập khẩu trực tiếp từ Nhật Bản tại 224 Đường 29 Tháng 3, Hòa Xuân, Đà Nẵng. Đảm bảo giá thành tốt nhất thị trường. Hotline: 0934 825 780.">
    
    <!-- Open Graph Thumbnail là Logo trang web khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://huyhoangpiano.com/">
    <meta property="og:title" content="Huy Hoàng Piano - Kho Đàn Piano Cơ, Piano Điện, Organ, Guitar Nhật Bản">
    <meta property="og:description" content="Kho đàn Piano cơ - Piano điện, Organ, Guitar nhập từ Nhật Bản. Đảm bảo giá thành tốt nhất thị trường. Địa chỉ: 224 Đường 29 Tháng 3, Hòa Xuân, Đà Nẵng.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1uwQg5nGLdpcyN9Xbx3L3KBc9RmwJ-ETG">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1uwQg5nGLdpcyN9Xbx3L3KBc9RmwJ-ETG">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1uwQg5nGLdpcyN9Xbx3L3KBc9RmwJ-ETG" type="image/png">

    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">
    
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        gold: {
                            50: '#fbf8f1',
                            100: '#f5eedb',
                            200: '#ead8b1',
                            300: '#dec082',
                            400: '#d1a353',
                            500: '#c58f31', /* Màu vàng hoàng gia theo logo Huy Hoàng Piano */
                            600: '#aa7226',
                            700: '#8a5721',
                            800: '#724621',
                            900: '#5f3b1f',
                        },
                        piano: {
                            dark: '#141414',
                            charcoal: '#222222',
                            sale: '#d26e4b', /* Màu badge giảm giá chuẩn Flatsome */
                            red: '#c81e1e'
                        }
                    },
                    maxWidth: {
                        'flatsome': '1500px'
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f9fafb;
            color: #1f2937;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome 1500px trên máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder (section-title-center) */
        .section-title-container {
            margin-bottom: 1.5rem;
        }
        .section-title {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
        }
        .section-title b {
            display: block;
            flex: 1;
            height: 2px;
            background-color: #e5e7eb;
        }
        .section-title-main {
            margin: 0 15px;
            text-align: center;
            text-transform: uppercase;
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            color: #141414;
            letter-spacing: 0.03em;
        }

        /* Badge phần trăm giảm giá góc trên bên trái chuẩn Flatsome */
        .flatsome-sale-badge {
            position: absolute;
            top: 10px;
            left: 10px;
            z-index: 10;
            width: 42px;
            height: 42px;
            border-radius: 9999px;
            background-color: #c81e1e;
            color: #ffffff;
            font-weight: 700;
            font-size: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(0,0,0,0.22);
            line-height: 1;
            pointer-events: none;
        }
        @media (max-width: 640px) {
            .flatsome-sale-badge {
                width: 36px;
                height: 36px;
                font-size: 11px;
                top: 7px;
                left: 7px;
            }
        }

        /* Dropdown menu chuẩn Flatsome */
        .nav-item-has-children:hover .sub-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .sub-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease-in-out;
        }

        /* Thanh cuộn ngang mượt cho danh mục trên mobile */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Nút nổi liên hệ rung nhẹ */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(197, 143, 49, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(197, 143, 49, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(197, 143, 49, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-[#f8f8f8] text-gray-800 antialiased selection:bg-gold-500 selection:text-white">

    <!-- ==========================================
         TOP BAR (Chuẩn Flatsome Top Bar)
    =========================================== -->
    <div class="bg-piano-dark text-gray-200 text-xs border-b border-gold-800/40">
        <div class="flatsome-container py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 md:gap-5 flex-wrap">
                <span class="font-medium text-gold-400 flex items-center gap-1.5">
                    <i class="fa-solid fa-crown text-gold-400"></i>
                    <span>HUY HOÀNG PIANO xin chào quý khách!</span>
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5 text-gray-300">
                    <i class="fa-solid fa-location-dot text-gold-400"></i>
                    224 Đường 29 Tháng 3, Phường Hòa Xuân, Đà Nẵng
                </span>
            </div>
            <div class="flex items-center gap-3 md:gap-5 ml-auto text-[11px] md:text-xs">
                <a href="tel:0934825780" class="hover:text-gold-400 transition flex items-center gap-1">
                    <i class="fa-solid fa-phone-volume text-gold-400"></i>
                    <span>Tư vấn: <strong class="text-white">0934 825 780</strong></span>
                </a>
                <span class="text-gray-600">|</span>
                <a href="tel:0762598824" class="hover:text-gold-400 transition flex items-center gap-1">
                    <i class="fa-solid fa-screwdriver-wrench text-gold-400"></i>
                    <span>Bảo hành: <strong class="text-white">076 259 8824</strong></span>
                </a>
                <span class="hidden lg:inline text-gray-600">|</span>
                <a href="https://www.facebook.com/huyhoangpianodanang" target="_blank" rel="noopener" class="hidden lg:inline-flex items-center gap-1 hover:text-gold-400 transition">
                    <i class="fa-brands fa-facebook text-blue-400"></i>
                    <span>Fanpage</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER (Flatsome Header - Logo gọn nhỏ, KHÔNG để nút gọi ngay tránh tràn viền)
    =========================================== -->
    <header id="header" class="bg-white sticky top-0 z-40 shadow-sm border-b border-gray-200">
        <!-- Header Main -->
        <div class="flatsome-container py-2.5 md:py-3 flex items-center justify-between gap-3 md:gap-6">
            
            <!-- Nút Menu Mobile -->
            <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg text-gray-700 hover:bg-gray-100 focus:outline-none">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>

            <!-- Logo (Chỉnh gọn nhỏ lại theo đúng yêu cầu, lấy từ link Google Drive + Fallback SVG sắc nét) -->
            <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                <div class="w-10 h-10 md:w-11 md:h-11 rounded-lg overflow-hidden border border-gold-300 bg-piano-dark flex items-center justify-center shrink-0 shadow-sm">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1uwQg5nGLdpcyN9Xbx3L3KBc9RmwJ-ETG" 
                        alt="Huy Hoàng Piano Logo" 
                        class="w-full h-full object-contain p-0.5"
                        onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1uwQg5nGLdpcyN9Xbx3L3KBc9RmwJ-ETG&sz=w300'; this.addEventListener('error', function(){ this.style.display='none'; document.getElementById('logoFallbackSvg').classList.remove('hidden'); });"
                    >
                    <!-- SVG Fallback nếu mạng chặn Google Drive -->
                    <svg id="logoFallbackSvg" class="hidden w-7 h-7 text-gold-400" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <rect x="6" y="14" width="52" height="36" rx="4" stroke="currentColor" stroke-width="4"/>
                        <path d="M18 14V34M27 14V34M37 14V34M46 14V34M14 34H50" stroke="currentColor" stroke-width="3"/>
                    </svg>
                </div>
                <div class="flex flex-col">
                    <span class="font-heading font-extrabold text-sm md:text-base lg:text-lg tracking-tight text-piano-dark leading-none">
                        HUY HOÀNG <span class="text-gold-600">PIANO</span>
                    </span>
                    <span class="text-[10px] md:text-[11px] text-gray-500 font-medium mt-0.5">
                        huyhoangpiano.com • Kho Đàn Nhật Bản
                    </span>
                </div>
            </a>

            <!-- Thanh tìm kiếm chuẩn Flatsome -->
            <div class="hidden md:flex flex-1 max-w-xl mx-auto">
                <form onsubmit="handleSearch(event)" class="w-full flex items-center border-2 border-gold-500/80 rounded-full overflow-hidden bg-gray-50 focus-within:bg-white focus-within:ring-2 focus-within:ring-gold-300 transition">
                    <select id="searchCategorySelect" class="bg-transparent text-xs font-medium text-gray-700 pl-3.5 pr-2 py-2.5 border-r border-gray-200 focus:outline-none cursor-pointer hidden xl:block">
                        <option value="all">Tất cả danh mục</option>
                        <option value="grand">Special Grand Piano</option>
                        <option value="upright">Upright Piano</option>
                        <option value="digital">Digital Piano</option>
                        <option value="organ">Đàn Organ</option>
                        <option value="guitar">Đàn Guitar</option>
                    </select>
                    <input 
                        id="searchInput"
                        type="text" 
                        placeholder="Tìm đàn Piano cơ Yamaha U3H, Clavinova, Kawai, Roland, Organ, Guitar..." 
                        class="w-full px-3.5 py-2 text-xs md:text-sm bg-transparent focus:outline-none text-gray-800"
                    >
                    <button type="submit" class="bg-gold-500 hover:bg-gold-600 text-white px-4 py-2.5 text-sm font-semibold transition shrink-0">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </form>
            </div>

            <!-- Khu vực thông tin ngắn gọn bên phải (Không đặt nút gọi ngay để tránh tràn viền) -->
            <div class="flex items-center gap-2 md:gap-4 shrink-0">
                <a href="#ban-do-showroom" class="hidden xl:flex items-center gap-2 text-xs text-gray-700 hover:text-gold-600 transition px-2.5 py-1.5 rounded-lg hover:bg-gold-50">
                    <i class="fa-solid fa-store text-gold-600 text-sm"></i>
                    <div class="leading-tight">
                        <div class="font-bold text-gray-900">Showroom Đà Nẵng</div>
                        <div class="text-[11px] text-gray-500">224 Đường 29/3, Hòa Xuân</div>
                    </div>
                </a>

                <a href="#form-bao-gia" class="flex items-center gap-1.5 text-xs font-semibold text-gray-700 hover:text-gold-600 px-2.5 py-1.5 rounded-lg border border-gray-200 hover:border-gold-400 transition">
                    <i class="fa-solid fa-file-invoice-dollar text-gold-600"></i>
                    <span class="hidden sm:inline">Nhận báo giá</span>
                </a>
            </div>
        </div>

        <!-- Thanh tìm kiếm hiển thị trên Mobile -->
        <div class="md:hidden flatsome-container pb-2.5">
            <form onsubmit="handleSearch(event)" class="w-full flex items-center border border-gold-500 rounded-full overflow-hidden bg-gray-50">
                <input 
                    id="mobileSearchInput"
                    type="text" 
                    placeholder="Tìm đàn Piano cơ, Piano điện, Organ, Guitar..." 
                    class="w-full px-3.5 py-1.5 text-xs bg-transparent focus:outline-none text-gray-800"
                >
                <button type="submit" class="bg-gold-500 text-white px-3.5 py-1.5 text-xs font-semibold">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </button>
            </form>
        </div>

        <!-- ==========================================
             THANH DANH MỤC TRÊN MÁY TÍNH (Flatsome Header Bottom Nav)
             Quy tắc: Tên danh mục viết liền trên 1 hàng (whitespace-nowrap), chữ nhỏ gọn, nằm trên 1 hàng hoặc xuống hàng 2 nguyên cụm, tuyệt đối không gãy chữ!
        =========================================== -->
        <nav class="hidden lg:block bg-piano-dark text-white border-t border-gold-900/30">
            <div class="flatsome-container">
                <ul class="flex flex-wrap items-center justify-center gap-x-1 xl:gap-x-2 py-1">
                    <li>
                        <a href="#" onclick="filterCategory('all'); return false;" class="inline-flex items-center gap-1.5 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gold-400 hover:text-white whitespace-nowrap transition">
                            <i class="fa-solid fa-house text-[11px]"></i> Trang Chủ
                        </a>
                    </li>

                    <!-- 1. Special Grand Piano -->
                    <li class="relative nav-item-has-children group">
                        <a href="#san-pham-piano-co" onclick="filterCategory('grand'); return false;" class="inline-flex items-center gap-1 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-100 hover:text-gold-400 whitespace-nowrap transition">
                            <span>Special Grand Piano</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                        </a>
                        <div class="sub-menu absolute left-0 top-full w-56 bg-white text-gray-800 shadow-xl rounded-b-lg border-t-2 border-gold-500 py-2 z-50">
                            <a href="#san-pham-piano-co" onclick="filterCategory('grand')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Grand Mới 100%</a>
                            <a href="#san-pham-piano-co" onclick="filterCategory('grand')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Autoplay Piano</a>
                            <a href="#san-pham-piano-co" onclick="filterCategory('grand')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Steinway &amp; Sons</a>
                            <a href="#san-pham-piano-co" onclick="filterCategory('grand')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Grand Piano Yamaha (C1, G2, C3)</a>
                            <a href="#san-pham-piano-co" onclick="filterCategory('grand')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Grand Piano Kawai &amp; Shigeru Kawai</a>
                            <a href="#san-pham-piano-co" onclick="filterCategory('grand')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Apollo / Diapason / Boston</a>
                        </div>
                    </li>

                    <!-- 2. Upright Piano -->
                    <li class="relative nav-item-has-children group">
                        <a href="#san-pham-piano-co" onclick="filterCategory('upright'); return false;" class="inline-flex items-center gap-1 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-100 hover:text-gold-400 whitespace-nowrap transition">
                            <span>Upright Piano</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                        </a>
                        <div class="sub-menu absolute left-0 top-full w-56 bg-white text-gray-800 shadow-xl rounded-b-lg border-t-2 border-gold-500 py-2 z-50">
                            <a href="#san-pham-piano-co" onclick="filterCategory('upright')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Upright Mới 100%</a>
                            <a href="#san-pham-piano-co" onclick="filterCategory('upright')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Yamaha (U1, U2, U3, UX, W Series)</a>
                            <a href="#san-pham-piano-co" onclick="filterCategory('upright')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Kawai (BL, US, K Series)</a>
                            <a href="#san-pham-piano-co" onclick="filterCategory('upright')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Apollo &amp; Diapason Nội Địa Nhật</a>
                            <a href="#san-pham-piano-co" onclick="filterCategory('upright')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Samick / Youngchang / Atlas</a>
                        </div>
                    </li>

                    <!-- 3. Digital Piano -->
                    <li class="relative nav-item-has-children group">
                        <a href="#san-pham-piano-dien" onclick="filterCategory('digital'); return false;" class="inline-flex items-center gap-1 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-100 hover:text-gold-400 whitespace-nowrap transition">
                            <span>Digital Piano</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                        </a>
                        <div class="sub-menu absolute left-0 top-full w-56 bg-white text-gray-800 shadow-xl rounded-b-lg border-t-2 border-gold-500 py-2 z-50">
                            <a href="#san-pham-piano-dien" onclick="filterCategory('digital')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Piano Điện Yamaha (CLP, YDP, P)</a>
                            <a href="#san-pham-piano-dien" onclick="filterCategory('digital')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Piano Điện Kawai (CA, CN, PW)</a>
                            <a href="#san-pham-piano-dien" onclick="filterCategory('digital')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Piano Điện Roland (HP, RP, FP)</a>
                            <a href="#san-pham-piano-dien" onclick="filterCategory('digital')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Piano Điện Casio (Celviano, Privia)</a>
                            <a href="#san-pham-piano-dien" onclick="filterCategory('digital')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Piano Điện Korg / Bowman / Nux</a>
                        </div>
                    </li>

                    <!-- 4. Đàn Organ -->
                    <li class="relative nav-item-has-children group">
                        <a href="#san-pham-organ-guitar" onclick="filterCategory('organ'); return false;" class="inline-flex items-center gap-1 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-100 hover:text-gold-400 whitespace-nowrap transition">
                            <span>Đàn Organ</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                        </a>
                        <div class="sub-menu absolute left-0 top-full w-52 bg-white text-gray-800 shadow-xl rounded-b-lg border-t-2 border-gold-500 py-2 z-50">
                            <a href="#san-pham-organ-guitar" onclick="filterCategory('organ')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Organ Yamaha Nhật Bản</a>
                            <a href="#san-pham-organ-guitar" onclick="filterCategory('organ')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Organ Casio Luyện Tập</a>
                            <a href="#san-pham-organ-guitar" onclick="filterCategory('organ')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Organ Kurtzman &amp; Roland</a>
                        </div>
                    </li>

                    <!-- 5. Đàn Guitar -->
                    <li class="relative nav-item-has-children group">
                        <a href="#san-pham-organ-guitar" onclick="filterCategory('guitar'); return false;" class="inline-flex items-center gap-1 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-100 hover:text-gold-400 whitespace-nowrap transition">
                            <span>Đàn Guitar</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                        </a>
                        <div class="sub-menu absolute left-0 top-full w-52 bg-white text-gray-800 shadow-xl rounded-b-lg border-t-2 border-gold-500 py-2 z-50">
                            <a href="#san-pham-organ-guitar" onclick="filterCategory('guitar')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Guitar Acoustic Nhật Bản</a>
                            <a href="#san-pham-organ-guitar" onclick="filterCategory('guitar')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Guitar Classic Yamaha / Morris</a>
                            <a href="#san-pham-organ-guitar" onclick="filterCategory('guitar')" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Guitar Điện &amp; Phụ Kiện</a>
                        </div>
                    </li>

                    <!-- 6. Khóa Học -->
                    <li class="relative nav-item-has-children group">
                        <a href="#dich-vu-khoa-hoc" class="inline-flex items-center gap-1 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-100 hover:text-gold-400 whitespace-nowrap transition">
                            <span>Khóa Học</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                        </a>
                        <div class="sub-menu absolute left-0 top-full w-52 bg-white text-gray-800 shadow-xl rounded-b-lg border-t-2 border-gold-500 py-2 z-50">
                            <a href="#dich-vu-khoa-hoc" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Khóa Học Piano Cơ Bản &amp; Nâng Cao</a>
                            <a href="#dich-vu-khoa-hoc" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Khóa Học Organ &amp; Đệm Hát</a>
                            <a href="#dich-vu-khoa-hoc" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Khóa Học Guitar Thực Hành</a>
                        </div>
                    </li>

                    <!-- 7. Service (Bảo hành - Sửa chữa) -->
                    <li class="relative nav-item-has-children group">
                        <a href="#dich-vu-khoa-hoc" class="inline-flex items-center gap-1 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-100 hover:text-gold-400 whitespace-nowrap transition">
                            <span>Service</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                        </a>
                        <div class="sub-menu absolute left-0 top-full w-60 bg-white text-gray-800 shadow-xl rounded-b-lg border-t-2 border-gold-500 py-2 z-50">
                            <a href="#dich-vu-khoa-hoc" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Dịch Vụ Sửa Chữa Piano (076 259 8824)</a>
                            <a href="#dich-vu-khoa-hoc" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Lên Dây Piano Tại Nhà</a>
                            <a href="#dich-vu-khoa-hoc" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Cho Thuê &amp; Vận Chuyển Piano</a>
                            <a href="#dich-vu-khoa-hoc" class="block px-4 py-1.5 text-xs hover:bg-gold-50 hover:text-gold-700 whitespace-nowrap">Thu Mua Đàn Piano Cũ Giá Cao</a>
                        </div>
                    </li>

                    <!-- 8. Tin Tức -->
                    <li>
                        <a href="#tin-tuc-piano" class="inline-flex items-center gap-1 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-100 hover:text-gold-400 whitespace-nowrap transition">
                            <span>Tin Tức</span>
                        </a>
                    </li>

                    <!-- 9. Đối Tác -->
                    <li>
                        <a href="#doi-tac-thuong-hieu" class="inline-flex items-center gap-1 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-100 hover:text-gold-400 whitespace-nowrap transition">
                            <span>Đối Tác</span>
                        </a>
                    </li>

                    <!-- 10. Khuyến Mãi -->
                    <li>
                        <a href="#san-pham-noi-bat" class="inline-flex items-center gap-1 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gold-400 hover:text-white whitespace-nowrap transition">
                            <i class="fa-solid fa-bolt text-[11px]"></i>
                            <span>Khuyến Mãi</span>
                        </a>
                    </li>

                    <!-- 11. Liên Hệ & Bản Đồ -->
                    <li>
                        <a href="#ban-do-showroom" class="inline-flex items-center gap-1 px-2.5 py-2 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-gray-100 hover:text-gold-400 whitespace-nowrap transition">
                            <span>Liên Hệ</span>
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Drawer Menu trên Điện Thoại -->
        <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/60 z-50 hidden"></div>
        <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-72 max-w-[82vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
            <div class="p-4 bg-piano-dark text-white flex items-center justify-between">
                <span class="font-heading font-bold text-sm text-gold-400">DANH MỤC SẢN PHẨM</span>
                <button onclick="toggleMobileMenu()" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center text-white">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-3 overflow-y-auto flex-1 divide-y divide-gray-100 text-xs font-semibold">
                <a href="#san-pham-noi-bat" onclick="filterCategory('all'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 px-2 hover:text-gold-600 whitespace-nowrap">
                    <span><i class="fa-solid fa-star text-gold-500 w-5"></i> Tất Cả Sản Phẩm Nổi Bật</span>
                    <i class="fa-solid fa-angle-right text-gray-400"></i>
                </a>
                <a href="#san-pham-piano-co" onclick="filterCategory('grand'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 px-2 hover:text-gold-600 whitespace-nowrap">
                    <span><i class="fa-solid fa-crown text-gold-500 w-5"></i> Special Grand Piano</span>
                    <i class="fa-solid fa-angle-right text-gray-400"></i>
                </a>
                <a href="#san-pham-piano-co" onclick="filterCategory('upright'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 px-2 hover:text-gold-600 whitespace-nowrap">
                    <span><i class="fa-solid fa-music text-gold-500 w-5"></i> Upright Piano Nhật Bản</span>
                    <i class="fa-solid fa-angle-right text-gray-400"></i>
                </a>
                <a href="#san-pham-piano-dien" onclick="filterCategory('digital'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 px-2 hover:text-gold-600 whitespace-nowrap">
                    <span><i class="fa-solid fa-sliders text-gold-500 w-5"></i> Digital Piano (Piano Điện)</span>
                    <i class="fa-solid fa-angle-right text-gray-400"></i>
                </a>
                <a href="#san-pham-organ-guitar" onclick="filterCategory('organ'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 px-2 hover:text-gold-600 whitespace-nowrap">
                    <span><i class="fa-solid fa-keyboard text-gold-500 w-5"></i> Đàn Organ Nhật Bản</span>
                    <i class="fa-solid fa-angle-right text-gray-400"></i>
                </a>
                <a href="#san-pham-organ-guitar" onclick="filterCategory('guitar'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 px-2 hover:text-gold-600 whitespace-nowrap">
                    <span><i class="fa-solid fa-guitar text-gold-500 w-5"></i> Đàn Guitar Acoustic / Classic</span>
                    <i class="fa-solid fa-angle-right text-gray-400"></i>
                </a>
                <a href="#dich-vu-khoa-hoc" onclick="toggleMobileMenu();" class="flex items-center justify-between py-2.5 px-2 hover:text-gold-600 whitespace-nowrap">
                    <span><i class="fa-solid fa-graduation-cap text-gold-500 w-5"></i> Khóa Học Đàn Tại Đà Nẵng</span>
                    <i class="fa-solid fa-angle-right text-gray-400"></i>
                </a>
                <a href="#dich-vu-khoa-hoc" onclick="toggleMobileMenu();" class="flex items-center justify-between py-2.5 px-2 hover:text-gold-600 whitespace-nowrap">
                    <span><i class="fa-solid fa-screwdriver-wrench text-gold-500 w-5"></i> Bảo Hành &amp; Sửa Chữa Piano</span>
                    <i class="fa-solid fa-angle-right text-gray-400"></i>
                </a>
                <a href="#tin-tuc-piano" onclick="toggleMobileMenu();" class="flex items-center justify-between py-2.5 px-2 hover:text-gold-600 whitespace-nowrap">
                    <span><i class="fa-solid fa-newspaper text-gold-500 w-5"></i> Tin Tức &amp; Kiến Thức Piano</span>
                    <i class="fa-solid fa-angle-right text-gray-400"></i>
                </a>
                <a href="#ban-do-showroom" onclick="toggleMobileMenu();" class="flex items-center justify-between py-2.5 px-2 hover:text-gold-600 whitespace-nowrap">
                    <span><i class="fa-solid fa-map-location-dot text-gold-500 w-5"></i> Bản Đồ &amp; Fanpage</span>
                    <i class="fa-solid fa-angle-right text-gray-400"></i>
                </a>
            </div>
            <div class="p-3 bg-gray-50 border-t border-gray-200 text-xs space-y-1.5">
                <div class="font-bold text-gray-800">Hotline tư vấn: <a href="tel:0934825780" class="text-gold-600">0934 825 780</a></div>
                <div class="font-bold text-gray-800">Bảo hành, sửa chữa: <a href="tel:0762598824" class="text-gold-600">076 259 8824</a></div>
            </div>
        </aside>
    </header>

    <!-- ==========================================
         SLIDER 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         - Thiết kế riêng phiên bản Banner Máy Tính (hidden md:block) và Banner Điện Thoại (block md:hidden)
         - Chữ nhỏ gọn nằm trọn bên trong ảnh banner, tuyệt đối không tràn viền
    =========================================== -->
    <section class="flatsome-container pt-3 pb-4">
        <div class="relative w-full overflow-hidden rounded-xl shadow-md bg-piano-dark">
            
            <!-- ================= SLIDE 1 ================= -->
            <div id="bannerSlide0" class="banner-slide transition-opacity duration-700 opacity-100">
                
                <!-- BANNER MÁY TÍNH 1 (Chiều cao cố định 400px bằng đúng Slide 2) -->
                <div class="hidden md:grid md:grid-cols-12 items-center h-[390px] lg:h-[420px] w-full bg-gradient-to-r from-[#111111] via-[#1d1912] to-[#2b2113] relative overflow-hidden px-8 lg:px-14">
                    <div class="col-span-7 z-10 pr-4">
                        <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-gold-500/20 border border-gold-400/40 text-gold-300 text-xs font-semibold mb-3">
                            <i class="fa-solid fa-certificate"></i> TỔNG KHO NHẠC CỤ NHẬP KHẨU NHẬT BẢN TẠI ĐÀ NẴNG
                        </div>
                        <h1 class="font-heading font-extrabold text-white text-2xl lg:text-3xl xl:text-4xl leading-tight mb-2.5">
                            HUY HOÀNG <span class="text-gold-400">PIANO</span>
                        </h1>
                        <p class="text-gold-200 font-semibold text-sm lg:text-base mb-3">
                            Kho Đàn Piano Cơ - Piano Điện, Organ, Guitar Nhập Từ Nhật Bản • Đảm Bảo Giá Thành Tốt Nhất Thị Trường
                        </p>
                        <div class="grid grid-cols-2 gap-2 text-xs text-gray-300 mb-5 max-w-xl">
                            <div class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-gold-400"></i> Nguyên bản 100% nội địa Nhật</div>
                            <div class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-gold-400"></i> Miễn phí vận chuyển Đà Nẵng</div>
                            <div class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-gold-400"></i> Tư vấn: <strong class="text-white">0934 825 780</strong></div>
                            <div class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-gold-400"></i> Bảo hành: <strong class="text-white">076 259 8824</strong></div>
                        </div>
                        <div class="flex items-center gap-3">
                            <a href="#san-pham-noi-bat" class="px-5 py-2.5 rounded-lg bg-gold-500 hover:bg-gold-600 text-white font-bold text-xs lg:text-sm transition shadow">
                                XEM KHO ĐÀN NGAY
                            </a>
                            <a href="#form-bao-gia" class="px-5 py-2.5 rounded-lg border border-gold-400 text-gold-300 hover:bg-gold-500/10 font-semibold text-xs lg:text-sm transition">
                                NHẬN BÁO GIÁ TỐT NHẤT
                            </a>
                        </div>
                    </div>
                    <div class="col-span-5 h-full flex items-center justify-center py-6 z-10">
                        <div class="relative w-full h-[310px] rounded-xl overflow-hidden border-2 border-gold-500/40 shadow-2xl bg-black">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1DcEfm21LNh0xgbhkeWvR9z3z8yMbBem1" 
                                alt="Kho đàn Huy Hoàng Piano Đà Nẵng" 
                                class="w-full h-full object-cover"
                                onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1520523839897-bd0b52f945a0?auto=format&fit=crop&w=900&q=80';"
                            >
                            <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/90 via-black/50 to-transparent p-3 text-white text-xs">
                                <div class="font-bold text-gold-300">Showroom: 224 Đường 29 Tháng 3, Hòa Xuân, Đà Nẵng</div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- BANNER ĐIỆN THOẠI 1 (Thiết kế riêng cho Mobile, kích thước cố định 240px, chữ nhỏ nằm gọn 100% trong khung) -->
                <div class="flex md:hidden flex-col justify-between h-[240px] w-full bg-gradient-to-br from-[#141414] via-[#221b10] to-[#302312] p-4 relative overflow-hidden">
                    <div class="z-10">
                        <span class="inline-block px-2 py-0.5 rounded bg-gold-500/20 border border-gold-400/40 text-gold-300 text-[10px] font-semibold mb-1">
                            NHẬP KHẨU TRỰC TIẾP NHẬT BẢN
                        </span>
                        <h2 class="font-heading font-extrabold text-white text-base leading-snug">
                            HUY HOÀNG PIANO ĐÀ NẴNG
                        </h2>
                        <p class="text-gold-200 text-[11px] font-medium leading-snug mt-0.5">
                            Kho đàn Piano cơ - Piano điện, Organ, Guitar nhập từ Nhật Bản. Đảm bảo giá thành tốt nhất thị trường!
                        </p>
                    </div>
                    <div class="z-10 bg-black/45 border border-gold-500/30 rounded-lg p-2 text-[11px] text-gray-200 space-y-0.5">
                        <div class="truncate"><i class="fa-solid fa-location-dot text-gold-400 mr-1"></i>224 Đường 29 Tháng 3, Hòa Xuân, Đà Nẵng</div>
                        <div class="flex items-center justify-between">
                            <span><i class="fa-solid fa-phone text-gold-400 mr-1"></i>Tư vấn: <strong>0934 825 780</strong></span>
                            <span>BH: <strong>076 259 8824</strong></span>
                        </div>
                    </div>
                    <div class="z-10 flex items-center gap-2">
                        <a href="#san-pham-noi-bat" class="px-3 py-1.5 rounded bg-gold-500 text-white font-bold text-[11px]">
                            Xem Kho Đàn
                        </a>
                        <a href="#form-bao-gia" class="px-3 py-1.5 rounded border border-gold-400 text-gold-300 font-semibold text-[11px]">
                            Nhận Báo Giá
                        </a>
                    </div>
                </div>
            </div>

            <!-- ================= SLIDE 2 ================= -->
            <div id="bannerSlide1" class="banner-slide transition-opacity duration-700 hidden opacity-0">
                
                <!-- BANNER MÁY TÍNH 2 (Chiều cao cố định 400px bằng đúng Slide 1) -->
                <div class="hidden md:grid md:grid-cols-12 items-center h-[390px] lg:h-[420px] w-full bg-gradient-to-r from-[#171310] via-[#241c14] to-[#121212] relative overflow-hidden px-8 lg:px-14">
                    <div class="col-span-7 z-10 pr-4">
                        <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-red-600/25 border border-red-400/40 text-red-300 text-xs font-semibold mb-3">
                            <i class="fa-solid fa-fire"></i> ƯU ĐÃI LÊN ĐẾN 20% • BẢO HÀNH &amp; HẬU MÃI TẬN TÂM
                        </div>
                        <h2 class="font-heading font-extrabold text-white text-2xl lg:text-3xl xl:text-4xl leading-tight mb-2.5">
                            PIANO CƠ &amp; PIANO ĐIỆN <span class="text-gold-400">YAMAHA • KAWAI • ROLAND</span>
                        </h2>
                        <p class="text-gray-200 font-medium text-sm lg:text-base mb-3">
                            Đầy đủ phân khúc từ học tập đến biểu diễn chuyên nghiệp • Hỗ trợ trả góp &amp; Kỹ thuật viên bảo dưỡng tận nhà
                        </p>
                        <div class="grid grid-cols-2 gap-2 text-xs text-gray-300 mb-5 max-w-xl">
                            <div class="flex items-center gap-2"><i class="fa-solid fa-check text-gold-400"></i> Tặng trọn bộ phụ kiện chuẩn Nhật</div>
                            <div class="flex items-center gap-2"><i class="fa-solid fa-check text-gold-400"></i> Lên dây &amp; kiểm tra định kỳ</div>
                            <div class="flex items-center gap-2"><i class="fa-solid fa-check text-gold-400"></i> Hotline tư vấn: <strong class="text-white">0934 825 780</strong></div>
                            <div class="flex items-center gap-2"><i class="fa-solid fa-check text-gold-400"></i> Sửa chữa, BH: <strong class="text-white">076 259 8824</strong></div>
                        </div>
                        <div class="flex items-center gap-3">
                            <a href="#san-pham-piano-dien" class="px-5 py-2.5 rounded-lg bg-gold-500 hover:bg-gold-600 text-white font-bold text-xs lg:text-sm transition shadow">
                                KHÁM PHÁ PIANO ĐIỆN &amp; CƠ
                            </a>
                            <a href="#ban-do-showroom" class="px-5 py-2.5 rounded-lg border border-gold-400 text-gold-300 hover:bg-gold-500/10 font-semibold text-xs lg:text-sm transition">
                                XEM ĐỊA CHỈ SHOWROOM
                            </a>
                        </div>
                    </div>
                    <div class="col-span-5 h-full flex items-center justify-center py-6 z-10">
                        <div class="relative w-full h-[310px] rounded-xl overflow-hidden border-2 border-gold-500/40 shadow-2xl bg-black">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1OIDORfA6G5OfHIlwFavTQ-WatxEGxH5S" 
                                alt="Sản phẩm thực tế Huy Hoàng Piano" 
                                class="w-full h-full object-cover"
                                onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=900&q=80';"
                            >
                            <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/90 via-black/50 to-transparent p-3 text-white text-xs">
                                <div class="font-bold text-gold-300">Cam kết giá tốt nhất thị trường • Bảo hành uy tín</div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- BANNER ĐIỆN THOẠI 2 (Kích thước cố định 240px bằng đúng Slide 1 Mobile, chữ nhỏ gọn) -->
                <div class="flex md:hidden flex-col justify-between h-[240px] w-full bg-gradient-to-br from-[#1b1410] via-[#271d12] to-[#141414] p-4 relative overflow-hidden">
                    <div class="z-10">
                        <span class="inline-block px-2 py-0.5 rounded bg-red-500/25 border border-red-400/40 text-red-200 text-[10px] font-semibold mb-1">
                            GIẢM GIÁ TỐT NHẤT THỊ TRƯỜNG
                        </span>
                        <h2 class="font-heading font-extrabold text-white text-base leading-snug">
                            PIANO YAMAHA • KAWAI • ROLAND
                        </h2>
                        <p class="text-gold-200 text-[11px] font-medium leading-snug mt-0.5">
                            Đầy đủ Piano cơ, Piano điện, Organ, Guitar tuyển chọn từ Nhật Bản. Tặng kèm ghế chuẩn &amp; miễn phí giao đàn!
                        </p>
                    </div>
                    <div class="z-10 bg-black/45 border border-gold-500/30 rounded-lg p-2 text-[11px] text-gray-200 space-y-0.5">
                        <div class="truncate"><i class="fa-solid fa-globe text-gold-400 mr-1"></i>Website: <strong>huyhoangpiano.com</strong></div>
                        <div class="flex items-center justify-between">
                            <span><i class="fa-solid fa-headset text-gold-400 mr-1"></i>Tư vấn: <strong>0934 825 780</strong></span>
                            <span>Sửa chữa: <strong>076 259 8824</strong></span>
                        </div>
                    </div>
                    <div class="z-10 flex items-center gap-2">
                        <a href="#san-pham-piano-co" class="px-3 py-1.5 rounded bg-gold-500 text-white font-bold text-[11px]">
                            Xem Ưu Đãi
                        </a>
                        <a href="#ban-do-showroom" class="px-3 py-1.5 rounded border border-gold-400 text-gold-300 font-semibold text-[11px]">
                            Chỉ Đường Map
                        </a>
                    </div>
                </div>
            </div>

            <!-- Nút điều hướng Slider -->
            <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2.5 top-1/2 -translate-y-1/2 w-8 h-8 md:w-10 md:h-10 rounded-full bg-black/40 hover:bg-gold-500 text-white flex items-center justify-center transition z-20">
                <i class="fa-solid fa-chevron-left text-xs md:text-sm"></i>
            </button>
            <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2.5 top-1/2 -translate-y-1/2 w-8 h-8 md:w-10 md:h-10 rounded-full bg-black/40 hover:bg-gold-500 text-white flex items-center justify-center transition z-20">
                <i class="fa-solid fa-chevron-right text-xs md:text-sm"></i>
            </button>

            <!-- Dots chỉ báo Slide -->
            <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                <button id="slideDot0" onclick="goToSlide(0)" class="w-6 h-2 rounded-full bg-gold-400 transition-all"></button>
                <button id="slideDot1" onclick="goToSlide(1)" class="w-2 h-2 rounded-full bg-white/50 transition-all"></button>
            </div>
        </div>
    </section>

    <!-- ==========================================
         BẠN ĐANG CẦN (4 Ô Tác Vụ Nhanh giống mẫu duongpiano.com)
    =========================================== -->
    <section class="flatsome-container py-3">
        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
            <a href="#san-pham-noi-bat" class="bg-white hover:bg-gold-50 border border-gray-200 hover:border-gold-400 rounded-xl p-3.5 md:p-4 flex items-center gap-3 shadow-sm transition group">
                <div class="w-11 h-11 rounded-lg bg-gold-100 text-gold-600 flex items-center justify-center text-lg shrink-0 group-hover:bg-gold-500 group-hover:text-white transition">
                    <i class="fa-solid fa-cart-shopping"></i>
                </div>
                <div>
                    <div class="text-[10px] md:text-xs text-gray-500 font-medium uppercase">Bạn đang cần</div>
                    <div class="font-heading font-bold text-xs md:text-sm text-piano-dark">MUA ĐÀN PIANO</div>
                </div>
            </a>

            <a href="#dich-vu-khoa-hoc" class="bg-white hover:bg-gold-50 border border-gray-200 hover:border-gold-400 rounded-xl p-3.5 md:p-4 flex items-center gap-3 shadow-sm transition group">
                <div class="w-11 h-11 rounded-lg bg-gold-100 text-gold-600 flex items-center justify-center text-lg shrink-0 group-hover:bg-gold-500 group-hover:text-white transition">
                    <i class="fa-solid fa-graduation-cap"></i>
                </div>
                <div>
                    <div class="text-[10px] md:text-xs text-gray-500 font-medium uppercase">Bạn đang cần</div>
                    <div class="font-heading font-bold text-xs md:text-sm text-piano-dark">HỌC ĐÀN PIANO</div>
                </div>
            </a>

            <a href="#form-bao-gia" class="bg-white hover:bg-gold-50 border border-gray-200 hover:border-gold-400 rounded-xl p-3.5 md:p-4 flex items-center gap-3 shadow-sm transition group">
                <div class="w-11 h-11 rounded-lg bg-gold-100 text-gold-600 flex items-center justify-center text-lg shrink-0 group-hover:bg-gold-500 group-hover:text-white transition">
                    <i class="fa-solid fa-screwdriver-wrench"></i>
                </div>
                <div>
                    <div class="text-[10px] md:text-xs text-gray-500 font-medium uppercase">Hotline: 076 259 8824</div>
                    <div class="font-heading font-bold text-xs md:text-sm text-piano-dark">SỬA &amp; BẢO HÀNH</div>
                </div>
            </a>

            <a href="#form-bao-gia" class="bg-white hover:bg-gold-50 border border-gray-200 hover:border-gold-400 rounded-xl p-3.5 md:p-4 flex items-center gap-3 shadow-sm transition group">
                <div class="w-11 h-11 rounded-lg bg-gold-100 text-gold-600 flex items-center justify-center text-lg shrink-0 group-hover:bg-gold-500 group-hover:text-white transition">
                    <i class="fa-solid fa-handshake"></i>
                </div>
                <div>
                    <div class="text-[10px] md:text-xs text-gray-500 font-medium uppercase">Sự kiện &amp; Tại nhà</div>
                    <div class="font-heading font-bold text-xs md:text-sm text-piano-dark">THUÊ ĐÀN PIANO</div>
                </div>
            </a>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM TRANG CHỦ
         Quy tắc: Chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng (whitespace-nowrap), tối ưu đẹp trên cả máy tính và điện thoại
    =========================================== -->
    <section class="flatsome-container py-5">
        <div class="section-title-container">
            <h2 class="section-title">
                <b></b>
                <span class="section-title-main text-base md:text-xl">DANH MỤC SẢN PHẨM</span>
                <b></b>
            </h2>
        </div>

        <!-- Lưới danh mục thiết kế gọn đẹp, tên danh mục giữ trên 1 dòng không bị gãy -->
        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 md:gap-3.5">
            <button onclick="filterCategory('grand')" class="cat-card group bg-white hover:bg-piano-dark border border-gray-200 hover:border-gold-500 rounded-xl p-3 text-center transition shadow-sm flex flex-col items-center justify-center">
                <div class="w-10 h-10 rounded-full bg-gold-100 text-gold-600 flex items-center justify-center mb-2 group-hover:bg-gold-500 group-hover:text-white transition">
                    <i class="fa-solid fa-crown text-sm"></i>
                </div>
                <span class="text-[12px] font-bold text-gray-800 group-hover:text-white whitespace-nowrap">Special Grand Piano</span>
                <span class="text-[10px] text-gray-400 group-hover:text-gold-300 whitespace-nowrap mt-0.5">Yamaha • Kawai • Steinway</span>
            </button>

            <button onclick="filterCategory('upright')" class="cat-card group bg-white hover:bg-piano-dark border border-gray-200 hover:border-gold-500 rounded-xl p-3 text-center transition shadow-sm flex flex-col items-center justify-center">
                <div class="w-10 h-10 rounded-full bg-gold-100 text-gold-600 flex items-center justify-center mb-2 group-hover:bg-gold-500 group-hover:text-white transition">
                    <i class="fa-solid fa-music text-sm"></i>
                </div>
                <span class="text-[12px] font-bold text-gray-800 group-hover:text-white whitespace-nowrap">Upright Piano</span>
                <span class="text-[10px] text-gray-400 group-hover:text-gold-300 whitespace-nowrap mt-0.5">U1 • U2 • U3 • UX • W Series</span>
            </button>

            <button onclick="filterCategory('digital')" class="cat-card group bg-white hover:bg-piano-dark border border-gray-200 hover:border-gold-500 rounded-xl p-3 text-center transition shadow-sm flex flex-col items-center justify-center">
                <div class="w-10 h-10 rounded-full bg-gold-100 text-gold-600 flex items-center justify-center mb-2 group-hover:bg-gold-500 group-hover:text-white transition">
                    <i class="fa-solid fa-sliders text-sm"></i>
                </div>
                <span class="text-[12px] font-bold text-gray-800 group-hover:text-white whitespace-nowrap">Digital Piano</span>
                <span class="text-[10px] text-gray-400 group-hover:text-gold-300 whitespace-nowrap mt-0.5">Yamaha • Roland • Kawai • Casio</span>
            </button>

            <button onclick="filterCategory('organ')" class="cat-card group bg-white hover:bg-piano-dark border border-gray-200 hover:border-gold-500 rounded-xl p-3 text-center transition shadow-sm flex flex-col items-center justify-center">
                <div class="w-10 h-10 rounded-full bg-gold-100 text-gold-600 flex items-center justify-center mb-2 group-hover:bg-gold-500 group-hover:text-white transition">
                    <i class="fa-solid fa-keyboard text-sm"></i>
                </div>
                <span class="text-[12px] font-bold text-gray-800 group-hover:text-white whitespace-nowrap">Đàn Organ Nhật Bản</span>
                <span class="text-[10px] text-gray-400 group-hover:text-gold-300 whitespace-nowrap mt-0.5">Yamaha PSR • Casio • Kurtzman</span>
            </button>

            <button onclick="filterCategory('guitar')" class="cat-card group bg-white hover:bg-piano-dark border border-gray-200 hover:border-gold-500 rounded-xl p-3 text-center transition shadow-sm flex flex-col items-center justify-center">
                <div class="w-10 h-10 rounded-full bg-gold-100 text-gold-600 flex items-center justify-center mb-2 group-hover:bg-gold-500 group-hover:text-white transition">
                    <i class="fa-solid fa-guitar text-sm"></i>
                </div>
                <span class="text-[12px] font-bold text-gray-800 group-hover:text-white whitespace-nowrap">Đàn Guitar Nhật Bản</span>
                <span class="text-[10px] text-gray-400 group-hover:text-gold-300 whitespace-nowrap mt-0.5">Acoustic • Classic • Morris</span>
            </button>

            <button onclick="filterCategory('all')" class="cat-card group bg-white hover:bg-piano-dark border border-gray-200 hover:border-gold-500 rounded-xl p-3 text-center transition shadow-sm flex flex-col items-center justify-center">
                <div class="w-10 h-10 rounded-full bg-gold-100 text-gold-600 flex items-center justify-center mb-2 group-hover:bg-gold-500 group-hover:text-white transition">
                    <i class="fa-solid fa-layer-group text-sm"></i>
                </div>
                <span class="text-[12px] font-bold text-gray-800 group-hover:text-white whitespace-nowrap">Xem Tất Cả Kho Đàn</span>
                <span class="text-[10px] text-gray-400 group-hover:text-gold-300 whitespace-nowrap mt-0.5">Giá tốt nhất thị trường</span>
            </button>
        </div>
    </section>

    <!-- ==========================================
         SECTION 1: SẢN PHẨM NỔI BẬT (KHO ĐÀN THỰC TẾ HUY HOÀNG PIANO)
         - Tích hợp 2 ảnh sản phẩm thực tế từ Google Drive
         - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
         - Chỉ có duy nhất badge % giảm giá góc trên bên trái chuẩn Flatsome, không có nhãn dán phụ
         - Tên sản phẩm hiển thị đầy đủ không bị tràn hay cắt chữ
    =========================================== -->
    <section id="san-pham-noi-bat" class="flatsome-container py-5">
        <div class="section-title-container">
            <h2 class="section-title">
                <b></b>
                <span class="section-title-main text-base md:text-xl">SẢN PHẨM NỔI BẬT</span>
                <b></b>
            </h2>
            <p id="activeFilterNotice" class="text-center text-xs text-gray-500 mt-1">
                Đàn Piano cơ, Piano điện, Organ, Guitar nhập khẩu trực tiếp từ Nhật Bản • Cam kết giá thành tốt nhất thị trường
            </p>
        </div>

        <div id="featuredProductsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-5">
            <!-- Render bằng JS từ dữ liệu chuẩn -->
        </div>
    </section>

    <!-- ==========================================
         SECTION 2: UPRIGHT PIANO & SPECIAL GRAND PIANO NHẬT BẢN
    =========================================== -->
    <section id="san-pham-piano-co" class="flatsome-container py-5">
        <div class="section-title-container">
            <h2 class="section-title">
                <b></b>
                <span class="section-title-main text-base md:text-xl">ĐÀN PIANO CƠ (UPRIGHT &amp; GRAND PIANO)</span>
                <b></b>
            </h2>
        </div>

        <div id="acousticProductsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-5">
            <!-- Render bằng JS -->
        </div>
    </section>

    <!-- ==========================================
         SECTION 3: DIGITAL PIANO (ĐÀN PIANO ĐIỆN NHẬT BẢN)
    =========================================== -->
    <section id="san-pham-piano-dien" class="flatsome-container py-5">
        <div class="section-title-container">
            <h2 class="section-title">
                <b></b>
                <span class="section-title-main text-base md:text-xl">ĐÀN PIANO ĐIỆN (DIGITAL PIANO NHẬT BẢN)</span>
                <b></b>
            </h2>
        </div>

        <div id="digitalProductsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-5">
            <!-- Render bằng JS -->
        </div>
    </section>

    <!-- ==========================================
         SECTION 4: ĐÀN ORGAN & GUITAR NHẬT BẢN
    =========================================== -->
    <section id="san-pham-organ-guitar" class="flatsome-container py-5">
        <div class="section-title-container">
            <h2 class="section-title">
                <b></b>
                <span class="section-title-main text-base md:text-xl">ĐÀN ORGAN &amp; GUITAR NHẬT BẢN</span>
                <b></b>
            </h2>
        </div>

        <div id="organGuitarProductsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-5">
            <!-- Render bằng JS -->
        </div>
    </section>

    <!-- ==========================================
         SECTION 5: DỊCH VỤ (SERVICE) & KHÓA HỌC ĐÀO TẠO
    =========================================== -->
    <section id="dich-vu-khoa-hoc" class="flatsome-container py-6">
        <div class="section-title-container">
            <h2 class="section-title">
                <b></b>
                <span class="section-title-main text-base md:text-xl">DỊCH VỤ CHUYÊN NGHIỆP &amp; KHÓA HỌC ĐÀN</span>
                <b></b>
            </h2>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
            <div class="bg-white rounded-xl border border-gray-200 p-5 shadow-sm flex flex-col justify-between">
                <div>
                    <div class="w-11 h-11 rounded-lg bg-gold-100 text-gold-600 flex items-center justify-center text-lg mb-3">
                        <i class="fa-solid fa-screwdriver-wrench"></i>
                    </div>
                    <h3 class="font-heading font-bold text-sm md:text-base text-piano-dark mb-1.5">Bảo Hành &amp; Sửa Chữa Piano</h3>
                    <p class="text-xs text-gray-600 leading-relaxed">
                        Đội ngũ kỹ thuật viên giàu kinh nghiệm chuyên căn chỉnh máy cơ, xử lý kẹt phím, thay búa dạ và sửa bo mạch Piano điện, Organ tận nhà.
                    </p>
                </div>
                <div class="mt-4 pt-3 border-t border-gray-100 text-xs font-bold text-gold-700">
                    Hotline Kỹ Thuật: <a href="tel:0762598824" class="underline">076 259 8824</a>
                </div>
            </div>

            <div class="bg-white rounded-xl border border-gray-200 p-5 shadow-sm flex flex-col justify-between">
                <div>
                    <div class="w-11 h-11 rounded-lg bg-gold-100 text-gold-600 flex items-center justify-center text-lg mb-3">
                        <i class="fa-solid fa-sliders"></i>
                    </div>
                    <h3 class="font-heading font-bold text-sm md:text-base text-piano-dark mb-1.5">Lên Dây &amp; Bảo Dưỡng Định Kỳ</h3>
                    <p class="text-xs text-gray-600 leading-relaxed">
                        Dịch vụ lên dây chuẩn tần số quốc tế 440Hz cho Upright Piano và Grand Piano tại Đà Nẵng &amp; Hội An, vệ sinh bảo quản ống sưởi.
                    </p>
                </div>
                <div class="mt-4 pt-3 border-t border-gray-100 text-xs font-bold text-gold-700">
                    Đặt lịch nhanh: <a href="tel:0762598824" class="underline">076 259 8824</a>
                </div>
            </div>

            <div class="bg-white rounded-xl border border-gray-200 p-5 shadow-sm flex flex-col justify-between">
                <div>
                    <div class="w-11 h-11 rounded-lg bg-gold-100 text-gold-600 flex items-center justify-center text-lg mb-3">
                        <i class="fa-solid fa-truck-fast"></i>
                    </div>
                    <h3 class="font-heading font-bold text-sm md:text-base text-piano-dark mb-1.5">Cho Thuê &amp; Vận Chuyển Piano</h3>
                    <p class="text-xs text-gray-600 leading-relaxed">
                        Nhận vận chuyển đàn Piano chuyên nghiệp toàn quốc, miễn phí vận chuyển nội thành Đà Nẵng và cho thuê đàn sự kiện, cưới hỏi.
                    </p>
                </div>
                <div class="mt-4 pt-3 border-t border-gray-100 text-xs font-bold text-gold-700">
                    Tư vấn dịch vụ: <a href="tel:0934825780" class="underline">0934 825 780</a>
                </div>
            </div>

            <div class="bg-white rounded-xl border border-gray-200 p-5 shadow-sm flex flex-col justify-between">
                <div>
                    <div class="w-11 h-11 rounded-lg bg-gold-100 text-gold-600 flex items-center justify-center text-lg mb-3">
                        <i class="fa-solid fa-graduation-cap"></i>
                    </div>
                    <h3 class="font-heading font-bold text-sm md:text-base text-piano-dark mb-1.5">Đào Tạo Piano - Organ - Guitar</h3>
                    <p class="text-xs text-gray-600 leading-relaxed">
                        Chiêu sinh liên tục các lớp Piano cổ điển, Piano đệm hát, Organ và Guitar cho mọi lứa tuổi với lịch học linh hoạt tại Hòa Xuân, Đà Nẵng.
                    </p>
                </div>
                <div class="mt-4 pt-3 border-t border-gray-100 text-xs font-bold text-gold-700">
                    Đăng ký học thử: <a href="tel:0934825780" class="underline">0934 825 780</a>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 6: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
    =========================================== -->
    <section id="form-bao-gia" class="flatsome-container py-6">
        <div class="bg-gradient-to-br from-piano-dark via-[#1d1812] to-piano-charcoal text-white rounded-2xl p-5 md:p-8 lg:p-10 shadow-lg border border-gold-700/40">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                
                <!-- Thông tin cam kết bên trái -->
                <div class="lg:col-span-5 space-y-4">
                    <span class="inline-block px-3 py-1 rounded-full bg-gold-500/20 border border-gold-400/40 text-gold-300 text-xs font-semibold">
                        BÁO GIÁ SỈ &amp; LẺ TỐT NHẤT THỊ TRƯỜNG
                    </span>
                    <h2 class="font-heading font-extrabold text-xl md:text-2xl lg:text-3xl text-white leading-tight">
                        YÊU CẦU TƯ VẤN &amp; NHẬN BÁO GIÁ ƯU ĐÃI
                    </h2>
                    <p class="text-xs md:text-sm text-gray-300 leading-relaxed">
                        Để lại thông tin nhu cầu của bạn, chuyên viên tại <strong>Huy Hoàng Piano Đà Nẵng</strong> sẽ gửi hình ảnh/video test âm thực tế từng cây đàn tại kho kèm báo giá chiết khấu tốt nhất trong 5 phút!
                    </p>
                    <div class="space-y-2.5 pt-2 text-xs md:text-sm">
                        <div class="flex items-center gap-3">
                            <span class="w-8 h-8 rounded-lg bg-gold-500/20 text-gold-400 flex items-center justify-center shrink-0"><i class="fa-solid fa-phone-volume"></i></span>
                            <div>Hotline tư vấn: <a href="tel:0934825780" class="font-bold text-gold-400 hover:underline">0934 825 780</a></div>
                        </div>
                        <div class="flex items-center gap-3">
                            <span class="w-8 h-8 rounded-lg bg-gold-500/20 text-gold-400 flex items-center justify-center shrink-0"><i class="fa-solid fa-wrench"></i></span>
                            <div>Bảo hành, sửa chữa: <a href="tel:0762598824" class="font-bold text-gold-400 hover:underline">076 259 8824</a></div>
                        </div>
                        <div class="flex items-center gap-3">
                            <span class="w-8 h-8 rounded-lg bg-gold-500/20 text-gold-400 flex items-center justify-center shrink-0"><i class="fa-solid fa-location-dot"></i></span>
                            <div>Showroom: <strong>224 Đường 29 Tháng 3, Phường Hòa Xuân, Đà Nẵng</strong></div>
                        </div>
                    </div>
                </div>

                <!-- Form nhập liệu bên phải -->
                <div class="lg:col-span-7 bg-white text-gray-800 rounded-xl p-5 md:p-6 shadow-xl">
                    <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Họ và tên quý khách *</label>
                                <input id="quoteName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3.5 py-2.5 text-xs md:text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-gold-500">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="quotePhone" type="tel" required placeholder="Ví dụ: 0934 825 780" class="w-full px-3.5 py-2.5 text-xs md:text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-gold-500">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Dòng sản phẩm / Dịch vụ quan tâm</label>
                                <select id="quoteCategory" class="w-full px-3.5 py-2.5 text-xs md:text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-gold-500 bg-white">
                                    <option value="Đàn Piano Cơ (Upright / Grand)">Đàn Piano Cơ (Upright / Grand Nhật Bản)</option>
                                    <option value="Đàn Piano Điện (Yamaha / Roland / Kawai)">Đàn Piano Điện (Yamaha / Roland / Kawai / Casio)</option>
                                    <option value="Đàn Organ Nhật Bản">Đàn Organ Nhật Bản</option>
                                    <option value="Đàn Guitar Acoustic / Classic">Đàn Guitar Acoustic / Classic</option>
                                    <option value="Bảo hành - Sửa chữa - Lên dây Piano">Bảo hành - Sửa chữa - Lên dây Piano</option>
                                    <option value="Đăng ký khóa học Piano / Organ / Guitar">Đăng ký khóa học Piano / Organ / Guitar</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Mức ngân sách dự kiến</label>
                                <select id="quoteBudget" class="w-full px-3.5 py-2.5 text-xs md:text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-gold-500 bg-white">
                                    <option value="Dưới 10 triệu">Dưới 10 triệu</option>
                                    <option value="Từ 10 - 20 triệu">Từ 10 - 20 triệu</option>
                                    <option value="Từ 20 - 45 triệu">Từ 20 - 45 triệu</option>
                                    <option value="Trên 45 triệu (Piano Cơ / Grand)">Trên 45 triệu (Piano Cơ Cao Cấp / Grand)</option>
                                    <option value="Cần tư vấn báo giá chi tiết">Cần tư vấn báo giá chi tiết</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-gray-700 mb-1">Model đàn hoặc yêu cầu chi tiết</label>
                            <textarea id="quoteNote" rows="2" placeholder="Ví dụ: Báo giá đàn Yamaha U3H, Yamaha CLP-535 hoặc đặt lịch sửa đàn tại nhà..." class="w-full px-3.5 py-2 text-xs md:text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-gold-500"></textarea>
                        </div>

                        <button type="submit" class="w-full py-3 rounded-lg bg-gold-500 hover:bg-gold-600 text-white font-heading font-bold text-xs md:text-sm uppercase tracking-wider transition shadow-md">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU &amp; NHẬN BÁO GIÁ NGAY
                        </button>
                    </form>

                    <!-- Hộp thông báo xác nhận gửi thành công (Thay cho alert) -->
                    <div id="quoteSuccessBox" class="hidden mt-3 p-3.5 rounded-lg bg-green-50 border border-green-300 text-green-800 text-xs">
                        <div class="font-bold flex items-center gap-1.5 mb-1">
                            <i class="fa-solid fa-circle-check text-green-600"></i> Đã ghi nhận yêu cầu báo giá thành công!
                        </div>
                        <p id="quoteSuccessText"></p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 7: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KIẾN THỨC PIANO)
    =========================================== -->
    <section id="tin-tuc-piano" class="flatsome-container py-6">
        <div class="section-title-container">
            <h2 class="section-title">
                <b></b>
                <span class="section-title-main text-base md:text-xl">TIN TỨC &amp; CẨM NANG CHỌN ĐÀN PIANO</span>
                <b></b>
            </h2>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 md:gap-5">
            <!-- Bài viết 1 -->
            <article class="bg-white rounded-xl overflow-hidden border border-gray-200 shadow-sm hover:shadow-md transition flex flex-col">
                <div class="relative h-44 overflow-hidden bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1DcEfm21LNh0xgbhkeWvR9z3z8yMbBem1" alt="Kinh nghiệm chọn mua đàn Piano Nhật Bản" class="w-full h-full object-cover hover:scale-105 transition duration-500" onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1520523839897-bd0b52f945a0?auto=format&fit=crop&w=600&q=80';">
                    <div class="absolute top-2.5 left-2.5 bg-piano-dark/90 text-gold-400 text-[10px] font-bold px-2.5 py-1 rounded">
                        TƯ VẤN CHỌN ĐÀN
                    </div>
                </div>
                <div class="p-4 flex-1 flex flex-col justify-between">
                    <div>
                        <h3 class="font-bold text-sm text-gray-900 hover:text-gold-600 transition leading-snug mb-2">
                            Cách Chọn Đàn Piano Cơ &amp; Piano Điện Nội Địa Nhật Bản Bền Đẹp Giá Tốt Nhất
                        </h3>
                        <p class="text-xs text-gray-600 leading-relaxed">
                            Hướng dẫn kiểm tra soundboard, búa đàn, độ nặng bàn phím GH3/Wooden Key và số serial khi chọn mua đàn tại kho Đà Nẵng.
                        </p>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-gray-100 flex items-center justify-between text-[11px] text-gray-500">
                        <span><i class="fa-regular fa-calendar mr-1"></i>Huy Hoàng Piano</span>
                        <a href="#form-bao-gia" class="text-gold-600 font-semibold hover:underline">Xem chi tiết →</a>
                    </div>
                </div>
            </article>

            <!-- Bài viết 2 -->
            <article class="bg-white rounded-xl overflow-hidden border border-gray-200 shadow-sm hover:shadow-md transition flex flex-col">
                <div class="relative h-44 overflow-hidden bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1OIDORfA6G5OfHIlwFavTQ-WatxEGxH5S" alt="Top mẫu đàn Piano điện dưới 10 triệu - 15 triệu" class="w-full h-full object-cover hover:scale-105 transition duration-500" onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=600&q=80';">
                    <div class="absolute top-2.5 left-2.5 bg-piano-dark/90 text-gold-400 text-[10px] font-bold px-2.5 py-1 rounded">
                        TOP PIANO ĐIỆN
                    </div>
                </div>
                <div class="p-4 flex-1 flex flex-col justify-between">
                    <div>
                        <h3 class="font-bold text-sm text-gray-900 hover:text-gold-600 transition leading-snug mb-2">
                            Top 10 Mẫu Đàn Piano Điện Nhật Bản Dưới 10 - 15 Triệu Đáng Mua Nhất Hiện Nay
                        </h3>
                        <p class="text-xs text-gray-600 leading-relaxed">
                            Tổng hợp các dòng Yamaha Clavinova CLP, Arius YDP, Roland HP, Kawai và Casio Privia nhỏ gọn, âm thanh chuẩn cho người mới.
                        </p>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-gray-100 flex items-center justify-between text-[11px] text-gray-500">
                        <span><i class="fa-regular fa-calendar mr-1"></i>Huy Hoàng Piano</span>
                        <a href="#san-pham-piano-dien" class="text-gold-600 font-semibold hover:underline">Xem chi tiết →</a>
                    </div>
                </div>
            </article>

            <!-- Bài viết 3 -->
            <article class="bg-white rounded-xl overflow-hidden border border-gray-200 shadow-sm hover:shadow-md transition flex flex-col">
                <div class="relative h-44 overflow-hidden bg-gray-100">
                    <img src="https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?auto=format&fit=crop&w=600&q=80" alt="Tra cứu năm sản xuất đàn Piano Yamaha Kawai" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    <div class="absolute top-2.5 left-2.5 bg-piano-dark/90 text-gold-400 text-[10px] font-bold px-2.5 py-1 rounded">
                        KIẾN THỨC PIANO
                    </div>
                </div>
                <div class="p-4 flex-1 flex flex-col justify-between">
                    <div>
                        <h3 class="font-bold text-sm text-gray-900 hover:text-gold-600 transition leading-snug mb-2">
                            Bảng Tra Cứu Năm Sản Xuất Đàn Piano Cơ &amp; Điện Yamaha, Kawai Chính Xác
                        </h3>
                        <p class="text-xs text-gray-600 leading-relaxed">
                            Cách kiểm tra số Serial và Model đàn Piano cơ Yamaha U1, U3, W102 và Kawai BL để biết chính xác năm xuất xưởng tại Nhật Bản.
                        </p>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-gray-100 flex items-center justify-between text-[11px] text-gray-500">
                        <span><i class="fa-regular fa-calendar mr-1"></i>Huy Hoàng Piano</span>
                        <a href="#form-bao-gia" class="text-gold-600 font-semibold hover:underline">Xem chi tiết →</a>
                    </div>
                </div>
            </article>

            <!-- Bài viết 4 -->
            <article class="bg-white rounded-xl overflow-hidden border border-gray-200 shadow-sm hover:shadow-md transition flex flex-col">
                <div class="relative h-44 overflow-hidden bg-gray-100">
                    <img src="https://images.unsplash.com/photo-1514119412350-e174d90d280e?auto=format&fit=crop&w=600&q=80" alt="Quy trình bảo hành và bảo quản đàn Piano" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    <div class="absolute top-2.5 left-2.5 bg-piano-dark/90 text-gold-400 text-[10px] font-bold px-2.5 py-1 rounded">
                        CHÍNH SÁCH HẬU MÃI
                    </div>
                </div>
                <div class="p-4 flex-1 flex flex-col justify-between">
                    <div>
                        <h3 class="font-bold text-sm text-gray-900 hover:text-gold-600 transition leading-snug mb-2">
                            Quy Trình Bàn Giao, Bảo Hành &amp; Chăm Sóc Định Kỳ Tại Huy Hoàng Piano Đà Nẵng
                        </h3>
                        <p class="text-xs text-gray-600 leading-relaxed">
                            Cam kết đồng hành lâu dài cùng khách hàng với đội ngũ kỹ thuật viên trực tiếp bảo dưỡng, sửa chữa qua số 076 259 8824.
                        </p>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-gray-100 flex items-center justify-between text-[11px] text-gray-500">
                        <span><i class="fa-regular fa-calendar mr-1"></i>Huy Hoàng Piano</span>
                        <a href="#dich-vu-khoa-hoc" class="text-gold-600 font-semibold hover:underline">Xem chi tiết →</a>
                    </div>
                </div>
            </article>
        </div>
    </section>

    <!-- ==========================================
         SECTION 8: DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU
    =========================================== -->
    <section id="doi-tac-thuong-hieu" class="flatsome-container py-6">
        <div class="section-title-container">
            <h2 class="section-title">
                <b></b>
                <span class="section-title-main text-base md:text-xl">ĐỐI TÁC THƯƠNG HIỆU CỦA CHÚNG TÔI</span>
                <b></b>
            </h2>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 md:gap-3">
            <div class="bg-white border border-gray-200 rounded-xl py-3.5 px-3 text-center shadow-sm hover:border-gold-500 transition">
                <div class="font-heading font-extrabold text-sm md:text-base text-piano-dark tracking-wider">YAMAHA</div>
                <div class="text-[10px] text-gray-400 mt-0.5">Japan</div>
            </div>
            <div class="bg-white border border-gray-200 rounded-xl py-3.5 px-3 text-center shadow-sm hover:border-gold-500 transition">
                <div class="font-heading font-extrabold text-sm md:text-base text-piano-dark tracking-wider">KAWAI</div>
                <div class="text-[10px] text-gray-400 mt-0.5">Japan</div>
            </div>
            <div class="bg-white border border-gray-200 rounded-xl py-3.5 px-3 text-center shadow-sm hover:border-gold-500 transition">
                <div class="font-heading font-extrabold text-sm md:text-base text-piano-dark tracking-wider">ROLAND</div>
                <div class="text-[10px] text-gray-400 mt-0.5">Japan</div>
            </div>
            <div class="bg-white border border-gray-200 rounded-xl py-3.5 px-3 text-center shadow-sm hover:border-gold-500 transition">
                <div class="font-heading font-extrabold text-sm md:text-base text-piano-dark tracking-wider">STEINWAY</div>
                <div class="text-[10px] text-gray-400 mt-0.5">Germany / USA</div>
            </div>
            <div class="bg-white border border-gray-200 rounded-xl py-3.5 px-3 text-center shadow-sm hover:border-gold-500 transition">
                <div class="font-heading font-extrabold text-sm md:text-base text-piano-dark tracking-wider">CASIO</div>
                <div class="text-[10px] text-gray-400 mt-0.5">Japan</div>
            </div>
            <div class="bg-white border border-gray-200 rounded-xl py-3.5 px-3 text-center shadow-sm hover:border-gold-500 transition">
                <div class="font-heading font-extrabold text-sm md:text-base text-piano-dark tracking-wider">KORG</div>
                <div class="text-[10px] text-gray-400 mt-0.5">Japan</div>
            </div>
            <div class="bg-white border border-gray-200 rounded-xl py-3.5 px-3 text-center shadow-sm hover:border-gold-500 transition">
                <div class="font-heading font-extrabold text-sm md:text-base text-piano-dark tracking-wider">APOLLO</div>
                <div class="text-[10px] text-gray-400 mt-0.5">Toyo Japan</div>
            </div>
            <div class="bg-white border border-gray-200 rounded-xl py-3.5 px-3 text-center shadow-sm hover:border-gold-500 transition">
                <div class="font-heading font-extrabold text-sm md:text-base text-piano-dark tracking-wider">DIAPASON</div>
                <div class="text-[10px] text-gray-400 mt-0.5">Hamamatsu Japan</div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 9: ĐƯA FANPAGE FACEBOOK & GOOGLE MAP RA NGOÀI TRANG CHỦ
    =========================================== -->
    <section id="ban-do-showroom" class="flatsome-container py-6">
        <div class="section-title-container">
            <h2 class="section-title">
                <b></b>
                <span class="section-title-main text-base md:text-xl">SHOWROOM GOOGLE MAP &amp; FANPAGE HUY HOÀNG PIANO</span>
                <b></b>
            </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
            
            <!-- Cột Google Map ngoài trang chủ (7 cột) -->
            <div class="lg:col-span-7 bg-white rounded-xl border border-gray-200 p-4 shadow-sm flex flex-col justify-between">
                <div>
                    <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                        <div>
                            <h3 class="font-heading font-bold text-sm md:text-base text-piano-dark flex items-center gap-2">
                                <i class="fa-solid fa-map-location-dot text-gold-600"></i>
                                BẢN ĐỒ ĐƯỜNG ĐI ĐẾN HUY HOÀNG PIANO ĐÀ NẴNG
                            </h3>
                            <p class="text-xs text-gray-600 mt-0.5">
                                Địa chỉ: <strong>224 Đường 29 Tháng 3, Phường Hòa Xuân, Đà Nẵng</strong>
                            </p>
                        </div>
                        <a href="https://share.google/C1mZXri8HNxN8ZDpM" target="_blank" rel="noopener" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-gold-500 hover:bg-gold-600 text-white text-xs font-semibold transition">
                            <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps Lớn
                        </a>
                    </div>

                    <div class="w-full h-[290px] md:h-[340px] rounded-lg overflow-hidden border border-gray-200 bg-gray-100">
                        <iframe 
                            title="Bản đồ Huy Hoàng Piano 224 Đường 29 Tháng 3, Phường Hòa Xuân, Đà Nẵng"
                            src="https://maps.google.com/maps?q=Huy%20Ho%C3%A0ng%20Piano%20224%20%C4%90%C6%B0%E1%BB%9Dng%2029%20Th%C3%A1ng%203,%20Ph%C6%B0%E1%BB%9Dng%20H%C3%B2a%20Xu%C3%A2n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                            class="w-full h-full border-0" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <div class="mt-3 pt-3 border-t border-gray-100 flex flex-wrap items-center justify-between gap-2 text-xs text-gray-600">
                    <span><i class="fa-solid fa-phone text-gold-600 mr-1"></i>Hotline tư vấn: <strong class="text-gray-900">0934 825 780</strong></span>
                    <span><i class="fa-solid fa-screwdriver-wrench text-gold-600 mr-1"></i>Bảo hành, sửa chữa: <strong class="text-gray-900">076 259 8824</strong></span>
                </div>
            </div>

            <!-- Cột Fanpage Facebook ngoài trang chủ (5 cột) -->
            <div class="lg:col-span-5 bg-white rounded-xl border border-gray-200 p-4 shadow-sm flex flex-col justify-between">
                <div>
                    <div class="flex items-center justify-between gap-2 mb-3">
                        <div>
                            <h3 class="font-heading font-bold text-sm md:text-base text-piano-dark flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600"></i>
                                FANPAGE HUY HOÀNG PIANO
                            </h3>
                            <p class="text-xs text-gray-600 mt-0.5">
                                Cập nhật video test đàn và hình ảnh bàn giao khách hàng mỗi ngày
                            </p>
                        </div>
                        <a href="https://www.facebook.com/huyhoangpianodanang" target="_blank" rel="noopener" class="inline-flex items-center gap-1 px-3 py-1.5 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-xs font-semibold transition shrink-0">
                            <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i> Theo Dõi
                        </a>
                    </div>

                    <!-- Nhúng Facebook Page Plugin chính thức -->
                    <div class="w-full flex justify-center overflow-hidden rounded-lg border border-gray-200 bg-gray-50 p-1">
                        <iframe 
                            title="Fanpage Huy Hoàng Piano Đà Nẵng"
                            src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fhuyhoangpianodanang&tabs=timeline&width=380&height=300&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                            width="380" 
                            height="300" 
                            style="border:none;overflow:hidden;max-width:100%;" 
                            scrolling="no" 
                            frameborder="0" 
                            allowfullscreen="true" 
                            allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                        </iframe>
                    </div>
                </div>

                <div class="mt-3 pt-3 border-t border-gray-100 flex items-center justify-between text-xs">
                    <span class="text-gray-600 truncate">facebook.com/huyhoangpianodanang</span>
                    <a href="https://www.facebook.com/huyhoangpianodanang" target="_blank" rel="noopener" class="text-blue-600 font-bold hover:underline shrink-0">Nhắn tin Fanpage →</a>
                </div>
            </div>

        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME
    =========================================== -->
    <footer class="bg-piano-dark text-gray-300 border-t-4 border-gold-500 mt-8">
        <div class="flatsome-container py-10">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8">
                
                <!-- Cột 1: Thông tin Huy Hoàng Piano (5 cột) -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-lg overflow-hidden border border-gold-400 bg-black flex items-center justify-center shrink-0">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1uwQg5nGLdpcyN9Xbx3L3KBc9RmwJ-ETG" 
                                alt="Logo Huy Hoàng Piano" 
                                class="w-full h-full object-contain"
                                onerror="this.style.display='none'"
                            >
                        </div>
                        <div>
                            <h3 class="font-heading font-extrabold text-base text-white">HUY HOÀNG <span class="text-gold-400">PIANO</span></h3>
                            <p class="text-xs text-gold-300">Website chính thức: huyhoangpiano.com</p>
                        </div>
                    </div>
                    <p class="text-xs text-gray-400 leading-relaxed">
                        Kho đàn Piano cơ - Piano điện, Organ, Guitar nhập khẩu trực tiếp từ Nhật Bản. Đảm bảo giá thành tốt nhất thị trường, nguyên bản tuyển chọn, bảo hành và hậu mãi tận tâm tại Đà Nẵng &amp; toàn quốc.
                    </p>
                    <ul class="space-y-2 text-xs text-gray-300 pt-1">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-gold-400 mt-1"></i>
                            <span><strong>Địa chỉ:</strong> 224 Đường 29 Tháng 3, Phường Hòa Xuân, Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone-volume text-gold-400"></i>
                            <span><strong>Hotline tư vấn:</strong> <a href="tel:0934825780" class="text-gold-400 font-bold hover:underline">0934 825 780</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-screwdriver-wrench text-gold-400"></i>
                            <span><strong>Bảo hành, sửa chữa:</strong> <a href="tel:0762598824" class="text-gold-400 font-bold hover:underline">076 259 8824</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-brands fa-facebook text-gold-400"></i>
                            <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/huyhoangpianodanang" target="_blank" rel="noopener" class="hover:text-gold-400 underline">facebook.com/huyhoangpianodanang</a></span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm (3 cột) -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="font-heading font-bold text-sm text-white uppercase tracking-wider border-b border-gold-500/40 pb-2">
                        DANH MỤC SẢN PHẨM
                    </h4>
                    <ul class="space-y-2 text-xs text-gray-300">
                        <li><a href="#san-pham-piano-co" onclick="filterCategory('grand')" class="hover:text-gold-400 transition">• Special Grand Piano Nhật Bản</a></li>
                        <li><a href="#san-pham-piano-co" onclick="filterCategory('upright')" class="hover:text-gold-400 transition">• Upright Piano Yamaha &amp; Kawai</a></li>
                        <li><a href="#san-pham-piano-dien" onclick="filterCategory('digital')" class="hover:text-gold-400 transition">• Digital Piano (Đàn Piano Điện)</a></li>
                        <li><a href="#san-pham-organ-guitar" onclick="filterCategory('organ')" class="hover:text-gold-400 transition">• Đàn Organ Nhật Bản Tuyển Chọn</a></li>
                        <li><a href="#san-pham-organ-guitar" onclick="filterCategory('guitar')" class="hover:text-gold-400 transition">• Đàn Guitar Acoustic &amp; Classic</a></li>
                        <li><a href="#dich-vu-khoa-hoc" class="hover:text-gold-400 transition">• Dịch Vụ Sửa Chữa &amp; Lên Dây Piano</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách & Hỗ trợ khách hàng (4 cột) -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h4 class="font-heading font-bold text-sm text-white uppercase tracking-wider border-b border-gold-500/40 pb-2">
                        THÔNG TIN &amp; CHÍNH SÁCH
                    </h4>
                    <ul class="space-y-2 text-xs text-gray-300">
                        <li><a href="#form-bao-gia" class="hover:text-gold-400 transition">• Chính sách bảo hành &amp; bảo dưỡng định kỳ</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-gold-400 transition">• Chính sách vận chuyển miễn phí Đà Nẵng</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-gold-400 transition">• Chính sách nâng cấp &amp; thu đổi đàn Piano</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-gold-400 transition">• Hướng dẫn thanh toán &amp; hỗ trợ trả góp</a></li>
                        <li><a href="https://share.google/C1mZXri8HNxN8ZDpM" target="_blank" rel="noopener" class="hover:text-gold-400 transition">• Chỉ đường Google Maps đến Kho Đàn</a></li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- Bản quyền dưới cùng -->
        <div class="bg-black/60 py-3.5 text-center text-xs text-gray-400 border-t border-white/10">
            <div class="flatsome-container flex flex-col sm:flex-row items-center justify-between gap-2">
                <span>Copyright 2026 © <strong class="text-gold-400">HUY HOÀNG PIANO (huyhoangpiano.com)</strong> - Kho Đàn Nhập Khẩu Nhật Bản.</span>
                <span>Địa chỉ: 224 Đường 29 Tháng 3, Hòa Xuân, Đà Nẵng</span>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE TƯ VẤN & BẢO HÀNH)
         Tương thích hoàn hảo trên cả máy tính và điện thoại, không làm tràn viền
    =========================================== -->
    <div class="fixed bottom-4 right-3 md:right-5 z-40 flex flex-col items-end gap-2.5">
        
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/huyhoangpianodanang" target="_blank" rel="noopener" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition group">
            <i class="fa-brands fa-facebook-messenger text-base md:text-lg"></i>
            <span class="text-[11px] md:text-xs font-bold pr-1">Fanpage</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0934825780" target="_blank" rel="noopener" class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition group">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center">Z</span>
            <span class="text-[11px] md:text-xs font-bold pr-1">Zalo: 0934 825 780</span>
        </a>

        <!-- Nút Bảo hành sửa chữa -->
        <a href="tel:0762598824" class="flex items-center gap-2 bg-piano-charcoal hover:bg-black text-gold-300 border border-gold-500/50 px-3 py-2 rounded-full shadow-lg transition">
            <i class="fa-solid fa-screwdriver-wrench text-xs md:text-sm text-gold-400"></i>
            <span class="text-[11px] md:text-xs font-bold">BH: 076 259 8824</span>
        </a>

        <!-- Nút Hotline Tư Vấn chính -->
        <a href="tel:0934825780" class="pulse-btn flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition">
            <i class="fa-solid fa-phone-volume text-sm md:text-base"></i>
            <span class="text-xs md:text-sm font-extrabold">0934 825 780</span>
        </a>
    </div>

    <!-- ==========================================
         MODAL XEM NHANH & ĐẶT MUA SẢN PHẨM (Thay cho alert)
    =========================================== -->
    <div id="productModal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-2xl max-w-lg w-full overflow-hidden shadow-2xl border border-gray-200 relative">
            <button onclick="closeProductModal()" class="absolute top-3 right-3 w-8 h-8 rounded-full bg-gray-100 hover:bg-gray-200 text-gray-700 flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div class="p-5">
                <div class="text-xs font-bold text-gold-600 uppercase mb-1" id="modalProductCategory">HUY HOÀNG PIANO ĐÀ NẴNG</div>
                <h3 id="modalProductName" class="font-heading font-bold text-base md:text-lg text-piano-dark mb-2"></h3>
                <div class="flex items-center gap-3 mb-4">
                    <del id="modalOldPrice" class="text-xs md:text-sm text-gray-400"></del>
                    <span id="modalNewPrice" class="text-base md:text-lg font-extrabold text-piano-red"></span>
                    <span id="modalDiscountBadge" class="px-2 py-0.5 rounded bg-red-100 text-red-700 font-bold text-xs"></span>
                </div>
                <p class="text-xs text-gray-600 leading-relaxed mb-4">
                    Sản phẩm nhập khẩu trực tiếp từ Nhật Bản, hiện đang có sẵn tại kho <strong>Huy Hoàng Piano (224 Đường 29 Tháng 3, Phường Hòa Xuân, Đà Nẵng)</strong>. Quý khách có thể gọi trực tiếp hoặc nhấn gửi yêu cầu để nhận video test âm thực tế.
                </p>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs font-bold">
                    <a href="tel:0934825780" class="py-2.5 px-4 rounded-lg bg-gold-500 hover:bg-gold-600 text-white text-center">
                        <i class="fa-solid fa-phone mr-1"></i> Gọi Tư Vấn: 0934 825 780
                    </a>
                    <a href="https://zalo.me/0934825780" target="_blank" rel="noopener" class="py-2.5 px-4 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-center">
                        <i class="fa-solid fa-comment-dots mr-1"></i> Nhắn Zalo Xem Video Đàn
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU SẢN PHẨM, SLIDER & TÌM KIẾM
    =========================================== -->
    <script>
        /* Danh sách sản phẩm chuẩn thực tế từ Kho Đàn Huy Hoàng Piano & mẫu duongpiano.com
           Sử dụng ảnh thực tế từ 2 file Google Drive của khách hàng làm sản phẩm chủ lực */
        const productsData = [
            // --- 8 SẢN PHẨM NỔI BẬT ---
            {
                id: 1,
                name: "Đàn Upright Piano Yamaha U3H Nhật Bản (Ảnh Thực Tế Tại Kho)",
                category: "upright",
                categoryLabel: "Upright Piano",
                oldPrice: "49.000.000 ₫",
                newPrice: "41.500.000 ₫",
                discount: "-15%",
                image: "https://lh3.googleusercontent.com/d/1DcEfm21LNh0xgbhkeWvR9z3z8yMbBem1",
                fallbackImage: "https://images.unsplash.com/photo-1520523839897-bd0b52f945a0?auto=format&fit=crop&w=700&q=80",
                featured: true
            },
            {
                id: 2,
                name: "Đàn Piano Điện Yamaha Clavinova CLP-535WA Nội Địa Nhật (Ảnh Thực Tế)",
                category: "digital",
                categoryLabel: "Digital Piano",
                oldPrice: "25.500.000 ₫",
                newPrice: "20.500.000 ₫",
                discount: "-20%",
                image: "https://lh3.googleusercontent.com/d/1OIDORfA6G5OfHIlwFavTQ-WatxEGxH5S",
                fallbackImage: "https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=700&q=80",
                featured: true
            },
            {
                id: 3,
                name: "Đàn Upright Piano Yamaha U1G (Serial 2.0 Nhật Bản Tuyển Chọn)",
                category: "upright",
                categoryLabel: "Upright Piano",
                oldPrice: "44.500.000 ₫",
                newPrice: "35.800.000 ₫",
                discount: "-20%",
                image: "https://lh3.googleusercontent.com/d/1DcEfm21LNh0xgbhkeWvR9z3z8yMbBem1",
                fallbackImage: "https://images.unsplash.com/photo-1520523839897-bd0b52f945a0?auto=format&fit=crop&w=700&q=80",
                featured: true
            },
            {
                id: 4,
                name: "Đàn Piano Điện Yamaha Arius YDP-163R Nhập Khẩu Nhật Bản",
                category: "digital",
                categoryLabel: "Digital Piano",
                oldPrice: "21.800.000 ₫",
                newPrice: "17.500.000 ₫",
                discount: "-20%",
                image: "https://lh3.googleusercontent.com/d/1OIDORfA6G5OfHIlwFavTQ-WatxEGxH5S",
                fallbackImage: "https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=700&q=80",
                featured: true
            },
            {
                id: 5,
                name: "Đàn Upright Piano Yamaha W102 Vân Gỗ Cao Cấp Nội Địa Nhật",
                category: "upright",
                categoryLabel: "Upright Piano",
                oldPrice: "58.900.000 ₫",
                newPrice: "49.800.000 ₫",
                discount: "-15%",
                image: "https://images.unsplash.com/photo-1520523839897-bd0b52f945a0?auto=format&fit=crop&w=700&q=80",
                fallbackImage: "https://images.unsplash.com/photo-1520523839897-bd0b52f945a0?auto=format&fit=crop&w=700&q=80",
                featured: true
            },
            {
                id: 6,
                name: "Đàn Piano Điện Kawai CA15A Phím Gỗ Wooden Key Nhật Bản",
                category: "digital",
                categoryLabel: "Digital Piano",
                oldPrice: "19.800.000 ₫",
                newPrice: "16.800.000 ₫",
                discount: "-15%",
                image: "https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=700&q=80",
                fallbackImage: "https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=700&q=80",
                featured: true
            },
            {
                id: 7,
                name: "Special Grand Piano Yamaha C1 Chính Hãng Nhập Khẩu Nhật Bản",
                category: "grand",
                categoryLabel: "Special Grand Piano",
                oldPrice: "282.000.000 ₫",
                newPrice: "239.000.000 ₫",
                discount: "-15%",
                image: "https://images.unsplash.com/photo-1514119412350-e174d90d280e?auto=format&fit=crop&w=700&q=80",
                fallbackImage: "https://images.unsplash.com/photo-1514119412350-e174d90d280e?auto=format&fit=crop&w=700&q=80",
                featured: true
            },
            {
                id: 8,
                name: "Đàn Upright Piano Yamaha UX Khung Chữ X Nội Địa Nhật Bản",
                category: "upright",
                categoryLabel: "Upright Piano",
                oldPrice: "53.800.000 ₫",
                newPrice: "45.580.000 ₫",
                discount: "-15%",
                image: "https://lh3.googleusercontent.com/d/1DcEfm21LNh0xgbhkeWvR9z3z8yMbBem1",
                fallbackImage: "https://images.unsplash.com/photo-1520523839897-bd0b52f945a0?auto=format&fit=crop&w=700&q=80",
                featured: true
            },

            // --- CÁC SẢN PHẨM PIANO CƠ & GRAND PIANO BỔ SUNG ---
            {
                id: 9,
                name: "Special Grand Piano Yamaha G2 Nội Địa Nhật Bản Nguyên Bản",
                category: "grand",
                categoryLabel: "Special Grand Piano",
                oldPrice: "200.000.000 ₫",
                newPrice: "170.000.000 ₫",
                discount: "-15%",
                image: "https://images.unsplash.com/photo-1514119412350-e174d90d280e?auto=format&fit=crop&w=700&q=80",
                fallbackImage: "https://images.unsplash.com/photo-1514119412350-e174d90d280e?auto=format&fit=crop&w=700&q=80",
                featured: false
            },
            {
                id: 10,
                name: "Special Grand Piano Diapason 170D Hamamatsu Nhật Bản",
                category: "grand",
                categoryLabel: "Special Grand Piano",
                oldPrice: "99.500.000 ₫",
                newPrice: "85.000.000 ₫",
                discount: "-15%",
                image: "https://images.unsplash.com/photo-1520523839897-bd0b52f945a0?auto=format&fit=crop&w=700&q=80",
                fallbackImage: "https://images.unsplash.com/photo-1520523839897-bd0b52f945a0?auto=format&fit=crop&w=700&q=80",
                featured: false
            },
            {
                id: 11,
                name: "Đàn Upright Piano Kawai BL-61 Cao Cấp Nhập Khẩu Nhật Bản",
                category: "upright",
                categoryLabel: "Upright Piano",
                oldPrice: "45.000.000 ₫",
                newPrice: "37.800.000 ₫",
                discount: "-16%",
                image: "https://lh3.googleusercontent.com/d/1DcEfm21LNh0xgbhkeWvR9z3z8yMbBem1",
                fallbackImage: "https://images.unsplash.com/photo-1520523839897-bd0b52f945a0?auto=format&fit=crop&w=700&q=80",
                featured: false
            },

            // --- CÁC SẢN PHẨM DIGITAL PIANO BỔ SUNG ---
            {
                id: 12,
                name: "Đàn Piano Điện Yamaha Arius YDP-143A Nội Địa Nhật Bản",
                category: "digital",
                categoryLabel: "Digital Piano",
                oldPrice: "19.800.000 ₫",
                newPrice: "16.800.000 ₫",
                discount: "-15%",
                image: "https://lh3.googleusercontent.com/d/1OIDORfA6G5OfHIlwFavTQ-WatxEGxH5S",
                fallbackImage: "https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=700&q=80",
                featured: false
            },
            {
                id: 13,
                name: "Đàn Piano Điện Roland HP-603 SuperNATURAL Piano Nhật Bản",
                category: "digital",
                categoryLabel: "Digital Piano",
                oldPrice: "26.500.000 ₫",
                newPrice: "21.900.000 ₫",
                discount: "-17%",
                image: "https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=700&q=80",
                fallbackImage: "https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=700&q=80",
                featured: false
            },
            {
                id: 14,
                name: "Đàn Piano Điện Casio Celviano AP-470 Nhập Khẩu Nhật Bản",
                category: "digital",
                categoryLabel: "Digital Piano",
                oldPrice: "21.000.000 ₫",
                newPrice: "17.850.000 ₫",
                discount: "-15%",
                image: "https://lh3.googleusercontent.com/d/1OIDORfA6G5OfHIlwFavTQ-WatxEGxH5S",
                fallbackImage: "https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=700&q=80",
                featured: false
            },
            {
                id: 15,
                name: "Đàn Piano Điện Korg LP-380 Nội Địa Nhật Bản Thiết Kế Nhỏ Gọn",
                category: "digital",
                categoryLabel: "Digital Piano",
                oldPrice: "14.500.000 ₫",
                newPrice: "11.600.000 ₫",
                discount: "-20%",
                image: "https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=700&q=80",
                fallbackImage: "https://images.unsplash.com/photo-1552422535-c45813c61732?auto=format&fit=crop&w=700&q=80",
                featured: false
            },

            // --- ĐÀN ORGAN & GUITAR NHẬT BẢN ---
            {
                id: 16,
                name: "Đàn Organ Yamaha PSR-SX700 Chuyên Nghiệp Nhập Khẩu Nhật Bản",
                category: "organ",
                categoryLabel: "Đàn Organ",
                oldPrice: "28.500.000 ₫",
                newPrice: "24.200.000 ₫",
                discount: "-15%",
                image: "https://images.unsplash.com/photo-1598488035139-bdbb2231ce04?auto=format&fit=crop&w=700&q=80",
                fallbackImage: "https://images.unsplash.com/photo-1598488035139-bdbb2231ce04?auto=format&fit=crop&w=700&q=80",
                featured: false
            },
            {
                id: 17,
                name: "Đàn Organ Yamaha PSR-E473 Luyện Tập & Biểu Diễn Đa Năng",
                category: "organ",
                categoryLabel: "Đàn Organ",
                oldPrice: "9.800.000 ₫",
                newPrice: "8.300.000 ₫",
                discount: "-15%",
                image: "https://images.unsplash.com/photo-1598488035139-bdbb2231ce04?auto=format&fit=crop&w=700&q=80",
                fallbackImage: "https://images.unsplash.com/photo-1598488035139-bdbb2231ce04?auto=format&fit=crop&w=700&q=80",
                featured: false
            },
            {
                id: 18,
                name: "Đàn Guitar Acoustic Yamaha FG800 Nội Địa Nhật Bản Âm Vang Sáng",
                category: "guitar",
                categoryLabel: "Đàn Guitar",
                oldPrice: "6.500.000 ₫",
                newPrice: "5.200.000 ₫",
                discount: "-20%",
                image: "https://images.unsplash.com/photo-1510915361894-db8b60106cb1?auto=format&fit=crop&w=700&q=80",
                fallbackImage: "https://images.unsplash.com/photo-1510915361894-db8b60106cb1?auto=format&fit=crop&w=700&q=80",
                featured: false
            },
            {
                id: 19,
                name: "Đàn Guitar Classic Morris W-30 Japan Tuyển Chọn Nguyên Bản",
                category: "guitar",
                categoryLabel: "Đàn Guitar",
                oldPrice: "7.900.000 ₫",
                newPrice: "6.700.000 ₫",
                discount: "-15%",
                image: "https://images.unsplash.com/photo-1510915361894-db8b60106cb1?auto=format&fit=crop&w=700&q=80",
                fallbackImage: "https://images.unsplash.com/photo-1510915361894-db8b60106cb1?auto=format&fit=crop&w=700&q=80",
                featured: false
            }
        ];

        /* Hàm tạo thẻ HTML cho từng sản phẩm theo đúng chuẩn Flatsome Product Box:
           - Chỉ có duy nhất badge % giảm giá góc trên bên trái (.flatsome-sale-badge)
           - Không gắn các nhãn dán thừa
           - Tên sản phẩm hiển thị đầy đủ (break-words whitespace-normal), không bị cắt chữ hay tràn ra ngoài */
        function createProductCardHTML(item) {
            return `
                <div class="product-small box bg-white rounded-xl border border-gray-200 hover:border-gold-500 shadow-sm hover:shadow-md transition overflow-hidden flex flex-col justify-between group">
                    <div>
                        <div class="box-image relative w-full pt-[82%] bg-gray-100 overflow-hidden">
                            <!-- Badge % Giảm Giá chuẩn Flatsome góc trên bên trái -->
                            <div class="flatsome-sale-badge">${item.discount}</div>
                            <img 
                                src="${item.image}" 
                                alt="${item.name}" 
                                class="absolute inset-0 w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                onerror="this.onerror=null; this.src='${item.fallbackImage}';"
                            >
                        </div>
                        <div class="box-text p-2.5 sm:p-3.5 text-center">
                            <div class="text-[10px] sm:text-[11px] uppercase tracking-wider text-gray-400 font-semibold mb-1">
                                ${item.categoryLabel}
                            </div>
                            <!-- Tên sản phẩm đầy đủ, tự xuống dòng mượt, không tràn viền hay mất chữ -->
                            <h3 class="font-semibold text-[12.5px] sm:text-[13.5px] md:text-[14px] text-gray-900 group-hover:text-gold-600 leading-snug break-words whitespace-normal mb-2">
                                ${item.name}
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 sm:px-3.5 pb-3 text-center">
                        <div class="price-wrapper flex flex-col sm:flex-row items-center justify-center gap-0.5 sm:gap-2 mb-2.5">
                            <del class="text-[11px] sm:text-xs text-gray-400 font-normal">${item.oldPrice}</del>
                            <ins class="no-underline text-xs sm:text-sm md:text-[15px] font-extrabold text-piano-red">${item.newPrice}</ins>
                        </div>
                        <button 
                            onclick="openProductModal(${item.id})" 
                            class="w-full py-1.5 sm:py-2 px-2 rounded-lg bg-gray-100 hover:bg-gold-500 text-gray-800 hover:text-white font-bold text-[11px] sm:text-xs transition"
                        >
                            Tư vấn &amp; Đặt mua
                        </button>
                    </div>
                </div>
            `;
        }

        function renderAllSections() {
            const featuredList = productsData.filter(p => p.featured);
            const acousticList = productsData.filter(p => p.category === 'upright' || p.category === 'grand').slice(0, 8);
            const digitalList = productsData.filter(p => p.category === 'digital').slice(0, 8);
            const organGuitarList = productsData.filter(p => p.category === 'organ' || p.category === 'guitar');

            document.getElementById('featuredProductsGrid').innerHTML = featuredList.map(createProductCardHTML).join('');
            document.getElementById('acousticProductsGrid').innerHTML = acousticList.map(createProductCardHTML).join('');
            document.getElementById('digitalProductsGrid').innerHTML = digitalList.map(createProductCardHTML).join('');
            document.getElementById('organGuitarProductsGrid').innerHTML = organGuitarList.map(createProductCardHTML).join('');
        }

        /* Lọc theo danh mục trên trang chủ */
        function filterCategory(cat) {
            const featuredGrid = document.getElementById('featuredProductsGrid');
            const notice = document.getElementById('activeFilterNotice');
            let filtered = [];

            if (cat === 'all') {
                filtered = productsData;
                notice.textContent = "Đang hiển thị tất cả sản phẩm tại kho Huy Hoàng Piano Đà Nẵng";
            } else {
                filtered = productsData.filter(p => p.category === cat);
                const labelMap = {
                    grand: "Special Grand Piano Nhật Bản",
                    upright: "Đàn Upright Piano Nhật Bản",
                    digital: "Đàn Piano Điện (Digital Piano)",
                    organ: "Đàn Organ Nhật Bản",
                    guitar: "Đàn Guitar Nhật Bản"
                };
                notice.textContent = "Đang lọc theo danh mục: " + (labelMap[cat] || "Tất cả sản phẩm");
            }

            featuredGrid.innerHTML = filtered.map(createProductCardHTML).join('');
            document.getElementById('san-pham-noi-bat').scrollIntoView({ behavior: 'smooth' });
        }

        /* Tìm kiếm sản phẩm */
        function handleSearch(e) {
            e.preventDefault();
            const desktopInput = document.getElementById('searchInput');
            const mobileInput = document.getElementById('mobileSearchInput');
            const keyword = (desktopInput.value || mobileInput.value || '').trim().toLowerCase();

            if (!keyword) {
                filterCategory('all');
                return;
            }

            const matched = productsData.filter(p => 
                p.name.toLowerCase().includes(keyword) || 
                p.categoryLabel.toLowerCase().includes(keyword)
            );

            const featuredGrid = document.getElementById('featuredProductsGrid');
            const notice = document.getElementById('activeFilterNotice');
            notice.textContent = `Kết quả tìm kiếm cho từ khóa "${keyword}" (${matched.length} sản phẩm)`;

            if (matched.length > 0) {
                featuredGrid.innerHTML = matched.map(createProductCardHTML).join('');
            } else {
                featuredGrid.innerHTML = `
                    <div class="col-span-full bg-white rounded-xl p-6 text-center border border-gray-200">
                        <p class="text-sm font-semibold text-gray-700 mb-2">Không tìm thấy mẫu đàn khớp từ khóa "${keyword}" trên trang hiển thị nhanh.</p>
                        <p class="text-xs text-gray-500 mb-3">Kho đàn Huy Hoàng Piano còn hơn 100+ mẫu đàn Nhật Bản cập nhật liên tục. Vui lòng gọi <strong>0934 825 780</strong> để kiểm tra kho ngay!</p>
                        <button onclick="filterCategory('all')" class="px-4 py-2 rounded-lg bg-gold-500 text-white text-xs font-bold">Xem toàn bộ sản phẩm</button>
                    </div>
                `;
            }
            document.getElementById('san-pham-noi-bat').scrollIntoView({ behavior: 'smooth' });
        }

        /* Mở / Đóng Modal Sản phẩm */
        function openProductModal(productId) {
            const product = productsData.find(p => p.id === productId);
            if (!product) return;
            document.getElementById('modalProductCategory').textContent = product.categoryLabel;
            document.getElementById('modalProductName').textContent = product.name;
            document.getElementById('modalOldPrice').textContent = product.oldPrice;
            document.getElementById('modalNewPrice').textContent = product.newPrice;
            document.getElementById('modalDiscountBadge').textContent = "Tiết kiệm " + product.discount;

            const modal = document.getElementById('productModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeProductModal() {
            const modal = document.getElementById('productModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /* Xử lý Form Yêu cầu & Báo giá */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('quoteName').value.trim();
            const phone = document.getElementById('quotePhone').value.trim();
            const category = document.getElementById('quoteCategory').value;
            const budget = document.getElementById('quoteBudget').value;

            const box = document.getElementById('quoteSuccessBox');
            const text = document.getElementById('quoteSuccessText');
            text.textContent = `Cảm ơn ${name} (${phone})! Yêu cầu báo giá mục "${category}" - Ngân sách "${budget}" đã được gửi tới Huy Hoàng Piano. Chuyên viên tư vấn (0934 825 780) sẽ liên hệ gửi ảnh thực tế và bảng giá tốt nhất cho quý khách ngay!`;
            box.classList.remove('hidden');
            document.getElementById('quoteRequestForm').reset();
        }

        /* Xử lý Mobile Menu Drawer */
        function toggleMobileMenu() {
            const overlay = document.getElementById('mobileMenuOverlay');
            const drawer = document.getElementById('mobileMenuDrawer');
            const isHidden = overlay.classList.contains('hidden');
            if (isHidden) {
                overlay.classList.remove('hidden');
                drawer.classList.remove('-translate-x-full');
            } else {
                overlay.classList.add('hidden');
                drawer.classList.add('-translate-x-full');
            }
        }

        /* Xử lý Slider 2 Banner Tự Trượt Chuyên Nghiệp */
        let currentSlideIndex = 0;
        const totalSlides = 2;
        let slideInterval = null;

        function showSlide(index) {
            for (let i = 0; i < totalSlides; i++) {
                const slide = document.getElementById('bannerSlide' + i);
                const dot = document.getElementById('slideDot' + i);
                if (i === index) {
                    slide.classList.remove('hidden', 'opacity-0');
                    slide.classList.add('opacity-100');
                    dot.classList.remove('w-2', 'bg-white/50');
                    dot.classList.add('w-6', 'bg-gold-400');
                } else {
                    slide.classList.add('hidden', 'opacity-0');
                    slide.classList.remove('opacity-100');
                    dot.classList.remove('w-6', 'bg-gold-400');
                    dot.classList.add('w-2', 'bg-white/50');
                }
            }
            currentSlideIndex = index;
        }

        function changeSlide(step) {
            const next = (currentSlideIndex + step + totalSlides) % totalSlides;
            showSlide(next);
            resetAutoSlide();
        }

        function goToSlide(index) {
            showSlide(index);
            resetAutoSlide();
        }

        function resetAutoSlide() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                changeSlide(1);
            }, 5500);
        }

        window.onload = function () {
            renderAllSections();
            resetAutoSlide();
        };
    </script>
</body>
</html>
