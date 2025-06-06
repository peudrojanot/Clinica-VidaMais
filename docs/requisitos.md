# 📌 Requisitos Técnicos – Projeto de Consultoria em Servidores

Este documento apresenta os requisitos técnicos identificados durante a análise das empresas fictícias **Vida+** e **TecnoVita**, dentro do escopo do projeto da disciplina de Arquitetura de Computadores.

---

## 💉 Vida+ – Requisitos Técnicos

### 📍Contexto:
Empresa do setor de saúde em expansão, adotando soluções digitais como:
- Prontuário eletrônico
- Telemedicina
- Análise de dados clínicos

### 🧾 Requisitos:
- **Alta disponibilidade**: Acesso aos dados 24h/dia
- **Armazenamento seguro**: Conformidade com a **LGPD** (dados sensíveis de pacientes)
- **Capacidade de escalabilidade**: Suportar o crescimento e novas unidades
- **Suporte a vídeo em tempo real**: Para teleconsultas médicas
- **Redundância de dados**: Backup automatizado e replicação geográfica

### 💡 Recomendação Técnica:
- Migração para **servidores em nuvem**
- Utilização de plataformas especializadas:  
  - **AWS HealthLake**  
  - **Microsoft Azure for Healthcare**

---

## 🧠 TecnoVita – Requisitos Técnicos

### 📍Contexto:
Startup de tecnologia lançando uma plataforma de atendimento ao cliente baseada em **IA** e **aprendizado de máquina**.

### 🧾 Requisitos:
- **Alto desempenho de CPU e GPU**: Para treinar modelos de IA
- **Processamento paralelo**: Para respostas em tempo real
- **Armazenamento em tempo real**: Alta velocidade e escalabilidade
- **Controle de custos operacionais**: Infraestrutura flexível
- **Segurança dos dados**: Para proteger interações e dados de clientes

### 💡 Recomendação Técnica:
- Aquisição de servidores com **GPUs NVIDIA** (suporte a CUDA)
- Arquitetura **híbrida**:
  - **Servidores locais** para treino de modelos
  - **Serviços de cloud** para escalabilidade e produção
- Plataformas sugeridas:
  - **Google Cloud AI**
  - **IBM Watson Studio**

---


