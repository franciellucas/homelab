# 🧪 Homelab de Segurança

Ambiente de laboratório **isolado** para praticar defesa, detecção e resposta —
base dos meus projetos de portfólio. Montado do zero e documentado.

> ⚠️ Ambiente fechado, sem acesso à minha rede real. Tudo aqui é para estudo.

## 🧱 Componentes e status
| # | Componente | Status |
|---|---|---|
| T1.1 | VM base + rede isolada (host-only/NAT) | 🚧 |
| T1.2 | Windows Server + Active Directory + 1 cliente | ⬜ |
| T1.3 | Linux endurecido (CIS / Lynis) | ⬜ |
| T1.4 | Wazuh (SIEM/XDR) coletando dos hosts | ⬜ |
| T1.5 | Firewall (pfSense/OPNsense) segmentando a rede | ⬜ |
| T1.6 | Ataque simulado detectado no Wazuh | ⬜ |

Legenda: ⬜ a fazer · 🚧 em andamento · ✅ concluído

## 📂 Estrutura
- `diagrams/` — diagramas de rede e topologia
- `windows-ad/` — configuração do AD, GPOs, prints
- `linux-hardening/` — checklist CIS, antes/depois, Lynis
- `wazuh/` — instalação, agentes, regras, dashboards
- `firewall/` — regras documentadas
- `attack-sim/` — ataques simulados e o que foi detectado
