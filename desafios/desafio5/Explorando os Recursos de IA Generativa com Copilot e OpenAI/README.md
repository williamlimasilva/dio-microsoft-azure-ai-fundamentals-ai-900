# Explorando os Recursos de IA Generativa com Copilot e OpenAI

## Introdução

Este documento apresenta um resumo dos conceitos abordados no módulo sobre IA Generativa, explorando seus fundamentos, aplicações e boas práticas para utilização responsável.

## Conceitos Fundamentais

### O que é IA Generativa?

A IA Generativa refere-se a sistemas que utilizam modelos de aprendizado de máquina para criar conteúdo original, como texto, imagens e código. Esses sistemas interpretam entradas em linguagem natural e geram respostas adequadas a partir de grandes modelos de linguagem (LLMs).

### Modelos de Linguagem Grandes (LLMs)

Os LLMs são modelos especializados em processamento de linguagem natural (PLN), usados para tarefas como:

- Determinação de sentimento e classificação de texto.
- Resumo de textos.
- Comparar similaridade semântica entre textos.
- Geração de novo texto baseado em aprendizado.

Os modelos transformadores incluem:

- **Codificador**: Cria representações semânticas das palavras.
- **Decodificador**: Gera sequências de linguagem com base nessas representações.

### Tokenização e Atenção

- O texto é **tokenizado**, convertendo palavras em códigos numéricos.
- **Inserções** capturam relações entre tokens.
- O método de **atenção** define pesos para tokens mais relevantes para prever palavras futuras.

## OpenAI no Azure

O **Azure OpenAI Service** é uma plataforma da Microsoft para hospedar e personalizar modelos de IA generativa. Ele oferece:

- Modelos prontos como GPT-4, GPT-3.5, Embeddings e DALL-E.
- Playgrounds para testes sem necessidade de código.
- Segurança corporativa com RBAC e redes privadas.
- Ferramentas para mitigar usos indevidos.

### Funcionalidades

- **Geração de Texto**: Criar respostas textuais em diversos contextos.
- **Geração de Código**: Traduzir descrições textuais para código e gerar testes automatizados.
- **Geração de Imagens**: Uso do DALL-E para criação, edição e variação de imagens.

## Copilotos

Os copilotos são assistentes de IA que interagem com usuários para auxiliar em tarefas comuns. Exemplos:

- **GitHub Copilot**: Sugere códigos para desenvolvedores.
- **Bing Copilot**: Fornece respostas aprimoradas em buscas.
- **Edge Copilot**: Assistência para navegação e produtividade.

## Engenharia de Prompt

A qualidade das respostas geradas pela IA depende da formulação dos prompts. Boas práticas incluem:

- Uso de linguagem clara e direta.
- Mensagens do sistema para definir o comportamento da IA.
- Inclusão de exemplos para contextualizar respostas.

## IA Generativa Responsável

A Microsoft propõe um ciclo de vida para soluções de IA responsáveis:

1. **Identificar** riscos e impactos.
2. **Medir** a eficiência do modelo.
3. **Mitigar** usos indevidos.
4. **Operar** de forma transparente e ética.

## Insights e Possibilidades

Durante a exploração deste módulo, alguns insights se destacaram:

- O uso de **LLMs transforma aplicações empresariais**, desde chatbots até análises de dados.
- A **engenharia de prompt** é uma habilidade essencial para obter respostas de qualidade.
- É fundamental adotar **práticas responsáveis**, mitigando riscos de alucinação de IA.

## Links de Referência

- [Laboratório: IA Generativa](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html)
- [Explorando o Azure AI Studio](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/01-Explore-ai-studio.html)
- [Filtros de Conteúdo](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/06-Explore-content-filters.html)
- [Inteligência de Documentos e Mineração de Conhecimento](https://learn.microsoft.com/en-us/training/paths/document-intelligence-knowledge-mining/)
