# 📹 Demonstração do Projeto:

https://github.com/user-attachments/assets/868e45c9-3a39-4430-aec7-ca8a1fe1790d

---

# 📩 Formulário de Contato

Este é um projeto simples de um **Formulário de Contato**, desenvolvido utilizando **HTML** e **CSS**. O objetivo é criar um layout moderno e responsivo para coleta de informações dos usuários.

---

## 🚀 Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **Flexbox** para alinhamento responsivo

---

## 🎨 Layout e Estilização

O design do formulário possui uma interface moderna com um fundo escuro e elementos em tons de verde para destaques. O foco está na usabilidade e na experiência do usuário.

### 🌑 Estilo Principal
- **Plano de fundo escuro** para uma interface moderna
- **Tipografia limpa** com fonte **Helvetica Neue**, Arial e Helvetica
- **Inputs responsivos** com realce para erros e validação
- **Botão de envio** estilizado com efeito de hover

---

## 📌 Estrutura do Projeto

```
/
├── index.html   # Estrutura do formulário
├── contato.css  # Estilização do formulário
└── README.md    # Documentação do projeto
```

---

## 📄 Código Fonte

### 📝 HTML
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Login</title>
    <link rel="stylesheet" href="contato.css">
</head>
<body>
    <form action="" method="post">
        <fieldset>
            <legend>Formulário de contato</legend>
            <label for="name">Nome</label>
            <input type="text" id="name" name="name" required placeholder="Digite seu nome completo">
            <label for="email">E-mail</label>
            <input type="email" name="email" id="email" required placeholder="Digite um e-mail válido">
            <label for="subject">Assunto</label>
            <input type="text" id="subject" name="subject">
            <label for="message">Mensagem</label>
            <textarea name="message" id="message" rows="7" required maxlength="3000" minlength="20" placeholder="Digite aqui o seu texto"></textarea>
            <button type="submit" class="btn">Enviar</button>
        </fieldset>
    </form>
</body>
</html>
```

### 🎨 CSS
```css
html {
    background-color: #181818;
    font-family: "Helvetica Neue", Arial, Helvetica, sans-serif;
    color: white;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
}

form {
    width: 90%;
    min-width: 28.125em;
    max-width: 35em;
    background-color: #0e1010;
    padding: 1em;
}

fieldset {
    border: none;
    padding: 0;
    margin: 0;
}

label, input, textarea {
    display: block;
    width: 100%;
    box-sizing: border-box;
    color: #0ec72a;
}

input, textarea {
    background-color: rgba(0, 0, 0, .3);
    border: 2px solid transparent;
    border-bottom-color: #bbb;
    padding: .75em;
    margin: .5em 0 2.5em;
    color: white;
    outline: 0;
}

input:invalid:focus, textarea:invalid:focus {
    border-bottom: 2px solid #ff000d;
}

input:valid:focus, textarea:valid:focus {
    border-bottom: 2px solid #0ec72a;
}

input:focus, textarea:focus {
    border-bottom: 2px solid #8e999a;
    background-color: #2a2727;
}

legend {
    padding: .5em;
    text-align: center;
    font-weight: bold;
    color: #0ec72a;
    font-size: 1.3em;
}

.btn {
    background-color: #2a2727;
    color: white;
    cursor: pointer;
    padding: .7em;
    font-size: 1.2em;
    border: none;
}
```

---

## 📌 Como Usar

1. Clone o repositório:
   ```sh
   git clone https://github.com/toz3tto/form_contato.git
   ```
2. Abra o arquivo `index.html` em seu navegador.
3. Teste o formulário preenchendo os campos e enviando os dados.

---

## 📢 Melhorias Futuras

- ✅ Adicionar um sistema de backend para processar os formulários
- ✅ Melhorar a acessibilidade do formulário
- ✅ Implementar uma versão responsiva para dispositivos menores

---

## 📝 Licença

Este projeto está sob a licença **MIT**. Sinta-se à vontade para usar e modificar! 🎉

