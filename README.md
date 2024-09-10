*Header simplu cu meniu de navigare și buton de apelare*
html
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


2. *Banner de impact*
html
<section class="hero">
    <div class="hero-content">
        <h2>Îngrijim prietenii tăi necuvântători din 2022</h2>
        <p>Consultații și tratamente personalizate pentru animalele tale de companie.</p>
        <a href="#servicii" class="btn">Află mai multe</a>
    </div>
</section>


3. *Serviciile oferite*
html
<section id="servicii">
    <h2>Servicii oferite</h2>
    <div class="services">
        <div class="service">
            <h3>Consultații</h3>
            <p>Consultații complete și personalizate.</p>
        </div>
        <div class="service">
            <h3>Deparazitări</h3>
            <p>Deparazitări interne și externe.</p>
        </div>
        <div class="service">
            <h3>Vaccinări</h3>
            <p>Vaccinări pentru sănătatea animalelor tale.</p>
        </div>
        <div class="service">
            <h3>Tratamente</h3>
            <p>Tratamente adaptate fiecărei situații.</p>
        </div>
    </div>
</section>


4. *Footer simplu*
html
<footer>
    <p>Ne găsești la: Strada Mihai Eminescu, Bloc B, scara D, Deva, Jud. Hunedoara</p>
    <p>Telefon: 0732 287 057 | Email: contact@moonveterinary.ro</p>
</footer>


Stilizare propusă (CSS):
css
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
    background: url('images/banner.jpg') no-repeat center center/cover;
    height: 60vh;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
}

.services {
    display: flex;
    justify-content: space-between;
}

.service {
    background-color: #f0f0f0;
    padding: 20px;
    margin: 10px;
    border-radius: 5px;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}

