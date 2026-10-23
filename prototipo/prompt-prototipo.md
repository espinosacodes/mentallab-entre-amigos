# Prompt para generar el prototipo (página de presentación por diapositivas)

Copia el bloque de abajo en una herramienta que genere páginas web (Claude, v0, Lovable, Bolt o similar). El resultado es una página que se ve como un deck de 12 diapositivas, se pasa con las flechas del teclado y muestra el prototipo de Entre amigos nos cuidamos con un iPhone que corre Instagram y la mascota Piñón al lado.

La referencia visual es la página de inicio de Duolingo: fondo blanco, títulos enormes y redondeados, la mascota y los objetos ilustrados al lado del texto, bloques que alternan de lado, una sección oscura de contraste y un cierre con una ola de color. La referencia del celular es un mockup de iPhone realista como el de la foto de Find My (marco grafito, Dynamic Island, sombra suave).

---

```
Crea una página web de una sola pantalla que funcione como presentación por diapositivas (deck de 12 diapositivas) para un pitch de 3 minutos en un hackathon de salud mental juvenil en Colombia. Todo el texto va en español de Colombia, con tono cálido, juvenil y claro. Es un prototipo, pero debe verse tan pulido y alegre como la página de inicio de Duolingo.

## Producto

Nombre: Entre amigos nos cuidamos
Lema: "La red de jóvenes que se queda"
Qué es: una red de jóvenes que, después de un desastre natural, encuentra a quien la está pasando mal y no se va cuando se van las brigadas. Un amigo ve que otro publica memes o historias tristes en Instagram y lo comparte con la cuenta @entreamigosnoscuidamos, o toca un botón "Me preocupa mi amigo". Detrás de la cuenta hay estudiantes de servicio social (grados 10 y 11) que quieren ser psicólogos o médicos, formados por universitarios en Primeros Auxilios Psicológicos (observar, escuchar y conectar) y supervisados por el psicólogo de la alcaldía. No hacen terapia ni diagnóstico. Un semáforo (verde, amarillo, rojo) prioriza cada caso y el rojo lo atiende un psicólogo el mismo día.

## Mascota: Piñón

Piñón es un golden retriever joven, amistoso y expresivo, con un chaleco rojo de rescatista y un pequeño engranaje dorado bordado en el pecho. Estilo de ilustración de las mascotas de Duolingo: formas redondas y gorditas, ojos grandes y brillantes, colores sólidos con una sombra plana un tono más oscuro debajo de cada forma (efecto casi 3D), sin contornos negros. Dibújalo en SVG inline (no uses imágenes externas). Variantes de expresión: saludando con la pata, preocupado con las orejas caídas, contento con la lengua afuera, señalando hacia el celular y sosteniendo un corazón.

Piñón vive AL LADO del iPhone, nunca dentro de la pantalla: asomado por el borde del teléfono, apoyado en él, señalándolo o "hablando" con globos de diálogo cortos y redondeados. Tiene una animación suave de respiración (sube y baja 4 px) y parpadea cada pocos segundos.

Importante: Piñón no se llama igual que ningún perro de la historia. En la historia, el perro perdido de Yeison no tiene nombre o se llama "su perro".

## Estilo visual (juvenil, inspirado en la landing de Duolingo)

- Fondo blanco puro (#FFFFFF) en la mayoría de diapositivas. Algunas alternan con un celeste muy suave (#F0F8FF).
- Paleta viva y amigable con la juventud:
  - Rojo coral principal, el del chaleco de Piñón: #FF4B4B (sombra #D93A3A).
  - Amarillo sol: #FFC800 (sombra #E0A800).
  - Azul cielo: #1CB0F6 (sombra #1899D6).
  - Morado: #CE82FF.
  - Verde: #58CC02 (sombra #46A302).
  - Texto principal azul noche: #2B2D42. Texto secundario gris: #777.
  - Semáforo: verde #58CC02, amarillo #FFC800, rojo #FF4B4B.
- Tipografía "Nunito" de Google Fonts en peso 800 y 900 para títulos, 600 para texto. Títulos enormes, en minúscula como Duolingo ("entre amigos nos cuidamos."), en rojo coral o azul noche.
- Botones "chunky": esquinas muy redondeadas, texto en mayúsculas pequeñas con tracking amplio y un borde inferior sólido de 4 px un tono más oscuro que se hunde al hacer clic.
- Composición tipo landing de Duolingo: en cada diapositiva el texto va a un lado y el iPhone con Piñón al otro, alternando izquierda y derecha entre diapositivas. Mucho aire, una idea por diapositiva, texto que se lea desde el fondo de un salón.
- Objetos ilustrados flotando alrededor del teléfono con una animación lenta de flotar y girar: corazones, huellas de perro, engranajes dorados, burbujas de chat, estrellas, casitas. Estilo plano con sombra de un tono más oscuro, como las monedas y gemas de Duolingo.
- Una sola diapositiva oscura de contraste (la 5, la de las 2:07 a. m.): fondo azul noche #131F48, estrellas pequeñas, el iPhone brilla en el centro y el título va en blanco con un degradado rojo coral a morado.
- La última diapositiva cierra con una ola grande de color rojo coral en la parte de abajo (como el cierre verde de Duolingo), con Piñón saltando de ella rodeado de corazones y huellas.
- Barra superior fija y delgada: a la izquierda el logo "red engranaje" con un engranaje y una huella; a la derecha un botón chunky rojo "QUIERO SER PARTE".

## El iPhone (componente central)

Construye un mockup de iPhone realista en HTML y CSS (no una imagen), que se reutiliza en varias diapositivas:

- Proporción 9 por 19,5, marco grafito oscuro (#1C1C1E) con un borde metálico fino más claro, esquinas muy redondeadas (radio cercano al 14 % del ancho), botones laterales sutiles.
- Dynamic Island negra arriba al centro y barra de estado con "9:41" (o "2:07" en la diapositiva nocturna), señal, wifi y batería.
- Sombra suave, amplia y difusa hacia abajo, como foto de producto de Apple.
- La pantalla tiene contenido HTML real (no capturas), para poder animarlo.
- Dentro de la pantalla corre Instagram: barra superior con el nombre "Instagram" en tipografía cursiva, historias con el aro en degradado amarillo, naranja, rosa y morado, publicaciones con corazón, comentario, compartir y guardar, la vista de compartir y los mensajes directos. Dibuja los íconos en SVG simple.
- Pon el iPhone inclinado unos pocos grados con un leve efecto 3D en algunas diapositivas, y recto en las de demo.
- Cuando la página se abre en un celular, el iPhone ocupa casi todo el ancho y Piñón se asoma pequeño por una esquina.

## Navegación

- Flechas izquierda y derecha, barra espaciadora y clic para avanzar.
- Indicador de progreso abajo: puntos redondos que se llenan de rojo coral, más el número de diapositiva.
- Transiciones suaves y rebotonas (el iPhone y Piñón entran con un pequeño rebote). Respeta prefers-reduced-motion.
- Tecla "F" para pantalla completa.

## Diapositivas

1. **Portada.** Título enorme "red engranaje." y lema "entre amigos nos cuidamos." En el iPhone, el perfil de Instagram de @entreamigosnoscuidamos: foto de perfil con Piñón, biografía "Jóvenes que acompañan a jóvenes después de un desastre 🧡 Escríbenos, aquí hay una persona real", botón "Seguir". Piñón saludando al lado, con engranajes y corazones flotando. Abajo, pequeño: "Reto 3 · Mental Lab · Bogotá 2026".

2. **El gancho.** Ilustración estilo Duolingo de una grúa levantando una casa en ruinas, sin iPhone. Texto grande: "la grúa llegó para la casa. ¿quién llegó para el joven que vivía en ella?"

3. **Yeison.** Un personaje juvenil de 16 años en el mismo estilo de ilustración, con audífonos, sentado en una colchoneta de un albergue. Tres íconos tachados en burbujas: casa, colegio, perro. Globo de Yeison: "Yo no estoy loco, no necesito psicólogo."

4. **Las dos fricciones.** Dos tarjetas grandes con borde inferior chunky:
   - "1. que el joven pida ayuda" (ícono de puerta cerrada, color azul cielo).
   - "2. que la ayuda dure" (calendario donde la ayuda se acaba en la semana 4, color amarillo sol).
   Dato abajo: "La OPS señaló la salud mental como la principal brecha de la respuesta al sismo del 10 de agosto de 2026."

5. **El insight (diapositiva oscura).** El iPhone a las 2:07 a. m. muestra una historia de Instagram de "@yeison.16": un meme triste ("cuando todos dicen que ya pasó pero tú sigues en el albergue") con la barra de progreso de la historia arriba. Texto en blanco: "los jóvenes ya dicen lo que sienten. lo dicen en memes. y los primeros en verlo son sus amigos." Piñón al lado con cara preocupada, mirando el celular.

6. **Demo, paso 1: el amigo avisa.** iPhone interactivo (cada clic avanza la animación):
   - La amiga "@daniela.17" ve la historia de Yeison.
   - Toca el ícono de compartir y se abre la hoja de Instagram; elige la cuenta "@entreamigosnoscuidamos". También aparece un botón rojo chunky "Me preocupa mi amigo".
   - Sale una notificación de Piñón: "¡Gracias por cuidar a tu amigo! Nosotros le escribimos con cuidado y nunca decimos quién avisó."
   Piñón al lado señalando la pantalla, con corazones saliendo.

7. **Demo, paso 2: alguien de su edad le escribe.** iPhone con los mensajes directos de Instagram entre "@entreamigosnoscuidamos" (avatar de Piñón) y Yeison. Los mensajes aparecen uno a uno con el indicador de "escribiendo...":
   - Entre amigos nos cuidamos: "Hola Yeison 🐾 Soy Daniel, de la red Entre amigos nos cuidamos. Estudio en Quibdó y quiero ser psicólogo. ¿Cómo vas con todo lo del sismo?"
   - Yeison: "Normal... no sé. Mi perro se perdió."
   - Entre amigos nos cuidamos: "Uy, qué duro. ¿Tienes una foto? Hay un centro de bienestar animal con la lista de animales rescatados, lo buscamos juntos. ¿Te puedo escribir mañana?"
   - Yeison: "Bueno, dale."
   Al otro lado, Piñón con un globo: "Detrás de mí hay una persona real, formada y supervisada. No soy un bot ni hago terapia."

8. **Demo, paso 3: la red se queda.** Sin iPhone: un tablero sencillo en una tarjeta grande redondeada, tipo vista del psicólogo de la alcaldía, con una tabla de 4 jóvenes ficticios: nombre, zona, estudiante asignado, último contacto, semáforo (punto de color) y próximo paso. Una fila en rojo dice "Psicóloga: cita hoy 4:00 p. m.". Arriba, contadores como insignias de colores: "Jóvenes ubicados 48 · Acompañados esta semana 31 · Remitidos 5 · Mascotas reencontradas 3". Aclara que son datos de ejemplo. Piñón asomado por la esquina de la tarjeta.

9. **Cómo funciona por dentro.** Diagrama de engranajes de colores encadenados que giran despacio, de izquierda a derecha: "Amigo avisa" → "Estudiante de la red escucha" → "Universitario acompaña" → "Psicólogo de la alcaldía supervisa" → "EPS · Línea 106 · Colegio · Bienestar animal". Debajo, el semáforo en tres píldoras: verde = acompañamiento cada 15 días, amarillo = semanal y revisado con supervisor, rojo = psicólogo el mismo día.

10. **Desde mañana.** Línea de tiempo de tres puntos tipo camino de lecciones de Duolingo (círculos grandes conectados):
    - "Mañana: abrimos la cuenta. Costo: $0."
    - "En 1 mes: una facultad de salud forma a 30 estudiantes de servicio social (80 horas obligatorias)."
    - "En 3 meses: piloto en un municipio del sismo. 24 millones de pesos, con fondos que el municipio ya tiene."
    Nota: "La Ley 2460 de 2025 ya creó los agentes comunitarios en salud mental."

11. **Lo que pedimos.** Tres tarjetas chunky de colores (azul, amarillo, morado): "un municipio", "un colegio", "una facultad de salud". Piñón contento con la lengua afuera.

12. **Cierre.** Ola grande rojo coral abajo. La grúa a un lado, el iPhone mostrando el chat de Yeison con su último mensaje "gracias por escribirme 🐶" al centro, y Piñón saltando con corazones. Texto grande: "la grúa reconstruye la casa. entre amigos, nos cuidamos." Debajo, pequeño: "Si tú o alguien que conoces está en riesgo: Línea 106, gratis, 24 horas."

## Reglas de contenido

- Nunca muestres ni sugieras diagnósticos, ni que la red "detecta trastornos". Usa siempre "escuchar, acompañar y conectar".
- La tecnología solo ordena los avisos. Siempre deja claro que quien escribe y decide es una persona.
- No uses nombres ni fotos de personas reales. Todos los personajes, cuentas y datos son ficticios.
- No copies el logo oficial de Instagram ni de Apple: la interfaz se reconoce por su estructura (historias, feed, compartir, mensajes), con íconos dibujados en SVG simple.
- No uses raya larga ni semirraya en ningún texto. Usa punto, coma o dos puntos.

## Entrega

Un solo archivo HTML con CSS y JavaScript incluidos, sin dependencias externas salvo Google Fonts. Las ilustraciones (Piñón, la grúa, Yeison, los objetos flotantes, los íconos y el iPhone) van en SVG o CSS inline. Debe verse bien en un portátil conectado a un proyector (16:9) y en el celular.
```

