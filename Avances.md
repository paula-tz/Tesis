
# Geografía del agua en superficie en hiperllanuras semiáridas a subhúmedas
##### Torre Zaffaroni, P.; Di Bella, C.M.; Jobbágy, E.G.

## Introducción
Estudiar la dinámica del agua en superficie a nivel global ayuda no sólo a comprender estos sistemas, sino que también puede dar indicios sobre la adaptación de cada región a la mayor o menor disponibilidad de agua.

Las hipótesis que guían el siguiente trabajo son: 
+ *a* el balance hídrico determina la extensión del ACA;
+ *b* la variabilidad del ACA presenta una respuesta tipo parabólica respecto al balance hídrico, dado que en situaciones intermedias se alternan años secos con ACAs menores y años húmedos con ACAs mayores; 
+ *c* las características del suelo de cada región determinan la extensión del ACA y su permanencia, dado que incide en la capacidad de eliminar los excedentes de agua.

## Metodología
### Selección de las regiones de estudio
Se seleccionaron siete hiperllanuras (*i.e.* áreas extensas con pendiente regional <0,1%) bajo balances hídricos promedios de entre 0,3 y 0,8 (Figura 1). 
La delimitación de cada región responde a los límites de balance hídrico, a los límites topográficos por presencia de cadenas montañosas, y a los límites hidrológicos en aquellas regiones donde hay cursos de agua con influencia exógena al sistema bajo estudio *e.g.* los ríos Danubio, Paraná y Songhua en la Llanura Húngara, Pampa-Chaco y Songnen, respectivamente).
Quedaron entonces definidas las siguientes regiones \colorbox{yellow}{quizás no va esto}:

1. *Australia*: km<sup>2</sup>, balance hídrico promedio de 0,30. 
Su delimitación corresponde a límites climáticos. Abarca la porción semiárida de la cuenca Murray-Darling (cuenca alta). 
2. *Sahel*: km<sup>2</sup>, balance hídrico promedio de 0,31. 
Su delimitación corresponde a límites climáticos. Abarca la porción semiárida de la cuenca del Río Niger (cuenca media).
3. *Songnen*: km<sup>2</sup>, balance hídrico promedio de 0,52. 
Su delimitación corresponde a límites topográficos. Comprende la cuenca alta del Río Nen. 
4. *Pampa-Chaco*: km<sup>2</sup>, balance hídrico promedio de 0,56. 
Su delimitación corresponde a límites climáticos y, hacia el este, a la exclusión del área cercana al Río Paraná
5. *Llanura Húngara*: km<sup>2</sup>, balance hídrico promedio de 0,66. 
Su delimitación corresponde a límites topográficos y, hacia el oeste, a la exclusión del Río Danubio y su área cercana.
6. *Saskatchewan*: km<sup>2</sup>, balance hídrico promedio de 0,66.
Su delimitación corresponde a límites climáticos y topográficos.  Comprende la porción subhúmeda de cuenca del Río Saskatchewan.
7. *Siberia Occidental*: km<sup>2</sup>, balance hídrico promedio de 0,72. 
Su delimitación corresponde a límites climáticos y topográficos. Comprende la porción subhúmeda de la cuenca del Río Ob (cuenca alta comprende Ríos Ishit, Irtish y Tobol)

![Figura 1: Distribución geográfica de las regiones bajo estudio]("Tesis/ROI.png")


### Cuantificación del área cubierta por agua (ACA)
Se trabajó con el producto de clasificación de agua realizado por el *Joint Research Centre* en base a imágenes Landsat con una resolución mensual. A este dataset se le aplicó un filtro de calidad, donde una imagen debía poseer al menos un 75% de sus píxeles con observaciones válidas para poder ser incluida en el análisis. En el caso de las métricas anuales, esa mínima proporción debía asimismo tener, al menos, 5 datos válidos en el año para poder ser analizado. De esta manera, se analizaron regiones con una menor extensión temporal (los análisis de la Llanura Húngara, el Sahel y Siberia Occidental comienzan en 2000, 2000 y 2006, respectivamente). Se decidió no excluir estas regiones ya que la información puede, de todas formas, ser útil para comprender la dinámica del agua en superficie. 
Las regiones boreales (Saskatchewan, Songnen, Hungría y Siberia Occidental), asimismo, no cuentan con datos entre noviembre y febrero 
dado que, por el bajo ángulo de elevación solar y fotoperiodo en invierno, las imágenes correspondientes no fueron clasificadas originalmente.

