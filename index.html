<!DOCTYPE html>
<html lang="en" data-theme="light">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Tasks – Simple To-Do App</title>
<meta name="description" content="A clean, fast to-do list that saves your tasks in your browser.">
<link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><rect width='100' height='100' rx='24' fill='%230f766e'/><path d='M27 52l17 17 30-36' fill='none' stroke='white' stroke-width='11' stroke-linecap='round' stroke-linejoin='round'/></svg>">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#f3f5f4;--card:#fff;--ink:#14201e;--mute:#6b7a77;--line:#e3e8e6;--acc:#0f766e;--acc2:#115e59;--soft:#e6f4f1;--hi:#dc2626;--md:#d97706;--lo:#2563eb;--shadow:0 1px 2px rgba(16,32,30,.06),0 12px 32px -12px rgba(16,32,30,.18)}
[data-theme=dark]{--bg:#0e1514;--card:#16201e;--ink:#eaf2f0;--mute:#8fa09c;--line:#26332f;--acc:#2dd4bf;--acc2:#5eead4;--soft:#173430;--shadow:0 1px 2px rgba(0,0,0,.4),0 12px 32px -12px rgba(0,0,0,.6)}
*{box-sizing:border-box}
html{-webkit-text-size-adjust:100%}
body{margin:0;min-height:100vh;background:var(--bg);color:var(--ink);font:400 16px/1.5 "Plus Jakarta Sans",system-ui,-apple-system,Segoe UI,Roboto,sans-serif;display:flex;justify-content:center;padding:clamp(16px,5vw,56px) 16px;transition:background .25s,color .25s}
button,input,select{font:inherit;color:inherit}
:focus-visible{outline:3px solid var(--acc);outline-offset:2px;border-radius:8px}
.app{width:100%;max-width:640px}
header{display:flex;align-items:flex-start;justify-content:space-between;gap:16px;margin-bottom:20px}
h1{margin:0;font-size:clamp(1.7rem,5vw,2.2rem);letter-spacing:-.03em;line-height:1.1}
.date{margin:6px 0 0;color:var(--mute);font-size:.95rem}
.icon-btn{width:42px;height:42px;border-radius:12px;border:1px solid var(--line);background:var(--card);cursor:pointer;display:grid;place-items:center;box-shadow:var(--shadow);transition:transform .15s}
.icon-btn:hover{transform:translateY(-1px)}
.icon-btn svg{width:20px;height:20px;stroke:currentColor;fill:none;stroke-width:2;stroke-linecap:round;stroke-linejoin:round}
.card{background:var(--card);border:1px solid var(--line);border-radius:18px;box-shadow:var(--shadow)}
.progress{padding:18px 20px;margin-bottom:16px}
.progress .top{display:flex;justify-content:space-between;align-items:baseline;font-size:.92rem;color:var(--mute);margin-bottom:10px}
.progress .top b{color:var(--ink);font-size:1.05rem}
.bar{height:8px;background:var(--soft);border-radius:99px;overflow:hidden}
.bar i{display:block;height:100%;width:0;background:var(--acc);border-radius:99px;transition:width .4s ease}
form.add{padding:14px;margin-bottom:16px;display:grid;gap:10px}
.add .main{display:flex;gap:10px}
.add input[type=text]{flex:1;min-width:0;border:1.5px solid var(--line);background:var(--bg);border-radius:12px;padding:12px 14px;transition:border-color .2s}
.add input[type=text]:focus{outline:none;border-color:var(--acc)}
.add .opts{display:flex;gap:10px;flex-wrap:wrap}
.add select,.add input[type=date]{border:1.5px solid var(--line);background:var(--bg);border-radius:10px;padding:8px 10px;font-size:.9rem}
.btn{border:0;background:var(--acc);color:#fff;font-weight:600;padding:0 20px;border-radius:12px;cursor:pointer;transition:background .2s,transform .15s}
[data-theme=dark] .btn{color:#06201c}
.btn:hover{background:var(--acc2);transform:translateY(-1px)}
.toolbar{display:flex;gap:10px;align-items:center;flex-wrap:wrap;margin-bottom:14px}
.seg{display:flex;background:var(--card);border:1px solid var(--line);border-radius:12px;padding:4px;gap:2px}
.seg button{border:0;background:none;padding:7px 14px;border-radius:9px;cursor:pointer;font-size:.9rem;font-weight:500;color:var(--mute)}
.seg button[aria-pressed=true]{background:var(--soft);color:var(--acc)}
.search{flex:1;min-width:140px;border:1px solid var(--line);background:var(--card);border-radius:12px;padding:10px 14px;font-size:.92rem}
.search:focus{outline:none;border-color:var(--acc)}
ul{list-style:none;margin:0;padding:0;display:grid;gap:10px}
li{display:flex;align-items:center;gap:12px;padding:14px 16px;background:var(--card);border:1px solid var(--line);border-radius:14px;border-left:4px solid var(--p,var(--line));animation:in .25s ease both}
@keyframes in{from{opacity:0;transform:translateY(6px)}}
li.p-high{--p:var(--hi)}li.p-med{--p:var(--md)}li.p-low{--p:var(--lo)}
.check{appearance:none;flex:none;width:24px;height:24px;border:2px solid var(--mute);border-radius:8px;cursor:pointer;display:grid;place-items:center;transition:background .2s,border-color .2s;margin:0}
.check:checked{background:var(--acc);border-color:var(--acc)}
.check:checked::after{content:"";width:6px;height:11px;border:solid #fff;border-width:0 2.5px 2.5px 0;transform:rotate(45deg) translate(-1px,-1px)}
.body{flex:1;min-width:0}
.title{display:block;overflow-wrap:anywhere;cursor:text}
li.done .title{text-decoration:line-through;color:var(--mute)}
.meta{display:flex;gap:10px;font-size:.8rem;color:var(--mute);margin-top:2px;flex-wrap:wrap}
.meta .late{color:var(--hi);font-weight:600}
.edit{width:100%;border:1.5px solid var(--acc);background:var(--bg);border-radius:8px;padding:6px 10px}
.row-btn{border:0;background:none;color:var(--mute);width:34px;height:34px;border-radius:9px;cursor:pointer;display:grid;place-items:center}
.row-btn:hover{background:var(--soft);color:var(--ink)}
.row-btn.del:hover{color:var(--hi)}
.row-btn svg{width:18px;height:18px;stroke:currentColor;fill:none;stroke-width:2;stroke-linecap:round;stroke-linejoin:round}
.empty{text-align:center;padding:44px 20px;color:var(--mute)}
.empty b{display:block;color:var(--ink);font-size:1.1rem;margin-bottom:4px}
footer{display:flex;justify-content:space-between;align-items:center;margin-top:16px;color:var(--mute);font-size:.9rem}
.link{border:0;background:none;color:var(--mute);cursor:pointer;text-decoration:underline;padding:6px}
.link:hover{color:var(--hi)}
.sr{position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0 0 0 0)}
@media(max-width:480px){.add .main{flex-direction:column}.btn{padding:12px}}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body>
<div class="app">
  <header>
    <div><h1 id="greet">Your tasks</h1><p class="date" id="date"></p></div>
    <button class="icon-btn" id="theme" aria-label="Switch to dark mode" title="Toggle theme">
      <svg id="ico" viewBox="0 0 24 24"><path d="M21 12.8A9 9 0 1 1 11.2 3a7 7 0 0 0 9.8 9.8z"/></svg>
    </button>
  </header>

  <section class="card progress" aria-label="Progress">
    <div class="top"><span><b id="done">0</b> of <span id="total">0</span> completed</span><span id="pct">0%</span></div>
    <div class="bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="0" id="pb"><i id="fill"></i></div>
  </section>

  <form class="card add" id="form" autocomplete="off">
    <div class="main">
      <label class="sr" for="text">New task</label>
      <input type="text" id="text" placeholder="What needs to be done?" maxlength="200" required>
      <button class="btn" type="submit">Add task</button>
    </div>
    <div class="opts">
      <label class="sr" for="prio">Priority</label>
      <select id="prio"><option value="low">Low priority</option><option value="med" selected>Medium priority</option><option value="high">High priority</option></select>
      <label class="sr" for="due">Due date</label>
      <input type="date" id="due">
    </div>
  </form>

  <div class="toolbar">
    <div class="seg" role="group" aria-label="Filter tasks" id="seg">
      <button data-f="all" aria-pressed="true">All</button>
      <button data-f="active" aria-pressed="false">Active</button>
      <button data-f="done" aria-pressed="false">Done</button>
    </div>
    <label class="sr" for="q">Search tasks</label>
    <input class="search" id="q" type="search" placeholder="Search tasks">
  </div>

  <ul id="list" aria-live="polite"></ul>

  <footer>
    <span id="left">0 tasks left</span>
    <button class="link" id="clear">Clear completed</button>
  </footer>
</div>

<script>
(function () {
  var KEY = "todo.tasks.v1", THEME = "todo.theme";
  var tasks = [], filter = "all", query = "", editing = null;
  var $ = function (s) { return document.querySelector(s); };

  function load(k, d) { try { var v = localStorage.getItem(k); return v ? JSON.parse(v) : d; } catch (e) { return d; } }
  function save(k, v) { try { localStorage.setItem(k, JSON.stringify(v)); } catch (e) {} }

  tasks = load(KEY, []);
  var theme = load(THEME, matchMedia("(prefers-color-scheme: dark)").matches ? "dark" : "light");

  var svg = {
    edit: '<svg viewBox="0 0 24 24"><path d="M12 20h9M16.5 3.5a2.1 2.1 0 0 1 3 3L7 19l-4 1 1-4z"/></svg>',
    del: '<svg viewBox="0 0 24 24"><path d="M3 6h18M8 6V4h8v2M19 6l-1 14H6L5 6M10 11v5M14 11v5"/></svg>'
  };

  function applyTheme() {
    document.documentElement.dataset.theme = theme;
    $("#theme").setAttribute("aria-label", theme === "dark" ? "Switch to light mode" : "Switch to dark mode");
    $("#ico").innerHTML = theme === "dark"
      ? '<circle cx="12" cy="12" r="4"/><path d="M12 2v2M12 20v2M4.9 4.9l1.4 1.4M17.7 17.7l1.4 1.4M2 12h2M20 12h2M4.9 19.1l1.4-1.4M17.7 6.3l1.4-1.4"/>'
      : '<path d="M21 12.8A9 9 0 1 1 11.2 3a7 7 0 0 0 9.8 9.8z"/>';
  }

  function esc(s) { return String(s).replace(/[&<>"']/g, function (c) { return { "&": "&amp;", "<": "&lt;", ">": "&gt;", '"': "&quot;", "'": "&#39;" }[c]; }); }
  function today() { var d = new Date(); return d.getFullYear() + "-" + String(d.getMonth() + 1).padStart(2, "0") + "-" + String(d.getDate()).padStart(2, "0"); }
  function fmt(d) { var p = d.split("-"); return new Date(p[0], p[1] - 1, p[2]).toLocaleDateString(undefined, { day: "numeric", month: "short" }); }
  function persist() { save(KEY, tasks); }

  function render() {
    var done = tasks.filter(function (t) { return t.done; }).length, total = tasks.length;
    var pct = total ? Math.round(done / total * 100) : 0;
    $("#done").textContent = done; $("#total").textContent = total; $("#pct").textContent = pct + "%";
    $("#fill").style.width = pct + "%"; $("#pb").setAttribute("aria-valuenow", pct);
    var left = total - done;
    $("#left").textContent = left + (left === 1 ? " task left" : " tasks left");
    $("#clear").style.visibility = done ? "visible" : "hidden";

    var q = query.trim().toLowerCase();
    var shown = tasks.filter(function (t) {
      if (filter === "active" && t.done) return false;
      if (filter === "done" && !t.done) return false;
      return !q || t.text.toLowerCase().indexOf(q) > -1;
    });

    var list = $("#list");
    if (!shown.length) {
      var msg = total === 0 ? ["Nothing here yet", "Add your first task above to get started."]
        : q ? ["No matches", "Try a different search."] : ["All clear", "No tasks in this view."];
      list.innerHTML = '<li class="empty" style="display:block;border-left-width:1px"><b>' + msg[0] + "</b>" + msg[1] + "</li>";
      return;
    }
    list.innerHTML = shown.map(function (t) {
      var late = t.due && !t.done && t.due < today();
      var meta = (t.due ? '<span class="' + (late ? "late" : "") + '">' + (late ? "Overdue · " : "Due ") + fmt(t.due) + "</span>" : "") +
        '<span>' + { high: "High", med: "Medium", low: "Low" }[t.prio] + " priority</span>";
      var body = editing === t.id
        ? '<input class="edit" data-edit="' + t.id + '" value="' + esc(t.text) + '" maxlength="200" aria-label="Edit task">'
        : '<span class="title" data-id="' + t.id + '">' + esc(t.text) + '</span><div class="meta">' + meta + "</div>";
      return '<li class="p-' + t.prio + (t.done ? " done" : "") + '">' +
        '<input class="check" type="checkbox" data-id="' + t.id + '"' + (t.done ? " checked" : "") + ' aria-label="Mark complete">' +
        '<div class="body">' + body + "</div>" +
        '<button class="row-btn" data-act="edit" data-id="' + t.id + '" aria-label="Edit task">' + svg.edit + "</button>" +
        '<button class="row-btn del" data-act="del" data-id="' + t.id + '" aria-label="Delete task">' + svg.del + "</button></li>";
    }).join("");
    var ed = list.querySelector(".edit");
    if (ed) { ed.focus(); ed.setSelectionRange(ed.value.length, ed.value.length); }
  }

  function finishEdit(id, commit) {
    var el = document.querySelector('[data-edit="' + id + '"]');
    if (commit && el && el.value.trim()) { tasks.forEach(function (t) { if (t.id === id) t.text = el.value.trim(); }); persist(); }
    editing = null; render();
  }

  $("#form").addEventListener("submit", function (e) {
    e.preventDefault();
    var text = $("#text").value.trim();
    if (!text) return;
    tasks.unshift({ id: Date.now().toString(36) + Math.random().toString(36).slice(2, 5), text: text, done: false, prio: $("#prio").value, due: $("#due").value, created: Date.now() });
    persist(); $("#text").value = ""; $("#due").value = ""; $("#text").focus(); render();
  });

  $("#list").addEventListener("click", function (e) {
    var el = e.target.closest("[data-id],[data-act]"); if (!el) return;
    var id = el.dataset.id, act = el.dataset.act;
    if (act === "del") { tasks = tasks.filter(function (t) { return t.id !== id; }); persist(); render(); }
    else if (act === "edit") { editing = id; render(); }
  });
  $("#list").addEventListener("change", function (e) {
    if (!e.target.classList.contains("check")) return;
    tasks.forEach(function (t) { if (t.id === e.target.dataset.id) t.done = e.target.checked; });
    persist(); render();
  });
  $("#list").addEventListener("dblclick", function (e) {
    var t = e.target.closest(".title"); if (t) { editing = t.dataset.id; render(); }
  });
  $("#list").addEventListener("keydown", function (e) {
    if (!e.target.dataset.edit) return;
    if (e.key === "Enter") finishEdit(e.target.dataset.edit, true);
    if (e.key === "Escape") finishEdit(e.target.dataset.edit, false);
  });
  $("#list").addEventListener("focusout", function (e) {
    if (e.target.dataset && e.target.dataset.edit && editing === e.target.dataset.edit) finishEdit(e.target.dataset.edit, true);
  });

  $("#seg").addEventListener("click", function (e) {
    var b = e.target.closest("button"); if (!b) return;
    filter = b.dataset.f;
    document.querySelectorAll("#seg button").forEach(function (x) { x.setAttribute("aria-pressed", x === b); });
    render();
  });
  $("#q").addEventListener("input", function (e) { query = e.target.value; render(); });
  $("#clear").addEventListener("click", function () { tasks = tasks.filter(function (t) { return !t.done; }); persist(); render(); });
  $("#theme").addEventListener("click", function () { theme = theme === "dark" ? "light" : "dark"; save(THEME, theme); applyTheme(); });

  var h = new Date().getHours();
  $("#greet").textContent = (h < 12 ? "Good morning" : h < 18 ? "Good afternoon" : "Good evening") + ".";
  $("#date").textContent = new Date().toLocaleDateString(undefined, { weekday: "long", day: "numeric", month: "long" });
  applyTheme(); render();
})();
</script>
</body>
</html>
