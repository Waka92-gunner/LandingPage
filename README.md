# LandingPage
Desarrollo de una landing page sencilla, con botones para redireccionamiento a redes sociales, ubicación y contacto al whatsapp

# Paso 1: Configura tu proyecto
Abre VS Code.
Crea una carpeta nueva para tu proyecto (por ejemplo, landing-page).
Dentro de la carpeta, crea tres archivos:
index.html (estructura principal)
styles.css (estilos)
(Opcional) Una imagen (como logo.jpg) si quieres incluirla.

# Paso 2: Código HTML (index.html)

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <img src="logo.jpg" alt="Mi Logo" class="logo">
        <h1>¡Bienvenid@ a Mi Negocio!</h1>
        <p>Encuentra todo lo que necesitas aquí.</p>

        <a href="https://maps.google.com/?q=TU_UBICACION" target="_blank" class="button">Cómo llegar</a>
        <a href="https://instagram.com/TU_PERFIL" target="_blank" class="button">Instagram</a>
        <a href="https://facebook.com/TU_PERFIL" target="_blank" class="button">Facebook</a>
        <a href="https://wa.me/TU_NUMERO" target="_blank" class="button whatsapp">Chatea por WhatsApp</a>
    </div>
</body>
</html>

# Personaliza:

Cambia TU_UBICACION por el enlace de Google Maps (busca tu local, haz clic en "Compartir" y copia el enlace).
Reemplaza TU_PERFIL con los nombres de usuario de tus redes sociales (por ejemplo, https://instagram.com/mi_negocio).
Sustituye TU_NUMERO por tu número con código de país (ejemplo: https://wa.me/521234567890).
Si tienes una imagen, cámbiale el nombre a logo.jpg o ajusta la ruta en <img src="...">.

# Paso 3: Código CSS (styles.css)

Esto hará que tu página se vea bonita y sea responsive (funcione bien en celulares):

body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    text-align: center;
    padding: 20px;
}

.logo {
    width: 150px; /* Ajusta el tamaño de tu imagen */
    border-radius: 50%; /* Opcional: hace la imagen circular */
    margin-bottom: 20px;
}

h1 {
    font-size: 24px;
    color: #333;
    margin-bottom: 10px;
}

p {
    font-size: 16px;
    color: #666;
    margin-bottom: 30px;
}

.button {
    display: block;
    background-color: #007bff; /* Color azul, cámbialo a tu gusto */
    color: white;
    text-decoration: none;
    padding: 15px;
    margin: 10px auto;
    border-radius: 25px;
    width: 80%;
    max-width: 300px;
    font-size: 18px;
}

.button:hover {
    background-color: #0056b3; /* Color más oscuro al pasar el mouse */
}

.whatsapp {
    background-color: #25d366; /* Verde de WhatsApp */
}

.whatsapp:hover {
    background-color: #1da851;
}

# Personaliza:

Cambia los colores (background-color) por los de tu marca (usa códigos hexadecimales como #ff0000 para rojo).
Ajusta tamaños (width, font-size, etc.) si quieres algo más grande o pequeño.

# Paso 4: Prueba tu página
Guarda ambos archivos.
Abre index.html en tu navegador (haz doble clic o arrástralo a Chrome).
Revisa cómo se ve y prueba los enlaces. Si algo no funciona, verifica que los enlaces sean correctos.

# Paso 5: Sube tu landing page
Para que esté disponible como enlace en Instagram:

Usa un servicio gratuito como GitHub Pages, Netlify o 000webhost.
Netlify (recomendado): Arrastra tu carpeta a su sitio web, y te dará un enlace público en minutos.
Una vez tengas el enlace (ejemplo: https://mi-negocio.netlify.app), cópialo en tu bio de Instagram.
