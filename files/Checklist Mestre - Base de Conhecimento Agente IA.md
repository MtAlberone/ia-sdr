**Checklist Mestre (PROMPT vs. RAG vs. Tools) - Base de Conhecimento Agente IA**

**Objetivo:** Coletar e organizar informações para definir o comportamento **[PROMPT]**, o conhecimento base **[RAG]**, e as fontes de dados dinâmicas **[TOOL]** de um agente de IA para vendas, pré-vendas ou suporte.

**Instrução:** Preencha abaixo.
*   Para **[PROMPT]**: Descreva a instrução, regra ou característica de persona.
*   Para **[RAG]**: Descreva o conceito, informação ou lógica a ser internalizada.
*   Para **[TOOL]**: Descreva o *tipo* de dado, sugira a ferramenta e indique o *local* específico (arquivo/tabela/link) para consulta.
Repita a Seção C para cada produto/serviço.

**A. Definições Gerais do Agente e Empresa**

1.  **[PROMPT] Nome/Identidade do Agente:** Como ele se apresenta?
    *   *Exemplo:* "Sou o Assistente Virtual da Acme Corp", "Sou o Max, especialista de produto da Acme".
2.  **[PROMPT] Persona do Agente:** Tom de voz, personalidade.
    *   *Exemplo:* "Aja como um consultor especialista: prestativo, confiante, claro, objetivo. Use linguagem acessível, evitando excesso de jargões. Seja proativo em ajudar."
3.  **[PROMPT] Objetivo Principal do Agente:** Qual a meta primária?
    *   *Exemplo:* "Seu objetivo principal é qualificar leads interessados no Acme Route Optimizer Pro e agendar uma demonstração com um especialista de vendas." *OU* "Seu objetivo é responder dúvidas de suporte nível 1 sobre o Produto X e escalar problemas complexos."
4.  **[RAG] Nome da Empresa e Descrição Breve:** Contexto básico.
    *   *Exemplo:* "Acme Corp: Ajuda PMEs a otimizar logística com IA."
5.  **[RAG] Missão e Valores da Empresa:** Para alinhar a comunicação do agente.
    *   *Exemplo:* "Missão: Democratizar eficiência. Valores: Inovação, Foco no Cliente..."
6.  **[PROMPT] Regras Gerais e Limites:** O que o agente NUNCA deve fazer?
    *   *Exemplo:* "Nunca prometa resultados financeiros específicos. Não dê opiniões pessoais. Não compartilhe dados internos confidenciais (roadmap, dados de outros clientes). Se não souber a resposta com certeza, diga que vai verificar ou direcione para um humano. Cumpra as regras da LGPD."
7.  **[PROMPT] Procedimento de Escalada:** Quando e como passar para um humano?
    *   *Exemplo:* "Se o cliente pedir explicitamente para falar com um humano, forneça o link de agendamento [link]. Se o cliente expressar frustração extrema, peça desculpas e ofereça conectar com um gerente [link/contato]. Se a dúvida for muito técnica e não estiver no [RAG] ou [TOOL], ofereça escalar para o suporte especializado [link/contato]."
8.  **[RAG] Visão Geral do Portfólio:** Categorias de produtos/serviços.
    *   *Exemplo:* "Software (Otimização de Rotas), Consultoria, Workshops."
9.  **[RAG] Perfil Geral do Cliente Ideal:** Quem a empresa ajuda.
    *   *Exemplo:* "PMEs de e-commerce/entregas (10-50 veículos)..."
10. **[RAG] Concorrentes Principais (Visão Geral):** Nomes e diferencial chave da empresa.
    *   *Exemplo:* "LogiFast (caro), RouteMax (grandes), Planilha (ineficiente). Nosso forte: IA adaptativa e Custo x Benefício para PMEs."
11. **[TOOL] Análise Competitiva Detalhada:** Comparativo funcional, preços.
    *   *Exemplo Data:* Tabela com features, preços Acme vs LogiFast vs RouteMax.
    *   *Sugestão Tool:* Google Sheets.
    *   *Local Específico:* `Analise_Concorrentes_Q3_2024.xlsx`, Aba: `Comparativo`

