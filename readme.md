# projeto loteca 
este é um projeto de simulador de loteria. onde o usuário digita 6 números e realiza um sorteio de outros 6 números,
que por fim é verificado quantos dos 6 números o usário acertou

 - **HTML**: estrutura do site
- __CSS__: estilização do site  
- *_JS_*: funções do site 
- ~~BootStrap~~: nao foi utilizado

### Melhorias possíveis
1.  [ ]  subir para GitHubPages
2.  [ ]  alterar os alerts
3.  [ ]  deixar responsivo

### disponibilizado em 
[githubpage] (https://alineroa.github.io/loteca/)

### prints da tela

| ID | primeira tela | segunda tela |
|----|---------------|----------------|
| 1  | loteca limpa  | loteca preenchida |
| 2  | ![tela loteca](https://user-images.githubusercontent.com/100213683/161781607-c4992bc5-2618-45f2-991b-b9c14cd3f471.png) |![tela loteca](https://user-images.githubusercontent.com/100213683/161781607-c4992bc5-2618-45f2-991b-b9c14cd3f471.png)     |

### funcão principal 
```
var numSort = [];
var numEsco = [];

function sorteio() {
  var cont = 0;
  numSort = [];

  while (cont < 6) {
    let num = Math.random() * 60;
    num = Math.ceil(num);
    if (!numSort.includes(num)) {
      numSort[cont] = num;
      console.log(numSort);
      cont++;
    }
  }
```
