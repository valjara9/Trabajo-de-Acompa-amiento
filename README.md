# Análisis de datos médicos de pacientes: variables clínicas y metabólicas
###### *Trabajo De Acompañamiento*

Se presenta información médica de diferente índole de alrededor 100 pacientes en una base de datos con el fin de generar información relacionada a la salud de los pacientes y las diferentes relaciones que pueden haber entre los resultado de las variables descritas.
Se tienen 15 columnas con información básica (edad, sexo, estrato, peso, IMC) e información clínina (presencia de diabetes, uso de medicamentos antidepresivos y oara el tratamiento de HTA, presión arterial media, presencia de hígado graso) y metabólica (índice de glucosa en ayunas, pesencia de enzimas AST y ATL).

## Análisis descriptivo
Se procede a realizar un análisis descriptivo de las variables numéricas.

![Captura de pantalla 2025-02-26 221514](https://github.com/user-attachments/assets/6b8967ab-2e24-44a5-8ea7-a4f40468185c)

De los datos obtenidos, podemos decir:

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

![Captura de pantalla 2025-02-26 223630](https://github.com/user-attachments/assets/4da4ed44-a484-47c4-b5da-e34c8e430cf3)

De la gráfica podemos decir:
- El Captopril es el medicamento más utilizado por la población, con un 29% de los pacientes.
- El Amlodipino y el Losartán representan el 25% y 24% de los casos respectivamente.
- El 22% de la población no utiliza ningún medicamento, indicando que presentan una presión arterial controlada.

### Según uso de otros medicamentos

La población utiliza principalmente dos medicamentos diferentes al tratamiendo de HTA, para diferentes fines. La Trazadona es un medicamentos antidepresivo, usado también para tratar el insomnio y la ansidad.La Azatioprina es un medicamento inmunosupresor usado en enfermedades autoinmunes.

![Captura de pantalla 2025-02-26 225834](https://github.com/user-attachments/assets/138c7460-bc36-438b-a66a-0f78474ae1e7)

De la gráfica podemos decir:
- La trazadona es el medicamento más utilizado en la población con un 73% de los casos.
- La Azatioprina respesenta el 27% de los casos.
- Toda la población se encuentra medicada por otras razones médicas aparte del tratamiento HTA, exceptuando aquellos casos en los que no se utiliza ningún medicamento para este último fin.

### Según presencia de diabetes

![Captura de pantalla 2025-02-26 230427](https://github.com/user-attachments/assets/8ea016e1-5877-444f-8b36-09e69a95e3d0)

De la gráfica podemos decir:
- Hay una alta prevalencia de diabetes en la población
- El 41% de la población no presenta diabetes. Es una proporción considerable pero sigue siendo menor en comparación con los casos positivos (59%)

### Según IMC

![Captura de pantalla 2025-02-26 230859](https://github.com/user-attachments/assets/84f9f3f3-9d10-4459-8d06-6bf5f55b40ae)

 De la gráfica podemos decir:
 - Casi la mitad de la población presenta obesidad y un 22% de ella presenta sobrepeso. Se presenta una alta prevalencia.
 - La prevalencia de obesidad y sobrepeso en la población puede ser un factor de riesgo importante para diversas enfermedades, incluyendo la diapetes o la hipertención.
 - Poco porcentaje de la población se encuentra dentro de rangos de peso normal o bajo peso.

### Según Presión Arterial Media PAM

![Captura de pantalla 2025-02-26 231626](https://github.com/user-attachments/assets/af8ba95f-758b-42ae-bbc5-22e962a36934)

De la gráfica podemos decir:
- El 83% de la población tiene presión arterial alta. Se presenta una alta prevalencia.
- Una pequeña parte de la población se encuentra dentro del rago de PAM nomral.
- No se presentan casos de presión arterial baja.
- Si la mayoría de la población presenta PAM alta, es importante cuestionarse por qué no hay un control de esta posible anomalía desde el uso medicamentos en el 22% de la población.

### Según la presencia de enfermedad hepática del hígado graso

![Captura de pantalla 2025-02-26 232114](https://github.com/user-attachments/assets/80c2089a-4436-493d-a058-169339fcc39e)

De la gráfica podemos decir:
- Hay una alta prevalencia de la enfermedad en la población, presentandose casos en el 78% de ella.
- La problemática del hígado graso pued eestar relacionada con la prevalencia de la obesidad y sobrepeso y presencia de diabetes en la población.

##  Análisis de correlación entre las diferentes variables

Dada la posible relación entre diferentes parámetos y variables medidas, se realizan diferentes análisis de correlación para generar información que nos permita llegar a conclusiones más precisas.

### Relación entre el tratamiendo de HTA y la medida de PAM

![Captura de pantalla 2025-02-26 234917](https://github.com/user-attachments/assets/31cffac6-4e0b-425c-8116-d464e2862887)

De la gráfica podemos decir:
- Aunque sabemos que el medicamentos más usado por la población, es el que presenta el porcentaje más alto de PAM alta (89.7%)
- Entre todos los medicamentos es el medicamento con porcentaje de PAM normal más alto (25%). Igualmente, el porcentaje de pacientes con PAM alta sigue siendo considerablemente elevado.
- El porcentaje de pacientes con PAM alto es considerablemente elevado aunque se tomen medicamentos para el control de esta anomalía cardiaca. El medicamento puede no estar cumpliendo adecuadamente su función, lo que indicaría la necesidad de un ajuste en el tratamiento y un mayor control en aspectos relacionados con el estilo de vida que puedan estar interfiriendo en el correcto avance del proceso terapéutico.
- Los pacientes sin tratamiento también tienen a presentar valores de PAM altos. Se sugiere adherencia a tratamiento.
