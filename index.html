import { useState } from "react";

// ─── Brand & Theme ────────────────────────────────────────────────────────────
const B = {
  bg: "#0B1120",
  surface: "#111827",
  card: "#1A2438",
  cardHover: "#1F2D45",
  border: "#243454",
  accent: "#00D4A8",
  accentDark: "#00A882",
  accentGlow: "rgba(0,212,168,0.15)",
  gold: "#F5A623",
  goldDark: "#D4891A",
  danger: "#F43F5E",
  warning: "#FBBF24",
  success: "#10B981",
  text: "#F1F5F9",
  muted: "#64748B",
  soft: "#94A3B8",
};

// ─── Market Config ─────────────────────────────────────────────────────────────
const MARKETS = {
  NG: { flag: "🇳🇬", name: "Nigeria", currency: "₦", code: "NGN", city: "Lagos", whatsapp: "+234" },
  KE: { flag: "🇰🇪", name: "Kenya", currency: "KSh", code: "KES", city: "Nairobi", whatsapp: "+254" },
};

// ─── Demo Practice ─────────────────────────────────────────────────────────────
const PRACTICE = {
  name: "SmileCare Dental Clinic",
  owner: "Dr. Amara Okonkwo",
  address: "14 Victoria Island, Lagos, Nigeria",
  market: "NG",
  plan: "Growth",
  staff: 6,
};

// ─── Demo Data ────────────────────────────────────────────────────────────────
const STAFF = [
  { id: 1, name: "Chioma Eze", role: "Dental Nurse", avatar: "CE", color: "#6366F1" },
  { id: 2, name: "Emeka Adeyemi", role: "Receptionist", avatar: "EA", color: "#EC4899" },
  { id: 3, name: "Fatima Bello", role: "Dental Nurse", avatar: "FB", color: "#F59E0B" },
  { id: 4, name: "Dr. Amara Okonkwo", role: "Principal Dentist", avatar: "AO", color: "#00D4A8" },
];

const JOBS = [
  { id: "j1", cat: "🔓 Opening", text: "Key secured, alarm deactivated", role: "Nurse" },
  { id: "j2", cat: "🔓 Opening", text: "Generator checked and fuelled", role: "Nurse" },
  { id: "j3", cat: "🔓 Opening", text: "Reception area cleaned and ready", role: "Receptionist" },
  { id: "j4", cat: "🔓 Opening", text: "Appointment diary reviewed", role: "Receptionist" },
  { id: "j5", cat: "🔓 Opening", text: "Treatment trays set per diary", role: "Nurse" },
  { id: "j6", cat: "🦺 PPE & Infection", text: "PPE protocol followed — mask, gloves, apron", role: "Nurse" },
  { id: "j7", cat: "🦺 PPE & Infection", text: "Dental chair water bottle disinfected", role: "Nurse" },
  { id: "j8", cat: "🦺 PPE & Infection", text: "Autoclave cycle run and validated", role: "Nurse" },
  { id: "j9", cat: "🦺 PPE & Infection", text: "All surfaces decontaminated", role: "Nurse" },
  { id: "j10", cat: "🧪 Materials", text: "Stock levels checked and logged", role: "Nurse" },
  { id: "j11", cat: "🧪 Materials", text: "Compressor and suction checked", role: "Nurse" },
  { id: "j12", cat: "🧪 Materials", text: "Emergency kit checked — contents and expiry", role: "Nurse" },
  { id: "j13", cat: "🤝 Patient Experience", text: "Waiting area refreshed and stocked", role: "Receptionist" },
  { id: "j14", cat: "🤝 Patient Experience", text: "WhatsApp confirmations sent to today's patients", role: "Receptionist" },
  { id: "j15", cat: "🤝 Patient Experience", text: "Deposit status confirmed for all bookings", role: "Receptionist" },
  { id: "j16", cat: "🔒 Closing", text: "All clinical areas decontaminated", role: "Nurse" },
  { id: "j17", cat: "🔒 Closing", text: "Autoclave final cycle logged", role: "Nurse" },
  { id: "j18", cat: "🔒 Closing", text: "Cash reconciled and secured", role: "Receptionist" },
  { id: "j19", cat: "🔒 Closing", text: "Generator switched off", role: "Nurse" },
  { id: "j20", cat: "🔒 Closing", text: "Premises locked and alarm set", role: "Receptionist" },
];

const CATEGORIES = [...new Set(JOBS.map(j => j.cat))];

const APPOINTMENTS = [
  { id: 1, time: "08:30", patient: "Kemi Adeyemi", type: "Examination", deposit: 5000, paid: true, phone: "+234 801 234 5678" },
  { id: 2, time: "09:15", patient: "Chukwuemeka Obi", type: "Scale & Polish", deposit: 3000, paid: true, phone: "+234 802 345 6789" },
  { id: 3, time: "10:00", patient: "Blessing Nwosu", type: "Composite Filling", deposit: 8000, paid: false, phone: "+234 803 456 7890" },
  { id: 4, time: "11:00", patient: "Taiwo Afolabi", type: "Teeth Whitening", deposit: 15000, paid: true, phone: "+234 804 567 8901" },
  { id: 5, time: "12:00", patient: "Grace Mensah", type: "Crown Fitting", deposit: 20000, paid: true, phone: "+234 805 678 9012" },
  { id: 6, time: "14:00", patient: "Olumide Bakare", type: "Extraction", deposit: 6000, paid: false, phone: "+234 806 789 0123" },
  { id: 7, time: "15:30", patient: "Ngozi Okonkwo", type: "New Patient Exam", deposit: 5000, paid: true, phone: "+234 807 890 1234" },
];

const COMPLIANCE = [
  { id: 1, item: "MDCN Registration", status: "compliant", expiry: "2026-06-30", cat: "Registration" },
  { id: 2, item: "Infection Control Audit", status: "compliant", expiry: "2025-12-01", cat: "Clinical" },
  { id: 3, item: "Fire Safety Certificate", status: "review", expiry: "2025-11-15", cat: "Safety" },
  { id: 4, item: "Staff BVN Verification", status: "compliant", expiry: "2026-01-01", cat: "HR" },
  { id: 5, item: "Waste Disposal Contract", status: "overdue", expiry: "2025-09-01", cat: "Environmental" },
  { id: 6, item: "Autoclave Validation Log", status: "compliant", expiry: "2026-03-01", cat: "Equipment" },
  { id: 7, item: "CPR Training — All Staff", status: "review", expiry: "2025-10-30", cat: "Training" },
];