Los descriptores del ACA por región fueron calculados en función de la extensión de cada región. Estos son: 
*ACA promedio anual*, *ACA máximo*, *Permanencia promedio del ACA*, *Variabilidad intra-anual del ACA* y *Variabilidad inter-anual del ACA*. 

### Variables meteorológicas
La descripción de la variación del agua en el suelo fue realizada a partir de GRACE. Los valores presentados de TWS corresponden a variaciones, mensuales o anuales, respecto a la media (base tomada para el período 2004-2009).
Los datos de precipitación y evapotranspiración potencial fueron derivados a partir de los datos TerraClimate, el cual usa información de WorldClim, CRU el JRA55 para generar interpolaciones con una resolución temporal mensual y espacial de ~0,04º.

### Variables edáficas
Se obtuvieron valores promedio de contenido de carbono orgánico (SOC), densidad aparente, ==partición arena/limo, arena/arcilla...==
 a partir del *Global Soil Dataset for Earth System Modelling*


## Resultados

A lo largo de las hiperllanuras se pueden diferenciar dos comportamientos del agua en superficie. Por un lado, una distribución restringida a los cursos de agua y, en menor medida, a cuerpos de agua de pequeño tamaño y corta permanencia. Por otro lado, una mayor expansión del agua por sobre las llanuras de inundación y por cuerpos de agua de diversa extensión y permanencia.

Este patrón de comportamiento está relacionado al balance hídrico, en tanto se observó un cambio progresivo de la primera situación hacia la segunda, en igual sentido que el progresivo aumento del balance hídrico, aunque no en iguales magnitudes. Tanto en Australia como en el Sahel, el agua estuvo restringida a los cursos predominantes (Río Murray y afluentes del Río Darling en Australia y el Río Níger en el Sahel), aunque también se encontraron algunos cuerpos de agua de pequeño tamaño. En Songnen, debido a que el Río Nen posee una llanura de inundación muy amplia, la situación es intermedia entre restringida y extensiva. El agua se concentró sobre la llanura de inundación y sus cercanías, con cuerpos de mayores tamaños. En Pampa-Chaco, por otro lado, se encontraron diferencias entre el Norte predominantemente semiárido y el Sur subhúmedo. En el Norte, el agua se restringió a los cursos de agua que allí se extienden; en una región intermedia se detectó la presencia de numerosos cuerpos de agua de pequeño tamaño, mientras que en el Sur predominaron los cuerpos de agua de diversos tamaños. La Llanura Húngara, si bien posee un balance mayor a Songnen y Pampa-Chaco, presentó una extensión del agua restringida al Río Tisza, con poca ampliación sobre sus proximidades. Cabe resaltar la gran diferencia entre esta región y Saskatchewan y Siberia Occidental, que bajo el mismo balance promedio, la extensión del ACA fue en ambas regiones marcadamente extensiva, con una presencia importante de cuerpos de agua de diversos tamaños a lo largo de toda la región.
 
La relación entre la extensión del agua en superficie y el balance hídrico es esperable, ya que a relaciones más cercanas a la unidad hay una menor limitación hídrica, lo cual puede más frecuentemente traducirse en excesos hídricos que se acumulan en la superficie (Figura 2). Esta relación tiene como salvedad a la Llanura Húngara, como se observaba anteriormente, ya que posee balance subhúmedo y sin embargo, tiene un comportamiento de agua en superficie restringido en el área. ==figuras de la extension del agua en SI?==

El área cubierta por agua (ACA) promedio en las regiones estudiadas no excedió el 8% de la superficie total de cada región, y el área máxima registrada no superó, en ningún caso, el 12% (Tabla 1). La permanencia promedio del ACA fue menor a los 4 meses y, analizando series temporales, se observó una asociación directa fuerte (R<sup>2</sup> > 0,7) entre la extensión del ACA y su permanencia. Es decir, que incrementos del ACA se asociaron a incrementos en la permanencia del agua en la superficie en el mismo año.

