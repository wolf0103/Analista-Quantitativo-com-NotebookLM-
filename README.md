# 📊 Miniguia de Estudos: Analista Quantitativo (com NotebookLM)

> Caderno temático criado com o auxílio do NotebookLM como parte do desafio de projeto da DIO. O objetivo deste repositório é documentar todo o processo de curadoria, experimentação com prompts e consolidação de conhecimento sobre a carreira e as competências de um **Analista Quantitativo (Quant Analyst)**.

---

## 🎯 Contexto e Objetivos

### Contexto
O mercado financeiro e de tecnologia tem demandado cada vez mais profissionais capazes de unir **matemática, estatística, programação e finanças** para tomar decisões orientadas por dados. O Analista Quantitativo ("Quant") é o profissional responsável por modelar riscos, precificar ativos, construir estratégias de investimento algorítmico e apoiar decisões financeiras com base em modelos matemáticos e computacionais.

Escolhi esse tema porque quero entender melhor:
- O que efetivamente esse profissional faz no dia a dia;
- Quais são as competências técnicas (hard skills) e comportamentais (soft skills) exigidas;
- Quais ferramentas, linguagens e modelos matemáticos são mais usados na prática;
- Como iniciar uma trilha de estudos consistente para migrar/entrar nessa área.

### Objetivos de Estudo
- [ ] Compreender o papel do Analista Quantitativo dentro de bancos, fundos de investimento e fintechs;
- [ ] Mapear as principais áreas de atuação (risco, pricing, trading algorítmico, pesquisa quantitativa);
- [ ] Identificar as ferramentas e linguagens mais usadas (Python, R, SQL, C++, bibliotecas estatísticas);
- [ ] Entender conceitos-chave de estatística, probabilidade e finanças quantitativas aplicados à rotina do quant;
- [ ] Construir um glossário de termos técnicos da área;
- [ ] Criar um conjunto de prompts reutilizáveis para revisar o assunto no futuro.

---

## 📚 Curadoria de Fontes

Fontes abertas selecionadas e carregadas no NotebookLM (texto e/ou PDF).

| # | Fonte | Tipo | Link |
|---|-------|------|------|
| 1 | Análise quantitativa (finanças) — Wikipédia PT | Texto (visão geral do conceito, áreas de atuação e formação) | https://pt.wikipedia.org/wiki/An%C3%A1lise_quantitativa_(finan%C3%A7as) |
| 2 | Understanding How to Become a Quantitative Analyst — QuantStart | Texto (guia de carreira em inglês, referência clássica da área) | https://www.quantstart.com/articles/Understanding-How-to-Become-a-Quantitative-Analyst/ |
| 3 | Self-Study Plan for Becoming a Quantitative Analyst — QuantStart | Texto (plano de estudos autodidata, matemática e programação) | https://www.quantstart.com/articles/Self-Study-Plan-for-Becoming-a-Quantitative-Analyst/ |
| 4 | Profissão: Quant — Artigos da Quantzed | Texto/Blog (mercado brasileiro, formação e matemática exigida) | https://artigos.quantzed.com.br/2024/02/02/profissao-quant/ |
| 5 | Finanças Quantitativas — Ementa do Mestrado Profissional em Métodos Matemáticos em Finanças (IMPA) | Texto/Syllabus (tópicos avançados: derivativos, Black-Scholes, VaR) | https://impa.br/postgraduate/training-programs/professional-masters-degree-in-mathematical-methods-in-finance/subjects-professional-masters-in-mathematical-methods-in-finance/quantitative-finance/?lang=en |

> 💡 **Fonte extra (opcional, mais avançada):** Ensaios em Finanças Quantitativas — dissertação de mestrado da USP sobre apreçamento de derivativos e cópulas de Lévy (PDF acadêmico): https://www.teses.usp.br/teses/disponiveis/12/12139/tde-10052010-151041/publico/EdsonBastosTese.pdf — boa para quem quiser aprofundar em modelagem matemática.
>
> 📥 **Como usar:** baixe/exporte essas páginas como PDF (ou use a extensão "Salvar como PDF" do navegador) e faça o upload dos arquivos no NotebookLM para começar as perguntas.

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

Aqui documento as perguntas estratégicas feitas ao NotebookLM, as variações testadas e as dificuldades encontradas no processo.

### Prompt 1 — Visão geral da profissão
**Prompt usado:**
> "Com base nos documentos carregados, explique de forma resumida o que faz um Analista Quantitativo, quais são suas principais responsabilidades e em quais tipos de empresas ele costuma atuar."

**Resposta obtida (resumo):** `[cole aqui o resumo da resposta gerada]`

**Referência:** Fonte(s) nº `[X]`

---

### Prompt 2 — Competências técnicas
**Prompt usado:**
> "Liste as principais ferramentas, linguagens de programação e conceitos matemáticos/estatísticos mencionados nos documentos como essenciais para um Analista Quantitativo."

**Variação testada:**
> "Quais são as 5 habilidades técnicas mais citadas nos documentos para essa carreira, ordenadas por relevância?"

