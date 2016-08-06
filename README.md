Desafio-cssPDF
==============

(avaliando tradução e merge com [print-css.rocks](https://print-css.rocks/intro.html))

<small>Concurso para "melhor visual e diagramação" de PDF obtido de HTML+CSS puro</small>

O uso de recursos CSS para documentos paginados ([CSS-page](http://www.w3.org/TR/CSS21/page.html)) ainda é pouco difundido,  assim como as ferramentas que lidam com esses recursos na geração de PDF. 
Essa foi a conclusão de [uma discussão na lista okfn-br@lists.okfn.org](http://open-knowledge-foundation-brasil-rede-pelo-conhecimento-livre.50579.x6.nabble.com/okfn-br-dados-abertos-burilados-num-PDF-tt4121.html), que  motivou 
o presente desafio aos webdesigners e experts em ferramentas de diagramação de PDF, partindo apenas de *HTML+CSS*.

Arquivos de HTML que exemplificam conteúdos típicos para a diagramação,

* Documentos sem padrão de referência:
 * **Livros**: ...
   * `thesis.htm`: ref. [yeslogic/prince-samples](https://github.com/yeslogic/prince-samples/tree/master/thesis)
 * **Catálogos**: 
   * `atividades-MEI.htm` apresenta tabelas, seções e índices. Requer apresentação compacta. 
   * `PrinceCatalogue.htm`: ref. [princexml.com/samples/catalog](http://www.princexml.com/samples/catalog/PrinceCatalogue.html)

* Documentos baseados em padrão de referência:
 * Documentos científicos, padrão **HTML-SJTAS**: *HTML Simple [JATS](https://en.wikipedia.org/wiki/Journal_Article_Tag_Suite)*
 * Documentos legislativos, padrão **HTML-SLexML** e **HTML-PMSPretranca**: *HTML Simple [LexML](https://en.wikipedia.org/wiki/LexML_Brasil)* e "[Diário Oficial da PMSC marcado com retrancas](http://devcolab.each.usp.br/do/)"

Na pasta `css` encontra-se um exemplo de CSS de referências, para destacar o mínimo de "efeitos de diagramação", típicos de *CSS-page*, que se espera conseguir usar.

## Como participar do concurso
...

Ferramentas aventadas (postar pedido no /issues  para discutir ou incluir outras):

* Ferramentas abertas:
 * [pandoc](http://pandoc.org/)
 * [pandoc MultiMarkDown](http://fletcherpenney.net/multimarkdown/install/#macosx)
 * [wkHtmlToPdf](http://wkHtmlToPdf.org/)
 * [LibreWriter](https://www.libreoffice.org/discover/writer/) (atualmente perde CSS2-page).

* Ferramentas "caixa preta":
 * [PrinceXML](http://www.princexml.com/)
 * [AntennaHouse](http://www.antennahouse.com/)
 * [ABC-PDF](http://www.websupergoo.com/abcpdf-1.htm)
 * [MS-Word](https://en.wikipedia.org/wiki/Microsoft_Word) (atualmente perde CSS2-page).

## regras
As diferenças entre o original e o fornecido serão documentadas no *git* e levadas em conta no julgamento. 
Modificações  inválidas tais como reposicionamento de blocos serão desclassificadas...

## Julgamento
Os resultados de conversões válidas (ver regras) do HTML+CSS para PDF serão julgados em três categorias: 
* Melhor design dentro da ferramenta (caso apresente mais de um concorrente)
* Melhor design entre todas as ferramentas públicas
* Melhor design entre todas as ferramentas


