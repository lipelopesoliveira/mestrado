---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Novos Alótropos de Carbono: ABF-Carbon

## ABF-Carbon

```{figure} fig/Figura_2.gif
```

Tomando com base o motivo estrutural explorado no alótropo de carbono da seção anterior, o motivo **spiro**, podemos conceber uma miríade de outras estruturas. Poderíamos, por exemplo, utilizar a estratégia de inserir unidades de acetileno entre as unidades spiro, formando estruturas conjugadas com poros progressivamente maiores como explorado em {cite}`costa2018n`. Por outro lado, é possível conectar o motivo estrutural diretamente a átomos de carbono *sp*<sup>3</sup>, formando estruturas porosas semelhantes ao Spiro-Carbon, porém sem a conjugação entre as ligações duplas, gerando um potencial alótropo de carbono 3D semi-condutor. Essa estrutura hipotética será explorada ao longo dessa próxima seção

### Estrutura

Essa estrutura idealizada, que pode representada por uma rede 3D do tipo [abf](http://rcsr.anu.edu.au/nets/abf\#) e por isso será nomeada como ABF-Carbon, apresenta 6 átomos em uma célula unitária primitiva tetragonal de corpo centrado, com grupo espacial $I\bar{4}m2$ (\#119) e grupo pontual $D_{2d}^{11}$. A geometria de equilíbrio obtida a partir da otimização completa da estrutura apresenta parâmetros de célula *a* = *b* = 3.811 Å, *c* = 8.726 Å e $\alpha$ = $\beta$ = $\gamma$ = 90$^\circ$, apresentando densidade de 1.89 g/cm$^3$. A célula unitária primitiva e convencional resultante é apresentada na {numref}`structure_homospiro`.

```{figure} fig/structure.png
:name: structure_homospiro

Representação da célula unitária do ABF-Spiro vista na direção dos vetores a) **a**, b) **b**, c) **c**, d) representação de célula primitiva e e). Representação da estrutura atômica da célula unitária tetragonal para o ABF-Carbon, com os átomos não equivalentes destacados em cores diferentes.
```

Baseado na simetria do grupo espacial desta estrutura os três átomos não equivalentes ocupam os sítios de Wyckoff *8i*, *2a* e *2d*, como representado na {numref}`structure_homospiro`-e). O átomo **C1** (verde) ocupa o sítio 8i e apresenta coordenadas fracionárias (0.00000, 0.00000, 0.00000), **C2** (amarelo) ocupa o sítio 2a e apresenta coordenadas (0.82651, 0.00000, 0.15266) e **C3** (azul) ocupa o sítio 2d apresentando coordenadas (0.00000, 0.50000, 0.75000). Baseado na estrutura otimizada é possível distinguir três diferentes tipos de ligação: *i)* As ligações do átomo $sp^3$ da unidade *spiro* com seus vizinhos (C1-C2) com comprimento iguais de 1.487 Å; *ii)* as ligações entre os átomos **C2** (C2=C2), com comprimento de 1.322 Å, fechando o anel de 3 membros e formando a unidade spiro; *iii)* as ligações das unidades *spiro* com o átomo de carbono $sp^3$ (**C3**), com comprimento de 1.506 \AA, comprimento típico de ligação simples entre átomos de carbono.
		
Os ângulos internos da unidade *spiro* são de 52.8$^\circ$ (C2-C1-C2) e 63.6$^\circ$ (C1-C2-C2), valores iguais aos apresentados pelo análogo molecular spiropentadieno. Os ângulos das ligações do átomo de carbono **C3** apresentam um leve desvio do padrão para um tetraedro perfeito, de 109.5$^\circ$, apresentando valores de 111.4$^\circ$ e 108.5$^\circ$.     
		
É possível observar que nessa estrutura que os comprimentos e ângulos das ligações na unidade *spiro* se assemelham muito mais ao seu análogo molecular, o spiropentadieno, do que na estrutura do Spiro-Carbon. Isso se dá pelo fato de que, nessa estrutura, as unidades *spiro* estão ligadas diretamente a átomos de carbono $sp^3$, o que impede que ocorra a conjugação entre as ligações duplas e fazendo que as ocorra uma localização maior das ligações duplas e simples. Isso nos permite antecipar que essa estrutura apresentará um caráter semi-condutor com *band gap* relativamente grande, devido à dificuldade de interação entre os orbitais $\pi$. 
		
### Estabilidade Relativa e Propriedades Mecânicas

Para investigar a estabilidade relativa desta estrutura, foi calculada a dispersão de fônons ao longo de um caminho entre pontos de alta simetria na primeira zona de Brillouin {cite}`bradley2010mathematical`. Como pode ser observado na {numref}`ph_DOS-2`-*a)* não há a presença de nenhuma frequência imaginária, indicando que a estrutura do ABF-Carbon corresponde a um mínimo na superfície de potencial. 

