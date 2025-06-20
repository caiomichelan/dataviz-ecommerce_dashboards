# Visualização de Dados - Painel Gerencial

## Data Analysis Project - Painel Gerencial de Inteligência de Negócio

<div align='center'>

![Dataviz](https://github.com/user-attachments/assets/67ab6be5-1718-44b8-b48f-d5b81ab2b6de)

</div>

# 1. Problema do Negócio

<p align='justify'>Uma empresa de e-commerce em fase de crescimento operava historicamente com decisões majoritariamente intuitivas. Embora essa abordagem tenha sustentado o progresso inicial, a ausência de análise aprofundada de indicadores resultou em prejuízos pontuais, evidenciando a necessidade de maior precisão estratégica.</p>
<p align='justify'>Reconhecendo a importância de um crescimento sustentável, a diretoria da empresa determinou uma mudança fundamental: a adoção da metodologia Data-Driven para todas as decisões estratégicas. Esta iniciativa visou erradicar a dependência de suposições, contribuindo para o desenvolvimento de uma cultura de tomada de decisão embasada em informações concretas.</p>
<p align='justify'>Considerando a relação custo-benefício e a familiaridade com o ambiente Microsoft, o Power BI foi selecionado pela diretoria como a ferramenta principal para este novo ciclo. A implementação foi faseada, com análises sendo desenvolvidas e entregues sequencialmente no Power BI Desktop, garantindo foco e resultados tangíveis a cada etapa.</p>
<p align='justify'>Como benefícios propostos por esta abordagem, foi esperado o desenvolvimento de Relatórios Gerenciais, também conhecidos como Dashboards, onde se buscou transformar grandes volumes de dados em insights visuais e acionáveis, facilitando a tomada de decisões estratégicas e o monitoramento contínuo da performance do negócio.</p>
<p align='justify'>Foram propostos os seguintes painéis de acompanhamento:</p>
<p align='justify'>- Visão Produto: Panorama sobre o desempenho do portfólio de produtos, indicando os produtos de maior e menor sucesso em vendas e o destaque por categoria. Essencial para decisões sobre oferta e sortimento.</p>
<p align='justify'>- Visão Pagamento: Detalha os métodos de geração de receita, identificando a prevalência de cada forma de pagamento, a ocorrência de cancelamentos, e o impacto financeiro de cada modalidade na receita.</p>
<p align='justify'>- Visão Pedidos: Apresenta o volume de transações, a distribuição entre os estados e uma avaliação sobre o desempenho em relação às metas propostas.</p>
<p align='justify'>- Visão de Avaliações de Produtos: Mensura o nível de satisfação dos clientes em relação aos produtos, destacando pontos fortes e áreas que requerem aprimoramento para otimizar a oferta e a experiência.</p>
<p align='justify'>- Visão Vendedores: Avalia a performance da equipe de vendas, indicando o desempenho individual, a contribuição por categoria e oportunidades para otimizar as estratégias de vendas.</p>
<p align='justify'>- Visão Vendas: Oferece um resumo executivo do faturamento geral, tendências de crescimento, eficácia das campanhas de vendas e análises de Pareto e Retenção de Clientes (Cohort).</p>

## 2. Premissas do Negócio

<p align='justify'>Foram consideradas dez bases de dados:</p>

<p align='justify'>- Produtos ("products_dataset"): Detalha os produtos vendidos, incluindo nomes, descrições, categorias e dados técnicos.</p>
<p align='justify'>- Pagamentos ("order_payments_dataset"): Registra todas as transações financeiras, como valores, métodos de pagamento utilizados pelos clientes e status de cada pagamento.</p>
<p align='justify'>- Pedidos ("orders_dataset"): Contém informações gerais sobre cada compra, incluindo status do pedido, datas de criação e entrega, e o cliente associado.</p>
<p align='justify'>- Itens do Pedido ("order_items_dataset"): Detalha o conteúdo de cada pedido, especificando quais produtos foram comprados, a quantidade, o preço por item e a data de envio.</p>
<p align='justify'>- Avaliações de Produtos ("order_reviews_dataset"): Contém o feedback dos clientes, incluindo notas (scores), comentários e a data da avaliação, refletindo a satisfação.</p>
<p align='justify'>- Vendedores ("sellers_dataset"): Informações sobre os lojistas da plataforma, como ID, cidade, estado e dados de contato.</p>
<p align='justify'>- Clientes ("customers_dataset"): Cadastro dos clientes, incluindo ID, cidade e estado, auxiliando na compreensão da localização dos compradores.</p>
<p align='justify'>- Tabela de Geolocalização ("geolocation_dataset"): Dados de geolocalização para cruzamento de informações e possibilidade de plotagem em mapas.</p>
<p align='justify'>- Tabela de Tradução das Categorias de Produto ("product_category_name_translation"): Utilizada para tradução da nomenclatura das categorias dos produtos entre português e inglês.</p>
<p align='justify'>- Tabela Calendário: Tabela de dimensão criada no Power Query especificamente para este projeto, contendo todas as datas do período analisado e servindo como base para análises temporais.</p>

## 3. Estratégia da Solução

<p align='justify'>A estratégia de solução foi focada na construção de relatórios gerenciais visuais no Power BI, precisamente desenhada para eliminar a dependência de suposições e impulsionar uma cultura de decisão embasada em fatos.</p>
<p align='justify'>Com a familiaridade com o ambiente Microsoft e a relação custo-benefício em mente, o Power BI Desktop se destacou como a ferramenta central para essa transformação. A implementação faseada dos painéis foi crucial, permitindo que cada etapa gerasse resultados tangíveis e mantivesse o foco nas perguntas de negócio mais críticas. Através de reuniões colaborativas com a gestão e a equipe de negócio, traduzimos suas principais indagações em visões de dados acionáveis, resultando na elaboração de dashboards essenciais para o monitoramento contínuo da performance e a tomada de decisões estratégicas.</p>
<p align='justify'>Os painéis desenvolvidos foram estruturados para oferecer uma compreensão geral do negócio:</p>
<p align='justify'>- Menu Principal de Navegação:</p>
<div align='center'>

![Menu](https://github.com/user-attachments/assets/5d97110e-8293-475c-9d02-15392fcd87f5)

</div>
<p align='justify'>- A Visão Produto fornece um panorama detalhado do portfólio, identificando sucessos e oportunidades por categoria, crucial para otimizar a oferta:</p>
<div align='center'>

![Product](https://github.com/user-attachments/assets/0f9aa266-da0e-4b94-8ba1-d040c27d9e41)

</div>
<p align='justify'>- A Visão Pagamento desvenda a dinâmica financeira, mostrando a prevalência das modalidades e seu impacto na receita, incluindo cancelamentos:</p>
<div align='center'>

![Payment](https://github.com/user-attachments/assets/7d604835-9820-4790-9d7b-7cf238ceea3c)

</div>
<p align='justify'>- A Visão Pedidos acompanha o volume de transações, distribuição geográfica e desempenho em relação às metas, essencial para o controle operacional:</p>
<div align='center'>

![Order](https://github.com/user-attachments/assets/80bc9873-763d-40f8-acba-7f691c442bdf)

</div>
<p align='justify'>- A Visão de Avaliações de Produtos mede a satisfação do cliente, destacando áreas de força e pontos para aprimoramento na experiência do cliente:</p>
<div align='center'>

![Review](https://github.com/user-attachments/assets/2b9aa298-eb4b-43f9-8bc9-22e4a7811bc9)

</div>
<p align='justify'>- A Visão Vendedores avalia a performance individual e coletiva da equipe de vendas, revelando oportunidades de otimização de estratégias:</p>
<div align='center'>

![Seller](https://github.com/user-attachments/assets/d93cf97a-035e-4750-bb67-fa46e18b1b72)

</div>
<p align='justify'>- A Visão Vendas oferece um resumo executivo do faturamento, tendências, eficácia de campanhas, além de análises de Pareto e Retenção de Clientes (Cohort), fornecendo uma perspectiva abrangente sobre a saúde do negócio:</p>
<div align='center'>

![Sales](https://github.com/user-attachments/assets/6e14e365-9e8e-4fc8-8acb-bbb8eea0c505)

</div>
<p align='justify'>Essa abordagem não apenas responde às perguntas de negócio com clareza visual, mas também capacita a diretoria e a equipe de negócio a monitorar, analisar e reagir proativamente às dinâmicas do mercado, assegurando que o crescimento da empresa seja robusto, sustentável e, acima de tudo, orientado por dados.</p>

## 4. Insights de Dados

<p align='justify'>Alguns insights obtidos através das análises:</p>
<p align='justify'>- Produtos: As Top 5 Categorias com mais produtos representam 40% do total das 74 categorias: “Cama, Mesa e Banho”, “Esporte e Lazer”, “Móveis e Decoração”, “Saúde e Beleza” e “Utilidades Domésticas”. Em paralelo, estas categorias figuram nas Top 6 categorias com mais fotos de produto.</p>
<p align='justify'>- Pagamento: Pagamentos em Cartão de Crédito representam 73,9% do total de pagamentos, com 78,3% do faturamento total, seguido pela modalidade de Boleto, com representatividade de 19%, e 18% do faturamento total.</p>
<p align='justify'>- Pedidos: Clientes do estado de SP lideram com 42% do total de pedidos realizados, seguido pelos estados do RJ e MG, com 12,9% e 11,7%, respectivamente.</p>
<p align='justify'>- Avaliações de Produtos: A avaliação “Ótima” figura no topo, com 77% do total. As avaliações “Média” e “Péssima” figuram no mesmo patamar, com aproximadamente 11,4% do total, cada.</p>
<p align='justify'>- Vendedores: O estado de SP concentra o maior número de vendedores, representando 59,7% do total, seguido pelos estados do PR e MG, com 11,3% e 7,9%, respectivamente.</p>
<p align='justify'>- Vendas: O estado de SP lidera o número de vendas, com 38,3% de representatividade frente aos demais, seguido dos estados do RJ e MG, representando 13,4% e 11,7% do total de vendas, respectivamente.</p>

## 5. Produto Final

<p align='justify'>O produto final desta solução são Relatórios Gerenciais Visuais, também conhecidos como Dashboards, desenvolvidos no Power BI Desktop.</p>
<p align='justify'>Esses dashboards são compostos por diversos painéis de acompanhamento (Visão Produto, Visão Pagamento, Visão Pedidos, Visão de Avaliações de Produtos, Visão Vendedores e Visão Vendas) que permitem transformar grandes volumes de dados em insights acionáveis para facilitar a tomada de decisões estratégicas e o monitoramento contínuo da performance do negócio.</p>

## 6. Conclusão

<p align='justify'>A transição de decisões intuitivas para uma cultura Data-Driven é um passo estratégico fundamental para organizações que buscam crescimento sustentável. A implementação de dashboards visuais no Power BI não apenas resolve a dependência de suposições, mas capacita a organização a transformar dados brutos em inteligência acionável.</p>
<p align='justify'>O produto final, um conjunto de relatórios gerenciais intuitivos e abrangentes, permite o monitoramento contínuo da performance e a tomada de decisões ágeis, garantindo que cada movimento do negócio seja embasado em fatos concretos e orientado ao sucesso.</p>

## 7. Próximos Passos

<p align='justify'>Como próximos passos, os painéis existentes poderão ser refinados, com adição de novas métricas, dimensões ou filtros, bem como a criação de novas visões que atendam a necessidades identificadas e otimização das visões para acesso via dispositivos móveis.</p>
<p align='justify'>Também poderão ser implementadas novas visões que aprofundem análises específicas, como lucratividade por cliente, um funil de vendas detalhado, e uma visão estratégica que correlaciona dados de vendas, previsões de demanda e níveis de estoque, impactando diretamente na satisfação do cliente e na eficiência operacional.</p>
