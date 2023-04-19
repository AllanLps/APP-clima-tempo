# Projeto 01 - APP Clima Tempo ☀️

Projeto publicado: https://allanlps.github.io/APP-clima-tempo/

## Descrição

O projeto tem como ideia criar um site de pesquisa simples, focando mais no código JS, com a funcionalidade de criar uma requisição à API do OpenWeatherMap para obter informações meteorológicas sobre uma cidade. O projeto tem que ser responsivo e funcional!

O objetivo é criar um input para realizar a pesquisa das cidades e consultar o clima da cidade. Caso o usuário escreva uma cidade ou país que não exista, uma tela de erro deve ser apresentada.

## Funcionalidades

- Input para pesquisa de cidades
- Consulta de informações meteorológicas da cidade pesquisada
- Responsividade
- Pesquisa

<p align="center">
  <img src="https://user-images.githubusercontent.com/100639279/227220655-2198e35e-6e80-4ebe-a48b-bdce18a18eab.png"/>
</p>


- Após pesquisar

<p align="center">
  <img src="https://user-images.githubusercontent.com/100639279/227220928-709ada40-df74-4ade-90cc-1e8dbca07820.png"/>
</p>

- Caso pesquise errado

<p align="center">
  <img src="https://user-images.githubusercontent.com/100639279/227221150-4e8b980e-76ed-4188-9bf1-1ebe3a259f09.png"/>
</p>

## O que o código JS deve fazer?

Ele deve ser responsável por fazer uma solicitação à API do OpenWeatherMap para obter informações meteorológicas sobre uma cidade, exibir essas informações na página HTML e também lidar com erros quando uma cidade não é encontrada.

### E para te dar uma luz! 💡

O código começa selecionando elementos HTML relevantes para o aplicativo usando o método **`document.querySelector()`** e adicionando um ouvinte de eventos ao botão de pesquisa. Quando o botão é clicado, o código obtém o valor do input de pesquisa, verifica se o valor é uma string vazia e, em seguida, faz uma solicitação à API usando a função **`fetch()`**.

Se a cidade não for encontrada (o que é indicado pelo status de resposta "404" da API), o código oculta os elementos da página HTML que mostram informações meteorológicas e exibe uma mensagem de erro no lugar. Caso contrário, o código preenche as informações da cidade em elementos HTML relevantes, como a imagem de tempo, temperatura, descrição do tempo, umidade e velocidade do vento.

Finalmente, o código adiciona classes CSS para animar a exibição desses elementos e altera a altura do contêiner HTML para acomodar as informações do tempo.

## links úteis! 🔗

* Ícones: https://fontawesome.com/icons
* API do OpenWeatherMap: https://openweathermap.org/api


## Conclusão

Espero que este projeto possa ajudar você a praticar e aprender mais sobre programação! Compartilhe seu projeto e me marque no LinkedIn se quiser. Vamos lá! 💪🏼
