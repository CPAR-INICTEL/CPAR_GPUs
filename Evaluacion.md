## Reglas generales

- Para acceder a DevCloud, se puede usar la consola o Jupyter Notebooks
- Las respuestas deben ser guardadas en un archivo con extensión Markdown dentro de algún repositorio público en GitHub. [[Ver guía para escribir Markdown]](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
- El URL de tal repositorio debe ser enviado a los emails de ambos docentes
- Máximo plazo de envio: 17 Marzo AoE [[Anywhere on Earth]](https://en.wikipedia.org/wiki/Anywhere_on_Earth)

## Preguntas

0. Clonar el repositorio [`oneAPI-samples`](https://github.com/oneapi-src/oneAPI-samples) [1 punto]
1. Cambiar al directorio del ejemplo `Nbody`  [1 punto]
    - Directorio: `oneAPI-samples/tree/master/DirectProgramming/C++SYCL/N-BodyMethods/Nbody`
2. Explicar brevemente el algoritmo de `Nbody` [3 puntos]
3. Acceder en modo interactivo a un nodo de cómputo con GPUs (`gen9` o `gen11`) [3 puntos]
    - Compilar y ejecutar `Nbody`
    - Proporcionar screenshot(s) de los resultados
        - Por cada screenshot, añadir una breve descripción
4. Realizar un análisis de _**GPU Hotspots**_ con VTune [8 puntos]
    - Indicar los hotspots del programa
    - Proporcionar screenshot(s) de los resultados
      - Por cada screenshot, añadir una breve descripción
5. Realizar un análisis _**Roofline**_ con Advisor [4 puntos]
    - Indicar los hotspots del programa
    - Proporcionar screenshot(s) de los resultados
      - Por cada screenshot, añadir una breve descripción
    - Indicar potenciales soluciones para optimizar la ejecución del programa


