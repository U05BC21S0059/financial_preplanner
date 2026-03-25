<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FinPlan Pro – Personal Financial Planner</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=DM+Sans:wght@300;400;500;600&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
<style>
:root {
  --bg: #0b0f1a;
  --surface: #131929;
  --surface2: #1a2236;
  --border: #253048;
  --accent: #3d8ef0;
  --accent2: #00d9a6;
  --accent3: #f0a23d;
  --danger: #f04f4f;
  --text: #e8edf5;
  --muted: #7a8ba8;
  --card: #16202e;
  --gold: #c9a84c;
}
*{box-sizing:border-box;margin:0;padding:0}
body{background:var(--bg);color:var(--text);font-family:'DM Sans',sans-serif;min-height:100vh;overflow-x:hidden}

/* ── HEADER ── */
header{background:linear-gradient(135deg,#0d1626 0%,#132040 50%,#0d1626 100%);border-bottom:1px solid var(--border);padding:0 32px;display:flex;align-items:center;justify-content:space-between;height:64px;position:sticky;top:0;z-index:100}
.logo{display:flex;align-items:center;gap:12px}
.logo-icon{width:36px;height:36px;background:linear-gradient(135deg,var(--accent),var(--accent2));border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:18px}
.logo-text{font-family:'Playfair Display',serif;font-size:20px;font-weight:700;background:linear-gradient(90deg,var(--accent),var(--accent2));-webkit-background-clip:text;-webkit-text-fill-color:transparent}
.logo-sub{font-size:11px;color:var(--muted);letter-spacing:2px;text-transform:uppercase;font-weight:500}
.header-meta{display:flex;align-items:center;gap:16px}
.year-badge{background:var(--surface2);border:1px solid var(--border);border-radius:8px;padding:6px 14px;font-family:'DM Mono',monospace;font-size:13px;color:var(--accent);font-weight:500}

/* ── LAYOUT ── */
.layout{display:flex;min-height:calc(100vh - 64px)}

/* ── SIDEBAR ── */
nav{width:220px;background:var(--surface);border-right:1px solid var(--border);padding:24px 0;display:flex;flex-direction:column;gap:2px;flex-shrink:0}
.nav-section{padding:6px 16px 4px;font-size:10px;text-transform:uppercase;letter-spacing:2px;color:var(--muted);font-weight:600;margin-top:8px}
.nav-item{display:flex;align-items:center;gap:10px;padding:9px 16px;cursor:pointer;color:var(--muted);font-size:13.5px;font-weight:500;transition:all .2s;border-left:3px solid transparent;margin:0 0;user-select:none}
.nav-item:hover{color:var(--text);background:var(--surface2)}
.nav-item.active{color:var(--accent);background:rgba(61,142,240,.08);border-left-color:var(--accent)}
.nav-item .icon{font-size:15px;width:20px;text-align:center}

/* ── MAIN ── */
main{flex:1;padding:32px;overflow-y:auto;background:var(--bg)}
.page{display:none;animation:fadeIn .3s ease}
.page.active{display:block}
@keyframes fadeIn{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:translateY(0)}}

/* ── PAGE HEADER ── */
.page-header{margin-bottom:28px}
.page-title{font-family:'Playfair Display',serif;font-size:26px;font-weight:700;color:var(--text);margin-bottom:4px}
.page-subtitle{font-size:13px;color:var(--muted);font-weight:400}

/* ── CARDS ── */
.card{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:24px;margin-bottom:20px}
.card-title{font-size:13px;text-transform:uppercase;letter-spacing:1.5px;color:var(--muted);font-weight:600;margin-bottom:18px;display:flex;align-items:center;gap:8px}
.card-title .dot{width:7px;height:7px;border-radius:50%;background:var(--accent)}

/* ── FORM ELEMENTS ── */
.form-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:16px}
.form-group{display:flex;flex-direction:column;gap:6px}
.form-group label{font-size:12px;color:var(--muted);font-weight:500;letter-spacing:.3px}
.form-group input,.form-group select{background:var(--surface2);border:1px solid var(--border);border-radius:8px;padding:9px 12px;color:var(--text);font-size:13.5px;font-family:'DM Sans',sans-serif;transition:border .2s;outline:none}
.form-group input:focus,.form-group select:focus{border-color:var(--accent);background:#1e2d45}
.form-group select option{background:var(--surface2)}
.form-group input[type=number]{font-family:'DM Mono',monospace}
.inp-prefix{position:relative}
.inp-prefix span{position:absolute;left:10px;top:50%;transform:translateY(-50%);color:var(--muted);font-family:'DM Mono',monospace;font-size:13px;pointer-events:none}
.inp-prefix input{padding-left:24px}

/* ── TABLES ── */
.table-wrap{overflow-x:auto;border-radius:10px;border:1px solid var(--border)}
table{width:100%;border-collapse:collapse;font-size:13px}
thead tr{background:var(--surface2)}
thead th{padding:10px 14px;text-align:left;color:var(--muted);font-weight:600;font-size:11.5px;text-transform:uppercase;letter-spacing:1px;white-space:nowrap;border-bottom:1px solid var(--border)}
tbody tr{border-bottom:1px solid rgba(37,48,72,.6);transition:background .15s}
tbody tr:last-child{border-bottom:none}
tbody tr:hover{background:rgba(61,142,240,.04)}
td{padding:10px 14px;color:var(--text);font-size:13px}
td input,td select{background:var(--surface);border:1px solid transparent;border-radius:6px;padding:5px 8px;color:var(--text);font-size:13px;font-family:'DM Sans',sans-serif;width:100%;outline:none;transition:border .2s}
td input:focus,td select:focus{border-color:var(--accent);background:var(--surface2)}
td input[type=number]{font-family:'DM Mono',monospace}
.td-num{font-family:'DM Mono',monospace;text-align:right;color:var(--accent2)}
.td-calc{font-family:'DM Mono',monospace;text-align:right;color:var(--gold);background:rgba(201,168,76,.05)}

/* ── BUTTONS ── */
.btn{display:inline-flex;align-items:center;gap:6px;padding:8px 18px;border-radius:8px;border:none;cursor:pointer;font-size:13px;font-weight:600;font-family:'DM Sans',sans-serif;transition:all .2s}
.btn-primary{background:var(--accent);color:#fff}
.btn-primary:hover{background:#2d7de0;transform:translateY(-1px)}
.btn-success{background:var(--accent2);color:#0b1a15}
.btn-success:hover{background:#00c295}
.btn-ghost{background:transparent;border:1px solid var(--border);color:var(--muted)}
.btn-ghost:hover{border-color:var(--accent);color:var(--accent)}
.btn-sm{padding:5px 12px;font-size:12px}
.btn-danger{background:rgba(240,79,79,.1);border:1px solid rgba(240,79,79,.3);color:var(--danger)}
.btn-danger:hover{background:rgba(240,79,79,.2)}
.actions-row{display:flex;gap:10px;margin-top:16px;flex-wrap:wrap}

/* ── SUMMARY CARDS ── */
.kpi-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(180px,1fr));gap:16px;margin-bottom:24px}
.kpi{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:18px 20px;position:relative;overflow:hidden}
.kpi::before{content:'';position:absolute;top:0;left:0;right:0;height:3px}
.kpi.blue::before{background:linear-gradient(90deg,var(--accent),#6eb5ff)}
.kpi.green::before{background:linear-gradient(90deg,var(--accent2),#7effd4)}
.kpi.gold::before{background:linear-gradient(90deg,var(--gold),#f0d28a)}
.kpi.red::before{background:linear-gradient(90deg,var(--danger),#ff9494)}
.kpi-label{font-size:11px;color:var(--muted);text-transform:uppercase;letter-spacing:1.5px;font-weight:600;margin-bottom:8px}
.kpi-value{font-family:'DM Mono',monospace;font-size:22px;font-weight:500;color:var(--text)}
.kpi-sub{font-size:11px;color:var(--muted);margin-top:4px}

/* ── TAGS ── */
.tag{display:inline-block;padding:2px 8px;border-radius:4px;font-size:11px;font-weight:600}
.tag-green{background:rgba(0,217,166,.1);color:var(--accent2)}
.tag-blue{background:rgba(61,142,240,.1);color:var(--accent)}
.tag-gold{background:rgba(201,168,76,.1);color:var(--gold)}
.tag-red{background:rgba(240,79,79,.1);color:var(--danger)}

/* ── CASHFLOW CHART ── */
.cf-bar-row{display:flex;align-items:center;gap:12px;margin-bottom:6px}
.cf-bar-label{width:60px;font-size:12px;color:var(--muted);text-align:right;font-family:'DM Mono',monospace}
.cf-bar-track{flex:1;height:18px;background:var(--surface2);border-radius:4px;overflow:hidden}
.cf-bar-fill{height:100%;border-radius:4px;transition:width .6s ease}
.cf-bar-val{width:90px;font-size:12px;font-family:'DM Mono',monospace;color:var(--text)}
.bar-in{background:linear-gradient(90deg,var(--accent2),#00a880)}
.bar-out{background:linear-gradient(90deg,var(--danger),#c03232)}
.bar-net{background:linear-gradient(90deg,var(--accent),#2d5fb0)}

/* ── PROGRESS ── */
.progress-row{margin-bottom:14px}
.progress-label{display:flex;justify-content:space-between;margin-bottom:5px;font-size:12.5px}
.progress-track{height:8px;background:var(--surface2);border-radius:4px;overflow:hidden}
.progress-fill{height:100%;border-radius:4px;background:linear-gradient(90deg,var(--accent),var(--accent2));transition:width .8s ease}

/* ── SECTION DIVIDER ── */
.section-sep{height:1px;background:var(--border);margin:24px 0}

/* ── STATUS PILLS ── */
.pill{display:inline-flex;align-items:center;gap:4px;padding:3px 10px;border-radius:20px;font-size:11.5px;font-weight:600}
.pill-on{background:rgba(0,217,166,.12);color:var(--accent2)}
.pill-off{background:rgba(240,79,79,.12);color:var(--danger)}

/* ── SCROLLBAR ── */
::-webkit-scrollbar{width:6px;height:6px}
::-webkit-scrollbar-track{background:var(--bg)}
::-webkit-scrollbar-thumb{background:var(--border);border-radius:3px}

/* ── RESPONSIVE ── */
@media(max-width:768px){nav{display:none}main{padding:20px}}
</style>
</head>
<body>

<header>
  <div class="logo">
    <div class="logo-icon">💎</div>
    <div>
      <div class="logo-text">FinPlan Pro</div>
      <div class="logo-sub">Personal Financial Planner</div>
    </div>
  </div>
  <div class="header-meta">
    <div style="display:flex;align-items:center;gap:6px;background:var(--surface2);border:1px solid var(--border);border-radius:8px;padding:4px 10px">
      <span style="font-size:11px;color:var(--muted);font-weight:600;letter-spacing:1px">FY</span>
      <select id="fy-select" onchange="onFYChange()" style="background:transparent;border:none;color:var(--accent);font-family:'DM Mono',monospace;font-size:13px;font-weight:600;outline:none;cursor:pointer;padding:2px 0">
        <option value="2023">2023–24</option>
        <option value="2024">2024–25</option>
        <option value="2025" selected>2025–26</option>
        <option value="2026">2026–27</option>
        <option value="2027">2027–28</option>
        <option value="2028">2028–29</option>
        <option value="2029">2029–30</option>
        <option value="2030">2030–31</option>
      </select>
    </div>
    <button class="btn btn-primary btn-sm" onclick="saveData()">💾 Save</button>
    <button class="btn btn-success btn-sm" onclick="exportToExcel()">📊 Export to Excel</button>
  </div>
</header>

<div class="layout">
<nav id="sidebar">
  <div class="nav-section">Overview</div>
  <div class="nav-item active" onclick="showPage('dashboard')" data-page="dashboard"><span class="icon">📊</span> Dashboard</div>

  <div class="nav-section">Profile</div>
  <div class="nav-item" onclick="showPage('about')" data-page="about"><span class="icon">👤</span> About You</div>
  <div class="nav-item" onclick="showPage('goals')" data-page="goals"><span class="icon">🎯</span> Goals</div>

  <div class="nav-section">Finances</div>
  <div class="nav-item" onclick="showPage('inflows')" data-page="inflows"><span class="icon">💰</span> Inflows</div>
  <div class="nav-item" onclick="showPage('outflows')" data-page="outflows"><span class="icon">💸</span> Outflows</div>
  <div class="nav-item" onclick="showPage('assets')" data-page="assets"><span class="icon">🏦</span> Assets</div>
  <div class="nav-item" onclick="showPage('loans')" data-page="loans"><span class="icon">🏠</span> Loan Details</div>
  <div class="nav-item" onclick="showPage('insurance')" data-page="insurance"><span class="icon">🛡️</span> Insurance</div>

  <div class="nav-section">Analysis</div>
  <div class="nav-item" onclick="showPage('cashflow')" data-page="cashflow"><span class="icon">📈</span> Cash Flow</div>
  <div class="nav-item" onclick="showPage('retirement')" data-page="retirement"><span class="icon">🌅</span> Post Retirement</div>
  <div class="nav-item" onclick="showPage('portfolio')" data-page="portfolio"><span class="icon">📂</span> Portfolio</div>
</nav>

<main>

<!-- ══════════ DASHBOARD ══════════ -->
<div class="page active" id="page-dashboard">
  <div class="page-header">
    <div class="page-title">Financial Dashboard</div>
    <div class="page-subtitle">Your complete financial snapshot at a glance</div>
  </div>

  <div class="kpi-grid" id="kpi-grid">
    <div class="kpi blue">
      <div class="kpi-label">Total Monthly Inflow</div>
      <div class="kpi-value" id="kpi-inflow">₹0</div>
      <div class="kpi-sub">Salary + Business + Other</div>
    </div>
    <div class="kpi red">
      <div class="kpi-label">Total Monthly Outflow</div>
      <div class="kpi-value" id="kpi-outflow">₹0</div>
      <div class="kpi-sub">Expenses + Investments</div>
    </div>
    <div class="kpi green">
      <div class="kpi-label">Monthly Surplus</div>
      <div class="kpi-value" id="kpi-surplus">₹0</div>
      <div class="kpi-sub">Inflow minus Outflow</div>
    </div>
    <div class="kpi gold">
      <div class="kpi-label">Total Assets</div>
      <div class="kpi-value" id="kpi-assets">₹0</div>
      <div class="kpi-sub">Fixed + Financial Assets</div>
    </div>
    <div class="kpi red">
      <div class="kpi-label">Total Liabilities</div>
      <div class="kpi-value" id="kpi-liabilities">₹0</div>
      <div class="kpi-sub">Outstanding Loans</div>
    </div>
    <div class="kpi green">
      <div class="kpi-label">Net Worth</div>
      <div class="kpi-value" id="kpi-networth">₹0</div>
      <div class="kpi-sub">Assets minus Liabilities</div>
    </div>
  </div>

  <div style="display:grid;grid-template-columns:1fr 1fr;gap:20px">
    <div class="card">
      <div class="card-title"><span class="dot" style="background:var(--accent2)"></span>Monthly Cash Flow</div>
      <div id="cf-chart">
        <div class="cf-bar-row"><div class="cf-bar-label">Inflow</div><div class="cf-bar-track"><div class="cf-bar-fill bar-in" id="bar-in" style="width:0%"></div></div><div class="cf-bar-val" id="bv-in">₹0</div></div>
        <div class="cf-bar-row"><div class="cf-bar-label">Outflow</div><div class="cf-bar-track"><div class="cf-bar-fill bar-out" id="bar-out" style="width:0%"></div></div><div class="cf-bar-val" id="bv-out">₹0</div></div>
        <div class="cf-bar-row"><div class="cf-bar-label">Surplus</div><div class="cf-bar-track"><div class="cf-bar-fill bar-net" id="bar-net" style="width:0%"></div></div><div class="cf-bar-val" id="bv-net">₹0</div></div>
      </div>
    </div>
    <div class="card">
      <div class="card-title"><span class="dot" style="background:var(--gold)"></span>Goals Progress</div>
      <div id="goals-progress">
        <div style="color:var(--muted);font-size:13px">No goals added yet. Go to Goals section →</div>
      </div>
    </div>
  </div>

  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--accent3)"></span>Family Members</div>
    <div id="family-summary" style="color:var(--muted);font-size:13px">Complete the About You section to see your family summary.</div>
  </div>

  <div class="card">
    <div class="card-title"><span class="dot"></span>Insurance Summary</div>
    <div id="ins-summary" style="color:var(--muted);font-size:13px">No insurance policies added yet.</div>
  </div>
</div>

<!-- ══════════ ABOUT YOU ══════════ -->
<div class="page" id="page-about">
  <div class="page-header">
    <div class="page-title">About You</div>
    <div class="page-subtitle">Personal & family details for your financial plan</div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot"></span>Planning Year</div>
    <div class="form-grid">
      <div class="form-group"><label>Current Year</label><input type="number" id="currentYear" value="2025" oninput="updateYear()"></div>
      <div class="form-group"><label>Last Planning Year</label><input type="number" id="lastPlanYear" value="2024"></div>
      <div class="form-group"><label>Risk Score (1–10)</label><input type="number" id="riskScore" min="1" max="10" value="5"></div>
    </div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot"></span>Self</div>
    <div class="form-grid">
      <div class="form-group"><label>Name</label><input type="text" id="selfName" placeholder="Your name"></div>
      <div class="form-group"><label>Date of Birth</label><input type="date" id="selfDob" value="1980-01-01" oninput="calcRetirement()"></div>
      <div class="form-group"><label>PAN</label><input type="text" id="selfPan" placeholder="ABCDE1234F"></div>
      <div class="form-group"><label>Retirement Age</label><input type="number" id="retireAge" value="58" oninput="calcRetirement()"></div>
      <div class="form-group"><label>Actual Retirement Year</label><input type="number" id="retireYear" value="2038" readonly style="color:var(--accent2)"></div>
    </div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot"></span>Spouse / Partner</div>
    <div class="form-grid">
      <div class="form-group"><label>Name</label><input type="text" id="spouseName" placeholder="Spouse's name"></div>
      <div class="form-group"><label>Date of Birth</label><input type="date" id="spouseDob"></div>
      <div class="form-group"><label>PAN</label><input type="text" id="spousePan" placeholder="ABCDE1234F"></div>
    </div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--accent3)"></span>Children
      <button class="btn btn-ghost btn-sm" style="margin-left:auto" onclick="addChildRow()">+ Add Child</button>
    </div>
    <div id="no-children-msg" style="color:var(--muted);font-size:13px;padding:4px 0 8px">No children added. Click "+ Add Child" to add.</div>
    <div class="table-wrap" id="children-table-wrap" style="display:none">
      <table>
        <thead>
          <tr>
            <th>#</th>
            <th>Name</th>
            <th>Date of Birth</th>
            <th>Age</th>
            <th>Gender</th>
            <th>Education Goal Year</th>
            <th>Marriage Goal Year</th>
            <th>Comments</th>
            <th></th>
          </tr>
        </thead>
        <tbody id="children-tbody"></tbody>
      </table>
    </div>
  </div>
  <div class="actions-row">
    <button class="btn btn-primary" onclick="savePage('about');showPage('goals')">Save & Next →</button>
  </div>
</div>

<!-- ══════════ GOALS ══════════ -->
<div class="page" id="page-goals">
  <div class="page-header">
    <div class="page-title">Financial Goals</div>
    <div class="page-subtitle">Define your life goals with target amounts and timelines</div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--gold)"></span>Goals List</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>#</th><th>Goal Name</th><th>Today's Cost (₹)</th><th>Target Year</th><th>Inflation %</th><th>Future Value (₹)</th><th>Comments</th><th></th></tr></thead>
        <tbody id="goals-tbody"></tbody>
      </table>
    </div>
    <div class="actions-row">
      <button class="btn btn-ghost btn-sm" onclick="addGoalRow()">+ Add Goal</button>
    </div>
  </div>
  <div class="actions-row">
    <button class="btn btn-primary" onclick="savePage('goals');showPage('inflows')">Save & Next →</button>
  </div>
</div>

<!-- ══════════ INFLOWS ══════════ -->
<div class="page" id="page-inflows">
  <div class="page-header">
    <div class="page-title">Income / Inflows</div>
    <div class="page-subtitle">Monthly and yearly income sources</div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--accent2)"></span>Monthly Income</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>#</th><th>Particulars</th><th>Self (₹/mo)</th><th>Spouse (₹/mo)</th><th>Total Monthly</th><th>Annual</th><th>Increment %</th><th></th></tr></thead>
        <tbody id="inflow-tbody"></tbody>
      </table>
    </div>
    <div class="actions-row"><button class="btn btn-ghost btn-sm" onclick="addInflowRow()">+ Add Income</button></div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot"></span>Yearly / One-time Inflows</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>#</th><th>Particulars</th><th>Amount (₹)</th><th>Year</th><th>Comments</th><th></th></tr></thead>
        <tbody id="yearly-inflow-tbody"></tbody>
      </table>
    </div>
    <div class="actions-row"><button class="btn btn-ghost btn-sm" onclick="addYearlyInflowRow()">+ Add Yearly Inflow</button></div>
  </div>
  <div class="actions-row">
    <button class="btn btn-primary" onclick="savePage('inflows');showPage('outflows')">Save & Next →</button>
  </div>
</div>

<!-- ══════════ OUTFLOWS ══════════ -->
<div class="page" id="page-outflows">
  <div class="page-header">
    <div class="page-title">Expenses / Outflows</div>
    <div class="page-subtitle">Monthly expenses and investments</div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--danger)"></span>Monthly Expenses</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>#</th><th>Particulars</th><th>Current Amount (₹)</th><th>Inflation %</th><th>Comments</th><th></th></tr></thead>
        <tbody id="expense-tbody"></tbody>
      </table>
    </div>
    <div class="actions-row"><button class="btn btn-ghost btn-sm" onclick="addExpenseRow()">+ Add Expense</button></div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--accent)"></span>Monthly Investments / Savings</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>#</th><th>Particulars</th><th>Amount (₹)</th><th>Expected Return %</th><th>Comments</th><th></th></tr></thead>
        <tbody id="invest-tbody"></tbody>
      </table>
    </div>
    <div class="actions-row"><button class="btn btn-ghost btn-sm" onclick="addInvestRow()">+ Add Investment</button></div>
  </div>
  <div class="actions-row">
    <button class="btn btn-primary" onclick="savePage('outflows');showPage('assets')">Save & Next →</button>
  </div>
</div>

<!-- ══════════ ASSETS ══════════ -->
<div class="page" id="page-assets">
  <div class="page-header">
    <div class="page-title">Assets</div>
    <div class="page-subtitle">Fixed lifestyle assets, investment assets, and financial assets</div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--gold)"></span>Fixed Assets – Lifestyle (Home, Car, etc.)</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>#</th><th>Particulars</th><th>Today's Value (₹)</th><th>Liability (₹)</th><th>Comments</th><th></th></tr></thead>
        <tbody id="fixed-lifestyle-tbody"></tbody>
      </table>
    </div>
    <div class="actions-row"><button class="btn btn-ghost btn-sm" onclick="addAssetRow('fixed-lifestyle-tbody')">+ Add</button></div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--accent)"></span>Fixed Assets – Investments (Real Estate, etc.)</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>#</th><th>Particulars</th><th>Today's Value (₹)</th><th>Liability (₹)</th><th>Growth % p.a.</th><th>Comments</th><th></th></tr></thead>
        <tbody id="fixed-invest-tbody"></tbody>
      </table>
    </div>
    <div class="actions-row"><button class="btn btn-ghost btn-sm" onclick="addInvestAssetRow()">+ Add</button></div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--accent2)"></span>Financial Assets (MF, Stocks, FD, etc.)</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>#</th><th>Particulars</th><th>Today's Value (₹)</th><th>Expected Return %</th><th>Category</th><th>Comments</th><th></th></tr></thead>
        <tbody id="fin-asset-tbody"></tbody>
      </table>
    </div>
    <div class="actions-row"><button class="btn btn-ghost btn-sm" onclick="addFinAssetRow()">+ Add</button></div>
  </div>
  <div class="actions-row">
    <button class="btn btn-primary" onclick="savePage('assets');showPage('loans')">Save & Next →</button>
  </div>
</div>

<!-- ══════════ LOANS ══════════ -->
<div class="page" id="page-loans">
  <div class="page-header">
    <div class="page-title">Loan Details</div>
    <div class="page-subtitle">All liabilities and outstanding loan amounts</div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--danger)"></span>Liabilities</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>#</th><th>Particulars</th><th>Lender</th><th>Start Yr</th><th>End Yr</th><th>Monthly EMI (₹)</th><th>Interest %</th><th>Outstanding (₹)</th><th></th></tr></thead>
        <tbody id="loans-tbody"></tbody>
      </table>
    </div>
    <div class="actions-row"><button class="btn btn-ghost btn-sm" onclick="addLoanRow()">+ Add Loan</button></div>
  </div>
  <div class="actions-row">
    <button class="btn btn-primary" onclick="savePage('loans');showPage('insurance')">Save & Next →</button>
  </div>
</div>

<!-- ══════════ INSURANCE ══════════ -->
<div class="page" id="page-insurance">
  <div class="page-header">
    <div class="page-title">Insurance</div>
    <div class="page-subtitle">Life, health, and investment insurance policies</div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--accent2)"></span>Insurance Policies</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>#</th><th>Plan Name</th><th>Type</th><th>Insured</th><th>Sum Assured (₹)</th><th>Annual Premium (₹)</th><th>Start Yr</th><th>End Yr</th><th>Maturity Value (₹)</th><th>Status</th><th></th></tr></thead>
        <tbody id="ins-tbody"></tbody>
      </table>
    </div>
    <div class="actions-row"><button class="btn btn-ghost btn-sm" onclick="addInsuranceRow()">+ Add Policy</button></div>
  </div>
  <div class="actions-row">
    <button class="btn btn-primary" onclick="savePage('insurance');showPage('cashflow')">View Cash Flow →</button>
  </div>
</div>

<!-- ══════════ CASH FLOW ══════════ -->
<div class="page" id="page-cashflow">
  <div class="page-header">
    <div class="page-title">Cash Flow Summary</div>
    <div class="page-subtitle">Year-by-year projected financial position</div>
  </div>
  <div class="kpi-grid" style="grid-template-columns:repeat(3,1fr)">
    <div class="kpi blue"><div class="kpi-label">Annual Inflow</div><div class="kpi-value" id="cf-annual-in">₹0</div></div>
    <div class="kpi red"><div class="kpi-label">Annual Outflow</div><div class="kpi-value" id="cf-annual-out">₹0</div></div>
    <div class="kpi green"><div class="kpi-label">Annual Surplus</div><div class="kpi-value" id="cf-annual-surplus">₹0</div></div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot"></span>Projected Year-by-Year</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>Year</th><th>Opening (₹)</th><th>Inflow (₹)</th><th>Outflow (₹)</th><th>Surplus (₹)</th><th>Growth (₹)</th><th>Closing (₹)</th><th>Net Worth</th></tr></thead>
        <tbody id="cf-tbody"></tbody>
      </table>
    </div>
  </div>
</div>

<!-- ══════════ POST RETIREMENT ══════════ -->
<div class="page" id="page-retirement">
  <div class="page-header">
    <div class="page-title">Post Retirement Cash Flow</div>
    <div class="page-subtitle">Projected finances after retirement</div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--gold)"></span>Assumptions</div>
    <div class="form-grid">
      <div class="form-group"><label>Corpus at Retirement (₹)</label><input type="number" id="retireCorpus" value="0" oninput="calcRetirementCF()"></div>
      <div class="form-group"><label>Monthly Expenses at Retirement (₹)</label><input type="number" id="retireExpense" value="0" oninput="calcRetirementCF()"></div>
      <div class="form-group"><label>Monthly Rental Income (₹)</label><input type="number" id="retireRent" value="0" oninput="calcRetirementCF()"></div>
      <div class="form-group"><label>Portfolio Return % p.a.</label><input type="number" id="retireReturn" value="7" step="0.1" oninput="calcRetirementCF()"></div>
      <div class="form-group"><label>Inflation % p.a.</label><input type="number" id="retireInflation" value="6" step="0.1" oninput="calcRetirementCF()"></div>
      <div class="form-group"><label>Life Expectancy (Age)</label><input type="number" id="lifeExpect" value="85" oninput="calcRetirementCF()"></div>
    </div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot"></span>Year-by-Year Post Retirement</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>Year</th><th>Age</th><th>Opening (₹)</th><th>Rent (₹)</th><th>Expenses (₹)</th><th>Surplus (₹)</th><th>Growth (₹)</th><th>Closing (₹)</th></tr></thead>
        <tbody id="retire-tbody"></tbody>
      </table>
    </div>
  </div>
</div>

<!-- ══════════ PORTFOLIO ══════════ -->
<div class="page" id="page-portfolio">
  <div class="page-header">
    <div class="page-title">Portfolio Analysis</div>
    <div class="page-subtitle">Asset allocation and portfolio performance</div>
  </div>
  <div class="kpi-grid">
    <div class="kpi blue"><div class="kpi-label">Equity</div><div class="kpi-value" id="pf-equity">₹0</div><div class="kpi-sub" id="pf-equity-pct">0% of portfolio</div></div>
    <div class="kpi gold"><div class="kpi-label">Hybrid</div><div class="kpi-value" id="pf-hybrid">₹0</div><div class="kpi-sub" id="pf-hybrid-pct">0% of portfolio</div></div>
    <div class="kpi green"><div class="kpi-label">Debt</div><div class="kpi-value" id="pf-debt">₹0</div><div class="kpi-sub" id="pf-debt-pct">0% of portfolio</div></div>
    <div class="kpi red"><div class="kpi-label">Others</div><div class="kpi-value" id="pf-others">₹0</div><div class="kpi-sub" id="pf-others-pct">0% of portfolio</div></div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot"></span>Asset Allocation</div>
    <div id="alloc-bars"></div>
  </div>
  <div class="card">
    <div class="card-title"><span class="dot" style="background:var(--accent2)"></span>Financial Assets Detail</div>
    <div class="table-wrap">
      <table>
        <thead><tr><th>Particulars</th><th>Value (₹)</th><th>Category</th><th>Return %</th></tr></thead>
        <tbody id="pf-detail-tbody"></tbody>
      </table>
    </div>
  </div>
</div>

</main>
</div>

<script>
// ── STATE ──────────────────────────────────────────────────────────
const state = {
  about:{currentYear:2025,lastPlanYear:2024,riskScore:5,selfName:'',selfDob:'1980-01-01',selfPan:'',retireAge:58,retireYear:2038,spouseName:'',spouseDob:'',spousePan:''},
  goals:[],
  inflows:[{particulars:'Salary',self:0,spouse:0,increment:0},{particulars:'Business Income',self:0,spouse:0,increment:0},{particulars:'Other Income',self:0,spouse:0,increment:0},{particulars:'Rent Income',self:0,spouse:0,increment:0}],
  yearlyInflows:[],
  expenses:[{particulars:'Household',amount:0,inflation:6},{particulars:'PF / EPF',amount:0,inflation:0}],
  investments:[{particulars:'SIP / Mutual Fund',amount:0,ret:12},{particulars:'PPF',amount:0,ret:7.1}],
  fixedLifestyle:[],
  fixedInvest:[],
  finAssets:[{particulars:'',value:0,ret:12,category:'Equity',comments:''}],
  loans:[],
  insurance:[],
  retire:{corpus:0,expense:0,rent:0,ret:7,inflation:6,lifeExpect:85}
};

const fmt = n => '₹'+Math.round(n).toLocaleString('en-IN');
const pct = n => parseFloat(n)||0;

// ── NAV ──────────────────────────────────────────────────────────
function showPage(id){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.nav-item').forEach(n=>n.classList.remove('active'));
  document.getElementById('page-'+id).classList.add('active');
  document.querySelector(`[data-page="${id}"]`).classList.add('active');
  if(id==='dashboard') updateDashboard();
  if(id==='cashflow') renderCashFlow();
  if(id==='retirement') calcRetirementCF();
  if(id==='portfolio') renderPortfolio();
}

// ── ABOUT ──────────────────────────────────────────────────────────
function onFYChange(){
  const fy = parseInt(document.getElementById('fy-select').value);
  // sync the currentYear input
  const cyEl = document.getElementById('currentYear');
  if(cyEl){ cyEl.value = fy; }
  state.about.currentYear = fy;
  calcRetirement();
  renderGoals();
}
function updateYear(){
  const y=document.getElementById('currentYear').value;
  // keep FY select in sync
  const sel=document.getElementById('fy-select');
  if(sel){
    const opt=[...sel.options].find(o=>o.value==y);
    if(opt) sel.value=y; else sel.value=2025;
  }
  state.about.currentYear=parseInt(y)||2025;
}
function calcRetirement(){
  const dob=document.getElementById('selfDob').value;
  const age=parseInt(document.getElementById('retireAge').value)||58;
  if(dob){
    const by=new Date(dob).getFullYear();
    document.getElementById('retireYear').value=by+age;
  }
}

// ── CHILDREN ──────────────────────────────────────────────────────────
function calcChildAge(dob){
  if(!dob) return '—';
  const today=new Date();
  const birth=new Date(dob);
  const age=today.getFullYear()-birth.getFullYear()-(today<new Date(today.getFullYear(),birth.getMonth(),birth.getDate())?1:0);
  return age>=0?age:'—';
}
function renderChildren(){
  const children=state.children;
  const tb=document.getElementById('children-tbody');
  const wrap=document.getElementById('children-table-wrap');
  const msg=document.getElementById('no-children-msg');
  if(!children.length){wrap.style.display='none';msg.style.display='block';return;}
  wrap.style.display='block';msg.style.display='none';
  tb.innerHTML='';
  children.forEach((c,i)=>{
    const age=calcChildAge(c.dob);
    const curYr=parseInt(document.getElementById('currentYear')?.value)||2025;
    const eduDefault=c.dob?new Date(c.dob).getFullYear()+18:curYr+18;
    const marDefault=c.dob?new Date(c.dob).getFullYear()+25:curYr+25;
    tb.innerHTML+=`<tr>
      <td>${i+1}</td>
      <td><input value="${c.name||''}" placeholder="Child's name" oninput="state.children[${i}].name=this.value" style="min-width:120px"></td>
      <td><input type="date" value="${c.dob||''}" oninput="state.children[${i}].dob=this.value;renderChildren()"></td>
      <td style="text-align:center;font-family:'DM Mono',monospace;color:var(--accent2)">${age}</td>
      <td><select oninput="state.children[${i}].gender=this.value" style="width:90px">
        <option${(c.gender||'Male')==='Male'?' selected':''}>Male</option>
        <option${c.gender==='Female'?' selected':''}>Female</option>
        <option${c.gender==='Other'?' selected':''}>Other</option>
      </select></td>
      <td><input type="number" value="${c.eduYear||eduDefault}" oninput="state.children[${i}].eduYear=parseInt(this.value)" style="width:80px"></td>
      <td><input type="number" value="${c.marYear||marDefault}" oninput="state.children[${i}].marYear=parseInt(this.value)" style="width:80px"></td>
      <td><input value="${c.comments||''}" placeholder="Notes" oninput="state.children[${i}].comments=this.value" style="min-width:120px"></td>
      <td><button class="btn btn-danger btn-sm" onclick="state.children.splice(${i},1);renderChildren()">✕</button></td>
    </tr>`;
  });
}
function addChildRow(){
  const curYr=parseInt(document.getElementById('currentYear')?.value)||2025;
  state.children.push({name:'',dob:'',gender:'Male',eduYear:curYr+18,marYear:curYr+25,comments:''});
  renderChildren();
}

// ── GOALS ──────────────────────────────────────────────────────────
function renderGoals(){
  const tb=document.getElementById('goals-tbody');
  tb.innerHTML='';
  state.goals.forEach((g,i)=>{
    const yr=parseInt(g.targetYear)||2025;
    const cur=parseInt(document.getElementById('currentYear')?.value)||2025;
    const periods=yr-cur;
    const inf=pct(g.inflation)/100;
    const fv=periods>0?g.cost*Math.pow(1+inf,periods):g.cost;
    g.fv=fv;
    tb.innerHTML+=`<tr>
      <td>${i+1}</td>
      <td><input value="${g.name}" oninput="state.goals[${i}].name=this.value" style="width:130px"></td>
      <td><input type="number" value="${g.cost}" oninput="state.goals[${i}].cost=parseFloat(this.value)||0;renderGoals()"></td>
      <td><input type="number" value="${g.targetYear}" oninput="state.goals[${i}].targetYear=this.value;renderGoals()"></td>
      <td><input type="number" value="${g.inflation}" oninput="state.goals[${i}].inflation=this.value;renderGoals()" style="width:60px"></td>
      <td class="td-calc">${fmt(fv)}</td>
      <td><input value="${g.comments||''}" oninput="state.goals[${i}].comments=this.value" style="width:130px"></td>
      <td><button class="btn btn-danger btn-sm" onclick="state.goals.splice(${i},1);renderGoals()">✕</button></td>
    </tr>`;
  });
}
function addGoalRow(){
  state.goals.push({name:'New Goal',cost:0,targetYear:2030,inflation:6,comments:''});
  renderGoals();
}

// ── INFLOWS ──────────────────────────────────────────────────────────
function renderInflows(){
  const tb=document.getElementById('inflow-tbody');
  tb.innerHTML='';
  state.inflows.forEach((r,i)=>{
    const total=(parseFloat(r.self)||0)+(parseFloat(r.spouse)||0);
    tb.innerHTML+=`<tr>
      <td>${i+1}</td>
      <td><input value="${r.particulars}" oninput="state.inflows[${i}].particulars=this.value"></td>
      <td><input type="number" value="${r.self}" oninput="state.inflows[${i}].self=parseFloat(this.value)||0;renderInflows()"></td>
      <td><input type="number" value="${r.spouse}" oninput="state.inflows[${i}].spouse=parseFloat(this.value)||0;renderInflows()"></td>
      <td class="td-calc">${fmt(total)}</td>
      <td class="td-calc">${fmt(total*12)}</td>
      <td><input type="number" value="${r.increment}" oninput="state.inflows[${i}].increment=parseFloat(this.value)||0" style="width:60px"> %</td>
      <td><button class="btn btn-danger btn-sm" onclick="state.inflows.splice(${i},1);renderInflows()">✕</button></td>
    </tr>`;
  });
  const totalIn=state.inflows.reduce((s,r)=>(parseFloat(r.self)||0)+(parseFloat(r.spouse)||0)+s,0);
  tb.innerHTML+=`<tr style="background:var(--surface2)"><td></td><td><strong>Total</strong></td><td></td><td></td><td class="td-calc"><strong>${fmt(totalIn)}</strong></td><td class="td-calc"><strong>${fmt(totalIn*12)}</strong></td><td></td><td></td></tr>`;
}
function addInflowRow(){state.inflows.push({particulars:'',self:0,spouse:0,increment:0});renderInflows();}

function renderYearlyInflows(){
  const tb=document.getElementById('yearly-inflow-tbody');
  tb.innerHTML='';
  state.yearlyInflows.forEach((r,i)=>{
    tb.innerHTML+=`<tr>
      <td>${i+1}</td>
      <td><input value="${r.particulars}" oninput="state.yearlyInflows[${i}].particulars=this.value"></td>
      <td><input type="number" value="${r.amount}" oninput="state.yearlyInflows[${i}].amount=parseFloat(this.value)||0"></td>
      <td><input type="number" value="${r.year}" oninput="state.yearlyInflows[${i}].year=parseInt(this.value)"></td>
      <td><input value="${r.comments||''}" oninput="state.yearlyInflows[${i}].comments=this.value"></td>
      <td><button class="btn btn-danger btn-sm" onclick="state.yearlyInflows.splice(${i},1);renderYearlyInflows()">✕</button></td>
    </tr>`;
  });
}
function addYearlyInflowRow(){const cur=parseInt(document.getElementById('currentYear')?.value)||2025;state.yearlyInflows.push({particulars:'',amount:0,year:cur,comments:''});renderYearlyInflows();}

// ── OUTFLOWS ──────────────────────────────────────────────────────────
function renderExpenses(){
  const tb=document.getElementById('expense-tbody');
  tb.innerHTML='';
  state.expenses.forEach((r,i)=>{
    tb.innerHTML+=`<tr>
      <td>${i+1}</td>
      <td><input value="${r.particulars}" oninput="state.expenses[${i}].particulars=this.value"></td>
      <td><input type="number" value="${r.amount}" oninput="state.expenses[${i}].amount=parseFloat(this.value)||0;renderExpenses()"></td>
      <td><input type="number" value="${r.inflation}" oninput="state.expenses[${i}].inflation=parseFloat(this.value)||0" style="width:60px"> %</td>
      <td><input value="${r.comments||''}" oninput="state.expenses[${i}].comments=this.value"></td>
      <td><button class="btn btn-danger btn-sm" onclick="state.expenses.splice(${i},1);renderExpenses()">✕</button></td>
    </tr>`;
  });
  const tot=state.expenses.reduce((s,r)=>s+(parseFloat(r.amount)||0),0);
  tb.innerHTML+=`<tr style="background:var(--surface2)"><td></td><td><strong>Total</strong></td><td class="td-calc"><strong>${fmt(tot)}</strong></td><td></td><td></td><td></td></tr>`;
}
function addExpenseRow(){state.expenses.push({particulars:'',amount:0,inflation:6,comments:''});renderExpenses();}

function renderInvestments(){
  const tb=document.getElementById('invest-tbody');
  tb.innerHTML='';
  state.investments.forEach((r,i)=>{
    tb.innerHTML+=`<tr>
      <td>${i+1}</td>
      <td><input value="${r.particulars}" oninput="state.investments[${i}].particulars=this.value"></td>
      <td><input type="number" value="${r.amount}" oninput="state.investments[${i}].amount=parseFloat(this.value)||0;renderInvestments()"></td>
      <td><input type="number" value="${r.ret}" oninput="state.investments[${i}].ret=parseFloat(this.value)||0" style="width:60px"> %</td>
      <td><input value="${r.comments||''}" oninput="state.investments[${i}].comments=this.value"></td>
      <td><button class="btn btn-danger btn-sm" onclick="state.investments.splice(${i},1);renderInvestments()">✕</button></td>
    </tr>`;
  });
  const tot=state.investments.reduce((s,r)=>s+(parseFloat(r.amount)||0),0);
  tb.innerHTML+=`<tr style="background:var(--surface2)"><td></td><td><strong>Total</strong></td><td class="td-calc"><strong>${fmt(tot)}</strong></td><td></td><td></td><td></td></tr>`;
}
function addInvestRow(){state.investments.push({particulars:'',amount:0,ret:12,comments:''});renderInvestments();}

// ── ASSETS ──────────────────────────────────────────────────────────
function renderSimpleAsset(tbodyId,arr,hasGrowth){
  const tb=document.getElementById(tbodyId);
  tb.innerHTML='';
  arr.forEach((r,i)=>{
    tb.innerHTML+=`<tr>
      <td>${i+1}</td>
      <td><input value="${r.particulars||''}" oninput="state.${tbodyId2state(tbodyId)}[${i}].particulars=this.value"></td>
      <td><input type="number" value="${r.value||0}" oninput="state.${tbodyId2state(tbodyId)}[${i}].value=parseFloat(this.value)||0"></td>
      <td><input type="number" value="${r.liability||0}" oninput="state.${tbodyId2state(tbodyId)}[${i}].liability=parseFloat(this.value)||0"></td>
      ${hasGrowth?`<td><input type="number" value="${r.growth||0}" oninput="state.${tbodyId2state(tbodyId)}[${i}].growth=parseFloat(this.value)||0" style="width:60px"> %</td>`:''}
      <td><input value="${r.comments||''}" oninput="state.${tbodyId2state(tbodyId)}[${i}].comments=this.value"></td>
      <td><button class="btn btn-danger btn-sm" onclick="state.${tbodyId2state(tbodyId)}.splice(${i},1);renderSimpleAsset('${tbodyId}',state.${tbodyId2state(tbodyId)},${hasGrowth})">✕</button></td>
    </tr>`;
  });
}
function tbodyId2state(id){return{
  'fixed-lifestyle-tbody':'fixedLifestyle',
  'fixed-invest-tbody':'fixedInvest'
}[id]||id;}
function addAssetRow(tbId){state.fixedLifestyle.push({particulars:'',value:0,liability:0,comments:''});renderSimpleAsset(tbId,state.fixedLifestyle,false);}
function addInvestAssetRow(){state.fixedInvest.push({particulars:'',value:0,liability:0,growth:0,comments:''});renderSimpleAsset('fixed-invest-tbody',state.fixedInvest,true);}

function renderFinAssets(){
  const tb=document.getElementById('fin-asset-tbody');
  tb.innerHTML='';
  state.finAssets.forEach((r,i)=>{
    tb.innerHTML+=`<tr>
      <td>${i+1}</td>
      <td><input value="${r.particulars||''}" oninput="state.finAssets[${i}].particulars=this.value" style="min-width:140px"></td>
      <td><input type="number" value="${r.value||0}" oninput="state.finAssets[${i}].value=parseFloat(this.value)||0;renderFinAssets()"></td>
      <td><input type="number" value="${r.ret||0}" oninput="state.finAssets[${i}].ret=parseFloat(this.value)||0" style="width:60px"> %</td>
      <td><select oninput="state.finAssets[${i}].category=this.value">
        ${['Equity','Hybrid','Debt','Others'].map(c=>`<option${c===r.category?' selected':''}>${c}</option>`).join('')}
      </select></td>
      <td><input value="${r.comments||''}" oninput="state.finAssets[${i}].comments=this.value"></td>
      <td><button class="btn btn-danger btn-sm" onclick="state.finAssets.splice(${i},1);renderFinAssets()">✕</button></td>
    </tr>`;
  });
  const tot=state.finAssets.reduce((s,r)=>s+(r.value||0),0);
  tb.innerHTML+=`<tr style="background:var(--surface2)"><td></td><td><strong>Total</strong></td><td class="td-calc"><strong>${fmt(tot)}</strong></td><td></td><td></td><td></td><td></td></tr>`;
}
function addFinAssetRow(){state.finAssets.push({particulars:'',value:0,ret:12,category:'Equity',comments:''});renderFinAssets();}

// ── LOANS ──────────────────────────────────────────────────────────
function renderLoans(){
  const tb=document.getElementById('loans-tbody');
  tb.innerHTML='';
  state.loans.forEach((r,i)=>{
    tb.innerHTML+=`<tr>
      <td>${i+1}</td>
      <td><input value="${r.particulars||''}" oninput="state.loans[${i}].particulars=this.value"></td>
      <td><input value="${r.lender||''}" oninput="state.loans[${i}].lender=this.value"></td>
      <td><input type="number" value="${r.startYr||2020}" oninput="state.loans[${i}].startYr=parseInt(this.value)" style="width:70px"></td>
      <td><input type="number" value="${r.endYr||2030}" oninput="state.loans[${i}].endYr=parseInt(this.value)" style="width:70px"></td>
      <td><input type="number" value="${r.emi||0}" oninput="state.loans[${i}].emi=parseFloat(this.value)||0;renderLoans()"></td>
      <td><input type="number" value="${r.rate||0}" oninput="state.loans[${i}].rate=parseFloat(this.value)||0" style="width:60px"> %</td>
      <td><input type="number" value="${r.outstanding||0}" oninput="state.loans[${i}].outstanding=parseFloat(this.value)||0;renderLoans()"></td>
      <td><button class="btn btn-danger btn-sm" onclick="state.loans.splice(${i},1);renderLoans()">✕</button></td>
    </tr>`;
  });
  const tot=state.loans.reduce((s,r)=>s+(r.outstanding||0),0);
  tb.innerHTML+=`<tr style="background:var(--surface2)"><td></td><td><strong>Total</strong></td><td></td><td></td><td></td><td class="td-calc"><strong>${fmt(state.loans.reduce((s,r)=>s+(r.emi||0),0))}</strong></td><td></td><td class="td-calc"><strong>${fmt(tot)}</strong></td><td></td></tr>`;
}
function addLoanRow(){state.loans.push({particulars:'',lender:'',startYr:2020,endYr:2030,emi:0,rate:8.5,outstanding:0});renderLoans();}

// ── INSURANCE ──────────────────────────────────────────────────────────
function renderInsurance(){
  const tb=document.getElementById('ins-tbody');
  tb.innerHTML='';
  state.insurance.forEach((r,i)=>{
    tb.innerHTML+=`<tr>
      <td>${i+1}</td>
      <td><input value="${r.name||''}" oninput="state.insurance[${i}].name=this.value" style="min-width:120px"></td>
      <td><select oninput="state.insurance[${i}].type=this.value">
        ${['Term','ULIP','Endowment','Health','Pension','Others'].map(t=>`<option${t===(r.type||'Term')?' selected':''}>${t}</option>`).join('')}
      </select></td>
      <td><input value="${r.insured||''}" oninput="state.insurance[${i}].insured=this.value" style="width:90px"></td>
      <td><input type="number" value="${r.sumAssured||0}" oninput="state.insurance[${i}].sumAssured=parseFloat(this.value)||0"></td>
      <td><input type="number" value="${r.premium||0}" oninput="state.insurance[${i}].premium=parseFloat(this.value)||0;renderInsurance()"></td>
      <td><input type="number" value="${r.startYr||2020}" oninput="state.insurance[${i}].startYr=parseInt(this.value)" style="width:65px"></td>
      <td><input type="number" value="${r.endYr||2035}" oninput="state.insurance[${i}].endYr=parseInt(this.value)" style="width:65px"></td>
      <td><input type="number" value="${r.maturity||0}" oninput="state.insurance[${i}].maturity=parseFloat(this.value)||0"></td>
      <td><span class="pill pill-on">Active</span></td>
      <td><button class="btn btn-danger btn-sm" onclick="state.insurance.splice(${i},1);renderInsurance()">✕</button></td>
    </tr>`;
  });
  const totPrem=state.insurance.reduce((s,r)=>s+(r.premium||0),0);
  if(state.insurance.length) tb.innerHTML+=`<tr style="background:var(--surface2)"><td></td><td><strong>Total</strong></td><td></td><td></td><td></td><td class="td-calc"><strong>${fmt(totPrem)}</strong></td><td></td><td></td><td></td><td></td><td></td></tr>`;
}
function addInsuranceRow(){state.insurance.push({name:'',type:'Term',insured:'Self',sumAssured:0,premium:0,startYr:2024,endYr:2034,maturity:0});renderInsurance();}

// ── CASH FLOW ──────────────────────────────────────────────────────────
function getTotals(){
  const monthlyIn=state.inflows.reduce((s,r)=>(parseFloat(r.self)||0)+(parseFloat(r.spouse)||0)+s,0);
  const monthlyExp=state.expenses.reduce((s,r)=>s+(parseFloat(r.amount)||0),0);
  const monthlyInv=state.investments.reduce((s,r)=>s+(parseFloat(r.amount)||0),0);
  const monthlyOut=monthlyExp+monthlyInv;
  const loanEMI=state.loans.reduce((s,r)=>s+(parseFloat(r.emi)||0),0);
  const totalOut=monthlyOut+loanEMI;
  return{monthlyIn,monthlyExp,monthlyInv,totalOut,surplus:monthlyIn-totalOut};
}

function renderCashFlow(){
  const t=getTotals();
  document.getElementById('cf-annual-in').textContent=fmt(t.monthlyIn*12);
  document.getElementById('cf-annual-out').textContent=fmt(t.totalOut*12);
  document.getElementById('cf-annual-surplus').textContent=fmt(t.surplus*12);

  const cur=parseInt(document.getElementById('currentYear')?.value)||2025;
  const retireYr=parseInt(document.getElementById('retireYear')?.value)||2038;
  const years=retireYr-cur;
  const tb=document.getElementById('cf-tbody');
  tb.innerHTML='';

  let opening=0;
  const avgInfAsset=state.finAssets.length?state.finAssets.reduce((s,r)=>s+(r.ret||0),0)/state.finAssets.length:7;

  for(let y=0;y<Math.min(years,40);y++){
    const yr=cur+y;
    const inflow=t.monthlyIn*12*Math.pow(1.08,y);
    const outflow=t.totalOut*12*Math.pow(1.06,y);
    const surplus=inflow-outflow;
    const growth=opening*(avgInfAsset/100);
    const closing=opening+surplus+growth;
    const color=closing>=0?'var(--accent2)':'var(--danger)';
    tb.innerHTML+=`<tr>
      <td>${yr}</td>
      <td class="td-num">${fmt(opening)}</td>
      <td class="td-num" style="color:var(--accent2)">${fmt(inflow)}</td>
      <td class="td-num" style="color:var(--danger)">${fmt(outflow)}</td>
      <td class="td-num" style="color:${surplus>=0?'var(--accent2)':'var(--danger)'}">${fmt(surplus)}</td>
      <td class="td-num" style="color:var(--accent)">${fmt(growth)}</td>
      <td class="td-num" style="color:${color}"><strong>${fmt(closing)}</strong></td>
      <td style="text-align:right"><span class="tag ${closing>=0?'tag-green':'tag-red'}">${closing>=0?'Surplus':'Deficit'}</span></td>
    </tr>`;
    opening=closing;
  }
}

// ── POST RETIREMENT ──────────────────────────────────────────────────────────
function calcRetirementCF(){
  const corpus=parseFloat(document.getElementById('retireCorpus').value)||0;
  const expense=parseFloat(document.getElementById('retireExpense').value)||0;
  const rent=parseFloat(document.getElementById('retireRent').value)||0;
  const ret=(parseFloat(document.getElementById('retireReturn').value)||7)/100;
  const inf=(parseFloat(document.getElementById('retireInflation').value)||6)/100;
  const lifeExp=parseInt(document.getElementById('lifeExpect').value)||85;
  const retireYr=parseInt(document.getElementById('retireYear')?.value)||2038;
  const selfDob=document.getElementById('selfDob')?.value||'1980-01-01';
  const retireAge=parseInt(document.getElementById('retireAge')?.value)||58;
  const years=lifeExp-retireAge;

  const tb=document.getElementById('retire-tbody');
  tb.innerHTML='';
  let opening=corpus;

  for(let y=0;y<Math.min(years,50);y++){
    const age=retireAge+y;
    const yr=retireYr+y;
    const rentY=rent*12*Math.pow(1.04,y);
    const expY=expense*12*Math.pow(1+inf,y);
    const surplus=rentY-expY;
    const growth=opening*(ret/1);
    const closing=opening+surplus+growth;
    const color=closing>=0?'var(--accent2)':'var(--danger)';
    tb.innerHTML+=`<tr>
      <td>${yr}</td>
      <td>${age}</td>
      <td class="td-num">${fmt(opening)}</td>
      <td class="td-num" style="color:var(--accent2)">${fmt(rentY)}</td>
      <td class="td-num" style="color:var(--danger)">${fmt(expY)}</td>
      <td class="td-num" style="color:${surplus>=0?'var(--accent2)':'var(--danger)'}">${fmt(surplus)}</td>
      <td class="td-num" style="color:var(--accent)">${fmt(growth)}</td>
      <td class="td-num" style="color:${color}"><strong>${fmt(closing)}</strong></td>
    </tr>`;
    opening=closing;
    if(closing<0&&y>2)break;
  }
}

// ── PORTFOLIO ──────────────────────────────────────────────────────────
function renderPortfolio(){
  const cats={Equity:0,Hybrid:0,Debt:0,Others:0};
  state.finAssets.forEach(r=>{
    const c=r.category||'Others';
    cats[c]=(cats[c]||0)+(r.value||0);
  });
  const total=Object.values(cats).reduce((a,b)=>a+b,0)||1;
  document.getElementById('pf-equity').textContent=fmt(cats.Equity);
  document.getElementById('pf-hybrid').textContent=fmt(cats.Hybrid);
  document.getElementById('pf-debt').textContent=fmt(cats.Debt);
  document.getElementById('pf-others').textContent=fmt(cats.Others);
  document.getElementById('pf-equity-pct').textContent=(cats.Equity/total*100).toFixed(1)+'% of portfolio';
  document.getElementById('pf-hybrid-pct').textContent=(cats.Hybrid/total*100).toFixed(1)+'% of portfolio';
  document.getElementById('pf-debt-pct').textContent=(cats.Debt/total*100).toFixed(1)+'% of portfolio';
  document.getElementById('pf-others-pct').textContent=(cats.Others/total*100).toFixed(1)+'% of portfolio';

  const colors={Equity:'var(--accent)',Hybrid:'var(--gold)',Debt:'var(--accent2)',Others:'var(--muted)'};
  document.getElementById('alloc-bars').innerHTML=Object.entries(cats).map(([cat,val])=>`
    <div class="progress-row">
      <div class="progress-label"><span>${cat}</span><span style="font-family:'DM Mono',monospace">${fmt(val)} · ${(val/total*100).toFixed(1)}%</span></div>
      <div class="progress-track"><div class="progress-fill" style="width:${(val/total*100)}%;background:${colors[cat]}"></div></div>
    </div>`).join('');

  const tb=document.getElementById('pf-detail-tbody');
  tb.innerHTML=state.finAssets.filter(r=>r.particulars||r.value).map(r=>`<tr>
    <td>${r.particulars||'—'}</td>
    <td class="td-num">${fmt(r.value||0)}</td>
    <td><span class="tag tag-${r.category==='Equity'?'blue':r.category==='Debt'?'green':r.category==='Hybrid'?'gold':'blue'}">${r.category}</span></td>
    <td class="td-num">${(r.ret||0).toFixed(1)}%</td>
  </tr>`).join('') || '<tr><td colspan="4" style="color:var(--muted);text-align:center;padding:20px">No financial assets added yet</td></tr>';
}

// ── DASHBOARD ──────────────────────────────────────────────────────────
function updateDashboard(){
  const t=getTotals();
  document.getElementById('kpi-inflow').textContent=fmt(t.monthlyIn);
  document.getElementById('kpi-outflow').textContent=fmt(t.totalOut);
  document.getElementById('kpi-surplus').textContent=fmt(t.surplus);

  const totalAssets=state.fixedLifestyle.reduce((s,r)=>s+(r.value||0),0)
    +state.fixedInvest.reduce((s,r)=>s+(r.value||0),0)
    +state.finAssets.reduce((s,r)=>s+(r.value||0),0);
  const totalLiab=state.loans.reduce((s,r)=>s+(r.outstanding||0),0);
  document.getElementById('kpi-assets').textContent=fmt(totalAssets);
  document.getElementById('kpi-liabilities').textContent=fmt(totalLiab);
  document.getElementById('kpi-networth').textContent=fmt(totalAssets-totalLiab);

  // bar chart
  const maxVal=Math.max(t.monthlyIn,t.totalOut,Math.abs(t.surplus))||1;
  document.getElementById('bar-in').style.width=(t.monthlyIn/maxVal*100)+'%';
  document.getElementById('bar-out').style.width=(t.totalOut/maxVal*100)+'%';
  document.getElementById('bar-net').style.width=(Math.abs(t.surplus)/maxVal*100)+'%';
  document.getElementById('bv-in').textContent=fmt(t.monthlyIn);
  document.getElementById('bv-out').textContent=fmt(t.totalOut);
  document.getElementById('bv-net').textContent=fmt(t.surplus);

  // goals
  const gp=document.getElementById('goals-progress');
  if(state.goals.length){
    const cur=parseInt(document.getElementById('currentYear')?.value)||2025;
    gp.innerHTML=state.goals.slice(0,5).map(g=>{
      const yr=parseInt(g.targetYear)||cur;
      const yrs=Math.max(yr-cur,0);
      const prog=Math.min(100,yrs>0?((1-(yrs/(yr-cur+1)))*100):100);
      return `<div class="progress-row">
        <div class="progress-label"><span>${g.name||'Goal'}</span><span style="font-family:'DM Mono',monospace">${fmt(g.fv||g.cost||0)} · ${yr}</span></div>
        <div class="progress-track"><div class="progress-fill" style="width:${100-prog}%"></div></div>
      </div>`;
    }).join('');
  } else {
    gp.innerHTML='<div style="color:var(--muted);font-size:13px">No goals added yet. Go to Goals section →</div>';
  }

  // family summary
  const fs=document.getElementById('family-summary');
  const selfName=document.getElementById('selfName')?.value||'Self';
  const spouseName=document.getElementById('spouseName')?.value;
  let familyHtml=`<div style="display:flex;flex-wrap:wrap;gap:10px;align-items:center">`;
  familyHtml+=`<div style="background:var(--surface2);border:1px solid var(--border);border-radius:10px;padding:10px 16px;display:flex;align-items:center;gap:8px">
    <span style="font-size:18px">👤</span>
    <div><div style="font-size:13px;font-weight:600;color:var(--text)">${selfName||'Self'}</div><div style="font-size:11px;color:var(--muted)">Primary Member</div></div>
  </div>`;
  if(spouseName){
    familyHtml+=`<div style="background:var(--surface2);border:1px solid var(--border);border-radius:10px;padding:10px 16px;display:flex;align-items:center;gap:8px">
      <span style="font-size:18px">👤</span>
      <div><div style="font-size:13px;font-weight:600;color:var(--text)">${spouseName}</div><div style="font-size:11px;color:var(--muted)">Spouse</div></div>
    </div>`;
  }
  state.children.forEach(c=>{
    const age=calcChildAge(c.dob);
    familyHtml+=`<div style="background:var(--surface2);border:1px solid var(--border);border-radius:10px;padding:10px 16px;display:flex;align-items:center;gap:8px">
      <span style="font-size:18px">🧒</span>
      <div><div style="font-size:13px;font-weight:600;color:var(--text)">${c.name||'Child'}</div><div style="font-size:11px;color:var(--muted)">Age ${age} · ${c.gender||'—'}</div></div>
    </div>`;
  });
  if(!spouseName&&!state.children.length){
    familyHtml+=`<span style="color:var(--muted);font-size:13px">Fill in About You to see family members here.</span>`;
  }
  familyHtml+='</div>';
  fs.innerHTML=familyHtml;

  // insurance
  const is=document.getElementById('ins-summary');
  if(state.insurance.length){
    is.innerHTML=state.insurance.map(r=>`<span class="tag tag-blue" style="margin:3px">${r.name||'Policy'} · ${r.type}</span>`).join('');
  } else {
    is.innerHTML='<span style="color:var(--muted);font-size:13px">No insurance policies added.</span>';
  }
}

function savePage(page){
  if(page==='about'){
    state.about.currentYear=parseInt(document.getElementById('currentYear').value)||2025;
    state.about.selfName=document.getElementById('selfName').value;
    state.about.selfDob=document.getElementById('selfDob').value;
    state.about.retireAge=parseInt(document.getElementById('retireAge').value)||58;
    state.about.retireYear=parseInt(document.getElementById('retireYear').value)||2038;
  }
}

function saveData(){
  try{localStorage.setItem('finplan_state',JSON.stringify(state));alert('Data saved locally!');}
  catch(e){alert('Saved in memory (localStorage unavailable)');}
}

function exportToExcel(){
  const wb = XLSX.utils.book_new();
  const fy = parseInt(document.getElementById('fy-select')?.value)||2025;
  const selfName = document.getElementById('selfName')?.value||'Self';
  const t = getTotals();
  const cur = fy;
  const retireYr = parseInt(document.getElementById('retireYear')?.value)||2038;

  // ── helpers ──
  function sheet(data){ return XLSX.utils.aoa_to_sheet(data); }
  function addSheet(name, data){
    const ws = sheet(data);
    // style column widths
    ws['!cols'] = Array(15).fill({wch:20});
    XLSX.utils.book_append_sheet(wb, ws, name);
  }

  // colour helpers — cell style objects
  const hdrFill = {patternType:'solid', fgColor:{rgb:'1F3864'}};
  const subFill  = {patternType:'solid', fgColor:{rgb:'2E75B6'}};
  const inputFill= {patternType:'solid', fgColor:{rgb:'DEEAF1'}};
  const calcFill = {patternType:'solid', fgColor:{rgb:'E2EFDA'}};
  const boldW    = {bold:true,color:{rgb:'FFFFFF'}};
  const boldB    = {bold:true,color:{rgb:'000000'}};
  const inputFont= {color:{rgb:'0000FF'}};
  const calcFont = {color:{rgb:'008000'}};

  // ── 1. ABOUT YOU ──────────────────────────────────────────────────
  const selfDob = document.getElementById('selfDob')?.value||'';
  const spouseName = document.getElementById('spouseName')?.value||'';
  const spouseDob  = document.getElementById('spouseDob')?.value||'';
  const retireAge  = document.getElementById('retireAge')?.value||58;
  const riskScore  = document.getElementById('riskScore')?.value||5;
  const aouRows = [
    ['ABOUT YOU & FAMILY','','','','',''],
    [''],
    ['Current Year', fy, 'Last Planning Year', parseInt(fy)-1, 'Risk Score', riskScore],
    [''],
    ['SELF','','','','',''],
    ['Name','Date of Birth','PAN','Retirement Age','Retirement Year',''],
    [selfName, selfDob, document.getElementById('selfPan')?.value||'', retireAge, retireYr, ''],
    [''],
    ['SPOUSE / PARTNER','','','','',''],
    ['Name','Date of Birth','PAN','','',''],
    [spouseName, spouseDob, document.getElementById('spousePan')?.value||'','','',''],
    [''],
    ['CHILDREN','','','','','','',''],
    ['#','Name','Date of Birth','Age','Gender','Education Goal Year','Marriage Goal Year','Comments'],
    ...state.children.map((c,i)=>[i+1,c.name,c.dob,calcChildAge(c.dob),c.gender,c.eduYear,c.marYear,c.comments]),
    ...(state.children.length===0?[['—','No children added','','','','','','']]:[])
  ];
  addSheet('About You', aouRows);

  // ── 2. GOALS ──────────────────────────────────────────────────────
  const goalsRows = [
    ['FINANCIAL GOALS','','','','','',''],
    [''],
    ['#','Goal Name',"Today's Cost (₹)",'Target Year','Inflation %','Future Value (₹)','Comments'],
    ...state.goals.map((g,i)=>{
      const periods=Math.max((parseInt(g.targetYear)||cur)-cur,0);
      const fv=g.cost*Math.pow(1+(parseFloat(g.inflation)||0)/100,periods);
      return [i+1,g.name,g.cost,g.targetYear,g.inflation,Math.round(fv),g.comments];
    }),
    [''],
    ['','Total',state.goals.reduce((s,g)=>s+(g.cost||0),0),'','',
      state.goals.reduce((s,g)=>{
        const p=Math.max((parseInt(g.targetYear)||cur)-cur,0);
        return s+g.cost*Math.pow(1+(parseFloat(g.inflation)||0)/100,p);
      },0).toFixed(0),'']
  ];
  addSheet('Goals', goalsRows);

  // ── 3. INFLOWS ────────────────────────────────────────────────────
  const inflowRows = [
    ['MONTHLY INCOME / INFLOWS','','','','',''],
    [''],
    ['#','Particulars','Self (₹/mo)','Spouse (₹/mo)','Total Monthly (₹)','Annual (₹)','Increment %'],
    ...state.inflows.map((r,i)=>{
      const tot=(parseFloat(r.self)||0)+(parseFloat(r.spouse)||0);
      return [i+1,r.particulars,r.self,r.spouse,tot,tot*12,r.increment];
    }),
    ['','TOTAL',
      state.inflows.reduce((s,r)=>s+(parseFloat(r.self)||0),0),
      state.inflows.reduce((s,r)=>s+(parseFloat(r.spouse)||0),0),
      t.monthlyIn, t.monthlyIn*12,''],
    [''],
    ['YEARLY / ONE-TIME INFLOWS','','','',''],
    ['#','Particulars','Amount (₹)','Year','Comments'],
    ...state.yearlyInflows.map((r,i)=>[i+1,r.particulars,r.amount,r.year,r.comments]),
    ...(state.yearlyInflows.length===0?[['—','None','','','']]:[])
  ];
  addSheet('Inflows', inflowRows);

  // ── 4. OUTFLOWS ───────────────────────────────────────────────────
  const outflowRows = [
    ['MONTHLY EXPENSES & INVESTMENTS','','','',''],
    [''],
    ['EXPENSES','','','',''],
    ['#','Particulars','Monthly Amount (₹)','Annual (₹)','Inflation %','Comments'],
    ...state.expenses.map((r,i)=>[i+1,r.particulars,r.amount,r.amount*12,r.inflation,r.comments||'']),
    ['','TOTAL',
      state.expenses.reduce((s,r)=>s+(parseFloat(r.amount)||0),0),
      state.expenses.reduce((s,r)=>s+(parseFloat(r.amount)||0),0)*12,'',''],
    [''],
    ['INVESTMENTS / SAVINGS','','','',''],
    ['#','Particulars','Monthly Amount (₹)','Annual (₹)','Expected Return %','Comments'],
    ...state.investments.map((r,i)=>[i+1,r.particulars,r.amount,r.amount*12,r.ret,r.comments||'']),
    ['','TOTAL',
      state.investments.reduce((s,r)=>s+(parseFloat(r.amount)||0),0),
      state.investments.reduce((s,r)=>s+(parseFloat(r.amount)||0),0)*12,'',''],
    [''],
    ['LOAN EMIs','','',''],
    ['#','Particulars','Monthly EMI (₹)','Annual (₹)'],
    ...state.loans.map((r,i)=>[i+1,r.particulars,r.emi,r.emi*12]),
    ['','TOTAL EMI',state.loans.reduce((s,r)=>s+(parseFloat(r.emi)||0),0),
      state.loans.reduce((s,r)=>s+(parseFloat(r.emi)||0),0)*12]
  ];
  addSheet('Outflows', outflowRows);

  // ── 5. ASSETS ─────────────────────────────────────────────────────
  const assetRows = [
    ['ASSETS','','','','',''],
    [''],
    ['FIXED ASSETS – LIFESTYLE','','','',''],
    ['#','Particulars',"Today's Value (₹)",'Liability (₹)','Comments'],
    ...state.fixedLifestyle.map((r,i)=>[i+1,r.particulars,r.value,r.liability,r.comments||'']),
    ...(state.fixedLifestyle.length===0?[['—','None','0','0','']]:[]),
    [''],
    ['FIXED ASSETS – INVESTMENTS','','','','',''],
    ['#','Particulars',"Today's Value (₹)",'Liability (₹)','Growth % p.a.','Comments'],
    ...state.fixedInvest.map((r,i)=>[i+1,r.particulars,r.value,r.liability,r.growth,r.comments||'']),
    ...(state.fixedInvest.length===0?[['—','None','0','0','0','']]:[]),
    [''],
    ['FINANCIAL ASSETS (MF / STOCKS / FD)','','','','',''],
    ['#','Particulars',"Today's Value (₹)",'Expected Return %','Category','Comments'],
    ...state.finAssets.map((r,i)=>[i+1,r.particulars,r.value,r.ret,r.category,r.comments||'']),
    [''],
    ['','TOTAL FINANCIAL ASSETS',state.finAssets.reduce((s,r)=>s+(r.value||0),0),'','',''],
    ['','TOTAL LIABILITIES',state.loans.reduce((s,r)=>s+(r.outstanding||0),0),'','',''],
    ['','NET WORTH',
      state.finAssets.reduce((s,r)=>s+(r.value||0),0)+
      state.fixedLifestyle.reduce((s,r)=>s+(r.value||0),0)+
      state.fixedInvest.reduce((s,r)=>s+(r.value||0),0)-
      state.loans.reduce((s,r)=>s+(r.outstanding||0),0),'','','']
  ];
  addSheet('Assets', assetRows);

  // ── 6. LOAN DETAILS ───────────────────────────────────────────────
  const loanRows = [
    ['LOAN DETAILS / LIABILITIES','','','','','','',''],
    [''],
    ['#','Particulars','Lender','Start Year','End Year','Monthly EMI (₹)','Interest Rate %','Outstanding Amount (₹)'],
    ...state.loans.map((r,i)=>[i+1,r.particulars,r.lender,r.startYr,r.endYr,r.emi,r.rate,r.outstanding]),
    ...(state.loans.length===0?[['—','No loans','','','','0','','0']]:[]),
    [''],
    ['','TOTAL','','','',
      state.loans.reduce((s,r)=>s+(parseFloat(r.emi)||0),0),'',
      state.loans.reduce((s,r)=>s+(parseFloat(r.outstanding)||0),0)]
  ];
  addSheet('Loan Details', loanRows);

  // ── 7. INSURANCE ──────────────────────────────────────────────────
  const insRows = [
    ['INSURANCE POLICIES','','','','','','','',''],
    [''],
    ['#','Plan Name','Type','Insured','Sum Assured (₹)','Annual Premium (₹)','Start Year','End Year','Maturity Value (₹)'],
    ...state.insurance.map((r,i)=>[i+1,r.name,r.type,r.insured,r.sumAssured,r.premium,r.startYr,r.endYr,r.maturity]),
    ...(state.insurance.length===0?[['—','No policies','','','','0','','','']]:[]),
    [''],
    ['','TOTAL ANNUAL PREMIUM','','','',state.insurance.reduce((s,r)=>s+(parseFloat(r.premium)||0),0)*('yearly'),'','','']
  ];
  addSheet('Insurance', insRows);

  // ── 8. CASH FLOW SUMMARY ──────────────────────────────────────────
  const avgRet = state.finAssets.length ? state.finAssets.reduce((s,r)=>s+(r.ret||0),0)/state.finAssets.length : 7;
  let opening = 0;
  const cfData = [
    ['CASH FLOW SUMMARY','','','','','','',''],
    [''],
    ['Year','Opening Balance (₹)','Inflow (₹)','Outflow (₹)','Surplus (₹)','Portfolio Growth (₹)','Closing Balance (₹)','Status']
  ];
  for(let y=0; y<Math.min(retireYr-cur,40); y++){
    const yr=cur+y;
    const inflow=t.monthlyIn*12*Math.pow(1.08,y);
    const outflow=t.totalOut*12*Math.pow(1.06,y);
    const surplus=inflow-outflow;
    const growth=opening*(avgRet/100);
    const closing=opening+surplus+growth;
    cfData.push([yr,Math.round(opening),Math.round(inflow),Math.round(outflow),Math.round(surplus),Math.round(growth),Math.round(closing),closing>=0?'Surplus':'Deficit']);
    opening=closing;
  }
  addSheet('CashFlow Summary', cfData);

  // ── 9. POST RETIREMENT ────────────────────────────────────────────
  const corpus   = parseFloat(document.getElementById('retireCorpus')?.value)||0;
  const retExp   = parseFloat(document.getElementById('retireExpense')?.value)||0;
  const retRent  = parseFloat(document.getElementById('retireRent')?.value)||0;
  const retRet   = (parseFloat(document.getElementById('retireReturn')?.value)||7)/100;
  const retInf   = (parseFloat(document.getElementById('retireInflation')?.value)||6)/100;
  const lifeExp  = parseInt(document.getElementById('lifeExpect')?.value)||85;
  const retAge   = parseInt(retireAge)||58;
  let retOpening = corpus;
  const prData = [
    ['POST RETIREMENT CASH FLOW','','','','','','',''],
    [''],
    [`Corpus at Retirement: ₹${corpus.toLocaleString('en-IN')}`, `Monthly Expenses: ₹${retExp.toLocaleString('en-IN')}`, `Rental Income: ₹${retRent.toLocaleString('en-IN')}`, `Portfolio Return: ${retRet*100}%`, `Inflation: ${retInf*100}%`, `Life Expectancy: ${lifeExp}`, '', ''],
    [''],
    ['Year','Age','Opening Balance (₹)','Rent Income (₹)','Expenses (₹)','Surplus (₹)','Portfolio Growth (₹)','Closing Balance (₹)']
  ];
  for(let y=0; y<lifeExp-retAge; y++){
    const age=retAge+y; const yr=retireYr+y;
    const rentY=retRent*12*Math.pow(1.04,y);
    const expY=retExp*12*Math.pow(1+retInf,y);
    const surplus=rentY-expY;
    const growth=retOpening*retRet;
    const closing=retOpening+surplus+growth;
    prData.push([yr,age,Math.round(retOpening),Math.round(rentY),Math.round(expY),Math.round(surplus),Math.round(growth),Math.round(closing)]);
    retOpening=closing;
    if(closing<0&&y>2) break;
  }
  addSheet('Post Retirement', prData);

  // ── 10. PORTFOLIO ANALYSIS ────────────────────────────────────────
  const cats={Equity:0,Hybrid:0,Debt:0,Others:0};
  state.finAssets.forEach(r=>{ const c=r.category||'Others'; cats[c]=(cats[c]||0)+(r.value||0); });
  const totPF=Object.values(cats).reduce((a,b)=>a+b,0)||1;
  const pfData = [
    ['PORTFOLIO ANALYSIS','','','',''],
    [''],
    ['Category','Value (₹)','% of Portfolio','',''],
    ['Equity', cats.Equity, (cats.Equity/totPF*100).toFixed(1)+'%','',''],
    ['Hybrid',  cats.Hybrid,  (cats.Hybrid/totPF*100).toFixed(1)+'%','',''],
    ['Debt',    cats.Debt,    (cats.Debt/totPF*100).toFixed(1)+'%','',''],
    ['Others',  cats.Others,  (cats.Others/totPF*100).toFixed(1)+'%','',''],
    ['TOTAL',   totPF,        '100%','',''],
    [''],
    ['FINANCIAL ASSETS DETAIL','','','',''],
    ['Particulars',"Today's Value (₹)",'Category','Return %','Comments'],
    ...state.finAssets.filter(r=>r.particulars||r.value).map(r=>[r.particulars,r.value,r.category,r.ret,r.comments||''])
  ];
  addSheet('Portfolio Analysis', pfData);

  // ── WRITE & DOWNLOAD ──────────────────────────────────────────────
  const fname=`FinPlan_${selfName.replace(/\s/g,'_')}_FY${fy}-${fy+1}.xlsx`;
  XLSX.writeFile(wb, fname);
}

// keep old name for any stale references
function exportSummary(){ exportToExcel(); }

// ── INIT ──────────────────────────────────────────────────────────
(function init(){
  // Pre-populate with 3 default goals
  state.goals=[
    {name:'Retirement',cost:0,targetYear:2038,inflation:6,comments:'Primary retirement goal'},
    {name:'Child Education',cost:0,targetYear:2032,inflation:8,comments:'Higher education fund'},
    {name:'Marriage',cost:0,targetYear:2035,inflation:7,comments:''}
  ];
  renderChildren();
  renderGoals();
  renderInflows();
  renderYearlyInflows();
  renderExpenses();
  renderInvestments();
  renderSimpleAsset('fixed-lifestyle-tbody',state.fixedLifestyle,false);
  renderSimpleAsset('fixed-invest-tbody',state.fixedInvest,true);
  renderFinAssets();
  renderLoans();
  renderInsurance();
  updateDashboard();
})();
</script>
</body>
</html>
