# Introdução ao ReactJS
## Criar projeto
Vá no terminal e digite:
>npm init

Exemplo com versão:
>npm install --save react@17.0.2 react-dom@17.0.2 react-scripts@3.0.1

Exemplo sem versão:
>npm install --save react react-dom

- [Versão - ReactJS](https://pt-br.reactjs.org/versions/) 
- [Versão - ReactJS Scripts](https://openbase.com/js/react-scripts/versions)

## Abrir projeto no navegador
>npm start

## Instalar EsLint
>npm install --save-dev eslint babel-eslint eslint-plugin-react eslint-watch 

## Documentações
- [Renderizando elementos](https://pt-br.reactjs.org/docs/rendering-elements.html)
- [Componentes e Props](https://pt-br.reactjs.org/docs/components-and-props.html)
- [Webpack](https://medium.com/tableless/webpack-para-react-o-guia-final-cb8a95b369ed)
- [Renderização condicional](https://pt-br.reactjs.org/docs/conditional-rendering.html)
- [Listas e chaves](https://pt-br.reactjs.org/docs/lists-and-keys.html)
- [Manipulando eventos](https://pt-br.reactjs.org/docs/handling-events.html)

## Pensando do jeito React
- Comece com um Mock
- Separe a UI em uma hierarquia de componentes
- Crie uma versão estática em React
- Identifique a representação mínima (mas completa) do state da UI
- Identifique onde o state deve ficar
- Adicione o fluxo de dados inverso

## Quiz
### Quais são principais conceitos do webpack?
Entry, Output, Loaders, Plugins e Mode.

### Quais são as etapas e a ordem correta do ciclo de vida de um componente?
Inicialização; Montagem; Atualização; Desmontagem.

### Como é feito a renderização de um componente React no DOM?
Utilizando o ReactDOM.render.

### A respeito de Manipulação de Eventos, qual alternativa abaixo é a correta?
Eventos em React são nomeados usando camelCase ao invés de letras minúsculas.

### O que são Loaders na configuração do webpack?
É uma configuração que permite que o webpack gerencie arquivos que não são JavaScript.

### A respeito de “if inline com o Operador Lógico &&”, qual alternativa abaixo é a correta para renderizar um componente?
{hasCustomer && (<Component />)}

### O que é webpack?
É um module bundlers (um empacotador de módulos para aplicações JS).

### O que é o React?
Uma biblioteca JavaScript para criar interfaces de usuário.

### Ao executar o código abaixo, qual parâmetro deve ser informado para que o React não retorne um aviso? 
```
Código: const numbers = [1, 2, 3, 4, 5]; const listItems = numbers.map((number) =>  <li>{number}</li> ); 
```
Necessário informar o parâmetro key no elemento `<li>`.
  
### A respeito de React, é correto afirmar que:
React é uma biblioteca onde é uma boa prática criar vários componentes e elementos para deixar o código mais legível e reaproveitável.

## Sobre a Autora
Oi, eu sou a Fernanda! Estou aqui para contribuir com meu conhecimento e espero poder ajudar no desenvolvimento profissional de cada um de vocês.

[![Linkedin Badge](https://img.shields.io/badge/-Fernanda_Maki_Hirose-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)](https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)  [![Gmail Badge](https://img.shields.io/badge/-femahi2020@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:femahi2020@gmail.com)](mailto:femahi2020@gmail.com)
