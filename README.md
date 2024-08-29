Projeto CRUD em Java com DAO, JDBC e Orientação a Objetos

Descrição

Este projeto é um exemplo de implementação de um sistema CRUD (Create, Read, Update, Delete) em Java, utilizando o padrão DAO (Data Access Object) para abstração do acesso a dados, JDBC (Java Database Connectivity) para interação com o banco de dados e conceitos de orientação a objetos para organização do código.

Funcionalidades

 - Cadastrar: Permite a criação de novos registros no banco de dados.
 - Consultar(por Id ou por Departamento): Permite a leitura de registros armazenados no banco de dados.
 - Atualizar: Permite a modificação de registros existentes no banco de dados.
 - Excluir: Permite a remoção de registros do banco de dados.

Tecnologias Utilizadas

- Java 8+: Linguagem de programação utilizada.
- JDBC: API para conexão com o banco de dados.
- MySQL: Banco de dados relacional.

Pré-requisitos

- JDK 8+: Certifique-se de ter o Java Development Kit instalado.
- Banco de Dados MySQL: Configurado com as tabelas necessárias.
- IDE de sua escolha: Como Eclipse, IntelliJ IDEA ou NetBeans.

Configuração

1 . Clone o repositório:
git clone https://github.com/seu-usuario/seu-repositorio.git

2 . Configure a conexão com o banco de dados no arquivo Conexao.java:

public class Conexao {
    private static final String URL = "jdbc:mysql://localhost:3306/seu_banco_de_dados";
    private static final String USER = "seu_usuario";
    private static final String PASSWORD = "sua_senha";
    
    // Código de conexão...
}
ou *via Db.properties*

3 . Execute o projeto na sua IDE de preferência.

4 . Uso

- Cadastrar: Utilize os métodos save() dos DAOs para adicionar novos registros.
- Consultar: Utilize os métodos findById() ou findAll() dos DAOs para recuperar registros.
- Atualizar: Utilize o método update() dos DAOs para modificar registros existentes.
- Excluir: Utilize o método delete() dos DAOs para remover registros.

Sinta-se à vontade para abrir issues e pull requests para melhorias.

Contato
Márcio Jorge - marciojorgemelofilho@gmail.com
