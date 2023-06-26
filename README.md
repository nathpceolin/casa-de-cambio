# casa-de-cambio

O projeto da casa de câmbio é uma aplicação que busca a conversão da taxa de uma moeda para diversas outras.

Requisitos

Ambiente do Projeto Criar um repositório do zero ou fazer um fork desse repositório (fique à vontade para fazer PRs quando terminar o desenvolvimento). Iniciar projeto com NPM. Estruturar o projeto para usar ESModules (usar type como module no package.json e nas tags script). Instalar Vite como Dev Tool e npm run dev.

Estrutura da Aplicação Estruturar o HTML de acordo com protótipo. Criar tags semânticas no HTML.

Interação com API O endpoint da API que deverá ser usada é https://api.exchangerate.host/latest?base=${moeda}. A moeda a ser pesquisada deverá ser passada como o parâmetro moeda do endpoint. Todas as moedas deverão ser listadas na tela. Link da API: https://exchangerate.host/#/docs

Tratamento de Erro Você deve usar o Sweet Alert 2 para as mensagens de Erro. Um erro deverá aparecer quando nenhuma moeda é passada. Um erro deverá aparecer quando uma moeda inexistente é passada.
