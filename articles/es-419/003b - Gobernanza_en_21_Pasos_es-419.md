# **Gobernanza en 21 Pasos**

## **Versión para el público general | Release 1.0**

Cada paso es una regla simple. Aplicados juntos, por muchas personas, generan resultados que ningún planificador central podría diseñar de antemano.

**Antes de empezar:** el grupo necesita acordar que va a usar este sistema. Sin ese acuerdo inicial, los pasos son imposición, no gobernanza. Este es el prerequisito cero.

---

## **LOS DERECHOS FUNDAMENTALES**

### **Pasos 1 a 4 | Stallman**

Antes de cualquier proceso, el sistema necesita garantizar cuatro libertades. Sin ellas, el resto es teatro. Inspirados en Richard Stallman (GNU Manifesto, 1985).

---

**Paso 1 — Todos pueden acceder y leer todo lo que se decidió.**

Libertad de ver (acceso). Ninguna decisión es secreta. Cualquier persona del grupo puede ver qué se hizo, quién lo hizo y cuándo.

*Como:* Un libro de actas abierto sobre la mesa de la sala de reuniones, no encerrado con llave en el armario del administrador.

---

**Paso 2 — Todos pueden proponer cambios.**

Libertad de participar. No hace falta ser jefe, experto ni electo. Cualquier persona puede sugerir, cuestionar o pedir una modificación.

*Como:* El micrófono abierto en la asamblea del consorcio: cualquier vecino puede pedir la palabra.

---

**Paso 3 — Todos pueden adaptar lo que existe a su propia realidad.**

Libertad de adaptar. Si un modelo funciona en una ciudad, alguien en otra puede copiarlo y cambiar lo que necesite. Sin pedir permiso.

*Como:* Una receta familiar: heredás el pan de la abuela, pero le ponés anís si preferís.

---

**Paso 4 — Todos pueden distribuir su versión a otros.**

Libertad de compartir. Lo que adaptaste, otros pueden usarlo también. Nadie le pone candado al conocimiento.

*Como:* Quien aprende a hacer pan y le enseña al vecino. El conocimiento no disminuye cuando se pasa adelante.

---

## **LA FORMA DE TRABAJAR**

### **Pasos 5 y 6 | Raymond**

Antes de comenzar el flujo, el grupo decide cómo va a operar. La elección entre dos modelos cambia todo. Inspirados en Eric Raymond (The Cathedral and the Bazaar, 1999).

---

**Paso 5 — Elegí cómo va a trabajar el grupo: en secreto con pocos, o de forma abierta con todos.**

Catedral o bazar. En la catedral, un pequeño grupo diseña todo en secreto y lo entrega terminado. En el bazar, cualquier persona puede contribuir, revisar y mejorar en cualquier momento. La catedral produce cosas hermosas, pero si el arquitecto se equivoca, todos pagan. El bazar es más ruidoso, pero encuentra errores más rápido. **Esta serie elige el bazar.**

*Como:* Una plaza con feriantes libres versus una galería comercial donde el administrador decide quién entra.

---

**Paso 6 — Con muchos ojos, todo problema se vuelve más fácil de encontrar.**

Revisión abierta. Cuando mucha gente puede mirar el mismo documento, los errores aparecen rápido. No porque las personas sean brillantes, sino porque son muchas y miran desde ángulos distintos.

*Como:* Un texto revisado por veinte personas tiene menos errores que el mismo texto revisado por una sola.

---

## **EL FLUJO DE VERSIONAMIENTO**

### **Pasos 7 a 20 | comunidad open source**

El motor del sistema. Cómo nacen las decisiones, son evaluadas, aprobadas, ejecutadas, rastreadas, corregidas o separadas. Inspirados en Git (creado por Linus Torvalds en 2005) y en las prácticas desarrolladas por la comunidad open source a lo largo de las dos décadas siguientes. Torvalds creó el mecanismo. La cultura de gobernanza en torno a él fue construida por muchos.

---

**Paso 7 — Creá la versión oficial del grupo: la fuente única de verdad.**

PRINCIPAL (MAIN). El documento principal donde está todo lo que se decidió y vale ahora. Puede llamarse `main`, `master`, `trunk` o cualquier nombre que el grupo elija: lo que importa es que exista una única versión oficial que todos reconozcan. Cuando hay dudas, la respuesta está aquí.

*Como:* El tablero oficial del consorcio: lo que está ahí es lo que vale, no lo que alguien dijo en la escalera.

---

**Paso 8 — Escribí las reglas en un lugar que todos puedan ver.**

El README. El documento que explica cómo funciona el grupo: cómo proponer, cómo revisar, quién decide cuando hay empate. Antes de jugar, todos conocen las reglas.

*Como:* El reglamento interno en la entrada de la sede, visible para todos.

---

**Paso 9 — Toda sugerencia se convierte en propuesta escrita.**

