
# Cap 10 - Explorando SQL e tipos de dados na Oracle

A ideia do banco é guardar a produção de laranja, limao e a produção total desses dois frutos desde e o ano 2015 de cada UF do Brasil, para isso o banco possui 3 tabelas ao total a primeira(quantidade_produzida_total) que guarda a produção dos dois frutos ao decorrer dos anos, a segunda(quantidade_produzida_laranaja) que guarda a produção de laranja dos estados, e a terceira(quantidade_produzida_limao) que guarda a produção de limão dos estados.

### Entidade 1: quantidade_produzida_total
Volume esperado: 15 linhas, e volume anual de uma linha  
Tempo de retenção: Permantente  
Rotina de limpeza: Não se aplica

|Atributo   |Tipo do Atributo   |Cardinalidade Minima|Cardinalidade Maxima | 
|-----------|-------------------|--------------------|---------------------|
|ano_total(number 10) 				| simples, determinante | 1 | 1 |
|rondônia_total(number 10) 			| simples				| 0 | 1 |
|acre_total(number 10) 				| simples  			 	| 0 | 1 |
|amazonas_total(number 10) 			| simples  			 	| 0 | 1 |
|roraima_total(number 10) 			| simples  			 	| 0 | 1 |
|pará_total(number 10) 				| simples  			 	| 0 | 1 |
|amapá_total(number 10)				| simples  			 	| 0 | 1 |
|tocantins_total(number 10) 		| simples  			 	| 0 | 1 |
|maranhão_total(number 10)  		| simples  			 	| 0 | 1 |
|miauí_total(number 10) 			| simples  			 	| 0 | 1 |
|ceará_total(number 10) 			| simples  			 	| 0 | 1 |
|rio_grande_norte_total(number 10)  | simples  			 	| 0 | 1 |
|paraíba_total(number 10) 	 		| simples  			 	| 0 | 1 |
|pernambuco_total(number 10) 		| simples  			 	| 0 | 1 |
|alagoas_total(number 10) 	 		| simples  			 	| 0 | 1 |
|sergipe_total(number 10) 	 		| simples  			 	| 0 | 1 |
|bahia_total(number 10) 		 	| simples  			 	| 0 | 1 |
|minas_Gerais_total(number 10)    	| simples  			 	| 0 | 1 |
|espírito_Santo_total(number 10)  	| simples  			 	| 0 | 1 |
|rio_janeiro_total(number 10)     	| simples  			 	| 0 | 1 |
|sao_paulo_total(number 10) 	  	| simples  			 	| 0 | 1 |
|paraná_total(number 10) 		  	| simples  			 	| 0 | 1 |
|santa_catarina_total(number 10)  	| simples  			 	| 0 | 1 |
|rio_grande_sul_total(number 10)  	| simples  			 	| 0 | 1 |
|mato_grosso_sul_total(number 10) 	| simples  			 	| 0 | 1 |
|mato_grosso_total(number 10) 		| simples  			 	| 0 | 1 |
|goiás_quatotal(number 10) 			| simples  			 	| 0 | 1 |
|distrito_federal_total(number 10)  | simples  			 	| 0 | 1 |


### Entidade 2: quantidade_produzida_laranaja
Volume esperado: 15 linhas, e volume anual de uma linha  
Tempo de retenção: Permantente  
Rotina de limpeza: Não se aplica  

