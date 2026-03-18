[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tro2Z-6l)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23171024&assignment_repo_type=AssignmentRepo)
# Lab 01: Lógica de Programação com Blockly 🐢

Bem-vindo(a) à sua atividade prática de Lógica Computacional! Siga os passos abaixo para completar o desafio.

**Nome do Aluno:** Carlos Vítor Alvim Bianchi dos Guaranys
**Matrícula:** 20261100040
---

## 🎯 Objetivo
Demonstrar capacidade de resolução de problemas algorítmicos completando o **Nível 10** do jogo da Tartaruga (Turtle). 

## 📝 Instruções

**Passo 1: Jogue e Resolva**

Acesse o jogo da Tartaruga no [Blockly Games](https://blockly.games/turtle) e complete as etapas até vencer o **nível 10**.

**Passo 2: Registre sua Solução**

Tire um screenshot (captura de tela) da sua solução final (mostrando os blocos que você usou para passar do nível 10). Faça o upload (envio) dessa imagem **dentro da pasta /imagens** que já existe neste repositório.

**Passo 3: Explique sua Estratégia**

Escreva um pequeno texto explicando qual foi a sua linha de raciocínio e a estratégia que você usou para resolver o nível 10.
*(Exemplo: "Criei uma função para desenhar uma estrela, depois usei um loop para repetir essa função 3 vezes girando 120 graus.")*

**Passo 4: Pergunta Desafio**

Olhando para os blocos que você usou para resolver o jogo no nível 10, imagine que o problema mudou. A sua nova missão agora é desenhar um **hexágono regular** (uma figura geométrica de 6 lados iguais) e repetir esse hexágono **4 vezes**, formando um padrão circular (como as pétalas de uma flor).

**Sem precisar montar os blocos** no jogo, responda por escrito:
* **A)** Quantas repetições o seu loop principal (que desenha o hexágono) precisaria ter e qual seria o ângulo (em graus) que a tartaruga deve virar a cada linha desenhada?
* **B)** Depois de desenhar um hexágono completo, qual deve ser o ângulo de giro (em graus) antes de começar a desenhar o próximo hexágono, para que os 4 fiquem distribuídos igualmente em um círculo completo?
* **C)** Explique brevemente qual foi a lógica (ou o cálculo) que você usou para descobrir os ângulos das questões A e B.

---

## ✍️ Suas Respostas

*(Edite este arquivo e escreva suas respostas dos Passos 3 e 4 aqui embaixo. Lembre-se de colocar a imagem do Passo 2 dentro da pasta **/imagens** deste repositório)*

## 2. Evidência Visual (Screenshot)
*Suba o screenshot da sua solução final (onde aparece "Você resolveu este nível!") para a pasta **/imagens** deste repositório.*

## 3. Estratégia Utilizada
*Explique com suas palavras como você resolveu o problema. Qual foi a lógica?*
> Para fazer as estrelas eu percebi que o padrão de desenho delas se repetia, então utilizei dois loops, um para fazer cada estrela e um para andar de uma estrela para a outra. O primeiro ele somente fazia com que a caneta se movesse pra frente e virasse 144 graus para direita, o que era suficiente para desenhar a estrela. O segundo fazia a caneta andar até onde seria a próxima estrela sem pintar o caminho e ajustar o ângulo para que o primeiro loop se repetisse sem erro. Já para fazer a lua eu utilizei um loop que fazia a caneta mover para frente e para tras 360 vezes, mudando seu ângulo em 1 grau para cada vez que se repetisse. Além disso, outro loop seguinte desse faria um círculo preto inclinado 120 graus a partir do ponto final do loop anterior para dar o aspecto de ser uma lua crescente

## 4. Desafio:
**A)** O loop principal deve repetir 6 vezes(número de lados do hexagono) e a tartaruga deve girar 60 graus para a direita(ângulo suplementar do ângulo interno do hexagono) a cada linha que ela desenhar
  
**B)** Ela deverá girar 90 graus para a esquerda, assim desenhando 4 hexagonos formando um círculo completo no centro
  
**C)** Na questão A, a lógica seria usar os ângulos suplementares dos ângulos internos do hexágono. Já na questão B, como seriam 4 hexágonos para formar um círculo completo, os 360 graus deveriam ser divididos por 4, gerando o ângulo de 90 graus

---
