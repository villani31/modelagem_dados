# Modelagem de Dados

Uma boa modelagem de banco de dados faz com que a empresa obtenha vários ganhos de eficiência e produtividade. É por meio dessa estrutura formada por hardware, software, dados, pessoas e procedimentos que são feitas consultas ao sistema, com os mais diversos objetivos.

<p align="center">
  <img src="https://github.com/villani31/modelagem_dados/blob/main/img/img01.jpg?w=740" alt="Modelagem"height=400px >
</p>

A modelagem de dados é um processo mais preciso na geração de informações com qualidade, que geram valor para o negócio de uma empresa. Nessa etapa, são definida as estruturas das tabelas, entidades, associações e restrições para os dados, que serão armazenados e gerenciado em um banco de dados.
Por isso é importante entender o negócio e os dados que estão sendo coletados, para desenvolver essa modelagem de dados de forma adequada nas formas de negócio do software e da analise que será implementada, se definido de forma assertiva, facilitará na analise de informações estratégicas e na tomada de decisões correta.

## O que é modelagem de dados:

Criar um modelo que explique as características de funcionamento e comportamento que os dados serão disponibilizados, qual a relação entre as tabelas em um banco de dados. 

Uma modelagem bem definida é importante na identificação de melhorias, correções e novas funcionalidades, na analise ou produto a ser desenvolvido.

werewrwer

## Entidade e relacionamento (MER e DER):

São modelos e diagramas para projetar Banco de Dados relacionais, utilizando como base a relação de objetos reais, e sendo representado por meio de entidades e relacionamentos. 

MER (Modelo Entidade-Relacionamento) um modelo entidade relacionamento é uma maneira sistemática de descrever e definir um processo de negócio. É possível usar o MER para ilustrar como os dados são estruturados no processo do negócio, ou para detalhar como os dados são armazenados em um banco de dados relacional.

DER (Diagrama Entidade-Relacionamento), nada mais é que a representação gráfica do modelo MER. Em termos conceituais podemos dizer que o DER é um modelo diagramático que descreve o modelo de dados de um sistema com alto nível de abstração. Ele é usado para representar o modelo conceitual do negócio. 

Diagramas são criados para representar graficamente as entidades, atributos e relacionamentos, denominados DER (Diagrama Entidade-Relacionamento).

O MER permite representar de forma abstrata a estrutura que irá construir o banco de dados, é composto pelos seguintes objetos:

**** Entidades:
Qual quer coisa, seja uma pessoa, objeto, máquina, estrutura ou equipamento, desde que tenha existência física ou virtual, é chamado de entidade.

**** Atributos:
Todo objeto ou pessoa que existe em um espaço virtual ou físico, é possuidor de atributo. Por exemplo, um cliente tem como atributo, nome, endereço, idade, entre outros.

* Atributos Simples: Possuem apenas uma propriedade associada à entidade, por exemplo, o atributo nome da entidade pessoa;
* Atributos Compostos: Possuem mais propriedades associadas ao mesmo atributo, por exemplo, é o caso do endereço associado à entidade pessoa, pois ele possui os atributos logradouro, endereço, número, complemento, bairro e CEP;
* Atributos Monovalorados: Possui um único valor para a entidade, como por exemplo, o campo nome relacionado à entidade pessoa;
* Atributos Multivalorados: São atributos que possuem mais de um valor. Por exemplo, o caso do telefone associado à entidade pessoa, pois é possível não ter nenhum telefone ou ter vários.

**** Relacionamentos:
As entidades podem ser conectadas entre si, por meio de relacionamentos. Trata-se de uma estrutura que indica a associação de elementos de uma ou mais entidades.

* Relacionamento de cardinalidade 1:1: Denominado “um para um”, é usado quando um elemento da entidade X se relaciona com um elemento da entidade Y;
* Relacionamento de cardinalidade 1:n: Denominado “um para muitos”,  usado quando um elemento da entidade X se relaciona com um ou mais elementos da entidade Y;
* Relacionamento de cardinalidade m:n: Denominado “muitos para muitos”, é quando vários elementos da entidade X se relacionam com um ou mais elementos da entidade Y.

imagem

## Criando um Modelo de Dados.

Entendendo um pouco dos conceito, criei um modelo de banco de dados, que representa uma loja, nesse caso usei o banco de dados Mysql Server, mas o conceito e lógica, pode ser usada para qualquer banco de dados, ou também, sendo para criar um software, ou um projeto de Engenharia de Dados | Ciencias de Dados.

Nesse projeto foi criado 10 tabelas, e demosntrando o relacionamento entre as tabelas, conforme imagens:

<p align="center">
  <img src="https://github.com/villani31/modelagem_dados/blob/main/img/Diagrama_modelagem_DB.png?w=740" alt="Modelagem"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/modelagem_dados/blob/main/img/Diagrama_modelagem_DB_02.png?w=740" alt="Modelagem"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/modelagem_dados/blob/main/img/sql01.png?w=740" alt="Modelagem"height=400px >
</p>

<p align="center">
  <img src="https://github.com/villani31/modelagem_dados/blob/main/img/sql02.png?w=740" alt="Modelagem"height=400px >
</p>

Em um ambiente, como onde temos um ERP, não tem como ser criado um único modelo, ficaria muito dificil a visualização e entendimento, uma forma profissional de se fazer, seria criar modelos separada, como por exemplo (Modelo de vendas, Modelo de cadastro de cliente), de forma separada, visualmente, fica mais claro o entendimento.

## Conclusão

A transformação digital é um fenômeno que acontece, e vem acontecendo, a Big Data, vem se tornando uma arma poderosa para garantir a competitividade e retorno de resultado para o negócio. Para garantir um bom resultado do inicio ao fim do projeto, a modelagem de dados, ela que vai lidar  com todas as caracteristicas dos dados, variedade, volume, complexidade e valor.

Entendendo como os dados estão relacionados, de forma geral, traz um grande ganho, com entendimento do negócio, facilitando o desenvolvimento de um software, analise e criação de modelo por um cientista de dados, agilisando a entrega de um produto final.

----------------------------------------------------------------

Para conhecer mais sobre meus projetos:

**Links:**
* [LinkedIn](https://www.linkedin.com/in/thiagovillani)
* [Portfólio de Projetos](https://github.com/villani31/Data_Science)
