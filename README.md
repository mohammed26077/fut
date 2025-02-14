<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Powered Future</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <style>
        
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #000000;
            color: #fff;
            overflow-x: hidden;
            padding-top: 120px; 
        }

        
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background-color: rgb(0, 0, 0);
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 200; 
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #fff;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        .nav-links li a {
            text-decoration: none;
            color: #fff;
            font-size: 16px;
            transition: color 0.3s;
        }

        .nav-links li a:hover {
            color: #00ffff;
        }

/* Custom Section for Moving Image */
.animated-section {
    position: relative;
    width: 100%;
    overflow: hidden;
    background-color: #1a1a1a;
}

.main-image {
    width: 100%;
    display: block;
}

.image-row {
    position: absolute;
    top: 10%; /* مركز الصورة الرئيسية */
    left: 50%;
    transform: translate(-50%, -50%);
    display: flex;
    justify-content: center;
    width: 100%;
}

.image-row img {
    position: absolute; /* السماح بالتحكم في المكان بشكل منفصل */
    width: 100%;
    max-width: 1000px; /* تحديد أقصى عرض للصورة */
    border-radius: 10px;
    transition: transform 0.3s;
}

.image-row img:nth-child(1) {
    left: -300px; /* التحكم في موقع الصورة الأولى */
}

.image-row img:nth-child(2) {
    left: 100; /* الصورة الثانية في المنتصف */
}

