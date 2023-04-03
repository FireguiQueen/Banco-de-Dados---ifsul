# DBMS - Date Base Manage System

É um software para nós, os desenvolvedores, gerenciarmos nosso banco de dados através de uma interface gráfica boa e organizada. Através desta interface, O DBMS nos permite.: </br>
_incluir, recuperar, consultar e alterar_ dados em um banco de dados. </br>

### Analogia 
Você está diante de uma enorme biblioteca, podemos pensar que a biblioteca é como um banco de dados, onde os livros seriam equivalentes aos dados. Você pode incluir livros (devolver livros), pegar emprestado (remover livros) e assim por diante. <br> 
Esta biblioca possui diversos livros, de diferentes cateogirias e autores. </br>
Para encontrar um livro específico, você possui duas opções, começar a procurar ou pedir ajuda a bibliotecária, que seberá exatamente onde se encontrar a estante que possui a categoria do livro. </br> Perceba que a bibliotecária é como se fosse um DBMS, pois para encontrar um livro específico, você irá precisar da ajuda dela, e quando você for incluir livros (devolver eles) você também irá precisar da ajuda dela. 

</br>

## Por que usar DBMS? 

* Segurança (é possível saber quem alterou, incluiu ou removeu dados do banco de dados) 
* A manuntenção torna-se mais simples
* Mais produtividade aos desenvolvedores

</br>

## E se não usarmos um DBMS?
Tecnicamente, é possível usar um banco de dados sem um DBMS, mas seria muito difícil gerenciar e acessar os dados sem o software adequado. </br>
Sem um DBMS, o desenvolvedor precisaria escrever código manualmente para manipular os dados, o que seria muito trabalhoso e sujeito a erros. Além disso, o desenvolvedor teria que gerenciar o armazenamento dos dados, garantindo que eles fossem organizados corretamente e que houvesse segurança contra falhas de hardware ou software. </br>
Portanto, é altamente __recomendável__ usar um DBMS para gerenciar um banco de dados, pois isso torna o processo muito mais eficiente, seguro e fácil de gerenciar.

</br>

## Software DBMS
- Oracle
- PostgreSQL
- MySQL
- Microsoft SQL Server


</br>
</br>

## ACID 
ACID é um acrônimo que representa as características essenciais que garantem a consistência, integridade e confiabilidade das transações em um sistema de gerenciamento de bancos de dados.

</br

__Atomicidade (Atomicity):__ garante que uma transação seja tratada como uma única unidade indivisível de trabalho. Se uma parte da transação falhar, toda a transação é revertida para o seu estado anterior. Ou seja, todas as operações da transação devem ser executadas com sucesso ou nenhuma delas deve ser executada.

__Consistência (Consistency):__ garante que uma transação leve o banco de dados de um estado válido para outro estado válido. Ou seja, as regras de integridade dos dados devem ser preservadas antes e depois de uma transação.

__Isolamento (Isolation):__ garante que várias transações possam ocorrer simultaneamente, sem que elas interfiram umas nas outras. Ou seja, as transações devem ser executadas de forma isolada, sem afetar outras transações em andamento.

__Durabilidade (Durability):__ garante que uma vez que uma transação tenha sido confirmada, ela permaneça no banco de dados mesmo que ocorram falhas de hardware, software ou interrupções do sistema. Ou seja, todas as alterações realizadas durante a transação devem ser salvas permanentemente no banco de dados.
