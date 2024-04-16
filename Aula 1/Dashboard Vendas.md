---
# Importando e Tratando os Dados
---
As informações que vão alimentar o nosso Dashboard serão dados referentes aos produtos vendidos por uma empresa. As informações que temos em cada uma  das colunas são:
- Data da venda
- Produto
- Categoria
- PrecoUnitario
- CustoUnitário
- Marca
- Qtd. Vendida
- Nome Cliente
- Localidade
  
Cada linha da tabela representa uma venda de um determinado produto (além das informações adicionais envolvidas nessa venda).

Ao clicar em Transformar Dados, uma nova janela será aberta. Esta nova janela é o ambiente do Power Query, que é o editor de consultas do Power BI. Nesse ambiente nós vamos fazer os tratamentos necessários na base de dados para que ela fique correta para utilizarmos no Power BI.


A primeira edição que vamos fazer na tabela é deletar a última coluna da tabela (Column10). Muitas vezes o Power BI acaba importando colunas em branco. Como não há nenhuma informação na coluna, o melhor a se fazer é deletar essa coluna para não atrapalhar as nossas análises. Para deletar uma coluna você pode selecioná-la e pressionar a tecla Delete, ou pode selecioná-la e ir até a opção Remover Colunas.

Além de remover as colunas em branco é importante que você vá até a opção Remover Linhas > Remover Linhas em Branco dentro da guia Página Inicial. Essa opção vai eliminar todas as linhas com informações em branco. Dessa forma você vai garantir que não tem nenhuma informação em branco na sua base de dados e vai ter seus resultados corretos!
