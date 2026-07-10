<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>YESHUA | Venta y Reparación de Celulares</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Poppins, sans-serif;
            scroll-behavior: smooth
        }
        
        body {
            background: #f4f7fc;
            color: #333
        }
        
        header {
            position: fixed;
            top: 0;
            width: 100%;
            background: #111827
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            padding: 18px 8%;
            align-items: center
        }
        
        .logo {
            color: #00d4ff;
            font-size: 30px;
            font-weight: 700
        }
        
        nav ul {
            display: flex;
            list-style: none;
            gap: 25px
        }
        
        nav a {
            color: #fff;
            text-decoration: none
        }
        
        .hero {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
            background: linear-gradient(rgba(0, 0, 0, .6), rgba(0, 0, 0, .6)), url('https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?auto=format&fit=crop&w=1600&q=80') center/cover
        }
        
        .btn {
            display: inline-block;
            background: #00d4ff;
            color: #fff;
            padding: 15px 35px;
            border-radius: 30px;
            text-decoration: none;
            margin-top: 20px
        }
        
        section {
            padding: 90px 8%
        }
        
        .titulo {
            text-align: center;
            font-size: 38px;
            margin-bottom: 40px
        }
        
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
            gap: 25px
        }
        
        .card {
            background: #fff;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 8px 18px rgba(0, 0, 0, .15)
        }
        
        .card img {
            width: 100%;
            height: 220px;
            object-fit: cover
        }
        
        .card h3,
        .card p,
        .precio {
            padding: 10px 15px
        }
        
        .precio {
            font-weight: 700;
            color: #009688
        }
        
        .card button {
            margin: 15px;
            width: calc(100% - 30px);
            padding: 12px;
            border: none;
            background: #111827;
            color: #fff;
            border-radius: 8px
        }
        
        .servicios {
            background: #111827;
            color: #fff
        }
        
        .servicios-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px
        }
        
        .servicio {
            background: #1f2937;
            padding: 20px;
            border-radius: 12px
        }
        
        .contacto {
            text-align: center
        }
        
        .wa {
            display: inline-block;
            background: #25D366;
            color: #fff;
            padding: 18px 35px;
            border-radius: 40px;
            text-decoration: none;
            font-size: 22px;
            font-weight: 700
        }
        
        footer {
            background: #111827;
            color: #fff;
            text-align: center;
            padding: 30px
        }
        
        .float {
            position: fixed;
            right: 20px;
            bottom: 20px;
            background: #25D366;
            color: #fff;
            width: 65px;
            height: 65px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 34px;
            text-decoration: none
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="logo">📱 YESHUA</div>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#productos">Celulares</a></li>
                <li><a href="#servicios">Servicio Técnico</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero" id="inicio">
        <div>
            <h1>Celulares Nuevos y de Segunda</h1>
            <p>Los mejores equipos al mejor precio.</p><a class="btn" href="#productos">Ver catálogo</a></div>
    </section>
    <section id="productos">
        <h2 class="titulo">Celulares</h2>
        <div class="grid">
            <div class="card"><img src="https://images.unsplash.com/photo-1592899677977-9c10ca588bbd?auto=format&fit=crop&w=800&q=80">
                <h3>iPhone 15 Pro</h3>
                <p>Nuevo</p>
                <div class="precio">$5.500.000</div><button>Cotizar</button></div>
            <div class="card"><img src="https://images.unsplash.com/photo-1610945265064-0e34e5519bbf?auto=format&fit=crop&w=800&q=80">
                <h3>Samsung S24 Ultra</h3>
                <p>Nuevo</p>
                <div class="precio">$4.800.000</div><button>Cotizar</button></div>
            <div class="card"><img src="https://images.unsplash.com/photo-1580910051074-3eb694886505?auto=format&fit=crop&w=800&q=80">
                <h3>Xiaomi Redmi</h3>
                <p>Seminuevo</p>
                <div class="precio">$950.000</div><button>Cotizar</button></div>
        </div>
    </section>
    <section class="servicios" id="servicios">
        <h2 class="titulo">Servicio Técnico</h2>
        <div class="servicios-grid">
            <div class="servicio">Cambio de pantalla</div>
            <div class="servicio">Cambio de batería</div>
            <div class="servicio">Reparación por humedad</div>
            <div class="servicio">Software y desbloqueos</div>
        </div>
    </section>
    <section class="contacto" id="contacto">
        <h2 class="titulo">Contáctanos</h2>
        <p>Escríbenos directamente por WhatsApp.</p><br><a class="wa" target="_blank" href="https://wa.me/573203495777?text=Hola%20YESHUA,%20quiero%20informaci%C3%B3n.">💬 Hablar por WhatsApp</a></section>
    <footer>
        <h2>YESHUA</h2>
        <p>© CREADO POR J. ESPINOSA </p>
        <p>PARA CONTRATOS AL 3042215084 </p>

    </footer>
    <a class="float" target="_blank" href="https://wa.me/573203495777?text=Hola%20YESHUA,%20quiero%20informaci%C3%B3n.">💬</a>
</body>

</html>
