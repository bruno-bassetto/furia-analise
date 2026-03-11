# O Paradoxo da FURIA — Análise Técnica · CBLOL Cup 2026

**[🇧🇷 Português](#português) · [🇺🇸 English](#english)**

---

## Português

### Sobre o projeto

Análise técnica e estatística do confronto FURIA vs RED Canids no CBLOL Cup 2026, com foco em responder uma pergunta específica: **por que o melhor early game da região não se converte em vitórias contra um adversário específico?**

O projeto parte de dados públicos do Oracle's Elixir (23.268 linhas, 165 colunas) e combina análise quantitativa com revisão qualitativa de VODs para identificar o mecanismo de derrota e propor recomendações acionáveis para o coaching staff.

### Documentos

| Documento | Descrição | Link |
|-----------|-----------|------|
| 📊 Análise Técnica | Sistema de notas por jogador, confronto direto, diagnóstico RED, mecanismo de derrota, evidência qualitativa e rankings por posição | [Abrir](https://bruno-bassetto.github.io/furia-analise/) |
| 📋 Recomendações | 7 recomendações estruturadas em curto e médio prazo para o coaching staff, com evidência específica para cada uma | [Abrir](https://bruno-bassetto.github.io/furia-analise/recomendacoes.html) |

### Principais achados

- **Baron = resultado em 7/7 jogos** — correlação perfeita. O Baron é o único fator que determina 100% dos resultados da série.
- **FURIA tem o melhor early game da região** (GD@15 médio +1085), mas colapsa entre @15 e @20 nos confrontos vs RED (de −141 para −1184 de ouro médio).
- **FURIA supera a RED em ward kills em todos os 7 jogos** (1.2–1.65×) — o problema não é ausência de visão, é a tomada de decisão com a visão disponível.
- **WR em scrims próximo de 60% vs RED** — o colapso é específico dos jogos oficiais, descartando diferença de elenco como causa.
- **4 de 5 jogadores da RED elevam sua performance especificamente nos confrontos vs FURIA**, enquanto 4 de 5 jogadores da FURIA performam abaixo da média geral nesses mesmos jogos.

### Stack técnica

- **Python** (pandas, numpy, matplotlib, seaborn)
- **Google Colab** para processamento e análise
- **Oracle's Elixir** como fonte de dados
- **HTML/CSS/JS** para visualização dos relatórios

### Metodologia

Sistema de notas por jogador (0–10) calculado a partir de métricas normalizadas contra o pool geral de cada jogo (10 jogadores), com pesos calibrados por posição. Nota final = mediana de todas as partidas. As notas não são comparáveis entre lanes por design.

---

## English

### About

Technical and statistical analysis of the FURIA vs RED Canids matchup at CBLOL Cup 2026, focused on a specific question: **why does the best early game in the region fail to convert into wins against a specific opponent?**

The project uses public Oracle's Elixir data (23,268 rows, 165 columns) and combines quantitative analysis with qualitative VOD review to identify the defeat mechanism and propose actionable recommendations for the coaching staff.

### Documents

| Document | Description | Link |
|----------|-------------|------|
| 📊 Technical Analysis | Player rating system, head-to-head breakdown, RED diagnosis, defeat mechanism, qualitative evidence and per-role rankings | [Open](https://bruno-bassetto.github.io/furia-analise/) |
| 📋 Recommendations | 7 structured short and medium-term recommendations for the coaching staff, each backed by specific evidence | [Open](https://bruno-bassetto.github.io/furia-analise/recomendacoes.html) |

### Key findings

- **Baron = result in 7/7 games** — perfect correlation. Baron control is the single factor that determines 100% of the series outcomes.
- **FURIA has the best early game in the region** (avg GD@15 +1085), but collapses between @15 and @20 in games vs RED (from −141 to −1184 avg gold diff).
- **FURIA outperforms RED in ward kills in all 7 games** (1.2–1.65×) — the problem is not lack of vision, but decision-making with the available information.
- **~60% scrim win rate vs RED** — the collapse is specific to official games, ruling out roster quality as the root cause.
- **4 of 5 RED players elevate their performance specifically in FURIA matchups**, while 4 of 5 FURIA players perform below their general average in those same games.

### Tech stack

- **Python** (pandas, numpy, matplotlib, seaborn)
- **Google Colab** for processing and analysis
- **Oracle's Elixir** as data source
- **HTML/CSS/JS** for report visualization

### Methodology

Player rating system (0–10) calculated from metrics normalized against the general pool of each game (10 players), with position-calibrated weights. Final rating = median across all games played. Ratings are not cross-position comparable by design.

---

## Autor · Author

**Bruno Bassetto**
Engenharia Elétrica · Esports Analytics

[![LinkedIn](https://img.shields.io/badge/LinkedIn-bruno--bassetto-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/bruno-bassetto)
[![Email](https://img.shields.io/badge/Email-brunobassetto3@gmail.com-D14836?style=flat&logo=gmail)](mailto:brunobassetto3@gmail.com)

---

*Dados: Oracle's Elixir · CBLOL Cup 2026 · Março 2026*
