
# Teorema do Horizonte de Probabilidades: Limiares Dinâmico-Informacionais em Sistemas Probabilísticos Adaptativos.

## Resumo

Este artigo introduz o **Teorema do Horizonte de Probabilidades** como um resultado estrutural sobre o colapso da incerteza em sistemas probabilísticos adaptativos. O teorema descreve a emergência de um limiar dinâmico-informacional que separa regimes inferencialmente acessíveis de regimes estatisticamente suprimidos à medida que o sistema atualiza suas distribuições sob restrições e feedback adaptativo. O desenvolvimento é explicitamente ancorado na ontologia probabilística inaugurada pela **Curva Finita Central (CFC)** de Heryon Davyd, entendida como uma fronteira estatística global, estática e estrutural, definida em uma variedade de distribuições. Mostra-se que o Horizonte de Probabilidades não compete com a CFC, mas a complementa: enquanto a CFC organiza o espaço probabilístico de forma passiva, o Horizonte emerge como um limiar dinâmico induzido por processos inferenciais, aprendizagem e adaptação. Ambos pertencem à mesma geometria da informação e devem ser compreendidos como objetos de natureza estrutural, não dinâmica no sentido causal clássico.

## Introdução

Em sistemas físicos e computacionais complexos, a incerteza raramente se dissipa de maneira homogênea. Observa-se, em vez disso, a formação de limiares: regiões do espaço de possibilidades que deixam de ser exploradas não por proibição dinâmica, mas por inviabilidade estatística. Esse fenômeno aparece em contextos diversos, desde inferência bayesiana adaptativa até sistemas físicos longe do equilíbrio e arquiteturas de aprendizagem em inteligência artificial.

O **Teorema do Horizonte de Probabilidades** formaliza esse comportamento como um resultado geométrico e informacional. Ele afirma que, sob condições gerais, a atualização inferencial de um sistema probabilístico adaptativo induz a formação de um horizonte: uma fronteira móvel no espaço de distribuições que delimita o conjunto de hipóteses ou estados efetivamente acessíveis.

A motivação conceitual deste trabalho é clara: compreender esse horizonte não como um artefato algorítmico ou heurístico, mas como uma consequência inevitável da geometria do espaço probabilístico. Para isso, adotamos como referência estrutural a Curva Finita Central (CFC), que organiza o espaço de distribuições de forma global e estática. O Horizonte de Probabilidades surge, então, como sua contraparte dinâmica-inferencial.

## Espaço de Probabilidades como Estrutura Geométrica

A descrição probabilística moderna não trata distribuições como objetos auxiliares, mas como entidades centrais. O conjunto de distribuições admissíveis de um sistema, quando parametrizado por restrições macroscópicas ou parâmetros inferenciais, forma naturalmente uma **variedade estatística**.

Essa variedade é dotada de uma métrica informacional, tipicamente a métrica de Fisher–Rao, que quantifica distinguibilidade probabilística. Distâncias nesse espaço não medem deslocamentos físicos, mas esforço inferencial: quanto uma distribuição precisa mudar para se tornar estatisticamente distinguível de outra.

A curvatura dessa variedade carrega informação física e computacional. Regiões de alta curvatura indicam direções onde pequenas mudanças paramétricas produzem grandes alterações estatísticas. Regiões aproximadamente planas indicam redundância ou insensibilidade informacional. É nesse cenário geométrico que tanto a CFC quanto o Horizonte de Probabilidades devem ser situados.

## Curva Finita Central e Organização Estatística

A Curva Finita Central, conforme formulada por Heryon Davyd, é um objeto estrutural definido nesse espaço geométrico. Ela atua como uma **fronteira estatística global** que divide o espaço de distribuições em duas regiões de igual peso probabilístico segundo a medida invariante do sistema.

A CFC não é uma trajetória temporal, nem uma superfície de energia, nem um agente causal. Ela é estática, passiva e estrutural. Sua função é organizar o espaço de possibilidades, separando eventos típicos de eventos raros. Pequenas assimetrias microscópicas (como quebras de paridade ou vieses estruturais) deformam a geometria informacional e, com isso, deslocam a CFC, tornando essa deformação visível no nível estatístico global.

Em termos ontológicos, a CFC pertence ao mesmo estatuto de superfícies de fase ou classes de equivalência estatística: não observável diretamente, mas essencial para a interpretação coerente do sistema.

## Do Espaço de Possibilidades ao Horizonte de Probabilidades