**B. Detalhamento por Produto ou Serviço**

**(Preencha esta seção completa para CADA produto/serviço)**

**Nome do Produto/Serviço:** `Ex: Acme Route Optimizer Pro`

1.  **[RAG] Descrição Essencial & Promessa Principal:** O que é, problema resolvido, resultado chave.
    *   *Exemplo:* "SaaS com IA para otimizar rotas. Resolve altos custos/atrasos. Promessa: Economia até 30% combustível, +25% pontualidade."
2.  **[RAG] Público-Alvo Específico e Dores:** Persona detalhada, necessidades, gatilhos. Anti-persona. Pré-requisitos chave.
    *   *Exemplo:* "Gestor Logística PME e-commerce (10-50 veículos). Dor: Ineficiência manual, reclamações. Gatilho: Alta combustível. Não para: 1 veículo. Req: Endereços digitais."
3.  **Funcionalidades e Estrutura:**
    *   **[RAG] Principais Funcionalidades/Metodologia (Conceito e Valor):** Os 3-5 recursos chave e *por que* importam.
        *   *Exemplo:* "1. Otimização IA (gera economia), 2. Monitoramento Real-Time (visibilidade), 3. App Motorista (execução fácil), 4. Relatórios (prova valor)."
    *   **[TOOL] Lista Detalhada de Funcionalidades/Especificações Técnicas:** Todas as features, limites, integrações.
        *   *Sugestão Tool:* Google Sheets, Google Docs, Supabase.
        *   *Local Específico:* `Features_AcmeRoutePro.xlsx`, Aba: `Detalhes_Tecnicos`
    *   **[RAG] Itens Incluídos Significativos:** O que agrega valor extra percebido.
        *   *Exemplo:* "Suporte chat, Comunidade usuários, Onboarding inicial."
    *   **[TOOL] Lista Completa de Itens Incluídos/Manuais/Links:** Documentação, acesso comunidade, etc.
        *   *Sugestão Tool:* Google Docs, Google Drive (PDF).
        *   *Local Específico:* `Manual_BemVindo_AcmeRoutePro.docx`
4.  **[RAG] Proposta de Valor Única (USP):** Benefícios chave (tangíveis/intangíveis), diferenciais vs concorrência/alternativas.
    *   *Exemplo:* "Benefícios: Redução custos, +Pontualidade, Melhor alocação, -Stress gestor. Diferencial: IA adaptativa, UI para PMEs, Suporte incluso."
5.  **Formato, Logística e Requisitos:**
    *   **[RAG] Modalidade e Acesso Padrão:** (Ex: "SaaS online, assinatura mensal/anual").
    *   **[TOOL] Requisitos Técnicos Detalhados:** Navegadores, SO, etc.
        *   *Sugestão Tool:* Google Docs, Google Drive (PDF).
        *   *Local Específico:* `Requisitos_Tecnicos_AcmeRoutePro.pdf`
    *   **[TOOL] Datas/Prazos (Eventos, Lançamentos):** Calendário.
        *   *Sugestão Tool:* Google Calendar, Google Sheets.
        *   *Local Específico:* `Calendário: Marketing_Acme`
6.  **[TOOL] Preços, Planos e Condições Comerciais:** Valores, pgto, parcelas, garantia, descontos, políticas.
    *   *Sugestão Tool:* Google Sheets, Supabase.
    *   *Local Específico:* `Precificacao_AcmeCorp.xlsx`, Aba: `AcmeRoutePro`
7.  **Perguntas Frequentes (FAQ):**
    *   **[RAG] Top 5 FAQs e Respostas Essenciais:** Dúvidas críticas e respostas padrão.
        *   *Exemplo:* "P: Integra com ERP? R:[Lógica RAG] Temos API e algumas nativas, consulte a lista [ver TOOL]."
    *   **[TOOL] Base Completa de FAQs (>20):** Lista extensiva Q&A.
        *   *Sugestão Tool:* Google Sheets, Supabase, Google Docs.
        *   *Local Específico:* `FAQ_Completo_Produtos.xlsx`, Aba: `AcmeRoutePro`
