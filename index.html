import { useState } from “react”;

const styles = `
@import url(‘https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Sans:wght@300;400;500&display=swap’);

- { margin: 0; padding: 0; box-sizing: border-box; }

:root {
–tec-blue: #003DA5;
–tec-blue-dark: #002670;
–tec-red: #E8001D;
–accent-cyan: #00C2FF;
–accent-lime: #B4FF3C;
–bg: #F0F2F7;
–card: #FFFFFF;
–text: #0D0F1A;
–muted: #6B7280;
–border: #E2E5EF;
}

body { font-family: ‘DM Sans’, sans-serif; background: var(–bg); color: var(–text); }

.app { min-height: 100vh; display: flex; flex-direction: column; }

/* ── LOGIN ── */
.login-screen {
min-height: 100vh;
display: flex;
align-items: stretch;
}
.login-left {
flex: 1;
background: var(–tec-blue);
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 60px 40px;
position: relative;
overflow: hidden;
}
.login-left::before {
content: ‘’;
position: absolute;
width: 500px; height: 500px;
border-radius: 50%;
border: 80px solid rgba(0,194,255,0.12);
top: -150px; right: -150px;
}
.login-left::after {
content: ‘’;
position: absolute;
width: 300px; height: 300px;
border-radius: 50%;
background: rgba(232,0,29,0.18);
bottom: -80px; left: -80px;
}
.login-logo { position: relative; z-index: 1; text-align: center; }
.login-logo .brand {
font-family: ‘Syne’, sans-serif;
font-size: 2.8rem;
font-weight: 800;
color: #fff;
letter-spacing: -1px;
}
.login-logo .brand span { color: var(–accent-lime); }
.login-logo .sub {
font-size: 0.95rem;
color: rgba(255,255,255,0.65);
margin-top: 4px;
letter-spacing: 2px;
text-transform: uppercase;
}
.login-tagline {
position: relative; z-index: 1;
margin-top: 48px;
color: rgba(255,255,255,0.85);
font-size: 1.25rem;
line-height: 1.6;
max-width: 320px;
text-align: center;
}
.login-badges {
position: relative; z-index: 1;
display: flex; gap: 10px; margin-top: 40px;
flex-wrap: wrap; justify-content: center;
}
.login-badge {
background: rgba(255,255,255,0.12);
border: 1px solid rgba(255,255,255,0.2);
color: #fff;
padding: 6px 14px;
border-radius: 20px;
font-size: 0.8rem;
font-weight: 500;
}

.login-right {
width: 460px;
background: #fff;
display: flex;
flex-direction: column;
justify-content: center;
padding: 60px 50px;
}
.login-title { font-family: ‘Syne’, sans-serif; font-size: 1.9rem; font-weight: 700; margin-bottom: 6px; }
.login-desc { color: var(–muted); font-size: 0.95rem; margin-bottom: 36px; }

.role-tabs {
display: flex; gap: 0; margin-bottom: 32px;
border: 2px solid var(–border); border-radius: 12px; overflow: hidden;
}
.role-tab {
flex: 1; padding: 12px; text-align: center; cursor: pointer;
font-family: ‘Syne’, sans-serif; font-weight: 600; font-size: 0.9rem;
transition: all .2s; color: var(–muted); background: #fff;
border: none; outline: none;
}
.role-tab.active { background: var(–tec-blue); color: #fff; }

.form-group { margin-bottom: 20px; }
.form-label { display: block; font-size: 0.85rem; font-weight: 500; margin-bottom: 6px; color: var(–text); }
.form-input {
width: 100%; padding: 13px 16px; border: 2px solid var(–border);
border-radius: 10px; font-size: 0.95rem; font-family: ‘DM Sans’, sans-serif;
outline: none; transition: border-color .2s; background: var(–bg);
}
.form-input:focus { border-color: var(–tec-blue); background: #fff; }

.btn-primary {
width: 100%; padding: 15px; background: var(–tec-blue); color: #fff;
border: none; border-radius: 12px; font-family: ‘Syne’, sans-serif;
font-size: 1rem; font-weight: 700; cursor: pointer; transition: all .2s;
letter-spacing: 0.3px;
}
.btn-primary:hover { background: var(–tec-blue-dark); transform: translateY(-1px); }

.demo-hint {
margin-top: 20px; text-align: center; font-size: 0.8rem; color: var(–muted);
}
.demo-hint strong { color: var(–tec-blue); }

/* ── TOPBAR ── */
.topbar {
background: var(–tec-blue);
padding: 0 28px;
height: 64px;
display: flex; align-items: center; justify-content: space-between;
position: sticky; top: 0; z-index: 100;
box-shadow: 0 2px 20px rgba(0,61,165,0.3);
}
.topbar-brand { font-family: ‘Syne’, sans-serif; font-size: 1.5rem; font-weight: 800; color: #fff; }
.topbar-brand span { color: var(–accent-lime); }
.topbar-right { display: flex; align-items: center; gap: 16px; }
.topbar-role {
background: rgba(255,255,255,0.15); color: #fff;
padding: 5px 14px; border-radius: 20px; font-size: 0.8rem; font-weight: 600;
}
.topbar-avatar {
width: 38px; height: 38px; border-radius: 50%;
background: var(–accent-lime); display: flex; align-items: center; justify-content: center;
font-family: ‘Syne’, sans-serif; font-weight: 800; font-size: 0.9rem; color: var(–tec-blue);
cursor: pointer;
}
.btn-logout {
background: rgba(255,255,255,0.12); border: 1px solid rgba(255,255,255,0.25);
color: #fff; padding: 7px 16px; border-radius: 8px; cursor: pointer;
font-size: 0.82rem; font-weight: 500; transition: all .2s;
}
.btn-logout:hover { background: rgba(255,255,255,0.22); }

/* ── LAYOUT ── */
.main-layout { display: flex; flex: 1; }
.sidebar {
width: 240px; background: #fff; border-right: 2px solid var(–border);
padding: 24px 16px; display: flex; flex-direction: column; gap: 4px;
min-height: calc(100vh - 64px);
}
.sidebar-label { font-size: 0.72rem; color: var(–muted); letter-spacing: 1.5px; text-transform: uppercase; font-weight: 600; padding: 12px 12px 6px; }
.nav-item {
display: flex; align-items: center; gap: 12px; padding: 11px 14px;
border-radius: 10px; cursor: pointer; transition: all .18s;
font-size: 0.9rem; font-weight: 500; color: var(–muted);
border: none; background: transparent; width: 100%; text-align: left;
}
.nav-item:hover { background: var(–bg); color: var(–text); }
.nav-item.active { background: #EEF3FF; color: var(–tec-blue); font-weight: 600; }
.nav-item .icon { font-size: 1.1rem; width: 22px; text-align: center; }
.nav-badge {
margin-left: auto; background: var(–tec-red); color: #fff;
font-size: 0.7rem; font-weight: 700; padding: 2px 7px; border-radius: 10px;
}

.content { flex: 1; padding: 32px 36px; overflow-y: auto; }

/* ── CARDS ── */
.page-title { font-family: ‘Syne’, sans-serif; font-size: 1.8rem; font-weight: 800; margin-bottom: 4px; }
.page-sub { color: var(–muted); font-size: 0.95rem; margin-bottom: 28px; }

.stats-row { display: grid; grid-template-columns: repeat(4, 1fr); gap: 16px; margin-bottom: 28px; }
.stat-card {
background: #fff; border-radius: 16px; padding: 20px 22px;
border: 2px solid var(–border); position: relative; overflow: hidden;
}
.stat-card::after {
content: ‘’; position: absolute; top: 0; left: 0; right: 0; height: 4px;
}
.stat-card.blue::after { background: var(–tec-blue); }
.stat-card.red::after { background: var(–tec-red); }
.stat-card.cyan::after { background: var(–accent-cyan); }
.stat-card.lime::after { background: #7EC800; }
.stat-num { font-family: ‘Syne’, sans-serif; font-size: 2.2rem; font-weight: 800; line-height: 1; }
.stat-label { font-size: 0.82rem; color: var(–muted); margin-top: 4px; font-weight: 500; }

.grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
.panel { background: #fff; border-radius: 16px; border: 2px solid var(–border); padding: 24px; }
.panel-title { font-family: ‘Syne’, sans-serif; font-weight: 700; font-size: 1rem; margin-bottom: 18px; display: flex; align-items: center; gap: 8px; }

/* ── TASK ITEM ── */
.task-item {
display: flex; align-items: flex-start; gap: 14px; padding: 14px 0;
border-bottom: 1px solid var(–border);
}
.task-item:last-child { border-bottom: none; }
.task-check {
width: 20px; height: 20px; border-radius: 6px; border: 2px solid var(–border);
flex-shrink: 0; cursor: pointer; display: flex; align-items: center; justify-content: center;
transition: all .15s; margin-top: 2px;
}
.task-check.done { background: var(–tec-blue); border-color: var(–tec-blue); color: #fff; font-size: 0.7rem; }
.task-info { flex: 1; }
.task-name { font-weight: 500; font-size: 0.93rem; }
.task-name.done { text-decoration: line-through; color: var(–muted); }
.task-meta { display: flex; gap: 10px; margin-top: 5px; flex-wrap: wrap; }
.task-subject {
font-size: 0.78rem; padding: 3px 10px; border-radius: 8px; font-weight: 600;
}
.tag-calc { background: #EEF3FF; color: var(–tec-blue); }
.tag-prog { background: #FFF1F0; color: #C0392B; }
.tag-fis { background: #F0FFF4; color: #16A34A; }
.tag-ing { background: #FFFBEA; color: #B45309; }
.tag-mate { background: #F5F3FF; color: #7C3AED; }
.task-due { font-size: 0.78rem; color: var(–muted); }
.task-due.urgent { color: var(–tec-red); font-weight: 600; }
.priority-dot { width: 8px; height: 8px; border-radius: 50%; flex-shrink: 0; margin-top: 6px; }
.p-high { background: var(–tec-red); }
.p-med { background: #F59E0B; }
.p-low { background: #10B981; }

/* ── SCHEDULE ── */
.schedule-item {
display: flex; gap: 14px; padding: 12px 0; border-bottom: 1px solid var(–border); align-items: center;
}
.schedule-item:last-child { border-bottom: none; }
.schedule-time { font-family: ‘Syne’, sans-serif; font-size: 0.82rem; font-weight: 700; color: var(–tec-blue); width: 80px; flex-shrink: 0; }
.schedule-bar { width: 4px; height: 40px; border-radius: 4px; flex-shrink: 0; }
.schedule-info .sname { font-weight: 600; font-size: 0.9rem; }
.schedule-info .sroom { font-size: 0.8rem; color: var(–muted); margin-top: 2px; }

/* ── GRADES ── */
.grade-row {
display: flex; align-items: center; justify-content: space-between;
padding: 13px 0; border-bottom: 1px solid var(–border);
}
.grade-row:last-child { border-bottom: none; }
.grade-subject { font-weight: 500; font-size: 0.92rem; }
.grade-right { display: flex; align-items: center; gap: 14px; }
.grade-bar-wrap { width: 100px; height: 6px; background: var(–bg); border-radius: 3px; overflow: hidden; }
.grade-bar { height: 100%; border-radius: 3px; }
.grade-num { font-family: ‘Syne’, sans-serif; font-weight: 800; font-size: 1rem; min-width: 36px; text-align: right; }
.grade-a { color: #16A34A; }
.grade-b { color: var(–tec-blue); }
.grade-c { color: #F59E0B; }

/* ── PARENT VIEW ── */
.parent-banner {
background: linear-gradient(135deg, var(–tec-blue) 0%, #1A56C4 100%);
border-radius: 20px; padding: 28px 32px; color: #fff; margin-bottom: 24px;
display: flex; align-items: center; justify-content: space-between;
position: relative; overflow: hidden;
}
.parent-banner::before {
content: ‘’; position: absolute; right: -30px; top: -30px;
width: 180px; height: 180px; border-radius: 50%;
background: rgba(180,255,60,0.15);
}
.parent-banner-text h2 { font-family: ‘Syne’, sans-serif; font-size: 1.5rem; font-weight: 800; }
.parent-banner-text p { opacity: 0.75; margin-top: 4px; font-size: 0.9rem; }
.parent-overall {
font-family: ‘Syne’, sans-serif; font-size: 3.5rem; font-weight: 800; color: var(–accent-lime);
position: relative; z-index: 1;
}
.parent-overall span { font-size: 1rem; color: rgba(255,255,255,0.7); font-weight: 400; font-family: ‘DM Sans’, sans-serif; }

.alert-card {
border-radius: 14px; padding: 16px 20px; margin-bottom: 12px;
display: flex; gap: 14px; align-items: flex-start;
border: 2px solid;
}
.alert-card.warning { background: #FFFBEA; border-color: #FDE68A; }
.alert-card.danger { background: #FFF1F0; border-color: #FECACA; }
.alert-card.ok { background: #F0FFF4; border-color: #BBF7D0; }
.alert-icon { font-size: 1.4rem; flex-shrink: 0; }
.alert-title { font-weight: 700; font-size: 0.9rem; }
.alert-desc { font-size: 0.82rem; color: var(–muted); margin-top: 2px; }

/* ── CALENDAR MINI ── */
.calendar-grid { display: grid; grid-template-columns: repeat(7, 1fr); gap: 4px; }
.cal-header { text-align: center; font-size: 0.7rem; color: var(–muted); font-weight: 700; padding: 4px 0; }
.cal-day { text-align: center; padding: 6px 4px; border-radius: 8px; font-size: 0.82rem; cursor: pointer; transition: all .15s; position: relative; }
.cal-day:hover { background: var(–bg); }
.cal-day.today { background: var(–tec-blue); color: #fff; font-weight: 700; }
.cal-day.has-task::after { content: ‘’; position: absolute; bottom: 3px; left: 50%; transform: translateX(-50%); width: 4px; height: 4px; border-radius: 50%; background: var(–tec-red); }
.cal-day.other { color: var(–border); }

/* ── CHAT AI ── */
.chat-box { display: flex; flex-direction: column; gap: 12px; margin-bottom: 16px; max-height: 300px; overflow-y: auto; }
.chat-msg { display: flex; gap: 10px; }
.chat-msg.user { flex-direction: row-reverse; }
.chat-bubble {
max-width: 80%; padding: 11px 15px; border-radius: 16px; font-size: 0.88rem; line-height: 1.5;
}
.chat-msg.ai .chat-bubble { background: var(–bg); color: var(–text); border-bottom-left-radius: 4px; }
.chat-msg.user .chat-bubble { background: var(–tec-blue); color: #fff; border-bottom-right-radius: 4px; }
.chat-avatar { width: 32px; height: 32px; border-radius: 50%; flex-shrink: 0; display: flex; align-items: center; justify-content: center; font-size: 0.9rem; }
.chat-avatar.ai { background: #EEF3FF; }
.chat-avatar.user { background: var(–accent-lime); }
.chat-input-row { display: flex; gap: 10px; }
.chat-input {
flex: 1; padding: 11px 14px; border: 2px solid var(–border); border-radius: 12px;
font-size: 0.9rem; font-family: ‘DM Sans’, sans-serif; outline: none; transition: border-color .2s;
}
.chat-input:focus { border-color: var(–tec-blue); }
.chat-send {
background: var(–tec-blue); color: #fff; border: none; border-radius: 12px;
padding: 11px 18px; cursor: pointer; font-size: 1rem; transition: all .2s;
}
.chat-send:hover { background: var(–tec-blue-dark); }

/* ── EMPTY STATE ── */
.empty { text-align: center; padding: 40px 20px; color: var(–muted); }
.empty-icon { font-size: 2.5rem; margin-bottom: 10px; }

@media (max-width: 900px) {
.stats-row { grid-template-columns: repeat(2, 1fr); }
.grid-2 { grid-template-columns: 1fr; }
.login-left { display: none; }
.login-right { width: 100%; }
.sidebar { width: 200px; }
}
`;

