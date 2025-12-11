## Definiciones alternativas y modernas de entropía
---
### Entropía como calidad de información
*"La entropía en la teoría mide la incertidumbre de los resultados y se aplica en la codificación para optimizar la comprensión y transmisión de datos."*

La entropía en la teoría de la información mide la incertidumbre o la cantidad de información contenida en fuentes de datos. Una mayor entropía indica una mayor incertidumbre y variabilidad de los datos. 

En codificación, se busca minimizar la longitud promedio de los códigos mediante comprensión, directamente influenciada por la entropía.

**Algunos esquemas de codificación importantes incluyen:**

- **Codificación Huffman:** Utiliza frecuencias de aparición de los símbolos para crear un árbol binario que asigna códigos más cortos a los símbolos más comunes y códigos más largos a los menos comunes.

- **Codificación Shannon-Fano:** Divide los símbolos en grupos basados en sus probabilidades y asigna códigos de manera recursiva, asegurando que los símbolos más probables tengan códigos más cortos.

- **Codificación Aritmética:** Representa un mensaje como un número real en el intervalo [0,1), asignando subintervalos a cada símbolo basado en su probabilidad, permitiendo una compresión cercana a la entropía teórica.
compresión cercana a la entropía teórica.

**Aplicaciones Prácticas**

El uso de la entropía y métodos de codificación eficientes es crítico en diversas aplicaciones prácticas, como:

- **Compresión de datos:** Algoritmos como ZIP y JPEG utilizan técnicas basadas en la entropía para reducir el tamaño de archivos y mejorar la eficiencia del almacenamiento y la transmisión de datos.

- **Transmisión de información:** En sistemas de comunicación, minimizar la redundancia y optimizar la codificación es esencial para maximizar la tasa de transmisión y reducir errores.

- **Criptografía:** La entropía se utiliza para evaluar la seguridad de sistemas criptográficos, garantizando que las claves y mensajes sean lo suficientemente impredecibles.

---
**Referencias:** 

1. https://www.thermal-engineering.org/es/la-entropia-en-la-teoria-de-la-informacion-y-la-codificacion/

---
### Entropía como entrelazamiento de la información 

La entropía de entrelazamiento es una medida de cuánta información se comparte entre diferentes partes de un sistema. Cuando dos sistemas están entrelazados, conocer el estado de uno nos da información sobre el estado del otro. En nuestro caso, consideramos un sistema central (llamémoslo sistema-A) y un sistema de baño más grande (sistema-B). Estos dos sistemas están conectados, y sus tamaños pueden cambiar mientras que el tamaño total se mantiene fijo.

A medida que varía el tamaño de estos sistemas, sus propiedades de entrelazamiento también cambian. Las leyes de conservación de la energía guían estas variaciones, lo que significa que la energía se equilibra entre ambos sistemas.

Cuando exploramos la entropía del sistema de baño en relación con el sistema central, surgen dos conceptos importantes: "islas" e "icebergs".

- Islas se refieren a regiones específicas dentro del baño que contribuyen a la entropía total. Estas regiones están generalmente separadas del sistema principal, pero juegan un papel crucial en cómo se comparte la información.
- Icebergs son considerados como contribuciones más pequeñas a la entropía que, aunque no sean tan significativas por sí solas, juntas forman una parte importante de la entropía total.
  
Tanto las islas como los icebergs ayudan a crear una comprensión más completa de cómo opera el entrelazamiento dentro de estos sistemas.

La interacción entre el sistema-A y el sistema-B puede cambiar dependiendo de sus tamaños individuales. Cuando el sistema-B es significativamente más grande que el sistema-A, la relación entre sus entropías se vuelve más clara. En casos donde el sistema-B es pequeño, las contribuciones de las islas y los icebergs pueden desconectarse, llevando a valores de entropía calculados de manera independiente.

