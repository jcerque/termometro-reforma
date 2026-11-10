# PROPOSTA — Resposta à queda de retenção de receita no segmento mid-market

*(Documento-modelo no padrão Sterling Drug — memorando de decisão interno. Empresa de referência: fornecedor B2B SaaS. Nomes, partes interessadas e números: fictícios/ilustrativos, sem identificar empresa ou produtos reais.)*

## 1. Overview

- **Propósito:** recomendar um curso de ação para estancar a queda da retenção de receita líquida (NRR) da Plataforma no segmento mid-market e levá-la à aprovação do comitê executivo.
- **Problema:** a NRR do mid-market caiu de 108% para 94% em quatro trimestres porque clientes não atingem o uso mínimo que sustenta a renovação, não por preço.
- **Conclusão do autor:** o problema é de **ativação e adoção pós-venda**, não comercial nem de produto. Vendemos bem e o produto entrega; os clientes não chegam ao valor a tempo da primeira renovação.
- **Recomendação:** implantar um motor de *onboarding orientado a marcos de ativação* com um time dedicado de Customer Success (CS) para o mid-market, atrelando contratos a metas de adoção nos primeiros 90 dias.
- **Concordâncias já obtidas:** VP de Produto e Diretor Comercial endossam o diagnóstico; Financeiro validou o modelo de impacto de caixa (Anexo 2). Falta a decisão do comitê sobre funding.

## 2. Situation Analysis

**Histórico (contexto que sustenta a decisão):**
A Empresa cresceu com vendas *self-service* e enterprise. O mid-market foi aberto há 24 meses e passou a responder por ~40% da nova receita, mas nunca recebeu um motor de pós-venda próprio — herdou o fluxo *self-service*, desenhado para contas que se viram sozinhas.

**Fatos atuais (verificáveis):**
- NRR mid-market: 108% → 94% em 4 trimestres (Anexo 1).
- Churn concentra-se na 1ª renovação: 71% dos cancelamentos ocorrem entre o mês 10 e o 13.
- Contas que ativam ≥3 módulos nos primeiros 90 dias renovam a 92%; as que ativam ≤1 renovam a 48%.
- Causa de cancelamento informada: "não chegamos a usar como esperávamos" (63%), não "caro" (11%).
- Hoje há 1 CSM para cada ~180 contas mid-market; enterprise opera a 1:25.

**Premissas (assumidas — se caírem, muda a resposta):**
- O padrão de correlação entre ativação e renovação se mantém nas safras futuras.
- A capacidade de produto para instrumentar marcos de ativação existe no roadmap do próximo trimestre.
- O mix de aquisição mid-market permanece estável (sem mudança abrupta de ICP).

## 3. Recommendation & Rationale

**Recomendação (o quê + como):**
Criar um motor de ativação para o mid-market com três componentes: (a) um **plano de ativação de 90 dias** com marcos mensuráveis por cliente; (b) um **time de CS dedicado** dimensionado a 1:60; (c) **gatilhos de produto** que sinalizam risco de baixa adoção e disparam intervenção. Contratos novos passam a incluir um *success plan* com metas de adoção acordadas na assinatura.

**Razões de apoio:**
- **Impacto no negócio (em cenários):** elevar a taxa de "contas bem ativadas" move a NRR de volta à faixa de 105–110%. Efeito sobre a receita de renovação do mid-market nos próximos 12 meses:

  | Cenário | Ganho de ativação | NRR projetada | Receita de renovação incremental (12m) |
  |---|---|---|---|
  | Conservador | +10 p.p. de contas ativadas | 99% | + R$ 2,1 mi |
  | Base | +20 p.p. | 104% | + R$ 4,3 mi |
  | Otimista | +30 p.p. | 109% | + R$ 6,6 mi |

- **Impacto no ciclo de caixa:** reter uma conta na 1ª renovação preserva receita recorrente a **custo de aquisição zero** — o CAC já foi pago. Cada ponto de NRR recuperado melhora a previsibilidade de caixa sem novo desembolso comercial, ao contrário de compensar o churn com mais vendas (que exigem CAC adiantado e alargam o ciclo caixa-a-caixa).
- **Precedentes:** o mesmo motor aplicado ao enterprise sustenta NRR de 118%; a diferença operacional entre os segmentos é justamente a ausência desse motor no mid-market.

**Custo/Funding:** R$ 1,4 mi/ano (6 CSMs + instrumentação de produto). Origem: realocação de 2 vagas comerciais ainda não preenchidas + orçamento de retenção. *Payback* no cenário base < 5 meses (Anexo 2).

## 4. Alternatives Considered

- **Alternativa A — Desconto na renovação / plano mais barato.** Rejeitada: o churn não é dirigido por preço (11% citam custo). Baixaria margem e caixa sem atacar a causa (ativação).
- **Alternativa B — Compensar o churn com mais aquisição comercial.** Rejeitada contra o critério de caixa: exige CAC adiantado, alarga o ciclo de caixa e não corrige o vazamento — encher um balde furado.
- **Alternativa C — Automação de onboarding sem time dedicado (só e-mails/in-app).** Rejeitada: é o modelo *self-service* atual, que já falha no mid-market; contas dessa faixa precisam de intervenção humana nos marcos.
- **Status quo — não fazer nada.** Rejeitado: a tendência projeta NRR < 90% em 2 trimestres, com perda de receita recorrente superior ao custo da intervenção.

*Critérios de decisão usados:* efeito na causa-raiz (ativação), impacto no ciclo de caixa, reversibilidade, custo e prazo até resultado.

## 5. Implementation Plan

1. **Semanas 1–2 — Estrutura.** Aprovar funding; definir os marcos de ativação (com Produto e CS); contratar/realocar os 2 primeiros CSMs.
2. **Semanas 3–6 — Instrumentação.** Produto entrega os gatilhos de adoção; CS cria o template de *success plan* de 90 dias.
3. **Semanas 7–12 — Piloto.** Aplicar a uma safra de ~50 contas novas + 30 contas em risco (meses 8–10). Medir ativação e renovação.
4. **A partir da semana 13 — Escala.** Estender a todo o mid-market conforme o piloto.

- **Próximo passo imediato se aprovado:** liberar as 2 vagas de CS e abrir a definição dos marcos de ativação na semana seguinte.
- **Como mediremos sucesso:** % de contas com ≥3 módulos ativos em 90 dias (meta +20 p.p.) e NRR mid-market trimestral (meta de retorno à faixa 105–110% em 3 trimestres). Gatilho de correção de rota: se a ativação não subir ≥8 p.p. no piloto, revisar o desenho antes de escalar.

## 6. Supporting Data/Documentation

- **Anexo 1:** série trimestral de NRR, churn por mês de contrato e coorte de ativação × renovação.
- **Anexo 2:** modelo de impacto de caixa — cenários conservador/base/otimista, payback e sensibilidade ao custo do time.
- **Anexo 3:** benchmark enterprise × mid-market (razão CSM:contas e NRR).

---

**Notas sobre o uso deste modelo:** o Overview é auto-suficiente (um leitor que pare nele tem o essencial); a frase do problema é a mesma no Overview e na análise; fatos e premissas estão rotulados separadamente; há quatro alternativas reais (incluindo status quo) rejeitadas pelos mesmos critérios da escolha; e o impacto financeiro vem em multi-cenário com foco em caixa — tudo conforme o checklist Sterling.
