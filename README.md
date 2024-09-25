<!-- 13/08/2024 - seguridad -->
# 🐱‍💻 Vulnerabilidades Informaticas

Una vulnerabilidad informatica es una debilidad o **error** en el código de un sistema o dispositivo que cuando se explota puede comprometer o poner en riesgo la seguridad de la informacion personal o de una organización.

Permite ejecutar distintos tipos de codigos para acceder a los sistemas, instalar malware y destruir o modificar en ellos datos confidenciales.

Realmente es un fallo en el diseño, programación, configuracion o humano que permite a los atacantes obtener información privada.

Cabe destacar que una vulnerabilidad y una amenaza no es lo mismo, pueden que esten muy relacionados entre si, pero son conceptos diferentes.

> [!NOTE]
> Error, defecto y fallo son terminos que pueden sonar similares pero son totalmente diferentes, pueden verse relacionadas como sucede con las vulnerabilidades y amenzas, pero son totalmente distintas.

## 🚧 Tipos de vulnerabilidades

- ### _Humanas_
    Las personas pueden causar daños en el ambiente tecnologico como en los sistemas de informacion, ya sea de forma intencional o no. El motivo principal puede ser la poca capacitacion o de conciencia de seguridad para llevar a cabo sus actividades rutinarias.

- ### _Físicas:_
    Son aquellas existentes en los **lugares** donde se encuentra almacenada la información. En algunas ocaciones a los atacantes les puede resultar más fácil acceder a la información vía física que vía lógica.

- ### _Naturales:_
    Hace referencia a todo lo relacionado con las condiciones de la naturaleza que ponen en riesgo la información (incendios, huracanes, terremotos, inundaciones...).

- ### _Hardware:_
    Hace referencia a los posibles defectos de fábrica o mala configuración de los equipos de la empresa que puedan permitir ataques o alteración de estos. Por ejemplo, falta de actualizacion de equipos o mala conservación son factores de riesgos para las empresas.

- ### _Comunicación:_
    La información lleva a cabo un viaje o sigue un camino(satelite, fibra, ondas de radio o cables) en el que debe existir seguridad. El transito de los datos debe encontrarse protegido para que la información en todo el proceso esté segura. Este tipo de vulnerabilidad conllevo a cifrar toda la información que se envia en los medios.

- ### _Software:_
    Accesos ilegales a los sistemas informáticos por parte del administrador de la red. Si se lleva a cabo una incorrecta configuración o instalación de programas en los equipos, se producirá un uso abusivo de los recursos.

- ### _Medios de Almacenaje:_
    Hace referencia a aquellas que pueden darse en los soportes físicos o magnéticos que se usan para almanacenar información (disco duro, USB...).

## 📝 Clasificación de vulnerabilidades
- ### **Bajas:** 
    Afecta poco a los sistemas informaticos, es decir, su impacto es minimo en los mismos Es fácil hacerle frente y reducirla por que apenas supone riesgos reales para la organización.

- ### **Moderna:**
    Son fáciles de solucionar, pero tienen un mayor impacto que las vulnerabilidades anteriores. Sus consecuencias se reducen de manera sencilla con herramientas o configuraciones previas.

- ### **Grave:**
    Se trata de una vulnerabilidad mucho mas peligrosa debido a que pone en riesgo la confidencialidad, integridad y disponibilidad de los sistemas de información. Afecta tanto a los datos como a los recursos.

- ### **Critica:**
    Es la peor clasificacion, ya que se propaga sin que sea necesaria la participación de los usuarios.

# ⚠ Amenazas informaticas

Son todas aquellas acciones que utilizan o se aprovechan de la existencia de una vulnerabilidad para violar la seguridad de un sistema.

Es importante destacar que una amenza puede convertirse en una vulnerabilidad en caso de que no se tomen medidas correctas de seguridad.

<!-- 20/08/2024 - seguridad -->

> [!DANGER]
> 3 DE SEPTIEMBRE: Lectura de documentos, de los cuales se va a realizar una sintesis de la información que contienen

# 🦺 Sistema de Gestión de Seguridad de la Información(SGSI)

Es basicamente, un conjunto de politicas de administración de la información. Para entender más a profundida en que consiste debemos partir de la definición dada por el estandar internacional ISO/IEC 27000:

> _"Un SGSI consiste en el conjunto de políticas, procedimientos y directrices junto a los recursos y actividades asociados que son administrados colectivamente por una organización, en la búsqueda de proteger sus activos de información esenciales"_

Se debe de tener en cuenta una visión dada por el estandar ISO/IEC 27001:

> _"Es un enfoque sistemático para establecer, implementar, operar, monitorear, revisar, mantener y mejorar la seguridad de la información de una organización y lograr sus objetivos comerciales y/o de servicio"_

## 💵 Activo de informacion

Segun la norma ISO/IEC 27001 es _"Algo que una organización valora y por lo tanto debe proteger"_. La proteccion de estos activos está destinada a preservar **la confidencialidad, la integridad y la disponibilidad de la información**.

 - **Confidencialidad:** La informacion no se debe poner a disposición ni se revela a individuos, entidades o procesos no autorizados. Es necesario acceder a la información mediante autorización y control. En simples palabras la información debe de ser acceso único.

 - **Integridad:** La información y sus métodos de procesos debe mantenerse con exactitud y completitud. Su objetivo es prevenir modificaciones no autorizadas. En simples palabras busca prevenir modificaciones indebidas. Si no se garantiza la confidencialidad puede afectar la integridad de la información.

 - **Disponibilidad:** Garantizar el acceso y la utilización de la información y los sistemas de tratamiento de la misma, por parte de los individuos, entidades o procesos autorizados cuando lo requieran. Su objetivo es prevenir interrupciones no autorizadas de los recursos informáticos. En simples palabras es que las personas que requieran acceso a la información con los permisos necesarios, puedan tenerlo.

Para lograr esta protección de activos se debe establecer, implantar, mantener y mejorar un SGSI. Se basa en el **ciclo de Deming**.

### ♾️ Pasos del ciclo de Deming

- El primer paso es la **planificación**, en donde se miran los riesgos de seguridad de la información y se seleccionan los controles adecuados. Dentro de los riesgos se analizan el tipo, la iterancia y la gravedad.

- El segundo paso es el **hacer**, en donde se envuelve la implantación y operación de los controles definidos en la planificación.

- El tercero es **verificar**, que tiene como objetivo revisar y evaluar el desempeño(eficiencia y eficacia) del SGSI.

- El cuarto y ultimo es el **actuar**, en donde se realizan cambios periódicamente para mantener el SGSI al máximo rendimiento.

El alcance del SGSI aclara suales son sus limites en función del contexto. En caso de que haya un estandar de manera estatal o distrital, estos se sobreponen ante el estandar internacional como lo es el ISO. Se debe de tener en cuenta los problemas internos y externos y los requisitos y espectativas procedentes de las partes interesadas, que se relacionan con las actividades esenciales, es decir, aquellas que permiten cumplir con la misión y los objetivos generales de la organización.

### Inventario de Activos de Información

Cuando uno define estos activos, deben de estar claramente identificados y debe de elaborarse y mantener un inventario de todos los activos de información importante de la organización.

Se recomienda realizar una clasificación, donde la recomendada puede ser la siguiente:

- ### Activos de informacion pura

    - Datos digitales
        - Bases de datos
        - Unidades Lógicas(Entornos Físicos)
        - Copias de Seguridad
    
    - Activos tangibles
        - Personales
        - Financieros
        - Legales
        
    - Activos Intangibles
        - Conocimiento
        - Relaciones
        - Secretos comerciales

    - Software de aplicación
        - Propietario desarrollo por la organización
        - Herramientas de bases de datos
        - Aplicaciones de comercio electrónico
        - Middleware

    - Sistemas Operativos
        - Servidores
        - Dispositivos de red
        - Dispositivos de mano e incrustados

<!-- 27/08/2024 - Seguridad Informatica -->

<!-- Para el 10 de agosto debe tener un resumen en cualquier formato para los 3 documentos en el campus: ISO 27001, ISO 31000 y ICONTEC, Enfocado en la gestion de riesgos -->

# Evaluación de Riesgos

Cada organización debe evaluar los riesgos tiendo en cuenta las guías ISO/IEC 27005 e ISO 31000.

Este proceso debe de ser estructura y repetible, un procedimiento documentado de evaluación de riesgos que explique cómo se identifican, analizan, evaluan y priorizan los riesgos seleccionados con los activos de información más relevantes del alcance. Esto se realiza con el fin de realizar planes de acción o mejoramiento.

## Delaración de aplicabilidad

Una vez evaluados los riesgos, se debe hacer una verificación para determinar cuáles de los controles recomendados en el Anexo A de ISO/IEC 27001 están siendo aplicados o deben aplicarse en la organización. Para esto se puede hacer una referencia cruzada directa con la guía de implementación ISO/IEC 27002 y con cualquier otra fuente alternativa o suplementaria.

El objetivo de este documento es evidenciar que los controles recomendados se aplican cuando están dentro del alcance y son apropiados para su organización o, por el contrario, dejar claro cuando no se justifica el esfuerzo.

# Tratamiento de riesgos

Una vez analizados, se define la política de tratamiento de los riesgos en función de la probabilidad de que las amenazas o las vulnerabilidades propias del activo puedan causar un daño total o parcial al activo de la información. Esta definición debe aliniarse con la disponibilidad, confidencialidad e integridad de este y con la política definida por la dirección. En este punto, se seleccionan las acciones adecuadas para cada riesgo, las cuales iran orientados a:

* **Asumir el riesgo:** Se trata de no hacer nada. Simplemente se sabe que no se tiene el como evitarlo y se convive con él.

