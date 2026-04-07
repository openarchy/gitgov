# **Gobernanza como Versionamiento**

## **Artículo Cero: Git Init**

### **Democracia, Poder y la Memoria que No Miente**

*Cómo las democracias mueren por dentro, qué tiene que ver eso con la tecnología y por qué la gobernanza versionada cambia las reglas del juego*

*Este es el Artículo Cero. No pertenece al conteo oficial de los veintiuno. Existe antes de la serie como contexto político: mostrar el problema concreto desde el punto de vista de alguien que pasó tres décadas viendo la misma falla de arquitectura en sistemas de datos antes de reconocerla en sistemas de poder. La serie Gobernanza como Versionamiento comienza oficialmente en el Artículo Uno, sobre John Locke (1689), el primero de veintiún pensadores que — cada uno en su tiempo — describió, sin nombrarlo, la lógica que Git luego formalizaría. Leer el Artículo Cero no es un requisito. Cada texto de la serie funciona solo. Pero quien lo haya leído comienza el camino sabiendo por qué el camino existe.*

---

## **La Democracia es Arquitectura**

¿Alguna vez participaste en una reunión donde la decisión ya estaba tomada antes de que la reunión comenzara?

¿O votaste en una asamblea donde, semanas después, nadie recordaba con exactitud qué se había decidido, ni por qué?

Eso no es una falla de memoria. Es una falla de arquitectura.

El problema no es quién gana las elecciones. Es lo que el sistema permite que los ganadores hagan después de ganar.

La democracia se convirtió en una palabra repetida hasta perder precisión. Aparece en discursos, campañas, decisiones institucionales. Se invoca para justificar actos opuestos. Todos la defienden. Pocos la examinan como sistema.

Pero la democracia no es un argumento. Es arquitectura.

Y toda arquitectura produce exactamente los resultados que su diseño permite.

Si las reglas pueden estirarse sin costo, lo serán. Si las decisiones no dejan rastro comparable, la memoria se disuelve. Si el precio del abuso es menor que el precio de la fiscalización, el abuso se vuelve racional. No por maldad de nadie. Por lógica estructural.

Las democracias rara vez desaparecen de un golpe. Siguen existiendo en el papel mientras su práctica cambia silenciosamente. Pequeñas alteraciones se acumulan. Las interpretaciones se expanden. Las excepciones se vuelven precedentes. Lo que era límite se vuelve elasticidad.

El poder que no deja rastro no necesita justificarse. Y el poder que no necesita justificarse tiende a expandirse hasta encontrar resistencia, o hasta no encontrar ninguna.

La erosión depende de la invisibilidad. Y la invisibilidad, en un mundo con almacenamiento prácticamente ilimitado y rastreabilidad técnica sin precedentes, es una elección de arquitectura, no una inevitabilidad.

La democracia representativa fue diseñada para un mundo diferente: información escasa, comunicación lenta, registros físicos. Funcionó con notable ingenio para su tiempo. Pero el entorno cambió. La infraestructura política, poco.

En cualquier organización compleja — empresa, ejército, universidad o Estado — siempre existe la posibilidad de captura interna. La diferencia entre sistemas frágiles y sistemas robustos no está en la virtud de las personas. Está en la arquitectura que limita, registra y hace rastreable cada decisión relevante.

Las arquitecturas frágiles dependen de la buena fe. Las arquitecturas robustas dependen de mecanismos.

En la ingeniería de software, ese problema se resolvió con un principio simple: cada cambio genera un historial permanente. Cada alteración queda registrada, es comparable y, cuando es necesario, reversible. No elimina los conflictos. No elimina los errores. Elimina el olvido conveniente.

Los abusos invisibles son baratos. Los abusos permanentemente registrados son caros.

La pregunta no es si es posible aplicar esta lógica a la gobernanza. Es por qué todavía no lo hemos hecho.

No se trata de reemplazar la política con código. No de automatizar la democracia. Sino de aplicar al proceso decisorio colectivo un principio básico de ingeniería: memoria auditable.

Si las democracias son sistemas, pueden analizarse como sistemas. Si pueden analizarse, pueden rediseñarse.

