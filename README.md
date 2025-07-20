# proyecto-final-programacion
# Ludtke Method 3 Parachute Deployment Simulation

## Descripción
Este script implementa el “Método Ludtke” usado en el semillero de volta para modelar la dinámica del despliegue transitorio de un paracaídas.  
Calcula paso a paso la evolución de:
- Velocidad resultante (V)  
- Ángulo de ataque (α)  
- Desplazamiento horizontal (R) y vertical (S)  
- Distancia total recorrida (DS)  
- Factor de choque (X)  
- Fuerza instantánea sobre el paracaídas (F)  

- Solo usa módulos de la biblioteca estándar: `math`

Se mostrará en consola una tabla con columnas scss

TIME   VELOCITY   ALPHA   RANGE    S     DISTANCE    SHOCK   F
(sec)  (ft/s)     (°)     (ft)    (ft)    (ft)     (factor) (lbf)

Personalización
Puedes editar los valores por defecto en el bloque de input() si quieres probar casos fijos.

Extiende el script para guardar resultados en CSV o generar gráficas con matplotlib.
