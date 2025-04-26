# interpretador
Construção de um interpretador de Reviews visando discernir se foi uma review positiva ou negativa.

Será utilizado a linguagem Python, com a biblioteca Scikit-Learn, e um modelo de regressão logística. O banco de dados consistem em 10000 reviews, na categoria livros, do site Amazon.com, disponível no arquivo "Books_small_10000.json".

O modelo final está contido no arquivo "reviews_classifier.pkl". 

Além da biblioteca Scikit-learn, foi utilizada a biblioteca pickle para salvar e reutilizar o modelo já treinado. Também foi utilizado o metodo Tfidf, com o objetivo de melhorar a acurácia do modelo.
