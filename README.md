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

• **Estação 1** lidera com **6.311 aluguéis**, seguida de perto pela **Estação 27 (6.241)**, indicando que ambas são **pontos críticos de mobilidade**, possivelmente localizadas em áreas de alta circulação (ex.: centros comerciais, estações de transporte público).

• **Estação 271** destaca-se como a **terceira mais movimentada**, sugerindo relevância em uma região específica (ex.: parques, zonas residenciais densas).

• Apesar de a **rota 33 - 33** ser a mais frequente (da Pergunta 2), a Estação 33 não está entre as top 5 individualmente, o que pode indicar que seu uso está concentrado em trajetos de ida e volta (uso recreativo), sem alta demanda isolada.

Recomendações para Otimização:

**1. Aumento da Capacidade das Estações:**
Ampliar o número de bikes e vagas de estacionamento nas estações mais movimentadas (1 e 27) para evitar escassez durante picos de demanda.

**2. Manutenção Preventiva:**
Priorizar a inspeção e manutenção frequente de bikes e infraestrutura nessas estações, devido ao alto desgaste causado pelo uso intensivo.

**3. Otimização de Distribuição:**
Analisar padrões horários/diários de uso para realocar bikes estrategicamente, garantindo disponibilidade em horários e dias de pico.

> Pergunta 2: Quais são as Top 5 rotas, com base na estação inicial e final, e a média de duração de cada aluguel?

A tabela abaixo apresenta as 5 rotas mais frequentes, ordenadas pela quantidade de aluguéis (Qtd) e suas respectivas médias de duração:

![image](https://github.com/user-attachments/assets/c5162ffb-2acb-42ad-b368-50d34437c8de)

• **Rota 33 - 33:** Destaca-se pelo maior número de aluguéis (376) e maior duração média (30 minutos e 49 segundos), indicando uso recreativo ou de passeio, já que a estação inicial e final são a mesma.

• **Rotas 449 - 449 e 208 - 206:** Também apresentam alta demanda, com durações intermediárias (17 e 9 minutos), possivelmente para deslocamentos cotidianos.

• **Rotas 18 - 1 e 211 - 217:** Possuem médias de duração curtas (5 e 3 minutos), sugerindo uso para trajetos rápidos, como deslocamentos urgentes.

Recomendações para Otimização:

**1. Redistribuição de bicicletas:** Priorizar estações como 33 e 449, que apresentam alta demanda, para evitar falta de bicicletas ou vagas.

**2. Expansão de capacidade:** Aumentar o número de bicicletas e vagas nas estações 33, 18 e 211, que são pontos críticos de uso.

**3. Incentivos** para rotas menos utilizadas: Criar promoções ou descontos para rotas com menor demanda, equilibrando a distribuição de usuários.

> Pergunta 3: Quem aluga mais bikes, homens ou mulheres? Qual o tempo médio de aluguel de bikes?

![image](https://github.com/user-attachments/assets/ac838f75-98be-4dfb-ba51-fc7d833728f8)

Com base na análise dos dados apresentados, observa-se que, em relação ao número de aluguéis, os **homens** são os que mais utilizam o sistema de compartilhamento de bicicletas, com um total de **511.103 aluguéis**, enquanto as **mulheres** realizaram **175.224 aluguéis**. Isso indica uma clara **predominância no uso do sistema por homens.**

No entanto, quando se analisa o tempo médio de aluguel, as **mulheres** têm uma duração média ligeiramente superior, com **00:15:53**, enquanto os **homens** apresentam uma média de **00:15:30.** Essa diferença, embora pequena, sugere que, apesar de um número maior de aluguéis por parte dos homens, as **mulheres tendem a utilizar as bicicletas por um tempo médio levemente mais longo.**

Recomendações para Otimização:
**1. Incentivo ao Uso por Mulheres:** Criar campanhas promocionais voltadas ao público feminino, destacando segurança, conveniência e benefícios do uso das bicicletas.

**2. Ajuste na Distribuição das Bicicletas e Estações:** Como os homens utilizam mais o sistema, pode ser necessário um maior volume de bicicletas disponíveis nas estações com maior demanda masculina.

**3. Melhoria na Experiência do Usuário:** Disponibilizar bicicletas mais confortáveis para atender a diferentes perfis de usuários.

> Pergunta 4: Qual faixa etária aluga mais bikes? Qual o tempo médio de aluguel de bikes?

![image](https://github.com/user-attachments/assets/43cd5467-ee7c-464c-9de3-ee68c17582a1)




✅ Fontes

Os dados utilizados estão hospedados no seguinte repositório:

GitHub Dataset
