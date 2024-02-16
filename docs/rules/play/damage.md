Ao longo da aventura você se encontrará diante de criaturas hostis onde o combate é inevitável, durante o combate você causará dano. Neste capítulo você encontra informações de como o dano é calculado, os tipos de dano, efeitos críticos e outros detalhes diversos sobre o tópico.

## Dano

Todo dano é causado em alguma das resistências, física (RF) ou mental (RM), ou diretamente em sua EN. Se você possui AP para uma ou ambas resistências, o dano é primeiramente subtraído do AP, a não ser que alguma situação diga o contrário.  

_**Exemplo:**Remella realiza um ataque de 3RF em uma criatura que possui 2AP:4RF._

- _O dano total do ataque de Remella é 3RF._
- _Como a criatura possui 2AP, 2 de dano será subtraído primeiramente de seu AP.
- _O dano restante, que é 1, será subtraído diretamente do RF da criatura._
- _Criatura possui 3RF restantes._

## Dano Adicional por Aptidão
Seus armamentos geralmente possuirão danos fixos, mas você causará mais dano assim que alcançar alguns valores em suas aptidões.  
Tenha em mente que Dano Adicional é diferente de Dano Extra, e sim, dano adicional é considerado para a mecânica de Dano Dobrado.

_**Exemplo:**Mari'Jonna possui 80 pontos em Físico e 60 pontos em Controle._

- _Ela resolve fazer um ataque a distância que causa 2RF._
- _Seu ataque utiliza a aptidão de controle, que com o valor de 60, possui 1 de dano adicional._
- _Seu ataque causa 3RF de dano._

| Valor | Dano Adicional |
| ----- | -------------- |
| 60    | +1             |
| 80    | +1             |
| 100   | +1             |

## Dano Múltiplo

Alguns armamentos ou habilidades mais avançadas podem ter mais de um tipo de dano, por exemplo, a munição explosiva dos humanos que causa tanto dano de perfuração, quanto dano de concussão. Essa informação estará indicada claramente no armamento ou habilidade. Nestes casos você considera ambos danos na soma do dano total.

## Explosão de Dano

A explosão de dano pode acontecer durante [Ações Surpresas](./situationalModifiers.md#ação-surpresa) ou caso algum armamento, habilidade ou outro efeito informe o mesmo.  
Quando um ataque seu possui explosão de dano, você causa 1RDA da aptitude usada no ataque como <ins>dano extra</ins>.  
Caso você tire o valor máximo do seu RDA, você rola novamente e acrescenta ainda mais o valor como dano extra. Esse efeito pode se repetir infinitamente, até você tirar um valor que seja menor que seu valor máximo de RDA.  

_**Exemplo:** Remella está em furtividade e decide atacar uma criatura, sendo assim, um ataque surpresa que possui explosão de dano_.

- _Remella ataca a distância com seu arco que tem dano base 2RF._
- _Remella tem explosão de dano e tem 1d4 como seu RDA da aptitude de controle._
- _Remella joga o dado e tira 4!_
- _Sendo 4 o valor máximo de seu RDA, ele joga novamente, rolando agora um 2._
- _Ao final das rolagens, Remella possui 6 de dano extra._
- _Dano total: 8RF_

### Múltiplas Instâncias de Explosão de Dano

Múltiplas instâncias de Explosão de dano são somatórias, ou seja, se você tem explosão de dano por ataque surpresa e ponto fraco, você rola seu RDA no mínimo 2 vezes.

## Dano Dobrado

Algumas situações, como tirar acerto crítico em um ataque com dano corte, podem fazer seu ataque ter dano dobrado.   
Para dobrar o dano, você dobra o dano total do seu ataque, menos fontes de <ins>dano extra</ins>.  
Tenha em mente que fontes de <ins>dano adicional</ins> ainda são consideradas para o dano dobrado.  

_**Exemplo 1:** Remella tira 33 no check do seu ataque com um armento que causa dano do tipo corte, causando assim dano dobrado no inimigo._

- _Remella ataca a distância com seu arco que tem dano base 2RF._
- _Dano total dobrado: 4RF_

_**Exemplo 2:** Remella tira 33 no check do seu ataque com um armento que causa dano do tipo corte, causando assim dano dobrado no inimigo._

- _Remella ataca a distância com seu arco que tem dano base 2RF._
- _Remella tem 60 na aptidude de controle, concedendo assim 1 de dano adicional ao seu ataque.
- _Dano com dano adiciona: 3RF._
- _Dano total dobrado: 6RF_

_**Exemplo 2:** Remella tira 33 no check do seu ataque com um armento que causa dano do tipo corte, causando assim dano dobrado no inimigo._

- _Remella ataca a distância com seu arco que tem dano base 2RF._
- _Remella estava em furtividade e seu ataque é surpresa, possuindo assim Explosão de Dano._
- _Explosão de dano lhe concede 1 de dano extra._
- _Dano dobrado: 4RF_
- _Dano total com dano extra: 5RF_

### Múltiplas Instâncias de Dano Dobrado

Múltiplas instâncias de dano dobrado <ins>não</ins> são somatórias.

## Penetração

Ataques com penetração causam 1 de dano extra no AP da resiliência alvo (RF ou RM), caso a criatura possua AP.

### Múltiplas Instâncias de Penetração

Múltiplas instâncias de penetração são somatórias. Você causa 1 de dano extra ao AP para cada instância de penetração.

## Ponto Fraco

Criaturas ou você podem ter seus pontos fracos expostos através de alguma habilidade ou equipamento, como por exemplo a habilidade de Legenda: Orgânicos do humano cientista. Pontos fracos não precisam ser necessariamente especificados, pode ser um ponto fraco genérico qualquer.  
Quando alguém ataca pela primeira vez uma criatura que tenha ponto fraco especificado, seu ataque tem Explosão de Dano.  
O ponto fraco "some" após a criatura sofrer o primeiro ataque e se torna indisponível pelas próximas 24 horas.

## Tipos de dano

No universo há diversos tipos de armamentos e habilidades diferentes, o tipo de dano aplicado não poderia ser diferente. Abaixo você encontra todos os tipos de dano e o efeito causado caso você tenha um Sucesso Crítico durante o ataque, além de alguns exemplos do que pode causar este dano.

| Tipo de Dano | Efeito Crítico             | Exemplos                           |
| ------------ | -------------------------- | ---------------------------------- |
| Caos         | Descrito no fator causador | Armamentos produzidos com Solarium |
| Concussão    | Dano Dobrado se AP         | Broto: Punhos, Braços-Tentáculos   |
| Corrosivo    | Dano Dobrado               | Florescer, Infectar                |
| Corte        | Dano Dobrado se não AP     | Lâmina Retrátil, Pétalas de Sangue |
| Energia      | Desconectado 2             | Lâmina de Energia                  |
| Fogo         | Dano Persistente (RF) 2    | Granada Termobárica                |
| Gelo         | Limitado 2                 | Mina de Congelamento               |
| Neural       | Incapacitado 2             | Palavra Final, Sonhos e Pesadelos  |
| Perfuração   | Penetração                 | Pistola, Broto: Espinhos           |
| Radiação     | Dano Persistente (RF) 2    | Objetos radioativos, espaço        |
| Sensorial    | Inapto 2                   | Granada de Luz                     |
| Veneno       | Descrito no fator causador | Glândula de Veneno                 |