Si bien las regiones de balances semiáridos presentaron menores ACA promedio, mientras que para las regiones subhúmedas los valores fueron mayores, la variabilidad relativa (coeficiente de variación, CV) no siguió un patrón de igual sentido (Tabla 1). La variabilidad interanual, en todos los casos, se encontró entre un 20 y 33%. Los mayores valores pertenecieron a Saskatchewan, Siberia Occidental y Australia. Por otro lado, a nivel mensual, los valores promedio siguieron el mismo patrón que los valores anuales, y la variabilidad intra anual varió entre 10 y 27%, siendo Sahel la región con la mayor variabilidad, seguida por Songnen, Australia y Siberia Occidental (Tabla 1). En general, la mayor variabilidad intra-anual está asociada a la mayor estacionalidad de la precipitación y a la ocurrencia del deshielo (Figura 3a-f). 

| Región| Régimen Hídrico| PPT promedio (mm/año)| PET promedio (mm/año)| ACA promedio (%)| ACA máximo (%) | Duración promedio (meses)| Variabilidad intra anual (%) | Variabilidad inter anual (%)|
| ------------- |:-------------:| -----:|---|---|---|---|---|---|
| Australia     | Semiárido (0,30) | 462 ± 103 | |0,68 ± 0,23|1,21|2,17±0,6|16,28|33,83|
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
\noindent\makebox[\textwidth]{
\fontsize{9}{11}\selectfont
\begin{tabular}{ |p{2.7cm}||p{2.7cm}|p{1.5cm}|p{2cm}|p{2cm}|p{1.2cm}|p{1.5cm}|p{1.5cm}|p{1.5cm}| }
 \hline
 Región&Régimen Hídrico&PPT promedio (mm/año)&PET promedio (mm/año) &ACA promedio (\%) & ACA máximo (\%)&Duración promedio (meses) &Variabilidad intra anual (\%)& Variabilidad inter anual (\%)\\
 \hline
 \hline Australia   &Semiárido (0,30)    &462 \underline{+}103& & 0,68 \underline{+}0,23 & 1,21 & 2,17\underline{+}0,6 & 16,28 & 33,83\\
 \hline Sahel&   Semiárido (0,31)  & 654 \underline{+}73& & 0,34 \underline{+}0,07 & 0,51 & 2,19\underline{+}0,8 & 27,78 & 20,59\\
 \hline Songnen &Semiárido (0,52) & 453 \underline{+}85& 853\underline{+}44 & 3,25 \underline{+}0,88 & 5,41 & 1,87\underline{+}0,61 & 16,89 & 27,08\\
 \hline Chaco-Pampa    &Subhúmedo (0,56) & 812 \underline{+}104& 1452\underline{+}36 & 2,12 \underline{+}0,48 & 2,99 & 3,49\underline{+}1,08 & 10,7 & 22,64\\
 \hline Llanura Húngara&   Subhúmedo (0,66)  & 555 \underline{+}108& 854\underline{+}58 & 1,50 \underline{+}0,52 & 2,34 & 2,72\underline{+}0,7 & 12,17 & 28\\
 \hline Saskatchewan& Subhúmedo (0,66)  & 446 \underline{+}59& & 7,30 \underline{+}2,36 & 12,20 & 2,37\underline{+}0,8 & 10,35 & 32,33\\
 \hline Siberia Occidental& Subhúmedo (0,72)  & 429 \underline{+}53& & 4,65 \underline{+}1,48 & 6,43 & 2,51\underline{+}0,8 & 16,07 & 31,83\\
 \hline
\end{tabular}}
\\
\\
\includegraphics{balance_area.jpg}\label{bal_area}\centering
\\{Figura 2: }

\justifying\subsection{Dinámica del ACA intra-anual}
\indent A grandes rasgos, la dinámica del agua en superficie está asociada a las variaciones del agua en el suelo (TWS) 
con mayor o menor fuerza (R\textsuperscript{2} entre 0,18 y 0,56). 
Las relaciones son más fuertes en las regiones semiáridas y más débiles en las regiones subhúmedas. 
Por otro lado, la precipitación no está asociada a las variaciones del agua en el suelo ni del ACA (Figura 3a-g). \\

