<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Speedy Website Development Service</title> 
  <style>
        /* Expensive & Luxurious Color Scheme */
        body {
            background-color: #000000;
            color: #E5E5E5;
            font-family: 'Playfair Display', serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 100px 20px;
        }

        .hero h1 {
            font-size: 48px;
            color: #FFD700;
            letter-spacing: 2px;
        }

        .hero p {
            font-size: 20px;
            font-style: italic;
        }

        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 30px;
            font-size: 18px;
            color: #FFD700;
            border: 2px solid #FFD700;
            background: transparent;
            cursor: pointer;
            transition: all 0.3s ease-in-out;
        }

        .button:hover {
            background: linear-gradient(90deg, #C0C0C0, #FFD700);
            color: black;
        }

        /* Services & Testimonials */
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            max-width: 1000px;
            padding: 50px 20px;
        }

        .card {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-left: 4px solid #FFD700;
        }

        /* Footer */
        .footer {
            text-align: center;
            padding: 20px;
            font-size: 14px;
            color: #C0C0C0;
        }

        .footer a {
            color: #FFD700;
            text-decoration: none;
            transition: color 0.3s;
        }

        .footer a:hover {
            color: #4169E1;
        }

        /* Animated Loading Line */
        .loading-bar {
            position: fixed;
            top: 0;
            left: 0;
            width: 0;
            height: 4px;
            background: #FFD700;
            transition: width 2s ease-in-out;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 36px;
            }
            .hero p {
                font-size: 18px;
            }
        }

        /* Hidden sections for navigation */
        .page {
            display: none;
            padding: 50px 20px;
            text-align: center;
        }

        /* Show active page */
        .active {
            display: block;
        }

        /* Contact Form Styling */
        form {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border: 2px solid #FFD700;
            width: 300px;
            margin: auto;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #FFD700;
            background: transparent;
            color: #FFD700;
            font-size: 16px;
        }

        input::placeholder, textarea::placeholder {
            color: #C0C0C0;
        }

        button[type="submit"] {
            background: #FFD700;
            color: black;
            padding: 12px 20px;
            border: none;
            cursor: pointer;
            font-size: 16px;
            transition: background 0.3s;
        }

        button[type="submit"]:hover {
            background: linear-gradient(90deg, #C0C0C0, #FFD700);
        }
    </style> 
  <script>
        function showPage(pageId) {
            document.querySelectorAll('.page').forEach(page => {
                page.classList.remove('active');
            });
            document.getElementById(pageId).classList.add('active');
        }
    </script> 
 </head> 
 <body onload="document.querySelector('.loading-bar').style.width = '100%';"> 
  <div class="loading-bar"></div> <!-- Navigation --> 
  <nav> <button class="button" onclick="showPage('home')">Home</button> <button class="button" onclick="showPage('about')">About</button> <button class="button" onclick="showPage('contact')">Contact</button> 
  </nav> <!-- Home Page --> 
  <div id="home" class="page active"> 
   <div class="hero"> 
    <h1>Speedy Website Development Service</h1> 
    <p>Ultra-Fast. Ultra-Exclusive.</p> <button class="button" onclick="showPage('contact')">Get Started</button> <button class="button" onclick="showPage('about')">Learn More</button> 
   </div> 
  </div> <!-- About Page --> 
  <div id="about" class="page"> 
   <h1 style="color:#FFD700;">About Us</h1> 
   <p> Speedy Website Development Service is dedicated to crafting high-end, visually stunning, and performance-driven websites. We focus on exclusivity, ensuring that every client receives a unique and luxurious digital experience. Our expert team specializes in minimalist, yet powerful designs that combine speed, efficiency, and premium aesthetics. </p> 
   <p> We understand the value of a website that not only looks great but also delivers seamless performance. That’s why we optimize for ultra-fast loading times and flawless responsiveness, providing an elite experience for your audience. </p> 
   <p> Whether you’re a business looking to establish a premium online presence or an entrepreneur in need of a sophisticated digital platform, our services are tailored to meet your needs with perfection and precision. </p> 
  </div> <!-- Contact Page --> 
  <div id="contact" class="page"> 
   <h1 style="color:#FFD700;">Contact Us</h1> 
   <p>Have questions? Fill out the form below, and we'll get back to you.</p> 
   <form action="mailto:akachukwulivingsoul33@gmail.com" method="POST" enctype="text/plain"> <label for="name">Full Name</label> 
    <br> 
    <input type="text" id="name" name="name" required placeholder="Enter your name"> 
    <br> 
    <br> <label for="email">Email Address</label> 
    <br> 
    <input type="email" id="email" name="email" required placeholder="Enter your email"> 
    <br> 
    <br> <label for="message">Your Message</label> 
    <br> <textarea id="message" name="message" rows="5" required placeholder="Write your message"></textarea> 
    <br> 
    <br> <button type="submit">Send Message</button> 
   </form> 
  </div> <!-- Footer --> 
  <div class="footer"> 
   <p>Contact: <a href="mailto:akachukwulivingsoul33@gmail.com">akachukwulivingsoul33@gmail.com</a></p> 
  </div> 
 </body>
</html>