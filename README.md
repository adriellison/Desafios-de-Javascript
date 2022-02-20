# Desafios de Javascript
##### Desafios práticos para quem esta começando ou quer exercitar suas habilidades em JS.
---
## Tudo que é necessario:
- Um editor de código ([visualStudioCode](https://code.visualstudio.com/), ou qualquer outro de sua escolha)

_Obs: No vídeo base dos projetos é utilizado o Visual Studio Code, mas fique a vontade em escolher a sua IDE._

![icone visualStudioCode](https://code.visualstudio.com/assets/blogs/2017/10/24/blueicon.png)

## Plugins
Plugins para ajudar no desenvolvimento dos projetos

| Plugin | LINK |
| ------ | ------ |
| Live Server | [https://marketplace.visualstudio.com](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) |

## Testando o primeiro código no console
Escreva seu primeiro código na IDE:
- dentro de um arquivo html na tag <script>

```html
<script>
    console.log("Olá, mundo!")
</script>
```

- em um arquivo .js sendo chamado pelo html:
- ou em um arquivo .js sendo chamado pelo node

```js
console.log("Olá, mundo!")
```

## Se você está começando, use o vídeo fonte dos projetos como direcionamento
> Curso Javascript Completo 2020 [Iniciantes] + 14 Mini-Projetos
O vídeo é uma aula de JavaScritp, se você está começando, tem dificuldade ou não lembra a syntaxe da linguagem, recomendo fortemente que assista o vídeo.
> https://www.youtube.com/watch?v=i6Oi-YtXnAU

> Nota: `Tente fazer os desafios antes de buscar por ajuda, tente se desafiar e se surpreenda com a sua capacidade 😉`

## Projeto 01  - Trocando Valores de Variáveis
- Inverta os valores de saída das variáveis abaixo.

```JS
let a = 'vermelho'
let b = 'azul'

console.log(a)
console.log(b)
```

output:
```
azul
vermelho
```

## Projeto 02 - Máximo Entre Dois Valores
- Dado dois valores N, retorne o maior valor usando funções e retornando o valor para o seu console.

```JS
function max(num1, num2){}

console.log(max(1, 2))
console.log(max(9, 2))
```

## Projeto 03 - FizzBuzz
- Se o valor N for divisível por 3 ele retorna o texto 'Fizz'
- Se o valor N for divisível por 5 ele retorna o texto 'Buzz'
- Se o valor N for divisível por 3 e por 5 ele retorna o texto 'FizzBuzz'
- Se ele não for divisível por 3 e nem por 5 ele retorna o valor o próprio N
- E se o valor N não for um número, tem de retornar o texto 'Não é um número'

```JS
function fizzBuzz(entrada){}

// entrada
const resultado = fizzBuzz(15);
// saida
console.log(resultado)
```

## Projeto 04 - Medidor de velocidade
- Criar um radar de veocidade e calcular multa
- Velocidade máxima de até 70km/h
- A cada 5km acima do limite, você ganha 1 ponto na carteira
- Se os pontos forem maior que 12, a carteira é suspensa
- Use Math.Floor() para arredondar o resultado
```JS
function verificarVelocidade(velocidade){}

// entrada
verificarVelocidade(180)
// saida
console.log()
```

---

**Uma organização LAG com o incentivo e busca de desafios dos próprios estudantes do servidor.**

Link de convite do servidor LAG: <https://discord.gg/Z4RcfxtPYE>

Fonte: <https://www.youtube.com/watch?v=i6Oi-YtXnAU>

**"Não é a linguagem de programação que define o programador, mas sim sua lógica!"**
