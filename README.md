# Grupo-de-salud-integral-ayacucho
:root{--primary:#0f5ba7;--accent:#28b463;--bg:#f5f7fa}
*{box-sizing:border-box} body{margin:0;font-family:Segoe UI,Arial,sans-serif;background:var(--bg);color:#1f2937}
header{background:#fff;position:sticky;top:0;padding:16px 24px;display:flex;justify-content:space-between;align-items:center;box-shadow:0 2px 8px rgba(0,0,0,.08)}
nav a{margin:0 10px;text-decoration:none;color:var(--primary);font-weight:600}
.hero{padding:80px 24px;background:linear-gradient(135deg,#eaf4ff,#fff)}
.container{max-width:1200px;margin:auto;padding:40px 20px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
.card{background:#fff;padding:20px;border-radius:20px;box-shadow:0 2px 10px rgba(0,0,0,.08)}
.btn{display:inline-block;background:var(--primary);color:#fff;padding:12px 18px;border-radius:10px;text-decoration:none}
footer{background:#083b6d;color:#fff;padding:40px;text-align:center}
form input,form textarea,form select{width:100%;padding:12px;margin:8px 0;border:1px solid #ddd;border-radius:8px}
@media(max-width:768px){header{flex-direction:column}}