\subsection{Dinámica del ACA inter-anual}

\subsection{Descripción por región}
\indent A continuación se describe la dinámica intra anual de los parámetros 
meteorológicos (precipitación y evapotranspiración potencial) e hidrológicos (variación de 
agua en el suelo y ACA) y la dinámica inter anual del ACA en cada región, en sentido 
creciente de balance hídrico. Las comparaciones entre regiones pueden verse en las 
Figuras 3 y 4. En grandes rasgos, se observa cómo, a escala mensual, el ACA está asociada a la variación de agua en el suelo, en distinta medida, mientras que hay una disociación entre el ACA y la precipitación, y entre la precipitación y las variaciones de agua en el suelo. A escala anual, existen asociaciones más fuertes entre el ACA y la variación de agua en el suelo, así como entre la precipitación y las variaciones de agua en el suelo. 
\indent\subsubsection {\textit{Australia} (balance promedio 0,3; semiárido)}

\indent La extensión del agua en superficie en Australia es restringida a cuerpos de agua de pequeña extensión y permanencia, distribuidos en “parches” (concentración en ciertas áreas, p. ej. norte y sur), muchos con formas antropogénicas coincidentes con parcelas demarcadas (\colorbox{yellow}{ver}). En un año promedio (Figura 3a), la variación del agua en el suelo (TWS) es positiva en invierno y negativa en verano (máximo en julio, +4,5\%, mínimo en enero, -0.5\%). La precipitación (PPT) no varía en gran medida (aprox. 45 mm/mes), mientras que la evapotranspiración potencial (PET) sí lo hace, presentando un máximo en verano y un mínimo en invierno (225 y 50 mm/mes, respectivamente). Finalmente, el área cubierta por agua (ACA) es baja (0,3\%) y no varía en el año, excepto en invierno cuando desciende levemente. En este sentido, la dinámica intra-anual o mensual del ACA está asociada principalmente a la variación de agua en el suelo (R\textsuperscript{2} = 0,4482), mientras que está disociada de la precipitación. \\
\indent A lo largo de los años analizados (1988-2014; Figura 4a), se observa una baja variación al comienzo de la serie (1987-2001), una variación negativa sostenida entre 2002 y 2010 y un posterior aumento del ACA con mayor variación entre años. La variación negativa condice con la sequía decadal occurida entre 2002 y 2010, con un posterior aumento de la PPT que se ve reflejado en el aumento del ACA. La variación del ACA muestra una fuerte asociación a las variaciones del agua en el suelo (R\textsuperscript{2} = 0,8028), una menor asociación a la precipitación (R\textsuperscript{2} = 0,2708) y una asociación muy baja entre la PPT y el TWS (R\textsuperscript{2} = 0,1178). Asimismo, se observa una sincronía alta entre el área cubierta por agua y la permanencia de la misma (R\textsuperscript{2} = 0,8391). \\

\indent\subsubsection {\textit{Sahel} (balance promedio 0,31; semiárido)}

\indent La extensión del agua en superficie en el Sahel es restringida al principal curso de agua en la región, el Río Niger. En un año promedio (Figura 3b), el TWS presenta la mayor variación intra anual de las siete regiones (-6\% en mayo a 11\% en septiembre), dinámica marcada principalmente por el ingreso de agua como precipitación. La PPT, monzónica, comienza en abril y tiene un máximo en agosto (200 mm) y, en respuesta, el TWS incrementa con un mes de desfasaje. El ACA también sigue esta dinámica, desfasado respecto a la TWS. Aumenta entre junio y octubre (a 0,25\%), y luego se mantiene sin variaciones hasta febrero, cuando disminuye (hasta un 0,1\%). En este sentido, la dinámica mensual del ACA está acoplada fuertemente a las variaciones de agua en el suelo (R\textsuperscript{2} = 0,5639), no así a la precipitación. Sí hay una muy baja asociación entre la precipitación y las variaciones de agua en el suelo (R\textsuperscript{2} = 0,1048), al igual que en Australia. \\
\indent A lo largo de la serie analizada (2000-2014; Figura 4b), hay una sincronía entre el ACA y la permanencia del mismo (R\textsuperscript{2} = 0,8839), y ambos presentan bajas variaciones (mayor en la duración que en el ACA) hasta 2012. La variación del ACA es explicada en cierta medida por las variaciones del agua en el suelo (R\textsuperscript{2} = 0,3961) y por la precipitación (R\textsuperscript{2} = 0,2459), pero estas variables están disociadas. \\

