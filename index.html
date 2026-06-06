<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="IPPERG">
<title>IPPERG · Disciplinas</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Mono:wght@400;500&family=DM+Sans:wght@300;400;500;700&display=swap" rel="stylesheet">
<style>
:root {
  --ink: #0b506d;
  --ink2: #083d54;
  --red: #f6453b;
  --green: #5fa33a;
  --blue: #98a5c8;
  --bg: #f0f4f7;
  --white: #ffffff;
  --card: #ffffff;
  --border: #dce6ec;
  --text: #1a2b35;
  --muted: #6b8a99;
  --tag-bg: #e6f0f5;
  --shadow-card: 0 2px 12px rgba(11,80,109,0.10), 0 1px 3px rgba(11,80,109,0.06);
  --shadow-lg: 0 8px 32px rgba(11,80,109,0.18);
  --r: 14px;
  --r-sm: 8px;
  --safe-top: env(safe-area-inset-top, 0px);
  --safe-bottom: env(safe-area-inset-bottom, 0px);
}

* { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }

html, body {
  font-family: 'DM Sans', sans-serif;
  background: var(--bg);
  color: var(--text);
  font-size: 14px;
  min-height: 100vh;
  overscroll-behavior: none;
}

/* ─── SHELL ─── */
.app-shell {
  max-width: 480px;
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  position: relative;
}

/* ─── HEADER ─── */
.app-header {
  background: var(--ink);
  color: white;
  padding: calc(var(--safe-top) + 18px) 20px 16px;
  position: sticky;
  top: 0;
  z-index: 50;
}
.header-top { display: flex; align-items: flex-start; justify-content: space-between; }
.header-logo {
  font-family: 'DM Serif Display', serif;
  font-size: 22px;
  letter-spacing: -0.5px;
  line-height: 1;
}
.header-logo span { color: var(--red); }
.header-sub { font-size: 10px; opacity: 0.6; margin-top: 3px; letter-spacing: 0.5px; text-transform: uppercase; font-weight: 500; }
.header-badge {
  background: var(--red);
  color: white;
  border-radius: 20px;
  padding: 4px 11px;
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 0.5px;
  font-family: 'DM Mono', monospace;
  white-space: nowrap;
  margin-top: 2px;
}

/* ─── ALERTA ─── */
.alerta-bar {
  background: #fff1f0;
  border-bottom: 2px solid var(--red);
  padding: 10px 20px;
  font-size: 12px;
  color: #c0392b;
  font-weight: 600;
  display: none;
  gap: 6px;
  align-items: flex-start;
  line-height: 1.4;
}
.alerta-bar.visible { display: flex; }
.alerta-icon { font-size: 14px; flex-shrink: 0; margin-top: 1px; }

/* ─── STATS ROW ─── */
.stats-row {
  display: flex;
  gap: 8px;
  padding: 16px 16px 8px;
  overflow-x: auto;
  scrollbar-width: none;
}
.stats-row::-webkit-scrollbar { display: none; }
.stat-pill {
  background: var(--card);
  border-radius: 10px;
  padding: 10px 14px;
  flex-shrink: 0;
  text-align: center;
  box-shadow: var(--shadow-card);
  min-width: 72px;
}
.stat-pill .num {
  font-family: 'DM Mono', monospace;
  font-size: 22px;
  font-weight: 500;
  line-height: 1;
  color: var(--ink);
}
.stat-pill.danger .num { color: var(--red); }
.stat-pill.ok .num { color: var(--green); }
.stat-pill.neutral .num { color: var(--blue); }
.stat-pill .lbl { font-size: 9px; color: var(--muted); margin-top: 3px; text-transform: uppercase; letter-spacing: 0.4px; font-weight: 600; }

/* ─── SEARCH + FILTROS ─── */
.search-area { padding: 0 16px 8px; }
.search-box {
  display: flex;
  align-items: center;
  background: var(--card);
  border-radius: 10px;
  padding: 0 14px;
  box-shadow: var(--shadow-card);
  gap: 8px;
  height: 42px;
}
.search-box input {
  border: none;
  outline: none;
  flex: 1;
  font-size: 14px;
  font-family: 'DM Sans', sans-serif;
  background: transparent;
  color: var(--text);
}
.search-box input::placeholder { color: var(--muted); }
.search-icon { color: var(--muted); font-size: 15px; }