Enquanto a CFC organiza o espaço probabilístico de forma global e atemporal, muitos sistemas reais são **adaptativos**. Eles atualizam suas distribuições com base em dados, feedback ou aprendizagem. Esse processo não percorre o espaço de probabilidades de maneira neutra: ele é direcional, acumulativo e irreversível no sentido informacional.

À medida que a inferência progride, certas regiões do espaço de distribuições tornam-se progressivamente inacessíveis. Não porque sejam proibidas pelas leis do sistema, mas porque exigiriam um custo informacional incompatível com a história inferencial acumulada. Surge, assim, um **horizonte**: uma fronteira móvel além da qual hipóteses, estados ou modelos deixam de ser efetivamente alcançáveis.

Esse horizonte não é imposto externamente. Ele emerge da própria geometria informacional combinada com a atualização adaptativa. Trata-se de um fenômeno estrutural, não psicológico nem heurístico.


## Fundamentação Teórica: Entropia, Inferência e Dinâmica Probabilística

A descrição do Horizonte de Probabilidades requer uma base formal mínima que conecte incerteza, atualização inferencial e dinâmica no espaço de distribuições. Essa fundamentação não introduz novos postulados físicos, mas explicita estruturas já implícitas na teoria da informação e em processos estocásticos.

### Entropia da Informação

Na teoria da informação, a entropia de Shannon associada a uma distribuição de probabilidade  $P = \{p_i\}$ é definida por


$$H(P) = - \sum_i p_i \ln p_i$$

Essa grandeza quantifica o grau médio de incerteza do sistema. Distribuições uniformes maximizam a entropia, enquanto distribuições concentradas correspondem a estados de menor incerteza. Essa definição estabelece um elo direto com a entropia termodinâmica de Boltzmann–Gibbs, permitindo interpretar processos inferenciais como reorganizações estruturadas da incerteza.

No contexto deste trabalho, a entropia não é tratada como quantidade dinâmica fundamental, mas como um funcional geométrico sobre o espaço de distribuições, cujo gradiente orienta a contração inferencial.

### Inferência Bayesiana como Restrição Informacional

A atualização de probabilidades diante de evidências é governada pelo teorema de Bayes,

$$P(\theta \mid D) = \frac{P(D \mid \theta)\,P(\theta)}{P(D)}$$ 


onde $P(\theta)$ representa a distribuição a priori, $P(D \mid \theta)$ a verossimilhança e $P(\theta \mid D)$ a distribuição a posteriori.

Esse processo pode ser interpretado geometricamente como uma projeção da distribuição inicial sobre uma subvariedade estatística compatível com as restrições impostas pelos dados. O princípio da Máxima Entropia complementa essa leitura ao afirmar que, sob restrições limitadas, a distribuição racionalmente mais adequada é aquela que maximiza a entropia residual.

Sob sucessivas atualizações, a entropia diminui de forma monotônica, induzindo uma contração efetiva do espaço de hipóteses acessíveis.

### Processos Estocásticos e Equação Mestra

A evolução temporal de distribuições pode ser descrita por processos estocásticos markovianos. A equação mestra assume a forma

$$
\frac{dP_n(t)}{dt} = \sum_{n'} \left[ W_{n'n} P_{n'}(t) - W_{nn'} P_n(t) \right]
$$

