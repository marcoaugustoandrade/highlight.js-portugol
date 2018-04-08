# highlight.js-portugol
Suporte Highlightjs para Portugol Studio.

### Utilize um dos dois temas disponíveis (light ou dark):
```html
<link rel="stylesheet" href="css/portugol-studio-light.css">
```
ou
```html
<link rel="stylesheet" href="css/portugol-studio-dark.css">
```

### Importe o arquivo js/highlight.js e carregue o método initHighlightingOnLoad:
```html
<script href="js/highlight.js"></script>
<script>hljs.initHighlightingOnLoad();</script>
```
              
### Utilize as classes do Highlight para Portugol:
```html
<pre><code class="hljs portugol">
    programa
    {
        funcao inicio()
        {
            // Declaração das Variáveis
            inteiro idade = 12
            cadeia nome

            escreva("Informe o nome: ")
            leia(nome)
            limpa()

            se (idade >= 18){
                escreva("Maior de idade!")
            } senao {
                escreva("Menor de idade!")
            }
        }
    }
</code></pre>
```
