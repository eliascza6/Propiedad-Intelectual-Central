Universidad Internacional de La Rioja (UNIR México)

Licenciatura en Administración de Empresas con Orientación en Inteligencia de Negocio

Materia: Microeconomía

Actividad: Actividad 1 - Análisis de Mercado

Estudiante: Elías Cruz Álvarez

Presentación Ejecutiva:

El presente documento constituye el análisis microeconómico y cuantitativo del mercado de telecomunicaciones móviles en México, formalizando su arquitectura industrial bajo la teoría del oligopolio asimétrico con liderazgo de cuota y modelizando la interdependencia estratégica mediante la teoría de juegos no cooperativos.

A través de una perspectiva de Administración e Inteligencia de Negocio, se evalúan los equilibrios de Nash intertemporales, la dinámica de la competencia monopolística en sectores diferenciados frente a bienes homogéneos, y la formulación de propuestas de transformación tecnológica (AI-RAN, operaciones Zero-Touch y servicios de cómputo en el borde) orientadas a maximizar el retorno de inversión y mitigar riesgos regulatorios en el horizonte 2026-2031.

- 1 Identificación y Características de la Estructura de Mercado

El mercado de servicios de conectividad y telefonía móvil en México, integrado de forma predominante por tres operadores comerciales con red e infraestructura propia (Telcel, AT&T y Movistar), corresponde analíticamente a una estructura de Oligopolio; específicamente un triopolio asimétrico con liderazgo dominante de cuota por parte de Telcel.

A diferencia de los modelos teóricos simétricos de duopolio (Cournot y Bertrand) donde las firmas se reparten el mercado en partes iguales, Telcel opera con funciones de reacción, economías de escala y capacidades de red notablemente superiores. En la práctica observable, esto configura una dinámica empírica análoga al modelo de Stackelberg (extrapolado a tres firmas), donde el agente preponderante toma la delantera e internaliza el comportamiento de los seguidores, mientras AT&T y Movistar compiten sobre la demanda residual.

Tabla 1. Diagnóstico Estructural del Mercado Móvil Mexicano
[[Tabla 1..png]]

Cálculo del Índice Herfindahl-Hirschman (HHI):

𝐻𝐻𝐼=Σ𝑠𝑖2=(62)2+(20)2+(18)2=3,844+400+324=4,568 𝑝𝑢𝑛𝑡𝑜𝑠

En la ciencia económica y regulatoria, un mercado con puntos clasifica 𝐻𝐻𝐼>2,500formalmente como un mercado altamente concentrado.

Características Fundamentales del Oligopolio Móvil:

1. Atomización de la Demanda y Concentración Severa de la Oferta: La demanda agregada se compone de más de 130 millones de líneas móviles activas (Instituto Federal de Telecomunicaciones IFT, 2024) cuyos usuarios se comportan como precio-aceptantes. La oferta de red e infraestructura recae en tres consorcios corporativos con marcado poder de mercado (precio-decisores).
2. Interdependencia Estratégica: Las decisiones de fijación tarifaria, bolsas de navegación, financiamiento de terminales o gasto de capital () tomadas por un operador 𝐶𝐴𝑃𝐸𝑋alteran de manera inmediata la función de ingresos de sus rivales. Ninguna firma puede formular su estrategia comercial sin modelar la respuesta de la competencia.
3. Elevadas Barreras a la Entrada y Salida: Exige costos hundidos masivos en infraestructura física (fibra óptica, torres, antenas de transmisión) y la compra onerosa de derechos sobre el espectro radioeléctrico regulado, impidiendo el libre ingreso de nuevos participantes directos.
4. Diferenciación de Servicios y Heterogeneidad Percibida: Aunque el transporte de datos y voz es homogéneo en su naturaleza física, las empresas compiten mediante diferenciación perceptual: cobertura 5G garantizada, paquetes con redes sociales y plataformas de streaming sin consumo de saldo, y programas de retención.
5. Preponderancia y Asimetría Operativa: Telcel supera con creces el umbral constitucional del 50% sectorial. La Comisión Reguladora de Telecomunicaciones (CRT) y la Comisión Nacional Antimonopolio (CNA) ratifican su condición de Agente Económico Preponderante en Telecomunicaciones (AEP-T), imponiendo medidas asimétricas para contrarrestar la falla de mercado.


