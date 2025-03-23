<script>

</script>

<template>
 <!--estructura html-->
 <header>
        <div class="logo">Hotel</div>
        <nav>
            <ul class="nav-links">
                <li class="titulos"><a href="#about">NOSOTROS</a></li>
                <li class="titulos"><a href="#rooms">HABITACIONES</a></li>
                <li class="titulos"><a href="#services">SERVICIOS</a></li>
                <li class="titulos"><a href="#gallery">OPINIONES</a></li>
                <li class="titulos"><a href="#contact">CONTACTO</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h1>Bienvenido a Hotel las Mil Noches</h1>
        <p>Un refugio de lujo y confort</p>
        <a href="#reserva" class="btn">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-whatsapp"
                viewBox="0 0 16 16">
                <path
                    d="M13.601 2.326A7.854 7.854 0 0 0 7.994 0C3.627 0 .068 3.558.064 7.926c0 1.399.366 2.76 1.057 3.965L0 16l4.204-1.102a7.933 7.933 0 0 0 3.79.965h.004c4.368 0 7.926-3.558 7.93-7.93A7.898 7.898 0 0 0 13.6 2.326zM7.994 14.521a6.573 6.573 0 0 1-3.356-.92l-.24-.144-2.494.654.666-2.433-.156-.251a6.56 6.56 0 0 1-1.007-3.505c0-3.626 2.957-6.584 6.591-6.584a6.56 6.56 0 0 1 4.66 1.931 6.557 6.557 0 0 1 1.928 4.66c-.004 3.639-2.961 6.592-6.592 6.592zm3.615-4.934c-.197-.099-1.17-.578-1.353-.646-.182-.065-.315-.099-.445.099-.133.197-.513.646-.627.775-.114.133-.232.148-.43.05-.197-.1-.836-.308-1.592-.985-.59-.525-.985-1.175-1.103-1.372-.114-.198-.011-.304.088-.403.087-.088.197-.232.296-.346.1-.114.133-.198.198-.33.065-.134.034-.248-.015-.347-.05-.099-.445-1.076-.612-1.47-.16-.389-.323-.335-.445-.34-.114-.007-.247-.007-.38-.007a.729.729 0 0 0-.529.247c-.182.198-.691.677-.691 1.654 0 .977.71 1.916.81 2.049.098.133 1.394 2.132 3.383 2.992.47.205.84.326 1.129.418.475.152.904.129 1.246.08.38-.058 1.171-.48 1.338-.943.164-.464.164-.86.114-.943-.049-.084-.182-.133-.38-.232z">
                </path>
            </svg>
            <p>RESERVA</p>
        </a>
    </section>
<!---Sobre nosotros-->
    <section id="about" class="content">
        <h2 class="sobreN">SOBRE NOSOTROS</h2>
        <p class="informacion">
            Un destino donde la elegancia, la comodidad y el servicio excepcional se combinan para brindarte una
            experiencia inolvidable. Ubicado en el corazón de La Heroica Ciudad de Tlaxiaco, nuestro hotel es el lugar
            perfecto tanto para quienes buscan relajación y aventura como para quienes necesitan un espacio ideal para
            negocios.
            <br><br>
            En Mil Noches, nos esforzamos por ofrecerte un ambiente acogedor y exclusivo. Disfruta de nuestras cómodas
            habitaciones, diseñadas para tu descanso, y descubre nuestras instalaciones de primer nivel, que incluyen un
            lujoso spa y una piscina con vista panorámica.
        </p>
        <div class="Cons">
            <a href="https://www.google.com/maps?q=Heroica+Ciudad+de+Tlaxiaco" target="_blank">
    <img class="ubicacion" src="../assets/ubicacion.gif" alt="">
    <span class="pan">Ubicación</span>
</a>
           
        </div>
        <p class="historia">
            ¡Déjanos ser parte de tu historia y haz de cada noche una experiencia especial!
        </p>
    </section>