Sin embargo, a medida que los sistemas crecen y varían en tamaño, su entrelazamiento también se vuelve estrechamente vinculado. La entropía del baño puede verse influenciada significativamente en función de cuán grande es el sistema-A, reforzando la idea de conservación de la entropía local.

Para calcular la entropía de entrelazamiento, primero se calcula la matriz densidad reducida para uno de los subsistemas, digamos A:

*ρA=TrB(|ψAB⟩⟨ψAB|)*

Luego, se computa la entropía de von Neumann de ρA:

*SA=–Tr(ρAlogρA)*

Esta cantidad, SA, es la entropía de entrelazamiento del sistema conjunto AB. En sistemas bipartitos puramente entrelazados, la entropía de entrelazamiento es máxima, indicando una fuerte correlación cuántica.

**Aplicaciones**

- Un ejemplo clásico de un estado entrelazado es el estado de Bell, que es una superposición de dos estados cuánticos base:

  *|ψAB⟩=12–√(|00⟩+|11⟩)*

  En este caso, si se efectúa una medida en uno de los subsistemas, el estado del otro subsistema queda instantáneamente determinado, mostrando una correlación perfecta entre A y B.

- Otro ejemplo es en la termodinámica, donde la entropía clásica mide el desorden o la incertidumbre en un sistema. De manera similar, la entropía de entrelazamiento puede interpretarse como una medida de la incertidumbre o la correlación intrínseca entre los subsistemas en un estado cuántico.
  
  Un aspecto fascinante de la entropía de entrelazamiento es su comportamiento en fases críticas de la materia. En física de la materia condensada, se ha observado que la entropía de entrelazamiento puede revelar información sobre transiciones de fase cuántica y la estructura de correlación en sistemas de muchos cuerpos.

  Además, en el contexto de la gravitación cuántica y la teoría de cuerdas, la entropía de entrelazamiento juega un papel crucial en la comprensión de la dinámica de agujeros negros y la holografía. Por ejemplo, el principio holográfico sugiere que toda la información contenida en un volumen de espacio puede ser descrita por una teoría que reside en su frontera. En estos estudios, la entropía de entrelazamiento es esencial para entender cómo se almacena y se transfiere la información.

---
**Referencias:** 

1. https://modern-physics.org/entropia-de-entrelazamiento-vision-general-y-significado/ 

2. https://modern-physics.org/entropia-de-entrelazamiento-vision-general-y-significado/
   
---
### Entropía como propiedad de la termodinámica 

**Se denomina entropía a la magnitud que indica la energía que no puede realizar un trabajo útil en un proceso termodinámico.**

La entropía se define como la medida de la dispersión de la energía en un sistema. Cuanto mayor es la entropía de un sistema, mayor es su grado de aleatoridad. Se puede pensar en la entropía como una medida de la cantidad de posibles configuraciones que puede tener un sistema, considerando todas las posibles combinaciones de partículas y energía. Se denota con la letra S y se expresa en unidades de energía dividida por temperatura, generalmente en julios por kelvin (J/K).

La entropía física, en su forma clásica, es definida por la ecuación propuesta por Rudolf Clausius:

*dS=dQ/T*

Esta es una magnitud termodinámica definida originalmente como criterio para predecir la evolución de los sistemas termodinámicos. En todo proceso irreversible, el desorden del sistema aumenta y por lo tanto, la entropía aumenta. Si el proceso es reversible, la variación de entropía es nula.

La entropía de un sistema es una función de estado de carácter extensivo. El valor de esta magnitud física, en un sistema aislado, crece en el transcurso de un proceso que se da de forma natural. El concepto de entropía describe cómo es de irreversible un sistema termodinámico.

En resumen, es un concepto fundamental en la termodinámica que se utiliza para medir la dispersión de la energía en un sistema y esta afecta la capacidad de un sistema para realizar trabajo útil.

---
**Referencias:** 
1. https://solar-energia.net/termodinamica/propiedades-termodinamicas/entropia
2. https://conceptos.es/entropia-en-termodinamica
