# 🏦 Análise Competitiva PJ

Estudo aprofundado do mercado bancário brasileiro voltado para Pessoa Jurídica (PJ), com foco na jornada de abertura de conta e os primeiros 90 dias de relacionamento. Análise realizada para subsidiar decisões estratégicas de produto, experiência do cliente e growth.

---

## 📑 Sumário

- [📋 Sobre o Projeto](#-sobre-o-projeto)
- [✅ Etapas Realizadas](#-etapas-realizadas)
- [🚀 Próximos Passos](#-próximos-passos)
- [⚠️ Desafios Encontrados](#️-desafios-encontrados)
- [💡 Aprendizados](#-aprendizados)
- [📁 Estrutura do Projeto](#-estrutura-do-projeto)
- [🔧 Como Usar](#-como-usar)
- [📝 Notas](#-notas)

---

## 📋 Sobre o Projeto

Este projeto consiste em uma análise competitiva estruturada do segmento bancário PJ no Brasil, avaliando como as principais instituições financeiras conduzem o início do relacionamento com clientes empresariais.

### 🎯 Objetivo Principal
Mapear e avaliar a experiência de abertura de conta PJ e os primeiros 90 dias de relacionamento em 12 instituições financeiras, identificando gaps, oportunidades e melhores práticas do mercado.

### 🔍 Escopo da Análise
- **Período analisado:** 2024-2025
- **Foco temporal:** Dia 0 (abertura) até Dia 90 (retenção)
- **Público-alvo:** MEI, ME, EPP, PME e Grandes Empresas

### 🏢 Instituições Analisadas

| Tipo | Instituições |
|------|-------------|
| Fintechs/Neobanks | Nubank, Inter Empresas, C6 Bank, Mercado Pago |
| Bancos Incumbentes (S1) | Itaú, Bradesco, Santander, Caixa Econômica |
| Banco S2/Digital | BTG Empresas |
| Cooperativa | Sicoob |
| Referências Internas | Itaú PF, Itaú Empresas |

### 📊 Metodologia
Cada análise segue uma estrutura de 8 blocos:
1. Informações Gerais (tipo, base de clientes, licença)
2. Abertura de Conta, Setup e Primeiros 90 Dias (com evidências visuais)
3. Recursos Avançados (API, ERP, automações)
4. Engajamento Digital (gamificação, recompensas)
5. Produtos e One-Click (facilidade de contratação)
6. Pontos Fortes, Fracos e Diferenciais
7. Reviews App Stores (análise qualitativa)
8. Mapa Visual de Screenshots

---

## ✅ Etapas Realizadas

- [x] Definição da metodologia de análise (prompt estruturado v3.0)
- [x] Criação do sistema de controle de concorrentes (`competitors-list.md`)
- [x] Análise individual dos 12 concorrentes
- [x] Coleta de evidências visuais (screenshots de apps, e-mails, fluxos)
- [x] Avaliação por categorias (notas 1-5 com evidências)
- [x] Geração do website interativo de inteligência competitiva
- [x] Estruturação das pastas e arquivos do projeto

### 📦 Entregáveis Produzidos
- **12 análises detalhadas** em `competitors/[nome]/[nome].md`
- **Website interativo** em `website/index.html` com:
  - Scorecard comparativo
  - Ranking de líderes por categoria
  - Gaps críticos identificados
  - Tabela de produtos One-Click
  - Sugestões estratégicas (curto/médio/longo prazo)
  - Perfis detalhados de cada concorrente

---

## 🚀 Próximos Passos

- [ ] Consolidar tabelas comparativas finais (`analysis/comparative-tables.md`)
- [ ] Elaborar análise de sentimento do cliente (`analysis/customer-sentiment-analysis.md`)
- [ ] Documentar insights estratégicos (`analysis/strategic-insights.md`)
- [ ] Validar análises com stakeholders
- [ ] Definir roadmap de ações baseado nos gaps identificados
- [ ] Agendar revisão periódica (recomendado: a cada 6 meses)

---

## ⚠️ Desafios Encontrados

### 🔎 Coleta de Dados
- Dificuldade em obter informações atualizadas de fluxos internos dos apps
- Necessidade de recorrer a múltiplas fontes (reviews, Reclame Aqui, vídeos YouTube) para validar informações
- Algumas instituições têm pouca transparência sobre o processo de abertura PJ

### 📐 Padronização
- Diferentes terminologias entre instituições para mesmas funcionalidades
- Variação na disponibilidade de informações públicas entre concorrentes
- Necessidade de criar critérios objetivos de avaliação para comparações justas

### 📏 Escopo
- Balancear profundidade da análise com volume de concorrentes
- Definir quais métricas são realmente comparáveis entre fintechs e incumbentes

---

## 💡 Aprendizados

### 🏛️ Sobre o Mercado
- **Fintechs lideram em UX de abertura:** Processos mais rápidos e menos burocráticos
- **Incumbentes se destacam em amplitude de produtos:** Maior oferta, mas com jornada mais fragmentada
- **Comunicação omnichannel é rara:** Poucos integram WhatsApp, e-mail, SMS e atendimento humano de forma consistente
- **One-click é diferencial competitivo:** Facilidade de contratar produtos impacta retenção

### ⚙️ Sobre o Processo
- Análise competitiva requer **metodologia bem definida** para garantir comparabilidade
- **Evidências visuais** (screenshots) são essenciais para embasar avaliações
- Manter **versionamento e datas** é crucial para rastrear evolução do mercado
- Estrutura de arquivos organizada facilita manutenção e atualizações futuras

### 🛠️ Sobre Ferramentas
- Utilização de Claude Code para automatizar geração de análises e website
- Markdown como formato central para documentação (portabilidade e versionamento)
- Website estático (HTML/Tailwind) permite visualização sem infraestrutura complexa

---

## 📁 Estrutura do Projeto

```
Analise-Competitiva/
├── README.md                    # Este arquivo
├── competitors-list.md          # Lista e status de todas as análises
├── run-prompt.md                # Prompt de análise (metodologia v3.0)
├── competitors/                 # Análises individuais
│   ├── nubank/
│   ├── itau/
│   ├── bradesco/
│   ├── santander/
│   ├── btg-empresas/
│   ├── inter-empresas/
│   ├── c6-bank/
│   ├── mercado-pago/
│   ├── sicoob/
│   ├── caixa/
│   ├── itau-pf/
│   └── itau-empresas/
├── analysis/                    # Análises consolidadas
│   ├── comparative-tables.md
│   ├── customer-sentiment-analysis.md
│   └── strategic-insights.md
├── website/                     # Dashboard interativo
│   ├── index.html
│   └── screenshots/
└── templates/                   # Templates reutilizáveis
```

---

## 🔧 Como Usar

1. **Consultar análise específica:** Acesse `competitors/[nome]/[nome].md`
2. **Visão geral interativa:** Abra `website/index.html` no navegador
3. **Adicionar novo concorrente:** Siga instruções em `competitors-list.md`
4. **Executar nova análise:** Utilize o prompt em `run-prompt.md`

---

## 📝 Notas

- Dados coletados entre Janeiro e Fevereiro de 2025
- Revisão recomendada a cada 6 meses ou após lançamentos relevantes
- Fontes principais: sites oficiais, App Store, Google Play, Reclame Aqui, press releases, Banco Central
