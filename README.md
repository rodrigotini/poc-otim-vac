F# poc-otimizacao-vacinacao
Projeto Final - Otimização - Solver - POC Distrib de Vacinas


# Otimização processo de produção e distribuição de vacinas

#### Alun(o/a): Rodrigo da Mata Tini(https://github.com/rodrigotini).
#### Orientador(/a/es/as): [Nome Sobrenome](https://github.com/link_do_github).


---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- [Link para o código](https://github.com/rodrigotini/poc-otimizacao-vacinacao/). 


---

### Resumo

Estamos falando de uma possível pandemia a nível global no qual possuímos 5 vacinas(A,B,C,D e E) que são aplicadas via dose única e que são produzidas respectivamente pelos laboratórios:
Laboratório		Vacina
X1		A e B
X2 		A e C
X3 		D e E
X4 		A e E
X5 		A, B e C
X7	 	B e C
X6 		F
Entendemos que apesar de todos os esforços, existem várias novas variantes do vírus que são muito agressivas e sob incerteza de cobertura vacinal por parte de cada vacinas.  Devido a este fato, ficou determinado pelo Ministério da Saúde que atende uma população de 200 milhões de habitantes, a necessidade de compras mínimas para cada vacina (15 milhões) para tentar garantir um mínimo de cobertura vacinal possível.

O escopo deste projeto inclui a obtenção do menor custo para os processos de: fornecimento do IFA (ingrediente farmacêutico ativo), produção local e a distribuição.
Sabemos que o país possui 4 plantas (1,2,3 e 4) e que cada planta irá produzir da seguinte forma:
Planta		Vacinas
1	      	A e B
2	      	C
3	      	D e E
4	      	F

Os custos de fornecimento são:
Planta		X1	  X2	  X3	  X4	  X5	  X6  	X7
1		      300K	300k	-	    300k	400k	-   	300k
2		      -	    500k	-	    -	    600k	-   	400k
3		      -   	-	    100K	700k	-   	-   	-
4		      -   	-	    -     -	    -   	700k	-


Os custos de produção são:
Planta 		Vacina		Custo
1		      A		      80k
1		      B	      	70k
2		      C	      	100k
3		      D		      200k
3		      E	      	105k
4		      F	      	55k

Os custos de distribuição das vacinas serão respectivamente:
Planta		Custo
1	      	110k
2	      	55k
3	      	85k
4		      35k


Foi utilizada a ferramenta Solver do Excel para identificar quais seriam os melhores resultados que atendessem os requisitos do problema.

### Abstract <!-- Opcional! Caso não aplicável, remover esta seção -->

We are talking about a possible pandemic at a global level in which we have 5 vaccines (A,B,C,D and E) which are applied via a single dose and which are produced respectively by the laboratories:
Lab   Vaccine
X1    A and B
X2    A and C
X3    D and E
X4    A and E
X5    A, B and C
X7    B and C
X6    F
We understand that despite all efforts, there are several new variants of the virus that are very aggressive and under uncertainty of vaccine coverage by each vaccine. Due to this fact, it was determined by the Ministry of Health, which serves a population of 200 million inhabitants, the need for minimum purchases for each vaccine (15 million) to try to ensure the minimum possible vaccination coverage.

The scope of this project includes obtaining the lowest cost for the processes of: supply of API (active pharmaceutical ingredient), local production and distribution.
We know that the country has 4 plants (1,2,3 and 4) and that each plant will produce as follows:
Plant Vaccines
1     A and B
2     C
3     D and E
4     F

Delivery costs are:
Plant X1    X2    X3    X4    X5    X6    X7
1     300K  300k  -     300k  400k  -     300k
2     -     500k  -     -     600k  -     400k
3     -     -     100K  700k  -     -     -
4     -     -     -     -     -     700k  -


The production costs are:
Plant     Vaccine   Cost
1		      A		      80k
1		      B	      	70k
2		      C	      	100k
3		      D		      200k
3		      E	      	105k
4		      F	      	55k

Vaccine distribution costs will be respectively:
Plant   Cost
1       110k
2       55k
3       85k
4       35k


Excel's Solver tool was used to identify the best results that would meet the problem's requirements.
---

Matrícula: 192.168.053

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*








