graph TD
    A[INÍCIO] --> B{Ativação de Listas de Clientes (se necessário)};
    B --> C{Receber Mensagem no WhatsApp};
    C --> D{Identificar Cliente (Novo Lead ou Existente?)};
    D -- Novo Lead --> E{Qualificar Lead};
    D -- Cliente Existente --> Q[Verificar Histórico no CRM];

    E -- Sim (Qualificado) --> F{Oferecer Produtos/Soluções};
    E -- Não (Não Qualificado) --> G[Agradecer e Registrar Não Qualificação no CRM];
    G --> P[FIM (Lead Não Qualificado)];

    F --> H{Apresentar Benefícios e Vantagens};
    H --> I{Responder Perguntas e Objeções};
    I --> J{Interesse em Avançar?};
    J -- Sim --> K{Agendar Reunião (Opcional)};
    J -- Não --> L[Agradecer e Registrar Não Interesse no CRM];
    L --> P;

    K --> M[Registrar/Atualizar CRM (Novo Lead e Próximos Passos)];
    M --> N[CONVERSÃO POTENCIAL];

    Q --> R[Entender Contexto do Contato];
    R --> S[Dar Continuidade ao Atendimento];
    S --> T[Registrar/Atualizar CRM (Interação e Próximos Passos)];
    T --> U[OPORTUNIDADE DE VENDA ADICIONAL/SUPORTE];
    U --> V[FIM];

    N --> W{Realizar Reunião (Se Houve)};
    W --> X{Apresentar Proposta Detalhada};
    X --> Y{Negociação};
    Y --> Z{Venda Concluída?};
    Z -- Sim --> AA[Registrar Venda no CRM];
    Z -- Não --> AB[Entender Motivo Não Venda e Registrar no CRM];
    AB --> AC[FIM (OPORTUNIDADE EM ABERTO/PERDIDA)];
    AA --> AD[Agradecer e Iniciar Onboarding/Entrega];
    AD --> AE[FIM (VENDA)];

    AE --> AF[Acompanhamento Pós-Venda (Opcional)];
    AF --> AG[FIM];
    P --> AG;
    V --> AG;
    AC --> AG;

    style AG fill:#f9f,stroke:#333,stroke-width:2px
    style AE fill:#ccf,stroke:#333,stroke-width:2px
    style P fill:#fcc,stroke:#333,stroke-width:2px
    style V fill:#eee,stroke:#333,stroke-width:2px
    style AC fill:#eee,stroke:#333,stroke-width:2px
    style N fill:#efe,stroke:#333,stroke-width:2px
    style U fill:#efe,stroke:#333,stroke-width:2px
