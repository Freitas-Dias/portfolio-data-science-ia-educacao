# Técnicas de Controle de Saída e Segurança em Prompts

## Visão Geral
As técnicas de controle de saída e segurança têm como finalidade **garantir que a resposta gerada pela Inteligência Artificial seja previsível, estruturada, ética e adequada ao contexto de uso**.

Em ambientes acadêmicos, educacionais e em saúde, essas técnicas são essenciais para:
- padronizar formatos de resposta,
- reduzir ambiguidades,
- prevenir conteúdos inadequados ou antiéticos,
- assegurar conformidade com normas científicas e legais (ex.: LGPD).

---

## 1. Especificar Estrutura de Saída

### Definição
Consiste em indicar explicitamente **como a resposta deve ser organizada**, definindo formato, seções ou tipos de elementos textuais.

### Boas práticas
- Indicar títulos, subtítulos ou listas obrigatórias
- Definir a ordem dos elementos
- Alinhar o formato ao objetivo final (artigo, resumo, roteiro, checklist)

### Exemplo aplicado à produção científica
> “Gere um modelo de resumo expandido para um congresso de fisioterapia.  
> Estruture a resposta obrigatoriamente nos seguintes tópicos:  
> Introdução, Objetivos, Metodologia e Resultados Esperados.”

### Erro comum
Solicitar um conteúdo complexo sem definir o formato desejado, resultando em respostas desorganizadas ou inconsistentes.

---

## 2. Preparar a Saída (Output Priming)

### Definição
A técnica de preparação da saída consiste em **inserir frases, padrões ou marcadores no próprio prompt** para induzir o formato final da resposta.

Essa abordagem ajuda o modelo a “ancorar” a estrutura do texto.

### Boas práticas
- Utilizar frases de abertura ou encerramento
- Indicar expressões fixas que devem aparecer na resposta
- Manter consistência com padrões acadêmicos

### Exemplo aplicado à busca bibliográfica
> “Crie um roteiro de busca avançada para a base PEDro.  
> Finalize a resposta obrigatoriamente com a frase:  
> ‘As palavras-chave selecionadas para esta busca são
