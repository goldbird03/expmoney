<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Iniciar sesión | ExpandeBot</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Sora:wght@400;500;600;700;800&family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg: #08090d;
    --bg-soft: #0e1016;
    --surface: #12141c;
    --surface-2: #171a24;
    --border: rgba(255,255,255,0.08);
    --text: #f2f4f8;
    --muted: #8c93a4;
    --muted-2: #5f6576;
    --brand: #29e07a;
    --violet: #7c6cff;
    --amber: #ffb454;
    --font-display: 'Sora', sans-serif;
    --font-body: 'Inter', sans-serif;
    --font-mono: 'JetBrains Mono', monospace;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  body{
    background:var(--bg);color:var(--text);font-family:var(--font-body);
    -webkit-font-smoothing:antialiased; min-height:100vh; overflow-x:hidden;
  }
  a{color:inherit;text-decoration:none;}
  ::selection{background:var(--brand);color:#04140b;}

  .grain{
    position:fixed;inset:0;pointer-events:none;z-index:2;opacity:.035;
    background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='120' height='120'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
  }
  .bg-grid{
    position:fixed;inset:0;z-index:0;pointer-events:none;
    background-image:
      linear-gradient(rgba(255,255,255,0.035) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,0.035) 1px, transparent 1px);
    background-size:64px 64px;
    -webkit-mask-image:radial-gradient(ellipse 70% 60% at 20% 30%, black 10%, transparent 70%);
    mask-image:radial-gradient(ellipse 70% 60% at 20% 30%, black 10%, transparent 70%);
  }
  .spotlight{
    position:fixed;inset:0;z-index:1;pointer-events:none;
    background:radial-gradient(600px circle at var(--x,30%) var(--y,30%), rgba(41,224,122,0.10), transparent 60%);
    transition:background .15s ease-out;
  }

  .shell{position:relative;z-index:3;min-height:100vh;display:grid;grid-template-columns:1.1fr 1fr;}
  @media (max-width:960px){.shell{grid-template-columns:1fr;}}

  /* ---------- left brand panel ---------- */
  .brand-panel{
    padding:56px 64px;display:flex;flex-direction:column;justify-content:space-between;
    border-right:1px solid var(--border);
    position:relative;overflow:hidden;
  }
  @media (max-width:960px){.brand-panel{border-right:none;border-bottom:1px solid var(--border);padding:40px 32px;}}

  .logo{font-family:var(--font-display);font-weight:700;font-size:19px;display:flex;align-items:center;gap:8px;}
  .logo .dot{width:8px;height:8px;border-radius:50%;background:var(--brand);box-shadow:0 0 12px var(--brand);}

  .brand-copy{max-width:460px;margin-top:10px;}
  .eyebrow{
    display:inline-flex;align-items:center;gap:8px;font-family:var(--font-mono);font-size:12px;
    letter-spacing:.06em;color:var(--brand);background:rgba(41,224,122,0.08);
    border:1px solid rgba(41,224,122,0.25);padding:6px 14px;border-radius:100px;margin-bottom:24px;
  }
  .eyebrow .pulse{width:6px;height:6px;border-radius:50%;background:var(--brand);animation:pulse 1.6s infinite;}
  @keyframes pulse{0%,100%{opacity:1;box-shadow:0 0 0 0 rgba(41,224,122,0.6);}50%{opacity:.5;box-shadow:0 0 0 6px rgba(41,224,122,0);}}
  h1{
    font-family:var(--font-display);font-weight:700;font-size:clamp(30px,3.4vw,42px);
    line-height:1.12;letter-spacing:-0.02em;margin-bottom:18px;
  }
  h1 .accent{
    background:linear-gradient(100deg,var(--brand),#7ff0b3 60%,var(--violet));
    -webkit-background-clip:text;background-clip:text;color:transparent;
  }
  .brand-copy p{color:var(--muted);font-size:15.5px;line-height:1.65;}

  .status-cards{margin-top:44px;display:flex;flex-direction:column;gap:14px;max-width:440px;}
  .status-card{
    background:var(--surface);border:1px solid var(--border);border-radius:14px;padding:18px 20px;
    display:flex;align-items:center;gap:16px;
    animation:float 7s ease-in-out infinite;
  }
  .status-card:nth-child(2){animation-delay:.4s;}
  @keyframes float{0%,100%{transform:translateY(0);}50%{transform:translateY(-6px);}}
  .status-card .icon{
    width:42px;height:42px;border-radius:11px;flex:0 0 auto;
    background:rgba(41,224,122,0.1);display:flex;align-items:center;justify-content:center;font-size:18px;
  }
  .status-card .info{flex:1;}
  .status-card .title{font-family:var(--font-display);font-size:14px;margin-bottom:3px;}
  .status-card .desc{font-size:12.5px;color:var(--muted-2);}
  .status-card .state{
    font-family:var(--font-mono);font-size:11px;color:var(--brand);display:flex;align-items:center;gap:6px;flex:0 0 auto;
  }
  .status-card .state .pulse{width:6px;height:6px;background:var(--brand);border-radius:50%;animation:pulse 1.6s infinite;}

  .brand-foot{font-size:12.5px;color:var(--muted-2);display:flex;justify-content:space-between;flex-wrap:wrap;gap:10px;margin-top:40px;}
  .brand-foot a:hover{color:var(--text);}

  /* ---------- right form panel ---------- */
  .form-panel{display:flex;align-items:center;justify-content:center;padding:56px 40px;}
  .form-card{
    width:100%;max-width:400px;
    background:linear-gradient(180deg,var(--surface),var(--surface-2));
    border:1px solid var(--border);border-radius:20px;padding:40px 34px;
    box-shadow:0 60px 120px -60px rgba(0,0,0,0.8);
  }
  .form-card h2{font-family:var(--font-display);font-size:24px;font-weight:700;letter-spacing:-0.02em;margin-bottom:8px;}
  .form-card .sub{color:var(--muted);font-size:13.5px;margin-bottom:32px;}

  .field{margin-bottom:20px;}
  .field label{
    display:block;font-family:var(--font-mono);font-size:11px;letter-spacing:.05em;text-transform:uppercase;
    color:var(--muted);margin-bottom:8px;
  }
  .field .input-wrap{position:relative;}
  .field input{
    width:100%;background:var(--bg-soft);border:1px solid var(--border);border-radius:10px;
    padding:13px 14px;color:var(--text);font-size:14px;font-family:var(--font-body);
    outline:none;transition:border-color .2s, box-shadow .2s;
  }
  .field input:focus{border-color:var(--brand);box-shadow:0 0 0 3px rgba(41,224,122,0.12);}
  .field input::placeholder{color:var(--muted-2);}

  .row-between{display:flex;justify-content:space-between;align-items:center;font-size:12.5px;margin-bottom:26px;}
  .remember{display:flex;align-items:center;gap:8px;color:var(--muted);}
  .remember input{accent-color:var(--brand);}
  .forgot{color:var(--muted);transition:color .2s;}
  .forgot:hover{color:var(--brand);}

  .btn{
    position:relative;display:inline-flex;align-items:center;justify-content:center;gap:8px;
    font-family:var(--font-body);font-weight:600;font-size:14px;width:100%;
    padding:13px 22px;border-radius:10px;cursor:pointer;border:none;
    transition:transform .2s ease, box-shadow .2s ease;
  }
  .btn-primary{background:var(--brand);color:#03130a;}
  .btn-primary:hover{transform:translateY(-2px);box-shadow:0 8px 30px -6px rgba(41,224,122,0.55);}

  .divider{display:flex;align-items:center;gap:12px;margin:28px 0;color:var(--muted-2);font-size:11.5px;font-family:var(--font-mono);}
  .divider::before,.divider::after{content:'';flex:1;height:1px;background:var(--border);}

  .form-note{
    font-size:12.5px;color:var(--muted-2);text-align:center;line-height:1.6;
    background:var(--bg-soft);border:1px solid var(--border);border-radius:10px;padding:14px 16px;
  }
  .form-note b{color:var(--muted);}

  .back-mobile{display:none;}
  @media (max-width:960px){
    .back-mobile{display:inline-block;font-size:13px;color:var(--muted);margin-top:20px;text-align:center;width:100%;}
  }
</style>
</head>
<body>

<div class="grain"></div>
<div class="bg-grid"></div>
<div class="spotlight" id="spotlight"></div>

<div class="shell">

  <!-- left brand panel -->
  <div class="brand-panel">
    <div>
      <a href="https://www.expandebot.com/" class="logo"><span class="dot"></span>ExpandeBot</a>

      <div class="brand-copy">
        <div class="eyebrow"><span class="pulse"></span>Centro de control corporativo</div>
        <h1>Impulsa tus ventas <span class="accent">en automático.</span></h1>
        <p>Entra a tu centro de control para gestionar tus playbooks de inteligencia artificial, revisar métricas de leads y expandir tu canal de WhatsApp.</p>
      </div>

      <div class="status-cards">
        <div class="status-card">
          <div class="icon">🧠</div>
          <div class="info">
            <div class="title">Cerebro de Inteligencia Artificial</div>
            <div class="desc">Modelos entrenados y calificados activos</div>
          </div>
          <div class="state"><span class="pulse"></span>Online</div>
        </div>
        <div class="status-card">
          <div class="icon">💬</div>
          <div class="info">
            <div class="title">WhatsApp Business Gateway</div>
            <div class="desc">Canal oficial conectado con latencia óptima</div>
          </div>
          <div class="state"><span class="pulse"></span>Activo</div>
        </div>
      </div>
    </div>

    <div class="brand-foot">
      <span>© 2026 ExpandeBot. Ecosistema empresarial inteligente de WhatsApp CRM.</span>
      <a href="https://www.expandebot.com/">← Volver a la landing</a>
    </div>
  </div>

  <!-- right form panel -->
  <div class="form-panel">
    <div class="form-card">
      <h2>Bienvenido de vuelta</h2>
      <div class="sub">Ingresa tus datos corporativos de ExpandeBot</div>

      <form onsubmit="return false;">
        <div class="field">
          <label for="email">Correo electrónico</label>
          <div class="input-wrap">
            <input type="email" id="email" placeholder="tu@empresa.com" autocomplete="email">
          </div>
        </div>
        <div class="field">
          <label for="pass">Contraseña</label>
          <div class="input-wrap">
            <input type="password" id="pass" placeholder="••••••••" autocomplete="current-password">
          </div>
        </div>
        <div class="row-between">
          <label class="remember"><input type="checkbox">Recordarme</label>
          <a href="#" class="forgot">¿Olvidaste tu contraseña?</a>
        </div>
        <button type="submit" class="btn btn-primary">Acceder al tablero →</button>
      </form>

      <div class="divider">ACCESO EXCLUSIVO</div>

      <div class="form-note">
        ¿No tienes acceso? <b>El administrador de tu empresa</b> debe dar de alta tu cuenta en ExpandeBot.
      </div>

      <a href="https://www.expandebot.com/" class="back-mobile">← Volver a la landing</a>
    </div>
  </div>

</div>

<script>
const spot = document.getElementById('spotlight');
window.addEventListener('mousemove', e=>{
  spot.style.setProperty('--x', e.clientX+'px');
  spot.style.setProperty('--y', e.clientY+'px');
});
</script>

</body>
</html>
