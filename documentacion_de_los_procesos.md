# Aplanar nombres de grupos
Paras las especificaciones definidas por el Sistema Abierto de Apariciones en el Territorio necesitamos que los nombres de los proyectos no tengan espacios, ni caracteres especiales, aquí se documenta la manera de hacerlo en emacs.
# Emacs
* Exporte los nombres de los proyectos a un archivo separado por líneas.
* Seleccione todo ```C-x h``` y convierta todo a minúscilas usando ```M-x downcase-region```
* Reemplaze los espacios por guión bajo "_" usando la opción de reemplazo (para ejecutarlo sobre todo el archivo uselo con la admiración !)
* Reemplaze los caracteres especiales
