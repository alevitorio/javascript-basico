
# 🧠 Aprendendo JavaScript para Web – ETEC Programação Web I

Seja bem-vindo(a) ao mundo do **JavaScript**! 🌍

Você que já mandou bem em Python 🐍, agora vai dominar essa nova linguagem que é a alma da **Web** 💻✨. Com ela, conseguimos deixar páginas HTML muito mais interativas e inteligentes.

Vamos direto ao ponto? 🚀

---

## 📚 Conteúdo Programático

- ✅ Fundamentos do JavaScript
- ✅ Variáveis, Tipos e Operadores
- ✅ Estruturas de Decisão (`if`, `else`, `else if`)
- ✅ Estruturas de Repetição (`for`, `while`)
- ✅ Comparações com Python (pra facilitar!)
- ✅ Exemplos práticos e divertidos 🤹‍♂️

---

## 🔰 1. Introdução ao JavaScript

JavaScript é uma linguagem de programação que roda no navegador 🧠💻.

Podemos escrever JS diretamente no HTML usando a tag `<script>`:

```html
<!DOCTYPE html>
<html>
  <head><title>JS na Web</title></head>
  <body>
    <h1>Olá, mundo!</h1>
    <script>
      console.log("Oi turma da ETEC! 👋");
    </script>
  </body>
</html>
```

🧪 **Teste você mesmo!** Salve esse código com a extensão `.html` e abra no navegador. Veja o resultado no console (`F12` > aba "Console").

---

## 💡 2. Variáveis, Tipos e Operadores

### 🧺 Declarando Variáveis

No JavaScript temos 3 formas principais:

```js
let nome = "Maria";   // pode mudar depois
const idade = 18;     // constante, não pode mudar
var cidade = "São Paulo"; // forma antiga, evite
```

### 🧠 Tipos de Dados

| Tipo        | Exemplo               |
|-------------|------------------------|
| `string`    | `"Olá"`, `'Mundo'`     |
| `number`    | `10`, `3.14`, `-5`     |
| `boolean`   | `true`, `false`        |
| `undefined` | valor não definido     |
| `null`      | valor nulo (intencional)|

### ➕ Operadores

- Aritméticos: `+`, `-`, `*`, `/`, `%`
- Comparação: `==`, `!=`, `===`, `!==`, `>`, `<`, `>=`, `<=`
- Lógicos: `&&` (E), `||` (OU), `!` (NÃO)

⚠️ Atenção: `==` compara valor, `===` compara valor e tipo!

```js
5 == "5"      // true
5 === "5"     // false
```

---

## 🤔 3. Estruturas de Decisão

### 🧾 Exemplo básico com `if`, `else`:

```js
let idade = 17;

if (idade >= 18) {
  console.log("Pode dirigir 🚗");
} else {
  console.log("Ainda não pode dirigir 🛴");
}
```

### 🔄 `else if`

```js
let nota = 7;

if (nota >= 9) {
  console.log("Excelente! 🏆");
} else if (nota >= 6) {
  console.log("Aprovado! 👍");
} else {
  console.log("Recuperação... 🤓");
}
```

---

## 🔁 4. Estruturas de Repetição

### 🔂 Usando `for`

```js
for (let i = 1; i <= 5; i++) {
  console.log("Contando: " + i);
}
```

### ♾️ Usando `while`

```js
let contador = 1;

while (contador <= 5) {
  console.log("Repetindo: " + contador);
  contador++;
}
```

---

## 🐍 Comparando com Python

| Conceito     | Python         | JavaScript          |
|--------------|----------------|---------------------|
| Variável     | `x = 5`        | `let x = 5;`        |
| Constante    | N/A            | `const x = 5;`      |
| Print        | `print("oi")`  | `console.log("oi")` |
| If           | `if x > 0:`    | `if (x > 0) {}`     |
| For          | `for i in range(5):` | `for (let i = 0; i < 5; i++)` |
| While        | `while x < 10:` | `while (x < 10) {}` |

---

## 🧪 5. Exercícios Práticos

### 🧮 Ex. 1 – Comparar dois números

```js
let a = 10;
let b = 20;

if (a > b) {
  console.log("A é maior que B");
} else {
  console.log("B é maior que A");
}
```

### 📊 Ex. 2 – Números pares de 1 a 20

```js
for (let i = 1; i <= 20; i++) {
  if (i % 2 === 0) {
    console.log(i);
  }
}
```

### 🔁 Ex. 3 – Contagem regressiva

```js
let n = 5;
while (n > 0) {
  console.log(n);
  n--;
}
```

---

## 🛠️ Dica de Ferramentas Online

- [JSFiddle](https://jsfiddle.net/)
- [CodePen](https://codepen.io/)
- [PlayCode](https://playcode.io/)
- Console do navegador (F12)

---

## 🏁 Conclusão

Você já tem a base! 🧱
Com o que você aprendeu em Python, o JavaScript vai parecer mais uma **nova roupagem** com cara de navegador. Continue praticando, fazendo experimentos, errando e aprendendo! 💪

> “O código é como mágica que você pode entender e criar.” ✨

---

Feito com 💙 para a turma da **ETEC Irmã Augustina – PW I**  
Prof. Alessandro (AleDev)

---
