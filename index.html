<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#123c33">
  <title>FreightFlow CRM</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Manrope:wght@600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="app-shell">
    <aside class="sidebar">
      <div class="brand">
        <div class="brand-mark" aria-hidden="true">
          <svg viewBox="0 0 40 40"><path d="M8 12h16l8 8-8 8H8l8-8-8-8Z"/><path d="m18 12 8 8-8 8"/></svg>
        </div>
        <div><strong>FreightFlow</strong><span>Sales CRM</span></div>
      </div>
      <nav aria-label="Main navigation">
        <button class="nav-item active" data-view="dashboard">
          <svg viewBox="0 0 24 24"><path d="M4 4h6v6H4zM14 4h6v6h-6zM4 14h6v6H4zM14 14h6v6h-6z"/></svg>
          Dashboard
        </button>
        <button class="nav-item" data-view="customers">
          <svg viewBox="0 0 24 24"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2M9 11a4 4 0 1 0 0-8 4 4 0 0 0 0 8ZM22 21v-2a4 4 0 0 0-3-3.87M16 3.13a4 4 0 0 1 0 7.75"/></svg>
          Customers
        </button>
        <button class="nav-item" data-view="followups">
          <svg viewBox="0 0 24 24"><path d="M12 8v4l3 2M21 12a9 9 0 1 1-3-6.7M21 3v6h-6"/></svg>
          Follow-ups
          <span class="nav-badge" id="followupNavBadge">0</span>
        </button>
      </nav>
      <div class="sidebar-foot">
        <p>Your sales data stays on this computer.</p>
        <button class="text-button" id="exportBtn">Export backup</button>
        <label class="text-button import-label">Import backup<input type="file" id="importInput" accept=".csv"></label>
      </div>
    </aside>

    <main>
      <header class="topbar">
        <button class="mobile-menu" id="mobileMenu" aria-label="Open menu">☰</button>
        <div class="search-wrap">
          <svg viewBox="0 0 24 24"><circle cx="11" cy="11" r="7"/><path d="m20 20-4-4"/></svg>
          <input id="globalSearch" type="search" placeholder="Search customers, contacts, lanes...">
        </div>
        <button class="primary-button" id="addCustomerBtn"><span>＋</span> Add customer</button>
      </header>

      <section class="content">
        <div class="view active" id="dashboardView">
          <div class="page-heading">
            <div><p class="eyebrow" id="dateGreeting"></p><h1>Sales overview</h1><p>Stay close to every opportunity and keep freight moving.</p></div>
          </div>
          <div class="metric-grid">
            <article class="metric-card">
              <div class="metric-icon green"><svg viewBox="0 0 24 24"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2M9 11a4 4 0 1 0 0-8 4 4 0 0 0 0 8ZM22 21v-2a4 4 0 0 0-3-3.87"/></svg></div>
              <span>Total prospects</span><strong id="totalProspects">0</strong><small id="prospectTrend">Build your pipeline</small>
            </article>
            <article class="metric-card">
              <div class="metric-icon blue"><svg viewBox="0 0 24 24"><path d="M3 20h18M5 17l4-5 4 3 6-9M16 6h3v3"/></svg></div>
              <span>Annual volume</span><strong id="totalVolume">0</strong><small>TEU / shipments in pipeline</small>
            </article>
            <article class="metric-card urgent">
              <div class="metric-icon coral"><svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M12 7v6M12 17h.01"/></svg></div>
              <span>Needs attention</span><strong id="overdueCount">0</strong><small>Overdue follow-ups</small>
            </article>
            <article class="metric-card">
              <div class="metric-icon amber"><svg viewBox="0 0 24 24"><rect x="3" y="5" width="18" height="16" rx="2"/><path d="M16 3v4M8 3v4M3 10h18"/></svg></div>
              <span>Due this week</span><strong id="weekCount">0</strong><small>Follow-ups in next 7 days</small>
            </article>
          </div>

          <div class="dashboard-grid">
            <article class="panel followup-panel">
              <div class="panel-head"><div><h2>Next follow-ups</h2><p>Your most time-sensitive conversations</p></div><button class="link-button" data-go="followups">View all →</button></div>
              <div id="followupList" class="followup-list"></div>
            </article>
            <article class="panel volume-panel">
              <div class="panel-head"><div><h2>Volume by status</h2><p>Annual opportunity mix</p></div></div>
              <div id="volumeChart" class="volume-chart"></div>
            </article>
          </div>

          <article class="panel recent-panel">
            <div class="panel-head"><div><h2>Recently added</h2><p>Your newest freight opportunities</p></div><button class="link-button" data-go="customers">All customers →</button></div>
            <div class="table-wrap"><table><thead><tr><th>Customer</th><th>Lane</th><th>Annual volume</th><th>Status</th><th>Next follow-up</th><th></th></tr></thead><tbody id="recentTable"></tbody></table></div>
          </article>
        </div>

        <div class="view" id="customersView">
          <div class="page-heading row">
            <div><p class="eyebrow">YOUR PIPELINE</p><h1>Customers</h1><p>Every prospect, contact, and trade lane in one place.</p></div>
            <button class="primary-button desktop-only" data-add>＋ Add customer</button>
          </div>
          <div class="toolbar panel">
            <div class="filter-group">
              <button class="filter-chip active" data-filter="All">All <span id="allCount">0</span></button>
              <button class="filter-chip" data-filter="Prospect">Prospects</button>
              <button class="filter-chip" data-filter="Qualified">Qualified</button>
              <button class="filter-chip" data-filter="Customer">Customers</button>
            </div>
            <select id="sortSelect" aria-label="Sort customers">
              <option value="followup">Next follow-up</option>
              <option value="newest">Recently added</option>
              <option value="volume">Highest volume</option>
              <option value="name">Customer name</option>
            </select>
          </div>
          <article class="panel customer-table-panel">
            <div class="table-wrap"><table><thead><tr><th>Customer & contact</th><th>Trade lane</th><th>Origins → destinations</th><th>Annual volume</th><th>Status</th><th>Next follow-up</th><th></th></tr></thead><tbody id="customerTable"></tbody></table></div>
            <div id="emptyCustomers" class="empty-state hidden"><div class="empty-icon">⌕</div><h3>No customers found</h3><p>Try a different search or add a new prospect.</p></div>
          </article>
        </div>

        <div class="view" id="followupsView">
          <div class="page-heading"><div><p class="eyebrow">STAY ON COURSE</p><h1>Follow-ups</h1><p>A focused list of every conversation that needs your attention.</p></div></div>
          <div class="followup-columns">
            <section class="followup-column"><div class="column-title overdue-title"><span></span><h2>Overdue</h2><b id="overdueLabel">0</b></div><div id="overdueCards" class="card-stack"></div></section>
            <section class="followup-column"><div class="column-title today-title"><span></span><h2>Today</h2><b id="todayLabel">0</b></div><div id="todayCards" class="card-stack"></div></section>
            <section class="followup-column"><div class="column-title upcoming-title"><span></span><h2>Upcoming</h2><b id="upcomingLabel">0</b></div><div id="upcomingCards" class="card-stack"></div></section>
          </div>
        </div>
      </section>
    </main>
  </div>

  <div class="modal-backdrop hidden" id="customerModal">
    <section class="modal" role="dialog" aria-modal="true" aria-labelledby="modalTitle">
      <div class="modal-head"><div><p class="eyebrow">CUSTOMER RECORD</p><h2 id="modalTitle">Add a customer</h2></div><button class="icon-button" data-close aria-label="Close">×</button></div>
      <form id="customerForm">
        <input type="hidden" id="customerId">
        <div class="form-section"><h3>Company & contact</h3>
          <div class="form-grid">
            <label class="span-2">Customer name *<input id="customerName" required placeholder="e.g. Acme Manufacturing"></label>
            <label>Contact name<input id="contactName" placeholder="Full name"></label>
            <label>Status<select id="status"><option>Prospect</option><option>Qualified</option><option>Customer</option><option>On hold</option></select></label>
            <label>Email<input id="email" type="email" placeholder="name@company.com"></label>
            <label>Phone number<input id="phone" type="tel" placeholder="+1 312 555 0123"></label>
          </div>
        </div>
        <div class="form-section"><h3>Freight opportunity</h3>
          <div class="form-grid">
            <label class="span-2">Lane<input id="lane" placeholder="e.g. Transpacific Eastbound"></label>
            <label>Country/countries of origin<input id="origins" placeholder="China, Vietnam"></label>
            <label>Destination/s<input id="destinations" placeholder="United States, Canada"></label>
            <label>Annual volume<input id="annualVolume" type="number" min="0" step="1" placeholder="e.g. 1200"></label>
            <label>Volume unit<select id="volumeUnit"><option>TEU</option><option>Shipments</option><option>Containers</option><option>Tons</option><option>Kg</option></select></label>
          </div>
        </div>
        <div class="form-section"><h3>Next step</h3>
          <div class="form-grid">
            <label>Next follow-up date *<input id="followupDate" type="date" required></label>
            <label class="span-2">Notes<textarea id="notes" rows="3" placeholder="Add context, rates discussed, or next action..."></textarea></label>
          </div>
        </div>
        <div class="modal-actions"><button type="button" class="secondary-button" data-close>Cancel</button><button type="submit" class="primary-button">Save customer</button></div>
      </form>
    </section>
  </div>

  <div class="modal-backdrop hidden" id="deleteModal">
    <section class="confirm-modal" role="alertdialog" aria-modal="true">
      <div class="danger-icon">!</div><h2>Delete this customer?</h2><p>This removes the customer and follow-up from this computer.</p>
      <div class="modal-actions"><button class="secondary-button" data-delete-cancel>Cancel</button><button class="danger-button" id="confirmDelete">Delete customer</button></div>
    </section>
  </div>
  <div class="toast" id="toast" role="status"></div>
  <script src="workbook-prospects.js"></script>
  <script src="app.js"></script>
</body>
</html>