Lo que sigue no es un manifiesto ideológico. Es una propuesta de infraestructura. Y la infraestructura determina el destino.

---

## **Quién escribe esto y por qué debería importar**

Me llamo Gustavo Jorge Alessandri. Soy apasionado por la tecnología, un autodidacta multidisciplinario y, sobre todo, pragmático. Pasé cerca de treinta años construyendo sistemas, proyectos y pipelines de datos para empresas de todos los tamaños: nacionales brasileñas como Telemar (hoy OI), Intelig, ATL (hoy Claro), Pan-Americana Indústrias Químicas; startups multinacionales como Katrium Indústrias Químicas, Bright Insight, Plus Power y SailPlan; y gigantes como Shell, TAM, BairesDev, Pinterest, Shutterstock, CapGemini y Merck. Fui gerente de proyectos, gerente de sistemas, CTO y CIO, trabajando con ingeniería de sistemas, arquitectura de back-end, implementación de ERPs, infraestructura de telecomunicaciones, en los sectores de energía, salud, telecom, redes sociales y química.

No soy politólogo. No soy filósofo. No tengo título de ingeniería. Soy alguien que aprendió en la práctica, fue a buscar lo que necesitaba saber, cruzó fronteras entre disciplinas sin pedir permiso, y acumuló con el tiempo una extraña colección de perspectivas que rara vez aparecen en el mismo lugar. Quizás fue exactamente eso lo que me permitió ver el problema con una mirada diferente.

Cuando pasas años estructurando bases de datos, aprendes algo que creo que no aparece en ningún libro de teoría política: la forma en que organizas la información determina lo que las personas pueden hacer con ella. Un sistema bien diseñado permite que personas comunes hagan cosas extraordinarias. Un sistema mal diseñado hace que incluso gente muy competente fracase. No es cuestión de virtud. Es cuestión de arquitectura.

Empecé a notar esto mirando flujos de datos sin rastreabilidad, integración de información donde nadie sabía exactamente qué había cambiado, cuándo o por quién. Me di cuenta de que estaba describiendo exactamente cómo funciona hoy la mayoría de las organizaciones corporativas, políticas y sociales del mundo. Decisiones tomadas sin registro claro. Errores imposibles de localizar. Responsabilidad diluida hasta desaparecer.

No estamos hablando de tecnología. Estamos hablando de un modelo mental: transparencia real, colaboración abierta, autonomía con responsabilidad, registro permanente, capacidad de comparar versiones y detectar desvíos. Eso es rutina en el desarrollo de software moderno. En la política, todavía es excepción.

Por eso escribo esta serie. No para dar una respuesta definitiva. Para traducir, del lenguaje técnico al lenguaje humano, lo que 335 años de pensamiento ya descubrieron sobre cómo los sistemas que funcionan son distintos de los sistemas que apenas sobreviven.

---

## **Lo que esta serie recorre**

La serie Gobernanza como Versionamiento tiene veinticuatro textos. Parte de John Locke en 1689 y llega a Dario Amodei en 2026, pasando por Karl Popper, Friedrich Hayek, Claude Shannon, Elinor Ostrom, Nassim Taleb y otros veintitrés pensadores. Filósofos, economistas, biólogos, matemáticos, especialistas en sistemas. Cada texto es independiente, pero cada uno le pasa un hilo al siguiente.

El arco de la serie está detallado en el prefacio y en la introducción. Lo que importa registrar aquí es el punto de llegada: el posfacio llega hasta Dario Amodei, presidente de Anthropic, quien en 2026 publicó un argumento perturbador. La ventana para incorporar salvaguardas antes de que la concentración de poder haga imposible cualquier corrección estructural se está cerrando. No en décadas. Ahora.

Este Artículo Cero no pertenece al conteo oficial. Existe antes de la serie como contexto político: mostrar el problema concreto desde el punto de vista de alguien que pasó tres décadas viendo la misma falla de arquitectura en sistemas de datos antes de reconocerla en sistemas de poder.

---

## **Lo que ve un autodidacta de sistemas**

