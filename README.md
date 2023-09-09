O poder da Inteligência Artificial aplicada à análise de dados.

AULA 01: ANÁLISE EXPLORATÓRIA DA BASE DE DADOS E CHATGPT

Introdução Trabalhar com dados no Excel e no Google Sheets se tornou uma habilidade essencial em diversas áreas, incluindo marketing, vendas e muitas outras. Essas ferramentas oferecem uma plataforma versátil para coletar, analisar e visualizar dados, permitindo que profissionais tomem decisões assertivas e estratégicas.

Nesta primeira aula, vamos te apresentar o Kaggle e fazer uma análise exploratória com uma base de dados de compras da Amazon, usando o ChatGPT como auxiliar na hora de gerar fórmulas básicas do Google Sheets.

Abaixo, disponibilizamos todo o material necessário para que você acompanhe a aula e avance em seu projeto.

Para começar, faça uma cópia da planilha de dados da Amazon usada na aula: https://docs.google.com/spreadsheets/d/1pzFHqIAKdNOfbyecJ9hSYUXA3YSbXXF6pYEqLA_0b9k/edit#gid=105405843

Informações representadas por cada coluna na planilha de dados:

product_id: ID do produto product_name: Nome do produto category: Categoria do produto actual_price: Valor do produto com desconto product_price: Valor do produto com valor cheio rating: Valor de 0 a 5 avaliando o produto rating_count: Quantidade de pessoas que avaliaram o produto about_product: Descrição do produto product_link: Link do produto na loja da Amazon

Desafios do dia: Adicionar a formatação condicional de cores à coluna de porcentagens. Faça uma análise exploratória e aplique as mesmas técnicas com o ChatGPT a uma nova base de dados do Kaggle: Top 1000 IMDb Movies Dataset: https://www.kaggle.com/datasets/inductiveanks/top-1000-imdb-movies-dataset

Links citados ChatGPT da OpenAI Artigo citado do “The New York Times” Link da base de dados completa da Amazon no Kaggle A função GOOGLEFINANCE do Google Sheets A função COUNTIF do Google Sheets Conteúdo extra: Bard da Google Conteúdo extra: Bing AI da Microsoft


AULA 02: MANIPULE PLANILHAS E CRIE GRÁFICOS COM AJUDA DA IA

Introdução Chegou a hora de avançar seus** aprendizados e usar a IA como assistente na manipulação de planilhas**.

Na segunda aula, vamos dar continuidade à utilização do ChatGPT para aprender a criar fórmulas no Google Sheets. Abordaremos algumas fórmulas mais avançadas, como o cálculo de média para faixas de valores e média ponderada, exploraremos a criação de gráficos e te apresentaremos a uma nova ferramenta de IA para dados. Vamos lá?

https://docs.google.com/spreadsheets/d/1vfgOR26f-ZH9SKN3JaTlUnSj5IpENS79sXvus6mV46E/edit#gid=105405843

Desafio do dia: Personalize o gráfico para adicionar as quantidades Analise qual seria o melhor gráfico para o seu caso usando o guia citado pelo Marcell: https://drive.google.com/file/d/12GLVEqzF5YqkdXJSUMx-_WpNHaAJo84A/view?usp=sharing Faça uma análise exploratória e aplique as mesmas técnicas vistas na aula de hoje, incluindo a criação de gráficos, a uma nova base de dados do Kaggle: base de dados de hoteis do Kaggle: https://www.kaggle.com/datasets/andrewgeorgeissac/hotels-in-munnar-kerala

AULA 03: CONECTE PLANILHAS E DOMINE CONCEITOS DE ENGENHARIA DE PROMPT

Introdução Na terceira aula dessa imersão, iremos um pouco mais fundo. Vamos mergulhar em uma nova base de dados, também da Amazon, que é relacionada à base antiga, e aprenderemos como conectá-las usando uma coluna comum a ambas. Apresentaremos também uma extensão que te permitirá ter o ChatGPT dentro do seu Google Sheets, e a empregaremos para realizar traduções, resumos e análises de sentimento de críticas. Por fim, focaremos uma parte da aula em te passar alguns dos principais conceitos de Engenharia de Prompt, como o uso de “few-shot” com o cadeia de pensamento, a fim de obter respostas mais precisas de IAs generativas como o ChatGPT.

