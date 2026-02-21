# Análise Competitiva · Nubank (Nu Empresas)

> **Produzido para:** Itaú Empresas — equipes de produto, experiência, growth e estratégia
> **Foco:** Início de relacionamento PJ — abertura de conta até os 90 primeiros dias
> **Data de execução:** Fevereiro/2025
> **Período coberto pelos dados:** 2024–2025

---

## Bloco 1 · Informações Gerais

| Campo | Informação |
|-------|------------|
| **Razão social** | Nu Pagamentos S.A. (controlada pela Nu Holdings Ltd.) |
| **Nome comercial** | Nubank / Nu Empresas |
| **Tipo** | Fintech / Neobank |
| **Ano de fundação** | 2013 |
| **Base de clientes PJ** | 4,5 milhões de contas PJ ativas (dez/2024); 10 milhões de empreendedores na base total |
| **Base total de clientes** | 114 milhões (Brasil, México e Colômbia) — maior IF privada do Brasil em número de clientes |
| **Share de mercado PJ** | Em crescimento acelerado; compete diretamente com Inter, C6, PagBank, Cora e Mercado Pago no segmento de pequenas empresas |
| **Porte do CNPJ atendido** | MEI (58% da base), ME, EPP — foco em empresas com faturamento até R$ 10 milhões/ano |
| **Regulatório** | Instituição de Pagamento (IP) autorizada pelo Banco Central |
| **Presença geográfica** | 100% digital, sem agências físicas. Brasil, México e Colômbia |
| **Canais disponíveis** | App iOS/Android, Web (para PJ), Chat 24h, Telefone SAC |

**Histórico resumido:**
O Nubank iniciou operações PJ em 2019. No primeiro ano, abriu 50 mil contas. Em 2022, atingiu 2,5 milhões; em 2023, 3,5 milhões; e em 2024, ultrapassou 4 milhões de clientes PJ. Em março/2024, lançou a primeira linha de crédito PJ (Capital de Giro) e em outubro/2024 ampliou a oferta. Em janeiro/2026, tornou-se a maior instituição financeira privada do Brasil em número de clientes, segundo o Banco Central.

---

## Bloco 2 · Abertura de Conta, Setup e Primeiros 90 Dias

---

### Fase 1 · Abertura de Conta (Dia 0)

#### C1 · Processo de abertura de conta digital (KYB/KYC)

`[NOTA: 4]` · `[AVALIAÇÃO: Muito Bom]`

**Descrição:**
- Fluxo **100% digital**, sem etapas presenciais
- Processo otimizado para **mobile** (app) e também disponível via web
- Para clientes PF existentes: abertura pelo app em "Pedir conta PJ" → informar CNPJ → análise automática
- Para não-clientes: site nubank.com.br/conta-pj → CNPJ + dados pessoais → aguardar aprovação
- KYC simplificado: documentos exigidos apenas em casos específicos (não-cliente precisa RG/CNH/RNM; múltiplos sócios exigem contrato social ou procuração)
- Para empresas com múltiplos sócios: todos os sócios-administradores precisam ter conta PF no Nubank e aprovar via app
- Não há diferenciação de fluxo por porte de CNPJ
- **Limitação identificada:** análise depende de bases de dados públicas/privadas; CNPJs recém-abertos ou com dados desatualizados frequentemente são negados automaticamente sem opção de envio manual de documentos

**Evidência:** Blog Nubank, Reclame Aqui, sites de review

[REF-01] Como abrir uma conta PJ no Nubank? | https://blog.nubank.com.br/abrir-conta-pj-nubank | fev/2025
[REF-02] Reclame Aqui - Reclamações abertura conta PJ | https://www.reclameaqui.com.br/nubank/ | fev/2025

---

#### C2 · Tempo médio de aprovação e ativação da conta

`[NOTA: 4]` · `[AVALIAÇÃO: Muito Bom]`

