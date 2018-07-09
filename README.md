# Repositorio

En este repositorio hay códigos para el análisis de ensayos de crecimiento de colonias con vectores que contienen 3 promotores diferentes fusionados a proteínas fluorescentes en diferentes condiciones. Los datos aquí contenidos fueron analizados en el trabajo "Desarrollo de biosensores multiespectrales". 

## Archivos
-En la carpeta "Análisis" se ubican carpetas con el numero de ensayo y dentro de estas se encuentran los notebooks del análisis de cada ensayo, mas archivos de datos (.txt) para cada vector por réplica y condición y archivos de imagen de los análisis.

## Códigos
-Los notebooks contienen códigos de ajuste de curvas de crecimiento, determinación de fase exponencial y gráficos de análisis para las diferentes mediciones (OD, CFP, RFP, YFP) y las distintas condiciones (Glucosa, Glicerol). Los gráficos realizados se basan en el trabajo de Rudge y Federici (2016) (http://pubs.acs.org/doi/abs/10.1021/acssynbio.5b00116).
-Para utilizar estos notebooks se debe contar con jupyter, matplotlib, numpy, scipy, scikit-image y pyhton 3.0.

-También se encuentran notebooks relacionados a la base de datos creada en el laboratorio (Github.com/SynBioUC/flapjack) para el análisis de Entropía de Información, incluyendo calculos de probabilidades de los datos, entropías condiciones e información mutua.
-Para estos notebooks se debe contar con jupyter, pandas, sqlalchemy, matplotlib, openpyxl, psycopg2, numpy, postgresql, scipy y python 2.7.
