# Bruno Mattos

**Infrastructure & Automation Engineer** · Porto Alegre, Brazil · 🇧🇷 [Versão em português ↓](#-em-português)

I take a business problem and carry it end to end: **network → servers → data → application → security**. Then I keep it running in production, with tests, monitoring and docs.

At [Guarida](https://www.guarida.com.br), a large real-estate company in southern Brazil, I run infrastructure and build the software on top of it:

- **Contact-center telephony.** Asterisk/FreePBX with ~150 extensions. A real-time call data warehouse in .NET. I'm building the telephony module of the new omnichannel platform: Asterisk 22 in HA, infrastructure as code, live transcription.
- **Internal platforms.** **G-Live**, a webinar platform that replaced Zoom Webinar (load-tested at 500 viewers, p95 116 ms). **GBI**, the company's BI portal (787 users).
- **Data & automation.** ETL into a DW, Airflow-orchestrated RPAs, and a banking-file pipeline (CNAB) with 0 errors across 573 runs/day.
- **Infra & security.** ~18 servers (Linux/Windows, Hyper-V cluster), 7 FortiGates, 42 UniFi APs, a 678 GB PostgreSQL ERP, Active Directory hardening after a ransomware incident, an internal pentest and a GCP posture audit (526 projects).

**~6,000 commits and thousands of automated tests in 2026**, mostly in private company repos ([@brunooutcore](https://github.com/brunooutcore) and Azure DevOps). This profile holds my open-source work and case studies.

### How I work

Design first (spec → plan → code), TDD, CI/CD and decision logs. I'm an **AI-native engineer**: I define the problem, design the architecture, review and ship, and I use AI agents as my execution tool. I also build my own tooling for that: MCP servers, Claude Code skills, and multi-agent code audits.

### Open source

| | |
|---|---|
| [**db-mcp**](https://github.com/brunocmattos/db-mcp) | Read-only MCP server for SQL databases (Postgres · MySQL · SQL Server). Gives AI agents schema introspection and `SELECT` without any write path. Python, FastMCP, mypy strict, CI. |
| [**mtg-brain**](https://github.com/brunocmattos/mtg-brain) | Local "brain" for Magic: The Gathering: full card and combo database, API, React app, hybrid semantic search and an MCP server. Runs at US$ 0. |

### Stack

**Languages** · Python · C#/.NET · PHP/Laravel · TypeScript/Node · SQL · PowerShell · Bash
**Data** · PostgreSQL · MySQL · SQL Server · Airflow · DuckDB · Grafana
**Infra** · Linux · Windows Server/AD · Hyper-V · Docker · Ansible · nginx · GitHub Actions · Azure DevOps · GCP
**Network & voice** · FortiGate · UniFi · VPN/IPsec · Asterisk · SIP/WebRTC
**Security** · Pentest (AD kill chains) · cloud posture (CSPM) · hardening · LGPD
**AI** · MCP · Claude Code (custom skills and agents)

📫 [LinkedIn](https://www.linkedin.com/in/brunocmattos) · Open to **Infra / DevOps / SRE / Platform** roles, remote (Brazil & international) · Fluent English

---

## 🇧🇷 Em português

**Engenheiro de Infraestrutura & Automação.** Pego um problema de negócio e levo de ponta a ponta, da rede ao servidor, ao dado, à aplicação e à segurança, e mantenho rodando em produção com teste, monitoramento e documentação.

Na [Guarida](https://www.guarida.com.br) eu cuido da infraestrutura e construo o software em cima dela:
- **Telefonia do contact center:** Asterisk com ~150 ramais, DW de chamadas em tempo real e o módulo de telefonia da nova plataforma omnichannel (Asterisk 22 em alta disponibilidade, infra como código, transcrição ao vivo).
- **Plataformas internas:** o **G-Live**, webinar próprio que substituiu o Zoom, e o **GBI**, portal de BI com 787 usuários.
- **Dados e automação:** ETL, RPAs no Airflow e a esteira de arquivos bancários (CNAB).
- **Infra e segurança:** ~18 servidores, 7 FortiGates, 42 APs, ERP PostgreSQL de 678 GB, hardening de AD pós-ransomware, pentest interno e auditoria de nuvem GCP.

São **~6.000 commits e milhares de testes em 2026**, a maior parte em repositórios privados. Aqui ficam o open-source e os cases. Trabalho *AI-native*: eu defino, desenho, reviso e coloco em produção, e construo minhas próprias ferramentas de agente.
