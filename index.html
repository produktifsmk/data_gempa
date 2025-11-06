<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>🌍 BMKG Dashboard</title>

<style>
:root {
  --primary: #00b4d8;
  --secondary: #0077b6;
  --light: #caf0f8;
  --dark: #03045e;
}
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: radial-gradient(circle at center, #000010, #000020);
  color: #fff;
  overflow-x: hidden;
}
canvas#stars3d {
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  z-index: -1;
}
.container {
  max-width: 420px;
  margin: 70px auto;
  padding: 20px;
  border-radius: 18px;
  background: rgba(255, 255, 255, 0.08);
  backdrop-filter: blur(14px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.5);
}
h1 {
  text-align: center;
  font-size: 1.6em;
  color: var(--light);
  text-shadow: 0 0 10px #00eaff;
  margin-bottom: 10px;
}
.subtitle {
  text-align: center;
  color: #a8dadc;
  margin-bottom: 25px;
  font-size: 0.9em;
  font-style: italic;
}
.card {
  background: rgba(255,255,255,0.1);
  border-radius: 14px;
  padding: 15px;
  margin-bottom: 25px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.3);
  transition: 0.3s;
}
.card:hover {
  transform: scale(1.02);
  background: rgba(255,255,255,0.18);
}
h2 {
  color: #fff;
  text-align: center;
  border-bottom: 2px solid var(--secondary);
  font-size: 1em;
  padding-bottom: 5px;
  margin-bottom: 10px;
}
.search-box {
  text-align: center;
  margin: 10px 0;
}
.search-box input {
  width: 85%;
  padding: 8px;
  border: none;
  border-radius: 14px;
  text-align: center;
  font-size: 14px;
  outline: none;
  background: rgba(255,255,255,0.15);
  color: white;
}
table {
  width: 100%;
  border-collapse: collapse;
  color: #fff;
  font-size: 12px;
}
th, td {
  padding: 6px;
  border-bottom: 1px solid rgba(255,255,255,0.15);
}
th {
  background: rgba(0,119,182,0.7);
}
tr:hover {
  background: rgba(0, 183, 255, 0.12);
}
img {
  width: 28px;
  height: 28px;
}
.add-form {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(110px, 1fr));
  gap: 6px;
  margin-top: 10px;
}
.add-form input {
  padding: 6px;
  border: none;
  border-radius: 8px;
  background: rgba(255,255,255,0.1);
  color: white;
  font-size: 12px;
}
.add-form button {
  background: var(--secondary);
  color: #fff;
  border: none;
  border-radius: 8px;
  padding: 8px;
  cursor: pointer;
  font-size: 13px;
  transition: 0.3s;
}
.add-form button:hover { background: var(--primary); transform: scale(1.05); }
.btn-hapus {
  background: #ff595e;
  border: none;
  color: white;
  padding: 4px 8px;
  border-radius: 6px;
  cursor: pointer;
  font-size: 11px;
}
.btn-hapus:hover {
  background: #ff1e1e;
}
.footer {
  text-align: center;
  color: #bde0fe;
  margin-top: 25px;
  font-size: 0.8em;
}
</style>
</head>
<body>

<canvas id="stars3d"></canvas>

<div class="container">
  <h1>🌍 BMKG Dashboard</h1>
  <p class="subtitle">Data Gempa & Cuaca - versi ringan</p>

  <div class="card">
    <h2>📉 Data Gempa</h2>
    <div class="search-box">
      <input type="text" id="searchGempa" placeholder="Cari wilayah...">
    </div>
    <table id="tabelGempa">
      <tr><th>No</th><th>Tanggal</th><th>Wilayah</th><th>Magnitudo</th><th>Aksi</th></tr>
      <tr><td>1</td><td>05 Nov 2025</td><td>BONEBOLANGO</td><td><b style="color:#ff595e">6.2</b></td><td><button class="btn-hapus">Hapus</button></td></tr>
      <tr><td>2</td><td>04 Nov 2025</td><td>HALMAHERABARAT</td><td><b style="color:#ff595e">5.1</b></td><td><button class="btn-hapus">Hapus</button></td></tr>
    </table>
    <div class="add-form">
      <input id="tgl" placeholder="Tanggal">
      <input id="wilayah" placeholder="Wilayah">
      <input id="mag" placeholder="Magnitudo">
      <button id="tambahGempa">Tambah</button>
    </div>
  </div>

  <div class="card">
    <h2>🌦️ Cuaca Kemayoran</h2>
    <table id="tabelCuaca">
      <tr><th>Waktu</th><th>Suhu</th><th>Keterangan</th><th>Ikon</th><th>Aksi</th></tr>
      <tr><td>09:00</td><td>30°C</td><td>Berawan</td><td><img src="https://api-apps.bmkg.go.id/storage/icon/cuaca/berawan-am.svg"></td><td><button class="btn-hapus">Hapus</button></td></tr>
      <tr><td>15:00</td><td>27°C</td><td>Hujan Ringan</td><td><img src="https://api-apps.bmkg.go.id/storage/icon/cuaca/hujan ringan-am.svg"></td><td><button class="btn-hapus">Hapus</button></td></tr>
    </table>
    <div class="add-form">
      <input id="waktu" placeholder="Waktu">
      <input id="suhu" placeholder="Suhu °C">
      <input id="ket" placeholder="Keterangan">
      <input id="ikon" placeholder="URL Ikon">
      <button id="tambahCuaca">Tambah</button>
    </div>
  </div>

  <p class="footer">© 2025 BMKG Dashboard | Gabriel Hutasoit</p>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script>
