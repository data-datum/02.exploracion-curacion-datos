# Repositorio de la materia "Exploración y Curación de Datos"
#### Diplomatura en Ciencia de Datos, Aprendizaje Automático y sus Aplicaciones. *Edición 2021*

Integrantes:
* Devesa, Maria Roberta. 
* Feldfeber, Ivana. 
* Finzi, Nadia. 
* Kinigsberg, Ezequiel. 
* Villafañe, Roxana Noelia


En este repositorio se encuentran los dos notebooks correspondientes a los dos entregables de la materia:
"Exploración y Curación de Datos". 
* Sitio web de la materia: https://diplodatos.famaf.unc.edu.ar/analisis-y-curacion-de-datos/ 

### Documentación

#### Datasets


* El conjunto de datos pre-procesado sobre [estimación de precios de ventas de propiedades](https://www.kaggle.com/dansbecker/melbourne-housing-snapshot) en Melbourne, Australia, disponible en la plataforma Kaggle. 
* Un conjunto de datos de [scrapings del sitio AirBnb](https://www.kaggle.com/tylerx/melbourne-airbnb-open-data?select=cleansed_listings_dec18.csv) para la ciudad de Melbourne, Australia, 2018, disponibilizado por Tyler Xie, a través de la plataforma Kaggle.



#### Entregable 1

Referido a las clases 1 y 2 de la materia.

*Temas:* 
* Exploración, 
* combinación de datasets 
* datos ruidosos.

Breve descripción

#### Entregable 2 

Referido a las clases 3 y 4 de la materia. 

*Temas:* 
* sesgo, 
* transformaciones, 
* normalización.

**Breve descripción**

* En primer se realizó un encoding de las variables excepto `BuildingArea` y `YearBuilt`, mediante la función `OneHotEncoder`.
* Posteriormente, las variables  `BuildingArea` y `YearBuilt` se imputaron mediante `IterativeImputer` con un estimador `KNNRegressor`. Se graficaron las distribuciones de valores antes y después de imputar con KNN. 
* Luego, estos resultados se procesaron mediante Análisis de Componentes Principales (PCA) y se graficaron las varianzas acumuladas en cada componente principal. 
* Se agregaron las columnas correspondientes del análisis de PCA a la matriz original de datos. 
* Composición de resultado. -------- completar
* Se documentaron los pasos realizados. 