```{figure} fig/cohesive_abf-carbon.svg
:name: ph_DOS-2

(a) Gráfico da dispersão de fônons ao longo de alguns pontos de alta simetria na primeira zona de Brillouin e a correspondente densidade de estados vibracionais (VDOS) para o ABF-Carbon. (b) Energia coesiva por átomo em função do volume ($E_c(V)$) por átomo para diferentes alótropos de carbono. (c) Energia potencial em função do tempo de simulação e snapshots selecionados em 2 e 20 ps para uma Dinâmica Molecular *ab-initio* do tipo Born-Oppenheimer à 900K. 
```

Para avaliar a estabilidade termodinâmica relativa do ABF-Carbon, a {numref}`ph_DOS-2`-*b)* mostra a variação da energia coesiva em função do volume (ambos por átomo) para diferentes alótropos de carbono. Como esperado, a curva $E_c(V)$ para o ABF-Carbon apresenta claramente um mínimo correspondente ao estado meta-estável desta estrutura. Assim como o Spiro-Carbon, esta estrutura se mostrou mais estável do que outros alótropos de carbono tridimensionais  como  1-diamantino/Y-Carbon {cite}`costa2018n,li2014modulated` por aproximadamente 1.55 kcal/mol (0.07 eV) por átomo e o T-Carbon {cite}`sheng2011t` por aproximadamente 5.1 kcal/mol (0.22 eV), como mostrado na {numref}`energy-abf`. 
		
Curiosamente o ABF-Carbon apresentou energia coesiva cerca de 1.0 kcal/mol (0.05 eV) menor do que o Spiro-Carbon. Em geral, é esperado que uma estrutura que apresente mais átomos de carbono com hibridização $sp^3$ apresente maior estabilidade, entretanto, o ABF-Carbon mesmo apresentando uma razão de átomos $sp^2$/$sp^3$ de 2/1, valor menor do que o apresentado pelo Spiro-Carbon de 4/1, apresenta menor energia de formação. Este fenômeno é bastante incomum, e pode ter uma relação direta com o fato de o grafite possuir energia coesiva maior do que o diamante. Talvez a deslocalização gerada pela formação de ligações $\pi$ conjugadas, como acontece no grafite e no Spiro-Carbon, seja um fator estabilizante maior do que a sobreposição frontal dos orbitais gerada pela formação das ligações $\sigma$ em estruturas como a do diamante e do ABF-Carbon. Esse fenômeno ainda não apresenta uma resposta conclusiva na literatura, e pesquisas mais aprofundadas devem ser feitas para tentar explicar esse resultado contra-intuitivo. 

```{list-table} Módulo das energias relativa e coesiva por átomo para o ABF-Carbon comparado com diferentes alótropos de carbono.
:header-rows: 1
:name: energy-abf


* - Estrutura
  - Energia Relativa (ev/átomo)
  - Energia Relativa (kcal/mol/átom)
  - Energia Coesiva (ev/átomo)
  - Energia Coesiva (kcal/mol/átomo)
* - Grafite
  - 0.000
  - 0.00
  - 7.856
  - 181.16
* - Diamante
  - 0.112
  - 2.57
  - 7.744
  - 178.59
* - Spiro-Carbon
  - 1.079
  - 24.88
  - 6.777
  - 156.29
* - Carbino
  - 1.106
  - 25.50
  - 6.750
  - 155.67
* - ABF-Carbon
  - 1.121
  - 25.86
  - 6.735
  - 155.30
* - Y Carbon
  - 1.189
  - 27.41
  - 6.667
  - 153.75
* - Y-II Carbon
  - 1.177
  - 27.15
  - 6.679
  - 154.01
* - T Carbon
  - 1.342
  - 30.94
  - 6.514
  - 150.22 
* - T-II Carbon
  - 1.554
  - 35.84
  - 6.302
  - 145.32
  ```

Avaliando as seis constantes elásticas ($\textbf{C}_{ij}$ em GPa) calculadas, apresentadas na {numref}`elastic_ABF`, é fácil ver que as condições necessárias e suficientes que devem ser satisfeitas, baseadas nos critérios de estabilidade de Born {cite}`born1940stability`, para garantir a estabilidade mecânica para uma rede tetragonal são satisfeitos pelo ABF-Carbon, indicando que essa nova estrutura proposta é mecanicamente estável. 


A {numref}`elastic_ABF` mostra os gráficos da dependência espacial nos planos **xy**, **xz** e **yz** para os módulos de Young (*E*) e shear (**G**), compressibilidade linear  ($\beta$) e razão de Poisson ($\nu$), calculadas a partir das constantes elásticas apresentadas na {numref}`elastic_ABF`. É possível notar uma anisotropia do módulo de Young e módulo shear semelhante à apresentada pelo Spiro-Carbon, porém com menor intensidade. Esse resultado pode ser associado com a presença do átomo de carbono $sp^3$ conectando as unidade spiro na formação da estrutura estendida, conferindo maior rigidez e menor anisotropia a esse material. De fato, a anisotropia do módulo de Young é de A<sub>E</sub> = 4.03 e do módulo de cisalhamento é de A<sub>G</sub> = 5.55, valores muito menores que o para o Spiro-Carbon que são de 19.58 e 29.98, respectivamente.
			
