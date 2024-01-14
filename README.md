## Desafio ( FrontEnd Challenge )
# Motograu

![Logo do projeto](https://github.com/SamuelWSGIT/frontend-challenge/blob/master/src/assets/imagens/capa1.png)

## Samuel Almeida
Esse foi um desafio que tive a oportunidade de participar, no desafio era disponibilizado o acesso aos jogos motograu e wall-street, como podem notar, escolhi o motograu para fazer minhas da UI.
Nesse projeto fui apresentado novamente ao tailwind de forma mais aprofundada, costumava usar styled components mas agora pretendo me aprofundar mais ainda no tailwind que um framework que facilita e muito o trabalho, apesar de ter uma curva de aprendisado maior.

## Stacks
Aqui estão as tecnologias que foram usadas no projeto.

* React
* TailwindCss
* Websocket

## Visualização

### 1 - Home page

![Homepage image](https://github.com/SamuelWSGIT/frontend-challenge/blob/master/src/assets/imagens/capa1.png)

### 2 - Chat e Nav Bar

![Homepage image](https://github.com/SamuelWSGIT/frontend-challenge/blob/master/src/assets/imagens/chat-e-navbar.png)

### 3 - End Game

![Homepage image](https://github.com/SamuelWSGIT/frontend-challenge/blob/master/src/assets/imagens/crashmsg.png)

# Instruções técnicas

Este projeto contém a aplicação das interfaces dos jogos **WallStreet** e **Motograu**:

### 1. Clone o repositório:
```bash
git clone https://github.com/hypetechgames/frontend-challenge
```

### 2. Instale as dependências e inicie o projeto

Acesse a pasta do projeto:
```bash
cd frontend-challenge
```

Instale as dependências do projeto:
```bash
yarn install
```

Inicie o projeto:
```bash
yarn dev
```

### 3. Obtendo um token de acesso ao jogo

Para acessar o jogo é necessário obter um token de acesso que cria uma sessão demonstrativa funcional para desenvolvimento.

Para obtê-lo:

**1 - Acesse a API de Demonstração:** 
 https://hypetech-demo-api-service-developer.up.railway.app/docs/

**2 - Obtenha um link de demonstração:**	

	{ "gameUrl": "https://hypetech-games-ui-developer.up.railway.app/44cdf4cec80508c531f71a1929d591c8" }

**3 - Extraia o token obtido:**
~~https://hypetech-games-ui-developer.up.railway.app/~~**44cdf4cec80508c531f71a1929d591c8**


Exemplo: https://i.ibb.co/fp07Mxs/Screen-Recording-2024-01-08-at-17-59-36.gif


**Obs:** Para cada jogo que desejar carregar, você deve gerar um novo token, alterando o parâmetro "game" da requisição:

 ```json
"game": "motograu",
"lang": "pt",
"currency": "BRL"
```

 ```json
"game": "wall-street",
"lang": "pt",
"currency": "BRL"
```

**4 - Acesse o jogo:**
Uma vez obtido o token, utilize-o no seu ambiente de desenvolvimento:

**Exemplo - URL do seu ambiente:** http://localhost:8000/
**Exemplo - URL do jogo no seu ambiente:** http://localhost:8000/2b29acad3f7a1e6b0995155668719e66

Caso encontre dificuldade em obter o token seguindo processo acima, você poderá utilizar os tokens públicos abaixo *(ciente que outros desenvolvedores podem estar utilizando a mesma sessão ao mesmo tempo)*:

**Motograu:** 44cdf4cec80508c531f71a1929d591c8
**WallStreet:** 294f24f2c661fc80fd6d12845a3ccdd6

## Características
A principal funcionadade desse repositorio :
 - Participar do Desafio.
 - Publicar minhas criações.

## Links e Contatos
  - Repository: [https://github.com/SamuelWSGIT]
    - Caso tenha interesse no meu trabalho, fique a vontade pare entrar em contato: 
    - e-mail: mail.samuel.contato@gmail.com
    - Linkedin:www.linkedin.com/in/SamuelLKQ

## Projetos
  - Site: netlify
    - https://samuelws-projetocss.netlify.app
    - https://samuelws-projetohtml.netlify.app
    - https://samuelws-projetojs.netlify.app
      
  ## Autor

  * **Samuel Almeida Ribeiro** 

  Junte-se a nos e me siga no github!
  Obrigado por me visitar e bons codigos!
