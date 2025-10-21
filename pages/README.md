per mantere ssr/ssg le pagine sono strutturate cosi:

1.  Il layout Page contiente navbar, footer, slot per content e meta tag.

2.  Page prende come slot il contenuto effettivo della pagina.

3.  Per condividere la struttura della pagina senza duplicarle, il contenuto verra tenuto dentro la cartella content.
    Dentro le cartelle della lingua c'e' solo il file per il routing che passa la lingua e le stringhe di traduzione al contenuto e il layout

4.  Per la struttura dei file di traduzione riferirsi al README.md presenta dentro la cartella i18n
