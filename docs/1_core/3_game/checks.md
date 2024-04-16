Quando uma ação/reação for realizada em uma situação de perigo ou tensão, ou quando esta deve ser realizada com cuidado e atenção, um check será requisitado. Um check em HB consiste em rolar um dado do Atributo associado a ação e então verificar seu resultado. Um check sem disputa tem sua resolução definida puramente pelo seu próprio resultado do dado, sem definição de grau/valor de dificuldade a ser alcançado. Um check com disputa é comparado com o lado oposto.

Checks também podem ser modificados por [dados caóticos](#dados-caóticos), [conhecimento](actions.md#ações-com-ciência), [condições](./conditions.md) e outros efeitos situacionais.

Sempre é importante manter o resultado dos checks na "mesa" ou anotados em caso de [Ataques](./actions.md#ataques), pois eles também determinando o dano.

#### Resultados

|                 |  d6   |  d8   |  d10   |  d12   |
| --------------- | :---: | :---: | :----: | :----: |
| Falha           | 1 - 3 | 1 - 3 | 1 - 3  | 1 - 3  |
| Sucesso Parcial | 4 - 6 | 4 - 7 | 4 - 7  | 4 - 7  |
| Sucesso         |       |   8   | 8 - 10 | 8 - 11 |
| Sucesso Crítico |       |       |        |   12   |

**Falha Crítica**  
Pode acontecer somente quando [Dados Caóticos](#dados-caóticos) são introduzidos ao check.  
Falha Crítica acontece quando você <ins>falha</ins> no check e <ins>ao menos 1 de seus dados caóticos</ins> rola o mesmo número do dado principal.

### Resoluções

Abaixo segue os efeitos que as diferentes resoluções causam quando o check é realizado por um jogador que não seja o GM.

| Resultado       | Narrativa                                                                            | Mecânica                                                                                                                          |
| --------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------- |
| Sucesso Crítico | Você consegue o que quer e mais.                                                     | Você causa <ins>alto</ins> dano extra. Turno da Equipe.                                                                           |
| Sucesso         | Você consegue o que quer.                                                            | Você causa <ins>moderado</ins> dano extra. Turno da Equipe.                                                                       |
| Sucesso Parcial | Você consegue o que quer porém enfrenta alguma consequência leve.                    | Você causa <ins>baixo</ins> dano extra. Turno do GM caso gaste 3 [Terror](./resources.md#terror), caso contrário Turno da Equipe. |
| Falha           | Você não consegue o que quer e deve enfrentar consequências moderadas.               | Equipe recebe Karma. Turno do GM caso desejar.                                                                                    |
| Falha Crítica   | Catástrofe. Você não consegue o que quer e deve enfrentar alguma consequência grave. | Equipe recebe Karma e GM recebe Terror. Turno do GM caso desejar.                                                                 |

Para informações sobre dano, veja [Calculando Dano](./damage.md#calculando-dano).

### Exemplo de Check

_Remella está tentando abrir uma fechadura digital de uma porta mexendo em seus componentes. O GM diz para Remella fazer um check com Controle e que envolve o conhecimento de Engenharia. Remella possui conhecimento em Engenharia, portanto o check será realizado normalmente, sem vantagem. Remella possui d12 em Controle._

Abaixo segue as possíveis resoluções para esse evento:

**Sucesso Crítico**  
_Remella rola 12 no d12 atribuido a Controle, o que representa um sucesso crítico! Remella escuta o som de guardas atrás da porta e aguarda eles se afastarem. Remella consegue desativar a fechadura digital e abrir a porta silenciosamente. O GM dá a opção a Remella de atacar um dos guardas usando o mesmo resultado de check ou passar despercebido para a próxima sala._  
O turno continua com a equipe de jogadores.

**Sucesso**  
_Remella rola 8, o que representa um sucesso. Remella escuta o som de guardas atrás da porta e aguarda eles se afastarem. Remella consegue desativar a fechadura digital e abrir a porta silenciosamente._  
O turno continua com a equipe de jogadores.

**Sucesso Parcial**  
_Remella rola 6, o que representa um sucesso parcial. Remella escuta o som de guardas atrás da porta e aguarda eles se afastarem. Remella consegue desativar a fechadura digital porém faz barulho ao abrir a porta, chamando a atenção dos guardas._  
GM pode gastar 3 [Terror](./resources.md#terror) para ter seu turno, caso contrário o Turno da Equipe continua.

**Falha**  
_Remella rola 2, o que representa uma falha. Remella não consegue desativar a fechadura digital._    
Equipe recebe Karma e é Turno do GM caso ele desejar.

**Falha Crítica**  
_Este resultado não poderia acontecer sem dados caóticos, mas vamos fingir que seja possível._  
_Remella rola uma falha crítica. Remella não consegue desativar a fechadura digital e ainda toma um choque, recebendo dano. Além disso um alarme toca, avisando de sua presença aos guardas._  
Equipe recebe Karma, GM recebe Terror e é o turno dele caso desejar.

### Vantagem e Desvantagem

Certas situações, efeitos ou [Condições](./conditions.md) irão modificar o jeito que você realiza o check, lhe dando vantagem ou desvantagem.

**Vantagem:** Use o <ins>maior</ins> valor entre seu dado principal e um dado caótico. Caso não possua dado caótico, role dois principais.  
**Desvantagem:** Use o <ins>menor</ins> valor entre seu dado principal e um dado caótico. Caso não possua dado caótico, role dois principais.

### Dados Caóticos

Ao abrir Portões do Caos de um Atributo, além de receber outros benefícios, você recebe Dados Caóticos para rolar junto com os checks daquele atributo. Você pode ter no máximo dois dados caóticos para cada atributo.  
Estes dados influenciam tanto nos seus checks quanto no cálculo de dano.

**Check**

- Caso você tenha qualquer grau de <ins>sucesso</ins> no check e role o mesmo número em ao menos um de seus dados caóticos, o resultado do check é <ins>sucesso crítico</ins>.
<!-- - Caso você tenha <ins>sucesso crítico</ins> no check e role o mesmo número em ao menos um de seus dados caóticos, o resultado do check é <ins>explosão</ins>. -->
- Caso você tenha qualquer grau de <ins>falha</ins> no check e role o mesmo número em ao menos um de seus dados caóticos, o resultado do check é <ins>falha crítica</ins>.
- Em caso de disputa, some o valor dos dados caóticos ao valor do dado principal para equiparar os resultados e determinar a resolução.

**Dano**

- Caso você tenha <ins>sucesso parcial</ins> no check, adicione o <ins>menor</ins> valor entre os dados caóticos ao dano.
- Caso você tenha <ins>sucesso</ins> no check, adicione o <ins>maior</ins> valor entre os dados caóticos ao dano.
- Caso você tenha <ins>sucesso crítico</ins> no check, adicione o valor de <ins>todos os dados</ins> caóticos ao dano.
<!-- - Caso você tenha <ins>qualquer tipo de sucesso</ins> e role o maior número possível no dado caótico, você irá somar aquele valor e rolar o dado novamente, somando o novo valor. Caso você role o maior valor possível de novo, você rola ele novamente e assim segue o ciclo. -->

### Disputa

Uma disputa acontece quando você tenta realizar uma ação contra alguma criatura que irá reagir, como por exemplo, quando você ataca uma criatura e ela esquiva, ou quando você tenta negociar um valor de um item e o vendedor considera se será persuadido ou não. O mesmo vale quando você reage a ação de algum inimigo.  
Na disputa ambos os lados irão rolar seu check e então comparar os resultados para determinar a resolução.

1. Se quem iniciou a disputa falhar, o outro lado automaticamente vence.
2. Se quem iniciou a disputa ter sucesso, compare o grau de sucesso entre os lados: Sucesso Crítico vence Sucesso, Sucesso vence Sucesso Parcial, Sucesso Parcial vence Falha, etc.
3. Se ambos tiverem o mesmo grau de sucesso, some o valor de todos os dados, incluindo os dados caóticos e então compare os valores. Vence aquele que tiver maior valor.

Para facilitar a resolução sempre que houver uma disputa, informe seu grau de sucesso juntamente com a soma dos dados:  
"Eu tive Sucesso com 13".  
"Eu tive Sucesso Crítico com 6".

### Modificadores Situacionais

Algumas situações, acontecimentos ou características do ambiente podem alterar a forma que você realiza um check, ou forçar você realizar um check.

#### Ataque a distância com inimigos adjacentes

Quando você for realizar algum ataque com um arma que possua alcance maior que adjacente e houver criaturas adjacentes a você, o check é realizado com Desvantagem.

#### Terreno difícil

Escombros, pântanos e outras coisas podem tornar um terreno difícil de transversar. Caso seu personagem for mover para uma distância Muito Perto em um terreno difícil, ele deve realizar um check de Agilidade, se falhar move apenas metade do caminho. Para mover para distâncias Perto ou maior, o check de Agilidade deve ser realizado com Desvantagem.

### Checks Passivos

Nem sempre o GM irá lhe pedir para realizar checks para saber se seu personagem avista alguma armadilha, lembra de alguma informação ou sente algum perigo. Para isso existe os checks passivos, onde você não irá rolar dados, seu dado de atributo irá dizer automaticamente se você sucede ou não. Por exemplo, o GM pode ter marcado que para avistar uma armadilha, você deve ter um d10 em Atenção, caso você possua d10 ou um dado maior no atributo requisitado, você é bem sucedido e consegue avistar a armadilha, caso contrário, você falha no check passivo e avistará a armadilha somente se você ativamente pedir "Quero procurar por armadilhas", ou quando for tarde demais.
