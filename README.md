<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MercPeople - Soluciones Integrales</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .service-card {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 20px;
            width: 300px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .service-card:hover {
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
        }
    </style>
</head>
<body>
    <header>
        <h1>MercPeople</h1>
        <p>Soluciones integrales para empresas y profesionales</p>
    </header>

    <nav>
        <a href="#nosotros">Nosotros</a>
        <a href="#servicios">Servicios</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <div class="container" id="nosotros">
        <h2>¿Quiénes somos?</h2>
        <p>MercPeople es una empresa especializada en brindar servicios empresariales y personales de alta calidad. Nuestro objetivo es impulsar el crecimiento empresarial y potenciar las habilidades de los profesionales mediante soluciones innovadoras y personalizadas.</p>
        <h3>Equipo Fundador</h3>
        <ul>
            <li><strong>Brenda Noelia Mercado Montoya:</strong> Experta en Recursos Humanos y Seguridad Laboral.</li>
            <li><strong>Herlinda Montoya Macías:</strong> Economista con más de 20 años de experiencia en el sector financiero.</li>
        </ul>
    </div>

    <div class="container" id="servicios">
        <h2>Servicios</h2>
        <div class="services">
            <div class="service-card">
                <h3>Constitución de Empresas</h3>
                <p>Te ayudamos a formalizar tu negocio con asesoría integral.</p>
            </div>
            <div class="service-card">
                <h3>Contabilidad</h3>
                <p>Gestiones contables mensuales y anuales para tu tranquilidad financiera.</p>
            </div>
            <div class="service-card">
                <h3>Recursos Humanos</h3>
                <p>Reclutamiento, nóminas y evaluaciones de desempeño personalizadas.</p>
            </div>
            <div class="service-card">
                <h3>Capacitaciones</h3>
                <p>Talleres en liderazgo, clima laboral, ventas y atención al cliente.</p>
            </div>
            <div class="service-card">
                <h3>Coaching Personal</h3>
                <p>Impulsa tu marca personal y crea un currículum impactante.</p>
            </div>
        </div>
    </div>

    <div class="container" id="contacto">
        <h2>Contacto</h2>
        <p><strong>Teléfono:</strong> +51 966 763 156</p>
        <p><strong>Correo electrónico:</strong> mercpeople.cusco@gmail.com</p>
        <p><strong>Instagram:</strong> <a href="https://www.instagram.com/merc.people" target="_blank">@merc.people</a></p>
    </div>

    <footer>
        <p>&copy; 2024 MercPeople. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
