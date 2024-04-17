## Dano

Quando você ter sucesso em um [Check](./checks.md) de [Ataque](./actions.md#ataques) contra um alvo, você irá utilizar os mesmos dados do check para determinar quanto dano e quantas Feridas você infringirá no alvo, ou AP caso ele possua. Algumas Habilidades ou Propriedades de armas podem modificar o dano.

### Calculando Dano

Após rolar o Check e determinar que você irá causar de fato dano no alvo, calcule o dano de acordo com o grau de sucesso.

**Sucesso Parcial:** <ins>Maior</ins> valor rolado no check.  
**Sucesso:** <ins>Soma</ins> dos 2 <ins>maiores</ins> valores rolado no check.  
**Sucesso Crítico:** <ins>Soma</ins> dos 3 <ins>maiores</ins> valores rolado no check + [efeito crítico](#tipos-de-dano-e-efeitos-críticos) do tipo de dano.

<!-- **Explosão: Dado Caótico com maior valor possível** você soma o valor do dado caótico e rola ele novamente, somando o novo valor. Caso seja o maior valor possível, você rola ele novamente e assim segue o ciclo. -->

#### Exemplo de cálculo de Dano

_Remella tenta realizar um ataque contra um dos guardas a sua frente. Remella rola 3d12 que é a quantidade de dados de seu atributo, sendo um o Dado Principal e os outros dois os Dado Caóticos._

Abaixo segue como é calculado o dano para cada grau de sucesso:

**Falha ou Falha Crítica**  
_Remella erra o ataque e não causa dano algum._

**Sucesso Parcial**  
_Remella tira 5 no seu Dado Principal, 3 e 2 nos Dados Caóticos. Remella causa 5 de dano no alvo._  
_Remella tira 5 no seu Dado Principal, 8 e 2 nos Dados Caóticos. Remella causa 8 de dano no alvo._

**Sucesso**  
_Remella tira 10 no seu Dado Principal, 3 e 2 nos Dados Caóticos. Remella causa 13 de dano no alvo._  
_Remella tira 10 no seu Dado Principal, 8 e 2 nos Dados Caóticos. Remella causa 18 de dano no alvo._

**Sucesso Crítico**  
_Remella tira 12 no seu Dado Principal, 3 e 2 nos Dados Caóticos. Remella causa 15 de dano no alvo mais o [efeito crítico](#tipos-de-dano-e-efeitos-críticos) do tipo de dano._  
_Remella tira 12 no seu Dado Principal, 8 e 2 nos Dados Caóticos. Remella causa 20 de dano no alvo mais o [efeito crítico](#tipos-de-dano-e-efeitos-críticos) do tipo de dano._

<!-- **Explosão**
Remella teve qualquer nível de sucesso e percebe que tirou 8 em um de seus dados caóticos, sendo o maior valor possível de 1d8, isso lhe concede explosão de dano.

Remella rola 1d6 que é o dano da arma, tirando um 3. Remella verifica o valor de <ins>todos os dados caóticos</ins>, que é 2 e 8, e soma-os ao dano total. Até agora temos 11 de dano, mas Remella pode rolar o dado com valor 8 novamente e somar o novo valor ao dano. Remella rola o dado e tira 4. Beck causa 15 de dano no alvo. -->

### Dano Dinâmico

Você verá em algumas habilidades, armas, equipamentos ou qualquer outro item que cause dano, algumas frases entre sinais de maior/menor: <>. Isto serve para indicar formas de calcular o dano dinamicamente, geralmente para acompanhar a progressão do seu personagem e ameaça das criaturas. Os exemplos mais comuns são:

**< Xd Atributo>:** Indica que você deve rolar X dados do atributo informado. Por exemplo <3d Físico> indica que você deve rolar 3 dados Físico para calcular o dano.  
**< seu nível>:** Indica que você deve somar o seu nível ao dano. Por exemplo, se você estiver nível 3, você soma 3 ao dano.

### Tipos de Dano e Efeitos Críticos

Em HB temos diversos tipos de dano e cada um deles possui seu efeito crítico. Este efeito acontece sempre que o resultado de um check de ataque seja Sucesso Crítico. Quando um ataque possui mais de um tipo de dano, o jogador que realizou o ataque escolhe apenas um dos efeitos críticos para ser aplicado ao alvo.

| Dano    | Efeito Crítico                                      | Exemplos                                                                                                                                        |
| ------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Físico  | + maior valor possível do dado do atributo ao dano. | Basicamente qualquer lâmina ou arma que lança projéteis são exemplos de dano físico.                                                            |
| Químico | Debilitado 2 ou Dano Persistente 2.                 | Fogo, gelo, ácido e veneno são exemplos de dano químico.                                                                                        |
| Energia | Debilitado 2.                                       | Descarga elétrica ou radiação são exemplos de dano energia.                                                                                     |
| Neural  | Incapacitado 1.                                     | Alguns ataques podem causar dano direto na mente, sistema nervoso ou algum sentido. Este tipo de dano geralmente causa dano em forma de Stress. |

## Resiliência

Algumas criaturas possuem algum tipo de resiliência, ou falta dele, que influenciam diretamente ao dano.

**Resistência**  
Quando uma criatura possui resistência a um tipo de dano, ela receberá 1 dano de AP/Ferida a menos de ataques daquele tipo. Por exemplo, você recebe dano severo do tipo químico, mas você possui resistência a químico, portanto recebe 2 de dano ao AP/Ferida em vez de 3. Resistência não interfere nada no efeito crítico e você nunca tomará menos de 1 de dano.

**Imunidade**  
Uma criatura com imunidade não recebe dano do tipo de dano que possui imunidade. Também não será afetada pelo efeito crítico.

**Vulnerabilidade**  
Exatamente o oposto de Resistência. Uma criatura com vulnerabilidade a um tipo de dano receberá 1 dano de AP/Ferida a mais de ataques daquele tipo. Por exemplo, você recebe dano severo do tipo químico, e você possui vulnerabilidade a químico, portanto recebe 4 de dano ao AP/Ferida em vez de 3. Vulnerabilidade não interfere nada no efeito crítico.
