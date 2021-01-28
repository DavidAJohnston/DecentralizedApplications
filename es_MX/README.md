La Teoría General de las Aplicaciones Descentralizadas, Dapps
=======================================================

Autores: David Johnston, Sam Onat Yilmaz, Jeremy Kandah, Nikos Bentenitis, Farzad Hashemi, Ron Gross, Shawn Wilkinson y Steven Mason

Traductores: Paynalton

Vea también la versión anterior de este documento [en Google Drive (eng)](https://docs.google.com/document/d/1Qh0KIQpy3Ob070BKHNA82fYGL0atlGSfmKCKJpS-QH8/edit?usp=sharing).

Tabla de Contenidos
-----------------

1.   Introducción
    1.   El surgimiento de las Dapps
    2.   Definición de una Dapp
    3.   Bitcoin como una Dapp
    4.   Nomenclatura y su importancia
    5.   Clasificación de las Dapps
    6.   El valor de las Dapps y sus tokens
2.   La operación de una Dapp
    1.   Mecanismos para concensos establecidos
    2.   Mecanismos para tokens distribuidos
    3.   Formación y desarrollo de una Dapp
3.   Modelo legal para la operación de Dapps
    1.   Emisión y retención de tokens
    2.   Organización no lucrativa
4.   Mejores prácticas para la creadión de una Dapp y Preguntas Frecuentes
    1.   ¿Qué califica a una aplicación de software como una Dapp?
    2.   ¿Qué es un token?
    3.   ¿Cómo se distribuyen los tokens?
    4.   ¿Cómo comienzo a desarrollar una Dapp?
    5.   ¿Porqué es una Dapp un modelo lucrativo para desarrolladores, usuarios y contribuyentes?
    6.   ¿Qué es una recompensa de comportamiento de usuario?
5.   El estado actual de las Dapps tipo II y III
6.   Conclusión
7.   Apéndice
    1.   Recursos para un modelo económico de Dapps
    2.   Una metamorfósis propuesta para las Dapps
    3.   La ley de Johnston



Introducción
------------

### El surgimiento de las Dapps

Un nuevo modelo para construir aplicaciones completa y masivamente escalables está surgiendo. Bitcoin abrió el camino con su código abierto, naturaleza peer-to-peer registros criptográficamente almacenados (block chain), y número limitado de tokens que dan fuerza al uso de sus características. En el último año docenas de aplicaciones han adoptado el modelo Bitcoin para triunfar. [Ethereum](https://www.ethereum.org/), [Omni](http://www.omnilayer.org/) y [SAFE Network](http://maidsafe.net/) son solo algunas de esas “aplicaciones descentralizadas” que usan una variedad de métodos para operar. Algunas utilizan su propia cadena de bloques(Ethereum), otras usan blockchains existentes y emiten sus propios tokens (Omni Layer), y otros operan en dos sobrecapas, una blockchain existente y emiten sus propios tokens (SAFE Network).

Este documento describe el porqué las aplicaciones descentralizadas tienen el potencial para ser inmensamente exitosas, cómo los diferentes tipos de aplicaciones descentralizadas pueden ser clasificadas, e introduce terminología que pretende ser acertiva y útil a la comunidad. Finalmente, este documento postula que esas aplicaciones descentralizadas algún día superarán a las más grandes corporaciones de software en utilidad, usuarios y valor de red debido a su estructura de incentivación superior, flexibilidad, transparencia, resistencia y naturaleza distribuida.

### Definición de una Dapp

Para que una aplicación sea donsiderada una Dapp (se pronuncia Diap, semejante a email) debe de cumplir con los siguientes criterios:

1.  La aplicación debe ser por completo     [código abierto](https://es.wikipedia.org/wiki/Open_source), debe operar de forma autónoma, y sin ninguna entidad controlando la suma de sus tokens. La aplicación puede adaptar sus protocolos en respuesta a mejoras propuestas y retroalimentación del mercado, pero todos los cambios deben ser decididos en concenso con sus usuarios.

2.  Los datos de la aplicación y registros de operación deben ser almacenados criptográficamente en una [blockchain](https://en.bitcoin.it/wiki/Block_chain) pública y descentralizada para evitar cualquier punto central de fallas.

3.  La aplicación debe usar un token criptográfico (bitcoin o un token nativo a su sistema) que sea necesario para acceder a la aplicación y cualquier contribución de valor de (mineros / granjeros) debería ser recompensada dentro de los tokens de la aplicación.

4.  La aplicación debe generar tokens de acuerdo a un algoritmo criptográfico estándas que actúe como prueba del valor de los nodos que contribuyen a la aplicación (Bitcoin usa el Algoritmo de Prueba de Trabajo).

### Bitcoin como una Dapp

Satoshi Nakamoto, el creador de Bitcoin, describe su invención como un “Sistema de Dinero Electrónico Punto a Punto[[2]](https://dl.dropboxusercontent.com#ftnt2)”. Bitcoin ha demostrado efectivamente resolver los problemas que surgen de un sistema de moneda electrónico escalable y poco confiable al usar una blockchain distribuida punto a punto a pesar de todo. Bitcoin es también una aplicación con la que los usuarios pueden interactuar através de software de computadora. Pero lo mas importante para el propósito de este documento es que se basa en los criterios arriba mencionados, Bitcoin es una aplicación descentralizada, y aquí está el porqué:

1.  Todas las aplicaciones de software Bitcoin son de código abierto, ninguna entidad (gobierno, compañía u organización) controla Bitcoin y todos los registros relacionados al uso de Bitcoin son abiertos y públicos.

2.  Bitcoin genera sus propios tokens, los bitcoins, con un algoritmo predeterminado que no puede ser cambiado y esos tokens son necesarios para que Bitcoin funcione. Los mineros de Bitcoin son recompensados con bitcoins por sus contribuciones en la seguridad de la red Bitcoin.

3.  Todos los cambios a Bitcoin deben ser aprovados por un concenso de la mayoría de los usuarios a través de mecanísmos de prueba de trabajo.

### Nomenclatura y su importancia

Las aplicaciones descentralizadas que inicialmente se describen como Corporaciones Autónomas Descentralizadas, DAC, en un artículo escrito por Daniel Larimer, de Inovaciones Invictas. Este documento evita el término "corporación" debido a dos razones.

Primero, debido a que carga con preconceptos innecesarios. Por ejemplo, una corporación se establece en una jurisdicción, tiene posesiones, un director, empleados, etc. Las Dapps, como Bitcoin, no tienen ninguna de esas características. Además, la narrativa es muy importante para la forma en que las Dapps son percibidas por varias naciones y jurisdicciones. De la misma manera en que gobiernos se esfuerzan por comprender y regular a Bitcoin debido a que el concepto de moneda está asociado con él, los gobiernos podrían verse obligados a regular un programa de computadora de código abierto que es una aplicación descentralizada.

Segundo, debido a que las corporaciones tradicionales pueden emplear diversas técnicas para incrementar capital (como vender posesiones de su inventario y pagar dividendos o solicitar préstamos contra su inventario y pagar intereses) lo cuan una Dapp no necesita. El concepto de una Dapp es tan poderoso y elegante debido a que no incluye esas técnicas corporativas tadicionales. La propiedad de los tokens de la Dapp es toda la que se necesita para sustentar el uso del sistema, así de simple. El valor de los tokens es determinado por cuanta gente valora la aplicación. Todos los incentivos, toda la monetización, todas las formas de incrementar el soporte son construidas dentro de esta hermosamente simple estructura. Las Dapps no necesitan recrear las funciones que eran necesarias en las corporaciones centralizadas para balancear la fuerza de accionistas y ofrecer ganancias a inversores y empleados.

### Clasificación de las Dapps

Hay varias características acerca de como las aplicaciones descentralizadas pueden clasificarse. Para los propósitos de este documento clasificaremos las Dapps basandonos en si tienen su propia blockchain o si usan la blockchain de otra Dapp. Siguiendo este criterio, tenemos tres tipos de Dapps.

**Tipo I** la aplicaciones descentralizadas tienen su propia blockchain. Bitcoin es el ejemplo más famoso de una aplicación descentralizada tipo I, pero Litecoin y otras "monedas alternativas" se encuentran en el mismo tipo.

**Tipo II** Las aplicaciones descentralizadas utilizan la blockchain de una aplicación descentralizada de tipo I. Las aplicaciones descentralizadas tipo II son protocolos y tienn tokens que son necesarios para su funcionamiento. El Protocolo Omni es un ejemplo de una aplicación descentralizada de tipo II.

**Tipo III** Las aplicaciones descentralizadas utilizan el protocolo de una aplicación descentralizada tipo II. Las aplicaciones descentralizadas de tipo III son protocolos y poseen tokens que son necesarios para su funcionamiento. Por ejemplo la Red SAFE que utiliza el Protocolo Omni para conseguir 'monedas seguras' que pueden ser usadas para adquirir almacenamiento de archivos distribuido es una aplicación descentralizada de tipo III.

Una analogía útil de una Dapp tipo 1 es un sistema operativo de computadora (como Windows, Mac OS X, Linux, Android, iOS, etc.) para una Dapp tipo II un programa de propósito general (como un procesador de textos, hoja de cálculo, un sistema de sincronización de archivos como Dropbox) y para una Dapp tipo III, una solución de software especializada (como una herramienta de mezcla de correos que usa un procesador de textos, un costoso generador de reportes que usa una hoja de cálculo o una plataforma de blogging que usa Dropbox.) Usando esta analogía, se puede esperar que tanto los efectos de la red como el ecosistema circundante de cada aplicación descentralezada será de unas cuantas Dapps tipo I, un poco más de Dapps tipo II y aun más de Dapps tipo III.

En este punto es importante mencionar que actualmente existen varios excelentes proyectos de código abierto que impulsan Dapps de tipo I. Colored coins y Coinjoin, por ejemplo, están basados en la blockchain de Bitcoin y proporcionan caracteristicas útiles a sis usuarios. Estos proyectos, sin embargo, no pueden ser clasificados como Dapps de tipo II, de acuerdo con nuestra definición, pues no usan ni administran ningún token. (El desarrollo y operación de estos proyectos dependen, además, de 
donativos.)

### El valor de las Dapps y sus tokens
Para un análisis complero acerca del porqué los tokens asociados con Dapps y las redes que potencian las Dapps son valiosas [vea este documento](https://docs.google.com/document/d/1Qh0KIQpy3Ob070BKHNA82fYGL0atlGSfmKCKJpS-QH8/edit).

La Operación de una Dapp
-----------------------

### Mecanismos para establecer concesos

Hay dos mecanismos por medio de los cuales las Dapps pueden establecer concensos: el mecanismo de **prueba-de-trabajo** (POW), y el mecanismo de **prueba-de-participacion** (POS).

Con el mecanismo POW, las deciciones sobre cambios en una Dapp se basan en el monto de trabajo con el que cada participante contribuye a la operación de la Dapp. Bitcoin usa este enfoce en su operación diaria. El mecanismo para establecer concensos a través de POW también es llamado "minería".

Con el mecanismo POS, las deciciones sobre cambios en la Dapp se hacen basados en el porcentahe de propiedad que varios participantes tienen sobre la aplicación. Por ejemplo, el voto de un participante que controla el 10% de los tokens utilizados por una Dapp conlleva un 10% de peso. El protocolo Omni está basado en mecanismos POS.

Los dos mecanismos pueden ser usados en paralelo, como es el caso de [Peercoin](http://peercoin.net/). Una combinación permite a una Dapp operar con un menor consumo de energía que con un mecanismo solitario, y permite ser más resistente al [51% de los ataques](https://en.bitcoin.it/wiki/Weaknesses).

### Mecanismos para distribuir tokens

Existen tres mecanismos por los cuales las Dapps pueden distribuir sus tokens: minería, fondeo y desarrollo.

Con el mecanismo de minería los tokens son distribuidos a aquellos que más contribuyen con más trabajo a la operación de una Dapp. Tomando Bitcoin como ejemplo, los bitcoins son distribuidos a través de un algoritmo predeterminado a los mineros que verifican transacciones y mantienen la blockchain de Bitcoin.

Con el mecanismo de fondeo, los tokens son distribuidos a aquellos que financian el desarrollo inicial de la Dapp. Tomando Master Protocol como ejemplo, los Mastercoins fueron inicialmente distribuidos a aquellos que enviaron bitcoins a una dirección determinada al cambio de 100 Mastercoins por cada Bitcoin enviado. Los bitcoins recolectados fueron entonces usados para costear el desarrollo de aplicaciones que impulsaron el desarrollo de Master Protocol.

Con el mecanismo de desarrollo, los tokens son generados usando un mecanismo predeterminado y solo están disponibles para el desarrollo de la Dapp. Por ejemplo, además de su mecanismo de fondeo, Master Protocol utilizó el mecanismo de colaboración para fondear su desarrollo futuro, Un 10% adicional de los Mastercoins generados a través del fondeo fueron apartados para el desarrollo de Master protocol. Esos Mastercoins están disponibles a través de una cédula predeterminada y son distribuidos por medio de un sistema de recompensas controlado por la comunidad, donde las decisiones son tomadas basados en el mecanismo POS.

Para resumir: Los tokens de una Dapp que establece concensos a través de POW son distribuidos por minería, por la compra directa a los mineros y por el comercio de bienes y servicios; este es el caso de Bitcoin. Los tokens de una Dapp que establece concensos a través de POS son distribuidos basado en la contribución de los participantes durante un fondeo, por personas que colaboran con el desarrollo de la Dapp y por el comercio de bienes y servicios; este es el caso de Omni Protocol.

### Formación y desarrollo de una Dapp

El desarrollo de aplicaciones descentralizadas toma lugar en tres pasos.

**Paso 1: Un libro blanco es publicado describiendo la Dapp y sus características**

Como en el caso de Bitcoin, el medio más común por el que una Dapp toma forma es la liberación pública de un libro blanco que describe el protocolo, sus características y su implementación. Despues de la liberación pública, la retroalimentación de la comunidad es necesaria para un mayor desarrollo de la DA.

**Paso 2: Los primeros tokens son distribuidos**

Si la Dapp está usando mecanismos para distribuir sus tokensm un programa de software referencial es liberado para poder ser usado en la minería. En el caso de Bitcoinm un programa de software de referencia fue liberado y el bloque de transacción inicial fue creado.

Si la Dapp está usando el mecanismo de fondeo, un software de cartera se hace disponible para los participantes de la Dapp, así que ellos pueden intercambiar los tokens de la DA. En el caso de Mastercoin, una dirección de fondeo Exodus y un script de cartera fueron liberados públicamente.

Si la Dapp está usando el mecanismo de desarrollo, un sistema de recompenzas se habilita para permitir la sugerencia de tareas a ser realizadas, el rastreo de personas que trabajan en esas tareas y el criterio con el que las recompenzas pueden ser obtenidas.

**Paso 3: La propiedad de participación de la Dapp es dispersada**

Como los tokens de la minería, fondeo y colaboración son dispersados a un mayor número de participantes, la propiedad de la Dapp se vuelve cada vez menos y menos centralizada, los participantes que poseen una mayoría de participación tienen cada vez menos poder y menos control. Conforme la Dapp madura, los participantes con las más diversas habilidades son incentivados a hacer contribuciones de mayor valor, y la propiedad de ka Dapp es dispersada aun más. A través de las fuerzas del mercado los tokens de una Dapp son transferidos a aquellos que más los valoran. Aquellos individuos pueden entonces contrinuir al desarrollo de la Dapp en áreas en las que ellos son expertos.

El caso de Bitcpon ilustra el punto. Según se estima, Satoshi Nakamoto minó muchos de los primeros 1,000,000 bitcoins. Como los desarrolladores contribuyeron con código a Bitcoin y los mineros contribuyeron con poder computacional a la red Bitcoin, el mercado comenzó a valorar más los bitcoins. Conforme el sistema fue madurando, la gente con diversas habilidades comenzó a valuar Bitcoin y a contribuir a su desarrollo. Ahora que más de 12 millones de bitcoins se encuentran en circulación la propiedad originalmente alta de Satoshi Nakamoto
ha sido diluida.

Modelo legal para la operación de Dapps
--------------------------------------

Operando bajo licencias de código abierto se permite que las Dapps se encuentren abiertas a la innovación sin restricciones de copyright o patente. Además, al ser completamente de código abierto, las aplicaciones descentralizadas pueden operar bajo el modelo legal del software de código abierto. Bitcoin, por ejemplo, usa la licencia de código abierto MIT. De manera simila Master Protocol requiere que todo el código basado en él sea de código abierto y disponible para la comunidad.

### Emisión y retención de tokens

Desde una perspectiva técnica, aquella emisión de tokens como parte de una preventa está vendiendo acceso a los usuarios de ese software. Las llaves privadas asociadas con esos tokens que los usuarios compran son literalmente las contrasellas que los usuarios necesitan para acceder al software de una Dapp. Desde la perspectiva fiscal, aquellos que poseen tokens poseen una propiedad digital. Si los tokens no tienen valor en el mercado fuera del uso dentro del la Dapp es difícil determinar su valor actual.

Debido a que pocas jurisdicciones han publicado una guía dada sobre como los tokens emitidos por Dapps serán tratados desde una perspectiva de fiscalización y regulación, los expertos legales en las jurisdicciones particulares deben ser consultados.

### Organización no lucrativa

No se requieren entidades legales para la operación de una Dapp debido a que no es una compañía. Los propietarios de los tokens no necesitan ser presentados por una corporación y los contribuidores no necesitan ninguna entidad legal tampoco. Sin embargo algunas veces los tocens son emitidos por una organización no lucrativa que nunca recibirña beneficios financieros de la Dapp. Dicha organización debe asumir las siguientes responsabilidades:

1.  Emisión de los tokens iniciales
2.  Almacenamiento de los tokens de desarrollo
3.  Administración del pago de recompenzas
4.  Determinar el rumbo de la Dapp

Idealmente, la organización no lucrativa tomará decisiones de una manera descentralizada, usando un mecanismo de votación POS para tomar cualquier decisión.

Mejores prácticas para la creación de una Dapp y Preguntas Frecuentes
-----------------------------------------------------------------

### ¿Qué califica a una aplicación de software como una Dapp?

1.  La aplicación debe ser por completo código abierto, debe operar de forma autónoma sin ninguna entidad que controle la mayoría de sus tokens, sus datos y registros de operaciones deben ser almacenados criptográficamente en una blockchain descentralizada y pública.

2.  La aplicación debe generar tokens de acuerdo a un algoritmo estándar o un conjunto de criterios y posiblemente distribuir algunos o todos sus tokens al inicio de su operación. Estos tokens deben ser necesarios para el uso de la aplicación y cualquier contribución de los usuarios debe ser recompensada con tokens de la aplicación.

3.  La aplicación debe adaptar su protocolo en respuesta a mejoras propuestas y retroalimentación del mercado, pero todos los cambios deben ser decididos por un concenso mayoritario de sus usuarios.

### ¿Qué es un token?

El propósito de un token es permitir el acceso a una aplicación computacional. Por ejemplo, un individuo debe poseer un cierto número de bitcoins para ser capaz de realizar cualquier transacción en la red de Bitcoin. Los tokens dentro de las Dapp no representan ningún activo subyacente, no otorgan privilegios a un dividendo y ningún valor de renta es representada a través de ellos. Además, el valor de un token de Dapp puede crecer o menguar con el tiempo, los tokens no son valores de renta.

### ¿Cómo se distribuyen los tokens?

Hay varias maneras en la que los tokens de una Dapp pueden ser distribuidos:

1.  Preventa de tokens: Una venta inicial de tokens es la forma común cuando se funda una Dapp. Los fondos recabados de dicha preventa son controlados por una entidad que es independiente a los fondeadores, usualmente una fundación.

2.  Tokens de desarrollo: Una parte de los tokens pueden ser reservados para los desarrolladores que trabajan en el proyecto. Como el mercado realiza una valuación del proyecto, los tokens de desarrollo ganarán valor, atrayendo así a contribuidores adicionales al proyecto.

3.  Tokens preminados: Es mejor si no hay tokens preminados, debido a que la mayoría de las comunidades e inversionistas están predispuestos negativamente a ello. Un preminado puede ser exitoso sólamente si una razón de fuerza mayor es propuesta por los fundadores.

4.  Tokens minables: La distribución de tokens por minería incentiva a la comunidad a contribuir con recursos a la Dapp. En Bitcoin, por ejemplo, hay un bloque de recompensa cada 10 minutos, lo cual incentiva a los mineros a proveer fuerza de hash a Bitcoin. De manera similar las Dapps necesitan determinar como incentivar a la red para contribuir con los recursos requeridos, lo que es la más importante decisión acerca de la distribución de tokens.

### ¿Cómo comienzo a desarrollar una Dapp?

Para desarrollar una Dapp es necesario seguir los soguientes pasos:

1.  Crear un libro blanco con al menos las siguientes secciones:
    -   Intenciones y metas de la Dapp
    -   Planes de distribución de tokens
    -   Mecanismos para establecer concensos
    -   Estructura de la entidad no lucrativa que vigilará la Dapp
    -   Administración de las recompensas de desarrollo
    -   Descripción técnica de la Dapp

2.  Obtener el interés de la comunidad publicando el plan y revisandolo en base a retroalimentación.
3.  Establecer una fecha en que la comunidad puede contribuir a la preventa.
4.  Vender los tokens iniciales basado en el libro blanco y establecer una entidad no lucrativa que vigile el desarrollo de la Dapp.
5.  Comenzar a ejecutar la idea mientras la entidad no lucrativa planea el desarrollo futuro.

### ¿Porqué es una Dapp un modelo lucrativo para desarrolladores, usuarios y contribuyentes?

El modelo permite a los contribuyentes mantenerse involucrados a lo largo del proyecto como compradores de tokens, como contribuyentes del proyecto o como proveedores de recursos a la red. Todas esas contribuciones se benefician del intercambio de tokens y de la posible apreciación de su valor.

### ¿Qué es una recompensa de comportamiento de usuario?

Una recompensa de comportamiento de usuario es otorgada a los contribuyentes que proveen utilidad a la red. El libro blanco debería marcar que se considera como utilidad para la Dapp. (Por ejemplo, potenciar el hashing es de utilidad para la red Bitcoin y es recompensado.). La utilidad debería ser medible, así como en el caso del almacenamiento de datos de la Dapp, el espacio de almacennamiento es medible.

El estado actual de las Dapps de tipo I y II
------------------------------------------

Un mecanismo por medio del cual las Dapps tipo II pueden aprovechar la blockchain de Dapps tipo I es agregar datos adicionales a la transacción, tomando lugar en el DA del tipo I. Master Protocol, por ejemplo, agrega datos adicionales a las transacciones de la red Bitcoin, Hasta el día de hoy (Febrero 2014) Mastercoin agrega sus datos adicionales de una manera apropiada dentro de la blockchain de Bitcoin, la liberación de la versión 0.9 del cliente de referencia de Bitcoin provee un método estándar para esos añadidos. Al usar la metodología de "provably prune-able outputs", las aplicaciones descentralizadas de tipo II que están basadas en Bitcoin serán capaces de agregar datos de manera sistemática y los mineros de Bitcoin tendrán la opción de validar dichos datos.

Dado su desarrollo, varias Dapps de tipo III se encuentran en diversos estados de desarrollo. Esto incluye:

-   MaidSafe provee un mecanismo “prueba de recurso” y estructura de datos descentralizad para almacenar archivos de forma privada o explícitamente en la nube.
-   StorJ proporciona un front-end de almacen de archivos tipo Dropbox utilizando MaidSafe y otros sistemas en el back-end.
-   Ethereum posee scripts basados en concensos y recursos de cálculo.
-   OpenGarden provee servicios de internet basados en red.
-   Scalion proporciona una vensión incentivada de la Red Tor con nodos que sirven como relés y salidas Tor.
-   Shared Miles posee un mecanismo de prueba de transporte que permite tener un estándar de transportación de código abierto.
-   BlockAuth proporciona un isitema de múltiples firmas parecido a OAuth para compartir datos privados con terceras partes.
-   API Protocol provee un estándar de código abierto para almacentar, normalizar y compartir datos de API.

Conclusión
----------

Las Dapps tienen el potencial de ser autosustentables pues empoderan a sis participantes al invertir en el desarrollo de la Dapp. Debido a eso es concebible que las Dapps para pagos, almacenamiento de datos, ancho de banda y computación en nube puedan un día sobrepasar en valor a las corporaciones multinacionales como Visa, Dropbox, Comcast, y  Amazon que se encuentran actualmente activas.

* * * * *

Apéndice
--------

### Recursos para un modelo económico de Dapps

-   [Una comparación entre la ley de Metcalfe, Zipf y Bitcoin](https://i.imgur.com/AWEfTjZ.jpg).

    “En efecto existe una fuerte correlación (R2 = 0.82) entre el número de usuarios y el precio. Todo esto no es sabido por la mayoría de la gente, desafortunadamente. Además el precio no crece linearmente con el número de usuarios pero si con el poder de 1.45 del número de usuarios. Esto es interesante pues para que el precio se incremente 1000 veces se necesita crecer solamente 140 veces el número de usuarios actuales. Tenemos aproximadamente 2 millones de usuarios de BTC.” <https://i.imgur.com/CiOxeBY.jpg>. Créditos por imágenes y citas [gsantostasi](http://www.reddit.com/r/Bitcoin/comments/21pujs/bitcoin_compared_with_metcalfes_and_zipfs_law/).

-   [Correlación entre el valor de una Dapp y la ley de Metcalfe](http://imgur.com/RDPz54G). Creédito por la imagen [Peter R](https://bitcointalk.org/index.php?topic=400235.msg5882283#msg5882283).

### Una metamórfosis propuesta para las Dapps

Sería benéfico tener una metamórfosis bien fundamentada, sencilla y accesible para las Dapps. Dicha metamórfosis podria idealmente tener la virtud de la simplicidad, lo que podría ser aprovechado por las interfaces humanas de computadora.

Esta metamórfosis podría ser un [cigoto](https://es.wikipedia.org/wiki/Cigoto). Un cigoto es el punto en el que la generación de una célula biológica termina y la siguiente inicia. Un cigoto se aclimata y responde al mundo exterior sin cambiar sus genes, no puede regularse, está cargado con sus propios genes y es recursivo. El cigoti es autónomo pues posee sus propuos genes, es una aplicación pues es una célula, se distribuye y está autorizada para actuar como una entidad aislada de otras células; comparte, en otras palabras, con muchas de las características de una aplicación descentralizada.

Los términos en los que se podría crear el llamado cigoto podrían incluire *zyprotocol*, el protocolo cigótico, *zapp*, la aplicación cigóticas, *zen*, la entidad cigótica, *zybit*, y el bit cigótico.

### La ley de Johnston

“Todo lo que pueda ser descentralizado, será descentralizado”. David A. Johnston

Basado en la economía y las eficientes ventajas de las aplicaciones descentralizadas, queda claro que la existencia de servicios centralizados será desplazadda con el tiempo por alternativas descentralizadas. Este cambio proveniente de servicios en la red afectados los las ventajas de la ley de Metcalfe será crítico para el éxito del proveedor de servicios.

http://www.johnstonslaw.org/

### Más enlaces

1. [Grupo de facebook](https://www.facebook.com/groups/appcoins)
2. TBD - otros canales sociales / grupo de skype (necesita un administrador del grupo de skype para solicitar unirse)
3. 
