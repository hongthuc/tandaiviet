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

    /* Kích thước chuyên nghiệp cho 2 Banner tự trượt */
    .fs-banner-slider {
      position: relative;
      width: 100%;
      aspect-ratio: 16 / 7;
      max-height: 500px;
      min-height: 220px;
      overflow: hidden;
      background-color: #072b52;
      border-radius: 10px;
    }
    @media (min-width: 1024px) {
      .fs-banner-slider {
        aspect-ratio: 21 / 8;
      }
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

    /* Ẩn thanh cuộn phụ nếu có */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>

  <!-- Script tự động xử lý link ảnh Google Drive đa luồng (Đảm bảo 100% chỉ dùng ảnh Drive thực tế của Tân Đại Việt) -->
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
       1. TOPBAR FLATSOME (Đơn giản, chỉ hiển thị thông tin công ty, không có thanh UX Builder)
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
       2. HEADER FLATSOME (Không để nút gọi ngay trên Header để tránh tràn viền)
       ===================================================================== -->
  <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-gray-200">
    <!-- Header Main -->
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

        <!-- Ô tìm kiếm chuẩn Flatsome (Hiển thị trên máy tính) -->
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

        <!-- Thông tin địa chỉ văn phòng & xưởng trên Desktop (Không để nút Gọi ngay) -->
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

      <!-- Thanh tìm kiếm gọn trên điện thoại -->
      <div class="mt-2.5 md:hidden">
        <form onsubmit="handleMobileSearch(event)" class="w-full flex">
          <input
            id="mobileSearchInput"
            type="text"
            placeholder="Tìm dịch vụ: Bảng hiệu, Chữ nổi, CNC, In ấn..."
            class="w-full px-3 py-1.5 text-xs border border-gray-300 rounded-l-md focus:outline-none focus:border-primary"
          >
          <button type="submit" class="bg-primary text-white px-3.5 py-1.5 rounded-r-md text-xs">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </form>
      </div>
    </div>

    <!-- Header Bottom Navigation (Chuẩn Flatsome Mega Menu + Danh mục mẫu Phucloiviet.vn) -->
    <nav class="hidden lg:block bg-primary text-white">
      <div class="fs-container flex items-center justify-between">
        <!-- Nút Danh Mục Sản Phẩm sổ xuống -->
        <div class="relative group">
          <div class="bg-accent px-5 py-3 font-bold text-sm uppercase flex items-center gap-2.5 cursor-pointer">
            <i class="fa-solid fa-bars-staggered"></i>
            <span>DANH MỤC SẢN PHẨM</span>
            <i class="fa-solid fa-chevron-down text-xs ml-1"></i>
          </div>
          <!-- Dropdown Danh mục chuẩn web mẫu phucloiviet.vn -->
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
              <span><i class="fa-solid fa-wand-magic-sparkles w-6 text-primary"></i>CNC – Cắt Laser – Hàn Uốn Inox</span>
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

        <!-- Menu Ngang Chính -->
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

    <!-- Menu Drawer trên Điện thoại -->
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
       3. [UX BUILDER SECTION] 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC CHUYÊN NGHIỆP
       (Sử dụng trực tiếp ảnh công trình thực tế từ Google Drive, không để nhãn dán thừa)
       ===================================================================== -->
  <section id="trang-chu" class="py-3 md:py-5">
    <div class="fs-container">
      <div class="fs-banner-slider shadow-md group" id="mainBannerSlider">

        <!-- SLIDE 1 -->
        <div class="banner-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10">
          <img
            src="https://lh3.googleusercontent.com/d/1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY=w1600"
            onerror="retryDriveImage(this, '1SMOThy-0k_10RMKYDuE8EGLMHeb0d3kY')"
            alt="Banner 1 - Công ty TNHH Thiết kế Thi công Quảng cáo Tân Đại Việt"
            class="w-full h-full object-cover"
          >
          <div class="absolute inset-0 bg-gradient-to-r from-slate-950/85 via-slate-900/60 to-transparent flex items-center">
            <div class="px-5 sm:px-10 md:px-14 max-w-2xl text-white space-y-2 sm:space-y-3.5">
              <p class="text-yellow-400 font-bold text-xs sm:text-sm uppercase tracking-wider">
                CÔNG TY TNHH THIẾT KẾ THI CÔNG QUẢNG CÁO TÂN ĐẠI VIỆT
              </p>
              <h1 class="text-lg sm:text-2xl md:text-4xl font-black leading-tight uppercase">
                THIẾT KẾ & THI CÔNG BẢNG HIỆU QUẢNG CÁO TRỌN GÓI ĐÀ NẴNG
              </h1>
              <p class="text-xs sm:text-sm md:text-base text-gray-200 line-clamp-2">
                Chuyên mặt dựng Alu, chữ nổi Inox - Mica đèn LED, Pano, Hộp đèn, Showroom nội ngoại thất. Sản xuất trực tiếp tại xưởng K88/9B Lê Đình Lý.
              </p>
              <div class="pt-1 flex flex-wrap items-center gap-2.5">
                <a href="#form-bao-gia" class="bg-accent hover:bg-red-700 text-white font-bold text-xs sm:text-sm px-4 sm:px-5 py-2 sm:py-2.5 rounded-md transition">
                  NHẬN BÁO GIÁ NGAY
                </a>
                <a href="#du-an-thuc-te" class="bg-white/15 hover:bg-white/25 backdrop-blur text-white font-bold text-xs sm:text-sm px-4 sm:px-5 py-2 sm:py-2.5 rounded-md border border-white/30 transition">
                  XEM CÔNG TRÌNH THỰC TẾ
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- SLIDE 2 -->
        <div class="banner-slide absolute inset-0 transition-opacity duration-700 opacity-0 z-0">
          <img
            src="https://lh3.googleusercontent.com/d/1H0Gh7sJbSuLnCQqUMuy_hYqh9knwWzTg=w1600"
            onerror="retryDriveImage(this, '1H0Gh7sJbSuLnCQqUMuy_hYqh9knwWzTg')"
            alt="Banner 2 - Xưởng Gia Công Chữ Nổi CNC Laser In Ấn Tân Đại Việt"
            class="w-full h-full object-cover"
          >
          <div class="absolute inset-0 bg-gradient-to-r from-primaryDark/90 via-primary/65 to-transparent flex items-center">
            <div class="px-5 sm:px-10 md:px-14 max-w-2xl text-white space-y-2 sm:space-y-3.5">
              <p class="text-yellow-300 font-bold text-xs sm:text-sm uppercase tracking-wider">
                XƯỞNG SẢN XUẤT TRỰC TIẾP - KHÔNG QUA TRUNG GIAN
              </p>
              <h2 class="text-lg sm:text-2xl md:text-4xl font-black leading-tight uppercase">
                GIA CÔNG CHỮ NỔI INOX - CẮT CNC LASER - IN PHUN KHỔ LỚN
              </h2>
              <p class="text-xs sm:text-sm md:text-base text-gray-100 line-clamp-2">
                Văn phòng: 149 Hoàng Diệu, Đà Nẵng | Xưởng SX: K88/9B Lê Đình Lý, Đà Nẵng | Hotline tư vấn 24/7: 0987.919.069 – 0369.561.458
              </p>
              <div class="pt-1 flex flex-wrap items-center gap-2.5">
                <a href="tel:0987919069" class="bg-yellow-400 hover:bg-yellow-300 text-slate-900 font-bold text-xs sm:text-sm px-4 sm:px-5 py-2 sm:py-2.5 rounded-md transition">
                  HOTLINE: 0987.919.069
                </a>
                <a href="#danh-muc-trang-chu" class="bg-white/15 hover:bg-white/25 text-white font-bold text-xs sm:text-sm px-4 sm:px-5 py-2 sm:py-2.5 rounded-md border border-white/30 transition">
                  KHÁM PHÁ DỊCH VỤ
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- Nút điều hướng Trái / Phải của Slider -->
        <button onclick="changeSlide(-1)" aria-label="Slide trước" class="
