# highlight.js-portugol
Suporte Highlightjs para Portugol Studio.

### Utilize um dos dois temas disponíveis (light ou dark):
<pre><code>
<link rel="stylesheet" href="css/portugol-studio-light.css">
</code></pre>
ou
<pre><code>
<link rel="stylesheet" href="css/portugol-studio-dark.css">
</code></pre>

### Importe o arquivo js/highlight.js e carregue o método initHighlightingOnLoad:
<pre><code>
<script href="js/highlight.js></script>
<script>hljs.initHighlightingOnLoad();</script>
</code></pre>
              
### Utilize as classes do Highlight para Portugol:
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