Cualquier ingeniero que haya trabajado con sistemas heredados conoce el concepto. Es aquel que sigue funcionando, pero nadie entiende completamente. Nadie quiere tocarlo porque cualquier cambio puede derribar todo. Las reglas existen, pero la justificación original se perdió. El sistema sobrevive por inercia, acumulando parches que crean dependencias, que crean zonas prohibidas, que crean más reglas que nadie cuestiona.

La democracia representativa es, desde esa mirada, un sistema heredado de primera magnitud.

No es una crítica moral. Es un diagnóstico técnico. El diseño original fue una solución ingeniosa a un problema concreto: ¿cómo coordinar a millones de personas dispersas en un mundo sin telecomunicaciones, sin transporte rápido, sin registros digitales?

La respuesta llegó en 1789. No solo como evento, sino como hito arquitectónico. La Revolución Francesa no fue solo la caída de un rey. Fue el primer intento moderno de reemplazar el poder hereditario por arquitectura racional: constitución escrita, representación formal, separación de poderes. Fue ingeniería política aplicada al problema del siglo XVIII.

Y fue brillante para su tiempo. El problema es que en ese tiempo usaba papel, tinta y meses de espera para circular una decisión.

En TI llamamos a lo que pasa después de décadas sin actualización deuda técnica: decisiones que resolvieron el problema de ayer, pero bloquean el de mañana. La complejidad crece. La legibilidad cae. Los errores se vuelven rutina aceptada. Los incentivos del sistema empiezan a divergir de los objetivos para los que fue creado. No por maldad. Por inercia estructural. En la democracia, llamamos a ese mismo fenómeno crisis institucional.

---

## **Cuando la logística de 1789 se volvió dogma en 2026**

El representante electo nació como solución logística pura. Veinte millones de personas no podían viajar semanas para votar una propuesta de ley. Entonces cada región delegaba ese poder a alguien que hiciera el viaje. El representante era, en la práctica, un mensajero con poder notarial: cargaba las opiniones de su región, viajaba al centro de decisión, descargaba y volvía.

Hoy, cualquier persona con un celular puede informarse, opinar y fiscalizar en tiempo real. La limitación física que justificaba la delegación total desapareció. Pero el sistema que generó permanece, ahora justificado no por la logística sino por argumentos filosóficos construidos retrospectivamente para defender una solución que nació pragmática y se volvió dogma.

Esta inversión tiene un nombre en ingeniería de software: *cargo cult*. Mantienes la forma de un proceso sin entender ya la función original que cumplía. El ritual continúa. El propósito se fue.

Lo que la Revolución Francesa promete sigue valiendo: limitar el poder, garantizar que tenga que justificarse, crear mecanismos de alternancia. La promesa de 1789 sigue siendo legítima. Lo que no acompañó a la promesa fue la infraestructura de 1789.

---

## **Cuando la complejidad es el producto, no el problema**

En cualquier sistema de datos bien diseñado, la complejidad innecesaria es un defecto. En sistemas de poder mal diseñados, la complejidad innecesaria es con frecuencia una ventaja para quienes están adentro.

La legislación incomprensible no es resultado de negligencia. Es resultado de incentivos. Quien domina el lenguaje de un sistema controla el acceso a él. Quien controla el acceso acumula poder de intermediación. Quien acumula poder de intermediación tiene interés activo en mantener el lenguaje opaco.

Los datos confirman el resultado. Según la OCDE, en 2025 la confianza en el gobierno en América Latina y el Caribe estaba alrededor del treinta y cinco al treinta y ocho por ciento.⁴ No es cinismo cultural. Es una evaluación racional de un sistema que perdió legibilidad y con ella perdió legitimidad.

---

## **Actualizar sin reinventar**

Los sistemas heredados pueden modernizarse sin ser destruidos. Los ingenieros hacen esto todo el tiempo: migración gradual, interfaces de compatibilidad, sustitución módulo por módulo. No es necesario apagar todo y empezar desde cero.

