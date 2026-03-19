# Projeto Recursos Humanos — Nexora Group
![BOSS BI Framework](https://img.shields.io/badge/Powered%20by-BOSS%20BI%20Framework-black?style=for-the-badge&logo=powerbi&logoColor=yellow)  

## 📊 Visão Geral

Este projeto apresenta um **dashboard de pesquisa de satisfação dos colaboradores**, desenvolvido em **Power BI**, para a empresa fictícia **Nexora Group**.

A solução permite acompanhar indicadores estratégicos de clima organizacional, engajamento e retenção, comparando diferentes ciclos de entrevistas e facilitando decisões de gestão de pessoas.

🔎 **[Dashboard Interativo](https://app.powerbi.com/view?r=eyJrIjoiNjhkNWViMjUtNTZhNi00MzM0LTkyNGMtYjYyNDA3ODZmMjA4IiwidCI6IjIzY2FjN2VlLWYxZDgtNDMzOS1hYTdiLTc4MWFhOWY5MjI1YiJ9)**  

---

## 🧠 Contexto do Problema

A área de Recursos Humanos da **Nexora Group** enfrentava desafios na análise integrada de:

- estrutura organizacional (cargos e colaboradores)
- perfil demográfico dos colaboradores
- canais de recrutamento
- nível de satisfação interna

Essas limitações dificultavam a identificação de padrões, tendências de contratação e percepções críticas relacionadas ao ambiente organizacional, impactando diretamente a tomada de decisão estratégica.

---

## 🎯 Abordagem Estratégica

Para resolver esses desafios, foi desenvolvida uma solução analítica utilizando **Power BI**, estruturada com **modelagem dimensional** e organização de indicadores estratégicos de capital humano.

O dashboard foi projetado para oferecer:

- leitura executiva clara
- análise detalhada de satisfação
- navegação intuitiva entre visões organizacionais  

### KPIs principais

- Quantidade de Colaboradores
- Quantidade de Cargos
- Volume de Respostas

---

## 🧠 Metodologia Aplicada — BOSS BI Framework

> Este projeto foi desenvolvido utilizando o BOSS BI Framework (Business-Oriented Smart Solutions), uma metodologia proprietária desenvolvida para estruturar projetos de Business Intelligence e Analytics, focada na geração de valor estratégico, consistência analítica e suporte à tomada de decisão.

## 🔷 Fluxo do BOSS BI Framework

```mermaid
flowchart LR
    A[Business Understanding] --> B[Data Understanding]
    B --> C[Data Preparation]
    C --> D[Data Modeling]
    D --> E[Analytical Exploration]
    E --> F[Data Visualization]
    F --> G[Insights & Decision Support]
    G --> H[Deployment]
    H --> I[Continuous Improvement]
    I --> A
```

## 📌 Detalhamento das Etapas

### 🔹 1. Business Understanding
Definição do problema analítico e alinhamento com os objetivos estratégicos do negócio, garantindo que a solução gere valor real e mensurável.

---

### 🔹 2. Data Understanding
Mapeamento das fontes de dados e análise inicial para compreensão da estrutura, qualidade e granularidade das informações disponíveis.

---

### 🔹 3. Data Preparation
Tratamento, limpeza e transformação dos dados, assegurando consistência, padronização e confiabilidade para análise.

---

### 🔹 4. Data Modeling
Estruturação do modelo de dados utilizando boas práticas de modelagem dimensional, com foco em performance e escalabilidade.

---

### 🔹 5. Analytical Exploration
Exploração dos dados para identificação de padrões, tendências, correlações e possíveis anomalias relevantes ao negócio.

---

### 🔹 6. Data Visualization
Desenvolvimento de dashboards e relatórios interativos, aplicando princípios de visualização e Data Storytelling.

---

### 🔹 7. Insights & Decision Support
Geração de insights acionáveis e recomendações estratégicas para apoiar a tomada de decisão baseada em dados.

---

### 🔹 8. Deployment
Publicação e disponibilização da solução analítica, garantindo acesso, atualização e governança dos dados.

---

### 🔹 9. Continuous Improvement
Monitoramento contínuo e evolução da solução, adaptando-se às mudanças e novas necessidades do negócio.

---

## 📈 Impactos e Resultados

A solução permite:

- identificar padrões de satisfação e insatisfação dos colaboradores
- analisar a efetividade dos canais de recrutamento
- compreender a distribuição demográfica da força de trabalho
- comparar percepções entre diferentes entrevistas e dimensões organizacionais

Com isso, gestores conseguem tomar decisões mais estratégicas e orientadas por dados na gestão de capital humano.

---

## 🧩 Estrutura do Dashboard

### 📊 **Indicadores Principais**

O dashboard apresenta três cartões principais:

### Colaboradores

- quantidade de colaboradores participantes

### Cargos

- quantidade de cargos monitorados

### Respostas

- consolidação das respostas coletadas

---

## 📊 Visualizações Analíticas

### 👥 **Distribuição por Faixa Etária**

Gráfico de barras horizontais apresentando:

- quantidade de colaboradores por faixa etária  
- análise do perfil demográfico organizacional  

---

### 🧲 **Formas de Recrutamento**

Gráfico Treemap exibindo:

- contratações por canal (site de empregos, site da empresa, feiras e indicações)  
- impacto relativo de cada fonte de recrutamento  

---

### 📅 **Contratações por Ano**

Gráfico de barras verticais mostrando:

- evolução das contratações ao longo do tempo  
- identificação de tendências de crescimento  

---

### 📊 **Comparativo entre Entrevistas**

Gráfico de barras verticais comparando:

- Entrevista 01 e Entrevista 02  
- classificações: satisfeito, neutro e insatisfeito  

---

### 📊 **Análise de Satisfação por Dimensão**

Gráfico de barras empilhadas apresentando:

- percentual de satisfação em Saúde, Carga Horária e Salário  
- distribuição entre satisfeito, neutro e insatisfeito

---

### Interatividade e Navegação

- **Filtro:** seleção da equipe entrevistada  
- **Link “Analisar Dashboard”** para abrir o dashboard interativo  
- **Modos Dark (padrão) e Light opcional**  
- **Ícone para voltar à Home** (descrição no README)

---

## 🛠️ Stack Técnica

- **Power BI**: construção do dashboard e storytelling analítico  
- **DAX**: criação de medidas percentuais comparativas  
- **Modelagem Dimensional**: organização de dados de colaboradores, cargos, recrutamento e avaliações  

---

## 🧱 Modelagem de Dados

**Tabelas Fato:**

- respostas da pesquisa  
- contratações  
- colaboradores  

**Tabelas Dimensão:**

- cargos  
- equipes  
- canais de recrutamento  
- faixas etárias  

---

# 📸 Preview do Dashboard

![Dashboard Preview](images/recursos-humanos-nexora-group.png)

# 🗂️ Modelo de Dados

![Modelo de Dados](images/modelo-dados-nexora-group.png)

## Documentação das Medidas

Para consultar a documentação das medidas deste projeto, suas fórmulas e descrições, acesse a **[Documentação das Medidas](docs/medidas-documentacao.md)**.

# 👨‍💻 Autor

Projeto desenvolvido como parte do meu portfólio profissional em **Business Intelligence e Data Analytics**, destacando habilidades avançadas e aplicáveis a diversos cenários analíticos:

- Desenvolvimento de **dashboards executivos e painéis estratégicos**, focados em insights acionáveis e tomada de decisão baseada em dados  
- **Modelagem dimensional e relacional**, aplicando corretamente **cardinalidade, granularidade** e hierarquias entre tabelas para garantir consistência e integridade dos dados  
- **Transformação de dados com Power Query e Linguagem M**, criando pipelines eficientes, automatizados e auditáveis  
- Criação de **KPIs estratégicos e métricas customizadas em DAX**, para análise de performance e comparações confiáveis  
- **Integração de múltiplas fontes de dados** (Excel, SQL, APIs, arquivos planos), padronizando e validando informações críticas  
- **Data storytelling e visualizações interativas**, com cores, hierarquias, filtros e destaque de insights, para facilitar interpretação e engajamento do usuário  
- **Análises estatísticas e preditivas**, usando Python, R, regressões, teste de hipóteses, séries temporais e técnicas de Machine Learning para identificação de tendências e padrões  
- **Automatização e otimização de processos analíticos**, incluindo ETL, scripts e compressão de dados, garantindo performance e escalabilidade dos relatórios  
- **Documentação detalhada de medidas, tabelas, modelos e processos**, permitindo reprodutibilidade, transparência e governança dos dados  
- Aplicação de **boas práticas de engenharia de dados**, integrando análise, estatística, IA e visualização para soluções analíticas completas e confiáveis  
- Domínio completo de **Power BI, DAX, Power Query, Python e R**, com foco em performance, qualidade e entrega de insights estratégicos

---

<div align="center">
  
**Portfólio de Business Intelligence & Data Analytics**  

<img src="images/assinatura.png" width="400">  

---

💼 Aberto a oportunidades em Business Intelligence & Data Analytics

| [LinkedIn](https://www.linkedin.com/in/rogério-clynton-ribeiro/) | [Portfólio](https://clyntonboss.github.io/) | [e-Mail](mailto:clyntonribeiror@gmail.com) | [WhatsApp](https://wa.me/5524999240768) |

</div>
