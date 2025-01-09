<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Casa de Asia | Arte Culinario Asiático</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <div class="side-decorations left">
        <div class="decoration-item lantern"></div>
        <div class="decoration-item bamboo"></div>
        <div class="decoration-item fan"></div>
        <div class="decoration-item dragon"></div>
    </div>

    <div class="side-decorations right">
        <div class="decoration-item fish"></div>
        <div class="decoration-item cloud"></div>
        <div class="decoration-item flower"></div>
        <div class="decoration-item bird"></div>
    </div>

    <header>
        <div class="floating-elements">
            <div class="floating-icon sushi"></div>
            <div class="floating-icon noodles"></div>
            <div class="floating-icon chopsticks"></div>
        </div>
        <nav>
            <div class="logo">Casa de Asia</div>
            <ul class="nav-links">
                <li><a href="#home">Inicio</a></li>
                <li><a href="#menu">Menú</a></li>
                <li><a href="#about">Nosotros</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="bg-pattern"></div>
        <div class="decorative-circle"></div>
        <h1>Casa de Asia</h1>
        <p>Explora el arte culinario asiático, vive una experiencia gastronómica única</p>
        <a href="#menu" class="cta-button">Explorar Menú</a>
        <div class="scroll-indicator">
            <div class="mouse"></div>
            <span>Desliza para descubrir más</span>
        </div>
    </section>

    <section id="menu" class="menu-section">
        <div class="bg-pattern"></div>
        <div class="container">
            <div class="section-title">
                <h2>Platos Selectos</h2>
                <div class="title-decoration"></div>
            </div>
            
            <div class="menu-categories">
                <button class="category-btn active" data-category="all">Todos</button>
                <button class="category-btn" data-category="sushi">Sushi</button>
                <button class="category-btn" data-category="ramen">Ramen</button>
                <button class="category-btn" data-category="wok">Wok</button>
            </div>

            <div class="menu-grid">
                <!-- Sushi 类别 -->
                <div class="menu-item" data-category="sushi">
                    <div class="item-image">
                        <img src="https://images.unsplash.com/photo-1579584425555-c3ce17fd4351" alt="Sushi Premium">
                        <div class="item-overlay">
                            <span class="chef-choice">Chef's Choice</span>
                        </div>
                    </div>
                    <div class="item-content">
                        <h3>Sushi Premium Selection</h3>
                        <div class="item-description">
                            <p>Selección de nigiri y rolls premium con pescado fresco del día</p>
                            <div class="ingredients">
                                <span>Salmón</span>
                                <span>Atún</span>
                                <span>Pez mantequilla</span>
                            </div>
                        </div>
                        <div class="item-footer">
                            <span class="price">¥488</span>
                            <span class="portion">8 piezas</span>
                        </div>
                    </div>
                </div>

                <!-- Ramen 类别 -->
                <div class="menu-item featured" data-category="ramen">
                    <div class="item-image">
                        <img src="https://images.unsplash.com/photo-1569718212165-3a8278d5f624" alt="Ramen Especial">
                        <div class="item-overlay">
                            <span class="best-seller">Best Seller</span>
                        </div>
                    </div>
                    <div class="item-content">
                        <h3>Ramen Premium</h3>
                        <div class="item-description">
                            <p>Caldo tonkotsu 48 horas, chashu de cerdo ibérico, huevo marinado</p>
                            <div class="spiciness-meter">
                                <span>Nivel de picante:</span>
                                <div class="spice-levels">
                                    <span class="active"></span>
                                    <span class="active"></span>
                                    <span></span>
                                </div>
                            </div>
                        </div>
                        <div class="item-footer">
                            <span class="price">¥168</span>
                            <button class="customize-btn">Personalizar</button>
                        </div>
                    </div>
                </div>

                <!-- Wok 类别 -->
                <div class="menu-item" data-category="wok">
                    <div class="item-image">
                        <img src="https://images.unsplash.com/photo-1512058564366-18510be2db19" alt="Wok de Pato">
                        <div class="item-overlay">
                            <span class="new-dish">Nuevo</span>
                        </div>
                    </div>
                    <div class="item-content">
                        <h3>Pato Pekín al Wok</h3>
                        <div class="item-description">
                            <p>Pato crujiente con verduras de temporada y salsa hoisin casera</p>
                            <div class="preparation-time">
                                <i class="time-icon"></i>
                                <span>25 min</span>
                            </div>
                        </div>
                        <div class="item-footer">
                            <span class="price">¥258</span>
                            <span class="for-two">Para compartir</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="wave-separator"></div>
    </section>

    <section id="about" class="about-section">
        <div class="bg-pattern"></div>
        <div class="container">
            <div class="content-grid">
                <div class="about-text">
                    <h2>Sobre Nosotros</h2>
                    <p>Casa de Asia se dedica a brindar la experiencia culinaria asiática más auténtica...</p>
                </div>
                <div class="image-wall">
                    <img src="https://images.unsplash.com/photo-1583032015879-e5022cb87c3b" alt="Ambiente del restaurante">
                    <img src="https://images.unsplash.com/photo-1579871494447-9811cf80d66c" alt="Detalle culinario">
                    <img src="https://images.unsplash.com/photo-1607330289024-1535c6b4e1c1" alt="Chef en acción">
                    <img src="https://images.unsplash.com/photo-1590846406792-0adc7f938f1d" alt="Área de comedor">
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact-section">
        <div class="bg-pattern"></div>
        <div class="container">
            <div class="content-grid">
                <div class="contact-info">
                    <h2>Contacto</h2>
                    <div class="info-item">
                        <i class="icon location"></i>
                        <p>Dirección: Calle XX, Distrito XX, Ciudad XX</p>
                    </div>
                    <div class="info-item">
                        <i class="icon phone"></i>
                        <p>Teléfono: 123-4567-8900</p>
                    </div>
                    <div class="info-item">
                        <i class="icon time"></i>
                        <p>Horario: Lunes a Domingo 11:00-22:00</p>
                    </div>
                </div>
                <div class="map">
                    <!-- Código del mapa -->
                </div>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Casa de Asia - Todos los derechos reservados</p>
    </footer>

    <script src="./js/main.js"></script>

    <style>
    .hero {
        background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                    url('https://images.unsplash.com/photo-1517248135467-4c7edcad34c4') !important;
        background-size: cover !important;
        background-position: center !important;
    }

    .about-section {
        background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                    url('https://images.unsplash.com/photo-1590846406792-0adc7f938f1d') !important;
        background-size: cover !important;
        background-position: center !important;
    }
    </style>
</body>
</html> 
