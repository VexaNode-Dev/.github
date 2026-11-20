<div align="center">
  <img src="banner.svg" alt="VexaNode Open Source" width="100%" />

  <p>
    <b>Open-source developer utilities, bot templates, and infrastructure tooling.</b><br/>
    Maintained by the engineering team at <a href="https://vexanode.gg">VexaNode</a>.
  </p>

  <p>
    <a href="https://vexanode.gg"><img src="https://img.shields.io/badge/website-vexanode.gg-0f172a?style=flat-square&logo=googlechrome&logoColor=38bdf8" alt="Website" /></a>
    <a href="https://discord.gg/devz"><img src="https://img.shields.io/badge/discord-join%20community-0f172a?style=flat-square&logo=discord&logoColor=5865F2" alt="Discord" /></a>
    <a href="https://github.com/VexaNode-Dev"><img src="https://img.shields.io/badge/org-VexaNode--Dev-0f172a?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>
</div>

---

### Repositories

| Project | Stack | Description |
| :--- | :--- | :--- |
| **[`server-log-analyzer`](https://github.com/VexaNode-Dev/server-log-analyzer)** | Node.js / CLI | Fast deep log search and crash diagnosis tool. Parses raw and compressed (`.gz`) logs for Minecraft, Discord bots, and Linux services. |
| **[`minecraft-server-optimization-guide`](https://github.com/VexaNode-Dev/minecraft-server-optimization-guide)** | Paper / Purpur / Node.js | Benchmarked configuration guide, production presets, and automated `mc-perf-audit` config scanning tool. |
| **[`discordjs-v14-bot-template`](https://github.com/VexaNode-Dev/discordjs-v14-bot-template)** | TypeScript / Discord.js v14 | Production bot starter with typed slash commands, Zod environment validation, graceful shutdowns, and Docker containerization. |
| **[`discordpy-bot-template`](https://github.com/VexaNode-Dev/discordpy-bot-template)** | Python 3.11+ / Discord.py 2.x | Asynchronous bot foundation with modular Cogs architecture, slash command sync, and async SQLite storage. |
| **[`pterodactyl-backup-manager`](https://github.com/VexaNode-Dev/pterodactyl-backup-manager)** | Node.js / Client API | Automated backup automation, offsite downloading, retention pruning, and Discord webhook failure/success alerts for Pterodactyl. |
| **[`docker-server-monitoring`](https://github.com/VexaNode-Dev/docker-server-monitoring)** | Docker Compose / Prometheus | Pre-configured monitoring stack (Prometheus, Grafana, Node Exporter, cAdvisor) with alert rules and custom dashboard JSON. |
| **[`node-vps-deploy`](https://github.com/VexaNode-Dev/node-vps-deploy)** | Bash / Ubuntu & Debian | Minimal VPS hardening script automating UFW firewall, fail2ban, Node.js LTS, PM2, and Nginx reverse proxy with SSL. |

---

### Command-Line Tools

Run utilities directly using Node or Git:

```bash
# Deep search and analyze server logs for crashes or OOM
git clone https://github.com/VexaNode-Dev/server-log-analyzer.git
node server-log-analyzer/bin/cli.js /path/to/server/logs --crashes

# Audit Minecraft server configuration files
git clone https://github.com/VexaNode-Dev/minecraft-server-optimization-guide.git
node minecraft-server-optimization-guide/bin/mc-perf-audit.js /path/to/server
```

---

### About VexaNode

We provide low-latency cloud infrastructure engineered specifically for gaming networks and bot developers:

- **[Discord Bot Hosting](https://vexanode.gg):** Containerized runtimes for Node.js, Python, Java, and Go with 24/7 uptime monitoring.
- **[Minecraft Server Hosting](https://vexanode.gg):** Dedicated single-thread performance powered by AMD Ryzen 9 series hardware and NVMe storage.
- **[KVM VPS Instances](https://vexanode.gg):** High-bandwidth Linux virtual servers with enterprise DDoS mitigation.

---

### Community & Contributing

- Join our developer community on Discord: **[discord.gg/devz](https://discord.gg/devz)**
- All tools are open-sourced under the **MIT License**. Bug reports, feature suggestions, and pull requests are welcomed across all repositories.
