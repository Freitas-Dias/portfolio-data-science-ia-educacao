# Componentes de Conteúdo e Suporte de um Prompt

## Visão Geral
Os componentes de conteúdo e suporte dizem respeito **à informação que será efetivamente processada pela Inteligência Artificial** e aos **insumos adicionais** que orientam, qualificam e restringem essa análise.

Em contextos acadêmicos e em saúde, esses componentes são cruciais para:
- reduzir ambiguidades,
- evitar alucinações,
- aumentar precisão conceitual,
- garantir rastreabilidade e responsabilidade científica.

---

## 1. Conteúdo Principal

### Definição
O conteúdo principal corresponde ao **material central** que a IA deverá analisar, resumir, transformar ou reinterpretar.

Esse conteúdo pode assumir diferentes formas:
- texto (artigo, abstract, relatório),
- dados descritivos,
- perguntas de pesquisa,
- trechos de documentos,
- descrições de cenários.

Quanto mais claro, delimitado e relevante for o conteúdo principal, maior a qualidade da saída gerada.

### Boas práticas
- Inserir apenas o conteúdo necessário para a tarefa
- Evitar misturar múltiplas demandas em um mesmo bloco
- Garantir que o texto esteja completo e compreensível

### Exemplo aplicado à pesquisa em saúde
> “Resuma os principais achados do seguinte resumo de artigo científico:  
>  
> *[Inserir aqui o abstract de um artigo sobre fisioterapia respiratória em pacientes pós-COVID]*”

Nesse caso, o abstract constitui o **conteúdo principal**, e a IA deve restringir sua análise estritamente a ele.

### Erro comum
Solicitar análise sem fornecer o conteúdo correspondente, esperando que a IA “deduza” ou “busque” informações externas.

---

## 2. Conteúdo de Suporte

### Definição
O conteúdo de suporte consiste em **informações adicionais** que enriquecem o processamento do conteúdo principal, sem substituí-lo.

Ele funciona como um **marco de referência**, orientando o modelo quanto a:
- diretrizes,
- normas,
- frameworks teóricos,
- boas práticas da área.

### Tipos comuns de conteúdo de suporte
- Diretrizes profissionais
- Normas técnicas (ex.: ABNT, APA)
- Protocolos clínicos
- Modelos conceituais
- Princípios metodológicos

### Exemplo aplicado à educação em saúde
> “Crie um roteiro para uma apresentação sobre os benefícios do Pilates para a saúde da coluna vertebral.  
> Utilize como base os princípios do método Pilates e as diretrizes da American Physical Therapy Association (APTA) para exercícios terapêuticos.”

Nesse exemplo:
- o **roteiro** é a tarefa,
- os **princípios do método Pilates** e as **diretrizes da APTA** são conteúdos de suporte.

### Erro comum
Fornecer conteúdo de suporte genérico ou não confiável, comprometendo a validade da resposta.

---

## 3. Relação entre Conteúdo Principal e Conteúdo de Suporte

| Elemento | Função |
|--------|-------|
| Conteúdo Principal | O que será diretamente processado |
| Conteúdo de Suporte | O que orienta como processar |

Um prompt bem estruturado deixa explícito:
- **o que** deve ser analisado,
- **com base em que refer**
