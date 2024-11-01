### Sobre o Projeto

Este projeto visa utilizar de machine learning para realizar análises preditivas de doenças cardiácas de dados vindos de um dataset advindo do https://www.kaggle.com/datasets

#### Dados do Dataset
Age: Idade do paciente (em anos).

Sex: Sexo do paciente, onde:</br>
M significa masculino.</br>
F significa feminino.</br>

ChestPainType: Tipo de dor no peito sentida pelo paciente, sendo:</br>
ATA (Angina Típica): Dor associada a um esforço específico e aliviada pelo repouso.</br>
NAP (Angina Atípica): Dor atípica, que pode ocorrer sem relação com esforço.</br>
ASY (Assintomático): Sem sintomas de dor no peito.</br>
TA (Angina Transitória): Dor no peito de curta duração.

RestingBP: Pressão arterial em repouso do paciente (em mmHg).</br>

Cholesterol: Nível de colesterol total (em mg/dL).</br>

FastingBS: Glicemia em jejum, onde:</br>
0 significa que a glicemia em jejum é menor que 120 mg/dL.</br>
1 significa que a glicemia em jejum é maior ou igual a 120 mg/dL.</br>

RestingECG: Resultados do eletrocardiograma em repouso, podendo ser:</br>
Normal: ECG sem anormalidades.</br>
ST: Anormalidade da onda ST-T, como inversão da onda T ou elevação ou depressão do segmento ST.</br>
LVH (Hipertrofia do Ventrículo Esquerdo): Pode indicar um aumento no ventrículo esquerdo.</br>

MaxHR: Frequência cardíaca máxima alcançada durante o exercício.</br>

ExerciseAngina: Angina induzida pelo exercício, onde:</br>
Y significa que o paciente apresenta angina durante o exercício.</br>
N significa que o paciente não apresenta angina durante o exercício.</br>

Oldpeak: Depressão do segmento ST induzida pelo exercício em relação ao repouso, medida em mm. Valores maiores indicam maior risco.</br>

ST_Slope: Inclinação do segmento ST, que indica o padrão de resposta ao exercício. Pode ser:</br>
Up: Inclinação ascendente (geralmente considerada um bom sinal).</br>
Flat: Inclinação plana (pode ser indicativo de risco).</br>
Down: Inclinação descendente (geralmente indicativo de risco aumentado).</br>

HeartDisease: Diagnóstico de doença cardíaca, onde:</br>
0 significa ausência de doença cardíaca.</br>
1 indica a presença de doença cardíaca.</br>

#### Bibliotecas
```
warnings
```
```
pandas  
```
```
matplotlib.pyplot  
```
```
seaborn  
```
```
numpy
```