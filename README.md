<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Moon Veterinary - Cabinet Medical Veterinar. Oferim consultații, vaccinări și tratamente pentru animalele de companie.">
    <meta name="keywords" content="veterinar, consultații animale, deparazitări, vaccinări, tratamente, cabinet veterinar, Deva, animale de companie">
    <title>Moon Veterinary - Cabinet Medical Veterinar</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            background-color: #333;
            color: white;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin-right: 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 500;
        }
        .social-icons a {
            color: white;
            margin-left: 15px;
            text-decoration: none;
            font-size: 1.5rem;
        }
        .call-button {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 30px;
            transition: background-color 0.3s;
        }
        .call-button:hover {
            background-color: #218838;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1200x600'); /* Fundal real */
            background-size: cover;
            background-position: center;
            height: 60vh;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
        }
        .hero-overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.5);
        }
        .hero-content {
            position: relative;
            z-index: 2;
        }
        .hero h2 {
            font-size: 3rem;
            margin: 0;
        }
        .hero p {
            font-size: 1.2rem;
            margin: 10px 0;
        }
        .btn {
            background-color: #28a745;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 30px;
            font-weight: 500;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #218838;
        }
        #doctor {
            text-align: center;
            margin-top: 50px;
        }
        .doctor-profile {
            display: inline-block;
            text-align: center;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .doctor-img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            margin-bottom: 20px;
        }
        h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
            color: #333;
        }
        p {
            font-size: 1rem;
            color: #555;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 40px;
        }
        .service {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 20px;
            transition: transform 0.3s;
        }
        .service:hover {
            transform: translateY(-5px);
        }
        .service img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        #orar {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .orar ul {
            list-style-type: none;
            padding: 0;
            font-size: 1.2rem;
            color: #333;
        }
        .orar li {
            margin: 10px 0;
        }
        .orar strong {
            color: #28a745;
        }
        #contact {
            text-align: center;
            margin-top: 50px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <h1>Moon Veterinary</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#despre">Despre noi</a></li>
                    <li><a href="#servicii">Servicii</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="social-icons">
                <a href="https://m.facebook.com/p/Moon-Veterinary-100083518988337/" target="_blank"><i class="fab fa-facebook"></i></a>
                <a href="https://wa.me/407322287057" target="_blank"><i class="fab fa-whatsapp"></i></a>
            </div>
        </header>

        <section class="hero">
            <div class="hero-overlay"></div>
            <div class="hero-content">
                <h2>Îngrijim prietenii tăi necuvântători din 2022</h2>
                <p>Consultații și tratamente personalizate pentru animalele tale de companie.</p>
                <a href="#servicii" class="btn">Află mai multe</a>
            </div>
        </section>

        <section id="doctor">
            <h2>Despre Doamna Doctor</h2>
            <div class="doctor-profile">
                <img src="https://exemplu.com/poza-doctor.jpg" alt="Doamna Doctor" class="doctor-img">
                <h3>Dr. Dancila Alexandra Elena </h3>
                <p>Medic Veterinar, Specializat în chirurgie veterinară și medicină internă.</p>
            </div>
        </section>

        <section id="servicii">
            <h2>Servicii oferite</h2>
            <div class="services">
                <div class="service">
                    <img src="https://via.placeholder.com/150/0000FF/808080?text=Consultatii" alt="Consultații">
                    <h3>Consultații</h3>
                    <p>Consultații complete și personalizate.</p>
                </div>
                <div class="service">
                    <img src="https://