const WEEKLY = [
  { day: "Mon", rev: 42000 }, { day: "Tue", rev: 68000 },
  { day: "Wed", rev: 35000 }, { day: "Thu", rev: 81000 },
  { day: "Fri", rev: 54000 }, { day: "Sat", rev: 29000 },
];

const fmt = (n, market = "NG") => `${MARKETS[market].currency}${n.toLocaleString()}`;

// ─── Shared Components ────────────────────────────────────────────────────────

const Badge = ({ children, type = "default" }) => {
  const map = {
    default: { bg: "#1E3A5F22", color: B.soft },
    success: { bg: "#064E3B33", color: B.success },
    warning: { bg: "#45330033", color: B.warning },
    danger: { bg: "#4C0519aa", color: B.danger },
    accent: { bg: B.accentGlow, color: B.accent },
    gold: { bg: "#78350F33", color: B.gold },
  };
  const c = map[type] || map.default;
  return (
    <span style={{
      background: c.bg, color: c.color,
      padding: "3px 10px", borderRadius: 20,
      fontSize: 11, fontWeight: 700,
      letterSpacing: "0.05em", textTransform: "uppercase", whiteSpace: "nowrap",
    }}>{children}</span>
  );
};

const Card = ({ children, style = {}, onClick, glow }) => (
  <div onClick={onClick} style={{
    background: B.card,
    border: `1px solid ${glow ? B.accent + "44" : B.border}`,
    borderRadius: 16, padding: 20,
    boxShadow: glow ? `0 0 24px ${B.accentGlow}` : "none",
    transition: "all 0.2s",
    cursor: onClick ? "pointer" : "default",
    ...style,
  }}
    onMouseEnter={e => { if (onClick) { e.currentTarget.style.background = B.cardHover; e.currentTarget.style.borderColor = B.accent + "66"; } }}
    onMouseLeave={e => { if (onClick) { e.currentTarget.style.background = B.card; e.currentTarget.style.borderColor = glow ? B.accent + "44" : B.border; } }}
  >{children}</div>
);

const KPI = ({ label, value, sub, accent, icon, gold }) => (
  <Card glow={accent}>
    <div style={{ display: "flex", justifyContent: "space-between", alignItems: "flex-start" }}>
      <div>
        <div style={{ color: B.muted, fontSize: 11, fontWeight: 700, letterSpacing: "0.08em", textTransform: "uppercase", marginBottom: 8 }}>{label}</div>
        <div style={{ fontSize: 26, fontWeight: 900, lineHeight: 1, color: gold ? B.gold : accent ? B.accent : B.text }}>{value}</div>
        {sub && <div style={{ color: B.muted, fontSize: 12, marginTop: 6 }}>{sub}</div>}
      </div>
      <span style={{ fontSize: 26, opacity: 0.6 }}>{icon}</span>
    </div>
  </Card>
);

const Bar = ({ value, max, color = B.accent, height = 6 }) => (
  <div style={{ background: B.border, borderRadius: 99, height, overflow: "hidden" }}>
    <div style={{ width: `${Math.min(100, (value / max) * 100)}%`, height: "100%", background: color, borderRadius: 99, transition: "width 0.6s ease" }} />
  </div>
);

const Input = ({ label, value, onChange, placeholder, type = "text" }) => (
  <div>
    <label style={{ color: B.muted, fontSize: 11, fontWeight: 700, letterSpacing: "0.07em", textTransform: "uppercase", display: "block", marginBottom: 6 }}>{label}</label>
    <input type={type} value={value} onChange={onChange} placeholder={placeholder} style={{
      width: "100%", background: B.surface, border: `1px solid ${B.border}`,
      borderRadius: 10, padding: "11px 14px", color: B.text, fontSize: 14,
      outline: "none", boxSizing: "border-box", fontFamily: "inherit",
    }}
      onFocus={e => e.target.style.borderColor = B.accent}
      onBlur={e => e.target.style.borderColor = B.border}
    />
  </div>
);

const Btn = ({ children, onClick, full, variant = "primary", small }) => {
  const styles = {
    primary: { background: `linear-gradient(135deg, ${B.accent}, #0096FF)`, color: "#fff", border: "none", boxShadow: `0 4px 20px ${B.accentGlow}` },
    ghost: { background: "transparent", color: B.accent, border: `1px solid ${B.accent}44` },
    gold: { background: `linear-gradient(135deg, ${B.gold}, ${B.goldDark})`, color: "#fff", border: "none", boxShadow: "0 4px 16px rgba(245,166,35,0.3)" },
    danger: { background: B.danger + "22", color: B.danger, border: `1px solid ${B.danger}44` },
  };
  return (
    <button onClick={onClick} style={{
      ...styles[variant],
      borderRadius: 10, padding: small ? "8px 16px" : "12px 22px",
      fontWeight: 700, fontSize: small ? 12 : 14, cursor: "pointer",
      width: full ? "100%" : "auto", fontFamily: "inherit", letterSpacing: "0.03em",
      transition: "opacity 0.2s",
    }}
      onMouseEnter={e => e.currentTarget.style.opacity = "0.85"}
      onMouseLeave={e => e.currentTarget.style.opacity = "1"}
    >{children}</button>
  );
};

// ─── Views ────────────────────────────────────────────────────────────────────

