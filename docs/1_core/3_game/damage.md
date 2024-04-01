## Dano

Quando você ter sucesso em um check de ataque contra um alvo, você irá **rolar dano** para determinar quanto dano e quantas Feridas você infringirá no alvo.

Os dados que você precisará rolar estarão descritos no armamento ou na habilidade que você usou durante o ataque. Além disso dados caóticos também podem influenciar no dano.

### Calculando Dano

Para calcular o dano você rolará o(s) dado(s) informados no armamento ou habilidade que você usou no ataque, e somará ou não o valor dos dados caóticos dependendo seu grau de sucesso. Para facilitar a leitura vamos chamar os dados do armamento/habilidade como dados da fonte.

**Sucesso Parcial** dados da fonte + <ins>menor</ins> valor rolado em um dado caótico.  
**Sucesso** dados da fonte + <ins>maior</ins> valor rolado em um dado caótico.  
**Sucesso Crítico** dados da fonte + valor de <ins>todos os dados</ins> caóticos + [efeito crítico](#tipos-de-dano-e-efeitos-críticos) do tipo de dano.  
<!-- **Explosão: Dado Caótico com maior valor possível** você soma o valor do dado caótico e rola ele novamente, somando o novo valor. Caso seja o maior valor possível, você rola ele novamente e assim segue o ciclo. -->

Em caso de Sucesso Crítico, verifique o efeito crítico de cada [tipo de dano](#tipos-de-dano-e-efeitos-críticos).

#### Exemplo de cálculo de Dano

Remella tenta realizar um ataque com seu Humano Batedor, Beck, contra um dos guardas a sua frente. Beck rola 3d8 que é a quantidade de dados de seu atributo. Seu armamento causa 1d6 de dano.

Abaixo segue como é calculado o dano para cada grau de sucesso:

**Sucesso Parcial**
Remella rola 1d6 que é o dano do armamento, tirando um 3. Remella verifica seu dado caótico com <ins>menor</ins> valor, que é 2, e soma-o ao dano total. Beck causa 5 de dano no alvo.

**Sucesso**
Remella rola 1d6 que é o dano do armamento, tirando um 3. Remella verifica seu dado caótico com <ins>maior</ins> valor, que é 6, e soma-o ao dano total. Beck causa 9 de dano no alvo.

**Sucesso Crítico**
Remella rola 1d6 que é o dano do armamento, tirando um 3. Remella verifica o valor de <ins>todos os dados caóticos</ins>, que é 2 e 6, e soma-os ao dano total. Beck causa 11 de dano no alvo.

<!-- **Explosão**
Remella teve qualquer nível de sucesso e percebe que tirou 8 em um de seus dados caóticos, sendo o maior valor possível de 1d8, isso lhe concede explosão de dano.

Remella rola 1d6 que é o dano do armamento, tirando um 3. Remella verifica o valor de <ins>todos os dados caóticos</ins>, que é 2 e 8, e soma-os ao dano total. Até agora temos 11 de dano, mas Remella pode rolar o dado com valor 8 novamente e somar o novo valor ao dano. Remella rola o dado e tira 4. Beck causa 15 de dano no alvo. -->

### Dano Dinâmico

Você verá em algumas habilidades, armamentos, equipamentos ou qualquer outro item que cause dano, algumas frases entre sinais de maior/menor: <>. Isto serve para indicar formas de calcular o dano dinamicamente, geralmente para acompanhar a progressão do seu personagem e ameaça das criaturas. Os exemplos mais comuns são:

**< Xd Atributo>:** Indica que você deve rolar X dados do atributo informado. Por exemplo <3d Físico> indica que você deve rolar 3 dados Físico para calcular o dano.  
**< seu nível>:** Indica que você deve somar o seu nível ao dano. Por exemplo, se você estiver nível 3, você soma 3 ao dano.

### Tipos de Dano e Efeitos Críticos

Em BTH temos diversos tipos de dano e cada um deles possui seu efeito crítico. Este efeito acontece sempre que o resultado de um check de ataque seja Sucesso Crítico. Quando um ataque possui mais de um tipo de dano, o jogador que realizou o ataque escolhe apenas um dos efeitos críticos para ser aplicado ao alvo.

| Dano    | Efeito Crítico                                  | Exemplos                                                                                                                                          |
| ------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Físico  | + maior valor possível do dado caótico ao dano. | Basicamente qualquer lâmina ou arma que lança projéteis são exemplos de dano físico.                                                              |
| Químico | Debilitado 2 ou Dano Persistente 2.             | Fogo, gelo, ácido e veneno são exemplos de dano químico.                                                                                          |
| Energia | Debilitado 2.                                   | Descarga elétrica ou radiação são exemplos de dano energia.                                                                                       |
| Neural  | Incapacitado 1.                                 | Alguns ataques podem causar dano direto na mente, sistema nervoso ou algum sentido. Este tipo de dano geralmente causa dano em forma de Stress. |

## Resiliência

Algumas criaturas possuem algum tipo de resiliência, ou falta dele, que influenciam diretamente ao dano.

**Resistência**  
Quando uma criatura possui resistência a um tipo de dano, ela receberá 1 dano de AP/Ferida a menos de ataques daquele tipo. Por exemplo, você recebe dano severo do tipo químico, mas você possui resistência a químico, portanto recebe 2 de dano ao AP/Ferida em vez de 3. Resistência não interfere nada no efeito crítico e você nunca tomará menos de 1 de dano.

**Imunidade**  
Uma criatura com imunidade não recebe dano do tipo de dano que possui imunidade. Também não será afetada pelo efeito crítico.

**Vulnerabilidade**  
Exatamente o oposto de Resistência. Uma criatura com vulnerabilidade a um tipo de dano receberá 1 dano de AP/Ferida a mais de ataques daquele tipo. Por exemplo, você recebe dano severo do tipo químico, e você possui vulnerabilidade a químico, portanto recebe 4 de dano ao AP/Ferida em vez de 3. Vulnerabilidade não interfere nada no efeito crítico.
