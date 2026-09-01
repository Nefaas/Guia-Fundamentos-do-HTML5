# 🧱 5. HTML Semântico

HTML semântico consiste em utilizar elementos que possuem significado sobre o conteúdo que representam.

Isso melhora a organização do código e facilita sua interpretação por navegadores, ferramentas e tecnologias assistivas.

## Principais elementos

### `<header>`

Representa o cabeçalho de uma página ou seção.

### `<nav>`

Representa uma área de navegação.

### `<main>`

Representa o conteúdo principal da página.

### `<section>`

Representa uma seção do conteúdo.

### `<article>`

Representa um conteúdo independente.

### `<footer>`

Representa o rodapé da página ou seção.

---

## Exemplo

```html
<header>
    <h1>Meu site</h1>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Sobre</a>
</nav>

<main>

    <section>
        <h2>Sobre mim</h2>

        <p>
            Sou estudante de desenvolvimento web.
        </p>
    </section>

</main>

<footer>
    <p>Meu site - 2026</p>
</footer>
```

---

## ❌ Evite

Utilizar apenas `<div>` para representar toda a estrutura da página:

```html
<div>
    <div>
        <h1>Meu site</h1>
    </div>

    <div>
        Conteúdo
    </div>
</div>
```

Quando existe um elemento semântico apropriado, prefira utilizá-lo.

---

## 🧠 Desafio

Qual elemento você utilizaria para representar:

**1. Navegação**

<details>
<summary>Resposta</summary>

`<nav>`

</details>

**2. Conteúdo principal**

<details>
<summary>Resposta</summary>

`<main>`

</details>

**3. Rodapé**

<details>
<summary>Resposta</summary>

`<footer>`

</details>