- 2 Modelización Mediante Teoría de Juegos y Dinámica de Cooperación

Modelización Formal: Dilema del Prisionero y Competencia No Cooperativa

La interacción oligopólica se modeliza rigurosamente bajo la Teoría de Juegos No Cooperativos. En su dimensión estática y simultánea, se formula como un Dilema del Prisionero; en su dimensión continua, opera mediante competencia en capacidades de red (Cournot) y competencia en tarifas comerciales con productos diferenciados (Bertrand).

Tabla 2. Matriz de Pagos en Forma Normal (Beneficios en Miles de Millones de MXN)
[[Tabla 2..png]]

Condición de Dominancia Estricta:

Π𝑖(𝑇𝑎𝑟𝑖𝑓𝑎𝑠𝐵𝑎𝑗𝑎𝑠,𝑠𝑗)>Π𝑖(𝑇𝑎𝑟𝑖𝑓𝑎𝑠𝐴𝑙𝑡𝑎𝑠,𝑠𝑗)∀𝑠𝑗∈{𝐴𝑙𝑡𝑎𝑠,𝐵𝑎𝑗𝑎𝑠}

Resolución y Mecánica del Juego:

● Si ambos jugadores cooperan tácitamente cobrando Tarifas Altas, emulan a un monopolio conjunto y alcanzan el óptimo agregado del sector (beneficio conjunto de 40).

● Si uno mantiene Tarifas Altas mientras el rival lanza promociones agresivas con Tarifas Bajas, la firma desertora captura masivamente suscriptores mediante portabilidad numérica, elevando su beneficio a 30 y desplazando al cooperador hacia pérdidas o márgenes mínimos (-10).

● Si ambos optan por Tarifas Bajas, se desata una guerra de precios que contrae los márgenes de toda la industria, estabilizando los pagos en (10, 10).

Dado que la estrategia de fijar Tarifas Bajas domina estrictamente a la de Tarifas Altas para ambos jugadores frente a cualquier decisión del competidor, el único Equilibrio de Nash en estrategias puras para el juego estático es (Tarifas Bajas, Tarifas Bajas). Este vector es ineficiente en el sentido de Pareto, ya que ambas firmas obtendrían mayores beneficios colectivos si sostuvieran tarifas elevadas.

Factibilidad de la Cooperación a Largo Plazo y Mecanismos de Ruptura:

● Sustentabilidad en Superjuegos Repetidos: En un horizonte de una sola etapa la cooperación es inviable. No obstante, en un juego repetido con horizonte infinito o indefinido, la cooperación tácita (colusión implícita) es matemáticamente sustentable mediante estrategias gatillo (Trigger Strategy o Grim Trigger) o esquemas de reciprocidad (Tit-for-Tat). Si el factor de descuento intertemporal () cumple la condición δmatemática:

δ≥Π𝑑𝑒𝑠𝑣í𝑜−Π𝑐𝑜𝑙𝑢𝑠𝑖ó𝑛Π𝑑𝑒𝑠𝑣í𝑜−Π𝑁𝑎𝑠ℎ=30−2030−10=1020=0.5

el valor presente descontado de cooperar indefinidamente supera la ganancia transitoria de engañar, sosteniendo tarifas estables a largo plazo.

● Factores de Ruptura de la Relación:

1. Incentivo Marginal al Desvío: Un operador puede lanzar paquetes con mayor volumen de datos o subsidios a terminales para arrebatar cuota neta antes de que los rivales detecten el desvío.
2. Shocks Regulatorios Asimétricos: La intervención de la CRT y CNA (como la fijación de tarifas de interconexión asimétricas o compartición forzosa de infraestructura) reduce los costos marginales de los seguidores, motivándolos a romper el status quo tarifario.
3. Marco Antitrust: El artículo 53 de la Ley Federal de Competencia Económica sanciona penal y económicamente los acuerdos colusivos explícitos (cárteles), obligando a las empresas a competir en un entorno sin contratos vinculantes.


