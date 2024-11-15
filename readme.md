<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo, objetivo, tipo de exercícios preferidos, com o apoio do exame de bioimpedância e uma dieta balanceada. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 2 dias              | Treino AB                   |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 4 dias              | Treino ABCD                 |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **AB**: Divisão do treino em dois dias, cada um focado em grupos musculares diferentes.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCD**: Divisão do treino em quatro dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

---
## 🎯 Objetivo

Informar o objetivo irá ajudar o assistente a providenciar o melhor treino, considerando esse dado especifico. Abaixo temos descrito os tipos de objetivos:

-**Hipertrofia Muscular**: Objetivo: Aumento do volume muscular. Significado: Treinamento focado em desenvolver o tamanho das fibras musculares, geralmente através de repetições moderadas e carga progressiva.

-**Definição Muscular**: Objetivo: Redução de gordura para exibir melhor o contorno muscular. Significado: Treinamento que combina trabalho muscular e atividades aeróbicas, visando a manutenção muscular com baixa gordura corporal.

-**Perda de Peso**: Objetivo: Redução do peso corporal total, geralmente focado em gordura. Significado: Treinamento aeróbico e de resistência, com controle alimentar, para reduzir o peso e melhorar a composição corporal.

-**Powerlifting**: Objetivo: Aumento de força máxima. Significado: Foco nos levantamentos básicos (agachamento, supino e levantamento terra) com baixa repetição e carga elevada, visando desenvolver força absoluta.

-**Condicionamento Físico Geral**: Objetivo: Melhora da saúde e capacidade física geral. Significado: Exercícios variados para melhorar resistência, flexibilidade, força e saúde cardiovascular, com foco em bem-estar.

-**Treinamento Funcional**: Objetivo: Melhorar a funcionalidade e desempenho das atividades do dia a dia. Significado: Exercícios que imitam movimentos cotidianos, visando equilíbrio, força e coordenação para o corpo funcionar de forma mais eficiente.

-**Aumento de Resistência Cardiovascular**: Objetivo: Melhorar a capacidade cardiorrespiratória. Significado: Exercícios aeróbicos de longa duração e intensidade moderada a alta, para fortalecer o sistema cardiovascular e aumentar a capacidade aeróbica.

-**Reabilitação Física**: Objetivo: Recuperação e fortalecimento após lesões ou cirurgias. Significado: Exercícios específicos e progressivos para ajudar na recuperação de funções e na prevenção de novas lesões, sempre com orientação médica.

-**Mobilidade e Flexibilidade**: Objetivo: Aumentar a amplitude de movimento e prevenir lesões. Significado: Foco em alongamentos, mobilidade articular e exercícios de flexibilidade, ajudando na performance e diminuindo o risco de lesões.

-**Performance Esportiva**: Objetivo: Aumentar a capacidade física específica para um esporte. Significado: Treinamento adaptado às demandas do esporte, como agilidade, explosão e resistência, focando em melhorar o desempenho atlético específico.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 📝Bioimpedância

Caso possua um exame de bioimpedância, compartilhe para que o assistente consiga compartilhar um treino adequado ao seu arquétipo físico.


---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e informe o seu **objetivo**.
3. **Escolha o tipo de treino mais adequado**.
4. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
5. **Compartilhe um exame de Bioimpedância** para que o assistente consiga informar um treino adequado aos seus objetivos.
6. Use o prompt do assistente para gerar um plano de treino personalizado e uma sugestão de dieta para seu desenvolvimento.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto
