HTML, que significa HyperText Markup Language (Linguagem de Marcação de Hipertexto), é o bloco de construção fundamental de páginas da web. Ele fornece a estrutura básica para o conteúdo na web, permitindo que os desenvolvedores definam e organizem o layout, o texto, as imagens, os links e outros elementos visuais de uma página da web.

### Importância do HTML:

1. **Estruturação de Conteúdo:** HTML é responsável por estruturar o conteúdo de uma página da web de forma lógica e semântica. Isso significa que através do HTML, os desenvolvedores podem definir cabeçalhos, parágrafos, listas, tabelas e outros elementos que compõem o conteúdo da página.

2. **Compatibilidade com Navegadores:** HTML é uma linguagem padronizada e é interpretada pelos navegadores da web. Isso significa que páginas HTML podem ser visualizadas em praticamente qualquer navegador web moderno, garantindo uma experiência consistente para os usuários.

3. **Acessibilidade e SEO:** Utilizando as tags semânticas corretas do HTML, os desenvolvedores podem melhorar a acessibilidade das suas páginas da web para pessoas com deficiência, bem como otimizar o conteúdo para mecanismos de busca (SEO), melhorando a visibilidade nos resultados de pesquisa.

4. **Integração com Outras Tecnologias:** HTML é frequentemente combinado com outras tecnologias web, como CSS (Cascading Style Sheets) para estilizar o conteúdo e JavaScript para adicionar interatividade e dinamismo às páginas.

5. **Base para o Desenvolvimento Web:** HTML é a base fundamental para o desenvolvimento web. Antes de aprender outras tecnologias web, como CSS e JavaScript, é essencial ter uma compreensão sólida do HTML, pois ele é o ponto de partida para criar qualquer tipo de conteúdo na web.

### Tags de markup

Tags de marcação, ou markup tags em inglês, são elementos utilizados em linguagens de marcação, como HTML (HyperText Markup Language), XML (eXtensible Markup Language), Markdown, entre outras, para definir a estrutura e o significado do conteúdo dentro de um documento.

As tags de marcação são compostas por um nome cercado por colchetes angulares (< e >), como por exemplo `<p>, <div>, <h1>, <a>`, entre outras. Essas tags são interpretadas pelo navegador ou outra aplicação que processa a linguagem de marcação e são responsáveis por definir como o conteúdo deve ser apresentado ou estruturado.

Por exemplo, em HTML, a tag `<p>` é utilizada para representar parágrafos de texto, enquanto a tag `<a>` é utilizada para criar links para outras páginas ou recursos.

As tags de marcação podem conter atributos, que são informações adicionais que modificam o comportamento ou a apresentação do elemento. Por exemplo, na tag `<img>`, o atributo src é utilizado para especificar o caminho da imagem que será exibida.

![Exemplo tag](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/HTML_basics/gato-rabujento-pequeno.png)
Fonte: https://developer.mozilla.org

As tags de marcação são essenciais para a criação de documentos estruturados na web e em outras formas de comunicação digital. Elas fornecem um meio consistente de representar informações e conteúdos, facilitando a compreensão e a interpretação por parte dos usuários e das máquinas que processam esses documentos.

### Atributos

As tags HTML podem conter atributos, que fornecem informações adicionais sobre o elemento. Por exemplo, o atributo src na tag `<img>` especifica o caminho para a imagem a ser exibida, enquanto o atributo href na tag `<a>` define o destino do link.

![Exemplo atributo](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/HTML_basics/gato-rabujento-atributo-pequeno.png)
Fonte: https://developer.mozilla.org

### Estrutura do Documento HTML:
Um documento HTML é composto por uma série de elementos, que são estruturados hierarquicamente. O arquivo possui extensão `.html`. O documento começa com a declaração `<!DOCTYPE html>`, que define o tipo de documento e a versão do HTML utilizada.

A estrutura básica de um documento HTML inclui as tags `<html>, <head> e <body>`. O conteúdo da página é colocado dentro da tag `<body>`, enquanto o `<head>` contém metadados e referências a recursos externos, como CSS e JavaScript.

### Primeiro Exemplo

Vamos analisar cada parte:

```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>Minha página de teste</title>
  </head>
  <body>
    <img src="images/firefox-icon.png" alt="minha página de teste" />
  </body>
</html>
```

- `<!doctype html>`: Declaração do tipo de documento HTML. Indica que este é um documento HTML5.

- `<html>`: Elemento raiz que envolve todo o conteúdo HTML da página.

- `<head>`: Contém metadados e informações sobre o documento, como o título da página e configurações de codificação.

  - `<meta charset="utf-8" />`: Define o conjunto de caracteres usado no documento como UTF-8, que suporta uma ampla variedade de caracteres e é comumente utilizado na web.
  
  - `<meta name="viewport" content="width=device-width" />`: Define a largura do viewport para o tamanho do dispositivo, o que é importante para garantir uma experiência de visualização adequada em dispositivos móveis.

  - `<title>Minha página de teste</title>`: Define o título da página exibido na aba do navegador ou na barra de título da janela.

- `<body>`: Contém todo o conteúdo visível da página, como texto, imagens, links, etc.

  - `<img src="images/firefox-icon.png" alt="minha página de teste" />`: Define uma imagem a ser exibida na página. O atributo `src` especifica o caminho da imagem, e o atributo `alt` fornece um texto alternativo que é exibido se a imagem não puder ser carregada ou se o usuário estiver usando um leitor de tela.

Neste exemplo, a página exibirá uma imagem com o ícone do Firefox, assumindo que o caminho `images/firefox-icon.png` está correto em relação ao diretório onde o arquivo HTML está localizado. O título da página será "Minha página de teste".

### Atividade

1. Baixe o arquivo teste.html que está na pasta Aula 1 em alguma pasta do seu computador.
2. Clicar com botão direito e abrir com algum navegador.
3. Abra o arquivo com algum editor (VS Code, Sublime etc).
4. Analise o código.
5. Modifique o Titulo da página.
6. Modifique a imagem e o texto.
7. Salve tudo.
8. Clicar com botão direito e abrir com algum navegador.

