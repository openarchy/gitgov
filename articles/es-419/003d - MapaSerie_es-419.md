# **Mapa de la Serie**

## **Gobernanza como Versionamiento | Release 1.0**

### **29 autores · 335 años · 21 pasos**

Cada artículo funciona de forma independiente. Pero cada uno crea un hilo con el anterior y el siguiente.

---

## **INTRODUCCIÓN (3 artículos)**

| # | Año | Autor | Obra | Problema que resuelve | Pieza que agrega | Pasos |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| I1 | 1985 | Richard Stallman | GNU Manifesto | Los sistemas cerrados bloquean la colaboración y la corrección. | Las cuatro libertades: ver, participar, adaptar, compartir. | 1–4 |
| I2 | 1999 | Eric S. Raymond | The Cathedral and the Bazaar | Cómo organizar a mucha gente sin crear caos. | Dos modelos: catedral (pocos, secreto) vs. bazar (todos, abierto). El bazar encuentra errores más rápido. | 5–6 |
| I3 | 2001/05 | Linus Torvalds | Just for Fun / Git | Cómo coordinar a gran escala sin un jefe central. | El mecanismo: confirmación (commit), rama (branch), fusión (merge), bifurcación (fork), reversión (revert), etiqueta (tag). Prueba de que funciona. | 7–20 |

---

## **PARTE I: Fundamentos del orden descentralizado (artículos 1–7)**

| # | Año | Autor | Obra | Problema que resuelve | Pieza que agrega | Pasos |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| 1 | 1689 | John Locke | Dos Tratados sobre el Gobierno | ¿De dónde viene la autoridad legítima? | El consentimiento. Ninguna autoridad es legítima sin el acuerdo de los gobernados. La reversión original. | 11–12 |
| 2 | 1945 | Karl Popper | La sociedad abierta y sus enemigos | ¿Y si el sistema basado en el consentimiento está equivocado? | Calidad = velocidad de corrección del error. La falsabilidad como mecanismo. | 16–17 |
| 3 | 1945 | Friedrich Hayek | El uso del conocimiento en la sociedad | ¿Quién tiene la información para corregir? | Conocimiento disperso. Ningún planificador central lo reúne todo. Cada colaborador contribuye con lo que sabe. | 9 |
| 4 | 1949 | Ludwig von Mises | La acción humana | ¿Cómo surge el orden sin un organizador? | Orden espontáneo. Millones actuando libremente generan coordinación. Linux, Wikipedia, mercados. | 7–8 |
| 5 | 1948/2011 | Claude Shannon + James Gleick | La información | ¿Qué es exactamente la información? | La información es lo que reduce la incertidumbre. La confirmación (commit) es información pura: qué cambió, cuándo, quién, por qué. | 9–10 |
| 6 | 1976 | Richard Dawkins | El gen egoísta | ¿Por qué sobreviven los sistemas malos? | Memes. Las ideas compiten por replicarse. "Siempre fue así" es el meme más fuerte. La fusión (merge) selecciona lo que vive. | 12–13 |
| 7 | 2001 | Steven Johnson | Emergencia | ¿Cómo surge algo mayor que la suma de las partes? | Emergencia. Reglas simples + interacción local = comportamiento colectivo complejo y no planificado. | 21 |

---

## **PARTE II: Límites, ruidos y correcciones (artículos 8–14)**

