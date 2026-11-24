<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>nhomthanhchau.com | CÔNG TY TNHH TM&DV TỔNG HỢP THANH CHÂU - Cửa Nhôm Xingfa Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH TM&DV TỔNG HỢP THANH CHÂU - Chuyên phân phối và thi công cửa nhôm Xingfa, cửa kính cường lực, cửa nhựa lõi thép, cầu thang kính, kính ốp bếp, phòng tắm kính uy tín tại Đà Nẵng. Hotline: 0905.471.427" />

  <!-- Meta Thumbnail Chia Sẻ Link (Open Graph & Twitter Card dùng ảnh Logo công ty) -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="nhomthanhchau.com" />
  <meta property="og:title" content="CÔNG TY TNHH TM&DV TỔNG HỢP THANH CHÂU - Nhôm Kính Hàng Đầu Đà Nẵng" />
  <meta property="og:description" content="Nhôm Thanh Châu - Trao uy tín, nhận niềm tin. Chuyên cửa nhôm Xingfa, cửa kính cường lực, cầu thang kính, phòng tắm kính tại 74 Trần Nam Trung, Hòa Xuân, Đà Nẵng." />
  <meta property="og:url" content="https://nhomthanhchau.com" />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1mGd074wuvHvQQIdW3Trval9a4Jsl3nZ2=w1200" />
  <meta property="og:image:alt" content="Logo Công ty TNHH TM&DV Tổng Hợp Thanh Châu" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH TM&DV TỔNG HỢP THANH CHÂU - nhomthanhchau.com" />
  <meta name="twitter:description" content="Cửa nhôm Xingfa, cửa kính cường lực chính hãng tại Đà Nẵng. Hotline: 0905.471.427" />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1mGd074wuvHvQQIdW3Trval9a4Jsl3nZ2=w1200" />
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1mGd074wuvHvQQIdW3Trval9a4Jsl3nZ2=w256" />

  <!-- Font Inter chuẩn hiện đại & dễ đọc tiếng Việt -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Cấu hình màu sắc đồng bộ theo tông màu thương hiệu Nhôm Thanh Châu -->
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              primary: '#0D3B66',     /* Xanh navy đậm chuẩn ngành nhôm kính */
              secondary: '#15528A',   /* Xanh dương nổi bật hover */
              light: '#EAF2FA',       /* Nền xanh nhạt sạch sẽ */
              accent: '#D62828',      /* Đỏ thương hiệu cho giá & giảm giá */
              accentHover: '#B51D1D',
              gold: '#D97706',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Reset chặt chẽ chống tràn viền ngang và lệch trang trên mọi thiết bị */
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
      scroll-behavior: smooth;
      background-color: #ffffff;
      color: #1e293b;
    }

    /* Khung giao diện chuẩn 95% trên máy tính, 100% có lề gọn trên điện thoại */
    .tc-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 640px) {
      .tc-container {
        padding-left: 18px;
        padding-right: 18px;
      }
    }
    @media (min-width: 1024px) {
      .tc-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Flatsome Section Title có đường kẻ ngang tinh tế */
    .flatsome-title-wrap {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 14px;
      margin-bottom: 1.5rem;
    }
    .flatsome-title-wrap::before,
    .flatsome-title-wrap::after {
      content: "";
      flex: 1;
      height: 2px;
      background: linear-gradient(90deg, transparent, #cbd5e1);
      max-width: 180px;
    }
    .flatsome-title-wrap::after {
      background: linear-gradient(90deg, #cbd5e1, transparent);
    }

    /* Menu desktop: chữ nhỏ gọn, viết liền không xuống dòng trong tên danh mục */
    .desktop-nav-link {
      white-space: nowrap;
      word-break: keep-all;
      font-size: 12.5px;
      line-height: 1.2;
      transition: background-color 0.2s ease, color 0.2s ease;
    }
    @media (min-width: 1280px) {
      .desktop-nav-link {
        font-size: 13px;
      }
    }

    /* Dropdown menu mượt mà chuẩn Flatsome */
    .nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(6px);
      transition: all 0.2s ease;
    }
    .nav-item-has-children:hover .nav-dropdown,
    .nav-item-has-children:focus-within .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Slider 2 banner kích thước bằng nhau tuyệt đối, tự trượt mượt mà */
    .banner-track {
      display: flex;
      transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
      width: 100%;
    }
    .banner-slide {
      min-width: 100%;
      width: 100%;
      flex-shrink: 0;
      display: flex;
      align-items: stretch;
    }

    /* Hiệu ứng nút liên hệ nổi tinh tế */
    @keyframes softPulse {
      0%, 100% { box-shadow: 0 0 0 0 rgba(214, 40, 40, 0.45); }
      50% { box-shadow: 0 0 0 10px rgba(214, 40, 40, 0); }
    }
    .pulse-hotline {
      animation: softPulse 2.2s infinite;
    }
  </style>
</head>

<body class="bg-white text-slate-800 antialiased">

  <!-- ======================================================================= -->
  <!-- PHẦN 1: TOP BAR THÔNG TIN (Gọn sạch, KHÔNG có thanh chỉnh sửa UXBuilder) -->
  <!-- ======================================================================= -->
  <div class="bg-brand-primary text-white text-xs border-b border-white/10">
    <div class="tc-container py-2 flex flex-col sm:flex-row items-center justify-between gap-1 text-center sm:text-left">
      <div class="flex flex-wrap items-center justify-center sm:justify-start gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <svg class="w-3.5 h-3.5 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          <span>74 Trần Nam Trung, Phường Hòa Xuân, Thành phố Đà Nẵng</span>
        </span>
        <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
          <svg class="w-3.5 h-3.5 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          <span>Làm việc: 07:30 - 17:30 (T2 - T7)</span>
        </span>
      </div>
      <div class="hidden sm:flex items-center gap-4 text-slate-100">
        <span class="font-medium tracking-wide">NHÔM THANH CHÂU - TRAO UY TÍN, NHẬN NIỀM TIN</span>
        <span class="text-white/40">|</span>
        <a href="https://nhomthanhchau.com" class="hover:text-amber-300 transition">nhomthanhchau.com</a>
      </div>
    </div>
  </div>

  <!-- ======================================================================= -->
  <!-- PHẦN 2: HEADER CHÍNH (Logo thu gọn + Ô tìm kiếm, KHÔNG để nút gọi ngay) -->
  <!-- ======================================================================= -->
  <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
    <!-- Hàng trên Header: Logo nhỏ gọn & Tìm kiếm sản phẩm -->
    <div class="tc-container py-2.5 flex items-center justify-between gap-3">
      <!-- Nút mở Menu trên điện thoại -->
      <button id="mobileMenuOpenBtn" type="button" aria-label="Mở danh mục menu"
        class="lg:hidden p-2 rounded-lg text-brand-primary hover:bg-brand-light transition shrink-0">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>

      <!-- Logo Công ty Thanh Châu (Chỉnh gọn nhỏ lại, cân đối) -->
      <a href="#trang-chu" class="flex items-center gap-2.5 min-w-0 shrink-0">
        <img
          src="https://lh3.googleusercontent.com/d/1mGd074wuvHvQQIdW3Trval9a4Jsl3nZ2=w400"
          data-gid="1mGd074wuvHvQQIdW3Trval9a4Jsl3nZ2"
          alt="Logo Công ty TNHH TM&DV Tổng Hợp Thanh Châu"
          class="h-10 sm:h-11 lg:h-12 w-auto max-w-[130px] object-contain rounded"
          onerror="handleDriveImgError(this, 'LOGO THANH CHAU')"
        />
        <div class="leading-tight hidden sm:block">
          <div class="text-xs lg:text-sm font-extrabold text-brand-primary uppercase tracking-tight">
            CÔNG TY TNHH TM&amp;DV TỔNG HỢP THANH CHÂU
          </div>
          <div class="text-[11px] text-slate-500 font-medium">
            nhomthanhchau.com • Nhôm Kính &amp; Cửa Xingfa Đà Nẵng
          </div>
        </div>
      </a>

      <!-- Thanh tìm kiếm sản phẩm chuẩn Flatsome -->
      <form id="headerSearchForm" class="flex-1 max-w-md ml-auto flex items-center bg-slate-100 border border-slate-200 rounded-lg overflow-hidden focus-within:border-brand-primary focus-within:bg-white transition">
        <input
          id="headerSearchInput"
          type="text"
          placeholder="Tìm cửa nhôm Xingfa, cầu thang kính..."
          class="w-full bg-transparent px-3 py-2 text-xs sm:text-sm text-slate-700 placeholder-slate-400 focus:outline-none"
        />
        <button type="submit" aria-label="Tìm kiếm"
          class="bg-brand-primary hover:bg-brand-secondary text-white px-3.5 py-2 transition shrink-0">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-4.35-4.35m0 0A7.5 7.5 0 1010.5 18a7.5 7.5 0 006.15-3.35z" />
          </svg>
        </button>
      </form>
    </div>

    <!-- ===================================================================== -->
    <!-- THANH MENU DANH MỤC TRÊN MÁY TÍNH (Chữ nhỏ gọn, viết liền 1 hàng)     -->
    <!-- ===================================================================== -->
    <nav aria-label="Menu chính máy tính" class="hidden lg:block bg-brand-primary text-white border-t border-white/10">
      <div class="tc-container">
        <ul class="flex flex-wrap items-center justify-center gap-x-1 xl:gap-x-2 py-0.5">
          <li>
            <a href="#trang-chu" class="desktop-nav-link inline-flex items-center px-2.5 xl:px-3 py-2.5 font-semibold uppercase hover:bg-brand-secondary rounded">
              Trang chủ
            </a>
          </li>
          <li>
            <a href="#gioi-thieu" class="desktop-nav-link inline-flex items-center px-2.5 xl:px-3 py-2.5 font-semibold uppercase hover:bg-brand-secondary rounded">
              Giới thiệu
            </a>
          </li>

          <!-- Dropdown: Cửa nhôm xingfa -->
          <li class="relative nav-item-has-children">
            <a href="#san-pham-xingfa" class="desktop-nav-link inline-flex items-center gap-1 px-2.5 xl:px-3 py-2.5 font-semibold uppercase hover:bg-brand-secondary rounded">
              <span>Cửa nhôm xingfa</span>
              <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <ul class="nav-dropdown absolute left-0 top-full w-56 bg-white text-slate-700 rounded-b-lg shadow-xl border border-slate-200 py-1.5 z-50">
              <li><a href="#san-pham-xingfa" onclick="filterProductKeyword('1 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-primary transition">Cửa nhôm xingfa 1 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProductKeyword('2 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-primary transition">Cửa nhôm xingfa 2 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProductKeyword('3 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-primary transition">Cửa nhôm xingfa 3 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProductKeyword('4 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-primary transition">Cửa nhôm xingfa 4 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProductKeyword('Xếp Trượt')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-primary transition">Cửa nhôm xingfa 5 cánh</a></li>
            </ul>
          </li>

          <li>
            <a href="#danh-muc-san-pham" class="desktop-nav-link inline-flex items-center px-2.5 xl:px-3 py-2.5 font-semibold uppercase hover:bg-brand-secondary rounded">
              Cửa kính cường lực
            </a>
          </li>

          <!-- Dropdown: Sản phẩm -->
          <li class="relative nav-item-has-children">
            <a href="#danh-muc-san-pham" class="desktop-nav-link inline-flex items-center gap-1 px-2.5 xl:px-3 py-2.5 font-semibold uppercase hover:bg-brand-secondary rounded">
              <span>Sản phẩm</span>
              <svg class="w-3 h-3 opacity-80" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <ul class="nav-dropdown absolute left-0 top-full w-56 bg-white text-slate-700 rounded-b-lg shadow-xl border border-slate-200 py-1.5 z-50">
              <li><a href="#san-pham-xingfa" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-primary transition">Cửa nhôm xingfa</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa nhựa lõi thép')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-primary transition">Cửa nhựa lõi thép</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa kính tự động')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-primary transition">Cửa kính tự động</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cầu thang kính')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-primary transition">Cầu thang kính</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Kính ốp bếp')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-primary transition">Kính ốp bếp</a></li>
              <li><a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Phòng tắm kính')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-primary transition">Phòng tắm kính</a></li>
            </ul>
          </li>

          <li>
            <a href="#cong-trinh" class="desktop-nav-link inline-flex items-center px-2.5 xl:px-3 py-2.5 font-semibold uppercase hover:bg-brand-secondary rounded">
              Công trình
            </a>
          </li>
          <li>
            <a href="#bao-gia" class="desktop-nav-link inline-flex items-center px-2.5 xl:px-3 py-2.5 font-semibold uppercase hover:bg-brand-secondary rounded">
              Báo giá
            </a>
          </li>
          <li>
            <a href="#tin-tuc" class="desktop-nav-link inline-flex items-center px-2.5 xl:px-3 py-2.5 font-semibold uppercase hover:bg-brand-secondary rounded">
              Tin tức
            </a>
          </li>
          <li>
            <a href="#lien-he" class="desktop-nav-link inline-flex items-center px-2.5 xl:px-3 py-2.5 font-semibold uppercase hover:bg-brand-secondary rounded">
              Liên hệ
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- ======================================================================= -->
  <!-- MENU TRƯỢT CHO ĐIỆN THOẠI (Mobile Off-canvas Flatsome Style)            -->
  <!-- ======================================================================= -->
  <div id="mobileMenuOverlay" class="fixed inset-0 bg-slate-900/60 z-50 hidden opacity-0 transition-opacity duration-200"></div>
  <aside id="mobileDrawer" aria-label="Menu di động"
    class="fixed top-0 left-0 h-full w-72 max-w-[85vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 shadow-2xl flex flex-col">
    <div class="p-4 bg-brand-primary text-white flex items-center justify-between">
      <div class="flex items-center gap-2">
        <img
          src="https://lh3.googleusercontent.com/d/1mGd074wuvHvQQIdW3Trval9a4Jsl3nZ2=w200"
          data-gid="1mGd074wuvHvQQIdW3Trval9a4Jsl3nZ2"
          alt="Logo Nhôm Thanh Châu"
          class="h-8 w-auto bg-white rounded p-0.5 object-contain"
          onerror="handleDriveImgError(this, 'TC')"
        />
        <span class="font-bold text-sm">NHÔM THANH CHÂU</span>
      </div>
      <button id="mobileMenuCloseBtn" type="button" aria-label="Đóng menu" class="p-1.5 rounded hover:bg-white/15">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
      </button>
    </div>

    <nav class="flex-1 overflow-y-auto divide-y divide-slate-100 text-sm font-medium text-slate-700">
      <a href="#trang-chu" class="mobile-nav-close block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Trang chủ</a>
      <a href="#gioi-thieu" class="mobile-nav-close block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Giới thiệu</a>

      <!-- Accordion: Cửa nhôm xingfa -->
      <div>
        <button type="button" class="mobile-accordion-btn w-full flex items-center justify-between px-4 py-3 hover:bg-brand-light hover:text-brand-primary">
          <span>Cửa nhôm xingfa</span>
          <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div class="hidden bg-slate-50 pl-6 pr-4 py-1 space-y-1 text-xs text-slate-600">
          <a href="#san-pham-xingfa" onclick="filterProductKeyword('1 cánh')" class="mobile-nav-close block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 1 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProductKeyword('2 cánh')" class="mobile-nav-close block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 2 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProductKeyword('3 cánh')" class="mobile-nav-close block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 3 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProductKeyword('4 cánh')" class="mobile-nav-close block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 4 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProductKeyword('Xếp Trượt')" class="mobile-nav-close block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 5 cánh</a>
        </div>
      </div>

      <a href="#danh-muc-san-pham" class="mobile-nav-close block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Cửa kính cường lực</a>

      <!-- Accordion: Sản phẩm -->
      <div>
        <button type="button" class="mobile-accordion-btn w-full flex items-center justify-between px-4 py-3 hover:bg-brand-light hover:text-brand-primary">
          <span>Sản phẩm</span>
          <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div class="hidden bg-slate-50 pl-6 pr-4 py-1 space-y-1 text-xs text-slate-600">
          <a href="#san-pham-xingfa" class="mobile-nav-close block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa</a>
          <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa nhựa lõi thép')" class="mobile-nav-close block py-2 hover:text-brand-primary">+ Cửa nhựa lõi thép</a>
          <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cửa kính tự động')" class="mobile-nav-close block py-2 hover:text-brand-primary">+ Cửa kính tự động</a>
          <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Cầu thang kính')" class="mobile-nav-close block py-2 hover:text-brand-primary">+ Cầu thang kính</a>
          <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Kính ốp bếp')" class="mobile-nav-close block py-2 hover:text-brand-primary">+ Kính ốp bếp</a>
          <a href="#danh-muc-san-pham" onclick="selectCategoryQuote('Phòng tắm kính')" class="mobile-nav-close block py-2 hover:text-brand-primary">+ Phòng tắm kính</a>
        </div>
      </div>

      <a href="#cong-trinh" class="mobile-nav-close block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Công trình</a>
      <a href="#bao-gia" class="mobile-nav-close block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Báo giá</a>
      <a href="#tin-tuc" class="mobile-nav-close block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Tin tức</a>
      <a href="#lien-he" class="mobile-nav-close block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Liên hệ</a>
    </nav>

    <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1">
      <div class="font-bold text-brand-primary">Hotline: 0905.471.427</div>
      <div>74 Trần Nam Trung, P. Hòa Xuân, TP. Đà Nẵng</div>
    </div>
  </aside>

  <!-- ======================================================================= -->
  <!-- PHẦN 3: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (Bằng kích thước, chữ xa viền) -->
  <!-- ======================================================================= -->
  <section id="trang-chu" class="py-3 sm:py-4 bg-slate-50">
    <div class="tc-container">
      <div class="relative rounded-xl overflow-hidden shadow-md border border-slate-200 bg-brand-primary">
        <!-- Khung trượt 2 banner kích thước đồng đều tuyệt đối -->
        <div id="bannerTrack" class="banner-track">

          <!-- BANNER 1 -->
          <div class="banner-slide bg-gradient-to-br from-[#0A2D4F] via-[#0D3B66] to-[#16558F] text-white">
            <!-- Khoảng đệm lớn mọi phía (px-10 py-8 sm:px-16 sm:py-12 lg:px-20 lg:py-14) đảm bảo chữ cách xa viền và không bao giờ bị mất chữ -->
            <div class="w-full px-10 py-8 sm:px-16 sm:py-12 lg:px-20 lg:py-14 grid grid-cols-1 md:grid-cols-12 gap-6 items-center">
              <!-- Nội dung chữ nằm trọn trong vùng an toàn -->
              <div class="md:col-span-7 space-y-3 sm:space-y-4 text-center md:text-left">
                <p class="text-xs sm:text-sm font-semibold uppercase tracking-widest text-amber-300">
                  CÔNG TY TNHH TM&amp;DV TỔNG HỢP THANH CHÂU
                </p>
                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                  CỬA NHÔM XINGFA &amp; NHÔM KÍNH CHÍNH HÃNG TẠI ĐÀ NẴNG
                </h1>
                <p class="text-xs sm:text-sm lg:text-base text-slate-100 leading-relaxed max-w-xl mx-auto md:mx-0">
                  Chuyên phân phối nhôm chuẩn hệ, gia công &amp; lắp đặt cửa nhôm Xingfa, cửa kính cường lực, cầu thang kính, phòng tắm kính. Giá trực tiếp tại xưởng — bảo hành chu đáo.
                </p>
                <div class="pt-2 flex flex-wrap items-center justify-center md:justify-start gap-3">
                  <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold shadow transition">
                    Nhận Báo Giá Ngay
                  </a>
                  <a href="#san-pham-xingfa" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                    Xem Sản Phẩm
                  </a>
                </div>
              </div>

              <!-- Hình ảnh minh họa nằm gọn hoàn toàn bên trong khung banner -->
              <div class="md:col-span-5 flex justify-center">
                <div class="w-full max-w-[340px] md:max-w-full aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-xl bg-white/10">
                  <img
                    src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w1000"
                    data-gid="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                    alt="Cửa nhôm Xingfa Thanh Châu Đà Nẵng"
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'CUA NHOM XINGFA THANH CHAU')"
                  />
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 -->
          <div class="banner-slide bg-gradient-to-br from-[#0F2942] via-[#13426B] to-[#0D3B66] text-white">
            <!-- Khoảng đệm giống hệt Banner 1 đảm bảo chiều cao & bố cục bằng nhau tuyệt đối -->
            <div class="w-full px-10 py-8 sm:px-16 sm:py-12 lg:px-20 lg:py-14 grid grid-cols-1 md:grid-cols-12 gap-6 items-center">
              <div class="md:col-span-7 space-y-3 sm:space-y-4 text-center md:text-left">
                <p class="text-xs sm:text-sm font-semibold uppercase tracking-widest text-amber-300">
                  NHÔM THANH CHÂU - TRAO UY TÍN, NHẬN NIỀM TIN
                </p>
                <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                  THI CÔNG CÔNG TRÌNH KHÁCH SẠN, RESORT &amp; NHÀ PHỐ ĐÀ NẴNG
                </h2>
                <p class="text-xs sm:text-sm lg:text-base text-slate-100 leading-relaxed max-w-xl mx-auto md:mx-0">
                  Đội ngũ kỹ thuật tay nghề cao, khảo sát tận nơi miễn phí tại Đà Nẵng &amp; Miền Trung. Cam kết tiến độ, độ kín khít cách âm, chống thấm và thẩm mỹ vượt trội.
                </p>
                <div class="pt-2 flex flex-wrap items-center justify-center md:justify-start gap-3">
                  <a href="#cong-trinh" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold shadow transition">
                    Xem Công Trình Thực Tế
                  </a>
                  <a href="#lien-he" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                    Liên Hệ Tư Vấn
                  </a>
                </div>
              </div>

              <!-- Hình ảnh dự án nằm trọn bên trong khung banner -->
              <div class="md:col-span-5 flex justify-center">
                <div class="w-full max-w-[340px] md:max-w-full aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-xl bg-white/10">
                  <img
                    src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w1000"
                    data-gid="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                    alt="Thi công công trình nhôm kính tại Đà Nẵng"
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'CONG TRINH THANH CHAU')"
                  />
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng trái / phải nhỏ gọn đặt sát mép ngoài vùng đệm chữ -->
        <button id="bannerPrev" type="button" aria-label="Banner trước"
          class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition z-10">
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
        </button>
        <button id="bannerNext" type="button" aria-label="Banner tiếp theo"
          class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition z-10">
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
        </button>

        <!-- Chấm chỉ báo vị trí slide -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
          <button type="button" class="banner-dot w-6 h-2 rounded-full bg-white transition-all" data-index="0" aria-label="Slide 1"></button>
          <button type="button" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 transition-all" data-index="1" aria-label="Slide 2"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ======================================================================= -->
  <!-- PHẦN 4: GIỚI THIỆU CÔNG TY & THÔNG SỐ NỔI BẬT (Chuẩn Flatsome Section) -->
  <!-- ======================================================================= -->
  <section id="gioi-thieu" class="py-10 sm:py-12 bg-white">
    <div class="tc-container">
      <div class="flatsome-title-wrap">
        <h2 class="text-lg sm:text-2xl font-extrabold text-brand-primary uppercase text-center">
          CÔNG TY TNHH TM&amp;DV TỔNG HỢP THANH CHÂU
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
        <!-- Nội dung giới thiệu -->
        <div class="lg:col-span-7 space-y-3 text-sm sm:text-[15px] leading-relaxed text-slate-600">
          <p>
            <strong class="text-brand-primary">Nhôm Thanh Châu Đà Nẵng</strong> là đơn vị chuyên phân phối nhôm thanh định hình chuẩn hệ, thiết kế, gia công và thi công lắp đặt trọn gói các hạng mục nhôm kính cao cấp tại Đà Nẵng và khu vực Miền Trung.
          </p>
          <p>
            Với phương châm <strong class="text-brand-primary">“Trao uy tín, nhận niềm tin”</strong>, chúng tôi cung cấp đa dạng sản phẩm chính hãng gồm: <strong>Cửa nhôm Xingfa nhập khẩu, Nhôm hệ Đại Tân / ALP, Cửa nhựa lõi thép, Cửa kính cường lực, Cửa tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính</strong>.
          </p>
          <p>
            Sở hữu kho xưởng nguồn hàng lớn tại <strong>74 Trần Nam Trung, Phường Hòa Xuân, TP. Đà Nẵng</strong>, Thanh Châu cam kết báo giá trực tiếp tại xưởng, thi công đúng tiến độ và chế độ bảo hành tận tâm cho mọi công trình nhà phố, biệt thự, khách sạn và resort.
          </p>

          <!-- Cam kết dịch vụ 4 dòng rõ ràng giống web mẫu -->
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-2 text-xs sm:text-sm">
            <div class="flex items-center gap-2 p-2.5 rounded-lg bg-slate-50 border border-slate-200">
              <svg class="w-4 h-4 text-brand-primary shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>
              <span><strong>Khảo sát &amp; lắp đặt:</strong> Tư vấn tận nơi miễn phí</span>
            </div>
            <div class="flex items-center gap-2 p-2.5 rounded-lg bg-slate-50 border border-slate-200">
              <svg class="w-4 h-4 text-brand-primary shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>
              <span><strong>Ưu đãi báo giá:</strong> Chiết khấu công trình lên đến 20%</span>
            </div>
            <div class="flex items-center gap-2 p-2.5 rounded-lg bg-slate-50 border border-slate-200">
              <svg class="w-4 h-4 text-brand-primary shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>
              <span><strong>Vật tư chuẩn hệ:</strong> Nhôm dày dặn, phụ kiện đồng bộ</span>
            </div>
            <div class="flex items-center gap-2 p-2.5 rounded-lg bg-slate-50 border border-slate-200">
              <svg class="w-4 h-4 text-brand-primary shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>
              <span><strong>Bảo hành uy tín:</strong> Hỗ trợ kỹ thuật nhanh chóng</span>
            </div>
          </div>
        </div>

        <!-- 4 Ô con số năng lực (Dễ dựng lại bằng Flatsome Row 2x2) -->
        <div class="lg:col-span-5 grid grid-cols-2 gap-3 sm:gap-4">
          <div class="p-4 sm:p-5 rounded-xl bg-brand-light border border-brand-primary/15 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">150+</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Dự án đã hoàn thành</div>
          </div>
          <div class="p-4 sm:p-5 rounded-xl bg-brand-light border border-brand-primary/15 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">50+</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Nhân sự &amp; kỹ thuật</div>
          </div>
          <div class="p-4 sm:p-5 rounded-xl bg-brand-light border border-brand-primary/15 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">100+</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Mẫu sản phẩm chuẩn hệ</div>
          </div>
          <div class="p-4 sm:p-5 rounded-xl bg-brand-light border border-brand-primary/15 text-center">
            <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">100%</div>
            <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Khách hàng hài lòng</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ======================================================================= -->
  <!-- PHẦN 5: DANH MỤC SẢN PHẨM (6 Danh mục từ web mẫu, chữ nhỏ gọn tối ưu)  -->
  <!-- ======================================================================= -->
  <section id="danh-muc-san-pham" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-200">
    <div class="tc-container">
      <div class="flatsome-title-wrap">
        <h2 class="text-lg sm:text-2xl font-extrabold text-brand-primary uppercase text-center">
          DANH MỤC SẢN PHẨM
        </h2>
      </div>

      <!-- 6 cột đẹp mắt trên máy tính, 3 cột tablet, 2 cột trên điện thoại -->
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
        <!-- Danh mục 1: Cửa nhôm xingfa -->
        <a href="#san-pham-xingfa" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w700"
              data-gid="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
              alt="Cửa nhôm Xingfa"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, 'Cua nhom Xingfa')"
            />
          </div>
          <div class="p-2.5 text-center flex-1 flex items-center justify-center">
            <h3 class="text-xs xl:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase leading-snug">
              Cửa nhôm Xingfa
            </h3>
          </div>
        </a>

        <!-- Danh mục 2: Cửa nhựa lõi thép -->
        <a href="#bao-gia" onclick="selectCategoryQuote('Cửa nhựa lõi thép')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA=w700"
              data-gid="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
              alt="Cửa nhựa lõi thép"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, 'Cua nhua loi thep')"
            />
          </div>
          <div class="p-2.5 text-center flex-1 flex items-center justify-center">
            <h3 class="text-xs xl:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase leading-snug">
              Cửa nhựa lõi thép
            </h3>
          </div>
        </a>

        <!-- Danh mục 3: Cửa tự động / Cửa kính tự động -->
        <a href="#bao-gia" onclick="selectCategoryQuote('Cửa kính tự động')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ=w700"
              data-gid="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
              alt="Cửa kính tự động"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, 'Cua kinh tu dong')"
            />
          </div>
          <div class="p-2.5 text-center flex-1 flex items-center justify-center">
            <h3 class="text-xs xl:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase leading-snug">
              Cửa kính tự động
            </h3>
          </div>
        </a>

        <!-- Danh mục 4: Cầu thang kính -->
        <a href="#bao-gia" onclick="selectCategoryQuote('Cầu thang kính')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul=w700"
              data-gid="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
              alt="Cầu thang kính"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, 'Cau thang kinh')"
            />
          </div>
          <div class="p-2.5 text-center flex-1 flex items-center justify-center">
            <h3 class="text-xs xl:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase leading-snug">
              Cầu thang kính
            </h3>
          </div>
        </a>

        <!-- Danh mục 5: Kính ốp bếp -->
        <a href="#bao-gia" onclick="selectCategoryQuote('Kính ốp bếp')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb=w700"
              data-gid="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
              alt="Kính ốp bếp"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, 'Kinh op bep')"
            />
          </div>
          <div class="p-2.5 text-center flex-1 flex items-center justify-center">
            <h3 class="text-xs xl:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase leading-snug">
              Kính ốp bếp
            </h3>
          </div>
        </a>

        <!-- Danh mục 6: Phòng tắm kính -->
        <a href="#bao-gia" onclick="selectCategoryQuote('Phòng tắm kính')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-primary hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH=w700"
              data-gid="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
              alt="Phòng tắm kính"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              onerror="handleDriveImgError(this, 'Phong tam kinh')"
            />
          </div>
          <div class="p-2.5 text-center flex-1 flex items-center justify-center">
            <h3 class="text-xs xl:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase leading-snug">
              Phòng tắm kính
            </h3>
          </div>
        </a>
      </div>
    </div>
  </section>

  <!-- ======================================================================= -->
  <!-- PHẦN 6: SẢN PHẨM CỬA NHÔM XINGFA (2 cột trên điện thoại, có giá & -%)  -->
  <!-- ======================================================================= -->
  <section id="san-pham-xingfa" class="py-10 sm:py-12 bg-white">
    <div class="tc-container">
      <div class="flatsome-title-wrap">
        <h2 class="text-lg sm:text-2xl font-extrabold text-brand-primary uppercase text-center">
          BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG
        </h2>
      </div>

      <!-- Thanh lọc nhanh theo số cánh (gọn nhẹ, không nhãn dán thừa) -->
      <div class="flex flex-wrap items-center justify-center gap-2 mb-6" id="productFilterBar">
        <button type="button" data-filter="all" class="prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-brand-primary text-white transition">Tất cả mẫu cửa</button>
        <button type="button" data-filter="1 cánh" class="prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Cửa 1 cánh</button>
        <button type="button" data-filter="2 cánh" class="prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Cửa 2 cánh</button>
        <button type="button" data-filter="3 cánh" class="prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Cửa 3 cánh</button>
        <button type="button" data-filter="4 cánh" class="prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Cửa 4 cánh</button>
        <button type="button" data-filter="Xếp Trượt" class="prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Xếp trượt</button>
      </div>

      <!-- Lưới sản phẩm: Đảm bảo 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="productGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
        <!-- Dữ liệu sản phẩm được render tự động từ JS để đồng bộ tìm kiếm & lọc -->
      </div>

      <div id="productEmptyState" class="hidden text-center py-8 text-sm text-slate-500">
        Không tìm thấy mẫu cửa phù hợp. <button type="button" onclick="resetProductFilter()" class="text-brand-primary font-semibold underline ml-1">Xem tất cả sản phẩm</button>
      </div>
    </div>
  </section>

  <!-- ======================================================================= -->
  <!-- PHẦN 7: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (6 Dự án thực tế)              -->
  <!-- ======================================================================= -->
  <section id="cong-trinh" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-200">
    <div class="tc-container">
      <div class="flatsome-title-wrap">
        <h2 class="text-lg sm:text-2xl font-extrabold text-brand-primary uppercase text-center">
          CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
        </h2>
      </div>

      <!-- 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="projectGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
        <!-- Render 6 dự án Đà Nẵng từ JS -->
      </div>
    </div>
  </section>

  <!-- ======================================================================= -->
  <!-- PHẦN 8: DANH MỤC CÁC BÀI VIẾT & TIN TỨC TRANG CHỦ                       -->
  <!-- ======================================================================= -->
  <section id="tin-tuc" class="py-10 sm:py-12 bg-white">
    <div class="tc-container">
      <div class="flatsome-title-wrap">
        <h2 class="text-lg sm:text-2xl font-extrabold text-brand-primary uppercase text-center">
          TIN TỨC &amp; KIẾN THỨC NHÔM KÍNH
        </h2>
      </div>

      <!-- Danh mục các bài viết trang chủ -->
      <div class="flex flex-wrap items-center justify-center gap-2 mb-6" id="articleCategoryTabs">
        <button type="button" data-cat="all" class="art-tab-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-brand-primary text-white transition">Tất cả bài viết</button>
        <button type="button" data-cat="Kỹ thuật Xingfa" class="art-tab-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Kỹ thuật Nhôm Xingfa</button>
        <button type="button" data-cat="Kinh nghiệm chọn cửa" class="art-tab-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Kinh nghiệm chọn cửa</button>
        <button type="button" data-cat="Tin Thanh Châu" class="art-tab-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Tin công ty &amp; Ưu đãi</button>
      </div>

      <!-- Lưới bài viết: 1 cột mobile nhỏ, 2 cột sm, 3 cột desktop -->
      <div id="articleGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
        <!-- Render danh sách bài viết từ JS -->
      </div>
    </div>
  </section>

  <!-- ======================================================================= -->
  <!-- PHẦN 9: ĐỐI TÁC CỦA CHÚNG TÔI (6 Logo đối tác thực tế)                  -->
  <!-- ======================================================================= -->
  <section class="py-10 bg-slate-50 border-t border-slate-200">
    <div class="tc-container">
      <div class="flatsome-title-wrap">
        <h2 class="text-lg sm:text-2xl font-extrabold text-brand-primary uppercase text-center">
          ĐỐI TÁC CỦA CHÚNG TÔI
        </h2>
      </div>

      <div class="grid grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4 items-center">
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk=w400" data-gid="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" alt="Đối tác nhôm kính 1" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'DOI TAC 1')" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq=w400" data-gid="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" alt="Đối tác nhôm kính 2" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'DOI TAC 2')" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn=w400" data-gid="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" alt="Đối tác nhôm kính 3" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'DOI TAC 3')" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT=w400" data-gid="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" alt="Đối tác nhôm kính 4" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'DOI TAC 4')" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-=w400" data-gid="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" alt="Đối tác nhôm kính 5" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'DOI TAC 5')" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 sm:p-4 h-20 sm:h-24 flex items-center justify-center hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg=w400" data-gid="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" alt="Đối tác nhôm kính 6" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'DOI TAC 6')" />
        </div>
      </div>
    </div>
  </section>

  <!-- ======================================================================= -->
  <!-- PHẦN 10: FORM YÊU CẦU BÁO GIÁ + FANPAGE FACEBOOK + BẢN ĐỒ GOOGLE MAP   -->
  <!-- ======================================================================= -->
  <section id="bao-gia" class="py-10 sm:py-12 bg-white border-t border-slate-200">
    <div class="tc-container">
      <div class="flatsome-title-wrap">
        <h2 class="text-lg sm:text-2xl font-extrabold text-brand-primary uppercase text-center">
          YÊU CẦU BÁO GIÁ &amp; KẾT NỐI THANH CHÂU
        </h2>
      </div>

      <!-- Hàng 1: Form Yêu Cầu Báo Giá (Trái) + Fanpage Facebook (Phải) -->
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 mb-8">

        <!-- Form yêu cầu tư vấn & báo giá trang chủ -->
        <div class="lg:col-span-7 bg-slate-50 rounded-xl border border-slate-200 p-5 sm:p-7 shadow-sm">
          <h3 class="text-base sm:text-lg font-extrabold text-brand-primary uppercase mb-1">
            Đăng ký nhận tư vấn &amp; báo giá miễn phí
          </h3>
          <p class="text-xs sm:text-sm text-slate-500 mb-5">
            Để lại thông tin, đội ngũ kỹ thuật Nhôm Thanh Châu sẽ liên hệ khảo sát và gửi bảng giá tốt nhất tại xưởng.
          </p>

          <form id="quoteForm" class="space-y-4">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                <input id="qName" type="text" required placeholder="Nhập họ tên của bạn"
                  class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15" />
              </div>
              <div>
                <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905 xxx xxx"
                  class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15" />
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="qCategory" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục cần báo giá</label>
                <select id="qCategory"
                  class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                  <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa (1 - 5 cánh / Xếp trượt)</option>
                  <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                  <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                  <option value="Cửa kính tự động">Cửa kính tự động</option>
                  <option value="Cầu thang kính">Cầu thang kính</option>
                  <option value="Kính ốp bếp">Kính ốp bếp</option>
                  <option value="Phòng tắm kính">Phòng tắm kính</option>
                  <option value="Nhập nhôm thanh đại lý / công trình">Nhập nhôm thanh cho xưởng / công trình</option>
                </select>
              </div>
              <div>
                <label for="qAddress" class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ công trình</label>
                <input id="qAddress" type="text" placeholder="Quận/Huyện tại Đà Nẵng..."
                  class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15" />
              </div>
            </div>

            <div>
              <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1">Nội dung yêu cầu / Kích thước dự kiến</label>
              <textarea id="qNote" rows="3" placeholder="Ví dụ: Cần báo giá cửa đi mở quay 4 cánh mặt tiền và 3 cửa sổ mở hất..."
                class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"></textarea>
            </div>

            <!-- Thông báo phản hồi form (Không dùng alert) -->
            <div id="quoteFeedback" class="hidden p-3 rounded-lg text-xs sm:text-sm font-medium"></div>

            <div class="flex flex-wrap items-center gap-3">
              <button type="submit"
                class="px-6 py-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-sm font-bold shadow transition cursor-pointer">
                Gửi Yêu Cầu Báo Giá
              </button>
              <span class="text-xs text-slate-500">Hoặc gọi trực tiếp: <a href="tel:0905471427" class="font-bold text-brand-primary hover:underline">0905.471.427</a></span>
            </div>
          </form>
        </div>

        <!-- Fanpage Facebook đưa trực tiếp ra trang chủ -->
        <div class="lg:col-span-5 bg-slate-50 rounded-xl border border-slate-200 p-5 sm:p-6 shadow-sm flex flex-col">
          <div class="flex items-center justify-between mb-3">
            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary uppercase">
              Fanpage Facebook
            </h3>
            <a href="https://www.facebook.com/Congtynhomhangdau" target="_blank" rel="noopener noreferrer"
              class="text-xs font-semibold text-[#1877F2] hover:underline">
              Mở Facebook &rarr;
            </a>
          </div>

          <!-- Khung nhúng Fanpage Facebook chuẩn responsive -->
          <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-white flex-1 min-h-[290px] flex flex-col justify-between">
            <iframe
              title="Fanpage Nhôm Thanh Châu Đà Nẵng"
              src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FCongtynhomhangdau&tabs=timeline&width=500&height=300&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
              class="w-full h-[300px] border-0"
              scrolling="no"
              frameborder="0"
              allowfullscreen="true"
              allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
            </iframe>

            <!-- Thẻ liên kết nhanh luôn hiển thị rõ ràng bên dưới phòng trường hợp trình duyệt chặn cookie bên thứ 3 -->
            <div class="p-3.5 bg-brand-light/70 border-t border-slate-200 flex items-center justify-between gap-3">
              <div class="flex items-center gap-2.5 min-w-0">
                <img
                  src="https://lh3.googleusercontent.com/d/1mGd074wuvHvQQIdW3Trval9a4Jsl3nZ2=w200"
                  data-gid="1mGd074wuvHvQQIdW3Trval9a4Jsl3nZ2"
                  alt="Nhôm Thanh Châu"
                  class="w-10 h-10 rounded-full object-contain bg-white border border-slate-200 p-1 shrink-0"
                  onerror="handleDriveImgError(this, 'TC')"
                />
                <div class="min-w-0">
                  <div class="text-xs sm:text-sm font-bold text-slate-800 truncate">Nhôm Thanh Châu - Đà Nẵng</div>
                  <div class="text-[11px] text-slate-500 truncate">facebook.com/Congtynhomhangdau</div>
                </div>
              </div>
              <a href="https://www.facebook.com/Congtynhomhangdau" target="_blank" rel="noopener noreferrer"
                class="px-3.5 py-2 rounded-lg bg-[#1877F2] hover:bg-[#1465D0] text-white text-xs font-bold shrink-0 transition">
                Theo dõi
              </a>
            </div>
          </div>
        </div>
      </div>

      <!-- Hàng 2: Bản Đồ Google Map đưa trực tiếp ra trang chủ -->
      <div id="lien-he" class="bg-slate-50 rounded-xl border border-slate-200 p-4 sm:p-5 shadow-sm">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
          <div>
            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary uppercase">
              Bản Đồ Chỉ Đường — Văn Phòng &amp; Kho Xưởng Thanh Châu
            </h3>
            <p class="text-xs sm:text-sm text-slate-600">
              Địa chỉ: <strong>74 Trần Nam Trung, Phường Hòa Xuân, Thành phố Đà Nẵng</strong> • Hotline: <strong>0905.471.427</strong>
            </p>
          </div>
          <a href="https://www.google.com/maps/search/?api=1&query=74+Trần+Nam+Trung,+Phường+Hòa+Xuân,+Đà+Nẵng" target="_blank" rel="noopener noreferrer"
            class="inline-flex items-center justify-center gap-1.5 px-4 py-2 rounded-lg bg-brand-primary hover:bg-brand-secondary text-white text-xs font-semibold transition shrink-0">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
            <span>Chỉ đường Google Maps</span>
          </a>
        </div>

        <div class="w-full h-[280px] sm:h-[360px] rounded-xl overflow-hidden border border-slate-200 bg-slate-200">
          <iframe
            title="Bản đồ 74 Trần Nam Trung, Phường Hòa Xuân, TP. Đà Nẵng"
            src="https://maps.google.com/maps?q=74%20Tr%E1%BA%A7n%20Nam%20Trung%2C%20H%C3%B2a%20Xu%C3%A2n%2C%20C%E1%BA%A9m%20L%E1%BB%87%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
            class="w-full h-full border-0"
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade">
          </iframe>
        </div>
      </div>
    </div>
  </section>

  <!-- ======================================================================= -->
  <!-- PHẦN 11: FOOTER CHUẨN FLATSOME 4 CỘT                                    -->
  <!-- ======================================================================= -->
  <footer class="bg-[#0A2B4C] text-slate-200 pt-10 pb-6 border-t-4 border-brand-accent">
    <div class="tc-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/15">

        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <img
              src="https://lh3.googleusercontent.com/d/1mGd074wuvHvQQIdW3Trval9a4Jsl3nZ2=w300"
              data-gid="1mGd074wuvHvQQIdW3Trval9a4Jsl3nZ2"
              alt="Logo Nhôm Thanh Châu"
              class="h-10 w-auto bg-white rounded p-1 object-contain"
              onerror="handleDriveImgError(this, 'THANH CHAU')"
            />
            <div class="font-extrabold text-sm text-white leading-tight uppercase">
              NHÔM THANH CHÂU<br /><span class="text-xs font-normal text-amber-300">nhomthanhchau.com</span>
            </div>
          </div>
          <p class="text-xs leading-relaxed text-slate-300">
            <strong>CÔNG TY TNHH TM&amp;DV TỔNG HỢP THANH CHÂU</strong><br />
            Mã số thuế: 0402261386<br />
            Địa chỉ: 74 Trần Nam Trung, Phường Hòa Xuân, Thành phố Đà Nẵng<br />
            Hotline / Zalo: <a href="tel:0905471427" class="text-amber-300 font-bold hover:underline">0905.471.427</a><br />
            Website: <a href="https://nhomthanhchau.com" class="text-white hover:underline">nhomthanhchau.com</a>
          </p>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-white/15 inline-block">
            Cửa Nhôm Xingfa
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#san-pham-xingfa" onclick="filterProductKeyword('1 cánh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductKeyword('2 cánh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductKeyword('3 cánh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductKeyword('4 cánh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductKeyword('Xếp Trượt')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 5 cánh / Xếp trượt</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục dịch vụ -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-white/15 inline-block">
            Danh Mục Sản Phẩm
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#san-pham-xingfa" class="hover:text-amber-300 transition">Cửa nhôm xingfa Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cửa nhựa lõi thép Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cửa kính cường lực &amp; Cửa tự động</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cầu thang kính cường lực</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Kính ốp bếp &amp; Phòng tắm kính</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-white/15 inline-block">
            Hỗ Trợ Khách Hàng
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#gioi-thieu" class="hover:text-amber-300 transition">Giới thiệu Nhôm Thanh Châu</a></li>
            <li><a href="#cong-trinh" class="hover:text-amber-300 transition">Dự án thi công tại Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-300 transition">Đăng ký khảo sát &amp; báo giá</a></li>
            <li><a href="#tin-tuc" class="hover:text-amber-300 transition">Tin tức &amp; Kiến thức nhôm kính</a></li>
            <li><a href="https://www.facebook.com/Congtynhomhangdau" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition">Fanpage Nhôm Thanh Châu</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
        <div>Copyright © 2026 <strong>CÔNG TY TNHH TM&amp;DV TỔNG HỢP THANH CHÂU</strong> (nhomthanhchau.com).</div>
        <div>Thiết kế chuẩn Flatsome UX Builder • Đà Nẵng</div>
      </div>
    </div>
  </footer>

  <!-- ======================================================================= -->
  <!-- PHẦN 12: CÁC NÚT LIÊN HỆ NỔI BẬT (Zalo, Facebook, Hotline)              -->
  <!-- Tương thích hoàn hảo trên cả máy tính và điện thoại, không tràn viền    -->
  <!-- ======================================================================= -->
  <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-40 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook -->
    <a href="https://www.facebook.com/Congtynhomhangdau" target="_blank" rel="noopener noreferrer" aria-label="Nhắn tin Facebook Nhôm Thanh Châu"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D0] text-white rounded-full shadow-lg px-3 py-2.5 sm:px-3.5 transition">
      <svg class="w-5 h-5 shrink-0" fill="currentColor" viewBox="0 0 24 24">
        <path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/>
      </svg>
      <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a href="https://zalo.me/0905471427" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0905.471.427"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg px-3 py-2.5 sm:px-3.5 transition">
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a href="tel:0905471427" aria-label="Gọi Hotline 0905.471.427"
      class="pulse-hotline flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white rounded-full shadow-xl px-3.5 py-2.5 sm:px-4 transition">
      <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
      </svg>
      <span class="text-xs sm:text-sm font-extrabold tracking-wide">0905.471.427</span>
    </a>
  </div>

  <!-- ======================================================================= -->
  <!-- MODAL XEM CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT                          -->
  <!-- ======================================================================= -->
  <div id="detailModal" class="fixed inset-0 bg-slate-900/65 z-50 hidden items-center justify-center p-3 sm:p-5">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="sticky top-0 bg-white px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-3 z-10">
        <h3 id="modalTitle" class="text-sm sm:text-base font-extrabold text-brand-primary leading-snug">Chi tiết</h3>
        <button id="modalCloseBtn" type="button" aria-label="Đóng cửa sổ"
          class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0 transition">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>
      <div id="modalBody" class="p-5 space-y-4 text-sm text-slate-700 leading-relaxed">
        <!-- Nội dung động -->
      </div>
    </div>
  </div>

  <!-- ======================================================================= -->
  <!-- JAVASCRIPT ĐIỀU KHIỂN TOÀN BỘ TƯƠNG TÁC WEBSITE                         -->
  <!-- ======================================================================= -->
  <script>
    /**
     * Hàm dự phòng thông minh khi tải ảnh từ Google Drive:
     * Bước 1: Thử chuyển sang link Google Drive Thumbnail độ phân giải cao.
     * Bước 2: Nếu vẫn lỗi, hiển thị ảnh placeholder chuyên nghiệp kèm tên sản phẩm.
     */
    function handleDriveImgError(imgEl, fallbackText) {
      const stage = imgEl.getAttribute('data-err-stage') || '0';
      const gid = imgEl.getAttribute('data-gid');
      if (stage === '0' && gid) {
        imgEl.setAttribute('data-err-stage', '1');
        imgEl.src = 'https://drive.google.com/thumbnail?id=' + gid + '&sz=w1000';
      } else {
        imgEl.onerror = null;
        const label = encodeURIComponent(fallbackText || 'NHOM THANH CHAU');
        imgEl.src = 'https://placehold.co/600x450/0D3B66/ffffff?text=' + label;
      }
    }

    /* ======================================================================
     * DỮ LIỆU 6 SẢN PHẨM CỬA NHÔM XINGFA CHÍNH HÃNG (Đầy đủ ảnh Drive & Giá)
     * ====================================================================== */
    const PRODUCTS = [
      {
        id: 1,
        name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
        gid: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: 2450000,
        price: 2100000,
        discount: '-14%',
        tag: '1 cánh',
        specs: 'Nhôm Xingfa hệ 55 dày 2.0mm, kính cường lực 8mm-10mm, phụ kiện Kinlong/đồng bộ chính hãng, gioăng EPDM kín khít tuyệt đối.',
        desc: 'Thiết kế gọn gàng, độ bền cao, cách âm cách nhiệt hiệu quả. Phù hợp cho cửa thông phòng, cửa ban công, cửa nhà vệ sinh hoặc cửa phụ nhà phố và khách sạn tại Đà Nẵng.'
      },
      {
        id: 2,
        name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
        gid: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: 2500000,
        price: 2100000,
        discount: '-16%',
        tag: '2 cánh',
        specs: 'Nhôm Xingfa nhập khẩu hệ 55 dày 2.0mm, sơn tĩnh điện ngoài trời chống ăn mòn muối biển Đà Nẵng, kính an toàn Hải Long/Việt Nhật.',
        desc: 'Mẫu cửa mặt tiền phổ biến cho nhà phố, căn hộ và ban công rộng. Mở rộng tối đa không gian đón gió, vận hành êm ái, khóa đa điểm an toàn.'
      },
      {
        id: 3,
        name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
        gid: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: 2480000,
        price: 2100000,
        discount: '-15%',
        tag: '3 cánh',
        specs: 'Nhôm Xingfa hệ 55 chuẩn độ dày 2.0mm, ép góc CNC công nghệ mới siêu cứng cáp, bản lề 3D chịu tải nặng.',
        desc: 'Lựa chọn tối ưu cho mặt tiền kích thước trung bình cần mở rộng lối đi linh hoạt 1 cánh hoặc toàn bộ 3 cánh, mang lại diện mạo hiện đại và sang trọng.'
      },
      {
        id: 4,
        name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
        gid: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: 2550000,
        price: 2100000,
        discount: '-18%',
        tag: '4 cánh',
        specs: 'Thanh nhôm Xingfa hệ 55 dày 2.0mm có gân gia cường, chống chịu áp lực gió bão khu vực Miền Trung, kính cường lực cao cấp.',
        desc: 'Giải pháp cửa chính đẳng cấp cho mặt tiền nhà phố, biệt thự, showroom. Mở rộng tối đa diện tích thông thủy, lấy sáng tự nhiên và đảm bảo an ninh tuyệt đối.'
      },
      {
        id: 5,
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        gid: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: 2600000,
        price: 2100000,
        discount: '-19%',
        tag: 'Xếp Trượt',
        specs: 'Nhôm Xingfa hệ 63 chuyên dụng xếp trượt dày 1.8mm - 3.5mm, hệ ray trượt và bánh xe treo chịu lực siêu êm, thiết kế linh hoạt từ 4 đến 5 cánh trở lên.',
        desc: 'Xếp gọn toàn bộ các cánh cửa sang một hoặc hai bên, mở thông hoàn toàn không gian phòng khách với sân vườn, hồ bơi, nhà hàng, khách sạn và resort.'
      },
      {
        id: 6,
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        gid: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: 2400000,
        price: 2050000,
        discount: '-15%',
        tag: '2 cánh',
        specs: 'Nhôm Xingfa hệ 55 dày 1.4mm, thanh định vị góc mở chống va đập gió, bản lề chữ A inox 304 chống gỉ sét.',
        desc: 'Cho phép mở lấy gió thoáng khí ngay cả khi trời mưa mà không lo nước hắt vào nhà. Rất được ưa chuộng cho nhà cao tầng, khách sạn ven biển và nhà phố Đà Nẵng.'
      }
    ];

    /* ======================================================================
     * DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
     * ====================================================================== */
    const PROJECTS = [
      {
        title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
        gid: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
        location: 'TP. Đà Nẵng',
        scope: 'Thi công trọn gói hệ thống cửa nhôm Xingfa cao cấp, vách kính mặt dựng và phòng tắm kính cường lực tiêu chuẩn khách sạn.'
      },
      {
        title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
        gid: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
        location: 'Đà Nẵng - Quảng Nam',
        scope: 'Cung cấp và lắp đặt cửa đi xếp trượt nhôm Xingfa, cửa sổ mở hất và hệ vách kính lấy sáng hài hòa thiên nhiên cho khu nghỉ dưỡng 4 sao.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
        gid: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
        location: 'TP. Đà Nẵng',
        scope: 'Gia công lắp đặt hệ cửa nhôm kính chống ồn, chống thấm nước mưa và chịu áp lực gió biển cho toàn bộ khối phòng lưu trú.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
        gid: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
        location: 'TP. Đà Nẵng',
        scope: 'Hoàn thiện hạng mục cửa chính sảnh kính cường lực, cửa nhôm Xingfa ban công và vách ngăn kính tắm sang trọng.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
        gid: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
        location: 'TP. Đà Nẵng',
        scope: 'Thiết kế và thi công toàn bộ hệ thống cửa nhôm kính kiến trúc hiện đại, tối ưu tầm nhìn và độ bền màu sơn tĩnh điện.'
      },
      {
        title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
        gid: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
        location: 'Ven biển Đà Nẵng',
        scope: 'Thi công cửa nhôm hệ cao cấp chuyên dụng vùng biển, phụ kiện inox chống ăn mòn và kính cường lực cách âm tối ưu.'
      }
    ];

    /* ======================================================================
     * DỮ LIỆU DANH MỤC BÀI VIẾT TRANG CHỦ
     * ====================================================================== */
    const ARTICLES = [
      {
        id: 1,
        category: 'Kỹ thuật Xingfa',
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu nắng gió miền Trung & Đà Nẵng không?',
        gid: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        date: '15/11/2026',
        excerpt: 'Nhờ lớp sơn tĩnh điện cao cấp và cấu trúc khoang trống có gân gia cường, cửa nhôm Xingfa chịu gió bão và chống ăn mòn muối biển vượt trội.',
        content: 'Đà Nẵng có khí hậu nhiệt đới gió mùa, nắng nóng kéo dài và độ ẩm muối biển cao. Cửa nhôm Xingfa chính hãng với độ dày từ 1.4mm đến 2.0mm kết hợp gioăng EPDM kín khít giúp ngăn nước mưa tuyệt đối, chống cong vênh co ngót như cửa gỗ và giữ màu sơn bền đẹp hàng chục năm.'
      },
      {
        id: 2,
        category: 'Kỹ thuật Xingfa',
        title: 'Cửa nhôm Xingfa có tiết kiệm điện năng và cách âm tốt không?',
        gid: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        date: '10/11/2026',
        excerpt: 'Cấu tạo đa khoang kết hợp kính cường lực hoặc kính hộp giúp giảm thất thoát nhiệt điều hòa và ngăn tiếng ồn đô thị hiệu quả.',
        content: 'Nhờ công nghệ ép góc tiên tiến và hệ gioăng cao su kép, cửa nhôm Xingfa hạn chế tối đa thất thoát hơi lạnh máy điều hòa vào mùa hè tại Đà Nẵng. Khi kết hợp kính cường lực 8-10mm hoặc kính hộp cách âm, không gian sống trở nên yên tĩnh và tiết kiệm chi phí điện đáng kể.'
      },
      {
        id: 3,
        category: 'Kinh nghiệm chọn cửa',
        title: 'So sánh cửa nhôm Xingfa với cửa gỗ và cửa nhựa lõi thép: Nên chọn loại nào?',
        gid: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        date: '02/11/2026',
        excerpt: 'Phân tích chi tiết độ bền, khả năng chống mối mọt, chi phí đầu tư và thẩm mỹ giúp gia chủ chọn đúng dòng cửa phù hợp công trình.',
        content: 'So với cửa gỗ truyền thống dễ cong vênh, mối mọt khi gặp mưa nắng, cửa nhôm Xingfa bền bỉ hơn hẳn và không tốn công bảo dưỡng định kỳ. So với cửa nhựa lõi thép, nhôm Xingfa có kết cấu cứng cáp hơn, thanh nhôm gọn thanh thoát giúp mở rộng tầm nhìn và mang lại phong cách kiến trúc hiện đại.'
      },
      {
        id: 4,
        category: 'Kinh nghiệm chọn cửa',
        title: 'Cửa nhôm Xingfa có chống trộm an toàn không? Lưu ý khi chọn phụ kiện',
        gid: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        date: '26/10/2026',
        excerpt: 'Độ an toàn của bộ cửa phụ thuộc lớn vào độ dày thanh nhôm, kính cường lực an toàn và bộ khóa đa điểm chính hãng.',
        content: 'Để tăng khả năng chống trộm tối ưu cho cửa mặt tiền và ban công, Thanh Châu khuyến nghị khách hàng sử dụng nhôm Xingfa chuẩn hệ dày 2.0mm, kết hợp khóa đa điểm đồng bộ và kính dán an toàn 2 lớp hoặc kính cường lực dày từ 8mm trở lên.'
      },
      {
        id: 5,
        category: 'Tin Thanh Châu',
        title: 'Nhôm Thanh Châu Đà Nẵng nhập lô nhôm chuẩn hệ lớn — Ổn định giá tốt tại xưởng',
        gid: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        date: '18/10/2026',
        excerpt: 'Sẵn kho số lượng lớn nhôm Xingfa, nhôm hệ Đại Tân, ALP đáp ứng kịp thời tiến độ cho các anh em thợ và chủ đầu tư cuối năm.',
        content: 'Nhằm hỗ trợ khách hàng và các đội thợ nhôm kính trước biến động giá vật liệu, Công ty TNHH TM&DV Tổng Hợp Thanh Châu đã chủ động nhập kho số lượng lớn nhôm thanh chuẩn hệ, đầy đủ màu sắc xám ghi, đen tuyền, trắng sứ, vân gỗ. Cam kết báo giá trực tiếp tại xưởng 74 Trần Nam Trung, Hòa Xuân, Đà Nẵng.'
      },
      {
        id: 6,
        category: 'Tin Thanh Châu',
        title: 'Cảnh báo anh em thợ nhôm kính cảnh giác chiêu trò lừa đảo đặt cọc công trình',
        gid: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        date: '05/10/2026',
        excerpt: 'Chia sẻ kinh nghiệm từ Nhôm Thanh Châu giúp các đơn vị thi công phòng tránh bẫy mạo danh chủ đầu tư yêu cầu chuyển cọc mua hộ vật tư.',
        content: 'Nhôm Thanh Châu lưu ý các đối tác và anh em thợ nhôm kính tuyệt đối không ứng tiền hoặc đặt cọc mua hộ nội thất ngoài chuyên môn khi chưa gặp mặt trực tiếp chủ đầu tư và ký kết hợp đồng rõ ràng. Mọi giao dịch vật tư nhôm kính hãy liên hệ trực tiếp văn phòng uy tín.'
      }
    ];

    /* Định dạng tiền tệ VNĐ */
    function formatVND(amount) {
      return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ',') + ' ₫';
    }

    /* ======================================================================
     * RENDER SẢN PHẨM (2 cột mobile, tên sản phẩm đầy đủ không cắt chữ)
     * ====================================================================== */
    function renderProducts(list) {
      const grid = document.getElementById('productGrid');
      const empty = document.getElementById('productEmptyState');
      if (!list.length) {
        grid.innerHTML = '';
        empty.classList.remove('hidden');
        return;
      }
      empty.classList.add('hidden');

      grid.innerHTML = list.map(function (p) {
        return `
          <article class="bg-white rounded-xl border border-slate-200 hover:border-brand-primary hover:shadow-md transition overflow-hidden flex flex-col">
            <!-- Khu vực ảnh sản phẩm + Nhãn giảm giá % góc trên bên trái -->
            <div class="relative aspect-[4/3] w-full bg-slate-100 overflow-hidden">
              <span class="absolute top-2 left-2 z-10 bg-brand-accent text-white text-[11px] sm:text-xs font-extrabold px-2 py-1 rounded-md shadow">
                ${p.discount}
              </span>
              <img
                src="https://lh3.googleusercontent.com/d/${p.gid}=w700"
                data-gid="${p.gid}"
                alt="${p.name}"
                class="w-full h-full object-cover hover:scale-105 transition duration-300 cursor-pointer"
                onclick="openProductModal(${p.id})"
                onerror="handleDriveImgError(this, '${p.name.replace(/'/g, '')}')"
              />
            </div>

            <!-- Nội dung thẻ sản phẩm: Đảm bảo tên không bị tràn viền hoặc thiếu chữ trên mobile 2 cột -->
            <div class="p-2.5 sm:p-4 flex flex-col flex-1 justify-between gap-2.5">
              <div class="space-y-1.5">
                <h3 onclick="openProductModal(${p.id})"
                  class="text-[12.5px] sm:text-sm md:text-[15px] font-bold text-slate-800 hover:text-brand-primary cursor-pointer leading-snug break-words">
                  ${p.name}
                </h3>

                <!-- Giá gốc gạch ngang & Giá ưu đãi nổi bật -->
                <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                  <span class="text-sm sm:text-base font-extrabold text-brand-accent">${formatVND(p.price)}</span>
                  <span class="text-[11px] sm:text-xs text-slate-400 line-through">${formatVND(p.oldPrice)}</span>
                </div>
              </div>

              <!-- 2 nút hành động gọn gàng -->
              <div class="grid grid-cols-2 gap-1.5 sm:gap-2 pt-1">
                <button type="button" onclick="openProductModal(${p.id})"
                  class="px-2 py-2 rounded-lg border border-brand-primary text-brand-primary hover:bg-brand-light text-[11px] sm:text-xs font-bold transition text-center">
                  Chi tiết
                </button>
                <button type="button" onclick="quoteForProduct('${p.name.replace(/'/g, "\\'")}')"
                  class="px-2 py-2 rounded-lg bg-brand-primary hover:bg-brand-secondary text-white text-[11px] sm:text-xs font-bold transition text-center">
                  Báo giá
                </button>
              </div>
            </div>
          </article>
        `;
      }).join('');
    }

    /* ======================================================================
     * RENDER 6 DỰ ÁN TẠI ĐÀ NẴNG
     * ====================================================================== */
    function renderProjects() {
      const grid = document.getElementById('projectGrid');
      grid.innerHTML = PROJECTS.map(function (proj, idx) {
        return `
          <article onclick="openProjectModal(${idx})"
            class="group bg-white rounded-xl border border-slate-200 hover:border-brand-primary hover:shadow-md transition overflow-hidden flex flex-col cursor-pointer">
            <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
              <img
                src="https://lh3.googleusercontent.com/d/${proj.gid}=w800"
                data-gid="${proj.gid}"
                alt="${proj.title}"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                onerror="handleDriveImgError(this, 'DU AN DA NANG')"
              />
            </div>
            <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between gap-2">
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary leading-snug break-words">
                ${proj.title}
              </h3>
              <div class="text-[11px] sm:text-xs text-slate-500 flex items-center justify-between pt-1 border-t border-slate-100">
                <span>${proj.location}</span>
                <span class="text-brand-primary font-semibold">Xem chi tiết &rarr;</span>
              </div>
            </div>
          </article>
        `;
      }).join('');
    }

    /* ======================================================================
     * RENDER BÀI VIẾT & LỌC THEO DANH MỤC TRANG CHỦ
     * ====================================================================== */
    function renderArticles(category) {
      const grid = document.getElementById('articleGrid');
      const filtered = category === 'all'
        ? ARTICLES
        : ARTICLES.filter(function (a) { return a.category === category; });

      grid.innerHTML = filtered.map(function (art) {
        return `
          <article onclick="openArticleModal(${art.id})"
            class="group bg-white rounded-xl border border-slate-200 hover:border-brand-primary hover:shadow-md transition overflow-hidden flex flex-col cursor-pointer">
            <div class="aspect-[16/9] w-full bg-slate-100 overflow-hidden">
              <img
                src="https://lh3.googleusercontent.com/d/${art.gid}=w700"
                data-gid="${art.gid}"
                alt="${art.title}"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                onerror="handleDriveImgError(this, 'TIN TUC NHOM KINH')"
              />
            </div>
            <div class="p-4 flex flex-col flex-1 justify-between gap-2.5">
              <div class="space-y-1.5">
                <div class="flex items-center justify-between text-[11px] text-slate-500">
                  <span class="font-semibold text-brand-primary">${art.category}</span>
                  <span>${art.date}</span>
                </div>
                <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 group-hover:text-brand-primary leading-snug">
                  ${art.title}
                </h3>
                <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                  ${art.excerpt}
                </p>
              </div>
              <div class="text-xs font-bold text-brand-primary pt-1">
                Đọc tiếp &rarr;
              </div>
            </div>
          </article>
        `;
      }).join('');
    }

    /* ======================================================================
     * CÁC HÀM LỌC SẢN PHẨM, CHỌN BÁO GIÁ & MỞ MODAL
     * ====================================================================== */
    function filterProductKeyword(keyword) {
      const buttons = document.querySelectorAll('.prod-filter-btn');
      buttons.forEach(function (btn) {
        const isMatch = btn.getAttribute('data-filter') === keyword;
        btn.className = isMatch
          ? 'prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-brand-primary text-white transition'
          : 'prod-filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition';
      });

      if (keyword === 'all') {
        renderProducts(PRODUCTS);
      } else {
        const lower = keyword.toLowerCase();
        renderProducts(PRODUCTS.filter(function (p) {
          return p.name.toLowerCase().includes(lower) || p.tag.toLowerCase().includes(lower);
        }));
      }
    }

    function resetProductFilter() {
      document.getElementById('headerSearchInput').value = '';
      filterProductKeyword('all');
    }

    function selectCategoryQuote(categoryName) {
      const sel = document.getElementById('qCategory');
      if (sel) {
        for (let i = 0; i < sel.options.length; i++) {
          if (sel.options[i].value === categoryName) {
            sel.selectedIndex = i;
            break;
          }
        }
      }
    }

    function quoteForProduct(productName) {
      closeModal();
      selectCategoryQuote('Cửa nhôm Xingfa');
      const noteEl = document.getElementById('qNote');
      if (noteEl) {
        noteEl.value = 'Tôi cần nhận báo giá chi tiết cho sản phẩm: ' + productName;
      }
      const target = document.getElementById('bao-gia');
      if (target) {
        target.scrollIntoView({ behavior: 'smooth' });
      }
    }

    function openModal(title, htmlContent) {
      document.getElementById('modalTitle').textContent = title;
      document.getElementById('modalBody').innerHTML = htmlContent;
      const modal = document.getElementById('detailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function closeModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    function openProductModal(productId) {
      const p = PRODUCTS.find(function (item) { return item.id === productId; });
      if (!p) return;
      const html = `
        <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-slate-100 aspect-[16/10]">
          <span class="absolute top-3 left-3 bg-brand-accent text-white text-xs font-extrabold px-2.5 py-1 rounded-md shadow">${p.discount}</span>
          <img src="https://lh3.googleusercontent.com/d/${p.gid}=w1000" data-gid="${p.gid}" alt="${p.name}"
            class="w-full h-full object-cover" onerror="handleDriveImgError(this, '${p.name.replace(/'/g, '')}')" />
        </div>
        <div class="flex flex-wrap items-baseline gap-3">
          <span class="text-2xl font-extrabold text-brand-accent">${formatVND(p.price)} / m²</span>
          <span class="text-sm text-slate-400 line-through">${formatVND(p.oldPrice)}</span>
        </div>
        <div class="p-3.5 rounded-lg bg-slate-50 border border-slate-200 text-xs sm:text-sm">
          <strong class="text-brand-primary block mb-1">Thông số kỹ thuật:</strong>
          ${p.specs}
        </div>
        <p class="text-sm text-slate-600">${p.desc}</p>
        <div class="flex flex-wrap gap-3 pt-2">
          <button type="button" onclick="quoteForProduct('${p.name.replace(/'/g, "\\'")}')"
            class="px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-sm font-bold transition">
            Yêu Cầu Báo Giá Sản Phẩm Này
          </button>
          <a href="tel:0905471427" class="px-5 py-2.5 rounded-lg bg-brand-primary hover:bg-brand-secondary text-white text-sm font-bold transition">
            Gọi Hotline: 0905.471.427
          </a>
        </div>
      `;
      openModal(p.name, html);
    }

    function openProjectModal(index) {
      const proj = PROJECTS[index];
      if (!proj) return;
      const html = `
        <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100 aspect-[16/10]">
          <img src="https://lh3.googleusercontent.com/d/${proj.gid}=w1000" data-gid="${proj.gid}" alt="${proj.title}"
            class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'DU AN DA NANG')" />
        </div>
        <div class="text-xs font-semibold text-brand-primary">Khu vực thi công: ${proj.location}</div>
        <p class="text-sm text-slate-700">${proj.scope}</p>
        <div class="p-3.5 rounded-lg bg-brand-light text-xs text-slate-700">
          Đơn vị thi công: <strong>CÔNG TY TNHH TM&amp;DV TỔNG HỢP THANH CHÂU</strong> — 74 Trần Nam Trung, Hòa Xuân, TP. Đà Nẵng.
        </div>
        <div class="pt-1">
          <button type="button" onclick="quoteForProduct('Thi công công trình tương tự: ${proj.title.replace(/'/g, "\\'")}')"
            class="px-5 py-2.5 rounded-lg bg-brand-primary hover:bg-brand-secondary text-white text-sm font-bold transition">
            Liên Hệ Báo Giá Công Trình
          </button>
        </div>
      `;
      openModal(proj.title, html);
    }

    function openArticleModal(articleId) {
      const art = ARTICLES.find(function (a) { return a.id === articleId; });
      if (!art) return;
      const html = `
        <div class="flex items-center justify-between text-xs text-slate-500">
          <span class="font-bold text-brand-primary">${art.category}</span>
          <span>Ngày đăng: ${art.date}</span>
        </div>
        <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100 aspect-[16/9]">
          <img src="https://lh3.googleusercontent.com/d/${art.gid}=w1000" data-gid="${art.gid}" alt="${art.title}"
            class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'TIN TUC')" />
        </div>
        <p class="font-semibold text-slate-800">${art.excerpt}</p>
        <p class="text-slate-600">${art.content}</p>
        <div class="p-3.5 rounded-lg bg-slate-50 border border-slate-200 text-xs text-slate-600">
          Cần tư vấn miễn phí về cửa nhôm kính tại Đà Nẵng? Liên hệ ngay <strong>0905.471.427</strong> hoặc đến <strong>74 Trần Nam Trung, Phường Hòa Xuân, TP. Đà Nẵng</strong>.
        </div>
      `;
      openModal(art.title, html);
    }

    /* ======================================================================
     * KHỞI TẠO SỰ KIỆN KHI TRANG TẢI HOÀN TẤT
     * ====================================================================== */
    document.addEventListener('DOMContentLoaded', function () {
      // 1. Render dữ liệu ban đầu
      renderProducts(PRODUCTS);
      renderProjects();
      renderArticles('all');

      // 2. Auto-slider 2 banner chuyên nghiệp kích thước bằng nhau
      let currentSlide = 0;
      const totalSlides = 2;
      const track = document.getElementById('bannerTrack');
      const dots = document.querySelectorAll('.banner-dot');
      let slideTimer = null;

      function goToSlide(index) {
        currentSlide = (index + totalSlides) % totalSlides;
        track.style.transform = 'translateX(-' + (currentSlide * 100) + '%)';
        dots.forEach(function (dot, i) {
          if (i === currentSlide) {
            dot.classList.remove('w-2.5', 'bg-white/50');
            dot.classList.add('w-6', 'bg-white');
          } else {
            dot.classList.remove('w-6', 'bg-white');
            dot.classList.add('w-2.5', 'bg-white/50');
          }
        });
      }

      function startAutoSlide() {
        clearInterval(slideTimer);
        slideTimer = setInterval(function () {
          goToSlide(currentSlide + 1);
        }, 5000);
      }

      document.getElementById('bannerPrev').addEventListener('click', function () {
        goToSlide(currentSlide - 1);
        startAutoSlide();
      });
      document.getElementById('bannerNext').addEventListener('click', function () {
        goToSlide(currentSlide + 1);
        startAutoSlide();
      });
      dots.forEach(function (dot) {
        dot.addEventListener('click', function () {
          goToSlide(parseInt(dot.getAttribute('data-index'), 10));
          startAutoSlide();
        });
      });

      // Hỗ trợ vuốt cảm ứng (swipe) cho banner trên điện thoại
      let touchStartX = 0;
      track.addEventListener('touchstart', function (e) {
        touchStartX = e.changedTouches[0].screenX;
      }, { passive: true });
      track.addEventListener('touchend', function (e) {
        const diff = touchStartX - e.changedTouches[0].screenX;
        if (Math.abs(diff) > 45) {
          goToSlide(diff > 0 ? currentSlide + 1 : currentSlide - 1);
          startAutoSlide();
        }
      }, { passive: true });

      startAutoSlide();

      // 3. Sự kiện lọc sản phẩm
      document.querySelectorAll('.prod-filter-btn').forEach(function (btn) {
        btn.addEventListener('click', function () {
          filterProductKeyword(btn.getAttribute('data-filter'));
        });
      });

      // 4. Sự kiện tìm kiếm trên Header
      document.getElementById('headerSearchForm').addEventListener('submit', function (e) {
        e.preventDefault();
        const q = document.getElementById('headerSearchInput').value.trim().toLowerCase();
        const section = document.getElementById('san-pham-xingfa');
        if (!q) {
          resetProductFilter();
        } else {
          const matched = PRODUCTS.filter(function (p) {
            return p.name.toLowerCase().includes(q) || p.specs.toLowerCase().includes(q);
          });
          renderProducts(matched);
        }
        section.scrollIntoView({ behavior: 'smooth' });
      });

      // 5. Sự kiện lọc danh mục bài viết trang chủ
      document.querySelectorAll('.art-tab-btn').forEach(function (btn) {
        btn.addEventListener('click', function () {
          document.querySelectorAll('.art-tab-btn').forEach(function (b) {
            b.className = 'art-tab-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition';
          });
          btn.className = 'art-tab-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-brand-primary text-white transition';
          renderArticles(btn.getAttribute('data-cat'));
        });
      });

      // 6. Điều khiển menu trượt điện thoại
      const drawer = document.getElementById('mobileDrawer');
      const overlay = document.getElementById('mobileMenuOverlay');

      function openMobileMenu() {
        overlay.classList.remove('hidden');
        requestAnimationFrame(function () {
          overlay.classList.remove('opacity-0');
          drawer.classList.remove('-translate-x-full');
        });
        document.body.style.overflow = 'hidden';
      }

      function closeMobileMenu() {
        overlay.classList.add('opacity-0');
        drawer.classList.add('-translate-x-full');
        setTimeout(function () {
          overlay.classList.add('hidden');
        }, 250);
        document.body.style.overflow = '';
      }

      document.getElementById('mobileMenuOpenBtn').addEventListener('click', openMobileMenu);
      document.getElementById('mobileMenuCloseBtn').addEventListener('click', closeMobileMenu);
      overlay.addEventListener('click', closeMobileMenu);
      document.querySelectorAll('.mobile-nav-close').forEach(function (link) {
        link.addEventListener('click', closeMobileMenu);
      });

      // Accordion menu con trên điện thoại
      document.querySelectorAll('.mobile-accordion-btn').forEach(function (btn) {
        btn.addEventListener('click', function () {
          const panel = btn.nextElementSibling;
          const icon = btn.querySelector('svg');
          panel.classList.toggle('hidden');
          icon.classList.toggle('rotate-180');
        });
      });

      // 7. Đóng Modal
      document.getElementById('modalCloseBtn').addEventListener('click', closeModal);
      document.getElementById('detailModal').addEventListener('click', function (e) {
        if (e.target === this) closeModal();
      });

      // 8. Xử lý gửi Form yêu cầu & báo giá (Hiển thị phản hồi trực tiếp, không dùng alert)
      document.getElementById('quoteForm').addEventListener('submit', function (e) {
        e.preventDefault();
        const name = document.getElementById('qName').value.trim();
        const phone = document.getElementById('qPhone').value.trim();
        const cat = document.getElementById('qCategory').value;
        const feedback = document.getElementById('quoteFeedback');

        if (!name || !phone) {
          feedback.className = 'p-3 rounded-lg text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
          feedback.textContent = 'Vui lòng nhập đầy đủ họ tên và số điện thoại để Thanh Châu liên hệ báo giá.';
          feedback.classList.remove('hidden');
          return;
        }

        feedback.className = 'p-3.5 rounded-lg text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
        feedback.innerHTML = 'Cảm ơn <strong>' + name + '</strong>! Yêu cầu báo giá mục <strong>' + cat + '</strong> đã được ghi nhận. Bộ phận kỹ thuật Nhôm Thanh Châu sẽ liên hệ số <strong>' + phone + '</strong> trong thời gian sớm nhất.';
        feedback.classList.remove('hidden');
        this.reset();
      });
    });
  </script>
</body>
</html>
