<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>etama — Eventos privados</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,500;0,600;0,700;1,500&family=Instrument+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>

  :root{
    --bg-cream: #EFE8D8;
    --bg-cream-light: #F7F2E6;
    --card-bg: #F7F2E6;
    --sage: #9CC0B1;
    --teal: #53A49A;
    --ink: #1B3128;
    --ink-dim: #5C6B62;
    --accent: #2F6F63;
    --line: rgba(27,49,40,0.16);
    --serif: "Lora", Georgia, serif;
    --sans: "Instrument Sans", -apple-system, sans-serif;
  }

  *{ margin:0; padding:0; box-sizing:border-box; }

  body{
    background: var(--bg-cream);
    font-family: var(--sans);
    color: var(--ink);
  }

  .eventos-section{
    position: relative;
    padding: 120px 24px 100px;
    background:
      radial-gradient(ellipse 900px 500px at 50% -10%, rgba(83,164,154,0.10), transparent 60%),
      linear-gradient(180deg, #F7F2E6 0%, #EFE8D8 45%, #E9E1CE 100%);
    overflow: hidden;
    isolation: isolate;
  }

  /* faint table-grain texture, echoes the wood table in the flyer photo */
  .eventos-section::before{
    content:"";
    position:absolute; inset:0;
    z-index:-1;
    opacity:0.035;
    background-image: repeating-linear-gradient(90deg, #1B3128 0px, transparent 1px 3px);
    mix-blend-mode: multiply;
  }

  .eventos-wrap{
    max-width: 620px;
    margin: 0 auto;
    text-align: center;
  }

  /* --- mark: three stacked lentil/leaf shapes, echoing the flyer logo --- */
  .mark{
    margin: 0 auto 30px;
    width: 84px;
  }
  .mark img{
    display:block;
    width: 100%;
    height: auto;
  }

  .eyebrow{
    font-family: var(--sans);
    font-size: 12.5px;
    letter-spacing: 0.32em;
    text-transform: uppercase;
    color: var(--accent);
    font-weight: 500;
    margin-bottom: 22px;
  }

  h1{
    font-family: var(--serif);
    font-weight: 700;
    font-size: clamp(34px, 5.4vw, 52px);
    line-height: 1.14;
    color: var(--ink);
    letter-spacing: -0.01em;
    margin-bottom: 30px;
  }

  .rule{
    width: 64px;
    height: 1px;
    background: var(--line);
    margin: 0 auto 34px;
  }

  .lede{
    font-size: 17px;
    line-height: 1.65;
    color: var(--ink-dim);
    max-width: 440px;
    margin: 0 auto 14px;
  }

  .kicker{
    font-family: var(--serif);
    font-style: italic;
    font-weight: 500;
    font-size: 17px;
    color: var(--accent);
    margin: 34px 0 6px;
  }

  .sub{
    font-size: 15px;
    color: var(--ink-dim);
    margin-bottom: 56px;
  }

  /* ---------- form card ---------- */
  .card{
    text-align: left;
    background: var(--card-bg);
    border: 1px solid var(--line);
    border-radius: 4px;
    padding: 40px clamp(20px, 5vw, 48px);
    box-shadow: 0 20px 50px -20px rgba(27,49,40,0.18);
  }

  .field{
    margin-bottom: 26px;
  }

  .field label{
    display:block;
    font-size: 11.5px;
    letter-spacing: 0.16em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 10px;
    font-weight: 500;
  }

  .row{
    display:grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }

  input[type="text"],
  input[type="email"],
  input[type="tel"],
  input[type="date"],
  select,
  textarea{
    width: 100%;
    background: transparent;
    border: none;
    border-bottom: 1px solid var(--line);
    color: var(--ink);
    font-family: var(--sans);
    font-size: 15.5px;
    padding: 10px 2px;
    outline: none;
    transition: border-color 0.25s ease;
  }

  input::placeholder, textarea::placeholder{ color: rgba(27,49,40,0.35); }

  input:focus, select:focus, textarea:focus{
    border-color: var(--sage);
  }

  select{
    appearance: none;
    -webkit-appearance: none;
    background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='12' height='8'><path d='M1 1l5 5 5-5' stroke='%232F6F63' stroke-width='1.4' fill='none'/></svg>");
    background-repeat: no-repeat;
    background-position: right 4px center;
    cursor: pointer;
  }
  select option{ background: #F7F2E6; color: var(--ink); }

  textarea{ resize: vertical; min-height: 84px; line-height: 1.5; }

  /* signature: table-for-N party size selector, replaces a generic number input */
  .party{
    display:flex;
    align-items:center;
    gap: 14px;
  }
  .party-track{
    display:flex;
    gap: 8px;
    flex: 1;
    flex-wrap: wrap;
  }
  .seat{
    width: 30px; height: 30px;
    border-radius: 50%;
    border: 1px solid var(--line);
    background: transparent;
    color: var(--ink-dim);
    font-family: var(--sans);
    font-size: 12.5px;
    cursor: pointer;
    display:flex; align-items:center; justify-content:center;
    transition: all 0.2s ease;
  }
  .seat:hover{ border-color: var(--teal); color: var(--ink); }
  .seat.active{
    background: var(--teal);
    border-color: var(--teal);
    color: #F7F2E6;
    font-weight: 600;
  }
  .party-count{
    font-family: var(--serif);
    font-size: 15px;
    color: var(--accent);
    white-space: nowrap;
    min-width: 74px;
    text-align: right;
  }

  .submit-btn{
    width: 100%;
    margin-top: 12px;
    padding: 16px;
    background: var(--teal);
    color: #F7F2E6;
    border: none;
    border-radius: 3px;
    font-family: var(--sans);
    font-size: 14px;
    font-weight: 600;
    letter-spacing: 0.04em;
    cursor: pointer;
    transition: transform 0.15s ease, background 0.2s ease;
  }
  .submit-btn:hover{ background: #438178; transform: translateY(-1px); }
  .submit-btn:active{ transform: translateY(0); }

  .form-note{
    text-align:center;
    font-size: 12.5px;
    color: var(--ink-dim);
    opacity: 0.85;
    margin-top: 16px;
  }

  .confirm{
    display:none;
    text-align:center;
    padding: 30px 10px 6px;
  }
  .confirm.show{ display:block; }
  .card.hidden-form .form-body{ display:none; }
  .confirm p.big{
    font-family: var(--serif);
    font-size: 20px;
    color: var(--ink);
    margin-bottom: 8px;
  }
  .confirm p.small{ font-size: 14px; color: var(--ink-dim); }

  /* ---------- footer strip ---------- */
  .footer{
    margin-top: 64px;
    text-align:center;
  }
  .footer .addr{
    font-size: 12px;
    letter-spacing: 0.22em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 30px;
  }
  .footer .brand{
    font-family: var(--serif);
    font-size: 26px;
    color: var(--ink);
    margin-bottom: 8px;
  }
  .footer .handle{
    font-size: 12px;
    letter-spacing: 0.2em;
    color: var(--ink-dim);
    margin-bottom: 10px;
  }
  .footer .tagline{
    font-family: var(--serif);
    font-style: italic;
    font-size: 14px;
    color: var(--accent);
  }

  /* reveal-on-scroll, restrained: one gentle fade+rise, no scattered effects */
  .reveal{
    opacity: 0;
    transform: translateY(16px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .reveal.in{ opacity: 1; transform: translateY(0); }

  @media (prefers-reduced-motion: reduce){
    .reveal{ opacity:1; transform:none; transition:none; }
  }

  @media (max-width: 480px){
    .row{ grid-template-columns: 1fr; }
    .card{ padding: 30px 20px; }
  }
</style>
</head>
<body>

<section class="eventos-section">
  <div class="eventos-wrap">

    <div class="mark reveal"><img src="data:image/png;base64,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" alt="Isotipo etama"></div>
    <div class="eyebrow reveal">Eventos privados</div>
    <h1 class="reveal">Reserva el local<br>entero para tu grupo.</h1>
    <div class="rule reveal"></div>

    <p class="lede reveal">
      Comidas de grupo, celebraciones y encuentros con menú cerrado.
      Adaptamos los platos a cada mesa.
    </p>
    <p class="lede reveal">Disponible fuera del horario de sala.</p>

    <p class="kicker reveal">Contadnos qué tenéis en mente.</p>
    <p class="sub reveal">Completad el formulario y os respondemos en menos de 48h.</p>

    <div class="card reveal" id="card">
      <div class="form-body" id="formBody">
        <form id="eventForm" action="https://formsubmit.co/ajax/gaetanomans92@gmail.com" method="POST">
          <input type="hidden" name="_subject" value="Nueva solicitud de evento — etama">
          <input type="hidden" name="_template" value="table">
          <div class="row">
            <div class="field">
              <label for="nombre">Nombre</label>
              <input type="text" id="nombre" name="nombre" placeholder="¿Cómo os llamáis?" required>
            </div>
            <div class="field">
              <label for="contacto">Teléfono o email</label>
              <input type="text" id="contacto" name="contacto" placeholder="Para responderos" required>
            </div>
          </div>

          <div class="row">
            <div class="field">
              <label for="fecha">Fecha</label>
              <input type="date" id="fecha" name="fecha" required>
            </div>
            <div class="field">
              <label for="motivo">Tipo de encuentro</label>
              <select id="motivo" name="motivo">
                <option>Comida de grupo</option>
                <option>Celebración</option>
                <option>Evento de empresa</option>
                <option>Otro</option>
              </select>
            </div>
          </div>

          <div class="field">
            <label>Número de personas</label>
            <div class="party">
              <div class="party-track" id="partyTrack"></div>
              <div class="party-count" id="partyCount">12 personas</div>
              <input type="hidden" id="personas" name="personas" value="12">
            </div>
          </div>

          <div class="field">
            <label for="mensaje">Contadnos qué tenéis en mente</label>
            <textarea id="mensaje" name="mensaje" placeholder="Horario preferido, alergias, ideas para el menú…"></textarea>
          </div>

          <button type="submit" class="submit-btn">Enviar solicitud</button>
          <p class="form-note">También podéis escribirnos por DM a @etamabcn</p>
        </form>
      </div>

      <div class="confirm" id="confirm">
        <p class="big" id="confirmTitle">Solicitud enviada.</p>
        <p class="small" id="confirmText">Gracias — os contestamos en menos de 48h para cerrar los detalles.</p>
      </div>
    </div>

    <div class="footer reveal">
      <div class="addr">Passatge Còrsega 3 · El Clot</div>
      <div class="brand">etama</div>
      <div class="handle">@etamabcn</div>
      <div class="tagline">comer saludable, no es complicado</div>
    </div>

  </div>
</section>

<script>
  // party-size selector: 2–24, step 2 — a table-setting rather than a generic number input
  const track = document.getElementById('partyTrack');
  const countLabel = document.getElementById('partyCount');
  const sizes = [2,4,6,8,10,12,16,20,24];
  let selected = 12;

  function renderSeats(){
    track.innerHTML = '';
    sizes.forEach(n => {
      const b = document.createElement('button');
      b.type = 'button';
      b.className = 'seat' + (n === selected ? ' active' : '');
      b.textContent = n;
      b.setAttribute('aria-label', n + ' personas');
      b.addEventListener('click', () => {
        selected = n;
        renderSeats();
        document.getElementById('personas').value = selected;
      });
      track.appendChild(b);
    });
    countLabel.textContent = selected + ' personas';
  }
  renderSeats();

  // real submit -> POSTs to FormSubmit, que reenvía cada solicitud a gaetanomans92@gmail.com
  const form = document.getElementById('eventForm');
  const submitBtn = form.querySelector('.submit-btn');

  form.addEventListener('submit', async function(e){
    e.preventDefault();
    submitBtn.disabled = true;
    submitBtn.textContent = 'Enviando…';

    try{
      const res = await fetch(form.action, {
        method: 'POST',
        body: new FormData(form),
        headers: { 'Accept': 'application/json' }
      });

      document.getElementById('formBody').style.display = 'none';
      const confirm = document.getElementById('confirm');

      if (res.ok){
        document.getElementById('confirmTitle').textContent = 'Solicitud enviada.';
        document.getElementById('confirmText').textContent = 'Gracias — os contestamos en menos de 48h para cerrar los detalles.';
      } else {
        document.getElementById('confirmTitle').textContent = 'Algo ha fallado.';
        document.getElementById('confirmText').textContent = 'Escribidnos directamente por DM a @etamabcn mientras lo revisamos.';
      }
      confirm.classList.add('show');

    } catch(err){
      document.getElementById('formBody').style.display = 'none';
      document.getElementById('confirmTitle').textContent = 'Algo ha fallado.';
      document.getElementById('confirmText').textContent = 'Escribidnos directamente por DM a @etamabcn mientras lo revisamos.';
      document.getElementById('confirm').classList.add('show');
    }
  });

  // gentle scroll reveal, respects reduced motion via CSS above
  const io = new IntersectionObserver((entries) => {
    entries.forEach(en => { if (en.isIntersecting) en.target.classList.add('in'); });
  }, { threshold: 0.15 });
  document.querySelectorAll('.reveal').forEach(el => io.observe(el));
</script>

</body>
</html>
