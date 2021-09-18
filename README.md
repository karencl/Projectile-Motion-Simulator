# Projectile-Motion-Simulator
Este simulador fue hecho con el fin de probar como es que sería el movimieno de un proyectil (que sale de un volcán por ejemplo), tomando en cuenta dos situaciones: sin y con fuerza de arrastre.

Para la programación de este simulador se utilizó un método numérico de *Verlet*, con el fin de realizar integraciones numéricas de ecuaciones diferenciales, a partir de ciertas condiciones iniciales que ya estabas predeterminadas o que pasa el usuario.
En base a esto, se obtienen las posiciones, velocidades y aceleraciones.

## Modos de simulación
1. Datos inciales ingresados por el usuario.
2. 3 simulaciones seguidas con datos aleatorios.

### Inputs
- Altura inicial en "Y" (m)
- Velocidad inicial (m/s)
- Ángulo de lanzamiento (º)
- Masa del objeto (kg)
- Constante de resistencia del aire
- Time step (s)
- Densidad del aire (kg/m^3)
- Sección transversal (m^2)
- Alfa

*Si se selecciona la forma aleatoria, estos datos serán puestos aleatoriamente por el programa.*
*En caso contrario, el usuario tendrá la libertad de cambiarlos a su gusto.*

### Outputs
- **Sin resistencia del aire:** posición en "X" (m), posición en "Y" (m), velocidad (m/s) -> se actualiza en tiempo real.
- **Con resistencia del aire:** posición en "X" (m), posición en "Y" (m), velocidad (m/s) -> se actualiza en tiempo real.
- Las condiciones iniciales (ya sean ingresadas por el usuario o seleccionadas de manera aleatoria)
- **Sin resistencia del aire:** altura máxima (m) - "Y", punto de caída (m) - "X", tiempo de vuelo (s) -> sale al término de la simulación.
- **Con resistencia del aire:** altura máxima (m) - "Y", punto de caída (m) - "X", tiempo de vuelo (s) -> sale al término de la simulación.
