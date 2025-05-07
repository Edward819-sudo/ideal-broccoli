# ideal-broccoli
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Venta de Computadora</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      max-width: 1200px;
      margin: 20px auto;
      background-color: white;
      padding: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .product-image {
      width: 100%;
      max-width: 500px;
      display: block;
      margin: 0 auto;
    }
    .product-details {
      text-align: center;
      margin-top: 20px;
    }
    .product-details h2 {
      margin-bottom: 10px;
    }
    .price {
      color: green;
      font-size: 24px;
      margin: 10px 0;
    }
    .buy-button {
      background-color: #28a745;
      color: white;
      padding: 15px 25px;
      text-decoration: none;
      font-size: 18px;
      border-radius: 5px;
    }
    .buy-button:hover {
      background-color: #218838;
    }
    .testimonials, .contact-form {
      margin-top: 40px;
    }
    .testimonial {
      background-color: #f0f0f0;
      padding: 15px;
      border-radius: 5px;
      margin-bottom: 10px;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    label {
      margin-top: 10px;
    }
    input, textarea {
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      margin-top: 15px;
      padding: 10px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 4px;
      font-size: 16px;
    }
    button:hover {
      background-color: #0056b3;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #333;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Venta de Computadoras</h1>
  </header>
  
  <div class="container">
    <img src="https://example.com/imagen-computadora.jpg" alt="Computadora de Alta Gama" class="product-image">
    <div class="product-details">
      <h2>Computadora Gamer X500</h2>
      <p>Procesador Intel Core i7, 16GB RAM, SSD 1TB, Tarjeta Gráfica RTX 3060</p>
      <p class="price">$1,200 USD</p>
      <a href="https://example.com/comprar" class="buy-button">Comprar Ahora</a>
    </div>

    <div class="testimonials">
      <h3>Testimonios</h3>
      <div class="testimonial">
        <p>"Esta computadora superó mis expectativas. ¡Ideal para juegos exigentes!" - Carlos M.</p>
      </div>
      <div class="testimonial">
        <p>"Excelente rendimiento y entrega rápida. Muy recomendable." - Laura G.</p>
      </div>
    </div>

    <div class="contact-form">
      <h3>Contáctanos</h3>
      <form action="#" method="post">
        <label for="name">Nombre:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Correo electrónico:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Mensaje:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Enviar</button>
      </form>
    </div>
  </div>

  <footer>
    <p>© 2025 Tienda de Tecnología. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
