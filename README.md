## Contexto e descrição

- Temos um conjunto de Base de Dados com informações sobre os produtos (`dim_produto.csv`), vendedores (`dim_vendedor.csv`), e sobre as vendas de uma loja de brinquedos (`fato_vendas.csv`).
- A Base de vendas fornece informações como a data da venda, o produto vendido, o vendedor, a quantidade vendida naquela compra, o calor total e o custo da venda.
- [TecToy-Sales](https://app.powerbi.com/view?r=eyJrIjoiNmYzMDYyOGQtNDI5OC00Nzg0LThiYWMtODIwZDI0Yzc2NzhhIiwidCI6ImRmY2E2YzQyLWM0NjktNDg1Ny05NDk5LWViN2YzNjczZjY4NCJ9): Este projeto analisa as vendas de uma loja de brinquedo. 


# TecToy-Sales

Clique na imagem para visualizar o dashboard interativo no Power BI:


[![ProjetoGame](https://github.com/arthurffc8/TecToy-Sales/blob/main/TecToy-Sales.png)](https://app.powerbi.com/view?r=eyJrIjoiNmYzMDYyOGQtNDI5OC00Nzg0LThiYWMtODIwZDI0Yzc2NzhhIiwidCI6ImRmY2E2YzQyLWM0NjktNDg1Ny05NDk5LWViN2YzNjczZjY4NCJ9)



## Estrutura do Projeto

- **`dim_produto.csv`**; Base de dados com as informações dos produtos da loja.
- **`dim_vendedor.csv`**; Base de dados com as informações dos vendedores.
- **`fato_vendas.csv`**; Informaç de cada venda da loja.

  
## Ferramentas Utilizadas

- **Power Query**: Utilizado para limpar e modelar os dados.
- **Power BI**: Utilizado para criação das medidas, de dashboards interativos e visualizações avançadas.


  
## Principais Métricas calculadas e Insights 

- **Itens Vendidos**: Total de Itens vendidos.
- **Faturamento**: Soma do faturamento total da loja.
- **Custo**: Soma do custo total da loja.
- **Margem de Lucro**: Lucro obtido pela loja.
- **Faturamento por mês**: Soma do faturamento obtido em cada mês.
- **Margem de Lucro por subcategoria**: Ranking com as subcategorias com maior margem de lucro.
- **Ranking de vendedores**: Ranking com os vendedores com maior faturamento.


 ## Dicas Adicionais 

 - **Filtros**: É possível filtrar todas as informações por ano, mês ou categoria.
 - **Variação do Custo**: É possivel verificar quanto o lucro varia com a variação do custo. Para isso basta auemntar ou diminuir o custo e observar os efeitos que geram no nosso lucro. Por exemplo: É possível perceber que ao dimunuir o custo em 50%, obteríamos um lucro 25% maior.
   



## Conclusão 

- **Maarço**: Março foi o mês com melhor desempenho nas vendas.
- **Alta margem de lucro**: A loja aintgiu uma margem de lucro de 50,1%.



