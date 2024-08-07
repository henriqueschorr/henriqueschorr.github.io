# Moves

Moves (inglês) engloba qualquer ação ou reação que uma criatura (PC ou NPC) pode realizar.

## Ações
PCs e NPCs podem executar basicamente todas as ações básicas como mover, empurrar, saltar, etc. Não há uma lista de ações fixa que deve ser seguida, o céu é o limite, use sua imaginação. Qualquer ação pode ser proposta, mas nem toda ação será válida. Os jogadores, juntamente com o GM, entrarão em acordo se algo é possível ou não, sendo o GM a pessoa com a palavra final. Um lobo não pode atirar com uma arma, por exemplo, uma vez que não possui mãos. Seja criativo, porém sensato.

Algumas ações, principalmente durante combate ou em situação de perigo, necessitarão de um [Check](./checks.md) para resolver, indicando assim seu grau de sucesso e o desfecho de sua narrativa.

Exemplos de ações básicas são:

<!-- no toc -->
- [Mover, Saltar, Nadar](#movimento)
- [Hackear, Desativar, Calcular](#ações-envolvendo-ciência)
- [Atacar](#ataques)
- [Usar um Equipamento](#uso-de-equipamentos)
- [Usar Habilidade](#habilidades)
- Empurrar
- Negociar
- Ameaçar
- etc

### Movimento

Quando sob pressão ou em situações de perigo, como em combate, seu personagem pode se mover até distância informada em suas ficha, como qualquer parte de alguma outra ação, ou fazer um check de Agilidade caso queira se mover para uma distância maior. Caso falhar no check de Agilidade, alguma complicação acontece que impede seu movimento.

NPCs podem se mover até distância informada em sua ficha e fazer alguma ação como parte de sua ativação. Caso o GM desejar mover o NPC para uma distância maior, esse movimento será toda sua ativação, não podendo realizar moves, mas também não precisando fazer um check de Agilidade.

Existem tipos de movimento, estes que identificam como você pode ser mover pelo ambiente.

| Tipo        | Descrição                                                                |
| ----------- | ------------------------------------------------------------------------ |
| Aéreo       | Criatura pode voar como um pássaro.                                      |
| Aquático    | Criatura pode se movimentar livremente quando submersa como um peixe.    |
| Subterrâneo | Criatura pode cavar túneis e se movimentar por sólidos como uma topeira. |
| Terrestre   | Criatura se movimenta em chão firme e horizontal como um humano.         |
| Vertical    | Criatura pode escalar paredes e tetos livremente como uma aranha.        |

### Uso de Equipamentos

Usar equipamentos conta como um move, porém não é necessário realizar checks, a não ser que indicado o contrário, ou caso você esteja usando o equipamento para auxiliar em alguma tarefa. Por exemplo, se você for simplesmente usar uma lanterna, não há necessidade alguma de realizar um check; porém se você estiver usando um pé-de-cabra para arrombar uma porta, provavelmente seu GM irá requisitar um.

### Ações envolvendo Ciência

Se sua espécie possui um nível de [conhecimento de ciência](./knowledge.md#ciência) Base, você pode realizar ações, como: 

* Hackear um dispositivo digital para desbloquear uma porta
* Desativar uma bomba
* Fazer uma ligação direta de um veículo
* [Crafting](./crafting.md)

Caso você seja perito em alguma das áreas da ciência, seu check de ação envolvendo aquela área é realizado com Vantagem.

### Ataques

Ataques são moves realizados com armas e habilidades, com o propósito de causar dano em criaturas inimigas. Um ataque sempre seguirá a seguinte linha de resolução:

#### Passo 1: Ataque

1. Escolha 1 ou mais alvos (dependendo da arma/habilidade).
2. Alvo deve indicar se irá usar alguma [Reação](#reações), gerando uma [Disputa](./checks.md#disputa).
3. Role o [Check](./checks.md) com o atributo indicado.   
   Mantenha os dados na "mesa", ou o resultado anotado, pois o dano é calculado a partir deles na maioria das vezes.
4. Verifique o [Grau de Sucesso](./checks.md#graus-de-sucesso). Resolva a disputa caso o alvo tenha usado alguma reação.
5. Calcule o [Dano](./damage.md#calculando-dano) de acordo com o grau de sucesso.  
   Algumas Habilidades ou Propriedades de armas podem modificar o dano.
6. Compare o Dano aos Limites de Dano do alvo.
7. Marque a quantidade de AP/Feridas de acordo com o Limite de Dano atingido. 

Quando um ataque é feito contra <ins>mais de um alvo</ins>, você realiza apenas um check para determinar se acerta os alvos ou não.

Quando um ataque é feito em uma <ins>área</ins>, você não faz um check, os alvos presentes na área terão que esquivar ou realizar outra reação para evitar o ataque.

Quando você causar <ins>dano em mais de uma criatura</ins>, você rola o dano apenas uma vez, aplicando o mesmo dano em todos os alvos atingidos.

<!-- 6. Verifique se o alvo possui alguma Resistência, Vulnerabilidade ou Imunidade. Modifique o valor do Dano de acordo. -->

#### Passo 2: Efeitos

Algumas armas/habilidades irão ter efeitos adicionais devido a alguma [Propriedade](./properties.md#propriedades-de-armas) ou outra característica, como por exemplo [Recarregar](./properties.md#recarregar), ou aplicarão [Condições](./conditions.md). Condições só serão aplicadas caso o ataque tenha causado dano, a não ser que indicado o contrário.

## Reações

Apesar das ações serem completamente livres, as reações possuem uma lista predefenida do que pode ser realizado. Personagens e NPCs podem possuir habilidades que se comportam como reação, dando-os assim mais opções. Quase todas as reações usam checks de [Disputa](./checks.md#disputa).

Seu personagem possui um número limitado de reações, que uma vez usadas, são recuperadas no começo do turno de equipe. 
<!-- Portões do Caos de Agilidade e outras fontes permitem você ter reações adicionais. -->

### Esquivar

Criatura tenta esquivar de um ataque inimigo realizando um check de Agilidade.

**Falha ou Falha Crítica:** Criatura não consegue esquivar e recebe o dano completo.  
**Perde a Disputa:** Criatura não consegue esquivar e recebe o dano completo.  
**Vence a Disputa:** Criatura consegue esquivar e não recebe dano algum.

### Defender

Criatura possui um escudo, outro objeto ou arma natural com a propriedade **Defender**, e defende a si mesmo ou alguma criatura adjacente. O Atributo utilizado neste check depende do item usado para realizar a defesa.

Caso o alvo seja si próprio:

**Falha ou Falha Crítica:** Criatura não consegue defender e recebe o dano completo.  
**Perde a Disputa:** Criatura não consegue defender e recebe o dano completo.  
**Vence a Disputa:** Criatura consegue defender e não recebe dano algum.  
**Sucesso Crítico:** Criatura consegue defender, não recebe dano algum e pode realizar uma ação imediatamente. 

Caso o alvo seja outra criatura:

**Falha ou Falha Crítica:** Criatura não consegue defender e alvo do ataque recebe o dano completo.   
**Perde a Disputa:** Criatura defende parcialmente e o dano completo é dividido (round up) entre ela e o alvo do ataque.   
**Vence a Disputa:** Criatura consegue defender e ninguém recebe dano.  
**Sucesso Crítico:** Criatura consegue defender, ninguém recebe dano e pode realizar uma ação imediatamente.  

### Resistir

Alguns ataques ou itens do cenário irão causar [Condições](./conditions.md) ou outros efeitos nocivos a uma criatura. Para se proteger deste efeitos a criatura deve Resistir com algum Atributo. A fonte de efeito sempre irá dizer se é possível Resistir e qual Atributo a criatura levará em consideração para realizar este check.

**Falha ou Falha Crítica:** Criatura recebe efeito da fonte normalmente.  
**Sucesso Parcial:** Criatura recebe efeito pela metade. Divida qualquer número encontrado no efeito (round up).  
**Sucesso ou Sucesso Crítico:** Criatura resiste ao efeito da fonte por completo.

## Habilidades

PCs e alguns NPCs possuirão Habilidades Ativas. Habilidades são ações e/ou reações com efeitos poderosos.Habilidades geralmente terão um custo em Caos, Stress, Terror ou outro recurso.
<!-- 
## Ações de Equipe

Ações de equipe são ações especiais que podem ser realizadas por qualquer integrante da equipe ao custo de [Karma](./resources.md#karma).

#### Teamwork

Ao custo de 1 karma, você pode ajudar um integrante da sua equipe a realizar uma ação.

1. Descreva narrativamente como você irá ajudar seu aliado.
2. GM e você decidem qual atributo você usará para conceder a ajuda.
3. Você rola um check do atributo e seu aliado rola o check da ação dele.
4. Considerem o melhor resultado para executar a ação.

#### Dose Dupla

Ao custo de 2 karma, dois integrantes da equipe podem realizar uma ação em conjunto.

1. Ambos os integrantes da dupla declaram qual ações/habilidades desejam realizar e descrevem de forma narrativa como irão realizá-las em conjunto.
2. Ambos realizam seu check separadamente, porém o melhor resultado entre os dois será utilizado para ambas ações.
3. Some o dano de ambos e aplique no alvo ou distribua entre os alvos caso seja mais de um. -->
