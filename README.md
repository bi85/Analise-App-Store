# Análise dos Aplicativos da App Store

![](https://blogdoiphone.com/wp-content/uploads/2018/05/AppStore.jpg)

## Sobre o dataset utilizado

Para criar essa análise, utilizei um dataset hospedado no Kaggle, chamado **Mobile App Store**, localizado no endereço: https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps/**. 

Utilizei apenas um dos dois arquivos hospedados no kaggle, chamada **AppleStore.csv**. Fiz a hospedagem do dataset também aqui, disponível para dowload.

As colunas do dataset são:

|Nome Coluna| Descrição |
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

## Sobre a Ferramenta utilizada como DataViz

A escolha da ferramenta de DataViz, foi a ferramenta de BI da Microsoft, o **Power BI Desktop**.
Utilizei a ultima versão da ferramenta, a Versão: 2.70.5494.761 64-bit (junho de 2019), juntamente com alguns visuais personalizados dentro da biblioteca do Power BI, o **Marketplace**.

## A Análise do Dataset

Os Dashboards criados, estão no arquivo com extensão `.pbix`, do qual é necessário ter a ferramenta do **Power BI Desktop** instalado, para que consiga utilizar o mesmo.

Caso não queira fazer instalação do mesmo, abaixo segue o link de acesso ao arquivo publicado na web, para visualizaçãodos indicadores:

https://app.powerbi.com/view?r=eyJrIjoiMjFhZjg3ODgtYjFmZC00MzU5LTliYjktOTA3NTVmYWQwZjhmIiwidCI6IjdlNjVmZWY2LWFkYjQtNGZmMC05YWQ3LTViNzM0ZGI4YmU5NiJ9


### A análise realizada

A simulação criada, foi pensando na necessidade de uma Startup, que criou um aplicativo. Ela possui seu aplicativo hospedado na App Store, e quer acompanhar como anda em relação aos seus concorrentes.

Com intenção de orientar essa empresa, os indicadores foram criados analisando os **10 app's mais bem avaliados**, e comparando com o app de seus concorrentes.

Para isso, foram criados **6 painéis com indicadores**, avaliando os aplicativos de formas diferentes, conforme algumas premissas.

Os indicadores criados, para analisar os **Top 10 App's**, foram:

1. **Top 10 Ultima Versão**: Foi criado um **cálculo de pontos**, para classificação desses app's, que é a **multiplicação de sua nota de avaliação média, pela quantidade de avaliações da ultima versão do app**. Com esse critério, os 10 primeiros mais bem avaliados, foram eleitos para essa lista!

2. **Top 10 Avaliação Geral**: Foi criado um **cálculo de pontos**, para classificação desses app's, que é a **multiplicação de sua nota de avaliação média, pela quantidade de avaliações gerais do app, independente da versão**. Com esse critério, os 10 primeiros mais bem avaliados, foram eleitos para essa lista!

3. **Top 10 Qtd Avaliações Ultima Versão**: Nesta análise, os Top 10 App's foram eleitos pela **quantidade de avaliações em sua ultima versão lançada na App Store**. Essa análise é *independente da sua nota média*!

4. **Top 10 Qtd. Avaliação Geral**: Nesta análise, os Top 10 App's foram eleitos pela **maior quantidade de avaliações gerais na App Store, independente da sua nota média**.

5. **Classificação dos App's**: Indicadores sobre os *gêneros, valor(em reais), Tamanho e Classificação Indicativa* dos aplicativos.

6. **Avaliação Específica de Aplicativos**:  Neste painel de indicadores, estão informações sobre aplicativos específicos de músico. São indicadores gerais de *Nota Média, Gênero, Avaliações da Ultima Versão, Avaliações Gerais, Tamanho, Valor do App (em reais) e classificação indicativa* dos aplicativos listados.








