> :warning: Projeto muito antigo e depreciado!

#Bem vindo(a)!
_v 0.1_

Este material visa auxiliar a publicação de conteúdos no site do PHP-PR.

Primeiramente deixar claro que atualmente o PHP-PR utiliza como base o WordPress então seria bom se você já possuísse um mínimo de conhecimento no painel administrativo do mesmo. Caso não possua não tem problema aqui vai um tutorial rapido de como publicar conteúdo.


##Criação do post

Após estar logado no painel administrativo clique em **posts** e em seguida **Add New** como mostra na imagem abaixo. 

![Adicionando um novo post][1]


##Detalhes do post

Agora informe um nome para seu post e comece a redigir seu texto.

![Título e conteúdo][2]

Por padrão utilizamos o [Code Prettify][3] do Google e você pode adicionar o sintax da linguagem desejada (desde que a mesma esteja disponível na biblioteca que o Google fornece). Para que isto seja possível é necessário adicionar o conteúdo dentro das tags `<pre></pre>` e adicionar as classes mínimas necessárias que são `prettyprint` e `lang-{linguagem-desejada}` Exemplo:

```html
<pre class="prettyprint lang-php">
<?php 
    echo 'Este é um exemplo de um código em PHP';
</pre>
```

O resultado será:

```php
<?php 
    echo 'Este é um exemplo de um código em PHP';
```

A imagem abaixo mostra como habilitar as opções avançadas do editor.

![Habilitando ações avançadas do editor][4]

Após estar com as opções expandidas basta adicionar o texto, selecionar o mesmo e informar que o estilo do mesmo é pre formatado como mostra na imagem abaixo.

![Selecionando texto e definindo-o como pre formatado][5]

Agora basta que você alterne de editor visual para editor de texto e adicionando as classes `prettyprint` e `lang-{linguagem-desejada}` como mostra nos passos 1 e 2 da imagem seguinte.

![Adicionando classes][6]

Pronto! Agora pode ser visualizado no admin.

> Se você clicar em Preview (pre visualizar) o prettyprint ainda não
> estará disponível. O mesmo somente se torna visível e deixa o código
> com sua sintax correta após o post ser enviado para revisão.

A visualização no admin não surtirá efeito, somente no Front e após o post estar com status "Pending Review".

![Resultado no admin][7]

Após ter criado todo seu conteúdo e aplicadas as classes para sintax da linguagem em tudo o que precisava basta finalizar as informações do post.

Defina a categoria do mesmo, tags, imagem destacada (se for necessário e preferencialmente não muito pesada para melhorar o carregamento de mobile) e as melhorias de SEO. 

Se você não entender muito de SEO (Search Engine Optimization) que é o melhoramento do conteúdo (entre outros) para motores de busca basta seguir as dicas que o próprio plugin SEO by Yoast dá clicando em "Page Analysis".

![Categorias tags imagem destacada e SEO][8]

Agora que está tudo pronto, basta enviar seu post para revisão e aguardar a publicação.

> Se necessária alguma correção você será avisado(a).

Após ter clicado em "Submit for review" você pode clicar em "Preview" para ver como seu post ficará após ser publicado.

![Enviar para revisão e preview][9]

> Este preview somente é visível por você, caso envie a URL do mesmo para alguém o mesmo não terá acesso ao seu conteúdo até que o mesmo seja de fato publicado.


Preview de seu artigo/post no site.

![preview][10]


Novamente, agradecemos sua contribuição!


> Written with [StackEdit](https://stackedit.io/).


  [1]: https://github.com/php-pr/site-author-guide/blob/master/images/1-adicionando-post.jpg?raw=true
  [2]: https://github.com/php-pr/site-author-guide/blob/master/images/2-titulo-e-conteudo.jpg?raw=true
  [3]: https://code.google.com/p/google-code-prettify/
  [4]: https://github.com/php-pr/site-author-guide/blob/master/images/3-expandindo-opcoes-avancadas.jpg?raw=true
  [5]: https://github.com/php-pr/site-author-guide/blob/master/images/4-aplicando-preformatted.jpg?raw=true
  [6]: https://github.com/php-pr/site-author-guide/blob/master/images/5-adicionando-classe-prettyprint.jpg?raw=true
  [7]: https://github.com/php-pr/site-author-guide/blob/master/images/6-resultado-no-admin.jpg?raw=true
  [8]: https://github.com/php-pr/site-author-guide/blob/master/images/8-seo-tags-imagem-destacada.jpg?raw=true
  [9]: https://github.com/php-pr/site-author-guide/blob/master/images/9-enviar-para-revisao-e-previsualizar.jpg?raw=true
  [10]: https://github.com/php-pr/site-author-guide/blob/master/images/10-previsualizando.jpg?raw=true
