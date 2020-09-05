# bio-informatica-2020-2c
Repo para la materia de Introducción a la Bioinformática de la UNQ

## Trabajo práctico 1. 

### RETO I: ¿Podrías buscar un ejemplo de macromoléculas que almacenen información sobre la ‘identidad’ de un organismo dado?

El ADN es una macromolécula que almacena información sobre la "identidad".
ADN es la sigla con que se conoce el ácido desoxirribonucleico, éste, conjuntamente con el ARN (ácido ribonucleico) son designados con el nombre general de ácidos nucleicos. Se localizan en el núcleo (ADN) y en el citoplasma (ARN) de las células animales y vegetales y representan los componentes fundamentales del sistema genético que dirige el metabolismo y la autoconservación de las células y los organismos.

....
Son biopolímeros cuyos monómeros se denominan nucleótidos; en el ADN están unidos formando macromoléculas lineales, apareadas en dos hebras o cadenas paralelas con desarrollo espacial helicoidal ( doble hélice).

Cada nucleótido está formado por un grupo fosfato unido a un hidrato de carbono (desoxirribosa en el ADN y ribosa en el ARN) y éste, a su vez, a una estructura llamada "base nitrogenada". Mientras el fosfato y el hidrato de carbono son siempre los mismos, las bases pueden ser de 4 tipos; de esta manera , se pueden presentar cuatro tipos de nucleótidos diferenciados según la base que contengan.

**Fosfato** + **Hidrato de carbono**(carbohidrato: biomolecula compuesta por carbono, hidrogeno y oxigeno cuya funcion es proporcionar energa) + **bases nitrogenadas**(Es la proteína) -> **Nucleótidos**

Los nucleótidos se unen entre si a través de enlaces que vinculan a los fosfatos con los hidratos de carbono (desoxirribosa o ribosa).

Los ácidos nucleicos, entonces, se pueden caracterizar por el tipo de secuencia en que se presentan estas bases contenidas en cada nucleótido. Esa secuencia especial es el lenguaje que tienen todas las formas de vida para producir y regular los procesos biológicos y que se conoce como código genético. Dentro de ese lenguaje están expresadas todas las instrucciones necesarias (que, como, cuando y donde) para la biosíntesis de proteínas, compuestos fundamentales en el desarrollo general, crecimiento, forma y rasgos del cuerpo , procesos metabólicos, reproducción,...

Cada "porción" de ADN que codifica la síntesis de una proteína o regula una función especifica se denomina gen.

Una particularidad muy importante del ADN es su capacidad de "autoduplicarse" (reproducirse !!), esto le permite elaborar copias de si mismo y de esta manera transmitir la información genética que contiene.

Las gametas, células sexuales, que a través de su fusión (fecundación) generan otro ser vivo contienen ADN, es decir, contienen toda la información necesaria para que un nuevo ser se origine, se desarrolle y reproduzca.

	
La secuencia de las bases de los nucleótidos en el ADN, muchas veces y en forma natural se altera "por un error de copia" de manera similar a los errores en la escritura originando una "mutación", que puede ser benéfica para la vida o negativa.

 Muchas formas de contaminación física y química tienen la propiedad de provocar mutaciones generalmente negativas, produciendo malformaciones y/o disfunciones que afectan el desarrollo de quien las posee y condicionan severamente la calidad del patrimonio genético de su descendencia, otras son mortales por alterar funciones vitales básicas.

Muchas formas de radiación tales como la ultravioleta y la nuclear y compuestos como el asbesto, las dioxinas, el benceno,... son agentes potencialmente capaces de producir cambios en la secuencia del ADN y generar así, mutaciones.

El ARN (ácido ribonucleico), no posee la estructura espacial "doble hélice", sino que se presenta en moléculas de una sola cadena que adopta diversas formas. Su función principal está vinculada a la síntesis de proteínas codificadas y dirigida por el ADN.
....................................................................................................................................
Definición de Covalente: 
-Unión es un término que deriva del latín, concretamente de “unus”, que puede traducirse como “uno”.
-Covalente, por otro lado, también procede del citado latín. En su caso, es fruto de la suma de tres componentes del mismo: el prefijo “con-”, que es equivalente a “junto”; el verbo “valere”, que puede traducirse como “valer”; y el sufijo “-nte”, que se utiliza para indicar al agente.

Un enlace covalente entre dos átomos se produce cuando estos átomos se unen, para alcanzar el "octeto estable", y comparten electrones del último nivel1​ (excepto el hidrógeno que alcanza la estabilidad cuando tiene 2 electrones). La diferencia de electronegatividad entre los átomos no es lo suficientemente grande como para que se produzca una unión de tipo iónica. Para que un enlace covalente se genere es necesario que la diferencia de electronegatividad entre átomos sea menor a 1,7.

De esta forma, los dos átomos comparten uno o más pares electrónicos en un nuevo tipo de orbital, denominado orbital molecular. Los enlaces covalentes se producen entre átomos de un mismo elemento no metal, entre distintos no metales y entre un no metal y el hidrógeno.
....................................................................................................................................

Estructura primaria: La estructura tridimensional de una proteína normal en su entorno fisiológico normal está determinada por la totalidad de las interacciones interatómicas y, por lo tanto, por la secuencia de aminoácidos la composición de aminoácidos que la conforman.

### RETO II: Proponé una forma de expresar la información contenida en la estructura primaria de las proteínas usando tipos de datos de los lenguajes de programación que conocés.

La estructura primaria de una proteína es la llamada cadena de aminoácidos, que se conectan con uno a la izquierda y otro a la derecha. 
Esto se podria representar con una tupla, con una posición con un puntero a la cadena de la izquierda, y la otra para la derecha.
....................................................................................................................................

### RETO III: ¿ En qué tipo de datos podrías expresar la información de la estructura terciaria proteica?

Si no entendí mal, lo mismo. Dado que se conectan en las puntas entre las hlice alfa y hojas plegadas. Me falta entender como representar las interacciones y repulsiones entre esas estructuras secundarias, que provocan esas "formas" en el espacio.

-------------------------------------------------------------------------------------------------------------------------------------

### RETO IV: Rosalind Franklin es una científica muy relevante, que tuvo menos reconocimiento del merecido. ¿Cuáles fueron sus contribuciones en este campo?

Propuso la estructura del ADN, basada en imágenes de la molécula a través de la técnica de disfracción de rayos x.

¿Qué nos cuenta su historia acerca del mundo de la ciencia?
Machismo es la palabra que lo resume. Pero también esta frase me parece interesante "Así es de enigmático a veces el lenguaje científico, además de ser un ejemplo impagable de cómo subestimar el trabajo de otro" a pesar de no saberlo facticamente, es lo que se desprende.

-------------------------------------------------------------------------------------------------------------------------------------
### RETO V: Proponé en pseudocódigo un programa que prediga la estructura secundaria que adoptará cada residuo de la secuencia proteica dada, especificandola como H (si es una hélice), B (si es una hoja beta plegada) y L (si es un bucle o loop).

PREGUNTAS DISPARADORAS: ¿Qué inputs tendría tu programa? ¿De qué modo se te
ocurre configurar el output?

Teniendo en cuenta la tabla de preferencias de los aminoácidos con cada estructura secundaria,..
