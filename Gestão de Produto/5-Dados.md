# 📊 Módulo 05 — Dados e Analytics

> **Material de Aula — Product Management**

---

## 🎯 Introdução

Product Managers não são apenas profissionais estratégicos — eles também **colocam a mão na massa**.  
Neste módulo, você aprenderá como **usar dados para guiar decisões**, **definir métricas relevantes**, **rodar experimentos A/B**, e até **extrair insights com SQL**.  

Ao final, você terá domínio sobre os principais conceitos e ferramentas de **dados e analytics aplicados à gestão de produtos**.

---

## 👥 Instrutores deste módulo

Especialistas de mercado compartilham experiências reais sobre como a análise de dados transforma o processo decisório em empresas de tecnologia, destacando **exemplos práticos e cases como GetNinjas, Nubank e Gympass**.

---

## 5.1 📈 Lidando com Métricas de Negócio e Produto

### 💡 O que são métricas?

Métricas são **indicadores numéricos que medem o desempenho** do produto e ajudam o PM a entender se está no caminho certo.

Existem dois grandes grupos:

| Tipo de Métrica | Foco | Exemplos |
|------------------|------|-----------|
| **Métricas de Negócio** | Resultados financeiros e estratégicos | Receita, margem, LTV, churn |
| **Métricas de Produto** | Uso e engajamento do produto | Retenção, MAU, DAU, NPS, taxa de conversão |

> ⚖️ O segredo está em **equilibrar métricas de negócio e de produto**, garantindo sustentabilidade e crescimento saudável.

---

### 🧮 Definindo boas métricas

Uma boa métrica deve ser:

- **Clara:** fácil de medir e entender;  
- **Acionável:** deve levar a uma decisão prática;  
- **Relevante:** alinhada aos objetivos do produto;  
- **Mensurável:** baseada em dados confiáveis.

> 🎯 Dica: escolha **1 a 3 métricas principais (North Star Metrics)** que representem o sucesso do produto como um todo.

---

### 📊 Exemplos e Casos Reais

- **Nubank:** acompanha métricas de *Net Activation* e *Engajamento*, priorizando produtos que aumentam o uso diário.  
- **Spotify:** usa *Time Spent Listening* como métrica de valor e engajamento.  
- **GetNinjas:** monitora *taxa de correspondência entre cliente e profissional* como métrica de sucesso do marketplace.

---

## 5.2 📉 Como Usar Dados para Tomar Decisões

### 🧠 Data-Driven Product Management

Ser um PM orientado por dados significa **usar informações quantitativas e qualitativas** para validar hipóteses e embasar decisões.  

> 🔍 Dados não substituem o julgamento humano — mas **tornam as decisões mais precisas e defensáveis**.

---

### 🧩 Processo de Tomada de Decisão Baseada em Dados

1. **Definir o problema** — o que queremos resolver?  
2. **Levantar hipóteses** — quais causas podem estar influenciando?  
3. **Coletar e analisar dados** — via dashboards, entrevistas, pesquisas, SQL.  
4. **Testar hipóteses** — através de experimentos ou testes A/B.  
5. **Medir resultados e aprender** — ajustar com base nos insights obtidos.

---

### 📘 Case: GetNinjas

A empresa utiliza **dados em tempo real** para decidir:
- quais categorias priorizar,  
- como ajustar preços, e  
- como equilibrar a oferta e demanda em seu marketplace.  

Os PMs da GetNinjas analisam **taxas de conversão e recorrência** para identificar gargalos e testar novas funcionalidades de forma rápida.

---

## 5.3 🧮 SQL para Análise de Dados

### 🔍 Por que SQL é importante para PMs?

Saber o básico de **SQL (Structured Query Language)** permite que o PM **acesse dados diretamente**, sem depender totalmente de analistas.  
Isso traz **autonomia, agilidade e profundidade** na análise.

---

### 🧱 Principais Comandos SQL

| Comando | Função | Exemplo |
|----------|---------|----------|
| `SELECT` | Seleciona colunas e dados | `SELECT name, revenue FROM users;` |
| `FROM` | Define a tabela a ser usada | `FROM transactions` |
| `WHERE` | Filtra resultados | `WHERE revenue > 1000` |
| `GROUP BY` | Agrupa resultados | `GROUP BY region` |
| `ORDER BY` | Ordena resultados | `ORDER BY created_at DESC` |

> 💡 PMs não precisam ser experts, mas devem entender **como interpretar dados e validar hipóteses com consultas simples.**

---

### 🧰 Benefícios para o PM

- Tomar decisões embasadas em dados reais;  
- Identificar padrões e anomalias no comportamento do usuário;  
- Apoiar times de engenharia e growth com informações relevantes.

---

## 5.4 🧪 Testes A/B

### 🧬 O que é um Teste A/B?

Um **teste A/B** compara duas (ou mais) versões de uma funcionalidade, página ou experiência, para identificar **qual gera melhor desempenho** em uma métrica definida.

---

### 🧠 Etapas do Processo

1. **Defina a hipótese:** o que deseja validar e por quê;  
2. **Escolha a métrica de sucesso:** ex: taxa de conversão, clique, engajamento;  
3. **Divida o público em grupos:** A (controle) e B (variação);  
4. **Rode o experimento:** mantenha o mesmo tempo e condições;  
5. **Analise os resultados:** determine se há significância estatística.

---

### 📈 Boas Práticas

- Teste **uma variável por vez**;  
- Mantenha o experimento **tempo suficiente para validade estatística**;  
- Documente aprendizados e resultados;  
- **Evite parar o teste cedo demais.**

---

### ⚠️ Erros Comuns

- Não definir hipóteses claras;  
- Métricas mal escolhidas;  
- Amostras pequenas demais;  
- Testes simultâneos que interferem entre si.

> 🧠 Exemplo real: o Netflix testa **imagens, títulos e descrições** para entender quais geram mais cliques — tudo baseado em A/B Testing.

---

## 5.5 🛠️ Ferramentas do Dia a Dia

### ⚙️ Por que usar ferramentas de Analytics?

Ferramentas ajudam o PM a **monitorar comportamento do usuário**, **identificar gargalos** e **acompanhar o impacto das releases** em tempo real.

---

### 🧰 Categorias e Exemplos

| Categoria | Ferramenta | Função Principal |
|------------|-------------|------------------|
| **Mapeamento de Comportamento** | Hotjar | Mapas de calor e gravações de sessões |
| **Visualização de Dados** | Tableau | Dashboards interativos e análises complexas |
| **Performance e Logs** | New Relic | Monitoramento de performance de sistemas |
| **Métricas Operacionais** | Librato | Observabilidade e alertas em tempo real |
| **Product Analytics** | Mixpanel / Amplitude | Acompanhamento de eventos e funil de uso |

> 💬 Use ferramentas que se integrem ao stack da empresa e garantam **confiabilidade dos dados**.

---

## 📚 Conclusão do Módulo

Neste módulo, você aprendeu:

- Como definir e equilibrar **métricas de negócio e produto**;  
- Como usar **dados para tomar decisões estratégicas**;  
- Como extrair informações com **SQL**;  
- Como aplicar **testes A/B** na prática;  
- E quais **ferramentas** auxiliam o trabalho de um PM moderno.

> ✨ *Dados são a bússola do Product Manager — mas o julgamento e a empatia continuam sendo o leme.*

