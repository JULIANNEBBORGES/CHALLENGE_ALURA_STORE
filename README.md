# CHALLENGE_ALURA_STORE
Esse projeto foi desenvolvido como parte do programa de ensino da Alura, em parceria com a Oracle Next Education (ONE), na formação em Data Science.

## 📋 Descrição do Projeto

O objetivo deste projeto é analisar dados de vendas, desempenho e avaliações de 4 lojas fictícias da Alura Store auxiliando o Sr. João no processo decisório de comercialização de uma de suas lojas, visando o fomento de capital para iniciar um novo empreendimento. A análise identifica a loja com menor eficiência com base em diversos indicadores de desempenho.

## 🔍 Métricas Analisadas

📈 Faturamento total das lojas <br>
🛍️ Categorias de produtos mais e menos vendidas <br>
☝️ Avaliação média dos clientes <br>
📦 Produtos mais e menos vendidos <br>
🚚 Frete médio por loja <br>
🌐 Distribuição geográfica das vendas (análise extra)

## 🛠️ Tecnologias Utilizadas

- **Python 3**: Linguagem principal
- **Pandas**: Manipulação e análise de dados
- **Matplotlib/Seaborn**: Visualização de dados
- **Google Colab**: Ambiente de desenvolvimento

## 📊 Visualizações Geradas

- Gráficos de barras para comparação de faturamento
- Gráficos de pizza para distribuição de categorias
- Gráficos de barras para avaliação média dos clientes
- Matriz de Correlação entre preço, frete e avaliação
- Visualização geográfica das vendas (análise extra)
- Resumo Comparativo das Lojas

## 📋 Estrutura do Projeto

├── AluraStore.ipynb # Notebook com análises e visualizações ├── README.md # Documentação do projeto └── dados/ # Dados utilizados nas análises ├── loja_1.csv ├── loja_2.csv ├── loja_3.csv └── loja_4.csv

## 🚀 Como Executar o Projeto

1. Clone este repositório:

   git clone https://github.com/juliannebborges/alura-store-analysis.git

2. Acesse o Google Colab e faça upload do notebook AluraStoreBr.ipynb

3. Execute todas as células para visualizar a análise completa

## 🐍 Indice no Google Colab 

  Na IDE o desafio foi estruturado da seguinte forma:
  
#👩‍💻 CHALLENGE ALURA STORE<br> 
##👩‍💻 Data Science<br> 
   🔗 link do challenge-alura-store plataforma Alura<br><br> 
##👩‍💻 Preparação do ambiente<br> 
    Importação das bibliotecas necessárias para resolução do desafio<br> 
    Configurações para melhorar a visualização dos gráficos<br> 
    Importação dos dados<br> 
    Adicionando identificador para cada loja<br> 
    Verificando a estrutura dos dados<br> 
    Combinando os dados de todas as lojas<br> 
    Verificando e Explorando os Dados Combinados<br> 
    Resumo estatístico dos dados numéricos<br> 
    Verificando valores ausentes<br><br> 
##👩‍💻 Faturamento<br> 
    Análise do faturamento<br> 
    Criando função para calcular o faturamento total de cada loja<br> 
    Visualização do faturamento através da função gráfico de barras<br><br> 
##👩‍💻 Vendas por Categoria<br> 
    Criando função para analisar vendas por categoria<br> 
    Categoria mais vendida<br> 
    Visualização das categorias por loja<br> 
    Criando gráficos de pizza para as categorias mais vendidas em cada loja<br><br> 
##👩‍💻 Média de Avaliação das Lojas<br> 
    Criando função para calcular a média de avaliação por loja def calcular_avaliacao_media(dados)<br> 
    Visualização da avaliação média<br><br> 
##👩‍💻 Produtos Mais e Menos Vendidos<br> 
    Top 5 produtos mais vendidos por loja<br> 
    Produtos mais vendidos por loja - Visualização através do método Gráfico de barras<br> 
    Top 5 produtos menos vendidos por loja<br> 
    Produtos menos vendidos por loja - Função Heatmap<br><br> 
##👩‍💻 Frete Médio por Loja<br> 
    Criando função para calcular o frete médio por loja<br> 
    Visualização do frete médio através da função gráfico de barras<br><br> 
##👩‍💻 Resumo Comparativo das Lojas<br> 
    Criando um dataframe de resumo para comparação<br> 
    Adicionando a categoria mais vendida<br> 
    Adicionando o produto mais vendido<br> 
    Análise de Correlação - Correlação entre preço, frete e avaliação<br> 
    Análise de faturamento por região (estado)<br><br> 
##👩‍💻 Análise Geográfica<br> 
    Verificando a distribuição geográfica das vendas<br><br> 
##👩‍💻 Relatório Final e Recomendação<br> 
    Identificação da loja com menor desempenho<br> 
    Criando critérios para avaliação<br> 
    Pontuação total (soma dos rankings)<br> 
    Loja recomendada para venda (menor pontuação total)<br> 
    Visualização da pontuação total<br> 
 🕵️‍♂️ Parecer Final<br> 
    
##📝 Resultados e Recomendação

  Mediante análise detalhada, foi possível identificar qual loja apresenta o menor desempenho considerando:
* Faturamento total
* Satisfação dos clientes
* Variedade de produtos
* Eficiência de operação (fretes)
<br>
O parecer final apresenta a recomendação sobre qual das unidades de negócio o sr. João deve vender encontra-se detalhada no encerramento do notebook.
<br>

##📚 Autora

   Juliane Borges, integrante do projeto ONE - Oracle Next Education.

##🙏 Agradecimentos

   Alura e Oracle Next Education pela oportunidade de aprendizado.
   Comunidade Alura pelos recursos e suporte.

