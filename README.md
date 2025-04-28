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

   git clone https://github.com/JULIANNEBBORGES/CHALLENGE_ALURA_STORE

2. Acesse o Google Colab e faça upload do notebook AluraStoreBr.ipynb

3. Execute todas as células para visualizar a análise completa
    
## 📝 Resultados e Recomendação

Mediante análise detalhada, foi possível identificar qual loja apresenta o menor desempenho considerando:
* Faturamento total<br>
⬇️ Visualização do faturamento através da função gráfico de barras.
     ![image](https://github.com/user-attachments/assets/c220d74a-bf95-40b9-b39f-083b0d6705ca)

* Satisfação dos clientes<br>
    ![image](https://github.com/user-attachments/assets/653acb17-ad65-478c-9df6-78fcae1ef4b7)

* Variedade de produtos<br>
   ![image](https://github.com/user-attachments/assets/e67934c0-94c1-42ba-ac5c-06cc443c28d4)

<br>⬇️ Sobre o gráfico:<br>

Cada barra representa uma categoria de produto, e a altura da barra representa a quantidade de vendas. As cores diferentes das barras representam as as quatro unidades de negócio do sr. João.
A respresenta visual possibilita, facilmente, comparar as vendas de cada categoria de produto em cada loja e identificar quais produtos são mais populares em cada uma delas.
Uma avaliação visual identifica que quando a variável target é a categoria móveis o ranking das lojas com maior venda é a loja 3.
Ao analisar a categoria eletrônicos, as lojas 3 e 4 apresentam vendas bem similares.

<br>⬇️ Criando gráficos de pizza para as categorias mais vendidas em cada loja.<br>
   ![image](https://github.com/user-attachments/assets/077ee97a-3214-4635-8512-c72743b5563e)

<br>⬇️ Produtos menos vendidos por loja - Função Heatmap<br>
   ![image](https://github.com/user-attachments/assets/b53638ed-f02c-4d39-9b65-579e0375c21e)

* Eficiência de operação (fretes)
   ![image](https://github.com/user-attachments/assets/a5fb9b66-8429-46e8-852a-e998312f76d7)

O parecer final apresenta a recomendação sobre qual das unidades de negócio o sr. João deve vender, encontra-se detalhada no encerramento do notebook.
<br>

##📚 Autora

   Juliane Borges, integrante do projeto ONE - Oracle Next Education.

##🙏 Agradecimentos

   Alura e Oracle Next Education pela oportunidade de aprendizado.
   Comunidade Alura pelos recursos e suporte.

