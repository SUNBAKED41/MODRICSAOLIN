<!DOCTYPE html>
</aside>
</div>
</section>


<section id="clips" class="section">
<h2>Clips destacados</h2>
<p class="muted">Sustituye las URL por clips reales de TikTok.</p>
<div class="grid" style="grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap:16px">
<div class="card pad"><iframe title="Clip 1" loading="lazy" style="width:100%; aspect-ratio:9/16; border:0; border-radius:16px" srcdoc="<style>body{margin:0;background:#000;color:#fff;display:grid;place-items:center;font:16px sans-serif}</style><body>Clip 1 — Pega aquí el embed</body>"></iframe></div>
<div class="card pad"><iframe title="Clip 2" loading="lazy" style="width:100%; aspect-ratio:9/16; border:0; border-radius:16px" srcdoc="<style>body{margin:0;background:#000;color:#fff;display:grid;place-items:center;font:16px sans-serif}</style><body>Clip 2 — Pega aquí el embed</body>"></iframe></div>
<div class="card pad"><iframe title="Clip 3" loading="lazy" style="width:100%; aspect-ratio:9/16; border:0; border-radius:16px" srcdoc="<style>body{margin:0;background:#000;color:#fff;display:grid;place-items:center;font:16px sans-serif}</style><body>Clip 3 — Pega aquí el embed</body>"></iframe></div>
</div>
</section>


<section id="agenda" class="section">
<div class="grid cards">
<div class="card pad col-6">
<h2 style="margin-top:0">Agenda</h2>
<ul>
<li><strong>Sept 12</strong> — Grabación especial en estudio</li>
<li><strong>Sept 28</strong> — Encuentro con fans (Madrid)</li>
<li><strong>Oct 05</strong> — Colaboración con creador sorpresa</li>
</ul>
</div>
<div class="card pad col-6">
<h2 style="margin-top:0">Contratación</h2>
<p>¿Quieres a Modric Saolin en tu evento, campaña o colaboración? Envíanos los detalles y te responderemos.</p>
<form class="grid" style="grid-template-columns:1fr 1fr; gap:12px" onsubmit="event.preventDefault(); alert('¡Gracias! Te contactaremos pronto.')">
<input class="card pad" style="padding:12px" placeholder="Nombre" required />
<input class="card pad" style="padding:12px" placeholder="Email" type="email" required />
<input class="card pad" style="padding:12px; grid-column:1/-1" placeholder="Asunto" />
<textarea class="card pad" style="padding:12px; grid-column:1/-1; min-height:120px" placeholder="Mensaje"></textarea>
<button class="cta" type="submit" style="border:0; cursor:pointer">Enviar</button>
</form>
</div>
</div>
</section>


<section id="galeria" class="section">
<h2>Galería</h2>
<div class="grid" style="grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap:12px">
<img class="card" alt="Foto 1" style="width:100%; aspect-ratio:1/1; object-fit:cover" src="https://images.unsplash.com/photo-1515378791036-0648a3ef77b2?q=80&w=1200&auto=format&fit=crop" />
<img class="card" alt="Foto 2" style="width:%; aspect-ratio:1/1; object-fit:cover" src="https://images.unsplash.com/photo-1515168833906-d2a3b82b302f?q=80&w=1200&auto=format&fit=crop" />
<img class="card" alt="Foto 3" style="width:100%; aspect-ratio:1/1; object-fit:cover" src="https://images.unsplash.com/photo-1520975930058-0e4a9b4330a4?q=80&w=1200&auto=format&fit=crop" />
<img class="card" alt="Foto 4" style="width:100%; aspect-ratio:1/1; object-fit:cover" src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1200&auto=format&fit=crop" />
</div>
</section>100


</main>


<footer class="container footer" id="contacto">
<div style="display:flex; align-items:center; justify-content:space-between; gap:12px; flex-wrap:wrap">
<div>© <span id="year"></span> Modric Saolin — Todos los derechos reservados</div>
<div class="links">
<a class="pill" href="#">Aviso legal</a>
<a class="pill" href="#">Privacidad</a>
<a class="pill" href="#">Cookies</a>
</div>
</div>
</footer>


<script>
// Relleno de estadísticas ficticias (puedes sustituir por valores reales)
const k = n => new Intl.NumberFormat('es-ES',{notation:'compact'}).format(n);
document.getElementById('followers').textContent = k(1234000);
document.getElementById('likes').textContent = k(9870000);
document.getElementById('views').textContent = k(56000000);
document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>