Análisis de Competencia Monopolística: Industria de Cerveza Artesanal Mexicana vs. Cervecerías Industriales

Definición y Mecanismos de Diferenciación

La estructura de Competencia Monopolística se caracteriza por la concurrencia de una multitud de firmas oferentes y demandantes (mercado atomizado), libre entrada y salida de participantes
a largo plazo, y una profunda diferenciación de producto. Dicha diferenciación segmenta la demanda agregada, confiriendo a cada productor una curva de demanda individual con pendiente negativa y cierto poder de fijación de precios (). 𝑃>𝐶𝑀𝑔

Un caso de alta riqueza microeconómica en México es la Industria de Cerveza Artesanal (Craft Beer), donde más de 1,400 microcervecerías independientes (Asociación de Cerveceros Artesanales de México ACERMEX & INEGI, 2024) compiten activamente frente al duopolio masivo conformado por Grupo Modelo (AB InBev) y Cuauhtémoc Moctezuma (Heineken México).

● Diferenciación Horizontal (Variedad y Estilo): Las microcervecerías no venden un bien homogéneo (lager genérica industrial). Segmentan el mercado mediante estilos técnicos específicos: India Pale Ale (IPA), Imperial Stout, Porter, Sour Ale o cervezas de fermentación salvaje, adaptándose con precisión a las curvas de indiferencia de consumidores especializados.

● Diferenciación Vertical (Calidad Percibida e Insumos): Empleo de 100% malta de cebada, lúpulos aromáticos seleccionados, agua de perfil mineral específico e ingredientes locales de origen (frutas regionales, café de especialidad o barricas de roble), proyectando un atributo de calidad superior frente al uso de adjuntos industriales (maíz o arroz).

● Diferenciación por Localización e Identidad: Apego al arraigo regional y consumo en taprooms o salas de degustación anexas a la planta de producción, generando un monopolio espacial y experiencial sobre su propia clientela.

Tabla 3. Balance Microeconómico de la Competencia Monopolística para el Consumidor
[[Tabla 3..png]]

Análisis del Liderazgo de Telcel y Recomendaciones Estratégicas a 5 Años

Producto Principal y Productos Complementarios

Telcel ha blindado su participación de mercado mediante una arquitectura integral de portafolio que incrementa deliberadamente los costos de cambio (switching costs) para el suscriptor:

1. Producto Principal: Conectividad móvil de voz y datos celulares en esquemas prepago y pospago, respaldado por la mayor densidad de infraestructura en el territorio nacional (red 4.5G de alta penetración y red comercial 5G en más de 125 zonas metropolitanas).

2. Productos Complementarios:

○ Ecosistema de Streaming y Contenido: Suscripciones incluidas o bonificadas a Claro Video, Claro Música, y paquetes convergentes con Netflix, Disney+, Max y Prime Video con cargo a la factura unificada.

○ Financiamiento Cautivo de Terminales: Esquemas de crédito y financiamiento de smartphones de gama media y alta a plazos forzosos (18 a 36 meses), reduciendo el churn en usuarios de alto consumo.

○ Soluciones Empresariales e Inclusión Fintech: Servicios de telemetría de flotas, Internet de las Cosas (IoT industrial), soluciones en la nube de Claro Empresas y la plataforma transaccional Claro Pay.

Recomendaciones Estratégicas Fundamentadas (Horizonte 2026-2031):

1. Evolución hacia una "Techco" Mediante Agentic AI, AI-RAN y Operaciones Zero-Touch: Fundamentado en los reportes de McKinsey & Company (2024, 2026), Telcel debe superar el estancamiento del tradicional transformando su red física en una 𝐴𝑅𝑃𝑈plataforma de cómputo inteligente. Debe implementar la arquitectura AI-RAN en sus radiobases 5G, permitiendo que los chips y servidores de la red procesen tanto la señal de telecomunicación como cargas de inferencia de Inteligencia Artificial perimetral (Edge AI). Asimismo, debe implementar Agentic AI (agentes autónomos) conectados a los sistemas OSS/BSS para ejecutar operaciones Zero-Touch (reconfiguración espectral automática y modelos de retención temprana basados en degradación de señal), reduciendo el abandono de pospago en un 15% y los costos operativos () de red 𝑂𝑃𝐸𝑋entre un 10% y 15%.

