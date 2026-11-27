🏁 LEGENDS GARAGE

<p align="center">
  <img src="assets/images/porsche-destaque.jpg" alt="Legends Garage — Porsche" width="50%">
</p><h3 align="center">MORE THAN CARS. A COLLECTION.</h3><p align="center">
  Sistema web para organização e gerenciamento de coleções de automóveis.
</p><p align="center">
  <img src="https://img.shields.io/badge/HTML5-Estrutura-orange?logo=html5" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-Estilização-blue?logo=css3" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-Lógica-yellow?logo=javascript" alt="JavaScript">
  <img src="https://img.shields.io/badge/API-MockAPI-purple" alt="MockAPI">
  <img src="https://img.shields.io/badge/Testes-Postman-orange?logo=postman" alt="Postman">
  <img src="https://img.shields.io/badge/Versionamento-Git-red?logo=git" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-Repositório-black?logo=github" alt="GitHub">
</p>---

📑 SUMÁRIO

- "1. Sobre o Projeto" (#-1-sobre-o-projeto)
- "2. Objetivos" (#-2-objetivos)
- "3. Tecnologias Utilizadas" (#-3-tecnologias-utilizadas)
- "4. Estrutura do Sistema" (#-4-estrutura-do-sistema)
- "5. Funcionalidades" (#-5-funcionalidades)
- "6. Estrutura dos Dados" (#-6-estrutura-dos-dados)
- "7. Lógica de Programação" (#-7-lógica-de-programação)
- "8. Integração com APIs" (#-8-integração-com-apis)
- "9. Métodos HTTP" (#-9-métodos-http)
- "10. Testes com Postman" (#-10-testes-com-postman)
- "11. Estrutura de Pastas" (#-11-estrutura-de-pastas)
- "12. Como Executar" (#-12-como-executar)
- "13. Controle de Versão" (#-13-controle-de-versão)
- "14. Autor" (#-14-autor)

---

🏎️ 1. SOBRE O PROJETO

O Legends Garage é uma aplicação web desenvolvida para cadastrar, organizar, consultar e gerenciar coleções de automóveis.

O sistema apresenta uma interface inspirada no universo automotivo, com uma identidade visual escura e detalhes em destaque.

A aplicação será desenvolvida utilizando HTML5, CSS3 e JavaScript, com integração a duas APIs criadas na plataforma MockAPI.

O projeto faz parte de uma atividade individual do curso Técnico em Informática para Internet do SENAI.

🎯 2. OBJETIVOS

O objetivo principal é desenvolver uma aplicação que permita gerenciar informações de automóveis por meio de operações realizadas em uma API.

Durante o desenvolvimento, serão aplicados conhecimentos de:

- Estruturação de páginas com HTML5.
- Estilização e organização visual com CSS3.
- Lógica de programação com JavaScript.
- Manipulação do DOM.
- Requisições HTTP utilizando Fetch API.
- Integração com APIs REST.
- Operações CRUD.
- Testes e documentação de requisições com Postman.
- Controle de versão com Git e GitHub.

💻 3. TECNOLOGIAS UTILIZADAS

Tecnologia| Finalidade
HTML5| Construção da estrutura da aplicação.
CSS3| Estilização, layout e responsividade.
JavaScript| Lógica de programação e interatividade.
MockAPI| Criação e disponibilização das APIs.
Fetch API| Comunicação entre o JavaScript e as APIs.
Postman| Testes e documentação das requisições HTTP.
Git| Controle de versão do código.
GitHub| Hospedagem do repositório e gerenciamento do projeto.

🖥️ 4. ESTRUTURA DO SISTEMA

A aplicação está organizada em cinco áreas principais:

Dashboard

Apresenta uma visão geral da coleção, com indicadores como:

- Total de veículos cadastrados.
- Valor total da coleção.
- Quantidade de categorias.
- Último cadastro realizado.

Minha Coleção

Área destinada à visualização e ao gerenciamento dos automóveis cadastrados.

Contará com pesquisa por marca ou modelo e filtro por categoria.

Garagem

Área destinada à organização dos automóveis por categorias, como esportivos, clássicos e supercarros.

Concessionária

Área responsável pelo formulário de cadastro e gerenciamento dos veículos.

Sobre

Apresenta a identidade e a finalidade do projeto.

⚙️ 5. FUNCIONALIDADES

O sistema tem como proposta implementar as seguintes funcionalidades:

Funcionalidade| Descrição
Cadastrar| Adicionar novos automóveis à coleção.
Listar| Consultar e apresentar os veículos cadastrados.
Pesquisar| Localizar veículos por marca ou modelo.
Filtrar| Separar veículos de acordo com a categoria.
Editar| Atualizar informações de um automóvel.
Excluir| Remover um automóvel da coleção.
Estatísticas| Apresentar informações gerais da coleção.

Observação: a estrutura visual dessas áreas está sendo desenvolvida no HTML. O funcionamento será implementado com JavaScript e integração com as APIs.

📋 6. ESTRUTURA DOS DADOS

Cada registro de automóvel deverá possuir os seguintes campos:

Campo| Tipo de dado| Descrição
id| Identificador| Identificação individual gerada pela API.
marca| Texto| Fabricante do automóvel.
modelo| Texto| Modelo do automóvel.
ano| Número| Ano de fabricação.
preco| Número| Valor do automóvel.
potencia| Número| Potência em cavalos (CV).
categoria| Texto| Categoria do automóvel.
cor| Texto| Cor do automóvel.

O sistema utilizará sete campos além do identificador "id", atendendo ao requisito mínimo de cinco campos adicionais.

As categorias serão definidas por opções fixas:

- Esportivo.
- Clássico.
- Supercarro.
- SUV.
- Sedan.

🧠 7. LÓGICA DE PROGRAMAÇÃO

A aplicação utilizará JavaScript para controlar as funcionalidades e manipular os elementos da interface.

As principais operações previstas são:

- Capturar os dados preenchidos no formulário.
- Validar as informações antes do envio.
- Enviar requisições para as APIs.
- Receber e organizar os dados retornados.
- Criar elementos HTML dinamicamente.
- Atualizar informações exibidas na tela.
- Pesquisar e filtrar os veículos.
- Atualizar os indicadores do Dashboard.
- Tratar respostas e possíveis erros das requisições.

Fluxo geral da aplicação

1. O usuário acessa o sistema.
2. O JavaScript consulta as APIs.
3. Os dados recebidos são organizados.
4. Os veículos são apresentados na interface.
5. O usuário pode cadastrar, pesquisar, filtrar, editar ou excluir registros.
6. As alterações são enviadas às APIs.
7. A interface é atualizada conforme os resultados das operações.

🔌 8. INTEGRAÇÃO COM APIs

O projeto utilizará duas APIs criadas na plataforma MockAPI.

A comunicação será realizada por meio da Fetch API, recurso nativo do JavaScript que permite realizar requisições HTTP.

A integração será responsável por enviar e receber informações entre a aplicação e os serviços disponibilizados pela MockAPI.

Recursos previstos

- API 1: gerenciamento dos dados de automóveis.
- API 2: segundo recurso de dados do sistema.

Os nomes definitivos dos recursos e seus respectivos endpoints serão registrados após a configuração das APIs.

🌐 9. MÉTODOS HTTP

Serão utilizados cinco métodos HTTP para realizar as operações de gerenciamento dos dados.

Método| Operação| Finalidade
GET| Consultar| Buscar os registros disponíveis.
POST| Cadastrar| Criar um novo registro.
PUT| Atualizar| Substituir os dados de um registro.
PATCH| Atualização parcial| Modificar determinados campos de um registro.
DELETE| Excluir| Remover um registro.

Esses métodos serão utilizados para implementar as operações CRUD e demonstrar o funcionamento da comunicação com as APIs.

🧪 10. TESTES COM POSTMAN

O Postman será utilizado para testar e documentar as requisições realizadas às APIs.

Serão verificadas as operações:

- GET: consulta dos registros.
- POST: criação de registros.
- PUT: atualização completa.
- PATCH: atualização parcial.
- DELETE: exclusão de registros.

Os testes permitirão verificar as respostas das APIs e o comportamento esperado de cada operação.

A documentação das requisições será organizada no Postman para facilitar a demonstração e a avaliação do projeto.

📁 11. ESTRUTURA DE PASTAS

A organização prevista para o repositório é:

LEGENDS-GARAGE/
│
├── assets/
│   └── images/
│       └── porsche-destaque.jpg
│
├── css/
│   └── style.css
│
├── docs/
│   └── images/
│       └── logica/
│
├── js/
│   └── script.js
│
├── index.html
│
└── README.md

Descrição das pastas

Pasta ou arquivo| Responsabilidade
assets/images| Armazenar imagens utilizadas na aplicação.
css| Armazenar os arquivos de estilização.
docs/images/logica| Armazenar imagens e diagramas da lógica do sistema, quando criados.
js| Armazenar os arquivos JavaScript.
index.html| Arquivo principal da aplicação.
README.md| Documentação do projeto.

🚀 12. COMO EXECUTAR

Para executar o projeto localmente:

1. Clone o repositório do GitHub.
2. Abra a pasta do projeto no Visual Studio Code.
3. Verifique se as pastas e os arquivos estão organizados corretamente.
4. Abra o arquivo "index.html" utilizando uma extensão como Live Server.
5. Acesse a aplicação pelo navegador.

A integração com as APIs dependerá da configuração dos endpoints e da implementação do JavaScript.

🔄 13. CONTROLE DE VERSÃO

O Git será utilizado para controlar as alterações realizadas durante o desenvolvimento.

O GitHub será utilizado para armazenar o repositório e acompanhar a evolução do projeto.

O desenvolvimento poderá ser organizado por branches, permitindo separar novas funcionalidades e alterações antes de integrá-las à branch principal.

👨‍💻 14. AUTOR

Projeto: Legends Garage

Desenvolvimento: Individual

Curso: Técnico em Informática para Internet

Instituição: SENAI

Ano: 2026

---

<p align="center">
  <strong>LEGENDS GARAGE</strong><br>
  MORE THAN CARS. A COLLECTION.
</p>