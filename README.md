- 👋 Hi, I’m @rishavlearner
- 👀 I’m interested in webdevloping
- 🌱 I’m currently learni<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"
        integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
    <header class="header">
        <a href="" class="logo">Portfolio</a>
        <i class="fa-solid fa-bars" id="menu-icon"></i>
        <nav class="navbar">
            <a href="#Home" class="active">Home</a>
            <a href="#about">About</a>
            <a href="#service">Services</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <section class="home" id="home">
        <div class="home-content">
            <h3>Hi, Myself</h3>
            <h1>RISHAV SINGH</h1>
            <h3>And I am a <span>Frontend Engineer</span></h3>
            <p>I am a frontend engineer specializing in HTML, CSS, JavaScript, and Tailwind CSS. I create intuitive web experiences, focusing on clean code, responsive design, and seamless functionality in every project.</p>
            <div class="social-media">
                <a href="https://www.facebook.com/share/1GtWCtYZFp/?mibextid=qi2Omg"><i class="fa-brands fa-facebook"></i></a>
                <a href="#"><i class="fa-brands fa-x-twitter"></i></a>
                <a href="https://github.com/kaustubhlearner"><i class="fa-brands fa-github"></i></a>
                <a href="https://www.linkedin.com/in/kaustubhcreative/"><i class="fa-brands fa-linkedin-in"></i></a>
            </div>
            <a href="./images/tech resume (1) - kaustubh kumar.pdf" class="btn" download="">Download Cv</a>
        </div>
        <div class="home-image">
            <img src="./rishav pic.jpg" alt="">
        </div>
    </section>
    <section class="about" id="about">
        <div class="about-img">
            <img src="./RISHAVKING.jpg" alt="">
        </div>
        <div class="about-content">
            <h2 class="heading">ABOUT <span>me</span></h2>
            <h3>Frontend Engineer</h3>
            <p> A frontend engineer, I wield HTML, CSS, JavaScript, and Tailwind CSS to craft dynamic web experiences that captivate users. My passion lies in blending artistry with technology, creating intuitive interfaces that engage and inspire. I strive for excellence by delivering clean, efficient code and responsive designs, seamlessly merging aesthetics and functionality. Every project I undertake is a canvas where beauty meets performance, ensuring a delightful user journey from start to finish</p>
            <a href="" class="btn">Read More</a>
        </div>
    </section>


    <!-- service section  -->
    <section class="service" id="service">
        <h2 class="heading">My <span>Services</span></h2>

        <div class="service-container">
            <div class="service-box">
                <i class="fa-solid fa-code"></i>
                <h3>Web Development</h3>
                <p>As a web developer, I build and maintain responsive websites by writing clean, efficient code, optimizing performance, and ensuring seamless user interaction across devices and platforms.</p>
                <div class="btn">Read More</div>
            </div>

            <div class="service-box">
                <i class="fa-solid fa-palette"></i>
                <h3>UI/UX Designing</h3>
                <p>As a UI/UX designer, I specialize in creating intuitive, visually appealing user interfaces and enhancing user experiences by balancing functionality, aesthetics.</p>
                <div class="btn">Read More</div>
            </div>

            <div class="service-box">
                <i class="fa-solid fa-arrow-trend-up"></i>
                <h3>Stock Analyst</h3>
                <p>
                    As a stock analyst in India, I analyze market trends, evaluate financial data, and offer insights to
                    help clients make informed investment decisions for better returns and reduced risks.</p>
                <div class="btn">Read More</div>
            </div>
        </div>

    </section>


    <!-- porfolio section  -->
    <section class="portfolio" id="portfolio">
        <h2 class="heading">Latest <span>Projects</span></h2>
        <div class="portfolio-container">
            <div class="portfolio-box">
                <img src="./images/1.jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="./images/2.jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="./images/3.jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="./images/4.jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="./images/5.jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="portfolio-box">
                <img src="./images/6.jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
        </div>
    </section>

<!-- contact section -->

    <section class="contact" id="contact">
<h2 class="heading">Contact <span>Me</span></h2>
<form action="https://sheetdb.io/api/v1/elv51byimfvxh" method="post">
    <div class="input-box">
        <input type="text"placeholder="Full Name" name="data[FULL NAME]">
        <input type="email" placeholder="Email Address" name="data[EMAIL ADDRESS]">
    </div>
    <div class="input-box">
        <input type="number" placeholder="Mobile Number" name="data[MOBILE NUMBER]">
        <input type="text" placeholder="Email Subject" name="data[EMAIL SUBJECT]">
    </div>
    <textarea name="" id="" cols="30" rows="10" placeholder="Your Message"></textarea>
    <input type="submit" name="data[MESSAGE]" value="Send Message" class="btn" >
</form>
    </section>
</body>

</html>
