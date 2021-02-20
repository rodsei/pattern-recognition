# Fichamento de Artigo: 

Link de Acesso: https://www.sciencedirect.com/science/article/pii/S0957417420307934?dgcid=coauthor

## An Experimental Methodology to Evaluate Machine Learning Methods for Fault Diagnosis based on Vibration Signals


### 1. O que o artigo propõe? Qual é a novidade que ele apresenta?

Propõe um processo experimental de comparação de resultados que não seja tendencioso e que não seja super ajustado para a base de dados.
A novidade está em como fazer o processo de validação, separando grupos de dados que não se sobrepõem e que não sejam visíveis entre eles, evitando que os dados utilizados para a seleção dos hiperparâmetros sejam os mesmos utilizados para a validação dos resultados.

Dessa forma os resultados obtidos não sofrem interferência dos dados de treinamento e os scores podem ser considerados mais realistas e próximos dos resultados reais ao que se encontrará ao se utilizar o modelo com dados de produção, não conhecidos até então.

### 2. Como os experimentos do artigo são modelados para corroborar a hipótese proposta?

Estão organizados de modo que passem pelos pontos mais importantes da hipótese: reprodutibilidade, evitar tendência de similaridade e a verificação estatística dos resultados. Foram realizados quatro tipos de experimentos levando em consideração as características principais da base de dados e as particularidades dos dados para separar os grupos em cada teste.  


### 3. Quais os pontos fortes do artigo?

Um dos pontos fortes do artigo é a seção 2 explicando todo o processo de Validação dos modelos e as técnicas utilizadas. Ela cria um bom embasamento para a utilização de validações cruzadas em qualquer cenário. Isso torna o artigo bem mais amplo e alcança outros públicos além daqueles interessados no contexto de detecção de falhas.

Outro ponto forte é a apresentação comparativa de outros métodos utilizados na literatura e os resultados alcançados por cada um deles para introduzir a motivação do novo experimento proposto e a real necessidade de se chegar mais próximo à realidade do modelo que será validado.

### 4. Quais os pontos fracos dele?

Por se tratar de um artigo que propõe um novo método de utilização das validações, ele acaba se tornando muito longo e aborda vários pontos específicos do contexto da base de dados e acaba tendo algumas partes mais complexas de se compreender, que não estão relacionadas diretamente ao processo de machine learning ou de validação de modelos.

Outro ponto fraco é que a distribuição das classes e as matrizes de confusão não foram reportadas para que se possa ter o conhecimento do quão fiel está sendo o treinamento do modelo em relação à possibilidade de se estar se classificando corretamente cada caso. Por se tratar de uma base desbalanceada, essas informações são relevantes para garantir que os Falsos Negativos (classificar que não está falhando e falhar), grupo de erro mais importante pelo contexto estão controlados.


### 5. O artigo está relacionado de alguma forma com o seu projeto de dissertação? Por quê?

A semelhança do artigo com meu projeto está no desbalanceamento da base de dados utilizada, na qual as ocorrências de falhas são muito menos frequentes do que os sinais sem falhas. Nesse caso a distribuição das bases de treinamento e validação devem considerar a distruibuição dos dados de forma a não enviesar os resultados da validação. Seja para um erro estatístico ou para um erro de similaridade. Além dos exemplos e cuidado ao se realizar as divisões, o artigo mostra como é possível identificar diferentes perspectivas do mesmo problema para obter resultados diferenciados e o grau de confiabilidade que eles apresentam. 
