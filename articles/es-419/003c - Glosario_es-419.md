# **Glosario**

## **Gobernanza como Versionamiento | Release 1.0**

Cada término está definido en lenguaje simple, con una analogía concreta y la referencia al paso correspondiente en los 21 Pasos. Si encontrás uno de estos términos en cualquier artículo de la serie y no recordás lo que significa, consultá aquí.

Este glosario tiene 22 entradas. Veintiuna integran la tabla de correlación de la serie (21 conceptos × 21 pasos × 21 artículos). Una, Publicación (Deploy), queda fuera de la tabla por una razón explicada en su propia entrada: pertenece a la ejecución, no al versionamiento.

---

### **1. Acceso (libertad 0)**

**Paso 1**

El derecho a ver. Cualquier persona puede leer todo lo que se decidió, sin necesidad de pedirle permiso a nadie.

*Como:* El libro de actas sobre la mesa de la sala de reuniones, no encerrado con llave en el armario del administrador.

---

### **2. Participación (libertad 1)**

**Paso 2**

El derecho a proponer. Cualquier persona puede sugerir cambios, sin necesitar ser elegida o designada.

*Como:* El micrófono abierto en la asamblea del consorcio. Cualquier vecino puede pedir la palabra.

---

### **3. Adaptación (libertad 2)**

**Paso 3**

El derecho a ajustar. Podés tomar lo que existe y modificarlo para tu realidad, sin pedir permiso.

*Como:* La receta familiar que heredás y condimentás a tu manera.

---

### **4. Distribución (libertad 3)**

**Paso 4**

El derecho a pasarlo adelante. Lo que adaptaste, otros pueden usarlo también. Nadie le pone candado al conocimiento.

*Como:* Quien aprendió a hacer pan y le enseña al vecino. El conocimiento no disminuye cuando se pasa adelante.

---

### **5. Catedral**

**Paso 5**

Forma de trabajar en la que un pequeño grupo diseña todo en secreto y lo entrega terminado, como un arquitecto que dibuja el edificio entero antes de mostrárselo a alguien. Nadie de afuera ve, sugiere ni corrige nada hasta que el producto está "terminado".

El problema: si el arquitecto se equivocó en algo importante, todos ya están comprometidos con la obra hecha. Los errores costosos aparecen tarde.

*Como:* Un consorcio en el que el administrador contrata la reforma, negocia el precio y firma el contrato, y los vecinos solo se enteran cuando llega la factura.

---

### **6. Bazar**

**Paso 6**

Forma de trabajar en la que cualquier persona puede contribuir, revisar y mejorar en cualquier momento, como una feria libre donde cada vendedor arma su puesto, cualquier cliente puede opinar y toda la plaza ve lo que está pasando.

Es más ruidoso. Pero los errores aparecen más rápido, porque muchos ojos miran desde ángulos distintos. No es caos: es una plaza con reglas claras sobre quién puede proponer y cómo se evalúan las propuestas.

Esta serie elige el bazar.

*Como:* Una asamblea abierta en la que cualquier vecino puede proponer, cualquiera puede comentar y la decisión final queda registrada para que todos la vean.

---

### **7. PRINCIPAL (rama principal / MAIN)**

**Paso 7**

La versión oficial. El documento principal donde está todo lo que se decidió y vale ahora. Cuando hay dudas sobre qué es lo oficial, la respuesta está aquí.

**Nota sobre los nombres:** En proyectos de software, esta versión puede llamarse `main`, `master`, `trunk` o cualquier otro nombre que el grupo elija. `main` es la convención más aceptada hoy, después de un proceso gradual de migración que empezó alrededor de 2020. El nombre no importa: lo que importa es que exista una única versión oficial, con un nombre claro, que todos reconozcan como la fuente de verdad.

*Como:* El tablero oficial del consorcio: lo que está ahí es lo que vale, no lo que alguien dijo en la escalera.

---

### **8. README (léeme)**

**Paso 8**

El manual de la casa. El documento que explica cómo funciona el grupo: cómo proponer, cómo revisar, quién decide cuando hay empate, cuáles son los límites de lo que se puede cambiar.

*Como:* El reglamento interno pegado en la entrada de la sede, visible para todos, antes de que comience cualquier reunión.

---

### **9. Incidencia (Issue)**

**Paso 9**

Una propuesta escrita. Toda idea, queja o pedido de cambio se convierte en un texto con fecha y firma. Nada cambia de palabra. La incidencia queda visible para todos y puede ser respondida, debatida o archivada, pero no desaparece.

