Este archivo documenta la estructura a seguir para los ficheros a crear en este vault. Los cambios a esta estructura deberán repercutirse de forma recíproca.

World Atlas
├─> Plano terrenal
│      ├─> Continente X
│      │      ├─> País X (1)
│      │      │      ├─> Ciencia y tecnología
│      │      │      ├─> Gobierno
│      │      │      ├─> Historia importante
│      │      │      ├─> Organizaciones (2)
│      │      │      └─> Regiones
│      │      │               ├─> Región X
│      │      │               │      ├─> Lugares (3)
│      │      │               │      │      ├─> Lugar X (4)
│      │      │               │      │      │      ├─> \_Eventos (5)
│      │      │               │      │      │      ├─> Historia importante
│      │      │               │      │      │      ├─> Puntos de interés
│      │      │               │      │      │      ├─> Organizaciones (3)
│      │      │               │      │      │      └─> Personas importantes (3)
│      │      │               │      │      ├─> Lugar Y 
│      │      │               │      │       ⋮
│      │      │               │      ├─> Personas importantes (3)
│      │      │               │       ⋮
│      │      │               ├─> Región Y
│      │      │                ⋮
│      │      ├─> País Y
│      │       ⋮
│      ├─> Continente Y
│       ⋮
├─> La Vigilia
│      ├─> Ciudad X (6)
│       ⋮
└─> Planos Superiores
        ├─> Plano X (7)
         ⋮

World Encyclopedia (8)
├─> Ciencia y Tecnología
├─> Cosmología y Religión (9)
├─> Héroes (10)
│      ├─> Héroe X
│      ├─> Héroe Y
│       ⋮
├─> Parties (11)
 ⋮      ├─> Party X
 ⋮      │      ├─> PJ X
 ⋮      │      ├─> PJ Y
 ⋮      │       ⋮
        ├─> Party Y
         ⋮

 ─ ├ │ ⋮

1. Sin carpeta "Países", porque es lo único que va a ir aquí (a no ser que se te ocurra algo más). Creo que poner personas, lugares, etc. a nivel de continente no tiene mucho sentido. A esa escala mejor poner en World Encyclopedia.
2. Podríamos usar "Núcleos de poder" para englobar tanto organizaciones como personas importantes. Así simplificamos nomenclatura también.
3. "Lugares" en vez de "Ciudades y pueblos" (englobamos aldeas, asentamientos, etc.)
4. No todos los lugares tienen por qué presentar más profundidad de detalles. A veces todo lo que es necesario saber sobre un asentamiento lo ofrece su propia página, sin necesidad de dedicarle subsecciones. Las subcarpetas de un Lugar se deberán crear bajo demanda, solo cuando se requiera.
5. Las carpetas que empiecen por barra baja serán ignoradas por git, crea tantas como quieras para organizar tus spoilers.
6. De momento La Vigilia no la separaré en regiones siquiera. En ese plano poco importa lo que no sean núcleos urbanos.
7. Template de lugar, o de región como mucho.
8. El cajón de sastre de todo lo que no podamos asociar a un continente/país/lugar concreto.
9. Posiblemente lo suyo sea describir el tema de las religiones en sus carpetas correspondientes en el Atlas, aunque es posible que una religión se extienda más allá de las fronteras de un país (o incluso de un continente). Vamos viendo.
10. Los héroes son personajes con mucho peso y unidos bajo el mismo manto semántico (aunque muchos de ellos no se llegaran a conocer entre sí). Veo mejor ponerlos todos aquí junticos, y referenciar a cada uno en el lugar donde es/fue relevante mediante links.
11. Aunque una party de jugadores empiece en un lugar concreto, el hecho de jugar "mundo abierto" no los ata a ningún lado. Me parece oportuno juntarlos en la Encyclopedia.