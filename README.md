<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Trí Huyền Food - Thế Giới Thực Phẩm Chay Sạch & Ngũ Cốc Dinh Dưỡng | trihuyenfood.com</title>
    <meta name="description" content="Trí Huyền Food (trihuyenfood.com) - Chuyên sỉ & lẻ Bột ngũ cốc dinh dưỡng, Ngũ cốc hạt Granola, Trà hoa thảo mộc, Thực phẩm chay sạch và Mâm cúng chay trọn gói tại 166 Phạm Hùng, Phường Hòa Xuân, Tp.Đà Nẵng. Hotline: 0933.936.939.">

    <!-- Thumbnail là ảnh Logo trang web khi gửi link qua Zalo, Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://trihuyenfood.com/">
    <meta property="og:title" content="Trí Huyền Food - Thực Phẩm Chay Sạch & Ngũ Cốc Dinh Dưỡng">
    <meta property="og:description" content="Chuyên Bột ngũ cốc, Hạt dinh dưỡng Granola, Trà hoa thảo mộc, Gia vị chay & Mâm cúng chay tại 166 Phạm Hùng, Phường Hòa Xuân, Tp.Đà Nẵng. ĐT: 0933.936.939">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1u-cNx1_9pZUbmGnWgHe_oOmeNUj1oV3P=w800">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1u-cNx1_9pZUbmGnWgHe_oOmeNUj1oV3P=w128">

    <!-- Tailwind CSS & Font Awesome & Google Fonts (Inter) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f2fbf5',
                            100: '#e1f6e8',
                            200: '#c3ecd2',
                            500: '#237a43',
                            600: '#1b6336',
                            700: '#154d2a',
                            800: '#103b20',
                            900: '#0b2916',
                            sale: '#d90429'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Đảm bảo giao diện tuyệt đối không tràn viền, không lệch sang phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f8faf8;
            color: #1f2937;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính chuẩn 1500px theo yêu cầu */
        .container-1500 {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 768px) {
            .container-1500 {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tiêu đề Section chuẩn UX Builder Flatsome */
        .flatsome-title-wrap {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e5e7eb;
            margin-bottom: 16px;
            padding-bottom: 8px;
            gap: 8px;
            flex-wrap: wrap;
        }
        .flatsome-title-main {
            position: relative;
            font-weight: 800;
            color: #154d2a;
            text-transform: uppercase;
            letter-spacing: 0.02em;
        }
        .flatsome-title-main::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: -10px;
            width: 100%;
            height: 3px;
            background-color: #1b6336;
            border-radius: 2px;
        }

        /* Badge % giảm giá chuẩn Flatsome góc trên bên trái */
        .badge-flatsome-sale {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            width: 40px;
            height: 40px;
            border-radius: 9999px;
            background-color: #d90429;
            color: #ffffff;
            font-weight: 800;
            font-size: 11px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(217, 4, 41, 0.35);
            line-height: 1;
            pointer-events: none;
        }

        /* Hiệu ứng nhịp đập nhẹ cho nút Hotline nổi */
        @keyframes pulseRing {
            0% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.6); }
            70% { box-shadow: 0 0 0 10px rgba(220, 38, 38, 0); }
            100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
        }
        .floating-btn-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="w-full overflow-x-hidden">

    <!-- ==========================================
         TOP BAR FLATSOME (Đơn giản, dễ dựng lại trên UX Builder)
    =========================================== -->
    <div class="bg-brand-800 text-emerald-50 text-[11px] sm:text-xs py-1.5 border-b border-brand-700">
        <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 truncate">
                <span class="inline-block w-2 h-2 rounded-full bg-amber-400 flex-shrink-0"></span>
                <span class="font-medium truncate">TRÍ HUYỀN FOOD – THẾ GIỚI THỰC PHẨM CHAY SẠCH & NGŨ CỐC DINH DƯỠNG</span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-emerald-100 flex-shrink-0">
                <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>166 Phạm Hùng, Phường Hòa Xuân, Tp.Đà Nẵng</span>
                <span><i class="fa-solid fa-globe text-amber-400 mr-1"></i>trihuyenfood.com</span>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH CHUẨN FLATSOME
         - Logo lấy từ Google Drive chỉnh gọn nhỏ lại
         - Không để nút Gọi ngay trên Header để tránh giao diện tràn viền
         - Danh mục trên máy tính viết liền trên 1 hàng chữ nhỏ gọn không gãy dòng
    =========================================== -->
    <header class="sticky top-0 z-40 bg-white shadow-sm border-b border-gray-200">
        <div class="container-1500 py-2.5 flex items-center justify-between gap-2 sm:gap-4">
            
            <!-- Nút mở menu trên Điện thoại -->
            <button onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden w-9 h-9 rounded-lg border border-gray-200 flex items-center justify-center text-brand-700 hover:bg-brand-50 flex-shrink-0">
                <i class="fa-solid fa-bars text-base"></i>
            </button>

            <!-- Logo Trí Huyền Food thu gọn tinh tế -->
            <a href="#" class="flex items-center gap-2 sm:gap-2.5 min-w-0 flex-shrink-0">
                <img src="https://lh3.googleusercontent.com/d/1u-cNx1_9pZUbmGnWgHe_oOmeNUj1oV3P=w200"
                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1u-cNx1_9pZUbmGnWgHe_oOmeNUj1oV3P&sz=w200';"
                     alt="Logo Trí Huyền Food"
                     class="w-9 h-9 sm:w-11 sm:h-11 rounded-full object-contain border border-brand-200 bg-white p-0.5 flex-shrink-0">
                <div class="leading-tight min-w-0">
                    <span class="block text-sm sm:text-base font-extrabold text-brand-700 tracking-tight truncate">TRÍ HUYỀN FOOD</span>
                    <span class="block text-[10px] sm:text-[11px] text-amber-600 font-semibold truncate">Thực Phẩm Chay & Ngũ Cốc Sạch</span>
                </div>
            </a>

            <!-- Ô tìm kiếm sản phẩm (hiển thị gọn trên máy tính) -->
            <div class="hidden md:flex flex-1 max-w-md mx-2">
                <div class="relative w-full">
                    <input type="text"
                           oninput="handleSearchProduct(this.value)"
                           placeholder="Tìm bột ngũ cốc, granola, trà hoa, đồ chay..."
                           class="w-full pl-3.5 pr-9 py-1.5 text-xs rounded-full border border-gray-300 focus:outline-none focus:border-brand-600 bg-gray-50">
                    <i class="fa-solid fa-magnifying-glass absolute right-3 top-1/2 -translate-y-1/2 text-gray-400 text-xs"></i>
                </div>
            </div>

            <!-- Giỏ hàng gọn gàng bên phải (Không để nút Gọi ngay trên Header theo đúng yêu cầu) -->
            <div class="flex items-center gap-2 flex-shrink-0">
                <button onclick="openCartModal()" class="flex items-center gap-1.5 bg-brand-50 hover:bg-brand-100 text-brand-700 border border-brand-200 rounded-full px-3 py-1.5 text-xs font-bold transition">
                    <i class="fa-solid fa-basket-shopping text-brand-600"></i>
                    <span class="hidden sm:inline">Giỏ hàng</span>
                    <span id="cartCountBadge" class="bg-amber-500 text-gray-900 text-[10px] font-extrabold px-1.5 py-0.5 rounded-full">0</span>
                </button>
            </div>
        </div>

        <!-- Thanh tìm kiếm trên điện thoại -->
        <div class="md:hidden px-3 pb-2">
            <div class="relative w-full">
                <input type="text"
                       oninput="handleSearchProduct(this.value)"
                       placeholder="Tìm sản phẩm chay, ngũ cốc, trà hoa..."
                       class="w-full pl-3 pr-8 py-1.5 text-xs rounded-lg border border-gray-300 focus:outline-none focus:border-brand-600 bg-gray-50">
                <i class="fa-solid fa-magnifying-glass absolute right-3 top-1/2 -translate-y-1/2 text-gray-400 text-xs"></i>
            </div>
        </div>

        <!-- Thanh Menu Danh Mục trên Máy Tính:
             Chữ nhỏ gọn, viết liền trên 1 hàng (whitespace-nowrap), có thể xuống hàng thứ 2 nếu màn hình nhỏ nhưng tuyệt đối không gãy dòng tên từng danh mục -->
        <nav class="hidden lg:block bg-brand-700 text-white border-t border-brand-600">
            <div class="container-1500">
                <ul class="flex flex-wrap items-center justify-center gap-x-4 xl:gap-x-6 gap-y-1 py-2 text-[12px] font-bold">
                    <li><a href="#" onclick="filterCategory('all')" class="whitespace-nowrap hover:text-amber-300 transition py-1 block"><i class="fa-solid fa-house mr-1 text-[11px]"></i>TRANG CHỦ</a></li>
                    <li><a href="#danh-muc-san-pham" onclick="filterCategory('bot-ngu-coc')" class="whitespace-nowrap hover:text-amber-300 transition py-1 block">BỘT NGŨ CỐC DINH DƯỠNG</a></li>
                    <li><a href="#danh-muc-san-pham" onclick="filterCategory('granola')" class="whitespace-nowrap hover:text-amber-300 transition py-1 block">NGŨ CỐC HẠT, GRANOLA</a></li>
                    <li><a href="#danh-muc-san-pham" onclick="filterCategory('tra-hoa')" class="whitespace-nowrap hover:text-amber-300 transition py-1 block">TRÀ HOA THẢO MỘC</a></li>
                    <li><a href="#danh-muc-san-pham" onclick="filterCategory('thuc-pham-chay')" class="whitespace-nowrap hover:text-amber-300 transition py-1 block">THỰC PHẨM & GIA VỊ CHAY</a></li>
                    <li><a href="#danh-muc-san-pham" onclick="filterCategory('san-pham-khac')" class="whitespace-nowrap hover:text-amber-300 transition py-1 block">MÂM CÚNG & SẢN PHẨM KHÁC</a></li>
                    <li><a href="#bai-viet" class="whitespace-nowrap hover:text-amber-300 transition py-1 block">TIN TỨC & KIẾN THỨC</a></li>
                    <li><a href="#doi-tac" class="whitespace-nowrap hover:text-amber-300 transition py-1 block">ĐỐI TÁC</a></li>
                    <li><a href="#bao-gia" class="whitespace-nowrap hover:text-amber-300 transition py-1 block">YÊU CẦU & BÁO GIÁ</a></li>
                    <li><a href="#he-thong-cua-hang" class="whitespace-nowrap hover:text-amber-300 transition py-1 block">BẢN ĐỒ & FANPAGE</a></li>
                </ul>
            </div>
        </nav>

        <!-- Menu Drawer trên Điện Thoại -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-gray-200 px-3 py-3 space-y-1.5 shadow-lg">
            <p class="text-[11px] font-extrabold text-brand-700 uppercase px-2 pb-1 border-b border-gray-100">Danh mục Trí Huyền Food</p>
            <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold">
                <a href="#danh-muc-san-pham" onclick="filterCategory('all'); toggleMobileMenu();" class="p-2 rounded-lg bg-brand-50 text-brand-700 truncate">Tất cả sản phẩm</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('bot-ngu-coc'); toggleMobileMenu();" class="p-2 rounded-lg bg-gray-50 hover:bg-brand-50 text-gray-800 truncate">Bột ngũ cốc</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('granola'); toggleMobileMenu();" class="p-2 rounded-lg bg-gray-50 hover:bg-brand-50 text-gray-800 truncate">Ngũ cốc hạt, Granola</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('tra-hoa'); toggleMobileMenu();" class="p-2 rounded-lg bg-gray-50 hover:bg-brand-50 text-gray-800 truncate">Trà hoa thảo mộc</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('thuc-pham-chay'); toggleMobileMenu();" class="p-2 rounded-lg bg-gray-50 hover:bg-brand-50 text-gray-800 truncate">Thực phẩm chay</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('san-pham-khac'); toggleMobileMenu();" class="p-2 rounded-lg bg-gray-50 hover:bg-brand-50 text-gray-800 truncate">Mâm cúng & Khác</a>
                <a href="#bai-viet" onclick="toggleMobileMenu();" class="p-2 rounded-lg bg-gray-50 hover:bg-brand-50 text-gray-800 truncate">Bài viết chay</a>
                <a href="#bao-gia" onclick="toggleMobileMenu();" class="p-2 rounded-lg bg-amber-50 text-amber-800 font-bold truncate">Nhận báo giá sỉ</a>
            </div>
        </div>
    </header>

    <!-- ==========================================
         2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         - Tách riêng phiên bản Banner Máy Tính và Banner Điện Thoại
         - Chữ nhỏ gọn nằm hết bên trong khung ảnh banner, tuyệt đối không tràn viền
    =========================================== -->
    <section class="container-1500 pt-3 pb-2">
        <div class="relative rounded-2xl overflow-hidden shadow-sm border border-brand-200 bg-brand-800">
            
            <!-- A. 2 SLIDE BANNER DÀNH RIÊNG CHO MÁY TÍNH (Kích thước bằng nhau h-[320px] lg:h-[360px]) -->
            <div class="hidden md:block relative w-full h-[320px] lg:h-[360px]">
                
                <!-- Slide 1 Máy tính -->
                <div class="banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-r from-brand-900 via-brand-700 to-emerald-800 flex items-center">
                    <div class="w-full h-full px-8 lg:px-14 grid grid-cols-12 items-center gap-6">
                        <div class="col-span-7 text-white space-y-2.5 pr-4">
                            <span class="inline-block bg-amber-400 text-gray-900 text-[11px] font-extrabold px-3 py-1 rounded-full uppercase">
                                Tinh Hoa Thực Dưỡng & Thuần Chay Sạch
                            </span>
                            <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-amber-300">
                                TRÍ HUYỀN FOOD – NGŨ CỐC HẠT, GRANOLA & THỰC PHẨM CHAY ĐÀ NẴNG
                            </h1>
                            <p class="text-xs lg:text-sm text-emerald-100 leading-relaxed max-w-xl">
                                Chuyên phân phối sỉ & lẻ Bột ngũ cốc 20 loại hạt, Granola siêu giòn, Trà hoa thảo mộc, Gia vị chay tự nhiên và Mâm cúng chay trọn gói. Cam kết 100% không chất bảo quản.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <a href="#danh-muc-san-pham" class="bg-amber-400 hover:bg-amber-300 text-gray-900 font-extrabold px-4 py-2 rounded-lg transition">
                                    MUA SẮM NGAY
                                </a>
                                <a href="#bao-gia" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-bold px-4 py-2 rounded-lg transition">
                                    NHẬN BÁO GIÁ SỈ & LẺ
                                </a>
                                <span class="text-emerald-200 font-semibold"><i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>166 Phạm Hùng, Hòa Xuân, Đà Nẵng</span>
                            </div>
                        </div>
                        <div class="col-span-5 flex items-center justify-center gap-3">
                            <img src="https://lh3.googleusercontent.com/d/1ZR7Mg96mM-WlNAnqSKMwrNVPrXYEyUgJ=w400"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ZR7Mg96mM-WlNAnqSKMwrNVPrXYEyUgJ&sz=w400';"
                                 alt="Ngũ cốc dinh dưỡng Trí Huyền Food"
                                 class="w-40 lg:w-48 h-52 lg:h-60 object-cover rounded-xl border-2 border-amber-300 shadow-lg">
                            <img src="https://lh3.googleusercontent.com/d/1mKK_ykzZThvYd9cFXt3Lx8y8XeAVslPm=w400"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1mKK_ykzZThvYd9cFXt3Lx8y8XeAVslPm&sz=w400';"
                                 alt="Granola siêu giòn Trí Huyền Food"
                                 class="w-36 lg:w-44 h-44 lg:h-52 object-cover rounded-xl border-2 border-white/80 shadow-lg">
                        </div>
                    </div>
                </div>

                <!-- Slide 2 Máy tính (Kích thước bằng đúng Slide 1) -->
                <div class="banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-r from-[#143d23] via-[#1c5932] to-[#0f2e1a] flex items-center">
                    <div class="w-full h-full px-8 lg:px-14 grid grid-cols-12 items-center gap-6">
                        <div class="col-span-7 text-white space-y-2.5 pr-4">
                            <span class="inline-block bg-amber-400 text-gray-900 text-[11px] font-extrabold px-3 py-1 rounded-full uppercase">
                                Đặc Sản Chay & Mâm Cúng Trọn Gói
                            </span>
                            <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-amber-300">
                                TRÀ HOA THẢO MỘC, GIA VỊ CHAY & MÂM CÚNG CHAY THANH TỊNH
                            </h2>
                            <p class="text-xs lg:text-sm text-emerald-100 leading-relaxed max-w-xl">
                                Đầy đủ Rong biển sấy mè, Chả lụa chay, Hạt nêm nấm hương, Chao môn, Bột đậu rau củ và dịch vụ đặt Mâm cúng chay ngày Rằm, Mùng 1, Khai trương giao tận nơi tại Đà Nẵng.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <a href="#danh-muc-san-pham" onclick="filterCategory('thuc-pham-chay')" class="bg-amber-400 hover:bg-amber-300 text-gray-900 font-extrabold px-4 py-2 rounded-lg transition">
                                    XEM THỰC PHẨM CHAY
                                </a>
                                <span class="text-amber-300 font-extrabold"><i class="fa-solid fa-phone-volume mr-1"></i>Hotline/Zalo: 0933.936.939</span>
                            </div>
                        </div>
                        <div class="col-span-5 flex items-center justify-center gap-3">
                            <img src="https://lh3.googleusercontent.com/d/1Af7EB3SBjLe_s8iOqIpPXchRTWxgZ1cW=w400"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Af7EB3SBjLe_s8iOqIpPXchRTWxgZ1cW&sz=w400';"
                                 alt="Rong biển sấy mè"
                                 class="w-40 lg:w-48 h-52 lg:h-60 object-cover rounded-xl border-2 border-amber-300 shadow-lg">
                            <img src="https://lh3.googleusercontent.com/d/14L3ksgau_oWcsirIKr-8UtKLjtaoTDfo=w400"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=14L3ksgau_oWcsirIKr-8UtKLjtaoTDfo&sz=w400';"
                                 alt="Mâm cúng chay trọn gói"
                                 class="w-36 lg:w-44 h-44 lg:h-52 object-cover rounded-xl border-2 border-white/80 shadow-lg">
                        </div>
                    </div>
                </div>
            </div>

            <!-- B. 2 SLIDE BANNER DÀNH RIÊNG CHO ĐIỆN THOẠI (Thiết kế khác bản máy tính, chữ nhỏ gọn nằm trọn trong ảnh, không tràn viền) -->
            <div class="block md:hidden relative w-full h-[215px] sm:h-[230px]">
                
                <!-- Slide 1 Điện thoại -->
                <div class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-br from-brand-800 via-brand-700 to-brand-900 p-3.5 flex items-center justify-between gap-2.5">
                    <div class="flex-1 min-w-0 text-white space-y-1.5">
                        <span class="inline-block bg-amber-400 text-gray-900 text-[9px] font-extrabold px-2 py-0.5 rounded uppercase">
                            Trí Huyền Food • Đà Nẵng
                        </span>
                        <h2 class="text-[13px] sm:text-sm font-extrabold text-amber-300 leading-snug break-words">
                            BỘT NGŨ CỐC, HẠT GRANOLA & ĐỒ CHAY SẠCH
                        </h2>
                        <p class="text-[10px] text-emerald-100 leading-tight break-words">
                            100% Tự nhiên – Không chất bảo quản. Giao nhanh tại 166 Phạm Hùng, Hòa Xuân.
                        </p>
                        <div class="pt-1 flex items-center gap-1.5">
                            <a href="#danh-muc-san-pham" class="bg-amber-400 text-gray-900 text-[10px] font-extrabold px-2.5 py-1 rounded">
                                Xem Sản Phẩm
                            </a>
                            <span class="text-[10px] text-amber-200 font-bold">0933.936.939</span>
                        </div>
                    </div>
                    <img src="https://lh3.googleusercontent.com/d/1ZR7Mg96mM-WlNAnqSKMwrNVPrXYEyUgJ=w250"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ZR7Mg96mM-WlNAnqSKMwrNVPrXYEyUgJ&sz=w250';"
                         alt="Ngũ cốc dinh dưỡng"
                         class="w-24 h-32 sm:w-28 sm:h-36 object-cover rounded-xl border border-amber-300 flex-shrink-0 shadow-md">
                </div>

                <!-- Slide 2 Điện thoại (Kích thước bằng đúng Slide 1 Điện thoại) -->
                <div class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-br from-[#143d23] via-brand-700 to-[#0d2817] p-3.5 flex items-center justify-between gap-2.5">
                    <div class="flex-1 min-w-0 text-white space-y-1.5">
                        <span class="inline-block bg-amber-400 text-gray-900 text-[9px] font-extrabold px-2 py-0.5 rounded uppercase">
                            Thực Phẩm Chay & Mâm Cúng
                        </span>
                        <h2 class="text-[13px] sm:text-sm font-extrabold text-amber-300 leading-snug break-words">
                            TRÀ HOA THẢO MỘC & MÂM CÚNG CHAY TRỌN GÓI
                        </h2>
                        <p class="text-[10px] text-emerald-100 leading-tight break-words">
                            Nhận đặt mâm cúng chay Rằm, Mùng 1, Khai trương chỉn chu, giao tận nơi đúng giờ.
                        </p>
                        <div class="pt-1 flex items-center gap-1.5">
                            <a href="#bao-gia" class="bg-amber-400 text-gray-900 text-[10px] font-extrabold px-2.5 py-1 rounded">
                                Nhận Báo Giá
                            </a>
                            <span class="text-[10px] text-amber-200 font-bold">166 Phạm Hùng</span>
                        </div>
                    </div>
                    <img src="https://lh3.googleusercontent.com/d/14L3ksgau_oWcsirIKr-8UtKLjtaoTDfo=w250"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=14L3ksgau_oWcsirIKr-8UtKLjtaoTDfo&sz=w250';"
                         alt="Mâm cúng chay Đà Nẵng"
                         class="w-24 h-32 sm:w-28 sm:h-36 object-cover rounded-xl border border-amber-300 flex-shrink-0 shadow-md">
                </div>
            </div>

            <!-- Nút chuyển trái/phải và chấm tròn chỉ báo Slide -->
            <button onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/30 hover:bg-black/50 text-white flex items-center justify-center transition">
                <i class="fa-solid fa-chevron-left text-xs"></i>
            </button>
            <button onclick="changeBannerSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/30 hover:bg-black/50 text-white flex items-center justify-center transition">
                <i class="fa-solid fa-chevron-right text-xs"></i>
            </button>
            <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-1.5">
                <button id="bannerDot0" onclick="setBannerSlide(0)" aria-label="Banner 1" class="w-5 h-1.5 rounded-full bg-amber-400 transition-all"></button>
                <button id="bannerDot1" onclick="setBannerSlide(1)" aria-label="Banner 2" class="w-2 h-1.5 rounded-full bg-white/60 transition-all"></button>
            </div>
        </div>
    </section>

    <!-- ==========================================
         4 CAM KẾT CHẤT LƯỢNG CHUẨN MẪU THUANDUYEN.VN
    =========================================== -->
    <section id="gioi-thieu" class="container-1500 py-3">
        <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-3">
            <div class="bg-white rounded-xl p-3 border border-gray-200 shadow-xs flex items-center gap-2.5">
                <div class="w-9 h-9 rounded-full bg-brand-50 text-brand-700 flex items-center justify-center flex-shrink-0">
                    <i class="fa-solid fa-seedling text-sm"></i>
                </div>
                <div class="min-w-0">
                    <p class="text-xs font-extrabold text-brand-700 truncate">100% Thuần Chay Sạch</p>
                    <p class="text-[11px] text-gray-500 truncate">Không chất bảo quản</p>
                </div>
            </div>
            <div class="bg-white rounded-xl p-3 border border-gray-200 shadow-xs flex items-center gap-2.5">
                <div class="w-9 h-9 rounded-full bg-amber-50 text-amber-700 flex items-center justify-center flex-shrink-0">
                    <i class="fa-solid fa-award text-sm"></i>
                </div>
                <div class="min-w-0">
                    <p class="text-xs font-extrabold text-brand-700 truncate">Chuẩn Vệ Sinh ATTP</p>
                    <p class="text-[11px] text-gray-500 truncate">Nông sản tuyển chọn</p>
                </div>
            </div>
            <div class="bg-white rounded-xl p-3 border border-gray-200 shadow-xs flex items-center gap-2.5">
                <div class="w-9 h-9 rounded-full bg-brand-50 text-brand-700 flex items-center justify-center flex-shrink-0">
                    <i class="fa-solid fa-truck-fast text-sm"></i>
                </div>
                <div class="min-w-0">
                    <p class="text-xs font-extrabold text-brand-700 truncate">Giao Nhanh Toàn Quốc</p>
                    <p class="text-[11px] text-gray-500 truncate">Kiểm hàng trước khi nhận</p>
                </div>
            </div>
            <div class="bg-white rounded-xl p-3 border border-gray-200 shadow-xs flex items-center gap-2.5">
                <div class="w-9 h-9 rounded-full bg-amber-50 text-amber-700 flex items-center justify-center flex-shrink-0">
                    <i class="fa-solid fa-handshake text-sm"></i>
                </div>
                <div class="min-w-0">
                    <p class="text-xs font-extrabold text-brand-700 truncate">Phân Phối Sỉ & Lẻ</p>
                    <p class="text-[11px] text-gray-500 truncate">Chiết khấu đại lý tốt</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM TRANG CHỦ
         - Chữ danh mục ở trang chủ nhỏ gọn
         - Trên máy tính: 6 ô trên 1 hàng, chữ viết liền không bị gãy dòng
         - Trên điện thoại: chia 2 cột đẹp mắt
    =========================================== -->
    <section id="danh-muc-san-pham" class="container-1500 py-4">
        <div class="flatsome-title-wrap">
            <h2 class="flatsome-title-main text-sm sm:text-base md:text-lg">DANH MỤC SẢN PHẨM</h2>
            <span class="text-xs text-gray-500 hidden sm:inline">Chọn danh mục để lọc nhanh sản phẩm</span>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2 sm:gap-2.5">
            
            <button onclick="filterCategory('all')" id="catCard-all" class="cat-card-btn group bg-brand-600 text-white rounded-xl p-2 sm:p-2.5 border border-brand-600 shadow-xs hover:shadow-md transition flex items-center gap-2 text-left overflow-hidden">
                <div class="w-8 h-8 rounded-lg bg-white/20 flex items-center justify-center flex-shrink-0">
                    <i class="fa-solid fa-layer-group text-xs"></i>
                </div>
                <div class="min-w-0 flex-1">
                    <p class="text-[11px] font-bold leading-tight lg:whitespace-nowrap">Tất Cả Sản Phẩm</p>
                    <p class="text-[10px] opacity-85 leading-tight mt-0.5">11 sản phẩm</p>
                </div>
            </button>

            <button onclick="filterCategory('bot-ngu-coc')" id="catCard-bot-ngu-coc" class="cat-card-btn group bg-white text-gray-800 rounded-xl p-2 sm:p-2.5 border border-gray-200 hover:border-brand-600 shadow-xs hover:shadow-md transition flex items-center gap-2 text-left overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/1ZR7Mg96mM-WlNAnqSKMwrNVPrXYEyUgJ=w150"
                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ZR7Mg96mM-WlNAnqSKMwrNVPrXYEyUgJ&sz=w150';"
                     alt="Bột ngũ cốc" class="w-8 h-8 rounded-lg object-cover flex-shrink-0 border border-gray-100">
                <div class="min-w-0 flex-1">
                    <p class="text-[11px] font-bold text-brand-700 leading-tight lg:whitespace-nowrap">Bột Ngũ Cốc</p>
                    <p class="text-[10px] text-gray-500 leading-tight mt-0.5">Thuận Duyên Gold</p>
                </div>
            </button>

            <button onclick="filterCategory('granola')" id="catCard-granola" class="cat-card-btn group bg-white text-gray-800 rounded-xl p-2 sm:p-2.5 border border-gray-200 hover:border-brand-600 shadow-xs hover:shadow-md transition flex items-center gap-2 text-left overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/1mKK_ykzZThvYd9cFXt3Lx8y8XeAVslPm=w150"
                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1mKK_ykzZThvYd9cFXt3Lx8y8XeAVslPm&sz=w150';"
                     alt="Granola" class="w-8 h-8 rounded-lg object-cover flex-shrink-0 border border-gray-100">
                <div class="min-w-0 flex-1">
                    <p class="text-[11px] font-bold text-brand-700 leading-tight lg:whitespace-nowrap">Ngũ Cốc Hạt, Granola</p>
                    <p class="text-[10px] text-gray-500 leading-tight mt-0.5">Hạt sấy, Bánh hạt</p>
                </div>
            </button>

            <button onclick="filterCategory('tra-hoa')" id="catCard-tra-hoa" class="cat-card-btn group bg-white text-gray-800 rounded-xl p-2 sm:p-2.5 border border-gray-200 hover:border-brand-600 shadow-xs hover:shadow-md transition flex items-center gap-2 text-left overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/1NskR8jA4UVo8oMtCPykxKyl_k82C8WB9=w150"
                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1NskR8jA4UVo8oMtCPykxKyl_k82C8WB9&sz=w150';"
                     alt="Trà hoa thảo mộc" class="w-8 h-8 rounded-lg object-cover flex-shrink-0 border border-gray-100">
                <div class="min-w-0 flex-1">
                    <p class="text-[11px] font-bold text-brand-700 leading-tight lg:whitespace-nowrap">Trà Hoa Thảo Mộc</p>
                    <p class="text-[10px] text-gray-500 leading-tight mt-0.5">Thanh nhiệt, an thần</p>
                </div>
            </button>

            <button onclick="filterCategory('thuc-pham-chay')" id="catCard-thuc-pham-chay" class="cat-card-btn group bg-white text-gray-800 rounded-xl p-2 sm:p-2.5 border border-gray-200 hover:border-brand-600 shadow-xs hover:shadow-md transition flex items-center gap-2 text-left overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/1Af7EB3SBjLe_s8iOqIpPXchRTWxgZ1cW=w150"
                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Af7EB3SBjLe_s8iOqIpPXchRTWxgZ1cW&sz=w150';"
                     alt="Thực phẩm chay" class="w-8 h-8 rounded-lg object-cover flex-shrink-0 border border-gray-100">
                <div class="min-w-0 flex-1">
                    <p class="text-[11px] font-bold text-brand-700 leading-tight lg:whitespace-nowrap">Thực Phẩm Chay</p>
                    <p class="text-[10px] text-gray-500 leading-tight mt-0.5">Rong biển, gia vị chay</p>
                </div>
            </button>

            <button onclick="filterCategory('san-pham-khac')" id="catCard-san-pham-khac" class="cat-card-btn group bg-white text-gray-800 rounded-xl p-2 sm:p-2.5 border border-gray-200 hover:border-brand-600 shadow-xs hover:shadow-md transition flex items-center gap-2 text-left overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/14L3ksgau_oWcsirIKr-8UtKLjtaoTDfo=w150"
                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=14L3ksgau_oWcsirIKr-8UtKLjtaoTDfo&sz=w150';"
                     alt="Sản phẩm khác" class="w-8 h-8 rounded-lg object-cover flex-shrink-0 border border-gray-100">
                <div class="min-w-0 flex-1">
                    <p class="text-[11px] font-bold text-brand-700 leading-tight lg:whitespace-nowrap">Sản Phẩm Khác</p>
                    <p class="text-[10px] text-gray-500 leading-tight mt-0.5">Mâm cúng & Món chay</p>
                </div>
            </button>

        </div>
    </section>

    <!-- ==========================================
         DANH SÁCH 11 SẢN PHẨM THỰC TẾ (CHIA 2 CỘT TRÊN ĐIỆN THOẠI)
         - Có giá giảm và % giảm giá góc trên bên trái giống Flatsome
         - Không để các nhãn dán dư thừa ở trang chủ
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn hay thiếu chữ
    =========================================== -->
    <section class="container-1500 py-4">
        <div class="flatsome-title-wrap">
            <h2 id="currentCategoryTitle" class="flatsome-title-main text-sm sm:text-base md:text-lg">SẢN PHẨM NỔI BẬT TẠI TRÍ HUYỀN FOOD</h2>
            <button onclick="filterCategory('all')" class="text-xs font-bold text-brand-700 hover:text-amber-600">
                Xem tất cả (11) <i class="fa-solid fa-angle-right ml-1"></i>
            </button>
        </div>

        <!-- Chia 2 cột trên điện thoại (grid-cols-2), 3 cột trên tablet, 4 cột trên máy tính -->
        <div id="productGridContainer" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4"></div>
    </section>

    <!-- ==========================================
         CHUYÊN MỤC 1: BỘT NGŨ CỐC DINH DƯỠNG & NGŨ CỐC HẠT GRANOLA (Giống bố cục thuanduyen.vn)
    =========================================== -->
    <section class="container-1500 py-4">
        <div class="flatsome-title-wrap">
            <h2 class="flatsome-title-main text-sm sm:text-base md:text-lg">BỘT NGŨ CỐC & HẠT DINH DƯỠNG GRANOLA</h2>
            <a href="#danh-muc-san-pham" onclick="filterCategory('bot-ngu-coc')" class="text-xs font-bold text-brand-700 hover:text-amber-600">
                Xem thêm <i class="fa-solid fa-angle-right ml-1"></i>
            </a>
        </div>
        <div id="cerealGranolaGrid" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4"></div>
    </section>

    <!-- ==========================================
         CHUYÊN MỤC 2: TRÀ HOA THẢO MỘC, THỰC PHẨM CHAY & MÂM CÚNG CHAY
    =========================================== -->
    <section class="container-1500 py-4">
        <div class="flatsome-title-wrap">
            <h2 class="flatsome-title-main text-sm sm:text-base md:text-lg">TRÀ HOA THẢO MỘC, THỰC PHẨM CHAY & MÂM CÚNG</h2>
            <a href="#danh-muc-san-pham" onclick="filterCategory('thuc-pham-chay')" class="text-xs font-bold text-brand-700 hover:text-amber-600">
                Xem thêm <i class="fa-solid fa-angle-right ml-1"></i>
            </a>
        </div>
        <div id="teaVeganOtherGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4"></div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU VÀ BÁO GIÁ SỈ & LẺ TRANG CHỦ
    =========================================== -->
    <section id="bao-gia" class="container-1500 py-5">
        <div class="bg-gradient-to-r from-brand-800 via-brand-700 to-brand-800 rounded-2xl p-4 sm:p-6 lg:p-8 text-white shadow-sm border border-brand-600">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                
                <!-- Thông tin tư vấn bên trái -->
                <div class="lg:col-span-5 space-y-3">
                    <span class="inline-block bg-amber-400 text-gray-900 text-[11px] font-extrabold px-3 py-1 rounded-full uppercase">
                        Đăng Ký Đại Lý & Đặt Hàng Nhanh
                    </span>
                    <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-amber-300 leading-snug">
                        FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRÍ HUYỀN FOOD
                    </h2>
                    <p class="text-xs sm:text-sm text-emerald-100 leading-relaxed">
                        Quý khách cần báo giá sỉ/lẻ Bột ngũ cốc, Hạt Granola, Trà hoa thảo mộc, Thực phẩm chay cho quán chay hoặc đặt Mâm cúng chay trọn gói tại Đà Nẵng, vui lòng để lại thông tin bên cạnh.
                    </p>
                    <div class="space-y-1.5 text-xs text-emerald-100 pt-1">
                        <p><i class="fa-solid fa-location-dot text-amber-300 w-5"></i><strong>Địa chỉ:</strong> 166 Phạm Hùng, Phường Hòa Xuân, Tp.Đà Nẵng</p>
                        <p><i class="fa-solid fa-phone-volume text-amber-300 w-5"></i><strong>Hotline/Zalo:</strong> 0933.936.939</p>
                        <p><i class="fa-solid fa-globe text-amber-300 w-5"></i><strong>Website:</strong> trihuyenfood.com</p>
                    </div>
                </div>

                <!-- Form nhập thông tin báo giá bên phải -->
                <div class="lg:col-span-7 bg-white text-gray-800 rounded-xl p-4 sm:p-5 shadow-md">
                    <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Họ và tên quý khách *</label>
                                <input id="quoteName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs rounded-lg border border-gray-300 focus:outline-none focus:border-brand-600">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="quotePhone" type="tel" required placeholder="VD: 0933.936.939" class="w-full px-3 py-2 text-xs rounded-lg border border-gray-300 focus:outline-none focus:border-brand-600">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Danh mục cần báo giá *</label>
                                <select id="quoteCategory" class="w-full px-3 py-2 text-xs rounded-lg border border-gray-300 focus:outline-none focus:border-brand-600 bg-white">
                                    <option value="Bột ngũ cốc dinh dưỡng">Bột ngũ cốc dinh dưỡng (Sỉ / Lẻ)</option>
                                    <option value="Ngũ cốc hạt Granola & Bánh hạt">Ngũ cốc hạt Granola & Bánh hạt</option>
                                    <option value="Trà hoa thảo mộc">Trà hoa thảo mộc</option>
                                    <option value="Thực phẩm & Gia vị chay">Thực phẩm & Gia vị chay</option>
                                    <option value="Đặt Mâm cúng chay trọn gói">Đặt Mâm cúng chay trọn gói tại Đà Nẵng</option>
                                    <option value="Đăng ký Đại lý / Cộng tác viên">Đăng ký Đại lý / Cộng tác viên</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Khu vực giao hàng</label>
                                <input id="quoteAddress" type="text" placeholder="VD: Hòa Xuân, Cẩm Lệ, Đà Nẵng..." class="w-full px-3 py-2 text-xs rounded-lg border border-gray-300 focus:outline-none focus:border-brand-600">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-gray-700 mb-1">Ghi chú số lượng hoặc yêu cầu chi tiết</label>
                            <textarea id="quoteNote" rows="2" placeholder="Nhập tên sản phẩm, số lượng hoặc ngày giờ cần đặt mâm cúng chay..." class="w-full px-3 py-2 text-xs rounded-lg border border-gray-300 focus:outline-none focus:border-brand-600"></textarea>
                        </div>

                        <button type="submit" class="w-full bg-brand-600 hover:bg-brand-700 text-white font-extrabold text-xs sm:text-sm py-2.5 px-4 rounded-lg transition shadow-xs">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU & NHẬN BÁO GIÁ NGAY
                        </button>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC - KIẾN THỨC CHAY)
    =========================================== -->
    <section id="bai-viet" class="container-1500 py-5">
        <div class="flatsome-title-wrap">
            <h2 class="flatsome-title-main text-sm sm:text-base md:text-lg">DANH MỤC BÀI VIẾT & KIẾN THỨC THỰC DƯỠNG</h2>
            <div class="flex flex-wrap items-center gap-1.5">
                <button onclick="filterArticles('all')" id="artTab-all" class="art-tab-btn px-2.5 py-1 rounded text-xs font-bold bg-brand-600 text-white">Tất cả</button>
                <button onclick="filterArticles('tin-tuc')" id="artTab-tin-tuc" class="art-tab-btn px-2.5 py-1 rounded text-xs font-semibold bg-white text-gray-700 border border-gray-200">Tin tức – Hoạt động</button>
                <button onclick="filterArticles('kien-thuc')" id="artTab-kien-thuc" class="art-tab-btn px-2.5 py-1 rounded text-xs font-semibold bg-white text-gray-700 border border-gray-200">Kiến thức – Kinh nghiệm</button>
                <button onclick="filterArticles('mam-cung')" id="artTab-mam-cung" class="art-tab-btn px-2.5 py-1 rounded text-xs font-semibold bg-white text-gray-700 border border-gray-200">Góc Mâm Cúng Chay</button>
            </div>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
            <!-- Bài viết 1 -->
            <article data-art-cat="tin-tuc" class="article-card bg-white rounded-xl overflow-hidden border border-gray-200 shadow-xs hover:shadow-md transition flex flex-col">
                <div class="h-44 overflow-hidden bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1ZR7Mg96mM-WlNAnqSKMwrNVPrXYEyUgJ=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ZR7Mg96mM-WlNAnqSKMwrNVPrXYEyUgJ&sz=w600';"
                         alt="Ngũ cốc Dinh dưỡng Gold 20 loại hạt" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
                    <div>
                        <span class="text-[11px] font-bold text-brand-600 uppercase">Tin tức – Hoạt động</span>
                        <h3 class="text-sm font-bold text-gray-800 mt-1 leading-snug">
                            Ngũ cốc Dinh dưỡng Gold 20 loại hạt – Bí quyết sống khỏe từ mầm xanh Xứ Quảng
                        </h3>
                        <p class="text-xs text-gray-600 mt-1.5 leading-relaxed">
                            Kết hợp 20 loại hạt quý giàu dưỡng chất, đạt chuẩn HACCP, cam kết 4 KHÔNG an toàn cho mọi lứa tuổi tại Trí Huyền Food.
                        </p>
                    </div>
                    <button onclick="openArticleDetail(0)" class="text-xs font-bold text-brand-700 hover:text-amber-600 text-left pt-1">
                        Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                    </button>
                </div>
            </article>

            <!-- Bài viết 2 -->
            <article data-art-cat="kien-thuc" class="article-card bg-white rounded-xl overflow-hidden border border-gray-200 shadow-xs hover:shadow-md transition flex flex-col">
                <div class="h-44 overflow-hidden bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1Af7EB3SBjLe_s8iOqIpPXchRTWxgZ1cW=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Af7EB3SBjLe_s8iOqIpPXchRTWxgZ1cW&sz=w600';"
                         alt="Rong biển sấy mè và bột đậu rau củ" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
                    <div>
                        <span class="text-[11px] font-bold text-amber-600 uppercase">Kiến thức – Kinh nghiệm</span>
                        <h3 class="text-sm font-bold text-gray-800 mt-1 leading-snug">
                            Rong Biển Sấy Mè & Bột Đậu Rau Củ Thuần Chay – Dinh dưỡng an lành từ thiên nhiên
                        </h3>
                        <p class="text-xs text-gray-600 mt-1.5 leading-relaxed">
                            Sự kết hợp hoàn hảo giữa nguyên liệu thuần chay tự nhiên và công thức chế biến giữ trọn dưỡng chất cho bữa cơm chay nhanh gọn.
                        </p>
                    </div>
                    <button onclick="openArticleDetail(1)" class="text-xs font-bold text-brand-700 hover:text-amber-600 text-left pt-1">
                        Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                    </button>
                </div>
            </article>

            <!-- Bài viết 3 -->
            <article data-art-cat="kien-thuc" class="article-card bg-white rounded-xl overflow-hidden border border-gray-200 shadow-xs hover:shadow-md transition flex flex-col">
                <div class="h-44 overflow-hidden bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1mKK_ykzZThvYd9cFXt3Lx8y8XeAVslPm=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1mKK_ykzZThvYd9cFXt3Lx8y8XeAVslPm&sz=w600';"
                         alt="Granola siêu giòn và Trà hoa ngũ cốc" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
                    <div>
                        <span class="text-[11px] font-bold text-amber-600 uppercase">Kiến thức – Kinh nghiệm</span>
                        <h3 class="text-sm font-bold text-gray-800 mt-1 leading-snug">
                            Cách kết hợp Ngũ cốc hạt Granola & Trà hoa thảo mộc cho bữa sáng thực dưỡng
                        </h3>
                        <p class="text-xs text-gray-600 mt-1.5 leading-relaxed">
                            Bữa sáng healthy chỉ với 3 phút cùng Granola sấy giòn và một tách trà hoa thảo mộc ấm nóng giúp giữ dáng, đẹp da và tràn đầy năng lượng.
                        </p>
                    </div>
                    <button onclick="openArticleDetail(2)" class="text-xs font-bold text-brand-700 hover:text-amber-600 text-left pt-1">
                        Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                    </button>
                </div>
            </article>

            <!-- Bài viết 4 -->
            <article data-art-cat="mam-cung" class="article-card bg-white rounded-xl overflow-hidden border border-gray-200 shadow-xs hover:shadow-md transition flex flex-col">
                <div class="h-44 overflow-hidden bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/14L3ksgau_oWcsirIKr-8UtKLjtaoTDfo=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=14L3ksgau_oWcsirIKr-8UtKLjtaoTDfo&sz=w600';"
                         alt="Mâm cúng chay trọn gói tại Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
                    <div>
                        <span class="text-[11px] font-bold text-brand-600 uppercase">Góc Mâm Cúng Chay</span>
                        <h3 class="text-sm font-bold text-gray-800 mt-1 leading-snug">
                            Gợi ý mâm cúng chay thanh tịnh ngày Rằm, Mùng Một & Lễ Khai Trương tại Đà Nẵng
                        </h3>
                        <p class="text-xs text-gray-600 mt-1.5 leading-relaxed">
                            Trí Huyền Food nhận đặt mâm cúng chay trọn gói chỉn chu, đầy đủ các món chay truyền thống, giao tận nơi đúng giờ tại Đà Nẵng.
                        </p>
                    </div>
                    <button onclick="openArticleDetail(3)" class="text-xs font-bold text-brand-700 hover:text-amber-600 text-left pt-1">
                        Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                    </button>
                </div>
            </article>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC ĐỐI TÁC TIÊU BIỂU CỦA TRÍ HUYỀN FOOD
    =========================================== -->
    <section id="doi-tac" class="container-1500 py-5">
        <div class="flatsome-title-wrap">
            <h2 class="flatsome-title-main text-sm sm:text-base md:text-lg">DANH MỤC ĐỐI TÁC & THƯƠNG HIỆU ĐỒNG HÀNH</h2>
            <span class="text-xs text-gray-500 hidden sm:inline">Hợp tác phân phối thực phẩm chay & nông sản sạch chính hãng</span>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3">
            <div class="bg-white rounded-xl p-3 border border-gray-200 shadow-xs text-center flex flex-col items-center justify-center hover:border-brand-600 transition">
                <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-700 flex items-center justify-center mb-2 font-extrabold text-xs">TD</div>
                <p class="text-xs font-bold text-brand-700">Thuận Duyên Food</p>
                <p class="text-[11px] text-gray-500 mt-0.5">Ngũ cốc & Trà hoa Xứ Quảng</p>
            </div>
            <div class="bg-white rounded-xl p-3 border border-gray-200 shadow-xs text-center flex flex-col items-center justify-center hover:border-brand-600 transition">
                <div class="w-10 h-10 rounded-full bg-amber-50 text-amber-700 flex items-center justify-center mb-2 font-extrabold text-xs">AL</div>
                <p class="text-xs font-bold text-brand-700">Thực Phẩm Chay Âu Lạc</p>
                <p class="text-[11px] text-gray-500 mt-0.5">Đồ chay khô & Gia vị chay</p>
            </div>
            <div class="bg-white rounded-xl p-3 border border-gray-200 shadow-xs text-center flex flex-col items-center justify-center hover:border-brand-600 transition">
                <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-700 flex items-center justify-center mb-2 font-extrabold text-xs">BL</div>
                <p class="text-xs font-bold text-brand-700">Thực Phẩm Chay Bình Loan</p>
                <p class="text-[11px] text-gray-500 mt-0.5">Nguyên liệu chay truyền thống</p>
            </div>
            <div class="bg-white rounded-xl p-3 border border-gray-200 shadow-xs text-center flex flex-col items-center justify-center hover:border-brand-600 transition">
                <div class="w-10 h-10 rounded-full bg-amber-50 text-amber-700 flex items-center justify-center mb-2 font-extrabold text-xs">OCOP</div>
                <p class="text-xs font-bold text-brand-700">Nông Sản Sạch Xứ Quảng</p>
                <p class="text-[11px] text-gray-500 mt-0.5">Đậu hạt thuần tự nhiên</p>
            </div>
            <div class="bg-white rounded-xl p-3 border border-gray-200 shadow-xs text-center flex flex-col items-center justify-center hover:border-brand-600 transition">
                <div class="w-10 h-10 rounded-full bg-brand-50 text-brand-700 flex items-center justify-center mb-2 font-extrabold text-xs">B2B</div>
                <p class="text-xs font-bold text-brand-700">Hệ Thống Quán Chay ĐN</p>
                <p class="text-[11px] text-gray-500 mt-0.5">Cung ứng sỉ nguyên liệu</p>
            </div>
            <div class="bg-white rounded-xl p-3 border border-gray-200 shadow-xs text-center flex flex-col items-center justify-center hover:border-brand-600 transition">
                <div class="w-10 h-10 rounded-full bg-amber-50 text-amber-700 flex items-center justify-center mb-2 font-extrabold text-xs">24/7</div>
                <p class="text-xs font-bold text-brand-700">Đại Lý & CTV Toàn Quốc</p>
                <p class="text-[11px] text-gray-500 mt-0.5">Chính sách chiết khấu tốt</p>
            </div>
        </div>
    </section>

    <!-- ==========================================
         BẢN ĐỒ GOOGLE MAPS & FANPAGE FACEBOOK NGOÀI TRANG CHỦ
         - Địa chỉ: 166 Phạm Hùng, Phường Hòa Xuân, Tp.Đà Nẵng
         - Map link: https://maps.app.goo.gl/4FpvwHrCZdpn7CwS8
         - Fanpage: https://www.facebook.com/TriHuyenFood
    =========================================== -->
    <section id="he-thong-cua-hang" class="container-1500 py-5">
        <div class="flatsome-title-wrap">
            <h2 class="flatsome-title-main text-sm sm:text-base md:text-lg">BẢN ĐỒ ĐƯỜNG ĐI & FANPAGE TRÍ HUYỀN FOOD</h2>
            <a href="https://maps.app.goo.gl/4FpvwHrCZdpn7CwS8" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-brand-700 hover:text-amber-600">
                <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở ứng dụng Google Maps
            </a>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
            <!-- Cột Bản đồ Google Maps ngoài trang chủ (7/12) -->
            <div class="lg:col-span-7 bg-white rounded-xl border border-gray-200 p-3 sm:p-4 shadow-xs flex flex-col justify-between">
                <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                    <div>
                        <h3 class="text-sm sm:text-base font-extrabold text-brand-700">
                            <i class="fa-solid fa-location-dot text-red-600 mr-1.5"></i>TRÍ HUYỀN FOOD – 166 PHẠM HÙNG, PHƯỜNG HÒA XUÂN, TP.ĐÀ NẴNG
                        </h3>
                        <p class="text-xs text-gray-600 mt-0.5">Chuyên sỉ & lẻ thực phẩm chay, ngũ cốc dinh dưỡng, granola, trà hoa thảo mộc, mâm cúng chay</p>
                    </div>
                    <a href="https://maps.app.goo.gl/4FpvwHrCZdpn7CwS8" target="_blank" rel="noopener noreferrer" class="bg-brand-600 hover:bg-brand-700 text-white text-xs font-bold px-3 py-1.5 rounded-lg transition flex items-center gap-1.5">
                        <i class="fa-solid fa-map-location-dot"></i>Chỉ đường Google Maps
                    </a>
                </div>

                <!-- Khung Google Maps trực tiếp ngoài trang chủ -->
                <div class="w-full h-[290px] sm:h-[340px] rounded-xl overflow-hidden border border-gray-200 relative bg-gray-100">
                    <iframe 
                        title="Bản đồ Trí Huyền Food 166 Phạm Hùng, Phường Hòa Xuân, Tp.Đà Nẵng"
                        src="https://maps.google.com/maps?q=166%20Ph%E1%BA%A1m%20H%C3%B9ng,%20H%C3%B2a%20Xu%C3%A2n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                        class="w-full h-full border-0"
                        loading="lazy"
                        referrerpolicy="no-referrer-when-downgrade">
                    </iframe>
                </div>

                <div class="mt-3 pt-2.5 border-t border-gray-100 flex flex-wrap items-center justify-between gap-2 text-xs text-gray-600">
                    <span><i class="fa-solid fa-clock text-brand-600 mr-1"></i>Giờ mở cửa: 06:30 – 21:00 (Tất cả các ngày trong tuần)</span>
                    <a href="tel:0933936939" class="font-bold text-amber-700 hover:underline"><i class="fa-solid fa-phone mr-1"></i>Hotline: 0933.936.939</a>
                </div>
            </div>

            <!-- Cột Fanpage Facebook trực tiếp ngoài trang chủ (5/12) -->
            <div class="lg:col-span-5 bg-white rounded-xl border border-gray-200 p-3 sm:p-4 shadow-xs flex flex-col justify-between">
                <div class="flex items-center justify-between gap-2 mb-3">
                    <div>
                        <h3 class="text-sm sm:text-base font-extrabold text-[#1877F2]">
                            <i class="fa-brands fa-facebook mr-1.5"></i>FANPAGE TRÍ HUYỀN FOOD
                        </h3>
                        <p class="text-xs text-gray-600 mt-0.5">Cập nhật món chay mới & ưu đãi mỗi ngày</p>
                    </div>
                    <a href="https://www.facebook.com/TriHuyenFood" target="_blank" rel="noopener noreferrer" class="bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold px-3 py-1.5 rounded-lg transition">
                        Theo dõi Fanpage
                    </a>
                </div>

                <!-- Khung hiển thị Fanpage kết hợp Plugin Facebook thực tế -->
                <div class="flex-1 flex flex-col justify-between bg-brand-50/50 rounded-xl p-3 border border-brand-100">
                    <div class="flex items-center gap-3 pb-3 border-b border-brand-100">
                        <img src="https://lh3.googleusercontent.com/d/1u-cNx1_9pZUbmGnWgHe_oOmeNUj1oV3P=w150"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1u-cNx1_9pZUbmGnWgHe_oOmeNUj1oV3P&sz=w150';"
                             alt="Avatar Fanpage Trí Huyền Food" class="w-12 h-12 rounded-full object-contain bg-white border border-brand-200 p-0.5 flex-shrink-0">
                        <div class="min-w-0">
                            <a href="https://www.facebook.com/TriHuyenFood" target="_blank" rel="noopener noreferrer" class="text-sm font-extrabold text-gray-900 hover:text-[#1877F2] block truncate">
                                Trí Huyền Food - Thực Phẩm Chay Sạch
                            </a>
                            <p class="text-xs text-gray-500">facebook.com/TriHuyenFood • 5.0 ★</p>
                        </div>
                    </div>

                    <!-- Nhúng Facebook Page Plugin chuẩn responsive -->
                    <div class="my-2.5 w-full overflow-hidden rounded-lg bg-white border border-gray-200 flex justify-center">
                        <iframe 
                            title="Fanpage Facebook Trí Huyền Food"
                            src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FTriHuyenFood&tabs=timeline&width=340&height=210&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                            width="340" 
                            height="210" 
                            style="border:none;overflow:hidden;max-width:100%;" 
                            scrolling="no" 
                            frameborder="0" 
                            allowfullscreen="true" 
                            allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                        </iframe>
                    </div>

                    <div class="grid grid-cols-2 gap-2 pt-1">
                        <a href="https://www.facebook.com/TriHuyenFood" target="_blank" rel="noopener noreferrer" class="bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold py-2 px-3 rounded-lg text-center transition">
                            <i class="fa-brands fa-facebook-f mr-1"></i>Xem Fanpage
                        </a>
                        <a href="https://zalo.me/0933936939" target="_blank" rel="noopener noreferrer" class="bg-brand-600 hover:bg-brand-700 text-white text-xs font-bold py-2 px-3 rounded-lg text-center transition">
                            <i class="fa-solid fa-comment-dots mr-1"></i>Nhắn Zalo Ngay
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (Đầy đủ thông tin như thuanduyen.vn)
    =========================================== -->
    <footer class="bg-brand-800 text-white mt-6 border-t-4 border-amber-500">
        <div class="container-1500 py-8">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-6">
                
                <!-- Cột 1: Thông tin thương hiệu -->
                <div class="lg:col-span-4 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <img src="https://lh3.googleusercontent.com/d/1u-cNx1_9pZUbmGnWgHe_oOmeNUj1oV3P=w150"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1u-cNx1_9pZUbmGnWgHe_oOmeNUj1oV3P&sz=w150';"
                             alt="Logo Trí Huyền Food" class="w-11 h-11 rounded-full bg-white p-0.5 object-contain flex-shrink-0">
                        <div>
                            <h3 class="text-base font-extrabold text-amber-300 tracking-wide">TRÍ HUYỀN FOOD</h3>
                            <p class="text-xs text-emerald-100">Website: trihuyenfood.com</p>
                        </div>
                    </div>
                    <p class="text-xs text-emerald-100 leading-relaxed">
                        Thế giới Thực Phẩm Chay Sạch & Dinh Dưỡng Xanh tại Đà Nẵng. Chuyên phân phối sỉ & lẻ Bột ngũ cốc dinh dưỡng, Ngũ cốc hạt Granola, Trà hoa thảo mộc, Gia vị chay, Đồ chay chế biến sẵn và Mâm cúng chay trọn gói.
                    </p>
                    <div class="space-y-1.5 text-xs text-emerald-100">
                        <p><i class="fa-solid fa-location-dot text-amber-300 w-5"></i>Địa chỉ: 166 Phạm Hùng, Phường Hòa Xuân, Tp.Đà Nẵng</p>
                        <p><i class="fa-solid fa-phone-volume text-amber-300 w-5"></i>Điện thoại / Zalo: <a href="tel:0933936939" class="font-bold text-amber-300 hover:underline">0933.936.939</a></p>
                        <p><i class="fa-solid fa-globe text-amber-300 w-5"></i>Website: <a href="https://trihuyenfood.com" class="hover:underline">https://trihuyenfood.com</a></p>
                    </div>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-amber-300 border-b border-brand-600 pb-2">DANH MỤC SẢN PHẨM</h4>
                    <ul class="space-y-1.5 text-xs text-emerald-100">
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('bot-ngu-coc')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Bột ngũ cốc dinh dưỡng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('granola')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Ngũ cốc hạt, Granola</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('tra-hoa')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Trà hoa thảo mộc</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('thuc-pham-chay')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Thực phẩm & Gia vị chay</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('san-pham-khac')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Mâm cúng chay & Sản phẩm khác</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Hỗ trợ & Chính sách khách hàng -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-amber-300 border-b border-brand-600 pb-2">HỖ TRỢ KHÁCH HÀNG</h4>
                    <ul class="space-y-1.5 text-xs text-emerald-100">
                        <li><a href="#bao-gia" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Đăng ký đại lý & Báo giá sỉ</a></li>
                        <li><a href="#gioi-thieu" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cam kết 100% Thuần chay sạch</a></li>
                        <li><a href="#he-thong-cua-hang" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Chính sách giao hàng tận nơi</a></li>
                        <li><a href="#he-thong-cua-hang" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Chính sách đổi trả & Kiểm hàng</a></li>
                        <li><a href="https://maps.app.goo.gl/4FpvwHrCZdpn7CwS8" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Xem chỉ đường Google Maps</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối nhanh -->
                <div class="lg:col-span-2 space-y-2.5">
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-amber-300 border-b border-brand-600 pb-2">KẾT NỐI VỚI CHÚNG TÔI</h4>
                    <p class="text-xs text-emerald-100">Liên hệ đặt hàng nhanh qua Hotline, Zalo hoặc Fanpage chính thức:</p>
                    <div class="flex flex-col gap-2 pt-1">
                        <a href="tel:0933936939" class="bg-amber-500 hover:bg-amber-400 text-gray-900 font-extrabold text-xs py-2 px-3 rounded-lg text-center transition">
                            <i class="fa-solid fa-phone-volume mr-1"></i>0933.936.939
                        </a>
                        <a href="https://zalo.me/0933936939" target="_blank" rel="noopener noreferrer" class="bg-blue-600 hover:bg-blue-500 text-white font-bold text-xs py-2 px-3 rounded-lg text-center transition">
                            Chat Zalo Tư Vấn
                        </a>
                        <a href="https://www.facebook.com/TriHuyenFood" target="_blank" rel="noopener noreferrer" class="bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs py-2 px-3 rounded-lg text-center transition">
                            Fanpage Facebook
                        </a>
                    </div>
                </div>

            </div>
        </div>

        <div class="bg-[#0f2e1a] py-3 text-center text-[11px] text-emerald-200 border-t border-brand-700">
            <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
                <p>© Bản quyền thuộc về <strong>Trí Huyền Food (trihuyenfood.com)</strong> – 166 Phạm Hùng, Phường Hòa Xuân, Tp.Đà Nẵng.</p>
                <p>Thiết kế chuẩn bố cục <strong>Flatsome UX Builder</strong> • Hotline: 0933.936.939</p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CỤM NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên cả Máy tính và Điện thoại, không gây tràn viền
    =========================================== -->
    <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0933936939" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0933.936.939" class="group flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white rounded-full p-1.5 sm:pr-3.5 shadow-lg transition">
            <span class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-white text-blue-600 font-extrabold text-xs flex items-center justify-center flex-shrink-0 shadow-xs">
                Zalo
            </span>
            <span class="hidden sm:inline text-xs font-bold">Chat Zalo</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com/TriHuyenFood" target="_blank" rel="noopener noreferrer" aria-label="Fanpage Facebook Trí Huyền Food" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full p-1.5 sm:pr-3.5 shadow-lg transition">
            <span class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-white text-[#1877F2] flex items-center justify-center flex-shrink-0 shadow-xs">
                <i class="fa-brands fa-facebook-f text-base"></i>
            </span>
            <span class="hidden sm:inline text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Gọi Hotline nổi bật -->
        <a href="tel:0933936939" aria-label="Gọi Hotline 0933.936.939" class="floating-btn-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full p-1.5 pr-3 sm:pr-4 shadow-xl transition">
            <span class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-amber-400 text-gray-900 flex items-center justify-center flex-shrink-0">
                <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
            </span>
            <div class="leading-tight text-left">
                <span class="block text-[10px] text-amber-200 font-semibold">Hotline 24/7</span>
                <span class="block text-xs sm:text-sm font-extrabold">0933.936.939</span>
            </div>
        </a>
    </div>

    <!-- ==========================================
         MODAL XEM CHI TIẾT SẢN PHẨM & ĐẶT HÀNG NHANH
    =========================================== -->
    <div id="productDetailModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-3 bg-black/60 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-2xl w-full overflow-hidden shadow-2xl border border-gray-100 max-h-[90vh] flex flex-col">
            <div class="px-4 py-3 bg-brand-700 text-white flex items-center justify-between">
                <h3 id="modalProdTitleHeader" class="text-xs sm:text-sm font-bold truncate pr-2">Chi tiết sản phẩm</h3>
                <button onclick="closeProductModal()" class="text-white hover:text-amber-300 p-1"><i class="fa-solid fa-xmark text-lg"></i></button>
            </div>
            <div id="modalProdBody" class="p-4 sm:p-5 overflow-y-auto"></div>
        </div>
    </div>

    <!-- ==========================================
         MODAL ĐỌC BÀI VIẾT CHI TIẾT
    =========================================== -->
    <div id="articleDetailModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-3 bg-black/60 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-2xl w-full overflow-hidden shadow-2xl border border-gray-100 max-h-[90vh] flex flex-col">
            <div class="px-4 py-3 bg-brand-700 text-white flex items-center justify-between">
                <h3 class="text-xs sm:text-sm font-bold">Chuyên mục Tin tức & Kiến thức Chay – Trí Huyền Food</h3>
                <button onclick="closeArticleModal()" class="text-white hover:text-amber-300 p-1"><i class="fa-solid fa-xmark text-lg"></i></button>
            </div>
            <div id="articleModalBody" class="p-4 sm:p-6 overflow-y-auto space-y-3"></div>
        </div>
    </div>

    <!-- ==========================================
         MODAL GIỎ HÀNG & ĐẶT HÀNG QUA ZALO / SĐT
    =========================================== -->
    <div id="cartModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-3 bg-black/60 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-lg w-full overflow-hidden shadow-2xl border border-gray-100 max-h-[90vh] flex flex-col">
            <div class="px-4 py-3 bg-brand-700 text-white flex items-center justify-between">
                <h3 class="text-sm font-bold"><i class="fa-solid fa-basket-shopping mr-1.5 text-amber-300"></i>Giỏ Hàng Của Bạn Tại Trí Huyền Food</h3>
                <button onclick="closeCartModal()" class="text-white hover:text-amber-300 p-1"><i class="fa-solid fa-xmark text-lg"></i></button>
            </div>
            <div id="cartItemsContainer" class="p-4 overflow-y-auto space-y-3 flex-1"></div>
            <div class="p-4 bg-brand-50 border-t border-brand-100 space-y-3">
                <div class="flex items-center justify-between text-sm font-extrabold text-brand-800">
                    <span>Tổng tạm tính:</span>
                    <span id="cartTotalAmount" class="text-red-600 text-base">0 ₫</span>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-2">
                    <input id="checkoutCustomerName" type="text" placeholder="Họ tên người nhận..." class="px-3 py-2 text-xs rounded-lg border border-gray-300 bg-white focus:outline-none focus:border-brand-600">
                    <input id="checkoutCustomerPhone" type="tel" placeholder="Số điện thoại liên hệ..." class="px-3 py-2 text-xs rounded-lg border border-gray-300 bg-white focus:outline-none focus:border-brand-600">
                </div>
                <input id="checkoutCustomerAddress" type="text" placeholder="Địa chỉ nhận hàng (VD: 166 Phạm Hùng, Hòa Xuân, Đà Nẵng)..." class="w-full px-3 py-2 text-xs rounded-lg border border-gray-300 bg-white focus:outline-none focus:border-brand-600">
                <button onclick="submitCartOrder()" class="w-full bg-brand-600 hover:bg-brand-700 text-white font-extrabold text-xs sm:text-sm py-2.5 rounded-lg transition shadow-xs">
                    <i class="fa-solid fa-paper-plane mr-1.5"></i>XÁC NHẬN ĐẶT HÀNG NHANH (HOTLINE: 0933.936.939)
                </button>
            </div>
        </div>
    </div>

    <!-- ==========================================
         TOAST THÔNG BÁO THÂN THIỆN (Thay thế hoàn toàn alert)
    =========================================== -->
    <div id="toastMessage" class="fixed top-4 right-4 z-50 hidden max-w-xs bg-brand-800 text-white px-4 py-3 rounded-xl shadow-xl border border-amber-400 text-xs font-semibold flex items-center gap-2.5">
        <i class="fa-solid fa-circle-check text-amber-400 text-base"></i>
        <span id="toastText">Đã cập nhật!</span>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU 11 SẢN PHẨM THỰC TẾ & TƯƠNG TÁC
    =========================================== -->
    <script>
        // Danh sách 11 sản phẩm thực tế lấy từ đúng 11 file Google Drive khách hàng cung cấp
        // Phân loại đúng theo danh mục của web mẫu thuanduyen.vn và fanpage Trí Huyền Food
        const PRODUCTS = [
            {
                id: 1,
                driveId: '1ZR7Mg96mM-WlNAnqSKMwrNVPrXYEyUgJ',
                name: 'Ngũ Cốc Dinh Dưỡng Thuận Duyên Gold 20 Loại Hạt Quý (Hộp 500g)',
                category: 'bot-ngu-coc',
                categoryLabel: 'Bột ngũ cốc dinh dưỡng',
                oldPrice: 180000,
                price: 160000,
                discountPercent: 11,
                desc: 'Kết hợp 20 loại hạt dinh dưỡng cao cấp (Óc chó, Macca, Hạnh nhân, Hạt sen, Đậu đen xanh lòng, Gạo lứt huyết rồng...). Đạt chuẩn HACCP, cam kết 4 KHÔNG: Không chất bảo quản, không đường tinh luyện, không phẩm màu và không đậu nành biến đổi gen.'
            },
            {
                id: 2,
                driveId: '1hmoc1cZYKwpDB5bO7EFdsihLXfxl6S7Z',
                name: 'Bột Đậu Rau Củ Thuần Chay Xứ Quảng Đậm Vị Tự Nhiên (Hộp 500g)',
                category: 'bot-ngu-coc',
                categoryLabel: 'Bột ngũ cốc dinh dưỡng',
                oldPrice: 165000,
                price: 145000,
                discountPercent: 12,
                desc: 'Món quà dinh dưỡng an lành từ nông sản Xứ Quảng, công thức kết hợp đặc biệt từ các loại đậu quê và rau củ sấy lạnh thuần tự nhiên, bổ sung chất xơ và vitamin thiết yếu cho cả gia đình.'
            },
            {
                id: 3,
                driveId: '1mKK_ykzZThvYd9cFXt3Lx8y8XeAVslPm',
                name: 'Ngũ Cốc Hạt Granola Siêu Giòn Cao Cấp Ăn Kiêng & Giữ Dáng (500g)',
                category: 'granola',
                categoryLabel: 'Ngũ cốc hạt, Granola',
                oldPrice: 170000,
                price: 150000,
                discountPercent: 12,
                desc: 'Được kết hợp từ hơn 10 loại hạt và quả sấy cao cấp (Hạnh nhân, hạt điều, bí xanh, óc chó, yến mạch nướng mật ong hoa rừng), giòn rụm thơm ngon, dùng ăn trực tiếp hoặc trộn sữa chua, sữa hạt cho bữa sáng healthy.'
            },
            {
                id: 4,
                driveId: '1Lmz-0e272vK09fP1DlJ2-PdI1coIxUku',
                name: 'Bánh Hạt Dinh Dưỡng 9 Loại Hạt & Gạo Lứt Huyết Rồng (Gói 250g)',
                category: 'granola',
                categoryLabel: 'Ngũ cốc hạt, Granola',
                oldPrice: 110000,
                price: 95000,
                discountPercent: 14,
                desc: 'Bánh thuyền hạt dinh dưỡng kết hợp hạt điều, hạnh nhân, hạt bí xanh, mè đen, gạo lứt huyết rồng giòn tan. Giải pháp tuyệt vời cho bữa sáng nhanh gọn và bữa phụ lành mạnh trong ngày.'
            },
            {
                id: 5,
                driveId: '1NskR8jA4UVo8oMtCPykxKyl_k82C8WB9',
                name: 'Trà Hoa Ngũ Cốc Thảo Mộc Thuận Duyên Thanh Nhiệt An Thần (500g)',
                category: 'tra-hoa',
                categoryLabel: 'Trà hoa thảo mộc',
                oldPrice: 135000,
                price: 120000,
                discountPercent: 11,
                desc: 'Thức uống thanh lọc cơ thể từ 07 nguyên liệu thuần nông nghiệp: đậu đỏ, đậu đen xanh lòng, gạo lứt huyết rồng, hạt muồng, lá sen, gừng sẻ và hoa cúc vàng giúp ngủ ngon, mát gan, đẹp da.'
            },
            {
                id: 6,
                driveId: '1Af7EB3SBjLe_s8iOqIpPXchRTWxgZ1cW',
                name: 'Rong Biển Sấy Mè Thuần Chay Giòn Ngon Ăn Liền Tiện Lợi (Hũ 200g)',
                category: 'thuc-pham-chay',
                categoryLabel: 'Thực phẩm & Gia vị chay',
                oldPrice: 95000,
                price: 80000,
                discountPercent: 16,
                desc: 'Rong biển tươi tuyển chọn sấy giòn cùng mè rang thơm lừng và gia vị chay thanh đạm. Dùng ăn liền với cơm nóng, cháo trắng, cuộn cơm hoặc làm món ăn vặt giàu khoáng chất cho trẻ nhỏ và người ăn chay.'
            },
            {
                id: 7,
                driveId: '1CM_kN5vqNt5BB9XoiY-T9dFHty4hoqBe',
                name: 'Hạt Nêm Nấm Hương & Gia Vị Chay Tự Nhiên Thanh Đạm (Gói 400g)',
                category: 'thuc-pham-chay',
                categoryLabel: 'Thực phẩm & Gia vị chay',
                oldPrice: 85000,
                price: 72000,
                discountPercent: 15,
                desc: 'Chiết xuất từ nấm hương, hạt sen, củ cải và rau củ tự nhiên giúp món canh, món kho, món xào chay ngọt thanh tròn vị mà không cần dùng bột ngọt công nghiệp.'
            },
            {
                id: 8,
                driveId: '1ViHgp5bQf5DLt-E2wBjNx8gYncZ4vfnX',
                name: 'Chao Môn Đặc Sản & Sốt Gia Vị Chay Đậm Đà Truyền Thống (Hũ 350g)',
                category: 'thuc-pham-chay',
                categoryLabel: 'Thực phẩm & Gia vị chay',
                oldPrice: 65000,
                price: 55000,
                discountPercent: 15,
                desc: 'Chao khoai môn lên men tự nhiên béo mịn, thơm dịu, dùng làm nước chấm rau củ luộc, đậu hũ chiên hoặc ướp các món kho, món nướng chay đậm đà chuẩn vị.'
            },
            {
                id: 9,
                driveId: '1uJrVhVwB7TaFWN8fdR1QoTVKEThGRncQ',
                name: 'Chả Lụa Chay & Thực Phẩm Chay Tươi Ngon Chế Biến Sẵn (Đòn 500g)',
                category: 'thuc-pham-chay',
                categoryLabel: 'Thực phẩm & Gia vị chay',
                oldPrice: 90000,
                price: 75000,
                discountPercent: 17,
                desc: 'Làm từ đạm đậu nành non và nấm tươi gói lá chuối truyền thống, dai giòn tự nhiên, không hàn the. Thích hợp bày mâm cỗ chay, ăn kèm bánh mì, bún, phở hoặc kho tiêu.'
            },
            {
                id: 10,
                driveId: '14L3ksgau_oWcsirIKr-8UtKLjtaoTDfo',
                name: 'Mâm Cúng Chay Trọn Gói Đà Nẵng Đầy Đủ Món Chay Thanh Tịnh',
                category: 'san-pham-khac',
                categoryLabel: 'Mâm cúng & Sản phẩm khác',
                oldPrice: 650000,
                price: 550000,
                discountPercent: 15,
                desc: 'Trí Huyền Food nhận đặt mâm cúng chay trọn gói ngày Rằm, Mùng Một, Lễ Khai Trương, Tân Gia, Cầu An tại Đà Nẵng. Món chay nấu mới trong ngày, trình bày trang nghiêm, giao tận nơi đúng giờ.'
            },
            {
                id: 11,
                driveId: '1tTxgQq3GowoNqq0x7wy3BmnzIElSKEYg',
                name: 'Bún Trộn Chay & Món Chay Dưỡng Sinh Tiện Lợi Mỗi Ngày (Phần Gia Đình)',
                category: 'san-pham-khac',
                categoryLabel: 'Mâm cúng & Sản phẩm khác',
                oldPrice: 75000,
                price: 65000,
                discountPercent: 13,
                desc: 'Sự kết hợp hài hòa giữa bún tươi, tàu hũ ky giòn, chả chay, rau củ tươi sạch và nước sốt trộn chay đậm đà độc quyền tại Trí Huyền Food 166 Phạm Hùng, Hòa Xuân, Đà Nẵng.'
            }
        ];

        // Dữ liệu chi tiết 4 bài viết
        const ARTICLES = [
            {
                title: 'Ngũ cốc Dinh dưỡng Gold 20 loại hạt – Bí quyết sống khỏe từ mầm xanh Xứ Quảng',
                category: 'Tin tức – Hoạt động',
                img: 'https://lh3.googleusercontent.com/d/1ZR7Mg96mM-WlNAnqSKMwrNVPrXYEyUgJ=w700',
                content: 'Ngũ cốc Dinh dưỡng Thuận Duyên Gold được phân phối chính hãng tại Trí Huyền Food (166 Phạm Hùng, Phường Hòa Xuân, Tp.Đà Nẵng) là sự kết tinh từ 20 loại hạt dinh dưỡng cao cấp: Óc chó, Macca, Hạnh nhân, Hạt điều, Hạt sen, Đậu đen xanh lòng, Gạo lứt huyết rồng... Sản phẩm đạt tiêu chuẩn HACCP, cam kết 4 KHÔNG an toàn cho người lớn tuổi, mẹ bầu, trẻ nhỏ và người ăn chay trường.'
            },
            {
                title: 'Rong Biển Sấy Mè & Bột Đậu Rau Củ Thuần Chay – Dinh dưỡng an lành từ thiên nhiên',
                category: 'Kiến thức – Kinh nghiệm',
                img: 'https://lh3.googleusercontent.com/d/1Af7EB3SBjLe_s8iOqIpPXchRTWxgZ1cW=w700',
                content: 'Với nhịp sống bận rộn hiện nay, việc chuẩn bị bữa ăn chay vừa nhanh gọn vừa đủ chất là mối quan tâm của nhiều gia đình. Rong biển sấy mè giòn rụm kết hợp cùng ly Bột đậu rau củ thuần chay mỗi sáng giúp bổ sung canxi, sắt, chất xơ tự nhiên mà không tốn nhiều thời gian chế biến.'
            },
            {
                title: 'Cách kết hợp Ngũ cốc hạt Granola & Trà hoa thảo mộc cho bữa sáng thực dưỡng',
                category: 'Kiến thức – Kinh nghiệm',
                img: 'https://lh3.googleusercontent.com/d/1mKK_ykzZThvYd9cFXt3Lx8y8XeAVslPm=w700',
                content: 'Chỉ cần 3-4 muỗng Ngũ cốc hạt Granola sấy giòn ăn kèm sữa hạt hoặc sữa chua, thưởng thức cùng một tách Trà hoa ngũ cốc thảo mộc ấm nóng là bạn đã có ngay bữa sáng Eat Clean thanh nhẹ, giữ dáng và tốt cho hệ tiêu hóa.'
            },
            {
                title: 'Gợi ý mâm cúng chay thanh tịnh ngày Rằm, Mùng Một & Lễ Khai Trương tại Đà Nẵng',
                category: 'Góc Mâm Cúng Chay',
                img: 'https://lh3.googleusercontent.com/d/14L3ksgau_oWcsirIKr-8UtKLjtaoTDfo=w700',
                content: 'Cúng chay thể hiện lòng thành kính và tâm hướng thiện. Trí Huyền Food chuyên nhận đặt mâm cúng chay trọn gói theo yêu cầu tại Đà Nẵng với thực đơn phong phú: Xôi đậu hạt sen, chả lụa chay, nem chay, canh nấm hạt sen, rau củ xào ngũ sắc... Liên hệ ngay Hotline/Zalo 0933.936.939 để được tư vấn chu đáo.'
            }
        ];

        let cart = [];
        let currentBannerIndex = 0;
        let bannerInterval = null;

        function formatVND(amount) {
            return amount.toLocaleString('vi-VN') + ' ₫';
        }

        // Tạo thẻ sản phẩm chuẩn Flatsome:
        // - Chỉ có duy nhất badge % giảm giá hình tròn ở góc trên bên trái
        // - Không có nhãn dán dư thừa ở trang chủ
        // - Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn viền
        function createFlatsomeProductCard(product) {
            const imgUrl = `https://lh3.googleusercontent.com/d/${product.driveId}=w500`;
            const fallbackUrl = `https://drive.google.com/thumbnail?id=${product.driveId}&sz=w500`;

            return `
                <div class="bg-white rounded-xl border border-gray-200 shadow-xs hover:shadow-md transition flex flex-col justify-between overflow-hidden group">
                    <div>
                        <!-- Khung ảnh vuông chuẩn Flatsome + Badge % giảm giá góc trên bên trái -->
                        <div onclick="openProductModal(${product.id})" class="relative w-full aspect-square bg-gray-50 overflow-hidden cursor-pointer border-b border-gray-100">
                            <span class="badge-flatsome-sale">-${product.discountPercent}%</span>
                            <img src="${imgUrl}" 
                                 onerror="this.onerror=null;this.src='${fallbackUrl}';" 
                                 alt="${product.name}" 
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        </div>

                        <!-- Thông tin sản phẩm: Tên hiển thị đầy đủ không cắt chữ, không tràn ra ngoài -->
                        <div class="p-2.5 sm:p-3.5">
                            <p class="text-[10px] sm:text-[11px] text-gray-500 uppercase font-medium mb-1 break-words">${product.categoryLabel}</p>
                            <h3 onclick="openProductModal(${product.id})" class="text-xs sm:text-sm font-bold text-gray-800 hover:text-brand-600 cursor-pointer leading-snug break-words">
                                ${product.name}
                            </h3>
                        </div>
                    </div>

                    <!-- Giá gốc gạch ngang + Giá khuyến mãi + Nút Thêm vào giỏ chuẩn Flatsome -->
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-gray-50 flex flex-col gap-2">
                        <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                            <span class="text-[11px] sm:text-xs text-gray-400 line-through">${formatVND(product.oldPrice)}</span>
                            <span class="text-xs sm:text-sm font-extrabold text-brand-sale">${formatVND(product.price)}</span>
                        </div>
                        <div class="grid grid-cols-2 gap-1.5">
                            <button onclick="addToCart(${product.id})" class="bg-brand-600 hover:bg-brand-700 text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition text-center">
                                + Giỏ hàng
                            </button>
                            <button onclick="openProductModal(${product.id})" class="bg-brand-50 hover:bg-brand-100 text-brand-700 border border-brand-200 text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded-lg transition text-center">
                                Chi tiết
                            </button>
                        </div>
                    </div>
                </div>
            `;
        }

        function renderAllProductSections(filterCat = 'all', searchKeyword = '') {
            const mainGrid = document.getElementById('productGridContainer');
            const titleEl = document.getElementById('currentCategoryTitle');

            let filtered = PRODUCTS;
            if (filterCat !== 'all') {
                filtered = PRODUCTS.filter(p => p.category === filterCat);
            }
            if (searchKeyword.trim() !== '') {
                const kw = searchKeyword.toLowerCase().trim();
                filtered = filtered.filter(p =>
                    p.name.toLowerCase().includes(kw) ||
                    p.categoryLabel.toLowerCase().includes(kw) ||
                    p.desc.toLowerCase().includes(kw)
                );
            }

            const catNames = {
                'all': 'SẢN PHẨM NỔI BẬT TẠI TRÍ HUYỀN FOOD',
                'bot-ngu-coc': 'DANH MỤC: BỘT NGŨ CỐC DINH DƯỠNG',
                'granola': 'DANH MỤC: NGŨ CỐC HẠT, GRANOLA',
                'tra-hoa': 'DANH MỤC: TRÀ HOA THẢO MỘC',
                'thuc-pham-chay': 'DANH MỤC: THỰC PHẨM & GIA VỊ CHAY',
                'san-pham-khac': 'DANH MỤC: MÂM CÚNG CHAY & SẢN PHẨM KHÁC'
            };

            if (titleEl) {
                titleEl.textContent = catNames[filterCat] || 'SẢN PHẨM NỔI BẬT TẠI TRÍ HUYỀN FOOD';
            }

            if (mainGrid) {
                if (filtered.length === 0) {
                    mainGrid.innerHTML = `
                        <div class="col-span-full bg-white rounded-xl p-6 text-center border border-gray-200">
                            <p class="text-sm font-semibold text-gray-600">Không tìm thấy sản phẩm phù hợp với từ khóa của bạn.</p>
                            <button onclick="filterCategory('all')" class="mt-3 bg-brand-600 text-white text-xs font-bold px-4 py-2 rounded-lg">Xem tất cả 11 sản phẩm</button>
                        </div>
                    `;
                } else {
                    mainGrid.innerHTML = filtered.map(createFlatsomeProductCard).join('');
                }
            }

            // Render 2 khu vực chuyên mục giống web mẫu thuanduyen.vn
            const cerealGranolaList = PRODUCTS.filter(p => p.category === 'bot-ngu-coc' || p.category === 'granola');
            const cerealGrid = document.getElementById('cerealGranolaGrid');
            if (cerealGrid) {
                cerealGrid.innerHTML = cerealGranolaList.map(createFlatsomeProductCard).join('');
            }

            const teaVeganOtherList = PRODUCTS.filter(p => p.category === 'tra-hoa' || p.category === 'thuc-pham-chay' || p.category === 'san-pham-khac');
            const teaGrid = document.getElementById('teaVeganOtherGrid');
            if (teaGrid) {
                teaGrid.innerHTML = teaVeganOtherList.map(createFlatsomeProductCard).join('');
            }
        }

        function filterCategory(catKey) {
            renderAllProductSections(catKey, '');
            document.querySelectorAll('.cat-card-btn').forEach(btn => {
                btn.classList.remove('bg-brand-600', 'text-white', 'border-brand-600');
                btn.classList.add('bg-white', 'text-gray-800', 'border-gray-200');
            });
            const activeCard = document.getElementById('catCard-' + catKey);
            if (activeCard) {
                activeCard.classList.remove('bg-white', 'text-gray-800', 'border-gray-200');
                activeCard.classList.add('bg-brand-600', 'text-white', 'border-brand-600');
            }
            const targetSection = document.getElementById('danh-muc-san-pham');
            if (targetSection) {
                targetSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
        }

        function handleSearchProduct(keyword) {
            renderAllProductSections('all', keyword);
        }

        // Lọc danh mục bài viết
        function filterArticles(cat) {
            document.querySelectorAll('.art-tab-btn').forEach(btn => {
                btn.className = 'art-tab-btn px-2.5 py-1 rounded text-xs font-semibold bg-white text-gray-700 border border-gray-200';
            });
            const activeBtn = document.getElementById('artTab-' + cat);
            if (activeBtn) {
                activeBtn.className = 'art-tab-btn px-2.5 py-1 rounded text-xs font-bold bg-brand-600 text-white';
            }
            document.querySelectorAll('.article-card').forEach(card => {
                if (cat === 'all' || card.getAttribute('data-art-cat') === cat) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // Điều khiển Banner tự trượt 2 slides kích thước bằng nhau
        function showBannerSlide(index) {
            const desktopSlides = document.querySelectorAll('.banner-slide-desktop');
            const mobileSlides = document.querySelectorAll('.banner-slide-mobile');
            const total = 2;
            currentBannerIndex = (index + total) % total;

            desktopSlides.forEach((slide, idx) => {
                if (idx === currentBannerIndex) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            mobileSlides.forEach((slide, idx) => {
                if (idx === currentBannerIndex) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            const dot0 = document.getElementById('bannerDot0');
            const dot1 = document.getElementById('bannerDot1');
            if (dot0 && dot1) {
                if (currentBannerIndex === 0) {
                    dot0.className = 'w-5 h-1.5 rounded-full bg-amber-400 transition-all';
                    dot1.className = 'w-2 h-1.5 rounded-full bg-white/60 transition-all';
                } else {
                    dot1.className = 'w-5 h-1.5 rounded-full bg-amber-400 transition-all';
                    dot0.className = 'w-2 h-1.5 rounded-full bg-white/60 transition-all';
                }
            }
        }

        function changeBannerSlide(step) {
            showBannerSlide(currentBannerIndex + step);
            resetBannerAutoSlide();
        }

        function setBannerSlide(index) {
            showBannerSlide(index);
            resetBannerAutoSlide();
        }

        function resetBannerAutoSlide() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                showBannerSlide(currentBannerIndex + 1);
            }, 4500);
        }

        // Mở/Đóng Menu Mobile
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            if (drawer) drawer.classList.toggle('hidden');
        }

        // Xem chi tiết sản phẩm
        function openProductModal(productId) {
            const p = PRODUCTS.find(item => item.id === productId);
            if (!p) return;

            const imgUrl = `https://lh3.googleusercontent.com/d/${p.driveId}=w700`;
            const fallbackUrl = `https://drive.google.com/thumbnail?id=${p.driveId}&sz=w700`;

            const titleHeader = document.getElementById('modalProdTitleHeader');
            const modalBody = document.getElementById('modalProdBody');
            const modal = document.getElementById('productDetailModal');

            if (titleHeader) titleHeader.textContent = p.name;
            if (modalBody) {
                modalBody.innerHTML = `
                    <div class="grid grid-cols-1 sm:grid-cols-12 gap-4 items-center">
                        <div class="sm:col-span-5 relative rounded-xl overflow-hidden border border-gray-200 aspect-square bg-gray-50">
                            <span class="badge-flatsome-sale">-${p.discountPercent}%</span>
                            <img src="${imgUrl}" onerror="this.onerror=null;this.src='${fallbackUrl}';" alt="${p.name}" class="w-full h-full object-cover">
                        </div>
                        <div class="sm:col-span-7 space-y-2.5">
                            <span class="inline-block text-[11px] font-bold uppercase text-brand-700 bg-brand-50 px-2.5 py-1 rounded border border-brand-100">${p.categoryLabel}</span>
                            <h4 class="text-sm sm:text-base font-extrabold text-gray-900 leading-snug">${p.name}</h4>
                            <div class="flex items-baseline gap-2.5">
                                <span class="text-xs text-gray-400 line-through">${formatVND(p.oldPrice)}</span>
                                <span class="text-base sm:text-lg font-extrabold text-brand-sale">${formatVND(p.price)}</span>
                            </div>
                            <p class="text-xs text-gray-600 leading-relaxed">${p.desc}</p>
                            <div class="p-2.5 rounded-lg bg-brand-50 border border-brand-100 text-xs text-gray-700 space-y-1">
                                <p><i class="fa-solid fa-location-dot text-brand-600 mr-1.5"></i><strong>Cửa hàng:</strong> 166 Phạm Hùng, Phường Hòa Xuân, Tp.Đà Nẵng</p>
                                <p><i class="fa-solid fa-phone text-brand-600 mr-1.5"></i><strong>Đặt nhanh Sỉ & Lẻ:</strong> 0933.936.939</p>
                            </div>
                            <div class="flex flex-wrap gap-2 pt-2">
                                <button onclick="addToCart(${p.id}); closeProductModal();" class="flex-1 bg-brand-600 hover:bg-brand-700 text-white text-xs font-extrabold py-2.5 px-4 rounded-lg transition">
                                    <i class="fa-solid fa-cart-plus mr-1.5"></i>THÊM VÀO GIỎ HÀNG
                                </button>
                                <a href="https://zalo.me/0933936939" target="_blank" rel="noopener noreferrer" class="bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold py-2.5 px-4 rounded-lg transition">
                                    Đặt Qua Zalo
                                </a>
                            </div>
                        </div>
                    </div>
                `;
            }
            if (modal) modal.classList.remove('hidden');
        }

        function closeProductModal() {
            const modal = document.getElementById('productDetailModal');
            if (modal) modal.classList.add('hidden');
        }

        // Xem chi tiết bài viết
        function openArticleDetail(idx) {
            const art = ARTICLES[idx];
            if (!art) return;
            const bodyEl = document.getElementById('articleModalBody');
            const modal = document.getElementById('articleDetailModal');
            if (bodyEl) {
                bodyEl.innerHTML = `
                    <span class="text-xs font-bold uppercase text-brand-600">${art.category}</span>
                    <h4 class="text-base sm:text-lg font-extrabold text-gray-900 leading-snug">${art.title}</h4>
                    <img src="${art.img}" alt="${art.title}" class="w-full h-56 object-cover rounded-xl border border-gray-200 my-2">
                    <p class="text-xs sm:text-sm text-gray-700 leading-relaxed">${art.content}</p>
                    <div class="p-3 rounded-xl bg-brand-50 border border-brand-100 text-xs text-gray-700">
                        <p class="font-bold text-brand-700">TRÍ HUYỀN FOOD – THẾ GIỚI THỰC PHẨM CHAY SẠCH</p>
                        <p>Địa chỉ: 166 Phạm Hùng, Phường Hòa Xuân, Tp.Đà Nẵng | Hotline/Zalo: 0933.936.939</p>
                    </div>
                `;
            }
            if (modal) modal.classList.remove('hidden');
        }

        function closeArticleModal() {
            const modal = document.getElementById('articleDetailModal');
            if (modal) modal.classList.add('hidden');
        }

        // Giỏ hàng
        function addToCart(productId) {
            const product = PRODUCTS.find(p => p.id === productId);
            if (!product) return;
            const existing = cart.find(item => item.id === productId);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ ...product, qty: 1 });
            }
            updateCartBadge();
            showToast(`Đã thêm "${product.name}" vào giỏ hàng!`);
        }

        function updateCartBadge() {
            const count = cart.reduce((sum, item) => sum + item.qty, 0);
            const badge = document.getElementById('cartCountBadge');
            if (badge) badge.textContent = count;
        }

        function openCartModal() {
            renderCartItems();
            const modal = document.getElementById('cartModal');
            if (modal) modal.classList.remove('hidden');
        }

        function closeCartModal() {
            const modal = document.getElementById('cartModal');
            if (modal) modal.classList.add('hidden');
        }

        function changeCartQty(productId, delta) {
            const idx = cart.findIndex(i => i.id === productId);
            if (idx === -1) return;
            cart[idx].qty += delta;
            if (cart[idx].qty <= 0) {
                cart.splice(idx, 1);
            }
            updateCartBadge();
            renderCartItems();
        }

        function renderCartItems() {
            const container = document.getElementById('cartItemsContainer');
            const totalEl = document.getElementById('cartTotalAmount');
            if (!container || !totalEl) return;

            if (cart.length === 0) {
                container.innerHTML = `<p class="text-xs text-gray-500 text-center py-6">Giỏ hàng của bạn đang trống. Hãy chọn sản phẩm chay yêu thích nhé!</p>`;
                totalEl.textContent = '0 ₫';
                return;
            }
            let total = 0;
            container.innerHTML = cart.map(item => {
                const sub = item.price * item.qty;
                total += sub;
                return `
                    <div class="flex items-center justify-between gap-2 p-2.5 rounded-xl border border-gray-200 bg-white">
                        <div class="min-w-0 flex-1">
                            <p class="text-xs font-bold text-gray-800 leading-snug">${item.name}</p>
                            <p class="text-xs text-brand-sale font-semibold mt-0.5">${formatVND(item.price)} x ${item.qty}</p>
                        </div>
                        <div class="flex items-center gap-1.5">
                            <button onclick="changeCartQty(${item.id}, -1)" class="w-6 h-6 rounded bg-gray-100 hover:bg-gray-200 text-xs font-bold">-</button>
                            <span class="text-xs font-bold w-5 text-center">${item.qty}</span>
                            <button onclick="changeCartQty(${item.id}, 1)" class="w-6 h-6 rounded bg-brand-600 text-white text-xs font-bold">+</button>
                        </div>
                    </div>
                `;
            }).join('');
            totalEl.textContent = formatVND(total);
        }

        function submitCartOrder() {
            if (cart.length === 0) {
                showToast('Vui lòng chọn ít nhất 1 sản phẩm trước khi đặt hàng!');
                return;
            }
            const nameEl = document.getElementById('checkoutCustomerName');
            const phoneEl = document.getElementById('checkoutCustomerPhone');
            const name = nameEl ? nameEl.value.trim() : '';
            const phone = phoneEl ? phoneEl.value.trim() : '';
            if (!name || !phone) {
                showToast('Vui lòng nhập Họ tên và Số điện thoại nhận hàng!');
                return;
            }
            cart = [];
            updateCartBadge();
            closeCartModal();
            showToast(`Cảm ơn ${name}! Trí Huyền Food (0933.936.939) đã nhận đơn và sẽ gọi xác nhận ngay.`);
        }

        // Xử lý gửi Form Báo Giá
        function submitQuoteForm(e) {
            e.preventDefault();
            const nameEl = document.getElementById('quoteName');
            const phoneEl = document.getElementById('quotePhone');
            const catEl = document.getElementById('quoteCategory');
            const formEl = document.getElementById('quoteRequestForm');

            const name = nameEl ? nameEl.value.trim() : '';
            const phone = phoneEl ? phoneEl.value.trim() : '';
            const cat = catEl ? catEl.value : '';
            showToast(`Đã gửi yêu cầu báo giá "${cat}" của ${name} (${phone}). Trí Huyền Food sẽ liên hệ ngay!`);
            if (formEl) formEl.reset();
        }

        function showToast(msg) {
            const toast = document.getElementById('toastMessage');
            const textEl = document.getElementById('toastText');
            if (!toast || !textEl) return;
            textEl.textContent = msg;
            toast.classList.remove('hidden');
            setTimeout(() => {
                toast.classList.add('hidden');
            }, 3800);
        }

        // Khởi chạy khi tải trang
        window.addEventListener('DOMContentLoaded', () => {
            renderAllProductSections('all', '');
            resetBannerAutoSlide();
        });
    </script>
</body>
</html>