| # | Año | Autor | Obra | Problema que resuelve | Pieza que agrega | Pasos |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| 8 | 1922 | Max Weber | Economía y sociedad | El destino estándar de toda organización. | La jaula de hierro. Las reglas que existían para servir a las personas pasan a servirse a sí mismas. | 21 |
| 9 | 1922 | Walter Lippmann | La opinión pública | ¿Las personas deciden basándose en la realidad? | Pseudoambiente. Las decisiones se toman sobre imágenes simplificadas, no sobre hechos directos. | 5–6 |
| 10 | 1979 | Daniel Kahneman & Amos Tversky | Heurísticas y sesgos | ¿El cerebro procesa la información racionalmente? | Sesgo sistemático. No es un error: es el sistema operativo. La revisión entre pares (review) lo compensa parcialmente. | 12 |
| 11 | 1989 | Richard Saul Wurman | Ansiedad informacional | ¿Más información ayuda? | LATCH. Cinco formas de organizar cualquier dato. El volumen sin estructura genera ansiedad, no claridad. | 8–9 |
| 12 | 1990 | Elinor Ostrom | El gobierno de los bienes comunes | ¿Cómo cuidan los grupos los recursos compartidos? | 8 principios de los comunes. Límites claros, reglas locales, participación, monitoreo, sanciones graduales. | 8–19 |
| 13 | 2008 | Donella Meadows | Pensando en sistemas | ¿Qué gobierna los sistemas? | Bucles de retroalimentación. La retroalimentación retrasada o bloqueada destruye el sistema. | 9–17 |
| 14 | 1927 | John Dewey | El público y sus problemas | ¿Cómo aprenden los ciudadanos a participar de verdad? | La democracia es una habilidad, no un talento. El repositorio como escuela: se aprende participando. La apertura sin capacitación reproduce la jerarquía. | 9, 19 |

---

## **PARTE III: Coordinación a escala (artículos 15–21)**

| # | Año | Autor | Obra | Problema que resuelve | Pieza que agrega | Pasos |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| 15 | 2004 | James Surowiecki | La sabiduría de las multitudes | ¿Las multitudes deciden mejor que los expertos? | Sabiduría de las multitudes: diversidad + independencia + descentralización + mecanismo de agregación. | 12 |
| 16 | 2006 | Yochai Benkler | La riqueza de las redes | ¿Cómo producen los pares sin empresa y sin jefe? | Producción entre pares basada en los comunes. Eficiente para ciertos bienes. Base económica del versionamiento. | 11–13 |
| 17 | 2006 | Lawrence Lessig | El código y otras leyes del ciberespacio 2.0 | ¿El código es neutral? | El código es ley. Quien escribe el código define lo que es posible. Bifurcación (fork) fácil = disidencia por diseño. | 19 |
| 18 | 1996 | Manuel Castells | La era de la información: La sociedad red | ¿Quién tiene poder en una red? | El poder está en quien conecta, no en quien manda. Las redes también excluyen. Código abierto ≠ acceso abierto. | 1–4 |
| 19 | 2010 | Kathryn Schulz | Estar equivocado | ¿Equivocarse es una falla moral? | El error es la condición humana estándar. Calidad = velocidad de corrección. "Errar es confirmar (commit)" es diseño, no excusa. | 15–17 |
| 20 | 2012 | Nassim Nicholas Taleb | Antifrágil | ¿Los sistemas deben resistir el estrés? | Antifragilidad. Sistemas que se fortalecen con el error. El conflicto genera bifurcación (fork), la bifurcación mejora el original. | 16–19 |
| 21 | 2010 | Thomas Sowell | Intelectuales y sociedad | ¿Quién debe gobernar? | Visión trágica vs. visión de los ungidos. No gobiernan los más sabios: gobiernan los más revisables. | 21 |

---

## **CONCLUSIÓN: Portales a la Fase 2 (5 artículos)**

