<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no,viewport-fit=cover">
<meta name="theme-color" content="#CC1F1F">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Techpack">
<meta http-equiv="Permissions-Policy" content="geolocation=(self)">
<title>Techpack Attendance</title>
<style>
:root{--red:#CC1F1F;--rdk:#A01515;--rlt:#FDF0F0;--ylw:#F5C100;--blu:#2563EB;--blt:#DBEAFE;--grn:#16a34a;--glt:#DCFCE7;--bg:#EDEDED;--wh:#fff;--g1:#F5F5F5;--g2:#E6E6E6;--g3:#C4C4C4;--g4:#888;--g5:#333;--r:14px}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Arial,sans-serif;background:var(--bg);min-height:100vh;color:var(--g5);padding-bottom:40px;-webkit-font-smoothing:antialiased}
.hdr{background:var(--red);position:sticky;top:0;z-index:100;box-shadow:0 3px 16px rgba(0,0,0,.25)}
.hdr-in{display:flex;align-items:center;gap:11px;padding:11px 16px;max-width:520px;margin:0 auto}
.logo{width:44px;height:44px;border-radius:50%;background:var(--ylw);display:flex;align-items:center;justify-content:center;flex-shrink:0}
.bname{font-size:20px;font-weight:900;color:#fff;letter-spacing:1px;line-height:1}
.bsub{font-size:9px;color:rgba(255,255,255,.72);margin-top:2px}
.hclk{margin-left:auto;text-align:right}
.htime{font-size:17px;font-weight:700;color:#fff;font-variant-numeric:tabular-nums}
.hdate{font-size:9px;color:rgba(255,255,255,.65);margin-top:1px}
/* Open in new tab banner */
.open-banner{background:#1a73e8;color:#fff;padding:12px 16px;text-align:center;font-size:13px;font-weight:600;display:none;cursor:pointer;line-height:1.5}
.open-banner.show{display:block}
.open-banner:active{opacity:.85}
.wrap{max-width:520px;margin:0 auto;padding:14px 13px}
.net{display:none;align-items:center;gap:8px;padding:10px 14px;border-radius:10px;margin-bottom:12px;font-size:12px;font-weight:600}
.net.show{display:flex}
.net.ok{background:var(--glt);border:1px solid #86EFAC;color:#166534}
.net.err{background:#FEF3C7;border:1px solid #FDE68A;color:#92400E}
.net.saving{background:var(--blt);border:1px solid #93C5FD;color:#1D4ED8}
.ndot{width:8px;height:8px;border-radius:50%;flex-shrink:0}
.net.ok .ndot{background:var(--grn)}.net.err .ndot{background:#F59E0B;animation:blink 1s infinite}.net.saving .ndot{background:var(--blu);animation:blink .5s infinite}
@keyframes blink{50%{opacity:.2}}
.sc{background:var(--wh);border-radius:var(--r);box-shadow:0 2px 14px rgba(0,0,0,.09);padding:13px 16px;margin-bottom:12px;display:flex;align-items:center;gap:12px;border-left:5px solid var(--g3)}
.sc.present{border-left-color:var(--grn)}.sc.absent{border-left-color:var(--red)}.sc.done{border-left-color:var(--blu)}
.sdot{width:12px;height:12px;border-radius:50%;flex-shrink:0;background:var(--g3)}
.sdot.present{background:var(--grn);box-shadow:0 0 0 4px rgba(22,163,74,.18)}.sdot.absent{background:var(--red)}.sdot.done{background:var(--blu)}
.slbl{font-size:13px;font-weight:700}.ssub{font-size:11px;color:var(--g4);margin-top:1px}
.sbadge{margin-left:auto;padding:4px 11px;border-radius:20px;font-size:10px;font-weight:800;letter-spacing:.5px;flex-shrink:0}
.b-absent{background:var(--rlt);color:var(--red)}.b-present{background:var(--glt);color:var(--grn)}.b-done{background:var(--blt);color:var(--blu)}.b-late{background:#FEF9C3;color:#92400E}
.tabs{display:flex;background:var(--wh);border-radius:var(--r);overflow:hidden;box-shadow:0 2px 14px rgba(0,0,0,.09);margin-bottom:13px}
.tab{flex:1;padding:12px 4px;border:none;background:none;font-size:12px;font-weight:700;cursor:pointer;color:var(--g4);border-bottom:3px solid transparent;transition:all .2s;font-family:inherit;-webkit-appearance:none}
.tab.on{color:var(--red);border-bottom-color:var(--red);background:var(--rlt)}
.pane{display:none}.pane.on{display:block}
.card{background:var(--wh);border-radius:var(--r);box-shadow:0 2px 14px rgba(0,0,0,.09);padding:18px;margin-bottom:13px}
.cttl{font-size:18px;font-weight:700;margin-bottom:3px}
.csub{font-size:11px;color:var(--g4);margin-bottom:17px}
.fld{margin-bottom:14px}
.lbl{font-size:10px;font-weight:800;color:var(--g4);display:flex;align-items:center;gap:5px;margin-bottom:5px;letter-spacing:.5px;text-transform:uppercase}
.req{color:var(--red)}
.inp{width:100%;padding:12px 13px;border:1.5px solid var(--g2);border-radius:10px;font-size:16px;color:var(--g5);background:var(--g1);outline:none;-webkit-appearance:none;appearance:none;transition:border .2s;font-family:inherit}
.inp:focus{border-color:var(--red);background:var(--wh)}
select.inp{background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='8'%3E%3Cpath d='M0 0l6 7 6-7' stroke='%23888' stroke-width='1.5' fill='none' stroke-linecap='round'/%3E%3C/svg%3E");background-repeat:no-repeat;background-position:right 13px center;padding-right:34px}
.r2{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.grow{display:flex;gap:8px}.grow .inp{flex:1}
.gbtn{padding:12px 13px;border:1.5px solid var(--red);border-radius:10px;background:var(--rlt);color:var(--red);font-size:13px;font-weight:700;cursor:pointer;white-space:nowrap;flex-shrink:0;-webkit-appearance:none;font-family:inherit;min-height:48px}
.gbtn:active{background:var(--red);color:#fff}
.gbox{margin-top:6px;padding:8px 11px;background:var(--g1);border-radius:8px;font-size:12px;color:var(--g4);display:none;align-items:center;gap:6px}
.gbox.show{display:flex}.gdot{width:7px;height:7px;border-radius:50%;background:var(--grn);flex-shrink:0}
.szn{border:2px dashed var(--g2);border-radius:11px;padding:20px 16px;text-align:center;cursor:pointer;background:var(--g1)}
.szn:active{border-color:var(--red);background:var(--rlt)}
.szico{font-size:30px;margin-bottom:6px}.sztxt{font-size:12px;color:var(--g4);font-weight:600}
.szprev{width:76px;height:76px;border-radius:50%;object-fit:cover;border:3px solid var(--red);display:none;margin:0 auto 6px}
.sbtn{width:100%;padding:15px;border:none;border-radius:11px;font-size:18px;font-weight:900;letter-spacing:1px;cursor:pointer;margin-top:4px;-webkit-appearance:none;display:flex;align-items:center;justify-content:center;gap:8px;min-height:52px;font-family:inherit}
.sbtn.red{background:var(--red);color:#fff}.sbtn.blu{background:var(--blu);color:#fff}
.sbtn:active{transform:scale(.98);opacity:.88}.sbtn:disabled{opacity:.5;cursor:not-allowed;transform:none}
.spin{width:16px;height:16px;border:2.5px solid rgba(255,255,255,.35);border-top-color:#fff;border-radius:50%;animation:sp .7s linear infinite;flex-shrink:0}
@keyframes sp{to{transform:rotate(360deg)}}
.alert{padding:13px 15px;border-radius:11px;margin-bottom:13px;display:none;align-items:flex-start;gap:10px}
.alert.ok{background:var(--glt);border:1.5px solid #86EFAC}.alert.er{background:var(--rlt);border:1.5px solid #FCA5A5}
.alert.on{display:flex}.aico{font-size:16px;flex-shrink:0;margin-top:1px}
.attl{font-size:13px;font-weight:700}.amsg{font-size:11px;margin-top:2px;color:var(--g4)}
.alert.ok .attl{color:var(--grn)}.alert.er .attl{color:var(--red)}
.hbar{background:var(--g1);border-radius:10px;padding:12px 14px;margin-top:12px;display:none}
.btr{height:8px;background:var(--g2);border-radius:4px;overflow:hidden;margin:6px 0 5px}
.bfl{height:100%;background:linear-gradient(90deg,var(--red),var(--ylw));border-radius:4px;transition:width .7s}
.hval{font-size:12px;font-weight:700;color:var(--red)}
.hrow{display:flex;justify-content:space-between;align-items:center;padding:10px 0;border-bottom:.5px solid var(--g2)}
.hrow:last-child{border:none}.hd{font-size:13px;font-weight:600}.ht{font-size:11px;color:var(--g4);margin-top:1px}
.hs{font-size:10px;font-weight:800;letter-spacing:.4px}.hs.p{color:var(--grn)}.hs.a{color:var(--red)}.hs.d{color:var(--blu)}
.skel{background:linear-gradient(90deg,var(--g2) 25%,var(--g1) 50%,var(--g2) 75%);background-size:200%;animation:sk 1.4s infinite;border-radius:8px;height:44px;margin-bottom:8px}
@keyframes sk{0%{background-position:200% 0}100%{background-position:-200% 0}}
.szn.missing{border-color:var(--red);background:var(--rlt);animation:shake .4s ease}
@keyframes shake{0%,100%{transform:translateX(0)}25%{transform:translateX(-6px)}75%{transform:translateX(6px)}}
.ci-success{background:linear-gradient(135deg,#16a34a,#15803d);border-radius:var(--r);padding:22px 18px;text-align:center;margin-bottom:12px;animation:fadeUp .4s ease}
@keyframes fadeUp{from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:translateY(0)}}
.ci-success .tick{font-size:44px;margin-bottom:8px}
.ci-success .ci-s-name{font-size:18px;font-weight:900;color:#fff}
.ci-success .ci-s-sub{font-size:12px;color:rgba(255,255,255,.8);margin-top:4px}
.ci-success .ci-s-new{margin-top:14px;padding:10px 16px;background:rgba(255,255,255,.2);border:1.5px solid rgba(255,255,255,.35);border-radius:8px;color:#fff;font-size:13px;font-weight:800;cursor:pointer;letter-spacing:.5px;font-family:inherit;width:100%}
.ci-success .ci-s-new:active{background:rgba(255,255,255,.35)}
</style>
</head>
<body>

<!-- OPEN IN NEW TAB BANNER — shown when inside Google Sites iframe -->
<div class="open-banner" id="open-banner" onclick="openFullScreen()">
  &#128205; Tap here to open the full attendance app (required for GPS to work)
</div>

<div class="hdr">
  <div class="hdr-in">
    <div class="logo">
      <img src="data:image/jpeg;base64,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" width="30" height="30" style="border-radius:50%;object-fit:cover" alt="Techpack">
    </div>
    <div><div class="bname">TECHPACK</div><div class="bsub">ATTENDANCE PORTAL</div></div>
    <div class="hclk"><div class="htime" id="ct">--:--:--</div><div class="hdate" id="cd">---</div></div>
  </div>
</div>

<div class="wrap">
  <div class="net" id="net"><div class="ndot"></div><span id="net-txt">Connecting...</span></div>
  <div class="tabs">
    <button class="tab on" onclick="sw('ci',this)">&#9728; Check-In</button>
    <button class="tab" onclick="sw('co',this)">&#9790; Check-Out</button>
    <button class="tab" onclick="sw('ht',this)">&#128203; History</button>
  </div>

  <div id="ci" class="pane on">
    <!-- SUCCESS STATE after check-in -->
    <div class="ci-success" id="ci-success" style="display:none">
      <div class="tick">✅</div>
      <div class="ci-s-name" id="ci-s-name">Checked In!</div>
      <div class="ci-s-sub" id="ci-s-sub">Your attendance has been saved.</div>
      <button class="ci-s-new" id="ci-s-new" onclick="resetCISuccess()">+ Check In Another Employee</button>
    </div>
    <div id="ci-form">
    <div class="alert ok" id="ci-ok"><span class="aico">&#10003;</span><div><div class="attl">Check-in saved!</div><div class="amsg" id="ci-ok-m"></div></div></div>
    <div class="alert er" id="ci-er"><span class="aico">&#10007;</span><div><div class="attl">Error</div><div class="amsg" id="ci-er-m"></div></div></div>
    <div class="card">
      <div class="cttl">Morning Check-In</div>
      <div class="csub">GPS checks if you are at the work site</div>
      <div class="fld r2">
        <div><div class="lbl">Your Name <span class="req">&#9733;</span></div><input type="text" id="ci-emp" class="inp" placeholder="Type your full name" autocomplete="off" autocorrect="off" spellcheck="false"></div>
        <div><div class="lbl">Employee ID <span class="req">&#9733;</span></div><input type="text" id="ci-id" class="inp" placeholder="e.g. TP-045" autocomplete="off" autocorrect="off" spellcheck="false" style="text-transform:uppercase"></div>
      </div>
      <div class="fld">
        <div class="lbl">Time</div><input type="time" id="ci-time" class="inp">
      </div>
      <div class="fld r2">
        <div>
          <div class="lbl">Role <span class="req">&#9733;</span></div>
          <select id="ci-role" class="inp" onchange="onRoleChange()">
            <option value="">Select role...</option>
            <option value="employee">Employee</option>
            <option value="candidate">Candidate / Visitor</option>
          </select>
        </div>
        <div><div class="lbl">Work Site <span class="req">&#9733;</span></div>
          <select id="ci-site" class="inp">
            <option value="">Select your site...</option>
            <option>NORTH 1</option><option>NORTH 2</option><option>NORTH 3</option><option>NORTH 4</option><option>NORTH 5</option><option>NORTH 6</option>
            <option>SOUTH 1</option><option>SOUTH 3</option><option>SOUTH 4</option><option>SOUTH 5</option><option>SOUTH 6</option><option>SOUTH 7</option>
            <option>HYD 1</option><option>CORPORATE</option><option>FACTORY</option>
          </select>
        </div>
      </div>
      <div id="ci-candidate-note" style="display:none;padding:9px 12px;background:#FEF9C3;border:1.5px solid #F5C100;border-radius:10px;font-size:12px;color:#92400E;font-weight:600;margin-bottom:10px">
        ⚠️ Candidate / Visitor — GPS location will be recorded as <strong>Guest</strong>. Attendance marked PRESENT with manager notification.
      </div>
      <div class="fld" id="ci-shift-wrap">
        <div class="lbl">Shift <span class="req">&#9733;</span></div>
        <select id="ci-shift" class="inp">
          <option value="">Select your shift...</option>
          <option value="General">General</option>
          <option value="A">A</option>
          <option value="B">B</option>
          <option value="C">C</option>
          <option value="Day">Day</option>
          <option value="Night">Night</option>
        </select>
      </div>
      <div class="fld">
        <div class="lbl">Today's Task</div>
        <textarea id="ci-task" class="inp" rows="2" style="font-size:16px" placeholder="What will you be working on today?"></textarea>
      </div>
      <div class="fld">
        <div class="lbl">GPS Location <span class="req">&#9733;</span></div>
        <div class="grow">
          <input type="text" id="ci-gps" class="inp" placeholder="Tap Capture button" readonly>
          <button class="gbtn" onclick="capGPS('ci')">&#128205; Capture</button>
        </div>
        <div class="gbox" id="ci-gi"><div class="gdot" id="ci-gdot"></div><span id="ci-gt"></span></div>
      </div>
      <div class="fld">
        <div class="lbl">Selfie Photo <span class="req">&#9733;</span> <span style="font-size:9px;color:var(--red);font-weight:700;text-transform:uppercase;letter-spacing:.3px">Required</span></div>
        <div class="szn" id="ci-szn" onclick="document.getElementById('ci-fi').click()">
          <img id="ci-pi" class="szprev">
          <div id="ci-ph"><div class="szico">&#128247;</div><div class="sztxt">Tap to take selfie (mandatory)</div></div>
        </div>
        <input type="file" id="ci-fi" accept="image/*" capture="user" style="display:none" onchange="loadImg(this,'ci-pi','ci-ph')">
      </div>
      <button class="sbtn red" id="ci-btn" onclick="doCI()">SUBMIT CHECK-IN</button>
    </div>
    </div>
  </div>

  <div id="co" class="pane">
    <!-- SUCCESS STATE after check-out -->
    <div class="ci-success" id="co-success" style="display:none;background:linear-gradient(135deg,#2563EB,#1d4ed8)">
      <div class="tick">🌙</div>
      <div class="ci-s-name" id="co-s-name">Checked Out!</div>
      <div class="ci-s-sub" id="co-s-sub">Day complete. See you tomorrow!</div>
      <button class="ci-s-new" id="co-s-new" onclick="resetCOSuccess()">+ Check Out Another Employee</button>
    </div>
    <div id="co-form">
    <div class="alert ok" id="co-ok"><span class="aico">&#10003;</span><div><div class="attl">Check-out saved!</div><div class="amsg" id="co-ok-m"></div></div></div>
    <div class="alert er" id="co-er"><span class="aico">&#10007;</span><div><div class="attl">Error</div><div class="amsg" id="co-er-m"></div></div></div>
    <div class="card">
      <div class="cttl">Evening Check-Out</div>
      <div class="csub">Submit tasks and close your day</div>
      <div class="fld r2">
        <div><div class="lbl">Your Name <span class="req">&#9733;</span></div><input type="text" id="co-emp" class="inp" placeholder="Type your full name" autocomplete="off" autocorrect="off" spellcheck="false"></div>
        <div><div class="lbl">Employee ID <span class="req">&#9733;</span></div><input type="text" id="co-id" class="inp" placeholder="e.g. TP-045" autocomplete="off" autocorrect="off" spellcheck="false" style="text-transform:uppercase" onblur="loadTodayTask()"></div>
      </div>
      <div class="fld"><div class="lbl">Time</div><input type="time" id="co-time" class="inp"></div>
      <div class="fld">
        <div class="lbl">GPS Location</div>
        <div class="grow">
          <input type="text" id="co-gps" class="inp" placeholder="Tap Capture" readonly>
          <button class="gbtn" onclick="capGPS('co')">&#128205; Capture</button>
        </div>
        <div class="gbox" id="co-gi"><div class="gdot"></div><span id="co-gt"></span></div>
      </div>
      <div class="fld">
        <div class="lbl">Today's Task <span style="font-weight:600;color:var(--g4);text-transform:none;letter-spacing:0">(pulled from your check-in)</span></div>
        <div class="grow"><textarea id="co-ta" class="inp" rows="2" style="font-size:16px" placeholder="Enter your Employee ID above to auto-load, or type it here"></textarea><button class="gbtn" onclick="loadTodayTask()">&#128260; Load</button></div>
        <div class="gbox" id="co-task-note"><div class="gdot"></div><span id="co-task-note-t"></span></div>
      </div>
      <div class="fld"><div class="lbl">Task Completed / Status</div><textarea id="co-tc" class="inp" rows="2" style="font-size:16px" placeholder="What you completed today..."></textarea></div>
      <div class="fld"><div class="lbl">Notes</div><textarea id="co-nt" class="inp" rows="2" style="font-size:16px" placeholder="Any updates..."></textarea></div>
      <div class="fld" id="co-reason-wrap" style="display:none">
        <div class="lbl">Reason Required <span class="req">&#9733;</span></div>
        <div id="co-reason-note" style="padding:8px 10px;background:#FEF9C3;border:1.5px solid #F5C100;border-radius:9px;font-size:11px;color:#92400E;font-weight:600;margin-bottom:8px">
          ⚠️ Please explain why so your manager can see it.
        </div>
        <textarea id="co-reason" class="inp" rows="2" style="font-size:16px" placeholder="e.g. Left early for a site visit, dropped material at another location..."></textarea>
      </div>
      <div class="fld">
        <div class="lbl">Selfie Photo <span class="req">&#9733;</span> <span style="font-size:9px;color:var(--red);font-weight:700;text-transform:uppercase;letter-spacing:.3px">Required</span></div>
        <div class="szn" id="co-szn" onclick="document.getElementById('co-fi').click()">
          <img id="co-pi" class="szprev">
          <div id="co-ph"><div class="szico">&#128247;</div><div class="sztxt">Tap to take selfie (mandatory)</div></div>
        </div>
        <input type="file" id="co-fi" accept="image/*" capture="user" style="display:none" onchange="loadImg(this,'co-pi','co-ph')">
      </div>
      <div class="hbar" id="hbar">
        <div style="font-size:11px;color:var(--g4)">Work hours today</div>
        <div class="btr"><div class="bfl" id="bfl" style="width:0%"></div></div>
        <div class="hval" id="hval">--</div>
      </div>
      <button class="sbtn blu" id="co-btn" onclick="doCO()">SUBMIT CHECK-OUT</button>
    </div>
    </div>
  </div>

  <div id="ht" class="pane">
    <div class="card">
      <div class="cttl">My Attendance History</div>
      <div class="csub">Your records from Google Sheet</div>
      <div class="fld r2"><div><div class="lbl">Your Name</div><input type="text" id="ht-emp" class="inp" placeholder="Type your full name" autocomplete="off" autocorrect="off" spellcheck="false"></div><div><div class="lbl">Employee ID</div><input type="text" id="ht-id" class="inp" placeholder="e.g. TP-045" autocomplete="off" autocorrect="off" spellcheck="false" style="text-transform:uppercase"></div></div>
      <button class="gbtn" style="width:100%;margin-bottom:12px" onclick="loadHist()">&#128269; Load History</button>
      <div id="ht-list"><div class="empty">Select your name to load history</div></div>
    </div>
  </div>
</div>

<script>
const SCRIPT_URL = "https://script.google.com/macros/s/AKfycbzkBmTnVB9iVC9BUZ3VkVqMZs3U9Omwtm1wiEVdsGR3aKa1Hhrh2xysZEFCfA2khyeBMg/exec";

// ── ONE CHECK-IN / ONE CHECK-OUT PER DEVICE PER DAY ──────────
// Device is identified by a persistent random ID stored in localStorage.
// Only ONE person can check-in and ONE person can check-out per device each day.
function getDeviceId(){
  let id = localStorage.getItem("tp_device_id");
  if(!id){ id = "dev_" + Math.random().toString(36).slice(2) + Date.now().toString(36); localStorage.setItem("tp_device_id", id); }
  return id;
}
function todayKey(){ const n=new Date(); return n.getFullYear()+"-"+String(n.getMonth()+1).padStart(2,"0")+"-"+String(n.getDate()).padStart(2,"0"); }
function alreadyCI(){ return !!localStorage.getItem("tp_ci_" + getDeviceId() + "_" + todayKey()); }
function alreadyCO(){ return !!localStorage.getItem("tp_co_" + getDeviceId() + "_" + todayKey()); }
// Stored as "id||name" so we keep the ID as the real match key while still
// showing a friendly name in the UI.
function markCI(id,emp){ localStorage.setItem("tp_ci_" + getDeviceId() + "_" + todayKey(), id+"||"+emp); }
function markCO(id,emp){ localStorage.setItem("tp_co_" + getDeviceId() + "_" + todayKey(), id+"||"+emp); }
function _parseWho(raw){
  if(!raw)return null;
  const i=raw.indexOf("||");
  return i===-1 ? {id:"",name:raw} : {id:raw.slice(0,i),name:raw.slice(i+2)};
}
function whoCheckedIn(){ const w=_parseWho(localStorage.getItem("tp_ci_" + getDeviceId() + "_" + todayKey())); return w?w.name:""; }
function whoCheckedOut(){ const w=_parseWho(localStorage.getItem("tp_co_" + getDeviceId() + "_" + todayKey())); return w?w.name:""; }

// GUEST/CANDIDATE TRACKING (per-person, not per-device)
// Regular employees still get the "one per device per day" lock above
// (anti buddy-punching). Guests/candidates commonly share ONE kiosk
// device (e.g. reception tablet), so they are tracked individually by
// name instead of locking the whole device after the first guest.
function guestSetKey(type){ return "tp_guests_" + type + "_" + getDeviceId() + "_" + todayKey(); }
function getGuestSet(type){
  try{ return JSON.parse(localStorage.getItem(guestSetKey(type)) || "[]"); }catch(e){ return []; }
}
function addGuestDone(type, name){
  const arr = getGuestSet(type);
  if(!arr.includes(name)){ arr.push(name); localStorage.setItem(guestSetKey(type), JSON.stringify(arr)); }
}
function isGuestDone(type, name){ return getGuestSet(type).includes(name); }
function isKnownGuestToday(name){ return getGuestSet("ci").includes(name); }

// ── WORK ZONES (client-side hint only — NOT the final decision) ────
// The final present/guest decision is now made server-side by the
// Site_Zones auto-calibration system in Code.gs: for each site, the
// first CALIBRATION_DAYS days of real check-ins are averaged into a
// locked GPS point automatically — no manual coordinates needed.
// This local WORK_ZONES list only drives the instant on-screen text
// ("✓ At work site" / "⚠ Guest location") right after GPS capture,
// before the checkin is even submitted — it's just a live preview,
// so it's fine if it's approximate or still placeholder values.
const WORK_ZONES = [
  { name:"Factory",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"T-Works",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"Corporate",   lat:17.478559, lng:78.429926, radius:10 },
  { name:"HYD 1",       lat:17.478559, lng:78.429926, radius:10 },
  { name:"NORTH 1",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"NORTH 2",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"NORTH 3",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"NORTH 4",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"NORTH 5",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"NORTH 6",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"SOUTH 1",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"SOUTH 3",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"SOUTH 4",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"SOUTH 5",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"SOUTH 6",     lat:17.478559, lng:78.429926, radius:10 },
  { name:"SOUTH 7",     lat:17.478559, lng:78.429926, radius:10 },
];
const MAX_DIST = 500; // meters — how far from a zone still counts as "at work"

// ── IFRAME DETECTION — Google Sites fix ────────────────────
// Google Sites embeds the app in an iframe which blocks GPS
// Solution: detect iframe → show banner → open app in new tab
(function(){
  const inIframe = (function(){
    try{ return window.self !== window.top; }
    catch(e){ return true; }
  })();

  if(inIframe){
    // Show the blue banner at top asking user to open full screen
    document.getElementById("open-banner").classList.add("show");
    // Store current URL for the open button
    window._pageURL = window.location.href;
  }
})();

function openFullScreen(){
  // Open this same page in a new tab — outside the iframe
  // GPS works in new tab
  const url = window._pageURL || window.location.href;
  window.open(url, "_blank");
}

const pad = v => String(v).padStart(2,"0");
const DAYS = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"];
const MONS = ["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"];



function tick(){
  const n=new Date();
  document.getElementById("ct").textContent=`${pad(n.getHours())}:${pad(n.getMinutes())}:${pad(n.getSeconds())}`;
  document.getElementById("cd").textContent=`${DAYS[n.getDay()]}, ${n.getDate()} ${MONS[n.getMonth()]} ${n.getFullYear()}`;
  const t=`${pad(n.getHours())}:${pad(n.getMinutes())}`;
  document.getElementById("ci-time").value=t;
  document.getElementById("co-time").value=t;
}
setInterval(tick,1000);tick();

function populateDropdowns(){
  showNet("ok","Connected to Google Sheet ✓",true);
}

function showNet(type,msg,hide=false){
  const el=document.getElementById("net"),tx=document.getElementById("net-txt");
  el.className="net "+type+" show";tx.textContent=msg;
  if(hide)setTimeout(()=>el.classList.remove("show"),3000);
}

function sw(id,btn){
  document.querySelectorAll(".tab").forEach(b=>b.classList.remove("on"));
  document.querySelectorAll(".pane").forEach(p=>p.classList.remove("on"));
  btn.classList.add("on");document.getElementById(id).classList.add("on");
}

function calcDist(lat1,lng1,lat2,lng2){
  const R=6371000,dL=(lat2-lat1)*Math.PI/180,dG=(lng2-lng1)*Math.PI/180;
  const a=Math.sin(dL/2)**2+Math.cos(lat1*Math.PI/180)*Math.cos(lat2*Math.PI/180)*Math.sin(dG/2)**2;
  return R*2*Math.atan2(Math.sqrt(a),Math.sqrt(1-a));
}

function checkZone(lat,lng){
  let closest=null,minDist=Infinity;
  for(const z of WORK_ZONES){
    const d=Math.round(calcDist(lat,lng,z.lat,z.lng));
    if(d<minDist){minDist=d;closest=z;}
  }
  return{inside:minDist<=MAX_DIST,zone:closest,distance:minDist};
}

function capGPS(p){
  const inp=document.getElementById(p+"-gps");
  const box=document.getElementById(p+"-gi");
  const txt=document.getElementById(p+"-gt");
  const dot=document.getElementById(p+"-gdot")||box.querySelector(".gdot");

  if(!navigator.geolocation){
    txt.textContent="GPS not available. Please use Chrome browser.";
    box.classList.add("show");
    return;
  }

  inp.value="Getting your location...";
  box.classList.remove("show");

  const tryGPS=(highAcc)=>{
    navigator.geolocation.getCurrentPosition(
      pos=>{
        const lat=pos.coords.latitude, lng=pos.coords.longitude;
        const acc=Math.round(pos.coords.accuracy);
        inp.value=`${lat.toFixed(6)}, ${lng.toFixed(6)}`;
        box.classList.add("show");
        if(p==="ci"){
          window._lat=lat;window._lng=lng;
          const r=checkZone(lat,lng);
          window._inZone=r.inside;window._zoneName=r.zone?r.zone.name:"";window._distance=r.distance;
          window._guestLoc = !r.inside;
          if(r.inside){
            txt.textContent=`✓ At work site — ${r.zone.name} (${r.distance}m) — PRESENT`;
            if(dot)dot.style.background="#16a34a";
          }else{
            txt.textContent=`⚠ Guest location — ${r.distance}m from ${r.zone?r.zone.name:""} — PRESENT with warning`;
            if(dot)dot.style.background="#F5C100";
          }
        }else if(p==="co"){
          // Checkout location is captured too — the server decides if this
          // counts as a "guest" checkout (only matters if the check-in was
          // from the normal work site; guest checkouts are always allowed).
          window._colat=lat;window._colng=lng;
          txt.textContent=`GPS confirmed: ${lat.toFixed(6)}, ${lng.toFixed(6)} (±${acc}m)`;
        }else{
          txt.textContent=`GPS confirmed: ${lat.toFixed(6)}, ${lng.toFixed(6)} (±${acc}m)`;
        }
      },
      err=>{
        if(highAcc&&err.code===3){tryGPS(false);return;}
        inp.value="";
        const msgs={1:"Location BLOCKED — tap lock icon in address bar → Allow",2:"Location unavailable — go outside and try again",3:"Timed out — try again"};
        txt.textContent=msgs[err.code]||"Location error";
        box.classList.add("show");
        if(dot)dot.style.background="#F59E0B";
        if(err.code===1){
          const isIOS=/iPhone|iPad|iPod/i.test(navigator.userAgent);
          if(isIOS) alert("iPhone: Settings → Privacy & Security → Location Services → Safari → While Using the App");
          else alert("Android: Tap the lock icon 🔒 in Chrome address bar → Permissions → Location → Allow");
        }
      },
      {enableHighAccuracy:highAcc,timeout:highAcc?15000:10000,maximumAge:highAcc?0:30000}
    );
  };
  tryGPS(true);
}


function loadImg(inp,imgId,phId){
  const f=inp.files[0];if(!f)return;
  const reader=new FileReader();
  reader.onload=e=>{
    const img=new Image();
    img.onload=()=>{
      const c=document.createElement("canvas"),MAX=500;
      let w=img.width,h=img.height;if(w>MAX){h=Math.round(h*MAX/w);w=MAX;}
      c.width=w;c.height=h;c.getContext("2d").drawImage(img,0,0,w,h);
      document.getElementById(imgId).src=c.toDataURL("image/jpeg",.65);
      document.getElementById(imgId).style.display="block";
      document.getElementById(phId).style.display="none";
    };img.src=e.target.result;
  };reader.readAsDataURL(f);
}

async function apiPost(data,timeoutMs=30000){
  const ctrl=new AbortController();
  const t=setTimeout(()=>ctrl.abort(),timeoutMs);
  try{
    const r=await fetch(SCRIPT_URL,{method:"POST",headers:{"Content-Type":"text/plain;charset=utf-8"},body:JSON.stringify(data),redirect:"follow",signal:ctrl.signal});
    if(!r.ok)throw new Error("Network error "+r.status);
    const text=await r.text();
    try{return JSON.parse(text);}catch(e){return{success:true,message:"Saved"};}
  }finally{clearTimeout(t);}
}
async function apiGet(params,timeoutMs=15000){
  const ctrl=new AbortController();
  const t=setTimeout(()=>ctrl.abort(),timeoutMs);
  try{
    const r=await fetch(SCRIPT_URL+"?"+new URLSearchParams(params).toString(),{redirect:"follow",signal:ctrl.signal});
    if(!r.ok)throw new Error("Network error "+r.status);
    const text=await r.text();
    try{return JSON.parse(text);}catch(e){return[];}
  }finally{clearTimeout(t);}
}

// ── RECOVERY: the Apps Script redirect hop can fail on the client even
// after the row has already been written to the sheet. Rather than trust
// a network error at face value, re-check the sheet before telling the
// user their check-in/out was lost. ──
function isSameLogDate(logDate){
  if(!logDate)return false;
  const d=new Date(logDate);
  if(isNaN(d))return String(logDate).slice(0,10)===todayKey();
  const n=new Date();
  return d.getFullYear()===n.getFullYear()&&d.getMonth()===n.getMonth()&&d.getDate()===n.getDate();
}
async function verifySaved(emp,kind,empId){
  try{
    const rows=await apiGet({action:"getHistory",emp,emp_id:empId||""});
    if(!Array.isArray(rows))return null;
    const todays=rows.filter(r=>isSameLogDate(r.log_date)&&(kind==="checkin"?r.checkin_time:r.checkout_time));
    if(!todays.length)return null;
    // Prefer a row matching Employee ID when we have one to match against.
    const idMatch=empId?todays.find(r=>String(r.emp_id||"").toUpperCase()===empId):null;
    return idMatch||todays[0];
  }catch(e){return null;}
}

function setBtn(id,loading,label){
  const b=document.getElementById(id);b.disabled=loading;
  b.innerHTML=loading?`<div class="spin"></div> Saving...`:label;
}
function showAlert(id,msg){
  const el=document.getElementById(id);
  document.getElementById(id+"-m").textContent=msg;
  el.classList.add("on");setTimeout(()=>el.classList.remove("on"),7000);
}

function showCISuccess(emp, site, time, isLate, isGuest){
  document.getElementById("ci-s-name").textContent = `✅ ${emp} — Checked In${isLate?" (Late)":""}${isGuest?" ⚠ Guest":""}`;
  document.getElementById("ci-s-sub").textContent = `${site} · ${time} · Saved to sheet`;
  document.getElementById("ci-success").style.display="block";
  document.getElementById("ci-form").style.display="none";
}

function resetCISuccess(){
  document.getElementById("ci-success").style.display="none";
  document.getElementById("ci-form").style.display="block";
  document.getElementById("ci-s-new").style.display="";
  clearCIForm();
}

function clearCIForm(){
  document.getElementById("ci-emp").value="";
  document.getElementById("ci-id").value="";
  document.getElementById("ci-role").value="";
  document.getElementById("ci-site").value="";
  document.getElementById("ci-shift").value="";
  document.getElementById("ci-shift-wrap").style.display="block";
  document.getElementById("ci-task").value="";
  document.getElementById("ci-gps").value="";
  // Reset GPS info box
  const gi=document.getElementById("ci-gi");
  gi.classList.remove("show");
  const gt=document.getElementById("ci-gt");
  if(gt) gt.textContent="";
  const gdot=document.getElementById("ci-gdot");
  if(gdot) gdot.style.background="";
  // Reset photo
  document.getElementById("ci-pi").style.display="none";
  document.getElementById("ci-ph").style.display="block";
  document.getElementById("ci-pi").src="";
  document.getElementById("ci-fi").value="";
  // Reset candidate note
  document.getElementById("ci-candidate-note").style.display="none";
  // Reset global GPS state
  window._lat=null;window._lng=null;window._inZone=false;window._zoneName="";window._distance=0;window._guestLoc=false;
}

async function doCI(){
  const emp=document.getElementById("ci-emp").value.trim();
  const id=document.getElementById("ci-id").value.trim().toUpperCase();
  const time=document.getElementById("ci-time").value;
  const site=document.getElementById("ci-site").value;
  const task=document.getElementById("ci-task").value.trim();
  const gps=document.getElementById("ci-gps").value;
  const photoSrc=document.getElementById("ci-pi").src;
  const hasPhoto=document.getElementById("ci-pi").style.display==="block"&&photoSrc&&photoSrc.startsWith("data:");
  if(!emp)return alert("Please enter your name");
  if(!id)return alert("Please enter your Employee ID (ask your manager if you don't have one yet)");
  if(!site)return alert("Please select your work site");
  const role=document.getElementById("ci-role").value;
  if(!role)return alert("Please select your role (Employee or Candidate)");
  const isCandidatePreCheck = role === "candidate";
  const shift=document.getElementById("ci-shift").value;
  if(!isCandidatePreCheck && !shift)return alert("Please select your shift");
  if(!gps||gps.includes("Getting"))return alert("Please tap the GPS Capture button first");
  if(!hasPhoto){
    const szn=document.getElementById("ci-szn");
    szn.classList.add("missing");
    setTimeout(()=>szn.classList.remove("missing"),1000);
    return alert("📸 Selfie photo is mandatory.\nPlease tap the photo area to take a selfie.");
  }
  // CANDIDATES always get guest location (allowed outside zone)
  const isCandidate = role === "candidate";
  // ONE CHECK-IN PER DEVICE PER DAY — applies to regular employees only.
  // Candidates/guests typically share one reception kiosk, so they are
  // tracked per-person instead of locking the whole device. Tracked by
  // Employee ID now (falls back to name for guests who have no ID) since
  // names alone can collide or be mistyped.
  const guestKey = id || emp;
  if(isCandidate){
    if(isGuestDone("ci", guestKey)){
      return alert(emp + " has already checked in today from this device.");
    }
  }else if(alreadyCI()){
    const who = whoCheckedIn();
    return alert("This device has already been used to check in today" + (who ? " by " + who : "") + ".\nOnly one check-in per device per day is allowed.");
  }
  const isGuest = isCandidate || window._guestLoc === true;
  const status = "present"; // always present if GPS captured (inside = normal, outside = guest)
  const isLate = time>"09:30";
  setBtn("ci-btn",true,"SUBMIT CHECK-IN");showNet("saving","Saving...");
  try{
    const res=await apiPost({action:"checkin",emp_name:emp,emp_id:id,role,site,shift,checkin_time:time,gps,
      lat:window._lat||null,lng:window._lng||null,
      in_zone:!isGuest,zone_name:window._zoneName||"",
      distance_meters:window._distance||0,
      guest_location:isGuest,status_override:status,task,
      photo:photoSrc});
    setBtn("ci-btn",false,"SUBMIT CHECK-IN");
    if(res.success||res.message){
      // Server (Site_Zones auto-calibration) has the final say on guest status
      const finalGuest = (res.guest_location !== undefined) ? !!res.guest_location : isGuest;
      if(isCandidate){ addGuestDone("ci", guestKey); } else { markCI(id,emp); }
      try{ localStorage.setItem("tp_live_event", JSON.stringify({type:"checkin",emp,id,site,time,isLate,isGuest:finalGuest,ts:Date.now()})); } catch(e){}
      const label=finalGuest?"PRESENT ⚠ (guest location)":"PRESENT ✓";
      showAlert("ci-ok",`${emp} · ${site} · ${time}${isLate?" · LATE ⚠":""} · ${label}`);
      showNet("ok","Saved to Google Sheet ✓",true);
      // Clear form immediately then show success card
      clearCIForm();
      showCISuccess(emp,site,time,isLate,finalGuest);
    }else{showAlert("ci-er",res.error||"Error saving");showNet("err","Save failed");}
  }catch(err){
    setBtn("ci-btn",true,"Verifying...");
    showNet("saving","Connection dropped — checking if it saved...");
    const saved=await verifySaved(emp,"checkin",id);
    setBtn("ci-btn",false,"SUBMIT CHECK-IN");
    if(saved){
      // It actually made it into the sheet — the earlier network error was
      // just the response coming back, not the save itself.
      markCI(id,emp);
      showAlert("ci-ok",`${emp} · ${site} · ${saved.checkin_time||time} · Confirmed saved ✓`);
      showNet("ok","Saved to Google Sheet ✓",true);
      clearCIForm();
      showCISuccess(emp,site,saved.checkin_time||time,false,false);
    }else{
      showAlert("ci-er","Cannot reach server. Check internet.\n"+err.message);
      showNet("err","Connection failed — not saved. Please retry.");
    }
  }
}

function showCOSuccess(emp, time, hours){
  document.getElementById("co-s-name").textContent = `🌙 ${emp} — Day Complete`;
  document.getElementById("co-s-sub").textContent = `Checked out at ${time}${hours>0?" · "+hours+"h worked":""}`;
  document.getElementById("co-success").style.display="block";
  document.getElementById("co-form").style.display="none";
}

function resetCOSuccess(){
  document.getElementById("co-success").style.display="none";
  document.getElementById("co-form").style.display="block";
  document.getElementById("co-s-new").style.display="";
  clearCOForm();
}

function clearCOForm(){
  document.getElementById("co-emp").value="";
  document.getElementById("co-id").value="";
  document.getElementById("co-gps").value="";
  const cogi=document.getElementById("co-gi");
  if(cogi) cogi.classList.remove("show");
  const cogt=document.getElementById("co-gt");
  if(cogt) cogt.textContent="";
  document.getElementById("co-ta").value="";
  document.getElementById("co-tc").value="";
  document.getElementById("co-nt").value="";
  const ctn=document.getElementById("co-task-note");
  if(ctn) ctn.classList.remove("show");
  document.getElementById("co-pi").style.display="none";
  document.getElementById("co-ph").style.display="block";
  document.getElementById("co-pi").src="";
  document.getElementById("co-fi").value="";
  document.getElementById("hbar").style.display="none";
  document.getElementById("co-reason-wrap").style.display="none";
  document.getElementById("co-reason").value="";
  window._colat=null;window._colng=null;
}

// Pulls today's task (entered at check-in) into the Check-Out form, matched
// by Employee ID first (falls back to Name if no ID typed yet).
async function loadTodayTask(){
  const emp=document.getElementById("co-emp").value.trim();
  const id=document.getElementById("co-id").value.trim().toUpperCase();
  if(!id&&!emp)return;
  const note=document.getElementById("co-task-note"), noteT=document.getElementById("co-task-note-t");
  note.className="gbox show";noteT.textContent="Looking up today's task...";
  try{
    const rows=await apiGet({action:"getHistory",emp,emp_id:id});
    const today=todayKey();
    const row=Array.isArray(rows)?rows.find(r=>(String(r.log_date||"").slice(0,10)===today||isSameLogDate(r.log_date))&&r.checkin_time):null;
    if(row&&(row.task||row.tasks_assigned)){
      document.getElementById("co-ta").value=row.task||row.tasks_assigned;
      noteT.textContent="Loaded from your check-in ✓";
    }else if(row){
      noteT.textContent="Found your check-in, but no task was entered this morning — type it in manually.";
    }else{
      noteT.textContent="No check-in found yet for today under that ID — you can type the task manually.";
    }
  }catch(e){
    noteT.textContent="Couldn't look this up right now — type the task manually.";
  }
}

async function doCO(){
  const emp=document.getElementById("co-emp").value.trim();
  const id=document.getElementById("co-id").value.trim().toUpperCase();
  const time=document.getElementById("co-time").value;
  const gps=document.getElementById("co-gps").value;
  const photoSrc=document.getElementById("co-pi").src;
  const hasPhoto=document.getElementById("co-pi").style.display==="block"&&photoSrc&&photoSrc.startsWith("data:");
  if(!emp)return alert("Please enter your name");
  if(!id)return alert("Please enter your Employee ID (ask your manager if you don't have one yet)");
  if(!gps||gps.includes("Getting"))return alert("Please capture GPS first");
  if(!hasPhoto){
    const szn=document.getElementById("co-szn");
    szn.classList.add("missing");
    setTimeout(()=>szn.classList.remove("missing"),1000);
    return alert("📸 Selfie photo is mandatory.\nPlease tap the photo area to take a selfie.");
  }
  // ONE CHECK-OUT PER DEVICE PER DAY — applies to regular employees only.
  // If this person checked in today as a Candidate/Guest, they are
  // tracked per-person (by ID when available) so multiple guests can check
  // out from the same shared kiosk device without blocking each other.
  const guestKey = id || emp;
  const isGuestEmp = isKnownGuestToday(guestKey);
  if(isGuestEmp){
    if(isGuestDone("co", guestKey)){
      return alert(emp + " has already checked out today from this device.");
    }
  }else if(alreadyCO()){
    const who = whoCheckedOut();
    return alert("This device has already been used to check out today" + (who ? " by " + who : "") + ".\nOnly one check-out per device per day is allowed.");
  }
  const reason=document.getElementById("co-reason").value.trim();
  setBtn("co-btn",true,"SUBMIT CHECK-OUT");showNet("saving","Saving...");
  try{
    const res=await apiPost({action:"checkout",emp_name:emp,emp_id:id,checkout_time:time,gps,
      lat:window._colat||null,lng:window._colng||null,reason,
      tasks_assigned:document.getElementById("co-ta").value,tasks_completed:document.getElementById("co-tc").value,notes:document.getElementById("co-nt").value,photo:photoSrc});
    setBtn("co-btn",false,"SUBMIT CHECK-OUT");
    // Server says a reason is required (early logout before standard
    // time, and/or checked in normally but checking out from a guest
    // location) — reveal the reason field with the server's own message
    // and let the person resubmit. Neither case blocks the checkout —
    // it just needs an explanation the manager can see.
    if(res.reason_required){
      document.getElementById("co-reason-wrap").style.display="block";
      document.getElementById("co-reason-note").textContent = "⚠️ " + (res.message || "Please add a reason to continue.");
      document.getElementById("co-reason").focus();
      showAlert("co-er",res.message||"Please add a reason to continue.");
      showNet("err","Reason needed");
      return;
    }
    if(res.success||res.message){
      if(isGuestEmp){ addGuestDone("co", guestKey); } else { markCO(id,emp); }
      try{ localStorage.setItem("tp_live_event", JSON.stringify({type:"checkout",emp,id,time,hours:res.work_hours||0,ts:Date.now()})); } catch(e){}
      showAlert("co-ok",res.message||`${emp} checked out at ${time}`);showNet("ok","Saved ✓",true);
      const wh=res.work_hours||0;
      if(wh>0){document.getElementById("hval").textContent=`${wh} hours worked today`;document.getElementById("bfl").style.width=Math.min(wh/8*100,100)+"%";document.getElementById("hbar").style.display="block";}
      clearCOForm();
      showCOSuccess(emp,time,wh);
    }else{showAlert("co-er",res.error||"Error");showNet("err","Save failed");}
  }catch(err){
    setBtn("co-btn",true,"Verifying...");
    showNet("saving","Connection dropped — checking if it saved...");
    const saved=await verifySaved(emp,"checkout",id);
    setBtn("co-btn",false,"SUBMIT CHECK-OUT");
    if(saved){
      markCO(id,emp);
      showAlert("co-ok",`${emp} checked out at ${saved.checkout_time||time} · Confirmed saved ✓`);
      showNet("ok","Saved ✓",true);
      clearCOForm();
      showCOSuccess(emp,saved.checkout_time||time,saved.work_hours||0);
    }else{
      showAlert("co-er","Cannot reach server. "+err.message);
      showNet("err","Connection failed — not saved. Please retry.");
    }
  }
}

async function loadHist(){
  const emp=document.getElementById("ht-emp").value.trim();
  const id=document.getElementById("ht-id").value.trim().toUpperCase();
  if(!emp&&!id)return;
  const el=document.getElementById("ht-list");
  el.innerHTML=Array(4).fill('<div class="skel"></div>').join("");
  try{
    const rows=await apiGet({action:"getHistory",emp,emp_id:id});
    if(!rows.length){el.innerHTML='<div class="empty">No records found yet</div>';return;}
    el.innerHTML=rows.map(r=>{
      const cls=r.status==="present"?"p":r.status==="absent"?"a":"d";
      const taskLine=r.task?`<div class="ht" style="color:var(--g5)">&#128221; ${r.task}</div>`:"";
      return`<div class="hrow"><div><div class="hd">${r.log_date}</div><div class="ht">In: ${r.checkin_time||"--"} &middot; Out: ${r.checkout_time||"--"}${r.work_hours>0?" &middot; "+r.work_hours+"h":""}</div>${taskLine}</div><div style="text-align:right"><div class="hs ${cls}">${(r.status||"").toUpperCase()}</div>${r.is_late?'<div style="font-size:9px;color:#92400E;font-weight:700">LATE</div>':""}</div></div>`;
    }).join("");
  }catch(err){el.innerHTML=`<div class="empty">Error: ${err.message}</div>`;}
}


function onRoleChange(){
  const role=document.getElementById("ci-role").value;
  document.getElementById("ci-candidate-note").style.display=role==="candidate"?"block":"none";
  // Candidates/visitors don't have a work shift — hide the field for them
  const shiftWrap=document.getElementById("ci-shift-wrap");
  if(role==="candidate"){
    shiftWrap.style.display="none";
    document.getElementById("ci-shift").value="";
  }else{
    shiftWrap.style.display="block";
  }
}

// ── ON PAGE LOAD: show locked state if device already used today ──
function checkDeviceOnLoad(){
  const ciWho = whoCheckedIn();
  const coWho = whoCheckedOut();
  if(ciWho){
    // Device already checked in — show the success card so form is locked
    showCISuccess(ciWho, "", "", false, false);
    document.getElementById("ci-s-name").textContent = "✅ " + ciWho + " — Already Checked In";
    document.getElementById("ci-s-sub").textContent = "This device has already recorded check-in today.";
    document.getElementById("ci-s-new").style.display = "none"; // hide the "another employee" button
  }
  if(coWho){
    showCOSuccess(coWho, "", 0);
    document.getElementById("co-s-name").textContent = "🌙 " + coWho + " — Already Checked Out";
    document.getElementById("co-s-sub").textContent = "This device has already recorded check-out today.";
    document.getElementById("co-s-new").style.display = "none";
  }
}

populateDropdowns();
checkDeviceOnLoad();
</script>
</body>
</html>