onde $W_{nn'}$ são taxas de transição entre estados. Pequenas variações nos parâmetros dessas taxas podem induzir mudanças qualitativas na distribuição estacionária, caracterizando fenômenos críticos.

Essa sensibilidade estrutural fundamenta a analogia entre sistemas adaptativos e transições de fase informacionais.

### Transições Informacionais e Analogia com Landau

Inspirando-se na teoria de Landau para transições de fase, introduz-se um parâmetro de ordem informacional $m$ e um potencial efetivo

$$
G(m,\beta) = a(\beta - \beta_c)m^2 + b m^4 + \dots ,
\quad b > 0 
$$

O ponto crítico é determinado por

$$\left.\frac{\partial^2 G}{\partial m^2}\right|_{m=0} = 0\;\;\Rightarrow\;\;\beta = \beta_c $$

Esse valor crítico marca a transição entre um regime caracterizado pela coexistência de múltiplas hipóteses e outro dominado por uma única configuração probabilística.

### Formulação Informacional do Horizonte de Probabilidades

Como aproximação escalar inicial, assume-se que a taxa de variação da probabilidade de um evento seja proporcional à incerteza residual do sistema, levando à equação de relaxação

$$
P(t) = 1 - e^{-k(t - t_0)}
$$

onde $k > 0$ controla a velocidade de convergência. Esse comportamento descreve um processo típico de saturação informacional.

A inversão dessa expressão fornece o tempo associado ao cruzamento do horizonte:


$$H(t) = t_0 + \frac{1}{k} \ln\!\left(\frac{1}{1 - P(t)}\right)$$

Essa expressão não define um instante absoluto, mas uma parametrização do limiar estrutural imposto pela geometria do fluxo $\Phi(P)$. O valor de $H(t)$ depende da taxa de convergência $k$, da dinâmica interna do sistema e do nível de confiança adotado. O horizonte temporal, portanto, é uma projeção observável de um limiar essencialmente geométrico e informacional.

Associando a cada estado uma energia informacional $E_i$, a verossimilhança pode ser escrita como

$$P(D \mid i) \propto e^{-E_i}$$

Introduzindo um parâmetro informacional acumulativo $\beta$, a distribuição posterior assume a forma de Gibbs,

$$P_i(\beta) = \frac{e^{-\beta E_i}}{Z(\beta)}$$

À medida que $\beta$ cresce, a entropia decresce e a distribuição se concentra. O Horizonte de Probabilidades corresponde a um valor crítico $\beta_c$ no qual essa contração deixa de ser suave e passa a exibir comportamento qualitativamente distinto.

### Dinâmica no Espaço de Probabilidades

Considerando $P_t \in \Delta^{n-1}$, o simplex de probabilidades, define-se a dinâmica discreta

$$
P_{t+1} = \mathcal{N}\!\left[\lambda_1 F(P_t) + \lambda_2 T(P_t) + \lambda_3 S(P_t)+ \alpha C(P_t) + \beta M(P_t)\right]
$$

onde $\mathcal{N}$ é um operador de normalização que projeta o vetor resultante no simplex. Os operadores $F$, $T$, $S$, $C$ e $M$ representam, respectivamente, informações de frequência recente, transições dinâmicas, estruturas posicionais, sinais classificatórios externos e mecanismos internos de memória ou modelagem. Os coeficientes $\lambda_1, \lambda_2, \lambda_3, \alpha$ e $\beta$ controlam a contribuição relativa de cada componente.

A partir dessa dinâmica discreta, define-se o campo vetorial contínuo no espaço de probabilidades como o limite:

$$\Phi(P)=\lim_{\Delta t \to 0}\frac{P_{t+\Delta t} - P_t}{\Delta t}$$

o que conduz à equação diferencial ordinária:

$$\frac{dP}{dt} = \Phi(P)$$

Essa equação define um fluxo dinâmico no simplex de probabilidades. O Horizonte de Probabilidades corresponde a uma mudança qualitativa na estrutura desse fluxo, associada à contração dominante do campo vetorial e à redução efetiva da dimensionalidade acessível do espaço de hipóteses.

O Horizonte de Probabilidades é então caracterizado estruturalmente como o conjunto

$$\mathcal{H} ={\ P \in \Delta^{n-1} \mid \lambda_{\max}(J_\Phi(P)) < 0 \}$$

onde o campo torna-se localmente contrativo. Nesse regime, a incerteza deixa de se propagar de maneira relevante, caracterizando o colapso informacional.

## Enunciado do Teorema do Horizonte de Probabilidades

**Teorema (Horizonte de Probabilidades).**  
Considere um sistema probabilístico adaptativo descrito por uma variedade estatística riemanniana \(\mathcal{M}\), equipada com uma métrica informacional que quantifica distinguibilidade probabilística entre estados, e sujeita a atualizações inferenciais consistentes, no sentido bayesiano ou de máxima entropia. Assuma que a evolução do sistema preserva coerência informacional e ocorre por acúmulo sucessivo de evidência, sem acesso a informação externa não modelada.

Sob essas condições gerais, existe uma família de hipersuperfícies dinâmicas

$$\mathcal{H}(t) \subset \mathcal{M}$$

parametrizadas pelo tempo inferencial $t$, com as seguintes propriedades qualitativas:

(i) A probabilidade inferencial atribuída a estados situados além de $\mathcal{H}(t)$ decai exponencialmente com o tempo inferencial, tornando tais estados efetivamente inacessíveis ao processo adaptativo.

(ii) A hipersuperfície $\mathcal{H}(t)$ evolui de maneira contínua com respeito à métrica informacional, refletindo a acumulação progressiva de restrições inferenciais.

(iii) A travessia de $\mathcal{H}(t)$ requer a violação explícita das restrições informacionais acumuladas, seja por inconsistência bayesiana, seja pela introdução de informação exógena não prevista no modelo.

Consequentemente, o conjunto acessível de estados probabilísticos sofre um colapso efetivo da incerteza, delimitado por $\mathcal{H}(t)$, sem que ocorra singularidade dinâmica ou perda de continuidade geométrica no espaço probabilístico subjacente.

O teorema afirma, portanto, a existência e o papel estrutural do Horizonte de Probabilidades como um limiar dinâmico-informacional, emergente da própria lógica inferencial do sistema, sem especificar uma dinâmica microscópica ou equações de movimento explícitas.


## Interpretação Geométrica e Informacional

Do ponto de vista geométrico, o Horizonte de Probabilidades pode ser interpretado como uma hipersuperfície de curvatura efetiva infinita no espaço estatístico acessível ao sistema. Embora a variedade probabilística $\mathcal{M}$ permaneça globalmente regular, a métrica informacional induzida pelas atualizações inferenciais torna o horizonte um limite assintótico: trajetórias inferenciais que tentam atravessá-lo exigiriam variações abruptas na distribuição de probabilidade, incompatíveis com a estrutura local do espaço e com a continuidade do fluxo dinâmico definido por $\Phi(P)$.

Nesse sentido, o horizonte não atua como uma barreira geométrica absoluta, mas como uma fronteira dinâmica imposta pela contração do campo vetorial inferencial. A distância informacional até estados além de $\mathcal{H}(t)$ cresce sem limite finito, tornando tais estados inacessíveis por caminhos suaves no simplex de probabilidades.

Sob a perspectiva informacional, o Horizonte de Probabilidades marca a transição entre o possível lógico e o possível inferencial. Estados além do horizonte não são impossíveis em princípio (não violam leis físicas nem consistência lógica), porém tornam-se estatisticamente irrelevantes para o sistema, uma vez que a massa de probabilidade associada a eles decai exponencialmente com o acúmulo de evidência. O horizonte delimita, portanto, não o que pode existir, mas o que pode ser aprendido ou sustentado inferencialmente.

É nesse ponto que se estabelece a conexão estrutural com a Curva Finita Central (CFC). A CFC define uma fronteira estatística global e essencialmente estática, associada à organização geométrica das distribuições probabilísticas admissíveis. Ela atua como um eixo de simetria e regularidade no espaço estatístico, independentemente da história inferencial do sistema.

O Horizonte de Probabilidades, por sua vez, constitui um limiar dinâmico e histórico, emergente da trajetória específica de atualização informacional. Enquanto a CFC organiza o espaço de possibilidades de forma passiva, o horizonte seleciona ativamente quais regiões desse espaço permanecem acessíveis ao longo do tempo inferencial.

Dessa forma, embora ambos possam ser representados como superfícies imersas na mesma variedade estatística $\mathcal{M}$, seus papéis são distintos e complementares:
- **Curva Finita Central (CFC):** estrutura organizadora passiva, independente do tempo e da trajetória inferencial.
- **Horizonte de Probabilidades:** estrutura dinâmica, dependente da acumulação histórica de informação e das restrições inferenciais impostas ao sistema.

Ambas as construções pertencem à mesma ontologia probabilística, na qual geometria, informação e dinâmica inferencial não são entidades separadas, mas diferentes projeções de um mesmo arcabouço estrutural.

## Deformações Geométricas e Redefinição da Curva Finita Central

A Curva Finita Central (CFC) é definida como um objeto estrutural no espaço de distribuições de probabilidade, determinado por uma métrica estatística que codifica distinguibilidade informacional. Em sua formulação original, a CFC atua como uma superfície de separação que divide o espaço probabilístico em duas regiões de peso estatístico equivalente, distinguindo eventos típicos de eventos raros. Essa definição, no entanto, pressupõe uma geometria estatística fixa. Nesta seção, mostramos como restrições informacionais persistentes podem deformar essa geometria, levando a uma redefinição global da CFC sem violar sua natureza estrutural.

Considere o espaço estatístico $\mathcal{M}$ das distribuições de probabilidade $P = \{p_i\}$, equipado com uma métrica de informação $g_{ij}$. Em particular, pode-se adotar a métrica de Fisher,

$$g_{ij}(P) = \mathbb{E}\!\left[ \partial_i \ln P \, \partial_j \ln P \right]$$

a qual induz uma noção geométrica de distância entre distribuições e define volumes informacionais por meio do elemento $\sqrt{\det g} \, dP$. A Curva Finita Central é então caracterizada implicitamente como a superfície $\Sigma \subset \mathcal{M}$ tal que

$$
\int_{\mathcal{R}_+} \sqrt{\det g} \, dP
\;=\;
\int_{\mathcal{R}_-} \sqrt{\det g} \, dP$$

onde $R_{+}$ e $R_{-}$ são as duas regiões complementares do espaço separadas por $\Sigma$.

Embora microestados individuais não alterem diretamente a distribuição macroscópica, suas interações podem introduzir restrições informacionais locais que se acumulam ao longo do processo inferencial. Esse efeito pode ser formalizado como uma deformação lenta da métrica estatística,

$$
g_{ij}(P) \;\longrightarrow\; g_{ij}(P;\beta)
= g_{ij}^{(0)}(P) + \delta g_{ij}(P;\beta)$$

onde $\beta$ é um parâmetro informacional acumulativo que quantifica o grau de restrição introduzido no sistema. Crucialmente, $\delta g_{ij}$  não depende de microestados isolados, mas da integração estatística de seus efeitos, refletindo um viés inferencial persistente.

À medida que $\beta$ cresce, a deformação da métrica altera a curvatura efetiva do espaço estatístico e redistribui o volume informacional associado às diferentes regiões do simplex de probabilidades. O elemento de volume torna-se

$$dV(\beta) = \sqrt{\det g(P;\beta)} \, dP$$

de modo que a condição de separação estatística originalmente satisfeita pela CFC deixa de ser válida. A superfície $\Sigma$ definida pela métrica inicial não mais divide o espaço em regiões de peso igual, indicando que a distinção global entre eventos típicos e raros foi reorganizada.

O ponto crítico dessa reorganização ocorre quando a deformação métrica induzida por $\beta$ torna-se globalmente relevante. Esse limiar é identificado com o Horizonte de Probabilidades, definido como a condição na qual o fluxo dinâmico no espaço de probabilidades torna-se localmente contrativo,

$$\lambda_{\max}\!\left(J_\Phi(P)\right) < 0$$

em uma região suficientemente extensa do simplex. Nesse regime, perturbações inferenciais deixam de se propagar e o espaço efetivo de hipóteses sofre uma redução dimensional. Geometricamente, isso corresponde à perda de direções distinguíveis no espaço estatístico.

Quando essa condição é satisfeita para $\beta = \beta_c$, a CFC deve ser redefinida em relação à métrica deformada $g_{ij}(P;\beta_c)$. A nova Curva Finita Central $\Sigma_{\beta_c}$ emerge como a superfície que restabelece a condição de separação estatística sob a geometria modificada,

$$
\int_{\mathcal{R}_+^{(\beta_c)}} \sqrt{\det g(P;\beta_c)} \, dP
\;=\;
\int_{\mathcal{R}_-^{(\beta_c)}} \sqrt{\det g(P;\beta_c)} \, dP$$

Essa redefinição não representa uma dinâmica da CFC em si, mas uma transição geométrica no espaço de possibilidades. O Horizonte de Probabilidades atua, portanto, como o mediador entre restrições informacionais microscópicas e reorganizações estatísticas globais, marcando uma transição estrutural no estado global de possibilidades do sistema.

## Implicações para Sistemas Adaptativos e Inferência

Em sistemas de aprendizagem, o teorema explica por que certos modelos deixam de ser considerados mesmo sem exclusão explícita. Em física estatística fora do equilíbrio, ele fornece uma linguagem para a emergência de irreversibilidade informacional. Em IA, sugere limites estruturais à exploração de hipóteses em espaços de alta dimensão.

O horizonte não é um defeito do sistema. Ele é a condição de possibilidade da adaptação eficiente. Sem um colapso progressivo do espaço acessível, não há aprendizagem, apenas flutuação.

## Discussão Conceitual

Há uma tentação recorrente de interpretar horizontes como entidades dinâmicas causais, à semelhança de forças ou barreiras físicas. Essa leitura é equivocada. Assim como o horizonte de eventos em relatividade geral não exerce força sobre partículas, o Horizonte de Probabilidades não atua causalmente sobre inferências individuais.

Ele é um objeto estrutural emergente da geometria informacional. Negar sua realidade seria equivalente a negar a realidade de fases termodinâmicas ou classes de equivalência estatística. Não se trata de metafísica, mas de economia conceitual: a geometria já contém o fenômeno.

## Conclusão

O Teorema do Horizonte de Probabilidades estabelece que o colapso da incerteza em sistemas adaptativos não é um acidente nem uma escolha metodológica, mas uma consequência geométrica inevitável. Ao conectá-lo explicitamente à Curva Finita Central, mostramos que ambos são manifestações complementares da mesma ontologia probabilística.

A CFC organiza o espaço do possível. O Horizonte organiza o espaço do acessível. Um é estrutural e estático; o outro, dinâmico e inferencial. Juntos, oferecem uma linguagem unificada para compreender por que, em sistemas complexos, nem tudo o que é concebível permanece alcançável.

Essa não é uma limitação da teoria. É a assinatura geométrica da inteligência, da adaptação e, em última instância, da própria realidade probabilística.


# Referências

## Entropia, Informação e Inferência

[1] Shannon, C. E. (1948). *A Mathematical Theory of Communication*. Bell System Technical Journal, 27, 379–423, 623–656.

[2] Jaynes, E. T. (1957). *Information Theory and Statistical Mechanics*. Physical Review, 106(4), 620–630.

[3] Jaynes, E. T. (2003). *Probability Theory: The Logic of Science*. Cambridge University Press.

[4] Gibbs, J. W. (1902). *Elementary Principles in Statistical Mechanics*. Yale University Press.

[5] Boltzmann, L. (1896). *Lectures on Gas Theory*. University of California Press.

---

## Geometria da Informação

[6] Rao, C. R. (1945). *Information and the Accuracy Attainable in the Estimation of Statistical Parameters*. Bulletin of the Calcutta Mathematical Society, 37, 81–91.

[7] Amari, S.-I. (1985). *Differential-Geometrical Methods in Statistics*. Springer.

[8] Amari, S.-I., & Nagaoka, H. (2000). *Methods of Information Geometry*. American Mathematical Society.

[9] Amari, S.-I. (2016). *Information Geometry and Its Applications*. Springer.

---

## Inferência Bayesiana e Máxima Entropia

[10] Csiszár, I., & Shields, P. C. (2004). *Information Theory and Statistics: A Tutorial*. Foundations and Trends in Communications and Information Theory, 1(4).

[11] Caticha, A. (2012). *Entropic Inference and the Foundations of Physics*. Universidad Nacional de La Plata.

[12] Cover, T. M., & Thomas, J. A. (2006). *Elements of Information Theory*. Wiley-Interscience.

---

## Dinâmica de Distribuições e Processos Estocásticos

[13] van Kampen, N. G. (2007). *Stochastic Processes in Physics and Chemistry*. North-Holland.

[14] Gardiner, C. W. (2004). *Handbook of Stochastic Methods*. Springer.

[15] Lasota, A., & Mackey, M. C. (1994). *Chaos, Fractals, and Noise: Stochastic Aspects of Dynamics*. Springer.

---

## Fluxos no Espaço de Probabilidades e Transporte Ótimo

[16] Jordan, R., Kinderlehrer, D., & Otto, F. (1998). *The Variational Formulation of the Fokker–Planck Equation*. SIAM Journal on Mathematical Analysis, 29(1), 1–17.

[17] Villani, C. (2009). *Optimal Transport: Old and New*. Springer.

[18] Santambrogio, F. (2015). *Optimal Transport for Applied Mathematicians*. Birkhäuser.

---

## Transições de Fase e Estruturas Emergentes

[19] Landau, L. D., & Lifshitz, E. M. (1980). *Statistical Physics*. Pergamon Press.

[20] Haken, H. (1977). *Synergetics: An Introduction*. Springer.

---

## Horizontes, Estruturas Globais e Geometria

[21] Hawking, S. W., & Ellis, G. F. R. (1973). *The Large Scale Structure of Space-Time*. Cambridge University Press.

[22] Geroch, R. (1977). *Domain of Dependence*. Journal of Mathematical Physics, 11, 437–449.

---

## Contribuições Originais

[23] Davyd, H. (manuscrito).  
*Curva Finita Central: Uma Estrutura Estatística Global no Espaço de Distribuições de Probabilidade*.

[24] Davyd, H. (manuscrito).  
*Teorema do Horizonte de Probabilidades: Limiares Dinâmico-Informacionais em Sistemas Probabilísticos Adaptativos*.