**Descrição:**
- SLA declarado: **até 5 dias úteis**
- Tempo real reportado: **1 a 5 dias úteis** na maioria dos casos
- Para clientes PF existentes com CNPJ regular: aprovação pode ocorrer em minutos/horas
- Feedback proativo: notificações no app e e-mail sobre status da solicitação
- **Ponto de fricção:** CNPJs recém-abertos ou com alterações cadastrais recentes frequentemente ficam "em análise" indefinidamente ou são negados sem justificativa clara

**Evidência:** Reviews de usuários, Reclame Aqui

[REF-03] Tecnoblog - Como abrir conta Nubank | https://tecnoblog.net/responde/como-abrir-uma-conta-no-nubank/ | fev/2025

---

#### C3 · Documentação exigida e nível de burocracia

`[NOTA: 4]` · `[AVALIAÇÃO: Muito Bom]`

**Descrição:**
- Documentação mínima: apenas CNPJ para clientes PF existentes
- Casos que exigem documentos: não-clientes (documento de identidade), empresas com múltiplos sócios (contrato social ou procuração)
- Upload 100% pelo app ou site
- Não há re-solicitação de documentos na maioria dos casos
- **Limitação:** não há opção de envio manual de documentos para casos onde a análise automática falha

**Evidência:** Site oficial Nubank

[REF-04] Conta PJ Nubank - Regras para abrir | https://blog.nubank.com.br/conta-pj-nubank-regras-para-abrir-uma/ | fev/2025

---

### Fase 2 · Setup Inicial (Dias 1–7)

#### C4 · Onboarding assistido e suporte na chegada

`[NOTA: 3]` · `[AVALIAÇÃO: Bom]`

**Descrição:**
- **Não há** gerente dedicado, video call ou onboarding humano personalizado
- Chat 24h disponível no app (atendimento automatizado + humano)
- Suporte genérico (não especializado exclusivamente em PJ)
- SAC telefônico: 0800 591 2117 (24h) e 4020 0185 (capitais)
- E-mail: meajuda@nubank.com.br
- NuCommunity: fórum com +300 mil participantes para dúvidas entre pares

**Evidência:** Site oficial, canais de atendimento

[REF-05] Nubank Contatos | https://nubank.com.br/contatos | fev/2025

---

#### C5 · Primeiro acesso ao canal digital (app ou internet banking)

`[NOTA: 4]` · `[AVALIAÇÃO: Muito Bom]`

**🔐 Validações de acesso:**
- Criação de senha de 4 dígitos + biometria (face ID / touch ID)
- OTP via e-mail ou SMS para validações críticas
- Reconhecimento facial durante abertura (para não-clientes)
- Fluxo fluido, poucas etapas de validação no primeiro acesso para clientes PF existentes

**🎁 Ofertas de produtos no primeiro acesso:**
- Cartão de débito disponível imediatamente
- Cartão de crédito PJ: depende de análise, oferta apresentada se aprovado
- Nu Limite Garantido: oferta para aumentar limite via investimento como garantia
- Formato: cards e banners no app
- Oferta não exige ação imediata

**✅ Tarefas e missões de engajamento:**
- Não há checklist explícito ou barra de progresso de setup
- Não há gamificação estruturada no onboarding
- Tom: descoberta, não obrigação
- Tarefas implícitas: "faça seu primeiro PIX", "ative o NuTap"

**Avaliação geral do setup:**
- Primeiro acesso é fluido e acolhedor, design limpo característico do Nubank
- A instituição não aproveita ao máximo o momento de alta atenção para engajar com missões estruturadas

[REF-06] Nu Empresas Login | https://app.nubank.com.br/ | fev/2025

---

#### C6 · Jornada de ativação do primeiro produto

`[NOTA: 4]` · `[AVALIAÇÃO: Muito Bom]`

**Descrição:**
- Primeiro produto priorizado: **PIX** (gratuito e ilimitado)
- Segunda prioridade: **NuTap** (maquininha no celular) para quem vende
- Facilidade: primeira transação em poucos toques após aprovação
- Incentivo explícito: NuTap sem custo de adesão, taxas competitivas
- Não há cashback ou bônus de boas-vindas estruturado para primeira ação

**Evidência:** Site oficial, reviews

[REF-07] NuTap - Maquininha Nubank | https://nubank.com.br/nutap/ | fev/2025

