# 📝 4. Formulários HTML

Os formulários permitem receber informações fornecidas pelos usuários.

## Estrutura básica

```html
<form>

    <label for="nome">Nome:</label>

    <input type="text" id="nome" name="nome">

    <button type="submit">Enviar</button>

</form>
```

---

## Tipos de input

O HTML5 possui diferentes tipos de campos.

```html
<input type="text">
<input type="email">
<input type="password">
<input type="number">
<input type="date">
```

Cada tipo possui uma finalidade diferente.

---

## Label

O `<label>` identifica um campo do formulário:

```html
<label for="email">E-mail:</label>

<input type="email" id="email">
```

O atributo `for` deve estar relacionado ao `id` do campo.

---

## Botão

Um botão pode ser criado com:

```html
<button type="submit">Enviar</button>
```

---

## 🧩 Desafio

Crie um formulário contendo:

* Nome;
* E-mail;
* Senha;
* Idade;
* Botão de envio.

### 💡 Desafio extra

Tente utilizar corretamente os tipos:

```text
text
email
password
number
```
