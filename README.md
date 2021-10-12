# An-lisis-Exploratorio-de-Datos
Análisis Exploratorio de Datos

Una de las industrias que utiliza mucho las soluciones basadas en el análisis de datos es la  banca. En particular, este proyecto se centra  en el campo del crédito: se refiere a cualquier  operación que implica un operador privado, lo que podría ser un solo individuo en lugar de una familia, y el banco. La idea del crédito es que el banco se beneficiará de aprobar el crédito solo si el cliente no incumple (es decir, no pagará la deuda). En efecto, una vez aceptado como solvente y recibido el crédito, el cliente planificará, junto con el banco, un cronograma de amortización según el cual deberá reembolsar no solo la deuda, sino también los intereses.


Fuente de la data:
El conjunto de datos contiene 1000 filas con 10 variables .En este conjunto de datos, cada entrada representa a un cliente que recibe un crédito de un banco. Cada cliente se clasifica con riesgo crediticio bueno o malo según el conjunto de variables. El enlace al conjunto de datos original se puede encontrar a continuación.
https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)
https://www.kaggle.com/uciml/german-credit


Variables:

1.	Edad (numérica
2.	Sexo (texto: masculino, femenino)
3.	Trabajo (numérico: 0 - no calificado y no residente, 1 - no calificado y residente, 2 - calificado, 3 - altamente calificado)
4.	Vivienda (texto: propia, alquilada o gratuita)
5.	Cuenta de ahorros (texto: pequeño, moderado, bastante rico, rico)
6.	Cuenta corriente (numérica, en DM - Deutsch Mark)
7.	Monto del crédito (numérico, en DM)
8.	Duración (numérica, en meses)
9.	Propósito (texto: automóvil, muebles / equipo, radio / TV, electrodomésticos, reparaciones, educación, negocios, vacaciones / otros)
10.	Risk: indica si el cliente cumplirá con el pago o no (Bueno , Malo)

Qué conseguirás en este análisis Exploratorio de Datos.

•	Identificación del tipo de variables 
	¿Categórica o numérica?
  
•	Identificación de variables con valores missing 

•	Imputación por la moda de las variables con valores missing.
•	Gráficos de barras de las variables :
        Job, housing, saving account, cheking account según default.
        
•	identificación de Outliers mediante Box-plot, histograma y QQ -plot (revisando la normalidad de credit amount) para las variables numéricas:
        Credit Amount
        Duration
        Age
        
•	Detectar outliers por el método del Rango Intercuartil.


        Lower_tail = q1 - 1.5 * iqr
	
        Upper_tail = q3 + 1.5 * iqr
        
•	 Eliminar outliers

•	Ingeniería de características:
I.	    Dumificación de las variables categóricas 
II.	     Estandarización de las variables

























