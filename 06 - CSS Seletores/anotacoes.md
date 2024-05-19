# CSS Seletores

### h1,p

- A virgula permite selecionarmos múltiplos elementos para a aplicação de um mesmo estilo

### p a

- Seleciona o a que tiver um p como elemento pai (não precisa ser filho direto)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/048eacc7-34eb-4d77-8b28-93509649fd7e/8b5155b8-1727-4102-aede-77f439d70e62/Untitled.png)

### ID

- Atributo HTML que adiciona um identificador **único** na tag. Esse identificador pode ser utilizado no CSS para selecionarmos o elemento: #nomeid

**HTML**

```html
<h1 id="logo">Bikcraft</h1>
```

**CSS**

```css
#logo {
  width: 200px;
}
```

### CLASS

- Atributo HTML que adiciona um identificador reutilizável na tag. Esse identificador pode ser utilizado no CSS para selecionarmos o(s) elemento(s): .nomedaclasse

**HTML**

```html
<h1>Cursos</h1>
<h2 class="codigo">HTML para iniciantes</h2>
<h2 class="codigo">CSS para iniciantes</h2>
<h2 class="codigo">JavaScript para iniciantes</h2>
<h2 class="design">UI Design</h2>
<h2 class="design">UX Design</h2>
```

**CSS**
