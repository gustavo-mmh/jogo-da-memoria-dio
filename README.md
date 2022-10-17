# jogo-da-memoria-dio

## 📌 Sobre este Projeto

Criação de um Jogo da memória utilizando HTML, CSS e Javascript. O jogo da memória criado tem uma temática voltada ao futebol, nele você deve encontrar o par de simbolo dos clubes brasileiros.
Para deixar o jogo mais atraente, utilizei o atributo:
filter: sepia();
nas costas dos cards (.card-back) para que tivessem um tom de sépia.
Adicionei:
.card-back:hover {
  transform: scale(1.03);
  transition: 100ms ease-in-out 0s;
  filter: grayscale(0.5);
}
no css para que quando o mouse passe sobre o card, ele além de voltar a sua cor original com um filtro de 0.5 de escala cinza, ele aumentasse suavemente de tamanho.
Coloquei nos cards uma borda com o efeito outset, que da um efeito 3d nos cars.
border: outset;
Como os efeitos citados foram criados apenas no card-back, quando os cards são clicados, o front aparece colorido e ao serem descobertos os pares, eles ganham um destaque a mais por estarem com cor em contraste com os backs em sépia.

## 💡 Por quê?

Este projeto faz parte do meu portfólio pessoal, então, ficarei feliz se você puder me fornecer algum feedback sobre o projeto, código, estrutura ou qualquer coisa que você possa relatar que possa me tornar um desenvolvedor melhor!

Email-me: gustavo-mmello@hotmail.com

Conecte-se comigo em [LinkedIn](https://www.linkedin.com/in/gustavo-m-mello/)

## 🖥️ Tecnologias

- HTML5
- CSS3
- JavaScript

## ☁️ Deploy na Nuvem

- Pages GitHub


## 🌎 Ver Site Funcionando

-  [Ver Site](https://gustavo-mmh.github.io/jogo-da-memoria-dio/)

## ⚠️ Instalando -Website de Portfólio Pessoal-

Para Clonar o repositório de *jogo-da-memoria-dio*, faça:

```
$ git clone https://github.com/gustavo-mmh/jogo-da-memoria-dio.git

$ cd jogo-da-memoria-dio
```
