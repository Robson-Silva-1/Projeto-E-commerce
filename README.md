# Projeto-E-commerce
Projeto do curso de Database experience
## Arquivo Projeto E-commerce
![Ordem](https://user-images.githubusercontent.com/111948561/189812120-d25025af-5cc0-4d5a-bf5e-ea6a5bb663f1.png)
![Universidade refinar](https://user-images.githubusercontent.com/111948561/189812155-301ae7f9-62a7-4173-861b-116faed7477a.png)
![E-commerce](https://user-images.githubusercontent.com/111948561/189812430-17012b77-3ea1-47f8-8b6e-5ba19a6dbb5e.png)
![Oficina mecanica](https://user-images.githubusercontent.com/111948561/190540252-664beb95-8f6d-4361-96f7-c9fc74d237c2.png)



       Category varchar (45)
);
## Criar Tabela pedido;
Create table request(
	   Idrequest int auto_increment primary key,
       Status varchar (45),
       Descrition Varchar (45),
       Value Varchar (45),
       idClient varchar (45)
);
## Criar Tabela Fornecedor;
Create table Provider(
       Idprovider int auto_increment primary key,
       corporate_name varchar(45),
       CNPJ Varchar (45),
       value varcharacter (45)
);
## Criar Tabela Estoque;
Create table inventory(
	   Idinventory int auto_increment primary key,
       Status varchar (45),
       Descrition Varchar (45),
       Value Varchar (45)
);
