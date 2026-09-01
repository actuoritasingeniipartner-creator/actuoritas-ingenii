[index.html](https://github.com/user-attachments/files/31713994/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Actuoritas Ingenii - Growth Partner</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
    body { background: #0a0a0f; color: #fff; }
    .hero { min-height: 80vh; display: flex; justify-content: center; align-items: center; text-align: center; padding: 2rem; background: linear-gradient(135deg, #1a0f2e 0%, #0a0a0f 100%); }
    .logo-img { max-width: 350px; margin-bottom: 1rem; filter: drop-shadow(0 0 30px rgba(139, 92, 246, 0.6)); }
    .hero h1 { font-size: 3rem; color: #fbbf24; margin-bottom: 0.5rem; text-shadow: 0 0 20px rgba(251, 191, 36, 0.5); letter-spacing: 3px; }
    .hero p { font-size: 1.2rem; color: #06b6d4; letter-spacing: 5px; text-transform: uppercase; margin-bottom: 1.5rem; }
    .hero button { padding: 1rem 2rem; background: #8b5cf6; color: #fff; border: none; border-radius: 8px; cursor: pointer; font-size: 1rem; transition: all 0.3s; }
    .hero button:hover { background: #7c3aed; transform: translateY(-2px); }
    .social-buttons { display: flex; gap: 1rem; justify-content: center; margin-top: 1.5rem; flex-wrap: wrap; }
    .social-btn { display: inline-flex; align-items: center; gap: 0.5rem; padding: 0.8rem 1.5rem; border-radius: 8px; text-decoration: none; color: #fff; font-weight: 600; transition: all 0.3s ease; font-size: 0.95rem; }
    .social-btn span { font-size: 1.2rem; }
    .social-btn.whatsapp { background: #25D366; }
    .social-btn.whatsapp:hover { background: #128C7E; transform: translateY(-2px); }
    .social-btn.instagram { background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%); }
    .social-btn.instagram:hover { transform: translateY(-2px); }
    .social-btn.facebook { background: #1877F2; }
    .social-btn.facebook:hover { background: #166fe5; transform: translateY(-2px); }
    .about { padding: 4rem 2rem; text-align: center; background: #15151f; }
    .about h2 { font-size: 2.5rem; color: #fbbf24; margin-bottom: 1.5rem; }
    .about-text { max-width: 800px; margin: 0 auto; font-size: 1.1rem; line-height: 1.8; color: #cbd5e1; }
    .about-text strong { color: #8b5cf6; }
    .newsletter { padding: 4rem 2rem; text-align: center; background: #0f0f18; border-top: 1px solid rgba(139, 92, 246, 0.2); border-bottom: 1px solid rgba(139, 92, 246, 0.2); }
    .newsletter h2 { font-size: 2.2rem; color: #fbbf24; margin-bottom: 1.5rem; }
    .chat-section { padding: 4rem 2rem; max-width: 700px; margin: auto; }
    .chat-section h2 { text-align: center; margin-bottom: 2rem; color: #fbbf24; }
    #chat-box { background: #1e1e2e; border-radius: 12px; padding: 1rem; min-height: 300px; max-height: 400px; overflow-y: auto; margin-bottom: 1rem; }
    .message-row { display: flex; gap: 0.8rem; margin: 0.5rem 0; align-items: flex-end; }
    .message-row.user { flex-direction: row-reverse; }
    .avatar { font-size: 1.5rem; }
    .bubble { padding: 0.8rem 1.2rem; border-radius: 12px; max-width: 75%; }
    .message-row.bot .bubble { background: #1e1e2e; border: 1px solid #8b5cf6; }
    .message-row.user .bubble { background: #7c3aed; color: #fff; }
    #chat-form { display: flex; gap: 0.5rem; }
    #chat-form input { flex: 1; padding: 0.9rem; border-radius: 8px; border: 1px solid #8b5cf6; background: #0a0a0f; color: #fff; }
    #chat-form button { padding: 0.9rem 1.5rem; background: #8b5cf6; color: #fff; border: none; border-radius: 8px; cursor: pointer; }
    footer { text-align: center; padding: 2rem; color: #94a3b8; border-top: 1px solid #1e1e2e; }
    @media (max-width: 768px) {
      .hero h1 { font-size: 2.2rem; }
      .about-text, .newsletter .about-text { text-align: center !important; padding: 0 1.5rem; }
      .social-buttons { flex-direction: column; align-items: center; }
      .social-btn { width: 80%; justify-content: center; }
    }
  </style>
</head>
<body>

  <header class="hero">
    <div>
      <img src="https://i.imgur.com/8vDhPrN.png" alt="Actuoritas Ingenii" class="logo-img">
      <h1>Actuoritas Ingenii</h1>
      <p>Growth Partner</p>
      <button onclick="document.getElementById('chat').scrollIntoView({behavior: 'smooth'})">Hablar con el agente</button>
      
      <div class="social-buttons">
        <!-- Emojis restaurados -->
        <a href="https://wa.me/522219294171?text=Hola%20Actuoritas%20Ingenii" target="_blank" class="social-btn whatsapp">
          <span>📱</span> WhatsApp
        </a>
        <a href="https://www.instagram.com/act.ing.par.001/" target="_blank" class="social-btn instagram">
          <span>📷</span> Instagram
        </a>
        <a href="https://www.facebook.com/actuatoritas.ingenii.partner" target="_blank" class="social-btn facebook">
          <span>👍</span> Facebook
        </a>
      </div>
    </div>
  </header>

  <section class="about">
    <h2>¿Quiénes somos?</h2>
    <p class="about-text">
      Somos <strong>Actuoritas Ingenii</strong>, tu aliado estratégico en crecimiento. 
      Nos especializamos en transformar negocios mediante Inteligencia Artificial, 
      automatización de procesos y Landing Pages de alto impacto.
    </p>
  </section>

  <section class="newsletter">
    <h2>¡El arte de dejar de construir!</h2>
    <p class="about-text">
      Para empezar a diseñar imperios, construir una empresa desde cero es un acto de valentía.<br>
      Pero llevarla a su máximo potencial, sin perder el control ni la esencia... eso requiere algo más que trabajo duro.<br><br>
      En la antigua Roma, el éxito y el dominio no se dejaban al azar. Se sostenían sobre principios inquebrantables. Hoy, esos principios inspiran nuestro nombre y la razón de nuestra existencia:<br><br>
      🏛️ <strong>Actuoritas (Prestigio).</strong> La autoridad que no se impone, sino que se gana por resultados, visión y solidez.<br>
      🧠 <strong>Ingenii (Mente).</strong> La agudeza intelectual, la sabiduría para ver las oportunidades donde otros solo ven obstáculos.<br>
      🤝 <strong>Partner (Aliado).</strong> Porque la historia nos ha enseñado que ningún gran imperio se construyó en soledad.
    </p>
  </section>

  <section id="chat" class="chat-section">
    <h2>Habla con nuestro agente</h2>
    <div id="chat-box">
      <div class="message-row bot">
        <div class="avatar">🤖</div>
        <div class="bubble">¡Hola! Soy el agente de Actuoritas Ingenii. ¿En qué te ayudo?</div>
      </div>
    </div>
    <form id="chat-form">
      <input type="text" id="user-input" placeholder="Escribe tu mensaje..." required>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>© 2026 Actuoritas Ingenii - Growth Partner</p>
  </footer>

  <script>
    const chatBox = document.getElementById('chat-box');
    const form = document.getElementById('chat-form');
    const input = document.getElementById('user-input');

    function addMessage(text, sender) {
      const row = document.createElement('div');
      row.className = 'message-row ' + sender;
      const avatar = document.createElement('div');
      avatar.className = 'avatar';
      avatar.textContent = sender === 'user' ? '👤' : '🤖';
      const bubble = document.createElement('div');
      bubble.className = 'bubble';
      bubble.textContent = text;
      row.appendChild(avatar);
      row.appendChild(bubble);
      chatBox.appendChild(row);
      chatBox.scrollTop = chatBox.scrollHeight;
    }

    form.addEventListener('submit', function(e) {
      e.preventDefault();
      const userText = input.value.trim();
      if (!userText) return;

      addMessage(userText, 'user');
      input.value = '';

      const loadingRow = document.createElement('div');
      loadingRow.className = 'message-row bot';
      loadingRow.innerHTML = '<div class="avatar">🤖</div><div class="bubble">Pensando...</div>';
      chatBox.appendChild(loadingRow);
      chatBox.scrollTop = chatBox.scrollHeight;

      setTimeout(function() {
        chatBox.removeChild(loadingRow);
        let reply = "";
        const texto = userText.toLowerCase();

        if (texto.includes("hola") || texto.includes("buenas") || texto.includes("hey")) {
          reply = "¡Hola! 👋 Soy el agente de Actuoritas Ingenii. ¿En qué puedo ayudarte?";
        } else if (texto.includes("precio") || texto.includes("cuesta") || texto.includes("costo")) {
          reply = "💰 Tenemos 3 planes: Básico (0€), Profesional (49€/mes) y Enterprise (149€/mes). ¿Cuál te interesa?";
        } else if (texto.includes("servicio") || texto.includes("hacen") || texto.includes("ofrecen")) {
          reply = "🚀 Ofrecemos: Landing Pages con IA, Agentes Inteligentes 24/7, Automatización de procesos y Estrategias de crecimiento.";
        } else if (texto.includes("contacto") || texto.includes("email") || texto.includes("whatsapp")) {
          reply = "📧 Escríbenos por WhatsApp (botón arriba) o a contacto@actuoritas.com";
        } else if (texto.includes("gracias")) {
          reply = "¡De nada! 😊 Estamos aquí para ayudarte.";
        } else {
          reply = "🤔 Entiendo. Para darte la mejor respuesta, haz clic en el botón de WhatsApp arriba y un Growth Partner te contactará.";
        }
        addMessage(reply, 'bot');
      }, 1000);
    });
  </script>

</body>
</html>
