# Node.js

> Entorn d'execució de JavaScript fora del navegador.

## Índex

1. [Què és Node.js?](#1-què-és-nodejs)
2. [Per què és important?](#2-per-què-és-important)
3. [NPM](#3-npm)
4. [NPX](#4-npx)
5. [Yarn](#5-yarn)
6. [Demo](#6-demo)
7. [Conclusió](#7-conclusió)

---

## 1. Què és Node.js?

Node.js és un entorn que permet executar **JavaScript fora del navegador**.

Amb Node.js podem executar codi JavaScript directament al nostre ordinador o en un servidor.

Node.js utilitza el motor **V8** per executar JavaScript.

---

## 2. Per què és important?

Node.js és una tecnologia molt utilitzada en el desenvolupament web actual.

També s'utilitza en eines de desenvolupament Front-End com:

* React
* Vue
* Angular
* Vite

---

## 3. NPM

**NPM (Node Package Manager)** és el gestor de paquets de Node.js.

Serveix per:

* Instal·lar llibreries.
* Gestionar dependències.
* Executar scripts.

Per exemple:

```bash
npm install cowsay
```

Les dependències del projecte es guarden al fitxer `package.json`.

---

## 4. NPX

**NPX** és una eina que permet executar paquets de Node.js sense haver d'instal·lar-los de manera permanent al projecte.

Per exemple:

```bash
npx cowsay "Hola DAW!"
```

És útil per executar eines de manera ràpida.

---

## 5. Yarn

**Yarn** és una alternativa a NPM per gestionar paquets i dependències.

Per exemple:

```bash
yarn add cowsay
```

NPM i Yarn tenen funcions molt similars.

---

## 6. Demo

En la demo crearem un petit projecte de Node.js i utilitzarem NPM i NPX.

Primer creem el projecte:

```bash
mkdir demo-node
cd demo-node
npm init -y
```

Instal·lem una dependència:

```bash
npm install cowsay
```

Creem el fitxer `app.js`:

```javascript
const cowsay = require("cowsay");

console.log(cowsay.say({
    text: "Hola DAW!"
}));
```

Executem el programa:

```bash
node app.js
```

També podem crear un script al `package.json`:

```json
"scripts": {
    "start": "node app.js"
}
```

I executar-lo amb:

```bash
npm start
```

Finalment, podem utilitzar **NPX** per executar una eina directament:

```bash
npx cowsay "Hola DAW!"
```

---

## 7. Conclusió

> Node.js permet executar JavaScript fora del navegador. NPM, NPX i Yarn faciliten la instal·lació, gestió i execució de paquets. És una tecnologia molt utilitzada en el desenvolupament web actual.

## Fonts

* [Node.js](https://nodejs.org/)
* [NPM](https://www.npmjs.com/)
* [Yarn](https://yarnpkg.com/)