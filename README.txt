Versões
python = 3.6.1
seaborn = 0.9.0
sklearn = 0.20.1

Quanto aos inputs:
1 - O csv quantidade_debitos.csv foi obtido utilizando a identificação do contribuinte. Após obtidos os números essa identificação foi removida;
2 - Os demais arquivos .csv foram obtidos diretamente do DataMart de cobrança da prefeitura.

Quanto ao código:
Fase de Limpeza e Seleção de característica:
    1. ML_engineering_assess_clean
Fase de seleção de modelo e previsão das porcentagens:
    1. ML_engineering_model
Fase de obtenção de resultados para o negócio:
    1. ML_engineering_results



Instruções para rodar o código
	1. Descompactar os inputs
		a. input/2016/2016.zip
		b. input/2017/2017.zip
		c. input/quantidade_debitos.zip
	2. Executar todo o código do arquivo: ML_engineering_assess_clean
		a. isso gerará os arquivos pkls para a próxima fase
	3. Executar o código do arquivo: ML_engineering_model
		a. para essa fase é interessante pular a parte de refinamento. Ela é bastante demorada, em média 6 horas.
	4. Executar o código do arquivo: ML_engineering_results

Se executado na ordem descrita, os arquivos pkls serão criados de forma correta.


Relatórios:
	Proposta de projeto: "proposta.pdf"
	Relatório Final: "Relatório Final.pdf"