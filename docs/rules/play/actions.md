Ações definem o que você pode fazer durante seu Turno. Em geral, você pode realizar 3 ações por turno, porém há ações com custo maior, ou seja, que consumirá o espaço de 2 ou mais ações, podendo ocupar até o turno inteiro.

## Visão Geral

| Ação                      | Custo | Detalhes                                                                                                                                                                                                                                                                                                                            |
| ------------------------- | ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Mover](#mover)           | 1     | Caminhar, Abaixar, Levantar, Saltar, Escalar, Nadar, Cavar, Voar.                                                                                                                                                                                                                                                                   |
| [Manobra](#manobra)       | 1     | Agarrar, Puxar, Empurrar, Derrubar, Desarmar, Libertar.                                                                                                                                                                                                                                                                             |
| [Interagir](#interagir)   | Varia | **Social**: Interagir, comunicar com outros personagens, criaturas, NPCs.<br>**Ambiente**: Interagir com ambiente, como jogar areia em alguém, acionar uma alavanca.<br>**Equipamento**: Interagir com algum objeto em sua posse, trocar de arma, aplicar med-gel, recarregar.<br>**Ajudar**: Ajude um aliado a performar uma ação. |
| [Preparar](#preparar)     | 1     | Escolha alguma outra ação e aja após um gatilho definido.                                                                                                                                                                                                                                                                           |
| [Procurar](#procurar)     | 1     | Procure por um objeto ou criatura.                                                                                                                                                                                                                                                                                                  |
| [Atacar](#atacar)         | Varia | Atacar com algum armamento.                                                                                                                                                                                                                                                                                                         |
| [Ciência](#ciência)       | Varia | Realizar cálculos, performar cirurgia, construir objeto, consertar veículo. Qualquer ação envolvendo a competência de Ciência e conhecimento sobre as áreas científicas.                                                                                                                                                            |
| [Habilidade](#habilidade) | Varia | Usar alguma habilidade do seu personagem.                                                                                                                                                                                                                                                                                           |

## Mover

Mover é uma das ações mais básicas do jogo e inclui qualquer ação que envolva o corpo do seu personagem mudar seu ponto no eixo espacial. Dependendo da ação desejada ou do contexto do cenário atual, um check de Mobilidade será necessário. Por exemplo, ao caminhar tentando manter o equilíbrio, será necessário um check de Mobilidade & Agilidade.  
Quando você usa a ação Mover, você não precisa mover toda sua velocidade antes de realizar alguma outra ação, no momento que você usou Mover, você pode intercalar seu movimento entre suas outras ações.  
Abaixo segue uma lista das ações relacionadas à mobilidade e seus detalhes.

| Movimento | Efeito                                                                                                                                                                                                                                                                                                                         |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Caminhar  | Caminha \<Velocidade\> de distância dentro do seu turno.                                                                                                                                                                                                                                                                       |
| Abaixar   | Se abaixa para uma posição de cócoras, joelho ou deitado.                                                                                                                                                                                                                                                                      |
| Levantar  | Levanta para a posição considerada de pé.                                                                                                                                                                                                                                                                                      |
| Saltar    | Salta um Salto Longo ou Alto.<br>**Distância Salto Longo**: Físico/15 se Caminhar ao menos 3m antes, Físico/20 se parado. <br>**Distância Salto Alto**: Físico/20 se Caminhar ao menos 3m antes, Físico/30 se parado.<br>A distância máxima é limitada pela quantidade de \<Velocidade\> que você ainda tem restante no turno. |
| Escalar   | Escala \<Velocidade\> de distância dentro do seu turno.                                                                                                                                                                                                                                                                        |
| Nadar     | Nada \<Velocidade\> de distância dentro do seu turno.                                                                                                                                                                                                                                                                          |
| Cavar     | Cava, move-se no subterrâneo \<Velocidade\> de distância dentro do seu turno.                                                                                                                                                                                                                                                  |
| Voar      | Voa \<Velocidade\> de distância dentro do seu turno.                                                                                                                                                                                                                                                                           |

| Físico   | Salto Longo Parado | Salto Longo Correndo |
| -------- | :----------------: | :------------------: |
| < 40     |         -          |          -           |
| 40 - 49  |         2m         |          2m          |
| 50 - 59  |         2m         |          3m          |
| 60 - 69  |         3m         |          4m          |
| 70 - 79  |         3m         |       4m - 5m        |
| 80 - 89  |         4m         |          5m          |
| 90 - 100 |      4m - 5m       |          6m          |

| Físico   | Salto Alto Parado | Salto Alto Correndo |
| -------- | :---------------: | :-----------------: |
| < 40     |         -         |          -          |
| 40 - 49  |        1m         |         2m          |
| 50 - 59  |        1m         |         2m          |
| 60 - 69  |        2m         |         3m          |
| 70 - 79  |        2m         |         3m          |
| 80 - 89  |        2m         |         4m          |
| 90 - 100 |        3m         |       4m - 5m       |

## Manobra

Durante o combate, você pode aplicar algumas manobras corporais. Você deve realizar um check de acordo com o descrito em cada manobra, enquanto seu alvo deve gastar uma Reação (caso a tenha), para Esquivar ou Defender.

| Manobra  | Efeito                                                                                             | Check                                |
| -------- | -------------------------------------------------------------------------------------------------- | ------------------------------------ |
| Agarrar  | Alvo fica Preso.                                                                                   | Combate & Físico/Agilidade.          |
| Puxar    | Move 1 alvo adjacente junto com você. Você deve gastar a ação de Mover juntamente com esta manobra | Combate & Físico.                    |
| Empurrar | Move 1 alvo adjacente para 2m longe de você.                                                       | Combate & Físico.                    |
| Derrubar | Alvo fica Caído.                                                                                   | Combate & Físico/Agilidade.          |
| Desarmar | Alvo ficar Desarmado.                                                                              | Combate & Físico/Agilidade/Controle. |
| Libertar | Liberta você ou algum aliado de uma situação que deixou você/ele Preso.                            | Combate & Físico/Agilidade/Cérebro.  |

Manobras só podem ser realizadas em criaturas que são do mesmo Tamanho ou menor a quem está aplicando. A não ser que alguma condição especial diga o contrário.

## Interagir 

Interagir, comunicar com seres vivos, construtos, outras criaturas ou objetos.

### Social

Qualquer interação social com qualquer outra criatura, sendo ela uma intimidação, mentira ou até mesmo um aperto de mão. Geralmente usada com Interação & Influência.

### Ambiente

Interações com objetos ou estruturas do ambiente, como por exemplo, chutar uma poça de água para tentar cegar um inimigo, derrubar uma porta, acionar uma alavanca, pegar uma arma do chão, etc. Geralmente essa ação é tratada como um improviso, portanto o check relacionado, se necessário, deve ser decidido na hora.

### Equipamento

Interação com objetos em sua posse, como por exemplo sacar, guardar ou trocar uma arma, tomar uma poção, etc. Esta ação também serve para recarregar armamentos que utilizam munição e possuam o marcador Recarregar. Geralmente não é necessário checks, mas se for necessário, esta ação também é considerada como um improviso e o check deve ser decidido na hora

### Ajudar

Você pode ajudar alguém a realizar uma ação. Esta ação também é tratada como um improviso, ou seja, o check e efeito são decididos no momento. Alguns exemplos são:

- Fazer um pezinho para um aliado pular mais alto.
- Jogar um aliado contra o inimigo de tamanho menor para aumentar o dano causado por ele ao atacar com uma lança, etc.

## Preparar

Quando você deseja agir somente quando certa situação escolhida acontece na rodada, ou seja, a partir de um gatilho. Exemplos:

- Remella decide Preparar a ação de Ajudar para dar um pezinho para seu aliado assim que ele sair correndo para atacar o inimigo.
- Remella decide Preparar a ação de Atacar para atacar o primeiro inimigo que apareça do esconderijo.

## Procurar

Às vezes um objeto pode virar a situação de um combate, ou você necessita procurar um botão para desligar algum gás venenoso que está entrando na sala, ou ainda sim, você desconfia de que algum inimigo está tentando se esgueirar de modo furtivo. Procurar é usada para cobrir estes cenários. Geralmente usado com Busca & Atenção.

## Atacar

Ação mais comum a se usar durante um combate. Você ataca alguma criatura ou outro alvo qualquer com algum armamento. Geralmente usado com Combate & Físico/Agilidade/Controle.

## Ciência

Realiza alguma ação relacionada às ciências, como por exemplo criar uma solução venenosa, desativar a fechadura eletrônica de uma porta, arrumar o motor de um drone. Essa ação é usada geralmente fora de combate, ou seja, no modo exploração do jogo.

## Habilidade 

Ação especial poderosa exclusiva da sua espécie, geralmente consome EN para alimentá-la.