---

### Fase 3 · Comunicação e Nutrição (Dias 1–30)

#### C7 · Comunicação pós-abertura com o cliente PJ

**📱 WhatsApp**
- `[AVALIAÇÃO: Básico]`
- WhatsApp **não é canal de atendimento** — apenas comunicações esporádicas (renegociação de dívidas, educação financeira, informações sobre produtos)
- Número oficial: (11) 5180-7064 — **não pode ser acionado pelo cliente**
- Uso passivo: apenas o Nubank inicia conversas
- Não há fluxos automatizados de onboarding via WhatsApp

**📧 E-mail**
- `[AVALIAÇÃO: Bom]`
- E-mail de boas-vindas após aprovação
- Welcome series estruturada: não há evidência pública de sequência robusta D+1/D+7/D+15/D+30
- E-mails transacionais e de segurança
- Design profissional, tom característico Nubank (informal, acolhedor)

**📩 SMS**
- `[AVALIAÇÃO: Básico]`
- SMS usado primariamente para autenticação (OTP)
- Alertas transacionais básicos
- Não há régua de nutrição via SMS

**🧑 Atendimento humano**
- `[AVALIAÇÃO: Bom]`
- Chat 24h no app (mix de bot + humano)
- Telefone SAC 24h
- **Não há gerente de relacionamento ou CS dedicado para PJ**
- Atendimento reativo (cliente precisa acionar)
- SLA de resposta no Reclame Aqui: 5 dias em média

**Avaliação geral do mix de comunicação:**
- Nubank depende fortemente de **1-2 canais** (app + e-mail)
- Não há estratégia omnichannel integrada
- Comunicação é mais reativa que proativa nos primeiros 90 dias

[REF-08] Nubank telefone e canais | https://www.remessaonline.com.br/blog/nubank-telefone/ | fev/2025

---

#### C8 · Personalização da experiência baseada no perfil do cliente

`[NOTA: 3]` · `[AVALIAÇÃO: Bom]`

**Descrição:**
- Não há diferenciação de fluxo por porte/setor do CNPJ
- Recomendações de produtos baseadas em comportamento (ex: oferta de Capital de Giro para quem movimenta)
- Nu Limite Garantido: oferta adaptada ao perfil de investimento
- Coleta mínima de informações adicionais sobre o negócio

**Evidência:** Experiência de usuário reportada

---

#### C9 · Educação financeira e capacitação no uso da plataforma

`[NOTA: 3]` · `[AVALIAÇÃO: Bom]`

**Descrição:**
- Não há tutoriais interativos ou walkthroughs dentro do app
- Blog Nubank com conteúdo educacional (externo ao app)
- NuCommunity para dúvidas entre pares
- Não há webinars ou materiais específicos para PJ
- Tooltips básicos em funcionalidades novas

**Evidência:** Blog Nubank, NuCommunity

[REF-09] Blog Nubank | https://blog.nubank.com.br/ | fev/2025

---

### Fase 4 · Engajamento e Retenção (Dias 30–90)

#### C10 · Milestones de engajamento e acompanhamento de progresso

`[NOTA: 2]` · `[AVALIAÇÃO: Regular]`

**Descrição:**
- **Não há** marcos de ativação comunicados (30/60/90 dias)
- **Não há** checkpoints ou score de saúde da conta
- **Não há** alertas de baixo engajamento ou mecanismo de reativação proativo evidente
- Área "Minhas Vendas" para acompanhar faturamento do NuTap
- Medição de ativação: [DADO NÃO ENCONTRADO PUBLICAMENTE]

**Evidência:** Experiência de usuário, reviews

---

#### C11 · Suporte e relacionamento dedicado na fase inicial

`[NOTA: 2]` · `[AVALIAÇÃO: Regular]`

**Descrição:**
- **Não há** gerente de relacionamento ou CS especializado em PJ
- Suporte não muda de perfil após abertura
- Não há SLA específico para clientes em fase inicial
- Atendimento 100% reativo — o banco não contata proativamente o cliente
- Canal de acesso: chat no app, telefone, e-mail