8.  **Prova Social (Testemunhos, Cases, Avaliações):**
    *   **[RAG] 2-3 Exemplos de Depoimentos Impactantes (Texto):** Citação curta com resultado chave para uso rápido.
        *   *Exemplo:* "'Reduzimos custo combustível em 22%!' - João Silva, Entrega Rápida Ltda."
    *   **[TOOL] Base de Dados de Testemunhos (Texto):** Lista maior.
        *   *Sugestão Tool:* Google Sheets, Supabase.
        *   *Local Específico:* `Testemunhos_Clientes.xlsx`, Aba: `AcmeRoutePro`
    *   **[TOOL] Links para Cases de Sucesso Detalhados:** PDFs ou páginas.
        *   *Sugestão Tool:* Google Drive (PDFs), Google Sheets (lista de links).
        *   *Local Específico:* `Pasta Drive: Cases_Sucesso`
    *   **[TOOL] Links para Vídeos de Testemunhos:**
        *   *Sugestão Tool:* YouTube, Google Drive.
        *   *Local Específico:* `Playlist YouTube ID: XYZ123`
9.  **Objeções Comuns e Estratégias de Contorno:**
    *   **[RAG] Top 3-5 Objeções e Lógica Principal da Resposta:** Entendimento da estratégia.
        *   *Exemplo:* "Objeção: Preço. Lógica: Focar em ROI, custo da ineficiência, valor do plano anual."
    *   **[TOOL] Manual Completo de Objeções:** Scripts, argumentos detalhados.
        *   *Sugestão Tool:* Google Docs, Google Drive (PDF).
        *   *Local Específico:* `Manual_Objeções_Vendas.docx`
10. **Processo de Venda e CTAs:**
    *   **[RAG] Funil de Vendas Padrão:** Entendimento da jornada do cliente.
    *   **[PROMPT] Instruções de CTA por Etapa:** Regras para o AI sobre qual CTA oferecer.
        *   *Exemplo:* "Se o lead parece frio (só pediu info básica), ofereça o [Webinar X]. Se demonstrou interesse claro ou mencionou dor específica, ofereça a [Demo Personalizada]. Se perguntar como comprar, direcione para a [Página de Vendas]."
    *   **[TOOL] Links Atuais para CTAs:** URLs para páginas, agendamento, trial.
        *   *Sugestão Tool:* Google Sheets, Supabase.
        *   *Local Específico:* `Links_Marketing.xlsx`, Aba: `CTAs`
    *   **[TOOL] Disponibilidade da Agenda (Vendas/Consultores):** Para agendamento.
        *   *Sugestão Tool:* Google Calendar.
        *   *Local Específico:* `Consultar calendários: vendas@acme.com, demo@acme.com`
11. **Processo de Suporte (Se Aplicável):**
    *   **[RAG] Fluxo Básico de Suporte:** Entendimento de como funciona.
    *   **[PROMPT] Instruções de Suporte para o AI:** O que tentar resolver, quando/como escalar.
        *   *Exemplo:* "Tente responder FAQs da base [RAG/TOOL]. Se for erro técnico não documentado, peça para abrir ticket em [link]. Se for financeiro, direcione para [email]."
12. **[PROMPT] Conformidade Específica do Produto:** Regras adicionais.
    *   *Exemplo:* "Ao discutir o App do Motorista, mencione que respeita a privacidade e não rastreia fora do horário de trabalho."

---

**Notas Chave:**

*   **PROMPT é o Comandante:** Define a missão, personalidade e regras do jogo.
*   **RAG é o Cérebro:** Contém o conhecimento fundamental, o contexto e a lógica.
*   **TOOLs são os Sentidos/Membros:** Permitem buscar dados externos e realizar ações (como verificar agendas).
*   **Consistência:** Garanta que as informações entre PROMPT, RAG e TOOLs sejam consistentes. Por exemplo, se o PROMPT diz para focar no ROI, o RAG deve explicar como o produto gera ROI, e as TOOLs podem ter cases que comprovam isso.