Hay ejemplos funcionando ahora. En Montreal, entre 2024 y 2025, más de 880 ideas propuestas y 28.000 votos decidieron directamente 45 millones de dólares en presupuesto participativo. En Estonia, alrededor del 46 por ciento de los votos en las elecciones locales de 2025 fueron digitales, dentro de un ecosistema de servicios públicos completamente en línea. En Brasil, el presupuesto participativo de Porto Alegre movilizó a más de 18.000 personas en asambleas en 2025. Ninguno de estos casos requirió revolución constitucional. Comenzó pequeño. Probó. Midió. Ajustó.

La pregunta no es si es posible actualizar. Es por qué todavía no lo hemos hecho a escala.

---

## **El diagnóstico: cómo las democracias mueren por dentro**

Imagina una caja fuerte. Adentro están las reglas que protegen tu democracia. Crees que solo una bomba puede abrirla por la fuerza. Pero Steven Levitsky, politólogo de la Universidad de Harvard, descubrió algo perturbador: la mayoría de las democracias modernas no son destruidas por bombas. Son destruidas por personas que tienen la llave.

En *Cómo mueren las democracias* (2018),¹ escrito con Daniel Ziblatt, Levitsky demostró que el mayor peligro no es el general con tanques en la calle. Es el político electo con una sonrisa en la cara. Hitler fue electo. Chávez fue electo. Erdoğan, Putin, Orbán, Fujimori: todos llegaron al poder por el voto. Después, usando leyes, decretos y procesos perfectamente legales, fueron desmantelando los mecanismos que limitaban su poder. No fue un golpe. Fue una erosión. Lenta. Casi invisible.

Lo que sostiene a una democracia no son solo leyes escritas. Son dos comportamientos invisibles que las personas simplemente asumen que existen: tolerancia mutua — el reconocimiento de que el adversario político es legítimo y no un enemigo a eliminar — y contención institucional, la elección de no usar todo el poder disponible solo porque se puede. Cuando esos comportamientos desaparecen, el sistema colapsa formalmente intacto.

En *La tiranía de la minoría* (2023),² Levitsky va más lejos: muchas democracias modernas son dominadas por minorías organizadas que aprendieron a usar las propias reglas del sistema para neutralizar a la mayoría. El juego sigue existiendo. Las reglas fueron reescritas por dentro.

El problema central que Levitsky identifica — y no resuelve completamente — es este: las democracias dependen de normas invisibles y de la buena fe de los actores. Pero la cultura cambia. La tradición se erosiona. Las coaliciones se disuelven. Cuando eso pasa, no hay mecanismo técnico de protección. Solo el comportamiento humano está entre el sistema y el colapso.

---

## **El comando que inicia todo**

Antes de cualquier teoría, una imagen concreta.

Imagina que tú y un grupo de amigos deciden construir algo juntos: una casa comunitaria, una huerta colectiva, o incluso las reglas para un barrio sin administrador. Al principio todo es un caos: papeles sueltos, ideas perdidas, nadie sabe quién cambió qué. Es exactamente ahí donde entra el `git init`.

`git init` es un comando de computadora — una instrucción que escribes en una carpeta vacía (o con tus archivos) y que transforma esa carpeta en un lugar con memoria. Git (programa gratuito de control de versiones, creado por Linus Torvalds en 2005) crea una carpetita oculta llamada `.git`, que funciona como un diario secreto: guarda todo lo que pasa desde ese momento en adelante. Cada cambio se convierte en un registro llamado confirmación (commit, en inglés; significa "comprometerse con una decisión"). Puedes volver en el tiempo si cometes un error. Puedes crear caminos paralelos llamados ramas (branches), como bifurcaciones en una carretera, sin arruinar el camino principal. Es el nacimiento del control colectivo: sin un jefe central, pero con reglas que todos siguen.

Pero hay algo más profundo en esa imagen.

Imagina ahora un barco en alta mar. Antes del `git init`, no hay timón, ni mapa, ni bitácora. Después de él, tres capas entran en funcionamiento.

**Gobernanza** se vuelve el timonel que define ruta y reglas: el propósito mayor, el "¿adónde vamos?". La palabra viene del griego antiguo *kybernan*, que significa exactamente "pilotar o dirigir un barco". Platón usaba la idea para hablar de guiar ciudades enteras. Pasó al latín como *gubernare*, luego al español como gobernanza: el proceso de dirigir con reglas claras, en el nivel más alto, estratégico.

