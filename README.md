# Segmentação de clientes usando K-means

Este projeto foi desenvolvido para aprimorar meu aprendizado na disciplina de Mineração de Dados do curso de Ciência de Dados. Os dados utilizados foram obtidos da plataforma Kaggle.

## Contexto

O projeto consiste na segmentação dos clientes de um shopping, que possui uma lista de clientes contendo informações como ID do cliente, idade, gênero, renda anual e pontuação de gastos (Spending Score). O Spending Score é atribuído com base em parâmetros como comportamento do cliente e dados de compra.

## Problema

Você é responsável por gerar insights e oferecer informações ao proprietário do shopping para entender melhor os clientes, identificando aqueles que podem ser facilmente convertidos em clientes-alvo. Essas informações serão usadas pela equipe de marketing para planejar estratégias direcionadas.

## Objetivo

Aplicar um modelo de Machine Learning ao conjunto de dados para responder as seguintes perguntas:

1. Como realizar a segmentação de clientes usando um algoritmo de aprendizado de máquina (K-Means) de forma simples em Python?

2. Quem são os clientes-alvo com os quais podemos iniciar uma estratégia de marketing (fáceis de abordar)?

## Estrutura do Projeto

1. **Importando Bibliotecas**:

    - Inclui todas as bibliotecas necessárias para a análise e modelagem, como pandas, numpy, matplotlib, seaborn e scikit-learn.

2.  **Análise Exploratória dos Dados (EDA)**:

    - Nesta fase, exploramos os dados para detectar padrões e tendências que auxiliarão na aplicação do modelo de segmentação.

    - Panorama Geral dos Dados: Revisão das estatísticas descritivas e verificação de valores ausentes.

    - Padrões de Compra por Gênero: Foi observado que as pessoas do sexo feminino gastam ligeiramente mais que as do sexo masculino, mas essa diferença não é significativa.

3. **Agrupamento com K-Means**:

    - Aplicando o Modelo K-Means: Realizamos a aplicação do algoritmo K-Means para identificar diferentes grupos de clientes com base nos dados fornecidos.

    - Análise dos Clusters: Foram identificados diferentes grupos de clientes, como aqueles com alta renda e altos gastos, e clientes com alta renda e gastos baixos. Cada cluster foi analisado para sugerir estratégias de marketing direcionadas.

4. **Refinamento da Segmentação e Análise Pós-Modelagem**:

    - Explorando Relações Multivariadas: Uma análise detalhada foi realizada após a modelagem inicial para entender melhor a segmentação, identificar outliers e ajustar os perfis dos clusters.

    - Essa etapa ajudou a refinar os grupos e validar a qualidade da segmentação, contribuindo para uma compreensão mais precisa do comportamento dos clientes e fornecendo orientações práticas para a área de marketing.

## Resultados e Conclusões

1. **Clusters Identificados**: Foram identificados clusters distintos que representam diferentes comportamentos de consumo, como:

    - Clientes com alta renda e altos gastos: Devem ser alvos de campanhas focadas em produtos ou serviços premium.

    - Clientes com alta renda e gastos baixos: Desafiam o marketing a entender suas preferências para ajustá-las.

    - Clientes com renda baixa e gastos médios: Podem ser envolvidos por meio de programas de fidelidade e promoções acessíveis.

2. **Sugestões de Ação**: As estratégias de marketing devem ser formuladas para engajar cada cluster de clientes de acordo com suas particularidades, levando em consideração os padrões de comportamento observados.