<!--Habitaciones-->
    <section id="rooms" class="content">
        <h2 class="sobreN">HABITACIONES</h2><br>
        <p class="texto-p">Explora nuestras habitaciones diseñadas para tu comodidad.</p>

        <div id="carouselExample" class="carousel slide">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img class="ruleta" src="https://th.bing.com/th/id/OIP.wJLz7YmzEq7__L9ccwr_WQHaE8?rs=1&pid=ImgDetMain">
                    <div  class="cuadro">
                        <h2 class="sobreN">Habitación Estándar</h2>
                        <p class="habitaciones">
                            Cómoda habitación con cama matrimonial o dos camas individuales, baño privado, aire
                            acondicionado, televisión por cable y wifi gratuito. Ideal para estancias cortas.
                        </p>
                        <button class="price-button" onclick="showPrice(this, '$80 USD')">Comprar</button>

                    </div>
                </div>
                <div class="carousel-item">
                    <img class="ruleta" src="https://cache.marriott.com/marriottassets/marriott/SDQJW/sdqjw-guestroom-0061-hor-clsc.jpg?interpolation=progressive-bilinear&">
                    <div class="cuadro">
                        <h2 class="sobreN">Habitación Doble</h2>
                        <p class="habitaciones">
                            Espaciosa habitación con dos camas matrimoniales, baño privado, aire acondicionado,
                            televisión por cable y wifi gratuito. Perfecta para familias o amigos.
                        </p>
                        <button class="price-button" onclick="showPrice(this, '$120 USD')">Comprar</button>
                    </div>
                </div>
                <div class="carousel-item">
                    <img class="ruleta" src="https://www.amenitiz.com/wp-content/uploads/2022/10/rrcibe846jo71ryoxahw.jpg">
                    <div class="cuadro">
                        <h2 class="sobreN">Habitación VIP</h2>
                        <p class="habitaciones">
                            Lujosa suite con cama king-size, jacuzzi, minibar, aire acondicionado, televisión por cable
                            y wifi gratuito. Experiencia premium para una estancia inolvidable.
                        </p>
                        <button class="price-button" onclick="showPrice(this, '$200 USD')">Comprar</button>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previo</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Siguiente</span>
            </button>
        </div><br>

    </section>
<!---Servicios-->

    <section id="services" class="content">
        <h2 class="section-title">Servicios</h2>
        <p class="texto-p">Disfruta de nuestras instalaciones y servicios de primer nivel.</p>

        <div class="services-container">
            <div class="service">
                <img src="https://th.bing.com/th/id/R.3d9de1e4701365059b5cc103f7bce336?rik=TaMXHFwnaX9%2fyw&pid=ImgRaw&r=0"
                    alt="Spa">
                <p>Spa</p>
            </div>
            <div class="service">
                <img src="https://lh5.googleusercontent.com/p/AF1QipMy39JDtMlvA8Qu1-cADCFFNOFTtNkvQqb4edse"
                    alt="Restaurante">
                <p>Restaurante gourmet</p>
            </div>
            <div class="service">
                <img src="https://i.pinimg.com/736x/0d/b5/6b/0db56bda4d8550836fd7aca921e48836.jpg" alt="Piscina">
                <p>Piscina y recreación</p>
            </div>
        </div>
    </section>
<!--Opiniones-->
    <section id="gallery" class="content">
        <h2 class="section-title">Opiniones</h2>
        <p class="texto-p">Descubre lo que dicen nuestros huéspedes sobre su experiencia.</p>

        <div class="carousel">
            <div class="review-card">
                <p class="stars">★★★★★</p>
                <p>"Una experiencia increíble, el mejor servicio y confort."</p>
                <p class="review-author">- María González</p>
            </div>
            <div class="review-card">
                <p class="stars">★★★★☆</p>
                <p>"Excelente lugar, con vistas espectaculares y servicio impecable."</p>
                <p class="review-author">- Juan Pérez</p>
            </div>
            <div class="review-card">
                <p class="stars">★★★★★</p>
                <p>"El mejor hotel en el que he estado, todo impecable y acogedor."</p>
                <p class="review-author">- Sofía Martínez</p>
            </div>
            
        </div>

        <button class="prev-btn" onclick="scrollCarousel(-1)">&#10094;</button>
        <button class="next-btn" onclick="scrollCarousel(1)">&#10095;</button>
    </section>

