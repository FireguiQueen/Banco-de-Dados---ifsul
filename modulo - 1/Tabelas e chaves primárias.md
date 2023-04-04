# Tabelas
Uma tabela é composta por linhas (também chamadas de registros ou tuplas) e colunas (também chamadas de campos ou atributos). Cada linha representa um registro, enquanto cada coluna representa um atributo específico desse registro. Por exemplo, uma tabela de clientes pode ter colunas como "Nome", "Endereço", "Telefone", "E-mail".. 
</br>
Cada tabela tem um nome único, e seus campos são definidos pelo tipo de dados que podem armazenar. Por exemplo, uma coluna de "Nome" pode armazenar uma sequência de caracteres, enquanto uma coluna de "Data de nascimento" pode armazenar uma data.
</br>
As tabelas são inter-relacionadas através de chaves primárias e chaves estrangeiras, permitindo que os dados sejam consultados e combinados de várias formas. Por exemplo, uma tabela de pedidos pode ter uma chave estrangeira que referencia a tabela de clientes, permitindo que os dados dos pedidos sejam associados aos dados dos clientes.
</br>
As tabelas são a base para a organização e armazenamento de dados em um banco de dados relacional. Elas são criadas e gerenciadas por meio de comandos SQL, que permitem a criação, exclusão, alteração, consulta e manipulação dos dados armazenados nas tabelas.

## Resumo
* É criada para armazenar os dados
* Cada tabela descreve um determinado assunto 


</br>
</br>


## Chave primária
A chave primária é uma ou mais colunas, cujo seu papel é identificar os valores de uma linha.</br>
No exemplo abaixo, nossa chave primária é identificada como "codigo". 
Temos uma pequena tabela com uma lista de países, e cada país é representado por uma ÚNICA chave-primária. Ou seja, temos uma coluna chamada "países", cada linha desta coluna recebe um país, e este país é representado por um identificador, uma chave primária.  

![Exemplo-chave-primária-](https://user-images.githubusercontent.com/98475125/229939050-740b8baa-deb8-4347-b411-2a2a4c80fc50.png)