* **Reducir el riesgo:** Se usa cuando se tiene la capacidad de eliminar el riesgo pero puede ser muy costosos o muy tardados que simplemente asumir las consecuencias negativas de que este llegara a materializarse.

* **Eliminar el riesgo:** Son las acciones para hacer que las condiciones o los factores desaparezcan y con ellos el riesgo. Es una opción para aquellos casos de alta probabilidad de ocurrencia, con un muy alto impacto negativo.

* **Transferir el riesgo:** Significa que se le pasa el problema a alguien mas. Es común el contratar una póliza de seguros que indemnice a la organización en caso de que se presente el problema.

<!-- seguridad 17/09/23 -->
# El ROI en la seguridad digital
***Justificación de presupuesto en ciberseguridad***
Es uno de los aspectos más importantes pero a su vez mas difícil de asignar.

Razones de importancia de cuantificar la inversión de ciberseguridad:
- Justificación de inversiones pasadas
- Demostrar la necesidad de una inversión futura
- Inversión estratégica en seguridad

## Como se calcula? 
**ROI** = ***(Beneficios de inversión - Costo de inversión en seguridad) / Costo de inversión en seguridad***

Para calcular los beneficios de inversión se basa en la **Expectativa Anual de Perdidas(ALE)**

> **ALE** = ***ARO(Tasa anual de ocurrencia) * SLE(Expectativa de Perdida Única)***

- **ARO:**  Cada cuanto ocurre anualmente el ataque, normalmente en %
- **SLE:** Los costos totales de una solo instancia de la amenaza, o sea lo que pierde la empresa por un ataque(costos de remediación, perdida de productividad, perdida de ventas, etc)

>**ROSI** = ***((ALE sin inversion - ALE con la inversión) - Costo de la inversión) / Costo de la inversión***

> [!WARNING]
> **Workhome:** Una empresa tecnológica ha enrentado repetidos intentos de phishing que han comprometido cuentas de empleados. La probabilidad anual de que ocurra un ataque exitoso es del 25%(ARO=0.25). Cada incidente le cuesta a la empresa $50.000 en tiempo de recuperación y daño de reputación(SLE=50000). La empresa está considerando invertir $15.000 en un programa de capacitación y mejoras de seguridad que reduciría la probabilidad de éxito de estos ataques en un 70%.
>
> Calcule el ROSI de esta inversión y evalúe si es financieramente ventajosa.

**ARO sin inversion:** 0,25(25%)
**ARO con inversion:** 0,075(7,5%)
**SLE:** $50.000
**Inversión:** $15.000

**ALE sin inversion:** 12500
**ALE con inversion:** 0,25 * 0,3 * 50000 = 3750

> **ROSI** = ***|(|(3750-12500)|-15000)/15000| = 0,42(42%)***

> [!IMPORTANT]
> Por cada dolar invertido en la seguridad, la organización obtendra $1.42 de beneficio.

> [!WARNING]
> **Workhome:** Una empresa de manufactur experimenta frecuentes infecciones de malware que ralentizan su red y afectan la productividad. La probabilidad de que ocurra unincidente de malware es del 30% anual(ARO=0.3). Cada incidente le cuesta a la empresa $80.000 en pérdida de datos y productividad (SLE = $80.000). La empresa planea gastar $25.000 en un nuevo software de seguridad que reduce el riesgo en un 60%
>
> Calcule el ROSI de esta inversión y evalúe si es financieramente ventajosa.

**ARO sin inversion:** 0,3(30%)
**ARO con inversion:** 0,12(12%)
**SLE:** $80.000
**Inversión:** $25.000

**ALE sin inversion:** 24.000
**ALE con inversion:** 9.600

> **ROSI** = ***|(|(9600-24000)|-25000)/25000| = 0.424(42%)***

> [!IMPORTANT]
> Por cada dolar invertido en la seguridad, la organización obtendra $1.42 de beneficio.

> [!WARNING]
> **Workhome:** Una empresa de retail tiene alta exposicón a violaciones de datos que involucran información de clientes. La probabilidad de que ocurra una violación de datos es del 10% anual. Cada incidente le cuesta $1'000.000 debido a multas regulatorias, pérdida de confianza y recuperación de sistemas. La empresa planea invertir $150.000 en una solución de encriptación avanzada que reduciría la probabilidad de este tipo de ataques en un 85%
>
> Calcule el ROSI de esta inversión y evalúe si es financieramente ventajosa.

**ARO sin inversion:** 0,1(10%)
**ARO con inversion:** 0,015(1.5%)
**SLE:** $1'000.000
**Inversión:** $150.000

**ALE sin inversion:** 100.000
**ALE con inversion:** 15.000

> **ROSI** = ***|(|(15000-100000)|-150000)/150000| = 0.43(43%)***

> [!IMPORTANT]
> Por cada dolar invertido en la seguridad, la organización obtendra $1.43 de beneficio.
