## Tesis

Repositorio: Códigos y archivos de ensayos de crecimiento de colonias con vectores que contienen 3 promotores diferentes fusionados a proteínas fluorescentes en diferentes condiciones. 

# Archivos

-Cada carpeta recibe su nombre por un vector determinado y la condición. Dentro de estas hay archivos de texto que contienen mediciones de OD, CFP, RFP e YFP por cada réplica de la colonia, el nombre de la medición vienen seguido por el nombre del pocillo donde se ubicó (p.e. CFPA3, 0DB8, etc.).
Hay archivos con los promedios de las réplicas se nombran "pxxxy" más el tipo de medición (CFP, OD, etc.). 

-"p" significa "promedio" de todas las réplicas de la colonia, las 3 letras siguientes (xxx) corresponden al vector que contiene (p.e. sss= std-std-std), la última letra (y) corresponde a la condición, por lo que puede ser "g" (glucosa) o "gl" (glicerol) según sea el caso. (p.e. psssglOD = promedio std-std-std glicerol para OD)

-Los controles se nombran "pcy" más la medición (CFP, OD, etc.). Al igual que en el caso anterior, "p" es por promedio, "c" corresponde a "control" y la última letra (y) corresponde a la condición "g" o "gl". (p.e. pcgRFP= promedio control glucosa para RFP).


# Códigos
-En cada carpeta hay un notebook que contiene códigos de ajuste de curvas de crecimiento, determinación de fase exponencial y gráficos de análisis para las diferentes mediciones y las distintas condiciones. Los gráficos realizados se basan en el trabajo de Rudge y Federici (2016) (http://pubs.acs.org/doi/abs/10.1021/acssynbio.5b00116).

-Para utilizar los notebooks se debe contar con jupyter, matplotlib, numpy, scipy, scikit-image y una versión de pyhton de 3.0 en adelante. 


