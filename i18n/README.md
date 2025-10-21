inizia tutto da interfaces:

1.  base contiene le interfacce per il layout (navbar, footer e meta tag comuni)

2.  si crea un file di interfaccia per ogni pagina, con il suo stesso nome (ex: index.astro > index.interface.astro), qua si mettono traduzioni
    e overwrite per i meta facendo ereditare da base.interface.ts

3.  dentro translations c'e' una cartella per ogni lingua, in esse, un oggetto di traduzione che eredita dalla interfaccia relativa

4.  alla creazione della pagina dentro pages, inserire il layout, la content component nella slot e passare la traduzione
