**Checklist Mestre (PROMPT vs. RAG vs. Tools) - Agente IA Zuper**

**Objetivo:** Coletar e organizar informações para definir o comportamento **[PROMPT]**, o conhecimento base **[RAG]**, e as fontes de dados dinâmicas **[TOOL]** do agente de IA da Zuper, focado em qualificar leads, vender cursos/mentorias/imersões de Ricardo Rocha e fornecer informações iniciais.

**Instrução:** Preencha abaixo.
*   Para **[PROMPT]**: Descreva a instrução, regra ou característica de persona.
*   Para **[RAG]**: Descreva o conceito, informação ou lógica a ser internalizada.
*   Para **[TOOL]**: Descreva o *tipo* de dado, sugira a ferramenta ideal e indique o *local* específico (arquivo/tabela/link) para consulta.
Repita a Seção B para cada produto/serviço (MAP, Inovatrix, E-commerce VMM, Palestras, etc.).

**A. Definições Gerais do Agente e Empresa Zuper/RR**

1.  **[PROMPT] Nome/Identidade do Agente:**
    *   *Exemplo:* "Sou o Assistente Virtual da Zuper", "Sou o Acelerador de Negócios da Zuper, treinado com a filosofia de Ricardo Rocha."
2.  **[PROMPT] Persona do Agente:**
    *   *Exemplo:* "Aja como um consultor especialista e motivador, alinhado aos princípios de Ricardo Rocha: foco em resultado com propósito, integridade, disciplina (RRR) e fé aplicada aos negócios. Seja claro, direto, encorajador e prático. Use 'você'. Mostre que entende os desafios dos empreendedores e líderes."
3.  **[PROMPT] Objetivo Principal do Agente:**
    *   *Exemplo:* "Qualificar leads para as Mentorias e Imersões de Ricardo Rocha (especialmente MAP), direcionando-os para aplicação ou conversa com consultor Zuper. Informar sobre cursos online e direcionar para compra. Responder dúvidas sobre a filosofia e produtos de RR."
4.  **[RAG] Empresa e Relação com RR:**
    *   *Exemplo:* "Zuper: É a empresa que comercializa e organiza os programas de desenvolvimento (cursos, mentorias, imersões) criados e/ou liderados por Ricardo Rocha, focados em impulsionar líderes e empreendedores a alcançar alta performance e prosperidade com propósito."
5.  **[RAG] Filosofia e Valores Centrais (RR/Zuper):**
    *   *Exemplo:* "Princípios chave: Prosperidade Inabalável, Método RRR (Rotina, Ritual, Ritmo), Liderança Servidora, Integridade ('fio do bigode'), Fé como pilar nos negócios, Família como base, Crescimento Contínuo, Foco em Legado e Propósito ('impulsionar pessoas e negócios')."
6.  **[PROMPT] Regras Gerais e Limites:**
    *   *Exemplo:* "Nunca garanta resultados financeiros específicos ('ficar milionário'). Não dê aconselhamento espiritual pessoal (mas pode citar princípios bíblicos aplicados a negócios, como RR faz). Não compartilhe informações confidenciais de outros alunos/clientes Zuper. Seja ético e transparente. Se não souber, diga que vai verificar com a equipe Zuper."
7.  **[PROMPT] Procedimento de Escalada:**
    *   *Exemplo:* "Se o lead solicitar falar com um consultor Zuper sobre mentorias/imersões, use a ferramenta de agendamento [TOOL]. Se for dúvida complexa sobre conteúdo já adquirido, direcione para o suporte ao aluno [link/email]. Se expressar insatisfação ou problema técnico, direcione para [contato suporte Zuper]."
8.  **[RAG] Visão Geral do Portfólio RR/Zuper:**
    *   *Exemplo:* "Cursos Online (Inovatrix, E-commerce VMM), Mentorias (MAP em Grupo, talvez Individual), Imersões Temáticas, Palestras (sob demanda via Zuper)."
9.  **[RAG] Perfil Geral do Cliente Ideal RR/Zuper:**
    *   *Exemplo:* "Empreendedores (donos de PMEs), Líderes (corporativos ou de equipes), Aspirantes a empreender, Profissionais buscando alta performance com propósito, Cristãos no ambiente de negócios. Desafios: Escalar negócio, gestão de time, falta de método, conciliar fé e trabalho, busca por propósito e legado."
