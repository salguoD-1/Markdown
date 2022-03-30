# Aprendendo Markdown

*Lightweight markup language* ou linguagem de marcação leve é uma linguagem muito utilizada para documentar nossos projetos e deixa-los de forma mais legível para outros programadores. Vejamos alguns comandos e as suas respectivas funções.
# Comandos
Os headings ou cabeçalhos no velho e bom português são responsáveis pelos títulos e sub-títulos e assim por diante, sendo utilizado o caractere # antes do título. Temos seis níveis de títulos, sendo representados respectivamente por: #, ##, ###, ####, #####, ######. Onde # é o título de maior tamanho.

# Título de grau 1
## Título de grau 2
### Título de grau 3
#### Título de grau 4
##### Título de grau 5
###### Título de grau 6 
---
# Deixando o texto ítalico
Para deixar o texto ítalico basta utilizar duplo asterísticos entre nosso texto, vejamos: *Exemplo de texto ítalico.*
Podemos também utilizar os caracteres de underline antes e depois do texto, vejamos: _Exemplo de texto com underline._

# Deixando o texto strong
O texto strong deixa enfatizado a sua importância, para isso fazemos uso do **duplo asterístico** ou __duplo underline.__

# Deixando o texto tachado
O texto tachado indica a exclusão de um erro. Para deixar o texto tachado basta utilizar ~~duplo til~~ antes e depois do texto.

# Colocando uma linha horizontal
Para acrescentar uma linha horizontal basta utilizar 3 hífens ou 3 underlines
- - -
___

# Bloco de citação
Para citar alguma frase ou algo do tipo fazemos uso do caractere >
> Isso é uma citação.

# Fazendo uso de links
Para utilizar links basta colocar o hyperlink entre colchetes e em seguida, abrir parêntes e colocar o link, vejamos: [Acesse o Google](https://www.google.com.br/)

# Fazendo uso de listas não ordenadas
Para fazer uso de uma lista não ordenada basta colocar um asterístico antes do texto, vejamos:
* Janeiro
* Fevereiro
## É possível fazer uma lista aninhada também, para isso basta dar dois espaços após o asterístico anterior, vejamos:
* Março
* Abril
  * Abril é muito legal né?
  * Abril é o quarto mês do ano!

# Fazendo uso de uma lista ordeanda
Para utilizar uma lista ordenada basta colocar o número 1 seguido de um ponto, vejamos:
1. Janeiro
1. Fevereiro
1. Março

# Fazendo uso de um bloco de código embutido
Para utilizar um bloco de código embutido basta utilizar o duplo acento grave (``), veja: <br>
`sudo apt update`


# Fazendo uso de imagens
Para fazer uso de imagens basta colocar um ponto de exclamação antes dos colchetes, veja: <br>
![Twitter Logo](https://cdn-icons-png.flaticon.com/512/124/124021.png)

---

# Fazendo uso de um bloco de código
Para fazer uso de um bloco de código basta utilizar triplo acento grave (```) antes e depois do código. Nota: Podemos escolher o nome da linguagem que queremos utilizar, basta colocar o nome da linguagem após os três primeiros acentos graves. Fazer uso da linguagem ajuda a deixar ela esteticamente destacada, vejamos: <br>

```bash
npm install
 
npm start
```

```javascript
function sumNumbers(x, y) {
    return x + y;
}
console.log(sumNumbers(2, 3));

```
Note que o código em JavaScript ficou esteticamente destacado, ou seja, visualmente mais agradável.

---

# Fazendo uso de tabelas
Para fazer uso de tabelas basta utilizar a seguinte estrutura <br>
```
| Nome           | Email                       |
| --------       | --------                    |
| Douglas Cunha  | exemplo@gmail.com           |
| João Guilherme | exemplo@hotmail.com         |
```
e o resultado será o seguinte:
| Nome           | Email                       |
| --------       | --------                    |
| Douglas Cunha  | exemplo@gmail.com           |
| João Guilherme | exemplo@hotmail.com         |
Basta fazer uso das barras verticais e dos hífens.

---

# Fazendo uso de uma lista de tarefas
Para demonstrar tarefas que foram ou não cumpridas, basta utilizar os caracteres * [x] Nome da tarefa. O x dentro dos colchetes demarca que a tarefa foi concluida, caso ela não tenha sido concluída basta não fazer uso do x, vejamos:
* [x] Estudar Markdown
* [ ] Estudar React

