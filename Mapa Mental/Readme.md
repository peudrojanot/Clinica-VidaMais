# 🏥 Modernização ou Aquisição de Servidor – Clínica VidaMais

Este projeto apresenta a análise da necessidade da Clínica VidaMais em modernizar seu servidor atual ou adquirir uma nova solução — seja física ou em nuvem — para atender à crescente demanda de dados e segurança digital da clínica.

---

## 📌 1. Necessidades da Clínica VidaMais

- Alta demanda de atendimento diário (~250/dia).
- Falta de redundância de dados.
- Sistema de prontuário eletrônico em crescimento.
- Problemas com lentidão, falhas e risco de perda de dados.
- Necessidade de segurança e disponibilidade.
- Equipamento atual obsoleto (i3/4GB RAM).

---

## 🧱 2. Opções de Arquitetura de Servidor

### 🔹 Físico

#### Opções:
- **Dell PowerEdge R640**
  - Intel Xeon Silver 4210R
  - 1x 16GB RAM, 480GB SSD
  - R$ 29.999,00
- **Dell PowerEdge R230**
  - Intel Xeon E-2236
  - 4x 8GB RAM, 2x 2TB HDD
  - R$ 12.649,00

**Vantagens:**
- Controle total sobre hardware.
- Personalização específica.

**Desvantagens:**
- Alto custo inicial.
- Necessidade de manutenção contínua.
- Risco de obsolescência.

---

### 🔹 Em Nuvem (AWS / Azure)

#### Opções:
- **Amazon AWS**:
  - t3a.nano (2 vCPUs, 512MB RAM): **US$ 1,75/mês**
  - t3a.xlarge (4 vCPUs, 16GB RAM): **US$ 0,13/hora**

- **Microsoft Azure**:
  - B2s (2 vCPUs, 4GB RAM): **US$ 33,24/mês**

**Vantagens:**
- Escalabilidade e backup automático.
- Alta disponibilidade e segurança.
- Conformidade com LGPD.

**Desvantagens:**
- Custo mensal contínuo.
- Depende de conexão estável com a internet.

---

### 🔹 Servidor Híbrido

- Servidor local para operações críticas.
- Nuvem para backup e escalabilidade.
- Flexível, mas exige gerenciamento mais complexo.

---

## ⚖️ 3. Comparação: Modernizar vs. Adquirir Novo Servidor

| Opção                 | Custo Inicial | Manutenção | Escalabilidade | Backup | Conformidade LGPD | Obsolescência |
|----------------------|---------------|------------|----------------|--------|-------------------|---------------|
| Modernizar o atual   | Baixo         | Contínua   | Limitada       | Manual | Difícil de garantir| Alto          |
| Novo servidor físico | Alto          | Contínua   | Limitada       | Manual | Parcial           | Médio         |
| Nuvem (AWS/Azure)    | Variável      | Reduzida   | Alta           | Automático | Facilitada      | Baixo         |

---

## ✅ 4. Escolha Final da Empresa

🔄 **Migração para servidores em nuvem (AWS ou Azure)**

---

## 💡 Justificativas:

- Redução de riscos com falhas físicas.
- Conformidade com a LGPD (criptografia e controle de acesso).
- Escalabilidade sob demanda.
- Suporte e manutenção 24/7 simplificados.
- Backup automatizado e alta disponibilidade.

---

## 🗣️ 5. Nome da Empresa e Feedback

> “A proposta apresentada trouxe clareza para nossa decisão. A transição para a nuvem nos oferece mais segurança, disponibilidade e agilidade no acesso aos dados dos pacientes. Estamos confiantes de que essa modernização contribuirá para a melhoria no atendimento.”
>
> — **Diretoria Administrativa da Clínica VidaMais**

---

## 🧠 Mapa Mental Visual

![Mapa Mental](https://github.com/peudrojanot/Clinica-VidaMais/blob/main/Mapa%20Mental/image.png)

---

