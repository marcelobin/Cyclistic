# **Cyclistic Bike-Share Analysis**
Este projeto tem como objetivo analisar dados históricos de viagens da Cyclistic, uma empresa fictícia de compartilhamento de bicicletas em Chicago, para entender como os usuários casuais e membros anuais utilizam o serviço de forma diferente. O objetivo final é fornecer insights para a equipe de marketing da Cyclistic, permitindo que eles desenvolvam estratégias eficazes para converter usuários casuais em membros anuais.

## **Contexto do Negócio**

A Cyclistic oferece diversos planos de assinatura, incluindo passes de viagem única e passes de um dia (usuários casuais) e planos anuais (membros). A empresa busca aumentar a receita, focando na conversão de usuários casuais em membros anuais, que são mais lucrativos.

**Os dados para este projeto estão disponibilizados na página https://divvy-tripdata.s3.amazonaws.com/index.html**


## **Análise de Dados**

O projeto utiliza dados históricos de viagens da Cyclistic, incluindo informações como tipo de bicicleta, data e hora de início e fim da viagem, nome e ID da estação, latitude e longitude, e tipo de usuário (casual ou membro). A análise inclui:

- Importação e limpeza dos dados: Os dados são carregados, combinados em um único DataFrame e limpos, removendo duplicatas e valores ausentes.
- Criação de novas features: São criadas colunas para o dia da semana, duração da viagem e distância percorrida.
- Tratamento de outliers: Outliers são identificados e removidos para garantir a qualidade da análise.
- Análise exploratória de dados (EDA): A EDA é realizada para entender as características dos dados e identificar padrões de uso entre usuários casuais e membros.
- Visualizações e Insights: O projeto inclui diversas visualizações para apresentar os resultados da análise, como gráficos de barras, histogramas e mapas. Os insights gerados podem ajudar a equipe de marketing a entender:

- Diferenças no comportamento de uso entre membros anuais e usuários casuais (dias da semana, horários, duração das viagens, distância percorrida, tipo de bicicleta, etc.).
- Padrões de uso das estações, identificando as mais populares e as menos utilizadas.
- Distribuição geográfica das viagens, visualizando as áreas da cidade com maior e menor demanda.

## **Recomendações**

Com base nos insights da análise, o projeto pode fornecer recomendações para a equipe de marketing, como:

- Desenvolver campanhas de marketing direcionadas para usuários casuais, com base em seus padrões de uso.
- Oferecer incentivos ou promoções para encorajar a conversão para planos anuais.
- Ajustar a distribuição das bicicletas nas estações para atender à demanda em diferentes regiões da cidade.
- Melhorar a comunicação sobre os benefícios dos planos anuais para os usuários casuais.


