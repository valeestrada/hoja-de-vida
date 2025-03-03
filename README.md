<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Hoja de vida de Rebecca Pérez</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: rgb(244, 244, 244);
        }
        header {
            background-color: rgb(107, 142, 35);
            color: white;
            padding: 20px;
        }
        img {
            width: 150px;
            border-radius: 50%;
            margin-top: 10px;
        }
        table {
            width: 60%;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-collapse: collapse;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        td {
            padding: 10px;
        }
        .contacto i {
            margin-right: 8px;
        }
        button {
            background-color: rgb(107, 142, 35);
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: rgb(85, 107, 47);
        }
    </style>
</head>
<body>
    <header>
        <h1>Rebecca Pérez</h1>
        <img src="capybara.jpg" alt="Foto del Capibara">
    </header>
    <table>
        <tr><td><h2>Datos Personales</h2></td></tr>
        <tr><td><strong>Fecha de nacimiento:</strong> 30 de abril de 1996</td></tr>
        <tr><td><strong>Ciudad y país:</strong> Toronto, Canadá</td></tr>
        <tr><td><strong>Teléfono:</strong> +1 773 486 059</td></tr>
        <tr><td class="contacto"><i>&#9993;</i> rperez@gmail.com</td></tr>
        
        <tr><td><h2>Perfil Profesional</h2></td></tr>
        <tr><td>Soy una persona enfocada en el desarrollo de hoteles a través del mundo. Me interesa crear un ambiente armonioso en cualquier entorno laboral y mi meta es fomentar la colaboración y el bienestar.</td></tr>
        
        <tr><td><h2>Educación</h2></td></tr>
        <tr><td><strong>Toronto University</strong></td></tr>
        <tr><td>2014 - 2019</td></tr>
        <tr><td><strong>Grado obtenido:</strong> Licenciatura en Gestión Hotelera</td></tr>
        
        <tr><td><h2>Experiencia Laboral / Proyectos Escolares</h2></td></tr>
        <tr><td><strong>Proyecto: Restauración de Humedales</strong></td></tr>
        <tr><td>Participé en la restauración de ecosistemas de humedales, coordinando el monitoreo de fauna y flora. <br> <em>(2020 - 2021)</em></td></tr>
        
        <tr><td><strong>Trabajo: Embajador del Bienestar Animal</strong></td></tr>
        <tr><td>Realicé campañas educativas sobre la conservación de especies y la importancia del equilibrio ecológico. <br> <em>(2021 - 2022)</em></td></tr>
        
        <tr><td><h2>Habilidades</h2></td></tr>
        <tr><td>
            <ul>
                <li>Idiomas: Español C1, Inglés C1, Alemán B2, Mandarín B2 </li>
                <li>Conocimientos en neogcios turísticos </li>
                <li>Trabajo en equipo y liderazgo</li>
                <li>Resolución de problemas y creatividad</li>
            </ul>
        </td></tr>
        
        <tr><td><h2>Contacto</h2></td></tr>
        <tr><td><button onclick="window.location.href='cv_capibara.pdf'">Descargar Hoja de Vida</button></td></tr>
    </table>
</body>
</html>