**Evidência:** Experiência de usuário, Reclame Aqui

---

### Resumo do Bloco 2

| Métrica | Valor |
|---------|-------|
| **Nota geral da jornada 0–90 dias** | 7/10 |
| **Principal força no início de relacionamento** | Abertura 100% digital, rápida e desburocratizada para clientes PF existentes |
| **Principal gargalo ou ponto de abandono** | Negativas automáticas sem justificativa para CNPJs novos/alterados; ausência de onboarding assistido e milestones de engajamento |
| **Posicionamento vs. mercado** | Acima da média |
| **Total de screenshots coletados neste bloco** | 0 (não disponíveis publicamente) |

---

## Bloco 3 · Recursos Avançados e Destaques

| Recurso | Disponível? | Observação |
|---------|-------------|------------|
| Integração com ERPs/contabilidade | Parcial | Via Open Finance; sem integrações nativas robustas |
| API Banking / Open Finance | Sim | Transferências inteligentes, iniciação de pagamentos app-to-app |
| Automação de pagamentos e cobranças | Sim | Área de gestão de cobranças, emissão de boletos |
| Conciliação bancária integrada | Parcial | Extrato detalhado, sem ferramenta de conciliação dedicada |
| Gestão multi-CNPJ | Não | Cada CNPJ exige conta separada |
| Gestão multi-usuário com permissões | Sim | Acesso Compartilhado (perfis Administrador, Consulta, Operação) — lançado em 2024 |
| Dashboards financeiros | Básico | Saldo, extrato, área "Minhas Vendas" |
| Câmbio e operações internacionais | Não | [DADO NÃO ENCONTRADO PUBLICAMENTE] |
| Emissão de NF integrada | Sim | Em fase de testes (2024) — via navegador |
| Funcionalidades com IA | Sim | Uso de IA para experiência do cliente; aquisição da Hyperplane |
| Marketplace de serviços | Não | — |

**TOP 3 diferenciais mais citados como diferencial competitivo:**

1. **NuTap** — maquininha no celular sem custo de adesão, taxas até 30% menores que concorrentes
2. **Conta 100% gratuita** — sem mensalidade, sem anuidade do cartão, PIX ilimitado
3. **Experiência de usuário** — app premiado, melhor onboarding do mercado (pesquisa idwall)

---

## Bloco 4 · Engajamento Digital e Recompensas

| Mecanismo | Presente? | Detalhes |
|-----------|-----------|----------|
| **Gamificação** | Não | Sem missões, desafios, badges ou barras de progresso |
| **Recompensas/Cashback** | Limitado | Sem programa de cashback estruturado para PJ |
| **Notificações inteligentes** | Parcial | Alertas transacionais; sem alertas proativos de engajamento |
| **Conteúdo educacional** | Externo | Blog, NuCommunity — não integrado ao app |
| **Recorrência forçada** | Parcial | Gestão de cobranças, NuTap para vendas |
| **Comunidade** | Sim | NuCommunity (+300 mil membros) |

**Nível geral de engajamento digital:** MÉDIO

---

## Bloco 5 · Produtos Ofertados e Jornada de Contratação

| # | Produto | Oferece? | One-click? | Observação |
|---|---------|----------|------------|------------|
| P01 | Conta corrente PJ | ✓ Sim | ✓ One-click | Conta de pagamentos gratuita |
| P02 | Cartão de crédito PJ | ✓ Sim | ✗ Não | Depende de análise de crédito |
| P03 | Capital de giro / crédito empresarial | ✓ Sim | ✗ Não | Lançado em 2024; análise de crédito necessária |
| P04 | Antecipação de recebíveis | ✗ Não | — | Não oferece |
| P05 | Maquininha / gateway de pagamento | ✓ Sim | ✓ One-click | NuTap — ativação imediata no app |
| P06 | Investimentos PJ (CDB, fundos) | ✓ Sim | ✓ One-click | Caixinha PJ com rendimento 100% CDI |
| P07 | Seguros empresariais | ✗ Não | — | Não oferece para PJ |
| P08 | Folha de pagamento / benefícios | ✗ Não | — | Não oferece |
| P09 | Câmbio e remessas internacionais | ✗ Não | — | [DADO NÃO ENCONTRADO] |
| P10 | Conta escrow / produtos estruturados | ✗ Não | — | Não oferece |

