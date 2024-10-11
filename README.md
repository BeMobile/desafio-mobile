# Teste Técnico Mobile BeTalent

Este é um repositório para Testes Técnicos em Mobile da Be. Ele é destinado a pessoas que participam de nossos processos seletivos. 

Se você chegou até aqui por meio de um formulário de Teste Técnico, siga em frente. Caso contrário, acompanhe a BeTalent no [Linkedin](https://www.linkedin.com/company/betalenttech), [Instagram](https://www.instagram.com/betalent.tech/), [Facebook](https://web.facebook.com/bemobile.tech) ou na nossa newsletter [BeTalent Academy](https://beacademy.substack.com/). Divulgamos novos processos seletivos por lá.

## Desafio

O Teste Técnico Mobile BeTalent consiste em construir a visualização de uma tabela com dados que virão de uma API simulada.

### Mockup

Este é o [projeto em Figma](https://www.figma.com/design/Lpdera6rS8SztMUAwzkpN0/Teste-T%C3%A9cnico-Mobile-BeTalent?node-id=1-4&node-type=canvas&t=NI5lQZvrO1hsQCqz-0) para você se orientar. Nele, você encontrará o guia de estilos e o design da tela a ser construída.

### Requisitos Gerais

Deve-se utilizar React Native ou Flutter para a construção da aplicação.

É permitido utilizar libs externas, mas recomenda-se que seja o mínimo possível.

A tabela deve conter as seguintes colunas:

- imagem (thumb do/a usuário/a);
- nome;
- cargo
- data de admissão;
- telefone.

Também deve ser possível realizar pesquisa na tabela por meio de um input. O input de pesquisa deve permitir filtrar dados por cargo, nome e telefone.

Datas e telefones devem ser formatadas no front-end e não na API.

Tenha instaladas em sua máquina as ferramentas [Git](https://git-scm.com/), [Node.js](https://nodejs.org/en/) e [Yarn](https://yarnpkg.com/), e [React Native](https://reactnative.dev/) ou [Dart](https://dart.dev/) e [Flutter](https://flutter.dev/), para poder trabalhar no projeto.

### Acesso aos dados da API simulada

Para ter acesso aos dados que alimentarão o projeto, faça o seguinte:

1. caso você não tenha, instale o pacote [json-server](https://github.com/typicode/json-server);
2. clone este repositório do GitHub em sua máquina: [https://github.com/BeMobile/desafio-mobile](https://github.com/BeMobile/desafio-mobile);
3. entre na pasta do projeto, em sua máquina, e, por meio da linha de comando, execute o comando `json-server --watch db.json`, para consumir a API simulada;
4. inicie a estrutura e o desenvolvimento do projeto.

É necessário deixar o json-server rodando no terminal para que os dados sejam visualizados no projeto.

Caso você tenha problemas com o json-server, tente rodá-lo com `npx json-server db.json` ou 
com `yarn json-server <path>/db.json`, em que `<path>` é o caminho completo até o diretório em que o arquivo db.json está localizado. Se mesmo assim não funcionar, busque ajuda na web.

### Critérios de Avaliação

Em ordem de relevância, avaliaremos:

1. lógica de programação;
2. organização (do código e dos arquivos);
3. proficiência no uso de React Native e/ou Flutter;
4. README, que deve conter, pelo menos, as seguintes informações: sobre o projeto, pré-requisitos e instruções para rodar a aplicação.

É um diferencial na avaliação o uso de TypeScript.

### Envio da Solução

O projeto deverá ser hospedado em um repositório no seu GitHub. O link do repositório deverá ser fornecido por meio do formulário de Teste Técnico encaminhado ao seu e-mail. Não serão aceitos links de projetos enviados por outros meios.

Demais instruções e regras serão instruídas nos formulários e nas comunicações do processo seletivo do qual você está participando.