| # | Año | Autor | Obra | Problema que resuelve | Pieza que agrega | Pasos |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| C1 | 2010 | Curtis Yarvin | Unqualified Reservations | ¿Qué pasa cuando el lenguaje de la descentralización se usa para concentrar poder? | Bifurcación maliciosa (malicious fork). Desviación 1: autoritarismo disfrazado de eficiencia. Ejemplo de lo que revertir. | 19 (negativo) |
| C2 | 2012 | Nick Land | The Dark Enlightenment | ¿Puede la tecnología volver irrelevante a la democracia? | Retroceso autoritario (authoritarian rollback). Desviación 2: tecnocracia sin consentimiento. Ejemplo de lo que no construir. | 17 (negativo) |
| C3 | 2012 | Nate Silver | La señal y el ruido | ¿Cómo separar señal de ruido sin ser capturado por los extremos? | Pensamiento bayesiano. Actualizar creencias con evidencia. Leer el sistema, no la narrativa. | 15–16 |
| C4 | 2014 | Peter Thiel | De cero a uno | ¿Qué pasa cuando alguien entiende el sistema mejor que todos? | Riesgo de captura. Desviación 3: monopolio silencioso. La apertura necesita ser protegida por diseño. | 8 + 19 |
| C5 | 2024 | Ethan Mollick | Co-Intelligence | ¿Qué pasa cuando agentes de IA participan en el sistema? | Portal a la Serie 2. Co-inteligencia: colaboración humano-IA. Los 21 pasos necesitan evolucionar. | 21 (portal) |

---

## **POSFACIO: Portales adicionales para la Serie 2**

| # | Año | Autor | Obra / Texto | Problema que abre | Posición en la serie |
| ----- | ----- | ----- | ----- | ----- | ----- |
| P1 | 2012 + 2024 | Nate Silver | *La señal y el ruido* (2012) + *On the Edge* (2024) | Cómo registrar, junto con cada decisión, las condiciones que justificarían revertirla. Sin eso, el historial de versiones existe, pero el disparador para usarlo no. | Portal 1 |
| P2 | 2024 | Ethan Mollick | *Co-Intelligence* (2024) | La IA como co-inteligencia: eleva el piso de participación, pero también acelera la participación fraudulenta. ¿Los 21 pasos funcionan con agentes artificiales? | Portal 2 |
| P3 | 2024 + 2026 | Dario Amodei | *Machines of Loving Grace* (oct. 2024) + *The Adolescence of Technology* (ene. 2026) | La ventana de tiempo para incorporar salvaguardas antes de que la concentración de IA vuelva imposible cualquier corrección estructural. Es estrecha. No en décadas. | Portal 3 |

> **Silver:** *La señal y el ruido* mostró cómo separar señal de ruido en predicciones. *On the Edge* (2024) extendió esto a entornos de incertidumbre extrema: traders, jugadores profesionales, analistas de riesgo. Su contribución a gobernanza como versionamiento: las decisiones honestas incluyen los criterios que llevarían a su propio deshacimiento. Una ley que no define cuándo debe ser revisada nunca será revisada.

> **Amodei:** *Machines of Loving Grace* (octubre de 2024) describe el escenario si todo sale bien: una IA que comprime cincuenta años de progreso científico en una década. *The Adolescence of Technology* (enero de 2026) es el reverso de la misma moneda: la misma IA, sin frenos adecuados, permite el control totalitario mediante propaganda personalizada y una concentración de poder sin precedentes. La metáfora central: la humanidad como un adolescente que ganó poder adulto antes de tener la madurez para usarlo. Amodei no excluye a su propia empresa de la lista de actores que necesitan ser monitoreados. Estos dos textos juntos son el argumento más urgente para que la Serie 2 no espere.

---

## **Nota sobre los números**

La serie principal tiene **25 piezas** (prefacio + introducción + 21 artículos + conclusión + posfacio). Los artículos del núcleo son **21**. Los autores suman **29** en la serie principal.

El recorte temporal declarado es **de 335 años**: de Locke (1689) a Mollick (2024). El posfacio extiende la conversación hasta 2026 con Amodei, pero no altera el recorte oficial de la serie.

**Portales en el posfacio:** Silver con dos libros (2012 y 2024), Mollick con *Co-Intelligence* (2024), Amodei con dos textos (*Machines of Loving Grace*, oct. 2024, y *The Adolescence of Technology*, ene. 2026). Seis nombres adicionales mencionados como terreno para series futuras: Freire, Boaventura, Mbembe (Serie 3), Landemore, Tufekci, Scott (Serie 3), Tang y Fei-Fei Li (puente Serie 2-3).

---

*Gobernanza como Versionamiento | Release 1.0*
