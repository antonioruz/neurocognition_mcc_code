# neurocognition_mcc_code

Código Python utilizado para el trabajo de fin de master **_Computación cuántica aplicada al análisis espacial en electroencefalografía_** para el **_master universitario en computación cuántica_** de la Universidad Internacional de La Rioja (UNIR).

Autores:

- Francisco Vidal Requejo
- Antonio José Ruz Hervás

Director:

- Rodrigo Gil-Merino y Rubio

## Estructura

Dado que el desarrollo del trabajo se divide en dos partes, el código de cada parte está en una carpeta distinta:

- AE, código correspondiente a la evaluación de armónicos esféricos mediante computación cuántica.
- QML, código correspondiente a la clasificación de coeficientes de expansión de electroencefalográmas (EEG, por sus siglas en inglés) mediante aprendizaje automático cuántico (QML, por sus siglas en inglés).

### AE

Archivos:

- AE.ipynb: Notebook para la ejecución del algoritmo cuántico de evaluación de armónicos esféricos.

También contiene las siguientes carpetas, en las que los achivos ".txt" contienen información acerca de los errores y los ".ipynb" son "notebooks" de python

- ErroresProcesadorReal: Datos de error obtenidos al evaluar armónicos esféricos de ciertos electrodos en un procesador cuántico real, así como el notebook utilizado para calcular las estadísticas y representarlas en Latex. Cada archivo ".txt" corresponde con un electrodo.
- ErroresSimuladorQASM: Datos de error obtenidos en las distintas comprobaciones de evaluación de armónicos esféricos mediante el simulador QASM de IBM y el código para obtener las estadísticas de los mismos.

- ShDraw: código para la representación gráfica de armónicos esféricos.

### QML

- MODELO_QCNN_EEGS_ARMONICOS_ESFERICOS.ipynb - código de la clasificación de los datos de expansiones en armónicos esféricos de EEG mediante QML.
