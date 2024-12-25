🇧🇷 Este projeto é um sistema de recomendação musical baseado em análise de clusters e redução de dimensionalidade utilizando PCA (Principal Component Analysis). O objetivo é recomendar músicas similares a partir de uma música inicial, aplicando técnicas de aprendizado de máquina.

Funcionalidades:

	•	Recomendação de Músicas: Dado o nome de uma música, o sistema recomenda outras músicas semelhantes utilizando PCA e K-means clustering.
	•	Visualização Interativa: As recomendações são visualizadas com imagens de álbuns e títulos de músicas.
	•	Uso da API Spotify: As informações sobre as músicas, incluindo imagens de álbuns, são obtidas através da API do Spotify.

Tecnologias Utilizadas:

	•	Python 3.9.13: Linguagem de programação usada para desenvolver o sistema de recomendação.
	•	Jupyter Notebook: Ambiente de desenvolvimento interativo utilizado para implementar e testar o código.

Bibliotecas:

	•	Pandas: Para manipulação e análise de dados.
	•	Numpy: Para cálculos numéricos avançados.
	•	Matplotlib: Para visualização de gráficos e imagens.
	•	Seaborn: Para visualização de dados estatísticos.
	•	Plotly Express: Para visualizações interativas.
	•	Scikit-learn: Para implementação de PCA e K-means.
	•	Spotipy: Para integração com a API do Spotify e obtenção de informações das músicas.
	•	Scikit-Image: Para exibição de imagens de álbuns.
 
 Como Funciona:
 
	1.	Pré-processamento de Dados: Os dados das músicas são carregados e tratados.
	2.	Redução de Dimensionalidade (PCA): A redução da dimensionalidade é aplicada para tornar o modelo mais eficiente.
	3.	Clusterização (K-means): O K-means é utilizado para agrupar músicas semelhantes em clusters.
	4.	Recomendação: Quando você fornece uma música, o sistema encontra músicas no mesmo cluster e calcula as distâncias euclidianas para recomendar as mais próximas.


-- // --

🇪🇸 Este proyecto es un sistema de recomendación musical basado en el análisis de clústeres y reducción de dimensionalidad utilizando PCA (Análisis de Componentes Principales). El objetivo es recomendar canciones similares a partir de una canción inicial, aplicando técnicas de aprendizaje automático.

Funcionalidades:

	•	Recomendación de Canciones: Dado el nombre de una canción, el sistema recomienda otras canciones similares utilizando PCA y K-means clustering.
	•	Visualización Interactiva: Las recomendaciones se visualizan con imágenes de álbumes y títulos de canciones.
	•	Uso de la API de Spotify: La información sobre las canciones, incluyendo imágenes de álbumes, se obtiene a través de la API de Spotify.

Tecnologías Utilizadas:

	•	Python 3.9.13: Lenguaje de programación utilizado para desarrollar el sistema de recomendación.
	•	Jupyter Notebook: Entorno de desarrollo interactivo utilizado para implementar y probar el código.

Bibliotecas:

	•	Pandas: Para manipulación y análisis de datos.
	•	Numpy: Para cálculos numéricos avanzados.
	•	Matplotlib: Para visualización de gráficos e imágenes.
	•	Seaborn: Para visualización de datos estadísticos.
	•	Plotly Express: Para visualizaciones interactivas.
	•	Scikit-learn: Para la implementación de PCA y K-means.
	•	Spotipy: Para la integración con la API de Spotify y obtención de información de las canciones.
	•	Scikit-Image: Para la visualización de imágenes de álbumes.

Cómo Funciona

	1.	Preprocesamiento de Datos: Se cargan y procesan los datos de las canciones.
	2.	Reducción de Dimensionalidad (PCA): Se aplica la reducción de dimensionalidad para hacer el modelo más eficiente.
	3.	Clustering (K-means): Se utiliza K-means para agrupar canciones similares en clústeres.
	4.	Recomendación: Cuando proporcionas una canción, el sistema encuentra canciones en el mismo clúster y calcula las distancias euclidianas para recomendar las más cercanas.