const Dashboard = ({ setView, market }) => {
  const M = MARKETS[market];
  const paidToday = APPOINTMENTS.filter(a => a.paid).length;
  const pendingDeposits = APPOINTMENTS.filter(a => !a.paid).length;
  const todayRevenue = APPOINTMENTS.filter(a => a.paid).reduce((s, a) => s + a.deposit, 0);
  const monthlyTarget = market === "NG" ? 1200000 : 85000;
  const collected = market === "NG" ? 820000 : 58000;

  return (
    <div style={{ display: "flex", flexDirection: "column", gap: 20 }}>
      {/* Header */}
      <div style={{ display: "flex", justifyContent: "space-between", alignItems: "flex-start", flexWrap: "wrap", gap: 12 }}>
        <div>
          <div style={{ color: B.muted, fontSize: 13, marginBottom: 4 }}>
            {new Date().toLocaleDateString("en-GB", { weekday: "long", day: "numeric", month: "long", year: "numeric" })}
            <span style={{ marginLeft: 10 }}>{M.flag} {M.city}</span>
          </div>
          <h2 style={{ color: B.text, fontSize: 24, fontWeight: 900, margin: 0 }}>Good morning, Dr. Okonkwo 👋</h2>
          <p style={{ color: B.muted, fontSize: 13, margin: "4px 0 0" }}>SmileCare Dental Clinic · {M.name}</p>
        </div>
        <Btn onClick={() => setView("prebooking")} gold>+ New Booking</Btn>
      </div>

      {/* KPIs */}
      <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fit, minmax(180px, 1fr))", gap: 12 }}>
        <KPI label="Today's Patients" value={APPOINTMENTS.length} sub={`${paidToday} confirmed`} accent icon="📅" />
        <KPI label="Deposits Pending" value={pendingDeposits} sub="WhatsApp chase needed" icon="💬" />
        <KPI label="Today's Revenue" value={fmt(todayRevenue, market)} sub="Deposits collected" icon="💰" gold />
        <KPI label="Staff Jobs" value={`8/${JOBS.length}`} sub="Completed today" icon="✅" />
      </div>

      {/* Monthly target */}
      <Card glow>
        <div style={{ display: "flex", justifyContent: "space-between", marginBottom: 14 }}>
          <div style={{ color: B.text, fontWeight: 700 }}>Monthly Revenue Target</div>
          <Badge type="accent">March 2026</Badge>
        </div>
        <Bar value={collected} max={monthlyTarget} />
        <div style={{ display: "flex", justifyContent: "space-between", marginTop: 10 }}>
          <span style={{ color: B.accent, fontWeight: 800 }}>{fmt(collected, market)} collected</span>
          <span style={{ color: B.muted, fontSize: 13 }}>Target: {fmt(monthlyTarget, market)}</span>
        </div>
        {/* Mini chart */}
        <div style={{ marginTop: 20, display: "flex", gap: 8, alignItems: "flex-end", height: 70 }}>
          {WEEKLY.map(d => {
            const max = Math.max(...WEEKLY.map(x => x.rev));
            const h = (d.rev / max) * 60;
            return (
              <div key={d.day} style={{ flex: 1, display: "flex", flexDirection: "column", alignItems: "center", gap: 5 }}>
                <div style={{ width: "100%", height: h, background: `linear-gradient(180deg, ${B.accent}, ${B.accentDark})`, borderRadius: "5px 5px 0 0" }} />
                <span style={{ color: B.muted, fontSize: 11, fontWeight: 600 }}>{d.day}</span>
              </div>
            );
          })}
        </div>
      </Card>

      {/* Today's appointments */}
      <Card>
        <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: 14 }}>
          <div style={{ color: B.text, fontWeight: 700 }}>Today's Schedule</div>
          <span onClick={() => setView("appointments")} style={{ color: B.accent, fontSize: 13, cursor: "pointer", fontWeight: 600 }}>View all →</span>
        </div>
        <div style={{ display: "flex", flexDirection: "column", gap: 8 }}>
          {APPOINTMENTS.slice(0, 5).map(a => (
            <div key={a.id} style={{
              display: "flex", alignItems: "center", justifyContent: "space-between",
              padding: "11px 14px", background: B.surface, borderRadius: 10,
              borderLeft: `3px solid ${a.paid ? B.accent : B.warning}`,
            }}>
              <div style={{ display: "flex", gap: 12, alignItems: "center" }}>
                <span style={{ color: B.accent, fontWeight: 800, fontSize: 13, minWidth: 44 }}>{a.time}</span>
                <div>
                  <div style={{ color: B.text, fontWeight: 600, fontSize: 14 }}>{a.patient}</div>
                  <div style={{ color: B.muted, fontSize: 12 }}>{a.type}</div>
                </div>
              </div>
              <div style={{ display: "flex", alignItems: "center", gap: 8 }}>
                <span style={{ color: B.muted, fontSize: 12 }}>{fmt(a.deposit, market)}</span>
                <Badge type={a.paid ? "success" : "warning"}>{a.paid ? "Paid" : "Pending"}</Badge>
              </div>
            </div>
          ))}
        </div>
      </Card>

      {/* Quick actions */}
      <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fit, minmax(140px, 1fr))", gap: 10 }}>
        {[
          { label: "DentTrack", icon: "✅", view: "denttrack" },
          { label: "Compliance", icon: "🛡️", view: "compliance" },
          { label: "Financials", icon: "📊", view: "finance" },
          { label: "WhatsApp", icon: "💬", view: "whatsapp" },
        ].map(a => (
          <Card key={a.view} onClick={() => setView(a.view)} style={{ padding: "16px", textAlign: "center" }}>
            <div style={{ fontSize: 26, marginBottom: 8 }}>{a.icon}</div>
            <div style={{ color: B.text, fontWeight: 700, fontSize: 13 }}>{a.label}</div>
          </Card>
        ))}
      </div>
    </div>
  );
};

