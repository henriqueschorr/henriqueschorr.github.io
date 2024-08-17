# Checks

Quando um move for realizado em uma situação de perigo ou tensão, ou quando deve ser realizado com cuidado e atenção, um check será requisitado. Um check em HB consiste em rolar um dado do Atributo associado ao move e então verificar seu resultado. Um check sem disputa tem sua resolução definida puramente pelo seu próprio resultado do dado, sem definição de grau/valor de dificuldade a ser alcançado. Um check com disputa é comparado com o lado oposto.

Sempre é importante manter o resultado dos checks na "mesa" ou anotados em caso de [Ataques](./moves.md#ataques), pois eles também determinam o dano.

## Graus de Sucesso

|                 |  d6   |  d8   |  d10   |  d12   |
| --------------- | :---: | :---: | :----: | :----: |
| Falha           | 1 - 3 | 1 - 3 | 1 - 3  | 1 - 3  |
| Sucesso Parcial | 4 - 6 | 4 - 7 | 4 - 7  | 4 - 7  |
| Sucesso         |       |   8   | 8 - 10 | 8 - 11 |
| Sucesso Crítico |       |       |        |   12   |

## Resoluções

Abaixo segue os efeitos que as diferentes resoluções causam quando o check é realizado por um jogador que não seja o GM.

| Resultado       | Narrativa                                                                            | Mecânica                                                                                                                          |
| --------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------- |
| Sucesso Crítico | Você consegue o que quer e mais.                                                     | Você causa <ins>alto</ins> dano extra. Turno da Equipe.                                                                           |
| Sucesso         | Você consegue o que quer.                                                            | Você causa <ins>moderado</ins> dano extra. Turno da Equipe.                                                                       |
| Sucesso Parcial | Você consegue o que quer porém enfrenta alguma consequência leve.                    | Você causa <ins>baixo</ins> dano extra. Turno do GM caso gaste 3 [Terror](./resources.md#terror), caso contrário Turno da Equipe. |
| Falha           | Você não consegue o que quer e deve enfrentar consequências moderadas.               | Turno do GM caso desejar.                                                                                    |
<!-- | Falha Crítica   | Catástrofe. Você não consegue o que quer e deve enfrentar alguma consequência grave. | Equipe recebe Karma e GM recebe Terror. Turno do GM caso desejar.                                                                 | -->

Para informações sobre dano, veja [Calculando Dano](./damage.md#calculando-dano).

### Vantagem e Desvantagem

Certas situações, efeitos ou [Condições](./conditions.md) irão modificar o jeito que você realiza o check, lhe dando vantagem ou desvantagem.

**Vantagem:** Jogue dois dados e considere o dado com o <ins>maior</ins> valor.  
**Desvantagem:** Jogue dois dados e considere o dado com o <ins>menor</ins> valor.  

<!-- **Vantagem:** Use o <ins>maior</ins> valor entre seu dado principal e um dado caótico. Caso não possua dado caótico, role dois principais.  
**Desvantagem:** Use o <ins>menor</ins> valor entre seu dado principal e um dado caótico. Caso não possua dado caótico, role dois principais. -->

### Disputa

Uma disputa acontece quando você tenta realizar um move contra alguma criatura que irá reagir, como por exemplo, quando você ataca uma criatura e ela tenta esquivar, ou quando você tenta negociar um valor de um item com um vendedor. O mesmo vale quando você reage ao move de algum inimigo.  
Na disputa, ambos os lados irão rolar seu check e então comparar os resultados para determinar a resolução.

1. Se quem iniciou a disputa falhar, o outro lado vence automaticamente.
2. Se quem iniciou a disputa ter sucesso, compare o grau de sucesso entre os lados: Sucesso Crítico vence Sucesso, Sucesso vence Sucesso Parcial, Sucesso Parcial vence Falha, etc.
3. Se ambos tiverem o mesmo grau de sucesso, compare o valor dos dados. Quem possuir o maior vence.
<!-- 3. Se ambos tiverem o mesmo grau de sucesso, some o valor de todos os dados, incluindo os dados caóticos e então compare os valores. Vence aquele que tiver maior valor. -->

Para facilitar a resolução, sempre que houver uma disputa, informe seu grau de sucesso juntamente com a soma dos dados:  
"Eu tive Sucesso com 13".  
"Eu tive Sucesso Crítico com 6".

### Modificadores Situacionais

Algumas situações, acontecimentos ou características do ambiente podem alterar a forma que você realiza um check, ou forçar você a realizar um.

#### Ataque a distância com inimigos adjacentes

Quando você for realizar algum ataque com um arma que possua alcance maior que adjacente e houver criaturas adjacentes a você, o check é realizado com Desvantagem.

<!-- #### Terreno difícil

Escombros, pântanos e outras coisas podem tornar um terreno difícil de transversar. Caso seu personagem for mover para distância 3 em um terreno difícil, ele deve realizar um check de Agilidade, se falhar move apenas metade do caminho. Para mover para distâncias maiores que 3, o check de Agilidade deve ser realizado com Desvantagem. -->

### Checks Passivos

Nem sempre o GM irá lhe pedir para realizar checks para saber se seu personagem avista alguma armadilha, lembra de alguma informação ou sente algum perigo. Para isso existe os checks passivos, onde você não irá rolar dados, seu dado de atributo irá dizer automaticamente se você sucede ou não. Por exemplo, o GM pode ter marcado que para avistar uma armadilha, você deve ter um d10 em Atenção, caso você possua d10 ou um dado maior no atributo requisitado, você é bem sucedido e consegue avistar a armadilha, caso contrário, você falha no check passivo e avistará a armadilha somente se você ativamente pedir "Quero procurar por armadilhas", ou quando for tarde demais.