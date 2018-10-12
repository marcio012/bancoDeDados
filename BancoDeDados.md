# Revisão de DB.

##Anatomia de um banco de dados.

  1. **Tabelas:** São as principais estruturas do banco de dados. Cada Tabela
     representa um único assunto ou "objeto" específico.
     O assunto de uma determinada tabela pode ser um objeto ou um evento, quando o
     assunto é um objeto, a tabela e algo tangível, como uma pessoa, um lugar ou
     uma coisa, quando o assunto e um evento, a tabela representa algo que ocorre
     em um determinado ponto no tempo e possui características a serem registradas. 

  2. **Linhas:** Representam uma instancia exclusiva do assunto de uma tabela
     que é composto de todo o conjunto de colunas da tabela, independente das
     colunas conterem ou não valores.

  3. **Chaves:** São colunas especiais que desempenha papeis muito especiais em
     uma tabela. O tipo de chaves determinam a finalidade na tabela. As duas
     mais importantes são _Primary Key_ e _Forengin Key_

     3.1 **Primary Key** consiste em uma ou mais colunas que identificam
     exclusivamente cada linha dentro de uma tabela quando a chave primaria é
     composta por duas ou mais colunas ela é chamada de _Chave Primaria
     Composta_. 

     3.2 **Foreing Key** consiste em uma chave que faz referencias a uma chave
     Primaria em uma outra tabela distinta.

  4. **Views** É uma tabela virtual composta de uma ou mais colunas de uma
     determinada tabela do banco. A tabela que compõe a exibição são conhecida
     como tabela base. As view permitem que você veja as informações do banco em
     diversas perspectivas.

##Relacionamento  

Quando duas ou mais tabelas estão interligadas ou relacionadas entre si. A
maneira pelo qual o relacionamento é estabelecido depende do tipo de
relacionamento. 

Existem três tipos de relacionamento: (um para um, um para muitos e muitos para
muitos). 

  1. **Um para um** -> Quando uma linha na tabela esta relacionada a apenas uma
     linha da segunda tabela e uma única linha na segunda tabela está
     relacionada a apenas uma linha na primeira tabela. 

     | **Tabala Principal** | -----------> | **Tabela Secundária** |
     |----------------------|:------------:| ---------------------:|
     |   _Chave Primaria_   | -----------> |   _Chave Secundária_  |