Para começar, faça uma cópia da nova planilha de dados da Amazon que será analisada e conectada com a antiga: https://docs.google.com/spreadsheets/d/1ECBmuHz75Fsb3aCWsLBxg_DKZiBLdilrFj7rzc-N65s/edit?usp=sharing

Informações representadas por cada coluna na nova planilha de dados:

product_id: ID do produto user_id: ID único do usuário user_name: Nome escolhido pelo usuário review_id: ID da crítica review_title: Título da crítica review_content: Conteúdo da crítica img_link: Link da imagem do produto

Prompts da aula: Pergunta: Tenho uma lista de valores. O meu resultado final será 30% da soma de valores. Porém, nem todos os valores serão somados, apenas aqueles acima de R$40.000,00. Para a lista abaixo, conte quantos valores existem e me diga qual é o meu resultado final?

R 10.000,00R 20.000,00 R 50.000,00R 60.000,00 Resposta: Nessa lista, existem 4 valores. Há 2 valores acima de R 40.000,00,quesãoR 50.000,00 e R 60.000,00.AsomadessesvaloreséR 110.000,00. O resultado final é 30% da soma desses valores, portanto, 30% de R 110.000,00,queresultaemR 33.000,00.

Pergunta: Tenho uma lista de valores. O meu resultado final será 30% da soma de valores. Porém, nem todos os valores serão somados, apenas aqueles acima de R$40.000,00. Para a lista abaixo, conte quantos valores existem e me diga qual é o meu resultado final?

(COLAR AQUI OS 10 VALORES DA NOSSA LISTA REAL DO GOOGLE SHEETS)

Resposta:

Desafio do dia: Gere a tradução das críticas e faça uma análise de sentimentos das mesmas usando a extensão SheetGPT em uma nova base de dados do Kaggle: base de críticas do aplicativo Threads: https://www.kaggle.com/datasets/saloni1712/threads-an-instagram-app-reviews

AULA 04: MANIPULE PLANILHAS COM PYTHON/PANDAS E O CHATGPT

Introdução Chegou a hora de conhecer o Google Colab. Vamos mergulhar em Python e na biblioteca de manipulação de dados Pandas, demonstrando como importar tabelas e realizar análises iniciais com os comandos mais importantes. Não se preocupe se você não sabe programar! Nós utilizaremos o ChatGPT para nos auxiliar na criação de código em Python e Pandas, e também para plotar gráficos.

https://docs.google.com/spreadsheets/d/1ECBmuHz75Fsb3aCWsLBxg_DKZiBLdilrFj7rzc-N65s/edit?usp=sharing

Links citados:

Documentação da biblioteca Pandas: https://pandas.pydata.org/docs/user_guide/index.html

Documentação da biblioteca Pandas Profiling: https://pypi.org/project/pandas-profiling/

Desafios do dia: Usando o Google Colab com Python e Pandas, criar uma nova coluna chamada “actual_price_real”, que será o valor da coluna “actual_price” convertido para reais (dica: você pode apenas multiplicar o valor em rúpias por 0.05, como fizemos na Aula 01, ou então buscar o valor de hoje da conversão entre rúpias indianas e reais brasileiros no Google).

Realizar as análises que foram executadas nas aulas anteriores usando o Google Sheets, mas agora utilizando Python e Pandas no Google Colab.

Conectar as duas planilhas usadas nas aulas anteriores, como fizemos com o VLOOKUP, mas usando Python e Pandas.

Colocar a base já corrigida na biblioteca Pandas Profiling citada no conteúdo extra.

AULA 05: CARREIRAS EM ANÁLISE DE DADOS E INTELIGÊNCIA ARTIFICIAL

Introdução Se prepare para mergulhar na última aula da imersão, onde iremos explicar as diferenças entre as principais carreiras nessa área de dados, tais como Analista de Dados, Cientista de Dados, Engenheiro de Dados, Engenheiro de Machine Learning, Engenheiro de IA e Engenheiro de Prompt. Vamos lá?

Links citados Engenheiro de Dados Líder na Globo: Matheus Encarnação Analista de Dados na ThoughtWorks: Carolina Assis Engenheiro de Machine Learning na Qantev: Filipe Lauar Analista de Governança de Dados no Itaú Unibanco: Pedro Moura Engenheiro de IA na Maritaca AI: Hugo Abonizio Conteúdo extra: TechGuide: https://techguide.sh/
