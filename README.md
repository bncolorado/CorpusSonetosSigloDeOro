#Corpus de sonetos castellanos del Siglo de Oro.

##Introducción

Corpus formado por sonetos escritos en castellano entre los siglos XVI y XVII.

Cada soneto ha sido anotado en XML siguiendo el estándar [TEI](http://www.tei-c.org/index.xml). Además de encabezado e información estructural, cada soneto tiene representado formalmente los __patrones métricos__ de cada verso.

El patrón está formado por la secuencia de sílabas átontas (representadas con el signo "-") y tónicas (símbolo "+"). La métrica de cada verso queda así representada:

		<l n="1" met="---+---+-+-">Cuando me paro a contemplar mi estado,</l>

##Poetas

Con el objetivo de crear un corpus lo más representativo posible, se ha incluido cualquier autor de los siglos XVI y XVII del que se disponga de al menos 10 sonetos digitalizados.

Los textos han sido extraídos de la [Biblioteca Virtual Miguel de Cervantes](http://www.cervantesvirtual.com/).

En estos momentos, el corpus consta de más de 5000 sonetos (más de 71000 versos).

##Anotación

La anotación de los patrones métricos se ha realizado de manera semi-automática. Primero se han procesado todos los sonetos con un sistema automático de escansión métrica, que asigna a cada verso su patrón métrico. Después se ha validado a mano una parte del corpus y se han corregido los errores detectados. En estos momentos el corpus se encuentra en fase de validación manual. En cada soneto se indica si los patrones métricos han sido validados a mano o no.

##Componentes

Proyecto realizado en la Universidad de Alicante por Borja Navarro Colorado, María Ribes Lafoz y Noelia Sánchez, con la colaboración de Sara Trigueros.

##Más información

Si quieres más información, consulta la guía de anotación ([PDF](http://www.dlsi.ua.es/~borja/GuiaAnotacionMetrica.pdf)), o las siguientes publicaciones.

##Cómo citar el corpus

Si utiliza este corpus en trabajos académicos, por favor, cite el recurso de manera apropiada:

- Navarro Colorado, Borja (2015) "A computational linguistic approach to Spanish Golden Age Sonnets: metrical and semantic aspects" [Computational Linguistics for Literature](https://sites.google.com/site/clfl2015/) NAACL 2015, Denver (Co), USA [PDF](http://www.aclweb.org/anthology/W/W15/W15-0712.pdf).

- Navarro Colorado, Borja; Ribes Lafoz, María; Trigueros, Sara J.; y Sánchez, Noelia (2015) "Compilación y anotación métrica de un corpus de sonetos del Siglo de Oro" [Humanidades Digitales Hispánicas](http://hdh2015.linhd.es/) UNED, Madrid.

##Licencia
La anotación métrica de este corpus se encuentra bajo licencia de Creative Commons Reconocimiento-NoComercial 4.0 Internacional.




