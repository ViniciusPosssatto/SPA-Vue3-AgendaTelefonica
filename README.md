# SPA-Vue3-AgendaTelefonica

<p>A página foi baseada em uma lista de requisitos e funcionalidades para uma agenda telefonica, sendo eles:</p>

- Deve ser construída em uma única página HTML.
- Botão para adicionar novo contato;
- Modal de criação de contato - possuindo campos input de nome e telefone;
- Validações = nome deve possuir 2 palavras com no mínimo 3 letras cada. Telefone deve possuir máscara (##) #####-#### e ter a quantidade de números válidos. O formulário não deve permitir salvar sem estar validado e deve apresentar avisos para o usuário.
- Modal para edição do contato, possuindo as mesmas validações anteriores.
- Data-table na tela principal = listar todos os contatos sendo construído em 3 colunas: nome, telefone e uma terceira contendo 2 botões de editar e excluir contatos.
- Caso o telefone possua DDD 11 a linha do contato deverá ser azul.

## Construção da página

<p>A página foi construída em framework Vue3, utilizando a biblioteca vee-validate para validações no formulário e bootstrap para construção do template.</p>
<p>Foi adicionado um campo de busca, o qual procura contatos na lista a partir de qualquer letra ou palavra que for colocado.</p>
<p>A lista de contatos está sendo salva no localStorage do navegador para que a manipulação dos dados seja mais parecida com um bando de dados.</p>
<p>Por fim foi utilizado cores que combinam com o template e um estilo de lista "comum" para os usuários.</p>