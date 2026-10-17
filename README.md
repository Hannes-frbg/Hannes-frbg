<h1 align="center">Hannes Schuler</h1>
<p align="center">
  <em>Homelab Architecture & Systems Engineering</em>
</p>

<p align="center">
  <a href="https://github.com/Hannes-frbg">
    <img src="https://img.shields.io/badge/GitHub-Hannes--frbg-24292e?style=flat&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="mailto:info@ewigetiomate.de">
    <img src="https://img.shields.io/badge/Email-info%40ewigetiomate.de-111111?style=flat&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

### Über mich
System- und Infrastruktur-Entwickler mit Fokus auf Virtualisierung, Netzwerk-Automatisierung und performante Backends. Spezialisiert auf den Betrieb eigenständiger Enterprise-Umgebungen auf Basis von Proxmox VE und Linux.

---

### 📊 GitHub & Coding Stats

<p align="center">
  <!-- GitHub Stats (Total Contributions, Commits, etc.) -->
  <img src="https://github-readme-stats.vercel.app/api?username=Hannes-frbg&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
</p>

<p align="center">
  <!-- Top Languages Card (Tortendiagramm wie auf deinem Screenshot) -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hannes-frbg&layout=donut&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <!-- GitHub Streak Stats -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Hannes-frbg&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

### 🛠️ Homelab & Core Specs
* **Hypervisor Layer:** Heterogenes 2-Node Proxmox-Setup (Standalone-Entkopplung für maximale Stabilität).
* **Compute Node (PVE 1):** AMD Ryzen 5 5600GT (Performance Governor, fixierter Takt), ZFS High-Performance SSD Pool, Pelican Panel & Docker-Containerisierung.
* **Backup & Gateway Node (PVE 2):** Intel Core i5-7500T, nativer Proxmox Backup Server (PBS) mit inkrementellen Block-Level-Backups, SHA-256 Deduplizierung und Offsite-Sync.
* **Security & Ingress:** Cloudflare Zero Trust Tunnels kombiniert mit einem eigenem Node.js-Reverse-Proxy-Gateway (RFC 6238 TOTP-Authentifizierung).
