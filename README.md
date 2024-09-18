# 🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal

Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário. O projeto deve ser feito utilizando as boas práticas de prompt engineering.

## 📋 Índice
- [📝 Introdução](#introducao)
- [💪 Biotipos Corporais](#biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#dias-disponiveis-para-treino)
- [🏋️ Tipos de Exercícios](#tipos-de-exercicios)
- [🛠️ Regras de Negócio](#regras-de-negocio)
- [📖 Material de Apoio](#material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#prompt-de-resposta-proposto)

## 📝 Introdução
Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

## 💪 Biotipos Corporais
A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

| Imagem | Biotipo    | Descrição                                                        |
|--------|------------|------------------------------------------------------------------|
| ![Ectomorfo](imagens/ectomorfo.png)  | Ectomorfo  | Corpo mais magro, difícil ganhar peso e massa muscular.          |
| ![Mesomorfo](imagens/mesomorfo.png)  | Mesomorfo  | Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura. |
| ![Endomorfo](imagens/endomorfo.png)  | Endomorfo  | Corpo com tendência a acumular gordura, maior dificuldade em perder peso. |

**Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

## 📅 Dias Disponíveis para Treino
A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| Imagem | Dias por Semana | Tipo de Treino Sugerido |
|--------|-----------------|--------------------------|
| ![1 dia](imagens/1-dia.png)   | 1 dia            | Treino Full Body         |
| ![3 dias](imagens/3-dias.png)  | 3 dias           | Treino ABC              |
| ![5 dias](imagens/5-dias.png)  | 5 dias           | Treino ABCDE            |

- **Full Body:** Treino que trabalha o corpo todo em uma única sessão.
- **ABC:** Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE:** Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

## 🏋️ Tipos de Exercícios
A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| Imagem | Tipo de Treino | Descrição                                                    |
|--------|----------------|--------------------------------------------------------------|
| ![Funcional](imagens/funcional.png) | Funcional      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais. |
| ![Maquinário](imagens/maquinario.png) | Maquinário      | Exercícios feitos em máquinas, com foco em isolar grupos musculares. |
| ![Peso Livre](imagens/peso-livre.png) | Peso Livre      | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| ![Cardio](imagens/cardio.png) | Cardio          | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo. |
| ![HIIT](imagens/hiit.png) | HIIT           | Treinos intervalados de alta intensidade, ótimos para queima de gordura. |

## 🛠️ Regras de Negócio
1. Identifique seu biotipo corporal consultando a seção de biotipos.
2. Determine quantos dias por semana você pode treinar e escolha o tipo de treino mais adequado.
3. Selecione o tipo de exercício que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

## 📖 Material de Apoio
Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de Prompt](link-para-fundamentos)
- [Boas Práticas de Prompt](link-para-boas-praticas)

## 🎯 Prompt de Resposta Proposto
O prompt proposto para o assistente de personal trainer deve solicitar as seguintes informações para gerar o plano de treino ideal:

