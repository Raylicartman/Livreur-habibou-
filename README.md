
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/
  <style>
    :root {
      --primary-color: #25D366;
      --secondary-color: #1877F2;
      --tiktok-color: #FE2C55;
      --text-color: #2d3436;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #f5f7fa 0%, #e4e8eb 100%);
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      color: var(--text-color);
    }

    .container {
      background-color: white;
      border-radius: 18px;
      box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
      padding: 40px;
      width: 90%;
      max-width: 450px;
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    .container::before {
      content: '';
      position: absolute;
      top: 0;
      right: 0;
      width: 100%;
      height: 8px;
      background: linear-gradient(90deg, var(--secondary-color), var(--tiktok-color));
    }

    .logo {
      width: 110px;
      height: 110px;
      margin: 10px auto 25px;
      display: block;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid white;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
      background-color: var(--primary-color);
      padding: 5px;
    }

    h1 {
      color: var(--secondary-color);
      margin-bottom: 30px;
      font-size: 28px;
      font-weight: 700;
      letter-spacing: -0.5px;
    }

    .contact-info {
      background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
      padding: 20px;
      border-radius: 12px;
      margin-bottom: 30px;
      box-shadow: inset 0 2px 4px rgba(0,0,0,0.05);
      border: 1px solid rgba(0,0,0,0.05);
    }

    .phone {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 15px;
      font-size: 20px;
      color: var(--text-color);
      font-weight: 600;
    }

    .phone-number {
      unicode-bidi: isolate;
      direction: ltr;
      margin-right: 8px;
    }

    .phone-icon {
      color: var(--primary-color);
      font-size: 28px;
    }

    .whatsapp-btn {
      display: inline-block;
      background-color: var(--primary-color);
      color: white;
      padding: 12px 25px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: 600;
      margin-top: 15px;
      transition: all 0.3s ease;
      box-shadow: 0 4px 15px rgba(37, 211, 102, 0.3);
    }

    .whatsapp-btn:hover {
      transform: translateY(-3px);
      box-shadow: 0 6px 20px rgba(37, 211, 102, 0.4);
    }

    .divider {
      height: 1px;
      background: linear-gradient(90deg, transparent, rgba(0,0,0,0.1), transparent);
      margin: 25px 0;
    }

    .social-links {
      display: flex;
      justify-content: center;
      gap: 25px;
      margin-top: 25px;
    }

    .social-link {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-decoration: none;
      color: var(--text-color);
      transition: all 0.3s ease;
    }

    .social-link:hover {
      transform: translateY(-5px);
    }

    .social-icon {
      width: 55px;
      height: 55px;
      margin-bottom: 10px;
      border-radius: 50%;
      padding: 12px;
      background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
      transition: all 0.3s ease;
    }

    .facebook:hover {
      color: var(--secondary-color);
    }

    .facebook:hover .social-icon {
      background: linear-gradient(135deg, #74b9ff 0%, var(--secondary-color) 100%);
      box-shadow: 0 8px 25px rgba(24, 119, 242, 0.3);
    }

    .tiktok:hover {
      color: var(--tiktok-color);
    }

    .tiktok:hover .social-icon {
      background: linear-gradient(135deg, #25F4EE 0%, var(--tiktok-color) 100%);
      box-shadow: 0 8px 25px rgba(254, 44, 85, 0.3);
    }

    .social-text {
      font-size: 15px;
      font-weight: 500;
      transition: all 0.3s ease;
    }

    .footer {
      margin-top: 35px;
      font-size: 14px;
      color: #636e72;
      line-height: 1.6;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="logo.png" alt="Habibou Livreur" class="logo" />
    <h1>Habibou Livreur</h1>

    <div class="contact-info">
      <div class="phone">
        <span class="phone-icon">📱</span>
        <span class="phone-number">+213 776 85 32 49</span>
      </div>
      <a href="https://wa.me/213776853249" class="whatsapp-btn">تواصل عبر واتساب</a>
    </div>

    <div class="divider"></div>

    <div class="social-links">
      <a href="https://www.facebook.com/share/1EoUoz7hym/" class="social-link facebook" target="_blank" rel="noopener noreferrer">
        <svg class="social-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
          <path fill="currentColor" d="M22.675 0h-21.35c-.732 0-1.325.593-1.325 1.325v21.351c0 .731.593 1.324 1.325 1.324h11.495v-9.294h-3.128v-3.622h3.128v-2.671c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12v9.293h6.116c.73 0 1.323-.593 1.323-1.325v-21.35c0-.732-.593-1.325-1.325-1.325z"/>
        </svg>
        <span class="social-text">فيسبوك</span>
      </a>

      <a href="https://www.tiktok.com/@habibouchoupot?_t=ZM-8wn7xAUTDO9&_r=1" class="social-link tiktok" target="_blank" rel="noopener noreferrer">
        <svg class="social-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
          <path fill="currentColor" d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"/>
        </svg>
        <span class="social-text">تيك توك</span>
      </a>
    </div>

    <div class="footer">
      للتواصل والاستفسارات<br>
      نحن في خدمتكم على مدار الساعة
    </div>
  </div>
</body>
</html>
