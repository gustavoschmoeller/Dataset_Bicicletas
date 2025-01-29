# Introdução
Este projeto tem como objetivo realizar a análise de um conjunto de dados contendo informações sobre o aluguel de bicicletas, processando e limpando os dados para extração de insights. Durante o desenvolvimento, além das perguntas iniciais, foram adicionadas duas perguntas extras que serão respondidas ao longo desta documentação, aprofundando ainda mais a compreensão do comportamento dos usuários.

Utilizando a linguagem Python e bibliotecas como Pandas, NumPy, Matplotlib e Seaborn, exploramos as tendências no aluguel de bikes, identificando as estações mais populares, os perfis de usuários e os horários de maior movimentação.

Os resultados desta análise podem ser utilizados para otimizar a distribuição de bicicletas, melhorar a infraestrutura das estações e aprimorar a experiência dos usuários.

# Processo
Para criar a análise de dados, a empresa disponibilizou um arquivo em formato CSV contendo informações detalhadas sobre o aluguel de bicicletas.

Inicialmente, carreguei o dataset utilizando a biblioteca pandas, explorando suas colunas e identificando possíveis inconsistências nos dados. Em seguida, realizei a limpeza e transformação das variáveis, incluindo conversão de datas, tratamento de valores ausentes e padronização de tipos de dados.

Embora o Python já seja eficiente para análise de dados, utilizei bibliotecas como matplotlib e seaborn para a exploração visual dos dados, permitindo uma melhor compreensão dos padrões e tendências do aluguel de bicicletas. Essa abordagem possibilitou insights mais detalhados sobre o comportamento dos usuários e ajudou na formulação das respostas às perguntas do projeto.

# Conclusão

> Pergunta 1: Quais são as Top 5 estações com maior número de aluguel de bikes?

![image](https://github.com/user-attachments/assets/dcf2916a-b7bf-44e9-b8a9-db77d2541ee6)

Com base na análise dos dados representados no gráfico, identificamos as **Top 5 estações com maior número de aluguéis de bicicletas**. A estação **1** se destaca significativamente como a mais utilizada, com **6.311 aluguéis**, seguida pelas estações **27** com **6.241** aluguéis, **271** com **5.265 aluguéis**, **64** com **4.834 aluguéis**, e **41**, que apresenta **4.633 aluguéis**.

Este resultado revela uma forte concentração de aluguéis nas estações 1 e 27, destacando-as como pontos centrais e cruciais dentro do sistema de compartilhamento de bicicletas.

> Pergunta 2: Qual é o horário de maior movimento?

Os dados indicam que há dois picos de demanda: pela manhã (horário de deslocamento para o trabalho) e ao final da tarde.

Pergunta 3: Como os feriados afetam o aluguel de bicicletas?

A análise dos feriados mostrou que há um aumento no aluguel de bicicletas em feriados prolongados e um declínio em feriados isolados.

✅ Fontes

Os dados utilizados estão hospedados no seguinte repositório:

GitHub Dataset
