# 📌 Projeto Perfil Interativo

Este projeto é uma página de perfil interativa com um modo claro/escuro e links para redes sociais. Criado com HTML, CSS e JavaScript, é uma forma elegante de compartilhar informações e redes sociais.

## 🚀 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (modo escuro/claro dinâmico)
- Ícones do Ionicons

## 🎨 Funcionalidades

- Alternância entre modo claro e escuro
- Exibição de avatar dinâmica conforme o tema
- Links para redes sociais e recursos

## 📸 Demonstração

<img src="./assets/cardLight.png" alt="">

## 🔧 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd nome-do-repositorio
   ```
3. Abra o arquivo `index.html` no navegador.

## 📄 Código Principal

```html
<!-- Estrutura do switch para alternância de tema -->
<div id="switch" onclick="toggleMode()">
    <button></button>
    <span></span>
</div>
```

```js
// Alternância de modo claro e escuro
function toggleMode(){
   const html = document.documentElement;
   html.classList.toggle('light');

   const img = document.querySelector(".profile img");
   img.setAttribute('src', html.classList.contains('light') ? './assets/avatar-light.png' : './assets/avatar.png');
}
```

## 📌 Autor

By [joseGjr](https://github.com/joseGjr)


