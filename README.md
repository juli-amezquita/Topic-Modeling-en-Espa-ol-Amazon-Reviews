# Topic Modeling
Topic Modeling Analysis in Spanish. Amazon Reviews

## Dataset: The Multilingual Amazon Reviews Corpus


El Modelado de Temas es tal vez la técnica más utilizada para agrupar y encontrar los denominados temas subyacentes u ocultos en los diferentes textos. El presente proyecto de Topic Modeling tiene justamente como propósito encontrar dichos temas dentro de las reseñas u opiniones dadas por los clientes o usuarios de Amazon y que se encuentran en el dataset que se puede descargar del siguiente [link](https://drive.google.com/uc?export=download&id=11XnXB7Ubgf3t6gotXGlM4FCwPOMHhDLX). 

Para desarrollar lo mencionado anteriormente debe tenerse en cuenta que estamos frente a un problema de aprendizaje no supervisado, esto debido a que nuestros datos no se encuentran etiquetados, es decir, en nuestros datos no se encuentran definidos los temas y por el contrario lo que se hará es encontrarlos. 

Para desarrollar este objetivo se emplearán 3 algorítmos frecuentemente utilizados: Latent Semantic Analysis (LSA), Hierarchical Dirichlet Process (HDP) y Latent Dirichlet Allocation (LDA) y se hará uso de librerías como SpaCy, Gensim, ConTexto y sus dependencias en español. Al final, estos algrorítmos tendrán como resultado grupos de palabras que representan un tema y nuestra labor será interpretarlas para enunciar dichos temas.

El presente proyecto tendrá como contenido los siguientes cinco pasos:

1. Carga de Datos
2. Limpieza y pre-procesamiento de datos
3. Ejecución de Modelos
4. Visualización del Modelo Final y Conclusiones


**Este proyecto también se puede visualizar de manera estática haciendo click [aquí](https://nbviewer.jupyter.org/github/juli-amezquita/Topic-Modeling-in-Spanish-Amazon-Reviews/blob/main/Topic_Modeling_en_Espa%C3%B1ol_Amazon_Reviews.ipynb).**

**Nota:** Si se desea revisar un Análisis Exploratorio de Datos (EDA) y otras aplicaciones sobre este mismo dataset, se puede consultar el siguiente repositorio en [GitHub](https://github.com/juli-amezquita/NLP-Amazon-Reviews-Star-Prediction) o el siguiente link de [nbviewer](https://nbviewer.jupyter.org/github/juli-amezquita/NLP-Amazon-Reviews-Star-Prediction/blob/main/1_NLP%20Amazon%20Reviews%20Espan%CC%83ol.ipynb).