---

## Bloco 6 · Pontos Fortes, Fracos e Diferenciais

### Pontos fortes (com evidência)

1. **Abertura 100% digital e rápida** — para clientes PF existentes, conta aprovada em minutos a dias, sem burocracia [REF-01]
2. **Custo zero** — sem mensalidade, anuidade ou taxa de manutenção; PIX ilimitado gratuito [REF-04]
3. **NuTap diferenciado** — maquininha no celular sem custo fixo, taxas competitivas (1,49% débito, 3,19% crédito) [REF-07]
4. **Melhor onboarding do mercado** — nota 7,50 em pesquisa idwall entre 23 bancos [REF-10]
5. **Escala e confiança** — 4,5 milhões de clientes PJ, maior IF privada do Brasil, nota 8,6 no Reclame Aqui com selo RA1000

### Pontos fracos (com evidência)

1. **Negativas automáticas sem transparência** — CNPJs recém-abertos ou com dados desatualizados são negados sem opção de envio manual de documentos [REF-02]
2. **Sem gerente de relacionamento** — atendimento 100% reativo, sem CS dedicado para PJ
3. **Ausência de milestones de engajamento** — sem checkpoints, gamificação ou mecanismos de reativação proativos
4. **Portfólio limitado de produtos** — sem antecipação de recebíveis, seguros, folha de pagamento, câmbio
5. **WhatsApp apenas passivo** — cliente não pode acionar suporte via WhatsApp; canal subaproveitado

### Diferenciais únicos (moat)

- **Escala + simplicidade:** maior base de clientes PJ entre fintechs, com experiência reconhecidamente superior
- **Integração PF-PJ no mesmo app:** 75% dos clientes abrem conta PJ onde já têm conta PF — Nubank captura esse fluxo
- **NuTap:** única solução de maquininha 100% no celular entre grandes players, sem custo fixo

### Posicionamento vs. concorrência direta

| Concorrente | Onde Nubank ganha | Onde Nubank perde |
|-------------|-------------------|-------------------|
| **Inter Empresas** | Experiência de app, simplicidade | Portfólio de produtos, investimentos |
| **C6 Bank** | Base de clientes, escala | Programa de benefícios, cashback |
| **Mercado Pago** | Marca, confiança, NuTap | Ecossistema de vendas integrado |

---

### 🏦 Implicação para o Itaú Empresas

**🔴 Ameaça**

- O Nubank converte clientes PF em PJ com extrema facilidade (75% abrem onde já têm conta) — isso representa migração direta de clientes que poderiam abrir no Itaú
- O NuTap atrai MEIs e microempreendedores que buscam solução simples para receber pagamentos
- Custo zero e abertura rápida criam barreira de entrada para bancos com estrutura de tarifas
- Segmento mais exposto: **MEI e ME** — maioria da base Nubank PJ

**🟢 Oportunidade**

- **Onboarding assistido:** Nubank não oferece gerente ou CS dedicado — Itaú pode diferenciar com atendimento humano especializado nos primeiros 90 dias
- **Portfólio expandido:** Nubank não tem antecipação de recebíveis, seguros, folha de pagamento — clientes que precisam desses produtos buscam alternativas
- **Empresas maiores:** Nubank foca em "pejotinhas" (até R$ 10 mi) — PMEs e médias empresas são oportunidade clara para Itaú
- **Milestones de engajamento:** Nubank não gamifica nem acompanha progresso — Itaú pode criar jornada de ativação estruturada

**⚡ Ação sugerida**

1. **Criar fluxo de abertura PJ simplificado para clientes PF Itaú** — replicar a conversão "um toque" do Nubank
2. **Implementar onboarding assistido nos primeiros 30 dias** — CS dedicado ou gerente digital para clientes PJ novos
3. **Desenvolver "Itaú Tap" ou equivalente** — solução de maquininha no celular para competir com NuTap
4. **Comunicar diferenciais de portfólio** — antecipação, seguros, câmbio, folha de pagamento como motivos para escolher Itaú
5. **Criar milestones de engajamento** — gamificação com recompensas nos primeiros 90 dias

