## Passo 1: Crie um novo repositório no GitHub
1. Vá para o GitHub e faça login na sua conta.
2. Crie um novo repositório clicando no botão "New" no canto superior direito.
3. Preencha as informações do repositório (nome, descrição, etc.) e clique em "Create repository".

## Passo 2: Clone o repositório no seu computador
```bash
git clone https://github.com/username/repo
cd nome-do-repositorio
```

## Passo 3: Criar um corpo de projeto simples
Vamos criar um projeto simples. Neste caso, um projeto web com HTML, CSS e JavaScript.
```bash
touch index.html style.css script.js
```
index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Meu Projeto Git</title>
</head>
<body>
    <h1>Meu Projeto Git</h1>
    <script src="script.js"></script>
</body>
</html>
```

style.css

```css

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    text-align: center;
}

h1 {
    color: #333;
}
```
script.js

```js
document.addEventListener('DOMContentLoaded', function() {
    alert('Bem-vindo ao Meu Projeto Git!');
});
```

## Passo 4: Verifique o conteúdo do repositório
Agora, adicione, faça commit e envie suas alterações para o GitHub.
```bash
git add .
git commit -m "Adicionado conteúdo"
git push or git push origin main
```

# Resultado final
![logo](./image-one.png)

<hr>

![logo](./image-two.png)

<hr>

