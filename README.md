<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Resset — O RH e o DP que Cuidam de Quem Cuida | UNIP</title>
  <meta name="description" content="Resset: encontro para RH e DP. Palestras sobre saúde emocional, liderança, compliance e inovação em RH. UNIP - 11/10/2025" />
  <style>
    /* ===== Reset & Base ===== */
    :root{
      --brand:#1f6feb;
      --muted:#6b7280;
      --bg:#f7f8fb;
      --card:#ffffff;
      --accent:#7dd3fc;
      --glass: rgba(255,255,255,0.7);
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background:linear-gradient(180deg,#f7f8fb 0%,#eef2f6 100%);
      color:#0f172a;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
      font-size:16px;
    }
    a{color:var(--brand); text-decoration:none}
    img{max-width:100%;height:auto;display:block}
    .container{max-width:1100px;margin:0 auto;padding:28px;}
    .row{display:flex;flex-wrap:wrap;gap:20px}
    .col{flex:1;min-width:0}

    /* ===== Header / Hero ===== */
    header{padding:20px 0}
    .topbar{display:flex;justify-content:space-between;align-items:center;gap:12px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:10px;background:linear-gradient(135deg,var(--brand),#0ea5a0);display:flex;align-items:center;justify-content:center;color:white;font-weight:700}
    .hero{
      margin-top:20px;
      background:linear-gradient(90deg, rgba(31,111,235,0.08), rgba(125,211,252,0.04));
      border-radius:14px;padding:28px;display:flex;flex-wrap:wrap;align-items:center;gap:20px;
      box-shadow:0 6px 20px rgba(15,23,42,0.06);
    }
    .hero-left{flex:1;min-width:260px}
    .kicker{display:inline-block;background:var(--brand);color:white;padding:6px 10px;border-radius:8px;font-weight:600;font-size:13px}
    h1{margin:10px 0 8px;font-size:28px;letter-spacing:-0.4px}
    .lead{color:var(--muted);margin-bottom:14px}
    .cta-row{display:flex;gap:12px;flex-wrap:wrap}
    .btn{
      display:inline-flex;align-items:center;gap:8px;padding:10px 16px;border-radius:10px;border:0;background:var(--brand);color:#fff;font-weight:600;cursor:pointer;
      box-shadow: 0 6px 18px rgba(31,111,235,0.16);
    }
    .btn-secondary{background:#fff;border:1px solid #e6eefc;color:var(--brand);font-weight:600}
    .hero-right{width:300px;min-width:220px}

    /* ===== Sections ===== */
    section{margin:36px 0}
    .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(15,23,42,0.04)}
    .speakers{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:12px}
    .speaker{padding:16px;border-radius:10px;background:linear-gradient(180deg,#fff,#fbfdff);display:flex;gap:12px;align-items:flex-start}
    .avatar{width:72px;height:72px;border-radius:8px;background:#f1f5f9;flex-shrink:0;display:flex;align-items:center;justify-content:center;font-weight:700}
    .sp-name{font-weight:700}
    .sp-role{color:var(--muted);font-size:13px;margin-top:6px}

    /* ===== Sponsors ===== */
    .sponsors{display:flex;flex-wrap:wrap;gap:18px;align-items:center;justify-content:center;padding:12px}
    .sponsor{width:140px;height:64px;background:#fff;border-radius:8px;display:flex;align-items:center;justify-content:center;padding:8px;box-shadow:0 6px 18px rgba(2,6,23,0.04)}

    /* ===== Agenda / CTA ===== */
    .grid-2{display:grid;grid-template-columns:1fr 360px;gap:20px}
    .agenda-item{padding:12px;border-radius:10px;border-left:4px solid var(--accent);background:#fff}
    .meta{color:var(--muted);font-size:14px}

    /* ===== Footer ===== */
    footer{padding:24px 0;color:var(--muted);text-align:center;font-size:14px}

    /* ===== Responsive ===== */
    @media (max-width:880px){
      .grid-2{grid-template-columns:1fr}
      .hero-right{width:100%}
    }

  </style>
</head>
<body>
  <div class="container">

    <!-- Header -->
    <header>
      <div class="topbar">
        <div class="brand">
          <div class="logo">RH</div>
          <div>
            <div style="font-weight:700">Resset • UNIP</div>
            <div style="color:var(--muted);font-size:13px">11 out 2025 — UNIP Paraíso — 08:30</div>
          </div>
        </div>

        <nav style="display:flex;gap:12px;align-items:center">
          <a class="meta" href="#programa">Programa</a>
          <a class="meta" href="#palestrantes">Palestrantes</a>
          <a class="meta" href="#patrocinadores">Apoiadores</a>
          <a class="meta" href="#inscricao">Inscrição</a>
        </nav>
      </div>

      <!-- Hero -->
      <div class="hero" role="region" aria-label="Resset - o RH que cuida">
        <div class="hero-left">
          <span class="kicker">ENCONTRO • RH • UNIP</span>
          <h1>Resset — O RH e o DP que cuidam de quem cuida</h1>
          <p class="lead">Encontro prático e inspirador para profissionais de RH e Departamento Pessoal. Debates sobre saúde emocional, compliance, tecnologia e liderança humana.</p>

          <div class="cta-row">
            <a class="btn" href="https://posunip.com.br/evento/227" target="_blank" rel="noopener">Inscreva-se (UNIP)</a>
            <a class="btn btn-secondary" href="#patrocinadores">Seja patrocinador</a>
          </div>
          <p style="margin-top:10px;color:var(--muted);font-size:13px">Vagas limitadas • Média de 50 convidados • Divulgação na rede UNIP</p>
        </div>

        <div class="hero-right card" aria-hidden="false">
          <h3 style="margin:0 0 8px">Destaques</h3>
          <ul style="margin:0;padding-left:18px;color:var(--muted);font-size:14px">
            <li>Painel de fotos instagramável</li>
            <li>Brindes e lista de networking para patrocinadores</li>
            <li>Exibição de vídeo institucional dos apoiadores</li>
          </ul>
        </div>
      </div>
    </header>

    <!-- Sobre -->
    <section id="sobre">
      <div class="card">
        <h2 style="margin-top:0">Por que participar?</h2>
        <p class="meta">O Resset foi criado para profissionais que atuam no cuidado das pessoas nas organizações. O evento propõe conhecimento prático, troca de experiências e ferramentas aplicáveis para RH e DP.</p>
        <div class="row" style="margin-top:12px">
          <div class="col">
            <strong>Quem deve participar</strong>
            <p class="meta">Profissionais de RH, líderes de loja, consultores, advogados trabalhistas, gestores de operações e estudantes de pós-graduação.</p>
          </div>
          <div class="col">
            <strong>Formato</strong>
            <p class="meta">Painéis presenciais, espaço para networking, materiais digitais e recursos para patrocinadores.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Palestrantes -->
    <section id="palestrantes">
      <h2>Palestrantes</h2>
      <div class="speakers">
        <article class="speaker">
          <div class="avatar"><img src="images/joao_lago.jpg" alt="João Lago" style="width:72px;height:72px;border-radius:8px;object-fit:cover"></div>
          <div>
            <div class="sp-name">João Henrique Lago</div>
            <div class="sp-role">Pedagogo Empresarial • Psicanalista • Autor</div>
            <div class="meta" style="margin-top:6px">Tema: Saúde emocional e liderança. Autor de "Despertar para o Amanhecer".</div>
          </div>
        </article>

        <article class="speaker">
          <div class="avatar"><img src="images/vanice_mauch.jpg" alt="Vanice Mauch" style="width:72px;height:72px;border-radius:8px;object-fit:cover"></div>
          <div>
            <div class="sp-name">Vanice Dias Mauch</div>
            <div class="sp-role">Consultora Organizacional • Relações Trabalhistas</div>
            <div class="meta" style="margin-top:6px">Especialista em compliance, FAP/RAT e programas de saúde mental no trabalho.</div>
          </div>
        </article>

        <article class="speaker">
          <div class="avatar"><img src="images/renato_rosa.jpg" alt="Renato Rosa" style="width:72px;height:72px;border-radius:8px;object-fit:cover"></div>
          <div>
            <div class="sp-name">Renato Rosa</div>
            <div class="sp-role">Executivo de RH • ZAMP</div>
            <div class="meta" style="margin-top:6px">Tema: Automação em RH, folha e transformação digital aplicada à gestão de pessoas.</div>
          </div>
        </article>

        <article class="speaker">
          <div class="avatar"><img src="images/fernando_marinov.jpg" alt="Fernando Marinov" style="width:72px;height:72px;border-radius:8px;object-fit:cover"></div>
          <div>
            <div class="sp-name">Dr. Fernando Marinov</div>
            <div class="sp-role">Advogado • Marinov Advocacia</div>
            <div class="meta" style="margin-top:6px">Tema: Segurança jurídica e prevenção de passivos trabalhistas.</div>
          </div>
        </article>

        <article class="speaker">
          <div class="avatar"><img src="images/michelle_franca.jpg" alt="Michelle França" style="width:72px;height:72px;border-radius:8px;object-fit:cover"></div>
          <div>
            <div class="sp-name">Michelle França</div>
            <div class="sp-role">Especialista em Desenvolvimento Humano</div>
            <div class="meta" style="margin-top:6px">Tema: Cultura organizacional e liderança sistêmica.</div>
          </div>
        </article>
      </div>
    </section>

    <!-- Agenda e inscrição -->
    <section id="programa" class="grid-2">
      <div>
        <h2>Programa (resumo)</h2>
        <div style="display:flex;flex-direction:column;gap:12px;margin-top:12px">
          <div class="agenda-item">
            <strong>08:30 — Credenciamento e welcome coffee</strong>
            <div class="meta">Recepção e espaço para networking</div>
          </div>
          <div class="agenda-item">
            <strong>09:00 — Abertura & Palestra</strong>
            <div class="meta">João Lago — Saúde emocional e soluções humanas</div>
          </div>
          <div class="agenda-item">
            <strong>10:00 — Painel</strong>
            <div class="meta">Vanice Mauch e Michelle França — Compliance, DP e cultura</div>
          </div>
          <div class="agenda-item">
            <strong>11:15 — Pausa para networking</strong>
            <div class="meta">Painel instagramável e coffee</div>
          </div>
          <div class="agenda-item">
            <strong>11:40 — Encerramento</strong>
            <div class="meta">Renato Rosa & Dr. Fernando Marinov — conclusão e recomendações práticas</div>
          </div>
        </div>
      </div>

      <aside class="card">
        <h3 id="inscricao">Inscrições e apoio</h3>
        <p class="meta">Inscrições pela página da UNIP: <a href="https://posunip.com.br/evento/227" target="_blank" rel="noopener">posunip.com.br/evento/227</a></p>

        <h4 style="margin-top:12px">O que oferecemos aos patrocinadores</h4>
        <ul style="padding-left:18px;color:var(--muted);margin-top:8px">
          <li>Exposição do logo no site e no banner instagramável</li>
          <li>Vídeo institucional exibido no evento</li>
          <li>Lista de contatos dos participantes para ações de marketing</li>
          <li>Brindes e espaço para divulgação</li>
        </ul>

        <p style="margin-top:10px;color:var(--muted)">Sugestão de apoio simbólico por parceiro: <strong>R$250 a R$300</strong> + 1 brinde (opcional)</p>
        <a class="btn" href="mailto:contato@rhreset.com.br">Quero patrocinar</a>
      </aside>
    </section>

    <!-- Patrocinadores -->
    <section id="patrocinadores">
      <h2>Apoiadores e parcerias</h2>
      <div class="card" style="margin-top:12px">
        <div class="sponsors">
          <!-- Substitua src pelas logos reais -->
          <div class="sponsor"><img src="images/3clicksrh_logo.png" alt="3ClicksRH" style="max-height:44px"></div>
          <div class="sponsor"><img src="images/rhdigitalexe_logo.png" alt="RH Digital EXE" style="max-height:44px"></div>
          <div class="sponsor"><img src="images/idesan_logo.png" alt="Idesan" style="max-height:44px"></div>
          <div class="sponsor"><img src="images/contacto_logo.png" alt="Contacto" style="max-height:44px"></div>
        </div>

        <p class="meta" style="text-align:center;margin-top:12px">Agradecemos o apoio das empresas que acreditam no valor do desenvolvimento humano e da inovação em RH.</p>
      </div>
    </section>

    <!-- Rodapé -->
    <footer>
      <div style="display:flex;flex-direction:column;gap:8px;align-items:center">
        <div style="font-weight:700">Resset • UNIP | 11 de outubro de 2025</div>
        <div style="color:var(--muted)">Organização: Ideal RH • Axium • Marinov Advocacia • RH Reset</div>
        <div style="margin-top:8px;color:var(--muted)">Contato: <a href="mailto:contato@rhreset.com.br">contato@rhreset.com.br</a></div>
      </div>
    </footer>

  </div>
</body>
</html>
