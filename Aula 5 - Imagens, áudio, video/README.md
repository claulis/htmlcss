# 1. `<img>`  

A tag `<img>` é utilizada em HTML para inserir imagens em uma página da web. É uma das tags mais básicas e fundamentais para a criação de conteúdo visual na web. 
A sintaxe básica da tag `<img>` é a seguinte:

```html
<img src="caminho_da_imagem" alt="texto_alternativo">
```

- `src`: Este atributo especifica o caminho para a imagem. Pode ser um caminho relativo ou absoluto.
- `alt`: Este atributo fornece um texto alternativo para a imagem. É usado pelos leitores de tela para acessibilidade e também é exibido quando a imagem não pode ser carregada.

**Exemplos**

**Exemplo 1: Inserindo uma imagem simples**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Imagem</title>
</head>
<body>
    <h1>Minha Imagem</h1>
    <img src="imagem.jpg" alt="Uma imagem simples">
</body>
</html>
```

**Exemplo 2: Imagem com link**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagem com Link</title>
</head>
<body>
    <a href="pagina.html">
        <img src="imagem.jpg" alt="Uma imagem com link">
    </a>
</body>
</html>
```

**Atributos adicionais**

**`width` e `height`**
Você também pode especificar a largura (`width`) e a altura (`height`) da imagem, em pixels. Isso pode ser útil para garantir que o espaço necessário para a imagem seja reservado antes mesmo de ela ser carregada.

**`title`**
O atributo `title` fornece um texto de título para a imagem, que geralmente aparece quando o usuário passa o mouse sobre a imagem.

**`loading`**
O atributo `loading` pode ser usado para controlar como a imagem é carregada. Os valores possíveis são `"eager"` (carrega imediatamente) e `"lazy"` (carrega apenas quando está prestes a entrar na tela). Isso pode melhorar o desempenho, especialmente em páginas com muitas imagens.

# 2. `<audio>`

A tag `<audio>` é utilizada em HTML para incorporar arquivos de áudio em uma página da web. Ela oferece uma maneira simples e eficaz de reproduzir áudio diretamente no navegador, sem a necessidade de plugins externos. 
A sintaxe básica da tag `<audio>` é a seguinte:

```html
<audio src="caminho_do_arquivo_de_audio" controls>
    Seu navegador não suporta a tag de áudio.
</audio>
```

- `src`: Este atributo especifica o caminho para o arquivo de áudio. Pode ser um caminho relativo ou absoluto.
- `controls`: Este atributo exibe os controles de reprodução de áudio (como play, pause, volume) para o usuário.

**Exemplos**

**Exemplo 1: Reproduzindo um arquivo de áudio simples**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Áudio</title>
</head>
<body>
    <h1>Meu Áudio</h1>
    <audio src="audio.mp3" controls>
        Seu navegador não suporta a tag de áudio.
    </audio>
</body>
</html>
```

**Exemplo 2: Áudio sem controles visíveis**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Áudio sem Controles</title>
</head>
<body>
    <h1>Meu Áudio</h1>
    <audio src="audio.mp3">
        Seu navegador não suporta a tag de áudio.
    </audio>
</body>
</html>
```

**Exemplo 3: Reproduzindo áudio automaticamente**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Áudio Automático</title>
</head>
<body>
    <h1>Meu Áudio</h1>
    <audio src="audio.mp3" controls autoplay>
        Seu navegador não suporta a tag de áudio.
    </audio>
</body>
</html>
```

**Atributos adicionais**

**`autoplay`**
O atributo `autoplay` faz com que o áudio comece a ser reproduzido automaticamente assim que a página é carregada.

**`loop`**
O atributo `loop` faz com que o áudio seja reproduzido em um loop contínuo, repetindo-se indefinidamente.

**`preload`**
O atributo `preload` pode ser usado para especificar se e como o áudio deve ser pré-carregado. Os valores possíveis são `"none"` (não pré-carrega), `"metadata"` (pré-carrega apenas metadados) e `"auto"` (pré-carrega todo o áudio).

# 3. `<video>` 

A tag `<video>` é utilizada em HTML para incorporar vídeos em uma página da web. Ela oferece uma maneira simples e eficaz de reproduzir vídeos diretamente no navegador, sem a necessidade de plugins externos. 
A sintaxe básica da tag `<video>` é a seguinte:

```html
<video src="caminho_do_arquivo_de_video" controls>
    Seu navegador não suporta a tag de vídeo.
</video>
```

- `src`: Este atributo especifica o caminho para o arquivo de vídeo. Pode ser um caminho relativo ou absoluto.
- `controls`: Este atributo exibe os controles de reprodução de vídeo (como play, pause, volume) para o usuário.

**Exemplos**

**Exemplo 1: Reproduzindo um vídeo simples**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Vídeo</title>
</head>
<body>
    <h1>Meu Vídeo</h1>
    <video src="video.mp4" controls>
        Seu navegador não suporta a tag de vídeo.
    </video>
</body>
</html>
```

**Exemplo 2: Vídeo sem controles visíveis**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vídeo sem Controles</title>
</head>
<body>
    <h1>Meu Vídeo</h1>
    <video src="video.mp4">
        Seu navegador não suporta a tag de vídeo.
    </video>
</body>
</html>
```

**Exemplo 3: Reproduzindo vídeo automaticamente**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vídeo Automático</title>
</head>
<body>
    <h1>Meu Vídeo</h1>
    <video src="video.mp4" controls autoplay>
        Seu navegador não suporta a tag de vídeo.
    </video>
</body>
</html>
```

**Atributos adicionais**

**`autoplay`**
O atributo `autoplay` faz com que o vídeo comece a ser reproduzido automaticamente assim que a página é carregada.

**`loop`**
O atributo `loop` faz com que o vídeo seja reproduzido em um loop contínuo, repetindo-se indefinidamente.

**`preload`**
O atributo `preload` pode ser usado para especificar se e como o vídeo deve ser pré-carregado. Os valores possíveis são `"none"` (não pré-carrega), `"metadata"` (pré-carrega apenas metadados) e `"auto"` (pré-carrega todo o vídeo).

