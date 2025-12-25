# Componentes Estruturais de um Prompt

## Visão Geral
Os componentes estruturais são a base de qualquer prompt eficaz. Eles definem **quem a IA deve ser**, **o que ela deve fazer**, **em qual contexto** e **sob quais limites** a resposta deve ser produzida.

Em contextos acadêmicos, educacionais e em saúde, esses componentes são essenciais para garantir **clareza, precisão, reprodutibilidade e responsabilidade ética**.

---

## 1. Persona (Quem a IA deve ser?) 🎭

### Definição
A *persona* define a identidade assumida pelo modelo de Inteligência Artificial, incluindo:
- nível de especialização,
- papel profissional,
- tom de comunicação,
- perspectiva epistemológica.

Ela funciona como um enquadramento cognitivo que orienta o tipo de conhecimento mobilizado pela IA.

### Boas práticas
- Definir nível de expertise (júnior, sênior, especialista)
- Especificar área de atuação
- Ajustar ao público-alvo final

### Exemplo aplicado à saúde
> “Atue como um pesquisador sênior, com especialidade em reabilitação traumato-ortopédica e experiência em publicação de artigos científicos indexados na base SciELO.”

### Erro comum
Usar personas vagas como “especialista” ou “professor”, sem indicar área, contexto ou público.

---

## 2. Instrução (O que deve ser feito?) 📝

### Definição
A instrução é o **comando central do prompt**. Ela descreve explicitamente a ação que o modelo deve executar.

Instruções eficazes:
- começam com verbos claros,
- descrevem tarefas específicas,
- evitam ambiguidades.

### Exemplos de verbos fortes
- Analise
- Compare
- Avalie
- Sintetize
- Estruture
- Justifique

### Exemplo aplicado à pesquisa
> “Analise a metodologia deste estudo fictício, identifique possíveis vieses, redija uma seção de discussão para os resultados apresentados e liste as principais limitações do estudo.”

### Erro comum
Instruções genéricas como: “me ajude com isso” ou “explique melhor”.

---

## 3. Exemplos (Few-shot Learning)

### Definição
O *Few-shot Learning* consiste em fornecer exemplos explícitos de **entrada → saída** dentro do próprio prompt, demonstrando ao modelo **como** a tarefa deve ser realizada.

Essa técnica é particularmente eficaz para:
- formatação,
- padronização,
- tarefas normativas (ex.: normas ABNT).

### Exemplo aplicado
> “Formate as referências abaixo segundo a norma ABNT.  
>  
> **Entrada 1:** Article by John Doe published in 2021 in the Journal of Physical Therapy, volume 10, pages 25–35.  
> **Saída esperada 1:** DOE, J. Article name. *Journal of Physical Therapy*, v. 10, p. 25–35, 2021.  
>  
> Agora, formate esta referência:  
> **Entrada 2:** Study by Mary Silva about aquatic therapy, from 2022, in the Brazilian Journal of Physiotherapy, issue 3, pages 112–120.”

### Erro comum
Confiar apenas em descrições abstratas sem exemplos concretos.

---

## 4. Contexto (Qual é o cenário?) 🌍

### Definição
O contexto fornece os **antecedentes da tarefa**, ajudando a IA a compreender:
- o objetivo maior,
- o público-alvo,
- o momento da interação.

Sem contexto, a IA tende a gerar respostas genéricas.

### Exemplo aplicado à educação
> “Você está me auxiliando na escrita do capítulo de metodologia do meu Trabalho de Conclusão de Curso. O público-alvo são professores de fisioterapia, e o tema é a análise da marcha em pacientes com doença de Parkinson.”

### Erro comum
Assumir que a IA “sabe” para quem ou para quê a resposta será utilizada.

---

## 5. Restrições ou Limitações ⚠️

### Definição
As restrições delimitam a resposta da IA em termos de:
- escopo,
- estilo,
- extensão,
- conteúdo permitido.

Elas são fundamentais para **segurança, precisão e ética**.

### Tipos de restrições

#### a) Limitação de escopo
> “Responda apenas sobre métodos de avaliação postural, sem realizar diagnósticos ou sugerir tratamentos clínicos.”

#### b) Restrição de estilo
> “Utilize linguagem acessível, evitando termos estatísticos avançados, considerando alunos do 3º período de Fisioterapia.”

#### c) Limitação de extensão
> “Apresente a análise crítica em, no máximo, dois parágrafos.”

### Erro comum
Não definir limites, levando a respostas longas, imprecisas ou inadequadas ao contexto profissional.

---

## Síntese dos Componentes Estruturais

| Componente | Função Principal |
|-----------|------------------|
| Persona | Define quem a IA deve ser |
| Instrução | Define o que deve ser feito |
| Exemplos | Demonstram como fazer |
| Contexto | Situa a tarefa |
| Restrições | Delimitam a resposta |

---

## Conclusão
O domínio dos componentes estruturais transforma o prompt de uma simples pergunta em uma **ferramenta metodológica**, capaz de gerar respostas mais confiáveis, úteis e alinhadas às exigências da educação e da saúde.

No próximo arquivo, serão abordados os **Componentes de Conteúdo e Suporte**, responsáveis por qualificar a informação processada pela IA.
