# Repositório de testes, para a cognitivo.ai.
>Este repositório possui os **arquivos trabalhados, para resolução de problema, do teste da cognitivo.ai**. 

![](https://media.licdn.com/dms/image/C4E1BAQF2jIU3kenxdw/company-background_10000/0?e=2159024400&v=beta&t=KUR75HhB1UxOR5vzlkmoqouC2IZXl0WSrW-t1D1yU88)

## Sobre o desenvolvimento

Escolhi utilizar esse repositório, para hospedar o arquivo `.csv`, com os dados para análise, e utilizar a ferramenta de BI da Microsoft, o **Power BI**.

Os indicadores criados estão no Dashboard criado com extensão `.pbix`, e pode ser feito download do mesmo para análise.
Também poderá ver o link de acesso ao arquivo publicado, para visualização e avaliação via navegador de preferência.

Aproveite seus indicadores!!!


## Sobre o Teste

Deixei abaixo a descrição do teste solicitado, para melhor visualização entre arquivo criado, e problema definido.

### O problema proposto

Uma empresa que fornece aplicativos de música precisa acompanhar regularmente a evolução das métricas de aplicativos de música disponíveis na Apple Store. Hoje, para que esse acompanhamento seja feito, um profissional precisa diariamente realizar a coleta desses dados atualizados, realizar a transformação desses dados, criar as visualizações necessárias e enviar o relatório gerado por e-mail.

Atualmente a empresa não dispõe de nenhuma ferramenta que faça esse trabalho de forma automatizada. Além disso, esse profissional está envolvido em diversas outras atividades, fazendo com que, muitas vezes, esses relatórios deixem de ser enviados.

### Objetivo a ser alcançado

A empresa deseja criar uma solução de Dashboard que automatize essas atividades e você será o responsável por essa atividade.
A partir dos dados disponibilizados, será necessário criar uma tela de Dashboard que apresente as seguintes informações:

- Ranking dos 10 Aplicativos mais bem avaliados em sua última versão;
- Ranking dos 10 Aplicativos mais bem avaliados no geral;
- Ranking dos 10 Aplicativos com maior qtde de avaliações em sua última versão;
- Ranking dos 10 Aplicativos com maior qtde de avaliações no geral;
- Distribuição percentual da Classificação Indicativa dos Aplicativos (Percentual por classificação indicativa);
- Média do preço dos aplicativos de música em reais (considerando $ 1 = R$ 3,80|considerando todos os apps de música);
- Média do tamanho dos aplicativos de música em Mega Bytes;
- Avaliação no geral dos aplicativos de ID: 284035177, 284993459, 292738169, 293523031, 298206806;
- Quantidade de Avaliações no geral dos aplicativos de ID: 284035177, 284993459, 292738169, 293523031, 298206806;

### Dados disponíveis

Dentro do arquivo .csv, estão as colunas com as seguintes informações.


|Nome Coluna| significado |
|------------|------------|
|**id**| Identificação do App|
|**track_name** | Nome|
|**size_bytes** | Tamanho em Bytes|
|**currency** | Moeda|
|**price** | Valor na Apple Store|
|**rating_count_tot** | Qtde de Avaliações|
|**rating_count_ver** | Qtde de Avaliações última versão|
|**user_rating** | Avaliação Média|
|**user_rating_ver** | Avaliação Média da última versão|
|**ver** | Última Versão|
|**cont_rating** | Classificação Indicativa|
|**prime_genre** | Gênero do App|
