# Listas

EM HTML5 existem elementos para criar listas: `<ul>`, `<ol>`, e `<dl>`.
O elemento `<li>` em HTML5 é usado para criar itens em listas, sejam elas ordenadas (`<ol>`) ou não ordenadas (`<ul>`). `<li>` significa "list item" em inglês, e é essencial para a estruturação de conteúdo em listas.

## 1. `<ul>` - Unordered List (Lista não ordenada)

O elemento `<ul>` é utilizado para criar listas não ordenadas, onde os itens não possuem uma ordem específica.

**Exemplo: Lista de Ingredientes com Atributos:**
```html
<ul type="circle">
  <li>Farinha</li>
  <li>Açúcar</li>
  <li>Ovos</li>
  <li>Leite</li>
</ul>
```

**Atributos:**
- `type`: Define o estilo dos marcadores de lista (discos, quadrados, círculos). Os valores possíveis para o atributo type em `<ul>` são:
  - type="disc": Define o marcador como um disco preenchido.
  - type="circle": Define o marcador como um círculo não preenchido.
  - type="square": Define o marcador como um quadrado preenchido.
  
Esses valores determinam o estilo visual dos marcadores usados nos itens da lista não ordenada. Por exemplo, se você definir type="circle", cada item da lista será precedido por um marcador em forma de círculo não preenchido.


## 2. `<ol>` - Ordered List (Lista ordenada)

O elemento `<ol>` é utilizado para criar listas ordenadas, onde os itens são numerados em sequência.

**Exemplo: Passos para Preparar um Bolo com Atributos:**
```html
<ol type="1" start="1" >
  <li>Pré-aqueça o forno a 180°C.</li>
  <li>Misture os ingredientes secos em uma tigela.</li>
  <li>Adicione os ingredientes líquidos e misture bem.</li>
  <li>Despeje a massa em uma forma untada.</li>
  <li>Asse por 30-40 minutos, ou até dourar.</li>
</ol>
```

**Atributos:**
- `type`: Define o estilo dos números da lista (1, A, a, I, i).
  - type="1": Numeradores decimais (1, 2, 3, ...).
  - type="A": Letras maiúsculas do alfabeto (A, B, C, ...).
  - type="a": Letras minúsculas do alfabeto (a, b, c, ...).
  - type="I": Numeradores romanos maiúsculos (I, II, III, ...).
  - type="i": Numeradores romanos minúsculos (i, ii, iii, ...). 
- `start`: Define o valor inicial da lista ordenada.
- `reversed`: Inverte a ordem dos números na lista.
.

### 3. `<dl>` - Description List (Lista de Descrição)

O elemento `<dl>` é utilizado para criar uma lista de termos e suas descrições correspondentes.
`<dt>`: O elemento `<dt>` é usado para representar os termos ou itens que estão sendo definidos na lista de definição. É abreviação de "definition term" em inglês.

`<dd>`: O elemento `<dd>` é usado para representar as definições ou descrições correspondentes aos termos na lista de definição. É abreviação de "definition description" em inglês.

**Exemplo: Glossário de Termos Técnicos com Atributos:**
```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language - Linguagem de marcação usada na criação de páginas web.</dd>
  
  <dt>CSS</dt>
  <dd>Cascading Style Sheets - Linguagem de estilo utilizada para definir a apresentação de documentos HTML.</dd>
  
  <dt>JavaScript</dt>
  <dd>Linguagem de programação de alto nível frequentemente utilizada para criar interatividade em páginas web.</dd>
</dl>
```

 

