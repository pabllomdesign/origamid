# CSS Seletores

### h1,p

- A virgula permite selecionarmos múltiplos elementos para a aplicação de um mesmo estilo

### p a

- Seleciona o a que tiver um p como elemento pai (não precisa ser filho direto)

![Captura de tela 2024-05-18 202803](https://github.com/pabllomdesign/origamid/assets/157547026/a0e6f6e4-a53f-44c5-857d-bf67794c2ee1)


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
![Captura de tela 2024-05-18 210751](https://github.com/pabllomdesign/origamid/assets/157547026/bc9ea9a2-c36f-4fe2-b563-04afa1384cb3)
