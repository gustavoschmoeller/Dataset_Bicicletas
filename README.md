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

> Pergunta 2: Quais são as Top 5 rotas, com base na estação inicial e final, e a média de duração de cada aluguel?

Com base na análise das rotas de aluguéis de bicicletas, identificamos as Top 5 rotas mais frequentes, considerando a estação inicial e final, além da média de duração de cada aluguel. A tabela abaixo apresenta as rotas mais recorrentes, com suas respectivas quantidades de aluguéis (Qtd) e a média de duração de cada aluguel:

![image](https://github.com/user-attachments/assets/c5162ffb-2acb-42ad-b368-50d34437c8de)

Essas rotas representam as mais populares dentro do sistema de compartilhamento de bicicletas, com destaque para a **rota 33 - 33**, que possui o maior número de aluguéis e a maior média de duração, indicando um possível padrão de uso mais prolongado nessa rota. A análise dessas rotas permite um melhor entendimento dos hábitos dos usuários e pode auxiliar na otimização do sistema, como a redistribuição de bicicletas e melhorias nas estações mais utilizadas.





✅ Fontes

Os dados utilizados estão hospedados no seguinte repositório:

GitHub Dataset
