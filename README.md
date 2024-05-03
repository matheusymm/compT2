- Integrantes
	- Ivan Capeli Navas, 802286
	- Matheus Yuiti Moriy Miata, 802097
	- Vítor Milanez, 804319
---
Implementação de um analisador sintático para a Linguagem Algorítmica (LA) desenvolvida pelo professor Jander.

- Executar com o corretor automático:
``` Shell
# java -jar caminhoCompilador caminhoJar gcc caminhoTemp caminhoCasosTeste 
# "RAs" Trabalho
java -jar ../corretor.jar "java -jar ./target/sintatico-1.0-SNAPSHOT-jar-with-dependencies.jar" gcc ./saidaT2 ../casos-de-teste/ "802286, 802097, 804319" t2
```  

- Executar manualmente:
``` Shell
# java -jar CaminhoJarWirhDependencies caminhoEntrada caminhoSaida 
java -jar ./target/sintatico-1.0-SNAPSHOT-jar-with-dependencies.jar ../casos-de-teste/2.casos_teste_t2/entrada/1-algoritmo_2-2_apostila_LA_1_erro_linha_3_acusado_linha_10.txt 1.out
```