\indent\subsubsection {\textit{Songnen} (balance promedio 0,52; semiárido)}

\indent La extensión del agua en superficie en Songnen es intermedia entre restringida y extensiva, pues el Río Nen, que atraviesa la región, posee una llanura de inundación muy amplia y en sus proximidades se encuentran cuerpos de mediano a gran tamaño. En un año promedio (Figura 3c), el TWS tiene una variación baja, con recargas de hasta 1\% y reducciones hasta un -1\%. La PPT es estacional, máxima en Julio (140 mm) y nula en invierno. El máximo del TWS en agosto parecería seguir al máximo de PPT en Julio. El ACA, por otro lado, tiene un comportamiento estacional-bimodal, con una tendencia de aumento hasta el 2\% en mayo, seguido por una disminución en junio, similar a la del TWS y un nuevo aumento post-PPT, cuando alcanza el 2,7\% de la superficie en agosto. En este sentido, la dinámica mensual del ACA está acoplada en cierta medida a las variaciones del agua en el suelo (R\textsuperscript{2} = 0,3239), aunque éstas no se asocian a la precipitación.\\
\indent Durante el período analizado (1986-2014; Figura 4c), se observa que la variación del ACA y de la duración es baja, con casos de mínimos en 1986 y 1997, y un máximo en 2013-14. La sincronía entre los dos descriptores es alta (R\textsuperscript{2} = 0,8739) y el acoplamiento más importante del ACA se da con el TWS (R\textsuperscript{2} = 0,8351), mientras que se sostiene la disociación entre la precipitación y el TWS, y entre la precipitación y el ACA. \\

\indent\subsubsection {\textit{Chaco-Pampa} (balance promedio 0,56; intermedio entre semiárido y subhúmedo)}

\indent La extensión del agua en superficie en Argentina difiere entre el Norte, región semiárida, y el Sur, subhúmedo. En la región más semiárida, el agua se restringe a los cursos de agua que allí se extienden; en una región intermedia se detecta la presencia de numerosos cuerpos de agua de pequeño tamaño; mientras que en la región más subhúmeda, predominan los cuerpos de agua de diversos tamaños. En un año promedio (Figura 3d), el TWS presenta variaciones mes a mes, con aumentos de 1\% y reducciones de 0,5\%, con un máximo de 4\%. El hecho de que todas las variaciones sean positivas, puede indicar que, a lo largo de la serie analizada (2002-2014) haya una tendencia de esta variable que asimismo pueda estar influyendo en los valores promedio de cada mes. Por otro lado, la precipitación es estacional con máximos en verano (aprox. 100 mm/mes) y mínimos entre mayo y agosto (30 mm/mes), con una similar dinámica del PET. El ACA es estable en verano, alrededor del 1\%, y presenta una disminución en junio y seguido aumento en agosto. Estas dinámicas variables se reflejan en una baja asociación entre el ACA y la precipitación y entre la precipitación y las variaciones del agua en el suelo, y se encontró un acoplamiento medianamente fuerte (R\textsuperscript{2} = 0,4087) entre el ACA y el TWS. \\
\indent A lo largo de los años analizados (1986-2014; Figura 4d), si bien se observa que la duración es más variable que el ACA, existe una sincronía entre ambos (R\textsuperscript{2} = 0,8356). Se halla un acoplamiento fuerte (R\textsuperscript{2} = 0,8225) entre el ACA y el TWS, al igual que en Songnen, y una baja asociación con la precipitación (R\textsuperscript{2} = 0,1218). La relación entre la PPT y el TWS es la más alta (R\textsuperscript{2} = 0,4293) entre las regiones estudiadas. \\

\indent\subsubsection {\textit{Llanura Húngara} (balance promedio 0,66; subhúmedo)}

