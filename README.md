# Introdução
Este projeto tem como objetivo realizar a análise de um conjunto de dados contendo informações sobre o aluguel de bicicletas, processando e limpando os dados para extração de insights. Durante o desenvolvimento, além das perguntas iniciais, foram adicionadas duas perguntas extras que serão respondidas ao longo desta documentação, aprofundando ainda mais a compreensão do comportamento dos usuários.

Utilizando a linguagem Python e bibliotecas como Pandas, NumPy, Matplotlib e Seaborn, exploramos as tendências no aluguel de bikes, identificando as estações mais populares, os perfis de usuários e os horários de maior movimentação.

Os resultados desta análise podem ser utilizados para otimizar a distribuição de bicicletas, melhorar a infraestrutura das estações e aprimorar a experiência dos usuários.

# Processo
Para criar a análise de dados, a empresa disponibilizou um arquivo em formato CSV contendo informações detalhadas sobre o aluguel de bicicletas.

Inicialmente, carreguei o dataset utilizando a biblioteca pandas, explorando suas colunas e identificando possíveis inconsistências nos dados. Em seguida, realizei a limpeza e transformação das variáveis, incluindo conversão de datas, tratamento de valores ausentes e padronização de tipos de dados.

Embora o Python já seja eficiente para análise de dados, utilizei bibliotecas como matplotlib e seaborn para a exploração visual dos dados, permitindo uma melhor compreensão dos padrões e tendências do aluguel de bicicletas. Essa abordagem possibilitou insights mais detalhados sobre o comportamento dos usuários e ajudou na formulação das respostas às perguntas do projeto.

# Conclusão

Pergunta 1: Quais são as Top 5 estações com maior número de aluguel de bikes?

![image](https://github.com/user-attachments/assets/721720bd-613a-449b-bf6b-9c5efa1559ca)

Com base na análise dos dados representados no gráfico, identificamos as **Top 5 estações com maior número de aluguéis de bicicletas**. A estação **5265** se destaca significativamente como a mais utilizada, com **271 aluguéis**, seguida pelas estações **4834** com **64** aluguéis, **4633** com **41 aluguéis**, **6241** com **27 aluguéis**, e **6311**, que apresenta **1 aluguel**.

Este resultado evidencia uma concentração notável na utilização da estação 5265, indicando sua importância estratégica no sistema de compartilhamento de bicicletas.

A análise revelou que a demanda de bicicletas é afetada por feriados e condições climáticas. Dias de semana apresentam um padrão distinto em relação aos finais de semana.

Pergunta 2: Qual é o horário de maior movimento?

Os dados indicam que há dois picos de demanda: pela manhã (horário de deslocamento para o trabalho) e ao final da tarde.

Pergunta 3: Como os feriados afetam o aluguel de bicicletas?

A análise dos feriados mostrou que há um aumento no aluguel de bicicletas em feriados prolongados e um declínio em feriados isolados.

✅ Fontes

Os dados utilizados estão hospedados no seguinte repositório:

GitHub Dataset