---

## Notas para el equipo

- **Referencia de estilo:** la landing de Duolingo (grabación de pantalla del 22 de octubre). Lo que tomamos: fondo blanco, títulos gruesos en minúscula, mascota al lado del producto, objetos flotando, botones con borde inferior, una sección oscura y el cierre con ola de color.
- **El iPhone con Instagram es el protagonista:** el jurado debe ver en 3 segundos que esto pasa donde ya están los jóvenes. Piñón va al lado, nunca dentro de la pantalla, para que se entienda que la app es Instagram y Piñón es la cara de la red.
- **Por qué "Piñón":** un piñón es la rueda dentada pequeña de un engranaje, así que amarra con el nombre de la red. Si prefieren otro nombre, cámbienlo en el prompt antes de usarlo.
- **No lo llamen Rocky:** ese era el nombre del perro perdido en el role-play, y confundiría.
- **Momento "wow":** las diapositivas 5 a 7. Un meme triste a las 2 de la mañana se convierte en un "¿cómo estás?" de una persona real.
- **Ojo con la jurado que creó Wilby (un chatbot):** el prompt insiste en que detrás de Piñón hay una persona y no un bot. Esa es la diferencia que hay que decir en voz alta.
- **El botón de reporte que ya tiene Instagram:** si alguien lo menciona, esa función manda recursos genéricos. Nosotros conectamos a una persona del mismo territorio que acompaña durante meses.