<!--Contacto-->
    <section id="contact" class="content">
        <h2 class="sobreN">CONTACTO</h2>
        <p class="texto-p">Ponte en contacto con nosotros para cualquier consulta o reserva.</p>

        <div class="Credes">
            <a class="redes" href="tel:+529531377517">
                <i class="fa-solid fa-phone"></i>
            </a>
            <a class="redes" href="mailto:contacto@milnoches.com">
                <i class="fa-solid fa-envelope"></i>
            </a>
            <a class="redes" href="#">
                <i class="fa-brands fa-twitter"></i>
            </a>
            <a class="redes" href="#">
                <i class="fa-brands fa-facebook-f"></i>
            </a>
            <a class="redes" href="#">
                <i class="fa-brands fa-instagram"></i>
            </a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Hotel las Mil Noches Todos los derechos reservados.</p>
    </footer>

</template>

<style scoped>
/*Estilos css*/
:root {
  --primary-color: #c9a861;
  --text-color: #fff;
  --header-bg: #c9a861a1;
  --dark-overlay: rgba(0, 0, 0, 0.4);
}

/* Fuentes */
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@300;400;500&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
}

/* Estilo del header */
header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: #c9a861a1;
  padding:  0.5rem 0;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  z-index: 1000;
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}

.logo {
  font-family: 'Playfair Display', serif;
  font-size: 1.2rem;
  font-weight: bold;
  color: #ffffff;
  letter-spacing: 1px;
  margin-bottom: 0.8rem;
  margin-left: 5rem;
}

nav {
  width: 100%;
  display: flex;
  justify-content: center;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 3rem;
  justify-content: center;
}

.nav-links li {
  display: inline;
}

.nav-links a {
  color: var(--text-color);
  text-decoration: none;
  font-weight: 500;
  font-size: 0.85rem;
  letter-spacing: 1px;
  text-transform: uppercase;
  transition: color 0.3s;
}

.nav-links a:hover {
  color:  #c9a861;
}

/* Estilo de la sección hero */
.hero {
  position: relative;
  height: 100vh;
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 0 20px;
  background-image: url('https://images.unsplash.com/photo-1578683010236-d716f9a3f461?q=80&w=2070');
  background-size: cover;
  background-position: center;
  background-blend-mode: overlay;
  background-color: rgba(0, 0, 0, 0.5);
}

.hero h1 {
  font-family: 'Playfair Display', serif;
  font-size: 4rem;
  font-weight: 700;
  color:white;
  margin-bottom: 1.5rem;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
  letter-spacing: 2px;
  line-height: 1.2;
}

.hero p {
  font-family: 'Poppins', sans-serif;
  font-size: 1.2rem;
  color:white;
  margin-bottom: 2.5rem;
  letter-spacing: 1px;
  text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
}

/* Estilo del botón */
.hero .btn, .hero a.btn, .hero button.btn {
  background-color: var(--primary-color);
  color: var(--text-color);
  border: none;
  padding: 1rem 2.5rem;
  font-size: 1rem;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 1px;
  border-radius: 0;
  cursor: pointer;
  transition: background-color 0.3s;
  display: inline-block;
  text-decoration: none;
}

.hero .btn:hover {
  background-color: #b08e45;
}

.hero .btn p {
  margin: 0;
  font-size: 0.9rem;
  text-shadow: none;
  display: inline;
}

