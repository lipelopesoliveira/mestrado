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

# Gerando novos alótropos

Nas seções anteriores deste trabalho foi apresentado a estrutura do Spiro-Carbon e um dos aspectos mais marcantes é sua semelhança com cadeias de *trans-cisoide*-(poli)acetileno conectadas por átomos de carbono $sp^3$, a origem de seu caráter metálico. Apesar de não ser um conceito prático, afinal polimerizar cadeias de (poli)acetileno para formar a estrutura cristalina do Spiro-Carbon pode ser um desafio sintético insuperável, utilizar uma molécula, ou motivo estrutural derivado de uma, como bloco de construção pode ser uma estratégia promissora para a idealização de novos alótropos de carbono.
	
De fato, alguns trabalhos recentes na literatura mostram que utilizar alótropos já existentes como ponto de partida para novas estruturas pode ser uma ótima estratégia. Hu *et al.* {cite}`hu2013compressed` em 2013 mostrou que nanotubos de carbono comprimidos podem reorganizar suas ligações e formar novas estruturas. Fedik *et al.* {cite}`fedik2020can` em 2020 mostrou que o cyclo[18]carbon pode ser entrelaçado, como anéis em uma corrente, para formar catenanos de carbono. 


```{figure} fig/carbina.png
:name: carbina

Possíveis distorções da cadeia do carbino.
```

Se olharmos para os modos normais de vibração do carbino, como apresentado na {numref}`carbina`, é possível perceber que dependendo de como esse modos se acoplam podem ser geradas duas formas muito parecidas com as diferentes configurações da cadeia de (poli)acetileno: um carbino em forma *armchair* **(a)**, semelhante ao *cis*-(poli)acetileno, e uma em forma *zigue-zague* **(b)**, semelhante ao *trans*-(poli)acetileno.
	
Dessa forma, é possível pensar na formação de alótropos de carbono como o grafeno, ou até mesmo o Spiro-Carbon, a partir de cadeias do carbino distorcidas na direção de um de seus modos normais de vibração. Se a cadeia for distorcida na forma *zigue-zague* e forem aproximadas de maneira paralela poderia ocorrer a quebra de uma ligação $\pi$ e consequente formação de ligações entre as cadeias, gerando assim a estrutura do grafeno. Por outro lado, se as cadeias fossem distorcidas na forma *armchair* e fossem aproximadas de um átomo de carbono de maneira perpendicular, poderia ocorrer a formação da estrutura do Spiro-Carbon. É importante ressaltar que esse método não é uma proposta de mecanismo de síntese, mas sim puramente um exercício mental para desenvolver uma lógica de construção de novas estruturas. 
	
A partir dessa metodologia, o grafeno e o Spiro-Carbon não são as únicas estruturas que podem ser geradas. Podemos conectar as cadeias distorcidas na forma zigue-zague não paralelamente, como é feito para gerar o grafeno, mas sim perpendicularmente e obter a estrutura proposta por Hoffman *et al.* {cite}`hoffmann1983hypothetical` em 1983. Podemos conectar as cadeias do carbino não por apenas um átomo, mas por dois ou mais átomos de carbono gerando assim uma miríade de estruturas, como representado na {numref}`alotropos`.

```{figure} fig/alotropos.svg
:name: alotropos

Diferentes alótropos que podem ser gerados a partir das diferentes formas de conectar o carbino.
```

## Conectando as cadeias diretamente

Seguindo a lógica de construção proposta, podemos gerar três estruturas diferentes conectando as cadeias diretamente. Utilizando a cadeia de carbino distorcida na forma *zigue-zague* pode-se gerar a estrutura do grafeno ({numref}`0atomos`-**a**), se conectadas de maneira paralela, e a do bct-4 ({numref}`0atomos`-**b**), explorada por Hoffman *et al.* {cite}`hoffmann1983hypothetical`, se conectadas de maneira perpendicular. Utilizando a cadeia deformada na forma *armchair* conectada diretamente de maneira paralela pode-se obter a estrutura (4,8)-carbon ({numref}`0atomos`-**c**), explorada por Nissar *et al.* {cite}`nisar2012semiconducting`. Não é possível formar uma estrutura estável com a forma *armchair* conectada perpendicularmente, pois dessa forma a distância entre dois átomos de cadeias adjacentes seria próxima do comprimento de uma ligação simples ($\approx$1.5 Å). 
		
A {numref}`0atomos` apresenta os cálculos do diagrama de bandas e dispersão de fônons para as três possíveis estruturas. É possível observar que nos três casos elas apresentam interseção entre as bandas de valência e condução, mostrando o caráter metálico já conhecido para essas estruturas. Uma característica que não é apresentada na literatura é a dispersão de fônons para o bct-4 ({numref}`0atomos`-*b*) e o (4,8)-carbon ({numref}`0atomos`-*c*). Os resultados para ambas as estruturas mostram uma grande incidência de modos vibracionais imaginários, indicando que nenhuma das estruturas é estável. De fato, no artigo original do bct-4 carbon os autores comentam que essa estrutura poderia apresentar uma espécie de "tensão $\pi$", devido à proximidade entre os orbitais $\pi$ na vizinhança de cada cadeia. Esse fator pode ser responsável pelas frequências vibracionais imaginárias apresentadas em {numref}`0atomos`-*c*.

