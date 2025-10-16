# Aula 01 Criar projeto React JS com o Vite, Estrutura do projeto

## Criar o Projeto3-React

### Instalação e Criação do Projeto

1.	Abra o VsCode na pasta onde deseja guardar o projeto
   
3.	Abra um novo terminal (integrado no VSCode)
   
5.	> Execute o comando: `npm create vite@latest`

6.	Responda as perguntas e aguarde o processo de criação do projeto com o Vite


* Project name:
Projeto3-React

* Package name:
projeto3-react

* Select a framework:
React

* Select a variant:
JavaScript

* Use rolldown-vite (Experimental)?:
No

* Install with npm and start now?
Yes

Scaffolding project in D:\Front-end\Desenvolvedor Front-End\Vite\Projeto3-React...
│
Installing dependencies with npm...
added 153 packages, and audited 154 packages in 34s
32 packages are looking for funding
run `npm fund` for details
found 0 vulnerabilities

Starting dev server...
projeto3-react@0.0.0 dev
vite

Verifique o carregamento da Aplicação React no seu browser,
irá abrir no endereço http://localhost:xxx

 VITE v7.1.10  ready in 421 ms
 
  ➜  Local: http://localhost:xxx/
  
  ➜  Network: use --host to expose
  
  ➜  press h + enter to show help
  
21:09:59 [vite] (client) page reload index.html

21:10:01 [vite] (client) page reload index.html (x2)



### Estrutura do projeto

1. Na raiz do projeto abra o index.html

> Mude o título da página para `<title>Portfólio</title>`

2. Na estrutura de pastas dentro de src, abrir o arquivo App.jsx

      - Apague todo o conteúdo que está dentro do return e digite:
      ~~~html
      <h1>Olá Mundo!</h1>
      ~~~
      - Apague a `const [count, setCount] = useState(0)`  (não vamos usar nesse projeto)

      - Apague as linhas de `import` que não estão mais sendo usadas


Estes são os passos básicos para criar um projeto react usando Vite.

Até a próxima aula dessa nossa série.