**Gestión** es lo inmediato que ajusta velas y turnos en el día a día: planifica, coordina, transforma el destino definido en planes reales. Deriva del latín *gerere*, que significa "cargar, hacer, ejecutar". La gestión es el "cómo" y el "cuándo" hacer bien, en el nivel táctico, de mediano plazo.

**Administración** cuida la cubierta limpia, las cuentas pagadas, el registro diario: ejecuta y anota en el corto plazo, con rutina y detalle. Viene del latín *ministrare*, que significa "servir". El prefijo *ad* ("hacia") indica que es delegada: alguien ejecutando en nombre de quien decide. Es el nivel operacional.

En grupos humanos descentralizados — aquellos que funcionan sin tecnología compleja — el `git init` equivale a un acuerdo simple y solemne: "Hoy comenzamos a registrar acuerdos, cambios y razones. Nadie borra el pasado sin consenso." Es el cero absoluto de la metodología de gobernanza versionada: la confirmación inicial (commit inicial) que habilita bifurcaciones (forks) pacíficas — grupos que se separan llevando el historial completo —, retrocesos (rollbacks) colectivos — decisiones que formalmente vuelven atrás — y auditoría eterna: cualquier persona puede verificar qué se decidió y quién lo decidió.

---

## **La propuesta: gobernanza como memoria auditable**

Aquí es donde la pregunta cambia de naturaleza.

Si las democracias dependen de normas invisibles, ¿qué pasa cuando esas normas se vuelven visibles? Registradas, versionadas, auditables por cualquier persona, en cualquier momento.

En el desarrollo de software, ese problema fue resuelto hace décadas. El principio es simple: cada cambio genera un registro permanente. Puedes comparar versiones, identificar autores, revertir decisiones. El sistema no depende de la buena memoria de nadie. Depende del historial.

La gobernanza versionada aplica esa lógica al proceso decisorio colectivo. No reemplaza la política con código. No automatiza la democracia. Cambia el costo estructural del abuso.

Violar reglas de forma invisible es barato. Violar reglas dejando rastro permanente en un sistema auditable por cualquier persona es mucho más caro. No porque la ley se volvió más dura. Porque la opacidad — de la que depende el abuso — desapareció.

La erosión gradual depende de la invisibilidad. Con versionamiento, puedes comparar cualquier versión de una regla con cualquier versión anterior. Los patrones de concentración de poder que serían invisibles sin ayuda se vuelven detectables antes de consolidarse.

---

## **La crítica honesta, sin suavizar**

El registro no impide las decisiones malas. El parlamento alemán aprobó legalmente el Acta de Habilitación en 1933, que le dio a Hitler poderes dictatoriales. Todo registrado. Todo legal. El resultado fue el fin de la democracia. Visibilidad no equivale a resistencia.

Los ataques reales ocurren a través de manipulación psicológica, propaganda, coerción económica y fatiga cognitiva. Si las personas aprueban decisiones malas, el sistema versionado registrará con perfección su propia destrucción. Un atacante puede generar un volumen masivo de cambios triviales para hacer la auditoría humana imposible. Se recrea la opacidad dentro de la transparencia.

La gobernanza versionada resuelve el problema de la ignorancia — no completamente el problema del poder. Transforma el abuso invisible en abuso visible. Eso es una mejora masiva y genuina. No es invulnerabilidad.

---

## **La arquitectura que hace posible esto**

La premisa honesta: el sistema será atacado, capturado y presionado. El objetivo no es impedir todos los ataques. Es garantizar que el sistema sobreviva, detecte problemas, aísle daños y se regenere.

Ocho capas forman esta arquitectura: un ancla de reglas que no cambian por mayoría simple; un registro permanente de decisiones con autor, fecha y motivo; líneas paralelas donde grupos prueban propuestas sin afectar al sistema principal; bifurcación (fork) — la capacidad de cualquier grupo de copiar el historial completo y continuar de forma independiente —; aprobación en múltiples dimensiones independientes; período de espera antes de que los cambios críticos entren en vigor; reputación basada en historial verificable, no en narrativa; monitoreo automatizado que detecta patrones sospechosos.