.hero .btn svg {
  width: 18px;
  height: 18px;
  margin-right: 8px;
  vertical-align: middle;
}

/* Responsive */
@media (max-width: 768px) {
  header {
    padding: 1rem 0;
  }
  
  .nav-links {
    gap: 1.5rem;
    flex-wrap: wrap;
    justify-content: center;
    padding: 0 1rem;
  }
  
  .hero h1 {
    font-size: 2.5rem;
  }
  
  .hero p {
    font-size: 1rem;
  }
}

/* Estilo del botón */
.hero .btn, .hero a.btn, .hero button.btn {
  background-color:  #c9a861;
  color: var(--text-color);
  border: none;
  padding: 1.2rem 2.5rem;
  font-size: 1rem;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 1px;
  border-radius: 18px;
  cursor: pointer;
  transition: background-color 0.3s;
  display: inline-block;
  text-decoration: none;
}

.hero .btn:hover {
  background-color: #b08e45;
}

.hero .btn p {
  margin: 0;
  font-size: 0.9rem;
  text-shadow: none;
  display: inline;
}

.hero .btn svg {
  width: 18px;
  height: 18px;
  margin-right: 8px;
  vertical-align: middle;
}

/* Responsive */
@media (max-width: 768px) {
  header {
    padding: 1rem;
    flex-direction: column;
    align-items: flex-start;
  }
  
  .nav-links {
    margin-top: 1rem;
    gap: 1rem;
    flex-wrap: wrap;
  }
  
  .hero h1 {
    font-size: 2.5rem;
  }
  
  .hero p {
    font-size: 1rem;
  }
}
/* Estilo del botón */
.hero .btn {
  background-color: var(--primary-color);
  color: white;
  border: none;
  padding: 1.3rem 5rem;
  font-size: 1rem;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 1px;
  border-radius: 4px;
  cursor: pointer;
  transition: background-color 0.3s;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.hero .btn:hover {
  background-color: #45b053;
}

.hero .btn p {
  margin: 0;
  font-size: 0.9rem;
  text-shadow: none;
}

.hero .btn svg {
  width: 20px;
  height: 20px;
}

/* Responsive */
@media (max-width: 768px) {
  header {
    padding: 1rem;
  }
  
  .nav-links {
    gap: 1rem;
  }
  
  .hero h1 {
    font-size: 2.5rem;
  }
  
  .hero p {
    font-size: 1rem;
  }
}

.content {
    padding: 3rem 1rem;
    text-align: center;

}

#rooms{
    padding: 40px; 
    background-color: #ece8e1; 
    border-radius: 10px;
}

footer {
    background: #c9a861;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
}
.btn {
    background-color: #ffffff;
    border: 1px solid #fff45c;
    padding: 5px;
    position: relative;
    width: 7.3em;
    height: 2.5em;
    transition: 0.5s;
    font-size: 17px;
    border-radius: 0.4em;
}

.btn p {

    position: absolute;
    top: 0.4em;
    left: 1.30em;
    margin: 0;
    padding: 0;
    transition: .5s;
    color: #000000;
}

.btn svg {
    position: absolute;
    top: 0.45em;
    right: 0.5em;
    margin: 0;
    padding: 0;
    opacity: 0;
    transition: 0.5s;
    height: 1em;
    fill: #fff
}

.btn:hover p {
    left: 0.5em;
    color: #fff
}

.btn:hover svg {
    opacity: 1;
}

.btn:hover {
    background-color: #25D366;
}

