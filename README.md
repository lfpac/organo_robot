🤖 Automação de Testes com Robot Framework (BDD)

Este projeto tem como objetivo demonstrar a automação de testes funcionais web utilizando o Robot Framework, aplicando boas práticas como BDD (Behavior Driven Development), Page Object Model (POM) e organização por keywords reutilizáveis.

Os testes foram desenvolvidos com foco no comportamento do usuário, garantindo que as funcionalidades atendam aos critérios de aceitação definidos.

🧪 Funcionalidade testada

A aplicação testada permite o cadastro de colaboradores (cards) em diferentes times por meio de um formulário web.

Os cenários automatizados validam:

Criação correta de cards

Validação de campos obrigatórios

Criação de múltiplos cards

Distribuição de cards entre diferentes times

🚀 Tecnologias e ferramentas utilizadas

Robot Framework

SeleniumLibrary

FakerLibrary (geração de dados dinâmicos)

BDD (Behavior Driven Development)

Page Object Model (POM)

CSS Selector e XPath

Python

Google Chrome

📂 Estrutura do projeto
├── resources
│   ├── main.robot
│   ├── pages
│   │   └── cadastro_organo.robot
│   └── shared
│       └── setup_teardown.robot
│
├── tests
│   ├── cadastro_com_sucesso.robot
│   └── validacao_campos_obrigatorios.robot
│
└── README.md

📌 Organização

resources/: arquivos reutilizáveis (keywords, páginas e setup/teardown)

pages/: implementação do Page Object Model

tests/: cenários de teste escritos em BDD

🧠 Conceitos aplicados

Escrita de testes orientados ao comportamento do usuário (BDD)

Reutilização de código com keywords customizadas

Uso de massa de dados dinâmica

Estruturação de testes legíveis e manuteníveis

Validações funcionais e mensagens de erro

Setup e teardown para controle do ciclo de testes

▶️ Como executar os testes
Pré-requisitos

Python instalado

Robot Framework

SeleniumLibrary

FakerLibrary

Google Chrome

Aplicação em execução local (http://localhost:3000)

Comando para execução:
robot tests/

📈 Objetivo do projeto

Este projeto foi desenvolvido com foco em aprendizado prático, reforçando conceitos de qualidade de software, automação de testes e boas práticas de QA, servindo também como portfólio profissional.
