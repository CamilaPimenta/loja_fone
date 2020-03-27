# HTML 5

É uma linguagem de marcação que tem as seguintes responsabilidades:

- Conteúdo - textos, imagens, vídeos;
- Semântico - utilizar as TAGS de forma correta;
- Estrutura;

## Tag's

- `<h1>` - heading 1 - 6
Usada quando queremos definir títulos.

- `<a>` - link (a - anchor).
Usada para definir a navegação do usuário. Se tem um texto e quer que o usuário clique e seja direcionado para outro local, pode usar a tag junto com o atributo `href`. Exemplo de um `<a>` que o usuário é direcionado para um site.

```
<a href="http://www.google.com">Goole</a>
```

- `<!DOCTYPE html>` - avisar para o browser qual a versão do HTML que está o código. O browser utiliza a versão mais recente e mais estável disponível.

- `<html>` - tem que envolver todas as tag dentro dessa tag, pois mostra que elas são do HTML.

- `<meta charset="utf-8">` - tag para uma tabela em que tenha os caracteres para acentuação. Não define uma tag de fechamento. Usada para a configuração.

- `<body>` - Tudo o que temos controle para ser mostrado para o usuário. Tudo o que mostra informação para o usuário.

- `<header>` - cabeçalho do site. Envolve as tags que farão parte do cabeçalho.

- `<nav>` - (n - navigation) - avisa que todas as tags que envolve fazem parte do menu de navegação.

- `<head>` - tag usada para passar as configurações do código.

- `<title>` - Passa qual o título, o navegador que define onde ela estará. Geralmente é na aba da página.

- `<link>` - faz a relação entre as duas páginas html e css. 


# CSS

É uma linguagem de estilgo e tem as seguintes responsabilidades:

- Visual;

 - `overflow: hidden;` - esconde um elemento [recalcula um elemento que está com um novo contexto] Quando os 'filhos' estão flutuando e quiser que o pai considere-os. Serve também para não perder a altura e largura do pai.

- `padding;` - Respiro interno. Quando preciso que conteúdo de um elemento se afaste das extremidades uso o `padding`. 
Sempre o tamanho será em pixels. Espaçamento dentro do próprio elemento. Quando precisar que o lado direito ou esquerdo se afaste é só digitar (ex). Quando o respiro precisa ser da extremidade para baixo ou para cima. Os tamanhos nem sempre são iguais. 

```
padding left: 60px;
padding rigth: 60px;
padding top: 60px;
padding bottom: 150px;
```

- Primeira forma para escrever o `padding` simplificada onde o exemplo acima pode ser escrito dessa forma (lembrar sempre da sequência `padding: top right bottom left;`):
```
    (-> Forma resumida: padding: top right bottom left;)
    padding: 55px 60px 95px 60px;
```

- Segunda maneira simplificada em que são passados apenas dois valores, os valores de `top e bottom` são iguais e os valores de `right e left` são iguais(lembrar sempre da sequência `padding: top/bottom right/left;`):
```
    (-> Forma resumida: padding: top/bottom right/left;)
    padding: 55px 60px;
```
- Terceira maneira simplificada em que são passados três valores, o valor de `top` é único, os valores de `right e left` são iguais e o valor do `bottom` é único(lembrar sempre da sequência `padding: top right/left bottom;`):
```
    (-> Forma resumida: padding: top right/left bottom;)
    padding: 55px 60px 95px;
```
- Quarta maneira simplificada em que é passado apenas 1 único valor e o mesmo vale para `top/right/left/bottom`:
```
    (-> Forma resumida: padding: top/right/left/bottom;)
    padding: 60px;
```

- `padding-inline;` - é definido um `padding:inline` para os quatro lados de um elemento inline o efeito será aplicado somente nos lados esquerdo e direito, sendo ignorado o padding-top e o padding-bottom.
```
padding-inline: 60px;
```

- `margin;` - Respiro externo. Quando preciso que os elementos se afastem. Quando precisar que o lado direito ou esquerdo se afaste é só digitar (ex). Sempre o tamanho será em pixels. Espaçamento entre elementos. As formas reduzidas para descrever o `margin` funcionam da mesma fomra que funcionam no `padding`.
```
margin top: 60px;
margin bottom: 150px;
```

