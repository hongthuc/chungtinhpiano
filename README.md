<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Chung Tình Piano (chungtinhpiano.com) - Đào Tạo Piano, Guitar, Violin Chuẩn Quốc Tế AMEB, ABRSM, LCM & Showroom Đàn Piano Đà Nẵng</title>
    <meta name="description" content="Chung Tình Piano (Soul Art Piano Đà Nẵng) - Chuyên đào tạo Piano, Guitar, Violin giáo trình quốc tế AMEB, ABRSM, LCM (Classic, For Leisure). Giảng viên Thạc sĩ Âm nhạc có chứng chỉ AMEB Level 2 đầu tiên tại Đà Nẵng. Cung cấp Grand Piano, Upright Piano, Digital Piano chính hãng tại 99/39 Núi Thành, Đà Nẵng.">

    <!-- Thumbnail là ảnh Logo trang web khi gửi/chia sẻ link trang web (Open Graph & Twitter Card) -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://chungtinhpiano.com/">
    <meta property="og:site_name" content="chungtinhpiano.com">
    <meta property="og:title" content="Chung Tình Piano - Đào Tạo Piano, Guitar, Violin Chuẩn Quốc Tế & Showroom Piano Đà Nẵng">
    <meta property="og:description" content="Giảng viên Thạc sĩ Âm nhạc - Chứng chỉ Quốc tế AMEB Level 2 đầu tiên tại Đà Nẵng. Giáo trình AMEB, ABRSM, LCM. Địa chỉ: 99/39 Núi Thành, P. Hòa Cường, TP. Đà Nẵng - ĐT: 0987.883.003">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v&sz=w1000">
    <meta property="og:image:width" content="800">
    <meta property="og:image:height" content="800">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Chung Tình Piano - chungtinhpiano.com">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v&sz=w1000">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v&sz=w200">
    <link rel="apple-touch-icon" href="https://drive.google.com/thumbnail?id=1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v&sz=w400">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Montserrat & Inter chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            gold: '#B8860B',      /* Màu vàng đồng chủ đạo theo Logo */
                            goldLight: '#D4AF37', /* Vàng kim sáng */
                            goldSoft: '#FDF8EC',  /* Nền kem vàng nhạt */
                            dark: '#1C1917',      /* Đen gỗ Piano */
                            wood: '#3E2723',      /* Nâu trầm cổ điển */
                            sale: '#D32F2F'       /* Đỏ giảm giá chuẩn Flatsome */
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif']
                    },
                    maxWidth: {
                        'flatsome': '1500px' /* Chiều ngang giao diện trên máy tính 1500px */
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
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #F9F9F9;
            color: #222222;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome 1500px trên máy tính */
        .container-flatsome {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .container-flatsome {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            margin-bottom: 1.5rem;
        }
        .flatsome-section-title b {
            display: block;
            flex: 1;
            height: 2px;
            background-color: #E5E7EB;
        }
        .flatsome-section-title span {
            padding: 0 16px;
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            text-transform: uppercase;
            text-align: center;
            color: #1C1917;
            letter-spacing: 0.03em;
        }

        /* Tên danh mục trên máy tính viết liền trên 1 hàng, chữ nhỏ gọn, tuyệt đối không tự xuống dòng trong tên */
        .nav-cat-item {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
        }

        /* Dropdown Menu trên máy tính kiểu Flatsome */
        .has-dropdown {
            position: relative;
        }
        .dropdown-menu {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 230px;
            background: #ffffff;
            box-shadow: 0 10px 25px rgba(0,0,0,0.12);
            border-top: 3px solid #B8860B;
            z-index: 100;
            padding: 8px 0;
            border-radius: 0 0 6px 6px;
        }
        .has-dropdown:hover .dropdown-menu {
            display: block;
        }

        /* Nút giảm giá % góc trên bên trái chuẩn Flatsome */
        .badge-sale-flatsome {
            position: absolute;
            top: 10px;
            left: 0;
            z-index: 10;
            background-color: #D32F2F;
            color: #ffffff;
            font-weight: 700;
            font-size: 12px;
            line-height: 1;
            padding: 6px 9px;
            border-radius: 0 4px 4px 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.18);
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc cắt mất chữ */
        .product-title-full {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            line-height: 1.4;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(184, 134, 11, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(184, 134, 11, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(184, 134, 11, 0); }
        }
        .float-btn-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>

    <!-- Hàm tự động xử lý ảnh Google Drive đa tầng để đảm bảo hiển thị 100% -->
    <script>
        function handleDriveImgError(img, driveId, fallbackLabel) {
            const step = parseInt(img.getAttribute('data-retry') || '0', 10);
            if (step === 0) {
                img.setAttribute('data-retry', '1');
                img.src = 'https://lh3.googleusercontent.com/d/' + driveId + '=w1000';
            } else if (step === 1) {
                img.setAttribute('data-retry', '2');
                img.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
            } else {
                img.onerror = null;
                img.src = 'https://placehold.co/600x600/FDF8EC/B8860B?text=' + encodeURIComponent(fallbackLabel || 'Chung+Tinh+Piano');
            }
        }
    </script>
</head>
<body class="bg-[#F9F9F9] text-stone-800 antialiased">

    <!-- ==========================================
         TOP BAR CHUẨN FLATSOME (Đơn giản, không có thanh UXBuilder)
         ========================================== -->
    <div class="bg-brand-dark text-stone-200 text-xs py-2 border-b border-stone-800">
        <div class="container-flatsome flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-4 truncate">
                <span class="font-medium text-brand-goldLight">
                    <i class="fa-solid fa-music mr-1"></i> CHUNG TÌNH PIANO - ĐÀO TẠO & SHOWROOM NHẠC CỤ CHUẨN QUỐC TẾ
                </span>
                <span class="hidden xl:inline-block text-stone-400">|</span>
                <span class="hidden xl:inline-block text-stone-300">
                    <i class="fa-solid fa-location-dot text-brand-goldLight mr-1"></i> 99/39 Núi Thành, Phường Hòa Cường, TP. Đà Nẵng
                </span>
            </div>
            <div class="flex items-center gap-4 ml-auto text-[11px] sm:text-xs">
                <a href="#gioi-thieu" class="hover:text-brand-goldLight transition">Giới thiệu</a>
                <span class="text-stone-600">|</span>
                <a href="#khoa-hoc" class="hover:text-brand-goldLight transition">Giáo trình AMEB - ABRSM - LCM</a>
                <span class="text-stone-600">|</span>
                <a href="#lien-he-map" class="hover:text-brand-goldLight transition">Chỉ đường Map</a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (Logo nhỏ gọn, KHÔNG để nút gọi ngay tránh tràn viền)
         ========================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-stone-200">
        <!-- Main Header Bar -->
        <div class="container-flatsome py-2.5 flex items-center justify-between gap-3">
            <!-- Nút mở Menu trên Điện thoại -->
            <button id="mobileMenuBtn" onclick="toggleMobileMenu()" class="lg:hidden p-2 text-stone-700 hover:text-brand-gold focus:outline-none" aria-label="Mở danh mục">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>

            <!-- Logo chỉnh gọn nhỏ lại theo đúng yêu cầu -->
            <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-full overflow-hidden border border-brand-gold/40 bg-brand-goldSoft flex items-center justify-center p-0.5 shrink-0">
                    <img src="https://drive.google.com/thumbnail?id=1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v&sz=w400"
                         onerror="handleDriveImgError(this, '1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v', 'Logo')"
                         alt="Logo Chung Tình Piano"
                         class="w-full h-full object-contain rounded-full">
                </div>
                <div class="flex flex-col">
                    <span class="font-heading font-extrabold text-sm sm:text-base lg:text-lg tracking-tight text-brand-dark group-hover:text-brand-gold transition leading-tight">
                        CHUNG TÌNH PIANO
                    </span>
                    <span class="text-[10px] sm:text-[11px] text-brand-gold font-semibold tracking-wider uppercase leading-tight">
                        chungtinhpiano.com
                    </span>
                </div>
            </a>

            <!-- Ô tìm kiếm kiểu Flatsome -->
            <div class="hidden md:flex flex-1 max-w-xl mx-4">
                <form onsubmit="handleSearchSubmit(event)" class="w-full flex items-center border border-stone-300 rounded-full overflow-hidden bg-stone-50 focus-within:border-brand-gold focus-within:bg-white transition">
                    <input id="desktopSearchInput" type="text" placeholder="Tìm đàn Grand Piano, Upright, Piano Điện, Khóa học AMEB..." class="w-full px-4 py-2 text-xs lg:text-sm bg-transparent focus:outline-none text-stone-700">
                    <button type="submit" class="px-4 py-2 bg-brand-gold text-white hover:bg-brand-wood transition text-xs lg:text-sm font-medium shrink-0">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </form>
            </div>

            <!-- Thông tin chứng nhận ngắn gọn trên máy tính (Không để nút gọi ngay để tránh tràn viền) -->
            <div class="hidden xl:flex items-center gap-5 shrink-0 text-xs">
                <div class="flex items-center gap-2">
                    <div class="w-8 h-8 rounded-full bg-brand-goldSoft text-brand-gold flex items-center justify-center font-bold">
                        <i class="fa-solid fa-graduation-cap"></i>
                    </div>
                    <div class="leading-tight">
                        <div class="font-bold text-stone-800">THẠC SĨ ÂM NHẠC</div>
                        <div class="text-[11px] text-stone-500">Chứng chỉ Quốc tế AMEB Lv2</div>
                    </div>
                </div>
                <div class="flex items-center gap-2">
                    <div class="w-8 h-8 rounded-full bg-brand-goldSoft text-brand-gold flex items-center justify-center font-bold">
                        <i class="fa-solid fa-award"></i>
                    </div>
                    <div class="leading-tight">
                        <div class="font-bold text-stone-800">GIÁO TRÌNH QUỐC TẾ</div>
                        <div class="text-[11px] text-stone-500">AMEB • ABRSM • LCM</div>
                    </div>
                </div>
            </div>

            <!-- Nút tìm kiếm nhỏ trên mobile -->
            <button onclick="toggleMobileSearch()" class="md:hidden p-2 text-stone-700 hover:text-brand-gold" aria-label="Tìm kiếm">
                <i class="fa-solid fa-magnifying-glass text-lg"></i>
            </button>
        </div>

        <!-- Thanh tìm kiếm sổ xuống trên Mobile -->
        <div id="mobileSearchBar" class="hidden md:hidden px-3 pb-2.5 bg-white border-t border-stone-100">
            <form onsubmit="handleSearchSubmit(event)" class="flex items-center border border-stone-300 rounded-full overflow-hidden bg-stone-50">
                <input id="mobileSearchInput" type="text" placeholder="Tìm đàn Piano, Guitar, Violin, Khóa học..." class="w-full px-3.5 py-1.5 text-xs bg-transparent focus:outline-none">
                <button type="submit" class="px-3.5 py-1.5 bg-brand-gold text-white text-xs">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </button>
            </form>
        </div>

        <!-- ==========================================
             THANH DANH MỤC MENU TRÊN MÁY TÍNH (Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2, tuyệt đối không gãy chữ tên danh mục)
             ========================================== -->
        <nav class="hidden lg:block bg-brand-dark text-white border-t border-stone-800">
            <div class="container-flatsome">
                <ul class="flex flex-wrap items-center justify-center gap-x-1 xl:gap-x-2 py-1 text-[12px] xl:text-[12.5px] font-semibold tracking-wide uppercase">
                    <li>
                        <a href="#" class="nav-cat-item px-2.5 py-2 rounded text-brand-goldLight hover:bg-stone-800 transition">
                            <i class="fa-solid fa-house mr-1.5 text-[11px]"></i>Trang Chủ
                        </a>
                    </li>
                    <li class="has-dropdown">
                        <a href="#san-pham" onclick="filterProducts('grand')" class="nav-cat-item px-2.5 py-2 rounded hover:text-brand-goldLight hover:bg-stone-800 transition">
                            Special Grand Piano <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-75"></i>
                        </a>
                        <ul class="dropdown-menu text-stone-700 text-xs font-medium normal-case">
                            <li><a href="#san-pham" onclick="filterProducts('grand')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Grand Mới 100%</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('grand')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Steinway & Sons / Boston</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('grand')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Yamaha Grand (C1, C3, G2...)</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('grand')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Kawai / Shigeru Kawai</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('grand')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Bösendorfer / C.Bechstein / Diapason</a></li>
                        </ul>
                    </li>
                    <li class="has-dropdown">
                        <a href="#san-pham" onclick="filterProducts('upright')" class="nav-cat-item px-2.5 py-2 rounded hover:text-brand-goldLight hover:bg-stone-800 transition">
                            Upright Piano <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-75"></i>
                        </a>
                        <ul class="dropdown-menu text-stone-700 text-xs font-medium normal-case">
                            <li><a href="#san-pham" onclick="filterProducts('upright')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Upright Mới 100%</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('upright')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Yamaha (U1G, U3H, UX, W102...)</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('upright')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Kawai Nhật Bản</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('upright')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Apollo / Diapason / Wendl & Lung</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('upright')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Samick / Youngchang / Germany</a></li>
                        </ul>
                    </li>
                    <li class="has-dropdown">
                        <a href="#san-pham" onclick="filterProducts('digital')" class="nav-cat-item px-2.5 py-2 rounded hover:text-brand-goldLight hover:bg-stone-800 transition">
                            Digital Piano <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-75"></i>
                        </a>
                        <ul class="dropdown-menu text-stone-700 text-xs font-medium normal-case">
                            <li><a href="#san-pham" onclick="filterProducts('digital')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Piano Điện Mới Nguyên Thùng</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('digital')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Yamaha (CLP, YDP Arius...)</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('digital')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Kawai (CA Series, CN Series...)</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('digital')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Roland / Casio / Korg / Nux</a></li>
                        </ul>
                    </li>
                    <li class="has-dropdown">
                        <a href="#san-pham" onclick="filterProducts('guitar-violin')" class="nav-cat-item px-2.5 py-2 rounded hover:text-brand-goldLight hover:bg-stone-800 transition">
                            Guitar & Violin <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-75"></i>
                        </a>
                        <ul class="dropdown-menu text-stone-700 text-xs font-medium normal-case">
                            <li><a href="#san-pham" onclick="filterProducts('guitar-violin')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Đàn Guitar Classic / Acoustic</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('guitar-violin')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Đàn Violin Chuyên Nghiệp Đủ Size</a></li>
                            <li><a href="#san-pham" onclick="filterProducts('guitar-violin')" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Phụ Kiện Nhạc Cụ Chính Hãng</a></li>
                        </ul>
                    </li>
                    <li class="has-dropdown">
                        <a href="#khoa-hoc" class="nav-cat-item px-2.5 py-2 rounded hover:text-brand-goldLight hover:bg-stone-800 transition">
                            Khóa Học Quốc Tế <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-75"></i>
                        </a>
                        <ul class="dropdown-menu text-stone-700 text-xs font-medium normal-case">
                            <li><a href="#khoa-hoc" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Chứng Chỉ Quốc Tế AMEB • ABRSM • LCM</a></li>
                            <li><a href="#khoa-hoc" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Khóa Học Piano Classic & For Leisure</a></li>
                            <li><a href="#khoa-hoc" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Khóa Học P-Plate Piano & Bastien</a></li>
                            <li><a href="#khoa-hoc" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Khóa Học Guitar Chuyên Sâu</a></li>
                            <li><a href="#khoa-hoc" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Khóa Học Violin Chuẩn Quốc Tế</a></li>
                        </ul>
                    </li>
                    <li class="has-dropdown">
                        <a href="#dich-vu" class="nav-cat-item px-2.5 py-2 rounded hover:text-brand-goldLight hover:bg-stone-800 transition">
                            Service (Dịch Vụ) <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-75"></i>
                        </a>
                        <ul class="dropdown-menu text-stone-700 text-xs font-medium normal-case">
                            <li><a href="#form-bao-gia" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Lên Dây & Bảo Dưỡng Piano Tại Nhà</a></li>
                            <li><a href="#form-bao-gia" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Dịch Vụ Sửa Chữa & Vận Chuyển Piano</a></li>
                            <li><a href="#form-bao-gia" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Cho Thuê Piano Sự Kiện, Tại Nhà</a></li>
                            <li><a href="#form-bao-gia" class="block px-4 py-2 hover:bg-brand-goldSoft hover:text-brand-gold">Tư Vấn Lắp Đặt Piano Trường Học</a></li>
                        </ul>
                    </li>
                    <li>
                        <a href="#bai-viet" class="nav-cat-item px-2.5 py-2 rounded hover:text-brand-goldLight hover:bg-stone-800 transition">
                            Tin Tức
                        </a>
                    </li>
                    <li>
                        <a href="#form-bao-gia" class="nav-cat-item px-2.5 py-2 rounded hover:text-brand-goldLight hover:bg-stone-800 transition">
                            Báo Giá & Khuyến Mại
                        </a>
                    </li>
                    <li>
                        <a href="#lien-he-map" class="nav-cat-item px-2.5 py-2 rounded hover:text-brand-goldLight hover:bg-stone-800 transition">
                            Liên Hệ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- ==========================================
         MENU DRAWER TRÊN ĐIỆN THOẠI (Thiết kế đẹp, gọn, chuẩn Flatsome Off-Canvas)
         ========================================== -->
    <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/60 z-50 hidden transition-opacity"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-[280px] max-w-[82vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 ease-in-out flex flex-col shadow-2xl">
        <div class="p-3.5 bg-brand-dark text-white flex items-center justify-between">
            <div class="flex items-center gap-2">
                <img src="https://drive.google.com/thumbnail?id=1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v&sz=w200"
                     onerror="handleDriveImgError(this, '1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v', 'Logo')"
                     alt="Logo" class="w-8 h-8 rounded-full object-contain bg-white p-0.5">
                <span class="font-heading font-bold text-sm text-brand-goldLight">CHUNG TÌNH PIANO</span>
            </div>
            <button onclick="toggleMobileMenu()" class="text-stone-300 hover:text-white p-1">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
        </div>
        <div class="flex-1 overflow-y-auto divide-y divide-stone-100 text-xs font-semibold text-stone-700">
            <a href="#" onclick="toggleMobileMenu()" class="block px-4 py-3 text-brand-gold bg-brand-goldSoft/60">
                <i class="fa-solid fa-house w-5"></i> TRANG CHỦ
            </a>
            <a href="#san-pham" onclick="filterProducts('grand'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-stone-50">
                <i class="fa-solid fa-crown w-5 text-brand-gold"></i> SPECIAL GRAND PIANO
            </a>
            <a href="#san-pham" onclick="filterProducts('upright'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-stone-50">
                <i class="fa-solid fa-music w-5 text-brand-gold"></i> UPRIGHT PIANO NHẬT BẢN
            </a>
            <a href="#san-pham" onclick="filterProducts('digital'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-stone-50">
                <i class="fa-solid fa-sliders w-5 text-brand-gold"></i> DIGITAL PIANO (PIANO ĐIỆN)
            </a>
            <a href="#san-pham" onclick="filterProducts('guitar-violin'); toggleMobileMenu()" class="block px-4 py-3 hover:bg-stone-50">
                <i class="fa-solid fa-guitar w-5 text-brand-gold"></i> ĐÀN GUITAR & VIOLIN
            </a>
            <a href="#khoa-hoc" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-stone-50">
                <i class="fa-solid fa-graduation-cap w-5 text-brand-gold"></i> KHÓA HỌC QUỐC TẾ (AMEB, ABRSM, LCM)
            </a>
            <a href="#trung-tam" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-stone-50">
                <i class="fa-solid fa-images w-5 text-brand-gold"></i> HÌNH ẢNH TRUNG TÂM
            </a>
            <a href="#bai-viet" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-stone-50">
                <i class="fa-solid fa-newspaper w-5 text-brand-gold"></i> TIN TỨC & GIÁO TRÌNH
            </a>
            <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-stone-50">
                <i class="fa-solid fa-file-signature w-5 text-brand-gold"></i> YÊU CẦU TƯ VẤN & BÁO GIÁ
            </a>
            <a href="#lien-he-map" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-stone-50">
                <i class="fa-solid fa-location-dot w-5 text-brand-gold"></i> BẢN ĐỒ & FANPAGE
            </a>
        </div>
        <div class="p-3.5 bg-stone-50 border-t border-stone-200 text-[11px] text-stone-600 space-y-1">
            <div class="font-bold text-stone-800">CHUNG TÌNH PIANO ĐÀ NẴNG</div>
            <div><i class="fa-solid fa-location-dot text-brand-gold mr-1"></i> 99/39 Núi Thành, P. Hòa Cường, Đà Nẵng</div>
            <div><i class="fa-solid fa-phone text-brand-gold mr-1"></i> Hotline/Zalo: <strong class="text-brand-dark">0987.883.003</strong></div>
        </div>
    </aside>

    <!-- ==========================================
         [UX_SLIDER] 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         - Thiết kế riêng ảnh Banner Máy Tính (hidden md:block) và ảnh Banner Điện Thoại (block md:hidden)
         - Chữ nhỏ gọn nằm trọn bên trong ảnh banner, tuyệt đối không tràn viền
         ========================================== -->
    <section class="w-full bg-stone-900 relative overflow-hidden">
        <div class="container-flatsome px-0 sm:px-3 lg:px-5 py-0 sm:py-3">
            <div class="relative w-full overflow-hidden sm:rounded-lg shadow-md">

                <!-- ================= BANNER TRÊN MÁY TÍNH (2 SLIDE KÍCH THƯỚC BẰNG NHAU: H-[390PX] LG:H-[430PX]) ================= -->
                <div class="hidden md:block relative w-full h-[390px] lg:h-[430px]">
                    <!-- SLIDE 1 MÁY TÍNH -->
                    <div id="desktopSlide0" class=" banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <img src="https://drive.google.com/thumbnail?id=1oTfAg0sNYwgXr50kAyGtVCBtEWDuxnBS&sz=w1600"
                             onerror="handleDriveImgError(this, '1oTfAg0sNYwgXr50kAyGtVCBtEWDuxnBS', 'Banner+1')"
                             alt="Đào tạo Piano Guitar Violin Chuẩn Quốc Tế"
                             class="w-full h-full object-cover object-center">
                        <div class="absolute inset-0 bg-gradient-to-r from-black/85 via-black/65 to-black/30 flex items-center">
                            <!-- Nội dung chữ thu gọn nằm hoàn toàn bên trong khung an toàn -->
                            <div class="w-full max-w-3xl px-12 lg:px-16 py-6 text-white space-y-2.5">
                                <div class="inline-block px-3 py-1 rounded bg-brand-gold text-white text-xs font-bold tracking-wider uppercase">
                                    CHUNG TÌNH PIANO • SOUL ART PIANO ĐÀ NẴNG
                                </div>
                                <h1 class="font-heading font-extrabold text-xl lg:text-2xl xl:text-3xl leading-snug text-white">
                                    ĐÀO TẠO CHUYÊN SÂU: PIANO, GUITAR, VIOLIN<br>
                                    <span class="text-brand-goldLight">GIÁO TRÌNH QUỐC TẾ AMEB • ABRSM • LCM</span>
                                </h1>
                                <p class="text-xs lg:text-sm text-stone-200 leading-relaxed max-w-2xl">
                                    • Giảng viên là <strong class="text-brand-goldLight">THẠC SĨ ÂM NHẠC</strong> và có <strong class="text-brand-goldLight">Chứng chỉ Giáo viên Quốc tế AMEB LEVEL 2 đầu tiên tại ĐÀ NẴNG</strong>.<br>
                                    • Nội dung học phong phú: <strong>CLASSIC, FOR LEISURE, P-PLATE PIANO...</strong> từ cơ bản đến nâng cao & luyện thi chứng chỉ quốc tế.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-3 text-xs text-stone-200">
                                    <span><i class="fa-solid fa-location-dot text-brand-goldLight mr-1"></i> 99/39 Núi Thành, P. Hòa Cường, TP. Đà Nẵng</span>
                                    <span>•</span>
                                    <span><i class="fa-solid fa-phone text-brand-goldLight mr-1"></i> ĐT/Zalo: <strong class="text-white">0987.883.003</strong></span>
                                </div>
                                <div class="pt-2 flex items-center gap-3">
                                    <a href="#form-bao-gia" class="px-4 py-2 bg-brand-gold hover:bg-brand-goldLight text-white font-bold text-xs rounded transition shadow">
                                        ĐĂNG KÝ TƯ VẤN KHÓA HỌC
                                    </a>
                                    <a href="#khoa-hoc" class="px-4 py-2 bg-white/15 hover:bg-white/25 text-white font-semibold text-xs rounded border border-white/30 transition">
                                        XEM CHƯƠNG TRÌNH HỌC
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- SLIDE 2 MÁY TÍNH (KÍCH THƯỚC BẰNG HỆT SLIDE 1) -->
                    <div id="desktopSlide1" class="banner-slide-desktop absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <img src="https://drive.google.com/thumbnail?id=1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B&sz=w1600"
                             onerror="handleDriveImgError(this, '1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B', 'Banner+2')"
                             alt="Showroom Đàn Piano Chính Hãng Đà Nẵng"
                             class="w-full h-full object-cover object-center">
                        <div class="absolute inset-0 bg-gradient-to-r from-black/85 via-black/65 to-black/30 flex items-center">
                            <div class="w-full max-w-3xl px-12 lg:px-16 py-6 text-white space-y-2.5">
                                <div class="inline-block px-3 py-1 rounded bg-brand-gold text-white text-xs font-bold tracking-wider uppercase">
                                    SHOWROOM NHẠC CỤ CHÍNH HÃNG • CHUNGTINHPIANO.COM
                                </div>
                                <h2 class="font-heading font-extrabold text-xl lg:text-2xl xl:text-3xl leading-snug text-white">
                                    CHUYÊN CUNG CẤP GRAND PIANO, UPRIGHT PIANO,<br>
                                    <span class="text-brand-goldLight">DIGITAL PIANO, GUITAR & VIOLIN NHẬP KHẨU</span>
                                </h2>
                                <p class="text-xs lg:text-sm text-stone-200 leading-relaxed max-w-2xl">
                                    • Tuyển chọn tỉ mỉ từ các thương hiệu hàng đầu: <strong class="text-brand-goldLight">Yamaha, Kawai, Steinway & Sons, Roland, Apollo, Diapason...</strong><br>
                                    • Cam kết chính hãng 100%, bảo hành hậu mãi tận tâm, tặng kèm phụ kiện & miễn phí vận chuyển tại Đà Nẵng.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-3 text-xs text-stone-200">
                                    <span><i class="fa-solid fa-location-dot text-brand-goldLight mr-1"></i> 99/39 Núi Thành, P. Hòa Cường, TP. Đà Nẵng</span>
                                    <span>•</span>
                                    <span><i class="fa-solid fa-phone text-brand-goldLight mr-1"></i> Hotline báo giá: <strong class="text-white">0987.883.003</strong></span>
                                </div>
                                <div class="pt-2 flex items-center gap-3">
                                    <a href="#san-pham" class="px-4 py-2 bg-brand-gold hover:bg-brand-goldLight text-white font-bold text-xs rounded transition shadow">
                                        XEM DANH MỤC ĐÀN PIANO
                                    </a>
                                    <a href="#form-bao-gia" class="px-4 py-2 bg-white/15 hover:bg-white/25 text-white font-semibold text-xs rounded border border-white/30 transition">
                                        NHẬN BÁO GIÁ ƯU ĐÃI
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ================= BANNER TRÊN ĐIỆN THOẠI (THIẾT KẾ MỚI KHÁC VỚI MÁY TÍNH, 2 SLIDE BẰNG NHAU H-[240PX] SM:H-[260PX], CHỮ NHỎ GỌN KHÔNG TRÀN VIỀN) ================= -->
                <div class="block md:hidden relative w-full h-[240px] sm:h-[260px]">
                    <!-- SLIDE 1 ĐIỆN THOẠI -->
                    <div id="mobileSlide0" class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <img src="https://drive.google.com/thumbnail?id=107RZcfsXfxlSJaQwrFKmUOpDlsep2cdd&sz=w1000"
                             onerror="handleDriveImgError(this, '107RZcfsXfxlSJaQwrFKmUOpDlsep2cdd', 'Mobile+Banner+1')"
                             alt="Đào tạo Âm nhạc Chung Tình Piano"
                             class="w-full h-full object-cover object-center">
                        <div class="absolute inset-0 bg-black/75 flex flex-col justify-center px-5 py-3 text-center text-white">
                            <span class="mx-auto px-2.5 py-0.5 rounded bg-brand-gold text-[10px] font-bold uppercase tracking-wide mb-1.5">
                                CHUNG TÌNH PIANO - ĐÀ NẴNG
                            </span>
                            <h2 class="font-heading font-extrabold text-[14px] sm:text-base leading-snug text-brand-goldLight">
                                DẠY CHUYÊN SÂU: PIANO • GUITAR • VIOLIN
                            </h2>
                            <p class="text-[11px] sm:text-xs text-stone-100 font-medium leading-tight mt-1">
                                Giáo trình chuẩn quốc tế: <strong>AMEB, ABRSM, LCM</strong><br>
                                (Classic, For Leisure...)
                            </p>
                            <p class="text-[10.5px] text-amber-200 leading-tight mt-1">
                                Giảng viên: <strong>THẠC SĨ ÂM NHẠC</strong> • Chứng chỉ Quốc tế <strong>AMEB LEVEL 2</strong> đầu tiên tại Đà Nẵng
                            </p>
                            <div class="mt-2 pt-1.5 border-t border-white/15 text-[10px] text-stone-200">
                                99/39 Núi Thành, P. Hòa Cường, Đà Nẵng | ĐT: <strong>0987.883.003</strong>
                            </div>
                        </div>
                    </div>

                    <!-- SLIDE 2 ĐIỆN THOẠI (KÍCH THƯỚC BẰNG HỆT SLIDE 1) -->
                    <div id="mobileSlide1" class="banner-slide-mobile absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <img src="https://drive.google.com/thumbnail?id=1w9FMSw-icHv-ojvQwp5tCneMlaV90jLZ&sz=w1000"
                             onerror="handleDriveImgError(this, '1w9FMSw-icHv-ojvQwp5tCneMlaV90jLZ', 'Mobile+Banner+2')"
                             alt="Showroom Đàn Piano Chung Tình"
                             class="w-full h-full object-cover object-center">
                        <div class="absolute inset-0 bg-black/75 flex flex-col justify-center px-5 py-3 text-center text-white">
                            <span class="mx-auto px-2.5 py-0.5 rounded bg-brand-gold text-[10px] font-bold uppercase tracking-wide mb-1.5">
                                SHOWROOM CHUNGTINHPIANO.COM
                            </span>
                            <h2 class="font-heading font-extrabold text-[14px] sm:text-base leading-snug text-brand-goldLight">
                                GRAND PIANO • UPRIGHT • PIANO ĐIỆN
                            </h2>
                            <p class="text-[11px] sm:text-xs text-stone-100 font-medium leading-tight mt-1">
                                Nhập khẩu chính hãng <strong>Yamaha, Kawai, Roland...</strong><br>
                                Giá tốt nhất - Bảo hành tận nhà
                            </p>
                            <p class="text-[10.5px] text-amber-200 leading-tight mt-1">
                                Dịch vụ lên dây, sửa chữa, vận chuyển & cho thuê đàn Piano chuyên nghiệp
                            </p>
                            <div class="mt-2 pt-1.5 border-t border-white/15 text-[10px] text-stone-200">
                                99/39 Núi Thành, P. Hòa Cường, Đà Nẵng | ĐT: <strong>0987.883.003</strong>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slider Trái/Phải & Chấm tròn -->
                <button onclick="prevBannerSlide()" class=" hidden sm:flex absolute left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-brand-gold text-white items-center justify-center transition" aria-label="Slide trước">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="nextBannerSlide()" class="hidden sm:flex absolute right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/40 hover:bg-brand-gold text-white items-center justify-center transition" aria-label="Slide tiếp">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button id="bannerDot0" onclick="goToBannerSlide(0)" class="w-6 h-1.5 rounded-full bg-brand-goldLight transition-all" aria-label="Slide 1"></button>
                    <button id="bannerDot1" onclick="goToBannerSlide(1)" class="w-2.5 h-1.5 rounded-full bg-white/50 transition-all" aria-label="Slide 2"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         [SECTION] DANH MỤC Ở TRANG CHỦ (Tối ưu đẹp trên cả máy tính & điện thoại, chữ nhỏ gọn, không tràn viền)
         Lấy theo danh mục web mẫu duongpiano.com
         ========================================== -->
    <section class="py-5 bg-white border-b border-stone-200">
        <div class="container-flatsome">
            <!-- 4 Nút Nhu Cầu Nhanh giống "BẠN ĐANG CẦN: MUA PIANO | HỌC PIANO | SỬA PIANO | THUÊ PIANO" của web mẫu -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4 mb-5">
                <a href="#san-pham" class="flex items-center gap-3 p-3 rounded-lg bg-brand-goldSoft border border-brand-gold/30 hover:bg-brand-gold hover:text-white transition group">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-brand-gold text-white group-hover:bg-white group-hover:text-brand-gold flex items-center justify-center shrink-0 transition">
                        <i class="fa-solid fa-cart-shopping text-sm"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="font-heading font-bold text-xs sm:text-sm uppercase truncate">MUA PIANO</div>
                        <div class="text-[11px] opacity-80 truncate">Grand, Upright, Digital</div>
                    </div>
                </a>
                <a href="#khoa-hoc" class="flex items-center gap-3 p-3 rounded-lg bg-brand-goldSoft border border-brand-gold/30 hover:bg-brand-gold hover:text-white transition group">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-brand-gold text-white group-hover:bg-white group-hover:text-brand-gold flex items-center justify-center shrink-0 transition">
                        <i class="fa-solid fa-graduation-cap text-sm"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="font-heading font-bold text-xs sm:text-sm uppercase truncate">HỌC NHẠC QUỐC TẾ</div>
                        <div class="text-[11px] opacity-80 truncate">AMEB, ABRSM, LCM</div>
                    </div>
                </a>
                <a href="#form-bao-gia" class="flex items-center gap-3 p-3 rounded-lg bg-brand-goldSoft border border-brand-gold/30 hover:bg-brand-gold hover:text-white transition group">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-brand-gold text-white group-hover:bg-white group-hover:text-brand-gold flex items-center justify-center shrink-0 transition">
                        <i class="fa-solid fa-screwdriver-wrench text-sm"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="font-heading font-bold text-xs sm:text-sm uppercase truncate">SỬA & LÊN DÂY</div>
                        <div class="text-[11px] opacity-80 truncate">Bảo dưỡng tận nhà</div>
                    </div>
                </a>
                <a href="#form-bao-gia" class="flex items-center gap-3 p-3 rounded-lg bg-brand-goldSoft border border-brand-gold/30 hover:bg-brand-gold hover:text-white transition group">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-brand-gold text-white group-hover:bg-white group-hover:text-brand-gold flex items-center justify-center shrink-0 transition">
                        <i class="fa-solid fa-calendar-check text-sm"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="font-heading font-bold text-xs sm:text-sm uppercase truncate">THUÊ PIANO</div>
                        <div class="text-[11px] opacity-80 truncate">Sự kiện & Tại nhà</div>
                    </div>
                </a>
            </div>

            <!-- Danh mục sản phẩm & dịch vụ ở trang chủ (Chữ nhỏ gọn, viết liền trên 1 hàng mỗi ô, hiển thị đẹp trên cả PC & Mobile) -->
            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2">
                <button onclick="filterProducts('all')" class="cat-pill active-cat flex items-center justify-center gap-1.5 px-2.5 py-2 rounded border border-brand-gold bg-brand-gold text-white text-[11.5px] font-semibold whitespace-nowrap transition">
                    <i class="fa-solid fa-border-all text-[10px]"></i> Tất Cả Sản Phẩm
                </button>
                <button onclick="filterProducts('grand')" class="cat-pill flex items-center justify-center gap-1.5 px-2.5 py-2 rounded border border-stone-200 bg-stone-50 hover:border-brand-gold hover:text-brand-gold text-stone-700 text-[11.5px] font-semibold whitespace-nowrap transition">
                    <i class="fa-solid fa-crown text-[10px] text-brand-gold"></i> Grand Piano
                </button>
                <button onclick="filterProducts('upright')" class="cat-pill flex items-center justify-center gap-1.5 px-2.5 py-2 rounded border border-stone-200 bg-stone-50 hover:border-brand-gold hover:text-brand-gold text-stone-700 text-[11.5px] font-semibold whitespace-nowrap transition">
                    <i class="fa-solid fa-music text-[10px] text-brand-gold"></i> Upright Piano
                </button>
                <button onclick="filterProducts('digital')" class="cat-pill flex items-center justify-center gap-1.5 px-2.5 py-2 rounded border border-stone-200 bg-stone-50 hover:border-brand-gold hover:text-brand-gold text-stone-700 text-[11.5px] font-semibold whitespace-nowrap transition">
                    <i class="fa-solid fa-sliders text-[10px] text-brand-gold"></i> Digital Piano
                </button>
                <button onclick="filterProducts('guitar-violin')" class="cat-pill flex items-center justify-center gap-1.5 px-2.5 py-2 rounded border border-stone-200 bg-stone-50 hover:border-brand-gold hover:text-brand-gold text-stone-700 text-[11.5px] font-semibold whitespace-nowrap transition">
                    <i class="fa-solid fa-guitar text-[10px] text-brand-gold"></i> Guitar & Violin
                </button>
                <a href="#khoa-hoc" class="flex items-center justify-center gap-1.5 px-2.5 py-2 rounded border border-stone-200 bg-stone-50 hover:border-brand-gold hover:text-brand-gold text-stone-700 text-[11.5px] font-semibold whitespace-nowrap transition">
                    <i class="fa-solid fa-book-open text-[10px] text-brand-gold"></i> Khóa Học AMEB
                </a>
                <a href="#dich-vu" class="flex items-center justify-center gap-1.5 px-2.5 py-2 rounded border border-stone-200 bg-stone-50 hover:border-brand-gold hover:text-brand-gold text-stone-700 text-[11.5px] font-semibold whitespace-nowrap transition">
                    <i class="fa-solid fa-Screwdriver-wrench text-[10px] text-brand-gold"></i> Dịch Vụ Piano
                </a>
                <a href="#bai-viet" class="flex items-center justify-center gap-1.5 px-2.5 py-2 rounded border border-stone-200 bg-stone-50 hover:border-brand-gold hover:text-brand-gold text-stone-700 text-[11.5px] font-semibold whitespace-nowrap transition">
                    <i class="fa-solid fa-newspaper text-[10px] text-brand-gold"></i> Tin Tức & Cẩm Nang
                </a>
            </div>
        </div>
    </section>

    <!-- ==========================================
         [SECTION] SẢN PHẨM NỔI BẬT TRANG CHỦ
         - Sử dụng đúng 8 ảnh sản phẩm thực tế từ Google Drive
         - Chia thành 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
         - Giá giảm giá và % giảm giá góc trên bên trái giống Flatsome
         - Không để các nhãn dán dư thừa khác ở trang chủ
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ
         ========================================== -->
    <section id="san-pham" class="py-8 sm:py-10">
        <div class="container-flatsome">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-xl">DANH MỤC SẢN PHẨM NỔI BẬT</span>
                <b></b>
            </div>

            <p class="text-center text-xs sm:text-sm text-stone-600 max-w-3xl mx-auto mb-6">
                Tuyển chọn các mẫu đàn <strong>Upright Piano, Grand Piano, Digital Piano, Guitar & Violin</strong> thực tế tại Showroom <strong>Chung Tình Piano</strong> – Cam kết chính hãng, âm thanh chuẩn quốc tế, bảo hành dài hạn tại Đà Nẵng.
            </p>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="productGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">

                <!-- SẢN PHẨM 1 (Ảnh thực tế 1: 1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B) -->
                <div data-cat="upright" class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square w-full bg-stone-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-15%</span>
                        <img src="https://drive.google.com/thumbnail?id=1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B&sz=w800"
                             onerror="handleDriveImgError(this, '1KuVw9azjuilVLi7cHga70n--Z5g5Wh0B', 'Yamaha+U3H')"
                             alt="Đàn Upright Piano Yamaha U3H Nhật Bản"
                             class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between text-center">
                        <div>
                            <div class="text-[10px] sm:text-xs text-stone-400 uppercase tracking-wider mb-1">Upright Piano</div>
                            <h3 class="product-title-full font-semibold text-xs sm:text-sm text-stone-800 hover:text-brand-gold transition">
                                Đàn Upright Piano Cơ Yamaha U3H (Serial 2.0 Nhật Bản)
                            </h3>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100">
                            <div class="flex flex-wrap items-center justify-center gap-1.5 text-xs sm:text-sm">
                                <span class="line-through text-stone-400 text-[11px] sm:text-xs">49.000.000 ₫</span>
                                <span class="font-bold text-brand-sale">41.500.000 ₫</span>
                            </div>
                            <button onclick="openQuoteModal('Đàn Upright Piano Cơ Yamaha U3H (Serial 2.0 Nhật Bản)', '41.500.000 ₫')" class="mt-2.5 w-full py-1.5 px-2 rounded bg-stone-100 hover:bg-brand-gold hover:text-white text-stone-700 font-semibold text-[11px] sm:text-xs transition">
                                Nhận báo giá ưu đãi
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 2 (Ảnh thực tế 2: 1w9FMSw-icHv-ojvQwp5tCneMlaV90jLZ) -->
                <div data-cat="upright" class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square w-full bg-stone-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-20%</span>
                        <img src="https://drive.google.com/thumbnail?id=1w9FMSw-icHv-ojvQwp5tCneMlaV90jLZ&sz=w800"
                             onerror="handleDriveImgError(this, '1w9FMSw-icHv-ojvQwp5tCneMlaV90jLZ', 'Yamaha+U1G')"
                             alt="Đàn Upright Piano Yamaha U1G"
                             class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between text-center">
                        <div>
                            <div class="text-[10px] sm:text-xs text-stone-400 uppercase tracking-wider mb-1">Upright Piano</div>
                            <h3 class="product-title-full font-semibold text-xs sm:text-sm text-stone-800 hover:text-brand-gold transition">
                                Đàn Upright Piano Cơ Yamaha U1G (Serial 2.0 Tuyển Chọn)
                            </h3>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100">
                            <div class="flex flex-wrap items-center justify-center gap-1.5 text-xs sm:text-sm">
                                <span class="line-through text-stone-400 text-[11px] sm:text-xs">44.500.000 ₫</span>
                                <span class="font-bold text-brand-sale">35.800.000 ₫</span>
                            </div>
                            <button onclick="openQuoteModal('Đàn Upright Piano Cơ Yamaha U1G (Serial 2.0)', '35.800.000 ₫')" class="mt-2.5 w-full py-1.5 px-2 rounded bg-stone-100 hover:bg-brand-gold hover:text-white text-stone-700 font-semibold text-[11px] sm:text-xs transition">
                                Nhận báo giá ưu đãi
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 3 (Ảnh thực tế 3: 1Brf48Fp-rKdm9I6_mPnUlDAqN-DPxl76) -->
                <div data-cat="upright" class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square w-full bg-stone-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-15%</span>
                        <img src="https://drive.google.com/thumbnail?id=1Brf48Fp-rKdm9I6_mPnUlDAqN-DPxl76&sz=w800"
                             onerror="handleDriveImgError(this, '1Brf48Fp-rKdm9I6_mPnUlDAqN-DPxl76', 'Yamaha+UX')"
                             alt="Đàn Upright Piano Yamaha UX"
                             class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between text-center">
                        <div>
                            <div class="text-[10px] sm:text-xs text-stone-400 uppercase tracking-wider mb-1">Upright Piano</div>
                            <h3 class="product-title-full font-semibold text-xs sm:text-sm text-stone-800 hover:text-brand-gold transition">
                                Đàn Upright Piano Cơ Yamaha UX Khung Chữ X Cao Cấp
                            </h3>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100">
                            <div class="flex flex-wrap items-center justify-center gap-1.5 text-xs sm:text-sm">
                                <span class="line-through text-stone-400 text-[11px] sm:text-xs">53.800.000 ₫</span>
                                <span class="font-bold text-brand-sale">45.580.000 ₫</span>
                            </div>
                            <button onclick="openQuoteModal('Đàn Upright Piano Cơ Yamaha UX Khung Chữ X', '45.580.000 ₫')" class="mt-2.5 w-full py-1.5 px-2 rounded bg-stone-100 hover:bg-brand-gold hover:text-white text-stone-700 font-semibold text-[11px] sm:text-xs transition">
                                Nhận báo giá ưu đãi
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 4 (Ảnh thực tế 4: 18c8z9UQJPM4fJkAHDeK7XpJ4LNJ7zRYI) -->
                <div data-cat="upright" class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square w-full bg-stone-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-15%</span>
                        <img src="https://drive.google.com/thumbnail?id=18c8z9UQJPM4fJkAHDeK7XpJ4LNJ7zRYI&sz=w800"
                             onerror="handleDriveImgError(this, '18c8z9UQJPM4fJkAHDeK7XpJ4LNJ7zRYI', 'Yamaha+W102')"
                             alt="Đàn Upright Piano Yamaha W102 Vân Gỗ"
                             class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between text-center">
                        <div>
                            <div class="text-[10px] sm:text-xs text-stone-400 uppercase tracking-wider mb-1">Upright Piano</div>
                            <h3 class="product-title-full font-semibold text-xs sm:text-sm text-stone-800 hover:text-brand-gold transition">
                                Đàn Upright Piano Cơ Yamaha W102 Vân Gỗ Tự Nhiên
                            </h3>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100">
                            <div class="flex flex-wrap items-center justify-center gap-1.5 text-xs sm:text-sm">
                                <span class="line-through text-stone-400 text-[11px] sm:text-xs">58.900.000 ₫</span>
                                <span class="font-bold text-brand-sale">49.800.000 ₫</span>
                            </div>
                            <button onclick="openQuoteModal('Đàn Upright Piano Cơ Yamaha W102 Vân Gỗ', '49.800.000 ₫')" class="mt-2.5 w-full py-1.5 px-2 rounded bg-stone-100 hover:bg-brand-gold hover:text-white text-stone-700 font-semibold text-[11px] sm:text-xs transition">
                                Nhận báo giá ưu đãi
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 5 (Ảnh thực tế 5: 1NJNKfPHNR1cgIvvyMLg12_dTGAb0gq5-) -->
                <div data-cat="grand" class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square w-full bg-stone-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-15%</span>
                        <img src="https://drive.google.com/thumbnail?id=1NJNKfPHNR1cgIvvyMLg12_dTGAb0gq5-&sz=w800"
                             onerror="handleDriveImgError(this, '1NJNKfPHNR1cgIvvyMLg12_dTGAb0gq5-', 'Grand+Yamaha+G2')"
                             alt="Đàn Grand Piano Yamaha G2"
                             class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between text-center">
                        <div>
                            <div class="text-[10px] sm:text-xs text-stone-400 uppercase tracking-wider mb-1">Special Grand Piano</div>
                            <h3 class="product-title-full font-semibold text-xs sm:text-sm text-stone-800 hover:text-brand-gold transition">
                                Đàn Grand Piano Yamaha G2 Chính Hãng Nhật Bản
                            </h3>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100">
                            <div class="flex flex-wrap items-center justify-center gap-1.5 text-xs sm:text-sm">
                                <span class="line-through text-stone-400 text-[11px] sm:text-xs">200.000.000 ₫</span>
                                <span class="font-bold text-brand-sale">170.000.000 ₫</span>
                            </div>
                            <button onclick="openQuoteModal('Đàn Grand Piano Yamaha G2 Chính Hãng', '170.000.000 ₫')" class="mt-2.5 w-full py-1.5 px-2 rounded bg-stone-100 hover:bg-brand-gold hover:text-white text-stone-700 font-semibold text-[11px] sm:text-xs transition">
                                Nhận báo giá ưu đãi
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 6 (Ảnh thực tế 6: 19fuYh7jbohm3KBx5ETE0JXUVBD031StW) -->
                <div data-cat="digital" class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square w-full bg-stone-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-20%</span>
                        <img src="https://drive.google.com/thumbnail?id=19fuYh7jbohm3KBx5ETE0JXUVBD031StW&sz=w800"
                             onerror="handleDriveImgError(this, '19fuYh7jbohm3KBx5ETE0JXUVBD031StW', 'Yamaha+CLP535')"
                             alt="Đàn Piano Điện Yamaha CLP535WA"
                             class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between text-center">
                        <div>
                            <div class="text-[10px] sm:text-xs text-stone-400 uppercase tracking-wider mb-1">Digital Piano</div>
                            <h3 class="product-title-full font-semibold text-xs sm:text-sm text-stone-800 hover:text-brand-gold transition">
                                Đàn Piano Điện Yamaha Clavinova CLP535WA Cao Cấp
                            </h3>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100">
                            <div class="flex flex-wrap items-center justify-center gap-1.5 text-xs sm:text-sm">
                                <span class="line-through text-stone-400 text-[11px] sm:text-xs">25.500.000 ₫</span>
                                <span class="font-bold text-brand-sale">20.500.000 ₫</span>
                            </div>
                            <button onclick="openQuoteModal('Đàn Piano Điện Yamaha Clavinova CLP535WA', '20.500.000 ₫')" class="mt-2.5 w-full py-1.5 px-2 rounded bg-stone-100 hover:bg-brand-gold hover:text-white text-stone-700 font-semibold text-[11px] sm:text-xs transition">
                                Nhận báo giá ưu đãi
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 7 (Ảnh thực tế 7: 1lJV2xF7YXfDCFxndRj0bR0vqeY2rFQMX) -->
                <div data-cat="digital" class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square w-full bg-stone-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-15%</span>
                        <img src="https://drive.google.com/thumbnail?id=1lJV2xF7YXfDCFxndRj0bR0vqeY2rFQMX&sz=w800"
                             onerror="handleDriveImgError(this, '1lJV2xF7YXfDCFxndRj0bR0vqeY2rFQMX', 'Kawai+CA15A')"
                             alt="Đàn Piano Điện Kawai CA15A"
                             class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between text-center">
                        <div>
                            <div class="text-[10px] sm:text-xs text-stone-400 uppercase tracking-wider mb-1">Digital Piano</div>
                            <h3 class="product-title-full font-semibold text-xs sm:text-sm text-stone-800 hover:text-brand-gold transition">
                                Đàn Piano Điện Kawai CA15A Phím Gỗ Tự Nhiên
                            </h3>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100">
                            <div class="flex flex-wrap items-center justify-center gap-1.5 text-xs sm:text-sm">
                                <span class="line-through text-stone-400 text-[11px] sm:text-xs">19.800.000 ₫</span>
                                <span class="font-bold text-brand-sale">16.800.000 ₫</span>
                            </div>
                            <button onclick="openQuoteModal('Đàn Piano Điện Kawai CA15A Phím Gỗ', '16.800.000 ₫')" class="mt-2.5 w-full py-1.5 px-2 rounded bg-stone-100 hover:bg-brand-gold hover:text-white text-stone-700 font-semibold text-[11px] sm:text-xs transition">
                                Nhận báo giá ưu đãi
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 8 (Ảnh thực tế 8: 1_8GxHwmFTXKXbh1yY0-TGlC49xb1MZSY) -->
                <div data-cat="guitar-violin" class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-square w-full bg-stone-100 overflow-hidden">
                        <span class="badge-sale-flatsome">-20%</span>
                        <img src="https://drive.google.com/thumbnail?id=1_8GxHwmFTXKXbh1yY0-TGlC49xb1MZSY&sz=w800"
                             onerror="handleDriveImgError(this, '1_8GxHwmFTXKXbh1yY0-TGlC49xb1MZSY', 'Yamaha+YDP163R')"
                             alt="Đàn Piano & Nhạc Cụ Quốc Tế Yamaha YDP163R"
                             class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between text-center">
                        <div>
                            <div class="text-[10px] sm:text-xs text-stone-400 uppercase tracking-wider mb-1">Digital Piano • Guitar & Violin</div>
                            <h3 class="product-title-full font-semibold text-xs sm:text-sm text-stone-800 hover:text-brand-gold transition">
                                Đàn Piano Yamaha YDP163R & Nhạc Cụ Học Quốc Tế
                            </h3>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100">
                            <div class="flex flex-wrap items-center justify-center gap-1.5 text-xs sm:text-sm">
                                <span class="line-through text-stone-400 text-[11px] sm:text-xs">21.800.000 ₫</span>
                                <span class="font-bold text-brand-sale">17.500.000 ₫</span>
                            </div>
                            <button onclick="openQuoteModal('Đàn Piano Yamaha YDP163R & Nhạc Cụ Học Quốc Tế', '17.500.000 ₫')" class="mt-2.5 w-full py-1.5 px-2 rounded bg-stone-100 hover:bg-brand-gold hover:text-white text-stone-700 font-semibold text-[11px] sm:text-xs transition">
                                Nhận báo giá ưu đãi
                            </button>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         [SECTION] GIỚI THIỆU CHUNG TÌNH PIANO & THẠC SĨ ÂM NHẠC (AMEB LEVEL 2 ĐẦU TIÊN TẠI ĐÀ NẴNG)
         ========================================== -->
    <section id="gioi-thieu" class="py-8 sm:py-10 bg-white border-y border-stone-200">
        <div class="container-flatsome">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-xl">VỀ TRUNG TÂM CHUNG TÌNH PIANO ĐÀ NẴNG</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-6 space-y-3.5 text-xs sm:text-sm text-stone-700 leading-relaxed">
                    <div class="text-brand-gold font-bold uppercase tracking-wider text-xs">
                        CHUNGTINHPIANO.COM • SOUL ART PIANO ĐÀ NẴNG
                    </div>
                    <h2 class="font-heading font-extrabold text-lg sm:text-2xl text-brand-dark leading-snug">
                        Đào Tạo Chuyên Sâu PIANO, GUITAR, VIOLIN Chuẩn Quốc Tế AMEB, ABRSM, LCM
                    </h2>
                    <p>
                        <strong>Chung Tình Piano</strong> tự hào là trung tâm đào tạo âm nhạc và cung cấp nhạc cụ uy tín hàng đầu tại TP. Đà Nẵng. Chương trình giảng dạy được dẫn dắt trực tiếp bởi <strong>Giảng viên là THẠC SĨ ÂM NHẠC</strong> và sở hữu <strong>Chứng chỉ Giáo viên Quốc tế AMEB LEVEL 2 đầu tiên tại ĐÀ NẴNG</strong>.
                    </p>
                    <ul class="space-y-2">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-brand-gold mt-1 shrink-0"></i>
                            <span><strong>Bộ môn đào tạo chuyên sâu:</strong> PIANO, GUITAR, VIOLIN… dành cho mọi lứa tuổi từ thiếu nhi đến người lớn và luyện thi chuyên nghiệp.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-brand-gold mt-1 shrink-0"></i>
                            <span><strong>Giáo trình chuẩn quốc tế:</strong> Áp dụng hệ thống giáo trình danh tiếng thế giới như <strong>AMEB (Úc), ABRSM (Anh), LCM (Anh)…</strong></span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-brand-gold mt-1 shrink-0"></i>
                            <span><strong>Phong phú về nội dung học:</strong> Đa dạng các nhánh đào tạo như <strong>CLASSIC (Cổ điển), FOR LEISURE (Giải trí ứng dụng), P-PLATE PIANO, BASTIEN NEW TRADITIONS…</strong> giúp học viên phát triển toàn diện kỹ thuật và cảm xúc âm nhạc.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-brand-gold mt-1 shrink-0"></i>
                            <span><strong>Điểm tham khảo giáo trình & tổ chức thi quốc tế:</strong> Không gian phòng học chuẩn quốc tế, trang bị 100% đàn Piano cơ & Grand Piano chất lượng cao tại <strong>99/39 Núi Thành, Phường Hòa Cường, TP. Đà Nẵng</strong>.</span>
                        </li>
                    </ul>
                    <div class="pt-2 flex flex-wrap gap-3">
                        <a href="#form-bao-gia" class="px-5 py-2.5 rounded bg-brand-gold hover:bg-brand-wood text-white font-bold text-xs uppercase transition">
                            Đăng Ký Học Thử & Tư Vấn Lộ Trình
                        </a>
                        <a href="tel:0987883003" class="px-5 py-2.5 rounded border border-brand-gold text-brand-gold hover:bg-brand-goldSoft font-bold text-xs uppercase transition">
                            Liên Hệ: 0987.883.003
                        </a>
                    </div>
                </div>

                <!-- 4 Ảnh nổi bật của Trung Tâm bên phải -->
                <div class="lg:col-span-6 grid grid-cols-2 gap-3">
                    <div class="rounded-lg overflow-hidden border border-stone-200 aspect-[4/3] bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1oTfAg0sNYwgXr50kAyGtVCBtEWDuxnBS&sz=w800"
                             onerror="handleDriveImgError(this, '1oTfAg0sNYwgXr50kAyGtVCBtEWDuxnBS', 'Trung+Tam+1')"
                             alt="Không gian đào tạo Chung Tình Piano 1" class="w-full h-full object-cover">
                    </div>
                    <div class="rounded-lg overflow-hidden border border-stone-200 aspect-[4/3] bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=107RZcfsXfxlSJaQwrFKmUOpDlsep2cdd&sz=w800"
                             onerror="handleDriveImgError(this, '107RZcfsXfxlSJaQwrFKmUOpDlsep2cdd', 'Trung+Tam+2')"
                             alt="Không gian đào tạo Chung Tình Piano 2" class="w-full h-full object-cover">
                    </div>
                    <div class="rounded-lg overflow-hidden border border-stone-200 aspect-[4/3] bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1Q1LBRkhMCFzFsHCOx84FM6ICVNE_6ZQy&sz=w800"
                             onerror="handleDriveImgError(this, '1Q1LBRkhMCFzFsHCOx84FM6ICVNE_6ZQy', 'Trung+Tam+3')"
                             alt="Không gian đào tạo Chung Tình Piano 3" class="w-full h-full object-cover">
                    </div>
                    <div class="rounded-lg overflow-hidden border border-stone-200 aspect-[4/3] bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1GplXmonRdwyNPtve8xPpdyyct9ZpUZgf&sz=w800"
                             onerror="handleDriveImgError(this, '1GplXmonRdwyNPtve8xPpdyyct9ZpUZgf', 'Trung+Tam+4')"
                             alt="Không gian đào tạo Chung Tình Piano 4" class="w-full h-full object-cover">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         [SECTION] HÌNH ẢNH HOẠT ĐỘNG & CƠ SỞ VẬT CHẤT TRUNG TÂM (Toàn bộ 12 ảnh trung tâm thực tế từ Google Drive)
         ========================================== -->
    <section id="trung-tam" class="py-8 sm:py-10">
        <div class="container-flatsome">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-xl">HÌNH ẢNH THỰC TẾ TẠI TRUNG TÂM CHUNG TÌNH PIANO</span>
                <b></b>
            </div>
            <p class="text-center text-xs sm:text-sm text-stone-600 max-w-3xl mx-auto mb-6">
                Không gian học tập nghệ thuật chuyên nghiệp, kỳ thi chứng chỉ quốc tế AMEB, ABRSM, LCM và hoạt động biểu diễn của học viên tại <strong>Chung Tình Piano - 99/39 Núi Thành, Đà Nẵng</strong>.
            </p>

            <!-- Lưới 12 ảnh thực tế của trung tâm: 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4">
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1oTfAg0sNYwgXr50kAyGtVCBtEWDuxnBS&sz=w800"
                             onerror="handleDriveImgError(this, '1oTfAg0sNYwgXr50kAyGtVCBtEWDuxnBS', 'Anh+Trung+Tam+1')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 1" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=107RZcfsXfxlSJaQwrFKmUOpDlsep2cdd&sz=w800"
                             onerror="handleDriveImgError(this, '107RZcfsXfxlSJaQwrFKmUOpDlsep2cdd', 'Anh+Trung+Tam+2')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 2" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1Q1LBRkhMCFzFsHCOx84FM6ICVNE_6ZQy&sz=w800"
                             onerror="handleDriveImgError(this, '1Q1LBRkhMCFzFsHCOx84FM6ICVNE_6ZQy', 'Anh+Trung+Tam+3')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 3" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1GplXmonRdwyNPtve8xPpdyyct9ZpUZgf&sz=w800"
                             onerror="handleDriveImgError(this, '1GplXmonRdwyNPtve8xPpdyyct9ZpUZgf', 'Anh+Trung+Tam+4')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 4" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1O6tlNO4aFnHGELf9klwPAmYB0K9d4mwa&sz=w800"
                             onerror="handleDriveImgError(this, '1O6tlNO4aFnHGELf9klwPAmYB0K9d4mwa', 'Anh+Trung+Tam+5')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 5" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1sG1Kk3d0ZESlEgJALX2eBUOe-4h7zSNi&sz=w800"
                             onerror="handleDriveImgError(this, '1sG1Kk3d0ZESlEgJALX2eBUOe-4h7zSNi', 'Anh+Trung+Tam+6')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 6" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1p3OEq2sT9g3sSuWLERFiiieQvK6Hag-1&sz=w800"
                             onerror="handleDriveImgError(this, '1p3OEq2sT9g3sSuWLERFiiieQvK6Hag-1', 'Anh+Trung+Tam+7')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 7" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1y3XrZ88trCP-kGyBV9i5oz383rgLvA9P&sz=w800"
                             onerror="handleDriveImgError(this, '1y3XrZ88trCP-kGyBV9i5oz383rgLvA9P', 'Anh+Trung+Tam+8')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 8" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1mE08LgoJjnNajfdbhLeBtlK653vc_Wia&sz=w800"
                             onerror="handleDriveImgError(this, '1mE08LgoJjnNajfdbhLeBtlK653vc_Wia', 'Anh+Trung+Tam+9')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 9" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1Zlfnnv_8rUHstUWEfwLsQ3kKxXeUGvcd&sz=w800"
                             onerror="handleDriveImgError(this, '1Zlfnnv_8rUHstUWEfwLsQ3kKxXeUGvcd', 'Anh+Trung+Tam+10')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 10" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=1M8cykH_tU64TXC5B6SS21yAr34JoCWHK&sz=w800"
                             onerror="handleDriveImgError(this, '1M8cykH_tU64TXC5B6SS21yAr34JoCWHK', 'Anh+Trung+Tam+11')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 11" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
                <div class="bg-white p-1.5 rounded-lg border border-stone-200 shadow-sm">
                    <div class="aspect-[4/3] rounded overflow-hidden bg-stone-100">
                        <img src="https://drive.google.com/thumbnail?id=19HGoJ-D9wDRFBLrxeNwknRGitgfyuRJx&sz=w800"
                             onerror="handleDriveImgError(this, '19HGoJ-D9wDRFBLrxeNwknRGitgfyuRJx', 'Anh+Trung+Tam+12')"
                             alt="Hình ảnh trung tâm Chung Tình Piano 12" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         [SECTION] DANH MỤC CÁC BÀI VIẾT TRANG CHỦ: KHÓA HỌC & ĐÀO TẠO + TIN TỨC CẨM NANG (Giống mẫu duongpiano.com)
         ========================================== -->
    <section id="khoa-hoc" class="py-8 sm:py-10 bg-white border-t border-stone-200">
        <div class="container-flatsome">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-xl">KHÓA HỌC & ĐÀO TẠO CHUẨN QUỐC TẾ</span>
                <b></b>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Bài viết khóa học 1 -->
                <article class="bg-[#F9F9F9] rounded-lg border border-stone-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-stone-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1O6tlNO4aFnHGELf9klwPAmYB0K9d4mwa&sz=w600"
                             onerror="handleDriveImgError(this, '1O6tlNO4aFnHGELf9klwPAmYB0K9d4mwa', 'Piano+Classic')"
                             alt="Lớp Piano Cổ Điển - Classical AMEB" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-bold text-brand-gold uppercase mb-1">AMEB • ABRSM • LCM</div>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-stone-800 hover:text-brand-gold">
                                Lớp Piano Cổ Điển – Classical Chuẩn Quốc Tế
                            </h3>
                            <p class="mt-1.5 text-[11px] sm:text-xs text-stone-600 line-clamp-3">
                                Chương trình Piano Classical chuẩn quốc tế AMEB, ABRSM, LCM được Thạc sĩ Âm nhạc trực tiếp giảng dạy bài bản từ cơ bản đến nâng cao.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block text-[11px] font-bold text-brand-gold hover:underline">
                            Đăng ký tư vấn khóa học →
                        </a>
                    </div>
                </article>

                <!-- Bài viết khóa học 2 -->
                <article class="bg-[#F9F9F9] rounded-lg border border-stone-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-stone-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1sG1Kk3d0ZESlEgJALX2eBUOe-4h7zSNi&sz=w600"
                             onerror="handleDriveImgError(this, '1sG1Kk3d0ZESlEgJALX2eBUOe-4h7zSNi', 'Piano+For+Leisure')"
                             alt="Lớp Piano For Leisure" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-bold text-brand-gold uppercase mb-1">CHƯƠNG TRÌNH AMEB</div>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-stone-800 hover:text-brand-gold">
                                Lớp Piano For Leisure – Âm Nhạc Phong Phú & Giải Trí
                            </h3>
                            <p class="mt-1.5 text-[11px] sm:text-xs text-stone-600 line-clamp-3">
                                Nhánh đào tạo Piano For Leisure trong hệ thống AMEB giúp học viên chinh phục các tác phẩm nhạc phim, nhạc nhẹ, Jazz, Pop cùng kỹ thuật chuẩn xác.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block text-[11px] font-bold text-brand-gold hover:underline">
                            Đăng ký tư vấn khóa học →
                        </a>
                    </div>
                </article>

                <!-- Bài viết khóa học 3 -->
                <article class="bg-[#F9F9F9] rounded-lg border border-stone-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-stone-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1p3OEq2sT9g3sSuWLERFiiieQvK6Hag-1&sz=w600"
                             onerror="handleDriveImgError(this, '1p3OEq2sT9g3sSuWLERFiiieQvK6Hag-1', 'Guitar+Violin')"
                             alt="Khóa học Guitar & Violin chuyên sâu" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-bold text-brand-gold uppercase mb-1">ĐÀO TẠO CHUYÊN SÂU</div>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-stone-800 hover:text-brand-gold">
                                Khóa Học Đàn Guitar & Violin Giáo Trình Quốc Tế
                            </h3>
                            <p class="mt-1.5 text-[11px] sm:text-xs text-stone-600 line-clamp-3">
                                Đào tạo chuyên sâu Guitar và Violin cho trẻ em và người lớn theo lộ trình cá nhân hóa, rèn luyện nhạc lý, kỹ thuật biểu diễn và thi chứng chỉ.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block text-[11px] font-bold text-brand-gold hover:underline">
                            Đăng ký tư vấn khóa học →
                        </a>
                    </div>
                </article>

                <!-- Bài viết khóa học 4 -->
                <article class="bg-[#F9F9F9] rounded-lg border border-stone-200 overflow-hidden hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-stone-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1y3XrZ88trCP-kGyBV9i5oz383rgLvA9P&sz=w600"
                             onerror="handleDriveImgError(this, '1y3XrZ88trCP-kGyBV9i5oz383rgLvA9P', 'P+Plate+Piano')"
                             alt="Lớp P-Plate Piano & Luyện thi chứng chỉ" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] font-bold text-brand-gold uppercase mb-1">CHỨNG CHỈ QUỐC TẾ</div>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-stone-800 hover:text-brand-gold">
                                Lớp P-Plate Piano & Luyện Thi AMEB, ABRSM, LCM
                            </h3>
                            <p class="mt-1.5 text-[11px] sm:text-xs text-stone-600 line-clamp-3">
                                Hướng dẫn bởi Thạc sĩ Âm nhạc có chứng chỉ Giáo viên Quốc tế AMEB Level 2 đầu tiên tại Đà Nẵng, giúp học viên tự tin đạt kết quả cao.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="mt-3 inline-block text-[11px] font-bold text-brand-gold hover:underline">
                            Đăng ký tư vấn khóa học →
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         [SECTION] DANH MỤC BÀI VIẾT TIN TỨC, CHÍNH SÁCH & DỊCH VỤ TRANG CHỦ
         ========================================== -->
    <section id="bai-viet" class="py-8 sm:py-10">
        <div class="container-flatsome">
            <div id="dich-vu" class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-xl">DANH MỤC BÀI VIẾT & CẨM NANG PIANO</span>
                <b></b>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-stone-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1mE08LgoJjnNajfdbhLeBtlK653vc_Wia&sz=w600"
                             onerror="handleDriveImgError(this, '1mE08LgoJjnNajfdbhLeBtlK653vc_Wia', 'Bai+Viet+1')"
                             alt="Tổng hợp các giáo trình chính trong hệ AMEB" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-stone-400">Giáo trình Quốc tế</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-stone-800 mt-0.5 hover:text-brand-gold">
                                Tổng Hợp Các Giáo Trình Chính Trong Hệ Thống Khảo Thí AMEB, ABRSM, LCM
                            </h3>
                            <p class="mt-1.5 text-[11px] sm:text-xs text-stone-600 line-clamp-2">
                                Tìm hiểu sự khác biệt và ưu điểm của bộ giáo trình quốc tế AMEB, ABRSM, LCM đang được giảng dạy trực tiếp tại Chung Tình Piano Đà Nẵng.
                            </p>
                        </div>
                        <span class="mt-2.5 text-[11px] font-semibold text-brand-gold">Xem chi tiết →</span>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-stone-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1Zlfnnv_8rUHstUWEfwLsQ3kKxXeUGvcd&sz=w600"
                             onerror="handleDriveImgError(this, '1Zlfnnv_8rUHstUWEfwLsQ3kKxXeUGvcd', 'Bai+Viet+2')"
                             alt="Hướng dẫn chọn mua đàn Piano" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-stone-400">Tư vấn chọn đàn</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-stone-800 mt-0.5 hover:text-brand-gold">
                                Kinh Nghiệm Chọn Mua Đàn Upright Piano Cơ & Piano Điện Cho Người Mới Bắt Đầu
                            </h3>
                            <p class="mt-1.5 text-[11px] sm:text-xs text-stone-600 line-clamp-2">
                                Cách kiểm tra số serial, bảng cộng hưởng Soundboard, máy đàn và độ nhạy bàn phím khi chọn đàn Piano Nhật Bản tại Đà Nẵng.
                            </p>
                        </div>
                        <span class="mt-2.5 text-[11px] font-semibold text-brand-gold">Xem chi tiết →</span>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-stone-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1M8cykH_tU64TXC5B6SS21yAr34JoCWHK&sz=w600"
                             onerror="handleDriveImgError(this, '1M8cykH_tU64TXC5B6SS21yAr34JoCWHK', 'Bai+Viet+3')"
                             alt="Quy trình chăm sóc bảo hành định kỳ" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-stone-400">Chính sách & Bảo hành</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-stone-800 mt-0.5 hover:text-brand-gold">
                                Quy Trình Lên Dây, Bảo Dưỡng Định Kỳ & Bàn Giao Đàn Tại Chung Tình Piano
                            </h3>
                            <p class="mt-1.5 text-[11px] sm:text-xs text-stone-600 line-clamp-2">
                                Dịch vụ kỹ thuật lên dây chuẩn tần số quốc tế, căn chỉnh Action và bảo quản đàn Piano thích ứng với khí hậu miền Trung.
                            </p>
                        </div>
                        <span class="mt-2.5 text-[11px] font-semibold text-brand-gold">Xem chi tiết →</span>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] bg-stone-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=19HGoJ-D9wDRFBLrxeNwknRGitgfyuRJx&sz=w600"
                             onerror="handleDriveImgError(this, '19HGoJ-D9wDRFBLrxeNwknRGitgfyuRJx', 'Bai+Viet+4')"
                             alt="Điểm thi và điểm sách AMEB tại Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] text-stone-400">Hoạt động đào tạo</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-stone-800 mt-0.5 hover:text-brand-gold">
                                Chung Tình Piano – Điểm Sách Giáo Trình & Tổ Chức Thi Quốc Tế AMEB Tại Đà Nẵng
                            </h3>
                            <p class="mt-1.5 text-[11px] sm:text-xs text-stone-600 line-clamp-2">
                                Quý phụ huynh, giáo viên và học viên có thể đến tham khảo trực tiếp bộ giáo trình gốc và trải nghiệm đàn tại 99/39 Núi Thành.
                            </p>
                        </div>
                        <span class="mt-2.5 text-[11px] font-semibold text-brand-gold">Xem chi tiết →</span>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         [SECTION] FORM YÊU CẦU TƯ VẤN KHÓA HỌC & BÁO GIÁ TRANG CHỦ
         ========================================== -->
    <section id="form-bao-gia" class="py-8 sm:py-10 bg-brand-dark text-white">
        <div class="container-flatsome">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <!-- Cột thông tin cam kết -->
                <div class="lg:col-span-5 space-y-3">
                    <span class="inline-block px-3 py-1 rounded bg-brand-gold text-white text-xs font-bold uppercase">
                        HỖ TRỢ NHANH CHÓNG 24/7
                    </span>
                    <h2 class="font-heading font-extrabold text-lg sm:text-2xl text-brand-goldLight leading-snug">
                        ĐĂNG KÝ TƯ VẤN KHÓA HỌC & NHẬN BÁO GIÁ ĐÀN PIANO
                    </h2>
                    <p class="text-xs sm:text-sm text-stone-300 leading-relaxed">
                        Quý phụ huynh, học viên và khách hàng cần tư vấn lộ trình học <strong>Piano, Guitar, Violin (AMEB, ABRSM, LCM)</strong> hoặc nhận báo giá ưu đãi các dòng đàn <strong>Grand Piano, Upright Piano, Digital Piano</strong> vui lòng để lại thông tin.
                    </p>
                    <div class="pt-2 space-y-2 text-xs sm:text-sm text-stone-200">
                        <div><i class="fa-solid fa-location-dot text-brand-goldLight w-5"></i> <strong>Địa chỉ:</strong> 99/39 Núi Thành, Phường Hòa Cường, TP. Đà Nẵng</div>
                        <div><i class="fa-solid fa-phone text-brand-goldLight w-5"></i> <strong>Hotline / Zalo:</strong> <a href="tel:0987883003" class="text-brand-goldLight font-bold">0987.883.003</a></div>
                        <div><i class="fa-solid fa-globe text-brand-goldLight w-5"></i> <strong>Website:</strong> chungtinhpiano.com</div>
                    </div>
                </div>

                <!-- Cột Form Yêu Cầu & Báo Giá -->
                <div class="lg:col-span-7">
                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="bg-white text-stone-800 p-4 sm:p-6 rounded-xl shadow-lg space-y-3.5">
                        <h3 class="font-heading font-bold text-sm sm:text-base text-brand-dark uppercase border-b border-stone-200 pb-2">
                            GỬI YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ ƯU ĐÃI
                        </h3>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">Họ và tên của bạn *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded focus:outline-none focus:border-brand-gold">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="qPhone" type="tel" required placeholder="Nhập số điện thoại (VD: 0987883003)..." class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded focus:outline-none focus:border-brand-gold">
                            </div>
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">Nội dung quan tâm *</label>
                                <select id="qService" class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded focus:outline-none focus:border-brand-gold bg-white">
                                    <option value="Báo giá mua đàn Upright / Grand Piano">Báo giá mua đàn Upright / Grand Piano</option>
                                    <option value="Báo giá mua đàn Digital Piano (Piano điện)">Báo giá mua đàn Digital Piano (Piano điện)</option>
                                    <option value="Đăng ký Khóa học Piano (AMEB, ABRSM, LCM)">Đăng ký Khóa học Piano (AMEB, ABRSM, LCM)</option>
                                    <option value="Đăng ký Khóa học Guitar / Violin">Đăng ký Khóa học Guitar / Violin</option>
                                    <option value="Dịch vụ Lên dây / Sửa chữa / Thuê đàn Piano">Dịch vụ Lên dây / Sửa chữa / Thuê đàn Piano</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">Sản phẩm / Cấp độ học (nếu có)</label>
                                <input id="qProduct" type="text" placeholder="VD: Yamaha U3H, Lớp Piano Classic..." class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded focus:outline-none focus:border-brand-gold">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-stone-700 mb-1">Ghi chú yêu cầu thêm</label>
                            <textarea id="qNote" rows="2" placeholder="Nhập yêu cầu chi tiết của bạn..." class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded focus:outline-none focus:border-brand-gold"></textarea>
                        </div>
                        <button type="submit" class="w-full py-2.5 px-4 bg-brand-gold hover:bg-brand-wood text-white font-heading font-bold text-xs sm:text-sm uppercase rounded transition shadow">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU & NHẬN BÁO GIÁ NGAY
                        </button>
                        <div id="quoteSuccessMsg" class="hidden p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium">
                            <i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i> Cảm ơn bạn! Yêu cầu của bạn đã được ghi nhận. Trung tâm <strong>Chung Tình Piano (0987.883.003)</strong> sẽ liên hệ tư vấn ngay!
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         [SECTION] DANH MỤC CÁC ĐỐI TÁC & HỆ THỐNG GIÁO TRÌNH QUỐC TẾ
         ========================================== -->
    <section class="py-8 bg-white border-b border-stone-200">
        <div class="container-flatsome">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-xl">ĐỐI TÁC CỦA CHÚNG TÔI</span>
                <b></b>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-3 text-center">
                <div class="p-3 rounded-lg border border-stone-200 bg-stone-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-extrabold text-sm sm:text-base text-brand-dark">AMEB</span>
                    <span class="text-[10px] text-stone-500">Hội Đồng Khảo Thí Úc</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-stone-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-extrabold text-sm sm:text-base text-brand-dark">ABRSM</span>
                    <span class="text-[10px] text-stone-500">Hiệp Hội Hoàng Gia Anh</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-stone-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-extrabold text-sm sm:text-base text-brand-dark">LCM</span>
                    <span class="text-[10px] text-stone-500">Học Viện Âm Nhạc London</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-stone-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-extrabold text-sm sm:text-base text-brand-dark">YAMAHA</span>
                    <span class="text-[10px] text-stone-500">Japan Piano</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-stone-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-extrabold text-sm sm:text-base text-brand-dark">KAWAI</span>
                    <span class="text-[10px] text-stone-500">Shigeru & Japan Piano</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-stone-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-extrabold text-sm sm:text-base text-brand-dark">STEINWAY</span>
                    <span class="text-[10px] text-stone-500">Steinway & Sons</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-stone-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-extrabold text-sm sm:text-base text-brand-dark">ROLAND</span>
                    <span class="text-[10px] text-stone-500">Digital Piano</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-stone-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-extrabold text-sm sm:text-base text-brand-dark">APOLLO</span>
                    <span class="text-[10px] text-stone-500">Toyo Piano Japan</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         [SECTION] ĐƯA FANPAGE FACEBOOK & ẢNH GOOGLE MAP RA NGOÀI TRANG CHỦ
         ========================================== -->
    <section id="lien-he-map" class="py-8 sm:py-10 bg-[#F9F9F9]">
        <div class="container-flatsome">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-xl">KẾT NỐI FANPAGE & BẢN ĐỒ GOOGLE MAP</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                <!-- ĐƯA FANPAGE RA NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-5 bg-white p-4 sm:p-5 rounded-xl border border-stone-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between border-b border-stone-100 pb-3 mb-3">
                            <div class="flex items-center gap-2.5">
                                <div class="w-10 h-10 rounded-full overflow-hidden border border-brand-gold p-0.5 bg-brand-goldSoft shrink-0">
                                    <img src="https://drive.google.com/thumbnail?id=1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v&sz=w200"
                                         onerror="handleDriveImgError(this, '1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v', 'Logo')"
                                         alt="Logo Chung Tình Piano" class="w-full h-full object-contain rounded-full">
                                </div>
                                <div>
                                    <h3 class="font-heading font-bold text-xs sm:text-sm text-stone-800">
                                        Chung Tình Piano - Soul Art Piano Đà Nẵng
                                    </h3>
                                    <div class="text-[11px] text-blue-600 font-medium">
                                        <i class="fa-brands fa-facebook mr-1"></i>facebook.com/soulartpianodanang
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Khung ảnh bìa Fanpage thực tế + Plugin Facebook -->
                        <div class="rounded-lg overflow-hidden border border-stone-200 mb-3 relative">
                            <img src="https://drive.google.com/thumbnail?id=1oTfAg0sNYwgXr50kAyGtVCBtEWDuxnBS&sz=w800"
                                 onerror="handleDriveImgError(this, '1oTfAg0sNYwgXr50kAyGtVCBtEWDuxnBS', 'Fanpage')"
                                 alt="Fanpage Chung Tình Piano Đà Nẵng" class="w-full h-44 object-cover">
                            <div class="p-3 bg-stone-50 text-xs text-stone-700 space-y-1">
                                <div class="font-bold text-stone-800">Đào tạo chuyên sâu: PIANO, GUITAR, VIOLIN…</div>
                                <p class="text-[11px] text-stone-600">
                                    Giáo trình chuẩn quốc tế AMEB, ABRSM, LCM. Giảng viên Thạc sĩ Âm nhạc - Chứng chỉ Giáo viên Quốc tế AMEB Level 2 đầu tiên tại Đà Nẵng.
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="flex flex-wrap gap-2.5">
                        <a href="https://www.facebook.com/soulartpianodanang" target="_blank" rel="noopener noreferrer" class="flex-1 py-2.5 px-3 bg-[#1877F2] hover:bg-blue-700 text-white text-center font-bold text-xs rounded transition">
                            <i class="fa-brands fa-facebook-f mr-1.5"></i> Truy Cập Fanpage Facebook
                        </a>
                        <a href="https://zalo.me/0987883003" target="_blank" rel="noopener noreferrer" class="py-2.5 px-3 bg-stone-100 hover:bg-stone-200 text-stone-800 font-bold text-xs rounded transition">
                            Nhắn Zalo
                        </a>
                    </div>
                </div>

                <!-- ĐƯA ẢNH & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-7 bg-white p-4 sm:p-5 rounded-xl border border-stone-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex flex-wrap items-center justify-between gap-2 border-b border-stone-100 pb-3 mb-3">
                            <div>
                                <h3 class="font-heading font-bold text-xs sm:text-sm text-stone-800 uppercase">
                                    <i class="fa-solid fa-map-location-dot text-brand-gold mr-1.5"></i> Bản Đồ Google Map Chung Tình Piano
                                </h3>
                                <p class="text-[11px] sm:text-xs text-stone-600 mt-0.5">
                                    Địa chỉ: <strong>99/39 Núi Thành, Phường Hòa Cường, TP. Đà Nẵng</strong> — ĐT: <strong>0987.883.003</strong>
                                </p>
                            </div>
                            <a href="https://share.google/OSjrQ4RnTrqGYFjf3" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded bg-brand-gold text-white font-bold text-xs hover:bg-brand-wood transition">
                                <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở Google Map Chỉ Đường
                            </a>
                        </div>

                        <!-- Google Map Embed trực tiếp 99/39 Núi Thành, Hòa Cường, Đà Nẵng -->
                        <div class="w-full h-64 sm:h-72 rounded-lg overflow-hidden border border-stone-200 relative bg-stone-100">
                            <iframe
                                title="Bản đồ Chung Tình Piano 99/39 Núi Thành Đà Nẵng"
                                src="https://maps.google.com/maps?q=99/39%20N%C3%BAi%20Th%C3%A0nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <div class="mt-3 pt-2 border-t border-stone-100 flex flex-wrap items-center justify-between gap-2 text-xs text-stone-600">
                        <span><i class="fa-solid fa-location-crosshairs text-brand-gold mr-1"></i> 99/39 Núi Thành, Phường Hòa Cường, TP. Đà Nẵng</span>
                        <a href="https://share.google/OSjrQ4RnTrqGYFjf3" target="_blank" rel="noopener noreferrer" class="text-brand-gold font-bold hover:underline">
                            Xem trên Google Maps (share.google/OSjrQ4RnTrqGYFjf3) →
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (Giống bố cục mẫu duongpiano.com)
         ========================================== -->
    <footer class="bg-brand-dark text-stone-300 pt-10 pb-6 border-t-4 border-brand-gold text-xs sm:text-sm">
        <div class="container-flatsome">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-stone-800">

                <!-- Cột 1: Thông tin liên hệ -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <div class="w-10 h-10 rounded-full overflow-hidden bg-white p-0.5 shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v&sz=w200"
                                 onerror="handleDriveImgError(this, '1N2uMy-6b_cYejlU6LJwP2rNpfcf4fw8v', 'Logo')"
                                 alt="Logo Chung Tình Piano" class="w-full h-full object-contain rounded-full">
                        </div>
                        <div>
                            <h3 class="font-heading font-extrabold text-base text-brand-goldLight">CHUNG TÌNH PIANO</h3>
                            <p class="text-[11px] text-stone-400">Website: chungtinhpiano.com</p>
                        </div>
                    </div>
                    <p class="text-xs text-stone-300 leading-relaxed">
                        Trung tâm đào tạo chuyên sâu <strong>PIANO, GUITAR, VIOLIN…</strong> chuẩn giáo trình quốc tế <strong>AMEB, ABRSM, LCM</strong> (Classic, For Leisure…). Giảng viên là <strong>THẠC SĨ ÂM NHẠC</strong> và có chứng chỉ giáo viên quốc tế <strong>AMEB LEVEL 2 đầu tiên tại ĐÀ NẴNG</strong>. Chuyên cung cấp đàn Grand Piano, Upright Piano, Digital Piano chính hãng.
                    </p>
                    <ul class="space-y-1.5 text-xs">
                        <li><i class="fa-solid fa-location-dot text-brand-goldLight w-5"></i> <strong>Địa chỉ:</strong> 99/39 Núi Thành, Phường Hòa Cường, Tp. Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-brand-goldLight w-5"></i> <strong>Điện thoại / Zalo:</strong> <a href="tel:0987883003" class="text-white font-bold hover:text-brand-goldLight">0987.883.003</a></li>
                        <li><i class="fa-brands fa-facebook text-brand-goldLight w-5"></i> <strong>Fanpage:</strong> <a href="https://www.facebook.com/soulartpianodanang" target="_blank" rel="noopener noreferrer" class="hover:text-brand-goldLight">facebook.com/soulartpianodanang</a></li>
                        <li><i class="fa-solid fa-map text-brand-goldLight w-5"></i> <strong>Google Map:</strong> <a href="https://share.google/OSjrQ4RnTrqGYFjf3" target="_blank" rel="noopener noreferrer" class="hover:text-brand-goldLight">Xem vị trí chỉ đường</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm & khóa học -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="font-heading font-bold text-sm text-white uppercase tracking-wider border-b border-stone-700 pb-2">
                        DANH MỤC NỔI BẬT
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham" onclick="filterProducts('grand')" class="hover:text-brand-goldLight transition">• Special Grand Piano</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('upright')" class="hover:text-brand-goldLight transition">• Upright Piano Nhật Bản</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('digital')" class="hover:text-brand-goldLight transition">• Digital Piano (Piano Điện)</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('guitar-violin')" class="hover:text-brand-goldLight transition">• Đàn Guitar & Đàn Violin</a></li>
                        <li><a href="#khoa-hoc" class="hover:text-brand-goldLight transition">• Khóa Học Quốc Tế AMEB, ABRSM, LCM</a></li>
                        <li><a href="#dich-vu" class="hover:text-brand-goldLight transition">• Dịch Vụ Sửa Chữa, Lên Dây & Cho Thuê Piano</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách & Hỗ trợ khách hàng -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h4 class="font-heading font-bold text-sm text-white uppercase tracking-wider border-b border-stone-700 pb-2">
                        THÔNG TIN & CHÍNH SÁCH
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#gioi-thieu" class="hover:text-brand-goldLight transition">• Giới thiệu Chung Tình Piano</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-brand-goldLight transition">• Chính sách bảo hành & hậu mãi tận nhà</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-brand-goldLight transition">• Chính sách vận chuyển & bàn giao đàn</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-brand-goldLight transition">• Phương thức thanh toán & hỗ trợ trả góp</a></li>
                        <li><a href="#bai-viet" class="hover:text-brand-goldLight transition">• Tra cứu giáo trình quốc tế AMEB / ABRSM / LCM</a></li>
                    </ul>
                </div>

            </div>

            <div class="pt-5 text-center text-xs text-stone-400">
                Copyright 2026 © <strong>CHUNGTINHPIANO.COM</strong> - Chung Tình Piano (99/39 Núi Thành, Phường Hòa Cường, TP. Đà Nẵng | ĐT: 0987.883.003)
            </div>
        </div>
    </footer>

    <!-- ==========================================
         MODAL NHẬN BÁO GIÁ NHANH KHI BẤM VÀO SẢN PHẨM
         ========================================== -->
    <div id="quoteModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-4">
        <div class="bg-white rounded-xl max-w-md w-full p-5 shadow-2xl relative">
            <button onclick="closeQuoteModal()" class="absolute top-3 right-3 text-stone-400 hover:text-stone-700 p-1">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
            <h3 class="font-heading font-bold text-sm sm:text-base text-brand-dark uppercase pr-6">
                Yêu Cầu Báo Giá Sản Phẩm
            </h3>
            <p id="modalProductName" class="text-xs font-semibold text-brand-gold mt-1"></p>
            <form onsubmit="submitModalQuote(event)" class="mt-3 space-y-3">
                <input id="mName" type="text" required placeholder="Họ và tên của bạn *" class="w-full px-3 py-2 text-xs border border-stone-300 rounded focus:outline-none focus:border-brand-gold">
                <input id="mPhone" type="tel" required placeholder="Số điện thoại / Zalo *" class="w-full px-3 py-2 text-xs border border-stone-300 rounded focus:outline-none focus:border-brand-gold">
                <textarea id="mNote" rows="2" placeholder="Yêu cầu tư vấn thêm..." class="w-full px-3 py-2 text-xs border border-stone-300 rounded focus:outline-none focus:border-brand-gold"></textarea>
                <button type="submit" class="w-full py-2.5 bg-brand-gold hover:bg-brand-wood text-white font-bold text-xs uppercase rounded transition">
                    Gửi Yêu Cầu Tư Vấn Ngay
                </button>
                <div id="modalSuccessMsg" class="hidden p-2.5 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs">
                    Đã gửi yêu cầu thành công! Chung Tình Piano (0987.883.003) sẽ liên hệ bạn ngay.
                </div>
            </form>
        </div>
    </div>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
         Tương thích hoàn hảo trên máy tính và điện thoại, không gây tràn viền
         ========================================== -->
    <div class="fixed bottom-4 right-3 sm:right-5 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/soulartpianodanang" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 sm:px-3.5 sm:py-2.5 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
           title="Chat Facebook Fanpage">
            <i class="fa-brands fa-facebook-f text-sm sm:text-base w-4 text-center"></i>
            <span class="text-[11px] sm:text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0987883003" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white px-3 py-2 sm:px-3.5 sm:py-2.5 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
           title="Nhắn tin Zalo 0987.883.003">
            <span class="font-extrabold text-[11px] sm:text-xs bg-white text-[#0068FF] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
            <span class="text-[11px] sm:text-xs font-bold pr-1">0987.883.003</span>
        </a>

        <!-- Nút Gọi Hotline Nổi Bật -->
        <a href="tel:0987883003"
           class="float-btn-pulse flex items-center gap-2 bg-brand-sale hover:bg-red-700 text-white px-3.5 py-2.5 sm:px-4 sm:py-2.5 rounded-full shadow-xl transition"
           title="Gọi Hotline 0987.883.003">
            <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
            <span class="text-xs sm:text-sm font-extrabold tracking-wide">0987.883.003</span>
        </a>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ SLIDER TỰ TRƯỢT, LỌC DANH MỤC & FORM BÁO GIÁ
         ========================================== -->
    <script>
        // 1. Tự động trượt 2 ảnh Banner chuyên nghiệp (Desktop & Mobile đồng bộ)
        let currentBannerIndex = 0;
        const totalBannerSlides = 2;
        let bannerInterval = null;

        function updateBannerDisplay() {
            for (let i = 0; i < totalBannerSlides; i++) {
                const dSlide = document.getElementById('desktopSlide' + i);
                const mSlide = document.getElementById('mobileSlide' + i);
                const dot = document.getElementById('bannerDot' + i);

                if (i === currentBannerIndex) {
                    if (dSlide) { dSlide.classList.remove('opacity-0', 'z-0'); dSlide.classList.add('opacity-100', 'z-10'); }
                    if (mSlide) { mSlide.classList.remove('opacity-0', 'z-0'); mSlide.classList.add('opacity-100', 'z-10'); }
                    if (dot) { dot.className = 'w-6 h-1.5 rounded-full bg-brand-goldLight transition-all'; }
                } else {
                    if (dSlide) { dSlide.classList.remove('opacity-100', 'z-10'); dSlide.classList.add('opacity-0', 'z-0'); }
                    if (mSlide) { mSlide.classList.remove('opacity-100', 'z-10'); mSlide.classList.add('opacity-0', 'z-0'); }
                    if (dot) { dot.className = 'w-2.5 h-1.5 rounded-full bg-white/50 transition-all'; }
                }
            }
        }

        function nextBannerSlide() {
            currentBannerIndex = (currentBannerIndex + 1) % totalBannerSlides;
            updateBannerDisplay();
            resetBannerTimer();
        }

        function prevBannerSlide() {
            currentBannerIndex = (currentBannerIndex - 1 + totalBannerSlides) % totalBannerSlides;
            updateBannerDisplay();
            resetBannerTimer();
        }

        function goToBannerSlide(index) {
            currentBannerIndex = index;
            updateBannerDisplay();
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(nextBannerSlide, 5000);
        }

        window.addEventListener('DOMContentLoaded', function () {
            resetBannerTimer();
        });

        // 2. Menu Điện Thoại & Thanh Tìm Kiếm
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            const overlay = document.getElementById('mobileMenuOverlay');
            const isClosed = drawer.classList.contains('-translate-x-full');
            if (isClosed) {
                drawer.classList.remove('-translate-x-full');
                overlay.classList.remove('hidden');
            } else {
                drawer.classList.add('-translate-x-full');
                overlay.classList.add('hidden');
            }
        }

        function toggleMobileSearch() {
            const bar = document.getElementById('mobileSearchBar');
            bar.classList.toggle('hidden');
        }

        function handleSearchSubmit(e) {
            e.preventDefault();
            const qDesktop = document.getElementById('desktopSearchInput').value.trim().toLowerCase();
            const qMobile = document.getElementById('mobileSearchInput').value.trim().toLowerCase();
            const keyword = qDesktop || qMobile;

            const cards = document.querySelectorAll('.product-card');
            cards.forEach(card => {
                const text = card.innerText.toLowerCase();
                if (!keyword || text.includes(keyword)) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
            document.getElementById('san-pham').scrollIntoView({ behavior: 'smooth' });
        }

        // 3. Lọc Danh Mục Sản Phẩm Trang Chủ
        function filterProducts(cat) {
            const cards = document.querySelectorAll('.product-card');
            cards.forEach(card => {
                const itemCat = card.getAttribute('data-cat');
                if (cat === 'all' || itemCat === cat) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });

            const pills = document.querySelectorAll('.cat-pill');
            pills.forEach(btn => {
                btn.classList.remove('bg-brand-gold', 'text-white', 'border-brand-gold');
                btn.classList.add('bg-stone-50', 'text-stone-700', 'border-stone-200');
            });
            if (event && event.currentTarget && event.currentTarget.classList.contains('cat-pill')) {
                event.currentTarget.classList.remove('bg-stone-50', 'text-stone-700', 'border-stone-200');
                event.currentTarget.classList.add('bg-brand-gold', 'text-white', 'border-brand-gold');
            }
        }

        // 4. Xử lý Form Yêu Cầu & Báo Giá
        function submitQuoteForm(e) {
            e.preventDefault();
            const msg = document.getElementById('quoteSuccessMsg');
            msg.classList.remove('hidden');
            document.getElementById('quoteForm').reset();
        }

        function openQuoteModal(productName, price) {
            const modal = document.getElementById('quoteModal');
            document.getElementById('modalProductName').textContent = productName + ' (' + price + ')';
            document.getElementById('modalSuccessMsg').classList.add('hidden');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeQuoteModal() {
            const modal = document.getElementById('quoteModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function submitModalQuote(e) {
            e.preventDefault();
            document.getElementById('modalSuccessMsg').classList.remove('hidden');
            setTimeout(() => {
                closeQuoteModal();
            }, 2200);
        }
    </script>
</body>
</html>
