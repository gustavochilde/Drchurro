<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dr. Churro - Fábrica de Churros Mayoristas</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background: #fff8f0;
      color: #4b2e0d;
    }
    header {
      background-color: #ff6600;
      color: white;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
    }
    .intro {
      padding: 20px;
      text-align: center;
    }
    .galeria {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }
    .galeria img {
      width: 300px;
      border-radius: 10px;
      box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
    }
    .contacto {
      background: #ffe0cc;
      padding: 20px;
      text-align: center;
    }
    .contacto form {
      display: flex;
      flex-direction: column;
      max-width: 400px;
      margin: auto;
    }
    .contacto input, .contacto textarea {
      margin: 10px 0;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .contacto button {
      background: #ff6600;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background: #4b2e0d;
      color: white;
      text-align: center;
      padding: 10px;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.3);
    }
    .whatsapp img {
      width: 35px;
      height: 35px;
    }
  </style>
</head>
<body>
  <header>
    <h1>DR. CHURRO</h1>
    <p>Fábrica de churros caseros - Solo para ventas mayoristas</p>
  </header>  <section class="intro">
    <p>Elaboramos churros simples, rellenos con dulce de leche y bañados en chocolate para comercios y panaderías. Consultanos para hacer tu pedido mayorista.</p>
  </section>  <section class="galeria">
    <img src="tu-imagen-1.jpg" alt="Churros simples">
    <img src="tu-imagen-2.jpg" alt="Churros rellenos">
    <img src="tu-imagen-3.jpg" alt="Churros bañados en chocolate">
  </section>  <section class="contacto">
    <h2>Hacé tu pedido</h2>
    <form action="#">
      <input type="text" placeholder="Nombre del comercio" required>
      <input type="text" placeholder="Localidad" required>
      <textarea placeholder="Detalle del pedido (cantidades, tipos de churros, etc.)" rows="4" required></textarea>
      <input type="tel" placeholder="Teléfono de contacto" required>
      <button type="submit">Enviar pedido</button>
    </form>
  </section>  <a class="whatsapp" href="https://wa.me/541122510017" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
  </a>  <footer>
    <p>Seguinos en Instagram: @doctorrchurro | WhatsApp: 1122510017 / 1123971018</p>
  </footer>
</body>
</html>
