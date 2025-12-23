# ADA

Conteúdo

Este conjunto de dados oferece uma visão detalhada de diversos fatores acadêmicos e pessoais que influenciam o desempenho dos estudantes em provas. Ele inclui informações sobre os hábitos de estudo de cada aluno, como o número de horas dedicadas ao estudo e a frequência de participação nas aulas, além de detalhes sobre o estilo de vida, como duração do sono, qualidade do sono e acesso à internet.

O conjunto de dados também abrange diferentes métodos de aprendizagem, tipos de curso e percepções sobre a dificuldade das provas, oferecendo uma visão abrangente do ambiente de aprendizagem do estudante. Ao combinar esses elementos, o dataset foi projetado para ajudar pesquisadores, professores e analistas de dados a compreender como diferentes comportamentos, rotinas e condições educacionais contribuem para as notas das provas e para o sucesso acadêmico geral.

Contexto

Este conjunto de dados foi criado para ajudar a analisar como diferentes hábitos acadêmicos e rotinas pessoais afetam o desempenho dos estudantes em provas. Em muitos contextos educacionais, professores e instituições enfrentam dificuldades para identificar quais fatores realmente melhoram os resultados de aprendizagem.

Ao coletar informações sobre tempo de estudo, frequência às aulas, padrões de sono, métodos de estudo e ambientes de aprendizagem, este dataset fornece uma base sólida para explorar essas relações. Ele pode ser utilizado em modelos de machine learning, pesquisas educacionais ou para gerar insights que ajudem os estudantes a melhorar seu desempenho em provas. O contexto deste conjunto de dados é oferecer uma visão realista do comportamento dos alunos e ajudar a prever e compreender os resultados acadêmicos de forma mais eficaz.

Descrição das Colunas

student_id – Identificador único de cada estudante
age – Idade do estudante
gender – Gênero do estudante
course – Curso ou programa em que está matriculado
study_hours – Horas diárias dedicadas ao estudo
class_attendance – Percentual de aulas frequentadas
internet_access – Indica se o estudante possui acesso à internet
sleep_hours – Média de horas de sono por dia
sleep_quality – Qualidade do sono (ruim / média / boa)
study_method – Método de estudo preferido
facility_rating – Avaliação do ambiente de estudo
exam_difficulty – Percepção do estudante sobre a dificuldade da prova
exam_score – Nota final da prova

Trabalho

A idéia deste projeto é primeiramente prever a nota(enquanto variável contínnua) do aluno baseado nas informações fornecidas. Para isso será utilizado uma regressão linear simples aliada a técnicas para o pré processamento de dados como tratamento de valores nulos, outliers, variáveis categóricas, ajuste de escalas, validação cruzada, balanceamento e feature importance aprendidas em aula, afim de fixar o conteúdo. Após a Target nota será convertida para 'aprovado' e 'reprovado' ou 1/0 afim de tornar o problema um caso de classificação e podermos utilizar as técnicas de EDA para tal caso exercitando modelos mais simples como KNN até ensembles com tunning de hiper parâmetros. Todos os modelos serão feitos em sequencia de uma avaliação caucada nas métricas aprendidas, tanto para problemas numéricos (r2,mae,rmse) quanto categóricas (f1, f2, recall, precision, accuracy, auc). Por fim será feita uma comparação entre as tentativas de modelos de previsão.
