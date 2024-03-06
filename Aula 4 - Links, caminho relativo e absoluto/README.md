# O elemento `<a>` (âncora) 

O elemento `<a>` é uma das partes fundamentais do HTML, usada para criar hiperlinks, permitindo aos usuários navegar de uma página para outra ou dentro da mesma página. Vamos explorar detalhadamente como usar e implementar o elemento `<a>` em HTML5.

## 1. Estrutura básica do elemento `<a>`

O elemento `<a>` tem a seguinte estrutura básica:

```html
<a href="URL_do_destino">Texto do Link</a>
```

- `href`: é o atributo obrigatório que especifica o destino do link. Pode ser um URL, um endereço de e-mail ou um ID de elemento no mesmo documento.
- `Texto do Link`: é o texto que aparece na página e que os usuários podem clicar para acessar o destino especificado.

## 2. Utilizando o elemento `<a>`

#### a. Criando um link para outra página da web:

```html
<a href="https://www.example.com">Visite o exemplo</a>
```

#### b. Criando um link para um endereço de e-mail:

```html
<a href="mailto:exemplo@example.com">Enviar e-mail de exemplo</a>
```

#### c. Criando um link para uma seção na mesma página:

```html
<a href="#secao1">Ir para a Seção 1</a>
```

#### d. Abrindo o link em uma nova aba/janela:

```html
<a href="https://www.example.com" target="_blank">Abrir em uma nova aba</a>
```

## 3. Outros atributos úteis do elemento `<a>`

#### a. Atributo `title`:

```html
<a href="https://www.example.com" title="Visite o Exemplo">Exemplo</a>
```

O atributo `title` fornece uma dica de ferramenta quando o usuário passa o mouse sobre o link.

#### b. Atributo `download`:

```html
<a href="arquivo.pdf" download>Download do PDF</a>
```

O atributo `download` faz com que o navegador baixe o arquivo em vez de navegar até ele quando o link é clicado.

#### c. Atributo `rel` (relacionamento):

```html
<a href="https://www.example.com" rel="nofollow">Link de Exemplo</a>
```

O atributo `rel` especifica o relacionamento entre a página atual e a página vinculada. O valor `nofollow` instrui os mecanismos de busca a não seguir o link.

O atributo `target` é usado no elemento `<a>` para especificar onde abrir o destino do link. Existem vários valores que podem ser atribuídos ao `target`, cada um determinando o comportamento do link quando clicado. Vamos explorar os principais valores do atributo `target`:

#### d. Atributo `target` e seus valores:

**`_self`**

Este é o valor padrão para o atributo `target`. Quando usado, o link abre no mesmo quadro ou janela em que foi clicado. Se você estiver dentro de um iframe, por exemplo, o link será aberto dentro do mesmo iframe.

Exemplo:
```html
<a href="https://www.example.com" target="_self">Abrir na mesma janela</a>
```

 **`_blank`**

Este valor faz com que o link seja aberto em uma nova janela ou aba do navegador, dependendo da configuração do navegador e do comportamento padrão.

Exemplo:
```html
<a href="https://www.example.com" target="_blank">Abrir em uma nova aba</a>
```

 **`_parent`**

Este valor faz com que o link seja aberto no quadro pai do quadro atual, se houver. Se não houver um quadro pai, ele funciona como `_self`.

Exemplo:
```html
<a href="https://www.example.com" target="_parent">Abrir no quadro pai</a>
```

 **`_top`**

Este valor faz com que o link seja aberto no topo do conjunto de quadros. Se o documento não estiver em um quadro, ele funciona como `_self`.

Exemplo:
```html
<a href="https://www.example.com" target="_top">Abrir no topo</a>
```

**Nome de uma janela ou quadro específico**

Também é possível definir o valor de `target` como o nome de uma janela ou quadro específico em que você deseja que o link seja aberto. Isso é usado principalmente quando trabalhando com janelas ou quadros nomeados em JavaScript.

Exemplo:
```html
<a href="https://www.example.com" target="minhaJanela">Abrir em uma janela com o nome "minhaJanela"</a>
```

Claro! Vamos explorar a sintaxe de caminhos absolutos e relativos em HTML, especialmente no contexto do atributo `href` do elemento `<a>`.

## 4. Caminho Absoluto e Relativo
#### Caminho Absoluto

Um caminho absoluto especifica o endereço completo para o recurso desejado, começando a partir da raiz do sistema de arquivos ou do servidor web. Ele inclui o esquema (como `http://` ou `https://`), o nome do host (como `www.example.com`), e o caminho completo para o recurso.

Exemplo de caminho absoluto:
```html
<a href="https://www.example.com/pagina.html">Link para a página</a>
```
Neste exemplo, o link aponta para a página `pagina.html` no site `www.example.com` usando o protocolo HTTPS.

### Caminho Relativo

Um caminho relativo especifica o endereço de um recurso em relação à localização atual do documento HTML. Ele não inclui o esquema ou o nome do host, apenas o caminho relativo ao documento atual.

- **Caminho Relativo ao Diretório Atual**: Indica o caminho em relação ao diretório atual do documento HTML.

Exemplo de caminho relativo ao diretório atual:
```html
<a href="imagens/foto.jpg">Link para a imagem</a>
```
Neste exemplo, o link aponta para uma imagem chamada `foto.jpg` dentro do diretório `imagens` no mesmo diretório do documento HTML atual.

- **Caminho Relativo à Raiz do Site**: Começa com uma barra (`/`) e indica o caminho em relação à raiz do site.

Exemplo de caminho relativo à raiz do site:
```html
<a href="/pasta/documento.pdf">Link para o documento PDF</a>
```
Neste exemplo, o link aponta para um documento PDF chamado `documento.pdf` no diretório `pasta` na raiz do site.

- **Referência ao Diretório Atual:** O ponto único (./) é uma notação que se refere explicitamente ao diretório atual em um caminho relativo. Na prática, é frequentemente omitido, já que os caminhos relativos sem ./ são implicitamente considerados como referentes ao diretório atual.

Exemplo:
```html
<a href="./outra_pagina.html">Link para outra página no mesmo diretório usando ./</a>
```

Neste exemplo, ./ está explicitamente referindo-se ao diretório atual, e outra_pagina.html é a página que está no mesmo diretório.

- **Caminho Relativo ao Diretório Pai**: Usa dois pontos (`..`) para indicar o diretório pai em relação à localização atual.

Exemplo de caminho relativo ao diretório pai:
```html
<a href="../outra_pasta/pagina.html">Link para outra página</a>
```
Neste exemplo, o link aponta para a página `pagina.html` dentro do diretório `outra_pasta`, que está no diretório pai do documento HTML atual.

