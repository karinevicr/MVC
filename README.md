# Readme

# Arquitetura MVC - Karine Victoria
- Nome do Projeto: Abandono zero
- Descrição: Esse MVC é a idealização de site com um questionário para pessoas que tem, tiveram, terão ou não se interessam por cachorros. Os dados coletados serão usados pelo INSPA para compreender o abandono de cachorros e tomar medidas para mitigar essa questão.
- Arquitetura: MVC (Model-View-Controller)
- Ferramenta de Diagramação: draw.io

### Modelos (Models):

 ####  __Entidades:__

 __Usuário:__
 
 Atributos: ID, nome, email, senha, localização, idade e se tem, teve, deseja ter ou não possui interesse em ter um cachorro

__Formulario:__

Atributos: ID, respostas do formulário, nome do usuário

 __Relações:__
 - Um usuario pode ter mais de um cachorro
 - Um cachorro pode ter apenas um usuario
 - Um usuario pode responder apenas um formulário
 

### Controladores (Controllers):
- Controlador: Pesquisador

 #### __Responsabilidades:__
1. Recebe as informações contidas nos formulários de cadastro
2. Recebe os dados coletados no formulario
3. Valida e adiciona as respostas no banco de dados

#### __Métodos__

Registro: Nome, email, senha, cep e localização


### Views (Views):
- Texto: Texto explicativo sobre cada parte do projeto.
- Navbar: Melhora a experiência do usuario, deixando links a facil acesso.
- Imagem: Busca odferecer uma experiência mais agradavel visualmente.
- Botão: Ajuda a acessar diferentes partes da plataforma.
- Formulário: Onde vai ser coletados os dados.

### Infraestrutura:
__Banco de dados:__ Ultizado para relacionar e armazenar dados dos usuarios e cachorros 
__APIs externas:__ Ultizado para ter dados sobre raças de cachorros e dados sobre abandono animal
__Integração com MVC:__ 

1. O controlador faz interação com os modelos para acessar e manipular os dados coletados.
2. As views são renderizadas pelo controlador e mostram as informações aos usuários.
3. A infraestrutura, como o banco de dados e as APIs externas, é acessada pelos modelos e o controlador quando é necessário.

### Justifique as escolhas feitas e como elas impactam o projeto.
#### Implicações da Arquitetura:
Descreva as implicações da arquitetura em termos de escalabilidade, manutenção, testabilidade e outros aspectos importantes.


