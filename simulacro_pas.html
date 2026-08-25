<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Simulacro PAS — PRO TRANSPORTE S.A.S.</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@500;600;700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --asphalt:#14161c;
    --asphalt-2:#1d212b;
    --card:#252a35;
    --card-2:#2e3441;
    --amber:#ffb627;
    --amber-dim:#8a6c22;
    --red:#e4572e;
    --green:#3fa34d;
    --white:#f5f3ec;
    --steel:#9aa0ad;
    --line:#3a3f4c;
  }
  *{box-sizing:border-box;}
  html,body{margin:0;padding:0;}
  body{
    background:
      radial-gradient(ellipse at 20% -10%, #2a3040 0%, transparent 55%),
      radial-gradient(ellipse at 90% 0%, #2a2320 0%, transparent 45%),
      var(--asphalt);
    color:var(--white);
    font-family:'Inter',sans-serif;
    min-height:100vh;
    display:flex;
    justify-content:center;
    padding:28px 16px 60px;
  }
  .wrap{width:100%;max-width:760px;}

  /* ---------- HEADER ---------- */
  .brand{display:flex;align-items:center;justify-content:space-between;margin-bottom:18px;gap:12px;flex-wrap:wrap;}
  .brand-left{display:flex;flex-direction:column;}
  .eyebrow{
    font-family:'Oswald',sans-serif;font-size:12px;letter-spacing:.18em;
    color:var(--amber);text-transform:uppercase;font-weight:600;
  }
  h1{
    font-family:'Oswald',sans-serif;font-weight:700;font-size:26px;
    margin:2px 0 0;letter-spacing:.01em;text-transform:uppercase;
  }
  .score-plate{
    background:var(--card);border:2px solid var(--line);border-radius:10px;
    padding:8px 14px;text-align:center;min-width:96px;
  }
  .score-plate .num{font-family:'Oswald',sans-serif;font-size:22px;font-weight:700;color:var(--amber);line-height:1;}
  .score-plate .lbl{font-size:10px;letter-spacing:.1em;color:var(--steel);text-transform:uppercase;margin-top:2px;}

  /* ---------- ROUTE STRIP (signature element) ---------- */
  .route{position:relative;margin:6px 0 26px;padding:0 6px;}
  .route-road{
    position:relative;height:6px;border-radius:4px;background:var(--line);overflow:visible;
  }
  .route-fill{
    position:absolute;top:0;left:0;height:100%;border-radius:4px;
    background:linear-gradient(90deg,var(--amber-dim),var(--amber));
    transition:width .6s ease;
  }
  .route-dashes{
    position:absolute;inset:0;background-image:repeating-linear-gradient(90deg,#ffffff55 0 10px, transparent 10px 20px);
    mix-blend-mode:overlay;
  }
  .route-truck{
    position:absolute;top:-17px;font-size:22px;transform:translateX(-50%);
    transition:left .6s cubic-bezier(.4,0,.2,1);filter:drop-shadow(0 2px 3px #000a);
  }
  .route-markers{display:flex;justify-content:space-between;margin-top:12px;}
  .marker{text-align:center;flex:1;font-family:'Oswald',sans-serif;font-size:10.5px;letter-spacing:.06em;
    text-transform:uppercase;color:var(--steel);position:relative;}
  .marker.active{color:var(--amber);}
  .marker.done{color:var(--green);}
  .marker .dot{width:9px;height:9px;border-radius:50%;background:var(--line);margin:0 auto 6px;
    border:2px solid var(--asphalt);}
  .marker.active .dot{background:var(--amber);box-shadow:0 0 0 4px #ffb62733;}
  .marker.done .dot{background:var(--green);}

  /* ---------- CARD ---------- */
  .card{
    background:var(--card);border:1px solid var(--line);border-radius:16px;
    padding:26px 24px;box-shadow:0 12px 30px -12px #000a;
  }
  .tag{
    display:inline-block;font-family:'Oswald',sans-serif;font-size:11px;letter-spacing:.14em;
    text-transform:uppercase;padding:4px 10px;border-radius:20px;margin-bottom:12px;font-weight:600;
  }
  .tag.proteger{background:#3fa34d22;color:var(--green);border:1px solid #3fa34d55;}
  .tag.avisar{background:#ffb62722;color:var(--amber);border:1px solid #ffb62755;}
  .tag.socorrer{background:#e4572e22;color:var(--red);border:1px solid #e4572e55;}
  .tag.casos{background:#8a8f9c22;color:var(--steel);border:1px solid #8a8f9c55;}

  h2{font-family:'Oswald',sans-serif;font-size:21px;margin:0 0 8px;line-height:1.25;}
  p.desc{color:var(--steel);font-size:14.5px;line-height:1.55;margin:0 0 18px;}

  /* ---------- SCENE (hazard spotting) ---------- */
  .scene{
    position:relative;width:100%;aspect-ratio:16/9;border-radius:12px;overflow:hidden;
    background:linear-gradient(#5b7a9e 0%,#7c98b8 38%,#8b8f78 38%,#6f7460 42%,#54575060 42%,#4a4d47 100%);
    margin-bottom:16px;border:1px solid var(--line);
  }
  .scene .road{
    position:absolute;left:0;right:0;bottom:0;height:46%;
    background:#3a3d44;
  }
  .scene .road::before{
    content:"";position:absolute;top:50%;left:0;right:0;height:4px;transform:translateY(-50%);
    background-image:repeating-linear-gradient(90deg,#ffb627 0 26px, transparent 26px 52px);
  }
  .spot{
    position:absolute;font-size:30px;cursor:pointer;user-select:none;line-height:1;
    filter:drop-shadow(0 2px 3px #0008);transition:transform .15s ease;
    background:none;border:none;padding:4px;
  }
  .spot:hover{transform:scale(1.12);}
  .spot.picked-correct{outline:3px solid var(--green);border-radius:50%;background:#3fa34d33;}
  .spot.picked-wrong{outline:3px solid var(--red);border-radius:50%;background:#e4572e33;}
  .spot.missed{outline:3px dashed var(--amber);border-radius:50%;}
  .spot[disabled]{cursor:default;}
  .hazard-tally{font-size:13px;color:var(--steel);margin-bottom:14px;}
  .hazard-tally b{color:var(--white);}

  /* ---------- OPTIONS / CHECKLIST ---------- */
  .options{display:flex;flex-direction:column;gap:10px;margin-bottom:18px;}
  .opt{
    display:flex;align-items:flex-start;gap:10px;background:var(--card-2);border:1.5px solid var(--line);
    border-radius:10px;padding:12px 14px;cursor:pointer;font-size:14.5px;line-height:1.4;transition:.15s;
  }
  .opt:hover{border-color:var(--amber-dim);}
  .opt .mark{
    flex:0 0 20px;height:20px;border-radius:5px;border:2px solid var(--steel);margin-top:1px;
    display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:700;color:transparent;
  }
  .opt.radio .mark{border-radius:50%;}
  .opt.selected .mark{border-color:var(--amber);background:var(--amber);color:var(--asphalt);}
  .opt.correct{border-color:var(--green);background:#3fa34d1f;}
  .opt.correct .mark{border-color:var(--green);background:var(--green);color:#0c1a0e;}
  .opt.incorrect{border-color:var(--red);background:#e4572e1f;}
  .opt.incorrect .mark{border-color:var(--red);background:var(--red);color:#2a0d05;}
  .opt.disabled{cursor:default;}

  .feedback{
    border-radius:10px;padding:12px 14px;font-size:14px;line-height:1.5;margin-bottom:16px;display:none;
  }
  .feedback.show{display:block;}
  .feedback.good{background:#3fa34d1f;border:1px solid #3fa34d55;color:#c9edd0;}
  .feedback.bad{background:#e4572e1f;border:1px solid #e4572e55;color:#f6d2c6;}

  .actions{display:flex;justify-content:flex-end;gap:10px;}
  button.btn{
    font-family:'Oswald',sans-serif;font-weight:600;letter-spacing:.04em;text-transform:uppercase;
    font-size:13.5px;padding:11px 22px;border-radius:9px;border:none;cursor:pointer;transition:.15s;
  }
  .btn.primary{background:var(--amber);color:#241a03;}
  .btn.primary:hover{filter:brightness(1.08);}
  .btn.primary:disabled{background:var(--line);color:var(--steel);cursor:not-allowed;}
  .btn.ghost{background:transparent;color:var(--steel);border:1.5px solid var(--line);}
  .btn.ghost:hover{color:var(--white);border-color:var(--steel);}

  /* ---------- INTRO / RESULTS ---------- */
  .hero-icon{font-size:44px;margin-bottom:8px;}
  ul.bullets{margin:0 0 18px;padding-left:20px;color:var(--steel);font-size:14px;line-height:1.7;}
  .stage-recap{width:100%;border-collapse:collapse;margin-bottom:18px;}
  .stage-recap th,.stage-recap td{text-align:left;padding:10px 8px;font-size:13.5px;border-bottom:1px solid var(--line);}
  .stage-recap th{color:var(--steel);font-family:'Oswald',sans-serif;letter-spacing:.06em;text-transform:uppercase;font-size:11px;}
  .badge{
    display:flex;align-items:center;gap:14px;background:var(--card-2);border:1px solid var(--amber-dim);
    border-radius:12px;padding:16px;margin-bottom:18px;
  }
  .badge .emoji{font-size:34px;}
  .badge .title{font-family:'Oswald',sans-serif;font-weight:700;font-size:16px;color:var(--amber);}
  .badge .sub{font-size:12.5px;color:var(--steel);margin-top:2px;}
  .quote{
    text-align:center;font-family:'Oswald',sans-serif;font-size:15px;color:var(--white);
    border-top:1px dashed var(--line);border-bottom:1px dashed var(--line);padding:14px 6px;margin:6px 0 18px;
  }
  footer{text-align:center;color:var(--steel);font-size:11.5px;margin-top:22px;letter-spacing:.03em;}
</style>
</head>
<body>
<div class="wrap">

  <div class="brand">
    <div class="brand-left">
      <span class="eyebrow">Pro Transporte S.A.S. · D-GO-14</span>
      <h1>Simulacro PAS</h1>
    </div>
    <div class="score-plate">
      <div class="num" id="scoreNum">0/0</div>
      <div class="lbl">Aciertos</div>
    </div>
  </div>

  <div class="route">
    <div class="route-road">
      <div class="route-fill" id="routeFill" style="width:0%"></div>
      <div class="route-dashes"></div>
      <div class="route-truck" id="routeTruck" style="left:0%">🚚</div>
    </div>
    <div class="route-markers" id="routeMarkers"></div>
  </div>

  <div class="card" id="card"></div>

  <footer>Basado en D-GO-14 · Protocolo PAS para la atención de siniestros viales · V.2</footer>
</div>

<script>
/* ===================== DATA ===================== */

const STAGE_GROUPS = ["PROTEGER","AVISAR","SOCORRER","CASOS","META"];

const HAZARDS = [
  {id:"traf", emoji:"🚗", top:"58%", left:"10%", correct:true, label:"Tráfico vehicular y riesgo de atropellamiento"},
  {id:"fuego", emoji:"🔥", top:"30%", left:"78%", correct:true, label:"Incendio, humo o explosión"},
  {id:"derrame", emoji:"🛢️", top:"70%", left:"46%", correct:true, label:"Derrame de combustible o sustancias"},
  {id:"volcado", emoji:"🚛", top:"46%", left:"64%", correct:true, label:"Vehículo inestable o con riesgo de volcamiento", rot:true},
  {id:"cables", emoji:"⚡", top:"14%", left:"36%", correct:true, label:"Cables eléctricos u otros elementos energizados"},
  {id:"clima", emoji:"🌧️", top:"10%", left:"85%", correct:true, label:"Condiciones climáticas o de visibilidad"},
  {id:"peaton", emoji:"🚶", top:"60%", left:"88%", correct:true, label:"Presencia de peatones u otros actores viales"},
  {id:"hazmat", emoji:"☣️", top:"72%", left:"20%", correct:true, label:"Mercancías peligrosas que representen un riesgo"},
  {id:"arbol", emoji:"🌳", top:"18%", left:"6%", correct:false, label:"Un árbol junto a la vía (no representa un peligro por sí solo)"},
  {id:"senal", emoji:"🛑", top:"36%", left:"14%", correct:false, label:"Una señal de tránsito en buen estado (no es un peligro)"},
];

const Q_PROTEGER = {
  prompt:"Acabas de detener el vehículo cerca del siniestro. ¿Qué debes hacer primero, antes de acercarte a los heridos?",
  type:"single",
  options:[
    {t:"Correr de inmediato a socorrer a los lesionados.", c:false},
    {t:"Evaluar la situación e identificar los peligros de la escena.", c:true},
    {t:"Mover el vehículo accidentado para despejar la vía.", c:false},
    {t:"Retirar el casco del motociclista para revisarlo mejor.", c:false},
  ],
  exp:"La primera prioridad es protegerse a sí mismo y evaluar la escena antes de actuar. No te conviertas en una segunda víctima."
};

const Q_AVISAR_NUM = {
  prompt:"Vas a reportar el siniestro. ¿A qué línea de emergencias te comunicas primero?",
  type:"single",
  options:[
    {t:"123 — Línea Única de Emergencias", c:true},
    {t:"Línea de atención al cliente de la empresa", c:false},
    {t:"El taller de mantenimiento de la flota", c:false},
    {t:"Un grupo de WhatsApp de conductores", c:false},
  ],
  exp:"Comuníquese con la línea de emergencias 123, y con #767 cuando corresponda. Además, informe de inmediato a su jefe inmediato y al área de SST."
};

const Q_AVISAR_CHECK = {
  prompt:"Al reportar la emergencia, selecciona TODA la información que debes entregar:",
  type:"multi",
  options:[
    {t:"Qué ocurrió (tipo de siniestro)", c:true},
    {t:"Dónde ocurrió (ubicación exacta y puntos de referencia)", c:true},
    {t:"Cuándo ocurrió (hora aproximada)", c:true},
    {t:"Cuántas personas están involucradas", c:true},
    {t:"Qué peligros existen (incendio, derrame, cables, etc.)", c:true},
    {t:"Qué vehículos están involucrados", c:true},
    {t:"El color de tu uniforme", c:false},
    {t:"Tu horario de almuerzo", c:false},
  ],
  exp:"Una buena comunicación puede marcar la diferencia entre la vida y la muerte: sé claro, rápido y preciso con estos seis datos."
};

const Q_SOCORRER = [
  {t:"Debo mover a los lesionados para que estén más cómodos.", c:false, exp:"No movilice a los lesionados, salvo que exista un peligro inminente que haga necesario retirarlos."},
  {t:"Puedo retirar el casco del lesionado si no es estrictamente necesario.", c:false, exp:"No retire cascos, cinturones u otros elementos de protección sin necesidad."},
  {t:"Debo tranquilizar y acompañar a los lesionados mientras llega la ayuda profesional.", c:true, exp:"Correcto: tranquilizar y acompañar es parte central de socorrer sin causar más daño."},
  {t:"Puedo darle agua o algo de comer al lesionado para calmarlo.", c:false, exp:"No suministre medicamentos, alimentos ni bebidas."},
  {t:"Si tengo formación de primer respondiente, puedo brindar primeros auxilios básicos.", c:true, exp:"Correcto: brinde primeros auxilios únicamente si cuenta con la formación necesaria."},
  {t:"Debo seguir las instrucciones de los organismos de emergencia cuando lleguen al lugar.", c:true, exp:"Correcto: una vez llega la ayuda profesional, siga sus instrucciones."},
];

const Q_CASOS = [
  {
    scenario:"Hay un derrame de combustible sobre la vía.",
    options:[
      {t:"Mantenerte alejado, evitar fuentes de ignición e informar a los organismos de emergencia.", c:true},
      {t:"Intentar contener el derrame con tierra tú mismo.", c:false},
      {t:"Encender un cigarrillo mientras esperas ayuda.", c:false},
    ]
  },
  {
    scenario:"El vehículo quedó volcado sobre su costado.",
    options:[
      {t:"Intentar enderezarlo con ayuda de otros conductores.", c:false},
      {t:"Señalizar, mantener a las personas alejadas y esperar personal especializado.", c:true},
      {t:"Ingresar a la zona de riesgo para revisar el interior.", c:false},
    ]
  },
  {
    scenario:"La carga lleva rombo de mercancía peligrosa y hay daños visibles.",
    options:[
      {t:"Abrir la carga para verificar qué se dañó.", c:false},
      {t:"Mover las cajas para despejar la vía.", c:false},
      {t:"No manipular la carga, mantener distancia e informar la presencia de mercancía peligrosa.", c:true},
    ]
  },
  {
    scenario:"Sale humo del motor del vehículo accidentado.",
    options:[
      {t:"Alejarte de la zona de peligro e informar de inmediato a los organismos de emergencia.", c:true},
      {t:"Abrir el capó para revisar el motor.", c:false},
      {t:"Acercarte a apagar el fuego con tu chaqueta.", c:false},
    ]
  },
];

/* ===================== STATE ===================== */
let state = {
  screen:"intro",           // intro | hazards | q_proteger | q_avisar1 | q_avisar2 | q_socorrer | q_casos | results
  score:0,
  total:0,
  hazardPicks:{},
  socorrerIdx:0,
  socorrerAnswered:false,
  casosIdx:0,
  casosAnswered:false,
  answeredSingle:false,
  answeredMulti:false,
  multiSel:[]
};

const GROUP_OF_SCREEN = {
  intro:0, hazards:0, q_proteger:0,
  q_avisar1:1, q_avisar2:1,
  q_socorrer:2,
  q_casos:3,
  results:4
};

/* ===================== HELPERS ===================== */
function setScore(delta){ if(delta) state.score += delta; }
function pct(n,d){ return d? Math.round(100*n/d):0; }

function renderRoute(){
  const groupIdx = GROUP_OF_SCREEN[state.screen] ?? 0;
  const fillPct = (groupIdx/(STAGE_GROUPS.length-1))*100;
  document.getElementById('routeFill').style.width = fillPct+"%";
  document.getElementById('routeTruck').style.left = fillPct+"%";
  const mEl = document.getElementById('routeMarkers');
  mEl.innerHTML = STAGE_GROUPS.map((g,i)=>{
    let cls = i<groupIdx? "done" : i===groupIdx? "active":"";
    return `<div class="marker ${cls}"><div class="dot"></div>${g}</div>`;
  }).join("");
  document.getElementById('scoreNum').textContent = state.score+"/"+state.total;
}

function card(html){ document.getElementById('card').innerHTML = html; renderRoute(); }

/* ===================== SCREENS ===================== */

function screenIntro(){
  card(`
    <div class="hero-icon">🚧</div>
    <span class="tag proteger">Briefing</span>
    <h2>Vas de camino a un siniestro vial</h2>
    <p class="desc">Recibes un aviso: uno de los vehículos de la flota está involucrado en un siniestro vial más adelante. Antes de que lleguen las autoridades, tú eres la primera respuesta. Este simulacro pone a prueba las tres fases del protocolo:</p>
    <ul class="bullets">
      <li><b style="color:var(--green)">PROTEGER</b> — la escena, a ti mismo y a los demás.</li>
      <li><b style="color:var(--amber)">AVISAR</b> — de forma clara, rápida y precisa.</li>
      <li><b style="color:var(--red)">SOCORRER</b> — sin causar más daño.</li>
    </ul>
    <div class="actions">
      <button class="btn primary" onclick="goHazards()">Iniciar simulacro →</button>
    </div>
  `);
}

/* ---- PROTEGER: hazard spotting ---- */
function goHazards(){
  state.screen="hazards";
  state.hazardPicks={};
  const spotsHtml = HAZARDS.map(h=>`
    <button class="spot" data-id="${h.id}" style="top:${h.top};left:${h.left};${h.rot?'transform:rotate(-8deg);':''}" onclick="pickHazard('${h.id}')">${h.emoji}</button>
  `).join("");
  card(`
    <span class="tag proteger">1 · Proteger</span>
    <h2>Identifica los peligros de la escena</h2>
    <p class="desc">Antes de acercarte, toca todos los elementos que representen un peligro real. Evita los que no lo sean.</p>
    <div class="hazard-tally">Peligros marcados: <b id="tally">0</b> / ${HAZARDS.filter(h=>h.correct).length}</div>
    <div class="scene"><div class="road"></div>${spotsHtml}</div>
    <div class="feedback" id="fb"></div>
    <div class="actions">
      <button class="btn ghost" onclick="revealHazards()">Terminar identificación</button>
    </div>
  `);
}

function pickHazard(id){
  if(state.hazardPicks[id]!==undefined) return;
  const h = HAZARDS.find(x=>x.id===id);
  state.hazardPicks[id]=true;
  const el = document.querySelector(`.spot[data-id="${id}"]`);
  el.classList.add(h.correct?"picked-correct":"picked-wrong");
  el.disabled = true;
  document.getElementById('tally').textContent = Object.keys(state.hazardPicks).filter(k=>HAZARDS.find(h=>h.id===k).correct).length;
}

function revealHazards(){
  let correctPicked=0, wrongPicked=0, missed=0;
  HAZARDS.forEach(h=>{
    const el = document.querySelector(`.spot[data-id="${h.id}"]`);
    el.disabled = true;
    const picked = state.hazardPicks[h.id]!==undefined;
    if(h.correct && picked) correctPicked++;
    if(h.correct && !picked){ missed++; el.classList.add("missed"); }
    if(!h.correct && picked) wrongPicked++;
  });
  const totalHazards = HAZARDS.filter(h=>h.correct).length;
  const good = correctPicked===totalHazards && wrongPicked===0;
  state.total += 1;
  if(good) setScore(1);
  const fb = document.getElementById('fb');
  fb.className = "feedback show " + (good?"good":"bad");
  fb.innerHTML = good
    ? `<b>Bien hecho.</b> Detectaste los ${totalHazards} peligros sin marcar elementos seguros.`
    : `<b>Repaso:</b> peligros correctos: ${correctPicked}/${totalHazards}${wrongPicked?`, marcaste ${wrongPicked} elemento(s) que no eran peligro`:""}${missed?`, te faltaron ${missed} por señalar (borde punteado ámbar)`:""}.`;
  document.querySelector('.actions').innerHTML = `<button class="btn primary" onclick="goProtegerQuiz()">Continuar →</button>`;
}

/* ---- generic single/multi question renderer ---- */
function renderQuestion(q, tag, tagLabel, onNext){
  const isMulti = q.type==="multi";
  const optsHtml = q.options.map((o,i)=>`
    <div class="opt ${isMulti?'':'radio'}" data-i="${i}" onclick="toggleOpt(${i}, ${isMulti})">
      <div class="mark">${isMulti?'':''}</div>
      <div>${o.t}</div>
    </div>
  `).join("");
  card(`
    <span class="tag ${tag}">${tagLabel}</span>
    <h2>${q.prompt}</h2>
    <div class="options" id="opts">${optsHtml}</div>
    <div class="feedback" id="fb"></div>
    <div class="actions" id="actions">
      <button class="btn primary" id="checkBtn" disabled onclick="checkQuestion()">Comprobar</button>
    </div>
  `);
  state._q = q;
  state._selected = new Set();
  state._checked = false;
  state._onNext = onNext;
}

function toggleOpt(i, isMulti){
  if(state._checked) return;
  const el = document.querySelector(`.opt[data-i="${i}"]`);
  if(isMulti){
    if(state._selected.has(i)){ state._selected.delete(i); el.classList.remove('selected'); }
    else { state._selected.add(i); el.classList.add('selected'); }
  } else {
    document.querySelectorAll('.opt').forEach(o=>o.classList.remove('selected'));
    state._selected = new Set([i]);
    el.classList.add('selected');
  }
  document.getElementById('checkBtn').disabled = state._selected.size===0;
}

function checkQuestion(){
  const q = state._q;
  state._checked = true;
  document.querySelectorAll('.opt').forEach((el,i)=>{
    el.classList.add('disabled');
    el.onclick=null;
    const correct = q.options[i].c;
    const chosen = state._selected.has(i);
    if(correct) el.classList.add('correct');
    else if(chosen && !correct) el.classList.add('incorrect');
  });
  const correctSet = new Set(q.options.map((o,i)=>o.c?i:null).filter(v=>v!==null));
  const isRight = correctSet.size===state._selected.size && [...correctSet].every(i=>state._selected.has(i));
  state.total += 1;
  if(isRight) setScore(1);
  const fb = document.getElementById('fb');
  fb.className = "feedback show " + (isRight?"good":"bad");
  fb.innerHTML = `<b>${isRight?"¡Correcto!":"No exactamente."}</b> ${q.exp}`;
  document.getElementById('actions').innerHTML = `<button class="btn primary" onclick="(${state._onNext.toString()})()">Continuar →</button>`;
}

function goProtegerQuiz(){
  renderQuestion(Q_PROTEGER, "proteger", "1 · Proteger", goAvisarNum);
}
function goAvisarNum(){
  state.screen="q_avisar1";
  renderQuestion(Q_AVISAR_NUM, "avisar", "2 · Avisar", goAvisarCheck);
}
function goAvisarCheck(){
  state.screen="q_avisar2";
  renderQuestion(Q_AVISAR_CHECK, "avisar", "2 · Avisar", goSocorrer);
}

/* ---- SOCORRER: rapid true/false series ---- */
function goSocorrer(){
  state.screen="q_socorrer";
  state.socorrerIdx=0;
  renderSocorrer();
}
function renderSocorrer(){
  const item = Q_SOCORRER[state.socorrerIdx];
  state.socorrerAnswered=false;
  card(`
    <span class="tag socorrer">3 · Socorrer</span>
    <h2>Situación ${state.socorrerIdx+1} de ${Q_SOCORRER.length}</h2>
    <p class="desc" style="font-size:15.5px;color:var(--white);">${item.t}</p>
    <div class="options">
      <div class="opt radio" onclick="answerSocorrer(true)"><div class="mark"></div>Sí, es correcto hacerlo</div>
      <div class="opt radio" onclick="answerSocorrer(false)"><div class="mark"></div>No, no se debe hacer</div>
    </div>
    <div class="feedback" id="fb"></div>
    <div class="actions" id="actions"></div>
  `);
}
function answerSocorrer(said){
  if(state.socorrerAnswered) return;
  state.socorrerAnswered = true;
  const item = Q_SOCORRER[state.socorrerIdx];
  const isRight = said===item.c;
  state.total+=1;
  if(isRight) setScore(1);
  document.querySelectorAll('.opt').forEach(o=>o.onclick=null);
  const fb = document.getElementById('fb');
  fb.className="feedback show "+(isRight?"good":"bad");
  fb.innerHTML = `<b>${isRight?"¡Correcto!":"No exactamente."}</b> ${item.exp}`;
  const isLast = state.socorrerIdx===Q_SOCORRER.length-1;
  document.getElementById('actions').innerHTML = `<button class="btn primary" onclick="${isLast?'goCasos()':'nextSocorrer()'}">${isLast?"Ver casos especiales →":"Siguiente →"}</button>`;
}
function nextSocorrer(){ state.socorrerIdx++; renderSocorrer(); }

/* ---- CASOS ESPECIALES ---- */
function goCasos(){
  state.screen="q_casos";
  state.casosIdx=0;
  renderCasos();
}
function renderCasos(){
  const c = Q_CASOS[state.casosIdx];
  state.casosAnswered=false;
  const optsHtml = c.options.map((o,i)=>`
    <div class="opt radio" data-i="${i}" onclick="answerCasos(${i})"><div class="mark"></div>${o.t}</div>
  `).join("");
  card(`
    <span class="tag casos">4 · Casos especiales</span>
    <h2>Caso ${state.casosIdx+1} de ${Q_CASOS.length}: ${c.scenario}</h2>
    <p class="desc">¿Cuál es la acción correcta?</p>
    <div class="options">${optsHtml}</div>
    <div class="feedback" id="fb"></div>
    <div class="actions" id="actions"></div>
  `);
}
function answerCasos(i){
  if(state.casosAnswered) return;
  state.casosAnswered=true;
  const c = Q_CASOS[state.casosIdx];
  const isRight = c.options[i].c;
  state.total+=1;
  if(isRight) setScore(1);
  document.querySelectorAll('.opt').forEach((el,idx)=>{
    el.onclick=null; el.classList.add('disabled');
    if(c.options[idx].c) el.classList.add('correct');
    else if(idx===i) el.classList.add('incorrect');
  });
  const fb = document.getElementById('fb');
  fb.className="feedback show "+(isRight?"good":"bad");
  fb.innerHTML = `<b>${isRight?"¡Correcto!":"No exactamente."}</b> Ante mercancías peligrosas, derrames o incendios, la prioridad es no exponerte, no manipular la carga o sustancia, y avisar de inmediato a los organismos de emergencia.`;
  const isLast = state.casosIdx===Q_CASOS.length-1;
  document.getElementById('actions').innerHTML = `<button class="btn primary" onclick="${isLast?'goResults()':'nextCasos()'}">${isLast?"Ver resultado final →":"Siguiente caso →"}</button>`;
}
function nextCasos(){ state.casosIdx++; renderCasos(); }

/* ---- RESULTS ---- */
function goResults(){
  state.screen="results";
  const p = pct(state.score, state.total);
  let badgeEmoji="🥉", badgeTitle="Sigue practicando", badgeSub="Repasa el protocolo y vuelve a intentarlo.";
  if(p>=90){ badgeEmoji="🏅"; badgeTitle="Conductor PAS Certificado"; badgeSub="Dominas las tres fases del protocolo."; }
  else if(p>=70){ badgeEmoji="🥈"; badgeTitle="Buen desempeño"; badgeSub="Estás muy cerca de dominar el protocolo."; }

  card(`
    <span class="tag proteger">Resultado</span>
    <h2>Simulacro completado</h2>
    <div class="badge">
      <div class="emoji">${badgeEmoji}</div>
      <div>
        <div class="title">${badgeTitle}</div>
        <div class="sub">${badgeSub}</div>
      </div>
      <div style="margin-left:auto;text-align:right;">
        <div style="font-family:'Oswald',sans-serif;font-size:26px;font-weight:700;color:var(--amber);">${state.score}/${state.total}</div>
        <div style="font-size:11px;color:var(--steel);">${p}% de aciertos</div>
      </div>
    </div>

    <table class="stage-recap">
      <tr><th>Etapa</th><th>Recomendación clave</th></tr>
      <tr><td style="color:var(--green);font-weight:600;">PROTEGER</td><td>No convertirse en una segunda víctima. Proteger la escena, señalizar y evitar nuevos riesgos.</td></tr>
      <tr><td style="color:var(--amber);font-weight:600;">AVISAR</td><td>Pedir la ayuda correcta y entregar información clara y precisa.</td></tr>
      <tr><td style="color:var(--red);font-weight:600;">SOCORRER</td><td>Ayudar sin causar más daño. Brindar primeros auxilios solo si se cuenta con formación.</td></tr>
    </table>

    <div class="quote">"No necesitamos ser héroes. Necesitamos actuar correctamente."</div>

    <div class="actions">
      <button class="btn ghost" onclick="restart()">Repetir simulacro</button>
    </div>
  `);
}

function restart(){
  state = {screen:"intro", score:0, total:0, hazardPicks:{}, socorrerIdx:0, casosIdx:0};
  screenIntro();
}

/* ===================== INIT ===================== */
screenIntro();
</script>
</body>
</html>
