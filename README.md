# Análisis de RRHH Sku-Don

Se busca visualizar indicadores de Colaboradores, Sueldos y Desempeño con el uso de un Reporte de Recursos Humanos de la compañía (ficticia) SKU-DON. Este reporte requiere ser compartido a usuarios por medio de un enlace web. Se requiere analizar:

-Análisis por empleado (Tabla).

-Total de empleados (Conteo).

-Promedio de Edad, Sueldo y Desempeño.

-Costos totales por Sueldos, Relación-Sueldo edad.

-Evaluación de desempeño Max-Min por jefe.

Se dispone de un dataset Datos+Empleados, dispone de 3 tablas Empleados, Evaluación y Sueldo.

Con pocas transformaciones en Power Query se cargan las tablas

## Tabla 1 - Empleados

![1-rrhh](https://github.com/user-attachments/assets/80d9ad39-dc78-4da8-bec1-eb9ce82f89d7)

## Transformaciones

![2-rrhh](https://github.com/user-attachments/assets/39274dfd-f1a7-4380-909d-f8e9ddd4c5a8)

## Tabla 2 - Sueldos

![3-rrhh](https://github.com/user-attachments/assets/0f010013-fc43-4811-85d4-666ec0b5fa40)

## Transformaciones

![4-rrhh](https://github.com/user-attachments/assets/e408fbb5-2c47-492f-8682-bccdf371c2c1)

## Tabla 3 - Evaluaciones

![5-rrhh](https://github.com/user-attachments/assets/03c93b90-9726-472e-9cf4-40a3b72cfd00)

## Transformaciones

![6-rrhh](https://github.com/user-attachments/assets/cb310c5c-0616-4a29-b4a1-00dc0d261168)

## Cálculos con DAX

Se generan 3 columnas calculadas con DAX, una por cada tabla:

Rango Etario.

![Captura de pantalla (211)](https://github.com/user-attachments/assets/b0450a7f-ff8c-4c6f-9eac-054dc27abd32)

Rango Salarial.

![Captura de pantalla (212)](https://github.com/user-attachments/assets/329fabe0-e633-40fd-9077-514e037b3f9d)

Rango de Evaluaciones.

![Captura de pantalla (213)](https://github.com/user-attachments/assets/297a8350-e319-4c67-8254-60e31b29dac6)

También se crea una tabla llamada _Medidas, donde se crean 4 medidas:

![Captura de pantalla (214)](https://github.com/user-attachments/assets/829391b8-b074-42fb-861b-a4fb9effdb3c)

# Reportes

## Con estas 3 tablas se realizan 3 reportes

## Reporte 1 - Análisis Empleados

Está compuesto por 4 Tarjetas y 7 Visualizaciones :

## Tarjetas

-Total Empleados.

-Edad Promedio.

-Sueldo Promedio.

-Evaluación Promedio.

## Visualizaciones

-Gráfico de anillos, detallando la proporción de empleados por Género.

-Mapa, detallando la cantidad de empleados por Estado.

-Gráfico de barras, Rango Etario.

-Gráfico de barras, Rango Salarial.

-Gráfico de barras, Rango de Evaluación.

-Gráfico de columnas, con detalle de la cantidad de empleados por Departamento.

-Tabla, con el detalle de todos los empleados.

![Captura de pantalla (216)](https://github.com/user-attachments/assets/19ccface-0a2d-463c-9ea6-3769c4287dd2)


## Reporte 2 - Análisis Sueldos

Está compuesto por 3 Tarjetas y 5 Visualizaciones :

## Tarjetas

-Total Empleados.

-Sueldo Total.

-Sueldo Promedio.

## Visualizaciones

-Gráfico de anillos, detallando la proporción de empleados por Sueldo y Género.

-Mapa, detallando el Sueldo Total por Estado.

-Gráfico de dispersión, evaluando la relación entre la edad de los emplados y el Sueldo.

-Gráfico de columnas, con detalle del Sueldo Promedio por Departamento.

-Tabla, con el detalle de todos los empleados.

![Captura de pantalla (215)](https://github.com/user-attachments/assets/8739a4ba-28b0-48b4-9c5a-d7763d48ebf6)

## Reporte 3 - Análisis Desempeño

Está compuesto por 4 Tarjetas y 5 Visualizaciones :

## Tarjetas

-Total Empleados.

-Evaluación Máxima.

-Evaluación Mínima.

-Evaluación Promedio.

## Visualizaciones

-Mapa, detallando Evaluaciones por Estado.

-Gráfico de barras, evaluando el desempeño de promedio de los empleados por Jefe directo.

-Gráfico de columnas, con detalle de promedio de Evaluación por Género.

-Gráfico de columnas, con detalle de promedio de Evaluación por Departamento.

-Tabla, con el detalle de todos los empleados.

![Captura de pantalla (217)](https://github.com/user-attachments/assets/3382194f-26c0-43f0-8686-a4a5da73b163)