\indent La extensión del agua en superficie en la Llanura Húngara es restringida al principal curso de agua, el Río Tisza. A nivel de región, ésta posee la menor área inundada entre las regiones subhúmedas. En un año promedio (Figura 3e), las variaciones del agua en el suelo son marcadas, con un período de recarga entre febrero y abril (6\%) y un período de depleción entre agosto y octubre (-6\%). La precipitación es poco variable y tiene su máximo en junio (aprox. 70mm). Durante los meses invernales, la PPT excede a la PET, lo cual podría explicar la recarga del agua en el suelo. El ACA parecería tener una dinámica marcada por las estaciones libres de hielo (marzo a octubre), ya que tiene un máximo en abril y luego disminuye y se mantiene estable alrededor del 1\%. El acoplamiento mensual del ACA a las variaciones de agua en el suelo es baja (R\textsuperscript{2} = 0,2585), y es nulo entre el ACA y la precipitación y entre la PPT y el TWS.\\
\indent Durante la serie analizada (2000-2014; Figura 4e), se observan mayores variaciones, tanto del ACA como de la duración (sincronía menor al resto, R\textsuperscript{2} = 0,7924). El ACA guarda una relación medianamente fuerte con el TWS (R\textsuperscript{2} = 0,3772) y nula con la precipitación, mientras que existe también una relación medianamente fuerte entre el TWS y la PPT (R\textsuperscript{2} = 0,3523). \\
	
\indent\subsubsection {\textit{Saskatchewan} (balance promedio 0,69; subhúmedo)}

\indent La extensión del agua en superficie en Saskatchewan es extensiva, con un gran número de cuerpos de agua. Es la región con la mayor extensión de ACA, llegando a un máximo del 12\% (en 2011). En un año promedio (Figura 3f), las variaciones de agua en el suelo son marcadas, recargándose entre invierno y primavera (máximo en junio, 4\%) y descargándose en verano-otoño (mínimo en octubre, -4,5\%). La precipitación es más o menos variable, con un máximos estivales (80 mm en junio) y mínimos invernales, en forma de nieve (20 mm en ), sugiriendo que el máximo en junio del TWS podría estar asociado a la precipitación. La evapotranspiración potrencial sigue, con mayor variabilidad, a la dinámica de la PPT. El ACA se dispara con gran magnitud, posiblemente por el deshielo (8\% en mayo) y luego se mantiene estable alrededor del 7\% de la superficie. En este sentido, a nivel mensual el ACA no guarda relación con la precipitación, y si lo hace, en cierta medida (R\textsuperscript{2} = 0,1814) con las variaciones del agua en el suelo. A esta escala, no se observa relación entre el TWS y la PPT.\\
\indent A lo largo de la serie analizada (1986-2014; Figura 4f), se observa una variación anual cíclica en el comienzo de la serie, con años más húmedos (mayor ACA y duración) seguidos de años más secos (menor ACA y duración). A partir del 2002, esta dinámica se “achata”, disminuyendo la variación anual y aumentando el valor medio de ambos descriptores, con 2012 figurando como año seco (gran cambio del ACA y duración de 2011 a 2012). La sincronía entre ACA y duración es muy alta (R\textsuperscript{2} = 0,9865). El ACA está asociado al TWS, pero no en gran medida (R\textsuperscript{2} = 0,4311), y está disociado de la precipitación, al igual que el TWS.\\

\indent\subsubsection {\textit{Siberia Occidental} (balance promedio 0,72; subhúmedo)}