const DentTrack = () => {
  const [done, setDone] = useState(new Set(["j1", "j2", "j3", "j6", "j7", "j13", "j14", "j15"]));
  const [taskText, setTaskText] = useState("");
  const [assignTo, setAssignTo] = useState(null);
  const [tasks, setTasks] = useState([
    { id: "t1", text: "Order more gloves — stock critically low", to: 1, deadline: "12:00", done: false },
    { id: "t2", text: "Call Blessing Nwosu re: unpaid deposit", to: 2, deadline: "09:30", done: false },
  ]);

  const toggle = id => setDone(p => { const n = new Set(p); n.has(id) ? n.delete(id) : n.add(id); return n; });
  const pct = Math.round((done.size / JOBS.length) * 100);

  return (
    <div style={{ display: "flex", flexDirection: "column", gap: 20 }}>
      <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center" }}>
        <div>
          <h2 style={{ color: B.text, fontSize: 22, fontWeight: 900, margin: 0 }}>DentTrack</h2>
          <p style={{ color: B.muted, fontSize: 13, margin: "4px 0 0" }}>Staff accountability & daily checklists</p>
        </div>
        <div style={{ textAlign: "right" }}>
          <div style={{ color: B.accent, fontSize: 34, fontWeight: 900, lineHeight: 1 }}>{pct}%</div>
          <div style={{ color: B.muted, fontSize: 12 }}>{done.size}/{JOBS.length} complete</div>
        </div>
      </div>

      <Card glow>
        <div style={{ display: "flex", justifyContent: "space-between", marginBottom: 10 }}>
          <span style={{ color: B.text, fontWeight: 600 }}>Today's Progress</span>
          <span style={{ color: done.size === JOBS.length ? B.success : B.accent, fontWeight: 700 }}>
            {done.size === JOBS.length ? "✅ All done!" : `${JOBS.length - done.size} remaining`}
          </span>
        </div>
        <Bar value={done.size} max={JOBS.length} color={done.size === JOBS.length ? B.success : B.accent} height={8} />
      </Card>

      {/* Team */}
      <Card>
        <div style={{ color: B.text, fontWeight: 700, marginBottom: 14 }}>Team On Duty</div>
        <div style={{ display: "flex", gap: 10, flexWrap: "wrap" }}>
          {STAFF.map(s => (
            <div key={s.id} style={{ display: "flex", alignItems: "center", gap: 10, background: B.surface, padding: "10px 14px", borderRadius: 10 }}>
              <div style={{ width: 34, height: 34, borderRadius: "50%", background: s.color, display: "flex", alignItems: "center", justifyContent: "center", color: "#fff", fontWeight: 800, fontSize: 12 }}>{s.avatar}</div>
              <div>
                <div style={{ color: B.text, fontWeight: 600, fontSize: 13 }}>{s.name}</div>
                <div style={{ color: B.muted, fontSize: 11 }}>{s.role}</div>
              </div>
              <div style={{ width: 8, height: 8, borderRadius: "50%", background: B.success, boxShadow: `0 0 6px ${B.success}` }} />
            </div>
          ))}
        </div>
      </Card>

      {/* Jobs by category */}
      {CATEGORIES.map(cat => {
        const catJobs = JOBS.filter(j => j.cat === cat);
        const catDone = catJobs.filter(j => done.has(j.id)).length;
        return (
          <Card key={cat}>
            <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: 14 }}>
              <span style={{ color: B.text, fontWeight: 700, fontSize: 15 }}>{cat}</span>
              <Badge type={catDone === catJobs.length ? "success" : "default"}>{catDone}/{catJobs.length}</Badge>
            </div>
            <div style={{ display: "flex", flexDirection: "column", gap: 8 }}>
              {catJobs.map(job => {
                const isDone = done.has(job.id);
                return (
                  <div key={job.id} onClick={() => toggle(job.id)} style={{
                    display: "flex", alignItems: "center", gap: 12,
                    padding: "11px 14px", borderRadius: 10, cursor: "pointer",
                    background: isDone ? "#052E1C" : B.surface,
                    border: `1px solid ${isDone ? "#065F46" : "transparent"}`,
                    transition: "all 0.15s",
                  }}>
                    <div style={{
                      width: 22, height: 22, borderRadius: 6, flexShrink: 0,
                      border: `2px solid ${isDone ? B.success : B.border}`,
                      background: isDone ? B.success : "transparent",
                      display: "flex", alignItems: "center", justifyContent: "center",
                      transition: "all 0.15s",
                    }}>{isDone && <span style={{ color: "#fff", fontSize: 12 }}>✓</span>}</div>
                    <span style={{ flex: 1, color: isDone ? B.muted : B.text, fontSize: 14, textDecoration: isDone ? "line-through" : "none" }}>{job.text}</span>
                    <Badge type="default">{job.role}</Badge>
                  </div>
                );
              })}
            </div>
          </Card>
        );
      })}

      {/* Task assign */}
      <Card>
        <div style={{ color: B.text, fontWeight: 700, marginBottom: 14 }}>Assign a Task</div>
        <div style={{ display: "flex", gap: 8, marginBottom: 14, flexWrap: "wrap" }}>
          {STAFF.map(s => (
            <div key={s.id} onClick={() => setAssignTo(s.id === assignTo ? null : s.id)} style={{
              padding: "8px 14px", borderRadius: 8, cursor: "pointer", fontWeight: 600, fontSize: 13,
              background: assignTo === s.id ? B.accent : B.surface,
              color: assignTo === s.id ? "#fff" : B.text,
              transition: "all 0.15s",
            }}>{s.name.split(" ")[0]}</div>
          ))}
        </div>
        <div style={{ display: "flex", gap: 10 }}>
          <input value={taskText} onChange={e => setTaskText(e.target.value)} onKeyDown={e => e.key === "Enter" && taskText.trim() && assignTo && (setTasks(p => [...p, { id: `t${Date.now()}`, text: taskText, to: assignTo, deadline: "17:00", done: false }]), setTaskText(""), setAssignTo(null))} placeholder="Describe the task..." style={{ flex: 1, background: B.surface, border: `1px solid ${B.border}`, borderRadius: 10, padding: "11px 14px", color: B.text, fontSize: 14, outline: "none", fontFamily: "inherit" }} />
          <Btn onClick={() => { if (taskText.trim() && assignTo) { setTasks(p => [...p, { id: `t${Date.now()}`, text: taskText, to: assignTo, deadline: "17:00", done: false }]); setTaskText(""); setAssignTo(null); } }}>Assign</Btn>
        </div>
        {tasks.length > 0 && (
          <div style={{ marginTop: 14, display: "flex", flexDirection: "column", gap: 8 }}>
            {tasks.map(t => {
              const s = STAFF.find(x => x.id === t.to);
              return (
                <div key={t.id} style={{ display: "flex", alignItems: "center", gap: 12, padding: "11px 14px", background: B.surface, borderRadius: 10 }}>
                  <div onClick={() => setTasks(p => p.map(x => x.id === t.id ? { ...x, done: !x.done } : x))} style={{ width: 20, height: 20, borderRadius: 5, border: `2px solid ${t.done ? B.success : B.border}`, background: t.done ? B.success : "transparent", cursor: "pointer", display: "flex", alignItems: "center", justifyContent: "center", flexShrink: 0 }}>
                    {t.done && <span style={{ color: "#fff", fontSize: 11 }}>✓</span>}
                  </div>
                  <span style={{ flex: 1, color: t.done ? B.muted : B.text, fontSize: 14, textDecoration: t.done ? "line-through" : "none" }}>{t.text}</span>
                  {s && <div style={{ width: 26, height: 26, borderRadius: "50%", background: s.color, display: "flex", alignItems: "center", justifyContent: "center", color: "#fff", fontSize: 10, fontWeight: 800 }}>{s.avatar}</div>}
                  <span style={{ color: B.muted, fontSize: 12 }}>{t.deadline}</span>
                </div>
              );
            })}
          </div>
        )}
      </Card>
    </div>
  );
};

