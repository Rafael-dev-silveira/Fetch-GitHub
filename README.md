
Busca de Repositórios de Usuários na API do GitHub
=

Este projeto tem como objetivo demonstrar como integrar e consumir a API do GitHub para buscar e exibir os repositórios públicos de um usuário diretamente na interface de uma aplicação. Com ele, é possível explorar dados fornecidos pela API do GitHub, como nomes de repositórios, descrição, linguagem principal, número de estrelas e links para os repositórios.

Funcionalidades Principais
Busca de Usuário:
=

Campo de entrada para o nome de usuário do GitHub.

Ao enviar, os dados são solicitados à API do GitHub.

Exibição de Repositórios:


Lista dinâmica com informações sobre os repositórios do usuário buscado.
Cada repositório exibe detalhes como:
=
Nome
Descrição
Linguagem principal
Link para acesso ao repositório no GitHub.

Tratamento de Erros:
=

Mensagem de erro caso o usuário não seja encontrado ou a API retorne uma falha.

Interface Dinâmica e Responsiva:
=

Design minimalista e fácil de usar.
Responsivo para diferentes dispositivos.

Tecnologias Utilizadas
=
HTML e CSS: Estrutura e estilização básica.

JavaScript:

Consumo da API do GitHub utilizando fetch.
Manipulação do DOM para exibir os dados dinamicamente.

API do GitHub: Endpoint usado para buscar informações dos repositórios públicos do usuário.

Benefícios e Aprendizados
=
Compreensão de como consumir APIs RESTful.

Manipulação de respostas JSON e integração com interfaces de usuário.

Prática em lidar com erros e feedbacks ao usuário final.