\indent La extensión del agua en superficie en la llanura siberiana es extensiva en la región sudoeste, mientras que al este se restringe al principal curso de agua, el Río Ob. Cabe resaltar que esta región posee una serie de análisis muy corta, desde 2006 en adelante, debido a que los años anteriores no poseían una proporción adecuada de píxeles con, al menos, 5 datos en cada año. En un año promedio (Figura 3g), la dinámica del agua en el suelo es muy variable, presentando un período de recarga en primavera (máximo en mayo, 6\%) y de descarga en verano (mínimo en septiembre, -7\%). La precipitación lleva casi una dinámica opuesta, teniendo un máximo en verano (70 mm en julio) y mínimos en invierno (aprox. 20 mm/mes). El ACA, de forma similar que en Canadá, se dispara luego del deshielo (máximo de 4,5\% en mayo), luego disminuye hasta un 3\%. A nivel mensual, el ACA está fuertemente asociado a las variaciones del TWS (R\textsuperscript{2} = 0,4557), mientras que está disociado de la precipitación, y ésta del TWS.\\
\indent Durante los años analizados (2006-2014; Figura 4g), si bien es una serie muy corta, se observa que la variabilidad del ACA es menor a la de la duración. A esta escala, el ACA no se asocia ni a la PPT ni al TWS, mientras que estos dos tienen una asociación media (R\textsuperscript{2} = 0,2726). \\

\indent En resumen, todas las regiones, a nivel mensual, muestran un acoplamiento del área cubierta por agua a las variaciones de agua en el suelo únicamente, mientras que ninguna de las dos variables es influenciada por la precipitación. A nivel anual, en cambio, se pueden diferenciar dos situaciones: por un lado, las regiones con balances más áridos muestran buenas asociaciones entre el área cubierta por agua y las variaciones de agua en el suelo y bajas correlaciones entre el área cubierta por agua y la precipitación, y entre la precipitación y las variaciones de agua en el suelo. Por otro lado, regiones con balances más húmedos presentan asociaciones tanto entre el área cubierta por agua y las variaciones de agua en el suelo, como entre la precipitación y las variaciones de agua en el suelo. Finalmente, Siberia Occidental es la única de las siete regiones estudiadas en la que no se halló una relación entre el área cubierta por agua y las variaciones de agua en el suelo.\\
 
\noindent\makebox[\textwidth]{\includegraphics[width=0.9\paperwidth]{verticales-m.pdf}}
\\{Figura 3: Corrida mensual en un año promedio del área cubierta por agua (ACA), precipitación (PPT), evapotranspiración potencial (PET) y variación de agua en el suelo (TWS) y relación entre las variables principales (ACA, PPT, TWS) en cada región}

\noindent\makebox[\textwidth]{\includegraphics[width=0.9\paperwidth]{verticales-a.pdf}}
\\{Figura 4: Corrida anual del área cubierta por agua (ACA) y su duración, y relación entre las variables principales (ACA, PPT, TWS) en cada región}

\section{Discusión}
\color{red}{Relación entre área y balance (figura), diferencia entre sistemas a nivel anual (hacer dos esquemas generales, para semiáridos y para subhúmedos). A nivel mensual las relaciones son más débiles y no mejoran con lags. ¿Qué otros factores pueden estar incidiendo? Tipo de suelo...}
  \\
