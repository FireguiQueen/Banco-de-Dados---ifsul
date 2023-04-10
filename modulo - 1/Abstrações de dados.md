# Níveis de abstração
Assim como no mundo de desenvolvimento de software, para estruturarmos um banco de dados, também precisamos analisar o que será feito, ou seja, precisamos conversar com quem demanda o sistema. </br> As necessidades dos usuários é um passo crucial para a estruturação de um banco de dados eficiente e adequado às demandas do sistema. Além disso, é preciso considerar também questões como o volume de dados que serão armazenados, a complexidade das relações entre as diferentes tabelas e entidades do sistema, a segurança das informações e as exigências de desempenho e escalabilidade. </br> Em resumo, antes de qualquer coisa, precisamos compreender o problema e assim começar a desenvolver a estruturação do nosso banco de dados. </br>

_________________________________________________________________


### __Modelo conceitual__ </br>
O modelo conceitual é a __primeira__ fase da modelagem, onde iremos representar dados do mundo real por meio de uma visão simplificada dos dados e seus relacionamentos. Vamos precisar entender o que o cliente precisa e assim saberemos como modelar nosso banco de dados através das informações que o nosso cliente nos passou. </br>
Neste modelo, iremos ver todos os dados que serão necessários, vamos precisar saber quais dados serão relacionados. </br> </br>
Para fazermos tudo isso, usaremos o diagrama ER (entidade-relaciomanto).</br>
O modelo ER é baseado em três conceitos fundamentais: _entidades, relacionamentos e atributos_.  As entidades representam objetos do mundo real (como pessoas, produtos, pedidos, etc.) que são relevantes para o sistema a ser modelado. Os relacionamentos representam as associações entre as entidades (como "tem", "é dono de", "trabalha para", etc.). E os atributos representam as características ou propriedades das entidades (como nome, número de telefone, preço, etc.).

Exemplo sistema escolar:
Neste banco de dados iremos armazenar quem são os professores e quais são suas disciplinas.
Vamos supor, que cada professor possua apenas conhecimento de uma única disciplina.
Sendo assim, temos o seguinte modelo.:

* __Entidades:__ </br>
_professores_ e _disciplinas_ 

* __Relacionamentos:__ </br>
'x' professor dá aula de 'x' disciplina

* __Atributos:__ </br>
"CPF", "nome", "turno" e "disciplina" </br>
"Identificador" e "nome da disciplina"

![Abstração - conceitual - diagrama](https://user-images.githubusercontent.com/98475125/231009300-0fb7e110-f28e-449a-9cf2-d36fdf25e9f2.png)
Neste modelo acima, temos todos os dados representados por um diagrama. 
O retângulo representa identidades, ou seja, "professores" e "disciplinas"
O losango representa a relação que essas duas entidades possuem. 
E por final, o círculo em branco representa atributos de uma entidade, e o círculo preenchido pela cor preta representa que ele é um atributo identificador, ou seja, uma chave primária. 



#### Resumo
* Independente do DBMS (ainda não iremos usar um software DBMS, pois iremos usar diagramas);
* Modelagem inicial, permitindo que o cliente compreenda o que está sendo feito;
* Representação abstrata dos dados do mundo real em um diagrama simplificado;
* Modelagem inicial, permitindo que o cliente compreenda o que está sendo feito.

</br>
</br>

### __Modelo lógico__

<table>
    <thead> 
        <tr>
            <td>CPF</td>
            <td>Nome</td>
            <td>Turno</td>
            <td>Disciplina</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td> 083.146.417-80 </td>    
            <td> Jorge Augusto </td>    
            <td> manhã </td>
            <td> 1 </td>
        </tr>   
        <tr>
            <td> 081.136.657-80 </td>    
            <td> Adrian Butivesk </td>    
            <td> noite </td>
            <td> 3 </td>
        </tr>
    </tbody>    
</table>

<table>
    <thead> 
        <tr>
            <td>id</td>
            <td>disciplina</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td> 1 </td>    
            <td> Álgebra </td>    
        </tr>
        <tr>
            <td> 2 </td>    
            <td> Programação II (Java) </td>    
        </tr>
        <tr>
            <td> 3 </td>    
            <td> Inglês </td>    
        </tr>           
    </tbody>    
</table>

### __Modelo físico__




