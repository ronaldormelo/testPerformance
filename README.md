Test Performance
==================


Projeto utilizado para realizar testes de desempenho automatizado em um ambiente de integração contínua.


Utiliza:
Apache Jmeter
	Realiza a gravação do cenário de teste de performance
	Salva o arquivo .jmx
	Executa os testes conforme configurado no build.xml
Apache Ant
	Executa o build.xml no cambiente de integração contínua.
	Gera os resultados na pasta build/logs
	Gera os Gráficos na pasta build/logs
