Claro! Aqui vão **10 exercícios de JavaScript** feitos especialmente para alunos do ensino técnico que **já aprenderam lógica com Python**. Os exercícios estão organizados por dificuldade crescente, são bem contextualizados e com linguagem acessível. Ideal para fazer em sala de aula ou como atividade prática. ✨

---

## 🧠 Exercícios JavaScript – Programação Web I – ETEC

### 🟢 **Exercícios Básicos (Fundamentos e Decisão)**

#### 1. 👋 Saudação personalizada

> Peça para o usuário digitar seu nome com `prompt()` e exiba uma mensagem com `alert()`:

```js
// Exemplo de entrada/saída:
let nome = prompt("Qual seu nome?");
alert("Olá, " + nome + "! Seja bem-vindo(a) 😊");
```

---

#### 2. 📊 Par ou Ímpar?

> Peça um número com `prompt()` e diga se ele é par ou ímpar:

```js
let numero = Number(prompt("Digite um número:"));
if (numero % 2 === 0) {
  alert("Esse número é par!");
} else {
  alert("Esse número é ímpar!");
}
```

---

#### 3. 🎂 Pode votar?

> Peça a idade do usuário e diga se ele pode votar ou não.

```js
let idade = Number(prompt("Qual sua idade?"));
if (idade >= 16) {
  alert("Você pode votar! 🗳️");
} else {
  alert("Ainda não pode votar 😢");
}
```

---

#### 4. 🧮 Calculadora simples

> Peça dois números e exiba a soma, subtração, multiplicação e divisão.

```js
let a = Number(prompt("Digite o primeiro número:"));
let b = Number(prompt("Digite o segundo número:"));

alert("Soma: " + (a + b) +
      "\nSubtração: " + (a - b) +
      "\nMultiplicação: " + (a * b) +
      "\nDivisão: " + (a / b));
```

---

### 🟡 **Exercícios Intermediários (Repetição)**

#### 5. 🔢 Números de 1 a 10

> Mostre no console os números de 1 até 10 usando `for`.

```js
for (let i = 1; i <= 10; i++) {
  console.log(i);
}
```

---

#### 6. 📈 Tabuada do 7

> Mostre a tabuada do 7 (de 7×1 até 7×10) no console.

```js
for (let i = 1; i <= 10; i++) {
  console.log(`7 x ${i} = ${7 * i}`);
}
```

---

#### 7. 📉 Contagem regressiva de 10 a 1

> Use `while` para contar de 10 até 1 no console.

```js
let n = 10;
while (n > 0) {
  console.log(n);
  n--;
}
```

---

#### 8. 💡 Somar números até 0

> Peça números com `prompt()` até que o usuário digite `0`, e mostre a soma de todos.

```js
let soma = 0;
let num;

do {
  num = Number(prompt("Digite um número (0 para parar):"));
  soma += num;
} while (num !== 0);

alert("Soma total: " + soma);
```

---

### 🔴 **Exercícios Avançados (Lógica + DOM ou Desafios)**

#### 9. 📦 Lista de produtos com preço

> Peça o nome e preço de 3 produtos e mostre o total da compra.

```js
let total = 0;

for (let i = 1; i <= 3; i++) {
  let produto = prompt(`Nome do produto ${i}:`);
  let preco = Number(prompt(`Preço de ${produto}:`));
  total += preco;
}

alert("Total da compra: R$ " + total.toFixed(2));
```

---

#### 10. 🧠 Jogo de adivinhação (1 a 10)

> Gere um número aleatório e peça para o usuário adivinhar.

```js
let secreto = Math.floor(Math.random() * 10) + 1;
let chute;

do {
  chute = Number(prompt("Adivinhe o número (1 a 10):"));
  if (chute < secreto) alert("Muito baixo!");
  else if (chute > secreto) alert("Muito alto!");
} while (chute !== secreto);

alert("Acertou! 🎯");
```

---