*Como:* El buzón de sugerencias donde cada nota tiene nombre, fecha y respuesta pública.

---

### **10. Rama (Branch)**

**Paso 10**

Una copia de la versión oficial (PRINCIPAL) hecha en ese momento exacto. A partir de ahí, trabajás en esa copia sin tocar el original: podés hacer borradores, probar, equivocarte y rehacer todas las veces que sea necesario. El original sigue intacto.

A veces la versión oficial avanza mientras vos seguís trabajando en tu borrador. Cuando eso pasa, podés actualizar tu copia con lo que cambió en el original: es como pedirle a alguien que te cuente lo que te perdiste mientras estabas afuera, e incorporar eso a tu trabajo. Si hay partes que entran en conflicto, el grupo decide qué queda.

*Como:* Una hoja en blanco para hacer el borrador mientras el documento original sigue intacto sobre la mesa.

---

### **11. Confirmación (Commit)**

**Paso 10 — segundo gesto**

Una fotografía firmada del estado actual de tu borrador en ese momento. Anotás: "día 15, versión con la regla de votación por mayoría simple, incluyendo los ajustes que sugirió María." Esa fotografía se convierte en un punto fijo en la historia.

La confirmación no es la decisión final: esa viene con la fusión (merge). Es el registro de adónde llegaste hasta ahí, congelado para no perderlo. Permite volver a ese punto después (reversión), compararlo con otros momentos, o incorporar partes de él al documento oficial (fusión).

En la práctica: la reunión terminó, anotaste en el cuaderno del equipo la versión actual de la propuesta con esos cambios, todos lo vieron y firmaron confirmando que esa es la fotografía del momento. Nadie puede negar después que llegaron hasta ahí.

*Como:* Sacarle una foto al borrador en el cuaderno y firmarlo con la fecha. No es el libro publicado. Es el registro de dónde estaba el trabajo en ese instante.

**Nota sobre el Paso 10:** Rama (Branch) y Confirmación (Commit) son dos gestos dentro del mismo paso operacional. Rama es abrir el borrador. Confirmación es sacar la fotografía firmada del punto al que llegaste. En la tabla de correlación de la serie (21×21×21), los dos gestos comparten el mismo paso y el mismo artículo de referencia. No hay conflicto: el paso describe el flujo completo del trabajo en borrador.

---

### **12. Solicitud de incorporación (Pull request)**

**Paso 11**

El pedido formal de aprobación. No empujás tu cambio directamente al documento oficial: pedís que el grupo evalúe lo que hiciste en tu borrador antes de que nada sea incorporado.

*Como:* Entregarle una enmienda al secretario para que sea votada, no modificar el acta vos solo.

---

### **13. Revisión (Review)**

**Paso 12**

La revisión entre pares. Nadie aprueba su propio trabajo. Siempre otro par de ojos. No es desconfianza: es arquitectura. El sistema asume que todos se equivocan, y que quien está afuera ve lo que quien está adentro ya no ve.

*Como:* El médico que no se opera a sí mismo. No por incompetencia: por falta de distancia.

---

### **14. Fusión (Merge)**

**Paso 13**

La incorporación. El borrador aprobado entra en la versión oficial. El proceso de aprobación terminó. Lo que estaba en el cuaderno paralelo pasa a formar parte del documento que todos usan.

*Como:* La enmienda aprobada en la asamblea que pasa a formar parte del estatuto. No lo reemplaza: se integra.

---

### **15. Transparencia / Registro de auditoría (Audit trail)**

**Paso 15**

El rastro permanente. Todo tiene fecha, autor e historial. Nadie borra nada. Cualquier persona puede ver quién decidió qué, cuándo y por qué.

*Como:* El extracto bancario que no podés borrar. Cada movimiento tiene fecha y descripción. No para castigar: para saber.

---

### **16. Reversión (Revert)**

**Paso 16**

El bisturí. Deshace una decisión específica sin tocar las demás. Sabés exactamente lo que estás deshaciendo.

*Como:* Cancelar una ley aprobada en marzo sin tocar las demás leyes del mismo año. El bisturí opera donde apuntás.

Diferencia con retroceso (rollback): la reversión es quirúrgica. El retroceso vuelve todo atrás.

---

### **17. Retroceso (Rollback)**

**Paso 17**

La máquina del tiempo. Restaura todo a como estaba en una fecha específica. Se usa cuando varias decisiones en cascada salieron mal y deshacerlas una por una sería un caos.

*Como:* Anular todo lo que se aprobó desde enero y volver a como estaban las cosas en diciembre.

