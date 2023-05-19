# Desafio: criar um modelo de previsão de doenças cardíacas

<font color=purple size=5>Colunas e valores do Data set</font>

* Age: idade dos pacientes em anos
* Sex: (Masculino: 1; Feminino: 0)
* cp: Tipo de dor torácica sentida pelo paciente. Este termo é categorizado em 4
categorias.
** 0 angina típica,
** 1 angina atípica,
** 2 dor não anginosa,
** 3 assintomática
* trestbps: nível de pressão arterial do paciente no modo de repouso em mm/HG
* chol: colesterol sérico em mg/dl
* fbs: Níveis de açúcar no sangue em jejum > 120 mg/dl representa 1 em caso de
verdadeiro e 0 como falso (Nominal)
* restecg: O resultado do eletrocardiograma em repouso é representado em 3 valores
distintos
** 0: Normal
** 1: com anormalidade da onda ST-T (inversões da onda T e/ou elevação ou depressão
do ST > 0,05 mV)
** 2: mostrando provável ou definitiva hipertrofia ventricular esquerda por Critérios de
Estes
* thalach: frequência cardíaca máxima alcançada
* exang: Angina induzida pelo exercício
** 0 retratando Não
** 1 retratando Sim
* oldpeak: Depressão do ST induzida pelo exercício em relação ao estado de repouso
* slope: segmento ST medido em termos de inclinação durante o pico do exercício
** 0: inclinação ascendente;
** 1: plano;
** 2: inclinação descendente
* ca: O número de vasos principais (0–3) (nominal)
* thal: Um distúrbio sanguíneo chamado talassemia
** 0: NULO
** 1: fluxo sanguíneo normal
** 2: defeito fixo (sem fluxo sanguíneo em alguma parte do coração)
** 3: defeito reversível (um fluxo sanguíneo é observado, mas não é normal (nominal)
* target: É a variável alvo que temos que prever 1 significa que o paciente sofre de
doença cardíaca e 0 significa que o paciente é normal.