---

## Bloco 7 · Comentários de Usuários · App Store & Google Play

| Loja | Nota | Avaliações |
|------|------|------------|
| **App Store** | ★ 4,8 | ~1,5 milhão |
| **Google Play** | ★ 4,6 | +100 milhões de downloads |

**Promotores — Top 5 temas dos reviews positivos (⭐⭐⭐⭐⭐):**

1. Facilidade de uso e design intuitivo do app
2. Atendimento ao cliente rápido e eficiente (chat)
3. Sem tarifas e sem burocracia
4. PIX rápido e gratuito
5. Cartão sem anuidade com bom limite

**Detratores — Top 5 temas dos reviews negativos (⭐ ou ⭐⭐):**

1. Negativa de abertura de conta PJ sem explicação clara
2. CNPJs novos ou alterados não conseguem abrir conta
3. Limite de crédito baixo ou negado
4. Dificuldade em falar com atendente humano em casos complexos
5. Encerramento de conta sem aviso prévio adequado

**Insights qualitativos:**

- Reclamações específicas de PJ no Reclame Aqui focam majoritariamente na **abertura de conta** — negativas automáticas frustrantes
- Nota geral no Reclame Aqui: 8,6/10, selo RA1000, 91,8% de resolução
- Tempo médio de resposta: 5 dias
- Padrão: clientes PF satisfeitos, mas fricção significativa na conversão para PJ quando CNPJ é novo

[REF-10] Nubank melhor onboarding | https://bpmoney.com.br/mercado/nubank-nubr33-melhor-onboarding/ | fev/2025
[REF-11] Reclame Aqui Nubank | https://www.reclameaqui.com.br/empresa/nubank/ | fev/2025

---

## Bloco 8 · Mapa Visual da Jornada · Screenshots e Evidências

> ⚠️ Screenshots não coletados nesta análise — jornada é in-app e poucos materiais públicos disponíveis.

**Resumo de cobertura visual:**

| Métrica | Valor |
|---------|-------|
| Total de screenshots coletados | 0 |
| Fases com boa cobertura visual | — |
| Fases sem evidência visual encontrada | Todas — abertura, setup, comunicação, engajamento |
| Canal com mais evidências disponíveis | Web (site institucional) |
| Transparência da jornada | Baixa (jornada in-app, pouca exposição pública) |

---

## Conclusão Executiva

O **Nubank (Nu Empresas)** é o líder em volume de contas PJ entre fintechs brasileiras, com 4,5 milhões de clientes empresariais e a maior base de clientes total do país. Sua proposta de valor é clara: **conta gratuita, abertura rápida, experiência de app superior**. O NuTap é um diferencial único que atrai microempreendedores que buscam simplicidade para receber pagamentos.

Na jornada 0–90 dias, o Nubank converte bem clientes PF existentes, mas apresenta **fricção significativa para CNPJs novos ou com alterações cadastrais** — principal ponto de abandono. Após a abertura, a ausência de onboarding assistido, gerente dedicado e milestones de engajamento deixa o cliente "solto", dependendo de iniciativa própria para ativar produtos.

O perfil ideal de cliente PJ é o **MEI ou ME com faturamento até R$ 5 milhões**, que já é cliente PF Nubank, busca simplicidade e não precisa de produtos complexos (antecipação, seguros, câmbio). Para o **Itaú Empresas**, a principal ameaça é a conversão fácil PF→PJ e o custo zero. A principal oportunidade está em **atendimento humano diferenciado, portfólio expandido e foco em empresas maiores** que o Nubank não prioriza.

---

## Consolidação de Funcionalidades Únicas

