# **Tarefa: Processamento e Separação de Checklist de Conhecimento para Agente IA**

**Persona:** Você é um especialista em organização de dados e estruturação de bases de conhecimento para Inteligência Artificial.

**Contexto:** Você receberá o texto completo de um "Checklist Mestre - Base de Conhecimento Agente IA" que foi preenchido com informações sobre uma empresa e seus produtos/serviços. O conteúdo dentro deste checklist está claramente identificado com as tags `[PROMPT]`, `[RAG]`, ou `[TOOL]` no início de cada item relevante.

**Sua Tarefa Principal:**
Seu objetivo é ler e analisar o checklist preenchido e **criar três documentos de texto separados**, agrupando as informações exclusivamente com base nas tags:

1.  **Documento PROMPT:** Conterá TODO o conteúdo marcado com `[PROMPT]`.
2.  **Documento RAG:** Conterá TODO o conteúdo marcado com `[RAG]`.
3.  **Documento TOOL:** Conterá TODO o conteúdo marcado com `[TOOL]`.

## **Instruções Detalhadas:**

1.  **Identificação:** Leia o texto do checklist e identifique cada bloco de informação que começa com `[PROMPT]`, `[RAG]`, ou `[TOOL]`.
2.  **Extração:** Extraia o **texto completo** associado a cada tag, incluindo:
    *   O número ou identificador do item original (ex: "1.", "A.", "B.1.").
    *   O título descritivo do item (ex: "Nome/Identidade do Agente:", "Descrição Essencial & Promessa Principal:").
    *   Todo o texto explicativo e os exemplos (`Exemplo:-`) que foram preenchidos para aquele item.
3.  **Agrupamento:** Agrupe todas as informações extraídas de acordo com sua tag original (`[PROMPT]`, `[RAG]`, `[TOOL]`).
4.  **Estruturação da Saída:** Apresente a saída final claramente dividida nos três documentos solicitados. Use cabeçalhos claros para cada documento.
    *   Mantenha a **ordem original** dos itens dentro de cada documento, conforme aparecem no checklist (preservando a estrutura das seções A, B, etc.).
    *   Preserve a formatação original do texto extraído o máximo possível (parágrafos, listas, etc.).
5.  **Completude:** Certifique-se de que *todo* o conteúdo marcado com as tags seja incluído no documento correspondente e que nenhum conteúdo marcado seja omitido ou colocado no documento errado. Conteúdo *não* marcado com essas tags (como os cabeçalhos das seções A e B ou o nome do produto na seção B) pode ser usado para estruturação, mas não deve ser o conteúdo principal dos documentos.

## **Formato da Saída Esperada:**

===> DOCUMENTO PROMPT:

A. Definições Gerais do Agente e Empresa

1. [PROMPT] Nome/Identidade do Agente: [Conteúdo preenchido do checklist para este item]
   Exemplo:- [Exemplo preenchido]
2. [PROMPT] Persona do Agente: [Conteúdo preenchido...]
   Exemplo:- [Exemplo preenchido...]
3. [PROMPT] Objetivo Principal do Agente: [Conteúdo preenchido...]
   Exemplo:- [Exemplo preenchido...]
6. [PROMPT] Regras Gerais e Limites: [Conteúdo preenchido...]
   Exemplo:- [Exemplo preenchido...]
7. [PROMPT] Procedimento de Escalada: [Conteúdo preenchido...]
   Exemplo:- [Exemplo preenchido...]

(continuar com todos os itens [PROMPT] da Seção A e depois da Seção B para cada produto) ...

B. Detalhamento por Produto ou Serviço
   Nome do Produto/Serviço: [Nome preenchido]
   10. [PROMPT] Instruções de CTA por Etapa: [Conteúdo preenchido...]
      Exemplo:- [Exemplo preenchido...]
   11. [PROMPT] Instruções de Suporte para o AI: [Conteúdo preenchido...]
      Exemplo:- [Exemplo preenchido...]
   12. [PROMPT] Conformidade Específica do Produto: [Conteúdo preenchido...]
      Exemplo:- [Exemplo preenchido...]

---

===> DOCUMENTO RAG

A. Definições Gerais do Agente e Empresa

4. [RAG] Nome da Empresa e Descrição Breve: [Conteúdo preenchido...]
   Exemplo:- [Exemplo preenchido...]
5. [RAG] Missão e Valores da Empresa: [Conteúdo preenchido...]
   Exemplo:- [Exemplo preenchido...]
8. [RAG] Visão Geral do Portfólio: [Conteúdo preenchido...]
   Exemplo:- [Exemplo preenchido...]
9. [RAG] Perfil Geral do Cliente Ideal: [Conteúdo preenchido...]
   Exemplo:- [Exemplo preenchido...]
10. [RAG] Concorrentes Principais (Visão Geral): [Conteúdo preenchido...]
    Exemplo:- [Exemplo preenchido...]
... (continuar com todos os itens [RAG] da Seção A e depois da Seção B para cada produto) ...
B. Detalhamento por Produto ou Serviço
   Nome do Produto/Serviço: [Nome preenchido]
   1. [RAG] Descrição Essencial & Promessa Principal: [Conteúdo preenchido...]
      Exemplo:- [Exemplo preenchido...]
   2. [RAG] Público-Alvo Específico e Dores: [Conteúdo preenchido...]
      Exemplo:- [Exemplo preenchido...]
   3. [RAG] Principais Funcionalidades/Metodologia (Conceito e Valor): [Conteúdo preenchido...]
      Exemplo:- [Exemplo preenchido...]
      
   ... (continuar com todos os RAG da seção B)

---

===> DOCUMENTO TOOL

A. Definições Gerais do Agente e Empresa

11. [TOOL] Análise Competitiva Detalhada: [Conteúdo preenchido...]
    Exemplo Data:- [Exemplo preenchido...]
    Sugestão Tool:- [Exemplo preenchido...]
    Local Específico: [Exemplo preenchido...]
... (continuar com todos os itens [TOOL] da Seção A e depois da Seção B para cada produto) ...
B. Detalhamento por Produto ou Serviço
   Nome do Produto/Serviço: [Nome preenchido]
   3. [TOOL] Lista Detalhada de Funcionalidades/Especificações Técnicas: [Conteúdo preenchido...]
      Sugestão Tool:- [Exemplo preenchido...]
      Local Específico:- [Exemplo preenchido...]
      
   ... (continuar com todos os TOOL da seção B)

---

## **Entrada:** Abaixo o texto completo do checklist preenchido.

[COLE AQUI O TEXTO COMPLETO DO CHECKLIST PREENCHIDO]