Nassim Taleb acuñó el término *antifrágil* para los sistemas que no solo resisten los choques sino que mejoran con ellos.³ La gobernanza versionada bien construida tiene esa propiedad. Los ataques generan bifurcaciones mejores. Los intentos de captura generan alertas. Los errores quedan registrados y se vuelven aprendizaje incorporado.

---

## **Lo que cambia de verdad**

La analogía más precisa no es tecnológica. Es contable. La transición de la contabilidad mental a la contabilidad formal auditable no eliminó la deshonestidad del comercio. Cambió el costo de ser deshonesto. Antes, confiabas en que el comerciante era honesto. Después, tenías el libro mayor para verificar. La confianza no desapareció, pero dejó de ser el único mecanismo de protección.

La gobernanza versionada hace con los sistemas de poder lo que la contabilidad hizo con el comercio.

Las democracias no mueren porque sean derrocadas. Mueren porque son abandonadas. Y un sistema que lo registra todo hace que el abandono sea mucho más difícil de fingir que nunca ocurrió.

---

## **Por qué este texto existe antes de la serie**

El prefacio cuenta el origen del proyecto y presenta Git como herramienta. La introducción explica las tres historias de Stallman, Torvalds y Raymond, y por qué eso importa para cualquier grupo humano que necesite tomar decisiones colectivas. Este texto hace otra cosa: muestra el problema político concreto desde el punto de vista de un autodidacta que pasó treinta años viendo la misma falla de arquitectura en sistemas técnicos antes de reconocerla en sistemas de poder.

Leer este Artículo Cero no es un requisito. Cada texto de la serie funciona solo. Pero quien lo haya leído comienza el camino sabiendo por qué el camino existe.

La serie comienza en 1689 — cien años antes de la Revolución Francesa — con John Locke y lo que llamó el derecho a resistir el poder ilegítimo. En aquella época, decir eso en público costaba la cabeza. Hoy todavía cuesta algo. Pero ahora tenemos herramientas que él no tenía.

---

## **Referencias**

CHACON, S.; STRAUB, B. *Pro Git*. 2. ed. New York: Apress, 2014. Disponible en: <https://git-scm.com/book/es/v2>. Acceso: 24 feb. 2026.

INSTITUTO BRASILEIRO DE GOVERNANÇA CORPORATIVA. *Código das melhores práticas de governança corporativa*. 5. ed. São Paulo: IBGC, 2015. (Sin edición en español disponible.)

LEVITSKY, Steven; ZIBLATT, Daniel. *Cómo mueren las democracias*. Barcelona: Ariel, 2018.

LEVITSKY, Steven; ZIBLATT, Daniel. *La tiranía de la minoría*. Barcelona: Ariel, 2023.

MICHAELIS. *Dicionário Brasileiro da Língua Portuguesa*. Governança; Gestão; Administração. Disponible en: <https://michaelis.uol.com.br>. Acceso: 24 feb. 2026. (Sin edición en español disponible.)

OCDE. *Government at a Glance Latin America and the Caribbean*. París: OECD Publishing, 2025.

ORIGEM DA PALAVRA. Governança. Disponible en: <https://origemdapalavra.com.br/palavras/governanca>. Acceso: 24 feb. 2026. (Sin edición en español disponible.)

TALEB, Nassim Nicholas. *Antifrágil: las cosas que se benefician del desorden*. Barcelona: Paidós, 2013.

TRIBUNAL DE CONTAS DA UNIÃO. *Referencial básico de governança organizacional*. 3. ed. Brasília: TCU, 2020. (Sin edición en español disponible.)

WIKIPÉDIA. Governança. Disponible en: <https://pt.wikipedia.org/wiki/Governança>. Acceso: 24 feb. 2026. (Sin edición en español disponible.)

---

*\* `git init` es el comando que crea un repositorio desde cero, el primer acto antes de que exista cualquier versión. Aquí: el texto que inicializa el repositorio conceptual de la serie.*
