# Cuantificando lo Universal

**Versión**: 1.0  
**Autor**: Tomás Cuesta

## Descripción

**"Cuantificando lo Universal"** es una aplicación web interactiva diseñada para fomentar la discusión en clase sobre la universalidad de las ideas platónicas. Inspirada en la teoría de las Ideas de Platón, este juego educativo permite al alumnado evaluar el grado de universalidad que otorgan a ciertos conceptos considerados "universales". La actividad busca explorar cómo varían las percepciones de universalidad entre el alumnado y compararlas con el ideal platónico.

El proyecto está pensado como una herramienta para clases de Filosofía, en las que se puede abordar de manera práctica y reflexiva el concepto de universalidad. El alumnado puntúa diferentes ideas propuestas, y al final se genera un ranking de ideas en función de la "universalidad" percibida por el grupo. Platón otorga a todas las ideas una puntuación de 10, proporcionando un punto de comparación absoluto.

## Funcionalidad

1. **Ingreso de Ideas**: El profesorado o el grupo introduce seis Ideas universales platónicas (e.g., "Belleza", "Caballo", "Circularidad") para ser evaluadas por el alumnado.
2. **Selección del Número de Alumnos**: Se solicita el número de alumnos en clase para elegir aleatoriamente a los participantes en cada ronda.
3. **Evaluación**: En cada ronda, cinco personas al azar puntúan una Idea en una escala de 0 a 10 según su percepción de universalidad.
4. **Cálculo de Promedios**: Al finalizar todas las rondas, el programa calcula la puntuación media para cada idea en función de las calificaciones otorgadas por el alumnado.
5. **Ranking de Universalidad**: Los resultados se muestran en una tabla que compara la puntuación media del alumnado con la puntuación de Platón (siempre 10). Las Ideas se ordenan de más universal a menos según la media del alumnado.

## Objetivo Educativo

La actividad busca que el alumnado:
- Reflexione sobre el concepto de universalidad y cómo aplicarlo a ideas abstractas.
- Compare sus percepciones individuales y colectivas de lo "universal" con el ideal filosófico propuesto por Platón.
- Explore la diferencia entre percepciones subjetivas y un ideal absoluto de universalidad.

Este ejercicio puede abrir un debate sobre la naturaleza de las Ideas platónicas y su vigencia en la actualidad, además de cuestionar cómo valores considerados "universales" pueden variar según el contexto o la perspectiva personal.

## Instrucciones de Uso

1. **Configuración Inicial**:
   - Abre el archivo `index.html` en un navegador.
   - Introduce seis ideas universales que el grupo desea evaluar.
   - Introduce el número total de alumnos en clase.

2. **Inicio de la Evaluación**:
   - Pulsa "Enter" en el campo de número de alumnos o haz clic en "Iniciar Evaluación".
   - Cada idea será evaluada por cinco alumnos seleccionados aleatoriamente.
   - Los estudiantes ingresan una puntuación del 0 al 10 para cada idea, confirmando cada vez con "Enter" o haciendo clic en "Enviar Puntuación".

3. **Visualización de Resultados**:
   - Al completar todas las rondas de evaluación, el programa muestra el "Ranking de Universalidad".
   - En la tabla de resultados, cada idea se compara con la puntuación platónica (10) y se ordena de mayor a menor según la media otorgada por el alumnado.

## Tecnologías Utilizadas

- **HTML5** y **CSS3** para la estructura y el diseño de la interfaz.
- **JavaScript** para la lógica interactiva y los cálculos.
- Funcionalidad de entrada mediante teclado para una experiencia de usuario más fluida.

## Licencia

Este proyecto es de uso libre para fines educativos y no comerciales. Si deseas utilizarlo, mejorar el código o hacer modificaciones, eres bienvenido a hacerlo, siempre que se mantenga la atribución al autor original.

## Contribuciones

Si deseas contribuir con mejoras al código o nuevas funcionalidades, no dudes en hacer un pull request o contactar al autor. Las sugerencias sobre funcionalidades adicionales o adaptaciones para otras actividades educativas también son bienvenidas.