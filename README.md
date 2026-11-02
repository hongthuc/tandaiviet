<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>Tân Đại Việt - Thiết Kế & Thi Công Quảng Cáo Nội Thất Đà Nẵng | tandaiviet.com</title>
  <meta name="description" content="CÔNG TY TNHH THIẾT KẾ THI CÔNG QUẢNG CÁO TÂN ĐẠI VIỆT - Chuyên thiết kế thi công bảng hiệu quảng cáo, chữ nổi Inox, Mica, Alu, cắt CNC Laser, in phun khổ lớn và nội thất showroom tại Đà Nẵng.">
  <meta name="keywords" content="quảng cáo tân đại việt, làm bảng hiệu đà nẵng, chữ nổi quảng cáo đà nẵng, cắt cnc laser đà nẵng, tandaiviet.com">

  <!-- Open Graph / Zalo / Facebook Link Thumbnail là Logo trang web -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://tandaiviet.com/">
  <meta property="og:site_name" content="tandaiviet.com - Quảng Cáo Tân Đại Việt">
  <meta property="og:title" content="CÔNG TY TNHH THIẾT KẾ THI CÔNG QUẢNG CÁO TÂN ĐẠI VIỆT">
  <meta property="og:description" content="Chuyên Thiết kế & Thi công Quảng cáo, Chữ nổi Inox - Mica - Đèn LED, Cắt khắc CNC - Laser, In phun khổ lớn, Showroom Nội Ngoại thất tại Đà Nẵng. Hotline: 0987.919.069 – 0369.561.458">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1a_drCTyMM41L7uinFZuK-itHgrr0KxD2=w1200">
  <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1a_drCTyMM41L7uinFZuK-itHgrr0KxD2&sz=w1200">
  <meta property="og:image:alt" content="Logo Công Ty Quảng Cáo Tân Đại Việt Đà Nẵng">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1a_drCTyMM41L7uinFZuK-itHgrr0KxD2=w1200">
  <link rel="icon" href="https://lh3.googleusercontent.com/d/1a_drCTyMM41L7uinFZuK-itHgrr0KxD2=w200">

  <!-- Tailwind CSS & Font Awesome -->
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Roboto', 'sans-serif'],
          },
          colors: {
            primary: '#0b4f94',     /* Xanh thương hiệu chuẩn ngành quảng cáo */
            primaryDark: '#07386b',
            accent: '#d9232d',      /* Đỏ điểm nhấn giảm giá & tiêu đề Flatsome */
            flatsomeBg: '#f5f7fa',
          }
        }
      }
    }
  </script>

  <style>
    /* Khóa tràn viền ngang tuyệt đối trên cả máy tính và điện thoại */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Roboto', sans-serif;
      background-color: #f5f7fa;
      color: #222222;
      scroll-behavior: smooth;
    }

    /* Chuẩn container Flatsome (rộng tối đa 1230px, căn giữa hoàn toàn) */
    .fs-container {
      width: 100%;
      max-width: 1230px;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    /* Chuẩn Section Title Flatsome (Style Normal / Center / Bold) */
    .fs-section-title {
      position: relative;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #e2e8f0;
      margin-bottom: 20px;
      margin-top: 25px;
    }
    .fs-section-title-main {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background-color: #0b4f94;
      color: #ffffff;
      font-weight: 700;
      text-transform: uppercase;
      padding: 9px 18px;
      font-size: 15px;
      border-top-left-radius: 6px;
      border-top-right-radius: 6px;
      position: relative;
      bottom: -2px;
    }
    @media (min-width: 768px) {
      .fs-section-title-main {
        font-size: 16px;
        padding: 10px 22px;
      }
    }

    /* Chuẩn Badge % giảm giá góc trên bên trái của Flatsome */
    .fs-badge-sale {
      position: absolute;
      top: 10px;
      left: 10px;
      z-index: 10;
      width: 44px;
      height: 44px;
      border-radius: 9999px;
      background-color: #d9232d;
      color: #ffffff;
      font-weight: 700;
      font-size: 13px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 6px rgba(217, 35, 45, 0.35);
      line-height: 1;
      pointer-events: none;
    }

    /* Card Sản Phẩm Flatsome */
    .fs-product-box {
      background: #ffffff;
      border-radius: 8px;
      border: 1px solid #e5e7eb;
      overflow: hidden;
      transition: transform 0.25s ease, box-shadow 0.25s ease;
      display: flex;
      flex-direction: column;
      height: 100%;
    }
    .fs-product-box:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.08);
      border-color: #cbd5e1;
    }

    /* Khung ảnh tỷ lệ chuẩn không bị méo */
    .fs-aspect-product {
      position: relative;
      width: 100%;
      aspect-ratio: 4 / 3;
      overflow: hidden;
      background-color: #f1f5f9;
    }
    .fs-aspect-product img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.4s ease;
    }
    .fs-product-box:hover .fs-aspect-product img {
      transform: scale(1.05);
    }

    /* Slider banner chuẩn không bị đè khuất */
    .fs-banner-slider {
      position: relative;
      width: 100%;
      overflow: hidden;
      border-radius: 10px;
      background-color: #072b52;
    }
    .banner-slide {
      display: none;
      width: 100%;
      position: relative;
    }
    .banner-slide.active {
      display: block;
    }

    /* Hiệu ứng rung nhẹ cho nút liên hệ nổi */
    @keyframes pulseRing {
      0% { box-shadow: 0 0 0 0 rgba(217, 35, 45, 0.55); }
      70% { box-shadow: 0 0 0 12px rgba(217, 35, 45, 0); }
      100% { box-shadow: 0 0 0 0 rgba(217, 35, 45, 0); }
    }
    .pulse-btn {
      animation: pulseRing 2s infinite;
    }
  </style>

  <!-- Script xử lý ảnh Google Drive đa luồng -->
  <script>
    function retryDriveImage(imgEl, fileId) {
      const step = parseInt(imgEl.getAttribute('data-retry') || '0', 10);
      if (step === 0) {
        imgEl.setAttribute('data-retry', '1');
        imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1200';
      } else if (step === 1) {
        imgEl.setAttribute('data-retry', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
      } else {
        imgEl.onerror = null;
        const svgFallback = `<svg xmlns="http://www.w3.org/2000/svg" width="600" height="450" viewBox="0 0 600 450"><rect width="100%" height="100%" fill="#0b4f94"/><text x="50%" y="46%" dominant-baseline="middle" text-anchor="middle" fill="#ffffff" font-family="Arial" font-weight="bold" font-size="22">QUẢNG CÁO TÂN ĐẠI VIỆT</text><text x="50%" y="56%" dominant-baseline="middle" text-anchor="middle" fill="#93c5fd" font-family="Arial" font-size="15">tandaiviet.com | 0987.919.069</text></svg>`;
        imgEl.src = 'data:image/svg+xml;utf8,' + encodeURIComponent(svgFallback);
      }
    }
  </script>
</head>

<body class="w-full overflow-x-hidden">

  <!-- =====================================================================
       1. TOPBAR FLATSOME
       ===================================================================== -->
  <div class="bg-primaryDark text-white text-xs py-2 border-b border-blue-900">
    <div class="fs-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-2 font-medium truncate">
        <i class="fa-solid fa-building text-yellow-400"></i>
        <span class="truncate">CÔNG TY TNHH THIẾT KẾ THI CÔNG QUẢNG CÁO TÂN ĐẠI VIỆT</span>
      </div>
      <div class="hidden md:flex items-center gap-5 text-blue-100">
        <span><i class="fa-solid fa-location-dot text-yellow-400 mr-1"></i>VP: 149 Hoàng Diệu, Đà Nẵng</span>
        <span><i class="fa-solid fa-industry text-yellow-400 mr-1"></i>Xưởng: K88/9B Lê Đình Lý, Đà Nẵng</span>
        <span><i class="fa-solid fa-globe text-yellow-400 mr-1"></i>tandaiviet.com</span>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       2. HEADER FLATSOME
       ===================================================================== -->
  <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-gray-200">
    <div class="fs-container py-2.5 md:py-3.5">
      <div class="flex items-center justify-between gap-3">
        <!-- Nút mở Menu trên Điện thoại -->
        <button onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden w-10 h-10 flex items-center justify-center rounded-md border border-gray-200 text-gray-700 hover:bg-gray-100 shrink-0">
          <i class="fa-solid fa-bars text-lg"></i>
        </button>

        <!-- Logo + Tên công ty -->
        <a href="#trang-chu" class="flex items-center gap-2.5 md:gap-3 min-w-0">
          <img
            src="https://lh3.googleusercontent.com/d/1a_drCTyMM41L7uinFZuK-itHgrr0KxD2=w400"
            onerror="retryDriveImage(this, '1a_drCTyMM41L7uinFZuK-itHgrr0KxD2')"
            alt="Logo Quảng Cáo Tân Đại Việt"
            class="h-11 w-11 md:h-14 md:w-14 object-contain rounded bg-white p-0.5 border border-gray-100 shrink-0"
          >
          <div class="min-w-0">
            <div class="text-primary font-black text-sm sm:text-base md:text-lg leading-tight truncate">
              QUẢNG CÁO TÂN ĐẠI VIỆT
            </div>
            <div class="text-[11px] md:text-xs text-gray-500 truncate">
              Thiết Kế & Thi Công Bảng Hiệu - Nội Thất Đà Nẵng
            </div>
          </div>
        </a>

        <!-- Ô tìm kiếm (Desktop) -->
        <div class="hidden md:flex flex-1 max-w-md mx-4">
          <form onsubmit="handleSearch(event)" class="w-full flex">
            <input
              id="desktopSearchInput"
              type="text"
              placeholder="Tìm bảng hiệu Alu, chữ nổi Inox, cắt CNC, in bạt..."
              class="w-full px-3.5 py-2 text-sm border border-gray-300 rounded-l-md focus:outline-none focus:border-primary"
            >
            <button type="submit" class="bg-primary hover:bg-primaryDark text-white px-4 py-2 rounded-r-md text-sm font-medium transition">
              <i class="fa-solid fa-magnifying-glass"></i>
            </button>
          </form>
        </div>

        <!-- Thông tin văn phòng & xưởng (Desktop) -->
        <div class="hidden xl:flex items-center gap-5 text-xs text-gray-600 shrink-0">
          <div class="flex items-center gap-2">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-primary flex items-center justify-center">
              <i class="fa-solid fa-map-location-dot"></i>
            </div>
            <div>
              <div class="font-bold text-gray-800">149 Hoàng Diệu</div>
              <div>Văn phòng Đà Nẵng</div>
            </div>
          </div>
          <div class="flex items-center gap-2">
            <div class="w-8 h-8 rounded-full bg-red-50 text-accent flex items-center justify-center">
              <i class="fa-solid fa-gears"></i>
            </div>
            <div>
              <div class="font-bold text-gray-800">K88/9B Lê Đình Lý</div>
              <div>Xưởng SX trực tiếp</div>
            </div>
          </div>
        </div>
      </div>

      <!-- Tìm kiếm trên Mobile -->
      <div class="mt-2.5 md:hidden">
        <form onsubmit="handleMobileSearch(event)" class="w-full flex">
          <input
            id="mobileSearchInput"
            type="text"
            placeholder="Tìm dịch vụ: Bảng hiệu, Chữ nổi, CNC..."
            class="w-full px-3 py-1.5 text-xs border border-gray-300 rounded-l-md focus:outline-none focus:border-primary"
          >
          <button type="submit" class="bg-primary text-white px-3.5 py-1.5 rounded-r-md text-xs">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </form>
      </div>
    </div>

    <!-- Navigation Menu (Desktop) -->
    <nav class="hidden lg:block bg-primary text-white">
      <div class="fs-container flex items-center justify-between">
        <div class="relative group">
          <div class="bg-accent px-5 py-3 font-bold text-sm uppercase flex items-center gap-2.5 cursor-pointer">
            <i class="fa-solid fa-bars-staggered"></i>
            <span>DANH MỤC SẢN PHẨM</span>
            <i class="fa-solid fa-chevron-down text-xs ml-1"></i>
          </div>
          <div class="absolute left-0 top-full w-72 bg-white text-gray-800 shadow-xl border border-gray-200 rounded-b-md opacity-0 invisible group-hover:opacity-100 group-hover:visible transition-all duration-200 z-50 divide-y divide-gray-100">
            <a href="#cat-thi-cong-quang-cao" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-primary text-sm font-medium transition">
              <span><i class="fa-solid fa-sign-hanging w-6 text-primary"></i>Thi Công Quảng Cáo</span>
              <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
            </a>
            <a href="#cat-chu-noi" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-primary text-sm font-medium transition">
              <span><i class="fa-solid fa-font w-6 text-primary"></i>Chữ Nổi Quảng Cáo</span>
              <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
            </a>
            <a href="#cat-cnc-laser" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-primary text-sm font-medium transition">
              <span><i class="fa-solid fa-wand-magic-sparkles w-6 text-primary"></i>CNC – Cắt Laser – Uốn Inox</span>
              <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
            </a>
            <a href="#cat-in-phun" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-primary text-sm font-medium transition">
              <span><i class="fa-solid fa-print w-6 text-primary"></i>In Phun Khổ Lớn</span>
              <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
            </a>
            <a href="#cat-showroom" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-primary text-sm font-medium transition">
              <span><i class="fa-solid fa-store w-6 text-primary"></i>Showroom Nội Ngoại Thất</span>
              <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
            </a>
            <a href="#cat-cnc-go" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-primary text-sm font-medium transition">
              <span><i class="fa-solid fa-layer-group w-6 text-primary"></i>Cắt CNC Gỗ Công Nghiệp</span>
              <i class="fa-solid fa-angle-right text-xs text-gray-400"></i>
            </a>
          </div>
        </div>

        <ul class="flex items-center text-xs xl:text-sm font-bold uppercase tracking-wide">
          <li><a href="#trang-chu" class="block px-3.5 py-3 hover:bg-primaryDark transition">Trang Chủ</a></li>
          <li><a href="#danh-muc-trang-chu" class="block px-3.5 py-3 hover:bg-primaryDark transition">Danh Mục</a></li>
          <li><a href="#cat-thi-cong-quang-cao" class="block px-3.5 py-3 hover:bg-primaryDark transition">Thi Công Quảng Cáo</a></li>
          <li><a href="#cat-chu-noi" class="block px-3.5 py-3 hover:bg-primaryDark transition">Chữ Nổi</a></li>
          <li><a href="#cat-cnc-laser" class="block px-3.5 py-3 hover:bg-primaryDark transition">CNC - Laser</a></li>
          <li><a href="#du-an-thuc-te" class="block px-3.5 py-3 hover:bg-primaryDark transition">Dự Án Đã Làm</a></li>
          <li><a href="#form-bao-gia" class="block px-3.5 py-3 hover:bg-primaryDark transition">Báo Giá</a></li>
          <li><a href="#tin-tuc" class="block px-3.5 py-3 hover:bg-primaryDark transition">Bài Viết</a></li>
          <li><a href="#lien-he-map" class="block px-3.5 py-3 hover:bg-primaryDark transition">Bản Đồ & Fanpage</a></li>
        </ul>
      </div>
    </nav>

    <!-- Menu Drawer (Mobile) -->
    <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
      <div onclick="toggleMobileMenu()" class="absolute inset-0 bg-black/60"></div>
      <div class="relative w-72 max-w-[82vw] h-full bg-white shadow-2xl flex flex-col justify-between overflow-y-auto">
        <div>
          <div class="p-4 bg-primary text-white flex items-center justify-between">
            <span class="font-bold text-sm uppercase">Danh Mục Tân Đại Việt</span>
            <button onclick="toggleMobileMenu()" class="w-8 h-8 rounded flex items-center justify-center bg-white/10">
              <i class="fa-solid fa-xmark"></i>
            </button>
          </div>
          <div class="divide-y divide-gray-100 text-sm font-medium text-gray-800">
            <a onclick="toggleMobileMenu()" href="#trang-chu" class="block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-house w-6 text-primary"></i>Trang Chủ</a>
            <a onclick="toggleMobileMenu()" href="#cat-thi-cong-quang-cao" class="block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-sign-hanging w-6 text-primary"></i>Thi Công Quảng Cáo</a>
            <a onclick="toggleMobileMenu()" href="#cat-chu-noi" class="block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-font w-6 text-primary"></i>Chữ Nổi Quảng Cáo</a>
            <a onclick="toggleMobileMenu()" href="#cat-cnc-laser" class="block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-wand-magic-sparkles w-6 text-primary"></i>CNC – Cắt Laser – Uốn Inox</a>
            <a onclick="toggleMobileMenu()" href="#cat-in-phun" class="block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-print w-6 text-primary"></i>In Phun Khổ Lớn</a>
            <a onclick="toggleMobileMenu()" href="#cat-showroom" class="block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-store w-6 text-primary"></i>Showroom Nội Ngoại Thất</a>
            <a onclick="toggleMobileMenu()" href="#cat-cnc-go" class="block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-layer-group w-6 text-primary"></i>Cắt CNC Gỗ Công Nghiệp</a>
            <a onclick="toggleMobileMenu()" href="#du-an-thuc-te" class="block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-images w-6 text-primary"></i>Hình Ảnh Thi Công Thực Tế</a>
            <a onclick="toggleMobileMenu()" href="#form-bao-gia" class="block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-file-invoice-dollar w-6 text-primary"></i>Yêu Cầu Báo Giá</a>
            <a onclick="toggleMobileMenu()" href="#tin-tuc" class="block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-newspaper w-6 text-primary"></i>Danh Mục Bài Viết</a>
            <a onclick="toggleMobileMenu()" href="#lien-he-map" class="block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-map-location-dot w-6 text-primary"></i>Bản Đồ & Fanpage</a>
          </div>
        </div>
        <div class="p-4 bg-gray-50 border-t border-gray-200 text-xs text-gray-600 space-y-1.5">
          <div class="font-bold text-primary">CÔNG TY QUẢNG CÁO TÂN ĐẠI VIỆT</div>
          <div><i class="fa-solid fa-location-dot mr-1 text-accent"></i>VP: 149 Hoàng Diệu, Đà Nẵng</div>
          <div><i class="fa-solid fa-industry mr-1 text-accent"></i>Xưởng: K88/9B Lê Đình Lý, Đà Nẵng</div>
          <div><i class="fa-solid fa-phone mr-1 text-accent"></i>0987.919.069 – 0369.561.458</div>
        </div>
      </div>
    </div>
  </header>

  <!-- =====================================================================
       3. 2 ẢNH BANNER TỰ TRƯỢT (Đã sửa lỗi hiển thị tầng, không bị đè khuất)
       ===================================================================== -->
  <section id="trang-chu" class="py-3 md:py-4">
    <div class="fs-container">
      <div class="fs-banner-slider shadow-md group" id="mainBannerSlider">

        <!-- SLIDE 1 -->
        <div class="banner-slide active">
          <div class="relative w-full aspect-[16/8] sm:aspect-[21/8] max-h-[460px] min-h-[220px]">
            <img
              src="https://lh3.googleusercontent.com/d/1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY=w1600"
              onerror="retryDriveImage(this, '1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY')"
              alt="Banner 1 - Công ty TNHH Thiết kế Thi công Quảng cáo Tân Đại Việt"
              class="w-full h-full object-cover"
            >
            <div class="absolute inset-0 bg-gradient-to-r from-slate-950/85 via-slate-900/60 to-transparent flex items-center">
              <div class="px-5 sm:px-10 md:px-14 max-w-2xl text-white space-y-2 sm:space-y-3">
                <p class="text-yellow-400 font-bold text-xs sm:text-sm uppercase tracking-wider">
                  CÔNG TY TNHH THIẾT KẾ THI CÔNG QUẢNG CÁO TÂN ĐẠI VIỆT
                </p>
                <h1 class="text-base sm:text-2xl md:text-4xl font-black leading-tight uppercase">
                  THIẾT KẾ & THI CÔNG BẢNG HIỆU QUẢNG CÁO TRỌN GÓI ĐÀ NẴNG
                </h1>
                <p class="text-xs sm:text-sm text-gray-200 line-clamp-2">
                  Chuyên mặt dựng Alu, chữ nổi Inox - Mica đèn LED, Pano, Hộp đèn, Showroom nội ngoại thất. Sản xuất trực tiếp tại xưởng K88/9B Lê Đình Lý.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-2">
                  <a href="#form-bao-gia" class="bg-accent hover:bg-red-700 text-white font-bold text-xs sm:text-sm px-4 py-2 rounded transition">
                    NHẬN BÁO GIÁ NGAY
                  </a>
                  <a href="#du-an-thuc-te" class="bg-white/15 hover:bg-white/25 text-white font-bold text-xs sm:text-sm px-4 py-2 rounded border border-white/30 transition">
                    XEM CÔNG TRÌNH THỰC TẾ
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- SLIDE 2 -->
        <div class="banner-slide">
          <div class="relative w-full aspect-[16/8] sm:aspect-[21/8] max-h-[460px] min-h-[220px]">
            <img
              src="https://lh3.googleusercontent.com/d/1H0Gh7sJbSuLnCQqUMuy_hYqh9knwWzTg=w1600"
              onerror="retryDriveImage(this, '1H0Gh7sJbSuLnCQqUMuy_hYqh9knwWzTg')"
              alt="Banner 2 - Xưởng Gia Công Chữ Nổi CNC Laser In Ấn Tân Đại Việt"
              class="w-full h-full object-cover"
            >
            <div class="absolute inset-0 bg-gradient-to-r from-primaryDark/90 via-primary/65 to-transparent flex items-center">
              <div class="px-5 sm:px-10 md:px-14 max-w-2xl text-white space-y-2 sm:space-y-3">
                <p class="text-yellow-300 font-bold text-xs sm:text-sm uppercase tracking-wider">
                  XƯỞNG SẢN XUẤT TRỰC TIẾP - KHÔNG QUA TRUNG GIAN
                </p>
                <h2 class="text-base sm:text-2xl md:text-4xl font-black leading-tight uppercase">
                  GIA CÔNG CHỮ NỔI INOX - CẮT CNC LASER - IN PHUN KHỔ LỚN
                </h2>
                <p class="text-xs sm:text-sm text-gray-100 line-clamp-2">
                  Văn phòng: 149 Hoàng Diệu, Đà Nẵng | Xưởng SX: K88/9B Lê Đình Lý, Đà Nẵng | Hotline: 0987.919.069 – 0369.561.458
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-2">
                  <a href="tel:0987919069" class="bg-yellow-400 hover:bg-yellow-300 text-slate-900 font-bold text-xs sm:text-sm px-4 py-2 rounded transition">
                    HOTLINE: 0987.919.069
                  </a>
                  <a href="#danh-muc-trang-chu" class="bg-white/15 hover:bg-white/25 text-white font-bold text-xs sm:text-sm px-4 py-2 rounded border border-white/30 transition">
                    KHÁM PHÁ DỊCH VỤ
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Nút điều hướng Trái / Phải -->
        <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-3 top-1/2 -translate-y-1/2 z-20 w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-sm"></i>
        </button>
        <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-3 top-1/2 -translate-y-1/2 z-20 w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-sm"></i>
        </button>

        <!-- Chấm tròn chỉ báo -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button onclick="goToSlide(0)" class="banner-dot w-6 h-2 rounded-full bg-yellow-400 transition-all"></button>
          <button onclick="goToSlide(1)" class="banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       4. DANH MỤC SẢN PHẨM TRANG CHỦ
       ===================================================================== -->
  <section id="danh-muc-trang-chu" class="py-2">
    <div class="fs-container">
      <div class="fs-section-title">
        <h2 class="fs-section-title-main">
          <i class="fa-solid fa-layer-group"></i>
          <span>DANH MỤC SẢN PHẨM & DỊCH VỤ</span>
        </h2>
        <span class="hidden sm:inline-block text-xs text-gray-500 font-medium">
          Thiết kế & Thi công trọn gói tại Đà Nẵng
        </span>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
        <a href="#cat-thi-cong-quang-cao" class="group bg-white rounded-lg border border-gray-200 p-2.5 hover:border-primary hover:shadow-md transition flex flex-col items-center text-center">
          <div class="w-full aspect-[4/3] rounded overflow-hidden bg-gray-100 mb-2">
            <img src="https://lh3.googleusercontent.com/d/1t6KlZoRaR5zdwSYOmhY9kzrsZkfBUNuR=w600" onerror="retryDriveImage(this, '1t6KlZoRaR5zdwSYOmhY9kzrsZkfBUNuR')" alt="Thi Công Quảng Cáo" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="font-bold text-xs text-gray-800 group-hover:text-primary uppercase leading-snug">Thi Công Quảng Cáo</h3>
        </a>

        <a href="#cat-chu-noi" class="group bg-white rounded-lg border border-gray-200 p-2.5 hover:border-primary hover:shadow-md transition flex flex-col items-center text-center">
          <div class="w-full aspect-[4/3] rounded overflow-hidden bg-gray-100 mb-2">
            <img src="https://lh3.googleusercontent.com/d/1SNhvg8Cp9Nb8TFPxnw-M7aoPdr97qOgb=w600" onerror="retryDriveImage(this, '1SNhvg8Cp9Nb8TFPxnw-M7aoPdr97qOgb')" alt="Chữ Nổi Quảng Cáo" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="font-bold text-xs text-gray-800 group-hover:text-primary uppercase leading-snug">Chữ Nổi Quảng Cáo</h3>
        </a>

        <a href="#cat-cnc-laser" class="group bg-white rounded-lg border border-gray-200 p-2.5 hover:border-primary hover:shadow-md transition flex flex-col items-center text-center">
          <div class="w-full aspect-[4/3] rounded overflow-hidden bg-gray-100 mb-2">
            <img src="https://lh3.googleusercontent.com/d/1Byk40D7yDREmk-7ggDNrVWrLIP7O_ckm=w600" onerror="retryDriveImage(this, '1Byk40D7yDREmk-7ggDNrVWrLIP7O_ckm')" alt="CNC - Laser" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="font-bold text-xs text-gray-800 group-hover:text-primary uppercase leading-snug">CNC – Laser – Uốn Inox</h3>
        </a>

        <a href="#cat-in-phun" class="group bg-white rounded-lg border border-gray-200 p-2.5 hover:border-primary hover:shadow-md transition flex flex-col items-center text-center">
          <div class="w-full aspect-[4/3] rounded overflow-hidden bg-gray-100 mb-2">
            <img src="https://lh3.googleusercontent.com/d/1OO7tZftFrzm1yhRZq96muys0p4o-Rt4R=w600" onerror="retryDriveImage(this, '1OO7tZftFrzm1yhRZq96muys0p4o-Rt4R')" alt="In Phun Khổ Lớn" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="font-bold text-xs text-gray-800 group-hover:text-primary uppercase leading-snug">In Phun Khổ Lớn</h3>
        </a>

        <a href="#cat-showroom" class="group bg-white rounded-lg border border-gray-200 p-2.5 hover:border-primary hover:shadow-md transition flex flex-col items-center text-center">
          <div class="w-full aspect-[4/3] rounded overflow-hidden bg-gray-100 mb-2">
            <img src="https://lh3.googleusercontent.com/d/1uO1DEDXrYbxR8pvav1t58WYrcn-NAR-_=w600" onerror="retryDriveImage(this, '1uO1DEDXrYbxR8pvav1t58WYrcn-NAR-_')" alt="Showroom Nội Thất" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="font-bold text-xs text-gray-800 group-hover:text-primary uppercase leading-snug">Showroom Nội Thất</h3>
        </a>

        <a href="#cat-cnc-go" class="group bg-white rounded-lg border border-gray-200 p-2.5 hover:border-primary hover:shadow-md transition flex flex-col items-center text-center">
          <div class="w-full aspect-[4/3] rounded overflow-hidden bg-gray-100 mb-2">
            <img src="https://lh3.googleusercontent.com/d/1X_eKfMy8doHLLFJGf2lwDj1h2e5DdVbh=w600" onerror="retryDriveImage(this, '1X_eKfMy8doHLLFJGf2lwDj1h2e5DdVbh')" alt="Cắt CNC Gỗ" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="font-bold text-xs text-gray-800 group-hover:text-primary uppercase leading-snug">Cắt CNC Gỗ Công Nghiệp</h3>
        </a>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       5. DANH MỤC 1: THI CÔNG QUẢNG CÁO (2 CỘT MOBILE, 4 CỘT PC, CÓ % GIẢM GIÁ)
       ===================================================================== -->
  <section id="cat-thi-cong-quang-cao" class="py-2">
    <div class="fs-container">
      <div class="fs-section-title">
        <h2 class="fs-section-title-main">
          <i class="fa-solid fa-sign-hanging"></i>
          <span>THI CÔNG QUẢNG CÁO</span>
        </h2>
        <a href="#form-bao-gia" class="text-xs sm:text-sm font-bold text-primary hover:text-accent">
          Nhận báo giá <i class="fa-solid fa-angle-right ml-1"></i>
        </a>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-18%</span>
            <img src="https://lh3.googleusercontent.com/d/1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY=w700" onerror="retryDriveImage(this, '1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY')" alt="Thi công bảng hiệu mặt dựng Alu chữ nổi">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">Thi công quảng cáo</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">Thi Công Bảng Hiệu Mặt Dựng Alu Chữ Nổi Trọn Gói</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">720.000đ/m²</span>
                <span class="text-xs sm:text-sm font-black text-accent">590.000đ/m²</span>
              </div>
              <button onclick="selectServiceForQuote('Thi Công Bảng Hiệu Mặt Dựng Alu Chữ Nổi')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>

        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-20%</span>
            <img src="https://lh3.googleusercontent.com/d/1H0Gh7sJbSuLnCQqUMuy_hYqh9knwWzTg=w700" onerror="retryDriveImage(this, '1H0Gh7sJbSuLnCQqUMuy_hYqh9knwWzTg')" alt="Thi công biển quảng cáo hộp đèn LED">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">Thi công quảng cáo</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">Thi Công Biển Quảng Cáo Hộp Đèn LED Siêu Sáng Đà Nẵng</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">1.200.000đ</span>
                <span class="text-xs sm:text-sm font-black text-accent">960.000đ</span>
              </div>
              <button onclick="selectServiceForQuote('Thi Công Biển Quảng Cáo Hộp Đèn LED')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>

        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-15%</span>
            <img src="https://lh3.googleusercontent.com/d/1t6KlZoRaR5zdwSYOmhY9kzrsZkfBUNuR=w700" onerror="retryDriveImage(this, '1t6KlZoRaR5zdwSYOmhY9kzrsZkfBUNuR')" alt="Thiết kế thi công Pano biển tấm lớn">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">Thi công quảng cáo</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">Thi Công Biển Pano Quảng Cáo Khung Sắt Bạt Hiflex Dày</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">450.000đ/m²</span>
                <span class="text-xs sm:text-sm font-black text-accent">380.000đ/m²</span>
              </div>
              <button onclick="selectServiceForQuote('Thi Công Biển Pano Quảng Cáo Khung Sắt')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>

        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-22%</span>
            <img src="https://lh3.googleusercontent.com/d/1SNhvg8Cp9Nb8TFPxnw-M7aoPdr97qOgb=w700" onerror="retryDriveImage(this, '1SNhvg8Cp9Nb8TFPxnw-M7aoPdr97qOgb')" alt="Làm bảng tên công ty Inox ăn mòn">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">Thi công quảng cáo</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">Làm Bảng Tên Công Ty Inox Ăn Mòn – Bảng Phòng Ban Mica</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">450.000đ</span>
                <span class="text-xs sm:text-sm font-black text-accent">350.000đ</span>
              </div>
              <button onclick="selectServiceForQuote('Làm Bảng Tên Công Ty Inox / Mica')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       6. DANH MỤC 2: CHỮ NỔI QUẢNG CÁO & CNC - LASER
       ===================================================================== -->
  <section id="cat-chu-noi" class="py-2">
    <div class="fs-container">
      <div id="cat-cnc-laser" class="fs-section-title">
        <h2 class="fs-section-title-main">
          <i class="fa-solid fa-font"></i>
          <span>CHỮ NỔI QUẢNG CÁO & GIA CÔNG CNC – LASER</span>
        </h2>
        <a href="#form-bao-gia" class="text-xs sm:text-sm font-bold text-primary hover:text-accent">
          Xưởng gia công giá gốc <i class="fa-solid fa-angle-right ml-1"></i>
        </a>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-19%</span>
            <img src="https://lh3.googleusercontent.com/d/1Byk40D7yDREmk-7ggDNrVWrLIP7O_ckm=w700" onerror="retryDriveImage(this, '1Byk40D7yDREmk-7ggDNrVWrLIP7O_ckm')" alt="Gia công chữ nổi Inox vàng gương">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">Chữ nổi quảng cáo</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">Gia Công Bộ Chữ Nổi Inox Vàng Gương / Xước Hắt Sáng Chân LED</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">1.350.000đ</span>
                <span class="text-xs sm:text-sm font-black text-accent">1.090.000đ</span>
              </div>
              <button onclick="selectServiceForQuote('Gia Công Chữ Nổi Inox Vàng Gương Đèn LED')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>

        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-17%</span>
            <img src="https://lh3.googleusercontent.com/d/1OO7tZftFrzm1yhRZq96muys0p4o-Rt4R=w700" onerror="retryDriveImage(this, '1OO7tZftFrzm1yhRZq96muys0p4o-Rt4R')" alt="Chữ nổi Mica viền Inox">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">Chữ nổi quảng cáo</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">Thi Công Chữ Nổi Mica Đài Loan Gắn Đèn LED Âm Bản Siêu Bền</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">1.150.000đ</span>
                <span class="text-xs sm:text-sm font-black text-accent">950.000đ</span>
              </div>
              <button onclick="selectServiceForQuote('Thi Công Chữ Nổi Mica Đèn LED')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>

        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-25%</span>
            <img src="https://lh3.googleusercontent.com/d/1uO1DEDXrYbxR8pvav1t58WYrcn-NAR-_=w700" onerror="retryDriveImage(this, '1uO1DEDXrYbxR8pvav1t58WYrcn-NAR-_')" alt="Cắt khắc CNC Laser Alu Mica">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">CNC – Cắt Laser</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">Cắt Khắc CNC – Laser Trên Mica, Alu, Inox Lấy Nhanh Tại Xưởng</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">200.000đ</span>
                <span class="text-xs sm:text-sm font-black text-accent">150.000đ</span>
              </div>
              <button onclick="selectServiceForQuote('Cắt Khắc CNC - Laser Mica, Alu, Inox')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>

        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-16%</span>
            <img src="https://lh3.googleusercontent.com/d/1X_eKfMy8doHLLFJGf2lwDj1h2e5DdVbh=w700" onerror="retryDriveImage(this, '1X_eKfMy8doHLLFJGf2lwDj1h2e5DdVbh')" alt="Logo Backdrop Quầy lễ tân">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">Chữ nổi & Logo</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">Thi Công Bộ Logo & Chữ Nổi Backdrop Sảnh Lễ Tân Công Ty</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">2.500.000đ</span>
                <span class="text-xs sm:text-sm font-black text-accent">2.100.000đ</span>
              </div>
              <button onclick="selectServiceForQuote('Thi Công Logo & Chữ Nổi Backdrop Lễ Tân')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       7. DANH MỤC 3: IN PHUN KHỔ LỚN - SHOWROOM NỘI THẤT - CNC GỖ
       ===================================================================== -->
  <section id="cat-in-phun" class="py-2">
    <div class="fs-container">
      <div id="cat-showroom" class="fs-section-title">
        <h2 id="cat-cnc-go" class="fs-section-title-main">
          <i class="fa-solid fa-store"></i>
          <span>IN PHUN KHỔ LỚN – SHOWROOM NỘI THẤT – CNC GỖ</span>
        </h2>
        <a href="#form-bao-gia" class="text-xs sm:text-sm font-bold text-primary hover:text-accent">
          Xem bảng giá ưu đãi <i class="fa-solid fa-angle-right ml-1"></i>
        </a>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-23%</span>
            <img src="https://lh3.googleusercontent.com/d/1hs87c-CqhaG6s3C936HzlbvCygPwi4Yq=w700" onerror="retryDriveImage(this, '1hs87c-CqhaG6s3C936HzlbvCygPwi4Yq')" alt="In bạt Hiflex khổ lớn">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">In phun khổ lớn</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">In Phun Bạt Hiflex Khổ Lớn, In Decal, PP, Băng Rôn Sự Kiện</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">65.000đ/m²</span>
                <span class="text-xs sm:text-sm font-black text-accent">50.000đ/m²</span>
              </div>
              <button onclick="selectServiceForQuote('In Phun Bạt Hiflex Khổ Lớn, Decal, PP')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>

        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-15%</span>
            <img src="https://lh3.googleusercontent.com/d/1dQeOMFFjRMYAiM7G7bMPZE2ONo2Gxxis=w700" onerror="retryDriveImage(this, '1dQeOMFFjRMYAiM7G7bMPZE2ONo2Gxxis')" alt="Thi công nội thất Showroom">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">Showroom Nội Ngoại Thất</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">Thiết Kế & Thi Công Trọn Gói Nội Ngoại Thất Showroom, Shop</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">3.800.000đ</span>
                <span class="text-xs sm:text-sm font-black text-accent">3.200.000đ</span>
              </div>
              <button onclick="selectServiceForQuote('Thiết Kế Thi Công Nội Ngoại Thất Showroom')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>

        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-20%</span>
            <img src="https://lh3.googleusercontent.com/d/1gwiOSNl-R5xZW5gSBsXnYdR4Su-4FI9c=w700" onerror="retryDriveImage(this, '1gwiOSNl-R5xZW5gSBsXnYdR4Su-4FI9c')" alt="Quầy kệ trưng bày sản phẩm">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">Showroom Nội Ngoại Thất</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">Gia Công Quầy Thu Ngân, Tủ Kệ Trưng Bày Mỹ Phẩm – Điện Thoại</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">2.400.000đ</span>
                <span class="text-xs sm:text-sm font-black text-accent">1.920.000đ</span>
              </div>
              <button onclick="selectServiceForQuote('Gia Công Quầy Thu Ngân & Tủ Kệ Trưng Bày')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>

        <div class="fs-product-box product-card">
          <div class="fs-aspect-product">
            <span class="fs-badge-sale">-18%</span>
            <img src="https://lh3.googleusercontent.com/d/1-zGZltnPKZavW1-8jScASbS82-teBSnw=w700" onerror="retryDriveImage(this, '1-zGZltnPKZavW1-8jScASbS82-teBSnw')" alt="Cắt CNC gỗ công nghiệp">
          </div>
          <div class="p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between">
            <div>
              <div class="text-[11px] text-gray-400 uppercase">Cắt CNC Gỗ Công Nghiệp</div>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-0.5 hover:text-primary">Cắt CNC Gỗ Công Nghiệp MDF, Vách Ngăn Hoa Văn Trang Trí Đà Nẵng</h3>
            </div>
            <div class="mt-2 pt-2 border-t border-gray-100">
              <div class="flex flex-wrap items-baseline gap-1.5">
                <span class="text-xs text-gray-400 line-through">850.000đ/m²</span>
                <span class="text-xs sm:text-sm font-black text-accent">690.000đ/m²</span>
              </div>
              <button onclick="selectServiceForQuote('Cắt CNC Gỗ Công Nghiệp MDF Vách Ngăn')" class="mt-2 w-full bg-primary hover:bg-primaryDark text-white text-xs font-bold py-2 rounded transition">
                Đặt Tư Vấn & Báo Giá
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       8. 15 HÌNH ẢNH THI CÔNG THỰC TẾ (GOOGLE DRIVE)
       ===================================================================== -->
  <section id="du-an-thuc-te" class="py-4 bg-white border-y border-gray-200">
    <div class="fs-container">
      <div class="fs-section-title">
        <h2 class="fs-section-title-main">
          <i class="fa-solid fa-camera-retro"></i>
          <span>DỰ ÁN & HÌNH ẢNH THI CÔNG THỰC TẾ TÂN ĐẠI VIỆT</span>
        </h2>
        <span class="hidden md:inline-block text-xs text-gray-500">100% Ảnh công trình thực tế của Tân Đại Việt</span>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3">
        <div onclick="openLightbox('1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY', 'Công trình #01')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY=w600" onerror="retryDriveImage(this, '1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY')" alt="Công trình 1" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Thi công bảng hiệu #01</div>
        </div>
        <div onclick="openLightbox('1H0Gh7sJbSuLnCQqUMuy_hYqh9knwWzTg', 'Công trình #02')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1H0Gh7sJbSuLnCQqUMuy_hYqh9knwWzTg=w600" onerror="retryDriveImage(this, '1H0Gh7sJbSuLnCQqUMuy_hYqh9knwWzTg')" alt="Công trình 2" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Thi công mặt dựng Alu #02</div>
        </div>
        <div onclick="openLightbox('1t6KlZoRaR5zdwSYOmhY9kzrsZkfBUNuR', 'Công trình #03')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1t6KlZoRaR5zdwSYOmhY9kzrsZkfBUNuR=w600" onerror="retryDriveImage(this, '1t6KlZoRaR5zdwSYOmhY9kzrsZkfBUNuR')" alt="Công trình 3" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Biển quảng cáo cửa hàng #03</div>
        </div>
        <div onclick="openLightbox('1SNhvg8Cp9Nb8TFPxnw-M7aoPdr97qOgb', 'Công trình #04')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1SNhvg8Cp9Nb8TFPxnw-M7aoPdr97qOgb=w600" onerror="retryDriveImage(this, '1SNhvg8Cp9Nb8TFPxnw-M7aoPdr97qOgb')" alt="Công trình 4" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Chữ nổi Mica LED #04</div>
        </div>
        <div onclick="openLightbox('1Byk40D7yDREmk-7ggDNrVWrLIP7O_ckm', 'Công trình #05')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1Byk40D7yDREmk-7ggDNrVWrLIP7O_ckm=w600" onerror="retryDriveImage(this, '1Byk40D7yDREmk-7ggDNrVWrLIP7O_ckm')" alt="Công trình 5" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Gia công chữ Inox #05</div>
        </div>
        <div onclick="openLightbox('1OO7tZftFrzm1yhRZq96muys0p4o-Rt4R', 'Công trình #06')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1OO7tZftFrzm1yhRZq96muys0p4o-Rt4R=w600" onerror="retryDriveImage(this, '1OO7tZftFrzm1yhRZq96muys0p4o-Rt4R')" alt="Công trình 6" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Bảng hiệu hộp đèn #06</div>
        </div>
        <div onclick="openLightbox('1uO1DEDXrYbxR8pvav1t58WYrcn-NAR-_', 'Công trình #07')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1uO1DEDXrYbxR8pvav1t58WYrcn-NAR-_=w600" onerror="retryDriveImage(this, '1uO1DEDXrYbxR8pvav1t58WYrcn-NAR-_')" alt="Công trình 7" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Nội thất Showroom #07</div>
        </div>
        <div onclick="openLightbox('1X_eKfMy8doHLLFJGf2lwDj1h2e5DdVbh', 'Công trình #08')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1X_eKfMy8doHLLFJGf2lwDj1h2e5DdVbh=w600" onerror="retryDriveImage(this, '1X_eKfMy8doHLLFJGf2lwDj1h2e5DdVbh')" alt="Công trình 8" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Lắp đặt chữ nổi #08</div>
        </div>
        <div onclick="openLightbox('1hs87c-CqhaG6s3C936HzlbvCygPwi4Yq', 'Công trình #09')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1hs87c-CqhaG6s3C936HzlbvCygPwi4Yq=w600" onerror="retryDriveImage(this, '1hs87c-CqhaG6s3C936HzlbvCygPwi4Yq')" alt="Công trình 9" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Thi công Pano bạt #09</div>
        </div>
        <div onclick="openLightbox('1dQeOMFFjRMYAiM7G7bMPZE2ONo2Gxxis', 'Công trình #10')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1dQeOMFFjRMYAiM7G7bMPZE2ONo2Gxxis=w600" onerror="retryDriveImage(this, '1dQeOMFFjRMYAiM7G7bMPZE2ONo2Gxxis')" alt="Công trình 10" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Bảng hiệu trọn gói #10</div>
        </div>
        <div onclick="openLightbox('1gwiOSNl-R5xZW5gSBsXnYdR4Su-4FI9c', 'Công trình #11')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1gwiOSNl-R5xZW5gSBsXnYdR4Su-4FI9c=w600" onerror="retryDriveImage(this, '1gwiOSNl-R5xZW5gSBsXnYdR4Su-4FI9c')" alt="Công trình 11" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Bảng hiệu thương hiệu #11</div>
        </div>
        <div onclick="openLightbox('1-zGZltnPKZavW1-8jScASbS82-teBSnw', 'Công trình #12')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1-zGZltnPKZavW1-8jScASbS82-teBSnw=w600" onerror="retryDriveImage(this, '1-zGZltnPKZavW1-8jScASbS82-teBSnw')" alt="Công trình 12" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Xưởng gia công CNC #12</div>
        </div>
        <div onclick="openLightbox('1YyvHYHvPJCcfvYQ7V1jdg3naCC9a4K20', 'Công trình #13')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1YyvHYHvPJCcfvYQ7V1jdg3naCC9a4K20=w600" onerror="retryDriveImage(this, '1YyvHYHvPJCcfvYQ7V1jdg3naCC9a4K20')" alt="Công trình 13" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Bảng hiệu LED nổi bật #13</div>
        </div>
        <div onclick="openLightbox('15inPwv3lEvSa35WuD9nOm8iRjz_2qvbG', 'Công trình #14')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/15inPwv3lEvSa35WuD9nOm8iRjz_2qvbG=w600" onerror="retryDriveImage(this, '15inPwv3lEvSa35WuD9nOm8iRjz_2qvbG')" alt="Công trình 14" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Lắp đặt hoàn thiện #14</div>
        </div>
        <div onclick="openLightbox('1Dbaf0XDGWpAbOwaLQlf63aqJH-4iaT6K', 'Công trình #15')" class="group cursor-pointer rounded-lg overflow-hidden border border-gray-200 bg-gray-50">
          <div class="aspect-[4/3] overflow-hidden"><img src="https://lh3.googleusercontent.com/d/1Dbaf0XDGWpAbOwaLQlf63aqJH-4iaT6K=w600" onerror="retryDriveImage(this, '1Dbaf0XDGWpAbOwaLQlf63aqJH-4iaT6K')" alt="Công trình 15" class="w-full h-full object-cover group-hover:scale-105 transition duration-300"></div>
          <div class="p-2 text-center text-xs font-medium text-gray-700 truncate">Công trình tiêu biểu #15</div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       9. FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ
       ===================================================================== -->
  <section id="form-bao-gia" class="py-5">
    <div class="fs-container">
      <div class="bg-primary rounded-xl shadow-lg overflow-hidden border border-blue-800">
        <div class="grid grid-cols-1 lg:grid-cols-12">
          <div class="lg:col-span-5 p-5 sm:p-7 text-white flex flex-col justify-between bg-primaryDark/60">
            <div class="space-y-3">
              <div class="inline-block bg-yellow-400 text-slate-900 font-bold text-xs px-3 py-1 rounded uppercase">
                Báo giá nhanh trong 5 phút
              </div>
              <h2 class="text-xl sm:text-2xl font-black uppercase leading-snug">
                ĐĂNG KÝ YÊU CẦU TƯ VẤN & BÁO GIÁ THI CÔNG
              </h2>
              <p class="text-xs sm:text-sm text-blue-100 leading-relaxed">
                Quý khách để lại thông tin hạng mục cần làm bảng hiệu, chữ nổi, cắt CNC hoặc nội thất. Kỹ thuật viên của <strong>Tân Đại Việt</strong> sẽ khảo sát đo đạc tận nơi và lên thiết kế 2D/3D miễn phí.
              </p>
              <ul class="space-y-2 text-xs sm:text-sm pt-2">
                <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-yellow-400"></i>Miễn phí 100% chi phí khảo sát & thiết kế khi thi công</li>
                <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-yellow-400"></i>Sản xuất trực tiếp tại xưởng K88/9B Lê Đình Lý</li>
                <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-yellow-400"></i>Bảo hành dài hạn từ 12 – 24 tháng tại Đà Nẵng</li>
              </ul>
            </div>

            <div class="mt-6 pt-4 border-t border-white/15 text-xs sm:text-sm space-y-1">
              <div><i class="fa-solid fa-phone-volume text-yellow-400 mr-2"></i>Hotline: <strong>0987.919.069 – 0369.561.458</strong></div>
              <div><i class="fa-solid fa-location-dot text-yellow-400 mr-2"></i>Văn phòng: 149 Hoàng Diệu, Đà Nẵng</div>
            </div>
          </div>

          <div class="lg:col-span-7 p-5 sm:p-7 bg-white">
            <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                <div>
                  <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Họ và tên quý khách *</label>
                  <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-primary">
                </div>
                <div>
                  <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Số điện thoại / Zalo *</label>
                  <input id="qPhone" type="tel" required placeholder="Nhập SĐT..." class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-primary">
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                <div>
                  <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Danh mục cần báo giá *</label>
                  <select id="qCategory" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-primary bg-white">
                    <option value="Thi Công Quảng Cáo (Alu, Bảng Hiệu, Hộp Đèn)">Thi Công Quảng Cáo (Alu, Bảng Hiệu, Hộp Đèn)</option>
                    <option value="Chữ Nổi Quảng Cáo (Inox, Mica, Đèn LED)">Chữ Nổi Quảng Cáo (Inox, Mica, Đèn LED)</option>
                    <option value="CNC – Cắt Laser – Hàn & Uốn Inox">CNC – Cắt Laser – Hàn & Uốn Inox</option>
                    <option value="In Phun Khổ Lớn (Bạt Hiflex, Decal, PP)">In Phun Khổ Lớn (Bạt Hiflex, Decal, PP)</option>
                    <option value="Showroom Nội Ngoại Thất">Showroom Nội Ngoại Thất</option>
                    <option value="Cắt CNC Gỗ Công Nghiệp Đà Nẵng">Cắt CNC Gỗ Công Nghiệp Đà Nẵng</option>
                  </select>
                </div>
                <div>
                  <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Địa chỉ khảo sát công trình</label>
                  <input id="qAddress" type="text" placeholder="Số nhà, tên đường, quận tại Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-primary">
                </div>
              </div>

              <div>
                <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Yêu cầu chi tiết</label>
                <textarea id="qNote" rows="3" placeholder="Ví dụ: Làm bảng hiệu ngang 4m cao 1.5m nền Alu..." class="w-full px-3.5 py-2 text-sm border border-gray-300 rounded-md focus:outline-none focus:border-primary"></textarea>
              </div>

              <div class="flex flex-wrap items-center gap-3 pt-1">
                <button type="submit" class="bg-accent hover:bg-red-700 text-white font-bold text-sm px-6 py-3 rounded-md transition flex items-center gap-2">
                  <i class="fa-solid fa-paper-plane"></i>
                  <span>GỬI YÊU CẦU BÁO GIÁ</span>
                </button>
                <a href="https://zalo.me/0987919069" target="_blank" rel="noopener" class="bg-blue-600 hover:bg-blue-700 text-white font-bold text-sm px-5 py-3 rounded-md transition flex items-center gap-2">
                  <i class="fa-solid fa-comment-dots"></i>
                  <span>NHẮN ZALO: 0987.919.069</span>
                </a>
              </div>

              <div id="quoteSuccessMsg" class="hidden p-3.5 rounded-md bg-green-50 border border-green-300 text-green-800 text-xs sm:text-sm font-medium"></div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       10. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ
       ===================================================================== -->
  <section id="tin-tuc" class="py-2">
    <div class="fs-container">
      <div class="fs-section-title">
        <h2 class="fs-section-title-main">
          <i class="fa-solid fa-newspaper"></i>
          <span>DANH MỤC BÀI VIẾT & TƯ VẤN QUẢNG CÁO</span>
        </h2>
        <span class="hidden sm:inline-block text-xs text-gray-500">Cập nhật báo giá & mẫu bảng hiệu đẹp</span>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
        <article class="bg-white rounded-lg border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-gray-100">
            <img src="https://lh3.googleusercontent.com/d/1YyvHYHvPJCcfvYQ7V1jdg3naCC9a4K20=w600" onerror="retryDriveImage(this, '1YyvHYHvPJCcfvYQ7V1jdg3naCC9a4K20')" alt="Bài viết 1" class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex flex-col flex-1 justify-between">
            <div>
              <span class="text-[11px] font-bold text-primary uppercase">Báo giá thi công</span>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-1 hover:text-primary">Bảng Báo Giá Làm Bảng Hiệu Quảng Cáo Tại Đà Nẵng Mới Nhất</h3>
              <p class="text-xs text-gray-500 line-clamp-2 mt-1.5">Tổng hợp chi tiết đơn giá thi công mặt dựng Alu, chữ nổi Mica, Inox tại xưởng Tân Đại Việt.</p>
            </div>
            <a href="#form-bao-gia" class="text-xs font-bold text-accent mt-2.5 inline-flex items-center gap-1">Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i></a>
          </div>
        </article>

        <article class="bg-white rounded-lg border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-gray-100">
            <img src="https://lh3.googleusercontent.com/d/15inPwv3lEvSa35WuD9nOm8iRjz_2qvbG=w600" onerror="retryDriveImage(this, '15inPwv3lEvSa35WuD9nOm8iRjz_2qvbG')" alt="Bài viết 2" class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex flex-col flex-1 justify-between">
            <div>
              <span class="text-[11px] font-bold text-primary uppercase">Tư vấn chất liệu</span>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-1 hover:text-primary">Kinh Nghiệm Chọn Chữ Nổi Inox Hay Chữ Nổi Mica Cho Mặt Tiền Shop</h3>
              <p class="text-xs text-gray-500 line-clamp-2 mt-1.5">So sánh độ bền và tính thẩm mỹ giữa chữ nổi Inox 304 và chữ nổi Mica đèn LED.</p>
            </div>
            <a href="#form-bao-gia" class="text-xs font-bold text-accent mt-2.5 inline-flex items-center gap-1">Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i></a>
          </div>
        </article>

        <article class="bg-white rounded-lg border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-gray-100">
            <img src="https://lh3.googleusercontent.com/d/1Dbaf0XDGWpAbOwaLQlf63aqJH-4iaT6K=w600" onerror="retryDriveImage(this, '1Dbaf0XDGWpAbOwaLQlf63aqJH-4iaT6K')" alt="Bài viết 3" class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex flex-col flex-1 justify-between">
            <div>
              <span class="text-[11px] font-bold text-primary uppercase">CNC - Laser</span>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-1 hover:text-primary">Xưởng Cắt Khắc CNC – Laser Trên Gỗ, Mica, Alu Chính Xác Tại Đà Nẵng</h3>
              <p class="text-xs text-gray-500 line-clamp-2 mt-1.5">Hệ thống máy cắt CNC và Laser hiện đại tại K88/9B Lê Đình Lý.</p>
            </div>
            <a href="#form-bao-gia" class="text-xs font-bold text-accent mt-2.5 inline-flex items-center gap-1">Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i></a>
          </div>
        </article>

        <article class="bg-white rounded-lg border border-gray-200 overflow-hidden hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-gray-100">
            <img src="https://lh3.googleusercontent.com/d/1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY=w600" onerror="retryDriveImage(this, '1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY')" alt="Bài viết 4" class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex flex-col flex-1 justify-between">
            <div>
              <span class="text-[11px] font-bold text-primary uppercase">Quy trình làm việc</span>
              <h3 class="font-bold text-xs sm:text-sm text-gray-800 line-clamp-2 mt-1 hover:text-primary">Quy Trình 4 Bước Khảo Sát, Thiết Kế Và Thi Công Quảng Cáo Tân Đại Việt</h3>
              <p class="text-xs text-gray-500 line-clamp-2 mt-1.5">Từ khâu tiếp nhận yêu cầu, dựng phối cảnh 3D đến gia công và nghiệm thu bảo hành.</p>
            </div>
            <a href="#form-bao-gia" class="text-xs font-bold text-accent mt-2.5 inline-flex items-center gap-1">Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i></a>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       11. BẢN ĐỒ GOOGLE MAPS & FANPAGE FACEBOOK TRANG CHỦ
       ===================================================================== -->
  <section id="lien-he-map" class="py-4">
    <div class="fs-container">
      <div class="fs-section-title">
        <h2 class="fs-section-title-main">
          <i class="fa-solid fa-map-location-dot"></i>
          <span>BẢN ĐỒ ĐƯỜNG ĐI & FANPAGE FACEBOOK TÂN ĐẠI VIỆT</span>
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
        <div class="lg:col-span-7 bg-white rounded-lg border border-gray-200 p-3 sm:p-4 shadow-sm flex flex-col justify-between">
          <div>
            <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
              <div>
                <h3 class="font-bold text-sm sm:text-base text-primary uppercase">
                  <i class="fa-solid fa-location-dot text-accent mr-1.5"></i>Vị Trí Google Maps Tân Đại Việt
                </h3>
                <p class="text-xs text-gray-600 mt-0.5">VP: 149 Hoàng Diệu, Đà Nẵng | Xưởng: K88/9B Lê Đình Lý, Đà Nẵng</p>
              </div>
              <a href="https://maps.app.goo.gl/2HGiecoLaT5Zsfk76" target="_blank" rel="noopener" class="bg-primary hover:bg-primaryDark text-white text-xs font-bold px-3.5 py-2 rounded inline-flex items-center gap-1.5 transition">
                <i class="fa-solid fa-diamond-turn-right"></i>
                <span>Mở Google Maps</span>
              </a>
            </div>
            <div class="w-full h-72 sm:h-80 rounded-lg overflow-hidden border border-gray-200 bg-gray-100">
              <iframe
                title="Bản đồ Tân Đại Việt"
                src="https://maps.google.com/maps?q=149%20Ho%C3%A0ng%20Di%E1%BB%87u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
              ></iframe>
            </div>
          </div>
          <div class="mt-3 pt-3 border-t border-gray-100 flex flex-wrap items-center justify-between gap-2 text-xs text-gray-600">
            <span><i class="fa-solid fa-map-pin text-accent mr-1"></i>Map: <a href="https://maps.app.goo.gl/2HGiecoLaT5Zsfk76" target="_blank" rel="noopener" class="text-primary font-bold underline">maps.app.goo.gl/2HGiecoLaT5Zsfk76</a></span>
            <span class="font-bold text-gray-800">Hotline: 0987.919.069 – 0369.561.458</span>
          </div>
        </div>

        <div class="lg:col-span-5 bg-white rounded-lg border border-gray-200 p-3 sm:p-4 shadow-sm flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between gap-2 mb-3">
              <div>
                <h3 class="font-bold text-sm sm:text-base text-[#1877F2] uppercase">
                  <i class="fa-brands fa-facebook mr-1.5"></i>Fanpage Tân Đại Việt
                </h3>
                <p class="text-xs text-gray-600 mt-0.5">facebook.com/qctandaiviet</p>
              </div>
              <a href="https://www.facebook.com/qctandaiviet/" target="_blank" rel="noopener" class="bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold px-3 py-2 rounded inline-flex items-center gap-1.5 transition">
                <i class="fa-solid fa-thumbs-up"></i>
                <span>Theo Dõi</span>
              </a>
            </div>
            <div class="rounded-lg border border-gray-200 overflow-hidden bg-gray-50">
              <div class="relative h-28 bg-primary overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY=w800" onerror="retryDriveImage(this, '1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY')" alt="Ảnh bìa" class="w-full h-full object-cover opacity-75">
                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-3">
                  <img src="https://lh3.googleusercontent.com/d/1a_drCTyMM41L7uinFZuK-itHgrr0KxD2=w200" onerror="retryDriveImage(this, '1a_drCTyMM41L7uinFZuK-itHgrr0KxD2')" alt="Logo" class="w-12 h-12 rounded-full border-2 border-white bg-white object-contain p-0.5 shrink-0">
                  <div class="text-white min-w-0">
                    <a href="https://www.facebook.com/qctandaiviet/" target="_blank" rel="noopener" class="font-bold text-sm hover:underline block truncate">Quảng Cáo Tân Đại Việt Đà Nẵng</a>
                    <span class="text-[11px] text-gray-200 block truncate">@qctandaiviet • Thi công Quảng Cáo</span>
                  </div>
                </div>
              </div>
              <div class="w-full flex justify-center bg-white py-2 overflow-hidden">
                <iframe
                  title="Fanpage Tân Đại Việt"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fqctandaiviet%2F&tabs=timeline&width=340&height=210&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                  width="340"
                  height="210"
                  style="border:none;overflow:hidden;max-width:100%;"
                  scrolling="no"
                  frameborder="0"
                  allowfullscreen="true"
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                ></iframe>
              </div>
            </div>
          </div>
          <div class="mt-3 pt-3 border-t border-gray-100 flex items-center justify-between text-xs">
            <span class="text-gray-600">Nhắn tin qua Messenger:</span>
            <a href="https://www.facebook.com/qctandaiviet/" target="_blank" rel="noopener" class="font-bold text-[#1877F2] hover:underline">Gửi tin nhắn <i class="fa-solid fa-arrow-up-right-from-square ml-1"></i></a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       12. FOOTER
       ===================================================================== -->
  <footer class="bg-slate-900 text-gray-300 pt-10 pb-20 md:pb-8 border-t-4 border-primary">
    <div class="fs-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-slate-800">
        <div class="space-y-3">
          <div class="flex items-center gap-3">
            <img src="https://lh3.googleusercontent.com/d/1a_drCTyMM41L7uinFZuK-itHgrr0KxD2=w300" onerror="retryDriveImage(this, '1a_drCTyMM41L7uinFZuK-itHgrr0KxD2')" alt="Logo" class="w-12 h-12 rounded bg-white p-1 object-contain shrink-0">
            <div>
              <div class="font-black text-white text-sm uppercase">QUẢNG CÁO TÂN ĐẠI VIỆT</div>
              <div class="text-xs text-yellow-400">Website: tandaiviet.com</div>
            </div>
          </div>
          <p class="text-xs text-gray-400 leading-relaxed">
            <strong>CÔNG TY TNHH THIẾT KẾ THI CÔNG QUẢNG CÁO TÂN ĐẠI VIỆT</strong> – Đơn vị uy tín hàng đầu tại Đà Nẵng chuyên thiết kế thi công bảng hiệu quảng cáo, chữ nổi, cắt CNC Laser và nội ngoại thất Showroom.
          </p>
        </div>

        <div class="space-y-2.5 text-xs">
          <h4 class="font-bold text-white text-sm uppercase border-b border-slate-700 pb-2">THÔNG TIN LIÊN HỆ</h4>
          <p class="flex items-start gap-2"><i class="fa-solid fa-location-dot text-yellow-400 mt-1"></i><span><strong>Văn phòng:</strong> 149 Hoàng Diệu, Hải Châu, Đà Nẵng</span></p>
          <p class="flex items-start gap-2"><i class="fa-solid fa-industry text-yellow-400 mt-1"></i><span><strong>Xưởng SX:</strong> K88/9B Lê Đình Lý, Thanh Khê, Đà Nẵng</span></p>
          <p class="flex items-center gap-2"><i class="fa-solid fa-phone-volume text-yellow-400"></i><span><strong>Hotline:</strong> <a href="tel:0987919069" class="text-white font-bold">0987.919.069</a> – <a href="tel:0369561458" class="text-white font-bold">0369.561.458</a></span></p>
          <p class="flex items-center gap-2"><i class="fa-solid fa-globe text-yellow-400"></i><span><strong>Website:</strong> tandaiviet.com</span></p>
        </div>

        <div class="space-y-2 text-xs">
          <h4 class="font-bold text-white text-sm uppercase border-b border-slate-700 pb-2">DANH MỤC SẢN PHẨM</h4>
          <ul class="space-y-2">
            <li><a href="#cat-thi-cong-quang-cao" class="hover:text-yellow-400"><i class="fa-solid fa-angle-right mr-1.5 text-primary"></i>Thi công Quảng Cáo Đà Nẵng</a></li>
            <li><a href="#cat-chu-noi" class="hover:text-yellow-400"><i class="fa-solid fa-angle-right mr-1.5 text-primary"></i>Chữ Nổi Quảng Cáo Inox - Mica</a></li>
            <li><a href="#cat-cnc-laser" class="hover:text-yellow-400"><i class="fa-solid fa-angle-right mr-1.5 text-primary"></i>CNC – Cắt Laser – Uốn Inox</a></li>
            <li><a href="#cat-in-phun" class="hover:text-yellow-400"><i class="fa-solid fa-angle-right mr-1.5 text-primary"></i>In Phun Khổ Lớn Bạt Hiflex</a></li>
            <li><a href="#cat-showroom" class="hover:text-yellow-400"><i class="fa-solid fa-angle-right mr-1.5 text-primary"></i>Showroom Nội Ngoại Thất</a></li>
            <li><a href="#cat-cnc-go" class="hover:text-yellow-400"><i class="fa-solid fa-angle-right mr-1.5 text-primary"></i>Cắt CNC Gỗ Công Nghiệp</a></li>
          </ul>
        </div>

        <div class="space-y-2 text-xs">
          <h4 class="font-bold text-white text-sm uppercase border-b border-slate-700 pb-2">CHÍNH SÁCH & ƯU ĐÃI</h4>
          <ul class="space-y-2">
            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-green-400 mt-0.5"></i>Miễn phí 100% thiết kế khi thi công trọn gói</li>
            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-green-400 mt-0.5"></i>Khảo sát & báo giá tận nơi nhanh chóng</li>
            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-green-400 mt-0.5"></i>Sản xuất trực tiếp không qua trung gian</li>
            <li class="flex items-start gap-2"><i class="fa-solid fa-check text-green-400 mt-0.5"></i>Bảo hành uy tín từ 12 – 24 tháng</li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-gray-400 text-center sm:text-left">
        <div>© Bản quyền thuộc về <strong>CÔNG TY TNHH THIẾT KẾ THI CÔNG QUẢNG CÁO TÂN ĐẠI VIỆT</strong> (tandaiviet.com)</div>
        <div>Văn phòng: 149 Hoàng Diệu – Xưởng: K88/9B Lê Đình Lý, TP. Đà Nẵng</div>
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       13. NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
       ===================================================================== -->
  <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
    <a href="https://www.facebook.com/qctandaiviet/" target="_blank" rel="noopener" aria-label="Facebook" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-4 sm:py-2.5 shadow-lg transition">
      <i class="fa-brands fa-facebook-f text-base sm:text-lg w-5 text-center"></i>
      <span class="hidden sm:inline text-xs font-bold">Fanpage Facebook</span>
    </a>
    <a href="https://zalo.me/0987919069" target="_blank" rel="noopener" aria-label="Zalo" class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white rounded-full p-2.5 sm:px-4 sm:py-2.5 shadow-lg transition">
      <span class="font-black text-xs bg-white text-[#0068ff] rounded-full w-5 h-5 flex items-center justify-center">Z</span>
      <span class="hidden sm:inline text-xs font-bold">Zalo: 0987.919.069</span>
    </a>
    <a href="tel:0369561458" aria-label="Hotline 2" class="flex items-center gap-2 bg-emerald-600 hover:bg-emerald-700 text-white rounded-full p-2.5 sm:px-4 sm:py-2.5 shadow-lg transition">
      <i class="fa-solid fa-phone text-sm sm:text-base w-5 text-center"></i>
      <span class="hidden sm:inline text-xs font-bold">0369.561.458</span>
    </a>
    <a href="tel:0987919069" aria-label="Hotline chính" class="pulse-btn flex items-center gap-2 bg-accent hover:bg-red-700 text-white rounded-full px-3.5 py-2.5 sm:px-4 sm:py-2.5 shadow-xl transition">
      <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
      <span class="text-xs font-black">0987.919.069</span>
    </a>
  </div>

  <!-- =====================================================================
       14. MODAL PHÓNG TO ẢNH THỰC TẾ (LIGHTBOX)
       ===================================================================== -->
  <div id="imageLightbox" class="fixed inset-0 z-50 hidden bg-black/85 flex items-center justify-center p-4">
    <div class="relative max-w-4xl w-full bg-white rounded-lg overflow-hidden shadow-2xl">
      <div class="flex items-center justify-between px-4 py-2.5 bg-primary text-white">
        <span id="lightboxCaption" class="font-bold text-xs sm:text-sm truncate">Hình ảnh công trình thực tế Tân Đại Việt</span>
        <button onclick="closeLightbox()" class="w-8 h-8 rounded bg-white/15 hover:bg-white/25 flex items-center justify-center">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-2 bg-slate-900 flex items-center justify-center max-h-[78vh]">
        <img id="lightboxImg" src="" alt="Phóng to công trình" class="max-h-[74vh] w-auto max-w-full object-contain">
      </div>
    </div>
  </div>

  <!-- =====================================================================
       15. JAVASCRIPT
       ===================================================================== -->
  <script>
    let currentBannerIndex = 0;
    const bannerSlides = document.querySelectorAll('#mainBannerSlider .banner-slide');
    const bannerDots = document.querySelectorAll('#mainBannerSlider .banner-dot');
    let bannerTimer = null;

    function showSlide(index) {
      if (!bannerSlides.length) return;
      currentBannerIndex = (index + bannerSlides.length) % bannerSlides.length;
      bannerSlides.forEach((slide, i) => {
        if (i === currentBannerIndex) {
          slide.classList.add('active');
        } else {
          slide.classList.remove('active');
        }
      });
      bannerDots.forEach((dot, i) => {
        if (i === currentBannerIndex) {
          dot.className = 'banner-dot w-6 h-2 rounded-full bg-yellow-400 transition-all';
        } else {
          dot.className = 'banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all';
        }
      });
    }

    function changeSlide(step) {
      showSlide(currentBannerIndex + step);
      resetBannerInterval();
    }

    function goToSlide(index) {
      showSlide(index);
      resetBannerInterval();
    }

    function resetBannerInterval() {
      if (bannerTimer) clearInterval(bannerTimer);
      bannerTimer = setInterval(() => {
        showSlide(currentBannerIndex + 1);
      }, 4500);
    }

    resetBannerInterval();

    function toggleMobileMenu() {
      const drawer = document.getElementById('mobileMenuDrawer');
      if (drawer) drawer.classList.toggle('hidden');
    }

    function selectServiceForQuote(serviceName) {
      const noteEl = document.getElementById('qNote');
      const formSection = document.getElementById('form-bao-gia');
      if (noteEl) noteEl.value = 'Tôi cần tư vấn & báo giá hạng mục: ' + serviceName;
      if (formSection) formSection.scrollIntoView({ behavior: 'smooth' });
    }

    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const category = document.getElementById('qCategory').value;
      const address = document.getElementById('qAddress').value.trim();
      const msgBox = document.getElementById('quoteSuccessMsg');

      if (msgBox) {
        msgBox.classList.remove('hidden');
        msgBox.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá hạng mục <strong>${category}</strong> ${address ? 'tại ' + address : ''} đã được ghi nhận. Kỹ thuật viên Tân Đại Việt sẽ liên hệ ngay!`;
      }
    }

    function filterProductsByQuery(query) {
      const q = query.trim().toLowerCase();
      if (!q) return;
      const cards = document.querySelectorAll('.product-card');
      let firstMatch = null;
      cards.forEach(card => {
        const text = card.innerText.toLowerCase();
        if (text.includes(q)) {
          card.classList.add('ring-2', 'ring-accent');
          if (!firstMatch) firstMatch = card;
        } else {
          card.classList.remove('ring-2', 'ring-accent');
        }
      });
      if (firstMatch) firstMatch.scrollIntoView({ behavior: 'smooth', block: 'center' });
    }

    function handleSearch(e) {
      e.preventDefault();
      filterProductsByQuery(document.getElementById('desktopSearchInput').value);
    }

    function handleMobileSearch(e) {
      e.preventDefault();
      filterProductsByQuery(document.getElementById('mobileSearchInput').value);
    }

    function openLightbox(fileId, caption) {
      const modal = document.getElementById('imageLightbox');
      const img = document.getElementById('lightboxImg');
      const cap = document.getElementById('lightboxCaption');
      if (modal && img && cap) {
        cap.textContent = caption;
        img.setAttribute('data-retry', '0');
        img.onerror = function() { retryDriveImage(this, fileId); };
        img.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w1400';
        modal.classList.remove('hidden');
      }
    }

    function closeLightbox() {
      const modal = document.getElementById('imageLightbox');
      if (modal) modal.classList.add('hidden');
    }
  </script>
</body>
</html>
