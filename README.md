# 📌 Política de Segurança da Informação - InnovaTech

<div align="center">
  
![Status](https://img.shields.io/badge/Status-Em%20Vigor-brightgreen)
![Versão](https://img.shields.io/badge/Versão-1.0-blue)
![LGPD](https://img.shields.io/badge/LGPD-Conforme-yellow)

</div>

---

## 📋 Sumário
- [1. Contexto](#-1-contexto)
- [2. Governança](#-2-governança)
- [3. Análise de Riscos](#-3-análise-de-riscos)
- [4. Diretrizes de Segurança](#-4-diretrizes-de-segurança)
- [5. Regras Disciplinares](#-5-regras-disciplinares)
- [6. Termo de Ciência](#-6-termo-de-ciência)

---

## 🏢 1. Contexto

**InnovaTech Solutions** - SaaS para setor financeiro

### Ativos Críticos
| Local | Criticidade |
|:---|:---:|
| ☁️ AWS (Produção) | 🔴 Alta |
| 🖥️ Sala Servidores | 🔴 Alta |
| 💻 Setor Dev | 🟡 Média |
| 📁 Setor RH | 🔴 Alta |

---

## 👥 2. Governança

| Membro | Cargo |
|:---|:---|
| Ana Souza | CISO |
| Carlos Lima | Gestor TI |
| Mariana Costa | DPO |
| João Pedro | RH |

---

## 📊 3. Análise de Riscos

```mermaid
quadrantChart
    title Matriz de Riscos
    x-axis Probabilidade -->
    y-axis Impacto -->
    quadrant-1 "CRÍTICO"
    quadrant-2 "MONITORAR"
    quadrant-3 "ACEITÁVEL"
    quadrant-4 "OBSERVAR"
    "Ransomware": [0.85, 0.95]
    "Phishing": [0.90, 0.70]
    "Falha Elétrica": [0.30, 0.85]
    "Vazamento": [0.40, 0.95]


## 📊 Análise de Riscos

| Risco | Prioridade |
|:---:|:---:|
| 🦠 Ransomware | 🔴 **MÁXIMA** |
| 🎣 Phishing | 🟠 **ALTA** |
| 💣 Vazamento | 🟠 **ALTA** |
| ⚡ Falha Energia | 🟡 **MÉDIA** |

---

## 🔒 4. Diretrizes de Segurança

### 🛡️ Confidencialidade

| Regra | Exigência |
|:---|:---|
| ✅ **MFA** | Obrigatório em sistemas críticos |
| ✅ **Criptografia** | Notebooks (BitLocker) + VPN |
| ✅ **Acesso Mínimo** | Revisão mensal de acessos |

---

### 📝 Integridade

| Regra | Especificação |
|:---|:---|
| ✅ **Backup** | 3-2-1 (3 cópias, 2 mídias, 1 off-site) |
| ✅ **Teste** | Restauração mensal |
| ✅ **Hashing** | Senhas com bcrypt |

---

### ⏱️ Disponibilidade

| Métrica | Meta |
|:---|:---:|
| 📈 **Uptime** | 99.9% |
| ⏰ **RTO** | 4h |
| 📊 **RPO** | 1h |

**Plano de Contingência:**
- ☁️ Failover AWS (us-east-1 → us-west-2)
- ⚡ Gerador com autonomia 48h
- 🌐 ISP Backup

---

### 👤 Fator Humano

| Regra de Ouro | Consequência |
|:---|:---|
| 🚫 **Compartilhar senhas** | 🔴 Grave |
| 🔒 **Bloquear tela** | 🟢 Leve/Média |
| 📱 **Sem USB pessoal** | 🟡 Média |
| 🎣 **Reportar phishing** | 📢 Obrigatório |

**Treinamentos:**
- 📚 Onboarding obrigatório
- 🎯 Phishing simulado trimestral

---

## ⚖️ 5. Regras Disciplinares

| Nível | Infração | Consequência |
|:---:|:---|:---|
| 🟢 **Leve** | Tela desbloqueada | Advertência Verbal |
| 🟡 **Média** | USB não autorizado | Advertência Escrita |
| 🟠 **Grave** | Compartilhar senha | Suspensão |
| 🔴 **Gravíssima** | Vazamento intencional | **Justa Causa** |

---

## ✅ 6. Aplicabilidade

✔️ **Quem?** Todos funcionários, estagiários e terceiros  
✔️ **Onde?** Escritórios, home office e nuvem  
✔️ **O quê?** Todos sistemas e dados corporativos
