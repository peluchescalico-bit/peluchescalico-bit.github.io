<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mundo de Peluches</title>
    <style>
        /* Reset y estilos generales */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            background-color: #fff9f9;
            color: #333;
            line-height: 1.6;
        }
        
        /* Header */
        header {
            background: linear-gradient(135deg, #ffb6c1, #ff69b4);
            color: white;
            text-align: center;
            padding: 2rem 0;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }
        
        /* Navegación */
        nav {
            background-color: #ff69b4;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }
        
        nav li {
            margin: 0 1.5rem;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            transition: all 0.3s ease;
        }
        
        nav a:hover {
            background-color: white;
            color: #ff69b4;
        }
        
        /* Contenido principal */
        main {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 2rem;
        }
        
        section {
            margin-bottom: 3rem;
            background-color: white;
            border-radius: 15px;
            padding: 2rem;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
        }
        
        h2 {
            color: #ff69b4;
            margin-bottom: 1.5rem;
            border-bottom: 2px solid #ffb6c1;
            padding-bottom: 0.5rem;
        }
        
        /* Galería de peluches */
        .galeria {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .peluche {
            background-color: #fff9f9;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .peluche:hover {
            transform: translateY(-10px);
        }
        
        .peluche img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        
        .peluche-info {
            padding: 1rem;
        }
        
        .peluche h3 {
            color: #ff69b4;
            margin-bottom: 0.5rem;
        }
        
        .precio {
            font-weight: bold;
            color: #ff1493;
            font-size: 1.2rem;
            margin: 0.5rem 0;
        }
        
        .btn {
            display: inline-block;
            background-color: #ff69b4;
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            text-decoration: none;
            margin-top: 0.5rem;
            transition: background-color 0.3s ease;
        }
        
        .btn:hover {
            background-color: #ff1493;
        }
        
        /* Testimonios */
        .testimonios {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .testimonio {
            background-color: #fff0f5;
            padding: 1.5rem;
            border-radius: 10px;
            border-left: 4px solid #ff69b4;
        }
        
        .testimonio p {
            font-style: italic;
            margin-bottom: 1rem;
        }
        
        .cliente {
            font-weight: bold;
            color: #ff69b4;
        }
        
        /* Footer */
        footer {
            background: linear-gradient(135deg, #ff69b4, #ff1493);
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }
        
        .redes-sociales {
            margin: 1rem 0;
        }
        
        .redes-sociales a {
            color: white;
            margin: 0 0.5rem;
            font-size: 1.5rem;
            transition: color 0.3s ease;
        }
        
        .redes-sociales a:hover {
            color: #ffb6c1;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav li {
                margin: 0.5rem 0;
            }
            
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Mundo de Peluches</h1>
        <p>Los peluches más suaves y adorables para todas las edades</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#productos">Productos</a></li>
            <li><a href="#nosotros">Nosotros</a></li>
            <li><a href="#testimonios">Testimonios</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
    
    <main>
        <section id="inicio">
            <h2>Bienvenido a nuestro mundo de peluches</h2>
            <p>En Mundo de Peluches nos especializamos en crear y distribuir los peluches más suaves, tiernos y de alta calidad. Desde clásicos ositos hasta criaturas fantásticas, tenemos el peluche perfecto para cada ocasión.</p>
            <p>Nuestros peluches son ideales para regalos, coleccionistas o simplemente para dar y recibir amor.</p>
        </section>
        
        <section id="productos">
            <h2>Nuestros Peluches Destacados</h2>
            <div class="galeria">
                <div class="peluche">
                    <img src="https://via.placeholder.com/300x200?text=Osito+Tierno" alt="Osito Tierno">
                    <div class="peluche-info">
                        <h3>Osito Tierno</h3>
                        <p>Suave osito de peluche con lazo de seda, perfecto para abrazar.</p>
                        <p class="precio">$24.99</p>
                        <a href="#" class="btn">Comprar ahora</a>
                    </div>
                </div>
                
                <div class="peluche">
                    <img src="https://via.placeholder.com/300x200?text=Unicornio+Mágico" alt="Unicornio Mágico">
                    <div class="peluche-info">
                        <h3>Unicornio Mágico</h3>
                        <p>Unicornio de colores pastel con crin arcoíris y cuerno brillante.</p>
                        <p class="precio">$29.99</p>
                        <a href="#" class="btn">Comprar ahora</a>
                    </div>
                </div>
                
                <div class="peluche">
                    <img src="https://via.placeholder.com/300x200?text=Dinosaurio+Amigable" alt="Dinosaurio Amigable">
                    <div class="peluche-info">
                        <h3>Dinosaurio Amigable</h3>
                        <p>Divertido dinosaurio verde con sonrisa adorable y patas suaves.</p>
                        <p class="precio">$27.99</p>
                        <a href="#" class="btn">Comprar ahora</a>
                    </div>
                </div>
                
                <div class="peluche">
                    <img src="https://via.placeholder.com/300x200?text=Perrito+Bebé" alt="Perrito Bebé">
                    <div class="peluche-info">
                        <h3>Perrito Bebé</h3>
                        <p>Pequeño cachorro de peluche con ojos brillantes y orejas suaves.</p>
                        <p class="precio">$22.99</p>
                        <a href="#" class="btn">Comprar ahora</a>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="nosotros">
            <h2>Sobre Nosotros</h2>
            <p>Mundo de Peluches comenzó como un pequeño negocio familiar en 2010, con la misión de crear peluches de alta calidad que traigan alegría a personas de todas las edades.</p>
            <p>Hoy en día, trabajamos con artesanos expertos y utilizamos solo los materiales más suaves y seguros para nuestros productos. Cada peluche está hecho con amor y cuidado.</p>
            <p>Nuestro compromiso es con la calidad, la seguridad y la satisfacción de nuestros clientes.</p>
        </section>
        
        <section id="testimonios">
            <h2>Lo que dicen nuestros clientes</h2>
            <div class="testimonios">
                <div class="testimonio">
                    <p>"Compré el unicornio para mi hija y no puede dormir sin él. La calidad es increíble y ha resistido muchos lavados."</p>
                    <p class="cliente">- María G.</p>
                </div>
                
                <div class="testimonio">
                    <p>"El osito tierno fue el regalo perfecto para mi novia en nuestro aniversario. Lo ama y siempre está en su cama."</p>
                    <p class="cliente">- Carlos M.</p>
                </div>
                
                <div class="testimonio">
                    <p>"Como coleccionista de peluches, aprecio la atención al detalle y la calidad de los productos de Mundo de Peluches."</p>
                    <p class="cliente">- Laura T.</p>
                </div>
            </div>
        </section>
        
        <section id="contacto">
            <h2>Contacto</h2>
            <p>¿Tienes preguntas o comentarios? ¡Nos encantaría escucharte!</p>
            <p>Email: info@mundodepeluches.com</p>
            <p>Teléfono: (555) 123-4567</p>
            <p>Dirección: Calle Peluche 123, Ciudad Juguete, País</p>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 Mundo de Peluches. Todos los derechos reservados.</p>
        <div class="redes-sociales">
            <a href="#" aria-label="Facebook">📘</a>
            <a href="#" aria-label="Instagram">📷</a>
            <a href="#" aria-label="Twitter">🐦</a>
            <a href="#" aria-label="Pinterest">📌</a>
        </div>
        <p>Hecho con ❤️ para amantes de los peluches</p>
    </footer>
</body>
</html>
