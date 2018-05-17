# Análise da situação dos discentes do curso de Bacharelado em Tecnologia da Informação da UFRN

1. Alunos:
	* Gabriel Estevam Narciso (gabriel.estevam.narciso@gmail.com)
	* Maria Rayane Ribeiro da Silva Alves (mrayalves05@gmail.com)

2. Link para o vídeo da apresentação no Youtube:
	* https://youtu.be/dZTWHz0-r78

## Introdução

Constantemente ouvimos falar que alguns cursos de graduação são um tanto quanto difíceis durante sua formação. Entre tais, o curso de Bacharelado em Tecnologia da Informação (BTI) é citado por possuir, supostamente, uma complexidade e baixos índices de formação, se comparado a quantidade de alunos ingressantes. Contudo, segundo pesquisas realizadas no Google, maior site de buscas da atualidade, até o momento não há conhecimento desse fato comprovado com estudos.

Partindo dessa problemática, acessamos o Portal de Dados Abertos da Universidade Federal do Rio Grande do Norte (UFRN) e desenvolvemos um Notebook em Python que analisa a quantidade de alunos ativos, cancelados, trancados, concluídos e formados no curso de Tecnologia da Informação divididos por seu ano de ingresso.

## Desenvolvimento

De forma sucinta, realizamos os downloads dos arquivos que contém as informações dos discentes ingressantes dos anos de 2013 a 2018 (período em que as turmas de BTI foram se consolidando) em formato .csv no Portal de Dados Abertos da UFRN; realizamos os tratamentos necessários para a remoção de dados nulos e não necessários; filtramos esses alunos como sendo da Graduação do curso de Tecnologia da Informação; e realizamos as operções necessárias para as análises.

## Bibliotecas Utilizadas

1. Pandas
2. Matplotlib
3. Numpy