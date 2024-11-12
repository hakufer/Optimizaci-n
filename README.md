# Optimización

url: https://hakufer.github.io/optimizacion/

# Ejercicio 1 


### Intento 1
![Intento 1](intento%201.png)


El resultado indica que se debe combinar ambos suplementos para satisfacer las necesidades nutricionales de la manera más económica posible. En este caso, debes adquirir 3.13 tabletas de Happy Health y 1.30 tabletas de Vega Vita. Dado que los suplementos normalmente vienen en cantidades enteras, puede ser necesario redondear los valores

### Intento 2 - Final
![Intento 2](Intento%202%20-%20Final.png)

Se obtiene una solución óptima que minimiza el costo a 1.20 dólares diarios, cumpliendo con todos los requisitos nutricionales. Para lograrlo, se deben consumir 3 tabletas de Happy Health y 3 tabletas de Vega Vita al día, garantizando una solución práctica donde las cantidades de tabletas son enteras. Este ajuste asegura que los requerimientos de vitamina C, calcio, hierro, niacina y magnesio se cumplen sin la necesidad de fraccionar suplementos, lo cual no es práctico en la vida real. Aunque el costo no cambió significativamente respecto al modelo anterior, ahora los resultados son más practicos.


# Ejercicio 1.A

- **DR_0_8: 0.0**: No se asignan conductores para el turno de 0:00 a 8:00 horas.
- **DR_4_12: 10.0**: Se asignan 10 conductores para el turno de 4:00 a 12:00 horas.
- **DR_8_16: 0.0**: No se asignan conductores para el turno de 8:00 a 16:00 horas.
- **DR_12_20: 12.0**: Se asignan 12 conductores para el turno de 12:00 a 20:00 horas.
- **DR_16_0: 0.0**: No se asignan conductores para el turno de 16:00 a 0:00 horas.
- **DR_20_4: 4.0**: Se asignan 4 conductores para el turno de 20:00 a 4:00 horas.

El objetivo del problema era minimizar el número de conductores necesarios para cubrir las necesidades de transporte durante las 24 horas del día, respetando ciertas demandas mínimas en cada tramo horario. La solución encontró que con **26 conductores** se pueden cumplir todas las restricciones establecidas, distribuidos de manera específica según los requerimientos de cada turno.


# Ejercicio 2

## Análisis de Países para Programa de Maestría

El análisis AHP se utilizó para determinar el país más adecuado para un programa de maestría, evaluando tres criterios principales: **Costo de Vida**, **Dificultad del Idioma** y **Oportunidades de Empleo**. Los países considerados en este análisis fueron **Brazil**, **Spain**, **USA**, y **Germany**. Cada criterio se ponderó en función de su importancia relativa, y luego se evaluaron los países en cada criterio.

### Resultados Finales

Los resultados finales muestran el siguiente ranking de países, basado en el puntaje global calculado:

1. **Germany**: 0.5314
2. **USA**: 0.2899
3. **Spain**: 0.1342
4. **Brazil**: 0.0445

Este ranking indica que **Germany** es la opción más adecuada para el programa de maestría, ya que tiene el puntaje global más alto. Esto sugiere que **Alemania** se destaca en los aspectos clave que se consideraron, particularmente en términos de **Dificultad del Idioma** y **Oportunidades de Empleo** después de la maestría.

**USA** ocupa el segundo lugar, siendo también una opción competitiva, pero menos favorable en comparación con **Alemania**. **Spain** y **Brazil** quedan en las posiciones tercera y cuarta, lo que implica que, aunque podrían ser opciones viables, no cumplen tan efectivamente con los criterios considerados en comparación con los otros dos países.


# Ejercicio 3 - Benchmarking para el programa Pensión 65 por departamento en 2024

Se realizará el ejercicio de Benchmarking en base a la información acerca del programa Pensión 65 por departamento ya que no existe información por provincia o por distrito. Se recopiló la información a través del portal de Transparencia Económica y los datos estadísticos del programa. Las variables elegidas son las siguientes:

- **departamento**: Se refiere al departamento del Perú.
- **puntos_pago**: Se refiere al número de puntos de pago establecidos para el programa Pensión 65 para el 2024.
- **presupuesto_p65**: Se refiere al Presupuesto Institucional Modificado (PIM) para el programa Pensión 65 para el 2024.
- **transferencia_p65**: Se refiere al dinero transferido a los usuarios bimestralmente en el programa Pensión 65 del último bimestre.
- **atendidos_p65**: Se refiere a la cantidad de usuarios atendidos en el último bimestre en el programa Pensión 65.

## Análisis de Eficiencia del Programa Pensión 65

Después de realizar el ejercicio de **Análisis Envolvente de Datos (DEA)**, se puede observar la eficiencia de los departamentos en el marco del programa social **Pensión 65**. Como se puede ver, todos los departamentos tienen una eficiencia superior al **90%**. 

Al considerar los **inputs** y **outputs** seleccionados para realizar el análisis, es posible afirmar que la eficiencia de los puntos de pagos para atender a los usuarios del programa y el uso del presupuesto en transferencias para los usuarios es alta. Sin embargo, se sabe que el programa tiene varios problemas en el **reconocimiento de usuarios**, el **alcance de los puntos de pago**, y la **provisión de información a la población atendida**.

Sería interesante realizar el análisis con información mucho más exacta y extensa acerca de la ejecución e implementación del programa para considerar todos los aspectos que puedan intervenir en la medición de su eficiencia.

## Observaciones sobre el Modelo y los Resultados

Por otra parte, en la tabla inferior, no es posible dar una interpretación correcta sobre los resultados. Como puede observarse, no ha sido posible calcular algunos coeficientes para la interpretación del modelo. Esto podría deberse a varios factores, tales como:

- **Problemas con la muestra**.
- **Colinealidad entre las variables independientes**.

Para mejorar el análisis, se debería:

- Observar el error del modelo actual.
- Desarrollar un nuevo modelo que incluya otras variables.
- Expandir la muestra a provincias o distritos, en caso de que se obtenga la información.

Esto permitiría obtener un análisis más preciso y una mejor comprensión de los factores que influyen en la eficiencia del programa **Pensión 65**.