.button {
    --width: 100px;
    --height: 35px;
    --tooltip-height: 35px;
    --tooltip-width: 90px;
    --gap-between-tooltip-to-button: 18px;
    --button-color: #222;
    --tooltip-color: #fff;
    width: var(--width);
    height: var(--height);
    background: var(--button-color);
    position: relative;
    text-align: center; 
    border-radius: 0.45em;
    font-family: "Arial";
    transition: background 0.3s;
  }
  
  .button::before {
    position: absolute;
    content: attr(data-tooltip);
    width: var(--tooltip-width);
    height: var(--tooltip-height);
    background-color: #555;
    font-size: 0.9rem;
    color: #fff;
    border-radius: .25em;
    line-height: var(--tooltip-height);
    bottom: calc(var(--height) + var(--gap-between-tooltip-to-button) + 10px);
    left: calc(50% - var(--tooltip-width) / 2);
  }
  
  .button::after {
    position: absolute;
    content: '';
    width: 0;
    height: 0;
    border: 10px solid transparent;
    border-top-color: #555;
    left: calc(50% - 10px);
    bottom: calc(100% + var(--gap-between-tooltip-to-button) - 10px);
  }
  
  .button::after,.button::before {
    opacity: 0;
    visibility: hidden;
    transition: all 0.5s;
  }
  
  .text {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .button-wrapper,.text,.icon {
    overflow: hidden;
    position: absolute;
    width: 100%;
    height: 100%;
    left: 0;
    color: #fff;
  }
  
  .text {
    top: 0
  }
  
  .text,.icon {
    transition: top 0.5s;
  }
  
  .icon {
    color: #fff;
    top: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .icon svg {
    width: 24px;
    height: 24px;
  }
  
  .button:hover {
    background: #222;
  }
  
  .button:hover .text {
    top: -100%;
  }
  
  .button:hover .icon {
    top: 0;
  }
  
  .button:hover:before,.button:hover:after {
    opacity: 1;
    visibility: visible;
  }
  
  .button:hover:after {
    bottom: calc(var(--height) + var(--gap-between-tooltip-to-button) - 20px);
  }
  
  .button:hover:before {
    bottom: calc(var(--height) + var(--gap-between-tooltip-to-button));
  }
  
  img {
    width: 100%;
    height: auto;
  }
  .Bienvenida{
    text-align: center;
    font-weight: bold;
    font-size: 20px;
    font-family: Arial, Helvetica, sans-serif;

  }

  .informacion{
    text-align: justify;
    font-size: 18px;
    font-family: Arial, Helvetica, sans-serif;
  }
  .historia{
    text-align: center;
    font-weight: bold;
    font-size: 20px;
    font-family: Arial, Helvetica, sans-serif;
  }

  .section-title {
    color: #c9a861;
    font-size: 2.5rem;
    text-align: center;
    font-weight: bold;
    margin-bottom: 10px;
    text-transform: uppercase;
    letter-spacing: 2px;
}

.section-description {
    text-align: center;
    font-size: 1.2rem;
    color: #555;
    margin-bottom: 30px;
}

.services-container {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin-top: 20px;
    flex-wrap: wrap;
}

.service {
    text-align: center;
    width: 250px;
    padding: 15px;
    background: #fff;
    border-radius: 15px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.service img {
    width: 100%;
    height: 160px;
    border-radius: 10px;
    object-fit: cover;
    transition: transform 0.3s ease, opacity 0.3s ease;
}

.service p {
  margin-top: 15px;
  font-size: 1.2rem;
  font-weight: bold;
  color: #333;
}

.service:hover {
  transform: translateY(-10px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
}

.service:hover img {
  transform: scale(1.1);
  opacity: 0.9;
}

.sobreN{
    color: #c9a861; 
    font-size: 2rem; 
    text-align: center; 
    font-weight: bold;
}

.informacion{
    font-size: 1.2rem; 
    line-height: 1.6; 
    text-align: justify; 
    margin: 20px 0; 
    padding: 10px; 
    background-color: #f8f8f8; 
    border-left: 5px solid #c9a861;
}
.Cons{
   text-align: center; 
   margin-top: 15px;
}

.pan{
    color: #c9a861;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 1.2rem;
    font-weight: bold;
}
.hotel-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: #333;
  color: white;
}

.hotel-logo {
  font-size: 1.8rem;
  font-weight: bold;
}

.hotel-nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.hotel-nav-links li a {
  text-decoration: none;
  color: white;
  font-size: 1.2rem;
}

.hotel-hero {
  text-align: center;
  padding: 50px;
  background: url('Img/hero.jpg') no-repeat center center/cover;
  color: white;
}

.hotel-btn {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #25D366;
  color: white;
  padding: 10px 20px;
  border-radius: 5px;
  text-decoration: none;
}
.ubicacion{
    width: 50px;
    height: 50px;
    margin: 0 auto;
    display: block;
    border-radius: 50%;
    transition: 0.5s;
}
.titulos{
  color: #ffffff;
}

.price-button {
    background-color: #c9a861;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 1.2rem;
    cursor: pointer;
    transition: all 0.3s ease-in-out;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
    position: relative;
    overflow: hidden;
}

.price-button:hover {
  background-color: #b28b4c;
  transform: scale(1.05);
  box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.3);
}

.price-button:active {
  transform: scale(0.98);
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2);
 }

 .price-btn {
  background-color: #007bff;
  color: white;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
  border-radius: 5px;
}

.price-btn:hover {
  background-color: #0056b3;
}


.ruleta{
  width: 100%; 
  height: 450px; 
  object-fit: cover; 
  border-radius: 10px;
  }

.habitaciones{
  font-size: 1.3rem; 
  text-align: center; 
  color: #555; 
  margin-bottom: 30px;
  font-size: 1.2rem; 
  line-height: 1.6; 
  text-align: justify; 
  margin: 20px auto; 
  padding: 15px; 
  background-color: #f8f8f8; 
  border-left: 5px solid #c9a861; 
  max-width: 80%;
}
.cuadro{
  text-align: center; 
  margin-top: 15px;
}
.texto-p{
  font-size: 1.3rem; 
  text-align: center; 
  color: #555; 
  margin-bottom: 30px;
}

.section-title {
    color: #c9a861;
    font-size: 2.5rem;
    text-align: center;
    font-weight: bold;
    margin-bottom: 10px;
    text-transform: uppercase;
    letter-spacing: 2px;
}

.section-description {
    text-align: center;
    font-size: 1.2rem;
    color: #555;
    margin-bottom: 30px;
}

.carousel {
    display: flex;
    gap: 20px;
    padding: 20px;
    overflow: hidden;
    scroll-behavior: smooth;
    justify-content: center;
    align-items: center;
    max-width: 80%;
    margin: auto;
    position: relative;
}

.review-card {
    min-width: 300px;
    max-width: 350px;
    flex: 0 0 auto;
    padding: 20px;
    background: linear-gradient(135deg, #f8f8f8, #fff);
    border-radius: 15px;
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    position: relative;
}

.review-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
}

.stars {
    font-size: 1.5rem;
    font-weight: bold;
    color: #ffcc00;
}

.review-author {
    font-style: italic;
    color: #777;
    margin-top: 10px;
}

.prev-btn,
.next-btn {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
    border: none;
    padding: 10px 15px;
    font-size: 1.5rem;
    cursor: pointer;
    border-radius: 50%;
    transition: background-color 0.3s ease;
}

.prev-btn:hover,
.next-btn:hover {
            background-color: rgba(0, 0, 0, 0.8);
}

.prev-btn {
            left: 5%;
}

.next-btn {
            right: 5%;
}
#contact{
  text-align: center; 
  padding: 20px; 
  color: #555; 
  background-color: #ece8e1; 
  border-radius: 10px; 
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}
.redes{
  text-decoration: none; 
  color: #c9a861; 
  font-size: 1.8rem;
}
.Credes{
  display: flex; 
  justify-content: center; 
  align-items: center; 
  gap: 20px; 
  margin-top: 15px;
}
</style>