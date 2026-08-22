<div align="center">

# ⚡ INCONTROL PLUS ЕООД
### Enterprise Fintech Infrastructure • Zero-Config Virtualization • Distributed Edge Mesh

[![Edge SLA](https://img.shields.io/badge/Edge%20SLA-99.99%25%20Uptime-06b6d4?style=for-the-badge&logo=cloudflare&logoColor=white)](https://openbalancer.com)
[![WCAG](https://img.shields.io/badge/Accessibility-WCAG%202.2%20AAA-10b981?style=for-the-badge&logo=w3c&logoColor=white)](https://dashboard.openbalancer.com)
[![Security](https://img.shields.io/badge/Security-Strict%20CSP%20%26%20Zero%20CDN-6366f1?style=for-the-badge&logo=auth0&logoColor=white)](https://openbalancer.com)
[![Mesh Network](https://img.shields.io/badge/Network-Tailscale%20WireGuard-0ea5e9?style=for-the-badge&logo=tailscale&logoColor=white)](https://dashboard.openbalancer.com)
[![License](https://img.shields.io/badge/License-MIT%20%2F%20Enterprise-3b82f6?style=for-the-badge)](https://github.com/incontrolplus)

<br>

<p align="center">
  <b>INCONTROL PLUS ЕООД</b> engineers mission-critical fintech automation, distributed edge mesh networks, and zero-config headless virtualization systems for corporate clients in the EU.
</p>

[🌐 **Corporate Portal**](https://openbalancer.com) • [📊 **Cluster Telemetry**](https://dashboard.openbalancer.com) • [💳 **Fintech & Cashflow**](https://cashflow.openbalancer.com) • [🖥️ **Windows 11 Gateway**](https://win.openbalancer.com)

---

</div>

## 🏛️ Flagship Production Platforms

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📊 Open Balancer Telemetry Hub</h3>
      <p>Real-time SSOT infrastructure monitor overseeing a 10-node distributed cluster mesh, edge latencies, and SSL certificate lifecycles with WCAG 2.2 AAA dark glassmorphism.</p>
      <ul>
        <li><b>Live SSOT:</b> <a href="https://dashboard.openbalancer.com">dashboard.openbalancer.com</a></li>
        <li><b>Source:</b> <a href="https://github.com/incontrolplus/openbalancer-dashboard"><code>incontrolplus/openbalancer-dashboard</code></a></li>
        <li><b>Stack:</b> React 18, TypeScript, Tailwind CSS, Vite, Cloudflare Pages</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🖥️ Portable Windows 11 QEMU VM</h3>
      <p>Automated zero-config portable Windows 11 virtual machine launcher with hardware requirement bypasses, noVNC browser gateway, and NFS byte-locking protection.</p>
      <ul>
        <li><b>Live Gateway:</b> <a href="https://win.openbalancer.com">win.openbalancer.com</a></li>
        <li><b>Source:</b> <a href="https://github.com/incontrolplus/portable-windows-11-qemu"><code>incontrolplus/portable-windows-11-qemu</code></a></li>
        <li><b>Stack:</b> QEMU, websockify, noVNC, Bash, Apple Silicon TCG / HVF</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💳 Wallestars B2B Cashflow</h3>
      <p>B2B corporate card issuing framework, cashflow automation, and Bulgarian Commercial Register API beneficial ownership derivation with Mod 11 validation.</p>
      <ul>
        <li><b>Live Gateway:</b> <a href="https://cashflow.openbalancer.com">cashflow.openbalancer.com</a></li>
        <li><b>Source:</b> <a href="https://github.com/incontrolplus/finans-protect-monorepo"><code>incontrolplus/finans-protect-monorepo</code></a></li>
        <li><b>Stack:</b> Node.js, Express, CompanyBook REST API, Supabase, Tailwind</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ Open Balancer Core Reverse Proxy</h3>
      <p>High-throughput asynchronous reverse proxy and load balancer with active circuit breaking, Prometheus metrics export, and health check routing.</p>
      <ul>
        <li><b>Live Edge:</b> <a href="https://openbalancer.com">openbalancer.com</a></li>
        <li><b>Source:</b> <a href="https://github.com/incontrolplus/openbalancer"><code>incontrolplus/openbalancer</code></a></li>
        <li><b>Stack:</b> Python, AsyncIO, Docker, Prometheus, Grafana (MIT)</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🌐 Distributed Cluster Mesh Architecture

```mermaid
graph TD
    subgraph "🌍 Cloudflare Global Edge"
        CF1["openbalancer.com<br/>(Core B2B Portal)"]
        CF2["dashboard.openbalancer.com<br/>(SSOT Cluster Monitor)"]
        CF3["cashflow.openbalancer.com<br/>(Wallestars Gateway)"]
        CF4["win.openbalancer.com<br/>(noVNC Web Portal)"]
        EDGE_WORKER["Cloudflare Edge Worker API<br/>(/api/health, /api/registry/check)"]
    end

    subgraph "🔒 Private Tailscale WireGuard Mesh"
        PRIMARY["🖥️ Primary Node (Leon)<br/>n8n • Supabase • Infisical KMS • Firecrawl"]
        SECONDARY["💾 Secondary Node (Leon2)<br/>QEMU Windows 11 VM • PHILIPS_SSD"]
        AIR["💻 DevOps Station (MacBook Air)<br/>Agent CLI • WebChat • SSOT Sync"]
    end

    CF1 --> EDGE_WORKER
    CF2 --> EDGE_WORKER
    CF3 --> EDGE_WORKER
    CF4 --> SECONDARY
    EDGE_WORKER -.-> PRIMARY
    PRIMARY <==>|Encrypted WireGuard| SECONDARY
    PRIMARY <==>|Encrypted WireGuard| AIR
```

---

## 🛡️ Enterprise Security & Regulatory Compliance

- **Bulgarian Commercial Register Integration**: Live Mod 11 checksum verification for company identification numbers (ЕИК/Булстат) and automated beneficial owner share derivation (>= 50%).
- **National Revenue Agency (НАП) Accounting**: CP1251 byte-accurate sales/purchases VAT triplet export (`DEKLAR.TXT`, `POKUPKI.TXT`, `PRODAGBI.TXT`).
- **Zero CDN & Strict CSP Policy**: Complete elimination of runtime external scripts (`cdn.tailwindcss.com`, `unpkg.com`) with self-hosted assets to guarantee zero supply-chain vulnerabilities.
- **Two-Tier KMS Key Derivation**: AES-256-GCM secret management powered by self-hosted Infisical vaults across developer and production environments.

---

## 📞 Enterprise Inquiries & SLA Support

- **Operating Entity:** INCONTROL PLUS ЕООД
- **Headquarters:** Sofia, Republic of Bulgaria
- **Official Portal:** [https://openbalancer.com](https://openbalancer.com)
- **Corporate Email:** [incontrolplusltd@gmail.com](mailto:incontrolplusltd@gmail.com)
- **SLA Response Window:** < 2 Hours for Enterprise Retainer Partners

<br>

<div align="center">
  <sub>© 2026 INCONTROL PLUS ЕООД. All rights reserved. Powered by Open Balancer.</sub>
</div>
