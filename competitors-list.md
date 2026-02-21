# Lista de Concorrentes

# competitors-list.md
> Arquivo de controle da lista de concorrentes a serem analisados.
> **Instrução ao agente:** Sempre leia este arquivo ANTES de iniciar qualquer análise.
> Ele define quais instituições devem ser cobertas, o status de cada análise e o caminho do arquivo de output.

---

## Como usar este arquivo

- Cada linha da tabela representa um concorrente a analisar
- O campo `Status` indica se a análise já foi feita, está em andamento ou pendente
- O campo `Arquivo` aponta para o `.md` dentro da pasta `competitors/[nome]/`
- Ao concluir uma análise, atualize o `Status` e a `Última atualização`

---

## Lista de Concorrentes · Segmento Bancário PJ

| # | Instituição | Tipo | Segmento PJ foco | Status | Arquivo | Última atualização |
|---|-------------|------|-----------------|--------|---------|-------------------|
| 01 | Nubank | Fintech / Neobank | MEI, ME, EPP | ✅ Concluída | `competitors/nubank/nubank.md` | Fev/2025 |
| 02 | Itaú | Banco Incumbente S1 | Todos os portes | ✅ Concluída | `competitors/itau/itau.md` | Fev/2025 |
| 03 | Bradesco | Banco Incumbente S1 | Todos os portes | ✅ Concluída | `competitors/bradesco/bradesco.md` | Fev/2025 |
| 04 | Santander | Banco Incumbente S1 | Todos os portes | ✅ Concluída | `competitors/santander/santander.md` | Fev/2025 |
| 05 | BTG Empresas | Banco S2 / Fintech | PME, Médias, Grandes | ✅ Concluída | `competitors/btg-empresas/btg-empresas.md` | Fev/2025 |
| 06 | Inter Empresas | Banco Digital / Fintech | MEI, ME, EPP, PME | ✅ Concluída | `competitors/inter-empresas/inter-empresas.md` | Fev/2025 |
| 07 | C6 Bank | Banco Digital / Fintech | MEI, ME, EPP | ✅ Concluída | `competitors/c6-bank/c6-bank.md` | Fev/2025 |
| 08 | Mercado Pago | Fintech / IP | MEI, ME (vendedores MP) | ✅ Concluída | `competitors/mercado-pago/mercado-pago.md` | Fev/2025 |
| 09 | Sicoob | Cooperativa de Crédito | Todos os portes | ✅ Concluída | `competitors/sicoob/sicoob.md` | Fev/2025 |
| 10 | Caixa Econômica | Banco Incumbente S1 | Todos os portes | ✅ Concluída | `competitors/caixa/caixa.md` | Fev/2025 |
| 11 | Itaú PF | Banco Incumbente S1 — Referência interna PF | Pessoas Físicas | ✅ Concluída | `competitors/itau-pf/itau-pf.md` | Fev/2025 |
| 12 | Itaú Empresas | Banco Incumbente S1 — Produto próprio | MEI, ME, EPP, PME, Grandes | ✅ Concluída | `competitors/itau-empresas/itau-empresas.md` | Fev/2025 |

---

## Status legend

| Ícone | Significado |
|-------|-------------|
| 🔲 Pendente | Análise ainda não iniciada |
| 🔄 Em andamento | Análise em execução |
| ✅ Concluída | Análise finalizada e arquivo preenchido |
| 🔁 Desatualizada | Análise feita mas dados precisam de revisão (>6 meses) |

---

## Instruções para adicionar novos concorrentes

1. Adicione uma linha na tabela acima com o número sequencial, nome, tipo e segmento
2. Defina o status como `🔲 Pendente`
3. Crie a pasta: `competitors/[slug-do-nome]/`
4. Crie o arquivo: `competitors/[slug-do-nome]/[slug-do-nome].md`
5. Execute o prompt de análise referenciando este arquivo

---

## Notas editoriais

- Prioridade de análise: fintechs e neobanks digitais primeiro (maior velocidade de mudança)
- Revisão recomendada: a cada 6 meses ou após lançamento relevante do concorrente
- Fonte de novos concorrentes: Distrito Fintech Report, Banco Central (lista de IFs), press
