# Guión de la presentación

Por aquí mis notas de lo que espero decir durante esta sesión.

## ¿Qué es el código sostenible?

> Ir preguntando a quien entre y los que ya están presentes para conocer opiniones
> según como respondan podré hacer o no más preguntas luego
> Una vez hemos entrado en calor, paso a presentarme con una frase tipo:

Efectivamente el código sostenible es todo eso que han dicho y algunas cosas más que veremos durante la charla de hoy
pero, antes dos puntos importantes

## Me presento

Lo primero presentarme, mi nombre en las redes es Cristian Suárez Dev.
Soy desarrollador de software desde hace casi 4 años.
Actualmente trabajo en Lean Mind con un grupo de personas maravillosas.
Pueden encontrarme por todas estas redes sociales, para que les sea más cómodo he dejado el QR a mi web en el apartado de redes sociales.
Últimamente estoy centrándome en big data y gestión de personas, hago directos sobre ello, subo historias contándoles mi vida y de vez en cuando escribo sobre lo que voy aprendiendo.

## ¿De dónde viene el término código sostenible?

Como segundo punto antes de empezar tenemos que dejar claro de dónde viene el término código sostenible y, para ahorrarles tiempo, les diré que su origen viene del inglés. Concretamente de, "_maintainable code_", un palabro que no tiene traducción al español al no existir la palabra mantenible.

## ¿Qué es el código sostenible?

Al inicio nombramos algunas de estas palabras sobre que es el código sostenible. Concretamente el código sotenible es:

- Intuitivo, no nos da sopresas.
- No muy complejo.
- Está cubierto por tests automáticos, a día de hoy mantener software sin test es bastante complicado.
- Fácil de mantener, tanto en el tiempo como a la hora de corregir errores que surgirán.
- Escribimos código válido para hoy, no intentamos adivinar el futuro. Salvo que sea obvio y sepamos a ciencia cierta que está previsto X cambio. Y aún así depende de como sea la situación.

## Ejemplos de código

Ahora pasaremos a ver unos ejemplos de código para entrar mejor en materia de lo que estámos hablando.

> en este punto decidir si ver todos los ejemplos o no según como esté de tiempo

## Porque es importante la sostenibilidad?

Lo primero y mas importante porque se espera que lo sea. No creo que a nadie nos contraten para que hagamos una chapuza que tenga que tirar dentro de unos meses.

Al final estamos dando servicio a otros negocios y profesionales que esperan una mejora en su productividad gracias a nuestras soluciones.

Y aunque no se nombre mucho, trabajamos en uno de los sectores mejor pagados a dia de hoy. Un dia calculen lo que sale un proyecto donde trabajen. Pagarian ese dinero si fuese de ustedes?

## El arte de escribir codigo para humanos

Escribir codigo es relativamente facil, escribirlo para que otras personas lo comprendan no tanto. Y si ya queremos que sean capaces de modificarlo sin que nada se rompa, uff se complica mas aun.

Lo llamo arte porque asi lo siento, no les parece maravilloso que con una pocas lineas de codigo podemos hacer mejor la vida de las personas. Hemos normalizado muchas cosas que antes eran impensables como poder comunicarnos con cualquier parte del mundo en tiempo real.

Incluso un codigo simple, testado y expresivo puede cambiar la vida de quien lo lee, de como programa.

Es por esto que quiero recalcar que es importante escribir para personas y no para maquinas.

## La degeneracion del codigo

Es bastante comun que el codigo no envejezca bien con el tiempo, tiende a dejenerase porque no supimos construirlo para ser flexible.

Para conseguir que incluso mejore con el tiempo es importante el punto que acabamos de ver, codificar para personas.

La importancia viene porque, esta claro que el codigo va a volverse mas complejo con el paso del tiempo. Cada nueva funcionalidad que creamos an'ade mas complejidad, a este tipo lo llamaremos complejidad fundamental. De esta no nos podemos librar y evoluciona de manera lineal a lo largo del proyecto.