\color{black}{\indent En todas las regiones, excepto Siberia Occidental, la extensión del área cubierta por agua está muy acoplada a las variaciones del agua en el suelo y, en aquellas regiones con períodos invernales crudos, al deshielo. \\
\indent Dado que no se observa una relación entre la entrada de agua al sistema como precipitación y la acumulación de agua en superficie, sino que ésta se relaciona más al componente suelo, podríamos hablar de una diferencia en cómo se comporta el sistema. Mientras que en algunas zonas se acumula el agua en la superficie como consecuencia directa de una precipitación local fuerte (flecha gruesa entre PPT y área), en las hiperllanuras semiáridas a subhúmedas se da un camino indirecto entre la PPT y el ACA, mediado por la actividad buffer del suelo. De esta manera, la precipitación determina una parte de la recarga del agua en el suelo (asociación positiva entre PPT y TWS), y es esa variación en el suelo la que determina una mayor o menor área inundable.} \\
\indent Teniendo en cuenta esto, un aspecto a estudiar es si los tipos de suelos predominantes en cada región pueden, a través de la distinta estructura del suelo, estar relacionados también a la extensión del ACA. \\
\indent Asimismo, la modificación de la estructura o de la capacidad de infiltración puede verse reflejado en el ACA. Así, prácticas que aumentan la infiltración, como la red de drenes realizada en Hungría, conllevan que el área inundada sea menor y restringida a los cursos de agua. \\
\begin{displayquote}
The history of drainage in Hungary goes back to the last century, when it was closely linked to those immense works of river regulation and flood protection which have transformed the Hungarian Plains from wetland to a fertile agricultural area. The proprietors of land that was no longer exposed to flooding, formed polder societies for the construction of drainage systems in order to remove also excess precipitation from local origin. This was necessary since the natural drainage of these areas through dead river branches and channels was cut off by the construction of dykes, so that canal networks had to be dug and their collected water to be lead, or lifted into the rivers. As potential evapotranspiration in these plains largely exceeds precipitation, and the supply of external water from the flooding rivers had been excluded, the groundwater table has generally sunk well below the root zone. The constructed drainage canals did not therefore serve in the long run for groundwater level regulation, but rather for relieving the arable land of logging surface waters originating, mainly in the spring period, from unfavourable infiltration conditions of the upper soil layer.\\
\textit{K. Csontos (1987:156)}
\end{displayquote}
\begin{displayquote}
As a result of climatic, geomorphological and hydrological conditions, 
25.3\% of the 4.3 million ha of Hungarian arable lands is vulnerable
to groundwater flooding (River Basin Management Plan of
Hungary – RBMPH, 2010). An extensive canal system protects these
arable lands that lie on former wetlands; they channelled an average
of 1.77 x 10\textsuperscript{9} m\textsuperscript{3}.y\textsuperscript{-1} of groundwater into the river system between
1982 and 2006 (Hungarian Hydrological Yearbooks, 1983–2007).\\
Risk from
groundwater floods is highest in January–March and in June, periods
that coincide with the peak of floods. The high waters in June,
however, precede the drought-prone summer months.\\
\textit{Pinke 2018}
\end{displayquote}

\section{Conclusiones}
\begin{itemize}
\item Extensiones – el agua en superficie en las hiperllanuras semiáridas a subhúmedas cubre, en general, una baja proporción del área total. Sin embargo se pueden encontrar algunos patrones en cuanto a su distribución espacial. Se distinguen dos distribuciones en función del balance hídrico: por un lado, sistemas semiáridos con distribución restringida a cursos de agua; por otro, sistemas subhúmedos con distribución extensiva, con presencia de un gran número de cuerpos de agua de diverso tamaño. En una situación intermedia, tanto de balance como de distribución espacial del ACA, se encuentran Songnen, donde la distribución espacial se centra en la amplia llanura de inundación del Río Nen; y Pampa-Chaco, donde se presentan ambas distribuciones, ya que posee una región con balance semiárido y distribución restringida (al norte), y otra con balance subhúmedo y distribución extensiva (sur).
\item Relación con balance – se encontró un buen ajuste entre el balance hídrico promedio y la extensión promedio y máxima del ACA (R\textsuperscript{2} = 0,54). Si bien esto es esperable – áreas con balances mayores presentarían más excesos de agua que se acumulan en superficie – es interesante de analizar 
\item Relación con factores – pesa más el invierno en las regiones con cobertura de hielo, porque marca más cuando se hace disponible el agua que cayó durante el invierno o justo antes. Como TWS junta un montón de cosas, tiene sentido que esté muy asociado al ACA. Y es interesante que la PPT no explique más del 27\% a nivel anual ni 2\% a nivel mensual (incluyendo desfasajes – lags). 
\item Existencia de otros factores
\end{itemize}


\noindent\makebox[\textwidth]{\includegraphics[width=0.75\paperwidth]{box-a.jpg}}
\\{\fontsize{9}{11}\selectfont Figura : Box-plot del área cubierta por agua anual en cada región estudiada. Los puntos dentro de la caja y sus valores indicados corresponden a la media de cada región, mientras que las barras corresponden a los cuartiles 2,5 y 97,5}

\noindent\makebox[\textwidth]{\includegraphics[width=0.75\paperwidth]{box-m.jpg}}
\\{\fontsize{9}{11}\selectfont Figura : Box-plot del área inundada mensual en cada región estudiada. Los puntos dentro de la caja y sus valores indicados corresponden a la media de cada región, mientras que las barras corresponden a los cuartiles 2,5 y 97,5 Los puntos representan datos por encima de la media + 3 D.E. }

\end{document}
