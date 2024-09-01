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
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de dias, tipo de exercícios preferidos, tempo disponível, nivel de experiência e Objetivos específicos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [<img src="https://github.com/user-attachments/assets/64e0ae06-062a-46d9-a5fa-d5d7bdf6cc0f" width="15px" height="15px"> Tempo disponível](#-tempo-disponivel)
- [<img src="https://github.com/user-attachments/assets/e1818f65-9659-440e-8579-613a16b9850c" width="15px" height="15px"> Nível de experiência](#-nível-de-experiência)
- [<img src="https://github.com/user-attachments/assets/eff47c0f-9edf-4da5-afae-6d5bb381a9a9" width="15px" height="15px"> Objetivos específicos](#-objetivos-específicos)
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
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

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

## <img src="https://github.com/user-attachments/assets/64e0ae06-062a-46d9-a5fa-d5d7bdf6cc0f" width="25px" height="25px"> Tempo disponível

A quarta regra envolve o tempo disponível para treinar por dia

1. **Caso seja de 1-2 horas** não divide o treino ao dia.
2. **Caso seja de 2-4 horas** divide o treino por duas vezes ao dia. 

---

## <img src="https://github.com/user-attachments/assets/e1818f65-9659-440e-8579-613a16b9850c" width="25px" height="25px"> Nível de experiência

A quinta regra envolve o nível de experiência.

1. Iniciante.
2. Intermediário.
3. Avançado.

---

## <img src="https://github.com/user-attachments/assets/eff47c0f-9edf-4da5-afae-6d5bb381a9a9" width="25px" height="25px"> Objetivos específicos

A sexta regra envolve os objetivos específicos.

1. Perder peso.
2. Ganhar massa muscular.
3. Melhorar definição corporal.

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. **Seleione o tempo disponível** que tem disponível por dia em horas.
5. **Selecione o nível de experiência** o treino será gerado de acordo com o seu nível de experiência.
6. **Determine o seu objetivo específico** o treino será gerado de acordo com o seu objetivo específico.
7. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

### Prompt:
#Conceito
Se comporte como um personal trainer, me ajude a montar um treino personalizado baseado em variáveis que irei te informar abaixo:

área de variáveis
- {{biotipo corporal}}
- {{dias disponíveis para treino}}
- {{tipo de treino}}
- {{tempo disponível}}
- {{nível de experiência}}
- {{objetivo específico}}

#regras

Regra 1 biotipo corporal:
O tipo corporal vai ser algum dos itens abaixo:
- Ectomorfo	Corpo mais magro, difícil ganhar peso e massa muscular.
- Mesomorfo	Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
- Endomorfo	Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

Regra 2 dias disponíveis para treino:
O tipo de treino de acordo com a quantidade de dia vai ser algum dos itens abaixo:
- 1 dia	Treino Full Body
- 3 dias	Treino ABC
- 5 dias	Treino ABCDE

Full Body: Treino que trabalha o corpo todo em uma única sessão.
ABC: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
ABCDE: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

Regra 3 tipo de treino:
- Funcional	Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
- Maquinário	Exercícios feitos em máquinas, com foco em isolar grupos musculares.
- Peso Livre	Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
- Cardio	Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
- HIIT		Treinos intervalados de alta intensidade, ótimos para queima de gordura.

Regra 4 tempo disponível:
- Caso seja de 1-2 horas não divide o treino ao dia.
- Caso seja de 3-4 horas divide o treino por duas vezes ao dia de forma igual, ou seja se for  horas, será 2 horas na parte da manhã e 2 na parte da tarde.

Regra 5 nível de experiência:
-  Iniciante, intermediário ou avançado.

Regra 6 objetivo específico:
- Perder peso.
- Ganhar massa muscular.
- Melhorar definição corporal.

### Resposta!

Personalizando seu treino!
Analisando seus dados:

Biotipo: Endomorfo (tendência a acumular gordura)
Dias disponíveis: 5
Preferência de treino: Mix de funcional, maquinário e peso livre (HIIT na sexta)
Tempo disponível: 4 horas (2 sessões de 2 horas)
Nível: Intermediário
Objetivo: Perder peso e ganhar massa muscular
Estratégia:

Como você é intermediário e busca perder peso e ganhar massa muscular, a combinação de treino de força com alta intensidade e foco em grandes grupos musculares será ideal. O HIIT na sexta-feira dará um boost na queima de calorias.

Sugestão de treino:

**Segunda-feira:** *Peito e Tríceps*

- Sessão 1: Supino reto com barra (3x10), flexão de braço (3x até a falha), crucifixo inclinado (3x12), tríceps na polia (3x12)
- Sessão 2: Desenvolvimento com halteres (3x12), tríceps francês com barra (3x12), pullover com haltere (3x15)

**Terça-feira:** *Costas e Bíceps*

- Sessão 1: Pull-up (ou remada alta na barra fixa) (3x máximo de repetições), remada curvada com barra (3x10), puxada frontal (3x12)
- Sessão 2: Rosca direta com barra (3x12), rosca alternada com halteres (3x12), rosca concentrada (3x15)

**Quarta-feira:** *Ombro e Abdomem*

- Sessão 1: Desenvolvimento com halteres (3x12), elevação lateral (3x15), remada alta (3x12)
- Sessão 2: Plank (3x30s), bicicleta (3x30s), russian twist (3x20)

**Quinta-feira:** *Pernas*

Sessão 1: Agachamento livre (3x12), leg press (3x12), lunges (3x10 por perna)
Sessão 2: Stiff (3x12), panturrilha na máquina (3x15)

**Sexta-feira:** *HIIT*

- 30 minutos alternando entre exercícios de alta intensidade (sprint, burpees, jump squats) e recuperação (caminhada leve).

**Dicas extras:**

- Aqueça sempre antes de cada treino e alongue no final.
- Varie os exercícios a cada 4-6 semanas para evitar a acomodação muscular.
- Aumente gradualmente a carga ou o número de repetições para continuar desafiando seus músculos.
- Descance entre as séries e entre os treinos.
- Alimente-se bem: Uma dieta equilibrada com proteínas, carboidratos e gorduras boas é essencial para o ganho de massa muscular e perda de peso.
- Hidrate-se: Beba bastante água ao longo do dia.
- Consulte um profissional: Um educador físico pode te auxiliar na execução correta dos exercícios e personalizar ainda mais o seu treino.
- Lembre-se: Perder peso e ganhar massa muscular ao mesmo tempo exige consistência e disciplina. Seja paciente e celebre cada pequena vitória!
