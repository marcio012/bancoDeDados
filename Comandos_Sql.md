# Comandos SQL


  1. **SELECT**
    
    Esta é a cláusula principal da instrução de seleção e é absolutamente
    necessária, para especificar as colunas desejadas no conjunto de resultado
    da sua coluna. 

  2. **FROM** 

    Esta é a segunda cláusula mais importante na instrução SELECT e também é
    necessária. E usada para especificar as tabelas ou visualizações a partir
    colunas descritas na cláusula SELECT. 

  3. **WHERE** 
    
    É uma cláusula opcional usada para filtra as linhas retornadas pela cláusula
    FROM. Ela é seguida por uma expressão, que e definida tecnicamente como
    predicado que é avaliada como verdadeira, falsa ou desconhecida. Pode usar
    os operadores de comparação, operadores booleanos ou operadores especiais. 

  4. **GROUP BY**
    
    E usada para dividir as informações em grupos distintos. Essa cláusula e
    opcional geralmente usada com funções agregadas. 

  5. **HAVING** 

    Filtra o resultado das funções agregadas em informações agrupadas. É
    semelhante a cláusula WHERE e é seguida por uma expressão usando operadores
    de comparação padrão, booleanos e especiais. 

# Instruções de Select:

  ```sql
  SELECT _nomeDaColuna_ FROM _nomeDaTabela_ ;
  ````
  ---

  Técnicas para tradução de um pedido para o sql:

  Pedido: 
  
  Selecione o nome do assunto, o Id da categoria e o código do assunto na tabela
  assunto 

  ---

  Filtro: 

  Selecione _o_ nome do assunto, _o_ Id da categoria _e o_ código _do_ assunto _na tabela_
  assunto 

  ---

  Resultado: 

  ```sql
  SELECT nome-assunto, id-categoria, codigo-assunto FROM Assuntos; 
  ```
  


