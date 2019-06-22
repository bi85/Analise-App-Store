# Análise dos Aplicativos da App Store
>Este repositório possui os **arquivos trabalhados, sobre o Dataset no Mobile App Store, localizado no Kaggle no endereço: https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps/**. 

![](https://blogdoiphone.com/wp-content/uploads/2018/05/AppStore.jpg)

## Sobre a análise desenvolvida

Fiz a hospedagem do dataset em `.csv`,  e a escolha da ferramenta de DataViz, a ferramenta de BI da Microsoft, o **Power BI Desktop**.
Utilizei a ultima versão da ferramenta, a Versão: 2.70.5494.761 64-bit (junho de 2019), juntamente com alguns visuais personalizados dentro da biblioteca do Power BI, o **Marketplace**.

Os indicadores criados, estão no Dashboard com extensão `.pbix`, do qual é necessário ter a versão **Power BI Desktop** instalado, para que consiga fazer download, e utilizar o mesmo.

Caso não queira fazer instalação do mesmo, abaixo segue o link de acesso ao arquivo publicado na web, para visualizaçãodos indicadores:

https://app.powerbi.com/view?r=eyJrIjoiMjFhZjg3ODgtYjFmZC00MzU5LTliYjktOTA3NTVmYWQwZjhmIiwidCI6IjdlNjVmZWY2LWFkYjQtNGZmMC05YWQ3LTViNzM0ZGI4YmU5NiJ9


### A análise realizada

A simulação criada, foi com intenção de orientar um empresário, que possui seu aplicativo na App Store. Os indicadores tem intenção de auxilia-lo a tomar uma melhor decisão em relação ao seu App, e comparado aos concorrentes, como está sua posição no ranking dos 10 primeiros aplicativos.

Para isso, foram criados 6 painéis, com indicadores avaliando os aplicativos de formas diferentes, e com informações sobre os próprios app's, fornecidos no dataset. Foi implementado, uma breve descrição do app, para identificação dos mesmos.

Os indicadores criados, para analisar os **Top 10 App's**, foram:

1. **Top 10 Ultima Versão**: Foi criado um **cálculo de pontos**, para classificação desses app's, que é a **multiplicação de sua nota de avaliação média, pela quantidade de avaliações da ultima versão do app**. Com esse critério, os 10 primeiros mais bem avaliados, foram eleitos para essa lista!

2. **Top 10 Avaliação Geral**: Foi criado um **cálculo de pontos**, para classificação desses app's, que é a **multiplicação de sua nota de avaliação média, pela quantidade de avaliações gerais do app, independente da versão**. Com esse critério, os 10 primeiros mais bem avaliados, foram eleitos para essa lista!

3. **Top 10 Qtd Avaliações Ultima Versão**: Nesta análise, os Top 10 App's foram eleitos pela **quantidade de avaliações em sua ultima versão lançada na App Store**. Essa análise é *independente da sua nota média*!





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