Utilizando o modelo empírico de Chen *et al.* {cite}`chen2011modeling` para o cálculo  da dureza de Vicker, o valor obtido para o ABF-Carbon é de 14.23 GPa (1452 HV). Esse valor é 3.25 vezes maior do que o apresentado pelo Spiro-Carbon, confiando que a adição dos átomos de carbono sp$^3$ na estrutura aumentam sua rigidez e dureza.

```{figure} fig/Elastic.png
:name: elastic_ABF

Dependência espacial do (a) módulo de Young; (b) compressibilidade linear; (c) módulo Shear e (d) razão de Poisson.
```

### Propredades Eletrônicas

A estrutura do ABF-Carbon, ao contrário do Spiro-Carbon, apresenta ligações duplas localizadas nas unidades *spiro* sem a possibilidade de conjugação, fazendo com que esse material possa apresentar um caráter semi-condutor. O *gap* HOMO-LUMO calculado para a molécula do spiropentadieno é de 3.92 eV e 5.22 eV quando calculado como os funcionais PBE e HSE, respectivamente. (Ver Apêndice 3 para mais detalhes} O diagrama de bandas calculado em nível PBE, apresentado na \autoref{band_ABF}, confirma o caráter semi-condutor com *band gap* direto da estrutura. Além disso, é possível observar que a densidade de estados próxima ao nível de Fermi é formada unicamente pelos orbitais $2p$ ($2p_x$, $2p_y$ e $2p_z$). O *band gap* direto calculado nesse nível é de 1.35 eV e 2.39 eV com o funcional HSE, indicando que essa estrutura apresenta um grande potencial para aplicações em optoeletrônica e fotocatálise.

```{figure} fig/band_structure.svg
:name: band_ABF

Dispersão de energia das bandas ao longo dos principais pontos de alta simetria na primeira zona de Brillouin (direita) e densidade de estados projetada nos orbitais (esquerda) para o ABF-Carbon. A energia de Fermi ($\epsilon_f$) foi ajustada para 0.
```

### Caracterização

Na {numref}`carac_abf` são apresentados os espectros simulados de FTIR, <sup>13</sup>C RMN e difração de raios-x e espectro de absorção no UV-VIS para o ABF-Carbon, na esperança de que sejam úteis no auxílio da caracterização de possíveis candidatos. O espectro de FTIR ({numref}`carac_abf`-*a*) apresenta um pico principal em 1391 cm<sup>-1</sup> devido ao modo vibracional com simetria B<sub>2</sub> e um pico  em 927 cm<sup>-1</sup> devido a outro modo B<sub>2</sub>. O espectro de <sup>13</sup>C RMN, mostrado na {numref}`carac_abf`-*b*, apresenta três deslocamentos químicos diferentes: 128.5 ppm para o átomo C1, 44.2 ppm para o átomo C2 e 39.2 para o átomo C3. O espectro de difração de raios-X, apresentado na {numref}`carac_abf`-*c*, calculado para comprimento de onda de 1.54059 Å apresenta um pico principal em 25.5° referente ao plano de Bragg (101) e picos menores em 20.3° e 33.2°, referentes aos planos (002) e (110), respectivamente. O espectro de absorção na região do UV-VIS apresenta bandas em 280, 320, 480 e 960 nm, indicando grande potencial para aplicações que dependam de absorção de luz em regiões no espectro visível e próximas. Essa estrutura não apresentam poros com tamanho suficiente para ser acessível a nenhum átomo ou molécula. 


```{figure} fig/characterization.png
:name: carac_abf

Gráficos dos espectros calculados de (a) FTIR (Lorentziana com 10 cm<sup>-1</sup> de largura); (b) deslocamentos químicos isotrópicos de <sup>13</sup>C RMN (Lorentziana com 1 ppm de largura); (c) Difratograma de raios-X; (d) Espectro de absorção UV-VIS (Lorentziana com 0.02 Ry de largura)
```

### Conclusões

Nesta seção foi apresentado um novo alótropo de carbono, denominado ABF-Carbon, formado pela conexão de unidades *spiro* por átomos de carbono sp<sup>3</sup>. Com base nos resultados apresentados é possível concluir que essa nova estrutura é estável, pois não apresenta frequências negativas na dispersão de fônons e sua matriz elástica satisfaz os critérios de estabilidade de Born. Diferentemente do Spiro-Carbon, essa estrutura apresenta um caráter semicondutor, com *band gap* de 2.4 eV. Além disso, ela apresenta menor energia de formação que outras estruturas alotrópicas tridimensionais, encorajando possíveis tentativas de síntese.

Os resultados discutidos nesta seção resultaram na publicação do artigo:

>Oliveira, F. L., & Esteves, P. M. (2021). First-Principles Calculations of a New Semi-Conductive Carbon Allotrope Named ABF-Carbon. **Journal of the Brazilian Chemical Society**, 32, 869-877.