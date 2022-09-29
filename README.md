<h2>Curso de TypeScript Avançado na Alura: Concluído</h2>

> Passo 1: Instalar os programas necessários em sua máquina, descritos abaixo:

```
Node.js (version 16.17.0)
Visual Studio Code ou outra IDE preferida (exemplo: Atom e Sublime)
```

> Passo 2: Abra o projeto em sua IDE e instale as dependências, digitando o comando no terminal na raiz da pasta do projeto:

```
npm install
```

> Passo 3: Para rodar o projeto na sua máquina, digite um dos dois comandos abaixo na raiz da pasta do projeto:

```
npm run server (executa a aplicação e abre no browser)
npm run start (sempre que uma alteração for salva o código é recompilado e exibido no browser de maneira reativa)
```

> Arquitetura do Projeto

```
A pasta Dist(Ditribution) é compartilhada com o navegador através do comando npm run server ou npm 
run start, logo os arquivos dentro da pasta Dist são compartilhados com navegador sendo eles no caso 
deste projeto o index.html, css(bootstrap), e o icone da minha pagina. No corpo do index.HTML 
criamos uma tag script antes do final da tag body para importar um arquivo JavaScript ou EcmaScript
que chamamos de módulo esse arquivo irá fazer a interação com o index.HTML. O projeto está configurado
para converter todos os arquivos typescript dentro da pasta app para arquivos javascript dentro da
pasta dist. Dentro do arquivo app.js instanciamos a nossa controller chamada de NegociacaoController
que manipulará os dados para serem apresentados no nosso DOM em sequencia obtemos o nosso form e manipulamos
ele através do evento submit. Na nossa controller criamos variaveis do tipo inputHTMLElement e obtemos
do form os campos através do id de cada um deles o seu HTML e para obtermos a tabela criamos uma classe
separada com nome negociacoesView para apresentar os dados depois de cadastrados utilizando o innerHTML.
```