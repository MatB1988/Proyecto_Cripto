<p align='center'>
<img src ="https://i.ibb.co/kM7qWsS/logo1.png">
<p>

# <h1 align="center">**`Cryptocurrency Market Data Analytics`**</h1>


¡Bienvenidos! En el marco de este proyecto, se me ha encomendado realizar un análisis exhaustivo del mercado de las criptomonedas, centrándome en las diez criptomonedas de mayor relevancia en la actualidad.

Las criptomonedas seleccionadas para este estudio son las siguientes: [A continuación, puedes enumerar las diez criptomonedas que has elegido].

Mi objetivo es proporcionar un análisis completo y detallado de cada una de estas criptomonedas, teniendo en cuenta diversos aspectos como su capitalización de mercado, tecnología subyacente, casos de uso, adopción, tendencias históricas y proyecciones futuras. A través de este análisis, busco arrojar luz sobre las tendencias actuales en el mundo de las criptomonedas y proporcionar información valiosa para comprender mejor este emocionante mercado.

Se seleccionario las siguientes criptomonedas:
 + Bitcoin (BTC): Elegí Bitcoin debido a su estatus como pionero en el espacio de las criptomonedas y su posición como "oro digital". Su limitada oferta y reconocimiento global le otorgan un valor duradero y decidí analizarlo como una inversión sólida a largo plazo.
 + Ethereum (ETH): Me incliné hacia Ethereum por su papel fundamental en la revolución de las finanzas descentralizadas y los contratos inteligentes. La comunidad y el ecosistema en constante crecimiento respaldan su potencial para cambiar la forma en que interactuamos con aplicaciones y servicios en línea, por lo que lo consideré valioso de analizar.
 + Cardano  (ADA): Incluí a Cardano en mi análisis debido a su enfoque en la investigación científica y su compromiso con la seguridad. La promesa de mejoras técnicas y escalabilidad sostenible me llevó a considerar su potencial como una inversión interesante en términos de innovación a largo plazo.
 + Binancecoin  (BNB): Decidí analizar a Binance Coin debido a su estrecha relación con uno de los intercambios más grandes del mundo. Su utilidad para descuentos en tarifas y participación en lanzamientos de proyectos en Binance podría influir en su adopción continua, por lo que lo incluí en mi estudio.
 + Solana  (SOL): Opté por incluir Solana en mi análisis debido a su enfoque en la velocidad y la escalabilidad. El hecho de que pueda manejar un alto rendimiento y aún así admitir aplicaciones descentralizadas y DeFi me hizo pensar en su potencial para unirse a los líderes del mercado, por lo que lo consideré relevante para mi estudio.
 + Ripple (XRP): Me atrajo Ripple por su enfoque en soluciones de pago y transferencias internacionales. A pesar de los desafíos regulatorios, su capacidad para acelerar las transacciones entre fronteras podría convertirse en un punto clave en el futuro financiero global, por lo que lo incluí en mi análisis.
 + Polkadot (DOT): Decidí analizar a Polkadot debido a su enfoque en la interoperabilidad entre cadenas de bloques. Creo que su capacidad para conectar diferentes proyectos podría ser esencial a medida que el ecosistema blockchain siga creciendo y diversificándose, por lo que lo consideré importante incluirlo en mi estudio.
 + Dogecoin (DOGE): Aunque comenzó como un meme, vi el potencial de incluir a Dogecoin en mi análisis debido a su crecimiento de comunidad y participación de figuras públicas. Aunque es más especulativo, su viralidad podría mantenerlo en el radar y por eso decidí considerarlo.
 + Avalanche-2 (AVAX): Elegí analizar a Avalanche por su enfoque en la escalabilidad de contratos inteligentes. Si logra cumplir sus objetivos y compite exitosamente con otras redes líderes, podría convertirse en una opción interesante en el ecosistema blockchain, por lo que lo incluí en mi estudio
 + Algorand (ALGO): Decidí incluir Algorand en mi análisis debido a su enfoque en la velocidad y la seguridad de las transacciones. Su diseño técnico para abordar las limitaciones de otras cadenas de bloques lo convierte en una opción atractiva en términos de innovación tecnológica, por lo que lo consideré relevante para mi estudio.

Se recolectaron los datos históricos correspondientes al último mes de cada una de las criptomonedas utilizando la API **Coingecko**. Para llevar a cabo esta tarea, se empleó el lenguaje de programación Python.

Dentro del repositorio encontraran 3 carpetas:
+ Notebooks: Tiene los procesos de *ETL* y *EDA* aque se realizaron para en Python.
+ Imagenes: Tiene imagenes que se generaron en la realizacion del *EDA*
+ DataSet: Tiene los df obtenidos en el proceso de *ETL* y fueron utilizados para realizar el tanto en el *EDA* como en el tablero de *Power Bi*.
+ Video: Esta carpeta tiene un *video* donde se puede observar la funcionalidades del tablero.
  

`IMPORTANTE`: En la fase inicial del proyecto, la concepción original consistía en disponer de un dataset para cada criptomoneda, y el análisis exploratorio de datos (*EDA*) se llevó a cabo empleando dichos datasets. Sin embargo, al comenzar a trabajar con *Power BI*, surgió la necesidad de consolidar todos los conjuntos de datos en uno único que incluyera todas las monedas. Como parte del proceso de **ETL**, se incorporó este conjunto de datos consolidado. No obstante, dado que no se introdujeron cambios en la información que ya se estaba aportando, no fue necesario modificar **EDA**.