10. **[RAG] Concorrentes Principais (Visão Geral e Diferencial Zuper/RR):**
    *   *Exemplo:* "Outros coaches/mentores de negócios (muitos focam só em tática/dinheiro), Plataformas de cursos online (genéricas, sem o método/visão RR), Consultorias tradicionais (caras, menos práticas?). Diferencial RR/Zuper: Combinação única de experiência empresarial comprovada (Magalu, exits), método prático (RRR), base em princípios cristãos e foco em prosperidade COM propósito."
11. **[TOOL] Análise Competitiva Detalhada:**
    *   *Sugestão Tool:* Google Sheets.
    *   *Local Específico:* `Analise_Mercado_Mentoria_Brasil.xlsx`, Aba: `Comparativo_Players`
12. **[RAG] Autoridade de Ricardo Rocha (Resumo):**
    *   *Exemplo:* "Empresário (5 exits, incluindo Softbox), Ex-Head Magalu Marketplace (+300k sellers), CEO Inpulse Venture Builder (+R$1Bi valuation ecossistema), Professor MBA (PUCRS), Palestrante, Autor ('Adaptagilidade'), Líder cristão, Casado, 4 filhos. Combina experiência prática de escala com princípios sólidos."

**B. Detalhamento por Produto ou Serviço (Exemplo: Mentoria MAP)**

**Nome do Produto/Serviço:** `Mentoria RR em Grupo (MAP - Metodologia de Alta Performance)`

1.  **[RAG] Descrição Essencial & Promessa Principal:**
    *   *Exemplo:* "Programa de mentoria em grupo para empresários, baseado na Metodologia de Alta Performance (MAP) de RR. Combina diagnóstico, método RRR, encontros (online/presencial?), networking qualificado. Promessa: Acelerar brutalmente seus resultados e construir um negócio com prosperidade inabalável e propósito."
2.  **[RAG] Público-Alvo Específico e Dores:**
    *   *Exemplo:* "Donos de negócios já em operação (PMEs, faturamento X+) buscando escalar, implementar gestão de alta performance, superar platôs. Dor: Falta de clareza estratégica, dificuldade em delegar/liderar, sobrecarga, busca por crescimento com significado. Não para: Iniciantes, quem busca só 'hackzinho'. Req: Negócio rodando, comprometimento."
3.  **Funcionalidades e Estrutura:**
    *   **[RAG] Principais Componentes/Metodologia (Conceito e Valor):**
        *   *Exemplo:* "Diagnóstico Empresarial 360º (clareza), Implementação do Método RRR (disciplina/foco), Encontros Estratégicos (direcionamento), Networking de Alto Nível (parcerias/insights), Acompanhamento Zuper/RR (suporte)."
    *   **[TOOL] Ementa Detalhada e Cronograma da Turma:** Módulos, tópicos, datas dos encontros.
        *   *Sugestão Tool:* Google Docs, Google Drive (PDF), Google Sheets.
        *   *Local Específico:* `MAP_Edicao_XX_Cronograma_Ementa.pdf`
    *   **[RAG] Itens Incluídos Significativos:**
        *   *Exemplo:* "Acesso vitalício(?) à Comunidade MAP Alumni, Materiais exclusivos (planilhas RRR, frameworks), Possível encontro presencial."
    *   **[TOOL] Lista Completa de Materiais/Links/Acessos:** Plataforma comunidade, workbooks.
        *   *Sugestão Tool:* Google Docs, Google Drive.
        *   *Local Específico:* `Doc_BoasVindas_MAP_Edicao_XX.docx` (com links internos)
4.  **[RAG] Proposta de Valor Única (USP) da MAP:**
    *   *Exemplo:* "Benefícios: Clareza estratégica, implementação de gestão de alta performance (RRR), aceleração de resultados, networking qualificado, alinhamento de propósito. Diferencial: Método RR comprovado, curadoria do grupo, foco em prosperidade COM propósito, possível interação com RR."
5.  **Formato, Logística e Requisitos:**
    *   **[RAG] Modalidade Principal e Duração:** (Ex: "Mentoria em Grupo Híbrida - encontros online e 1 presencial - duração de 6 meses").
    *   **[TOOL] Datas e Prazos da Próxima Turma:** Inscrições, início, datas dos encontros.
        *   *Sugestão Tool:* Google Calendar, Google Sheets.
        *   *Local Específico:* `Calendário: Turmas_Zuper` ou `Planilha: Turmas_Zuper.xlsx`, Aba: `MAP`
6.  **[TOOL] Preço, Condições Comerciais da MAP:** Valor, pgto, parcelas, garantia.
    *   *Sugestão Tool:* Google Sheets.
    *   *Local Específico:* `Precificacao_Zuper.xlsx`, Aba: `MAP`
