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
- [6. Aplicabilidade](#-6-aplicabilidade)

---

## 🏢 1. Contexto

**InnovaTech Solutions** — SaaS para o setor financeiro.

### Ativos Críticos
| Local | Criticidade |
|:---|:---:|
| ☁️ AWS (Produção) | 🔴 Alta |
| 🖥️ Sala de Servidores | 🔴 Alta |
| 💻 Setor Dev | 🟡 Média |
| 📁 Setor RH | 🔴 Alta |

---

## 👥 2. Governança

| Membro | Cargo |
|:---|:---|
| Ana Souza | CISO |
| Carlos Lima | Gestor(a) de TI |
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
```

### Priorização
| Risco | Prioridade |
|:---:|:---:|
| 🦠 Ransomware | 🔴 **MÁXIMA** |
| 🎣 Phishing | 🟠 **ALTA** |
| 💣 Vazamento | 🟠 **ALTA** |
| ⚡ Falha de energia | 🟡 **MÉDIA** |

---
### 🔐 Controles de Acesso
<img width="587" height="671" alt="image" src="https://github.com/user-attachments/assets/d3f7341d-ce27-40d9-97ff-741a75add243" />



---
## 🔒 4. Diretrizes de Segurança

### 🛡️ Confidencialidade
| Regra | Exigência |
|:---|:---|
| ✅ **MFA** | Obrigatório em sistemas críticos |
| ✅ **Criptografia** | Notebooks (BitLocker) + VPN |
| ✅ **Acesso mínimo** | Revisão mensal de acessos |

### 📝 Integridade
| Regra | Especificação |
|:---|:---|
| ✅ **Backup** | 3-2-1 (3 cópias, 2 mídias, 1 off-site) |
| ✅ **Teste** | Restauração mensal |
| ✅ **Hashing** | Senhas com bcrypt |

### ⏱️ Disponibilidade
| Métrica | Meta |
|:---|:---:|
| 📈 **Uptime** | 99.9% |
| ⏰ **RTO**(Fora do Ar) | 4h |
| 📊 **RPO**(Quantidade de Dados) | 1h |

**Plano de contingência:**
- ☁️ Failover AWS (us-east-1 → us-west-2)
- ⚡ Gerador com autonomia de 48h
- 🌐 ISP backup

### 👤 Fator Humano
| Regra de Ouro | Consequência |
|:---|:---|
| 🚫 **Compartilhar senhas** | 🔴 Grave |
| 🔒 **Bloquear a tela** | 🟢 Leve/Média |
| 📱 **Sem USB pessoal** | 🟡 Média |
| 🎣 **Reportar phishing** | 📢 Obrigatório |

**Treinamentos:**
- 📚 Onboarding obrigatório
- 🎯 Simulação de phishing trimestral

---

## ⚖️ 5. Regras Disciplinares

| Nível | Infração | Consequência |
|:---:|:---|:---|
| 🟢 **Leve** | Tela desbloqueada | Advertência verbal |
| 🟡 **Média** | USB não autorizado | Advertência escrita |
| 🟠 **Grave** | Compartilhar senha | Suspensão |
| 🔴 **Gravíssima** | Vazamento intencional | **Justa causa** |

---

## ✅ 6. Aplicabilidade

- ✔️ **Quem?** Todos(as) os(as) funcionários(as), estagiários(as) e terceiros(as)
- ✔️ **Onde?** Escritórios, home office e nuvem
- ✔️ **O quê?** Todos os sistemas e dados corporativos

### 📊 Matriz de Priorização de Riscos
| Risco | Impacto | Probabilidade | Prioridade |
|:---|:---|:---|:---|
| 🦠 Ransomware | 🔴 Crítico | 📈 Alta | 🔴 **MÁXIMA** |
| 🎣 Phishing | 🟠 Alto | 📈 Alta | 🟠 **ALTA** |
| 💣 Vazamento | 🔴 Crítico | 📊 Média | 🟠 **ALTA** |
| ⚡ Falha de energia | 🟠 Alto | 📉 Baixa | 🟡 **MÉDIA** |