**Dificuldade encontrada (troubleshooting):** A primeira versão do prompt trouxe uma lista genérica demais, misturando conceitos de diferentes níveis de profundidade. Foi necessário pedir explicitamente para **ordenar por relevância** e **limitar a quantidade de itens**, o que tornou a resposta mais objetiva e utilizável.

---

### Prompt 3 — Glossário de termos técnicos
**Prompt usado:**
> "Extraia dos documentos um glossário com os 10 termos técnicos mais importantes relacionados a finanças quantitativas, com uma definição curta para cada um."

**Dificuldade encontrada:** Nas primeiras tentativas, o modelo trazia definições muito longas e técnicas demais. Ajustei o prompt pedindo explicitamente **"definições de até 2 linhas, em linguagem acessível para iniciantes"**, o que melhorou bastante a clareza.

---

### Prompt 4 — Comparação entre áreas de atuação
**Prompt usado:**
> "Compare, com base nos documentos, as diferenças entre um analista de risco quantitativo, um pesquisador quantitativo (quant researcher) e um trader quantitativo."

**Resposta obtida (resumo):** `[cole aqui o resumo]`

**Referência:** Fonte(s) nº `[X]`

---

### Prompt 5 — Trilha de estudos
**Prompt usado:**
> "Com base em tudo que foi discutido nos documentos, sugira uma trilha de estudos de 3 meses para alguém que quer migrar para a área de análise quantitativa, do zero."

**Dificuldade encontrada:** A resposta inicial era vaga em relação a prazos. Refinei pedindo para **estruturar por semanas** e **indicar pré-requisitos**, o que resultou em um plano muito mais acionável.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado

**O que é um Analista Quantitativo?**
Profissional que aplica matemática, estatística, programação e conhecimento financeiro para desenvolver modelos que apoiam decisões de investimento, precificação de ativos e gestão de risco.

**Principais áreas de atuação:**
- **Quant Research** — desenvolvimento de modelos e estratégias;
- **Quant Trading** — execução e automação de estratégias de investimento;
- **Risk Management (Quant Risk)** — modelagem e controle de riscos financeiros;
- **Quant Development** — construção de infraestrutura e sistemas para suportar modelos quantitativos.

**Ferramentas e competências mais citadas:**
- Linguagens: Python, R, SQL, C++;
- Matemática/Estatística: probabilidade, séries temporais, cálculo estocástico, álgebra linear;
- Finanças: precificação de derivativos, gestão de portfólio, teoria de risco;
- Bibliotecas comuns: `pandas`, `numpy`, `scikit-learn`, `QuantLib`.

**Trilha de estudo sugerida (resumo):**
1. Fundamentos de estatística e probabilidade;
2. Python aplicado a dados e finanças;
3. Fundamentos de finanças quantitativas (precificação, risco, portfólio);
4. Projetos práticos (backtesting de estratégias, modelos de risco).

---

### 2. Glossário

| Termo | Definição |
|-------|-----------|
| **Quant** | Abreviação para Analista/Profissional Quantitativo. |
| **VaR (Value at Risk)** | Medida estatística que estima a perda máxima esperada de um investimento em um período, com determinado nível de confiança. |
| **Backtesting** | Processo de testar uma estratégia de investimento usando dados históricos. |
| **Derivativo** | Instrumento financeiro cujo valor deriva de um ativo subjacente (ex: opções, futuros). |
| **CAPM** | Modelo de precificação de ativos que relaciona risco e retorno esperado. |
| **Black-Scholes** | Modelo matemático clássico para precificação de opções financeiras. |
| **Série Temporal** | Conjunto de dados ordenados no tempo, usado para prever comportamentos futuros. |
| **Portfólio (Carteira)** | Conjunto de ativos financeiros mantidos por um investidor. |
| **Cálculo Estocástico** | Ramo da matemática usado para modelar processos aleatórios ao longo do tempo, essencial em finanças quantitativas. |
| **Sharpe Ratio** | Métrica que avalia o retorno de um investimento ajustado ao risco. |

---

### 3. Prompts Reutilizáveis (para futuras revisões)

```
1. "Resuma em 5 tópicos os principais conceitos sobre [tema específico] presentes nos documentos."

2. "Crie um glossário com os 10 termos mais importantes sobre [tema] encontrados nos documentos,
   com definições de até 2 linhas cada."

3. "Compare as abordagens de [conceito A] e [conceito B] mencionadas nos documentos, destacando
   semelhanças e diferenças."

4. "Com base nos documentos, sugira uma trilha de estudos estruturada por semanas sobre [tema]."

5. "Gere 5 perguntas de múltipla escolha para testar meu conhecimento sobre o conteúdo dos
   documentos relacionados a [tema]."

6. "Explique [conceito técnico] como se eu fosse um iniciante completo no assunto, usando
   analogias simples."
```

---

## 🛠️ Como este material foi construído

1. Seleção de 3 a 5 fontes abertas sobre Analista Quantitativo (artigos, PDFs e materiais introdutórios);
2. Upload das fontes no [NotebookLM](https://notebooklm.google.com/);
3. Elaboração de prompts estratégicos para extrair resumos, comparações e glossários;
4. Documentação do processo de tentativa e erro (troubleshooting) na engenharia de prompts;
5. Consolidação do conteúdo final neste README como Miniguia de Estudo.

