# PROPOSTA COMERCIAL — Programa de redução de turnover na linha de frente

*(Modelo no padrão Sterling — proposta de fornecedor de tecnologia para um cliente. Fornecedor, cliente, nomes e números: fictícios/ilustrativos, sem identificar empresa ou produtos reais.)*

**Preparado para:** Grupo Varejo Aurora — Diretoria de Gente & Gestão
**Preparado por:** a Empresa
**Data:** 07/11/2026

## 1. Overview

- **Propósito:** recomendar ao Grupo Aurora a adoção da Plataforma para reduzir o turnover da linha de frente e o custo de reposição associado, com piloto em 90 dias.
- **Problema (do cliente):** o Aurora perde ~45% dos operadores de loja por ano e descobre o risco de saída tarde demais para agir, o que eleva custo de reposição e derruba a produtividade das lojas.
- **Nossa conclusão:** o turnover do Aurora é previsível com os dados que a própria operação já gera; hoje falta instrumentação para antecipá-lo e um fluxo para agir antes da saída.
- **Recomendação:** implantar a Plataforma como camada de *people analytics + engajamento*, começando por um piloto em 12 lojas, com metas de retenção acordadas.
- **Alinhamentos já feitos:** diagnóstico validado em workshop com a Diretoria de Gente e dois gerentes regionais do Aurora; TI do cliente confirmou viabilidade de integração com a folha e o ponto.

## 2. Situation Analysis

**Histórico (contexto relevante):**
O Aurora cresceu de 90 para 140 lojas em três anos. O RH opera com processos desenhados para a escala antiga: pesquisas de clima anuais e gestão de desligamento reativa. A operação gera dados de ponto, folha e performance, mas eles não são lidos de forma preditiva.

**Fatos atuais (informados pelo cliente / verificáveis no diagnóstico):**
- Turnover anual da linha de frente: ~45% (benchmark do setor: 30–35%).
- Custo médio de reposição por operador: ~R$ 6.800 (recrutamento + treinamento + curva de produtividade).
- 68% dos desligamentos voluntários ocorrem nos primeiros 6 meses.
- A pesquisa de clima é anual — defasagem média de ~5 meses entre o sinal e a ação.
- Gerentes de loja não têm indicador de risco de saída por pessoa.

**Premissas (assumidas — se caírem, muda o caso):**
- Os dados de ponto, folha e performance estão acessíveis e com qualidade mínima para integração.
- Gerentes de loja terão ~1h/semana para agir sobre os alertas de risco.
- O padrão "saída previsível pelos dados existentes" se confirma no piloto (é o que o piloto testa).

## 3. Recommendation & Rationale

**Recomendação (o quê + como):**
Adotar a Plataforma em três frentes: (a) **modelo preditivo de risco de saída** por colaborador, alimentado pelos dados que o Aurora já tem; (b) **pulsos de engajamento** quinzenais que substituem a pesquisa anual; (c) **fluxo de ação para o gerente de loja** — alerta + próxima ação recomendada. Começar por um **piloto em 12 lojas** (~900 colaboradores) antes de escalar à rede.

**Razões de apoio — impacto no negócio (em cenários):**
Sobre uma base de ~9.000 colaboradores de linha de frente, o efeito de reduzir o turnover em pontos percentuais, via economia de custo de reposição em 12 meses:

| Cenário | Redução de turnover | Reposições evitadas/ano | Economia anual |
|---|---|---|---|
| Conservador | 45% → 40% | ~450 | ~R$ 3,1 mi |
| Base | 45% → 36% | ~810 | ~R$ 5,5 mi |
| Otimista | 45% → 32% | ~1.170 | ~R$ 8,0 mi |

- **Impacto no caixa do cliente:** cada reposição evitada é caixa que **não sai** — economia direta, não receita projetada. No cenário base, a economia paga o investimento anual em menos de 3 meses; o restante do ano é retorno líquido.
- **Precedentes:** redes varejistas comparáveis que adotaram a Plataforma reduziram turnover de linha de frente em 8–12 p.p. no primeiro ano (referências anonimizadas no Anexo 3).

**Investimento:** assinatura anual de R$ X por colaborador ativo + setup único de integração. O piloto de 12 lojas tem preço reduzido e condicionado a meta: se a retenção acordada não for atingida no piloto, o Aurora não é obrigado a prosseguir. *(Valores detalhados no Anexo 2.)*

## 4. Alternatives Considered

- **Alternativa A — Construir internamente (BI próprio + planilhas).** Rejeitada: o Aurora não tem time de data science dedicado a gente; o tempo até o primeiro resultado passaria de 12 meses e o custo de manutenção recai sobre TI.
- **Alternativa B — Só aumentar salário/benefício da linha de frente.** Rejeitada: ataca um sintoma (uma das causas) sem instrumentar as demais; eleva custo fixo de forma permanente sem mecanismo de ação dirigida.
- **Alternativa C — Manter a pesquisa de clima anual, reforçada.** Rejeitada: mantém a defasagem de ~5 meses entre sinal e ação — tarde demais para os desligamentos dos primeiros 6 meses, que são a maioria.
- **Status quo — não fazer nada.** Rejeitado: projeta manutenção de ~45% de turnover e custo de reposição recorrente superior a qualquer dos cenários de investimento.

*Critérios usados:* tempo até o primeiro resultado, efeito sobre a causa (antecipação), impacto no caixa, esforço de TI do cliente e reversibilidade.

## 5. Implementation Plan

1. **Semanas 1–2 — Integração.** Conexão com folha, ponto e performance; validação de qualidade de dados (a Empresa conduz, TI do Aurora apoia).
2. **Semanas 3–4 — Calibração.** Treino do modelo preditivo com histórico do Aurora; definição das metas de retenção do piloto.
3. **Semanas 5–12 — Piloto (12 lojas).** Alertas ativos para gerentes; pulsos quinzenais; acompanhamento semanal de indicadores.
4. **Semana 13 — Revisão de resultados e decisão de escala.**

- **Próximo passo imediato se aprovado:** assinatura do piloto e kickoff de integração com a TI do Aurora na semana seguinte.
- **Como mediremos sucesso:** retenção a 6 meses nas lojas-piloto vs. grupo de controle (meta: +6 p.p.) e redução do custo de reposição no período. Gatilho de não-escala: se o ganho de retenção no piloto ficar abaixo da meta acordada, o Aurora encerra sem compromisso de rede.

## 6. Supporting Data/Documentation

- **Anexo 1:** diagnóstico do Aurora — turnover por tempo de casa, por região e por função.
- **Anexo 2:** proposta comercial detalhada — preço do piloto, assinatura anual, setup e cálculo de payback por cenário.
- **Anexo 3:** casos de referência anonimizados (varejo comparável) com resultados de retenção.
- **Anexo 4:** arquitetura de integração e requisitos de dados/TI.

---

**Nota sobre a adaptação:** o padrão Sterling continua levando o leitor **da recomendação para a evidência**, mas aqui o "aprovador" é o cliente, a seção de custo vira **investimento + ROI**, e as "alternativas consideradas" incluem as opções que o próprio cliente teria (construir, pagar mais, status quo) — o que torna a proposta mais defensável e menos "vendedora".
