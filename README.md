# Classificador de artigos científicos de Astrofísica
Projeto do segundo semestre da disciplina ECM514 - Ciência de Dados.
> Autores: Daniel de Souza Scabar e Marcello Beer
![Project Description](https://github.com/danielscabar/arxiv_text_classification/blob/main/projeto_segundo_semestre.png)
# Apresentação
![Project Video](https://www.youtube.com/watch?v=bta265KNGwc)
# Metodologia
Esse projeto foi desenvolvido utilizando dados mantidos no repositório ArXiv mantido pela Cornell University extraidos através de uma API pública.

1) Text Embedding: Foi realizado limpeza dos dados utilizando biblioteca NLTK e foi aplicados as seguintes transformações: Remoção stopwords e pontuação, tokenização e lemmatization.
2) Feature Engineering: Foi utilizada a técnica de TF-IDF para vetorização dos dados.
3) Hiperparameter and Model Selection: Utilizada GridSearchCV para realizar seleção do modelo e dos melhores hiperparâmetros
4) Dashboard: Foi utilizado o Streamlit para criar uma aplicação Web para apresentar o trabalho.

# Referências


https://medium.com/@JyotsnaPyarasani/building-a-text-classification-system-for-news-articles-a-comprehensive-guide-10a99e8e862d

https://lukasschwab.me/arxiv.py/arxiv.html

https://www.kaggle.com/code/honggiangtrnh/topic-model-lda/input

https://colab.research.google.com/github/EPS-Libraries-Berkeley/volt/blob/main/Search/arxiv_api.ipynb#scrollTo=uznzjWmSBoLF

https://pypi.org/project/arxiv/

https://arxiv.org/category_taxonomy

https://ngrok.com/
