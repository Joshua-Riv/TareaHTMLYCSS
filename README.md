<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Sitio Web - Tarea HTML5 y CSS3</title>
    <link href="NewFolder1/Estilo.css" rel="stylesheet" />
</head>
<body>

    <header>
        <div class="logo">
            <h1>Desarrollo Web Pro</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#nosotros">Nosotros</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main class="container">
        
        <section id="inicio" class="hero">
            <h2>Bienvenido a la Plataforma de Aprendizaje</h2>
            <p>Este sitio ha sido desarrollado para demostrar el dominio de las tecnologías fundamentales de la web: HTML5 para la estructuración semántica del contenido y CSS3 para el diseño visual, maquetación y adaptabilidad de la interfaz de usuario.</p>
            
            <svg class="placeholder-img" width="100%" height="250" viewBox="0 0 800 250" xmlns="http://www.w3.org/2000/svg">
                <rect width="100%" height="100%" fill="#1e293b"/>
                <text x="50%" y="50%" fill="#ffffff" font-family="Arial, sans-serif" font-size="24" text-anchor="middle" dominant-baseline="middle">Tecnologías Web: HTML5 & CSS3</text>
            </svg>
            <img src="Imagen/ceo-adalah.jpg" />
        </section>
        

        <section id="servicios">
            <h2>Nuestros Servicios Core</h2>
            <p>Ofrecemos soluciones integrales basadas en estándares modernos para asegurar un rendimiento óptimo, accesibilidad universal y una experiencia de usuario fluida e intuitiva en cualquier dispositivo.</p>
            
            <h3>Beneficios Clave</h3>
            <ul>
                <li>Optimización completa de motores de búsqueda (SEO) mediante el uso de etiquetas semánticas nativas.</li>
                <li>Estructuras de diseño altamente adaptables y modernas utilizando módulos avanzados como Flexbox.</li>
                <li>Hojas de estilo limpias, modulares y fáciles de mantener a lo largo del tiempo.</li>
                <li>Garantía de total compatibilidad entre múltiples navegadores y plataformas web modernas.</li>
                <li>Optimización avanzada del rendimiento de carga para mejorar la retención de usuarios.</li>
            </ul>
        </section>

        <section id="nosotros">
            <h2>Sobre Nosotros y las Competencias</h2>
            <p>Somos un equipo enfocado en la excelencia técnica. A través de este proyecto práctico, consolidamos las bases de la ingeniería web, aplicando las mejores directrices de la industria informática para lograr un código limpio, estructurado y semánticamente correcto.</p>
            
            <h3>Matriz de Tecnologías y Roles</h3>
            <table>
                <thead>
                    <tr>
                        <th>Tecnología</th>
                        <th>Propósito Principal</th>
                        <th>Estado de Implementación</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>HTML5</td>
                        <td>Estructura y Semántica</td>
                        <td>100% Completado</td>
                    </tr>
                    <tr>
                        <td>CSS3</td>
                        <td>Estilos Básicos y Flexbox</td>
                        <td>100% Completado</td>
                    </tr>
                    <tr>
                        <td>Diseño Web</td>
                        <td>Experiencia de Usuario</td>
                        <td>Optimizado</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section id="contacto">
            <h2>Formulario de Contacto</h2>
            <form action="#" method="POST" class="contact-form">
                <div class="form-group">
                    <label for="nombre">Nombre:</label>
                    <input type="text" id="nombre" name="nombre" placeholder="Escriba su nombre completo" required>
                </div>
                
                <div class="form-group">
                    <label for="correo">Correo electrónico:</label>
                    <input type="email" id="correo" name="correo" placeholder="ejemplo@correo.com" required>
                </div>
                
                <div class="form-group">
                    <label for="mensaje">Mensaje:</label>
                    <textarea id="mensaje" name="mensaje" rows="5" placeholder="Escriba su consulta o mensaje aquí..." required></textarea>
                </div>
                
                <button type="submit" class="btn-submit">Enviar</button>
            </form>
        </section>

    </main>

    <footer>
        <p><strong>Curso:</strong> Programacion ll | <strong>Estudiante:</strong> Joshua Rivera Ramos | <strong>Fecha:</strong> Junio 2026</p>
    </footer>
</body>
</html>