// === LATAR BELAKANG BINTANG 3D ===
const canvas = document.getElementById("stars3d");
const scene = new THREE.Scene();
const camera = new THREE.PerspectiveCamera(75, innerWidth / innerHeight, 0.1, 1000);
const renderer = new THREE.WebGLRenderer({ canvas, alpha: true });
renderer.setSize(innerWidth, innerHeight);
renderer.setPixelRatio(devicePixelRatio);

const starsGeometry = new THREE.BufferGeometry();
const starVertices = [];
for (let i = 0; i < 2500; i++) {
  const x = (Math.random() - 0.5) * 2000;
  const y = (Math.random() - 0.5) * 2000;
  const z = -Math.random() * 2000;
  starVertices.push(x, y, z);
}
starsGeometry.setAttribute('position', new THREE.Float32BufferAttribute(starVertices, 3));
const starsMaterial = new THREE.PointsMaterial({ color: 0xffffff, size: 1 });
const stars = new THREE.Points(starsGeometry, starsMaterial);
scene.add(stars);
camera.position.z = 1;

function animate() {
  requestAnimationFrame(animate);
  stars.rotation.x += 0.0003;
  stars.rotation.y += 0.0005;
  renderer.render(scene, camera);
}
animate();

// === FITUR TAMBAH GEMPA ===
document.getElementById("tambahGempa").addEventListener("click", () => {
  const tgl = document.getElementById("tgl").value;
  const wilayah = document.getElementById("wilayah").value;
  const mag = document.getElementById("mag").value;
  if (!tgl || !wilayah || !mag) return alert("Lengkapi data!");
  const tabel = document.getElementById("tabelGempa");
  const row = tabel.insertRow(-1);
  const no = tabel.rows.length - 1;
  row.innerHTML = `<td>${no}</td><td>${tgl}</td><td>${wilayah}</td><td><b style='color:#ff595e'>${mag}</b></td><td><button class='btn-hapus'>Hapus</button></td>`;
  tambahEventHapus();
  document.querySelectorAll(".add-form input").forEach(i => i.value = "");
});

// === FITUR TAMBAH CUACA ===
document.getElementById("tambahCuaca").addEventListener("click", () => {
  const waktu = document.getElementById("waktu").value;
  const suhu = document.getElementById("suhu").value;
  const ket = document.getElementById("ket").value;
  const ikon = document.getElementById("ikon").value || "https://api-apps.bmkg.go.id/storage/icon/cuaca/berawan-am.svg";
  if (!waktu || !suhu || !ket) return alert("Lengkapi data!");
  const tabel = document.getElementById("tabelCuaca");
  const row = tabel.insertRow(-1);
  row.innerHTML = `<td>${waktu}</td><td>${suhu}°C</td><td>${ket}</td><td><img src='${ikon}'></td><td><button class='btn-hapus'>Hapus</button></td>`;
  tambahEventHapus();
  document.querySelectorAll(".add-form input").forEach(i => i.value = "");
});

// === FITUR HAPUS DATA ===
function tambahEventHapus() {
  document.querySelectorAll(".btn-hapus").forEach(btn => {
    btn.onclick = () => {
      if (confirm("Hapus data ini?")) btn.closest("tr").remove();
    };
  });
}
tambahEventHapus();

// === FITUR PENCARIAN GEMPA ===
document.getElementById("searchGempa").addEventListener("keyup", function() {
  const val = this.value.toLowerCase();
  document.querySelectorAll("#tabelGempa tr:not(:first-child)").forEach(tr => {
    tr.style.display = tr.textContent.toLowerCase().includes(val) ? "" : "none";
  });
});
</script>
</body>
</html>