Pero luego, existe otro tipo, __la complejidad accidental__. Este tipo de complejidad es la que vamos introduciendo sin darnos cuenta, nombres que no tenemos claros, arquitecturas desproporcionadas, inconsistencias, etc. Esta es nas dificil de ver pero, una vez la conocemos la podemos tener mas en cuenta, pensaremos mejor la proxima vez si ese *if* nuevo que vamos a poner en la lista de 10 que ya tenemos realmente ayuda o entorpece aun mas.

## Se puede tener un software sostenible

Si, es posible y tener una buena cobertura de test es una de las bases. Sin test no hay gloria

Lo que no podemos esperar es que un proyecto que lleva an'os descontrolandose, pase a estar como nuevo en unos pocos meses. Requiere tanto o mas trabajo y paciencia para poder llegar a ser sostenible.

Otro punto importante para tener un software sostenible es usar metodologias agiles para el desarrollo. Es imposible planear un proyecto entero y que no cambie cada par de meses.

## Diseñar código para el presente

Otra caracteristica que es fundamental tener en cuenta es diseñar código para el presente. Hoy en dia vivimos en la era de la adaptacion, los objetivos van cambiando segun evoluciona el producto y los clientes. Ademas de, las correcciones que tenemos que hacer.

Existe una idea en el mundillo bastante arraigada y extendida, que es la de escribir codigo generico y abstracto esperando que va a ser usado o lo van a necesitar en varios sitios. Anticipandonos a escenarios futuros que no sabremos si llegaran. Esto es perfecto para que sea insostenible nuestro software. Ya que programamos para que no requiera cambios nuestro codigo. Es mejor hacer codigo especifico, consiso y facil de modificar, ya tendremos tiempo de generalizar cuando este claro que queremos generalizar.

## El mito de la reutilizacion de codigo

Al igual que en el punto anterior hacer codigo reutilizable es adelantarnos a saber si realmente va a ser reutilizado o no, llegado el momento en el que tenemos claro que se puede reutilizar podemos hacer un refactor y unificar logica si tiene sentido que lo hagamos.

## Las reglas del codigo sostenible segun kent beck

Despues de todo lo que les he contado y lo que me he dejado atras, escribir codigo sostenible es mas dificil de lo que uno podria pensar. Y por mucho que nos esmeremos cuando miremos codigo de tiempo atras veamos que podria mejorarse, es normal, en este momento tenemos mas conocimiento y sabemos mas informacion para poder hacerlo mejor.

Existen un minimo comun denominador del codigo sostenible? probablemente no pero kent beck dice que el codigo debe:

> leer cosas de las diapos

las dos ultimas reglas se suelen mal interpretar, la duplicidad hace referencia a logica del negocio no lineas de codigo como tal. Si un mismo codigo esta en dos partes pero soluciona dos problemas diferentes no tiene porque unificarse. Significa no duplicar artefactos y objetos de dominio.

## Las reglas segun Carlos ble

Ahora les voy a mostrar una revision de estas mismas reglas

> improvisa wey

## Las personas primero

Por ultimo antes de cerrar esta sesion me gustaria recordarles por encima de todo que lo mas importante son las personas al final del dia. La calidad del codigo es clave pero les sorprenderia saber la candidad de veces que he estado en equipos que nos llaman porque dicen tener un problema con el codigo y despues de una temporada vemos que realmente son problemas de falta de comunicacion, relaciones tensas, falta de reconocimiento.

Una llamada cara a cara es mas efectiva y rentrable que un comentario escrito frio en una revision de codigo.

Un grupo de personas que trabaja en equipo llegara mas lejos que una sola.

Un lema que me gusta es "firme con el asunto, pero flexible con la persona"

## Bibliografia

Nombrar los libros que hemos usado de referencia y que la presentación la hemos hecho basada
en el libro que esta por salir Código sostenible.

Enlazar con la landing codigosostenible.com

## Gracias

...

## Hasta la proxima

...
