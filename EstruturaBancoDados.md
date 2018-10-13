# Estruturas do banco de dados. 

  Se a estrutura do banco de dados não for boa, haverá problemas para recuperar
  informações simples, será difícil trabalhar com os dados e causará arrepios
  toda vez que precisar adicionar ou excluir colunas em suas tabelas. 

## Ajuste finos. 

  1. **Nomes claros** o nome das tabelas devem ser claros e representar o
     assunto referente a tabela que pertence. Evite nomes ambíguo, vago de baixa
     clareza. 

     1.1. Nomes descritivos e significativos para todo. 
        Escolha nomes que sejam significativos para todos que acessam. Semântica
        e relevância são preponderantes. 

     1.2. Nomes claros e não ambíguo, ser especifico atômico. 

     1.3. Nomes devem ser únicos em toda tabela. 

     1.4. Evitar abreviação ou acrônimo para nomear as tabelas. 

     1.5. Sempre use na forma singular, uma coluna no plural implica que ela
     pode conter dois ou mais valores para a linha. 

  2. **Analisando as Colunas** a ideia e retirar a redundância

    2.1. A Coluna tem representação específica do assunto da tabela. A ideia é
        determinar se a coluna realmente pertence à tabela.  
    
    2.2. Certifica-se que a coluna contenha apenas um único valor. 
         Uma coluna pode conter vários valores e é conhecida como multivalorada. 
         Multi valores podem causar estragos em seu banco de dados,
         especialmente quando tentamos edita-los, quando garantimos que cada
         coluna armazena apenas uma único valor garantimos a integridades dos
         dados e informações precisas. 
    
    2.3. Cálculos ou informações concatenadas, os valores calculados são
         problemas para atualizações e manutenção dos dados. Havendo um ajuste em uma
         das partes que geram o cálculo esse mesmo resultado não será atualizado. 

    2.4. Certificar que a coluna apareça apenas uma vez no banco de dados.  










