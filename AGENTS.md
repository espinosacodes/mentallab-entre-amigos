# AGENTS.md

Contexto para cualquier agente que trabaje en esta carpeta. Léelo completo antes de empezar.

## Qué es este proyecto

Preparación para el **Reto 3 GRIS del Mental Lab Central** (hackathon humanaMENTE+, Universidad de La Sabana con la Fundación I+D, Bogotá, 22 de octubre de 2026).

**Pregunta del reto:** ¿Cómo podríamos ayudar a los jóvenes afectados por desastres naturales a reconocer y afrontar las consecuencias emocionales de la pérdida, el miedo y la incertidumbre, y a recuperar sus redes de apoyo después de una crisis?

**Resultado:** "Entre amigos nos cuidamos" fue elegida **idea ganadora del Mental Lab Central** el 22 de octubre de 2026.

**Clave de contexto:** la solución debe fortalecer el trabajo que ya hacen las **autoridades locales** en salud mental juvenil, y debe venir **desde los propios jóvenes**.

**Idea actual del equipo: Entre amigos nos cuidamos** (detalle en `solucion.md`). Es una red de estudiantes de servicio social y voluntarios jóvenes que quieren estudiar carreras de salud. Los forman universitarios en práctica y los supervisa el psicólogo de la alcaldía. Después de un desastre ubican a cada joven afectado, lo priorizan con un semáforo (que confirma un profesional) y lo conectan con lo que ya existe (EPS, alcaldía, ICBF, colegio, centro animal). Además, reciben los casos cuando las brigadas se van. Su rol es observar, escuchar y conectar, nunca hacer terapia. Es una solución compuesta con un centro: la red. Alrededor están el semáforo de prioridad, el aterrizaje emocional para recuperar el "ancla" (la casa como metáfora de lo que amarra al joven), la formación a familias y profesores, un canal de aviso "¿A alguien le pasó algo?", las redes sociales, el duelo por mascotas y el proyecto de vida.

## Dónde está cada cosa

| Ruta | Qué contiene |
|---|---|
| `prototipo/pitch-final.md` | **Pitch final de 3 minutos para ensayar**, con tiempos, reparto, qué recortar y preguntas probables |
| `prototipo/prompt-prototipo.md` | Prompt para generar el prototipo como página de diapositivas, con la mascota Piñón (golden retriever con chaleco rojo) |
| `prototipo/landing.html` | Landing page del proyecto con el sello de idea ganadora y los Instagram @espinosacodes_ y @fimasd_org. Publicada en espinosacodes.com/mentallab |
| `prototipo/prototipo.html` | Deck de 12 diapositivas generado con ese prompt (iPhone con Instagram y Piñón). Publicado en espinosacodes.com/mentallab/presentacion |
| `prototipo/qr-mentallab.png` y `.svg` | QR que abre espinosacodes.com/mentallab |
| `solucion.md` | **La solución final consolidada (Entre amigos nos cuidamos).** Empieza aquí |
| `ideation/reto3-ideacion.md` | Documento principal: el reto, cómo nos evalúan, problema central, Iceberg, mapa del problema, punto de apalancamiento, idea, borrador de la ficha de solución y del pitch |
| `ideation/notas-sesion-ideacion.md` | Lo que pidieron los facilitadores para la ideación: divergencia hasta las 12:50, los 8 métodos y cómo converger |
| `ideation/divergencia.md` | 35 ideas por actor, mapa de empatía, flor de loto, buena idea y mala idea, ideas compuestas, matriz de convergencia y modelo LEGO |
| `ideation/*.mmd` y `ideation/*.png` | Diagramas en Mermaid y sus imágenes: mapa del problema, Iceberg y mapa de ideas |
| `prototipo/README.md` | **Prototipo de la idea elegida ("Entre amigos nos cuidamos"):** hipótesis, perfiles, plan de validación y enlaces a storyboard, blueprint, role-play, materiales, maqueta, one pager, ficha de solución y pitch |
| `investigacion/README.md` | **Resumen de la investigación:** qué existe hoy, quién lo hace y cómo apoyarlo. Empieza aquí |
| `investigacion/01-marco-legal-colombia.md` | Marco legal e institucional colombiano con fuentes |
| `investigacion/02-casos-y-actores-colombia.md` | Casos de desastres en Colombia y organizaciones que trabajan en esto |
| `investigacion/03-evidencia-internacional.md` | Evidencia internacional, modelos de pares y salvaguardas |
| `investigacion/04-psicologos-y-brigadas-choco.md` | Psicólogos en Colombia, brigadas psicológicas y lo que pasó en el Chocó |
| `investigacion/05-autofinanciamiento.md` | Fuentes de financiación, costo del piloto y mezclas para sostener la red |
| `investigacion/06-duelo-por-mascotas.md` | Duelo por mascotas y ganado en desastres, y cómo incluirlo en la red |

Antes de proponer algo, lee `ideation/reto3-ideacion.md` y `investigacion/README.md`.

## Reglas del reto que no se pueden romper

- Nada que reemplace la atención profesional en salud mental.
- Nada de diagnósticos ni terapias sin respaldo clínico.
- Nada basado solo en prohibir.
- Ninguna dinámica ni prototipo puede pedir testimonios personales de sufrimiento.

## Cómo nos califican

Comprensión sistémica 25 %, pertinencia juvenil 20 %, innovación 20 %, viabilidad y escalabilidad 20 %, prototipo y pitch 15 %. El desempate es por viabilidad y escalabilidad. Pitch de 3 minutos más 3 de preguntas; la final es de 1 minuto.

## Cómo trabajar aquí

- Todo el contenido de documentos va en **español**.
- **Nunca uses raya (U+2014) ni semirraya (U+2013).** Reescribe con punto, coma, dos puntos o paréntesis.
- Los diagramas van en Mermaid (`.mmd`) y se renderizan a PNG en `ideation/`.
- Cuando cites un dato, distingue lo **verificado** de lo **no verificado**, siguiendo la convención de `investigacion/`.
- Si agregas investigación nueva, crea un archivo numerado en `investigacion/` y enlázalo desde `investigacion/README.md` y desde la tabla de arriba.
