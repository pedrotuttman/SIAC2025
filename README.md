# ⚙️ Visão Geral sobre RISC-V e Pwning Aplicado a Essa Arquitetura  
### 🧠 Semana de Integração Acadêmica (SIAC) – UFRJ | 2025  
#### 👤 Autor: [Pedro Tuttman Cysne Soares](https://github.com/pedrotuttman)  
📍 Engenharia de Computação e Informação – UFRJ  
🛡️ Grupo de Resposta a Incidentes de Segurança (GRIS)

---

## 🧩 Descrição do Projeto  

Este projeto apresenta uma **análise técnico-conceitual da arquitetura RISC-V**, com foco em **desempenho, design modular e fundamentos de segurança em baixo nível**.  

A proposta foi desenvolvida e apresentada na **Semana de Integração Acadêmica (SIAC) 2025 da UFRJ**, no contexto do **Grupo de Resposta a Incidentes de Segurança (GRIS)**, e busca **unir dois mundos** tradicionalmente separados:  
> **Arquitetura de Computadores** e **Segurança da Informação**.  

---

## 🚀 Objetivos  

- Fornecer uma **visão geral da arquitetura RISC-V**, seus princípios de design e comparações com ARM e x86.  
- Explorar **estruturas internas de processadores**, como datapath, unidade de controle e execução pipeline.  
- Discutir **conceitos de desempenho**, como paralelismo, hierarquia de memória e mitigação de *hazards*.  
- Introduzir **conceitos de segurança em hardware**, incluindo vulnerabilidades clássicas de memória e suas implicações arquiteturais.  
- Mostrar como o **RISC-V**, por ser aberto e modular, é uma excelente plataforma para **ensino, pesquisa e experimentação em segurança computacional**.  

---

## 🧱 Tópicos Abordados  

### 🔹 Fundamentos de Arquitetura  
- Conceitos de **ISA (Instruction Set Architecture)**  
- **Filosofia RISC**: simplicidade e eficiência  
- Estrutura de instruções (tipos R, I, S, B, U, J)  
- Datapath, Unidade de Controle e Pipeline  

### 🔹 Desempenho e Paralelismo  
- Execução *single-cycle*, *multicycle* e *pipeline*  
- *Hazards* (estruturais, de dados e de controle)  
- Técnicas de paralelismo e *multiple issue*  
- Hierarquia de memória e cache  

### 🔹 Segurança em Baixo Nível  
- Estrutura da **stack** e funcionamento da **memória**  
- **Buffer Overflow** e sobrescrita de endereços de retorno  
- **Shellcode Injection**  
- **Return-Oriented Programming (ROP)**  
- Diferenças entre vulnerabilidades em **x86-64** e **RISC-V**  

---

## 📊 Comparativo de Arquiteturas  

| Arquitetura | Tipo | Licenciamento | Registradores | Aplicações |
|--------------|------|----------------|----------------|-------------|
| **x86-64** | CISC | Proprietário | 16 | PCs e servidores |
| **ARM** | RISC | Licenciado | 31 | Mobile, IoT, laptops |
| **RISC-V** | RISC | **Aberto e livre** | 31 | Pesquisa, IoT, sistemas customizados |

---

## 🔐 Segurança e Pwning  

A parte final do estudo introduz o conceito de **pwning aplicado à arquitetura RISC-V**, explorando como o design simples da ISA impacta a **superfície de ataque** e as técnicas de **exploração de vulnerabilidades**.  
São analisadas diferenças práticas entre as arquiteturas **RISC e CISC** na forma como manipulam a pilha, salvam endereços de retorno e lidam com o controle de fluxo.  

---

## 🧾 Estrutura do Material  

📘 `Visão_Geral_sobre_Arquitetura_RISC-V.pdf` – Texto completo com fundamentos teóricos e exemplos.  
🎞️ `Arquitetura_RISC-V_Uma_Visão_Geral_sobre_Desempenho_e_Segurança.pptx` – Slides da apresentação exibida na SIAC 2025.  
📜 `certificado_SIAC2025.pdf` – Certificação de participação e apresentação.  

---

## 🧠 Conclusão  

O projeto busca mostrar que compreender **arquitetura de computadores** é fundamental para **compreender segurança em profundidade**.  
Mais do que uma arquitetura promissora, o **RISC-V** é um **laboratório aberto** para pesquisa, inovação e ensino de hardware seguro.  

---

## 🔗 Repositório e Contato  

📂 [Repositório completo no GitHub](https://github.com/pedrotuttman/SIAC2025)  
✉️ Contato: pedro.tuttman@poli.ufrj.br  
