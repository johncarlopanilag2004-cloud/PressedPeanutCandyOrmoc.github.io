<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Pressed Peanut Candy | Ormoc City</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #fffaf0;
        }

        /* NAVIGATION */
        header {
            background-color: #6b3e26;
            color: white;
            padding: 15px 8%;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 22px;
            font-weight: bold;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 25px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffd166;
        }

        /* HERO */
        .hero {
            min-height: 90vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 50px 8%;
            background-color: #8b5435;
            color: white;
        }

        .hero-content {
            max-width: 750px;
        }

        .hero h1 {
            font-size: 55px;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 30px;
        }

        .button {
            display: inline-block;
            padding: 13px 25px;
            background-color: #ffd166;
            color: #4a2a19;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
            transition: 0.3s;
        }

        .button:hover {
            transform: scale(1.05);
            background-color: white;
        }

        /* GENERAL SECTIONS */
        section {
            padding: 70px 8%;
        }

        .section-title {
            text-align: center;
            margin-bottom: 40px;
        }

        .section-title h2 {
            color: #6b3e26;
            font-size: 35px;
            margin-bottom: 10px;
        }

        .section-title p {
            color: #666;
        }

        /* ABOUT */
        .about {
            max-width: 900px;
            margin: auto;
        }

        .about-text h3 {
            color: #6b3e26;
            font-size: 28px;
            margin-bottom: 15px;
        }

        .about-text p {
            margin-bottom: 15px;
        }

        /* PRODUCT */
        .product-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .card {
            background-color: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card-icon {
            font-size: 45px;
            margin-bottom: 15px;
        }

        .card h3 {
            color: #6b3e26;
            margin-bottom: 10px;
        }

        /* PROCESS */
        .process {
            background-color: #f5e6cc;
        }

        .process-container {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
        }

        .process-step {
            background-color: white;
            padding: 25px;
            text-align: center;
            border-radius: 15px;
        }

        .step-number {
            width: 50px;
            height: 50px;
            margin: 0 auto 15px;
            border-radius: 50%;
            background-color: #6b3e26;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 20px;
            font-weight: bold;
        }

        .process-step h3 {
            color: #6b3e26;
            margin-bottom: 10px;
        }

        /* BENEFITS */
        .benefits {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        /* PRODUCT DETAILS */
        .details {
            background-color: white;
        }

        .details-container {
            max-width: 900px;
            margin: auto;
        }

        .detail-row {
            display: flex;
            justify-content: space-between;
            padding: 15px 20px;
            border-bottom: 1px solid #ddd;
        }

        .detail-row strong {
            color: #6b3e26;
        }

        /* CTA */
        .cta {
            background-color: #6b3e26;
            color: white;
            text-align: center;
        }

        .cta h2 {
            font-size: 35px;
            margin-bottom: 15px;
        }

        .cta p {
            margin-bottom: 25px;
        }

        /* FOOTER */
        footer {
            background-color: #3b2417;
            color: white;
            text-align: center;
            padding: 25px;
        }

        footer p {
            margin: 5px;
        }

        /* MOBILE */
        @media (max-width: 768px) {

            nav {
                flex-direction: column;
                gap: 15px;
            }

            nav ul {
                gap: 12px;
                flex-wrap: wrap;
                justify-content: center;
            }

            .hero h1 {
                font-size: 40px;
            }

            .hero p {
                font-size: 17px;
            }

            .product-container {
                grid-template-columns: 1fr;
            }

            .process-container {
                grid-template-columns: 1fr;
            }

            .benefits {
                grid-template-columns: 1fr;
            }

            .detail-row {
                flex-direction: column;
                gap: 5px;
            }
        }
    </style>
</head>

<body>

    <!-- NAVIGATION -->
    <header>
        <nav>
            <div class="logo">🥜 Pressed Peanut Candy</div>

            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#product">Product</a></li>
                <li><a href="#process">Process</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>


    <!-- HERO SECTION -->
    <section class="hero" id="home">

        <div class="hero-content">

            <h1>Pressed Peanut Candy</h1>

            <p>
                A simple and delicious peanut-based treat,
                carefully pressed into a convenient individual serving.
            </p>

            <a href="#product" class="button">
                Discover Our Product
            </a>

        </div>

    </section>


    <!-- ABOUT SECTION -->
    <section id="about">

        <div class="section-title">
            <h2>About Our Product</h2>
            <p>A simple snack made with carefully selected ingredients.</p>
        </div>

        <div class="about">

            <div class="about-text">

                <h3>What is Pressed Peanut Candy?</h3>

                <p>
                    Pressed Peanut Candy is a peanut-based snack made from
                    roasted red peanuts, sugar, and salt. The peanuts are
                    processed into a fine, powdery-like consistency before
                    being pressed into a compact shape.
                </p>

                <p>
                    The finished product is individually packaged to provide
                    convenience, cleanliness, and easier handling for
                    consumers.
                </p>

                <p>
                    The product is intended for consumers in Ormoc City,
                    Leyte who are looking for a simple and convenient
                    peanut-based snack.
                </p>

            </div>

        </div>

    </section>


    <!-- PRODUCT FEATURES -->
    <section id="product">

        <div class="section-title">

            <h2>Our Product</h2>

            <p>
                Simple ingredients. Convenient packaging.
                Enjoyable snack.
            </p>

        </div>

        <div class="product-container">

            <div class="card">

                <div class="card-icon">🥜</div>

                <h3>Roasted Peanuts</h3>

                <p>
                    Red peanuts are roasted before processing
                    to prepare them for production.
                </p>

            </div>


            <div class="card">

                <div class="card-icon">🍬</div>

                <h3>Pressed Form</h3>

                <p>
                    The processed peanut mixture is pressed
                    using a cylindrical mold to create its shape.
                </p>

            </div>


            <div class="card">

                <div class="card-icon">📦</div>

                <h3>Individual Packaging</h3>

                <p>
                    Each piece is individually packaged for
                    convenience, cleanliness, and protection.
                </p>

            </div>

        </div>

    </section>


    <!-- MANUFACTURING PROCESS -->
    <section class="process" id="process">

        <div class="section-title">

            <h2>Manufacturing Process</h2>

            <p>
                From roasted peanuts to individually packaged candy.
            </p>

        </div>


        <div class="process-container">

            <div class="process-step">

                <div class="step-number">1</div>

                <h3>Roasting</h3>

                <p>
                    Red peanuts are roasted properly before
                    proceeding to the next stage.
                </p>

            </div>


            <div class="process-step">

                <div class="step-number">2</div>

                <h3>Blending</h3>

                <p>
                    The roasted peanuts are blended until they
                    reach a powdery-like consistency.
                </p>

            </div>


            <div class="process-step">

                <div class="step-number">3</div>

                <h3>Pressing</h3>

                <p>
                    The processed peanut mixture is placed
                    into a cylindrical mold and pressed.
                </p>

            </div>


            <div class="process-step">

                <div class="step-number">4</div>

                <h3>Packaging</h3>

                <p>
                    Finished pieces are individually packaged
                    to protect the product.
                </p>

            </div>

        </div>

    </section>


    <!-- BENEFITS -->
    <section>

        <div class="section-title">

            <h2>Product Benefits</h2>

            <p>
                Designed with convenience and consumer needs in mind.
            </p>

        </div>


        <div class="benefits">

            <div class="card">

                <div class="card-icon">✨</div>

                <h3>Convenient</h3>

                <p>
                    Individual packaging makes the product
                    easy to carry and consume.
                </p>

            </div>


            <div class="card">

                <div class="card-icon">🥜</div>

                <h3>Peanut-Based</h3>

                <p>
                    Made primarily from roasted red peanuts,
                    combined with sugar and salt.
                </p>

            </div>


            <div class="card">

                <div class="card-icon">💰</div>

                <h3>Accessible Snack</h3>

                <p>
                    A simple snack concept intended to provide
                    an affordable option for consumers.
                </p>

            </div>

        </div>

    </section>


    <!-- PRODUCT SPECIFICATIONS -->
    <section class="details">

        <div class="section-title">

            <h2>Product Specifications</h2>

            <p>Basic characteristics of Pressed Peanut Candy.</p>

        </div>


        <div class="details-container">

            <div class="detail-row">
                <strong>Product Name</strong>
                <span>Pressed Peanut Candy</span>
            </div>

            <div class="detail-row">
                <strong>Main Ingredient</strong>
                <span>Roasted Red Peanuts</span>
            </div>

            <div class="detail-row">
                <strong>Other Ingredients</strong>
                <span>Sugar and Salt</span>
            </div>

            <div class="detail-row">
                <strong>Form</strong>
                <span>Pressed / Molded</span>
            </div>

            <div class="detail-row">
                <strong>Packaging</strong>
                <span>Individual Packaging</span>
            </div>

            <div class="detail-row">
                <strong>Target Market</strong>
                <span>Consumers in Ormoc City, Leyte</span>
            </div>

        </div>

    </section>


    <!-- CONTACT / CTA -->
    <section class="cta" id="contact">

        <h2>Try Pressed Peanut Candy</h2>

        <p>
            A simple peanut-based treat made for convenient snacking.
        </p>

        <a href="mailto:pressedpeanutcandy69@gmail.com" class="button">
            Contact Us
        </a>

    </section>


    <!-- FOOTER -->
    <footer>

        <p>
            <strong>Pressed Peanut Candy</strong>
        </p>

        <p>
            Ormoc City, Leyte, Philippines
        </p>

        <p>
            © 2026 Pressed Peanut Candy. All Rights Reserved.
        </p>

    </footer>

</body>
</html>