Incidencia (issue): un pedido registrado. Nada cambia de palabra. Toda idea, queja o pedido de cambio se escribe con fecha y firma. Queda visible para todos. Puede ser respondida, debatida o archivada, pero no desaparece.

*Como:* El buzón de sugerencias donde cada nota tiene nombre, fecha y respuesta pública.

---

**Paso 10 — Toda propuesta obtiene un borrador separado para ser trabajado.**

Rama (branch): una copia de la versión oficial hecha en ese momento exacto. A partir de ahí, trabajás en esa copia sin tocar el original. Podés hacer borradores, probar, equivocarte y rehacer todas las veces que sea necesario.

A veces la versión oficial avanza mientras vos seguís trabajando. Cuando eso pasa, podés actualizar tu borrador con lo que cambió en el original. Si hay partes que entran en conflicto, el grupo decide qué queda. Ese momento de conflicto entre versiones tiene su propio nombre: conflicto de fusión (merge conflict). No es un error: es la señal de que dos personas estaban pensando en el mismo punto al mismo tiempo. Alguien necesita leer los dos lados y decidir.

*Como rama:* Una hoja en blanco para hacer el borrador mientras el documento original sigue intacto sobre la mesa.

*Como conflicto de fusión:* Dos personas reescribieron el mismo párrafo del reglamento al mismo tiempo. El sistema avisa. El grupo se sienta y resuelve qué versión entra, o combina las dos.

**Confirmación (commit)** (segundo gesto dentro del paso 10): una fotografía firmada del estado actual de tu borrador en ese momento. Anotás: "día 15, versión con la regla de votación por mayoría simple, incluyendo los ajustes que sugirió María." Esa fotografía se convierte en un punto fijo en la historia. La confirmación no es la decisión final: esa viene con la fusión (merge). Es el registro de adónde llegaste hasta ahí, congelado para no perderlo. Permite volver a ese punto después (reversión), compararlo con otros momentos, o incorporar partes de él al documento oficial.

*Como confirmación:* Sacarle una foto al borrador en el cuaderno y firmarlo con la fecha. Todos lo vieron y acordaron que esa es la foto del momento. Nadie puede negar después que llegaron hasta ahí.

---

**Paso 11 — Quien terminó la propuesta pide incorporarla a la versión oficial.**

Solicitud de incorporación (pull request): el pedido formal de aprobación. No empujás tu cambio directamente. Pedís que el grupo evalúe.

*Como:* Entregarle una enmienda al secretario para que sea votada, no modificar el acta vos solo.

---

**Paso 12 — Toda decisión exige que alguien la verifique antes de aceptarla.**

Revisión (review): revisión entre pares. Nadie aprueba su propio trabajo. Siempre otro par de ojos. No es desconfianza: es arquitectura. El sistema asume que todos se equivocan.

*Como:* El médico que no se opera a sí mismo. No por incompetencia: por falta de distancia.

---

**Paso 13 — Si se aprueba, la propuesta entra en la versión oficial.**

Fusión (merge): la incorporación. El borrador aprobado se integra al documento principal. Lo que estaba en el cuaderno paralelo pasa a formar parte del documento que todos usan.

*Como:* La enmienda aprobada en la asamblea que pasa a formar parte del estatuto. No lo reemplaza: se integra.

---

**Paso 14 — La decisión aprobada se convierte en acción concreta.**

Publicación (deploy): la ejecución. No basta con decidir: hay que hacer. Definí de antemano quién ejecuta, para cuándo y cómo el grupo verifica que se hizo. Una decisión sin responsable es una intención, no gobernanza.

La mayoría de los sistemas falla aquí. La decisión existe en el papel. La acción no ocurre.

*Como:* Aprobar la pintura y designar a quién contrata, con qué presupuesto, para cuándo. Sin esos tres, la pintura nunca sale del balde.

**Nota sobre el alineamiento 21×21×21:** Publicación (Deploy) es el único de los 22 conceptos del glosario que vive fuera del versionamiento en sí. Describe lo que pasa cuando la decisión sale del sistema y se encuentra con el mundo real. Por eso es un paso operacional pleno, pero no integra la tabla de correlación de la serie (que mapea el isomorfismo entre versionamiento y gobernanza). El concepto que ocupa la posición 21 en la tabla es Conflicto de fusión (Merge Conflict), descrito en el Paso 10. Más detalles en el Apéndice.

---

**Paso 15 — Todo error queda visible para todos.**

Transparencia y rastreabilidad. Todo tiene fecha, autor e historial. Nadie borra rastros. Cualquier persona puede ver quién decidió qué, cuándo y por qué. Esto no es castigo: es memoria institucional.

*Como:* El extracto bancario que no podés borrar. Cada movimiento tiene fecha y descripción.

---

**Paso 16 — Si una decisión específica salió mal, puede deshacerse.**

Reversión (revert): el bisturí. Deshace un cambio puntual sin tocar el resto. Sabés exactamente lo que estás deshaciendo.