```{figure} fig/0atoms.png
:name: 0atomos

Diferentes alótropos que podem ser gerados a partir do carbino conectada diretamente.
```

## Conectando as cadeias por um átomo

Conectando as cadeias por um átomo pode-se gerar duas estruturas diferentes, sendo ambas tridimensionais. A primeira estrutura, derivada do carbino *zigue-zague*, apresenta uma geometria parecida com a do bct-4, mas com as cadeias conectadas por duas ligações duplas cumulências ({numref}`1atomos`-*a*). A segunda é derivada do carbino *armchair*, e já foi explorada anteriormente tendo sido denominada Spiro-Carbon ({numref}`1atomos`-*b*). Nenhuma das duas estruturas haviam sido relatadas na literatura anteriormente a esse trabalho. 


```{figure} fig/1atoms.png
:name: 1atomos

Diferentes alótropos que podem ser gerados a partir do carbino conectada por um átomo de carbono.
```

Nenhuma das duas apresentaram frequências imaginárias na dispersão de fônons, indicando que as estruturas são um mínimo na superfície de energia potencial. Além disso, ambas as estruturas apresentam caráter eletrônico metálico com grande densidade de estados próximo ao nível de Fermi, uma consequência do caráter *quasi*-unidimensional da cadeia do carbino. 

## Conectando as cadeias por dois átomo ou mais átomos

Conectando as cadeias por dois átomos podemos gerar pelo menos quatro estruturas diferentes. Essa estratégia pode ser comparada a adicionar uma unidade acetilênica (-C$\equiv$C-) entre as cadeias do carbino distorcida, entretanto esses átomos têm a liberdade de apresentar ligações acetilênicas (ligando-se entre sí por ligações triplas e com seus vizinhos por ligações simples) ou ligações cumulênicas (formando uma sequência de três ligações duplas com orbitais $\pi$ perpendiculares). Das quatro estruturas possíveis, três são bidimensionais e somente uma tridimensional.  

```{figure} fig/2atoms.png
:name: 2atomos

Diferentes alótropos que podem ser gerados conectando cadeias do carbino por dois átomos de carbono.
```

Ao tentar conectar as cadeias por três ou mais átomos, é possível notar que a estrutura geral passa a seguir o mesmo padrão, porém agora com mais átomos entre as cadeias principais. Por exemplo, ao conectar o carbino *armchair* por três átomos o motivo estrutural semelhante ao *Spiro-Carbon* aparece, mas agora os anéis de três membros estão separados por um átomo de carbono e não mais ligados diretamente. O mesmo acontece com as cadeias *zigue-zague* conectadas por três átomos, estruturalmente ela fica muito parecida com a conectada por apenas um átomo porém agora as cadeias do carbino estão mais espaçadas. 
		
Por fim é importante ressaltar que o conceito geral de gerar novos alótropos segundo as direções das distorções provenientes dos modos normais de vibração não está limitado ao carbino. Podemos pensar em estruturas 3D, como o diamante ou o Lonsdaleite, como sendo formado por distorções seguindo os modos normais de vibração do grafeno, por exemplo. Seguindo essa mesma lógica, outros materiais 2D podem ser distorcidos e conectados para gerar novas estruturas tridimensionais. Isso abre intrigantes e excitantes perspectivas para pesquisas futuras, mostrando como ainda somente arranhamos a superfície de todo o potencial estrutural que um único tipo de átomo pode gerar. 
	
		
## Conclusões
		
Neste capítulo foi explorado o conceito de obtenção de novos alótropos a partir de um alótropo já conhecido, o carbino. Seguindo a distorção de cadeia na direção de um de seus modos normais de vibração e combinando as cadeias de maneira paralela ou perpendicular é possível obter a estrutura de alótropos já conhecidos como o grafeno e o bct-4 carbon. Adicionando um ou mais átomos entre as cadeias é possível conceber uma variedade de novas estruturas, com propriedades eletrônicas completamente diferentes. 
		
Esse conceito abre espaço para novas pesquisas futuras, utilizando não somente o carbino como "bloco de construção" para novos alótropos, mas também outras estruturas como o grafeno e nanotubos de carbono. Essa estratégia permite a criação de um espaço amostral de possíveis estruturas de maneira simples e objetiva, facilitando a busca pelas estruturas mais estáveis e/ou que apresentem propriedades especiais, e assim incentivando esforços experimentais para sintetizar alguns candidatos. 