2. Diversificación Hacia Infraestructura Crítica B2B (GPUaaS y Redes Privadas 5G): Ante la Revisión Bienal de Medidas de Preponderancia coordinada por la CRT y la CNA, Telcel debe mitigar su exposición regulatoria en el mercado masivo residencial. Debe acelerar el despliegue de redes privadas 5G de ultra-baja latencia para manufactura avanzada, logística portuaria y agroindustria tecnificada. Paralelamente, debe rentar capacidad perimetral para servicios de GPU-as-a-Service (GPUaaS) interconectando los centros de datos de IA del centro y norte de México, capturando flujos de efectivo corporativos de alto margen que no están alcanzados por las tarifas reguladas de interconexión minorista.

Tabla 5. Matriz Operativa
[[Tabla 5..png]]

Declaración de Uso de Inteligencia Artificial Generativa
En cumplimiento estricto con los Artículos 2 (Principio de Transparencia, Supervisión Humana y Confidencialidad), 7, 9, 10 y 12 del Manual práctico de uso de sistemas de Inteligencia Artificial Generativa para estudiantes de UNIR (2026), se declara que en la elaboración de esta actividad se utilizó un sistema de Inteligencia Artificial Generativa (IAG) bajo el siguiente marco metodológico:
● Herramienta empleada: Gemini (Modelo Gemini 2.5 Pro / Advanced), desarrollada por Google.
● Finalidad de uso:
1. Sintetización inicial de la información y auxilio en la estructuración lógica.
2. Contrastación y validación de fuentes regulatorias actualizadas en México (resoluciones de la CRT y CNA sobre medidas de preponderancia).
● Supervisión humana y autoría: El sistema de IA no sustituyó el criterio analítico, la redacción final ni la toma de decisiones del estudiante. Todos los resultados generados fueron auditados, verificados con fuentes primarias confiables, editados y contrastados con el temario oficial de la asignatura, asumiendo la autoría y responsabilidad intelectual plena sobre el contenido del documento. No se incorporaron datos personales, sensibles ni confidenciales en el sistema.

Referencias Bibliográficas (Normas APA 7.ª Edición)

● Comisión Reguladora de Telecomunicaciones. (2026, 20 de marzo). CRT y CNA firman convenio rumbo a la Revisión Bienal de Medidas de Preponderancia (Comunicado Bol. 009/2026). Gobierno de México. https://www.gob.mx/crt/prensa/crt-y-cna-firman-convenio-rumbo-a-la-revision-bienal-de-medidas-de-preponderancia?idiom=es
● McKinsey & Company. (2024, 18 de diciembre). The future of telcos: Mapping the routes to renewed success. McKinsey Insights. https://www.mckinsey.com/industries/technology-media-and-telecommunications/our-insights/the-future-of-telcos-mapping-the-routes-to-renewed-success
● McKinsey & Company. (2026, 27 de febrero). The telco reinvention: How AI can fuel value creation. McKinsey Insights. https://www.mckinsey.com/industries/technology-media-and-telecommunications/our-insights/the-telco-reinvention-how-ai-can-fuel-value-creation
● Google. (2026). Gemini (Versión Advanced / Gemini 2.5 Pro) [Modelo de lenguaje de gran escala / Software]. https://gemini.google.com
● ACERMEX, & INEGI. (2024). Conociendo la industria de la cerveza: Colección de estudios sectoriales y regionales. Instituto Nacional de Estadística y Geografía / Asociación de Cerveceros Artesanales de México. https://www.inegi.org.mx
● Instituto Federal de Telecomunicaciones. (2024). Banco de Información de Telecomunicaciones (BIT): Indicadores del mercado móvil y concentración económica en México. IFT. https://bit.ift.org.mx