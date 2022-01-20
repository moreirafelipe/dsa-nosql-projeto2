## **Curso - Modelagem de Bancos de Dados relacionais, Não Relacionais e Data Stores - Data Science Academy** 



#### Projeto 2: Design e implementação de Modelo de dados no Apache Cassandra com carga de dados 



#### 📓 Especificações e contexto do Projeto



Uma empresa vende produtos de beleza através de um website. São milhares de pedidos por dia e os gestores precisam de relatórios para tomar decisões sobre campanhas de Marketing quase em tempo real. 

Atualmente a empresa armazena os dados em um banco de dados relacional onde são realizadas as consultas. O problema é que as consultas são muito lentas uma vez que o volume de dados é muito alto.

A empresa ouviu dizer que poderia otimizar suas consultas usando um banco de dados NoSQL e os gestores convidaram você para demonstrar como o Apache Cassandra poderia ser usado para resolver esse tipo de problema.



#### 🌐 Recursos externos



De todos os relatórios, três são de extrema importância:

1. Total de vendas pela fonte de onde o cliente acessou o website (Facebook, Twitter,Afiliado, etc...). A empresa realiza campanhas nas redes sociais e precisa saber sobre a efetividade desses canais.

2. Total  de  vendas  por  estado  de  onde  o  cliente  fez  o  acesso  ao  website.Isso  é importante para prever custos de entrega e pagamento de impostos.

3. Média de desconto por estadoe por data do pedido.



O objetivo é cruzar os dados a fim de otimizar os custos.



A empresa forneceu dois arquivos:•Clientes.csv possui dados cadastrados dos clientes.•Pedidos.csv possuios registros dos pedidos. A coluna Id_Cliente conecta os registros de ambos os arquivos.Os arquivos podem ser encontrados ao final do capítulo.



#### 🔨 Desenvolvimento e implementação



Crie  o  modelo  de  dados  no  Apache  Cassandra  e  carregue  os  dados  para  atender  a demanda dos gestores.



#### 💻 Tecnologias envolvidas

Apache Cassandra

Db Schemma

PySpark