# Análisis de datos médicos de pacientes: variables clínicas y metabólicas
###### *Trabajo De Acompañamiento*

Se presenta información médica de diferente índole de alrededor 100 pacientes en una base de datos con el fin de generar información relacionada a la salud de los pacientes y las diferentes relaciones que pueden haber entre los resultado de las variables descritas.
Se tienen 15 columnas con información básica (edad, sexo, estrato, peso, IMC) e información clínina (presencia de diabetes, uso de medicamentos antidepresivos y oara el tratamiento de HTA, presión arterial media, presencia de hígado graso) y metabólica (índice de glucosa en ayunas, pesencia de enzimas AST y ATL).

## Análisis descriptivo
Se procede a realizar un análisis descriptivo de las variables numéricas.

![Captura de pantalla 2025-02-26 221514](https://github.com/user-attachments/assets/6b8967ab-2e24-44a5-8ea7-a4f40468185c)

*De los datos obtenidos, podemos decir:*
- La media de la edad de los pacientes es de aproximadamente 49.62 años, con una amplia dispersión entre ellas. La edad mínima es de 18 años y la máxima de 79.
- El valor promedio de glucosa en ayunas es de 96.8 mg/dL, con un mínimo de 70 y un máximo de 119.7. La mayoría de los valores se encuentrarn en un rango normal, aunque hay variabilidad.
- La media de los valores de Presión Arterial Media es de 102mmHg con una desviación estándar de 11.57. Se presentan casos de presiones altas y bajas devido a la variabilidad.
- El peso promedio de los pacientes es de 90.37kg, con un mínimo de 56.76 y un máximo de 119.42.
- El índice de masa corporal promedio es de 30.37, indicando que la mayoría de pacientes pueden estar en un rango de sobrepeso u obesidad. Siendo el máximo de 52.27, se presentarían casos de obesidad severa.
- Los niveles de enzimas AST antes tienen una media de 202.65; los niveles de AST después tienen una media de 60.95. Similarmente pasa con los niveles de ALT que pasan de 124.16 a valores más bajos. Esto puede indicar una reducción significativa en los niveles enzimáticos luego de tratamiento o intervención.

## Descripción de la población según variables medidas

Se realiza una descripción detallada según algunos variables medidas, con el fin de clasificar la población. 

### Según uso de medicamentos para el tratamiento de HTA

El Captopril, Losartán, Amlopino son medicamentos para el tratamiento de la hipertensión arterial. Sus mecanismos de acción varían entre inhibidores de la enzima convertidora de angiotensina IECA y bloqueadores de canales de calcio.

![Captura de pantalla 2025-02-27 110525](https://github.com/user-attachments/assets/756ca2e6-fd44-4851-8a4b-ed9394d9625f)

*De la gráfica podemos decir:*
- El Captopril es el medicamento más utilizado por la población, con un 29% de los pacientes.
- El Amlodipino y el Losartán representan el 25% y 24% de los casos respectivamente.
- El 22% de la población no utiliza ningún medicamento, indicando que presentan una presión arterial controlada.

### Según uso de otros medicamentos

La población utiliza principalmente dos medicamentos diferentes al tratamiendo de HTA, para diferentes fines. La Trazadona es un medicamentos antidepresivo, usado también para tratar el insomnio y la ansidad.La Azatioprina es un medicamento inmunosupresor usado en enfermedades autoinmunes.

![Captura de pantalla 2025-02-27 110538](https://github.com/user-attachments/assets/3d589be3-3a11-4edc-b381-c0a6e032e9ad)

*De la gráfica podemos decir:*
- La trazadona es el medicamento más utilizado en la población con un 73% de los casos.
- La Azatioprina respesenta el 27% de los casos.
- Toda la población se encuentra medicada por otras razones médicas aparte del tratamiento HTA, exceptuando aquellos casos en los que no se utiliza ningún medicamento para este último fin.

### Según presencia de diabetes

![Captura de pantalla 2025-02-27 110551](https://github.com/user-attachments/assets/4444fa41-6840-40fd-9b17-1f7d7e1330b4)

*De la gráfica podemos decir:*
- Hay una alta prevalencia de diabetes en la población
- El 41% de la población no presenta diabetes. Es una proporción considerable pero sigue siendo menor en comparación con los casos positivos (59%)

### Según IMC

![Captura de pantalla 2025-02-27 111250](https://github.com/user-attachments/assets/5b40b034-b4c9-4b37-8d23-ceb842dc21e9)

 *De la gráfica podemos decir:*
 - Casi la mitad de la población presenta obesidad y un 22% de ella presenta sobrepeso. Se presenta una alta prevalencia.
 - La prevalencia de obesidad y sobrepeso en la población puede ser un factor de riesgo importante para diversas enfermedades, incluyendo la diapetes o la hipertención.
 - Poco porcentaje de la población se encuentra dentro de rangos de peso normal o bajo peso.

### Según Presión Arterial Media PAM

![Captura de pantalla 2025-02-27 111302](https://github.com/user-attachments/assets/b5b19354-6582-4bfd-ae00-b86fe0e73338)

*De la gráfica podemos decir:*
- El 83% de la población tiene presión arterial alta. Se presenta una alta prevalencia.
- Una pequeña parte de la población se encuentra dentro del rago de PAM nomral.
- No se presentan casos de presión arterial baja.
- Si la mayoría de la población presenta PAM alta, es importante cuestionarse por qué no hay un control de esta posible anomalía desde el uso medicamentos en el 22% de la población.

### Según la presencia de enfermedad hepática del hígado graso

![Captura de pantalla 2025-02-27 113847](https://github.com/user-attachments/assets/5a4016a7-5eee-4438-aa60-b033e909ab46)

*De la gráfica podemos decir:*
- Hay una alta prevalencia de la enfermedad en la población, presentandose casos en el 78% de ella.
- La problemática del hígado graso pued eestar relacionada con la prevalencia de la obesidad y sobrepeso y presencia de diabetes en la población.

##  Análisis de correlación entre las diferentes variables

Dada la posible relación entre diferentes parámetos y variables medidas, se realizan diferentes análisis de correlación para generar información que nos permita llegar a conclusiones más precisas.

### Relación entre el tratamiendo de HTA y la medida de PAM

![Captura de pantalla 2025-02-27 111321](https://github.com/user-attachments/assets/163efc1a-2722-4be8-a3f6-a23102bc33bb)

*De la gráfica podemos decir:*
- Aunque sabemos que el medicamentos más usado por la población, es el que presenta el porcentaje más alto de PAM alta (89.7%)
- Entre todos los medicamentos es el medicamento con porcentaje de PAM normal más alto (25%). Igualmente, el porcentaje de pacientes con PAM alta sigue siendo considerablemente elevado.
- El porcentaje de pacientes con PAM alto es considerablemente elevado aunque se tomen medicamentos para el control de esta anomalía cardiaca. El medicamento puede no estar cumpliendo adecuadamente su función, lo que indicaría la necesidad de un ajuste en el tratamiento y un mayor control en aspectos relacionados con el estilo de vida que puedan estar interfiriendo en el correcto avance del proceso terapéutico.
- Los pacientes sin tratamiento también tienen a presentar valores de PAM altos. Se sugiere adherencia a tratamiento.

### Distribución de la Edad en pacientes que toman Antidepresivos

Se busca identificar si la edad es un factor determinante para el consumo de antidepresivos en la población estudiada.

![Captura de pantalla 2025-02-27 111333](https://github.com/user-attachments/assets/96f31c5a-a289-4f02-b817-ee5e3406c8b6)

*De la gráfica podemos decir:*
- La cantidad de pacientes es variable en diferentes grupos de edad.
- Se observa una mayor concentración de pacientes entre los 40 y 50 años, lo que sugiere que el uso de antihipertensivos es más común en esta franja de edad.
- También hay un segundo grupo significativo en edades mayores (60-70 años).

### Índice de glucosa en ayunas según el consumo de antidepresivos

  Se busca determinar si hay alguna posible asociación entre el uso de antidepresivos e hiperglucemia como efecto adverso de este tratamiento

  ![Captura de pantalla 2025-02-27 114422](https://github.com/user-attachments/assets/09aac477-996b-41a7-a711-51b77b87cf58)

*Para pacientes que NO toman antidepresivos:*
- La mediana de la glucosa en ayunas se encuentra cerca de 100 mg/dL.
- Existe una dispersión amplia en los valores, con algunos pacientes presentando niveles por debajo de 70 mg/dL y otros por encima de 120 mg/dL.
- Se observan valores atípicos en el extremo superior, lo que indica algunos casos con hiperglucemia

*Para pacientes que toman antidepresivos:*
- No hay presencia de datos en el gráfico, lo que sugiere que la muestra de pacientes que toman antidepresivos puede ser muy reducida o no reporta valores distintos a los del grupo "No toma".

*En general, podemos concluir:*
- No se puede determinar una asociación clara entre el uso de antidepresivos y la hiperglucemia solo con este gráfico, ya que no hay valores visibles para el grupo "Toma Antidepresivo".
- Si los valores estuvieran disponibles, se podría comparar si la mediana y el rango de glucosa en ayunas es mayor en quienes toman antidepresivos, lo que podría sugerir un posible efecto adverso.

### Relación entre el IMC y niveles de AST/ALT después del tratamiento

Se representa la distribución de los niveles de transaminasas hepáticas en función del índice de masa corporal IMC mediante un histograma bidimensional, donde los colores nos indica la densidad de los datos en cada rango.

![Captura de pantalla 2025-02-27 120441](https://github.com/user-attachments/assets/30e49181-c619-4942-bceb-c6ec4ead907a)

*Distribución de AST aspartato aminotransferasa (Color azul)
- Se observa que los valores de AST tienden a agruparse en un rango de 50 a 80 unidades.
- No parece haber una relación clara entre el IMC y los niveles de AST, ya que los datos están dispersos en diferentes valores de IMC sin una tendencia evidente.

*Distribución de ALT alanina aminotransferasa (Color violeta)
- Los valores de ALT están más dispersos y generalmente son más altos que los de AST, con una mayor densidad en el rango de 100 a 140 unidades.
- A diferencia de AST, ALT muestra una mayor variabilidad a medida que el IMC aumenta.

*En general, podemos concluir:*
- No se observa una relación lineal clara entre el IMC y los niveles de AST o ALT después del tratamiento.
- ALT parece tener una mayor variabilidad con el IMC, lo que podría sugerir que pacientes con mayor IMC tienden a tener valores más elevados de ALT.

----------------------------------------------------

![Captura de pantalla 2025-02-27 111429](https://github.com/user-attachments/assets/a597c37d-025f-49a6-8504-a79c86a42460)

Se representa una matriz de correlación que busca evalúar la relación entre el Índice de Masa Corporal (IMC) y los niveles de transaminasas (ASTDespues y ALTDespues). La correlación se mide con el coeficiente de Pearson, que varía entre -1 (correlación negativa total) y 1 (correlación positiva total).

*Correlación entre IMC y AST/ALT después:*
- La correlación entre IMC y ASTDespues es de 0.13, lo que indica una relación muy débil y positiva.
- La correlación entre IMC y ALTDespues también es de 0.13, con un comportamiento similar.

*Correlación entre ASTdespués y ALTdespués:*
- Existe una correlación negativa moderada (-0.21) entre los niveles de ASTDespues y ALTDespues, lo que sugiere que cuando ALT disminuye, AST tiende a aumentar y viceversa.

*En general, podemos concluir:*
- No se observa una relación fuerte entre el IMC y las transaminasas. Un IMC más alto no parece estar claramente asociado con aumentos significativos de AST o ALT.
- La relación entre AST y ALT es ligeramente negativa, lo que podría indicar que responden de manera diferente a ciertos factores, como enfermedades hepáticas o medicamentos.

### Clasificación de riesgo basado en parámetros clínicos

Se muestra la relación entre el Índice de Masa Corporal (IMC) y la Presión Arterial Media (PAM), con los pacientes categorizados en tres grupos de riesgo: Bajo, Moderado y Alto.

![Captura de pantalla 2025-02-27 111459](https://github.com/user-attachments/assets/7c02dac0-7ea1-47b5-8646-dfe38ee2fbc2)

*Distribución del IMC según el Riesgo:*
- Los pacientes de Alto Riesgo (lila) tienden a tener valores más elevados de IMC en comparación con los de Bajo Riesgo (azul).
- Los pacientes de Moderado Riesgo (verde) presentan una distribución intermedia, pero con una mayor dispersión.
- Se observa una diferencia clara en la densidad de IMC entre los grupos, sugiriendo que un mayor IMC podría estar relacionado con un mayor riesgo clínico.

*Distribución de la presión arterial media PAM:*
- Se aprecia una tendencia ascendente en la PAM a medida que el riesgo aumenta.
- Los pacientes con Alto Riesgo presentan valores más altos de Presión Arterial Media, lo que podría indicar que la hipertensión podría ser un factor determinante en la clasificación del riesgo.
- Por otro lado, los pacientes de Bajo Riesgo tienden a tener una PAM más baja y más homogénea.

*Relación entre IMC y PAM según el Riesgo:*
- Se observa una correlación positiva entre IMC y PAM dentro de cada grupo de riesgo, lo que sugiere que a un mayor IMC, hay una mayor tendencia a que la PAM también sea más alta.
- No obstante, hay dispersión dentro de cada grupo, lo que indica que, aunque la relación existe, otros factores clínicos pueden estar influyendo en la clasificación del riesgo.

*En general:*
Se puede determinar con estos resultados que el IMC y la Presión Arterial Media son factores clave en la clasificación del riesgo clínico. En este mismo contexto, los pacientes de Alto Riesgo tienden a tener mayores valores de IMC y PAM, lo que sugiere una posible asociación con la obesidad e hipertensión.

### Densidad de peso e IMC según Hipertensión

Se evidencia la relación entre peso e índice de masa corporal (IMC) diferenciando entre personas hipertensas (rosa) y normotensas (verde). 

![Captura de pantalla 2025-02-27 111534](https://github.com/user-attachments/assets/96cb7b64-1f81-4a2b-90c0-1d8db76cd065)

*Correlación entre peso e IMC:*
- Existe una correlación clara entre el peso y el IMC, ya que ambos valores aumentan en conjunto.
- Las personas con mayor peso tienden a tener un IMC más alto, lo que es esperado dado que el IMC se calcula a partir del peso y la altura.

*Diferencia entre Hipertensos y Normotensos:*
- Los individuos hipertensos tienden a tener mayores valores de peso e IMC en comparación con los normotensos.
- La densidad de los hipertensos se extiende hacia valores más altos de peso e IMC, lo que sugiere que el sobrepeso y la obesidad pueden estar asociados con la hipertensión.

*Superposición entre grupos:*
Aunque hay diferencias evidentes, también es posible observar una superposición considerable entre ambos grupos, lo que indica que algunos individuos con peso e IMC más bajos también pueden ser hipertensos. Con lo anterior, si bien el peso y el IMC son factores de riesgo importantes, otros factores pueden influir en la hipertensión, como la genética, el estilo de vida y la dieta.

## Conclusión general

Loa análisis realizados revelan una población con una alta prevalencia de enfermedades crónicas como la diabetes, la hipertensión, la obesidad y el hígado graso. Aunque se utilizan medicamentos para controlar estas condiciones, los resultados sugieren que los tratamientos actuales podrían no ser suficientes para todos los pacientes, lo que indica la necesidad de un enfoque más integral que incluya cambios en el estilo de vida, ajustes en los tratamientos médicos y un monitoreo más estrecho de los factores de riesgo. Además, la correlación entre el IMC y la presión arterial refuerza la importancia de abordar la obesidad como un factor clave en la prevención y el manejo de enfermedades cardiovasculares y metabólicas.

# FIN :)