const Appointments = ({ market }) => (
  <div style={{ display: "flex", flexDirection: "column", gap: 20 }}>
    <h2 style={{ color: B.text, fontSize: 22, fontWeight: 900, margin: 0 }}>Appointments</h2>
    <div style={{ display: "grid", gridTemplateColumns: "repeat(3,1fr)", gap: 12 }}>
      <KPI label="Total Today" value={APPOINTMENTS.length} icon="📅" />
      <KPI label="Confirmed" value={APPOINTMENTS.filter(a => a.paid).length} accent icon="✅" />
      <KPI label="Deposits Pending" value={APPOINTMENTS.filter(a => !a.paid).length} icon="⚠️" />
    </div>
    <Card>
      <div style={{ display: "flex", flexDirection: "column", gap: 10 }}>
        {APPOINTMENTS.map(a => (
          <div key={a.id} style={{
            display: "flex", alignItems: "center", justifyContent: "space-between",
            padding: "14px 16px", background: B.surface, borderRadius: 12,
            borderLeft: `4px solid ${a.paid ? B.accent : B.warning}`,
          }}>
            <div style={{ display: "flex", gap: 14, alignItems: "center" }}>
              <span style={{ color: B.accent, fontWeight: 800, minWidth: 46 }}>{a.time}</span>
              <div>
                <div style={{ color: B.text, fontWeight: 700 }}>{a.patient}</div>
                <div style={{ color: B.muted, fontSize: 12 }}>{a.type} · {a.phone}</div>
              </div>
            </div>
            <div style={{ display: "flex", gap: 10, alignItems: "center" }}>
              <span style={{ color: B.muted, fontSize: 13 }}>{fmt(a.deposit, market)}</span>
              <Badge type={a.paid ? "success" : "warning"}>{a.paid ? "Paid" : "Pending"}</Badge>
            </div>
          </div>
        ))}
      </div>
    </Card>
  </div>
);

const PreBooking = ({ market }) => {
  const M = MARKETS[market];
  const [form, setForm] = useState({ name: "", phone: "", email: "", date: "", time: "", type: "", deposit: "5000" });
  const [sent, setSent] = useState(false);
  const treatments = [
    { label: "Examination", deposit: market === "NG" ? "5000" : "800" },
    { label: "Scale & Polish", deposit: market === "NG" ? "3000" : "500" },
    { label: "Composite Filling", deposit: market === "NG" ? "8000" : "1200" },
    { label: "Teeth Whitening", deposit: market === "NG" ? "15000" : "2500" },
    { label: "Crown Fitting", deposit: market === "NG" ? "20000" : "3500" },
    { label: "Extraction", deposit: market === "NG" ? "6000" : "1000" },
  ];

  if (sent) return (
    <div style={{ display: "flex", flexDirection: "column", gap: 20 }}>
      <Card style={{ textAlign: "center", padding: 48 }} glow>
        <div style={{ fontSize: 52, marginBottom: 16 }}>✅</div>
        <h3 style={{ color: B.accent, fontSize: 20, fontWeight: 800, margin: "0 0 12px" }}>Booking Request Sent!</h3>
        <div style={{ background: B.surface, borderRadius: 12, padding: 16, margin: "16px 0", textAlign: "left" }}>
          <div style={{ display: "flex", alignItems: "center", gap: 10, marginBottom: 10 }}>
            <span style={{ fontSize: 20 }}>💬</span>
            <span style={{ color: B.text, fontWeight: 600 }}>WhatsApp sent to {form.phone}</span>
          </div>
          <div style={{ color: B.muted, fontSize: 13, lineHeight: 1.6, fontStyle: "italic" }}>
            "Hi {form.name}, your appointment at SmileCare Dental on {form.date} at {form.time} is reserved. Please pay your deposit of {M.currency}{form.deposit} to confirm: [payment link] — SmileCare Dental"
          </div>
        </div>
        <div style={{ background: B.surface, borderRadius: 12, padding: 16, textAlign: "left", marginBottom: 20 }}>
          <div style={{ display: "flex", alignItems: "center", gap: 10, marginBottom: 10 }}>
            <span style={{ fontSize: 20 }}>📧</span>
            <span style={{ color: B.text, fontWeight: 600 }}>Email sent to {form.email || "patient"}</span>
          </div>
          <div style={{ color: B.muted, fontSize: 13 }}>Booking confirmation with Stripe payment link attached</div>
        </div>
        <div style={{ color: B.muted, fontSize: 13, marginBottom: 20 }}>
          Routed via <span style={{ color: B.accent, fontWeight: 600 }}>n8n automation</span> — translation, WhatsApp, email and logging handled automatically
        </div>
        <Btn full onClick={() => { setSent(false); setForm({ name: "", phone: "", email: "", date: "", time: "", type: "", deposit: treatments[0].deposit }); }}>New Booking</Btn>
      </Card>
    </div>
  );

  return (
    <div style={{ display: "flex", flexDirection: "column", gap: 20 }}>
      <div>
        <h2 style={{ color: B.text, fontSize: 22, fontWeight: 900, margin: 0 }}>Pre-Booking & Deposit</h2>
        <p style={{ color: B.muted, fontSize: 13, margin: "4px 0 0" }}>Automated via n8n · WhatsApp + Email + Stripe</p>
      </div>
      <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: 12 }}>
        <KPI label="Confirmed Today" value={APPOINTMENTS.filter(a => a.paid).length} accent icon="✅" />
        <KPI label="Pending Deposits" value={APPOINTMENTS.filter(a => !a.paid).length} icon="⏳" />
      </div>
      <Card>
        <div style={{ color: B.text, fontWeight: 700, fontSize: 15, marginBottom: 18 }}>New Booking Request</div>
        <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: 14 }}>
          <Input label="Patient Name" value={form.name} onChange={e => setForm(p => ({ ...p, name: e.target.value }))} placeholder="Full name" />
          <Input label={`WhatsApp (${M.whatsapp})`} value={form.phone} onChange={e => setForm(p => ({ ...p, phone: e.target.value }))} placeholder={M.whatsapp + " 800 000 0000"} />
          <Input label="Email Address" value={form.email} onChange={e => setForm(p => ({ ...p, email: e.target.value }))} placeholder="patient@email.com" />
          <Input label="Appointment Date" value={form.date} onChange={e => setForm(p => ({ ...p, date: e.target.value }))} type="date" />
          <Input label="Appointment Time" value={form.time} onChange={e => setForm(p => ({ ...p, time: e.target.value }))} type="time" />
          <div>
            <label style={{ color: B.muted, fontSize: 11, fontWeight: 700, letterSpacing: "0.07em", textTransform: "uppercase", display: "block", marginBottom: 6 }}>Treatment Type</label>
            <select value={form.type} onChange={e => { const t = treatments.find(x => x.label === e.target.value); setForm(p => ({ ...p, type: e.target.value, deposit: t ? t.deposit : p.deposit })); }} style={{ width: "100%", background: B.surface, border: `1px solid ${B.border}`, borderRadius: 10, padding: "11px 14px", color: form.type ? B.text : B.muted, fontSize: 14, outline: "none", boxSizing: "border-box", fontFamily: "inherit" }}>
              <option value="">Select treatment</option>
              {treatments.map(t => <option key={t.label} value={t.label}>{t.label}</option>)}
            </select>
          </div>
        </div>

        <div style={{ marginTop: 16, padding: "14px 18px", background: B.surface, borderRadius: 12, display: "flex", justifyContent: "space-between", alignItems: "center" }}>
          <div>
            <div style={{ color: B.muted, fontSize: 11, fontWeight: 700, letterSpacing: "0.06em", textTransform: "uppercase" }}>Deposit Amount</div>
            <div style={{ color: B.gold, fontSize: 28, fontWeight: 900 }}>{M.currency}{parseInt(form.deposit || 0).toLocaleString()}</div>
          </div>
          <div style={{ display: "flex", flexDirection: "column", gap: 6 }}>
            <div style={{ display: "flex", alignItems: "center", gap: 8, color: B.muted, fontSize: 13 }}><span>💬</span> WhatsApp via n8n</div>
            <div style={{ display: "flex", alignItems: "center", gap: 8, color: B.muted, fontSize: 13 }}><span>📧</span> Email via Gmail</div>
            <div style={{ display: "flex", alignItems: "center", gap: 8, color: B.muted, fontSize: 13 }}><span>💳</span> Stripe payment link</div>
          </div>
        </div>

        <div style={{ marginTop: 14 }}>
          <Btn full onClick={() => form.name && form.phone && setSent(true)}>Send Booking & Deposit Request →</Btn>
        </div>
      </Card>
    </div>
  );
};