|Atributo   |Tipo do Atributo   |Cardinalidade Minima   |Cardinalidade Maxima	|
|----------|----------------|--------------------|---------------------|
|ano_quantidade_laranja(number 10) 				| simples, determinante | 1 | 1 |
|rondônia_laranja(number 10) 			| simples				| 0 | 1 |
|acre_laranja(number 10) 				| simples  			 	| 0 | 1 |
|amazonas_laranja(number 10) 			| simples  			 	| 0 | 1 |
|roraima_laranja(number 10) 			| simples  			 	| 0 | 1 |
|pará_laranja(number 10) 				| simples  			 	| 0 | 1 |
|amapá_laranja(number 10)				| simples  			 	| 0 | 1 |
|tocantins_laranja(number 10) 		| simples  			 	| 0 | 1 |
|maranhão_laranja(number 10)  		| simples  			 	| 0 | 1 |
|miauí_laranja(number 10) 			| simples  			 	| 0 | 1 |
|ceará_laranja(number 10) 			| simples  			 	| 0 | 1 |
|rio_grande_norte_laranja(number 10)  | simples  			 	| 0 | 1 |
|paraíba_laranja(number 10) 	 		| simples  			 	| 0 | 1 |
|pernambuco_laranja(number 10) 		| simples  			 	| 0 | 1 |
|alagoas_laranja(number 10) 	 		| simples  			 	| 0 | 1 |
|sergipe_laranja(number 10) 	 		| simples  			 	| 0 | 1 |
|bahia_laranja(number 10) 		 	| simples  			 	| 0 | 1 |
|minas_Gerais_laranja(number 10)    	| simples  			 	| 0 | 1 |
|espírito_Santo_laranja(number 10)  	| simples  			 	| 0 | 1 |
|rio_janeiro_laranja(number 10)     	| simples  			 	| 0 | 1 |
|sao_paulo_laranja(number 10) 	  	| simples  			 	| 0 | 1 |
|paraná_laranja(number 10) 		  	| simples  			 	| 0 | 1 |
|santa_catarina_laranja(number 10)  	| simples  			 	| 0 | 1 |
|rio_grande_sul_laranja(number 10)  	| simples  			 	| 0 | 1 |
|mato_grosso_sul_laranja(number 10) 	| simples  			 	| 0 | 1 |
|mato_grosso_laranja(number 10) 		| simples  			 	| 0 | 1 |
|goiás_laranja(number 10) 			| simples  			 	| 0 | 1 |
|distrito_federal_laranja(number 10)  | simples  			 	| 0 | 1 |

### Entidade 3: quantidade_produzida_limao
Volume esperado: 15 linhas, e volume anual de uma linha  
Tempo de retenção: Permantente  
Rotina de limpeza: Não se aplica  

|Atributo   |Tipo do Atributo   |Cardinalidade Minima   |Cardinalidade Maxima	|
|----------|----------------|--------------------|---------------------|
|ano_quantidade_limao(number 10) 	| simples, determinante | 1 | 1 |
|rondônia_limao(number 10) 			| simples				| 0 | 1 |
|acre_limao(number 10) 				| simples  			 	| 0 | 1 |
|amazonas_limao(number 10) 			| simples  			 	| 0 | 1 |
|roraima_limao(number 10) 			| simples  			 	| 0 | 1 |
|pará_limao(number 10) 				| simples  			 	| 0 | 1 |
|amapá_limao(number 10)				| simples  			 	| 0 | 1 |
|tocantins_limao(number 10) 		| simples  			 	| 0 | 1 |
|maranhão_limao(number 10)  		| simples  			 	| 0 | 1 |
|miauí_limao(number 10) 			| simples  			 	| 0 | 1 |
|ceará_limao(number 10) 			| simples  			 	| 0 | 1 |
|rio_grande_norte_limao(number 10)  | simples  			 	| 0 | 1 |
|paraíba_limao(number 10) 	 		| simples  			 	| 0 | 1 |
|pernambuco_limao(number 10) 		| simples  			 	| 0 | 1 |
|alagoas_limao(number 10) 	 		| simples  			 	| 0 | 1 |
|sergipe_limao(number 10) 	 		| simples  			 	| 0 | 1 |
|bahia_limao(number 10) 		 	| simples  			 	| 0 | 1 |
|minas_Gerais_limao(number 10)    	| simples  			 	| 0 | 1 |
|espírito_Santo_limao(number 10)  	| simples  			 	| 0 | 1 |
|rio_janeiro_limao(number 10)     	| simples  			 	| 0 | 1 |
|sao_paulo_limao(number 10) 	  	| simples  			 	| 0 | 1 |
|paraná_limao(number 10) 		  	| simples  			 	| 0 | 1 |
|santa_catarina_limao(number 10)  	| simples  			 	| 0 | 1 |
|rio_grande_sul_limao(number 10)  	| simples  			 	| 0 | 1 |
|mato_grosso_sul_limao(number 10) 	| simples  			 	| 0 | 1 |
|mato_grosso_limao(number 10) 		| simples  			 	| 0 | 1 |
|goiás_limao(number 10) 			| simples  			 	| 0 | 1 |
|distrito_federal_limao(number 10)  | simples  			 	| 0 | 1 |