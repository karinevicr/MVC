# Readme

# Arquitetura MVC - Karine Victoria
- Nome do Projeto: Abandono Zero
- Descrição: Este MVC é a idealização de um site com um questionário para pessoas que têm, tiveram, terão ou não têm interesse em cachorros. Os dados coletados serão usados pelo INSPA para compreender o abandono de cachorros e tomar medidas para mitigar essa questão.
- Arquitetura: MVC (Model-View-Controller)
- Ferramenta de Diagramação: draw.io

### Modelos (Models):

 ####  __Entidades:__

 __Usuário:__
 
 Atributos: ID, nome, email, senha, localização, idade e se tem, teve, deseja ter ou não tem interesse em ter um cachorro

__Formulário:__

Atributos: ID, respostas do formulário, nome do usuário

 __Relações:__
 - Um usuário pode ter mais de um cachorro
 - Um cachorro pode ter apenas um usuário
 - Um usuário pode responder apenas um formulário
 

### Controladores (Controllers):
- Controlador: Pesquisador

 #### __Responsabilidades:__
1. Recebe as informações contidas nos formulários de cadastro
2. Recebe os dados coletados no formulário
3. Valida e adiciona as respostas no banco de dados

#### __Métodos__

Registro: Nome, email, senha, CEP e localização

### Views (Views):
- Texto: Texto explicativo sobre cada parte do projeto.
- Navbar: Melhora a experiência do usuário, deixando links de fácil acesso.
- Imagem: Busca oferecer uma experiência mais agradável visualmente.
- Botão: Ajuda a acessar diferentes partes da plataforma.
- Formulário: Onde serão coletados os dados.

### Infraestrutura:
__Banco de dados:__ Utilizado para relacionar e armazenar dados dos usuários e cachorros 

__APIs externas:__ Utilizado para obter dados sobre raças de cachorros e dados sobre abandono animal


__Integração com MVC:__ 

1. O controlador faz interação com os modelos para acessar e manipular os dados coletados.
2. As views são renderizadas pelo controlador e mostram as informações aos usuários.
3. A infraestrutura, como o banco de dados e as APIs externas, é acessada pelos modelos e pelo controlador quando necessário.

### Justificações e implicações da Arquitetura:
- A Arquitetura MVC ajuda a organizar as ideias, deixando assim, o código mais organizado.
- Com a Arquitetura, o projeto fica bem estruturado para coletar os dados necessários.

