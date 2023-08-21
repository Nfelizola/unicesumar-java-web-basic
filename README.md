# unicesumar-java-web-basic
Projeto básico para construção de sistemas para internet com Java

SEGUE PASSOS PARA O PROJETO NÃO TIUVE TEMPO UTIL PARA IMPLEMENTAR O CODIGO POIS ESTOU TRABALHANDO ATUALMENTE COM .NODEJS + REACT JS E REAT NATICE...
Configuração Inicial:

Configure o Apache Tomcat para executar o projeto.
Crie um novo projeto no NetBeans e configure-o para usar as tecnologias mencionadas (JSF, PrimeFaces, JPA, MySQL).
Criação de Entidades JPA:

Crie classes de entidade JPA para representar os usuários (Vendedor, Comprador, Administrador) e os produtos.
Defina as relações entre as entidades, como os produtos associados a um vendedor.
Implementação da Camada de Persistência:

Crie classes de acesso a dados (DAOs) para as entidades usando JPA.
Implemente métodos para inserir, atualizar, buscar e excluir registros no banco de dados.
Autenticação e Autorização:

Implemente um filtro de autenticação para verificar se o comprador está logado antes de permitir a realização de pedidos.
Implemente uma lógica para limitar o acesso de acordo com o tipo de usuário (vendedor, comprador, administrador).
Criação de Managed Beans:

Crie Managed Beans para lidar com a interação entre a camada de visão (JSF) e a camada de negócios.
Use o escopo de sessão para armazenar dados do carrinho de compras ou do usuário autenticado.
Criação das Interfaces (JSF e PrimeFaces):

Crie páginas JSF para cada tipo de usuário (vendedor, comprador, administrador).
Use componentes PrimeFaces para criar interfaces interativas e amigáveis.
Integração com Banco de Dados:

Nas páginas JSF, use os Managed Beans para interagir com os DAOs e mostrar informações dos vendedores, produtos e pedidos.
Funcionalidades de Administrador:

Implemente ações específicas para o administrador, como aprovação de cadastros e bloqueio de usuários.
Padrão de Interface (Facelet Template):

Crie um template Facelet para manter a aparência consistente em toda a aplicação.
Use os templates para incluir cabeçalhos, rodapés e outros elementos compartilhados.
Testes e Ajustes:

Teste a aplicação para garantir que todas as funcionalidades estejam funcionando corretamente.
Realize ajustes e melhorias com base no feedback e nos testes.

