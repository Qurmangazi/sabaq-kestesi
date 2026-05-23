<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sabaq kestesi</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: system-ui, -apple-system, sans-serif; background: #f5f5f0; color: #1a1a18; min-height: 100vh; }
  .container { max-width: 720px; margin: 0 auto; padding: 2rem 1rem; }
  h1 { font-size: 22px; font-weight: 600; margin-bottom: 4px; display: flex; align-items: center; gap: 8px; }
  .subtitle { font-size: 14px; color: #888780; margin-bottom: 1rem; }

  /* QADAǴALAW ESLATMA BANNER */
  .qadaǵalaw-banner { display: none; background: #fff8e1; border: 1px solid #f9c825; border-radius: 12px; padding: 14px 16px; margin-bottom: 1.25rem; }
  .qadaǵalaw-banner.show { display: block; }
  .qadaǵalaw-banner-head { font-size: 13px; font-weight: 600; color: #7a5c00; display: flex; align-items: center; gap: 6px; margin-bottom: 10px; }
  .qadaǵalaw-item { display: flex; align-items: flex-start; gap: 10px; padding: 8px 0; border-bottom: 0.5px solid #fde98a; }
  .qadaǵalaw-item:last-child { border-bottom: none; padding-bottom: 0; }
  .qadaǵalaw-item-left { flex: 1; }
  .qadaǵalaw-pán { font-size: 13px; font-weight: 500; color: #1a1a18; margin-bottom: 3px; }
  .qadaǵalaw-tur-badge { display: inline-block; font-size: 11px; padding: 2px 8px; border-radius: 10px; font-weight: 600; }
  .nb-házirgi    { background: #e1f5ee; color: #0f6e56; }
  .nb-Aralıq   { background: #e6f1fb; color: #185fa5; }
  .nb-juwmaqlawshı  { background: #fce8e8; color: #a32d2d; }
  .qadaǵalaw-ball { font-size: 12px; color: #888780; margin-top: 3px; }
  .qadaǵalaw-date-badge { font-size: 12px; font-weight: 600; color: #7a5c00; background: #fde98a; padding: 3px 10px; border-radius: 20px; white-space: nowrap; flex-shrink: 0; }
  .qadaǵalaw-empty { font-size: 13px; color: #888780; text-align: center; padding: 6px 0; }
  .tab-row { display: flex; gap: 6px; margin-bottom: 1.5rem; flex-wrap: wrap; }
  .tab-btn { padding: 7px 16px; font-size: 13px; font-family: inherit; background: #f1efe8; border: 0.5px solid #d3d1c7; border-radius: 20px; color: #888780; cursor: pointer; transition: all 0.15s; display: flex; align-items: center; gap: 5px; }
  .tab-btn:hover { background: #e8e6de; color: #1a1a18; }
  .tab-btn.active { background: #fff; border-color: #888780; color: #1a1a18; font-weight: 500; }
  .tab-btn.active.green { background: #e1f5ee; border-color: #2d8c6e; color: #0f6e56; }

  .btn-row { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 1.5rem; }
  .btn { padding: 8px 16px; font-size: 14px; font-family: inherit; background: #fff; border: 0.5px solid #c8c6bc; border-radius: 8px; color: #1a1a18; cursor: pointer; transition: background 0.15s; display: flex; align-items: center; gap: 6px; }
  .btn:hover { background: #f1efe8; }
  .btn.active { background: #e6f1fb; color: #185fa5; border-color: #85b7eb; }

  .day-tabs { display: flex; gap: 6px; flex-wrap: wrap; margin-bottom: 1.5rem; }
  .day-tab { padding: 6px 14px; font-size: 13px; font-family: inherit; background: #f1efe8; border: 0.5px solid #d3d1c7; border-radius: 20px; color: #888780; cursor: pointer; transition: all 0.15s; }
  .day-tab:hover { border-color: #b4b2a9; color: #1a1a18; }
  .day-tab.active { background: #fff; border-color: #888780; color: #1a1a18; font-weight: 500; }
  .day-tab.today { border-color: #2d8c6e; color: #0f6e56; }
  .day-tab.today.active { background: #e1f5ee; border-color: #2d8c6e; }

  .section-title { font-size: 16px; font-weight: 600; margin-bottom: 12px; display: flex; align-items: center; gap: 8px; }
  .badge { font-size: 12px; font-weight: 400; background: #f1efe8; color: #888780; padding: 2px 10px; border-radius: 20px; border: 0.5px solid #d3d1c7; }
  .empty { text-align: center; padding: 2.5rem 1rem; color: #888780; font-size: 15px; background: #f1efe8; border-radius: 12px; border: 0.5px solid #d3d1c7; }
  .cards { display: flex; flex-direction: column; gap: 0; border: 0.5px solid #d3d1c7; border-radius: 12px; overflow: hidden; background: #fff; }
  .card { background: #fff; padding: 14px 16px; border-bottom: 0.5px solid #ebebE6; display: flex; flex-direction: column; gap: 6px; cursor: pointer; transition: background 0.13s; }
  .card:last-child { border-bottom: none; }
  .card:hover { background: #f8f8f4; }
  .card-top { display: flex; align-items: flex-start; justify-content: space-between; gap: 8px; }
  .card-title { font-size: 14px; font-weight: 500; color: #1a1a18; }
  .card-num { color: #2d8c6e; margin-right: 2px; }
  .card-time { font-size: 13px; font-weight: 600; color: #1a1a18; white-space: nowrap; }
  .card-meta { display: flex; align-items: center; gap: 0; font-size: 12px; color: #888780; flex-wrap: wrap; }
  .meta-sep { margin: 0 6px; color: #ccc; }
  .badge-ámeliy { display: inline-block; font-size: 11px; padding: 1px 8px; border-radius: 10px; background: #e6f1fb; color: #185fa5; font-weight: 500; }
  .badge-maruza { display: inline-block; font-size: 11px; padding: 1px 8px; border-radius: 10px; background: #e1f5ee; color: #0f6e56; font-weight: 500; }
  .info-hint { font-size: 11px; color: #b4b2a9; display: flex; align-items: center; gap: 4px; margin-top: 2px; }

  .week-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(140px, 1fr)); gap: 10px; }
  .week-card { background: #fff; border: 0.5px solid #d3d1c7; border-radius: 8px; padding: 12px 14px; cursor: pointer; transition: border-color 0.15s; }
  .week-card:hover { border-color: #b4b2a9; }
  .week-card.today-card { border-color: #2d8c6e; }
  .week-card-name { font-size: 14px; font-weight: 500; margin-bottom: 4px; display: flex; align-items: center; gap: 5px; }
  .week-card-count { font-size: 13px; color: #888780; }
  .week-card-count.zero { color: #b4b2a9; }
  .qadaǵalaw-full { display: flex; flex-direction: column; gap: 14px; }
  .nf-card { background: #fff; border: 0.5px solid #d3d1c7; border-radius: 12px; overflow: hidden; }
  .nf-card-head { padding: 12px 16px; background: #f8f8f4; border-bottom: 0.5px solid #d3d1c7; font-size: 14px; font-weight: 600; color: #1a1a18; display: flex; align-items: center; gap: 8px; }
  .nf-rows { padding: 0 16px; }
  .nf-row { display: flex; align-items: center; justify-content: space-between; padding: 10px 0; border-bottom: 0.5px solid #f0f0ec; gap: 12px; }
  .nf-row:last-child { border-bottom: none; }
  .nf-row-left { flex: 1; }
  .nf-row-tur { font-size: 13px; font-weight: 500; color: #1a1a18; margin-bottom: 3px; display: flex; align-items: center; gap: 7px; }
  .nf-row-date { font-size: 12px; color: #888780; }
  .nf-row-right { text-align: right; flex-shrink: 0; }
  .nf-ball { font-size: 13px; font-weight: 600; color: #1a1a18; }
  .nf-days { font-size: 11px; color: #888780; margin-top: 2px; }
  .days-soon { color: #c0392b; font-weight: 600; }
  .days-today { color: #2d8c6e; font-weight: 700; }
  svg.icon { display: inline-block; vertical-align: middle; flex-shrink: 0; }
  .modal-overlay { display: none; position: fixed; inset: 0; background: rgba(0,0,0,0.35); z-index: 100; align-items: center; justify-content: center; padding: 1rem; }
  .modal-overlay.open { display: flex; }
  .modal { background: #fff; border-radius: 14px; width: 100%; max-width: 400px; overflow: hidden; }
  .modal-header { background: #2d8c6e; color: #fff; padding: 16px 18px; display: flex; align-items: flex-start; justify-content: space-between; gap: 10px; }
  .modal-header-title { font-size: 16px; font-weight: 600; line-height: 1.4; }
  .modal-close { background: none; border: none; color: #fff; font-size: 20px; cursor: pointer; padding: 0; line-height: 1; opacity: 0.85; flex-shrink: 0; margin-top: 2px; }
  .modal-close:hover { opacity: 1; }
  .modal-body { padding: 16px 18px; max-height: 70vh; overflow-y: auto; }
  .modal-section { margin-bottom: 18px; }
  .modal-section:last-child { margin-bottom: 0; }
  .modal-table { width: 100%; border-collapse: collapse; font-size: 14px; }
  .modal-table th { text-align: left; font-weight: 600; font-size: 13px; color: #1a1a18; padding: 6px 0 8px; border-bottom: 1.5px solid #d3d1c7; }
  .modal-table th:last-child { text-align: right; }
  .modal-table td { padding: 8px 0; border-bottom: 0.5px solid #ebebE6; color: #444; font-size: 13px; }
  .modal-table td:last-child { text-align: right; font-weight: 500; color: #1a1a18; }
  .modal-table tr:last-child td { border-bottom: none; font-weight: 600; color: #1a1a18; }
  .modal-divider { border: none; border-top: 0.5px solid #d3d1c7; margin: 14px 0; }
</style>
</head>
<body>
<div class="container">
  <h1>
    <svg class="icon" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
    Sabaq kestesi
  </h1>
  <p class="subtitle" id="subtitle">Búgin anıqlanbaqda...</p>
  <div class="qadaǵalaw-banner" id="qadaǵalaw-banner">
    <div class="qadaǵalaw-banner-head">
      <svg class="icon" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="#7a5c00" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/></svg>
      Bugingi qadaǵalaw esletpeleri
    </div>
    <div id="banner-items"></div>
  </div>
  <div class="tab-row">
    <button class="tab-btn active" id="tab-keste" onclick="switchTab('keste')">
      <svg class="icon" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
      Sabaq kestesi
    </button>
    <button class="tab-btn" id="tab-qadaǵalaw" onclick="switchTab('qadaǵalaw')">
      <svg class="icon" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/></svg>
      Qadaǵalaw kestesi
    </button>
  </div>

 <div id="section-keste">
    <div class="btn-row">
      <button class="btn" id="btn-bugin" onclick="showMode('bugin')">
        <svg class="icon" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
        Búgin
      </button>
      <button class="btn" id="btn-erteń" onclick="showMode('erteń')">
        <svg class="icon" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/><line x1="12" y1="15" x2="12" y2="19"/><line x1="10" y1="17" x2="14" y2="17"/></svg>
        Erteń
      </button>
      <button class="btn" id="btn-hápte" onclick="showMode('hápte')">
        <svg class="icon" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="7" height="7" rx="1"/><rect x="14" y="3" width="7" height="7" rx="1"/><rect x="3" y="14" width="7" height="7" rx="1"/><rect x="14" y="14" width="7" height="7" rx="1"/></svg>
        Hápteniń kestesi
      </button>
      <button class="btn" id="btn-kun" onclick="showMode('kun')">
        <svg class="icon" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><line x1="8" y1="6" x2="21" y2="6"/><line x1="8" y1="12" x2="21" y2="12"/><line x1="8" y1="18" x2="21" y2="18"/><circle cx="3" cy="6" r="1.2" fill="currentColor"/><circle cx="3" cy="12" r="1.2" fill="currentColor"/><circle cx="3" cy="18" r="1.2" fill="currentColor"/></svg>
        Kún tańlaw
      </button>
    </div>
    <div id="content"></div>
  </div>
  <div id="section-qadaǵalaw" style="display:none">
    <div id="qadaǵalaw-content"></div>
  </div>
</div>
<div class="modal-overlay" id="modal-overlay" onclick="closeModal(event)">
  <div class="modal" id="modal-box">
    <div class="modal-header">
      <div class="modal-header-title" id="modal-title">Sabaq</div>
      <button class="modal-close" onclick="closeModalDirect()">✕</button>
    </div>
    <div class="modal-body" id="modal-body"></div>
  </div>
</div>
<script>
const QADAǴALAW_SÁNELERI = {
  "Mobil qosımshalardı islep shıǵıw": [
    { tur:"Házirgi qadaǵalaw",   ball:20, sáne:"2026-05-28" },
    { tur:"Aralıq qadaǵalaw",  ball:30, sáne:"2026-06-10" },
    { tur:"Juwmaqlawshı qadaǵalaw", ball:50, sáne:"2026-07-01" },
  ],
  "Individual joybar": [
    { tur:"Aralıq qadaǵalaw",  ball:50, sáne:"2026-06-05" },
    { tur:"Juwmaqlawshı qadaǵalaw", ball:50, sáne:"2026-06-25" },
  ],
  "Programmalıq támiynat sapasın támiyinlew": [
    { tur:"Házirgi qadaǵalaw",   ball:20, sáne:"2026-05-30" },
    { tur:"Aralıq qadaǵalaw",  ball:30, sáne:"2026-06-12" },
    { tur:"Juwmaqlawshı qadaǵalaw", ball:50, sáne:"2026-07-03" },
  ],
  "Interaktiv bagdarlamalıq qurallar jaratıw texnologiyaları": [
    { tur:"Házirgi qadaǵalaw",   ball:20, sáne:"2026-05-27" },
    { tur:"Aralıq qadaǵalaw",  ball:30, sáne:"2026-06-08" },
    { tur:"Juwmaqlawshı qadaǵalaw", ball:50, sáne:"2026-06-29" },
  ],
  "Kompyuter támiynatı": [
    { tur:"Házirgi qadaǵalaw",   ball:20, sáne:"2026-06-02" },
    { tur:"Aralıq qadaǵalaw",  ball:30, sáne:"2026-06-15" },
    { tur:"Juwmaqlawshı qadaǵalaw", ball:50, sáne:"2026-07-05" },
  ],
};
const SABAQ_INFO = {
  "Mobil qosımshalardı islep shıǵıw": {
    jukleme: [{tur:"Lekciya",saat:"38 saat"},{tur:"Ámeliy",saat:"38 saat"},{tur:"Óz betinshe",saat:"104 saat"},{tur:"Jámi",saat:"180 saat"}],
    qadaǵalaw: [{tur:"Házirgi qadaǵalaw",ball:"20 ball"},{tur:"Aralıq qadaǵalaw",ball:"30 ball"},{tur:"Juwmaqlawshı qadaǵalaw",ball:"50 ball"},{tur:"Ulıwma",ball:"100 ball"}]
  },
  "Individual joybar": {
    jukleme: [{tur:"Ámeliy",saat:"60 saat"},{tur:"Óz betinshe",saat:"60 saat"},{tur:"Jámi",saat:"120 saat"}],
    qadaǵalaw: [{tur:"Aralıq qadaǵalaw",ball:"50 ball"},{tur:"Juwmaqlawshı qadaǵalaw",ball:"50 ball"},{tur:"Ulıwma",ball:"100 ball"}]
  },
  "Programmalıq támiynat sapasın támiyinlew": {
    jukleme: [{tur:"Lekciya",saat:"30 saat"},{tur:"Ámeliy",saat:"30 saat"},{tur:"Óz betinshe",saat:"60 saat"},{tur:"Jámi",saat:"120 saat"}],
    qadaǵalaw: [{tur:"Házirgi qadaǵalaw",ball:"20 ball"},{tur:"Aralıq qadaǵalaw",ball:"30 ball"},{tur:"Juwmaqlawshı qadaǵalaw",ball:"50 ball"},{tur:"Ulıwma",ball:"100 ball"}]
  },
  "Interaktiv bagdarlamalıq qurallar jaratıw texnologiyaları": {
    jukleme: [{tur:"Lekciya",saat:"44 saat"},{tur:"Ámeliy",saat:"46 saat"},{tur:"Óz betinshe",saat:"90 saat"},{tur:"Jámi",saat:"180 saat"}],
    qadaǵalaw: [{tur:"Házirgi qadaǵalaw",ball:"20 ball"},{tur:"Aralıq qadaǵalaw",ball:"30 ball"},{tur:"Juwmaqlawshı qadaǵalaw",ball:"50 ball"},{tur:"Ulıwma",ball:"100 ball"}]
  },
  "Kompyuter támiynatı": {
    jukleme: [{tur:"Lekciya",saat:"30 saat"},{tur:"Ámeliy",saat:"30 saat"},{tur:"Óz betinshe",saat:"60 saat"},{tur:"Jámi",saat:"120 saat"}],
    qadaǵalaw: [{tur:"Házirgi qadaǵalaw",ball:"20 ball"},{tur:"Aralıq qadaǵalaw",ball:"30 ball"},{tur:"Juwmaqlawshı qadaǵalaw",ball:"50 ball"},{tur:"Ulıwma",ball:"100 ball"}]
  }
};

const KESTE = {
  "Dúyshenbi": [
    {num:9,  waqıt:"13:10", pán:"Interaktiv bagdarlamalıq qurallar jaratıw texnologiyaları", tur:"Ámeliy",   xana:"K-217", oqıtıwshı:"AUEZOVA R. T."},
    {num:10, waqıt:"14:50", pán:"Kompyuter támiynatı",                                     tur:"Ámeliy",   xana:"K-224", oqıtıwshı:"BABANAZAROVA M. S."},
    {num:11, waqıt:"16:20", pán:"Individual joybar",                                       tur:"Ámeliy",   xana:"K-224", oqıtıwshı:"ZIUATDINOV I. SH."},
  ],
  "Siyshenbi": [
    {num:9,  waqıt:"13:10", pán:"Mobil qosımshalardı islep shıǵıw",  tur:"Lekciya", xana:"113",   oqıtıwshı:"ZARIPOV O. K."},
    {num:10, waqıt:"14:50", pán:"Individual joybar",                tur:"Ámeliy",  xana:"K-217", oqıtıwshı:"ZIUATDINOV I. SH."},
  ],
  "Sárshembi": [
    {num:2, waqıt:"10:00", pán:"Mobil qosımshalardı islep shıǵıw",                                tur:"Ámeliy",  xana:"K-222", oqıtıwshı:"BERDIBAEV K. J."},
    {num:8, waqıt:"11:40", pán:"Interaktiv bagdarlamalıq qurallar jaratıw texnologiyaları",          tur:"Ámeliy",  xana:"K-217", oqıtıwshı:"AUEZOVA R. T."},
  ],
  "Peyshembi": [
    {num:2, waqıt:"10:00", pán:"Kompyuter támiynatı",                   tur:"Lekciya", xana:"116", oqıtıwshı:"MAMBETNIYAZOV M. T."},
    {num:8, waqıt:"11:40", pán:"Programmalıq támiynat sapasın támiyinlew", tur:"Lekciya", xana:"113", oqıtıwshı:"KALXANOV P. J."},
  ],
  "Juma": [
    {num:1, waqıt:"08:30", pán:"Programmalıq támiynat sapasın támiyinlew",                  tur:"Ámeliy",  xana:"K-217", oqıtıwshı:"QUDAYBERGENOVA G. R."},
    {num:2, waqıt:"10:00", pán:"Interaktiv bagdarlamalıq qurallar jaratıw texnologiyaları", tur:"Lekciya", xana:"221",   oqıtıwshı:"AUEZOVA R. T."},
  ],
  "Shembi":    [],
  "Ekshembi": []
};

const KUNLER = ["Dúyshenbi","Siyshenbi","Sárshembi","Peyshembi","Juma","Shembi","Ekshembi"];
const todayIdx = new Date().getDay() === 0 ? 6 : new Date().getDay() - 1;
const today = KUNLER[todayIdx];
const tomorrow = KUNLER[(todayIdx + 1) % 7];
let selectedKun = today;

const nowDate = new Date();
nowDate.setHours(0,0,0,0);

document.getElementById('subtitle').textContent = "Búgin: " + today;
function daysDiff(sanStr) {
  const d = new Date(sanStr); d.setHours(0,0,0,0);
  return Math.round((d - nowDate) / 86400000);
}
function formatDate(sanStr) {
  const d = new Date(sanStr);
  const months = ["yanvar","fevral","mart","aprel","may","iyun","iyul","avgust","sentabr","oktabr","noyabr","dekabr"];
  return d.getDate() + " " + months[d.getMonth()] + ", " + d.getFullYear();
}
function turClass(tur) {
  if (tur.includes("Házirgi"))   return "nb-házirgi";
  if (tur.includes("Aralıq"))  return "nb-Aralıq";
  if (tur.includes("Juwmaqlawshı")) return "nb-juwmaqlawshı";
  return "nb-házirgi";
}
function daysLabel(diff) {
  if (diff < 0)  return `<spán>${Math.abs(diff)} kun oldin o'tdi</spán>`;
  if (diff === 0) return `<spán class="days-today">BUGIN!</spán>`;
  if (diff <= 7)  return `<spán class="days-soon">${diff} kun qaldı</spán>`;
  return `<spán>${diff} kun qaldı</spán>`;
}
function buildBanner() {
  const items = [];
  for (const pán in QADAǴALAW_SÁNELERI) {
    for (const n of QADAǴALAW_SÁNELERI[pán]) {
      const diff = daysDiff(n.sáne);
      if (diff >= 0 && diff <= 7) items.push({pán, ...n, diff});
    }
  }
  items.sort((a,b) => a.diff - b.diff);
  const banner = document.getElementById('qadaǵalaw-banner');
  const cont   = document.getElementById('banner-items');
  if (!items.length) { banner.classList.remove('show'); return; }
  banner.classList.add('show');
  cont.innerHTML = items.map(it => `
    <div class="qadaǵalaw-item">
      <div class="qadaǵalaw-item-left">
        <div class="qadaǵalaw-pán">${it.pán}</div>
        <spán class="qadaǵalaw-tur-badge ${turClass(it.tur)}">${it.tur}</spán>
        <div class="qadaǵalaw-ball">${it.ball} ball · ${formatDate(it.sáne)}</div>
      </div>
      <div class="qadaǵalaw-date-badge">${it.diff===0?'BUGIN':it.diff+' kun'}</div>
    </div>`).join('');
}
function buildQadaǵalawFull() {
  const allItems = [];
  for (const pán in QADAǴALAW_SÁNELERI) {
    for (const n of QADAǴALAW_SÁNELERI[pán]) {
      allItems.push({pán, ...n, diff: daysDiff(n.sáne)});
    }
  }
  allItems.sort((a,b) => new Date(a.sáne) - new Date(b.sáne));

  // Sabaqlarga guruhlash
  const byPán = {};
  for (const it of allItems) {
    if (!byPán[it.pán]) byPán[it.pán] = [];
    byPán[it.pán].push(it);
  }

  let html = `<div class="qadaǵalaw-full">`;
  for (const pán in byPán) {
    html += `<div class="nf-card">
      <div class="nf-card-head">
        <svg class="icon" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"/><path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"/></svg>
        ${pán}
      </div>
      <div class="nf-rows">`;
    for (const it of byPán[pán]) {
      const past = it.diff < 0;
      html += `<div class="nf-row" style="${past?'opacity:0.45':''}">
        <div class="nf-row-left">
          <div class="nf-row-tur">
            <spán class="qadaǵalaw-tur-badge ${turClass(it.tur)}">${it.tur}</spán>
          </div>
          <div class="nf-row-date">${formatDate(it.sáne)}</div>
        </div>
        <div class="nf-row-right">
          <div class="nf-ball">${it.ball} ball</div>
          <div class="nf-days">${daysLabel(it.diff)}</div>
        </div>
      </div>`;
    }
    html += `</div></div>`;
  }
  html += `</div>`;
  document.getElementById('qadaǵalaw-content').innerHTML = html;
}

// ── TAB SWITCH
function switchTab(tab) {
  document.getElementById('tab-keste').className  = 'tab-btn' + (tab==='keste'  ? ' active' : '');
  document.getElementById('tab-qadaǵalaw').className = 'tab-btn' + (tab==='qadaǵalaw' ? ' active green' : '');
  document.getElementById('section-keste').style.display  = tab==='keste'  ? '' : 'none';
  document.getElementById('section-qadaǵalaw').style.display = tab==='qadaǵalaw' ? '' : 'none';
  if (tab==='qadaǵalaw') buildQadaǵalawFull();
}

// ── SABAQ KESTESI
const ICON_MOON = `<svg class="icon" width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="display:block;margin:0 auto 10px"><path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"/></svg>`;

function turBadge(tur) {
  return tur==="Ámeliy"
    ? `<spán class="badge-ámeliy">Ámeliy</spán>`
    : `<spán class="badge-maruza">Lekciya</spán>`;
}

function getQadaǵalawHint(pán) {
  const list = QADAǴALAW_SÁNELERI[pán];
  if (!list) return '';
  const next = list.filter(n => daysDiff(n.sáne) >= 0).sort((a,b) => new Date(a.sáne)-new Date(b.sáne))[0];
  if (!next) return '';
  const diff = daysDiff(next.sáne);
  const cls  = diff===0 ? 'days-today' : diff<=7 ? 'days-soon' : '';
  const txt  = diff===0 ? 'BUGIN qadaǵalaw!' : diff<=7 ? diff+' kunde qadaǵalaw' : diff+' kunde qadaǵalaw';
  return `<div class="info-hint">
    <svg class="icon" width="11" height="11" viewBox="0 0 24 24" fill="none" stroke="${diff<=7?'#c0392b':'#b4b2a9'}" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/></svg>
    <spán class="${cls}">${next.tur} · ${txt}</spán>
  </div>`;
}

function renderCards(kun) {
  const sabaqlar = KESTE[kun] || [];
  if (!sabaqlar.length) return `<div class="empty">${ICON_MOON}Bul kúni sabaq joq</div>`;
  return `<div class="section-title">${kun} <spán class="badge">${sabaqlar.length} sabaq</spán></div>
  <div class="cards">`
    + sabaqlar.map(d => `
      <div class="card" onclick="openModal('${d.pán.replace(/'/g,"\\'")}')">
        <div class="card-top">
          <div class="card-title"><spán class="card-num">${d.num}.</spán> ${d.pán}</div>
          <div class="card-time">${d.waqıt}</div>
        </div>
        <div class="card-meta">
          <svg class="icon" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M3 21h18"/><rect x="6" y="3" width="12" height="18" rx="1"/><circle cx="15" cy="12" r="1" fill="currentColor"/></svg>
          ${d.xana}<spán class="meta-sep">/</spán>${turBadge(d.tur)}<spán class="meta-sep">/</spán>
          <svg class="icon" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>
          ${d.oqıtıwshı}
        </div>
        ${getQadaǵalawHint(d.pán)}
      </div>`).join('') + `</div>`;
}

function renderWeek() {
  const ci = `<svg class="icon" width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>`;
  return `<div class="section-title">Hápte kestesi</div><div class="week-grid">`
    + KUNLER.map(k => {
      const n = KESTE[k].length, isT = k===today;
      return `<div class="week-card${isT?' today-card':''}" onclick="selectKunFromWeek('${k}')">
        <div class="week-card-name">${ci} ${k}${isT?' <spán style="font-size:9px;color:#2d8c6e">●</spán>':''}</div>
        <div class="week-card-count${n?'':' zero'}">${n?n+' sabaq':'Sabaq joq'}</div>
      </div>`;
    }).join('') + `</div>`;
}

function renderKunTanlaw() {
  return `<div class="section-title">Kún tańlaw</div>
  <div class="day-tabs">`
    + KUNLER.map(k=>`<button class="day-tab${k===today?' today':''}${k===selectedKun?' active':''}" onclick="selectKun('${k}')">${k}</button>`).join('')
    + `</div><div id="kun-cards">${renderCards(selectedKun)}</div>`;
}

function selectKun(k) {
  selectedKun = k;
  document.querySelectorAll('.day-tab').forEach(b=>b.classList.toggle('active',b.textContent.trim()===k));
  document.getElementById('kun-cards').innerHTML = renderCards(k);
}
function selectKunFromWeek(k) { selectedKun=k; showMode('kun'); }

function showMode(mode) {
  ['bugin','erteń','hápte','kun'].forEach(m=>document.getElementById('btn-'+m).classList.toggle('active',m===mode));
  const el = document.getElementById('content');
  if (mode==='bugin')       el.innerHTML = renderCards(today);
  else if (mode==='erteń') el.innerHTML = `<div class="section-title" style="font-size:14px;color:#888780;font-weight:400;margin-bottom:8px">Erteń: ${tomorrow}</div>`+renderCards(tomorrow);
  else if (mode==='hápte')  el.innerHTML = renderWeek();
  else if (mode==='kun')    el.innerHTML = renderKunTanlaw();
}

// ── MODAL
function openModal(pán) {
  const info = SABAQ_INFO[pán]; if (!info) return;
  document.getElementById('modal-title').textContent = pán;
  const naz = QADAǴALAW_SÁNELERI[pán] || [];
  let nazSection = '';
  if (naz.length) {
    nazSection = `<hr class="modal-divider">
    <div class="modal-section">
      <table class="modal-table">
        <thead><tr><th>Qadaǵalaw</th><th>Sáne / Ball</th></tr></thead>
        <tbody>${naz.map(n => {
          const diff = daysDiff(n.sáne);
          const dl = diff<0 ? `<spán style="color:#b4b2a9;font-size:11px">o'tdi</spán>`
                   : diff===0 ? `<spán class="days-today" style="font-size:11px">BUGIN</spán>`
                   : diff<=7  ? `<spán class="days-soon" style="font-size:11px">${diff} kun</spán>`
                   : `<spán style="font-size:11px;color:#888780">${diff} kun</spán>`;
          return `<tr><td><spán class="qadaǵalaw-tur-badge ${turClass(n.tur)}">${n.tur}</spán><br><spán style="font-size:11px;color:#888780">${formatDate(n.sáne)}</spán></td><td>${n.ball} ball<br>${dl}</td></tr>`;
        }).join('')}</tbody>
      </table>
    </div>`;
  }
  let yukRows = info.jukleme.map((r,i)=>{
    const last = i===info.jukleme.length-1;
    return `<tr${last?' style="font-weight:600"':''}><td>${r.tur}</td><td>${r.saat}</td></tr>`;
  }).join('');
  let nazRows = info.qadaǵalaw.map((r,i)=>{
    const last = i===info.qadaǵalaw.length-1;
    return `<tr${last?' style="font-weight:600"':''}><td>${r.tur}</td><td>${r.ball}</td></tr>`;
  }).join('');
  document.getElementById('modal-body').innerHTML = `
    <div class="modal-section">
      <table class="modal-table">
        <thead><tr><th>Shınıǵıw</th><th>Jukleme</th></tr></thead>
        <tbody>${yukRows}</tbody>
      </table>
    </div>
    <hr class="modal-divider">
    <div class="modal-section">
      <table class="modal-table">
        <thead><tr><th>Qadaǵalaw turi</th><th>Maks. ball</th></tr></thead>
        <tbody>${nazRows}</tbody>
      </table>
    </div>
    ${nazSection}`;
  document.getElementById('modal-overlay').classList.add('open');
  document.body.style.overflow = 'hidden';
}
function closeModalDirect() {
  document.getElementById('modal-overlay').classList.remove('open');
  document.body.style.overflow = '';
}
function closeModal(e) { if(e.target===document.getElementById('modal-overlay')) closeModalDirect(); }
document.addEventListener('keydown', e=>{ if(e.key==='Escape') closeModalDirect(); });

// ── INIT
buildBanner();
showMode('bugin');
</script>
</body>
</html>