const WhatsApp = ({ market }) => {
  const M = MARKETS[market];
  const [sent, setSent] = useState(new Set());
  const pending = APPOINTMENTS.filter(a => !a.paid);

  const templates = [
    { id: "deposit", label: "Deposit Reminder", icon: "💳", msg: (p) => `Hi ${p.patient.split(" ")[0]}, this is a reminder to pay your deposit of ${M.currency}${p.deposit.toLocaleString()} to confirm your appointment at SmileCare Dental on ${p.time} today. Pay here: [link]` },
    { id: "confirm", label: "Appointment Confirmation", icon: "✅", msg: (p) => `Hi ${p.patient.split(" ")[0]}, your appointment at SmileCare Dental today at ${p.time} is confirmed. Please arrive 5 minutes early. See you soon! 😊` },
    { id: "reminder", label: "24hr Reminder", icon: "⏰", msg: (p) => `Hi ${p.patient.split(" ")[0]}, just a reminder you have an appointment at SmileCare Dental tomorrow. Reply YES to confirm or call us to reschedule.` },
  ];

  return (
    <div style={{ display: "flex", flexDirection: "column", gap: 20 }}>
      <div>
        <h2 style={{ color: B.text, fontSize: 22, fontWeight: 900, margin: 0 }}>WhatsApp Automation</h2>
        <p style={{ color: B.muted, fontSize: 13, margin: "4px 0 0" }}>Powered by n8n · WhatsApp Business API</p>
      </div>

      {/* n8n info */}
      <Card glow>
        <div style={{ display: "flex", gap: 14, alignItems: "center" }}>
          <div style={{ fontSize: 36 }}>🔄</div>
          <div>
            <div style={{ color: B.accent, fontWeight: 800, fontSize: 15 }}>n8n Translation & Automation Layer</div>
            <div style={{ color: B.muted, fontSize: 13, marginTop: 4 }}>All messages route through n8n for automatic translation (English → French → Hausa → Swahili), logging to Google Sheets, and WhatsApp delivery via WhatsApp Business API. No manual sending required.</div>
          </div>
        </div>
      </Card>

      {/* Message templates */}
      <Card>
        <div style={{ color: B.text, fontWeight: 700, marginBottom: 14 }}>Message Templates</div>
        <div style={{ display: "flex", flexDirection: "column", gap: 10 }}>
          {templates.map(t => (
            <div key={t.id} style={{ padding: "14px 16px", background: B.surface, borderRadius: 12, border: `1px solid ${B.border}` }}>
              <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: 8 }}>
                <div style={{ display: "flex", gap: 8, alignItems: "center" }}>
                  <span>{t.icon}</span>
                  <span style={{ color: B.text, fontWeight: 700 }}>{t.label}</span>
                </div>
                <Badge type="accent">n8n automated</Badge>
              </div>
              <div style={{ color: B.muted, fontSize: 13, fontStyle: "italic", lineHeight: 1.5 }}>"{t.msg(APPOINTMENTS[0])}"</div>
            </div>
          ))}
        </div>
      </Card>

      {/* Chase pending deposits */}
      <Card>
        <div style={{ color: B.text, fontWeight: 700, marginBottom: 14 }}>Chase Pending Deposits ({pending.length})</div>
        <div style={{ display: "flex", flexDirection: "column", gap: 8 }}>
          {pending.map(a => (
            <div key={a.id} style={{ display: "flex", alignItems: "center", justifyContent: "space-between", padding: "12px 14px", background: B.surface, borderRadius: 10 }}>
              <div>
                <div style={{ color: B.text, fontWeight: 600 }}>{a.patient}</div>
                <div style={{ color: B.muted, fontSize: 12 }}>{a.time} · {a.phone} · {M.currency}{a.deposit.toLocaleString()}</div>
              </div>
              <Btn small variant={sent.has(a.id) ? "ghost" : "gold"} onClick={() => setSent(p => new Set([...p, a.id]))}>
                {sent.has(a.id) ? "✓ Sent" : "💬 Chase"}
              </Btn>
            </div>
          ))}
        </div>
      </Card>
    </div>
  );
};

