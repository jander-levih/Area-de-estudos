# Comentários das principais tags HTML

- `<!DOCTYPE html>`: Declara que este documento é um documento HTML5.
- `<html>`: Elemento raiz de uma página HTML.
- `<head>`: Contém meta informações sobre a página HTML.
- `<title>`: Especifica um título para a página HTML (mostrado na barra de título do navegador ou na guia da página).
- `<body>`: Define o corpo do documento e é um contêiner para todo o conteúdo visível, como títulos, parágrafos, imagens, hiperlinks, tabelas, listas, etc.
- `<h1>`: Define um grande título.
- `<p>`: Define um parágrafo.

---

## O que são atributos em HTML?

Todo elemento HTML (como `<p>`, `<img>`, `<a>`, etc.) pode ter atributos.

Eles não aparecem na página para o usuário, mas servem para dar informações extras ao navegador sobre como aquele elemento deve funcionar ou ser exibido.

Os atributos ficam sempre dentro da tag de abertura.

Normalmente eles seguem o formato `nome="valor"`.

---

## Exemplos práticos

**Adicionar um link com o atributo `href`:**

```html
<a href="https://google.com">Ir para o Google</a>
```
➡️ Aqui o atributo é `href` e o valor é o endereço do site.

**Imagem com `src` e `alt`:**

```html
<img src="gato.png" alt="Foto de um gato fofo">
```
➡️ `src` indica o caminho da imagem e `alt` é um texto alternativo (caso a imagem não carregue).

**Parágrafo com estilo inline usando `style`:**

```html
<p style="color:red;">Este é um parágrafo vermelho.</p>
```
➡️ O atributo `style` permite definir estilos diretamente na tag, como cor, fonte ou tamanho.

**Definindo idioma da página com `lang`:**

```html
<html lang="pt-BR">
```
➡️ O atributo `lang` informa ao navegador e buscadores o idioma principal do conteúdo.

**Tooltip com o atributo `title`:**

```html
<p title="Sou uma dica!">Passe o mouse aqui.</p>
```
➡️ O atributo `title` exibe uma dica quando o usuário passa o mouse sobre o elemento.

**Imagem com largura, altura e texto alternativo:**

```html
<img src="img_girl.jpg" width="500" height="600" alt="Menina com uma jaqueta">
```
➡️ Os atributos `width` e `height` definem o tamanho da imagem, enquanto `alt` fornece texto alternativo para acessibilidade.

```html
<p style="color: blue;">Esse texto está azul</p>
```
➡️ O atributo `style` muda a cor do texto.

**Input de formulário com `type` e `placeholder`:**

```html
<input type="text" placeholder="Digite seu nome">
```
➡️ O atributo `type` define o tipo do campo (texto, número, senha etc.) e `placeholder` mostra uma dica dentro do campo.

---

👉 **Em resumo:** atributo = informação extra dentro da tag.

**Exemplo de estrutura:**

```html

**Boas práticas:**
- Use nomes de atributos em minúsculas.
- Coloque valores entre aspas duplas.
- Evite omitir aspas, especialmente se o valor tiver espaços.


## 📖 Resumo do capítulo

Todo elemento HTML pode ter atributos.

- `href` → Define destino do link (`<a>`).
- `src` → Define caminho da imagem (`<img>`).
- `width` e `height` → Tamanho da imagem.
- `alt` → Texto alternativo da imagem.
- `style` → Estilo inline.
- `lang` → Idioma da página.
- `title` → Tooltip ao passar o mouse.
```