# iran-better
ایران بهتر؛ بستری مستقل برای تحلیل، یادداشت و گفت‌وگوی مسئولانه درباره آینده ایران
<!DOCTYPE html>
<html lang="fa-IR" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">

  <title>ایران بهتر — گفت‌وگوی مسئولانه و آگاهانه</title>
  <meta name="description" content="ایران بهتر؛ بستری مستقل، حرفه‌ای و قابل اعتماد برای تحلیل، یادداشت و گفت‌وگوی مدنی.">
  <meta name="robots" content="index, follow">
  <meta name="theme-color" content="#020617">
  <meta name="color-scheme" content="dark light">

  <!-- Open Graph -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="ایران بهتر">
  <meta property="og:title" content="ایران بهتر — گفت‌وگوی مسئولانه و آگاهانه">
  <meta property="og:description" content="فضایی برای تفکر، تحلیل و گفت‌وگوی مسئولانه.">
  <meta property="og:image" content="https://iranbetter.ir/images/og-image.jpg">
  <meta property="og:url" content="https://iranbetter.ir/">
  <meta property="og:locale" content="fa_IR">

  <!-- Twitter -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="ایران بهتر — گفت‌وگوی مسئولانه و آگاهانه">
  <meta name="twitter:description" content="فضایی برای تفکر، تحلیل و گفت‌وگوی مسئولانه.">
  <meta name="twitter:image" content="https://iranbetter.ir/images/og-image.jpg">

  <!-- Font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  
  <!-- Favicon (اضافه شده) -->
  <link rel="icon" type="image/x-icon" href="/favicon.ico">
  <link rel="apple-touch-icon" href="/apple-touch-icon.png">

  <!-- Schema -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebSite",
    "name": "ایران بهتر",
    "url": "https://iranbetter.ir",
    "description": "بستری مستقل، حرفه‌ای و قابل اعتماد برای تحلیل، یادداشت و گفت‌وگوی مدنی",
    "inLanguage": "fa-IR",
    "publisher": {
      "@type": "Organization",
      "name": "ایران بهتر",
      "logo": {
        "@type": "ImageObject",
        "url": "https://iranbetter.ir/logo.png"
      }
    }
  }
  </script>

  <style>
    :root {
      --bg: #020617;
      --surface: #0f172a;
      --surface-secondary: #1e293b;
      --border: #334155;
      --text: #f8fafc;
      --muted: #94a3b8;
      --accent: #3b82f6;
      --radius: 22px;
      --shadow: 0 24px 70px rgba(0, 0, 0, 0.45);
      --transition: 0.3s ease;
    }

    [data-theme="light"] {
      --bg: #f8fafc;
      --surface: #ffffff;
      --surface-secondary: #f1f5f9;
      --border: #e2e8f0;
      --text: #0f172a;
      --muted: #64748b;
      --shadow: 0 24px 70px rgba(0, 0, 0, 0.08);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Vazirmatn, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.8;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      transition: background-color var(--transition), color var(--transition);
    }

    header {
      position: sticky;
      top: 0;
      z-index: 100;
      background: rgba(2, 6, 23, 0.9);
      backdrop-filter: blur(16px);
      border-bottom: 1px solid var(--border);
      transition: background-color var(--transition), border-color var(--transition);
    }

    [data-theme="light"] header {
      background: rgba(255, 255, 255, 0.95);
    }

    .nav {
      max-width: 1280px;
      margin: 0 auto;
      padding: 1rem 1.5rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 1rem;
    }

    .brand {
      font-size: 1.5rem;
      font-weight: 800;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    nav ul {
      display: flex;
      gap: 1.5rem;
      list-style: none;
    }

    nav a {
      color: var(--muted);
      text-decoration: none;
      padding: 0.5rem 0;
      position: relative;
      transition: color var(--transition);
    }

    nav a:hover {
      color: var(--text);
    }

    nav a[aria-current="page"] {
      color: var(--text);
      font-weight: 600;
    }

    nav a[aria-current="page"]::after {
      content: '';
      position: absolute;
      bottom: 0;
      right: 0;
      width: 100%;
      height: 2px;
      background-color: var(--accent);
      border-radius: 2px;
    }

    #theme-toggle {
      background: var(--surface-secondary);
      border: 1px solid var(--border);
      border-radius: 50%;
      width: 44px;
      height: 44px;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      font-size: 1.2rem;
      color: var(--text);
      transition: background-color var(--transition), border-color var(--transition);
    }

    #theme-toggle:hover {
      background: var(--surface);
    }

    main {
      max-width: 1280px;
      margin: 0 auto;
      padding: 4rem 1.5rem;
      flex: 1;
      width: 100%;
    }

    .card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 3rem;
      box-shadow: var(--shadow);
      margin-bottom: 3rem;
      transition: background-color var(--transition), border-color var(--transition), box-shadow var(--transition);
    }

    .card h2 {
      margin-bottom: 1.5rem;
      font-size: 2rem;
      color: var(--text);
    }

    .card p {
      color: var(--muted);
      font-size: 1.1rem;
      max-width: 65ch;
    }

    footer {
      text-align: center;
      padding: 3rem 1.5rem;
      background: var(--surface-secondary);
      border-top: 1px solid var(--border);
      color: var(--muted);
      transition: background-color var(--transition), border-color var(--transition), color var(--transition);
    }

    /* بهبودهای ریسپانسیو */
    @media (max-width: 768px) {
      .nav {
        flex-direction: column;
        text-align: center;
        padding: 1rem;
      }
      
      nav ul {
        flex-wrap: wrap;
        justify-content: center;
        gap: 1rem;
      }
      
      .card {
        padding: 2rem 1.5rem;
      }
      
      main {
        padding: 2rem 1rem;
      }
    }

    @media (max-width: 480px) {
      .brand {
        font-size: 1.25rem;
      }
      
      .card {
        padding: 1.5rem 1rem;
      }
      
      .card h2 {
        font-size: 1.75rem;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      * {
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: 0.01ms !important;
        scroll-behavior: auto !important;
      }
    }
    
    /* بهبود دسترسی برای فوکوس */
    :focus-visible {
      outline: 2px solid var(--accent);
      outline-offset: 3px;
      border-radius: 4px;
    }
    
    /* بهبود خوانایی برای users با تنظیمات خاص */
    @media (prefers-contrast: high) {
      :root {
        --border: #000000;
      }
    }
  </style>
</head>

<body>

<header>
  <div class="nav">
    <h1 class="brand">
      <span aria-hidden="true">🇮🇷</span>
      <span>ایران بهتر</span>
    </h1>
    <nav aria-label="منوی اصلی">
      <ul>
        <li><a href="#about" aria-current="page">درباره</a></li>
        <li><a href="#posts">نوشته‌ها</a></li>
        <li><a href="#contact">تماس</a></li>
      </ul>
    </nav>
    <button id="theme-toggle" type="button" aria-label="تغییر تم تاریک/روشن">🌙</button>
  </div>
</header>

<main>
  <section id="about" class="card" aria-labelledby="about-heading">
    <h2 id="about-heading">درباره ما</h2>
    <p>ایران بهتر بستری برای گفت‌وگوی مسئولانه و آینده‌نگر است. ما به دنبال ایجاد فضایی برای تفکر عمیق، تحلیل بی‌طرفانه و گفت‌وگوی سازنده میان شهروندان هستیم تا با همفکری و تبادل نظر، تصویری روشن‌تر از آینده ایران ترسیم کنیم.</p>
  </section>
  
  <!-- بخش‌های اضافه شده برای کامل‌تر شدن ساختار -->
  <section id="posts" class="card" aria-labelledby="posts-heading" style="display: none;">
    <h2 id="posts-heading">آخرین نوشته‌ها</h2>
    <p>به زودی مطالب جدید در این بخش منتشر خواهد شد.</p>
  </section>
  
  <section id="contact" class="card" aria-labelledby="contact-heading" style="display: none;">
    <h2 id="contact-heading">تماس با ما</h2>
    <p>برای ارتباط با تیم ایران بهتر، از طریق ایمیل یا شبکه‌های اجتماعی با ما در تماس باشید.</p>
  </section>
</main>

<footer>
  <p>© ۱۴۰۲–۱۴۰۵ — ایران بهتر. تمامی حقوق محفوظ است.</p>
  <p style="margin-top: 0.5rem; font-size: 0.9rem;">ایده‌پردازی، تحلیل و گفت‌وگوی سازنده برای آینده‌ای بهتر</p>
</footer>

<script defer>
  // ذخیره و بارگذاری تم انتخابی کاربر
  const themeToggle = document.getElementById('theme-toggle');
  const prefersDarkScheme = window.matchMedia('(prefers-color-scheme: dark)');
  const currentTheme = localStorage.getItem('theme');
  
  // تنظیم تم اولیه
  if (currentTheme) {
    document.documentElement.setAttribute('data-theme', currentTheme);
  } else if (prefersDarkScheme.matches) {
    document.documentElement.setAttribute('data-theme', '');
  } else {
    document.documentElement.setAttribute('data-theme', 'light');
  }
  
  // به‌روزرسانی آیکون دکمه تم
  function updateThemeButton() {
    const isLight = document.documentElement.getAttribute('data-theme') === 'light';
    themeToggle.textContent = isLight ? '🌙' : '☀️';
    themeToggle.setAttribute('aria-label', isLight ? 'تغییر به تم تاریک' : 'تغییر به تم روشن');
  }
  
  // تغییر تم
  themeToggle.onclick = () => {
    const currentTheme = document.documentElement.getAttribute('data-theme');
    const newTheme = currentTheme === 'light' ? '' : 'light';
    
    document.documentElement.setAttribute('data-theme', newTheme);
    localStorage.setItem('theme', newTheme);
    updateThemeButton();
  };
  
  // نمایش بخش‌های دیگر هنگام کلیک روی منو
  document.querySelectorAll('nav a').forEach(link => {
    link.addEventListener('click', function(e) {
      if (this.getAttribute('href').startsWith('#')) {
        e.preventDefault();
        const targetId = this.getAttribute('href').substring(1);
        const targetSection = document.getElementById(targetId);
        
        // مخفی کردن همه بخش‌ها
        document.querySelectorAll('main > section').forEach(section => {
          section.style.display = 'none';
        });
        
        // نمایش بخش هدف
        if (targetSection) {
          targetSection.style.display = 'block';
          targetSection.scrollIntoView({ behavior: 'smooth' });
        }
        
        // به‌روزرسانی وضعیت لینک فعال
        document.querySelectorAll('nav a').forEach(a => {
          a.removeAttribute('aria-current');
        });
        this.setAttribute('aria-current', 'page');
      }
    });
  });
  
  // مقداردهی اولیه دکمه تم
  updateThemeButton();
  
  // نمایش بخش about به صورت پیش‌فرض
  document.getElementById('about').style.display = 'block';
</script>

</body>
</html>