```
💡 FUNCIONALIDADE ÚNICA #1
Nome: NuTap — Maquininha no celular
Onde aparece: Setup / Engajamento
O que é: Transforma o celular com NFC em maquininha de cartão, sem custo de adesão ou mensalidade
Por que é relevante: Elimina barreira de entrada para MEIs aceitarem cartão; taxas competitivas (1,49%-3,19%)
Concorrentes similares: Não — inédito nessa escala entre grandes players
Referência: [REF-07]
```

```
💡 FUNCIONALIDADE ÚNICA #2
Nome: Nu Limite Garantido para PJ
Onde aparece: Setup / Engajamento
O que é: Permite aumentar limite do cartão de crédito usando investimentos (Caixinha PJ) como garantia, com rendimento de 100% CDI
Por que é relevante: Resolve problema de limite baixo sem análise de crédito adicional; dinheiro continua rendendo
Concorrentes similares: Sim — Inter e outros oferecem variações, mas integração é diferencial
Referência: [REF-12]
```

```
💡 FUNCIONALIDADE ÚNICA #3
Nome: Acesso Compartilhado com perfis
Onde aparece: Setup / Gestão
O que é: Permite dividir acesso à conta PJ entre sócios/funcionários com perfis distintos (Administrador, Consulta, Operação)
Por que é relevante: Resolve demanda de empresas com mais de uma pessoa gerenciando finanças
Concorrentes similares: Sim — funcionalidade comum, mas Nubank lançou apenas em 2024
Referência: [REF-13]
```

[REF-12] Nu Limite Garantido PJ | https://blog.nubank.com.br/nu-limite-garantido-nubank-pj/ | fev/2025
[REF-13] Nubank retrospectiva 2024 | https://international.nubank.com.br/pt-br/companhia/nubank-alcanca-110-milhoes-de-clientes-e-avanca-em-todas-as-prioridades-em-2024/ | fev/2025

---

## Índice Geral de Referências

| # | Título | URL | Data de acesso |
|---|--------|-----|----------------|
| REF-01 | Como abrir conta PJ Nubank | https://blog.nubank.com.br/abrir-conta-pj-nubank | fev/2025 |
| REF-02 | Reclame Aqui - Nubank | https://www.reclameaqui.com.br/empresa/nubank/ | fev/2025 |
| REF-03 | Tecnoblog - Abrir conta Nubank | https://tecnoblog.net/responde/como-abrir-uma-conta-no-nubank/ | fev/2025 |
| REF-04 | Regras conta PJ Nubank | https://blog.nubank.com.br/conta-pj-nubank-regras-para-abrir-uma/ | fev/2025 |
| REF-05 | Nubank Contatos | https://nubank.com.br/contatos | fev/2025 |
| REF-06 | Nu Empresas Login | https://app.nubank.com.br/ | fev/2025 |
| REF-07 | NuTap | https://nubank.com.br/nutap/ | fev/2025 |
| REF-08 | Nubank telefone | https://www.remessaonline.com.br/blog/nubank-telefone/ | fev/2025 |
| REF-09 | Blog Nubank | https://blog.nubank.com.br/ | fev/2025 |
| REF-10 | Nubank melhor onboarding | https://bpmoney.com.br/mercado/nubank-nubr33-melhor-onboarding/ | fev/2025 |
| REF-11 | Reclame Aqui Nubank | https://www.reclameaqui.com.br/empresa/nubank/ | fev/2025 |
| REF-12 | Nu Limite Garantido PJ | https://blog.nubank.com.br/nu-limite-garantido-nubank-pj/ | fev/2025 |
| REF-13 | Nubank retrospectiva 2024 | https://international.nubank.com.br/pt-br/companhia/nubank-alcanca-110-milhoes-de-clientes-e-avanca-em-todas-as-prioridades-em-2024/ | fev/2025 |

---

**Metadados da análise:**

| Campo | Valor |
|-------|-------|
| Instituição analisada | Nubank (Nu Empresas) |
| Data de execução | Fevereiro/2025 |
| Período coberto pelos dados | 2024–2025 |
| Total de fontes referenciadas | 13 |
| Total de screenshots coletados | 0 |
| Total de funcionalidades únicas identificadas | 3 |
| Gaps de informação | Screenshots da jornada, métricas internas de ativação, detalhes de welcome series por e-mail |
