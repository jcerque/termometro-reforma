# Material de Transição — Sessão "sterling-decision-model"

**Repositório:** `jcerque/termometro-reforma`
**Branch da sessão:** `claude/sterling-decision-model-l4fvkf`
**Data da passagem:** 2026-11-10
**Estado do working tree:** limpo (sem alterações não commitadas)

> Documento de passagem para a próxima sessão/pessoa. Lê-se de cima para baixo: objetivo,
> o que esta sessão fez, estado atual, pendências e arquivos relevantes.

---

## 1. Objetivo

Dois níveis se sobrepõem nesta sessão — importante não confundir:

- **Projeto (repositório):** é a suíte **Termômetro da Reforma** (EQVALOR), um conjunto de
  páginas estáticas publicadas em `termometro.eqvalor.com.br` (GitHub Pages, ver `CNAME`) sobre o
  impacto **financeiro** da Reforma Tributária — margem, caixa e capital de giro, não conformidade fiscal.
- **Trabalho desta sessão (branch `sterling-decision-model`):** NÃO alterou o código da suíte.
  A sessão foi usada para **produzir e demonstrar o modelo de decisão Sterling** (skill
  `sterling-proposal`) e gerar **propostas-exemplo** a partir dele.

## 2. O que foi feito nesta sessão

Todo o resultado foi entregue **inline no chat** — **nada foi salvo em arquivo nem commitado**
(exceto este próprio documento de transição).

1. **Descrição do modelo de decisão Sterling** — explicação das 4 fases iterativas do *Problem
   Solving Process* (Preparação/WHY, Geração/HOW, Decisão/WHICH, Implementação/DO) e do *Proposal
   Format* de 6 seções (Overview, Situation Analysis, Recommendation & Rationale, Alternatives
   Considered, Implementation Plan, Supporting Data).
2. **Proposta-modelo 1 — memorando de decisão interno** de uma empresa de tecnologia B2B SaaS.
   Cenário: queda de NRR no mid-market por falha de ativação. Anonimizada (sem identificar empresa
   ou produtos reais).
3. **Proposta-modelo 2 — proposta comercial de fornecedor para um cliente.** Cenário: programa de
   redução de turnover para um varejista fictício. Também anonimizada.

## 3. Decisões tomadas

- Adotar o **padrão Sterling** (Problem Solving Process + Proposal Format) como estrutura das propostas.
- **Anonimizar** empresa e produtos de referência em todos os exemplos — usar "a Empresa" / "a
  Plataforma" e clientes fictícios; números ilustrativos.
- Nas propostas financeiras, usar **sensibilidade multi-cenário** (conservador/base/otimista) e
  destacar o **efeito no ciclo de caixa**, não só o resultado contábil (preferência do João).
- Na proposta comercial, as "Alternatives Considered" incluem as opções do próprio **cliente**
  (construir internamente, pagar mais, status quo), para ficar defensável e menos "vendedora".
- Entrega **inline por padrão**, oferecendo o `.docx` ao final — não foi gerado `.docx` nesta sessão
  (ninguém confirmou).

## 4. Estado atual

- Branch `claude/sterling-decision-model-l4fvkf` **sem commits novos** além do histórico já mergeado;
  working tree limpo.
- As propostas-exemplo existem **apenas no histórico da conversa** (use `/export` para preservá-lo).
- **Não existe `CLAUDE.md`** no repositório.

## 5. Pendências (abertas)

- [ ] **Persistir os exemplos Sterling**, se forem úteis: salvar como `.md`/`.docx` e/ou commitar,
      ou descartar se eram só demonstração.
- [ ] **Gerar `.docx`** de qualquer uma das duas propostas, se for circular (interna ou ao cliente).
- [ ] **Decidir o destino deste arquivo** (`MATERIAL-DE-TRANSICAO.md`): hoje está **untracked** na
      raiz do repo. Commitar, mover para fora do repo, ou apagar após a passagem.
- [ ] **Criar um `CLAUDE.md`** do repositório concentrando instruções/convenções da suíte
      (o próprio pedido de transição sugere que ele deveria existir) — opcional.
- [ ] Exportar o histórico completo com `/export` se quiser o registro integral junto.

## 6. Arquivos relevantes

### Do repositório (a suíte Termômetro da Reforma)
| Arquivo | Papel |
|---|---|
| `index.html` | **Termômetro da Reforma** — ferramenta de entrada (laudo/diagnóstico gratuito). |
| `transicao.html` | **Planilha da Transição 2026–2033** — motor de margem líquida (DRE), mix de enquadramento LC 214, KPIs; tranca de acesso por convite/e-mail; modo exemplo com dados fictícios; preenchimento por CNPJ via BrasilAPI. |
| `ferramentas.html` | **Vitrine de ferramentas** da suíte — navegação e handoffs por persona. |
| `admin.html` | Painel administrativo do Termômetro. |
| `CNAME` | Domínio do GitHub Pages: `termometro.eqvalor.com.br`. |

### Desta sessão
| Item | Onde está |
|---|---|
| Modelo Sterling + 2 propostas-exemplo | **Somente no chat** — não salvos em arquivo. Use `/export` para preservar. |
| `MATERIAL-DE-TRANSICAO.md` | Este documento (raiz do repo, untracked). |

### Skill usada
| Skill | Local |
|---|---|
| `sterling-proposal` | `~/.claude/skills/sterling-proposal/` — `SKILL.md` + `references/processo-resolucao-problemas.md` + `references/formato-proposta.md`. |

---

## Notas para quem assume

- **`CLAUDE.md`: não existe.** Não há instruções/convenções centralizadas do repositório para levar
  junto; se precisar delas, terá de reconstruir ou criar o arquivo.
- O histórico git mostra que o trabalho **de produto** da suíte vinha pela branch
  `claude/tax-reform-spreadsheet-ux0hn9` (PRs #1–#7). Esta branch (`sterling-decision-model`) é
  paralela e **não** tocou o produto.
- Se o objetivo for continuar a suíte, comece pelos PRs mergeados acima e por `transicao.html` /
  `index.html`. Se for continuar o trabalho de propostas, o material está no chat (exporte antes de fechar).
