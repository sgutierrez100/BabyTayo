# Baby Tayo · Investigación (Etapa 1)

**Fecha de corte:** 10 de noviembre de 2026 · **Mercado:** EE. UU. (USD) · **Idiomas:** español + inglés · **Plataforma:** WordPress + Elementor Pro

Este documento reúne cuatro investigaciones hechas con búsqueda web actual, cada dato con su fuente:

- **Parte A.** Referencias visuales.
- **Parte B.** Stack técnico.
- **Parte C.** Marca, aspectos legales y seguridad.
- **Parte D.** Crecimiento.

Al final de este resumen están las **tres direcciones de diseño** propuestas. Su tablero visual está en [`prototipo/direcciones.html`](prototipo/direcciones.html).

> Nada de esto es asesoría legal ni fiscal. Los puntos de marca, impuestos y seguridad de producto deben confirmarse con un abogado de marcas y un CPA.

## Supuestos (lo que no quedó definido)

| Tema | Supuesto |
|---|---|
| Presupuesto de plugins | "No sé". Se asume un stack austero de unos **$115–250 USD/año** además de Elementor Pro y el hosting. Todo lo que cueste dinero se marca como opcional o para más adelante. |
| Plan de Elementor Pro | No se sabe cuál. Si es **Essential**, conviene pasar a **Advanced Solo** (unos $84/año), porque Essential no incluye WooCommerce Builder, Popups ni Custom CSS. |
| Hosting | No se sabe cuál. La parte B trae la lista para evaluarlo; si no cumple, se recomienda LiteSpeed compartido para la fase 1. |
| Logo | No existe. La dirección elegida define el logotipo. |
| Idioma principal | Español primero, inglés como segunda versión completa (no traducción automática visible). |

## Resumen ejecutivo: lo que cambia decisiones

### 1. ⚠️ El nombre "Baby Tayo" tiene un riesgo comercial alto (parte C)

- **En la USPTO:** no hay ninguna solicitud ni registro de "BABY TAYO". ICONIX, dueña de *Tayo the Little Bus*, perdió en 2023 sus registros amplios de TAYO. Hoy solo conserva "TAYO THE LITTLE BUS" en la clase 21.
- **Pero ICONIX usa activamente "Baby Tayo" en EE. UU.:** distribuye *Baby Tayo Songs* en Prime Video, un programa para bebés y toddlers. Además tiene canales de YouTube con millones de suscriptores en inglés y en español, y vende juguetes en Walmart. Ese uso puede darle derechos de marca sin registro (*common law*) justo en las clases que Baby Tayo necesita: 9 (descargables), 16 (impresos), 28 (juguetes) y 41 (educación).
- **Las cuentas @babytayo** ya están ocupadas en YouTube, TikTok y Pinterest. Variantes como @hellobabytayo y @babytayocrafts parecen libres.
- **Recomendación:** antes de invertir en logo, imprenta o kits, pedir a un abogado de marcas una búsqueda de disponibilidad (*clearance search*) con opinión escrita, y tener preparado un nombre alternativo. El sistema de diseño se construirá de forma que sobreviva a un cambio de nombre: la historia de Thiago y el lenguaje visual no dependen de la palabra "Tayo".

### 2. Hay un hueco claro en español (parte D)

- En español dominan portales generalistas de España.
- No apareció ningún sitio especializado en toddlers, con biblioteca filtrable, pensado para familias hispanas de EE. UU.
- Las marcas infantiles revisadas no son bilingües ES/EN.
- **Lo bilingüe es el diferenciador principal**, además del diseño.

### 3. Pinterest está creciendo justo en este nicho (parte D)

- El informe de crianza 2026 de Pinterest reporta *sensory play* +1070 %, *art & craft* +330 % y *screen-free* +200 %.
- Los Rich Pins siguen existiendo; los Idea Pins se eliminaron en 2025.
- Formato 2:3 (1000×1500), con 3–5 diseños nuevos por URL.
- Google dejó de mostrar resultados enriquecidos de FAQ (mayo de 2026) y HowTo (2023). Siguen funcionando Product, Review, Article y migas de pan.

### 4. Ninguna marca del nicho lleva la manualidad a la interfaz (parte A)

- Lovevery, KiwiCo, Hape y Busy Toddler tienen interfaces neutras: el color lo ponen las fotos de producto.
- Errores repetidos: tres iconos de "beneficios", rejillas de tarjetas iguales, pasteles y Poppins/Montserrat.
- **La oportunidad de Baby Tayo es que la propia interfaz sea material:** papel, cinta, crayón.

### 5. El stack recomendado (parte B)

- **Base:** Hello Elementor + Elementor Pro, WooCommerce (es la única opción que cubre PDFs, kits físicos y suscripciones en el mismo sitio).
- **Pagos:** Stripe + PayPal.
- **Email:** MailerLite.
- **Bilingüe:** TranslatePress (o WPML).
- **Plugins gratis:** Rank Math, LiteSpeed Cache, Converter for Media, Wordfence, UpdraftPlus y Complianz.
- **Marca de agua en los PDFs** con el email del comprador: PDF Ink Lite (gratis).
- **Precios:** por la comisión fija de $0.30, conviene evitar PDFs de menos de $8 sueltos y empujar paquetes.

### 6. Seguridad y privacidad (parte C)

- **Avisos de asfixia:** el sitio y los PDFs deben llevar el texto "CHOKING HAZARD" de 16 CFR 1500.19 (en inglés y español), más supervisión adulta y materiales no tóxicos.
- **Kits con piezas pequeñas:** solo se pueden vender para mayores de 3 años.
- **Fase 2 (kits):** exigirá CPSIA, ASTM F963 y certificado CPC. Las pruebas cuestan unos $400–1.800 por SKU sencillo.
- **Thiago:** mostrar solo sus manos y sus creaciones, sin cara, sin nombre completo ni metadatos de ubicación.
- **COPPA:** una estética muy infantil puede hacer que la FTC trate el sitio como dirigido a niños. Los textos deben dirigirse claramente a madres y padres.

---

## Direcciones de diseño propuestas

Las tres pasan la prueba "¿se vería igual en el sitio de otra marca?" por la misma razón: **cada una nace de un material o de una historia que solo Baby Tayo tiene** (la mesa de la cocina, la palabra mal dicha, la altura de Thiago). Ninguna usa degradados, blobs, glassmorphism, emojis, 3D de stock, Inter/Poppins/Montserrat ni la fila de tres iconos.

Las tres paletas se revisaron con la fórmula de contraste WCAG 2.1. La regla común: los colores claros (amarillo, mandarina, rosa, kraft) **nunca llevan texto encima en blanco ni se usan como color de texto**. Se usan como superficie con texto oscuro encima (todas las combinaciones dan 5:1 o más).

### Dirección A · "Recortado por Tayo"

**Concepto.** El sitio es la mesa de manualidades de la cocina: cada sección es un pedazo de cartulina cortado con tijeras de niño y pegado con cinta. No se simula: los recortes, las tiras de cinta y los crayones se escanean de verdad (como Memberful con Maren Schabhüser, parte A §2).

**Por qué es propio:**
- Se navega por los verbos de la manualidad: **Recorta · Pega · Pinta · Juega**.
- La edad se elige con **pestañas de carpeta**.
- El logotipo son las letras T-A-Y-O recortadas en cuatro cartulinas.

**Paleta · caja de cartulinas.**

| Color | HEX | Uso |
|---|---|---|
| Papel | `#FBF8F2` | Fondo |
| Grafito | `#2A2622` | Texto (14,2:1) |
| Rojo Tayo | `#E5432D` | Superficie; para texto, `#C0321E` (5,3:1) |
| Caléndula | `#F6B21A` | Solo superficie |
| Cobalto | `#2349C8` | Texto y enlaces (6,9:1) |
| Césped | `#2E9A4F` | Superficie; para texto, `#1E7A3B` (5,1:1) |
| Mandarina | `#F27A1A` | Solo superficie |
| Chicle | `#F27BA8` | Solo superficie |
| Kraft | `#D9B98A` | Solo superficie |

**Tipografía.**
- **Bricolage Grotesque** para titulares, con eje de ancho estrecho.
- **Shantell Sans** para notas a mano, con ejes de rebote e informalidad.
- **Figtree** para el texto.

Las tres tienen español completo, verificado con fontTools (parte A §3.3).

**Formas e ilustración.** Bordes cortados a tijera (polígonos irregulares, nunca rectángulos perfectos), piezas giradas ±1–4° y cinta adhesiva.

**Fotografía.** Cenital sobre la mesa con luz de ventana, las manos de Thiago y las creaciones reales.

**Elementos firma.**
- Letras del logo recortadas en cartulina.
- Tiras de cinta escaneadas.
- Pestañas de carpeta para la edad.
- El boleto de "descarga gratis" con muescas.

**Microinteracciones:**

| Interacción | Cómo se hace en Elementor |
|---|---|
| La pieza se levanta con sombra al pasar el cursor | CSS (transform) |
| Subrayado de crayón que se dibuja | SVG con stroke-dashoffset |
| Pestaña que sube al elegirla | CSS |
| Sticker que se despega en el CTA principal | CSS clip-path; solo 1–3 por página |

**Riesgo.** El "scrapbook" genérico se va a saturar en 2026–27. Funciona solo si los materiales son reales y propios.

### Dirección B · "Diccionario Tayo"

**Concepto.** La marca nace de una palabra mal dicha, así que el sitio es un **diccionario ilustrado del idioma de los toddlers**, en español e inglés. Tipografía editorial grande, como de libro, con los círculos y subrayados de crayón de Thiago encima y notas al margen escritas a mano.

**Por qué es propio:**
- Las secciones llevan palabras toddler: "¡Otra vez!" (lo más pedido), "Yo solito" (actividades independientes), "Aba" (juegos con agua).
- La entrada de diccionario de *Ta·yo* cuenta la historia en la primera pantalla.
- Es bilingüe por naturaleza: los toddlers de familias hispanas en EE. UU. mezclan los dos idiomas.

**Paleta · caja de 8 crayones.**

| Color | HEX | Uso |
|---|---|---|
| Hoja | `#FFFDF8` | Fondo |
| Tinta | `#1E1A17` | Texto (17:1) |
| Rojo | `#D7372B` | Texto y CTA (4,6:1) |
| Naranja | `#EE7B22` | Solo trazos y superficies |
| Amarillo | `#F3C318` | Solo trazos y superficies |
| Verde | `#2F8F3A` | Trazos; texto grande (4,0:1) |
| Azul | `#1F64C8` | Texto (5,6:1) |
| Violeta | `#6E43B8` | Texto (6,5:1) |
| Rosa | `#E6618F` | Solo trazos y superficies |
| Café | `#8A5A3B` | Texto (5,7:1) |

**Tipografía.**
- **Fraunces** para titulares, con los ejes SOFT 100 y WONK personalizados para que no sea la Fraunces "de todos".
- **Shantell Sans** como la voz de Tayo.
- **Atkinson Hyperlegible Next** para el texto y las instrucciones; la máxima legibilidad sirve a padres cansados y en el celular.

**Formas e ilustración.** Más aire y menos objetos. El color llega por trazos de crayón (cera), no por bloques.

**Fotografía.** Editorial, de detalles: crayones gastados, manos y papel. Dibujos reales de Thiago escaneados.

**Elementos firma.**
- Entradas de diccionario: palabra, fonética y acepciones.
- Círculo de crayón que se dibuja solo.
- La "Palabra del mes".
- El índice de palabras toddler.

**Microinteracciones:**

| Interacción | Cómo se hace en Elementor |
|---|---|
| Círculo y subrayado de crayón que se dibujan | SVG |
| Letra manuscrita que "rebota" al pasar el cursor | Eje BNCE de Shantell Sans, en CSS |
| Notas al margen que aparecen al hacer scroll | Efectos de movimiento nativos de Elementor |

**Riesgo.** Es la dirección más ligada a la palabra "Tayo". Si el abogado recomienda cambiar el nombre, hay que rehacer el concepto central, aunque el sistema (diccionario de palabras toddler) se puede conservar con otra palabra.

### Dirección C · "A la altura de Tayo (90 cm)"

**Concepto.** El mundo visto y tocado a 90 cm del suelo: formas grandes y gruesas (círculo, cuadrado, triángulo, arco, las primeras que aprende un toddler), sellos de papa y huellas de dedo.

**Por qué es propio:**
- La edad se elige en una **regla de crecimiento** como la marcada en la pared de casa.
- Los botones son enormes: pensados para usarse con una mano y un niño en brazos.

**Paleta · tinta de sello.**

| Color | HEX | Uso |
|---|---|---|
| Blanco | `#FFFFFF` | Fondo |
| Tinta | `#1A1D2E` | Texto (16,7:1) |
| Rojo sello | `#D4302A` | Texto y superficie (4,9:1) |
| Azul | `#1D5BD8` | Texto y superficie (5,9:1) |
| Yema | `#FFC93C` | Solo superficie |
| Verde | `#0F8F63` | Texto grande y superficie (4,1:1) |
| Coral | `#FF7A59` | Solo superficie |
| Masa | `#F4EFE6` | Bloques secundarios |

**Tipografía.**
- **Grandstander** 800–900 para titulares.
- **Playpen Sans** como manuscrita legible.
- **Hanken Grotesk** para el texto.

**Formas e ilustración.** Geometría básica con textura de sello (escaneada) y huellas de dedo como viñetas.

**Fotografía.** Encuadres bajos, a la altura del niño, con fondos lisos de color.

**Elementos firma.**
- La regla de crecimiento.
- Formas sellables.
- Huellas de dedo como viñetas.
- Botones "aplastables".

**Microinteracciones:**

| Interacción | Cómo se hace en Elementor |
|---|---|
| Botón que se aplasta al tocarlo | CSS active, translateY |
| Forma que se tambalea | CSS |
| Sello que deja marca al hacer clic | CSS más ~15 líneas de JS |

**Riesgo.** Es la más "infantil" de las tres. Por COPPA y por el tono premium, los textos deben hablarle claramente a los adultos.

### Recomendación

**A como base, tomando de B la voz y los diccionarios de palabras toddler.**

- **A** es la más tangible y fotografiable (alimenta Pinterest e Instagram con material propio).
- **A** es la que mejor sobrevive a un cambio de nombre.
- **A** se construye en Elementor con CSS ligero.
- **B** aporta el alma de la historia ("Ta·yo, sustantivo") y un sistema bilingüe que ninguna competidora tiene.
- **C** queda como recurso puntual: la regla de crecimiento puede ser el selector de edad dentro de A.

La decisión es tuya.

---

# Parte A · Referencias visuales


**Fecha:** 10 de noviembre de 2026
**Alcance:** marcas infantiles y de crianza, referencias fuera del nicho, tipografía y color, y microinteracciones táctiles.

**Cómo se verificó:**

- Los sitios se consultaron con WebFetch y búsqueda web. WebFetch lee el HTML como texto y no ve el diseño renderizado. Por eso, cuando un dato sobre colores o imágenes no aparece en el código ni en una fuente citada, lo marco como **(no verificado)** o **(opinión / conocimiento previo)**.
- Las fuentes tipográficas que usan algunas marcas se sacaron del CSS de su página de inicio con `curl` y `grep`.
- La existencia de cada familia en Google Fonts y su cobertura de caracteres del español se comprobaron con el catálogo oficial (`fonts.google.com/metadata/fonts`) y con fontTools sobre los archivos que sirve la API de Google Fonts (detalle en la sección 3.3).

---

### 1. Marcas infantiles y de crianza

#### 1.1 Lovevery (lovevery.com)

**Qué hace bien**