.filtros-row {
  display: flex;
  gap: 6px;
  padding: 8px 16px 4px;
  overflow-x: auto;
  scrollbar-width: none;
}
.filtros-row::-webkit-scrollbar { display: none; }
.filtro-btn {
  border: 1.5px solid var(--border);
  background: var(--card);
  color: var(--muted);
  border-radius: 20px;
  padding: 5px 13px;
  font-size: 11px;
  font-weight: 600;
  white-space: nowrap;
  cursor: pointer;
  flex-shrink: 0;
  transition: all 0.15s;
  font-family: 'DM Sans', sans-serif;
}
.filtro-btn.active {
  background: var(--ink);
  border-color: var(--ink);
  color: white;
}
.filtro-btn.urgente.active { background: var(--red); border-color: var(--red); }

/* ─── LISTA DE CARDS ─── */
.cards-list {
  flex: 1;
  padding: 8px 16px calc(var(--safe-bottom) + 80px);
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.disc-card {
  background: var(--card);
  border-radius: var(--r);
  box-shadow: var(--shadow-card);
  overflow: hidden;
  cursor: pointer;
  transition: transform 0.12s, box-shadow 0.12s;
  border-left: 4px solid var(--border);
  active: scale(0.98);
}
.disc-card:active { transform: scale(0.98); }
.disc-card.urgente { border-left-color: var(--red); background: #fffafa; }
.disc-card.proximo { border-left-color: #f59e0b; }
.disc-card.ok-card { border-left-color: var(--green); }
.disc-card.sem-prof { border-left-color: var(--blue); }

.card-top {
  padding: 14px 16px 10px;
  display: flex;
  gap: 10px;
  align-items: flex-start;
}
.card-num {
  background: var(--tag-bg);
  color: var(--ink);
  border-radius: 6px;
  padding: 3px 8px;
  font-family: 'DM Mono', monospace;
  font-size: 12px;
  font-weight: 500;
  flex-shrink: 0;
  margin-top: 1px;
}
.card-info { flex: 1; min-width: 0; }
.card-title {
  font-size: 13px;
  font-weight: 700;
  color: var(--ink);
  line-height: 1.35;
  margin-bottom: 4px;
}
.card-prof {
  font-size: 11px;
  color: var(--muted);
  font-weight: 500;
  display: flex;
  align-items: center;
  gap: 4px;
}
.card-prof.sem { color: var(--red); font-weight: 700; }

.card-meta {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 16px 12px;
  gap: 8px;
}
.card-datas {
  font-family: 'DM Mono', monospace;
  font-size: 10px;
  color: var(--muted);
  letter-spacing: 0.3px;
}
.card-eixo {
  font-size: 10px;
  font-weight: 700;
  color: var(--ink);
  background: var(--tag-bg);
  border-radius: 6px;
  padding: 2px 8px;
  letter-spacing: 0.3px;
}
.card-prazo-badge {
  font-size: 10px;
  font-weight: 700;
  border-radius: 20px;
  padding: 3px 10px;
  font-family: 'DM Mono', monospace;
  white-space: nowrap;
}
.card-prazo-badge.hot { background: #fee2e2; color: var(--red); }
.card-prazo-badge.warm { background: #fef3c7; color: #92400e; }
.card-prazo-badge.ok { background: #dcfce7; color: #166534; }
.card-prazo-badge.past { background: var(--tag-bg); color: var(--muted); text-decoration: line-through; }

/* PROGRESS BAR */
.card-progress { padding: 0 16px 14px; }
.progress-row { display: flex; align-items: center; gap: 8px; }
.progress-bar {
  flex: 1;
  height: 5px;
  background: var(--bg);
  border-radius: 3px;
  overflow: hidden;
}
.progress-fill {
  height: 100%;
  background: var(--green);
  border-radius: 3px;
  transition: width 0.3s;
}
.progress-fill.low { background: var(--red); }
.progress-fill.mid { background: #f59e0b; }
.progress-label {
  font-family: 'DM Mono', monospace;
  font-size: 10px;
  color: var(--muted);
  white-space: nowrap;
}

/* MINI-CHIPS na card */
.card-chips { padding: 0 16px 14px; display: flex; gap: 4px; flex-wrap: wrap; }
.mini-chip {
  width: 24px; height: 24px;
  border-radius: 6px;
  display: flex; align-items: center; justify-content: center;
  font-size: 11px;
  cursor: pointer;
  transition: transform 0.1s;
  flex-shrink: 0;
}
.mini-chip:active { transform: scale(0.88); }
.mini-chip.done { background: #dcfce7; }
.mini-chip.pend { background: #fef3c7; }
.mini-chip.miss { background: #fee2e2; }

/* ─── BOTTOM NAV ─── */
.bottom-nav {
  position: fixed;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 100%;
  max-width: 480px;
  background: var(--card);
  border-top: 1px solid var(--border);
  padding: 10px 20px calc(var(--safe-bottom) + 8px);
  display: flex;
  justify-content: space-around;
  z-index: 50;
  box-shadow: 0 -4px 20px rgba(11,80,109,0.08);
}
.nav-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 3px;
  cursor: pointer;
  padding: 4px 12px;
  border-radius: 10px;
  transition: background 0.15s;
  min-width: 56px;
}
.nav-item.active { background: var(--tag-bg); }
.nav-icon { font-size: 20px; line-height: 1; }
.nav-label { font-size: 9px; font-weight: 700; text-transform: uppercase; letter-spacing: 0.4px; color: var(--muted); }
.nav-item.active .nav-label { color: var(--ink); }
.nav-badge {
  position: absolute;
  top: -3px; right: -3px;
  background: var(--red);
  color: white;
  border-radius: 10px;
  font-size: 9px;
  font-weight: 700;
  padding: 1px 5px;
  min-width: 16px;
  text-align: center;
}
.nav-item-wrap { position: relative; }

/* ─── EMPTY STATE ─── */
.empty-state {
  text-align: center;
  padding: 40px 20px;
  color: var(--muted);
}
.empty-state .big { font-size: 40px; margin-bottom: 12px; }
.empty-state p { font-size: 13px; }

/* ─── MODAL SHEET ─── */
.sheet-bg {
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(10,30,40,0.5);
  z-index: 100;
  align-items: flex-end;
}
.sheet-bg.open { display: flex; }
.sheet {
  background: var(--card);
  border-radius: 20px 20px 0 0;
  padding: 0 0 calc(var(--safe-bottom) + 20px);
  width: 100%;
  max-height: 92vh;
  overflow-y: auto;
  overscroll-behavior: contain;
  animation: slideUp 0.25s cubic-bezier(0.34,1.56,0.64,1);
}
@keyframes slideUp {
  from { transform: translateY(100%); opacity: 0; }
  to { transform: translateY(0); opacity: 1; }
}
.sheet-handle {
  width: 40px; height: 4px;
  background: var(--border);
  border-radius: 2px;
  margin: 12px auto 16px;
}
.sheet-header { padding: 0 20px 14px; border-bottom: 1px solid var(--bg); }
.sheet-header h2 {
  font-family: 'DM Serif Display', serif;
  font-size: 17px;
  color: var(--ink);
  line-height: 1.3;
  margin-bottom: 6px;
}
.sheet-sub { font-size: 12px; color: var(--muted); font-weight: 500; }
.sheet-sub.sem { color: var(--red); font-weight: 700; }

/* CHECKLIST no sheet */
.sheet-section { padding: 14px 20px; }
.sheet-section-title {
  font-size: 10px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.8px;
  color: var(--muted);
  margin-bottom: 10px;
}
.check-list { display: flex; flex-direction: column; gap: 6px; }
.check-row {
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 10px 14px;
  background: var(--bg);
  border-radius: 10px;
  cursor: pointer;
  transition: background 0.12s;
  -webkit-user-select: none;
  user-select: none;
}
.check-row:active { background: #dce6ec; }
.check-row.done { background: #f0fdf4; }
.check-dot {
  width: 22px; height: 22px;
  border-radius: 6px;
  border: 2px solid var(--border);
  flex-shrink: 0;
  display: flex; align-items: center; justify-content: center;
  font-size: 13px;
  transition: all 0.15s;
}
.check-row.done .check-dot { background: var(--green); border-color: var(--green); color: white; }
.check-row-label { flex: 1; font-size: 13px; font-weight: 500; }
.check-row.done .check-row-label { color: var(--green); }
.check-icon-right { font-size: 14px; }

.obs-section { padding: 0 20px 14px; }
.obs-label {
  font-size: 10px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.8px;
  color: var(--muted);
  margin-bottom: 8px;
}
.obs-input {
  width: 100%;
  background: var(--bg);
  border: 1.5px solid var(--border);
  border-radius: 10px;
  padding: 10px 14px;
  font-family: 'DM Sans', sans-serif;
  font-size: 13px;
  color: var(--text);
  resize: none;
  min-height: 72px;
  outline: none;
}
.obs-input:focus { border-color: var(--ink); }

.sheet-actions { padding: 0 20px; display: flex; gap: 10px; }
.btn-salvar {
  flex: 1;
  background: var(--ink);
  color: white;
  border: none;
  border-radius: 12px;
  padding: 14px;
  font-size: 14px;
  font-weight: 700;
  font-family: 'DM Sans', sans-serif;
  cursor: pointer;
  transition: background 0.15s;
}
.btn-salvar:active { background: var(--ink2); }
.btn-fechar2 {
  background: var(--bg);
  color: var(--muted);
  border: none;
  border-radius: 12px;
  padding: 14px 18px;
  font-size: 14px;
  font-weight: 700;
  font-family: 'DM Sans', sans-serif;
  cursor: pointer;
}

/* ─── VIEW DE URGENTES ─── */
.view-urgentes { display: none; flex-direction: column; }
.view-urgentes.active { display: flex; }
.view-lista { display: flex; flex-direction: column; }
.view-lista.active { display: flex; }

/* ─── DESKTOP override ─── */
@media (min-width: 600px) {
  .app-shell { box-shadow: 0 0 40px rgba(0,0,0,0.12); }
  .bottom-nav { max-width: 480px; }
}
</style>
</head>
<body>
<div class="app-shell">

  <!-- HEADER -->
  <div class="app-header">
    <div class="header-top">
      <div>
        <div class="header-logo">IPPER<span>G</span></div>
        <div class="header-sub">Pós-Graduação · Gestão de Disciplinas</div>
      </div>
      <div class="header-badge" id="turma-badge">TURMA 3</div>
    </div>
  </div>

  <!-- ALERTA -->
  <div class="alerta-bar" id="alerta-bar">
    <span class="alerta-icon">⚠️</span>
    <span id="alerta-texto"></span>
  </div>

  <!-- STATS -->
  <div class="stats-row" id="stats-row"></div>

  <!-- BUSCA + FILTROS -->
  <div class="search-area">
    <div class="search-box">
      <span class="search-icon">🔍</span>
      <input type="search" id="busca" placeholder="Buscar disciplina ou professor…" oninput="renderLista()">
    </div>
  </div>
  <div class="filtros-row" id="filtros-row">
    <button class="filtro-btn active" data-f="todos" onclick="setFiltro('todos', this)">Todas</button>
    <button class="filtro-btn urgente" data-f="urgente" onclick="setFiltro('urgente', this)">🔴 Urgente</button>
    <button class="filtro-btn" data-f="sem-prof" onclick="setFiltro('sem-prof', this)">⚠️ Sem professor</button>
    <button class="filtro-btn" data-f="pendentes" onclick="setFiltro('pendentes', this)">Pendentes</button>
    <button class="filtro-btn" data-f="prontos" onclick="setFiltro('prontos', this)">✅ Prontos</button>
    <button class="filtro-btn" data-f="eixo1" onclick="setFiltro('eixo1', this)">Eixo I</button>
    <button class="filtro-btn" data-f="eixo2" onclick="setFiltro('eixo2', this)">Eixo II</button>
    <button class="filtro-btn" data-f="eixo3" onclick="setFiltro('eixo3', this)">Eixo III</button>
    <button class="filtro-btn" data-f="eixo4" onclick="setFiltro('eixo4', this)">Eixo IV</button>
    <button class="filtro-btn" data-f="eixo5" onclick="setFiltro('eixo5', this)">Eixo V</button>
  </div>

  <!-- LISTA -->
  <div class="cards-list" id="cards-list"></div>

</div>

<!-- BOTTOM NAV -->
<nav class="bottom-nav">
  <div class="nav-item active" onclick="setView('lista', this)">
    <span class="nav-icon">📋</span>
    <span class="nav-label">Disciplinas</span>
  </div>
  <div class="nav-item-wrap">
    <div class="nav-item" onclick="setView('urgentes', this)">
      <span class="nav-icon">🔴</span>
      <span class="nav-label">Urgente</span>
    </div>
    <span class="nav-badge" id="badge-urgente" style="display:none"></span>
  </div>
  <div class="nav-item" onclick="setView('checklist', this)">
    <span class="nav-icon">✅</span>
    <span class="nav-label">Progresso</span>
  </div>
</nav>

<!-- MODAL SHEET -->
<div class="sheet-bg" id="sheet-bg" onclick="fecharSheet(event)">
  <div class="sheet" id="sheet-content">
    <div class="sheet-handle"></div>
    <div class="sheet-header">
      <h2 id="sh-titulo"></h2>
      <div id="sh-sub" class="sheet-sub"></div>
      <div id="sh-datas" style="font-size:11px;color:var(--muted);margin-top:4px;font-family:'DM Mono',monospace;"></div>
    </div>
    <div class="sheet-section">
      <div class="sheet-section-title">Checklist de Tarefas</div>
      <div class="check-list" id="sh-checks"></div>
    </div>
    <div class="obs-section">
      <div class="obs-label">Observações</div>
      <textarea class="obs-input" id="sh-obs" placeholder="Notas, contatos, lembretes…"></textarea>
    </div>
    <div class="sheet-actions">
      <button class="btn-fechar2" onclick="document.getElementById('sheet-bg').classList.remove('open')">Cancelar</button>
      <button class="btn-salvar" onclick="salvarSheet()">💾 Salvar</button>
    </div>
  </div>
</div>

<script>
// ── DADOS ──────────────────────────────────────────
const CHECKS = [
  { key:'convite',    label:'Convite Enviado',       icon:'✉️' },
  { key:'aceite',     label:'Aceite Recebido',        icon:'✅' },
  { key:'contrato',   label:'Contrato Assinado',      icon:'📄' },
  { key:'ementa',     label:'Ementa Recebida',        icon:'📚' },
  { key:'biblio',     label:'Bibliografia Recebida',  icon:'📖' },
  { key:'material',   label:'Material Biblioteca',    icon:'📁' },
  { key:'zoom',       label:'Zoom Configurado',       icon:'🔗' },
  { key:'email',      label:'E-mail Alunos',          icon:'📧' },
  { key:'whatsapp',   label:'WhatsApp Alunos',        icon:'💬' },
  { key:'aula',       label:'Aula Realizada',         icon:'🎓' },
  { key:'zoom_rel',   label:'Relatório Zoom',         icon:'📊' },
  { key:'frequencia', label:'Frequência Lançada',     icon:'📋' },
  { key:'pagamento',  label:'Pagamento Docente',      icon:'💰' },
  { key:'declaracao', label:'Declaração Docente',     icon:'🏅' },
];

const DISC = [
  {n:'01',disc:'Psicanálise e relações de gênero: mapeando conceitos em disputa',eixo:'EIXO I',prof:'José Stona',inicio:'2026-03-27',fim:'2026-03-28'},
  {n:'02',disc:'As histórias não contadas da psicanálise',eixo:'EIXO I',prof:'Flávia Ripoli Martins, Camila Terra da Rosa',inicio:'2026-04-24',fim:'2026-04-25'},
  {n:'03',disc:'Elaborações sobre a psicanálise freudiana: conceitos fundamentais',eixo:'EIXO I',prof:'Tom Rodrigues',inicio:'2026-05-29',fim:'2026-05-30'},
  {n:'04',disc:'Gênero, sexualidade e inconsciente: pensar as normatividades das psicanálise[s]',eixo:'EIXO I',prof:'Luciana Redivo Drehmer',inicio:'2026-06-19',fim:'2026-06-20'},
  {n:'05',disc:'A questão do gênero pensada a partir dos pós-freudianos',eixo:'EIXO I',prof:'Alexandre Patrício de Almeida',inicio:'2026-07-24',fim:'2026-07-25'},
  {n:'06',disc:'A crítica de Foucault à psicanálise e o que fazer com ela?',eixo:'EIXO II',prof:'Eduardo Leal Cunha',inicio:'2026-08-28',fim:'2026-08-29'},
  {n:'07',disc:'Psicanálise na encruzilhada dos saberes e na travessia do Atlântico',eixo:'EIXO II',prof:'José Damico',inicio:'2026-09-25',fim:'2026-09-26'},
  {n:'08',disc:'Colonialidade e psicanálise: a aquilombação da clínica psicanalítica',eixo:'EIXO II',prof:'Emiliano de Camargo David',inicio:'2026-10-23',fim:'2026-10-24'},
  {n:'09',disc:'Psicanálise e estudos feministas I',eixo:'EIXO III',prof:'Paula Gruman Martins',inicio:'2026-11-27',fim:'2026-11-28'},
  {n:'10',disc:'Psicanálise e estudos feministas II',eixo:'EIXO III',prof:'',inicio:'2026-12-18',fim:'2026-12-19'},
  {n:'11',disc:'Psicanálise e estudos de gênero I',eixo:'EIXO III',prof:'José Stona',inicio:'2027-01-29',fim:'2027-01-30'},
  {n:'12',disc:'Psicanálise e estudos de gênero II',eixo:'EIXO III',prof:'Patrícia Porchat',inicio:'2027-02-26',fim:'2027-02-27'},
  {n:'13',disc:'Psicanálise e teorias queer I',eixo:'EIXO III',prof:'Rafael Leopoldo A. S. Ferreira',inicio:'2027-03-26',fim:'2027-03-27'},
  {n:'14',disc:'Psicanálise e teorias queer II',eixo:'EIXO III',prof:'Rafael Leopoldo A. S. Ferreira',inicio:'2027-04-30',fim:'2027-05-01'},
  {n:'15',disc:'Infâncias e parentalidades dissidentes',eixo:'EIXO IV',prof:'',inicio:'2027-05-28',fim:'2027-05-29'},
  {n:'16',disc:'Psicanálise à brasileira: por uma aterrissagem territorial',eixo:'EIXO IV',prof:'',inicio:'2027-06-25',fim:'2027-06-26'},
  {n:'17',disc:'A escuta clínica diante das diversidades sexuais e de gênero',eixo:'EIXO IV',prof:'',inicio:'2027-07-30',fim:'2027-07-31'},
  {n:'18',disc:'Cis-temas-mono: políticas da norma e invenções de resistência',eixo:'EIXO IV',prof:'',inicio:'2027-08-27',fim:'2027-08-28'},
  {n:'19',disc:'Escrita e Autoria — Módulo I',eixo:'EIXO V',prof:'José Stona',inicio:'2027-09-24',fim:'2027-09-25'},
  {n:'20',disc:'Escrita e Autoria — Módulo II',eixo:'EIXO V',prof:'José Stona',inicio:'2027-10-29',fim:'2027-10-30'},
  {n:'21',disc:'Escrita e Autoria — Módulo III',eixo:'EIXO V',prof:'José Stona',inicio:'2027-11-26',fim:'2027-11-27'},
];

// ── ESTADO ──────────────────────────────────────────
const SK = 'ipperg_app_v1';
let estado = {};
let filtroAtivo = 'todos';
let modalAtual = null;

function carregar() {
  try { const r = localStorage.getItem(SK); if(r) estado = JSON.parse(r); } catch(e){}
  DISC.forEach(d => {
    if(!estado[d.n]) {
      estado[d.n] = {obs:''};
      CHECKS.forEach(c => { estado[d.n][c.key] = false; });
    }
  });
}

function salvar() { localStorage.setItem(SK, JSON.stringify(estado)); }

// ── UTILS ───────────────────────────────────────────
function diasAte(s) {
  return Math.ceil((new Date(s) - new Date()) / 86400000);
}
function fmtData(s) {
  const d = new Date(s);
  return d.toLocaleDateString('pt-BR',{day:'2-digit',month:'short'}).replace(' de ','/')
    .replace('jan','jan').replace('fev','fev').replace('mar','mar').replace('abr','abr')
    .replace('mai','mai').replace('jun','jun').replace('jul','jul').replace('ago','ago')
    .replace('set','set').replace('out','out').replace('nov','nov').replace('dez','dez');
}
function progresso(n) {
  const e = estado[n];
  const f = CHECKS.filter(c => e[c.key]).length;
  return {f, t: CHECKS.length, pct: Math.round(f/CHECKS.length*100)};
}
function prazoCls(dias) {
  if(dias < 0) return 'past';
  if(dias <= 14) return 'hot';
  if(dias <= 30) return 'warm';
  return 'ok';
}
function cardCls(d) {
  const dias = diasAte(d.inicio);
  if(!d.prof) return 'sem-prof';
  if(dias >= 0 && dias <= 14 && !estado[d.n].aceite) return 'urgente';
  if(dias >= 0 && dias <= 30) return 'proximo';
  const {f,t} = progresso(d.n);
  if(f === t) return 'ok-card';
  return '';
}

// ── RENDER STATS ────────────────────────────────────
function renderStats() {
  const urgentes = DISC.filter(d => { const dia=diasAte(d.inicio); return dia>=0&&dia<=14&&!estado[d.n].aceite; }).length;
  const semProf = DISC.filter(d=>!d.prof).length;
  const realizadas = DISC.filter(d=>diasAte(d.inicio)<0).length;
  const prontos = DISC.filter(d=>{ const {f,t}=progresso(d.n); return f===t; }).length;
  const proximas = DISC.filter(d=>{ const dia=diasAte(d.inicio); return dia>=0&&dia<=60; }).length;

  document.getElementById('stats-row').innerHTML = `
    <div class="stat-pill neutral"><div class="num">${DISC.length}</div><div class="lbl">Total</div></div>
    <div class="stat-pill"><div class="num">${proximas}</div><div class="lbl">60 dias</div></div>
    <div class="stat-pill danger"><div class="num">${urgentes}</div><div class="lbl">Urgente</div></div>
    <div class="stat-pill danger"><div class="num">${semProf}</div><div class="lbl">Sem prof</div></div>
    <div class="stat-pill ok"><div class="num">${realizadas}</div><div class="lbl">Feitas</div></div>
    <div class="stat-pill ok"><div class="num">${prontos}</div><div class="lbl">Prontos</div></div>
  `;

  // badge nav
  const badgeEl = document.getElementById('badge-urgente');
  if(urgentes > 0) { badgeEl.textContent = urgentes; badgeEl.style.display='block'; }
  else badgeEl.style.display='none';

  // alerta
  const urg = DISC.filter(d=>{ const dia=diasAte(d.inicio); return dia>=0&&dia<=14&&!estado[d.n].aceite; });
  const alertaEl = document.getElementById('alerta-bar');
  if(urg.length) {
    alertaEl.classList.add('visible');
    document.getElementById('alerta-texto').innerHTML =
      `<b>${urg.length} disciplina(s) em até 14 dias sem aceite:</b> `+
      urg.map(d=>`<b>${d.n}</b> ${d.prof||'sem professor'}`).join(' · ');
  } else {
    alertaEl.classList.remove('visible');
  }
}

// ── RENDER LISTA ────────────────────────────────────
function renderLista() {
  const busca = document.getElementById('busca').value.toLowerCase().trim();

  let lista = DISC.filter(d => {
    const texto = (d.disc+d.prof+d.eixo).toLowerCase();
    if(busca && !texto.includes(busca)) return false;
    const dias = diasAte(d.inicio);
    const {f,t} = progresso(d.n);
    switch(filtroAtivo) {
      case 'urgente': return dias>=0&&dias<=14&&!estado[d.n].aceite;
      case 'sem-prof': return !d.prof;
      case 'pendentes': return f<t && dias>=0;
      case 'prontos': return f===t;
      case 'eixo1': return d.eixo==='EIXO I';
      case 'eixo2': return d.eixo==='EIXO II';
      case 'eixo3': return d.eixo==='EIXO III';
      case 'eixo4': return d.eixo==='EIXO IV';
      case 'eixo5': return d.eixo==='EIXO V';
      default: return true;
    }
  });

  const el = document.getElementById('cards-list');
  if(!lista.length) {
    el.innerHTML = `<div class="empty-state"><div class="big">🔍</div><p>Nenhuma disciplina encontrada.</p></div>`;
    return;
  }

  el.innerHTML = lista.map(d => {
    const dias = diasAte(d.inicio);
    const pc = prazoCls(dias);
    const prazoTxt = dias<0?'Realizada':dias===0?'HOJE':dias+'d';
    const {f,t,pct} = progresso(d.n);
    const fillCls = pct < 30?'low':pct<70?'mid':'';
    const cc = cardCls(d);
    // mini chips (apenas os 9 principais)
    const mainKeys = ['convite','aceite','contrato','ementa','biblio','material','zoom','email','whatsapp'];
    const chipsHtml = mainKeys.map(k => {
      const v = estado[d.n][k];
      const ch = CHECKS.find(c=>c.key===k);
      return `<div class="mini-chip ${v?'done':'miss'}" onclick="event.stopPropagation();toggleMini('${d.n}','${k}')" title="${ch.label}">${ch.icon}</div>`;
    }).join('');

    return `<div class="disc-card ${cc}" onclick="abrirSheet('${d.n}')">
      <div class="card-top">
        <div class="card-num">${d.n}</div>
        <div class="card-info">
          <div class="card-title">${d.disc}</div>
          <div class="card-prof ${!d.prof?'sem':''}">${d.prof || '⚠ Professor a definir'}</div>
        </div>
      </div>
      <div class="card-meta">
        <span class="card-datas">${fmtData(d.inicio)} → ${fmtData(d.fim)}</span>
        <span class="card-eixo">${d.eixo}</span>
        <span class="card-prazo-badge ${pc}">${prazoTxt}</span>
      </div>
      <div class="card-chips">${chipsHtml}</div>
      <div class="card-progress">
        <div class="progress-row">
          <div class="progress-bar"><div class="progress-fill ${fillCls}" style="width:${pct}%"></div></div>
          <span class="progress-label">${f}/${t}</span>
        </div>
      </div>
    </div>`;
  }).join('');
}

function toggleMini(n, key) {
  estado[n][key] = !estado[n][key];
  salvar();
  renderStats();
  renderLista();
}

// ── FILTRO ──────────────────────────────────────────
function setFiltro(f, btn) {
  filtroAtivo = f;
  document.querySelectorAll('.filtro-btn').forEach(b => b.classList.remove('active'));
  btn.classList.add('active');
  renderLista();
}

// ── VIEW NAV ────────────────────────────────────────
function setView(v, item) {
  document.querySelectorAll('.nav-item').forEach(b => b.classList.remove('active'));
  item.classList.add('active');
  if(v==='urgentes') {
    setFiltro('urgente', document.querySelector('[data-f="urgente"]'));
  } else if(v==='checklist') {
    setFiltro('pendentes', document.querySelector('[data-f="pendentes"]'));
  } else {
    setFiltro('todos', document.querySelector('[data-f="todos"]'));
  }
}

// ── MODAL SHEET ─────────────────────────────────────
function abrirSheet(n) {
  modalAtual = n;
  const d = DISC.find(x=>x.n===n);
  const e = estado[n];
  document.getElementById('sh-titulo').textContent = d.disc;
  document.getElementById('sh-sub').className = 'sheet-sub'+(d.prof?'':' sem');
  document.getElementById('sh-sub').textContent = d.prof || '⚠ Professor ainda não definido';
  document.getElementById('sh-datas').textContent = `${fmtData(d.inicio)} → ${fmtData(d.fim)} · ${d.eixo}`;
  document.getElementById('sh-obs').value = e.obs || '';

  const checksHtml = CHECKS.map(c => `
    <div class="check-row ${e[c.key]?'done':''}" id="cr_${c.key}" onclick="toggleSheetCheck('${c.key}')">
      <div class="check-dot">${e[c.key]?'✓':''}</div>
      <span class="check-row-label">${c.icon} ${c.label}</span>
    </div>
  `).join('');
  document.getElementById('sh-checks').innerHTML = checksHtml;
  document.getElementById('sheet-bg').classList.add('open');
}

function toggleSheetCheck(key) {
  if(!modalAtual) return;
  estado[modalAtual][key] = !estado[modalAtual][key];
  const row = document.getElementById('cr_'+key);
  if(row) {
    row.classList.toggle('done', estado[modalAtual][key]);
    row.querySelector('.check-dot').textContent = estado[modalAtual][key]?'✓':'';
  }
}

function salvarSheet() {
  if(!modalAtual) return;
  estado[modalAtual].obs = document.getElementById('sh-obs').value;
  salvar();
  renderStats();
  renderLista();
  document.getElementById('sheet-bg').classList.remove('open');
}

function fecharSheet(e) {
  if(e.target.id==='sheet-bg') document.getElementById('sheet-bg').classList.remove('open');
}

// ── INIT ─────────────────────────────────────────────
carregar();
renderStats();
renderLista();
</script>
</body>
</html>