const Compliance = () => {
  const overdue = COMPLIANCE.filter(c => c.status === "overdue").length;
  const review = COMPLIANCE.filter(c => c.status === "review").length;
  return (
    <div style={{ display: "flex", flexDirection: "column", gap: 20 }}>
      <h2 style={{ color: B.text, fontSize: 22, fontWeight: 900, margin: 0 }}>Compliance Tracker</h2>
      <div style={{ display: "grid", gridTemplateColumns: "repeat(3,1fr)", gap: 12 }}>
        <KPI label="Compliant" value={COMPLIANCE.filter(c => c.status === "compliant").length} accent icon="🛡️" />
        <KPI label="Due Review" value={review} icon="⚠️" />
        <KPI label="Overdue" value={overdue} icon="🚨" />
      </div>
      <Card>
        {COMPLIANCE.map(c => {
          const m = { compliant: { type: "success", icon: "✅" }, review: { type: "warning", icon: "⏰" }, overdue: { type: "danger", icon: "🚨" } };
          return (
            <div key={c.id} style={{ display: "flex", alignItems: "center", justifyContent: "space-between", padding: "13px 14px", background: B.surface, borderRadius: 10, marginBottom: 8 }}>
              <div style={{ display: "flex", gap: 12, alignItems: "center" }}>
                <span>{m[c.status].icon}</span>
                <div>
                  <div style={{ color: B.text, fontWeight: 600 }}>{c.item}</div>
                  <div style={{ color: B.muted, fontSize: 12 }}>{c.cat} · Expires {c.expiry}</div>
                </div>
              </div>
              <Badge type={m[c.status].type}>{c.status}</Badge>
            </div>
          );
        })}
      </Card>
    </div>
  );
};

const Finance = ({ market }) => {
  const M = MARKETS[market];
  const target = market === "NG" ? 1200000 : 85000;
  const collected = market === "NG" ? 820000 : 58000;
  const deposits = market === "NG" ? 234000 : 16500;
  const noshow = market === "NG" ? 48000 : 3400;
  return (
    <div style={{ display: "flex", flexDirection: "column", gap: 20 }}>
      <h2 style={{ color: B.text, fontSize: 22, fontWeight: 900, margin: 0 }}>Financial Dashboard</h2>
      <div style={{ display: "grid", gridTemplateColumns: "repeat(2,1fr)", gap: 12 }}>
        <KPI label="Collected" value={fmt(collected, market)} sub={`${Math.round(collected / target * 100)}% of target`} accent icon="💰" />
        <KPI label="Monthly Target" value={fmt(target, market)} icon="🎯" />
        <KPI label="Deposits Held" value={fmt(deposits, market)} icon="💳" gold />
        <KPI label="No-Show Cost" value={fmt(noshow, market)} icon="😤" />
      </div>
      <Card glow>
        <div style={{ color: B.text, fontWeight: 700, marginBottom: 12 }}>Monthly Revenue Progress</div>
        <Bar value={collected} max={target} height={10} />
        <div style={{ display: "flex", justifyContent: "space-between", marginTop: 10 }}>
          <span style={{ color: B.accent, fontWeight: 800 }}>{fmt(collected, market)}</span>
          <span style={{ color: B.muted, fontSize: 13 }}>{fmt(target - collected, market)} remaining</span>
        </div>
      </Card>
      <Card>
        <div style={{ color: B.text, fontWeight: 700, marginBottom: 16 }}>Weekly Revenue</div>
        <div style={{ display: "flex", gap: 8, alignItems: "flex-end", height: 100 }}>
          {WEEKLY.map(d => {
            const max = Math.max(...WEEKLY.map(x => x.rev));
            const mult = market === "KE" ? 0.071 : 1;
            const h = (d.rev / max) * 84;
            return (
              <div key={d.day} style={{ flex: 1, display: "flex", flexDirection: "column", alignItems: "center", gap: 6 }}>
                <span style={{ color: B.muted, fontSize: 10 }}>{M.currency}{Math.round(d.rev * mult / 1000)}k</span>
                <div style={{ width: "100%", height: h, background: `linear-gradient(180deg, ${B.accent}, ${B.accentDark})`, borderRadius: "5px 5px 0 0" }} />
                <span style={{ color: B.muted, fontSize: 11, fontWeight: 600 }}>{d.day}</span>
              </div>
            );
          })}
        </div>
      </Card>
    </div>
  );
};

// ─── Nav ──────────────────────────────────────────────────────────────────────
const NAV = [
  { id: "dashboard", label: "Dashboard", icon: "🏠" },
  { id: "denttrack", label: "DentTrack", icon: "✅" },
  { id: "appointments", label: "Appointments", icon: "📅" },
  { id: "prebooking", label: "Pre-Booking", icon: "💳" },
  { id: "whatsapp", label: "WhatsApp", icon: "💬" },
  { id: "compliance", label: "Compliance", icon: "🛡️" },
  { id: "finance", label: "Financials", icon: "📊" },
];

