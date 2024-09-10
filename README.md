<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Moon Veterinary - Cabinet Medical Veterinar. Oferim consultații, vaccinări și tratamente pentru animalele de companie.">
    <meta name="keywords" content="veterinar, consultații animale, deparazitări, vaccinări, tratamente, cabinet veterinar, Deva, animale de companie">
    <title>Moon Veterinary - Cabinet Medical Veterinar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f3f3;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
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
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .call-button {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1200x600'); /* Imagine de fundal */
            background-size: cover;
            background-position: center;
            height: 60vh;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .btn {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
        .services {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        .service {
            background-color: #f0f0f0;
            padding: 20px;
            margin: 10px;
            border-radius: 5px;
            text-align: center;
            flex: 1 1 calc(25% - 20px);
            box-sizing: border-box;
        }
        .service img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        .contact-form {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
            box-sizing: border-box;
        }
        .contact-form button {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        @media (max-width: 768px) {
            header {
                flex-direction: column;
                align-items: flex-start;
            }
            nav ul {
                display: flex;
                flex-direction: column;
            }
            nav ul li {
                margin: 10px 0;
            }
            .services {
                flex-direction: column;
            }
            .service {
                flex: 1 1 100%;
            }
            .hero {
                height: 40vh;
            }
        }
    </style>
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
            <a href="tel:07322878057" class="call-button">Sună acum</a>
        </header>

        <section class="hero">
            <div class="hero-content">
                <h2>Îngrijim prietenii tăi necuvântători din 2022</h2>
                <p>Consultații și tratamente personalizate pentru animalele tale de companie.</p>
                <a href="#servicii" class="btn">Află mai multe</a>
            </div>
        </section>

        <section id="servicii">
            <h2>Servicii oferite</h2>
            <div class="services">
                <div class="service">
                    <img src="https://via.placeholder.com/150" alt="Consultații">
                    <h3>Consultații</h3>
                    <p>Consultații complete și personalizate.</p>
                </div>
                <div class="service">
                    <img src="https://via.placeholder.com/150" alt="Deparazitări">
                    <h3>Deparazitări</h3>
                    <p>Deparazitări interne și externe.</p>
                </div>
                <div class="service">
                    <img src="https://via.placeholder.com/150" alt="Vaccinări">
                    <h3>Vaccinări</h3>
                    <p>Vaccinări pentru sănătatea animalelor tale.</p>
                </div>
                <div class="service">
                    <img src="https://via.placeholder.com/150" alt="Tratamente">
                    <h3>Tratamente</h3>
                    <p>Tratamente adaptate fiecărei situații.</p>
                </div>
            </div>
        </section>

        <section id="contact" class="contact-form">
            <h2>Contactează-ne</h2>
            <form action="#" method="post">
                <label for="name">Nume</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Mesaj</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <button type="submit">Trimite</button>
            </form>
        </section>

        <footer>
            <p>Ne găsești la: Strada Mihai Eminescu, Bloc B, scara D, Deva, Jud. Hunedoara</p>
            <p>Telefon: 0732 287 057 | Email: contact@moonveterinary.ro</p>
        </footer>
    </div>
</body>
</html>
