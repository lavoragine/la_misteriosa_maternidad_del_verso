# ReadMe

Este repositorio contiene los archivos del proyecto de edición del libro "La misteriosa maternidad del verso".

Build con pandoc: `pandoc md/*.md metadata/metadata.yaml -f markdown+smart+footnotes -t epub3 -s  --epub-toc-level= -o epub/3conf.epub`

# ToDo

- [X] añadir archivos de audio e incorporarlos en el libro-- (desde sigil: por alguna razon no funciona en pandoc)
- [X] tunear template & CSS para maquetar la página de título--
- [X] crear una muestra con texto & audio
- [X] custom css for auddio controls
- [X] incluir audios en nav
- [ ] mejorar audios (volumen de audio de la gaby)
- [ ] crear links en la web a wikipedia y goodreads
- [ ] 