// ─── App ──────────────────────────────────────────────────────────────────────
export default function App() {
  const [view, setView] = useState("dashboard");
  const [market, setMarket] = useState("NG");
  const [sidebarOpen, setSidebarOpen] = useState(true);
  const M = MARKETS[market];

  const views = {
    dashboard: <Dashboard setView={setView} market={market} />,
    denttrack: <DentTrack />,
    appointments: <Appointments market={market} />,
    prebooking: <PreBooking market={market} />,
    whatsapp: <WhatsApp market={market} />,
    compliance: <Compliance />,
    finance: <Finance market={market} />,
  };

  return (
    <div style={{ display: "flex", minHeight: "100vh", background: B.bg, fontFamily: "'DM Sans', 'Segoe UI', sans-serif", color: B.text }}>

      {/* Sidebar */}
      <div style={{ width: sidebarOpen ? 232 : 0, flexShrink: 0, background: B.surface, borderRight: `1px solid ${B.border}`, display: "flex", flexDirection: "column", overflow: "hidden", transition: "width 0.3s ease" }}>
        {/* Logo */}
        <div style={{ padding: "22px 18px 16px", borderBottom: `1px solid ${B.border}` }}>
          <div style={{ display: "flex", alignItems: "center", gap: 10, marginBottom: 16 }}>
            <div style={{ width: 36, height: 36, borderRadius: 10, background: `linear-gradient(135deg, ${B.accent}, #0096FF)`, display: "flex", alignItems: "center", justifyContent: "center", fontWeight: 900, fontSize: 18, color: "#fff" }}>D</div>
            <div>
              <div style={{ fontWeight: 900, fontSize: 16, color: B.text, lineHeight: 1 }}>Dentiq</div>
              <div style={{ fontSize: 10, color: B.muted, letterSpacing: "0.08em" }}>by Mythros</div>
            </div>
          </div>
          {/* Practice card */}
          <div style={{ background: B.bg, borderRadius: 10, padding: "10px 12px" }}>
            <div style={{ color: B.text, fontWeight: 700, fontSize: 12 }}>{PRACTICE.name}</div>
            <div style={{ color: B.muted, fontSize: 11, marginTop: 2 }}>{PRACTICE.owner}</div>
            <div style={{ marginTop: 6 }}><Badge type="accent">{PRACTICE.plan}</Badge></div>
          </div>
        </div>

        {/* Market switcher */}
        <div style={{ padding: "12px 18px", borderBottom: `1px solid ${B.border}` }}>
          <div style={{ color: B.muted, fontSize: 10, fontWeight: 700, letterSpacing: "0.08em", textTransform: "uppercase", marginBottom: 8 }}>Market</div>
          <div style={{ display: "flex", gap: 6 }}>
            {Object.entries(MARKETS).map(([k, v]) => (
              <div key={k} onClick={() => setMarket(k)} style={{
                flex: 1, padding: "7px", borderRadius: 8, cursor: "pointer", textAlign: "center",
                background: market === k ? B.accentGlow : B.bg,
                border: `1px solid ${market === k ? B.accent + "66" : B.border}`,
                transition: "all 0.15s",
              }}>
                <div style={{ fontSize: 16 }}>{v.flag}</div>
                <div style={{ color: market === k ? B.accent : B.muted, fontSize: 10, fontWeight: 700, marginTop: 2 }}>{v.name}</div>
              </div>
            ))}
          </div>
        </div>

        {/* Nav */}
        <nav style={{ flex: 1, padding: "12px 10px", display: "flex", flexDirection: "column", gap: 2 }}>
          {NAV.map(item => (
            <div key={item.id} onClick={() => setView(item.id)} style={{
              display: "flex", alignItems: "center", gap: 10, padding: "10px 12px",
              borderRadius: 10, cursor: "pointer",
              background: view === item.id ? B.accentGlow : "transparent",
              borderLeft: `3px solid ${view === item.id ? B.accent : "transparent"}`,
              transition: "all 0.15s",
            }}
              onMouseEnter={e => { if (view !== item.id) e.currentTarget.style.background = B.bg; }}
              onMouseLeave={e => { if (view !== item.id) e.currentTarget.style.background = "transparent"; }}
            >
              <span style={{ fontSize: 16 }}>{item.icon}</span>
              <span style={{ color: view === item.id ? B.accent : B.text, fontWeight: view === item.id ? 700 : 400, fontSize: 14 }}>{item.label}</span>
            </div>
          ))}
        </nav>

        <div style={{ padding: "14px 18px", borderTop: `1px solid ${B.border}` }}>
          <div style={{ display: "flex", alignItems: "center", gap: 8 }}>
            <div style={{ width: 8, height: 8, borderRadius: "50%", background: B.success, boxShadow: `0 0 8px ${B.success}` }} />
            <span style={{ color: B.muted, fontSize: 11 }}>All systems live</span>
          </div>
        </div>
      </div>

      {/* Main */}
      <div style={{ flex: 1, display: "flex", flexDirection: "column", minWidth: 0 }}>
        {/* Topbar */}
        <div style={{ height: 58, display: "flex", alignItems: "center", justifyContent: "space-between", padding: "0 24px", borderBottom: `1px solid ${B.border}`, background: B.surface, flexShrink: 0 }}>
          <div style={{ display: "flex", alignItems: "center", gap: 14 }}>
            <button onClick={() => setSidebarOpen(p => !p)} style={{ background: "none", border: "none", color: B.muted, cursor: "pointer", fontSize: 18, padding: 4 }}>☰</button>
            <span style={{ color: B.text, fontWeight: 700 }}>{NAV.find(n => n.id === view)?.label}</span>
          </div>
          <div style={{ display: "flex", alignItems: "center", gap: 14 }}>
            <div style={{ background: B.accentGlow, border: `1px solid ${B.accent}44`, borderRadius: 8, padding: "5px 12px", display: "flex", alignItems: "center", gap: 6 }}>
              <span style={{ fontSize: 14 }}>{M.flag}</span>
              <span style={{ color: B.accent, fontSize: 12, fontWeight: 700 }}>{M.name} · {M.currency}</span>
            </div>
            <div style={{ position: "relative", cursor: "pointer" }}>
              <span style={{ fontSize: 18, color: B.muted }}>🔔</span>
              <div style={{ position: "absolute", top: -2, right: -2, width: 8, height: 8, borderRadius: "50%", background: B.danger }} />
            </div>
            <div style={{ display: "flex", alignItems: "center", gap: 8 }}>
              <div style={{ width: 32, height: 32, borderRadius: "50%", background: `linear-gradient(135deg, ${B.accent}, #0096FF)`, display: "flex", alignItems: "center", justifyContent: "center", fontWeight: 800, fontSize: 12, color: "#fff" }}>AO</div>
              <span style={{ color: B.text, fontWeight: 600, fontSize: 13 }}>Dr. Okonkwo</span>
            </div>
          </div>
        </div>

        {/* Content */}
        <div style={{ flex: 1, overflowY: "auto", padding: 24 }}>
          {views[view]}
        </div>
      </div>
    </div>
  );
}