- **La edad es la navegación principal.** Una fila de cinco tarjetas con imagen, de "0–12 Months" a "4-Year-Old", lleva cada una a su kit ([lovevery.com](https://lovevery.com)). Baby Tayo puede hacer lo mismo con sus PDFs ("1 año", "2 años", "3–4 años"), porque es la pregunta que se hace un padre al llegar.
- **La portada tiene una sola llamada a la acción.** "Explore The Play Kits" se repite en la cabecera, en el hero y a mitad de página ([lovevery.com](https://lovevery.com)).
- **La prueba social va justo bajo el hero.** La línea "4.9/5 from 22K+ happy families" aparece en cuanto se carga la página ([lovevery.com](https://lovevery.com)).
- **El registro de email pide la fecha de nacimiento del niño (opcional).** Eso permite personalizar envíos según la etapa ([lovevery.com](https://lovevery.com)). Para Baby Tayo, esto es la base para enviar el PDF adecuado a cada edad.
- **El texto es corto, confiado y habla de autoridad.** Ejemplos: "Raise curious, capable kids", "We did all the research so you don't have to" ([lovevery.com](https://lovevery.com)).

**Qué conviene evitar**

- **Datos de desarrollo sin fuente.** La frase "Ninety percent of your child's physical brain growth occurs by age 5" aparece sin cita en la portada ([lovevery.com](https://lovevery.com)). Si Baby Tayo usa datos de desarrollo, debería enlazar la fuente.
- **Estética escandinava contenida (opinión / conocimiento previo).** Madera, beige y fotografía de estilo de vida tranquila. Es premium, pero hoy la usan casi todas las marcas Montessori. Baby Tayo se diferenciaría yendo hacia el color saturado del papel de construcción.

#### 1.2 KiwiCo (kiwico.com)

**Qué hace bien**

- **Una línea de producto por edad, cada una con nombre propio.** Panda (0–36 meses), Koala (3–6), Kiwi (6–9), etc., y cada tarjeta muestra la edad en su etiqueta ([kiwico.com](https://www.kiwico.com)). Baby Tayo podría bautizar sus etapas con palabras de Thiago.
- **"Cómo funciona" en pasos numerados con icono, más FAQ y una fila de prensa "Featured in"** ([kiwico.com](https://www.kiwico.com)).
- **Tipografía comercial propia.** Usa Centra (no es de Google Fonts), según su CSS (verificado con `curl`). Eso evita el aspecto de plantilla.

**Qué conviene evitar**

- **Rejilla de ocho tarjetas iguales y onboarding de tres pasos con icono.** Es justo el patrón de "fila de tarjetas con iconos" que el brief quiere evitar ([kiwico.com](https://www.kiwico.com)).
- **Pop-up de "50% off" que repite la captura de email que ya está en la página** ([kiwico.com](https://www.kiwico.com)). A una marca premium le resta.

#### 1.3 Tiny Land (tinylandus.com)

**Qué hace bien**

- **Fotografía de "interiorismo infantil".** Un análisis externo dice que el sitio se siente más como una marca de interiorismo para espacios de niños que como una juguetera, con luz natural y muebles de madera ([SocialBook](https://socialbook.io/blog/how-tiny-land-turned-chinese-manufacturing-into-a-premium-global-toy-brand/)).
- **Barra de confianza con cifras concretas.** "3 Million+ Worldwide Sales", "5,000+ 5-star Reviews" ([tinylandus.com](https://www.tinylandus.com)).
- **Microtexto con personalidad en el carrito.** La nota de regalo dice "Psst... Just for us, not the gift!" ([tinylandus.com](https://www.tinylandus.com)).

**Qué conviene evitar**

- **Poppins y Montserrat.** Su CSS declara `font-family: 'Poppins'` y `'Montserrat'` (verificado con `curl`). Son justo las tipografías genéricas que el brief prohíbe.
- **Títulos de producto largos pensados para SEO.** Ejemplo: "Tiny Land® Iconic Wooden Play Kitchen – Cream Pretend Cooking Set for Kids". Además: insignias de descuento por todas partes (19%, 22%, 33%), "Price Guarantee" y Black Friday en el menú principal ([tinylandus.com](https://www.tinylandus.com)). Todo eso empuja a la marca hacia "tienda de ofertas".
- **Paleta pastel de crema, salvia y "Sakura Pink"** ([tinylandus.com](https://www.tinylandus.com)). Es el pastel deslavado que el brief quiere evitar.

#### 1.4 Hape (toys.hape.com)

**Qué hace bien**

- **Heritage y credenciales.** "Inspiring Play Since 1986" y "Toys & Curriculum in 5,000+ Schools" ([toys.hape.com](https://toys.hape.com/)).
- **Colaboración cultural destacada ("The Met x Hape")** y "Shop by age" con miniaturas circulares ([toys.hape.com](https://toys.hape.com/)).

**Qué conviene evitar**

- **Tres propuestas de valor con icono** (Child-Safe Materials / Educators / Trusted Worldwide) ([toys.hape.com](https://toys.hape.com/)). Es el patrón genérico.
- **Corazones "♡" decorando los títulos de sección** ([toys.hape.com](https://toys.hape.com/)). Es un recurso fácil, muy cercano a usar emojis como iconos.
- **Una afirmación de sostenibilidad sin respaldo:** "sustainably sourced wood and non-toxic paint" ([toys.hape.com](https://toys.hape.com/)).
- **Mensajes de envío contradictorios.** "$50+" en un sitio y "over $0.50" en otro ([toys.hape.com](https://toys.hape.com/)). Muestra lo que pasa cuando el CMS no se cuida.

#### 1.5 Busy Toddler (busytoddler.com): independiente, actividades para toddlers

**Qué hace bien**

- **Filtros de actividades por edad y por tema.** Edades: Baby, Toddler, Pre-K, Big Kids. Temas: Indoor, Fine Motor, Art, Science, Outdoor, Sensory, Math, Bath Time ([busytoddler.com](https://busytoddler.com)). Es el modelo de catálogo para los PDFs de Baby Tayo: filtrar por habilidad y no solo por tema.
- **Una voz de padre a padre muy reconocible.** "making it to naps, one activity at a time" ([busytoddler.com](https://busytoddler.com)).
- **Producto estrella con una promesa cuantificada.** Playing Preschool, "190 days of hands-on learning" ([busytoddler.com](https://busytoddler.com)).
- **Lead magnet concreto.** "35 Easy Toddler Activities to Break Up the Day!" ([busytoddler.com](https://busytoddler.com)). Un PDF gratis en español e inglés es el equivalente directo para Baby Tayo.

**Qué conviene evitar**

- **Estética de blog.** Su CSS usa Tahoma, Verdana y Muli (verificado con `curl`), y la página repite bloques de miniatura más título más "SEE ALL" ([busytoddler.com](https://busytoddler.com)). Funciona por contenido, no por diseño.

#### 1.6 Mini Mad Things (minimadthings.com): printables de manualidad (Australia)

Es la referencia de negocio más cercana a la Fase 1.

**Qué hace bien**

- **Precios escalonados.** Hojas a $1.99, plantillas a $2.50, packs de $3.50 a $6.50 y bundles de $11.99 a $13.50 (AUD). Más promos como "Buy 5 & get one free!" y "Save 30% with our printable bundles" ([minimadthings.com](https://www.minimadthings.com)).
- **Temas con gancho, como packs de artistas.** Kusama, Frida Kahlo, Keith Haring, Hilma af Klint ([minimadthings.com](https://www.minimadthings.com)). Baby Tayo podría hacer packs de artistas latinoamericanos.
- **Una sección que justifica la compra.** "What's the point of art & craft?" con beneficios como motricidad fina y "Screen free fun" ([minimadthings.com](https://www.minimadthings.com)).

**Qué conviene evitar**

- **Diseño de plantilla de Shopify.** Título en Bayon y cuerpo con la fuente del sistema (verificado con `curl`). Todo el color viene de las miniaturas, así que la marca en sí no tiene identidad visual.

#### 1.7 Hello Wonderful (hellowonderful.co) y The Artful Parent (artfulparent.com)

- **Hello Wonderful.**
  - Bien: contenido gratuito con plantilla imprimible, del tipo "Paper Egg Chick Craft With Printable Template" ([hellowonderful.co](https://www.hellowonderful.co)).
  - Mal: estructura de blog genérica con categorías en iconos. Además, WebFetch detectó en la portada un párrafo de spam farmacéutico en sueco ([hellowonderful.co](https://www.hellowonderful.co)). Es una alerta de seguridad para cualquier sitio WordPress: mantener plugins actualizados y revisar inyecciones.
- **The Artful Parent.** La portada actual está dominada por listas sobre padres de **hijos adultos**, del tipo "8 habits of wise parents" ([artfulparent.com](https://artfulparent.com)). En esta visita no aparecieron printables ni cursos. Es un ejemplo de marca de arte infantil que perdió el foco. Lo único aprovechable es el quiz "What is Your Inner Child's Artist Type?" como mecánica de captación ([artfulparent.com](https://artfulparent.com)).

#### 1.8 Crayola (crayola.com)

- **Bien:** lo gratuito es la puerta de entrada. "Explore Free Coloring Pages!" y "free activity sheets" en el menú principal ([crayola.com](https://www.crayola.com)). Ofrece selector de idioma, con México y España entre los mercados ([crayola.com](https://www.crayola.com)). Su texto es breve y rítmico: "Gather, color, create!" ([crayola.com](https://www.crayola.com)).
- **Evitar:** un mega-menú enorme y una cuadrícula tipo masonry de promociones ([crayola.com](https://www.crayola.com)). A la escala de Baby Tayo, eso es ruido.

#### 1.9 Conclusiones del nicho

1. **Todas navegan por edad.** Es obligatorio, pero se puede hacer de forma única: por ejemplo, la edad como "pestañas de carpeta" o "regla de crecimiento" en papel.
2. **Ninguna de las marcas revisadas lleva el mundo físico de la manualidad a la propia interfaz.** El color lo ponen las fotos de producto; la interfaz es neutra. **Esa es la oportunidad de Baby Tayo.**
3. **Patrones que se repiten y conviene evitar:** tres iconos de valor, rejillas de tarjetas iguales, pasteles, Poppins y Montserrat, y pop-ups de descuento.
4. **Ninguna de las revisadas es bilingüe en español e inglés para EE. UU.** Solo Crayola tiene selector por país. Esto es un hueco de mercado, aunque es una observación limitada a estas marcas.

---

### 2. Referencias fuera del nicho infantil

Todas las URLs respondieron HTTP 200 el 10 de noviembre de 2026 (comprobado con `curl`).

| # | Referencia | URL | Técnica concreta que se puede tomar |
|---|---|---|---|
| 1 | **Dropbox, identidad 2017 (Collins)** | [brand.dropbox.com](https://brand.dropbox.com) | **Collage como sistema:** dibujo a grafito con elementos recortados y CGI, más parejas de color que contrastan ([It's Nice That](https://www.itsnicethat.com/news/dropbox-rebrand-collins-graphic-design-041017), [Dezeen](https://www.dezeen.com/2017/10/11/dropbox-rebrand-logo-visual-identity-graphic-design/amp/)). Para Baby Tayo: fijar 6–8 parejas de papel (fondo + recorte) y usar siempre esas. Lección también: la paleta "agresiva" se criticó ([Dezeen](https://www.dezeen.com/2017/10/11/dropbox-rebrand-logo-visual-identity-graphic-design/amp/)), así que conviene que la base blanca descanse la vista. |
| 2 | **Mailchimp (Collins, 2018)** | [mailchimp.com](https://mailchimp.com) | **Un color propio y valiente** (Cavendish Yellow), una serif cálida (Cooper Light, después la custom Means) e ilustraciones "a medio camino entre Dr. Seuss y Quentin Blake" ([Creative Review](https://www.creativereview.co.uk/mailchimp-rebrand-by-collins/), [Design Week](https://www.designweek.co.uk/issues/1-7-october-2018/mailchimp-rebrand-aims-to-unify-bran), [Fonts In Use](https://www.fontsinuse.com/uses/39539/mailchimp-identity-2018-redesign)). Para Baby Tayo: elegir un color insignia (por ejemplo un amarillo crayón o un rojo tomate) y usarlo en exclusiva. |
| 3 | **Memberful, ilustraciones de papel de Maren Schabhüser** | [memberful.com](https://www.memberful.com) | **15 escenas hechas entera y físicamente en papel** para la web y el marketing ([The Artworks](https://www.theartworksinc.com/2021/12/13/maren-schabhuser-crafts-a-beautiful-paper-world-for-membership-platform-memberful/)). Para Baby Tayo: construir y fotografiar los recortes de verdad, en lugar de simular papel en vectores. Es la diferencia entre lo auténtico y el 3D de stock. |
| 4 | **Big Cartel, rebrand 2025 (How&How + Extraset)** | [bigcartel.com](https://www.bigcartel.com) | **Wordmark con letras gruesas y "cortes"** en la A y la R, ilustración con texturas litográficas y un lenguaje "scrappy" de garabatos ([Design Compass](https://designcompass.org/en/2025/05/14/big-cartel)). Para Baby Tayo: recortar letras del logo como si fueran tijera sobre cartulina. |
| 5 | **Gentle Thrills** (tienda de Los Ángeles) | [gentlethrills.com](https://gentlethrills.com) | **Ilustración plana en lugar de foto de estilo de vida, paleta casi monocroma con un acento rosa** y el titular "MORE IS MORE" ([ecomm.design](https://ecomm.design/site/gentle-thrills/)). Lección: el maximalismo funciona si se limita la paleta de la interfaz. |
| 6 | **Fishwife** (conservas) | [eatfishwife.com](https://eatfishwife.com) | **Stickers ilustrados** (por ejemplo "fishwife-sardines-sticker") dentro de secciones de comparación, y un texto con juegos de palabras, de aire coleccionable ([eatfishwife.com](https://eatfishwife.com)). Para Baby Tayo: sellos y stickers como marcas de "nuevo" o "favorito de Tayo". Ojo: Fishwife usa emojis en el texto de producto, algo que Baby Tayo debe evitar. |
| 7 | **It's Nice That** (editorial) | [itsnicethat.com](https://www.itsnicethat.com) | **Wordmark en minúsculas con una serie rotativa de iconos dibujados a mano** ([Made Good](https://madegooddesigns.com/?p=101043), según el resumen de búsqueda; no abrí el artículo completo). Para Baby Tayo: un set de 20–30 garabatos de Thiago (o al estilo de un niño) que rotan junto al logo o en los separadores. |
| 8 | **Kolaj Magazine** (revista de collage) | [kolajmagazine.com](https://kolajmagazine.com) | Archivo editorial del collage contemporáneo, que incluye el World Collage Day ([Kolaj](https://kolajmagazine.com/content/issues/world-collage-day-2025-special-edition/)). Sirve como banco de inspiración para composiciones (no analicé su interfaz). |
| 9 | **Collage** (objetos artesanales), Awwwards SOTD del 2 de septiembre de 2019 | [collagecrafting.com/en](https://collagecrafting.com/en) | E-commerce artesanal con estética "Clean, Minimal, Parallax" ([Awwwards](https://www.awwwards.com/sites/collage-hand-crafted-objects)). Lección: lo artesanal no necesita caos; mucho blanco y producto en primer plano. Es antiguo (2019) y no lo vi renderizado. |
| 10 | **Present & Correct** (papelería, Londres) | [presentandcorrect.com](https://www.presentandcorrect.com) | Categorías con verbos: **"Write, Organise, Give, Home"** ([presentandcorrect.com](https://www.presentandcorrect.com)). Para Baby Tayo: "Recorta / Pega / Pinta / Juega" (Cut / Stick / Paint / Play) como navegación bilingüe por acción. El estilo fotográfico no lo pude verificar. |
| 11 | **Tony's Chocolonely** | [us.tonyschocolonely.com](https://us.tonyschocolonely.com) | **(Conocimiento previo, no verificado en esta sesión.)** Rejilla "rota" a propósito, bloques de color plano de envoltorio y texto activista. Técnica: romper la alineación de forma controlada, por ejemplo con piezas giradas ±2–4°. |
| 12 | **Oatly** | [oatly.com](https://www.oatly.com) | **(Conocimiento previo, no verificado en esta sesión.)** Rotulación a mano imperfecta y texto en primera persona, con humor. Técnica: titulares "escritos" y notas al margen como si la fundadora hubiera garabateado sobre la página. |

**Galerías para seguir buscando**

- Categoría Illustration de Awwwards: recientes como Extrafazant (SOTD del 8 de noviembre de 2026) y "Pop-up 10 ans la Rosée" (SOTD del 28 de julio de 2025), según el resumen de búsqueda ([Awwwards Illustration](https://www.awwwards.com/websites/illustration/)). No abrí cada sitio, así que no confirmo que usen collage.
- No encontré en SiteInspire ni en FWA un listado indexado por "collage", "scrapbook" o "tape". Hay que buscar a mano con sus filtros ([SiteInspire en Toolradar](https://toolradar.com/tools/siteinspire)).

---

### 3. Tipografía y color 2025–2026

#### 3.1 Tendencias relevantes

- **Lo "hecho a mano" como respuesta a la IA.** Varios informes de 2026 lo describen:
  - Creative Market lista "Peak Journal" (recibos, sellos, cinta, notas), "Gumball Memories" (envoltorios, juguetes, stickers, colores de caramelo) y "Hand-drawn Revival" ([Creative Market Trends](https://creativemarket.com/trends)).
  - GoDaddy incluye "Retro Scrapbook" en sus tendencias web 2026 ([GoDaddy](https://www.godaddy.com/resources/skills/web-design-trends)).
  - Kittl habla de "type collage" ([Kittl](https://www.kittl.com/blogs/?p=10191)).
  - Pixlr lo resume como "handmade, scrapbooked, dopamine-bright" ([Pixlr](https://pixlr.com/blog/handmade-scrapbooked-and-dopamine-bright-the-design-trend-bringing-back-the-human-touch/)).
  - **Ojo:** son blogs de vendedores de software, sin datos que respalden la tendencia. Confirma la dirección, pero también avisa de que **el scrapbook genérico (polaroid + washi + sticker) se va a saturar en 2026–27**. Baby Tayo debe anclarlo a material propio: los recortes de Thiago y fotos reales del papel.
- **Vuelta de las serif.** Creative Bloq dice que "Fraunces and Instrument Serif" son "the hottest fonts for designers" y recoge publicaciones de diseñadores pidiendo "move on from Instrument Serif" ([Creative Bloq](https://www.creativebloq.com/design/fonts-typography/serif-fonts-are-back-in-fashion-and-i-couldnt-be-happier)). El WSJ (según un resumen) habla del regreso de las serif condensadas ([Let's Data Science](https://letsdatascience.com/news/condensed-serifs-return-as-brand-trend-d6d9bd85)).
- **Color de Pantone 2026: "Cloud Dancer" (11-4201), un blanco, el primero en la historia del programa** ([Creative Review](https://www.creativereview.co.uk/pantone-colour-of-the-year-2026-cloud-dancer/), [Dezeen](https://www.dezeen.com/2025/12/04/lofty-white-cloud-dancer-pantone-colour-of-the-year-2026/amp/)). Respalda la "base blanca". Para que no quede frío, conviene un blanco cálido tipo papel (alrededor de #FBF8F2, propuesta mía) y no #FFFFFF puro.
- **Color "dopamina", saturado y que choca** ([Pixlr](https://pixlr.com/blog/handmade-scrapbooked-and-dopamine-bright-the-design-trend-bringing-back-the-human-touch/), [Blend Now](https://www.blendnow.com/blog/design-trends-2026-you-need-to-know)). Encaja con el papel de construcción. La clave premium está en limitar los tonos y darles nombre.
- **Monotype:** solo encontré su informe 2025 (Re:Vision); el de 2026 no aparece indexado ([Monotype](https://monotype.com/type-trends)).

#### 3.2 Qué está saturado (evitar o usar con cuidado)

| Elemento | Por qué |
|---|---|
| Inter, Poppins, Montserrat | Lo pide el brief. Además, Tiny Land usa Poppins y Montserrat (CSS verificado). |
| Instrument Serif | Ya hay fatiga entre diseñadores ([Creative Bloq](https://www.creativebloq.com/design/fonts-typography/serif-fonts-are-back-in-fashion-and-i-couldnt-be-happier)). Además solo tiene un peso con su itálica (2 estilos en el catálogo de Google Fonts). |
| Fraunces "por defecto" | También aparece como "hottest" ([Creative Bloq](https://www.creativebloq.com/design/fonts-typography/serif-fonts-are-back-in-fashion-and-i-couldnt-be-happier)). Se puede usar, pero personalizando los ejes SOFT y WONK para que no parezca la de todos. |
| Fredoka, Baloo, Nunito | Redondas "infantiles" muy vistas en apps y marcas de niños (opinión). |
| Glasscore, gradientes líquidos | Creative Market lo lista como tendencia de 2026 ([Creative Market](https://creativemarket.com/trends)), pero es lo contrario de lo táctil y el brief lo excluye. |
| Pastel salvia, crema o rosa sakura | Es la paleta de Tiny Land ([tinylandus.com](https://www.tinylandus.com)), igual que la de muchas marcas Montessori. |

#### 3.3 Google Fonts con personalidad: verificación

**Método:**

- La existencia y los ejes salen del catálogo oficial `fonts.google.com/metadata/fonts`.
- La cobertura del español se comprobó con fontTools sobre los archivos servidos por `fonts.googleapis.com/css2`, buscando `ñ Ñ á é í ó ú Á É Í Ó Ú ü Ü ¿ ¡ « » — " "`.
- Para Gaegu y Gamja Flower se pidió además a la API un subset con `text=ñá¿¡`.

**Display y titulares**

| Fuente | Existe | Ejes / estilos | Español | Notas para Baby Tayo |
|---|---|---|---|---|
| **Bricolage Grotesque** | Sí (2023) | opsz, wdth, wght | Completo | Grotesca "rara" con tamaño óptico: en tamaños grandes gana carácter. **Muy recomendable para titulares.** |
| **Fraunces** | Sí (2020) | SOFT, WONK, opsz, wght | Completo | Es la mejor alternativa a Recoleta en Google Fonts: con SOFT=100 queda blanda y cálida. Recoleta **no existe** en Google Fonts (verificado). |
| **Young Serif** | Sí (2023) | 1 estilo | Completo | Serif antigua y cálida. Buena para titulares editoriales, pero solo tiene un peso. |
| **Gloock** | Sí (2023) | 1 estilo | Completo | Serif de alto contraste. Tiende a lo elegante y frío; úsala solo para acentos. |
| **Corben** | Sí | 2 estilos | Completo | Serif suave de aire retro. La propongo como sustituta de Cooper (Cooper no está en Google Fonts). Es una opinión de parecido, no una equivalencia. |
| **Bagel Fat One** | Sí (2023) | 1 estilo | Completo | Muy gruesa, tipo "letra recortada de cartulina". Para palabras sueltas o stickers. |
| **Darumadrop One** | Sí (2020) | 1 estilo | Completo | Formas de gota, muy blanda. Riesgo de leerse como "blob"; mejor solo para el logotipo o etiquetas. |
| **Grandstander** | Sí (2020) | wght (18 estilos) | Completo | Juguetona y gruesa, con muchos pesos. Buena opción "infantil" que no es Fredoka. |
| **DynaPuff** | Sí (2022) | wdth, wght | Completo | Inflada y blanda. Diseñada por Toshi Omagari y Jennifer Daniel. |
| **Sniglet** | Sí (2010) | 2 estilos | Completo, con solo 244 glifos | Redonda clásica, pero limitada. |
| **Rammetto One / Chango** | Sí | 1 estilo | Completo | Display pesadas y anchas, para sellos y etiquetas. |
| **Agbalumo** | Sí (2023) | 1 estilo | Completo | Script gruesa con mucho carácter. |
| **Poetsen One** | Sí (2024) | 1 estilo | Completo | Display amable, más nueva y menos vista. |

**Acento manuscrito ("escrito con crayón")**

| Fuente | Existe | Español | Notas |
|---|---|---|---|
| **Shantell Sans** | Sí (2023) | Completo | Basada en la letra de la artista Shantell Martin. Tiene ejes **BNCE (bounce)** e **INFM (informality)**: con ellos se puede animar un "rebote" de letras en hover usando solo CSS. **Muy recomendable.** |
| **Caveat Brush** | Sí (2015) | Completo | Pincel o crayón. Para notas al margen. |
| **Gluten** | Sí (2021) | Completo | Ejes slnt y wght. Gruesa y desenfadada. |
| **Delicious Handrawn** | Sí (2023) | Completo | Manuscrita sencilla. |
| **Playpen Sans** | Sí (2023) | Completo | De TypeTogether. Es manuscrita **legible**, la más apta para texto corto en PDFs de actividades. |
| **Borel** | Sí (2023) | Completo | Cursiva escolar francesa. |
| **Gaegu** | Sí | **NO soporta español.** Le faltan ñ, á, é, í, ó, ú, ¿ y ¡. La API devolvió solo "a" y "n" al pedir `ñá¿¡`. | Descartar. |
| **Gamja Flower** | Sí | **NO soporta acentos ni ñ.** Sí tiene ¿ y ¡. | Descartar. |

**Texto de cuerpo (legible y bilingüe)**

| Fuente | Notas |
|---|---|
| **Figtree**, **Hanken Grotesk**, **Schibsted Grotesk**, **Familjen Grotesk** | Las cuatro existen y tienen cobertura completa del español. Son alternativas sobrias a Inter. |
| **Atkinson Hyperlegible Next** (2025) | Pensada para máxima legibilidad (Braille Institute). Buena para padres que leen en el móvil y para instrucciones en los PDFs. |

**Combinaciones sugeridas (propuesta, no verificada con usuarios)**

- **A.** Bricolage Grotesque (titulares, opsz alto) + Shantell Sans (notas y acentos) + Figtree (cuerpo).
- **B.** Fraunces con SOFT 100 (titulares cálidos) + Caveat Brush (garabatos) + Atkinson Hyperlegible Next (cuerpo).
- **C.** Grandstander (titulares lúdicos) + Playpen Sans (manuscrita legible) + Hanken Grotesk (cuerpo).

**Nota de rendimiento en WordPress:** conviene alojar las fuentes en el propio servidor (Elementor permite subir fuentes propias) y limitar los ejes variables a los rangos que se usan. No medí el tamaño de cada archivo.

#### 3.4 Paleta sugerida: "papel de construcción" (propuesta)

- **Fondo:** blanco papel cálido, más un "kraft" para bloques secundarios.
- **Colores:** 5–6 tonos saturados y opacos, como los de una caja de cartulinas. Por ejemplo: tomate, caléndula/amarillo crayón, cobalto, verde césped, mandarina y rosa chicle.
- **Nombres en ambos idiomas:** "Rojo Tayo / Tayo Red".
- **Texto en un tono casi negro de lápiz grafito**, no negro puro.
- **Contraste:** el amarillo y la mandarina sobre blanco no llegan a AA para texto (afirmación general de WCAG, no medida con hex concretos). Úsalos como superficie o recorte, no para texto.

---

### 4. Microinteracciones táctiles y su costo de rendimiento

**Principio base:** las únicas propiedades que el navegador puede animar solo en el compositor son `transform` y `opacity`; además conviene vigilar cuántas capas se crean ([web.dev](https://web.dev/articles/stick-to-compositor-only-properties-and-manage-layer-count)). Chrome recomienda animar `transform` y `opacity` y reducir el movimiento con `prefers-reduced-motion` ([Chrome for Developers](https://developer.chrome.com/docs/modern-web-guidance/guides/ui-behaviors/motion)). Shopify da el mismo patrón, con `animation: none` dentro de `@media (prefers-reduced-motion: reduce)` ([Shopify](https://shopify.dev/docs/storefronts/themes/best-practices/performance/use-transform-for-animations)).

| Técnica | Cómo | Costo | Recomendación |
|---|---|---|---|
| **Wiggle o tambaleo** de stickers y botones | `@keyframes` con `transform: rotate(-3deg)` ↔ `rotate(3deg)` en hover | **Bajo**, va en el compositor ([web.dev](https://web.dev/articles/stick-to-compositor-only-properties-and-manage-layer-count)) | Sí. Solo en hover o foco, nunca en bucle infinito en toda la página. |
| **Piezas "pegadas" giradas** | `transform: rotate()` estático con valores distintos (±1–4°) | Prácticamente nulo | Sí. Es la base del aspecto collage. |
| **Subrayado tipo crayón** | Trazo SVG irregular con `pathLength="1"`, animando `stroke-dashoffset` de 1 a 0 ([CSS-Tricks](https://css-tricks.com/?p=254582)) | **Bajo o medio:** `stroke-dashoffset` no es una propiedad del compositor, así que repinta, pero solo el área pequeña del trazo (inferencia a partir de web.dev; no medido) | Sí. Usar `stroke-linecap: round` para disimular los extremos. En foros de GSAP reportan puntitos o muescas en los bordes con el método solo-CSS ([GSAP](https://gsap.com/community/tags/strokedashoffset/)). |
| **Cinta adhesiva (washi)** | Pseudo-elemento `::before` con PNG o SVG semitransparente con bordes dentados (o `clip-path: polygon()`), girado | Nulo si es estático | Sí. Mejor usar 3–4 tiras de cinta escaneadas de verdad (webp pequeño) que dibujarlas en CSS. |
| **Papel con textura** | (a) imagen de textura escaneada en webp como `background`; (b) ruido SVG con `feTurbulence` | (a) bajo, solo el peso del archivo. (b) el ruido se calcula **por píxel** y más octavas cuestan más ([CSS-Tricks](https://css-tricks.com/?p=335760), [lista W3C](https://lists.w3.org/Archives/Public/www-svg/2013Nov/0049.html)). No encontré una medición fiable del repintado al aplicarlo como `filter: url()`. | Usar (a). Si se usa `feTurbulence`, con 1–3 octavas, solo como fondo estático y **nunca animado** ([Codrops](https://tympanus.net/codrops/2019/02/19/svg-filter-effects-creating-texture-with-feturbulence/)). |
| **Sombra de papel levantado** | `box-shadow` doble y suave. Al "levantar" en hover, animar `transform: translateY()` y la `opacity` de un pseudo-elemento que ya tiene la sombra | Animar `box-shadow` directamente provoca repintado. Con el truco del pseudo-elemento se queda en el compositor ([web.dev](https://web.dev/articles/stick-to-compositor-only-properties-and-manage-layer-count)). | Sí, con el truco. |
| **Sticker que se despega (esquina doblada)** | `clip-path` más un pseudo-elemento con gradiente. Se puede animar porque `clip-path` funciona con transiciones CSS ([Kitty Giraudel vía Frontend Feeds](https://frontend-feeds.netlify.app/kitty-giraudel/folded-corner-with-css/)). Texto que se despega solo con CSS: Mandy Michael ([CodeMyUI](https://codemyui.com/peel-away-sticker-text-effect/)). Versiones con arrastre en JS ([tutorial](https://learnhowto.vercel.app/blog/css/mastering-the-peeling-sticker-effect-with-css-and-javascript), [DEV](https://dev.to/petertech/recreating-imessages-sticker-peel-off-effect-i2g)). | **Medio:** `clip-path` y los gradientes repintan. No verifiqué si se compone en el compositor en todos los navegadores. | Para 1–3 stickers "premio" por página (por ejemplo "¡Descarga gratis!"), no para cada tarjeta. |
| **Stickers arrastrables** | Pointer Events más `transform: translate()` y unos 30 líneas de JS | Bajo si solo se mueve `transform` | Opcional, como juego en la página de "Sobre Tayo". |
| **Texto con rebote** | Animar el eje `BNCE` de Shantell Sans con `font-variation-settings` | Cambiar ejes variables obliga a recalcular el texto (repintado; no medido) | Solo en palabras sueltas. |

**Notas para Elementor Pro (opinión técnica):**

- Meter estas animaciones como CSS personalizado o en un snippet global, en vez de usar varios add-ons de animación.
- Cargar el JS de arrastre o despegado solo en las páginas que lo usan.
- Respetar siempre `prefers-reduced-motion`.

---

### 5. Huecos y lo que no pude verificar

- **Colores y tipografía de Lovevery y Hape:** el HTML no los expone (Lovevery se renderiza por JS). Las descripciones visuales que no tienen cita salen de conocimiento previo.
- **Tony's Chocolonely y Oatly:** la descripción de la técnica es de conocimiento previo; no la verifiqué en esta sesión.
- **Howkapow** (paper cut-outs fotografiados, rediseño de Hype & Slippers) aparece en un resultado de búsqueda de Creative Bloq. No pude leer el artículo, así que no lo incluyo como referencia principal.
- **Ghia (ghia.com):** responde HTTP 200, pero no pude analizarla (falló la consulta con WebFetch).
- **Costos de rendimiento:** no medí ninguno en DevTools. La tabla de la sección 4 se basa en las reglas generales del compositor y en las fuentes citadas. Se recomienda perfilar en un móvil Android de gama media antes de lanzar.

---

# Parte B · Stack técnico


Investigación hecha el 10 de noviembre de 2026 con búsqueda web. Junto a cada dato va su fuente. Las fuentes oficiales (páginas de precios y wordpress.org) tienen prioridad sobre los blogs de afiliados. Si algo **no se pudo verificar**, se dice así.

Contexto: mercado de EE. UU. (USD), sitio bilingüe ES/EN y fundadora que no programa. El presupuesto de plugins es austero, de unos $100–250 al año además de Elementor Pro.
- **Fase 1:** PDFs de pago y gratis.
- **Fase 2:** kits físicos y libros impresos.
- **Fase 3:** juguetes y una posible suscripción.

---

### 0. Resumen de la recomendación

| Capa | Recomendación | Costo anual aprox. |
|---|---|---|
| Tema | **Hello Elementor** (gratis) | $0 |
| Constructor | **Elementor Pro**, como mínimo el plan **Advanced Solo** (Essential no trae WooCommerce, Popups, Custom CSS ni el guardado de envíos de formularios) | ya pagado; Advanced Solo $84/año |
| Tienda | **WooCommerce** (gratis) con descargas nativas | $0 |
| Marca de agua en PDF | **PDF Ink Lite** (gratis); si falla, **Smart PDF Watermarking** ($39/año) | $0–39 |
| Pagos | **WooPayments** o **WooCommerce Stripe Gateway** (2.9% + $0.30) + **PayPal Payments** | solo comisiones |
| Impuestos | **WooCommerce Tax** (gratis, solo calcula) y registro únicamente en el estado propio; vigilar los umbrales de nexo | $0 |
| Email | **MailerLite** gratis (hasta 250 suscriptores) con la acción nativa de Elementor Forms | $0, luego desde ~$12/mes |
| Bilingüe | **TranslatePress Personal** (€99) o **WPML Multilingual CMS** (€99) | ~$115 |
| SEO | **Rank Math** gratis | $0 |
| Caché | **LiteSpeed Cache** gratis (si el servidor es LiteSpeed); si no, **Perfmatters** $29.95 + la caché del hosting | $0–30 |
| Imágenes | **Converter for Media** gratis (WebP), o la conversión de LiteSpeed/QUIC.cloud | $0 |
| Seguridad | **Cloudflare Free** + **Wordfence Free** (o la seguridad del hosting) | $0 |
| Backups | Backups del hosting + **UpdraftPlus Free** a Google Drive | $0 |
| Cookies/legal | **Complianz** gratis (Premium $59 si hace falta) | $0–59 |
| Reseñas | Reseñas nativas de WooCommerce | $0 |
| Filtros | **Loop Grid + Taxonomy Filter** de Elementor Pro con taxonomías propias | $0 |
| Campos | Ninguno al inicio. Si hace falta: **ACF** gratis | $0 |

**Total en plugins (sin Elementor):** unos **$115–245 al año**, y probablemente cerca de $115–150.

---

### 1. Tema base para Elementor

| Tema | Peso base (según fuentes) | Compatibilidad con Elementor/Woo | Comentario |
|---|---|---|---|
| **Hello Elementor** 3.5.2 (actualizado el 3/nov/2026, más de 1M de instalaciones, requiere WP 6.0+ y PHP 7.4+) [wordpress.org](https://wordpress.org/themes/hello-elementor/) | ~6 KB el tema solo; Elementor añade 200–400 KB [theplusaddons](https://theplusaddons.com/blog/wordpress-elementor-stack-2026.md) | Es el tema oficial de Elementor. Cabecera, pie y plantillas Woo se hacen con Theme Builder (Pro) | La opción más ligera y la más simple si ya se paga Pro. Una reseña en wordpress.org advierte que sin Pro no se edita el header/footer [wordpress.org](https://wordpress.org/plugins/elementor/) |
| **Astra** | 38–48 KB según distintas pruebas [deothemes](https://deothemes.com/?p=17815), [themeisle](https://themeisle.com/blog/fastest-wordpress-themes/) | Muy buena | Útil sin Elementor Pro. Con Pro, duplica funciones |
| **GeneratePress** | Va de ~30 KB a 277 KB según la prueba; las cifras no son comparables entre sí [colorlib](https://colorlib.com/wp/free-wordpress-themes/) | Buena | Muy ligero, pero pensado sobre todo para el editor de bloques |
| **Kadence** | 42–55 KB [wpschool](https://wpschool-3vo.pages.dev/comparisons/kadence-vs-astra/) | Buena | Su punto fuerte es el header builder gratis, que no hace falta si se tiene Pro |
| **Blocksy** | Pocos datos; "competitivo" según [master-addons](https://master-addons.com/best-lightweight-wordpress-themes-for-elementor/) | Buena | Trae más funciones de serie |

**No verificado:** no hay ninguna prueba independiente de 2026 que compare los cinco temas con el mismo contenido. Los números vienen de blogs de afiliados.

**Recomendación:** usar **Hello Elementor**. Con Elementor Pro, el Theme Builder hace el trabajo de los temas "multipropósito". Lo que pesa es Elementor, no el tema.

---

### 2. Elementor gratis vs. Pro en 2026

#### Estado del producto
- **Elementor 4.4.0** salió el 9 de noviembre de 2026 y tiene más de 10 millones de instalaciones. La descripción oficial dice: "Elementor is now in version 4, with a new generation of performance-first atomic building blocks" [wordpress.org](https://wordpress.org/plugins/elementor/).
- **Editor V4 (Atomic)** [FAQ oficial V4](https://elementor.com/products/website-builder/v4-faq/):
  - Es el editor por defecto en los sitios **nuevos** desde abril de 2026.
  - Los sitios existentes **no** migran solos.
  - Los widgets clásicos (v3) y los Atomic conviven en la misma página.
  - Atomic produce HTML sin capas extra de envoltorios, lo que mejora el DOM y los Core Web Vitals. Elementor no publica cifras.
  - Según esa FAQ, **Grid y Loop todavía no existían** como Atomic Elements. El changelog cita "Loop" en la 4.2.0 (20/jul/2026) [theplusaddons](https://theplusaddons.com/blog/elementor-loop-grid-v4-atomic/). La 4.0.0 (30/mar/2026) se presentó como "Atomic Forms".
  - **Hay contradicciones entre fuentes.** Lo prudente es seguir usando los widgets clásicos de Loop Grid, Woo y Forms (Pro) para las partes dinámicas, y Atomic solo para el maquetado.
- **Contenedores flexbox/grid:** la ayuda oficial tiene un artículo llamado "Analyze Flexbox container performance" [elementor help](https://elementor.com/help/what-are-performance-experiments/). Los contenedores son el estándar de v3; las secciones y columnas son el modelo antiguo. **No verificado** en un changelog de 2026 si los contenedores grid siguen marcados como experimento.

#### Planes de Elementor Pro
La página oficial no mostraba precios al consultarla [elementor.com/pricing](https://elementor.com/pricing/). Los precios siguientes vienen de un tercero que revisó esa página el 29 de octubre de 2026 [theplusaddons](https://theplusaddons.com/blog/elementor-pro-pricing/).

| Plan | Año 1 | Renovación | Sitios | WooCommerce | Popups | Custom CSS/Code | Envíos de formularios guardados |
|---|---|---|---|---|---|---|---|
| Essential | $60 | $60 | 1 | ❌ | ❌ | ❌ | ❌ |
| **Advanced Solo** | $84 | $84 | 1 | ✅ | ✅ | ✅ | ✅ (no confirmado de forma explícita) |
| Advanced | $108 | $108 | 3 | ✅ | ✅ | ✅ | ✅ |
| Expert | $204 | $204 | 25 | ✅ | ✅ | ✅ | ✅ |
| One (incluye IA, imágenes, cookies, email) | $180 | $228 | 1 | ✅ | ✅ | ✅ | ✅ |

La tabla oficial confirma lo siguiente [elementor.com/pricing](https://elementor.com/pricing/):
- **Essential** incluye Theme Builder, Forms (sin guardar los envíos) y Loop Grid, con 57 widgets.
- **Advanced Solo y superiores** tienen 85 widgets y añaden eCommerce, Popups y Custom CSS.
- **Custom fonts:** la página no los menciona en ningún plan, así que **no se pudo verificar**. Revisarlo en el panel de la licencia.

#### Funciones de Pro que Baby Tayo necesita

| Función | ¿Por qué? | ¿Plan mínimo? |
|---|---|---|
| Theme Builder | Header, footer y plantillas de entrada/archivo para la "biblioteca de actividades" | Essential |
| WooCommerce Builder | Diseñar la ficha de producto, la tienda, el carrito y el checkout | **Advanced Solo** |
| Loop Grid + Taxonomy Filter | Biblioteca filtrable por edad, habilidad o material [elementor help](https://elementor.com/help/taxonomy-filter-widget/) | Essential (Loop Grid) |
| Forms + acción MailerLite/Kit | Lead magnet | Essential (sin guardar envíos) |
| Popups | Pop-up de lead magnet o de salida | **Advanced Solo** |
| Custom CSS | Ajustes finos | **Advanced Solo** |

**Conclusión:** si la licencia actual es **Essential**, conviene subir a **Advanced Solo** (+$24/año) antes de la Fase 1.

---

### 3. E-commerce: qué plataforma usar

| Opción | Costo | PDFs (límite/expiración de descargas) | Marca de agua con email | Físicos/envíos/inventario | Suscripciones | Impuestos |
|---|---|---|---|---|---|---|
| **WooCommerce** 11.2.2 (4/nov/2026, más de 7M instalaciones, requiere WP 7.0+) [wordpress.org](https://wordpress.org/plugins/woocommerce/) | Gratis | Límite y expiración **por producto**, de forma nativa [stackharbor](https://stackharbor.com/fr/base-de-connaissances/woo-vs-easy-digital-downloads/) | Con plugin: PDF Ink Lite (gratis) o Smart PDF Watermarking ($39) | ✅ Nativo y completo | WooCommerce Subscriptions **$279/año** [woocommerce.com](https://woocommerce.com/products/woocommerce-subscriptions/) | WooCommerce Tax gratis (solo calcula) |
| **Easy Digital Downloads** | Lite gratis. Personal $99.50, Extended $199.50, Professional $299.50 [EDD pricing](https://easydigitaldownloads.com/pricing/) | ✅ Enlaces que expiran y límites | PDF Ink Lite es compatible con EDD [wordpress.org](https://wordpress.org/plugins/waterwoo-pdf/) | ❌ "Built for digital goods, so physical sales need WooCommerce" [EDD vs Woo](https://easydigitaldownloads.com/compare/woocommerce) | Extensión de pago | Extensión de pago |
| **SureCart** | Gratis con 1.9% por venta; Pro ~$179–199/año [gauravtiwari](https://gauravtiwari.org/surecart-vs-woocommerce/), [bitdoze](https://www.bitdoze.com/surecart-review/) (**no verificado** en la página oficial) | ✅ | No consta | Básico | ✅ | Su propio sistema |
| **Lemon Squeezy** (Merchant of Record) | 5% + $0.50 [dodopayments](https://dodopayments.com/blogs/lemonsqueezy-review) | ✅ | No consta | ❌ | ✅ | ✅ Paga los impuestos por ti. Ojo: Stripe está pasando el producto a "Stripe Managed Payments" (2026) y algunas reseñas critican el soporte [alexcloudstar](https://alexcloudstar.com/blog/merchant-of-record-indie-saas-2026/) |
| **Payhip** (MoR) | Gratis con 5%; Plus $29/mes con 2%; Pro $99/mes con 0%, más Stripe/PayPal [payhip.com/pricing](https://payhip.com/pricing) | ✅ | **No verificado** en la página de precios | Limitado | ✅ | ✅ Cobra y paga los impuestos de ventas de EE. UU. |
| **Gumroad** (MoR desde 2025) | 10% + $0.50 por venta directa; 30% vía Discover [gumroad.com/pricing](https://gumroad.com/pricing) | ✅ | No consta | ❌ | ✅ | ✅ |
| **Shopify Buy Button** | Requiere un plan Shopify; **precio no verificado** en esta sesión | ✅ con apps | Con apps | ✅ | ✅ | Shopify Tax |

#### Entrega segura en WooCommerce
- **Descargas nativas.** Se configura por producto (límite y expiración) [stackharbor](https://stackharbor.com/fr/base-de-connaissances/woo-vs-easy-digital-downloads/).
- **Método de entrega.** En Ajustes → Productos → Descargables, usar "Forzar descargas" o "X-Accel-Redirect/X-Sendfile" para no exponer la URL del archivo. Esto **viene de la documentación de WooCommerce y no se re-verificó** en esta sesión.
- **Marca de agua (PDF Ink Lite).**
  - Ficha [wordpress.org](https://wordpress.org/plugins/waterwoo-pdf/): v4.1.6, actualizado el 12/oct/2026, probado hasta WP 7.1.4, compatible con WooCommerce 8.2+, EDD y Download Monitor.
  - **La versión gratis ya estampa nombre, email, fecha y teléfono**, y puede poner contraseña y bloquear copia e impresión.
  - La versión completa cuesta desde $45.
- **Smart PDF Watermarking** [woocommerce.com](https://woocommerce.com/products/smart-pdf-watermarking/):
  - Cuesta $39/año. Crea una copia con marca de agua en cada descarga y deja intacto el original.
  - Probado con WooCommerce 11.2.1 y WP 7.1.
  - **Necesita Ghostscript y `proc_open()` en el servidor para PDF 1.5+.** Hay que preguntarle al hosting.
- **WooCommerce PDF Watermark** (el oficial antiguo) solo admite PDF ≤1.4 [docs](https://woocommerce.com/document/woocommerce-pdf-watermark/). No se recomienda, porque Canva exporta versiones más nuevas.

#### Recomendación clara: WooCommerce
Es la única opción que cubre las tres fases en el mismo sitio sin migrar:
- **Fase 1:** PDFs, gratis.
- **Fase 2:** envíos, inventario y variaciones, de forma nativa.
- **Fase 3:** WooCommerce Subscriptions ($279/año) cuando haya ingresos.

Además, Elementor Pro tiene un WooCommerce Builder nativo.

EDD se queda corto en cuanto lleguen los productos físicos. Un MoR (Payhip, Gumroad o Lemon Squeezy) quita el trabajo de impuestos, pero saca el checkout fuera del sitio, cobra entre el 5% y el 10% y complica el catálogo bilingüe. Es una alternativa válida **solo** si la fundadora no quiere ocuparse de los impuestos de ventas en la Fase 1.

---

### 4. Pasarelas de pago (EE. UU.)

| Pasarela | Tarjeta doméstica | Tarjeta internacional | Disputa | Wallets |
|---|---|---|---|---|
| **WooPayments** | 2.9% + $0.30 | +1.5% (+1% si hay conversión de divisa) | $15, devueltos si se gana | Apple Pay y Google Pay con la misma tarifa que las tarjetas [woocommerce.com](https://woocommerce.com/document/woopayments/fees-and-debits/fees/) |
| **Stripe** (plugin oficial *WooCommerce Stripe Payment Gateway* 11.1.1, 16/oct/2026, más de 700k instalaciones) | 2.9% + 30¢ [stripe.com/pricing](https://stripe.com/pricing) | +1.5% (+1% conversión) | $15 (+$15 si se contesta y se pierde) | Apple Pay, Google Pay, Link, ACH, Klarna y Afterpay [wordpress.org](https://wordpress.org/plugins/woocommerce-gateway-stripe/) |
| **PayPal Checkout** | 3.49% + $0.49 | — | — | Venmo con la misma tarifa; Pay Later 4.99% + $0.49 [paypal.com](https://www.paypal.com/us/business/paypal-business-fees) (tabla del 4/nov/2026) |
| PayPal Advanced Card | 2.89% + $0.29 | — | — | — |

#### Notas
- **Comisión fija en PDFs baratos.** En un PDF de $5, Stripe se lleva unos $0.45 (9%) y PayPal unos $0.66 (13%). Conviene vender en **bundles** o fijar precios ≥ $8–10.
- **Suscripciones.** Las suscripciones integradas de WooPayments **se eliminaron en la versión 10.2.0**. Ahora hace falta WooCommerce Subscriptions [woocommerce.com](https://woocommerce.com/document/woopayments/subscriptions/).
- **Recomendación:** **WooPayments** (todo dentro de WooCommerce, más sencillo) o **Stripe oficial** (cuenta Stripe propia y portátil, compatible con Stripe Tax). Para alguien que no programa, cualquiera de las dos sirve. Se prefiere **Stripe oficial** porque la cuenta no depende de Woo y se integra con Stripe Tax. A eso se añade **PayPal Payments** como segundo método.

---

### 5. Impuestos sobre productos digitales en EE. UU.

> No es asesoría fiscal. Conviene consultar con un CPA del estado donde esté registrada la empresa.

**Estados que gravan las descargas digitales** (total o parcialmente), según [Quaderno, actualizado el 11/may/2026](https://www.quaderno.io/blog/sales-tax-digital-products-us):
- AL, AZ, AR, CO, CT, GA (con condiciones), HI, ID, IN, IA, KY, LA, ME, MD, MN, MS, NE, NJ, NM, NC, OH (parcial), PA, RI, SD, TN, TX, UT, VT, WA, WI, WY y DC.

**Estados que no las gravan:**
- CA, FL, IL, KS, MA, MI, MO, NV, NY, ND, OK, SC, VA y WV.

**Estados sin impuesto de ventas:**
- DE, MT, NH y OR. En AK depende de la localidad.

**Cambios en 2026:**
- **Maine** amplió el impuesto a audio y audiovisual digital desde el 1/ene/2026 [taxcloud](https://taxcloud.com/?p=23705).
- **Utah** lo amplió a más productos digitales desde el 1/jul/2026 [vatcalc](https://vatcalc.com/united-states/us-utah-sales-tax-on-digital-services-july-2026).
- Las fuentes no se ponen de acuerdo en los totales. Los PDFs imprimibles para niños no siempre encajan en una categoría clara.

#### Nexo económico
- Casi todos los estados usan un umbral de **$100,000 en ventas** dentro del estado. AL y MS usan **$250k**; CA, NY y TX, **$500k** [taxually](https://www.taxually.com/blog/economic-nexus-by-state), [beancount](https://beancount.io/blog/2026/05/16/sales-tax-economic-nexus-wayfair-online-sellers-100000-threshold-multistate-registration-guide).
- **Unos 16 estados ya eliminaron el umbral de 200 transacciones**, entre ellos Illinois (1/ene/2026) y Kentucky (1/ago/2026) [avalara](https://www.avalara.com/us/en/blog/states-eliminating-economic-nexus-transaction-thresholds.html), [vatcalc](https://www.vatcalc.com/?p=43552).
- Todavía unos 15 estados mantienen ese umbral de 200 transacciones. Un negocio de PDFs baratos podría alcanzar 200 ventas en un estado antes que los $100k.

#### Herramientas

| Herramienta | Costo | Qué hace |
|---|---|---|
| **WooCommerce Tax** | Gratis | Calcula el impuesto en el checkout; **no presenta ni paga** las declaraciones [woocommerce.com](https://woocommerce.com/products/tax) |
| **Stripe Tax** (plugin para Woo) | 0.5% por transacción **en los estados donde estés registrado** (Basic, no-code); Complete desde $90/mes [stripe.com/pricing](https://stripe.com/pricing), [woocommerce.com](https://woocommerce.com/products/stripe-tax/) | Calcula el impuesto y **monitorea los umbrales**. Algunas reseñas del plugin son negativas (por ejemplo, el impuesto del envío) |
| TaxJar / Avalara | De pago; **precio 2026 no verificado** | Calculan y presentan las declaraciones |
| MoR (Payhip, Gumroad, Lemon Squeezy, Paddle) | 5–10% por venta | Asumen toda la obligación |

#### Recomendación práctica para una microempresa
1. Registrar el permiso de ventas **solo en el estado propio**, si ese estado grava productos digitales o los kits físicos.
2. Activar WooCommerce Tax (gratis) con tasas **únicamente** para ese estado y asignar la clase de impuesto correcta a los productos digitales.
3. Revisar cada trimestre las ventas por estado (WooCommerce → Analíticas). Cuando un estado se acerque a 200 transacciones o $100k, pasar a **Stripe Tax** y registrarse allí.

---

### 6. Email marketing y lead magnet

| Servicio | Plan gratis 2026 | Precio de entrada | Elementor Forms | WooCommerce | Entrega del PDF |
|---|---|---|---|---|---|
| **MailerLite** | **250 suscriptores**, 2,500 emails/mes, 3 automatizaciones de 5 pasos, 3 formularios, 1 landing [mailerlite.com/pricing](https://www.mailerlite.com/pricing). Bajó desde 1,000 el 16/jun/2026 [groupmail](https://blog.groupmail.io/mailerlite-free-plan-limits/) | Comfort desde $12/mes; Power desde $25/mes [mailerlite.com/pricing](https://www.mailerlite.com/pricing) | ✅ Acción nativa [elementor help](https://elementor.com/help/mailerlite-and-elementor-integration) | Integración listada, **plan no confirmado** | Automatización de bienvenida con enlace al PDF |
| **Kit** (ConvertKit) | **10,000 suscriptores**, formularios y landings ilimitados, **sin automatizaciones ni secuencias** [kit.com/pricing](https://kit.com/pricing) | Creator $390/año con 1,000 suscriptores [kit.com/pricing](https://kit.com/pricing) | ✅ Acción nativa [elementor help](https://elementor.com/help/convertkit-elementor-integration/) | Plugin propio | "Incentive email" con archivo. **No verificado** que siga en el plan gratis de 2026 |
| **Klaviyo** | 250 perfiles, 500 emails/mes [klaviyo.com/pricing](https://www.klaviyo.com/pricing) | $20/mes con 500 perfiles | ❌ No nativo; requiere un plugin o un formulario embebido [klaviyo community](https://community.klaviyo.com/marketing-30/how-to-add-klaviyo-on-elementor-8973) | ✅ Excelente | Flow |
| **Brevo** | 300 emails/día, contactos amplios, marca Brevo en los emails [sendx](https://www.sendx.io/blog/brevo-pricing-plans-costs-alternatives-2026) | Starter desde ~$9/mes (**sin confirmar** en la web oficial) | ❌ No nativo (TriggerNinja u otro plugin) | ✅ Plugin | Automatización |

Elementor Pro trae de serie las acciones de MailChimp, Drip, ActiveCampaign, GetResponse, ConvertKit y MailerLite [developers.elementor.com](https://developers.elementor.com/docs/form-actions/).

#### Recomendación: MailerLite
- Tiene acción nativa en Elementor, 3 automatizaciones gratis para el email de bienvenida con el PDF y una integración con WooCommerce.
- Al pasar de 250 suscriptores costará unos $12–15/mes. Esto es marketing, no un plugin; conviene presupuestarlo aparte.
- **Alternativa austera:** Kit gratis (hasta 10k suscriptores) si basta con entregar el PDF sin secuencias.
- **Klaviyo** encaja en la Fase 2–3, cuando importen los flujos de carrito abandonado y la segmentación por compras.

**Cómo entregar el PDF gratis.** Opción A: subirlo a la biblioteca de medios y enviar el enlace en el email automático. Opción B, más trazable: crear un **producto WooCommerce de $0** descargable, lo que da registro del cliente, límite de descargas y marca de agua.

---

### 7. Sitio bilingüe

| Plugin | Costo anual | Elementor | WooCommerce | SEO (hreflang, slugs) | Nota |
|---|---|---|---|---|---|
| **WPML** | Blog €39 (sin Woo ni builders); **CMS €99** (Woo + Elementor, 22,500 palabras de IA); Agency €199 [app.wpml.org](https://app.wpml.org/purchase) | ✅ oficial en CMS | ✅ WooCommerce Multilingual incluido | ✅ | El más completo; algo más pesado |
| **Polylang** | Gratis. Pro €99; Business Pack (Pro + Woo) €139 [polylang.pro](https://polylang.pro/pricing/). Polylang for Woo suelto €99 según [wpml.org](https://wpml.org/es/pagina-principal/el-mejor-plugin-de-traduccion-para-wordpress-comparacion-detallada-2026/wpml-frente-a-polylang/) (fuente competidora) | Vía el plugin de terceros "Polylang Connect for Elementor"; DeepL **no** funciona con Elementor | Requiere el add-on de pago | ✅ (traducir slugs es Pro) | La versión gratis sirve para el blog, pero la tienda exige pagar €99–139 |
| **TranslatePress** | Personal €99 (1 sitio, 50k palabras de IA); Business €199 [translatepress.com](https://translatepress.com/pricing/) | Traduce desde el front-end, así que funciona con cualquier constructor | Sí; la compatibilidad no se detalla en la página de precios | SEO Pack y traducción de slugs en todos los planes de pago | **El más fácil** para alguien que no programa: edición visual. Que la versión gratis traiga 1 idioma extra **no se verificó** en esta sesión |
| **Weglot** | Starter $170/año (**10,000 palabras en total**, 1 idioma); Business $320 (50k) [weglot.com](https://www.weglot.com/pricing) | ✅ | ✅ | ✅ | El límite de palabras no se renueva. Un catálogo de actividades lo agota pronto; **no recomendado** |

#### Recomendación
- **TranslatePress Personal (€99, ~$115/año).** Se traduce sobre la página tal como se ve: Elementor, Woo y los emails, con URLs `/es/` y hreflang gracias al SEO Pack.
- **Alternativa robusta: WPML CMS (€99).** Tiene compatibilidad oficial con Elementor y WooCommerce y es mejor si el catálogo crece mucho.
- Antes de comprar, probar en un sitio de staging que las plantillas del Theme Builder y el checkout se traducen bien.

---

### 8. Plugins esenciales (mínimos)

| Función | Elegido | Alternativa | Costo |
|---|---|---|---|
| SEO | **Rank Math Free** | Rank Math Pro: $5.59/mes el primer año y $107.88/año al renovar [rankmath.com](https://rankmath.com/pricing/); Yoast y SEOPress (precios no verificados) | $0 |
| Caché | **LiteSpeed Cache** (gratis, solo en servidores LiteSpeed) o la caché del hosting | WP Rocket: Single $3/mes el primer año, renovación no publicada [wp-rocket.me](https://wp-rocket.me/pricing/); FlyingPress $59/año, sin CDN [flyingpress.com](https://flyingpress.com/pricing/); Perfmatters $29.95/año [perfmatters.io](https://perfmatters.io/pricing/) | $0–59 |
| Imágenes WebP/AVIF | **Converter for Media** gratis (WebP; AVIF solo en PRO). v6.7.2, 5/nov/2026, más de 500k instalaciones [wordpress.org](https://wordpress.org/plugins/webp-converter-for-media/) | Optimizador de LiteSpeed/QUIC.cloud; ShortPixel y EWWW (precios no verificados) | $0 |
| Seguridad | **Cloudflare Free** (DNS, CDN, WAF básico) + **Wordfence Free** | Solid Security; la seguridad del hosting | $0 |
| Backups | **Backups diarios del hosting** + **UpdraftPlus Free** a Google Drive | — | $0 |
| Formularios | **Elementor Forms** (Pro) | — | incluido |
| Reseñas | **Reseñas nativas de WooCommerce** (solo de compradores verificados) | Judge.me (gratis con marca; Awesome $15/mes [capterra](https://www.capterra.com/p/215990/Judge-me/pricing/)); CusRev (no verificado) | $0 |
| Cookies/legal | **Complianz Free** | Complianz Premium $59/año, con Consent Mode v2 en el plan Personal [complianz.io](https://complianz.io/pricing/); CookieYes (no verificado). El plan Elementor One incluye Cookie Consent [elementor.com](https://elementor.com/pricing/) | $0–59 |
| Biblioteca filtrable | **Loop Grid + Taxonomy Filter** de Elementor Pro. Admite varios filtros sobre el mismo Loop Grid y modo AND/OR [elementor help](https://elementor.com/help/taxonomy-filter-widget/) | Filter Everything Pro $69/año [filtereverything.pro](https://filtereverything.pro/pricing/); JetSmartFilters ~$26–57/año (cifras contradictorias) [crocoblock](https://crocoblock.com/plugins/jetsmartfilters/); Search & Filter Pro (no verificado) | $0 |
| Campos personalizados | **Ninguno** al principio. Usar taxonomías propias (edad, habilidad, material, idioma) | ACF Free si hiciera falta, por ejemplo para el campo "tiempo de preparación"; JetEngine y Pods (no se investigó el precio) | $0 |
| Taxonomías y CPT | Registrar el CPT "Actividad" y sus taxonomías con **ACF Free**, que lo permite desde la interfaz (**no re-verificado** en esta sesión) | CPT UI | $0 |

**Posibles extras de pago:** marca de agua ($0–39), Complianz Premium ($59) y Filter Everything Pro ($69) solo si el Taxonomy Filter nativo se queda corto.

---

### 9. Rendimiento con Elementor

#### Ajustes de Elementor
En Elementor → Ajustes → Rendimiento/Features [elementor help](https://elementor.com/help/what-are-performance-experiments/):

| Ajuste | Estado oficial | Acción |
|---|---|---|
| Inline Font Icons | Estable | **Activar** (evita cargar Font Awesome y eicons) |
| Optimized Image Loading | Estable | **Activar** (fetchpriority en la imagen LCP y lazy load debajo del pliegue) |
| Lazy Load Background Images | Estable | **Activar** |
| Optimized Gutenberg Loading | Estable | **Activar** |
| Element Caching | Experimental | Probar en staging |
| Optimized Markup / Improved Asset Loading | Activos por defecto en versiones recientes, según guías; **estado 2026 no confirmado** | Activar y revisar el CSS a medida [master-addons](https://master-addons.com/how-to-speed-up-elementor-websites/) |
| Google Fonts | Elegir "Load locally" [master-addons](https://master-addons.com/how-to-speed-up-elementor-websites/) | Usar 1–2 familias y solo los pesos necesarios. Desactivar las fuentes y colores por defecto de Elementor |
| Atomic (V4) | Por defecto en sitios nuevos | Úsalo para el maquetado; es más ligero [FAQ V4](https://elementor.com/products/website-builder/v4-faq/) |

#### Otros puntos
- **Imágenes:** usar WebP (o AVIF), subirlas ya a su tamaño (≤1600 px) y no aplicar lazy load a la imagen principal.
- **CDN:** Cloudflare Free, o QUIC.cloud si el hosting es LiteSpeed.
- **Plugins y widgets:** menos de 20 plugins y ningún pack de addons de Elementor si no hace falta.
- **Objetivo:** LCP < 2.5 s, INP < 200 ms y CLS < 0.1 en PageSpeed Insights (móvil).

#### Hosting

| Tipo | Ejemplos y precio aproximado | Nota |
|---|---|---|
| Compartido LiteSpeed (económico) | **Hostinger Business**: ~$2.99/mes de entrada y ~$16.99/mes al renovar; servidores LiteSpeed [websitesetup](https://websitesetup.org/?p=57739), [bearhost](https://bearhost.com/blogs/hostinger-review) | Suficiente para la Fase 1 |
| Compartido gestionado | **SiteGround GrowBig**: ~$4.99/mes el primer año y ~$24.99–29.99 al renovar [allaboutcookies](https://allaboutcookies.org/siteground-pricing) | Buen soporte, pero la renovación es cara |
| Cloud | **Cloudways**: ~$12–14/mes, sin subida al renovar | Más técnico |
| Gestionado premium | **Rocket.net** desde ~$30/mes; **Kinsta** desde ~$35/mes [websitesetup](https://websitesetup.org/wordpress-hosting-performance/) | Para la Fase 2–3, con más tráfico y pedidos |

Todos estos precios vienen de agregadores. **Hay que confirmarlos en el checkout.**

#### Cómo saber si el hosting actual sirve (checklist)
1. **Proveedor y servidor:** buscar el dominio en `whois`/`nslookup`, o mirar las cabeceras con DevTools → Red → Respuesta. `server: LiteSpeed` o `x-litespeed-cache` indican LiteSpeed; `server: nginx` o `apache` no.
2. **WP Admin → Herramientas → Salud del sitio → Información → Servidor:**
   - PHP **8.2 o superior**. WooCommerce recomienda 8.0+ y WP 7.0+ [wordpress.org](https://wordpress.org/plugins/woocommerce/).
   - `memory_limit` ≥ 256M.
   - `max_execution_time` ≥ 60.
   - HTTPS activo.
3. **Panel del hosting:** backups diarios con restauración, staging, SSL gratis, acceso SSH/SFTP y caché de servidor.
4. **TTFB:** < 600 ms en PageSpeed Insights con una página vacía de Elementor.
5. **Marca de agua:** preguntar al soporte si **Ghostscript** y `proc_open()` están disponibles, porque los necesita Smart PDF Watermarking.
6. **Señales de alarma:** PHP < 8.1, sin staging, sin backups o con un límite de "inodes/CPU" muy bajo. En ese caso, migrar a un plan LiteSpeed o gestionado.

---

### Cosas no verificadas o contradictorias
- **Elementor:** los precios de Pro no se veían en la página oficial (se usó un tercero con fecha 29/oct/2026). Las fuentes Custom Fonts no aparecen en ningún plan. Tampoco está claro qué funciones de Pro (Theme Builder, Woo, Loop) son ya "Atomic".
- **Plataformas y pasarelas:** no se verificaron en la web oficial los precios de SureCart Pro ni de Shopify. Tampoco la tarifa de Stripe Managed Payments ni la comisión extra de Stripe Billing con WooPayments (un tercero dice 1%).
- **Email:** no se confirmó en Brevo.com el precio Starter, ni si el "incentive email" de Kit sigue en el plan gratis.
- **Traducción:** falta confirmar cuántos idiomas trae la versión gratis de TranslatePress y el precio oficial de Polylang for WooCommerce.
- **Plugins sin precio verificado:** ShortPixel, EWWW, CookieYes, CusRev, Yoast, SEOPress, Search & Filter Pro, JetEngine y TaxJar.
- **Impuestos:** las fuentes no coinciden en la lista de estados ni en el número de estados que eliminaron el umbral de transacciones.

---

# Parte C · Marca, legal y seguridad


**Fecha de la investigación:** 10 de noviembre de 2026
**Alcance:** "Baby Tayo" (babytayo.com), marca de EE. UU. de manualidades y actividades para toddlers de 1 a 4 años, con sitio bilingüe. La fase 1 son PDFs; las fases 2 y 3 son kits, libros y juguetes.

> **Aviso:** esto es investigación, no asesoría legal. Las conclusiones sobre riesgo son orientativas. La decisión final, la búsqueda de *clearance* y cualquier solicitud ante la USPTO las debe revisar una abogada o un abogado de marcas en EE. UU.

---

### Resumen ejecutivo

| Tema | Hallazgo clave | Nivel de riesgo |
|---|---|---|
| Registros de ICONIX en EE. UU. | Los registros amplios de TAYO (clases 9, 16, 18, 21, 25, 28, 32) se **cancelaron en 2023** por no presentar la declaración de la Sección 8. Hoy solo está vivo **TAYO THE LITTLE BUS**, Reg. 7831314, en la **clase 21** (palillos). | Bajo en el registro, pero ver la fila siguiente |
| Uso real de ICONIX en EE. UU. | ICONIX distribuye **"Baby Tayo Songs"** en Prime Video (en inglés, 3 temporadas, contenido para bebés y toddlers), tiene un canal de YouTube de unos 12,6 M de suscriptores y vende juguetes Tayo en Walmart y eBay. Eso puede dar **derechos de *common law* (uso sin registro)** y una marca "famosa" para el mismo público: padres de niños pequeños. | **ALTO** |
| "Baby Tayo" en la USPTO | No hay ninguna solicitud ni registro con "BABY TAYO" (0 resultados en tmsearch). | Libre en el registro |
| Otros TAYO vivos | TAYOO! (Reg. 7297703, clase 28, *infant toys*), TATAYO (clase 28, carritos de juguete), TAIYO (Toyshock, clase 28, juguetes RC), TAYO (Tayo LLC, clase 35, abarrotes) y SAMA TAYO (clase 25, ropa). | Medio en la clase 28 |
| Redes sociales | El canal **@BabyTayo de YouTube ya existe**. **@babytayo** está ocupado en TikTok y en Pinterest. | Hay que usar variantes |
| COPPA | El sitio se dirige a padres, pero el tema (actividades para toddlers) y el diseño infantil pueden llevar a que la FTC lo trate como de "audiencia mixta". Las enmiendas a COPPA son obligatorias desde el 22/4/2026. | Medio y manejable |
| Seguridad (PDFs) | Los PDFs no son "productos" sujetos a la CPSC, pero las actividades sí tienen riesgos reales (asfixia, tóxicos). Conviene poner advertencias claras como diligencia y para reducir responsabilidad. | Medio |
| Fases 2 y 3 (físicos) | CPSIA: pruebas en un laboratorio aceptado por la CPSC, CPC, etiqueta de rastreo, ASTM F963-23 y, si se importa, **eFiling obligatorio desde el 8/7/2026**. Partes pequeñas **prohibidas** para menores de 3 años. | **ALTO** si no se planifica |

---

### 1. Conflictos de marca

#### 1.1 Qué consulté y cómo

- **USPTO Trademark Search (tmsearch.uspto.gov):** la interfaz es interactiva, pero pude consultar su API pública de búsqueda, la misma que usa la web, el 10/11/2026. Hice búsquedas por `tayo`, `*tayo*`, `"baby tayo"`, variantes fonéticas (`taio`, `taiyo`, `tiago`, `thiago`, `babytayo`) y por propietario `ICONIX`. Los resultados de esa API cubren solicitudes y registros vivos y muertos.
- **USPTO TSDR (tsdr.uspto.gov/statusview/sn…):** consulté el detalle de estado de los registros de ICONIX. Algunas solicitudes devolvieron HTTP 403 por límite de bots.
- **WIPO Global Brand Database / TMview:** **no verificado.** Son interfaces interactivas que no consulté. Los registros internacionales (Madrid) que designan EE. UU. sí aparecen en tmsearch con números de serie 79xxxxxx, y ninguno de ellos es de TAYO por ICONIX.
- **Amazon y Etsy:** bloquearon las consultas automáticas (Amazon devolvió una página vacía y Etsy un 403). **No verificado.** Más abajo explico cómo revisarlo a mano.

#### 1.2 Registros de ICONIX Co., Ltd. (Corea) en EE. UU.

| Marca | Serie / Registro | Estado | Clases | Notas | Fuente |
|---|---|---|---|---|---|
| **TAYO THE LITTLE BUS** (caracteres estándar) | SN 98406741 / **Reg. 7831314** (17/6/2025) | **VIVA** | **21** solamente ("Chopsticks; Training chopsticks") | Es la única marca TAYO viva de ICONIX en EE. UU. Primer uso en 2017. | [TSDR 98406741](https://tsdr.uspto.gov/statusview/sn98406741) · [Justia](https://trademark.justia.com/984/06/tayo-the-little-98406741.html) |
| TAYO THE LITTLE BUS 120 (logotipo con autobús azul) | SN 86565503 / Reg. 5196071 (2/5/2017) | **MUERTA**: cancelada el 17/11/2023 (Sección 8) | 9, 16, 18, 21, 25, 32 | La clase 16 cubría stickers, cuadernos, papel de origami, *sketch books*, crayones y *painting sets for children*. La clase 9 cubría DVDs, apps y publicaciones descargables. | [TSDR 86565503](https://tsdr.uspto.gov/statusview/sn86565503) |
| "꼬마버스 타요" (KKOMABEOSEU TAYO, en coreano, con logotipo) | SN 86565571 / Reg. 5078752 (8/11/2016) | **MUERTA**: cancelada el 19/5/2023 (Sección 8) | 9, 16, 18, 21, 25, **28**, 32 | La clase 28 incluía peluches, juguetes educativos y carritos de juguete. | [TSDR 86565571](https://tsdr.uspto.gov/statusview/sn86565571) |
| TITIPO TITIPO (*spin-off* de Tayo) | SN 87944536 / Reg. 6088127 | VIVA | 9, 16, 18, 21, 25, **28**, 32, **41**, 43 | Demuestra que ICONIX registra en EE. UU. las clases que nos importan para otros personajes y podría hacerlo con Tayo. | API de tmsearch (consulta del 10/11/2026) |
| PORORO (marca hermana) | Reg. 5055341 y 5055340 | VIVAS | 9, 16, 28, 41… | Igual que la anterior. | API de tmsearch |
| DECO DECO | SN 50114385 (2026) | Pendiente | 28 | ICONIX sigue presentando solicitudes en EE. UU. en 2026. | API de tmsearch |

**Interpretación:** en el **registro federal**, ICONIX **no tiene hoy ningún derecho vivo sobre "TAYO" en las clases 9, 16, 28, 35 ni 41**. Aun así, la ley de EE. UU. protege marcas **no registradas que se usan en el comercio** (Lanham Act §43(a), confusión y falsa designación de origen). Las pruebas de uso son estas:

- **"Baby Tayo Songs"**: serie de ICONIX Entertainment en **Prime Video**, en inglés, con 3 temporadas y episodios de 2022 como *"Peek-a-boo"*, *"One little finger"* o *"I love to take a bath"*. Está dirigida exactamente al público de toddlers y bebés. [Prime Video](https://www.primevideo.com/detail/0NGTHMMTXFZAUCIKB3EQ5SG0SF) · [Yidio](https://www.yidio.com/show/baby-tayo-songs)
- **YouTube**: el canal oficial de Tayo tiene unos 12,6 M de suscriptores y también hay canal en español ("Tayo El Pequeño Autobús", unos 4,26 M). Eso es especialmente relevante porque Baby Tayo es una marca bilingüe. [vidIQ: canal principal](https://vidiq.com/youtube-stats/channel/UC9CsZoTaHZqZjnNZv7v3T1g) · [vidIQ: español](https://vidiq.com/youtube-stats/channel/UCc_alYmt_LTSb5oOjF8Stjw) · [SponsorRadar](https://sponsorradar.com/channels/tayo)
- **Otros títulos en EE. UU.**: "Tayo's Kids Songs Collection", "Tayo Car Songs" y "Tayo's Sing Along Show". [Yidio](https://www.yidio.com/show/tayos-kids-songs-collection) · [Yidio](https://www.yidio.com/show/tayo-car-songs)
- **App "TAYO TV"** en la App Store, clasificada 4+. [App Store](https://apps.apple.com/at/app/tayo-tv/id1459621366)
- **Juguetes Tayo a la venta en EE. UU.**: Walmart, eBay y revendedores. No se pudo confirmar cuáles son licencias oficiales. [Walmart](https://www.walmart.com/c/kp/tayo) · [Walmart: Rogi](https://www.walmart.com/ip/TAYO-The-Little-Bus-Friends-ROGI/727683558) · [eBay](https://www.ebay.com/itm/313945570707)
- **Contexto de la franquicia**: es una serie surcoreana de ICONIX con EBS, en emisión desde 2010, con 7 temporadas y 182 episodios. Bandai lanzó juguetes en Japón en octubre de 2025. ICONIX y EBS crearon en 2024 una sociedad para una película. [Wikipedia](https://en.wikipedia.org/wiki/Tayo_the_Little_Bus) · [Korea Times](https://www.koreatimes.co.kr/www/nation/2024/12/113_155124.html)

**Hallazgo crítico:** "BABY TAYO" ya funciona en EE. UU. **como título de contenido de ICONIX dirigido a bebés y toddlers**. No es una marca registrada, pero un abogado probablemente lo verá como el mayor factor de riesgo. Además, ICONIX podría volver a presentar solicitudes para TAYO en cualquier momento. Ya lo hizo en 2024 para la clase 21 y en 2026 tiene una solicitud pendiente para DECO DECO en la clase 28.

#### 1.3 Otras marcas TAYO (o similares) en la USPTO

Solo listo las vivas o las relevantes. Todas vienen de la API de tmsearch, consultada el 10/11/2026.

| Marca | Serie / Registro | Titular | Clase | Productos o servicios | Relevancia |
|---|---|---|---|---|---|
| **TAYOO!** | 97727665 / Reg. 7297703 | Zhongwan (Shenzhen) Industry Co. | **28** | *Children's multiple activity toys; Infant toys; Plush toys; Toy building blocks*, juegos de mesa | **Alta para la fase 3 (juguetes).** Se pronuncia casi igual. [Justia](https://trademarks.justia.com/977/27/tayoo-97727665.html) |
| TATAYO | 88919303 / Reg. 6215978 | Tao Liu (China) | 28 | *Spinning tops; toy cars; toy masks*, artículos de ejercicio | Media para la fase 3 |
| TAIYO | 86149535 / Reg. 4813613 | Toyshock USA LLC | 28 | Vehículos de juguete y juguetes RC | Media-baja (sonido parecido) |
| TAYOVSZY / WATAYONIS / FOTAYOY / ANTAYOND / ITAYO | varios | vendedores chinos y otros | 28 | juguetes inflables, de arena, etc. | Baja (impresión distinta) |
| TAYO | 97065031 / Reg. 7101762 | Tayo, LLC (Nevada) | 29, 30, **35** | Gumbo, salsa, *online retail grocery store services* | Baja (abarrotes) |
| SAMA TAYO BY JEN+LEX | 97026293 / Reg. 6876237 | Sama Tayo LLC (CA) | 25 | Ropa | Baja para nosotros; relevante si habrá ropa |
| TAYOJR | 97135651 / Reg. 6760424 | Particular (EE. UU.) | 35, 41 | Fotografía | Baja |
| MIA & TIAGO | 98806191 / Reg. 8064926 | Weeva, Inc. | 16 | (impresos) | Baja; conviene revisarla si se usa "Thiago" |
| BABYBUS | 79337296 / 79337589 / 79337588 y otras | BabyBus Co. (China) | 9, 16, 28, 41 | Marca de contenido infantil en YouTube | Baja-media: es otra marca "Baby + vehículo" del mismo nicho y conviene diferenciarse visualmente |
| **BABY TAYO** | — | — | — | **No hay ninguna solicitud ni registro** | — |

**Registros concretos para que el abogado revise:**

1. Reg. **7831314**, TAYO THE LITTLE BUS (ICONIX, clase 21, viva).
2. Reg. **5196071** y **5078752** (ICONIX, canceladas en 2023). Sirven para saber qué cubrían y si ICONIX las puede reactivar o volver a presentar.
3. Reg. **6088127**, TITIPO TITIPO, y Reg. **5055341**, PORORO. Muestran el patrón de clases de ICONIX.
4. Reg. **7297703**, TAYOO! (clase 28, juguetes para bebés).
5. Reg. **6215978**, TATAYO, y Reg. **4813613**, TAIYO (clase 28).
6. Reg. **7101762**, TAYO (clase 35).
7. Uso no registrado: "Baby Tayo Songs" (Prime Video), los canales de YouTube de Tayo y la app TAYO TV.

#### 1.4 Evaluación orientativa de la probabilidad de confusión por clase

La USPTO y los tribunales aplican los **factores DuPont**: similitud de las marcas, relación entre productos, canales de venta, consumidores, fuerza o fama de la marca previa, etc. Esta evaluación no es jurídica.

| Clase | Qué cubriría a Baby Tayo | Riesgo frente al registro USPTO | Riesgo frente al uso real de ICONIX | Comentario |
|---|---|---|---|---|
| **9** (PDFs descargables, apps, video) | Actividades imprimibles descargables | Bajo (no hay TAYO vivo en la clase 9) | **Alto** | ICONIX distribuye videos "Baby Tayo Songs" y la app TAYO TV para el mismo público. |
| **16** (impresos, libros, stickers, láminas para colorear) | Libros impresos, cuadernos de actividades | Bajo | **Alto** | El registro cancelado de ICONIX cubría precisamente cuadernos, crayones y *painting sets for children*, y es probable que siga usando la marca en papelería. |
| **28** (juguetes, kits de manualidades como juguete) | Kits y juguetes | **Medio** (TAYOO! para *infant toys*, TATAYO) | **Alto** (juguetes Tayo en Walmart y eBay) | Es la clase de mayor riesgo. |
| **41** (educación y entretenimiento, contenido en línea no descargable, talleres) | Blog o videos educativos, clases | Bajo | **Alto** (YouTube y Prime Video) | — |
| **35** (tienda en línea) | *Online retail store services featuring craft kits, printables* | Bajo-medio (TAYO para abarrotes, otro sector) | Medio | — |

**Conclusión orientativa:** el registro federal está despejado para "BABY TAYO", pero el **riesgo comercial y de conflicto con ICONIX es alto**. "Tayo" es el elemento dominante y coincide con una franquicia infantil conocida, con canales grandes en inglés **y en español**, que además usa literalmente "Baby Tayo" para contenido de toddlers. Hay otros riesgos que no son jurídicos:

- **SEO**: las búsquedas de "baby tayo" llevarán a Tayo el autobús.
- **Bloqueos**: ICONIX puede usar Amazon Brand Registry o denuncias en YouTube y Meta.
- **Expectativa del público**: muchos padres pueden asumir que es un producto oficial de Tayo.

#### 1.5 Opciones de mitigación

1. **Búsqueda de *clearance* completa con un abogado de marcas.** Debe cubrir la base federal, las bases estatales, *common law* y web (por ejemplo, con Corsearch o CompuMark) y el uso de ICONIX. Además conviene una **opinión escrita sobre el riesgo**. Costo típico: unos cientos a pocos miles de USD; es una estimación propia que hay que cotizar.
2. **Nombre compuesto y distintivo** que reduzca el peso de "Tayo". Algunos ejemplos que hay que buscar antes de usarlos: "Tayo & Me Crafts", "Little Hands by Tayo", o un nombre principal distinto con la historia de Thiago y "Tayo" solo en el relato de la marca. Ojo: añadir "Crafts" o "Studio" no elimina el conflicto si "Tayo" sigue siendo lo dominante.
3. **No usar autobuses ni vehículos antropomórficos, ni la paleta azul y verde** del logotipo de Tayo. Usar un diseño de logotipo propio.
4. **Presentar la solicitud temprano** en las clases 9, 16 y 41, más la 35 y la 28 con *intent-to-use*, si el abogado lo aprueba. Así se fija una fecha de prioridad, aunque eso no protege contra derechos anteriores de *common law*. Tasa de la USPTO: **350 USD por clase** con el sistema de base desde el 18/1/2025. Es un dato conocido, pero conviene confirmarlo en uspto.gov.
5. **Plan B**: tener un nombre alternativo listo antes de invertir en empaques físicos.
6. **Cómo revisar a mano lo que no se pudo verificar:**
   - **WIPO Global Brand Database** (branddb.wipo.int): buscar "TAYO" con el filtro de titular "ICONIX" y las clases 9, 16, 28 y 41, y revisar las designaciones a EE. UU.
   - **TMview** (tmdn.org/tmview): buscar "TAYO" y "BABY TAYO" para ver la UE, Corea (KIPO) y otros territorios, por si hay expansión futura.
   - **tmsearch.uspto.gov**: buscar `TAYO` en Wordmark, con el filtro Status: Live, y revisar también las marcas de diseño del propietario "ICONIX".
   - **Amazon**: buscar "baby tayo" y "tayo" en Amazon.com y en Brand Registry.
   - **Etsy**: buscar "baby tayo" y "tayo crafts" y la tienda etsy.com/shop/babytayo.
   - **Registros estatales de marcas**, en particular California, Texas, Florida y Nueva York.

---

### 2. Disponibilidad de usuarios en redes sociales

Lo comprobé con consultas HTTP automatizadas el 10/11/2026. "Ocupado" significa que el perfil existe.

| Usuario | Instagram | TikTok | Pinterest | YouTube | Facebook | X |
|---|---|---|---|---|---|---|
| **babytayo** | No verificable (muro de login) | **OCUPADO**: cuenta personal "Shif'ah", unos 6,2 K seguidores, no relacionada | **OCUPADO**: "Tayo Adebisi (babytayo)" | **OCUPADO**: canal **"Baby Tayo" @BabyTayo** (ID UCTXsCwPrpBvjeLP96wk-eNg). No pude ver los videos ni a quién pertenece; revisar si es de ICONIX. | No verificable | Probablemente libre (devuelve 404 "User Profile Not Found") |
| **babytayo.co** | No verificable | Parece libre ("user not found", código 10221) | Parece libre ("User not found") | Parece libre (404). YouTube no admite puntos en el handle de la misma forma; verificarlo. | No verificable | Probablemente libre (404). **X no permite puntos en los usuarios.** |
| **hellobabytayo** | No verificable (429, límite de peticiones) | Parece libre | Parece libre | Parece libre (404) | No verificable | Probablemente libre |
| **babytayocrafts** | No verificable (429) | Parece libre | Parece libre | Parece libre (404) | No verificable (muro de login) | Probablemente libre |
| **babytayo_** | No verificable (429) | **OCUPADO**: cuenta "babytayo_", unos 670 seguidores | Parece libre | Parece libre (404) | No verificable | Probablemente libre (404) |

**Cautelas:** un 404 o un "not found" puede deberse también a una cuenta suspendida, desactivada o privada, o a un nombre reservado. La única prueba definitiva es intentar registrarlo.

**Cómo comprobarlo a mano:**

1. **Instagram**: en la app, entrar en Editar perfil > Nombre de usuario y escribir cada variante. Si sale un aviso de "no disponible", está tomado. También se puede abrir instagram.com/USUARIO en una ventana privada.
2. **TikTok**: Perfil > Editar perfil > Nombre de usuario.
3. **Pinterest**: crear una cuenta de empresa y probar en Configuración > Editar perfil > Nombre de usuario.
4. **YouTube**: en studio.youtube.com, ir a Personalización > Información básica > Handle. El sistema dice si está disponible.
5. **Facebook**: al crear la página, en Configuración > Nombre de usuario, lo valida al momento.
6. **X**: en Configuración > Tu cuenta > Información de la cuenta > Nombre de usuario.
7. Herramienta de apoyo: namecheckr.com o namechk.com. No son fiables al 100 %.

**Recomendación:** dado que @babytayo está ocupado en YouTube, TikTok y Pinterest, elegir **un solo usuario que esté libre en todas las redes**, por ejemplo **@hellobabytayo** o **@babytayocrafts**, y reservarlo hoy en las seis redes, aunque no se usen todas. Esperar a la decisión sobre la marca antes de invertir en contenido.

---

### 3. Páginas legales necesarias

#### 3.1 Política de privacidad (obligatoria en la práctica)

**Por qué:**

- California (CalOPPA) exige una política de privacidad visible a cualquier sitio comercial que recoja PII de residentes de California.
- La **CCPA/CPRA** solo aplica a partir de estos umbrales: **26.625.000 USD de ingresos brutos anuales** (ajuste en vigor desde el 1/1/2025, próximo ajuste el 1/1/2027), **o** datos de 100.000 o más consumidores u hogares de California, **o** 50 % o más de los ingresos por vender o compartir datos. [CPPA, ajuste de umbrales](https://www.cppa.ca.gov/regulations/cpi_adjustment.html) · [CPPA, anuncio](https://cppa.ca.gov/announcements/2024/20241217.html)
- Hoy hay **unos 20 estados con leyes integrales de privacidad en vigor y 23 promulgadas**. Varias tienen umbrales bajos o ninguno: por ejemplo, Texas y Nebraska aplican a casi cualquier negocio que no sea una "pequeña empresa" según la SBA. Esto último es un dato conocido que hay que verificar. [MultiState](https://www.multistate.us/insider/2026/2/4/all-of-the-comprehensive-privacy-laws-that-take-effect-in-2026) · [IAPP tracker](https://iapp.org/resources/article/us-state-privacy-legislation-tracker) · [Offlist (snapshot IAPP, abril de 2026)](https://www.offlist.me/us-state-privacy-bills-tracker)

**Qué debe incluir:**

- Qué datos se recogen: nombre, correo, dirección de envío, datos de pago (procesados por Stripe o Shopify), IP, cookies y datos de analítica.
- Para qué se usan, con quién se comparten (procesador de pagos, plataforma de email, analítica, píxeles publicitarios) y si hay "venta" o "compartir" con fines de publicidad conductual.
- Derechos del consumidor: acceso, eliminación, corrección y exclusión de venta, de compartir y de publicidad dirigida. Cómo ejercerlos (correo o formulario) y el proceso de verificación.
- Respeto de la **señal Global Privacy Control (GPC)**, que exigen California y varios estados más. Enlace "Your Privacy Choices / Do Not Sell or Share" si se usan píxeles de Meta, TikTok o Google Ads.
- Retención, seguridad, transferencias, fecha de actualización y contacto.
- **Sección sobre niños** (ver COPPA abajo).
- **Versión en español completa**, porque la audiencia es bilingüe. Indicar qué versión prevalece.

#### 3.2 COPPA: por qué importa aunque el sitio se dirija a padres

- COPPA aplica a operadores de sitios **dirigidos a menores de 13 años** o con **conocimiento real** de que recogen datos de menores de 13. Las **enmiendas de 2025** se publicaron el 22/4/2025, entraron en vigor el 23/6/2025 y son de **cumplimiento obligatorio desde el 22/4/2026**. Exigen, entre otras cosas, un programa escrito de seguridad, una política de retención y consentimiento separado para compartir con terceros. [Toy Association](https://toyassociation.org/PressRoom2/News/2026-News/updated-coppa-rule-requirements-take-effect-april-22.aspx) · [Hunton](https://www.hunton.com/privacy-and-cybersecurity-law-blog/coppa-rule-amendment-compliance-deadline-approaches) · [Finnegan](https://www.finnegan.com/en/insights/articles/coppas-amended-rule-is-now-in-full-effect-what-operators-need-to-know.html)
- **Por qué importa para Baby Tayo:** para decidir si un sitio está "dirigido a niños", la FTC mira el tema, el contenido visual, los personajes animados, la música, las actividades infantiles y la edad de los modelos. Una marca de actividades para toddlers, con colores infantiles, mascotas animadas o un niño en fotos, **puede parecer dirigida a niños** aunque el comprador sea el padre.
- **Medidas recomendadas:**
  1. Copy y diseño dirigidos explícitamente a adultos ("para padres y educadores").
  2. No crear áreas "para niños": ni juegos, ni formularios para que escriban los niños, ni "envía el dibujo de tu hijo" sin consentimiento.
  3. Cuenta, newsletter y compras **solo para mayores de 18 años**, indicado en los Términos.
  4. Si se piden **fotos de niños usando el producto** (UGC), hay que tratarlas como datos de menores: consentimiento expreso de los padres, no publicarlas sin permiso y nunca con nombre completo.
  5. No recoger el nombre ni la fecha de nacimiento del niño. Si se pide "edad del niño" para personalizar, guardar solo un rango de edad y verlo con el abogado.
  6. **YouTube:** los videos de actividades para toddlers probablemente deban marcarse como **"Made for Kids"** según la política de YouTube derivada del acuerdo FTC–Google de 2019. Eso desactiva los comentarios y los anuncios personalizados. Es un dato conocido que hay que confirmar en la ayuda de YouTube.
- La FTC emitió el 25/2/2026 una declaración de política sobre la verificación de edad en servicios de audiencia general o mixta. [Toy Association](https://toyassociation.org/PressRoom2/News/2026-News/updated-coppa-rule-requirements-take-effect-april-22.aspx)

#### 3.3 Términos y condiciones

Deben incluir:

- Quién opera el sitio (entidad legal, estado y contacto) y la elegibilidad (mayores de 18 años).
- Proceso de compra, precios, impuestos, pagos y errores de precio.
- **Propiedad intelectual**: todo el contenido es de Baby Tayo. Remisión a la licencia del PDF.
- **Asunción de riesgo y supervisión adulta**: las actividades requieren supervisión, el adulto evalúa si son adecuadas para su hijo y no hay garantía de resultados de desarrollo.
- Exención de garantías, limitación de responsabilidad e indemnidad.
- Ley aplicable y jurisdicción. Arbitraje o renuncia a demandas colectivas, solo si el abogado lo recomienda.
- Política de contenido de usuarios (reseñas, fotos), cumpliendo la **regla de la FTC sobre reseñas y testimonios falsos de 2024** (16 CFR 465): no se pueden comprar reseñas ni suprimir las negativas. Es un dato conocido que hay que verificar en ftc.gov.
- Modificaciones, terminación y aviso de DMCA (agente designado ante la Copyright Office si se aloja contenido de usuarios).
- Versión en español, indicando cuál prevalece.

#### 3.4 Licencia de uso del PDF (*End-User License*)

Debe incluir:

- **Uso personal y familiar**: imprimir copias ilimitadas para los niños del propio hogar.
- **Uso en aula o en casa de cuidado infantil**: elegir entre (a) una licencia "Classroom/Educator" separada, de precio mayor, para un solo docente y su grupo; o (b) permitirlo en la licencia básica para un solo docente. Prohibir compartirlo en el servidor de la escuela o del distrito sin licencia de sitio.
- **Prohibido**: revender o redistribuir el archivo (impreso o digital), subirlo a sitios como TpT o Etsy o a grupos de Facebook o Drive públicos, alterarlo y venderlo, usarlo en productos comerciales y usarlo para entrenar IA (opcional, pero cada vez más habitual).
- Atribución, marca de agua o nombre del comprador en el pie del PDF (opcional).
- El copyright sigue siendo de Baby Tayo; la compra es una licencia, no una venta del contenido.
- Aviso de seguridad en el propio PDF (ver la sección 4).
- Registrar en la **U.S. Copyright Office** las colecciones principales. Así se pueden reclamar daños legales y honorarios. Es una opción que hay que comentar con el abogado.

#### 3.5 Política de reembolsos

- **Digitales**: lo habitual es "sin reembolsos una vez descargado" con excepciones: archivo dañado o inaccesible, compra duplicada o producto que no corresponde a la descripción. En esos casos, ofrecer reemplazo o crédito. La política debe estar **visible antes de pagar**. Si un estado o una plataforma exige más (por ejemplo, las reglas de disputas de Stripe o PayPal), se aplica.
- **Físicos (fase 2 y siguientes)**: plazo (por ejemplo, 30 días), estado del producto (sin abrir, por higiene y seguridad infantil), quién paga el envío, productos dañados o defectuosos y **retiradas de productos (recalls)**: reembolso completo y aviso a la CPSC si corresponde.
- **Regla de la FTC sobre pedidos por correo o Internet (*Mail, Internet, or Telephone Order Merchandise Rule*)**: hay que enviar en el plazo anunciado o, si no se anuncia ninguno, en **30 días**. Si hay retraso, hay que avisar al cliente y ofrecer cancelación con reembolso rápido. [FTC Business Guide](https://ftc.gov/business-guidance/resources/business-guide-ftcs-mail-internet-or-telephone-order-merchandise-rule)

#### 3.6 Política y banner de cookies

- Listar las cookies necesarias, de analítica y de publicidad (Meta Pixel, TikTok Pixel, Google).
- En EE. UU. no hace falta *opt-in* en general, pero sí **opt-out de publicidad dirigida y respeto de GPC** en los estados con ley de privacidad. Si hay tráfico de la UE o el Reino Unido, se necesita *opt-in* (RGPD/ePrivacy).
- Banner bilingüe con un enlace a "Your Privacy Choices".

#### 3.7 Divulgación de afiliados (FTC), si aplica

- Si se recomiendan materiales con enlaces de Amazon Associates u otros (tijeras, pintura, etc.), las **Endorsement Guides de la FTC (16 CFR 255, revisadas en 2023)** exigen una divulgación **"clear and conspicuous"**: difícil de pasar por alto, **cerca del enlace** y no escondida en el pie de página ni solo en los Términos. Ejemplo: *"We earn a commission if you buy through these links"* o *"Ganamos una comisión si compras a través de estos enlaces"*. [Manatt sobre las Guides 2023](https://www.manatt.com/insights/newsletters/advertising-law/an-in-depth-look-at-the-ftcs-updates-2) · [Gordon Law](https://gordonlaw.com/learn/ftc-endorsement-guidelines/)
- Amazon Associates exige además su propia frase: "As an Amazon Associate I earn from qualifying purchases".
- Si se envían productos gratis a influencers, ellos deben poner #ad. Las colaboraciones pagadas con niños influencers tienen implicaciones adicionales (ver la sección 5).

#### 3.8 Accesibilidad (ADA)

- El Título III de la ADA no tiene un estándar web explícito para empresas privadas, pero el DOJ y los tribunales consideran que los sitios de comercio están cubiertos y usan **WCAG 2.1 AA** como referencia de hecho. **No hay exención para pequeñas empresas.** Las demandas sobre sitios web crecieron mucho en 2025, con unos 3.100 a 3.900 casos según la fuente. [Level Access](https://www.levelaccess.com/blog/web-accessibility-lawsuits) · [Clym](https://www.clym.io/blog/the-ada-deadline-small-businesses-dont-know-is-coming)
- **No conviene confiar en "overlays" o widgets de accesibilidad**: la FTC sancionó a accesiBe con **1 millón de USD** (orden final en abril de 2025) por decir falsamente que su widget hacía los sitios conformes con WCAG. [TechCrunch](https://techcrunch.com/2025/01/03/ftc-orders-ai-accessibility-startup-accessibe-to-pay-1m-for-misleading-advertising) · [JD Supra](https://jdsupra.com/legalnews/ftc-targets-accessibility-overlays-5593127)
- **Qué hacer**:
  - Usar un tema accesible, texto alternativo en las imágenes, contraste suficiente, navegación con teclado, formularios con etiquetas, subtítulos en los videos y el atributo `lang` correcto en las páginas en español.
  - **PDFs accesibles**: etiquetados y con texto real en las instrucciones; las láminas para colorear son visuales por naturaleza.
  - Publicar una **declaración de accesibilidad** con un contacto para pedir ayuda.

#### 3.9 Otras páginas o avisos útiles

- **Aviso de seguridad** (*Safety Information*), una página propia con el texto de la sección 4.
- **Contacto e información de la empresa.**
- Si hay suscripciones o membresías: leyes de renovación automática, como la California Automatic Renewal Law (consentimiento afirmativo y cancelación en línea fácil). No lo verifiqué en esta investigación; conviene consultarlo si se ofrece un "club mensual".

---

### 4. Seguridad de productos infantiles

#### 4.1 Marco legal según la fase

- **Fase 1 (PDFs):** un PDF descargable **no es un "consumer product" físico** sujeto a la CPSC. Las advertencias no son obligatorias por ley federal, pero son **diligencia razonable** y reducen el riesgo de responsabilidad por instrucciones peligrosas. Las actividades para niños de 1 a 3 años con materiales pequeños son el mayor riesgo.
- **Fases 2 y 3 (kits, libros, juguetes):** son "children's products" para menores de 12 años y aplica la CPSIA completa (ver 4.4).

#### 4.2 Reglas federales clave sobre asfixia (referencia y para la fase 2 y siguientes)

- **16 CFR 1501**: **prohíbe** juguetes y artículos destinados a **menores de 3 años** que sean o contengan **partes pequeñas**, es decir, piezas que caben en el cilindro de prueba de unos 3,17 cm de diámetro. Hay **excepciones** para libros y artículos de papel, crayones, tiza, lápices, plastilina o masa de modelar, pinturas de dedos, acuarelas y sets de pintura, globos, etc. [CPSC Small Parts FAQ](https://www.cpsc.gov/FAQ/Small-Parts) · [CPSC Business Guidance](https://www.cpsc.gov/Business--Manufacturing/Business-Education/Business-Guidance/Small-Parts-For-Toys-And-Childrens-Products)
  - **Consecuencia práctica:** un **kit físico para niños de 1 a 3 años no puede incluir cuentas, pompones pequeños, ojos móviles, botones, etc.** Si se incluyen, el kit tiene que estar diseñado y etiquetado para **3 años o más**.
- **16 CFR 1500.19**: obliga a poner advertencias en juguetes y juegos para niños de **3 a 6 años** con partes pequeñas, en **globos de látex** (cualquier producto que los contenga), **pelotas pequeñas** (de 1,75" o menos) y **canicas**. El texto debe estar **en inglés**, en un bloque, con la palabra de señal "WARNING" y el triángulo con signo de exclamación. [CPSC Small Parts & Choking Hazard Labeling FAQs](https://cpsc.gov/FAQ/Small-Parts-and-Choking-Hazard-Labeling-FAQs) · [eCFR 16 CFR 1500.19](https://www.ecfr.gov/current/title-16/chapter-II/subchapter-C/part-1500/section-1500.19)
- **Textos exactos** según la [CPSC, publicación 282](https://www.cpsc.gov/s3fs-public/282.pdf), precedidos del triángulo y de "WARNING:":
  - Partes pequeñas: **"CHOKING HAZARD -- Small parts. Not for children under 3 yrs."**
  - Globos: **"CHOKING HAZARD -- Children under 8 yrs. can choke or suffocate on uninflated or broken balloons. Adult supervision required. Keep uninflated balloons from children. Discard broken balloons at once."**
  - Pelota pequeña: **"CHOKING HAZARD -- This toy is a small ball. Not for children under 3 yrs."**
  - Canica: **"CHOKING HAZARD -- This toy is a marble. Not for children under 3 yrs."**
- **16 CFR 1500.20 y CPSIA §105**: la advertencia también debe aparecer en **anuncios de Internet y catálogos** que permitan comprar directamente, es decir, en la **página de producto de la tienda** para los kits físicos. [eCFR 1500.20](https://www.ecfr.gov/current/title-16/chapter-II/subchapter-C/part-1500/section-1500.20)
- **Materiales de arte (LHAMA, 16 CFR 1500.14(b)(8))**: los materiales de arte, como pinturas, crayones, pegamento, plastilina y marcadores, deben estar evaluados por un toxicólogo y llevar **"Conforms to ASTM D-4236"** junto con un teléfono de EE. UU. Si son para menores de 12 años, también necesitan **pruebas CPSIA y CPC**. [CPSC Art Materials](https://www.cpsc.gov/old/Business--Manufacturing/Business-Education/Business-Guidance/Art-Materials) · [CPSC FAQ](https://www.cpsc.gov/FAQ/art-materials) · [Eurofins](https://www.eurofins.com/en/consumer-product-testing/softlines-hardlines/news-articles/safe-creative-play-navigating-compliance-with-lhama-for-art-materials/)
- **Sello AP (ACMI)**: es un programa voluntario del Art & Creative Materials Institute que certifica productos "no tóxicos" tras una evaluación toxicológica. Es buena práctica **recomendar en los PDFs materiales con sello AP**. [ACMI](https://acmiart.org/regulations)
- **Water beads (bolitas de gel)**: la CPSC aprobó en diciembre de 2025 una norma de seguridad específica. Lo prudente es **no usarlas nunca** en actividades para toddlers. [NIST SIBR](https://sibr.nist.gov/record/safety-standard-toys-requirements-water-beads-0)

#### 4.3 Texto recomendado para el sitio y los PDFs

Es una propuesta para que la revise el abogado. En los PDFs, poner un **bloque fijo en la página 1** y **advertencias específicas junto a cada actividad** que use materiales de riesgo.

**A) Aviso general (PDF y página de Seguridad)**

> **EN — Safety first.** These activities are designed for children ages 1–4 **with constant, hands-on adult supervision**. An adult should read all instructions, prepare all materials, and decide whether each activity is appropriate for their child's age, development, and any allergies or sensitivities. Never leave a child alone with craft materials. Choose non-toxic, age-appropriate supplies (look for "Conforms to ASTM D-4236" and the ACMI "AP" seal). Store supplies out of reach after use. Baby Tayo is not responsible for injuries resulting from use of materials or failure to supervise.

> **ES — La seguridad primero.** Estas actividades están pensadas para niños de 1 a 4 años **con supervisión constante y cercana de un adulto**. Un adulto debe leer todas las instrucciones, preparar los materiales y decidir si cada actividad es adecuada para la edad, el desarrollo y las posibles alergias o sensibilidades de su hijo. Nunca deje a un niño solo con materiales de manualidades. Use materiales no tóxicos y adecuados a su edad (busque "Conforms to ASTM D-4236" y el sello "AP" de ACMI). Guarde los materiales fuera de su alcance después de usarlos. Baby Tayo no se responsabiliza de lesiones derivadas del uso de materiales o de la falta de supervisión.

**B) Asfixia por piezas pequeñas** (pompones, cuentas, botones, ojos móviles, frijoles, pasta seca, tapas, piedras, etc.). Va junto al icono ⚠ en cada actividad que los use.

> **EN — ⚠ WARNING: CHOKING HAZARD — Small parts.** Not for children under 3 yrs. without direct adult supervision. Small items can block a child's airway. Count pieces before and after the activity.

> **ES — ⚠ ADVERTENCIA: PELIGRO DE ASFIXIA — Piezas pequeñas.** No apto para menores de 3 años sin supervisión directa de un adulto. Los objetos pequeños pueden bloquear las vías respiratorias del niño. Cuente las piezas antes y después de la actividad.

*Nota:* en un PDF (fase 1), se puede añadir "without direct adult supervision", porque el PDF no es un juguete regulado. En un **kit físico (fase 2)** el texto debe ser **exactamente** el de 16 CFR 1500.19, sin cambios, y el producto **no puede** destinarse a menores de 3 años si contiene partes pequeñas.

**C) Globos**

> **EN — ⚠ WARNING: CHOKING HAZARD — Children under 8 yrs. can choke or suffocate on uninflated or broken balloons. Adult supervision required. Keep uninflated balloons from children. Discard broken balloons at once.**

> **ES — ⚠ ADVERTENCIA: PELIGRO DE ASFIXIA — Los niños menores de 8 años pueden asfixiarse con globos desinflados o rotos. Se requiere supervisión de un adulto. Mantenga los globos desinflados lejos de los niños. Deseche de inmediato los globos rotos.**

Recomendación: evitar globos en actividades para niños de 1 a 4 años y, si se usan, que solo los manipule el adulto.

**D) Tijeras y herramientas**

> **EN —** Scissors, hole punches, needles, and hot-glue guns are **for adult use only**. Pre-cut all pieces before inviting your child to join.
> **ES —** Las tijeras, perforadoras, agujas y pistolas de silicona caliente son **solo para uso del adulto**. Recorte todas las piezas antes de invitar a su hijo a participar.

**E) Pintura, masa, pegamento y materiales que el niño pueda llevarse a la boca**

> **EN —** Toddlers explore with their mouths. Use only non-toxic, washable paints and glues labeled for children ("Conforms to ASTM D-4236", AP seal). Homemade dough contains high amounts of salt, which can be harmful if eaten in quantity — do not allow children to eat it. Wash hands after the activity.
> **ES —** Los niños pequeños exploran con la boca. Use solo pinturas y pegamentos no tóxicos y lavables, etiquetados para niños ("Conforms to ASTM D-4236", sello AP). La masa casera contiene mucha sal, que puede ser dañina si se come en cantidad: no permita que los niños la coman. Lávense las manos después de la actividad.

**F) Alergias y alimentos** (actividades sensoriales con arroz, pasta, harina, maní, gluten, látex)

> **EN —** Some activities use food items or materials (e.g., flour, pasta, rice, nuts, latex) that may cause allergic reactions. Check ingredients and your child's allergies before starting. Uncooked rice, beans, and pasta are choking hazards.
> **ES —** Algunas actividades usan alimentos o materiales (por ejemplo, harina, pasta, arroz, frutos secos o látex) que pueden causar reacciones alérgicas. Revise los ingredientes y las alergias de su hijo antes de empezar. El arroz, los frijoles y la pasta crudos presentan peligro de asfixia.

**G) Cuerdas, cintas, imanes y pilas de botón**

> **EN —** Strings, ribbons, and yarn longer than 12 in. (30 cm) can pose a strangulation hazard — supervise closely and remove after play. Never use small magnets or button/coin batteries in toddler activities; if swallowed they can cause serious internal injury — seek medical help immediately.
> **ES —** Las cuerdas, cintas y lanas de más de 30 cm (12 in) pueden presentar peligro de estrangulamiento: supervise de cerca y retírelas después del juego. Nunca use imanes pequeños ni pilas de botón en actividades para niños pequeños; si se tragan pueden causar lesiones internas graves: busque atención médica de inmediato.

Nota: el límite de cuerdas y la información sobre imanes y pilas de botón se basan en ASTM F963 y en la **Ley de Reese de 2022 (16 CFR 1263)**. Son datos conocidos que hay que verificar si se aplican a productos físicos.

**H) Emergencias** (EE. UU.)

> **EN —** In case of ingestion of a non-food material call Poison Control: **1-800-222-1222**. In an emergency call **911**.
> **ES —** En caso de ingestión de un material no comestible, llame a Control de Envenenamientos: **1-800-222-1222** (atención en español). En una emergencia, llame al **911**.

#### 4.4 Fases 2 y 3: obligaciones CPSIA para kits, libros y juguetes

| Obligación | Qué implica | Fuente |
|---|---|---|
| **Norma de juguetes ASTM F963-23** (16 CFR 1250) | Es obligatoria para juguetes **fabricados desde el 20/4/2024**. Cubre requisitos mecánicos y físicos (bordes, puntas, partes pequeñas, cuerdas, imanes), inflamabilidad, metales pesados en el recubrimiento, etc. | [Federal Register 2024-00741](https://www.govinfo.gov/content/pkg/FR-2024-01-18/html/2024-00741.htm) · [Toy Association](https://toyassociation.org/PressRoom2/News/2024_News/cpsc-approves-updated-federal-toy-safety-standard-effective-april-20.aspx) |
| **Plomo** | Sustrato de **100 ppm** o menos y pintura o recubrimiento de **90 ppm** o menos. | Dato conocido de la CPSIA; verificar en [CPSC](https://www.cpsc.gov) |
| **Ftalatos** (16 CFR 1307) | 8 ftalatos limitados a 0,1 % en juguetes y artículos de cuidado infantil con plástico accesible. | Dato conocido; verificar |
| **Pruebas en un laboratorio aceptado por la CPSC** | Son obligatorias para los productos infantiles. Lista de laboratorios en cpsc.gov/labsearch. | [CPSC Art Materials FAQ](https://www.cpsc.gov/FAQ/art-materials) |
| **Children's Product Certificate (CPC)** | La emite el fabricante o importador y cita cada regla aplicable, el laboratorio y las fechas. | [CPSC](https://www.cpsc.gov/FAQ/art-materials) |
| **eFiling del CPC (importación)** | **Obligatorio desde el 8/7/2026** para productos regulados importados. Los datos del certificado se transmiten a CBP/ACE en la entrada, **sin mínimo de valor**. Las zonas francas siguen el 8/1/2027. | [Foley](https://www.foley.com/?p=120147) · [FedEx (CSMS #68290359)](https://www.fedex.com/content/dam/fedex/us-united-states/International/CPSC_to_implement_mandatory_electronic_filing_requirements_in_ACE_on_July_8_2026.pdf) · [C.H. Robinson](https://www.chrobinson.com/pl-pl/resources/insights-and-advisories/client-advisories/2026q1/03-11-2026-client-advisory-upcoming-cpsc-efiling-requirements-key-dates-importer-responsibilities/) |
| **Etiqueta de rastreo** (*tracking label*, CPSIA §103) | Marcas permanentes en el producto **y** el empaque, en la medida de lo posible: fabricante o marca, lugar y fecha de producción, número de lote o cohorte. | [CPSC Tracking Label FAQ](https://www.cpsc.gov/FAQ/Tracking-Label) |
| **Advertencias de asfixia** en el empaque **y en la página web** | 16 CFR 1500.19 y 1500.20. | ver 4.2 |
| **Materiales de arte en el kit** | LHAMA: ASTM D-4236, revisión toxicológica y etiqueta, además de CPSIA para menores de 12 años. | ver 4.2 |
| **Libros impresos** | Los libros de papel corrientes para niños están **exentos de las pruebas de plomo por terceros** si son "ordinary books", pero **no** los libros con elementos de juguete (plástico, tela, piezas). Es un dato conocido que hay que verificar en la guía de la CPSC sobre libros. | verificar en [cpsc.gov](https://www.cpsc.gov) |
| **Registro de pequeño fabricante (*Small Batch*)** | Alivio parcial de pruebas (solo los requisitos del "Grupo B") si los ingresos son de **1.480.296 USD o menos (2026)** y hay **7.500 unidades o menos**. **No** exime del plomo en pintura ni de ASTM F963 en sus partes del "Grupo A". Hay que renovarlo cada año. | [CPSC Small Batch FAQ](https://cpsc.gov/FAQ/Small-Batch) · [SaferProducts FAQ](https://www.saferproducts.gov/FAQs/FrequentlyAskedQuestions6) · [Registro](https://saferproducts.gov/BusinessRegister/SmallBatchManufacturer) |
| **Marketplaces** | Amazon y otros exigen CPC e informes de laboratorio para listar juguetes. | Dato conocido |
| **Estados** | California Prop 65, leyes estatales de químicos en productos infantiles (Washington, Vermont, Maine, Oregón y otras) y prohibiciones de PFAS. | Verificar con el laboratorio o el abogado |

**Costos aproximados** (orientativos, de fuentes de proveedores; hay que cotizar con un laboratorio):

- Pruebas iniciales por SKU sencillo: **400 a 1.800 USD**. ASTM F963 mecánico y físico: 400 a 1.200 USD por SKU. Plomo: 150 a 400 USD **por material o color**. Ftalatos: 200 a 500 USD por componente plástico. [ComplianceGate](https://www.compliancegate.com/cpsia-product-lab-testing/) · [Alibaba Seller Blog 2026](https://seller.alibaba.com/blogs/2026/southeast-asia/baby-safety/cpc-certification-us-compliance-guide-alibaba-b2b)
- Kits con muchos materiales o colores, o juguetes complejos: **2.000 a 8.000 USD o más por SKU**. Lo que más encarece es la cantidad de materiales y colores.
- Además: revisión toxicológica LHAMA por producto de arte, si se fabrica uno propio (cotizar), seguro de responsabilidad civil de producto (cotizar) y nuevas pruebas cuando cambie el material o el proveedor, o de forma periódica.
- **Estrategia para ahorrar**: usar componentes ya certificados (crayones y pinturas con su propio CPC y ASTM D-4236) y pedir al proveedor los CPC y los informes. Pocos colores y pocos materiales por kit. Kits **para 3 años o más** si llevan piezas pequeñas.

---

### 5. Privacidad de Thiago (menor en la marca)

#### 5.1 Buenas prácticas recomendadas

1. **Solo manos y detalles**: manos, pies, espalda o perfil desenfocado. **Nunca la cara** en fotos de producto. Así se evita el reconocimiento facial y el uso indebido de la imagen.
2. **Nombre**: usar solo "Tayo" o "T." como apodo de marca. **Nunca** el nombre completo, los apellidos, la fecha de nacimiento ni el cumpleaños exacto.
3. **Metadatos EXIF**: desactivar la geolocalización de la cámara y **borrar los EXIF** antes de publicar. En iPhone, en Compartir > Opciones > desactivar "Ubicación". En computadora, usar ExifTool o exportar sin metadatos. No hay que confiar en que la red los quite: unas plataformas lo hacen y otras no, y pueden guardar una copia. [Allstate Identity Protection](https://allstateidentityprotection.com/business/content-hub/how-to-help-your-employees-keep-their-kids-safe-online) · [Pixevety](https://pixevety.com/whats-in-a-photo-and-the-dangers-of-sharing-online/) · [The Citizen](https://www.citizen.co.za/kempton-express/uncategorized/2022/07/31/how-to-share-images-of-your-child-safely-on-social-media/)
4. **Fondo neutro**: sin ventanas a la calle, número de casa, coche o placa, uniforme o logotipo de guardería o escuela, ni camisetas de equipos locales. El NCMEC advierte de que estos detalles se usan para localizar a niños. [Allstate](https://allstateidentityprotection.com/business/content-hub/how-to-help-your-employees-keep-their-kids-safe-online)
5. **Nunca** mostrar ropa interior, la hora del baño, desnudez ni momentos íntimos o vergonzosos. Es una recomendación de la presentación de Keith y Steinberg en la AAP. [NPR/KPBS](https://www.kpbs.org/news/2016/10/27/do-parents-invade-childrens-privacy-when-they) · [CBS News](https://www.cbsnews.com/news/pediatricians-caution-posting-about-kids-online-security-privacy)
6. **Publicar con retraso**: no en tiempo real ni con ubicación ("hoy en el parque X").
7. **Rutinas y lugares**: no revelar horarios, el nombre de la guardería ni el barrio.
8. **Comentarios y mensajes**: moderar, desactivar los comentarios en publicaciones con el niño si hace falta y bloquear las cuentas sospechosas. En YouTube, el contenido "Made for Kids" ya desactiva los comentarios.
9. **Dar voz al niño a medida que crece**: Steinberg propone darle poder de veto desde los 4 años aproximadamente. Conviene planificar que en el futuro Thiago pueda pedir que se retire el contenido. [KPBS](https://www.kpbs.org/news/2016/10/27/do-parents-invade-childrens-privacy-when-they) · [Children and Screens](https://www.childrenandscreens.org/learn-explore/research/what-is-sharenting/)
10. **Separar la marca del niño**: "Tayo" puede ser la historia de la marca sin que la marca dependa de la imagen de Thiago. Se pueden usar ilustraciones o un personaje dibujado en lugar de fotos reales.
11. **Fotos de otros niños** (clientes o amigos): pedir **permiso escrito** de los padres y aplicar las mismas reglas.
12. **Activos de la cuenta**: activar autenticación en dos pasos en todas las redes y usar un correo de la marca, no el personal.

#### 5.2 Leyes sobre "niños influencers" (si el contenido se monetiza)

- **California SB 764** (vigente desde el 1/1/2025): si un menor aparece en **al menos el 30 %** del contenido monetizado de un *vlogger*, este debe reservar una parte proporcional de los ingresos (citada como **hasta el 65 %**) en un **fideicomiso** para el niño. Hay un proyecto adicional, **SB 1247**, en trámite en 2026, sobre el derecho a borrar ese contenido a los 18 años. [NBC News](https://www.nbcnews.com/news/california-passes-law-protect-financial-security-child-influencers-rcna172928) · [Davis+Gilbert](https://www.dglaw.com/californias-new-laws-will-change-the-way-marketers-engage-child-influencers/) · [Análisis SB 764 del Senado de CA](https://sjud.senate.ca.gov/sites/sjud.senate.ca.gov/files/sb_764_padilla_sjud_analysis.pdf)
- **Illinois** tiene una ley similar desde 2024 y fue el modelo de California. Minnesota y Utah aparecen citados en fuentes secundarias poco fiables, así que **hay que verificarlos**. [Sen. Koehler (IL)](https://senatordavekoehler.com/news/28-press-releases/506-koehler-celebrates-nationwide-wins-in-child-influencer-legislation) · [Romano Law (Utah)](https://www.romanolaw.com/utah-passes-landmark-law-to-protect-child-influencers/)
- **Implicación:** si Thiago aparece con frecuencia en contenido monetizado y la fundadora vive en uno de esos estados, puede haber obligaciones de llevar registros y abrir un fideicomiso. Mostrar **solo manos** y en **menos del 30 %** del contenido reduce ese riesgo, pero hay que confirmarlo con el abogado según el estado de residencia.

---

### 6. Recomendaciones priorizadas

1. **Antes de invertir más en el nombre**: encargar una *clearance search* completa y una opinión escrita a un abogado de marcas, centrada en el uso de ICONIX de "Baby Tayo Songs" y TAYO en EE. UU. (inglés y español). Tener **un plan B de nombre**.
2. Si el abogado da luz verde: **presentar la solicitud** en las clases 9, 16 y 41 (más la 35, y la 28 con *intent-to-use*) con un logotipo propio sin autobuses. Vigilar las nuevas solicitudes de ICONIX.
3. **Reservar hoy un usuario uniforme** que esté libre en todas las redes (por ejemplo, @hellobabytayo o @babytayocrafts). @babytayo ya está tomado en YouTube, TikTok y Pinterest.
4. **Paquete legal mínimo para el lanzamiento**: privacidad (con GPC y sección de niños), términos, licencia del PDF, reembolsos, cookies, declaración de accesibilidad y página de seguridad, todo en EN y ES. Para empezar se puede usar un generador como Termly o iubenda, pero un abogado debe revisarlo.
5. **Bloque de seguridad en cada PDF** e iconos de advertencia por actividad. Evitar globos, imanes, pilas de botón y water beads en actividades para niños de 1 a 3 años.
6. **Plan de la fase 2**: presupuestar las pruebas CPSIA (de 400 a varios miles de USD por SKU), CPC, eFiling si se importa, etiquetas de rastreo y seguro de responsabilidad civil. Kits con piezas pequeñas, solo para 3 años o más.
7. **Thiago**: solo manos, sin EXIF, sin nombre completo, sin escuela ni ubicación. Pensar en un personaje ilustrado como imagen de la marca.

---

### 7. Qué no pude verificar y cómo hacerlo

| Elemento | Motivo | Cómo verificarlo |
|---|---|---|
| WIPO Global Brand Database / TMview | Interfaz interactiva | branddb.wipo.int y tmdn.org/tmview: buscar "TAYO" y "BABY TAYO", filtrar por las clases 9, 16, 28 y 41 y el titular ICONIX |
| Detalle completo en TSDR de algunos registros | Límite de bots (403) | tsdr.uspto.gov e introducir el número de serie |
| Amazon y Etsy | Bloqueo de bots | Buscar a mano "baby tayo", "tayo crafts" y "tayo printable" |
| Instagram, Facebook | Muro de login o límite de peticiones (429) | Probar el usuario en la app (ver sección 2) |
| Dueño y contenido del canal de YouTube @BabyTayo | No se cargaron los videos | Abrir youtube.com/@BabyTayo y mirar la pestaña "Acerca de" |
| Texto vigente de 16 CFR 1500.19 | En eCFR las advertencias son imágenes; el texto citado viene de la publicación 282 de la CPSC | Confirmar en ecfr.gov o con el laboratorio |
| Leyes de niños influencers fuera de CA e IL | Fuentes secundarias poco fiables | Revisar las webs legislativas del estado de residencia |
| Tasa de la USPTO de 350 USD por clase, regla 16 CFR 465, exención de libros de la CPSC | Datos conocidos que no recomprobé hoy | uspto.gov/fees, ftc.gov, cpsc.gov |

---

# Parte D · Crecimiento


*Investigación hecha el 10 de noviembre de 2026. Cada dato lleva su URL. Muchas fuentes 2026 son blogs de terceros; cuando un dato no viene de la fuente oficial, se indica "(secundaria)". **No se incluyen volúmenes de búsqueda inventados**: el potencial de las palabras clave se da en términos relativos, junto con el método para validarlo.*

---

### 0. Resumen ejecutivo

1. **Contexto de demanda.** El primer *Parenting Trend Report 2026* de Pinterest reporta "screen free activities" +200 %, "sensory play" +1070 %, "art and craft activities" +330 % y "educational activities for kids" +280 %, todo interanual ([CTV News](https://www.ctvnews.ca/lifestyle/article/pinterest-search-trends-reveal-parents-push-for-offline-and-experience-rich-parenting/); [Pinterest Business Community](https://community.pinterest.biz/t/introducing-the-pinterest-parenting-trend-report-2026/43396)). Baby Tayo entra en un nicho que está creciendo dentro de Pinterest.
2. **Hueco en español.** En español, quienes dominan son portales generalistas: Guiainfantil, Consumer/Eroski, Educación 3.0 y Lifeder. Son mayoritariamente de España, organizan el contenido "por edades" de forma amplia y casi nada se centra en niños de 1–3 años ni en familias hispanas de EE. UU. (fiestas como Thanksgiving o el 4 de julio, junto con Día de Muertos y Las Posadas). En la búsqueda no apareció ningún sitio de nicho "toddler" en español con biblioteca filtrable ([Guiainfantil por edades](https://www.guiainfantil.com/articulos/ocio/manualidades/manualidades-para-ninos-por-edades); [Educación 3.0](https://www.educaciontrespuntocero.com/recursos/manualidades-para-infantil-y-primaria/); [Consumer](https://www.consumer.es/bebe/razones-por-las-que-es-importante-hacer-manualidades-con-los-ninos.html)). Los sitios bilingües EE. UU. que sí existen (Spanish Mama, Mommy Maestra) se dirigen sobre todo a la enseñanza del español a niños más grandes ([Spanish Mama](https://spanishmama.com/category/spanish-resources/free-downloads-for-teaching-spanish/); [Mommy Maestra](https://mommymaestra.com/2013)).
3. **Rich results.** Google retiró los rich results de FAQ el 7 de mayo de 2026 y HowTo desde 2023. Product, Review/AggregateRating, Article y Breadcrumb siguen activos. Conviene implementar Product + Offer + AggregateRating en los PDFs.
4. **Pinterest.** Es el canal número 1. Los Rich Pins (Article/Product/Recipe) siguen vigentes y se activan con Open Graph/Schema. Los Idea Pins ya no existen como formato aparte (desde septiembre de 2025 son Pins de video). Tamaño recomendado: 1000×1500 (2:3).
5. **Embudo.** PDF gratis → 5–7 emails → tripwire de $5–9 → bundle de $15–29. En Etsy se ven precios que van de $1–5 (megabundles muy rebajados) hasta $45–55 (bundles grandes). Etsy sirve como canal de descubrimiento secundario, con márgenes de ~10–11 % en comisiones sin Offsite Ads.

---

### 1. SEO

#### 1.1 Estado de los rich results (noviembre 2026)

| Tipo | Estado | Qué hacer en Baby Tayo | Fuente |
|---|---|---|---|
| **HowTo** | Deprecado (rich result retirado en 2023, primero en móvil y luego del todo) | No esperar ningún rich result. Mantener el marcado HowTo es opcional e inocuo, porque Schema.org lo sigue aceptando. Es más útil escribir pasos numerados en HTML limpio | [PPC Land](https://ppc.land/google-kills-faq-rich-results-what-seos-saw-coming-since-2019/); [Search Engine Journal](https://www.searchenginejournal.com/google-drops-faq-rich-results/574429/) |
| **FAQ** | Rich result **retirado el 7 de mayo de 2026** en todos los idiomas y países. Soporte en Search Console y Rich Results Test eliminado en junio de 2026, y en la API en agosto de 2026 | Escribir FAQs visibles en la página (sirven a usuarios y a respuestas de IA). FAQPage puede quedarse sin penalización, pero no genera fragmentos | [jsonld.com](https://jsonld.com/google-faq-rich-results-deprecated/); [SEJ](https://www.searchenginejournal.com/google-drops-faq-rich-results-from-search/574429/); [seocrawl](https://seocrawl.ai/blog/faq-structured-data-google-2026) (secundarias; verificar en [Google Search Central](https://developers.google.com/search/docs/appearance/structured-data/search-gallery)) |
| **Otros retirados en 2025** | Book Actions, Course Info, Claim Review, Estimated Salary, Learning Video, Special Announcement, Vehicle Listing; también Practice Problem (nov. 2025) | Ninguno afecta al proyecto. Google indica que **no afectan al ranking** | [Google Search Central Blog, 12/06/2025](https://developers.google.com/search/blog/2025/06/simplifying-search-results); [Search Engine Land](https://searchengineland.com/google-to-remove-more-search-features-including-practice-problems-nutrition-facts-nearby-offers-and-more-464255) |
| **Product / Offer / merchant listings** | Activo. No figura en ninguna lista de deprecación | Ficha de cada PDF y kit con `Product` + `Offer` (precio, disponibilidad) + `AggregateRating`/`Review` con reseñas reales. WooCommerce y Yoast/Rank Math lo generan | [Search Engine Land](https://searchengineland.com/google-to-drop-support-for-several-rich-result-types-to-simplify-the-search-results-page-456969); confirmar en [Search gallery](https://developers.google.com/search/docs/appearance/structured-data/search-gallery) |
| **Review snippets** | Activo para Product, Recipe, etc., pero no se admiten autorreseñas de la propia organización | Reseñas solo en fichas de producto, recogidas tras la compra (p. ej. con el email de seguimiento de WooCommerce) | [whitehat-seo](https://whitehat-seo.co.uk/blog/rich-snippets) (secundaria) |
| **Article, BreadcrumbList, Organization, VideoObject** | Activos | Article con `author` (Person) en cada actividad. VideoObject cuando la actividad incluya un video vertical incrustado | Search gallery (enlace arriba) |

**Recomendación práctica de schema para una actividad:** `Article` (+ `author` Person enlazado a la página "Sobre mí") + `BreadcrumbList` + `VideoObject` si hay video + `ImageObject` vertical. HowTo es opcional. `inLanguage` va en `es-US` / `en-US`, y las versiones de idioma se conectan con **hreflang** (WPML o Polylang lo hacen solos).

#### 1.2 Arquitectura de la biblioteca de actividades

**URL e idioma:** usar subcarpetas, `/es/actividades/...` y `/en/activities/...`, con hreflang recíproco. No conviene mezclar idiomas en una misma URL. La forma más sólida es una página por idioma, cada una traducida y adaptada culturalmente, no traducida literal.

**Custom Post Type "Actividad"** (con ACF/JetEngine si se usa Elementor), con estas taxonomías:

| Taxonomía | Valores sugeridos | ¿Página indexable? |
|---|---|---|
| **Edad** (jerárquica) | 12–18 m, 18–24 m, 2 años, 3 años, 4 años | **Sí**: son páginas pilar ("actividades para niños de 2 años") |
| **Habilidad / área** | motricidad fina, motricidad gruesa, sensorial, lenguaje (bilingüe), colores, números, formas, vida práctica (Montessori), arte | **Sí** |
| **Tipo** | manualidad, sensory bin, busy bag, juego de mesa/bandeja, imprimible, receta de masa/plastilina | **Sí** (sensory bins y busy bags tienen búsqueda propia) |
| **Materiales** | sin materiales, papel y crayones, reciclaje, cocina/despensa, plastilina, pompones… | Solo los grandes ("manualidades con material reciclado"). El resto como filtro `noindex` |
| **Tiempo de preparación** | <5 min, 5–15 min, 15+ min | No: filtro (`noindex` o parámetro) |
| **Lugar / contexto** | en casa, al aire libre, en el carro, día de lluvia, restaurante | Solo algunos ("actividades para el carro") |
| **Temporada / fiesta** | Halloween, Día de Muertos, Thanksgiving, Navidad, Posadas/Reyes, San Valentín, Easter/Pascua, 4 de julio, verano, otoño | **Sí**: páginas evergreen que se actualizan cada año con la misma URL (sin año en el slug) |

**Filtros facetados:** con JetSmartFilters, Search & Filter Pro o FacetWP. Las combinaciones de filtros generan parámetros (`?edad=2&habilidad=fina`), así que hay que declarar `canonical` hacia la página base y `noindex` en combinaciones. Solo se indexan las combinaciones que tengan demanda probada (por ejemplo, "actividades de motricidad fina para niños de 2 años") y que se conviertan en una **landing estática con texto propio**. Así se evita el *index bloat*.

#### 1.3 Contenido programático vs editorial

- **Editorial (prioritario):** cada actividad, con fotos y video propios, variantes por edad, "qué aprende", seguridad (riesgo de atragantamiento con piezas pequeñas en menores de 3 años), errores comunes y versión en el otro idioma. Es lo que favorecen las actualizaciones de 2026, que según análisis de terceros premian la evidencia de experiencia propia ([digitalapplied, marzo 2026](https://www.digitalapplied.com/blog/e-e-a-t-march-2026-google-rewards-experience-content-guide); [hobo-web](https://www.hobo-web.co.uk/the-google-helpful-content-update-and-its-relevance-in-2026/), secundarias).
- **Programático (con cuidado):** páginas de taxonomía (edad × habilidad, temporada) generadas a partir de la base de actividades. Solo funcionan si cada una tiene una introducción de 150–300 palabras escrita a mano, una selección curada y suficientes actividades (por ejemplo, 8 o más). Con menos de eso: `noindex` hasta que haya contenido. **Evitar** generar en masa "50 actividades para X" con IA, porque es precisamente lo que penalizan las core updates de 2026 ([clickintelligence, mayo 2026](https://www.clickintelligence.com/what-to-do-now-that-the-google-may-2026-core-update-is-complete/), secundaria).
- **Roundups ("25 actividades de Halloween para niños de 2 años"):** son el formato que mejor funciona en Pinterest y en Google para fechas estacionales. Se construyen enlazando actividades propias.

#### 1.4 E-E-A-T para una mamá creadora

- Página **"Sobre mí / Quién es Tayo"** con nombre real o seudónimo coherente, foto (de las manos o de ella, sin mostrar al niño), historia bilingüe y formación si la hay (educación infantil, Montessori, etc.). Si no hay credencial, conviene **revisión de una educadora o terapeuta ocupacional** con firma "Revisado por" en las piezas de desarrollo o seguridad.
- **Prueba de experiencia:** fotos y videos originales del proceso (manos en cámara), "lo que pasó cuando lo probamos", fallos y adaptaciones. Hay que evitar las fotos de stock.
- **Confianza (Trust):** política de privacidad, contacto, aviso de seguridad, política de devoluciones de PDFs y cumplimiento de **COPPA** (el sitio se dirige a padres, no a niños, y debe decirlo).
- Se puede enlazar a fuentes de autoridad sobre hitos (CDC "Learn the Signs. Act Early.", AAP/HealthyChildren) en las piezas de desarrollo.

#### 1.5 Palabras clave y clusters

> **Sin cifras verificadas.** El potencial (alto/medio/bajo) se estima a partir de la frecuencia con que aparecen en la competencia, de las tendencias de Pinterest citadas y de la amplitud del término. **Cómo validarlo:** (1) **Google Keyword Planner**: ubicación EE. UU., idioma español y luego inglés; (2) **Google Trends**: comparar términos, región EE. UU., 5 años, para ver estacionalidad; (3) **Pinterest Trends** (trends.pinterest.com, con filtro EE. UU.) y la barra de búsqueda de Pinterest (las sugerencias de colores = subtemas); (4) **autocompletado** de Google, YouTube y TikTok, y "Otras preguntas de los usuarios"; (5) Search Console a partir del mes 2–3.

**Español (EE. UU.)**: la competencia es moderada (portales de España/México) y está poco especializada en toddlers.

| Cluster | Palabras clave semilla | Intención | Potencial | Competencia |
|---|---|---|---|---|
| A. Por edad (pilar) | actividades para niños de 1 año en casa · actividades para niños de 2 años · juegos para niños de 3 años · actividades para bebés de 12 meses | Informacional | **Alto** | Media (Guiainfantil, Bebés y más) |
| B. Manualidades por edad | manualidades para niños de 2 años · manualidades fáciles para niños pequeños · manualidades con material reciclado para niños | Informacional | **Alto** | Media |
| C. Montessori | actividades montessori para bebés · montessori en casa 1 año · bandejas montessori 2 años | Informacional / comercial | **Medio-alto** | Media ([Guiainfantil](https://www.guiainfantil.com/educacion/juegos/6-juegos-montessori-para-hacer-en-casa-con-los-ninos-sin-gastar-dinero/); [Lifeder](https://www.lifeder.com/actividades-montessori/)) |
| D. Habilidades | motricidad fina para niños de 2 años · actividades sensoriales para bebés · juegos para estimular el lenguaje | Informacional | Medio | Baja-media |
| E. Imprimibles (comercial) | actividades imprimibles para niños de 2 años · fichas para niños de 3 años pdf · libro de actividades bilingüe | Comercial / transaccional | Medio | **Baja**: hueco para el PDF bilingüe |
| F. Bilingüe | actividades bilingües para niños · enseñar español a mi hijo pequeño · colores en español e inglés para niños | Informacional / comercial | Medio-bajo (nicho, pero muy afín) | **Baja** |
| G. Estacional | manualidades de Día de Muertos para niños · manualidades de Navidad para niños pequeños · manualidades de otoño · manualidades de Acción de Gracias · manualidades de Pascua/huevos de Pascua · manualidades del Día de las Madres | Informacional | **Alto en temporada** | Media (Guiainfantil ya ordena las de Navidad por edades: [link](https://www.guiainfantil.com/navidad/manualidades/manualidades-de-navidad-para-ninos-por-edades-adornos-caseros-faciles/)) |

**Inglés (EE. UU.)**: la competencia es muy alta (Busy Toddler, con ~2,5 M de seguidores y programas de pago, según [CreatorDB](https://creatordb.app/creatorstats/busytoddler/); Teaching 2 and 3 Year Olds; Hands On As We Grow; NurtureStore), así que conviene apuntar a long-tail y Pinterest.

| Cluster | Palabras clave semilla | Intención | Potencial | Competencia |
|---|---|---|---|---|
| A. Edad | toddler activities at home · activities for 1 year olds · 2 year old activities · activities for 18 month olds | Info | **Alto** | **Muy alta** |
| B. Crafts | toddler crafts · easy crafts for 2 year olds · process art for toddlers | Info | **Alto** | Muy alta |
| C. Sensorial | sensory bin ideas · sensory bins for toddlers · taste-safe sensory play | Info | **Alto** (sensory play +1070 % en Pinterest, [CTV](https://www.ctvnews.ca/lifestyle/article/pinterest-search-trends-reveal-parents-push-for-offline-and-experience-rich-parenting/)) | Alta |
| D. Motricidad | fine motor activities for toddlers · gross motor activities indoor | Info | Medio-alto | Alta |
| E. Busy bags | busy bags for toddlers · quiet time activities · busy book printable | Info / comercial | Medio | Media |
| F. Printables | printable toddler activities · toddler busy book printable · toddler learning binder | **Transaccional** | Medio-alto | Alta (Etsy domina) |
| G. Screen-free | screen free activities for toddlers · no prep toddler activities | Info | **Alto y creciente** (+200 %) | Alta |
| H. Bilingüe (EN) | bilingual toddler activities · spanish activities for toddlers · learn spanish toddler printable | Comercial | Medio-bajo | **Baja-media**: diferenciador |
| I. Estacional | Halloween/Thanksgiving/Christmas/Easter/Valentine's crafts for toddlers · Day of the Dead crafts for kids | Info | Alto en temporada | Alta (excepto Día de Muertos bilingüe: media) |

**Calendario estacional (publicar 45–60 días antes; Pinterest indexa despacio):** Día de Muertos/Halloween → publicar en ago–sep · Thanksgiving → sep · Navidad/Posadas/Reyes → oct · San Valentín → dic · Easter → feb · Día de las Madres (10 de mayo para México y 2.º domingo de mayo en EE. UU.: doble oportunidad) → mar · verano → abr.

---

### 2. Pinterest como canal principal

#### 2.1 Datos de audiencia

- ~600 millones de usuarios y ~80 000 millones de búsquedas mensuales, según el Parenting Trend Report ([pulse.bot](https://www.pulse.bot/fatherhood/video/i-read-pinterests-parenting-trend-report-so-you-dont-have-to-bdaaaa38-6052-4501-91df-0dc9376ee262)). 619 M MAU en el 4T de 2025 ([GenSumo](https://gensumo.pages.dev/blog/pinterest-user-and-growth-statistics), secundaria).
- Audiencia mayoritariamente femenina: 76,7 % mujeres según las herramientas publicitarias ([Socialchamp](https://blog.socialchamp.com/?p=16998), secundaria).
- Madres: suele repetirse que "80 % de las madres de EE. UU. con internet usan Pinterest", pero es un dato antiguo. El dato tipo Pew (40 % de las madres frente a 15 % de los padres) mide otra cosa ([passport-photo.online](https://passport-photo.online/blog/pinterest-statistics/)). eMarketer muestra un uso estable entre madres de EE. UU. de 2023 a 2024 ([eMarketer](https://chart-na1.emarketer.com/c/351861/moms-pinterest-use-remains-strong-despite-fluctuations-throughout-past-year-thousands-of-unique-visitors-thousands-of-total-minutes-spent-per-month-on-pinterest-among-us-mothers-sep-2023-sep-2024)).
- **Tendencias 2026 relevantes:** screen-free +200 %, sensory play +1070 %, art & craft activities +330 %, DIY playgrounds +630 %, pretend play food +370 %, educational activities for kids +280 %, indoor fun activities +130 % ([CTV News](https://www.ctvnews.ca/lifestyle/article/pinterest-search-trends-reveal-parents-push-for-offline-and-experience-rich-parenting/); [Social Media Today](https://www.socialmediatoday.com/news/pinterest-publishes-inaugural-parenting-trend-report/813030/)).
- Madres hispanas: entre las madres hispanas que prefieren español, el 60 % recurre a blogs de mamás y el 52 % a otros padres en redes ([BabyCenter vía Portada](https://www.portada-online.com/?p=9272), dato antiguo). La mitad de las madres hispanas es bilingüe y está comprometida con enseñar español ([Mintel](https://reports.mintel.com/display/853533)).

#### 2.2 Configuración técnica

1. **Cuenta Business** (gratis): da acceso a Analytics, a anuncios, al catálogo y a la verificación de Rich Pins. Hay que **reclamar el dominio** babytayo.com con una meta tag o un TXT.
2. **Rich Pins: siguen existiendo** en tres tipos: **Article, Product y Recipe**. Pinterest lee metadatos **Open Graph o Schema.org**. Cuando una página tiene varios tipos, la prioridad es Product > Recipe > Article. Para desactivarlos: `<meta name="pinterest-rich-pin" content="false">` ([Pinterest Developers](https://developers.pinterest.com/docs/rich-pins/); [Pinterest Help](https://help.pinterest.com/business/article/rich-pins)).
   - En WordPress, Yoast SEO o Rank Math ya emiten `og:title`, `og:description`, `og:type=article` y `article:published_time`. En fichas WooCommerce, `og:type=product` + `product:price:amount` + `product:price:currency` (o Schema Product).
   - Se valida pegando una URL en la herramienta de validación o depuración de URLs de Pinterest Developers. En 2026 está disponible para cuentas Business ([Racklify](https://racklify.com/encyclopedia/what-is-a-pinterest-rich-pin-a-practical-ecommerce-overview/), secundaria).
   - Los Article Rich Pins se actualizan solos cuando cambia la página.
3. **Catálogo / Shopping con WooCommerce:** usar el plugin oficial **Pinterest for WooCommerce** (gratis), que sincroniza el catálogo como Product Pins, instala el **Pinterest Tag** (conversiones) y se mantiene activamente ([WooCommerce.com](https://woocommerce.com/products/pinterest-for-woocommerce/); [WordPress.org](https://gl.wordpress.org/plugins/pinterest-for-woocommerce/)). Problemas reportados: errores 429 al descargar imágenes y datos desactualizados (foros, principios de 2026). En Shopify ha habido reportes de suspensiones por "spam" tras sincronizaciones masivas, así que conviene **sincronizar de forma gradual** ([Shopify App Store reviews](https://apps.shopify.com/pinterest?rating=3)). Los productos digitales (PDF) pueden entrar en el catálogo, pero hay que revisar la política de Merchant Guidelines vigente antes de subirlos.
4. **Botón Guardar en WordPress:** Pinterest no tiene un plugin oficial. Hay dos opciones: (a) insertar el script oficial `pinit.js` con `data-pin-hover="true"` mediante WPCode ([PixandHue](https://www.pixandhue.com/?p=8973)); o (b) un plugin mantenido: BestWebSoft's Pinterest ([WordPress.org](https://wordpress.org/plugins/bws-pinterest/)) o **Tasty Pins** (de pago), que además deja definir una **imagen de Pin oculta** vertical y una descripción por imagen ([WP Tasty](https://www.wptasty.com/tasty-pins/pinterest-save-button)). La recomendación es Tasty Pins o una alternativa similar, porque permite tener en cada post 1–3 imágenes verticales "pinables" sin estropear el diseño.

#### 2.3 Formatos y creatividades

- **Tamaño:** **1000×1500 px (2:3)**. Pinterest advierte que otras proporciones pueden rendir peor ([Outfy, 2026](https://www.outfy.com/blog/pinterest-image-size-guide); [Tailwind](https://www.tailwindapp.com/blog/pinterest-image-size)). Video: 2:3 o 9:16 (1080×1920), de 4 s a 15 min, en .mp4/.mov ([Soona](https://soona.co/image-resizer/pinterest-image-size-specs)).
- **Idea Pins: desaparecieron como formato.** Desde el 24 de septiembre de 2025 todos son "Pins". Si se suben varias imágenes, se unen en un **Pin de video**, y los Idea Pins antiguos se convirtieron en video ([Pinterest Business Community](https://community.pinterest.biz/t/pin-creation-announcement-and-faq/1847.md); [Pinterest Help](https://help.pinterest.com/en/node/3281)). Los Idea Pins ya no son una recomendación válida. Lo que conviene hacer es **reutilizar los reels de 9:16 como Pins de video con enlace**.
- **Plantillas que funcionan en este nicho:** foto del resultado + título grande ("5-Minute Sensory Bin for 2 Year Olds" / "Caja sensorial en 5 minutos"), banda de edad, "sin preparación", y collages de roundup ("25 Fall Crafts for Toddlers").
- **Bilingüismo:** crear **Pins separados por idioma**, con texto y descripción en un solo idioma, que apunten a la URL de ese idioma. Pinterest clasifica por idioma, y mezclar ambos en un Pin confunde.

#### 2.4 Frecuencia y tableros

- **Frecuencia:** ninguna fuente fiable publica un número oficial. La guía común es **constancia** (por ejemplo, de 1 a 5 Pins *nuevos* al día, distribuidos) y **no** repinear el mismo Pin en muchos tableros, porque ahora se marca como spam ([SocialRails](https://socialrails.com/blog/pinterest-best-practices), secundaria). Lo que más rinde es crear **varios diseños nuevos para cada URL**: 3–5 por actividad, repartidos en semanas.
- **Tableros sugeridos** (con palabra clave en el nombre y descripción; ES y EN separados):
  - Toddler Activities at Home / Actividades para niños de 1–2 años
  - Sensory Bins & Sensory Play / Juego sensorial
  - Fine Motor Activities / Motricidad fina
  - Toddler Crafts / Manualidades para niños pequeños
  - Busy Bags & Quiet Time
  - Montessori at Home / Montessori en casa
  - Bilingual Learning – Spanish for Toddlers / Aprendizaje bilingüe
  - Printable Toddler Activities (productos)
  - Estacionales: Fall/Halloween, Día de Muertos, Thanksgiving, Christmas/Navidad, Valentine's, Easter, Summer
- **Herramientas:** Pinterest Trends (gratis), **Tailwind** (plan gratis: 1 cuenta, 5 posts/mes; de pago desde ~$17.99/mes anual según terceros, [socialk.it](https://socialk.it/en/pricing/tailwind)), el programador nativo de Pinterest (gratis) y Canva para las plantillas.

---

### 3. Instagram y TikTok

#### 3.1 Formatos que funcionan

- **Reels/TikToks de 15–30 s, vista cenital ("manos en cámara"):** gancho visual en el primer segundo (el resultado final o "¿tienes 5 minutos y un rollo de papel?"), 3–5 pasos rápidos y luego el niño jugando (solo manos o de espaldas). Texto en pantalla en un idioma y subtítulos en el otro, o publicar dos versiones.
- **Series fijas:** "Actividad de 5 minutos", "Con lo que hay en la despensa", "Palabra del día: rojo/red", "¿Qué aprende?" (con educadora invitada). Las series generan hábito y son fáciles de reutilizar en Pinterest.
- **Carruseles en Instagram:** "10 actividades para un día de lluvia", que funcionan como lista guardable. El guardado es una señal fuerte, y el carrusel lleva al PDF con "comenta PDF" y DM automático (ManyChat o la respuesta automática nativa).
- **Stories:** encuestas ("¿en casa hablan español, inglés o ambos?"), detrás de cámaras, reenvío de UGC.
- **TikTok:** el mismo video adaptado, con tono más espontáneo, más "mamá real" y fallos incluidos. Las búsquedas dentro de TikTok ("toddler activities") hacen que los títulos y el texto en pantalla funcionen como SEO.

#### 3.2 Comunidad, UGC y prueba social

- **Hashtag de marca:** p. ej. `#JugandoConTayo` / `#PlayWithTayo`. Se pide en cada PDF ("¡Etiquétanos!") y se premia con un reenvío o un sorteo mensual de un bundle.
- **Reseñas:** email automático de WooCommerce 7 días después de la compra pidiendo reseña con foto, que alimenta `AggregateRating`. Reutilizar capturas de DMs (con permiso) y destacar "+X familias descargaron".
- **Colaboraciones:** microcreadoras (5–50 k) bilingües o latinas en EE. UU., maestras de preescolar y terapeutas ocupacionales. Para empezar: intercambio de PDF gratis + afiliado (20–30 % con un plugin de afiliados de WooCommerce o AffiliateWP). Más adelante, publicaciones Collab de Instagram (aparecen en ambos perfiles).
- **Referencia del sector:** Busy Toddler (Susie Allison, exmaestra) construyó ~2,5 M de seguidores con actividades de bajo costo y luego monetizó con programas ("Playing Preschool"), libro y marcas ([CreatorDB](https://creatordb.app/creatorstats/busytoddler/); [Today's Parent](https://www.todaysparent.com/influential-parents-list/susie-allison/)). Es el modelo a imitar, con la diferencia de enfocarse en lo bilingüe.

#### 3.3 Privacidad del niño

- **Buenas prácticas:** mostrar manos, de espaldas, desde arriba o con la cara fuera de cuadro. Sin nombre completo, sin uniforme escolar, sin ubicación ni geoetiquetas, sin detalles de la casa reconocibles y sin publicar en tiempo real. Desactivar los metadatos EXIF y no mostrar al niño en baño ni en ropa interior.
- **Marco legal emergente:** California **SB 1247** (firmada el 30/09/2026, en vigor el **1/01/2027**) obliga a las plataformas a dar a quien fue "niño influencer" un mecanismo para pedir que se borre o edite contenido *pagado* en el que aparecía de menor, si salía en ≥30 % del contenido pagado del creador ([Digital Policy Alert](https://digitalpolicyalert.org/event/44597-california-governor-signed-bill-on-social-media-platforms-and-child-influencers-sb-1247-into-law-as-chapter-1022-of-the-statutes-of-2026); [CalMatters](https://calmatters.digitaldemocracy.org/bills/ca_202520260sb1247)). Illinois exige desde 2024 apartar ingresos para niños que aparecen en contenido monetizado ([GMA](https://www.goodmorningamerica.com/family/story/illinois-1st-state-regulate-kid-influencers-law-102259218)). **Conclusión:** una política de "manos, no caras" reduce el riesgo legal y también el reputacional. Además, el formato cenital es el que mejor funciona para tutoriales.

#### 3.4 Herramientas de programación

- **Metricool:** el plan gratis incluye 1 marca con Instagram, TikTok y Pinterest (~50 posts/mes según varias fuentes) y Starter desde ~$18/mes ([Metricool Help](https://help.metricool.com/en/article/1al21xc); [inmagic](https://inmagic.ai/metricool-review/), secundaria). Es la mejor opción gratis multiplataforma.
- **Tailwind:** especialista en Pinterest e Instagram, pero no publica en TikTok ([PinGroupie](https://pingroupie.com/blog/best-social-media-schedulers-2026)).
- Alternativas: Meta Business Suite (gratis, IG/FB), el programador nativo de TikTok y Later/Buffer.

---

### 4. Embudo y precios

#### 4.1 Embudo recomendado

```
Pinterest / IG / SEO
   → Actividad gratis (post)  ──►  Lead magnet en contexto (content upgrade)
        "Descarga las 10 actividades de 5 minutos para 2 años (PDF bilingüe)"
   → Página de gracias con OFERTA ÚNICA (tripwire $5–9, 24–72 h)
   → Secuencia de bienvenida (5–7 emails, 10–14 días)
   → Producto núcleo $12–19 → Bundle/estacional $19–35 → (futuro) suscripción / kit
```

**Lead magnets por segmento:** se pregunta la edad del niño en el formulario y se etiqueta (12–24 m / 2 años / 3–4 años), y también el idioma preferido. Con esa información se personalizan los emails y las ofertas.

**Secuencia de bienvenida (ejemplo):**
1. Día 0: entrega del PDF + "quién soy" + "responde contándome la edad de tu peque" (mejora la entregabilidad).
2. Día 1: actividad extra gratis + video, más la recomendación del tripwire.
3. Día 3: historia personal sobre el bilingüismo y por qué la marca existe. Prueba social.
4. Día 5: "3 errores al hacer actividades con toddlers" + producto núcleo.
5. Día 7: preguntas frecuentes del producto, reseñas y garantía.
6. Día 9–10: último aviso del descuento + bundle.
7. Después: newsletter semanal ("La actividad del viernes") con cadencia estacional.

**Plataforma de email:** **Kit** (antes ConvertKit) con plan gratis de hasta 10 000 suscriptores. Las automatizaciones en el plan gratis cambiaron en 2026 y hay que verificarlas ([CostBench](https://costbench.com/software/marketing-automation/convertkit/free-plan/); [marcandrews](https://marcandrews.com/?p=2966)). **MailerLite** redujo su plan gratis a 250 suscriptores y 2500 envíos/mes desde junio/julio de 2026 ([MailerLite FAQ](https://www.mailerlite.com/pl/help/free-plan-update-faq); [EmailOctopus](https://emailoctopus.com/blog/mailerlite-pricing-update)). Alternativa: FluentCRM o MailPoet dentro de WordPress, que se integran nativamente con WooCommerce.

#### 4.2 Precios de mercado (snapshots de noviembre 2026; verificar en vivo)

| Producto | Precio | Fuente |
|---|---|---|
| Busy book Montessori toddler (PDF) | $1.20 (oferta; precio original $3.00) | [Etsy](https://www.etsy.com/listing/4533236154) |
| "Toddler's First Busy Book" PDF | $9.99 | [Etsy](https://www.etsy.com/listing/1792689531/busy-book-printable-toddler-learning) |
| Montessori learning binder PDF | $3.78 (original $10.81) | [Etsy](https://www.etsy.com/listing/1558189754) |
| Megabundle 400+ páginas | $3.63 (original $9.82) | [Etsy](https://www.etsy.com/listing/806945673) |
| Busy book bundle 500+ actividades | $45.37 (original $181.50) | [Etsy](https://www.etsy.com/listing/4487193886) |
| Busy Book Mega Bundle 129 actividades | $55.00 | [Etsy](https://www.etsy.com/listing/4525012562) |
| Pack 10 actividades Montessori sin pantallas (2–5 años) | $5.99 | [Payhip](https://payhip.com/b/QdwGt) |
| Bundle imprimible toddler (tienda propia) | $14.07 | [Gumroad](https://kimdigitals.gumroad.com/l/kimdigitals) |
| Bilingüe ES/EN para colorear toddler | ver listado | [Etsy](https://www.etsy.com/listing/4536790201) |

*Los precios de Etsy salen de fragmentos de búsqueda y casi siempre muestran "rebajas" permanentes. TPT no devolvió precios verificables en la búsqueda; conviene revisarlo manualmente filtrando "toddler" o "PreK" por precio.*

**Escalera de precios propuesta para Baby Tayo** (tienda propia, posicionamiento premium-asequible bilingüe):
- Lead magnet: gratis (8–12 páginas).
- Tripwire: **$5–7** (p. ej. "Pack de otoño: 15 actividades bilingües").
- Producto núcleo: **$12–15** (busy book bilingüe 30–40 páginas por edad).
- Bundle por edad o estacional del año: **$24–35**.
- Más adelante, "membresía biblioteca imprimible": $7–9/mes o $59–79/año, como paso previo al kit físico.

#### 4.3 ¿Vender también en Etsy?

**Sí, como canal de descubrimiento secundario,** no como canal principal:
- **Comisiones:** $0.20 por listado (se renueva cada 4 meses o con cada venta), 6,5 % de transacción, procesamiento ~3 % + $0.25 y Offsite Ads del 15 % (12 % para tiendas con más de $10 k/año; se puede desactivar si se está por debajo de $10 k). En total, ~10–11 % sin Offsite Ads y ~22–25 % con ellos ([Craftybase](https://app.craftybase.com/blog/the-complete-guide-to-etsy-fees); [Checkoutpage](https://checkoutpage.com/blog/etsy-fees); [Gelato](https://www.gelato.com/blog/etsy-fees), secundarias).
- **A favor:** tráfico con intención de compra para "busy book printable", "toddler learning binder" y "bilingual"; reseñas tempranas como prueba social; y validación de qué productos venden.
- **En contra:** fuerte guerra de precios ($1–4 por megabundles) y pocas opciones para capturar emails (Etsy limita el marketing directo).
- **Táctica:** listar 5–10 productos "puerta de entrada" en Etsy, incluir dentro del PDF un enlace a la biblioteca gratis de babytayo.com y una oferta para suscriptores, y reservar los bundles grandes y la membresía para la tienda propia. También vale considerar **TPT** para packs "PreK bilingual" dirigidos a maestras de preescolar y guarderías.

---

### 5. Preparar fases futuras (breve)

| Área | Opción | Costo / dato | Fuente |
|---|---|---|---|
| **Suscripción** | WooCommerce Subscriptions | **$279/año** (1 sitio); 2 años $446.40. Ojo: las renovaciones van a precio de lista | [ActiveCampaign](https://www.activecampaign.com/blog/woocommerce-subscriptions-2); [FitGap](https://us.fitgap.com/products/006159/woocommerce-subscriptions) |
| | Alternativas | YITH Subscriptions, WPSwings (versión gratis limitada), o Cratejoy/Subbly para cajas | [WiserReview](https://wiserreview.com/blog/woocommerce-subscriptions-alternatives/) |
| **Etiquetas de envío** | **Pirate Ship** | **Gratis**, sin cuota mensual ni markup; USPS (Ground Advantage, cúbico automático) y UPS; sin automatizaciones avanzadas | [Ship.com](https://www.ship.com/post/best-pirate-ship-alternatives); [CostBench](https://www.costbench.com/compare/pirateship-vs-shipstation/) |
| | ShipStation | Desde ~$14.99/mes hasta varios cientos; conviene cuando se suman canales (Etsy + Woo + Amazon) | [Capterra](https://capterra.com/compare/155621-172133/ShipStation-vs-Pirate-Ship) |
| | USPS 2026 | Desde el 12/07/2026 la tarifa comercial publicada de Ground Advantage cobra todos los paquetes <1 lb a la tarifa de 15,999 oz; las plataformas con tarifas negociadas mantienen los tramos por onza | [Ship.com](https://www.ship.com/post/usps-ground-advantage-vs-priority-mail-2026) |
| **Inventario** | Plugin de stock nativo de WooCommerce al empezar; Sortly/inFlow o ATUM Inventory (gratis) al crecer; 3PL (ShipBob, ShipMonk) a partir de ~200–300 pedidos/mes | — | (recomendación) |
| **Seguridad de producto** | Los kits para menores de 12 años requieren **CPSIA**: pruebas en laboratorio acreditado por CPSC, Certificado de Producto Infantil (CPC), etiquetas de seguimiento y advertencia de piezas pequeñas para 3–6 años; los menores de 3 años no pueden tener piezas pequeñas | Verificar en cpsc.gov antes de lanzar | (requisito regulatorio; validar) |
| **Libros POD** | **Amazon KDP** | Sin costo inicial. Regalía 60 % del precio menos impresión (40 % en distribución expandida). Color premium: **$1.00 + $0.065/página** (42–828 pág.) o **$3.60 fijo** (24–40 pág.) | [KDP Help](https://kdp.amazon.com/en_US/help/topic/G201834340); [Books.by](https://books.by/compare/kdp-vs-ingramspark) |
| | **IngramSpark** | **Setup gratis**; desde el 1/02/2026 sin cuota de revisiones; cuota de "market access" sobre ventas mayoristas; descuento mayorista típico 55 % para librerías/bibliotecas; tapa dura disponible | [IngramSpark Help](https://help.ingramspark.com/hc/en-us/articles/41657495062029-Changes-in-Print-Cost-Market-Access-Fee-and-More); [selfpublishing.com](https://selfpublishing.com/ingramspark) |
| | **Lulu** | Sin costo inicial; 80 % del margen en la tienda Lulu propia (o integración directa con WooCommerce/Shopify para POD con envío al cliente); mejor calidad de color según reseñas | [Lulu blog](https://blog.lulu.com/print-on-demand-costs-for-authors/); [TCK Publishing](https://www.tckpublishing.com/lulu-publishing-review/) |

**Recomendación de libros:** KDP para Amazon (libros de actividades bilingües en color de 24–40 páginas, con costo fijo de $3.60), IngramSpark para bibliotecas y librerías (los bilingües tienen demanda en bibliotecas públicas) y Lulu Direct si se quiere vender el libro impreso desde babytayo.com sin inventario.

---

### 6. Plan de acción (primeros 90 días)

1. **Semana 1–2:** cuenta Pinterest Business + dominio reclamado + Rich Pins (OG vía Yoast/Rank Math) + Pinterest for WooCommerce + Tag; botón Guardar/Tasty Pins; Kit con 1 lead magnet segmentado por edad.
2. **Semana 2–4:** CPT de Actividad + 5 taxonomías + filtros; 20 actividades editoriales (10 ES + 10 EN equivalentes) con fotos y video cenitales; páginas pilar por edad.
3. **Mes 2:** contenido de Thanksgiving, Navidad, Posadas y Reyes (ya está tarde para Halloween y Día de Muertos 2026; dejarlos preparados para agosto de 2027). 3–5 Pins por URL, 1 reel diario reutilizado en TikTok y Pinterest, y hashtag de marca.
4. **Mes 2–3:** tripwire de $5–7 en la página de gracias; producto núcleo $12–15; 5–10 listados en Etsy; primeras 5 colaboraciones con microcreadoras bilingües.
5. **Validación continua:** Keyword Planner y Pinterest Trends por cluster; Search Console a partir del mes 2; métricas clave: guardados/salidas de Pinterest, conversión del lead magnet (objetivo 20–40 % en landing) y conversión del tripwire (objetivo 3–8 %).

---
