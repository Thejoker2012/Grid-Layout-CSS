### CSS-GRID-LAYOUT

```CSS
grid-template-areas:
 "cabecalho" "cabecalho" "cabecalho"
 "conteudo" "conteudo" "conteudo"
  "rodape" "rodape" "rodape"
;

Tamanho de cada coluna da grid

grid-template-columns: 50px 100px 200px; 

Tamanho de cada linha da grid

grid-template-rows: 50px 100px 200px;

Definindo a área do  cabeçalho no template
.cabecalho{
 grid-area:cabecalho;
}

Definindo a área do conteúdo no template
.conteudo{
 grid-area:conteudo;
}

Definindo a área do rodapé no template
.rodape{
 grid-area:rodape;
}
