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

As seguintes recomendações podem ser implementadas para otimizar o serviço e melhorar a experiência dos usuários:

**1. Aumento da Capacidade das Estações:**
Ampliar o número de bikes e vagas de estacionamento nas estações mais movimentadas para evitar escassez durante picos de demanda.

**2. Manutenção Preventiva:**
Priorizar a inspeção e manutenção frequente de bikes e infraestrutura nessas estações, devido ao alto desgaste causado pelo uso intensivo.

**3. Otimização de Distribuição:**
Analisar padrões horários/diários de uso para realocar bikes estrategicamente, garantindo disponibilidade em horários de pico.

> Pergunta 2: Quais são as Top 5 rotas, com base na estação inicial e final, e a média de duração de cada aluguel?

Com base na análise das rotas de aluguéis de bicicletas, identificamos as Top 5 rotas mais frequentes, considerando a estação inicial e final, além da média de duração de cada aluguel. A tabela abaixo apresenta as rotas mais recorrentes, com suas respectivas quantidades de aluguéis (Qtd) e a média de duração de cada aluguel:

![image](https://github.com/user-attachments/assets/c5162ffb-2acb-42ad-b368-50d34437c8de)

Essas rotas representam as mais populares dentro do sistema de compartilhamento de bicicletas, com destaque para a **rota 33 - 33**, que possui o maior número de aluguéis e a maior média de duração, indicando um possível padrão de uso mais prolongado nessa rota. A análise dessas rotas permite um melhor entendimento dos hábitos dos usuários e pode auxiliar na otimização do sistema, como a redistribuição de bicicletas e melhorias nas estações mais utilizadas.

> Pergunta 3: Quem aluga mais bikes, homens ou mulheres? Qual o tempo médio de aluguel de bikes?

![image](https://github.com/user-attachments/assets/ac838f75-98be-4dfb-ba51-fc7d833728f8)

Com base na análise dos dados apresentados, observa-se que, em relação ao número de aluguéis, os **homens** são os que mais utilizam o sistema de compartilhamento de bicicletas, com um total de **511.103 aluguéis**, enquanto as **mulheres** realizaram **175.224 aluguéis**. Isso indica uma clara **predominância no uso do sistema por homens.**

No entanto, quando se analisa o tempo médio de aluguel, as **mulheres** têm uma duração média ligeiramente superior, com **00:15:53**, enquanto os **homens** apresentam uma média de **00:15:30.** Essa diferença, embora pequena, sugere que, apesar de um número maior de aluguéis por parte dos homens, as **mulheres tendem a utilizar as bicicletas por um tempo médio levemente mais longo.**

Essas informações podem ser úteis para entender os padrões de uso por gênero e auxiliar na otimização do sistema, como no ajuste das bicicletas e estações de acordo com o comportamento dos usuários.

> Pergunta 4: Qual faixa etária aluga mais bikes? Qual o tempo médio de aluguel de bikes?

![image](https://github.com/user-attachments/assets/43cd5467-ee7c-464c-9de3-ee68c17582a1)




✅ Fontes

Os dados utilizados estão hospedados no seguinte repositório:

GitHub Dataset