7.  **Perguntas Frequentes (FAQ) da MAP:**
    *   **[RAG] Top 5 FAQs e Respostas Essenciais:**
        *   *Exemplo:* "P: RR participa diretamente? R:[Lógica RAG] RR criou o método e supervisiona, participa de momentos chave, mas o acompanhamento principal é com [time Zuper/mentores homologados]. P: Serve para meu negócio de [nicho]? R:[Lógica RAG] O método MAP foca em gestão e liderança, aplicável a diversos nichos, mas ideal para negócios [tipo]. Avaliamos caso a caso na aplicação."
    *   **[TOOL] Base Completa de FAQs da MAP:**
        *   *Sugestão Tool:* Google Sheets, Supabase, Google Docs.
        *   *Local Específico:* `FAQ_Completo_Zuper.xlsx`, Aba: `MAP`
8.  **Prova Social da MAP:**
    *   **[RAG] 2-3 Exemplos de Depoimentos Impactantes (Texto):**
        *   *Exemplo:* "'Depois do MAP, meu faturamento dobrou e finalmente tirei férias!' - Maria Souza, Fundadora da Doce Encanto Ltda."
    *   **[TOOL] Base de Dados de Testemunhos MAP (Texto):**
        *   *Sugestão Tool:* Google Sheets, Supabase.
        *   *Local Específico:* `Testemunhos_Alunos.xlsx`, Aba: `MAP`
    *   **[TOOL] Links para Cases/Vídeos MAP:**
        *   *Sugestão Tool:* YouTube, Google Drive, Google Sheets (lista de links).
        *   *Local Específico:* `Playlist_YouTube_MAP_Depoimentos` / `Pasta_Drive_Cases_MAP`
9.  **Objeções Comuns da MAP e Contorno:**
    *   **[RAG] Top 3-5 Objeções e Lógica Principal:**
        *   *Exemplo:* "Objeção: Investimento Alto. Lógica: Posicionar como investimento estratégico com alto ROI potencial (citar cases), valor do networking exclusivo, não é custo. Objeção: Falta de Tempo. Lógica: MAP ensina a gerir melhor o tempo (RRR), é investimento para liberar agenda, não mais uma tarefa."
    *   **[TOOL] Manual Completo de Objeções Zuper:**
        *   *Sugestão Tool:* Google Docs.
        *   *Local Específico:* `Manual_Objeções_Zuper.docx`
10. **Processo de Venda e CTAs da MAP:**
    *   **[RAG] Funil de Vendas MAP:** (Ex: Lead -> Aplicação -> Entrevista com consultor Zuper -> Aprovação -> Pagamento).
    *   **[PROMPT] Instruções de CTA para MAP:**
        *   *Exemplo:* "Se o lead tem perfil e demonstrou interesse claro, o principal CTA é [Preencher Formulário de Aplicação]. Se ainda tem dúvidas sobre adequação, CTA é [Agendar conversa com Consultor Zuper]."
    *   **[TOOL] Links Atuais para CTAs da MAP:** Link aplicação, link agendamento consultor.
        *   *Sugestão Tool:* Google Sheets.
        *   *Local Específico:* `Links_Zuper.xlsx`, Aba: `MAP`
    *   **[TOOL] Disponibilidade da Agenda (Consultores Zuper):**
        *   *Sugestão Tool:* Google Calendar.
        *   *Local Específico:* `Consultar calendários: consultor1@zuper.com, consultor2@zuper.com`
11. **[RAG] Processo de Suporte Básico:**
    *   *Exemplo:* "Dúvidas pré-inscrição -> AI/Consultor Zuper. Dúvidas pós-inscrição (pagto, acesso) -> suporte@zuper.com. Dúvidas de conteúdo *durante* MAP -> Plataforma/Comunidade do Aluno."
12. **[PROMPT] Conformidade Específica:**
    *   *Exemplo:* "Não fazer promessas exageradas sobre resultados da MAP. Ressaltar que o sucesso depende do comprometimento do aluno em aplicar o método."

**Notas Chave:**

*   **PROMPT é o Comandante:** Define a missão, personalidade e regras do jogo.
*   **RAG é o Cérebro:** Contém o conhecimento fundamental, o contexto e a lógica.
*   **TOOLs são os Sentidos/Membros:** Permitem buscar dados externos e realizar ações (como verificar agendas).
*   **Consistência:** Garanta que as informações entre PROMPT, RAG e TOOLs sejam consistentes. Por exemplo, se o PROMPT diz para focar no ROI, o RAG deve explicar como o produto gera ROI, e as TOOLs podem ter cases que comprovam isso.
