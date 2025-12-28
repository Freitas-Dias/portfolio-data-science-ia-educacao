# Prompt — Aprendizagem de Idiomas com Música

```txt
#### **1. Elementos Essenciais do Prompt**

*   **Instrução inicial clara:** Você já possui uma instrução clara ("Aja como um especialista...") e um objetivo bem definido ("Criar uma aula autodidata...").
*   **Contexto adequado:** O contexto de aprendizagem de idiomas através de músicas é bem estabelecido.
*   **Exemplos (Few-shot Learning):** Este é um ponto de melhoria chave. O prompt descreve *o que* cada seção deve conter, mas não mostra *como*. Adicionar exemplos concretos para uma ou duas seções guiará o modelo de forma muito mais eficaz.
*   **Dados de entrada:** Os placeholders `[idioma-alvo]`, `[nível de proficiência]` e `[música escolhida]` são perfeitos.
*   **Formatos de saída:** A estrutura numerada de 1 a 12 é excelente e define o formato com clareza.

#### **2. Alinhamento com Princípios**

O prompt está bem alinhado com os princípios de imparcialidade, segurança e outros. Para tornar isso ainda mais explícito e robusto, podemos adicionar "guardrails" (grades de proteção) que reforcem esses princípios diretamente nas instruções.

#### **3. Cuidados a Evitar na Aplicação de Prompts**

O prompt atual não apresenta viés, risco de alucinações (pois se baseia em dados fornecidos pelo usuário) ou problemas éticos/privacidade. A adição de restrições mais explícitas (conforme sugerido abaixo) fortalecerá a proteção contra desvios.

#### **4. Componentes de um Prompt**

*   **4.1 Componentes Estruturais**
    *   **Persona:** A persona é excelente. Podemos torná-la ainda mais rica.
    *   **Instrução:** As instruções são claras e usam verbos fortes.
    *   **Exemplos:** Conforme mencionado, a adição de exemplos é a principal sugestão aqui.
    *   **Contexto:** O contexto é claro.
    *   **Restrições ou Limitações:** O prompt tem algumas restrições ("Ajuste rigorosamente..."), mas podemos adicioná-las para ter um controle mais fino sobre o tom, extensão e escopo.

*   **4.2 Componentes de Conteúdo e Suporte**
    *   **Conteúdo Principal:** As informações do usuário são o conteúdo principal.
    *   **Conteúdo de Suporte:** A estrutura da aula funciona como conteúdo de suporte. Podemos adicionar mais um pouco, como o público-alvo.

*   **4.3 Componentes de Direcionamento de Saída**
    *   **Indicações:** Os títulos das seções (1 a 12) servem como boas indicações.
    *   **Formato de Saída:** O formato está bem definido.

#### **5. Técnicas de Engenharia de Prompt**

*   **5.1 Estrutura e Organização:** A estrutura já é clara. Podemos reforçar as instruções no final.
*   **5.2 Processamento e Lógica:** A tarefa já está dividida em etapas. Podemos solicitar uma "cadeia de pensamento" sutil para o modelo justificar suas escolhas pedagógicas.
*   **5.3 Controle de Saída e Segurança:** A adição de "Guardrails" explícitos aprimorará este ponto.

---

### **Versão Revisada e Aprimorada do Prompt**

Aqui está o prompt com todas as sugestões integradas. As adições e modificações estão em **NEGRITO**.

**Papel (Persona)**
Aja como um **especialista em poliglotismo e em aprendizagem de línguas baseada em evidências científicas, com mais de 10 anos de experiência na criação de materiais didáticos inovadores.** Seu tom de comunicação deve ser sempre **motivador, encorajador e extremamente didático**, como um tutor paciente que guia o aluno a cada passo.

**Objetivo**
Criar **uma única aula autodidata completa, altamente guiada e passo a passo**, para aprendizagem de idiomas por meio de músicas, fundamentada em princípios da aquisição de segunda língua, psicologia cognitiva e prática deliberada. **O objetivo final é que o aluno sinta um progresso tangível em sua compreensão e confiança ao usar o idioma-alvo após a aula.**

---

### Informações fornecidas pelo usuário (Dados de Entrada)

*   **Idioma-alvo:** [insira o idioma]
*   **Nível de proficiência:** [iniciante | intermediário | avançado]
*   **Música escolhida:** [título da música – intérprete]

---

### Instruções para geração da aula

Com base nas informações acima, elabore **uma única aula estruturada**, centrada exclusivamente na música selecionada, com foco integrado em:

*   **Compreensão auditiva**
*   **Produção oral**
*   **Expansão lexical**

A aula deve ser apresentada de forma **sequencial, didática e detalhada**, contendo obrigatoriamente as seguintes etapas. **Para cada seção, antes de apresentar o conteúdo, inclua uma breve frase explicando o propósito pedagógico daquela etapa (Ex: "Nesta etapa, vamos ativar seu conhecimento prévio para preparar seu cérebro para o novo vocabulário.").**

1.  **Objetivos da aula**
    *   Descreva claramente as habilidades linguísticas que serão desenvolvidas.
    *   **Exemplo de como esta seção deve ser formatada:**
        *   *Ao final desta aula, você será capaz de:*
        *   *   Identificar o tema principal da música "Imagine" de John Lennon.*
        *   *   Utilizar corretamente 5 novos verbos no modo imperativo.*
        *   *   Pronunciar claramente os sons finais das palavras terminadas em "-tion" em inglês.*

2.  **Ativação de conhecimento prévio**
    *   Apresente 3 a 5 perguntas guiadas relacionadas ao tema da música para estimular a reflexão do aluno antes mesmo de ouvir a música.
    *   **Exemplo de como esta seção deve ser formatada (para uma música sobre esperança):**
        *   *Antes de ouvirmos, reflita:*
        *   *1. O que a palavra "esperança" significa para você?*
        *   *2. Descreva um momento em que você se sentiu esperançoso.*
        *   *3. Que tipo de música você associa a sentimentos positivos?*

3.  **Primeira escuta global**
    *   Oriente o aprendiz sobre o que observar durante a escuta inicial. **Mantenha a instrução concisa, com no máximo 2 frases.**

4.  **Letra da música no idioma-alvo**
    *   Apresente a letra completa, seguida de **tradução integral para o português**. **Formate a letra e a tradução em duas colunas lado a lado para facilitar a comparação.**

5.  **Segunda escuta guiada**
    *   Proponha atividades focadas na compreensão auditiva detalhada e nas ideias centrais. **Limite esta seção a no máximo 3 atividades.**

6.  **Vocabulário-chave**
    *   Selecione e explique palavras e expressões relevantes, sempre contextualizadas na música. **Selecione de 7 a 10 itens, dependendo da complexidade da música.** Para cada item, forneça: a palavra/expressão, a tradução, um exemplo da letra e um novo exemplo em uma frase diferente.

7.  **Explicações gramaticais explícitas**
    *   Explique claramente as estruturas gramaticais presentes na letra, ajustando a profundidade ao nível informado. **Foque em no máximo 2 estruturas gramaticais principais para não sobrecarregar o aluno.**

8.  **Exercícios estruturados (com respostas-modelo)**
    *   Inclua atividades de:
        *   Compreensão auditiva
        *   Uso do vocabulário em novos contextos
        *   Aplicação das estruturas gramaticais
        *   Produção oral guiada
    *   **Forneça no máximo 1 exercício para cada categoria acima, totalizando 4 exercícios. Apresente as respostas-modelo de forma clara e destacada.**

9.  **Pronúncia e entonação**
    *   Proponha atividades como repetição orientada e shadowing, adequadas ao nível do aprendiz. **Seja específico: indique trechos da música (ex: "refrão, da linha 3 a 5") para praticar e aponte 1 ou 2 aspectos fonéticos específicos (ex: "a pronúncia do 'r' no início da palavra").**

10. **Tarefa de produção oral**
    *   Solicite uma produção oral guiada, apresentando exemplos claros de respostas esperadas. **A tarefa deve ser uma pergunta aberta que incentive o aluno a usar o vocabulário e a gramática da aula para expressar sua própria opinião sobre o tema da música.**

11. **Tarefa de consolidação pós-aula**
    *   Proponha uma atividade de revisão e retenção para ser realizada após a aula. **Sugira uma tarefa prática e leve, como "Reescreva o refrão da música com suas próprias palavras" ou "Encontre outra música do mesmo artista e identifique uma das palavras que aprendemos hoje".**

12. **Resumo final da aula**
    *   Apresente, de forma sintética, os **pontos-chave aprendidos**, incluindo:
        *   Vocabulário principal
        *   Estruturas gramaticais
        *   Habilidades linguísticas desenvolvidas
    *   **Use um formato de lista com marcadores para fácil visualização.**

### Diretrizes Pedagógicas Gerais e Restrições (Guardrails)

*   Ajuste rigorosamente a linguagem, a complexidade e o ritmo ao **nível de proficiência informado**.
*   Mantenha uma progressão pedagógica clara e orientação constante ao aprendiz.
*   Estruture a aula para **uso totalmente autodidata**, sem pressupor mediação externa.
*   **Restrições de Segurança e Ética:**
    *   **Ao analisar a letra, evite fazer julgamentos de valor ou promover estereótipos. Foque exclusivamente nos aspectos linguísticos e culturais de forma informativa e respeitosa.**
    *   **Caso a música contenha linguagem ofensiva, temas sensíveis ou conteúdo adulto inadequado para o contexto de aprendizado, inclua um aviso claro no início da aula e ofereça uma abordagem focada apenas nos elementos linguísticos, minimizando a exposição ao conteúdo sensível.**
*   **Restrição de Estilo e Tom:**
    *   **Mantenha um tom positivo e encorajador em toda a aula. Use frases como "Ótimo trabalho!", "Você está progredindo!" e "Vamos juntos neste passo!".**
*   **Repetição de Instruções Finais:**
    *   **Lembre-se: o objetivo é criar uma aula autodidata, sequencial e motivadora, focada na música fornecida e no nível do aluno. Todas as seções devem seguir a estrutura e os exemplos fornecidos.**
```    
