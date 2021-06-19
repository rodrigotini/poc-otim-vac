# poc-otimizacao-vacinacao
Projeto Final - Otimização - Solver - POC Distrib de Vacinas



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
1		A		80k
1		B		70k
2		C		100k
3		D		200k
3		E		105k
4		F		55k

Os custos de distribuição das vacinas serão respectivamente:
Planta		Custo
1		110k
2		55k
3		85k
4		35k