Diferencia con reversión (revert): la reversión deshace una cosa. El retroceso vuelve todo a un punto anterior.

---

### **18. Parche urgente (Hotfix)**

**Paso 18**

La corrección de emergencia. Va directamente a la versión oficial sin pasar por el proceso normal, porque la urgencia no permite esperar.

**Atención:** La emergencia tiene un plazo y una rendición de cuentas. Quien activó el parche urgente le explica al grupo después. La decisión de emergencia entra en el historial como cualquier otra. Toda dictadura empieza con una emergencia sin plazo. Definí el plazo antes, no durante la crisis.

*Como:* Arreglar la cañería reventada ahora. La reforma planificada viene después.

---

### **19. Bifurcación (Fork)**

**Paso 19**

La ramificación. Alguien toma la versión oficial, hace una copia completa y sigue un camino diferente a partir de ahí. Mismo origen, rumbos distintos. No es una traición: es el reconocimiento de que el conflicto es irresoluble dentro del sistema actual.

**Límite importante:** La bifurcación funciona para reglas, documentos y procesos. Para recursos físicos compartilhados (dinero, espacio, equipamiento) la bifurcación no resuelve sola: no podés dividir el patio de la escuela en dos. En esos casos, hace falta un arbitraje con consecuencias reales.

*Como:* Una sucursal que se independiza de la casa matriz. Ambas siguen existiendo. Ninguna necesita destruir a la otra.

---

### **20. Etiqueta / Versión estable (Tag / Release)**

**Paso 20**

El sello de estabilidad. Cuando el grupo llega a un punto en que las cosas funcionan bien, marca esa versión con un nombre y una fecha. Sirve como referencia futura y como punto de retorno si las cosas empeoran después.

*Como:* La edición de un libro: "versión 1.0, aprobada en marzo de 2025". No significa perfección. Significa: hasta aquí, funciona.

---

### **21. Conflicto de fusión (Merge Conflict)**

**Paso 10 — situación específica**

El momento en que dos borradores distintos hicieron cambios en el mismo tramo del documento oficial y el sistema no puede decidir solo qué versión queda. No es un error: es una señal de que dos personas estaban pensando en el mismo problema al mismo tiempo. Alguien necesita leer los dos lados y decidir.

*Como:* Dos personas reescribieron el mismo párrafo del reglamento al mismo tiempo. El sistema avisa: "hay un conflicto aquí". El grupo se sienta y resuelve qué versión entra, o combina las dos.

**Nota:** El conflicto de fusión aparece durante el trabajo en la Rama (Paso 10) y se resuelve antes de la Solicitud de incorporación (Paso 11). Es una situación, no un paso separado. Integra la tabla 21×21×21 como el concepto número 21.

---

### **Publicación / Despliegue (Deploy — fuera de la tabla 21×21×21)**

**Paso 14**

La ejecución. La decisión aprobada se convierte en acción concreta. Necesita un nombre (quién lo hace), un plazo (para cuándo) y un criterio de verificación (cómo confirma el grupo que se hizo). Una decisión sin responsable es una intención, no gobernanza.

*Como:* Aprobar la pintura del pasillo y designar a quién contrata, con qué presupuesto, para cuándo. Sin esos tres, la pintura nunca sale del balde.

**Por qué Publicación queda fuera de la tabla:** Publicación describe lo que pasa cuando la decisión sale del sistema de versionamiento y se encuentra con el mundo real: quién ejecuta, con qué plazo, cómo se verifica. Es un concepto operacional necesario en la práctica, pero no pertenece al versionamiento en sí: pertenece a la ejecución. Todos los demás 21 conceptos describen operaciones dentro del sistema de registro. Publicación describe lo que viene después. Por eso integra el protocolo de los 21 Pasos (que es operacional) pero no integra la tabla de correlación (que mapea el isomorfismo entre el sistema de versionamiento y el sistema de gobernanza). La tabla cierra en 21×21×21. Publicación permanece en el glosario y en el protocolo como concepto de pleno derecho.

---

## **Nota final**

Este glosario tiene 22 entradas. Veintiuna forman la tabla de correlación con los 21 pasos y los 21 artículos de la serie. Una, Publicación (Deploy), sostiene el protocolo operacional sin integrar la tabla. Los tres sistemas (conceptos, pasos, artículos) son isomórficos: no solamente parecidos, sino estructuralmente equivalentes. Esa equivalencia está documentada en el Apéndice de la serie.

---

*Gobernanza como Versionamiento | Release 1.0*
