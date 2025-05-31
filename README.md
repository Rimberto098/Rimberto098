<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Farmacia FARMAFRED</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #2e7d32; /* Un verde más oscuro para el encabezado */
            color: white;
            padding: 15px 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        header h1 {
            margin: 0;
            font-size: 2.2em;
            display: inline-block;
            vertical-align: middle;
        }
        header .logo-icon {
            height: 40px; /* Ajusta el tamaño del icono */
            vertical-align: middle;
            margin-left: 10px;
        }
        nav {
            background-color: #388e3c; /* Un verde un poco más claro para la navegación */
            padding: 10px 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 0 15px;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #c8e6c9; /* Un verde muy claro al pasar el mouse */
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        h2 {
            color: #2e7d32;
            border-bottom: 3px solid #dcedc8;
            padding-bottom: 10px;
            margin-bottom: 20px;
            font-size: 1.8em;
        }
        h3 {
            color: #43a047;
            margin-top: 30px;
            margin-bottom: 15px;
            font-size: 1.5em;
        }
        .section-address {
            background-color: #e8f5e9;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
            font-weight: bold;
            color: #1b5e20;
        }
        .section-address p {
            margin: 0;
        }
        .vision-mission p {
            margin-bottom: 15px;
        }
        .products-offered table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        .products-offered th, .products-offered td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        .products-offered th {
            background-color: #e8f5e9;
            color: #2e7d32;
            font-weight: bold;
        }
        .products-offered td {
            background-color: #f9fdf9;
        }
        .inventory-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        .inventory-table th, .inventory-table td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        .inventory-table th {
            background-color: #c8e6c9;
            color: #1b5e20;
            font-weight: bold;
        }
        .inventory-table tbody tr:nth-child(even) {
            background-color: #f1f8e9;
        }
        .inventory-table tbody tr:hover {
            background-color: #e0f2f1;
        }
        .form-section {
            margin-top: 40px;
            background-color: #f9fdf9;
            padding: 30px;
            border-radius: 8px;
            border: 1px solid #e8f5e9;
        }
        .form-section .form-group {
            margin-bottom: 15px;
        }
        .form-section label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: #43a047;
        }
        .form-section input[type="text"],
        .form-section input[type="email"] {
            width: calc(100% - 22px);
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1em;
        }
        .form-section .radio-group label {
            display: inline-block;
            margin-right: 20px;
            font-weight: normal;
        }
        .form-section .checkbox-group label {
            display: inline-block;
            margin-right: 20px;
            font-weight: normal;
        }
        .form-section button {
            background-color: #4CAF50;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.1em;
            margin-right: 10px;
            transition: background-color 0.3s ease;
        }
        .form-section button:hover {
            background-color: #45a049;
        }
        .form-section button.cancel {
            background-color: #f44336;
        }
        .form-section button.cancel:hover {
            background-color: #da190b;
        }
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            background-color: #2e7d32;
            color: white;
            box-shadow: 0 -2px 5px rgba(0,0,0,0.2);
            font-size: 0.9em;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>👨🏻‍⚕️FARMAFRED💉 <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48cGdoL2Nvb3BzLz48cGF0aCBkPSJNOSAxNCA1IDE0IDUgMTloNGE0IDQgMCAwIDAgNC00di01eiI+PC9wYXRoPjxwYXRoIGQ9Ik0xOCAyMWwtMS0xLTctNy00LTRaIj48L3BhdGg+PHBhdGggZD0iTTEyIDZoNi41QTEuNSAxLjUgMCAwIDEgMjAgNy41VjExIj48L3BhdGg+PC9zdmc+" alt="" class="logo-icon"></h1>
    </header>

    <nav>
        <a href="#vision-mision">Quiénes Somos</a>
        <a href="#productos-ofrecidos">Nuestros Productos</a>
        <a href="#inventario">Inventario</a>
        
    </nav>

    <div class="container">
        <div class="section-address">
            <p><strong>Dirección:</strong> Cochabamba av. Km7</p>
        </div>

        <section id="vision-mision" class="vision-mission">
            <h2><span style="color: #4CAF50;">VISIÓN</span></h2>
            <p>La farmacia Farmafred en general, es un horizonte aspiracional que define el futuro deseado de la empresa. Para Farmafred, podría ser: ser la farmacia más confiable y accesible para la comunidad, ofreciendo medicamentos y servicios de salud de calidad, con un enfoque en la atención personalizada y la prevención.</p>

            <h2><span style="color: #4CAF50;">MISIÓN</span></h2>
            <p>En Farmafred es ayudar a las personas a mejorar su salud y lo hacemos asegurándonos de que usen sus medicamentos de forma correcta y ofreciendo un servicio de calidad más allá de entregar medicamentos, estamos acá para acompañar, orientar y cuidar a cada paciente, queremos ser parte del bienestar de nuestra comunidad, ayudando también a prevenir enfermedades y estando siempre disponibles para brindar el mejor consejo profesional.</p>
        </section>

        <section id="productos-ofrecidos" class="products-offered">
            <h2>PRODUCTOS QUE TE OFRECE LA FARMACIA FARMAFRED</h2>
            <table>
                <thead>
                    <tr>
                        <th>MARCA</th>
                        <th>NOMBRE</th>
                        <th>DESCRIPCIÓN</th>
                        <th>PRECIO (Bs)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Trébol</td>
                        <td>Aspirador nasal</td>
                        <td>Higiene nasal en los bebes y niños.</td>
                        <td>5</td>
                    </tr>
                    <tr>
                        <td>Bagó</td>
                        <td>Metagesic</td>
                        <td>analgésico y antiperetico</td>
                        <td>8</td>
                    </tr>
                    <tr>
                        <td>Inti</td>
                        <td>Batrom</td>
                        <td>antibiótico de amplio espectrol.</td>
                        <td>4</td>
                    </tr>
                    </tbody>
            </table>
        </section>

        <section id="inventario" class="inventory-section">
            <h2>Inventario de Productos de Farmacia</h2>
            <p>Aquí puedes consultar la disponibilidad y detalles de nuestros productos.</p>
            <table class="inventory-table">
                <thead>
                    <tr>
                        <th>ID Producto</th>
                        <th>Nombre</th>
                        <th>Principio Activo</th>
                        <th>Formato</th>
                        <th>Stock</th>
                        <th>Precio Unitario (Bs)</th>
                        <th>Fecha Vencimiento</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>P001</td>
                        <td>Paracetamol</td>
                        <td>Acetaminofén</td>
                        <td>Tabletas 500mg</td>
                        <td>250</td>
                        <td>5.50</td>
                        <td>2026-12-31</td>
                    </tr>
                    <tr>
                        <td>P002</td>
                        <td>Amoxicilina</td>
                        <td>Amoxicilina</td>
                        <td>Cápsulas 500mg</td>
                        <td>180</td>
                        <td>12.00</td>
                        <td>2025-08-15</td>
                    </tr>
                    <tr>
                        <td>P003</td>
                        <td>Ibuprofeno</td>
                        <td>Ibuprofeno</td>
                        <td>Tabletas 400mg</td>
                        <td>200</td>
                        <td>7.25</td>
                        <td>2027-03-20</td>
                    </tr>
                    <tr>
                        <td>P004</td>
                        <td>Omeprazol</td>
                        <td>Omeprazol</td>
                        <td>Cápsulas 20mg</td>
                        <td>120</td>
                        <td>15.00</td>
                        <td>2026-05-10</td>
                    </tr>
                    <tr>
                        <td>P005</td>
                        <td>Salbutamol</td>
                        <td>Salbutamol</td>
                        <td>Inhalador 100mcg</td>
                        <td>50</td>
                        <td>35.00</td>
                        <td>2025-11-01</td>
                    </tr>
                    <tr>
                        <td>P006</td>
                        <td>Loratadina</td>
                        <td>Loratadina</td>
                        <td>Tabletas 10mg</td>
                        <td>90</td>
                        <td>8.50</td>
                        <td>2027-01-25</td>
                    </tr>
                    <tr>
                        <td>P007</td>
                        <td>Vitamina C</td>
                        <td>Ácido Ascórbico</td>
                        <td>Tabletas 1000mg</td>
                        <td>300</td>
                        <td>10.00</td>
                        <td>2028-06-30</td>
                    </tr>
                    <tr>
                        <td>P008</td>
                        <td>Alcohol Antiséptico</td>
                        <td>Etanol</td>
                        <td>Frasco 500ml</td>
                        <td>75</td>
                        <td>20.00</td>
                        <td>2029-02-14</td>
                    </tr>
                    <tr>
                        <td>P009</td>
                        <td>Guantes de Látex</td>
                        <td>N/A</td>
                        <td>Caja de 100 unid.</td>
                        <td>40</td>
                        <td>45.00</td>
                        <td>N/A</td>
                    </tr>
                    <tr>
                        <td>P010</td>
                        <td>Termómetro Digital</td>
                        <td>N/A</td>
                        <td>Unidad</td>
                        <td>25</td>
                        <td>60.00</td>
                        <td>N/A</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section id="registro" class="form-section">
            <h2>REGISTRO DE DATOS PERSONALES</h2>
            <p>Por favor, complete el siguiente formulario para ponerse en contacto con nosotros o para recibir nuestras novedades.</p>
            <form action="#" method="post">
                <div class="form-group">
                    <label for="nombre">Nombre:</label>
                    <input type="text" id="nombre" name="nombre" required>
                </div>
                <div class="form-group">
                    <label for="apellido">Apellido:</label>
                    <input type="text" id="apellido" name="apellido" required>
                </div>
                <div class="form-group">
                    <label for="correo">Correo:</label>
                    <input type="email" id="correo" name="correo" required>
                </div>
                <div class="form-group">
                    <label>Género:</label>
                    <div class="radio-group">
                        <input type="radio" id="mujer" name="genero" value="mujer">
                        <label for="mujer">Mujer</label>
                        <input type="radio" id="varon" name="genero" value="varon">
                        <label for="varon">Varón</label>
                    </div>
                </div>
                <div class="form-group">
                    <label>Gustos:</label>
                    <div class="checkbox-group">
                        <input type="checkbox" id="facebook" name="gustos[]" value="facebook">
                        <label for="facebook">Facebook</label>
                        <input type="checkbox" id="tiktok" name="gustos[]" value="tiktok">
                        <label for="tiktok">TikTok</label>
                    </div>
                </div>
                <button type="submit">Registrar</button>
                <button type="reset" class="cancel">Cancelar</button>
            </form>
        </section>
    </div> 
</body>
</html>




