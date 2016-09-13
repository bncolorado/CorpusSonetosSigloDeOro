#Corpus de sonetos castellanos del Siglo de Oro.

##Introducción
Corpus formado por sonetos escritos en castellano entre los siglos XVI y XVII.

Cada soneto ha sido anotado en XML siguiendo el estándar [TEI](http://www.tei-c.org/index.xml). Además de encabezado e información estructural, cada soneto tiene representado formalmente los __patrones métricos__ de cada verso.

El patrón está formado por la secuencia de sílabas átonas (representadas con el signo "-") y tónicas (símbolo "+"). La métrica de cada verso queda así representada:

		<l n="1" met="---+---+-+-">Cuando me paro a contemplar mi estado,</l>

##Poetas
Con el objetivo de crear un corpus lo más representativo posible, se ha incluido cualquier autor de los siglos XVI y XVII del que se disponga de al menos 10 sonetos digitalizados.

Los textos han sido extraídos de la [Biblioteca Virtual Miguel de Cervantes](http://www.cervantesvirtual.com/).

En estos momentos, el corpus consta de más de 5000 sonetos (más de 71000 versos).

##Anotación
La anotación de los patrones métricos se ha realizado de manera semi-automática. Primero se han procesado todos los sonetos con un sistema automático de escansión métrica, que asigna a cada verso su patrón métrico. Después se ha validado a mano una parte del corpus y se han corregido los errores detectados. En estos momentos el corpus se encuentra en fase de validación manual. En cada soneto se indica si los patrones métricos han sido validados a mano o no.

##Componentes
Proyecto realizado en la [Universidad de Alicante](http://www.ua.es) por Borja Navarro Colorado, María Ribes Lafoz y Noelia Sánchez, con la colaboración de Sara Trigueros.


##Cómo citar el corpus
Si utiliza este corpus en trabajos académicos, por favor, cite el recurso de manera apropiada:

- Navarro-Colorado, Borja; Ribes-Lafoz, María and Sánchez, Noelia (2016) "Metrical Annotation of a Large Corpus of Spanish Sonnets: Representation, Scansion and Evaluation" [Proceedings of the Tenth International Conference on Language Resources and Evaluation (LREC 2016)](http://www.lrec-conf.org/proceedings/lrec2016/pdf/453_Paper.pdf) Portorož, Slovenia.

- Navarro-Colorado, Borja (2015) "A computational linguistic approach to Spanish Golden Age Sonnets: metrical and semantic aspects" [Computational Linguistics for Literature NAACL 2015](https://sites.google.com/site/clfl2015/), Denver (Co), USA ([PDF](https://aclweb.org/anthology/W/W15/W15-0712.pdf)).

##Más información
Para más información, consulte la guía de anotación ([PDF](http://www.dlsi.ua.es/~borja/GuiaAnotacionMetrica.pdf)) o las siguientes publicaciones.

- Navarro Colorado, Borja (2015) "A computational linguistic approach to Spanish Golden Age Sonnets: metrical and semantic aspects" [Computational Linguistics for Literature](https://sites.google.com/site/clfl2015/) NAACL 2015, Denver (Co), USA [PDF](http://www.aclweb.org/anthology/W/W15/W15-0712.pdf).

- Navarro-Colorado, Borja; Ribes Lafoz, María; Trigueros, Sara J.; y Sánchez, Noelia (2015) "Compilación y anotación métrica de un corpus de sonetos del Siglo de Oro" [Humanidades Digitales Hispánicas](http://hdh2015.linhd.es/) UNED, Madrid.

##Licencia
La anotación métrica de este corpus se encuentra bajo licencia de Creative Commons Reconocimiento-NoComercial 4.0 Internacional.

Sobre los sonetos, "this digital object is protected by copyright and/or related rights. This digital object is accessible without charge, but its use is subject to the licensing conditions set by the organization giving access to it. Further information available at http://www.cervantesvirtual.com/marco-legal/ ".