const TASKS = [
{ id: 1, name: “Tarea 3: Integrales definidas”, subject: “Cálculo II”, tag: “tag-calc”, due: “Hoy 11:59 PM”, urgent: true, priority: “high”, done: false },
{ id: 2, name: “Proyecto final: Sistema de inventario”, subject: “Programación”, tag: “tag-prog”, due: “Mañana 11:59 PM”, urgent: false, priority: “high”, done: false },
{ id: 3, name: “Resumen capítulo 8: Cinemática”, subject: “Física I”, tag: “tag-fis”, due: “Vie 23 May”, urgent: false, priority: “med”, done: false },
{ id: 4, name: “Ensayo: Impacto IA en la industria”, subject: “Inglés IV”, tag: “tag-ing”, due: “Lun 26 May”, urgent: false, priority: “med”, done: false },
{ id: 5, name: “Ejercicios 5.1 – 5.4 álgebra lineal”, subject: “Matemáticas”, tag: “tag-mate”, due: “Mié 28 May”, urgent: false, priority: “low”, done: true },
{ id: 6, name: “Laboratorio: Circuito RC”, subject: “Física I”, tag: “tag-fis”, due: “Jue 29 May”, urgent: false, priority: “low”, done: true },
];

const SCHEDULE = [
{ time: “07:00”, name: “Cálculo II”, room: “Aula 3B — Ing. Martínez”, color: “#003DA5” },
{ time: “09:00”, name: “Programación Avanzada”, room: “Lab Cómputo A — Dr. Saldaña”, color: “#E8001D” },
{ time: “11:00”, name: “Física I”, room: “Aula 7A — Ing. Robles”, color: “#00C2FF” },
{ time: “13:00”, name: “Inglés IV”, room: “Aula 2C — Mtra. López”, color: “#7EC800” },
{ time: “15:00”, name: “Álgebra Lineal”, room: “Aula 5B — Dr. Herrera”, color: “#7C3AED” },
];

const GRADES = [
{ subject: “Cálculo II”, grade: 88, color: “#003DA5” },
{ subject: “Programación Avanzada”, grade: 94, color: “#E8001D” },
{ subject: “Física I”, grade: 76, color: “#00C2FF” },
{ subject: “Inglés IV”, grade: 91, color: “#7EC800” },
{ subject: “Álgebra Lineal”, grade: 83, color: “#7C3AED” },
];

const AI_RESPONSES = {
default: “¡Hola! Soy tu asistente de estudio del Tec 🎓. Puedo ayudarte a entender temas, repasar conceptos, o prepararte para exámenes. ¿En qué materia necesitas apoyo hoy?”,
“calculo”: “Para las integrales definidas, recuerda el Teorema Fundamental del Cálculo: si F’(x) = f(x), entonces ∫[a→b] f(x)dx = F(b) - F(a). ¿Quieres que repasemos un ejemplo juntos?”,
“fisica”: “¡Claro! En cinemática, lo más importante es entender las tres ecuaciones del movimiento uniformemente acelerado. ¿Quieres que practiquemos con un problema de lanzamiento de proyectil?”,
“programacion”: “Para tu sistema de inventario, te recomiendo empezar por definir las clases principales: Producto, Inventario y GestorDeVentas. ¿Ya tienes el diagrama UML? Puedo ayudarte a diseñarlo.”,
“matematicas”: “Para álgebra lineal, los ejercicios 5.1-5.4 probablemente cubren transformaciones lineales. La clave es recordar que T(u+v) = T(u) + T(v) y T(cu) = cT(u). ¿Quieres practicar?”,
};

function getAIResponse(msg) {
const m = msg.toLowerCase();
if (m.includes(“cálculo”) || m.includes(“integral”) || m.includes(“calculo”)) return AI_RESPONSES[“calculo”];
if (m.includes(“física”) || m.includes(“fisica”) || m.includes(“cinemática”)) return AI_RESPONSES[“fisica”];
if (m.includes(“programación”) || m.includes(“programacion”) || m.includes(“sistema”)) return AI_RESPONSES[“programacion”];
if (m.includes(“álgebra”) || m.includes(“algebra”) || m.includes(“matemáticas”)) return AI_RESPONSES[“matematicas”];
return “Entendido. Puedo ayudarte con Cálculo, Física, Programación, Inglés o Matemáticas. ¿Sobre qué tema quieres trabajar hoy?”;
}

const DAYS = [“D”, “L”, “M”, “X”, “J”, “V”, “S”];
const calDays = Array.from({ length: 35 }, (_, i) => {
const d = i - 2;
return { n: d <= 0 ? “” : d > 31 ? “” : d, today: d === 6, hasTask: [6, 14, 22, 26].includes(d), other: d <= 0 || d > 31 };
});

export default function TecStudyApp() {
const [screen, setScreen] = useState(“login”);
const [role, setRole] = useState(“student”);
const [email, setEmail] = useState(””);
const [pass, setPass] = useState(””);
const [tab, setTab] = useState(“dashboard”);
const [tasks, setTasks] = useState(TASKS);
const [chatMsgs, setChatMsgs] = useState([
{ role: “ai”, text: AI_RESPONSES.default }
]);
const [chatInput, setChatInput] = useState(””);

const pending = tasks.filter(t => !t.done);
const done = tasks.filter(t => t.done);
const urgent = tasks.filter(t => t.urgent && !t.done);

const toggleTask = (id) => {
setTasks(ts => ts.map(t => t.id === id ? { …t, done: !t.done } : t));
};

const sendChat = () => {
if (!chatInput.trim()) return;
const user = chatInput;
setChatInput(””);
setChatMsgs(m => […m, { role: “user”, text: user }]);
setTimeout(() => {
setChatMsgs(m => […m, { role: “ai”, text: getAIResponse(user) }]);
}, 700);
};

const login = () => {
if (email && pass) setScreen(“app”);
};

const avgGrade = Math.round(GRADES.reduce((s, g) => s + g.grade, 0) / GRADES.length);

if (screen === “login”) return (
<>
<style>{styles}</style>
<div className="login-screen">
<div className="login-left">
<div className="login-logo">
<div className="brand">Tec<span>Study</span></div>
<div className="sub">Powered by Tec de Monterrey</div>
</div>
<div className="login-tagline">
Tu plataforma académica inteligente. Organiza, aprende y conecta a tu familia con tu progreso.
</div>
<div className="login-badges">
<span className="login-badge">📚 Tareas en tiempo real</span>
<span className="login-badge">🤖 IA de apoyo</span>
<span className="login-badge">👨‍👩‍👧 Modo Padres</span>
<span className="login-badge">📊 Calificaciones</span>
</div>
</div>
<div className="login-right">
<div className="login-title">Bienvenido de vuelta</div>
<div className="login-desc">Accede con tu cuenta institucional del Tec</div>
<div className="role-tabs">
<button className={`role-tab ${role === "student" ? "active" : ""}`} onClick={() => setRole(“student”)}>
🎓 Alumno
</button>
<button className={`role-tab ${role === "parent" ? "active" : ""}`} onClick={() => setRole(“parent”)}>
👨‍👩‍👧 Padre/Madre
</button>
</div>
<div className="form-group">
<label className="form-label">{role === “student” ? “Matrícula o correo institucional” : “Correo del tutor registrado”}</label>
<input className=“form-input” value={email} onChange={e => setEmail(e.target.value)} placeholder={role === “student” ? “A01234567@tec.mx” : “padre@gmail.com”} />
</div>
<div className="form-group">
<label className="form-label">Contraseña</label>
<input className=“form-input” type=“password” value={pass} onChange={e => setPass(e.target.value)} placeholder=”••••••••” onKeyDown={e => e.key === “Enter” && login()} />
</div>
<button className="btn-primary" onClick={login}>
{role === “student” ? “Entrar como Alumno →” : “Entrar como Padre/Madre →”}
</button>
<div className="demo-hint">Demo: cualquier correo + contraseña funciona · <strong>Cambia de rol arriba</strong></div>
</div>
</div>
</>
);

const isParent = role === “parent”;

const STUDENT_NAV = [
{ id: “dashboard”, icon: “🏠”, label: “Inicio” },
{ id: “tasks”, icon: “📋”, label: “Mis Tareas”, badge: pending.length },
{ id: “grades”, icon: “📊”, label: “Calificaciones” },
{ id: “schedule”, icon: “🗓️”, label: “Horario” },
{ id: “ai”, icon: “🤖”, label: “Asistente IA” },
];
const PARENT_NAV = [
{ id: “dashboard”, icon: “🏠”, label: “Inicio” },
{ id: “tasks”, icon: “📋”, label: “Tareas Pendientes”, badge: pending.length },
{ id: “grades”, icon: “📊”, label: “Calificaciones” },
{ id: “alerts”, icon: “🔔”, label: “Alertas”, badge: urgent.length },
];
const navItems = isParent ? PARENT_NAV : STUDENT_NAV;

return (
<>
<style>{styles}</style>
<div className="app">
<div className="topbar">
<div className="topbar-brand">Tec<span>Study</span></div>
<div className="topbar-right">
<span className="topbar-role">{isParent ? “👨‍👩‍👧 Padre/Madre” : “🎓 Alumno”}</span>
<div className="topbar-avatar">{isParent ? “P” : “A”}</div>
<button className=“btn-logout” onClick={() => setScreen(“login”)}>Cerrar sesión</button>
</div>
</div>

```
    <div className="main-layout">
      <div className="sidebar">
        <div className="sidebar-label">Menú</div>
        {navItems.map(n => (
          <button key={n.id} className={`nav-item ${tab === n.id ? "active" : ""}`} onClick={() => setTab(n.id)}>
            <span className="icon">{n.icon}</span>
            {n.label}
            {n.badge > 0 && <span className="nav-badge">{n.badge}</span>}
          </button>
        ))}
        {!isParent && (
          <>
            <div className="sidebar-label" style={{ marginTop: 12 }}>Mi cuenta</div>
            <div style={{ padding: "12px 14px", fontSize: "0.82rem", color: "var(--muted)", background: "var(--bg)", borderRadius: 10 }}>
              <div style={{ fontWeight: 600, color: "var(--text)" }}>Alejandro Martínez</div>
              <div>A01234567</div>
              <div>ITC · 5° semestre</div>
            </div>
          </>
        )}
        {isParent && (
          <>
            <div className="sidebar-label" style={{ marginTop: 12 }}>Alumno vinculado</div>
            <div style={{ padding: "12px 14px", fontSize: "0.82rem", color: "var(--muted)", background: "var(--bg)", borderRadius: 10 }}>
              <div style={{ fontWeight: 600, color: "var(--text)" }}>Alejandro Martínez</div>
              <div>ITC · 5° semestre</div>
              <div style={{ marginTop: 6, color: "#16A34A", fontWeight: 600 }}>● Conectado</div>
            </div>
          </>
        )}
      </div>

      <div className="content">

        {/* ── DASHBOARD ── */}
        {tab === "dashboard" && !isParent && (
          <>
            <div className="page-title">¡Buenos días, Alejandro! 👋</div>
            <div className="page-sub">Miércoles, 7 de mayo · Semana 12 del semestre</div>
            <div className="stats-row">
              <div className="stat-card blue">
                <div className="stat-num">{pending.length}</div>
                <div className="stat-label">Tareas pendientes</div>
              </div>
              <div className="stat-card red">
                <div className="stat-num">{urgent.length}</div>
                <div className="stat-label">Urgentes hoy</div>
              </div>
              <div className="stat-card cyan">
                <div className="stat-num">{avgGrade}</div>
                <div className="stat-label">Promedio general</div>
              </div>
              <div className="stat-card lime">
                <div className="stat-num">{done.length}</div>
                <div className="stat-label">Completadas</div>
              </div>
            </div>
            <div className="grid-2">
              <div className="panel">
                <div className="panel-title">📋 Tareas prioritarias</div>
                {pending.slice(0, 3).map(t => (
                  <div key={t.id} className="task-item">
                    <div className={`priority-dot p-${t.priority}`} />
                    <div className="task-info">
                      <div className="task-name">{t.name}</div>
                      <div className="task-meta">
                        <span className={`task-subject ${t.tag}`}>{t.subject}</span>
                        <span className={`task-due ${t.urgent ? "urgent" : ""}`}>⏰ {t.due}</span>
                      </div>
                    </div>
                  </div>
                ))}
                <button className="btn-primary" style={{ marginTop: 14, padding: "10px" }} onClick={() => setTab("tasks")}>Ver todas las tareas →</button>
              </div>
              <div className="panel">
                <div className="panel-title">🗓️ Horario de hoy</div>
                {SCHEDULE.slice(0, 4).map((s, i) => (
                  <div key={i} className="schedule-item">
                    <div className="schedule-time">{s.time}</div>
                    <div className="schedule-bar" style={{ background: s.color }} />
                    <div className="schedule-info">
                      <div className="sname">{s.name}</div>
                      <div className="sroom">{s.room}</div>
                    </div>
                  </div>
                ))}
              </div>
            </div>
          </>
        )}

        {/* ── PARENT DASHBOARD ── */}
        {tab === "dashboard" && isParent && (
          <>
            <div className="page-title">Panel de Seguimiento 👨‍👩‍👧</div>
            <div className="page-sub">Monitorea el progreso académico de Alejandro en tiempo real</div>
            <div className="parent-banner">
              <div className="parent-banner-text">
                <h2>Alejandro Martínez</h2>
                <p>Ingeniería en Tecnología Computacional · 5° Semestre · Campus Monterrey</p>
                <div style={{ marginTop: 16, display: "flex", gap: 10, flexWrap: "wrap" }}>
                  {[`${pending.length} tareas pendientes`, `${done.length} completadas`, `${urgent.length} urgentes`].map((b, i) => (
                    <span key={i} style={{ background: "rgba(255,255,255,0.15)", padding: "5px 14px", borderRadius: 20, fontSize: "0.82rem" }}>{b}</span>
                  ))}
                </div>
              </div>
              <div className="parent-overall">{avgGrade}<span>/100</span></div>
            </div>
            <div className="grid-2">
              <div className="panel">
                <div className="panel-title">🔔 Alertas académicas</div>
                <div className="alert-card danger">
                  <div className="alert-icon">🚨</div>
                  <div>
                    <div className="alert-title">Tarea urgente hoy</div>
                    <div className="alert-desc">Tarea 3 de Cálculo II vence a las 11:59 PM. Aún no entregada.</div>
                  </div>
                </div>
                <div className="alert-card warning">
                  <div className="alert-icon">⚠️</div>
                  <div>
                    <div className="alert-title">Proyecto mañana</div>
                    <div className="alert-desc">Proyecto final de Programación vence mañana a las 11:59 PM.</div>
                  </div>
                </div>
                <div className="alert-card ok">
                  <div className="alert-icon">✅</div>
                  <div>
                    <div className="alert-title">Buen desempeño general</div>
                    <div className="alert-desc">Promedio de 86/100. Programación y Matemáticas con excelentes notas.</div>
                  </div>
                </div>
              </div>
              <div className="panel">
                <div className="panel-title">📊 Calificaciones actuales</div>
                {GRADES.map((g, i) => (
                  <div key={i} className="grade-row">
                    <div className="grade-subject">{g.subject}</div>
                    <div className="grade-right">
                      <div className="grade-bar-wrap">
                        <div className="grade-bar" style={{ width: `${g.grade}%`, background: g.color }} />
                      </div>
                      <div className={`grade-num ${g.grade >= 90 ? "grade-a" : g.grade >= 80 ? "grade-b" : "grade-c"}`}>{g.grade}</div>
                    </div>
                  </div>
                ))}
              </div>
            </div>
          </>
        )}

        {/* ── TASKS ── */}
        {tab === "tasks" && (
          <>
            <div className="page-title">{isParent ? "Tareas de Alejandro" : "Mis Tareas"}</div>
            <div className="page-sub">{pending.length} pendientes · {done.length} completadas</div>
            <div className="panel" style={{ marginBottom: 20 }}>
              <div className="panel-title">⏳ Pendientes</div>
              {pending.length === 0 && <div className="empty"><div className="empty-icon">🎉</div>¡Sin tareas pendientes!</div>}
              {pending.map(t => (
                <div key={t.id} className="task-item">
                  <div className={`priority-dot p-${t.priority}`} />
                  {!isParent && (
                    <div className={`task-check ${t.done ? "done" : ""}`} onClick={() => toggleTask(t.id)}>
                      {t.done && "✓"}
                    </div>
                  )}
                  <div className="task-info">
                    <div className={`task-name ${t.done ? "done" : ""}`}>{t.name}</div>
                    <div className="task-meta">
                      <span className={`task-subject ${t.tag}`}>{t.subject}</span>
                      <span className={`task-due ${t.urgent ? "urgent" : ""}`}>⏰ {t.due}</span>
                    </div>
                  </div>
                </div>
              ))}
            </div>
            <div className="panel">
              <div className="panel-title">✅ Completadas</div>
              {done.map(t => (
                <div key={t.id} className="task-item">
                  <div className={`priority-dot p-${t.priority}`} />
                  {!isParent && (
                    <div className={`task-check done`} onClick={() => toggleTask(t.id)}>✓</div>
                  )}
                  <div className="task-info">
                    <div className="task-name done">{t.name}</div>
                    <div className="task-meta">
                      <span className={`task-subject ${t.tag}`}>{t.subject}</span>
                      <span className="task-due">{t.due}</span>
                    </div>
                  </div>
                </div>
              ))}
            </div>
          </>
        )}

        {/* ── GRADES ── */}
        {tab === "grades" && (
          <>
            <div className="page-title">{isParent ? "Calificaciones de Alejandro" : "Mis Calificaciones"}</div>
            <div className="page-sub">Semestre Agosto–Diciembre 2025 · Parcial 2 de 3</div>
            <div className="stats-row" style={{ gridTemplateColumns: "repeat(3, 1fr)" }}>
              <div className="stat-card blue"><div className="stat-num">{avgGrade}</div><div className="stat-label">Promedio general</div></div>
              <div className="stat-card lime"><div className="stat-num">94</div><div className="stat-label">Nota más alta</div></div>
              <div className="stat-card red"><div className="stat-num">76</div><div className="stat-label">Nota más baja</div></div>
            </div>
            <div className="panel">
              <div className="panel-title">📊 Desglose por materia</div>
              {GRADES.map((g, i) => (
                <div key={i} className="grade-row">
                  <div>
                    <div className="grade-subject">{g.subject}</div>
                    <div style={{ fontSize: "0.78rem", color: "var(--muted)", marginTop: 2 }}>
                      {g.grade >= 90 ? "🏆 Excelente" : g.grade >= 80 ? "👍 Bien" : "⚠️ Requiere atención"}
                    </div>
                  </div>
                  <div className="grade-right">
                    <div className="grade-bar-wrap" style={{ width: 140 }}>
                      <div className="grade-bar" style={{ width: `${g.grade}%`, background: g.color }} />
                    </div>
                    <div className={`grade-num ${g.grade >= 90 ? "grade-a" : g.grade >= 80 ? "grade-b" : "grade-c"}`}>{g.grade}/100</div>
                  </div>
                </div>
              ))}
            </div>
          </>
        )}

        {/* ── SCHEDULE ── */}
        {tab === "schedule" && !isParent && (
          <>
            <div className="page-title">Mi Horario</div>
            <div className="page-sub">Semana actual · Miércoles 7 de mayo</div>
            <div className="grid-2">
              <div className="panel">
                <div className="panel-title">📅 Hoy — Miércoles</div>
                {SCHEDULE.map((s, i) => (
                  <div key={i} className="schedule-item">
                    <div className="schedule-time">{s.time}</div>
                    <div className="schedule-bar" style={{ background: s.color }} />
                    <div className="schedule-info">
                      <div className="sname">{s.name}</div>
                      <div className="sroom">{s.room}</div>
                    </div>
                  </div>
                ))}
              </div>
              <div className="panel">
                <div className="panel-title">🗓️ Calendario Mayo 2025</div>
                <div className="calendar-grid">
                  {DAYS.map(d => <div key={d} className="cal-header">{d}</div>)}
                  {calDays.map((d, i) => (
                    <div key={i} className={`cal-day ${d.today ? "today" : ""} ${d.hasTask ? "has-task" : ""} ${d.other ? "other" : ""}`}>
                      {d.n}
                    </div>
                  ))}
                </div>
                <div style={{ marginTop: 14, display: "flex", gap: 14, fontSize: "0.78rem", color: "var(--muted)" }}>
                  <span>● Hoy</span>
                  <span style={{ color: "var(--tec-red)" }}>● Con tarea</span>
                </div>
              </div>
            </div>
          </>
        )}

        {/* ── AI ── */}
        {tab === "ai" && !isParent && (
          <>
            <div className="page-title">Asistente de Estudio 🤖</div>
            <div className="page-sub">Tu tutor IA disponible 24/7 — pregunta sobre cualquier materia</div>
            <div className="panel">
              <div className="panel-title">💬 Chat con tu asistente</div>
              <div className="chat-box">
                {chatMsgs.map((m, i) => (
                  <div key={i} className={`chat-msg ${m.role}`}>
                    <div className={`chat-avatar ${m.role}`}>{m.role === "ai" ? "🤖" : "👤"}</div>
                    <div className="chat-bubble">{m.text}</div>
                  </div>
                ))}
              </div>
              <div className="chat-input-row">
                <input className="chat-input" placeholder="Pregunta sobre Cálculo, Física, Programación..." value={chatInput} onChange={e => setChatInput(e.target.value)} onKeyDown={e => e.key === "Enter" && sendChat()} />
                <button className="chat-send" onClick={sendChat}>➤</button>
              </div>
              <div style={{ marginTop: 14 }}>
                <div style={{ fontSize: "0.8rem", color: "var(--muted)", marginBottom: 8 }}>Sugerencias rápidas:</div>
                <div style={{ display: "flex", gap: 8, flexWrap: "wrap" }}>
                  {["Explícame integrales", "Ayuda con Física", "Repasar álgebra", "¿Cómo hago mi proyecto?"].map(s => (
                    <button key={s} onClick={() => { setChatInput(s); }} style={{ padding: "6px 14px", border: "2px solid var(--border)", borderRadius: 20, fontSize: "0.8rem", cursor: "pointer", background: "var(--bg)", fontFamily: "DM Sans" }}>{s}</button>
                  ))}
                </div>
              </div>
            </div>
          </>
        )}

        {/* ── PARENT ALERTS ── */}
        {tab === "alerts" && isParent && (
          <>
            <div className="page-title">Alertas y Notificaciones 🔔</div>
            <div className="page-sub">Mantente informado sobre el progreso de Alejandro</div>
            <div className="panel">
              <div className="panel-title">⚠️ Alertas activas</div>
              <div className="alert-card danger">
                <div className="alert-icon">🚨</div>
                <div>
                  <div className="alert-title">Tarea vence HOY — Cálculo II</div>
                  <div className="alert-desc">La Tarea 3 sobre integrales definidas vence a las 11:59 PM. Alejandro aún no la ha marcado como entregada.</div>
                </div>
              </div>
              <div className="alert-card warning">
                <div className="alert-icon">📁</div>
                <div>
                  <div className="alert-title">Proyecto final — Programación Avanzada</div>
                  <div className="alert-desc">El sistema de inventario debe entregarse mañana. Es una calificación de alto impacto.</div>
                </div>
              </div>
              <div className="alert-card ok">
                <div className="alert-icon">🏆</div>
                <div>
                  <div className="alert-title">Excelente en Programación</div>
                  <div className="alert-desc">Alejandro obtuvo 94/100 en el último parcial. ¡Va muy bien en esta materia!</div>
                </div>
              </div>
              <div className="alert-card ok">
                <div className="alert-icon">✅</div>
                <div>
                  <div className="alert-title">2 tareas completadas esta semana</div>
                  <div className="alert-desc">Álgebra Lineal y Laboratorio de Física fueron entregadas a tiempo.</div>
                </div>
              </div>
              <div className="alert-card warning">
                <div className="alert-icon">📉</div>
                <div>
                  <div className="alert-title">Física I requiere atención</div>
                  <div className="alert-desc">Calificación actual: 76/100. Puede mejorar asistiendo a tutorías los martes de 4–6 PM.</div>
                </div>
              </div>
            </div>
          </>
        )}

      </div>
    </div>
  </div>
</>
```

);
}
