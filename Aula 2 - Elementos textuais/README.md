# Elementos textuais em HTML

## Parágrafo
   - O elemento `<p>` é usado para definir um parágrafo de texto.
   - Ele cria uma quebra de linha antes e depois do conteúdo do parágrafo.
   - Exemplo:
     ```html
     <p>Isto é um parágrafo.</p>
     ```

## Títulos 
   - Os elementos de `<h1>` a `<h6>` são usados para definir diferentes níveis de títulos, sendo `<h1>` o mais importante e `<h6>` o menos importante.
   - Eles são geralmente usados para organizar e estruturar o conteúdo da página.
   - Exemplo:
     ```html
     <h1>Título Principal</h1>
     <h2>Subtítulo</h2>
     ```

## Negrito
   - O elemento `<strong>` é usado para enfatizar o texto, indicando que o texto deve ser exibido em negrito.
   - Ele não possui significado semântico específico além de enfatizar o texto.
   - Exemplo:
     ```html
     <strong>Texto em negrito</strong>
     ```

## Itálico
   - O elemento `<em>` é usado para enfatizar o texto, indicando que o texto deve ser exibido em itálico.
   - Ele não possui significado semântico específico além de enfatizar o texto.
   - Exemplo:
     ```html
     <em>Texto em itálico</em>
     ```

## Sublinhado:
   - O elemento `<u>` é usado para criar um sublinhado no texto.
   - No entanto, é importante notar que o uso excessivo de sublinhados é desencorajado em design web moderno.
   - Exemplo:
     ```html
     <u>Texto sublinhado</u>
     ```

## Texto tachado
   - O elemento `<del>` é usado para representar texto que foi removido ou deletado.
   - Ele é frequentemente exibido com uma linha através do texto.
   - Exemplo:
     ```html
     <del>Texto deletado</del>
     ```

## Texto inserido
   - O elemento `<ins>` é usado para representar texto que foi inserido ou adicionado.
   - Ele é frequentemente exibido com sublinhado.
   - Exemplo:
     ```html
     <ins>Texto inserido</ins>
     ```

## Texto sobrescrito
   - O elemento `<sub>` é usado para representar texto que deve ser exibido como subscrito.
   - É comumente usado para fórmulas químicas e equações matemáticas.
   - Exemplo:
     ```html
     H<sub>2</sub>O
     ```

## Texto sobrescrito
   - O elemento `<sup>` é usado para representar texto que deve ser exibido como sobrescrito.
   - É comumente usado para exponenciação e índices.
   - Exemplo:
     ```html
     x<sup>2</sup>
     ```

## Citação em bloco
   - O elemento `<blockquote>` é usado para citar texto de outra fonte.
   - Ele geralmente é exibido com recuo e pode ter um efeito visual diferente em alguns navegadores.
   - Exemplo:
     ```html
     <blockquote>
       Esta é uma citação em bloco.
     </blockquote>
     ```

## Citação curta
   - O elemento `<q>` é usado para indicar uma citação curta dentro do texto.
   - Ele geralmente é envolto por aspas automáticas pelo navegador.
   - Exemplo:
     ```html
     <p>O autor disse: <q>Esta é uma citação curta.</q></p>
     ```

### Atividade

1. Crie um arquivo `texto.html`
2. Copie o seguinte código html
3. Abra em um navegador


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exemplo de Elementos Textuais em HTML</title>
</head>
<body>
    <h1>Título Principal</h1>
    
    <p>Este é um parágrafo de texto que contém <strong>texto em negrito</strong>, <em>texto em itálico</em>, <u>texto sublinhado</u>, <del>texto deletado</del>, <ins>texto inserido</ins>, <sub>texto subscrito</sub> e <sup>texto sobrescrito</sup>.</p>
    
    <h2>Subtítulo</h2>
    
    <blockquote>
        Esta é uma citação em bloco.
    </blockquote>
    
    <p>O autor disse: <q>Esta é uma citação curta.</q></p>
    
    <p>Por fim, <strong>concluímos</strong> nosso exemplo de elementos textuais em HTML. Espero que tenha sido útil!</p>
</body>
</html>
```

