# Vaga programador PHP - 2020 - Inspetoria São João Bosco

> Tudo que for desenvolvido não será utilizado comercialmente e a única intenção é de avaliar o conhecimento atual do candidato

## Observações Gerais

O objetivo deste teste é conhecer as habilidades do candidato em:
- Programação PHP / Laravel
- Organização (código/arquivos)
- Controle de versão
- Análise de requisitos
- Modelagem de Banco de Dados
- Utilização de frameworks/libs de frontend JS (Jquery, React ou vanilla)
- Utilização de frameworks/libs de frontend CSS (Bootstrap ou vanilla)
- Capricho (atenção com urls, metatags, validações, modelagem, nomenclatura, ...)

Fora do que foi definido de ferramentas e tecnologias acima, sinta-se livre para usar qualquer pacote adicional que encontre necessidade.

**Tente realizar todos os itens, porém, mesmo que não termine, me envie no prazo o que você conseguiu realizar.**

Qualquer dúvida, estarei disponível para contato no e-mail vinicius.gusmao@salesiano.br.

## Prazo
Uma semana.

## Requisitos
- Usar o Laravel
- Usar banco de dados Mysql

## Qual é o teste ?
Construir uma aplicação para listar informações básicas de uma escola (cursos, séries, turmas e alunos).

## O que deve ser feito ?
As seguintes funcionalidades deverão ser implementadas:
- Área autenticada com login e senha
- Após login, a tela inicial da aplicação deverá mostrar as informações da Escola.
- CRUD Cursos (Cadastro, edição, exclusão e leitura)
- CRUD Séries (Cadastro, edição, exclusão e leitura)
- CRUD Turmas (Cadastro, edição, exclusão e leitura)
- CRUD Alunos (Cadastro, edição, exclusão e leitura)
- Relacionamentos:
	- Uma escola possui vários cursos (1 - N)
	- Um curso possui várias séries (1 - N)
	- Uma série possui várias turmas (1 - N)
	- Uma turma possui vários alunos (1 - N)
- Consultas obrigatórias:
	- Consultar alunos de uma determinada TURMA
	- Consultar turmas por turno (MATUTINO ou VESPERTINO)
	- Consultar séries por curso.
- Implementar logout da aplicação
- Implementar responsividade no layout
- Validações básicas no lado do frontend e backend

## Modelos
O modelo do Usuário deverá conter (mas não limitado a):
- Nome
- E-mail
- Senha

*Não é necessário fazer o CRUD de Usuário. O cadastro do primeiro usuário deve ser feito utilizando Seeds e o cadastro de outros usuários pode ser manual dentro do banco de dados.*

O modelo da Escola deverá conter (mas não limitado a):
- Nome
- Sigla
- Telefone
- Cidade
- Estado

*Não é necessário fazer o CRUD de Escola. O cadastro da primeira escola deve ser feito utilizando Seeds ou manualmente dentro do banco de dados.*

O modelo de Curso deverá conter (mas não limitado a):
- Nome
- Sigla

O modelo de Série deverá conter (mas não limitado a):
- Nome
- Sigla
- Descrição

O modelo de Turma deverá conter (mas não limitado a):
- Nome
- Sigla
- Descrição
- Turno (vespertino ou matutino)

O modelo de Aluno deverá conter (mas não limitado a):
- Nome
- Matrícula
- Data de nascimento
- E-mail
- Status (ativo ou inativo)

## Conhecimentos desejáveis, mas não essenciais
- Conhecimento no framework web Bootstrap para desenvolvimento dos componentes de interface.
- Conhecimento de libs como Jquery ou React para o frontend em JS.

## Finalizei o teste, e agora ?

Você pode enviar de duas maneiras:

Fazer um fork deste repositório, programar para atender os requisitos e fazer um merge request quando finalizar. 

ou

Criar um repositório público, desenvolver o projeto e enviar o link do resultado para esse e-mail **vinicius.gusmao@salesiano.br**.

*É importante que conste no projeto as instruções para executar a aplicação desenvolvida (preferencialmente usando markdown).*

## Considerações Finais
A intenção com este projeto é que o candidato seja capaz de desenvolver um sistema do zero, considerando a modelagem no banco de dados, criação de uma área autenticada, CRUD no banco de dados e consultas específicas para listagem das informações no frontend.
