<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title> Azure Horizon Charters - Fajardo, PR </title>
  <style>
    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-image: url('https://i.postimg.cc/c4bSrv24/image1.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;
      color: #003049;
    }
    header {
      background-color: rgba(0, 119, 182, 0.7);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    nav {
      background-color: rgba(2, 62, 138, 0.7);
      color: white;
      text-align: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
  section, .cta {
  background-color: rgba(255, 255, 255, 0.6);
  border-radius: 10px;
  padding: 40px 20px;
  margin: 20px auto;
  max-width: 900px;
    }
    border-radius: 10px;
    padding: 40px 20px;
    margin: 20px auto;
    max-width: 900px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
    }
    h2 {
      color: #0077b6;
    }
    .cta {
      background-color: rgba(0, 150, 199, 0.85);
      color: white;
      text-align: center;
    }
    .cta a {
      background: white;
      color: #0077b6;
      padding: 12px 20px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 6px;
    }
    footer {
      background-color: rgba(2, 62, 138, 0.7);
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
</style>
</head>
<body>
<header style="position: relative; text-align: center; color: white;">
  <img src="https://i.postimg.cc/448CSKJb/image0.jpg" 
       alt="Azure Horizon Charters" 
       style="width: 100%; height: auto; max-height: 500px; object-fit: cover;">
<div style="
        position: absolute; 
        top: 50%; left: 50%; 
        transform: translate(-50%, -50%);
        padding: -10px -10px;
        background: rgba(0,0,0,0.35);
        border-radius: 1px;">
  <h1 style="font-size: 3em; margin: 0;">Azure Horizon Charters</h1>
  <p style="font-size: 1.2em; margin-top: 10px;">
      Explora Icacos, Palomino, Vieques y Culebra desde Fajardo, Puerto Rico</p>
  </div>
</header>
  <nav>
    <a href="#servicios">Servicios</a>
    <a href="#precios">Precios</a>
    <a href="#contacto">Contacto</a>
  </nav>
  <section id="servicios">
    <h2>Sobre Nosotros</h2>
    <p>Descubre la belleza del Caribe con Azure Horizon Charters. Ofrecemos experiencias privadas en bote a destinos paradisíacos como Icacos, Palomino, Vieques y Culebra. Disfruta de aguas cristalinas, playas escondidas, buena música, bebidas frías y atardeceres inolvidables.</p>
  </section>
  <section id="precios">
    <h2>Paquetes &amp; Precios</h2>
    <ul>
      <li><strong>4 horas:</strong> $450 en semana (Lunes a Jueves) / $550 fines de semana (Viernes a Domingo) <br><em>No incluye comida ni cervezas locales</em></li>
      <li><strong>6 horas:</strong> $550 en semana / $650 fines de semana<br><em>Incluye comida y cervezas locales</em></li>
      <li><strong>Culebra o Vieques (7 hrs):</strong> $1,350</li>
      <li><strong>Depósito requerido:</strong> $200</li>
    *Máximo de 6 personas por embarcación 
    </ul>
  </section>
  <section class="cta">
  <h2>¡Reserva tu aventura en el mar hoy!</h2>
  <p>Experiencias personalizadas, privacidad y atención de primera.</p>
  <a href="https://wa.me/17874734037?text=Hola%2C%20me%20gustaría%20reservar%20una%20charter%20con%20Azure%20Horizon" target="_blank">Reservar por WhatsApp</a>
</section>
  <section id="contacto">
    <h2>Contacto</h2>
    <p>📞 <strong>Teléfono:</strong> <a href="tel:+17874734037">787-473-4037</a></p>
    <p>📧 <strong>Email:</strong> <a href="mailto:j.gm13@hotmail.com">j.gm13@hotmail.com</a></p>
    <p>📍 Fajardo, Puerto Rico</p>
    
  <h2>Reservar por WhatsApp</h2>
<form onsubmit="enviarWhatsApp(event)">
  <label>Nombre:<br><input type="text" id="nombre" required></label><br><br>
  <label>Fecha deseada:<br><input type="date" id="fecha" required></label><br><br>
  <label>Duración:<br>
    <select id="duracion" required>
      <option value="4 horas">4 horas</option>
      <option value="6 horas">6 horas</option>
      <option value="7 horas (Culebra o Vieques)">7 horas (Culebra o Vieques)</option>
       </select>
  </label><br><br>  
  <label>Personas:<br><input type="number" id="personas" required></label><br><br>
  <label>Comentarios:<br><textarea id="comentarios" rows="4"></textarea></label><br><br>
  <button type="submit" style="
    background: #25D366;
    color: white;
    border: none;
    padding: 12px 24px;
    font-size: 16px;
    font-weight: bold;
    border-radius: 6px;
    cursor: pointer;
  ">
    Reservar por WhatsApp
  </button>
</form>

<script>
  function enviarWhatsApp(event) {
    event.preventDefault();
    const nombre = document.getElementById('nombre').value;
    const fecha = document.getElementById('fecha').value;
    const duracion = document.getElementById('duracion').value;
    const personas = document.getElementById('personas').value;
    const comentarios = document.getElementById('comentarios').value;

    const mensaje = `Hola, me gustaría reservar con Azure Horizon Charters.%0A` +
                    `*Nombre:* ${nombre}%0A` +
                    `*Fecha:* ${fecha}%0A` +
                    `*Personas:* ${personas}%0A` +
                    `*Comentarios:* ${comentarios}`;
    
    const url = `https://wa.me/17874734037?text=${mensaje}`;
    window.open(url, '_blank');
  }
</script>

 <footer>
  <div style="display: flex; align-items: center; justify-content: center; gap: 10px;">
    <img src="https://i.postimg.cc/wMWy3n1r/Azure-Logo.jpg" alt="Logo Azure Horizon" style="height: 40px;">
    <span>© 2025 Azure Horizon Charters. Todos los derechos reservados.</span>
  </div>
</footer>
