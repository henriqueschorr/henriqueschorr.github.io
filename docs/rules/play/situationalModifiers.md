### Ataques Múltiplos

Em um turno você geralmente tem 3 ações, se você quiser realizar um ataque para cada ação, seus ataques sofrem as seguintes penalidades:

| Ataque     | Penalidade Check        |
| ---------- | ----------------------- |
| 1º         | -                       |
| 2º         | -5 no check de combate  |
| 3º ou mais | -10 no check de combate |

Você não sofre dessa penalidade caso seu armamento tenha o marcador [Contínuo](../tags/weaponEquipment.md#contínuo).

### Ataques a distância contra inimigos adjacentes

Quando você realiza ataques a distância contra um inimigo adjacente, o ataque é realizado com desvantagem.

### Furtividade

Furtividade é um estado de jogo especial em que seu personagem se encontra quando tenta se esgueirar, infiltrar lugares sem ser percebido por qualquer criatura ou sensores.
Para entrar em estado furtivo, você necessita realizar um check de Infiltração & Agilidade/Atenção, com os possíveis efeitos dependendo o resultado:

- **Sucesso:** Você consegue se infiltrar sem ser percebido.
- **Falha:** As criaturas no local tem ideia da sua presença e sabem sua localização caso tenham linha de visão direta para você.

### Ação Surpresa

Ações Surpresas acontecem quando você realiza alguma ação contra uma criatura ou objeto que não consegue lhe ver, quando você está furtivo quanto a esta criatura. Durante uma ação surpresa o seguinte acontece:

- Ações contra inimigos surpreendidos são Muito Fácil.
- Inimigos não podem usar reações.
- [Explosão de Dano](./damage.md#explosão-de-dano).

### Disputa

Uma Disputa acontece quando uma criatura reage a uma ação sua, como exemplo quando um inimigo tenta esquivar de um ataque seu. Caso você falhe na ação, não há necessidade da criatura reagir a sua ação, portanto não há disputa. Uma disputa pode ter quatro resultados para você: Falha, Sucesso Parcial, Sucesso Total ou Falha Crítica.

- **Sucesso Total:** A criatura alvo da sua ação <ins>falha</ins> no check da reação.
- **Sucesso Parcial:** A criatura alvo da sua ação tem <ins>sucesso</ins> no check da reação porém tira um valor <ins>maior</ins> que você.
- **Falha:** A criatura alvo da sua ação tem <ins>sucesso</ins> no check da reação e tira um valor <ins>menor</ins> que você.
- **Falha Crítica:** A criatura alvo da sua ação <ins>sucede criticamente</ins> no check da reação. Esse resultado acontece independente do valor que você tira no dado.

As consequências de ser parcialmente ou totalmente sucedido estarão descritas em cada ação/reação.

#### Patrulha e Vigia

Caso há criaturas ou sensores/equipamentos fazendo patrulha ou vigia no ambiente que você esteja tentando infiltrar, uma Disputa acontece entre vocês:

- **Você:** Realiza um check de Infiltração & Agilidade/Atenção
- **Patrulheiro/Vigia:** Realiza um check de Busca & Atenção

Os possíveis resultados e efeitos podem acontecer:

- **Sucesso Total:** Você consegue se infiltrar sem ser percebido.
- **Sucesso Parcial:** O patrulheiro/vigia possui uma ideia geral da presença de alguém e uma localização geral.
- **Falha:** O patrulheiro/vigia tem ideia da sua presença e sabem sua localização caso tenham linha de visão direta para você.

### Proteção

Durante um combate, muitas vezes você se encontra em uma posição desvantajosa, a melhor saída é buscar proteção atrás de uma parede ou qualquer outro objeto. Existem 3 tipos de nível de proteção e elas também são caracterizadas como condições. São elas:

| Proteção | Efeito                                                                                                |
| -------- | ----------------------------------------------------------------------------------------------------- |
| Parcial  | Ações contra você nesta condição são consideradas Difícil.                                            |
| Alta     | Ações contra você nesta condição são consideradas Muito Difícil.                                      |
| Total    | Ações não podem ser performadas diretamente contra você. <br>Efeitos em área ainda podem lhe atingir. |

### Terreno Alto

Quando você ataca alguém a distância a partir de um terreno alto, o check de ataque é considerado Fácil. É considerado terreno alto quando a diferença de altura do terreno entre você e a criatura é entre 2m e 10m.

### Terreno Difícil

Terrenos difíceis são áreas e superfícies difíceis de se locomover, transitar, podendo ser um lodo pegajoso, uma sala cheia de entulhos ou até um corpo de animal grande. Mover por Terreno Difícil custa o dobro de movimento, ou seja, se você possui uma velocidade de 30, conseguirá se mover somente 14m.
