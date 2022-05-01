## Curso de API Rest com .NET 5: operações essenciais com verbos HTTP


***Aula 01 - Incrementando o projeto*** 

- O EF Core é um framework pronto para gerar entidades e relacionamentos no sistema.
- O conceito de relacionamentos é importante para um sistema complexo.
- O EF Core 5 trouxe diversas mudanças que podem ser conferidas na documentação.

***Aula 02 - O relacionamento 1:1*** 

- Que relacionamento 1:1 é usado quando queremos estabelecer relacionamentos em que uma entidade possui exatamente uma outra como par.
- Que para criar relacionamentos 1:1 entre entidades precisamos alterar nossas properties e definir nosso DbContext.
- Que utilizamos o ModelBuilder para explicitar como o relacionamento será estabelecido.
- Que Lazy Properties são usadas quando queremos carregar informações de uma entidade que é propriedade de outra.

***Aula 03 - O relacionamento 1:n*** 

- Que um relacionamento 1:n estabelece uma relação entre uma entidade e muitas outras.
- Que relacionamentos 1:n com o Entity podem ser gerados de maneira similar ao 1:1.
- Que problemas de loops podem ser resolvidos com o AutoMapper em conjunto com o método CreateMap().
- A alterar o modo de deleção com o método OnModelCreating().
- Que a deleção em cascata remove a entidade e suas dependências.
- Como tornar um atributo de chave estrangeira opcional ou não através do método isRequired()..

***Aula 04 - O relacionamento n:n*** 

- Que um relacionamento de muitos para muitos é usado para relacionar muitos de uma entidade com muitos de outra entidade...
- Como gerar um relacionamento de muitos para muitos com o Entity.
- Que para quebrar um relacionamento de muitos para muitos em dois relacionamentos de um para muitos precisamos criar um modelo para representar o relacionamento.
- Utilizar o AutoMapper para calcular informações a partir de entidades diferentes em tempo de execução.

***Aula 05 - Executando consultas*** 

- Que query parameters são enviados através da URL a fim de tornar o GET mais criterioso.
- Como receber os parâmetros através do [FromQuery].
- Como realizar consultas através do encadeamento de métodos.
- Como realizar consultas com LINQ.

Site: **[Alura](https://cursos.alura.com.br/course/net-5-ef-core-relacionando-entidades)**
