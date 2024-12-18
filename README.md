# generador-embeddings
Cuadernos de código abierto para generar, visualizar y explorar _embeddings_ de texto con modelos de lenguaje de la librería [Sentence-Transformers](https://www.sbert.net/)


## Descripción
Cuadernos de código abierto diseñados para importar cualquier cuerpo de texto separado por filas, en formato CSV o Excel, y generar incrustaciones de texto (*embeddings*) para cada fila, que permitan visualizar sus relaciones y agrupaciones semánticas, así como ejecutar consultas de búsqueda semántica, con ayuda de modelos de lenguaje de la librería [sentence-transformers](https://www.sbert.net/), alojados en repositorios de [HuggingFace](https://huggingface.co/sentence-transformers) (en la nube) o descargados localmente.


## Cuadernos
- **Cuaderno 01:** Limpieza y depuración de texto. ([Jupyter Notebook](https://github.com/signalab/generador-embeddings/blob/main/cuadernos/01_Signa_Lab_generador_embeddings_Depuraci%C3%B3n_importar_limpiar_depurar_texto_02.ipynb) / [Google Colab](https://colab.research.google.com/drive/1HH5a-eJ6-gtKQBVojxeKmb_NhxZhCPt2?usp=sharing))

- **Cuaderno 02:** Generación de embeddings y clusterización.([Jupyter Notebook](https://github.com/signalab/generador-embeddings/blob/main/cuadernos/02_Signa_Lab_generador_embeddings_Generar_procesar_reducir_clusterizar_embeddings_02.ipynb) / [Google Colab](https://colab.research.google.com/drive/1QidtVoTqUfyRmWFCqh_IxnwOS11W1g53?usp=sharing))
- **Cuaderno 03:** Exploración de consultas y relaciones semánticas. ([Jupyter Notebook](https://github.com/signalab/generador-embeddings/blob/main/cuadernos/03_Signa_Lab_generador_embeddings_Explorar_visualizar_relaciones_sem%C3%A1nticas_03.ipynb) / [Google Colab](https://colab.research.google.com/drive/1jh6pB3qSWcfVSdHUfG_Mlh44EJSOln0n?usp=sharing))

![SL_generador-embedings_3Dviz-demo_03-min](https://github.com/user-attachments/assets/0ebec356-12f2-44ef-9569-b98f7874530d)


## Tutoriales
Puedes revisar los video tutoriales para guiar tu uso de estos cuadernos en la siguiente [lista de reproducción de YouTube](https://www.youtube.com/watch?v=LSMDd9im_hQ&list=PLR5StpKSfq4bj00-8Ex8-OmxMdzKXA0kl).
[![Ver tutoriales en YouTube](https://github.com/user-attachments/assets/6c06d985-a7bd-4ca9-b015-66f55df8011f)](https://www.youtube.com/watch?v=LSMDd9im_hQ&list=PLR5StpKSfq4bj00-8Ex8-OmxMdzKXA0kl)



## Sobre estos cuadernos
Desde el pensamiento crítico hay cada vez más discusiones acerca de la Inteligencia Artificial y de su incidencia en distintos ámbitos de la realidad social, así como múltiples cursos y experiencias de apropiación crítica de diversas herramientas de Inteligencia Artificial Generativa. Sin embargo, desde el pensamiento crítico hay poco, y en español todavía menos, desarrollo de herramientas con Inteligencia Artificial.

Signa_Lab ITESO ha desarrollado tres cuadernos escritos con Python, ejecutables localmente con [Jupyter Notebooks](https://github.com/signalab/generador-embeddings/tree/main/cuadernos) o desde la plataforma de [Google Colab](https://drive.google.com/drive/folders/1EbiWzfe6h0IbprBVP37o8Be6R8nuHfhN?usp=sharing), para el procesamiento y post-procesamiento de conjuntos de datos textuales. El aspecto diferenciador de este desarrollo, que implementa modelos de IA de software libre, radica en que el énfasis del procesamiento de la información está en los valores categóricos de los datasets, es decir, en los datos cualitativos. 

Los [modelos de lenguaje](https://huggingface.co/sentence-transformers) implementados en estos cuadernos permiten codificar y agrupar similitudes entre fragmentos de texto, que pueden cotejarse con otros posibles metadatos asociados a cada uno, así como con otras técnicas establecidas de Procesamiento de Lenguaje Natural (PNL) para el análisis semántico.

Estos cuadernos son de acceso público e invitan a la comunidad académica, laboratorios, medios de comunicación y entusiastas del análisis crítico de datos, a descargarlos y utilizarlos para la exploración de conjuntos de datos y colecciones de textos en la investigación, la docencia, el periodismo de datos, los estudios de mercado, etc., así como a transformarlos y ampliarlos a partir de desarrollos y necesidades propias, por lo que también les invitamos a compartir este mensaje con aquellas personas y organizaciones a las que pueda interesar este desarrollo.

Los cuadernos desarrollados por Signa_Lab ITESO parten del supuesto de que una mirada centrada en el análisis de los aspectos cualitativos de los datos no tiene como objetivo arrojar resultados acabados ni hacer investigaciones en lugar de las personas, sino ofrecer una serie de insumos (segmentaciones personalizadas de datos con diccionarios, visualizaciones interactivas, generación personalizada de clusters y de interfaces de consulta, etc.) para diseñar, complejizar y potenciar investigaciones de corte cualitativo y mixto.

Nuestro objetivo es contribuir a la generación de rutas que además de buscar la apropiación crítica de la inteligencia artificial, también incentiven el desarrollo de este tipo de herramientas desde el pensamiento crítico.

![DIAGRAMA CUADERNO_01-min](https://github.com/user-attachments/assets/cb174e1a-e1c2-4afa-86f1-ea18acd50f04)

![DIAGRAMA CUADERNO_02-min](https://github.com/user-attachments/assets/5b04e310-6f94-4aeb-87e6-ecc84ce3a371)

![DIAGRAMA CUADERNO_03-min](https://github.com/user-attachments/assets/fc7208a7-1423-4cf9-8fe7-42f58c48626a)



## Dependencias e instalación (para ejecución local)

### Entorno de ejecución
El código desarrollado y contenido en los cuadernos de este repositorio requiere la instalación de [Python versión 3.9](https://www.python.org/downloads/) o más alta.

Aunque el software para ejecutar los cuadernos de código, [Jupter Notebook](https://jupyter.org/install), puede ser instalado de manera individual, se recomienda hacer la instalación completa de la paquetería contenida en [Anaconda](https://www.anaconda.com/download) que, además de Jupyter Notebook, incluye una gran cantidad de las librerías de software libre requeridas para la ejecución del código en los cuadernos de este repositorio. Su instalación es gratuita y compatible con sistemas operativos de Windows, macOS y Linux.

### Librerías y dependencias de Python
Para instalar las dependencias requeridas, cada [cuaderno de código](cuadernos/) contiene una primera celda que debe ejecutarse al inicio para asegurar la correcta instalación de las librerías y herramientas necesarias para replicar el funcionamiento del código.

### Modelo de lenguaje
Entre las alternativas de modelos de lenguaje compatibles con la librería de [sentence-transformers](https://huggingface.co/sentence-transformers) sugeridas en los cuadernos, desde Signa_Lab ITESO hemos optado para el trabajo con texto en español por el modelo [intfloat/multilingual-e5-large-instruct](https://huggingface.co/intfloat/multilingual-e5-large-instruct/tree/main). Este modelo, además de garantizar la transparencia, trazabilidad y replicabilidad de su uso, al ser de software libre, ha producido algunos de los mejores resultados entre las pruebas preliminares realizadas desde el equipo del laboratorio. Lo anterior se atribuye a su mayor densidad semántica (1024 dimensiones), a la presencia considerable de contenido en español en sus datos de entrenamiento (Wang et al, 2024) y a su capacidad de añadir tareas específicas vinculadas a la ejecución de consultas de búsqueda semántica (*instruct*), lo cual permite una mayor precisión en la orientación de consultas por búsqueda semántica.

Este modelo, así como el resto de los modelos sugeridos, puede ser ejecutado tanto desde su repositorio en la nube como localmente, [descargando sus archivos](https://huggingface.co/intfloat/multilingual-e5-large-instruct/tree/main) y alojándolos en una carpeta, de la que se debe indicar su ruta:

```Python
# Ejemplo de ruta para cargar modelo de lenguaje localmente desde una carpeta con todos sus archivos:
modelo = "./modelos/multilingual-e5-large-instruct"

# Ejemplo de ruta para cargar modelo de lenguaje desde repositorio en la nube de Hugging Face:
modelo = "intfloat/multilingual-e5-large-instruct"

# Cargar modelo para embeddings
embedder = SentenceTransformer(modelo)
```

## Licencia
El código y contenidos de este repositorio están publicados como software libre bajo la [Licencia MIT](LICENSE), que corresponde a la misma licencia del modelo de lenguaje sugerido por default [intfloat/multilingual-e5-large-instruct](https://huggingface.co/intfloat/multilingual-e5-large-instruct)


## Créditos
**Realizado por el equipo de Signa_Lab ITESO:**

- **Programación de cuadernos de código (Python)**: 
Javier de la Torre Silva, José Luis Almendarez González y Diego Arredondo Ortiz

- **Supervisión del desarrollo tecnológico y documentación:** 
Diego Arredondo Ortiz

- **Equipo de Coordinación Signa_Lab ITESO:** 
Paloma López Portillo Vázquez, Víctor Hugo Ábrego Molina y Eduardo G. de Quevedo Sánchez

Octubre, 2024. Instituto Tecnológico y de Estudios Superiores de Occidente (ITESO) Tlaquepaque, Jalisco, México.

## Referencias
- Bird, Steven, Edward Loper & Ewan Klein (2009). *Natural Language Processing with Python*. O'Reilly Media Inc.
- Hunston, S. (2022). *Corpora in Applied Linguistics* (2a ed.). Cambridge University Press. [https://doi.org/10.1017/9781108616218](https://doi.org/10.1017/9781108616218)
- Kiss, T., & Strunk, J. (2006). *Unsupervised Multilingual Sentence Boundary Detection*. Computational Linguistics, 32(4), 485-525. [https://doi.org/10.1162/coli.2006.32.4.485](https://doi.org/10.1162/coli.2006.32.4.485)
- Longhi, J. (2021). *Mapping information and identifying disinformation based on digital humanities methods: From accuracy to plasticity*. Digital Scholarship in the Humanities, 36 (4), 980–998. [https://doi.org/10.1093/llc/fqab005](https://doi.org/10.1093/llc/fqab005)
- McInnes, L., Healy, J., & Melville, J. (2018). *Umap: Uniform manifold approximation and projection for dimension reduction*. arXiv preprint arXiv:1802.03426. [https://arxiv.org/abs/1802.03426](https://arxiv.org/abs/1802.03426)
- Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., Blondel, M., Prettenhofer, P., Weiss, R., Dubourg, V., Vanderplas, J., Passos, A., Cournapeau, D., Brucher, M., Perrot, M., Duchesnay, E., & others. (2011). *Scikit-learn: Machine Learning in Python*. Journal of Machine Learning Research, 12, 2825–2830.
- Reimers, N., & Gurevych, I. (2019). *Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks* (arXiv:1908.10084). arXiv. [http://arxiv.org/abs/1908.10084](http://arxiv.org/abs/1908.10084)
- Rousseeuw, P. (1987). *Silhouettes: a Graphical Aid to the Interpretation and Validation of Cluster Analysis*. Computational and Applied Mathematics. 20: 53–65. doi:10.1016/0377-0427(87)90125-7.
- Spärck-Jones, K. (1972). A statistical interpretation of term specificity and its application in retrieval. Journal of Documentation, 28(1), 11-21. [https://www.staff.city.ac.uk/~sbrp622/idfpapers/ksj_orig.pdf](https://www.staff.city.ac.uk/~sbrp622/idfpapers/ksj_orig.pdf)
- Wang, L., Yang, N., Huang, X., Yang, L., Majumder, R., & Wei, F. (2024). *Multilingual E5 Text Embeddings: A Technical Report* (arXiv:2402.05672). arXiv. [http://arxiv.org/abs/2402.05672](http://arxiv.org/abs/2402.05672)
