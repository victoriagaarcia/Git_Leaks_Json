# Git_Leaks_Json
Se extraen en un fichero formato .json los commits encontrados en Git con posibles leaks de información. Se toma un repositorio de la empresa Skale y se recorren sus ramas realizándose una búsqueda de commits con palabras como 'password' o 'key', que pueden dar lugar a información delicada. Todas las ocurrencias encontradas se incluyen en un fichero JSON, adjunto también en este repositorio.