.image-row img:nth-child(3) {
    left: 700px; /* التحكم في موقع الصورة الثالثة */
}
  <style>
    body, html {
      margin: 0;
      padding: 0;
      height: 100%;
      width: 100%;
      overflow-y: scroll; /* السماح بالتمرير عموديًا */
    }

    body {
      font-family: Arial, sans-serif;
      background: #000000;
      color: rgb(255, 255, 255);
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 100%;
      padding-bottom: 0px; /* إضافة مساحة إضافية أسفل الصفحة للتمرير */
    }


        @keyframes float {
            0%, 100% {
                transform: translateY(-10px);
            }
            50% {
                transform: translateY(10px);
            }
        }

    /* الكروت جنب بعض */
    .card-container {
      display: flex;
      justify-content: center;
      gap: 30px;
      z-index: 1;
      opacity: 0;
      animation: fadeCards 0s forwards;
      animation-delay: 0s;
      position: relative;
      top: -100%;
      left: 50%;
      transform: translateX(-50%);
      width: 100%;
      justify-content: space-evenly;
    }

    @keyframes fadeCards {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    .card {
      background-color: #292b2c;
      color: white;
      padding: 20px;
      border-radius: 10px;
      width: 300px;
      height: 300px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      box-shadow: 0 4px 6px rgba(255, 255, 255, 0.682);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 10px;
    }

    .card h3 {
      font-size: 1.5rem;
      margin-bottom: 10px;
    }

    .card p {
      font-size: 1rem;
    }

        /* Hero Section */
        .hero {
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 100vh;
            padding: 100px 50px 50px;
            background: linear-gradient(to right, #000, #000000);
        }

        .hero-content {
            max-width: 50%;
        }

        .hero-content h1 {
            font-size: 48px;
            margin-bottom: 20px;
            line-height: 1.2;
        }

        .hero-content h1 span {
            color: #00ffff;
            font-weight: bold;
        }

        .hero-content p {
            font-size: 18px;
            margin-bottom: 30px;
            line-height: 1.6;
            color: #ccc;
        }

        .cta-button {
            padding: 15px 30px;
            font-size: 16px;
            background-color: #00ffff;
            color: #000;
            border: none;
            cursor: pointer;
            transition: background 0.3s, transform 0.3s;
        }

        .cta-button:hover {
            background-color: #00bfbf;
            transform: scale(1.1);
        }

        .robot-image img {
            max-width: 800px;
        }
    .card-btn {
      padding: 10px 20px;
      background-color: #1644a2;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .card-btn:hover {
      background-color: #1e74d0;
    }
    /* الكود المتبقي كما هو */
  </style>

  <title>my design</title>
  <style>
    /* إضافة التنسيق الخاص بالأزرار */
    .card-btn {
      padding: 10px 20px;
      background-color: #00ffff;
      color: rgb(0, 0, 0);
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    .moving-text {
    position: absolute;
    top: 230%; /* التحكم بمكان النص (يمكنك تغييره) */
    left: 100%; /* النص يبدأ خارج الشاشة من اليمين */
    white-space: nowrap; /* منع التفاف النص */
    font-size: 50px;
    color: #ffffff;
    animation: moveText 15s linear infinite; /* الحركة المتكررة */
}

@keyframes moveText {
    0% {
        left: 100%;
    }
    100% {
        left: -100%; /* النص يختفي من الجهة اليسرى */
    }
}

    .card-btn:hover {
      background-color: #1e74d0;
    }
    /* الكود المتبقي كما هو */
  </style>

    </style>
</head>
<body>
    <body>
        <!-- إضافة الموسيقى -->
        <audio id="backgroundMusic" loop>
            <source src="/Users/mohamedahmed/Downloads/Robert Miles - Children [Dream Version] (Extended).mp4" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    
        <!-- زر التحكم -->
        <div style="position: fixed; bottom: 700px; right: 20px; z-index: 100;">
            <button id="toggleButton" style="padding: 10px 20px; background-color: #00ffff; border: none; cursor: pointer;">Play</button>
        </div>
    
    <!-- Navigation Bar -->
    <nav class="navbar">
        <div class="logo">AI - Powered FUTURE</div>
        <ul class="nav-links">
            <li><a href="#">Services</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Careers</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Contact Us</a></li>
        </ul>
    </nav>
    
    <!-- Script للتحكم -->
    <script>
        const music = document.getElementById('backgroundMusic');
        const toggleButton = document.getElementById('toggleButton');

        toggleButton.addEventListener('click', () => {
            if (!music.paused) {
                // إذا كانت الموسيقى تعمل، يتم إيقافها
                music.pause();
                music.currentTime = 0; // إعادة مؤشر التشغيل إلى البداية
                toggleButton.textContent = 'Play';
            } else {
                // إذا كانت الموسيقى متوقفة، يتم تشغيلها من البداية
                music.play();
                toggleButton.textContent = 'Pause';
            }
        });
    </script>
</body>
<!DOCTYPE html>
<html lang="ar">
<head>
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقعك</title>
</head>
<body>
    <!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صورة داخل صورة مع تحكم بالحجم</title>
    <style>
        body {
            margin: 0;
            padding: 0;
        }
        .image-container {
            position: relative;
            width: 100%;
            max-width: 1450px;
            margin: 0 auto;
            overflow: hidden; /* للتأكد من عدم تجاوز أي عناصر الحدود */
        }
        .image-container img {
            width: 100%;
            display: block;
        }

        /* إعدادات الصورة الثانوية */
        .overlay-image {
            position: absolute;
            top: 65%; /* وضع الصورة الثانوية في منتصف الصورة الرئيسية */
            left: 70%;
            transform: translate(-50%, -50%); /* لضمان التمركز */
            width: 35% !important; /* التأكيد على التطبيق */
            height: auto !important; /* الارتفاع يتناسب مع العرض */
            opacity: 0.7; /* الشفافية */
            z-index: 1;
            animation: fadeInUp 2s ease-in-out forwards; /* نفس الأنيميشن */
        }

        .image-container .text-overlay {
            position: absolute;
            top: 55%;
            left: 30%;
            transform: translate(-50%, 60%);
            color: white;
            font-size: 40px;
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            text-align: center;
            opacity: 0;
            animation: fadeInUp 2s ease-in-out forwards;
            z-index: 2; /* النص فوق الصورة الثانوية */
            line-height: 1.5;
        }

        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translate(-50%, -20%);
            }
            100% {
                opacity: 1;
                transform: translate(-50%, -50%);
            }
        }
    </style>
</head>
<body>
    
    <div class="image-container">
        <img src="/Users/mohamedahmed/Desktop/DALL·E 2024-12-27 00.51.46 - A dark night space background with minimal colors, featuring a subtle scattering of faint stars across a black sky. The scene should feel calm and sim copy.png" alt="الصورة الرئيسية">
        
        <!-- صورة إضافية أمام الصورة الرئيسية -->
        <img class="overlay-image" src="/Users/mohamedahmed/Desktop/IMG_F79D4F917DC6-1 copy.png" alt="الصورة الثانوية">
        
        <div class="text-overlay">
            In this website<br>
            we will explore<br>
            artificial intelligence<br>
            its importance<br>
            and its applications
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>خطين رأسيين أبيض مع Top و Left</title>
    <style>
        body {
            background-color: black; /* خلفية سوداء */
            color: white;
            text-align: center;
        }

        .vertical-line {
            width: 2px; /* عرض الخط */
            height: 100px; /* طول الخط */
            background-color: white; /* لون الخط */
            margin: 20px auto; /* توسيط الخط */
            position: absolute; /* تمكين التحكم في position */
            opacity: 0; /* الخطوط مخفية في البداية */
            animation: fadeIn 2s forwards; /* تطبيق الأنميشن للظهور */
        }

        /* الأنميشن لجعل الخطوط تظهر بعد 3 ثوانٍ */
        @keyframes fadeIn {
            0% {
                opacity: 0; /* مخفي في البداية */
            }
            100% {
                opacity: 1; /* يظهر تدريجيًا */
            }
        }

        /* تأخير الأنميشن بعد 3 ثوانٍ لكل خط */
        .line-1 {
            top: 50px; /* المسافة من الأعلى */
            left: 425px; /* المسافة من اليسار */
            animation-delay: 2s; /* تأخير الخط الأول بعد 3 ثوانٍ */
        }

        .line-2 {
            top: 478px; /* المسافة من الأعلى */
            left: 425px; /* المسافة من اليسار */
            animation-delay: 2s; /* تأخير الخط الثاني بعد 3 ثوانٍ */
        }
    </style>
</head>
<body>

    <!-- الخط الأول -->
    <div class="vertical-line line-1"></div>
    
    <!-- الخط الثاني -->
    <div class="vertical-line line-2"></div>
</body>
</html>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h1>AI - Powered <span>FUTURE</span></h1>
            <p>Experience the vast and limitless opportunities that AI brings, empowering individuals and organizations to achieve unprecedented levels of innovation and success.</p>
            <button class="cta-button">Let's Start</button>
        </div>
        <div class="robot-image">
            <img src="/Users/mohamedahmed/Desktop/untitled1 copy 2.png" alt="AI Robot">
        </div>
    </section>
</body>
</html>

<!-- الكروت هنا -->
<div class="card-container">
    <!-- كارت 1 مع نص وزرار -->
    <div class="card">
      <img src="/Users/mohamedahmed/Downloads/IMG_5603.JPG" alt="صورة كارت 1">
      <h3>ANOUT AI</h3>
      <p>CILCK HERE TO LEARN MOER</p>
      <button class="card-btn" onclick="alert('تم الضغط على الزر 1!')">CILCK HERE </button>
    </div>
  
    <!-- كارت 2 مع نص وزرار -->
    <div class="card">
      <img src="/Users/mohamedahmed/Downloads/IMG_5604.JPG" alt="صورة كارت 2">
      <h3>TEACHING AI</h3>
      <p>CILCK HERE TO LEARN MOER</p>
      <button class="card-btn" onclick="alert('تم الضغط على الزر 2!')">CILCK HERE </button>
    </div>
  
    <!-- كارت 3 مع نص وزرار -->
    <div class="card">
      <img src="/Users/mohamedahmed/Downloads/DALL·E 2024-12-24 16.16.29 - A visually stunning abstract design composed of two complementary colors (e.g., blue and white) with a technology theme. The image should feature slee.webp" alt="صورة كارت 3">
      <h3>WHY AI</h3>
      <p>CILCK HERE TO LEARN MOER </p>
      <button class="card-btn" onclick="alert('تم الضغط على الزر 3!')">CILCK HERE </button>
    </div>
  </div>
  <!DOCTYPE html>
  <html lang="en">
  <head>      <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقعك</title>
    <style>
        hr {
            border: 0;
            border-top: 2px solid black;
            margin: 20px 0;
        }
    </style>
</head>
<body>

    <hr> <!-- المسافة الصغيرة السودة -->

</body>
</html>

        <!-- Custom Animated Section -->
        <section class="animated-section">
            <!-- Main Animated Image -->
            <img src="/Users/mohamedahmed/Desktop/DALL·E 2024-12-27 00.51.46 - A dark night space background with minimal colors, featuring a subtle scattering of faint stars across a black sky. The scene should feel calm and sim.jpeg" alt="Moving Background" class="main-image">
            
            <!-- Three Images Row inside the main image -->
            <div class="image-row">
                <img src="/Users/mohamedahmed/Desktop/Screenshot 2024-12-24 at 2.58.29 AM copy.png" alt="Image 1">
                <img src="/Users/mohamedahmed/Desktop/Screenshot 2024-12-24 at 2.58.16 AM copy.png" alt="Image 2">
                <img src="/Users/mohamedahmed/Desktop/Screenshot 2024-12-24 at 2.57.58 AM copy.png" alt="Image 3">
            </div>
        </section>
        
    <!-- النص المتحرك -->
    <div class="moving-text" id="movingText">Welcome to the AI Powered Future</div>
    
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Chat Bot</title>
      <style>
          /* زر الشات المدور */
          #chatButton {
              position: fixed;
              bottom: 20px;
              right: 20px;
              width: 50px;
              height: 50px;
              background-color: #00ffd5;
              color: rgb(0, 0, 0);
              border-radius: 50%;
              border: none;
              font-size: 24px;
              cursor: pointer;
              box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
              transition: background-color 0.3s;
          }
  
          #chatButton:hover {
              background-color: #484747;
          }
  
          /* نافذة الشات بوت */
          #chatbot-container {
              position: fixed;
              bottom: 80px;
              right: 20px;
              width: 300px;
              height: 400px;
              background-color: #000000;
              border: 2px solid #ccc;
              border-radius: 10px;
              display: none; /* يبدأ مخفي */
              flex-direction: column;
              box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
              z-index: 1000;
          }
  
          #chatbot-header {
              background-color: #00ffea;
              color: rgb(0, 0, 0);
              padding: 10px;
              text-align: center;
              font-size: 18px;
              font-weight: bold;
              border-top-left-radius: 10px;
              border-top-right-radius: 10px;
          }
  
          #chatbot-messages {
              flex-grow: 1;
              padding: 10px;
              overflow-y: auto;
              font-size: 14px;
          }
  
          #chatbot-input-container {
              display: flex;
              border-top: 1px solid #000000;
          }
  
          #chatbot-input {
              flex-grow: 1;
              padding: 10px;
              font-size: 14px;
              border: none;
              outline: none;
          }
  
          #chatbot-send {
              padding: 10px;
              background-color: #00ffc8;
              color: rgb(0, 0, 0);
              border: none;
              cursor: pointer;
              outline: none;
          }
  
          #chatbot-send:hover {
              background-color: #555454;
          }
      </style>
  </head>
  <body>
  
  <!-- زر الشات -->
  <button id="chatButton">💬</button>
  
  <!-- نافذة الشات بوت -->
  <div id="chatbot-container">
      <div id="chatbot-header">MOHAMMED</div>
      <div id="chatbot-messages"></div>
      <div id="chatbot-input-container">
          <input type="text" id="chatbot-input" placeholder="Type a message...">
          <button id="chatbot-send">Send</button>
      </div>
  </div>
  
  <script>
      // إظهار وإخفاء الشات بوت عند الضغط على الزر
      const chatButton = document.getElementById('chatButton');
      const chatbotContainer = document.getElementById('chatbot-container');
  
      chatButton.addEventListener('click', () => {
          if (chatbotContainer.style.display === 'none' || chatbotContainer.style.display === '') {
              chatbotContainer.style.display = 'flex'; // إظهار الشات بوت
          } else {
              chatbotContainer.style.display = 'none'; // إخفاء الشات بوت
          }
      });
  
      // وظائف الشات بوت
      const messagesContainer = document.getElementById('chatbot-messages');
      const inputField = document.getElementById('chatbot-input');
      const sendButton = document.getElementById('chatbot-send');
  
      // استجابات الشات بوت
      const responses = {
          مرحبا: "Hi there! How can I help you today?",
          ساعدني: "Sure! Let me know your question.",
          باي: "Goodbye! Have a great day.",
          default: "send me massage in gmail m09649380@gmail.com"
      };
  
      // إرسال الرسالة
      function sendMessage() {
          const userMessage = inputField.value.trim().toLowerCase();
          if (userMessage === "") return;
  
          // عرض رسالة المستخدم
          displayMessage(`You: ${inputField.value}`, "user");
  
          // تحديد استجابة الشات بوت
          const botResponse = responses[userMessage] || responses.default;
  
          // عرض استجابة الشات بوت
          setTimeout(() => {
              displayMessage(`Bot: ${botResponse}`, "bot");
          }, 500);
  
          inputField.value = ""; // مسح حقل الإدخال
      }
  
      // عرض الرسالة في نافذة الشات
      function displayMessage(message, sender) {
          const messageElement = document.createElement('div');
          messageElement.textContent = message;
          messageElement.style.margin = "7px 0";
          if (sender === "bot") {
              messageElement.style.color = "ORANGE";
          }
          messagesContainer.appendChild(messageElement);
          messagesContainer.scrollTop = messagesContainer.scrollHeight; // التمرير التلقائي
      }
  
      // مستمعو الأحداث
      sendButton.addEventListener('click', sendMessage);
      inputField.addEventListener('keypress', (e) => {
          if (e.key === 'Enter') sendMessage();
      });
  </script>
  <!DOCTYPE html>
  <html lang="ar">
  <head>


  </body>
  </html>
  <!-- Footer Section -->
<footer style="background-color: #4e4e4e; color: white; text-align: center; padding: 20px 40px; margin-top: 0px; width: 100%; margin-left: auto; margin-right: auto; border-radius: 10px;">
    <!-- Social Media Links -->
    <div>
        <a href="https://www.facebook.com/share/1LMCiMdqkM/?mibextid=wwXIfr" target="_blank" style="color: white; margin: 0 10px; text-decoration: none;">Facebook</a>
        <a href="https://www.instagram.com/_mo7amed_ahmeed_/profilecard/?igsh=MWYxa2RubnpmcmV6NQ==" target="_blank" style="color: white; margin: 0 10px; text-decoration: none;">Instagram</a>
    </div>

    <!-- Copyright -->
    <div style="margin-top: 10px;">
        © 2024 All rights reserved. AND
        BY: MOHAMED AHMED RASHAD
    </div>
</footer>
