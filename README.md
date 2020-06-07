### CSS-GRID-LAYOUT

```CSS
Definição das areas do template

grid-template-areas:
 "cabecalho" "cabecalho" "cabecalho"
 "conteudo" "conteudo" "conteudo"
  "rodape" "rodape" "rodape"
;

Tamanho de cada coluna da grid

grid-template-columns: 50px 100px 200px; 

Tamanho de cada linha da grid

grid-template-rows: 50px 100px 200px;

.cabecalho{
 grid-area:cabecalho;
}
.conteudo{
 grid-area:conteudo;
}
.rodape{
 grid-area:rodape;
}
