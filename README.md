# 🧠 Decisões em Lógica: simples, composta e encadeada

Quando programamos, muitas vezes precisamos que o computador **tome decisões**.
Essas decisões são baseadas em **condições** (verdadeiro ou falso).
👉 É como responder perguntas de **Sim/Não** no dia a dia:

* “Está chovendo?”
* “A idade é maior que 18?”
* “A senha está correta?”

Essas perguntas são traduzidas em **expressões lógicas** dentro do código.

---

## 🔹 Decisão **Simples** (if)

👉 **Definição:** executa uma ação **somente se a condição for verdadeira**.
Se não for, o algoritmo apenas segue em frente sem fazer nada.

📌 **Exemplo no cotidiano:**
“Se estiver chovendo, levo guarda-chuva.”

* Se chover → pega o guarda-chuva
* Se não → segue a vida normalmente

### Exemplo em JavaScript

```js
const chuva = true;

if (chuva) {
  console.log("Levar guarda-chuva ☔");
}
```

---

## 🔸 Decisão **Composta** (if…else)

👉 **Definição:** oferece **dois caminhos possíveis**:

* um quando a condição é verdadeira
* outro quando a condição é falsa

📌 **Exemplo no cotidiano:**
“Se a idade for maior ou igual a 18, pode entrar; senão, não pode.”

### Exemplo em JavaScript

```js
const idade = 16;

if (idade >= 18) {
  console.log("Pode entrar ✅");
} else {
  console.log("Não pode entrar ❌");
}
```

---

## 🔻 Decisão **Encadeada** (if…else if…else)

👉 **Definição:** quando há **mais de duas possibilidades**, testamos condições em sequência.

* A primeira condição verdadeira é escolhida.
* Se nenhuma for verdadeira, usamos o **else** como “padrão”.

📌 **Exemplo no cotidiano:**
“Se a nota for maior ou igual a 7, aprovado; se for maior ou igual a 5, recuperação; senão, reprovado.”

### Exemplo em JavaScript

```js
const nota = 6;

if (nota >= 7) {
  console.log("Aprovado 🎉");
} else if (nota >= 5) {
  console.log("Recuperação 📘");
} else {
  console.log("Reprovado ❌");
}
```

---

## 🔍 Resumindo

* **Simples:** só faz algo se for verdadeiro.
* **Composta:** escolhe entre dois caminhos.
* **Encadeada:** decide entre várias opções.

💡 Pensar em **perguntas do dia a dia** ajuda muito a visualizar como as condições funcionam.

