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
