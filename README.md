# Pré-requisitos
É necessário clonar o projeto para teste do repositorio fornecido pela empresa no git informado.<br>
O projeto utiliza Python, ambiente virtual venv e dependências PIP que estao no arquivo requiments.txt dentro do git informado pela empresa.

A versão do NPM é 10.8.3, e, a versao do Cypress utilizada 13.15.0.<br>
Recomendo que você use as mesmas versões ou versões mais recentes.

## Instalação
Seguir os passos do arquivo README.md fornecedio no git da empresa.
Execute npm install (ou npm i para a versão curta) para instalar as dependências de desenvolvimento dos testes para utilizar com cypress.<br>
Instale o cypress npm install cypress --save-dev

## Testes
Execute npm test (ou npm t para a versão curta) para rodar os testes em modo headless.
Ou, execute npm run cy:open para abrir o Cypress em modo interativo.