A continuación, presentaré algunos gráficos que se obtuvieron durante el **EDA**. Es importante señalar que las explicaciones detalladas de estos gráficos se encuentran disponibles en el siguiente archivo: https://github.com/MatB1988/Proyecto_Cripto/blob/0437c223264b034036111c04eabdf337afb23457/Notebooks/EDA.IPYNBn

<p align='center'>
<img src ="https://i.ibb.co/5RHdGTT/Boxplot-1.png">
<p>

<p align='center'>
<img src ="https://i.ibb.co/6JSbRnq/capitalizacion-de-mercado-Binancecoin.png">
<p>

<p align='center'>
<img src ="https://i.ibb.co/fDL0Q3d/Histograma-Criptos.png">
<p>

# **Desarrollo del tablero**

Al crear el tablero diseñado para realizar un seguimiento exhaustivo de las diversas criptomonedas a lo largo del día y el tiempo, se ha implementado un sistema de segmentación de monedas y un filtro de fechas. Esta configuración nos proporciona la capacidad de enfocarnos de manera precisa en monedas particulares y en intervalos temporales pertinentes.

Además, se han establecido tres indicadores clave de rendimiento (KPIs) fundamentales para la evaluación del mercado de las criptomonedas:

+ Variación de Precio: Analizamos cómo han variado los precios de las criptomonedas en el tiempo, identificando tendencias alcistas o bajistas.
+ Volumen Mediana vs. Volumen Promedio: Comparamos la mediana del volumen de negociación con el volumen promedio para entender las fluctuaciones en la actividad de compra y venta.
+ MarketCap Mediana vs. MarketCap Promedio: Observamos la mediana y el promedio de capitalización de mercado para evaluar la distribución de las criptomonedas en el mercado.

Junto con esos KPIs, he incorporado visualizaciones como un gráfico de cascada que proporciona una descripción detallada de cada criptomoneda y su respectiva capitalización de mercado, así como una lista que muestra el precio promedio de cada criptomoneda. Esto me ayuda a comprender su valor relativo.

En la segunda solapa del tablero, observarás el mismo segmentador y filtro junto con tres gráficos diferentes que muestran la suma diaria de aspectos clave:

+ Suma de Volumen por Día: Observamos cómo varía el volumen de negociación de las criptomonedas día a día.
+ Suma de Precio por Día: Analizamos la fluctuación diaria de los precios de las criptomonedas.
+ Suma de Capitalización de Mercado por Día: Evaluamos cómo cambia la capitalización de mercado en función de los días.

Para finalizar el análisis, he agregado personalmente dos gráficos de dispersión que visualizan:

+ Precio por Capitalización de Mercado: Este gráfico muestra cómo se relaciona el precio de una criptomoneda con su capitalización de mercado, ayudándonos a identificar patrones interesantes.
+ Precio por Volumen: Aquí, explore la relación entre el precio de una criptomoneda y su volumen de negociación, lo que puede revelar comportamientos de los inversores.

A continuación, se presentarán algunas imágenes del tablero:

<p align='center'>
<img src ="https://i.ibb.co/gj3bY1C/Tablero1.png">
<p>

<p align='center'>
<img src ="https://i.ibb.co/72SGf2y/Tablero2.png">
<p>

<p align='center'>
<img src ="https://i.ibb.co/TggrGqj/Tablero3.png">
<p> 


`CONCLUSIONES FINALES`

Es cierto que el mercado de las criptomonedas genera una gran expectativa en términos de ganancias potenciales. Sin embargo, es importante tener en cuenta que el valor de estas monedas es altamente especulativo. A diferencia de los activos con valor intrínseco, como las acciones en los mercados financieros tradicionales, la posesión de criptomonedas, como el Bitcoin, no otorga propiedad tangible, y su valor puede experimentar cambios drásticos en un corto período de tiempo.

En contraste, las acciones en los mercados tradicionales representan una participación en la propiedad de una empresa, lo que incluye activos tangibles como bienes raíces, inventario y ganancias. Este contraste plantea una distinción significativa entre ambos tipos de inversiones.

Es recomendable considerar no invertir en criptomonedas exclusivamente basándose en la expectativa de ganancias financieras, ya que el valor de estas monedas puede ser volátil y no necesariamente respaldado por activos reales. Sin embargo, es cierto que la tecnología subyacente, como la blockchain y los contratos inteligentes, tiene un valor real y aplicaciones más allá de las criptomonedas en sí. Estas tecnologías pueden ser utilizadas de manera independiente, incluso con monedas respaldadas por instituciones gubernamentales, como las monedas digitales emitidas por China y Estados Unidos.

***En resumen, es importante ser cauteloso al considerar la inversión en criptomonedas y comprender los riesgos asociados con su volatilidad. Al mismo tiempo, reconocer el valor de la tecnología subyacente puede llevar a explorar formas alternativas de aprovechar las ventajas de la blockchain y los contratos inteligentes sin necesariamente invertir en criptomonedas en sí.***