*Como:* Cancelar una ley aprobada en marzo sin tocar las demás leyes del mismo año.

*Diferencia con retroceso (rollback):* la reversión es quirúrgica. El retroceso vuelve todo atrás.

---

**Paso 17 — Si varias decisiones recientes salieron mal, todo vuelve a un punto anterior.**

Retroceso (rollback): la máquina del tiempo. Elegís una fecha en el pasado en que las cosas funcionaban bien y restaurás todo a ese estado. No es quirúrgico: es un retroceso completo.

Usá el retroceso cuando haya contaminación en cascada: la decisión incorrecta A llevó a B y C, que llevaron a D y E. Revertirlas una por una sería un caos.

*Como:* Anular todo lo que se aprobó desde enero y volver a como estaban las cosas en diciembre.

---

**Paso 18 — Si algo urgente se rompe y no puede esperar el proceso normal, existe el parche de emergencia.**

Parche urgente (hotfix): la corrección sin fila. Va directamente a la versión oficial porque la urgencia no permite esperar el proceso completo.

**Atención:** La emergencia tiene plazo y rendición de cuentas. Quien activó el parche urgente le explica al grupo después. La decisión de emergencia entra en el historial como cualquier otra. Toda dictadura empieza con una emergencia sin plazo. Definí el plazo antes, no durante la crisis.

*Como:* Arreglar la cañería reventada ahora. La reforma planificada viene después.

---

**Paso 19 — Todo conflicto profundo puede generar una ramificación de la idea original.**

Bifurcación (fork): seguir otro camino. Alguien toma la versión oficial, hace una copia completa y sigue un rumbo diferente. Mismo origen, trayectorias distintas. La bifurcación no es una traición: es una evolución legítima cuando el conflicto es irresoluble dentro del sistema actual.

**Límite:** La bifurcación funciona para reglas, documentos y procesos. Para recursos físicos compartidos (dinero, espacio, equipamiento) la bifurcación no resuelve sola: no podés dividir el patio de la escuela en dos. En esos casos, hace falta un arbitraje con consecuencias reales.

*Como:* Una sucursal que se independiza de la casa matriz. Ambas siguen existiendo. Ninguna necesita destruir a la otra.

---

**Paso 20 — Toda versión estable merece una marca.**

Etiqueta o versión estable (tag o release): el sello de estabilidad. Cuando el grupo llega a un punto en que las cosas funcionan bien, marca esa versión con un nombre y una fecha. Sirve de referencia para el futuro y de punto de retorno si las cosas empeoran después.

*Como:* La edición de un libro: "versión 1.0, aprobada en marzo de 2025". No significa perfección. Significa que, hasta aquí, funciona.

---

## **EL PRINCIPIO DE CIERRE**

### **Paso 21**

---

**Paso 21 — Ninguna versión es final. Incluyendo esta.**

El sistema entero existe para ser mejorado, cuestionado y superado. Si deja de cambiar, murió. Si se convierte en dogma, debe ser abandonado.

**No gobiernan los más sabios: gobiernan los más revisables.** El valor no está en dominar el lenguaje del sistema. Está en aceptar ser corregido.

**Este sistema existe para ser superado.** Si se convierte en verdad absoluta, falló. Toda versión debe ser reemplazada por otra más simple, más clara y más abierta. Esta regla se aplica a sí misma.

---

## **Nota sobre la atribución**

Los pasos 1 a 4 están inspirados en las cuatro libertades del software libre, formuladas por Richard Stallman (GNU Manifesto, 1985). Los pasos 5 y 6 parten de la distinción catedral-bazar de Eric Raymond (The Cathedral and the Bazaar, 1999). Los pasos 7 a 20 describen prácticas que Git hizo posibles, desarrolladas por la comunidad open source a lo largo de dos décadas. Torvalds creó el mecanismo. La cultura de gobernanza en torno a él fue construida por muchos. El paso 21 no le pertenece a nadie. O le pertenece a todos.

**Sobre el alineamiento 21×21×21:** Este protocolo de 21 pasos corresponde, paso a paso, a los 21 conceptos del glosario y a los 21 artículos de la serie. El alineamiento es isomórfico: los tres sistemas tienen la misma estructura. El único ajuste necesario para cerrar el alineamiento fue reconocer que Publicación (Deploy, Paso 14) pertenece a la ejecución, no al versionamiento, y que Conflicto de fusión (Merge Conflict), descrito dentro del Paso 10, completa los 21 conceptos de la tabla como concepto de pleno derecho. Más detalles en el Apéndice de la serie.

## **Prerrequisitos mínimos**

El grupo necesita poder leer y escribir (para que el paso 9 funcione), tener un lugar común donde los registros queden accesibles a todos, y acordar de antemano que va a usar este sistema. Un grupo que no puede cumplir estos prerrequisitos necesita resolverlo antes de empezar.

---

*Gobernanza como Versionamiento | Release 1.0*
