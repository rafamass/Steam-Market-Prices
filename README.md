Steam Market Prices
===================

<h3><b>1.1 Introdução</b></h3>

Esse software tem como objetivo analisar os preços de determinados produtos "itens" na loja virtual da steam (http://steamcommunity.com/market/), com base nos itens analisados indicaremos quais sofreram mudanças significativas de preços.


<h3><b>1.2 Análise do problema</b></h3>

<h4><b>1.2.1 Esboço do problema</b></h4>

  <img src="http://i.imgur.com/E1rWtkc.png">
  
<h4><b>1.2.2 Resumo do problema</b></h4>

  O usuário irá cadastrar o item da loja, e podera acompanhar qual é sua variação de preço em tempo real.
  
<h4><b>1.2.3.1 Requisitos - funcionais</b></h4> 

  - O usuário irá cadastrar o item através de uma URL.
  - A URL deve ser exclusivamente do site (http://steamcommunity.com/market/).
  - Os dados serão salvos.
  - O usuário poderá remover o item que foi inserido anteriomente.
  - O usuário tem acesso ao painel de configuração do programa, onde poderá configurar o modo de alerta e a margem de variação de preço.
  - O programa alerta o usuário quando o preço está em alta ou em baixa.
  - O programa deve rodar em constatemente e suas verificações também.
  - O programa informa a situação que se encontra o site (ON/OFF).
  - O moeda tratada com usuário será o Real.
  - Todos valores diferentes da moeda Real deverá ser convertido.
  
  - TODO: completar requisitos
  

<h4><b>1.2.3.2 Requisitos - Não funcionais</b></h4>
  
  - Os dados serão salvos em um Banco de Dados
  - A URL deve possuir um filtro de verificação.
  - Modo de alerta poderá ser por pop-up no  Windows ou por mensagem via twitter.
  - O intervalo de verificação poderá ser ajustado pelo usuário entre 5 segundos a "n" horas
  
  - TODO: completar requisitos
