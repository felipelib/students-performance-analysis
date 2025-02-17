# Análise de Desempenho Acadêmico de Estudantes
Este projeto tem como objetivo analisar o desempenho acadêmico de estudantes do ensino médio, utilizando técnicas de análise exploratória de dados (EDA) e modelagem preditiva para identificar fatores que impactam o GPA (Grade Point Average) dos alunos.

# Objetivo
O objetivo principal é desenvolver um modelo de Machine Learning capaz de prever o GPA dos alunos com base em variáveis como idade, tempo de estudo, número de faltas, nível de educação dos pais, participação em atividades extracurriculares, entre outras. Com isso, a instituição de ensino poderá identificar alunos com risco de baixo desempenho e tomar medidas preventivas.

# Dados
O dataset utilizado contém informações sobre 2.392 estudantes do ensino médio, com as seguintes variáveis:

StudentID: Identificador único do aluno.
Age: Idade do aluno.
Gender: Gênero do aluno.
Ethnicity: Etnia do aluno.
ParentalEducation: Nível de educação dos pais.
StudyTimeWeekly: Tempo de estudo semanal em horas.
Absences: Número de faltas ao longo do ano.
Tutoring: Indica se o aluno teve aulas particulares.
ParentalSupport: Nível de apoio familiar nos estudos.
Extracurricular: Participação em atividades extracurriculares.
Sports: Participação em atividades esportivas.
Music: Participação em atividades musicais.
Volunteering: Participação em atividades voluntárias.
GPA: Nota média do aluno (Grade Point Average).
GradeClass: Classificação das notas (A, B, C, D, F).

# Análise Exploratória de Dados (EDA)
A análise exploratória foi dividida em três partes principais:

Análises Univariadas: Distribuição das variáveis individuais, como idade, gênero, etnia, tempo de estudo, número de faltas, etc.

Análises Bivariadas: Relação entre variáveis, como tempo de estudo vs. GPA, número de faltas vs. GPA, e participação em atividades extracurriculares vs. desempenho acadêmico.

Análises Multivariadas: Correlação entre múltiplas variáveis para identificar padrões mais complexos.

# Principais Insights
- Mais de 50% dos alunos têm nota F (GPA < 2).
- O número de faltas tem uma correlação negativa forte com o GPA (-0.92).
- Alunos que participam de atividades extracurriculares tendem a ter um desempenho acadêmico melhor.
- Aulas particulares e apoio parental estão associados a um GPA mais alto.

# Modelagem Preditiva
Foram testados vários modelos de regressão para prever o GPA dos alunos, incluindo:

- Regressão Linear
- Árvore de Decisão
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM

O melhor modelo foi a Regressão Linear, com um R² de 0.95, indicando que 95% da variância do GPA pode ser explicada pelas variáveis independentes.

# Métricas do Modelo

MAE (Mean Absolute Error): 0.16
MSE (Mean Squared Error): 0.04
RMSE (Root Mean Squared Error): 0.20
R²: 0.95

# Soluções Propostas
Com base nas análises, foram propostas as seguintes soluções para melhorar o desempenho acadêmico dos alunos:

Redução de Faltas:

- Implementar um sistema de monitoramento de faltas.
- Enviar alertas para pais e responsáveis.
- Oferecer suporte psicológico e social para alunos com faltas frequentes.

Aulas Particulares:

- Oferecer sessões de monitoria no contraturno.
- Recomendar professores particulares de confiança.

# Atividades Extracurriculares:
- Expandir o leque de atividades oferecidas.
- Oferecer horários flexíveis para participação.
