# Readme

# Arquitetura MVC - Karine Victoria
- Nome do Projeto: Abandono zero
- Descrição: [Insira uma breve descrição do seu projeto]
- Arquitetura: MVC (Model-View-Controller)
- Ferramenta de Diagramação: draw.io

### Modelos (Models):

 #### __Entidades:__

 __Usuário:__
 Atributos: ID, nome, email, senha, localização, idade e se tem, teve, deseja ter ou não possui interesse em ter um cachorro

__Formulario:__
Atributos: Id, respostas do formulário, nome do usuário

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

- Descreva os componentes de infraestrutura do seu projeto, como bancos de dados, APIs externas e outras dependências.
- Explique como a infraestrutura se integra à arquitetura MVC.


### Justifique as escolhas feitas e como elas impactam o projeto.
#### Implicações da Arquitetura:
Descreva as implicações da arquitetura em termos de escalabilidade, manutenção, testabilidade e outros aspectos importantes.


