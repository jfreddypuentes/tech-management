# Notas de Gerencia en Tecnología


## ⏰ Estimaciones
* Buscar hacer entregables cortos para obtener un retorno de inversión constante.
* Predecir el futuro a largo plazo en desarrollo de software es: complejo + complicado
  Proyectos definidos en modelo en cascada: [caos-report](https://www.projectsmart.co.uk/white-papers/chaos-report.pdf)
  * 16.2% fueron exitosos
  * 52.7% fueron desafiados (No terminaron en el tiempo, costo y alcance estimados; Costaron 189% más de lo predicho)
    Sobrecostos por tamaño de empresa:
    - Grandes: 178%
    - Medianas: 182%
    - Pequeñas: 214%
  * 31.1% Fracasaron, no terminaron.
* Los requerimientos cambian en el tiempo. Esto es seguro.
* Proyectos restrasados:
  * Promedio de tiempo excedido: 222%
  * Tiempos de restraso por tamaño de empresa:
    - Grandes: 230%
    - Medianas: 202%
    - Pequeñas: 239%

**Indicadores encontrados en proyectos DESAFIADOS**
* Falta de feedback
* Requisitos y/o requerimientos incompletos
* Cambios de requisitos y/o requerimientos
* Falta de apoyo ejecutivo
* Incompetencia técnica

**Indicadores encontrados en proyectos FALLIDOS**
* Requisitos y/o requerimientos incompletos
* Falta de feedback
* Falta de recursos
* Expectativas irreales
* Falta de apoyo ejecutivo


### Buenas prácticas para estimar proyectos "not lean"
* Estimar épicas a muy alto nivel (_porque no se tiene el detalle y hay incertidumbre_), las historias de usuario las estima los desarrolladores.
* Crear un roadmap de alto nivel con las épicas, prioridad y tamaño o complejidad
* Tener una métrica o técnica de estimación consistente
* Eliminar dependencias o involucrarlas al proyecto.
* Toma notas sobre riesgos, suposiciones o incertidumbre. y comunicalos!
* Evalua otros costos que pueda salir.


### Buenas prácticas para estimar proyectos "Lean"
* Definir un MVP (versión más corta que de valor) de forma iterativa.
* Hacer entregas cortas, pedir feedback e iterar.
* Los cambios en requerimientos, prioridades y alcance son bienvenidos.
* Enfocarse en el entregable de la iteración.
* TIP: Pensar si hay un MVP del MVP.
* TIP: Tomar desiciones basadas en data.
* TIP: Listo es mejor que perfecto.
* TIP: Si vamos a fallar, fallemos barato.
* LIBRO RECOMENDADO: Lean startup


### Fechas de entrega
* No entregar fechas de entrega a largo plazo. Si se debe tener y entregar fecha de entrega del sprint o MVP.
* Agregar más personas a un proyecto no hace que se entregue más rápido. Vea [Ley_de_Brooks](https://es.wikipedia.org/wiki/Ley_de_Brooks)
* Negociar con el triangulo de negociación de Alcance * Tiempo * Costo (siempre entregando valor)


### Buscando capital
* Pensar en como el proyecto o MVP retornará la inverión.
* Vender una idea:
  * Plantilla del deck [Aquí](https://www.canva.com/templates/EADrOnpuH7Y-green-and-blue-illustrative-technology-pitch-deck-presentation/) y aqui [startup-picth-deck](https://slidebean.com/templates/startup-pitch-deck-template)
  * Titulo
  * Definir un problema
  * Explicar solución para convencer. (_buscar data y numeros_)
  * Mostrar tracción: pruebas que han hecho, feedback.
  * Mostrar tamaño del mercado. (_mostrar data_)
  * Pensar en la competencia. (interna o interna)
  * Ventejas competitivas.
  * Mostrar cual es el pronóstico de negocio.
  * Como se va a usar los fondos.
  * Soporta


## 👥 Creación de equipos

### Estructura
* Definir celulas de trabajo que funcione de forma optimizada.
* Definir el objetivo de cada equipo. Definir la misión del equipo.
* Empoderarlo para que vayan de la mano con el negocio. No al contrario
* Minimizar las dependencias al máximo. Construir equipos autónomos.
* Construir equipos multidisciplinarios y auto-organizados.
* Brindar la seguridad psicológica de fallar.

### Reclutamiento
* Es necesario conocer el stack tecnológico.
* Definir el perfil. Debe ser claro.
* No cerrar la puerta a la personas sin experiencia o estudios.
* OJO: Alerta con el sesgo inconsiente. Eliminalo.
* Define el pipeline del proceso de reclutamiento. [Contacto, entrevista ténica, entrevista fee cultural etc]
* Automatizar el pipeline. Para optimizar tiempo, encontrar cuellos de botella.
  Algunas herramientas:
  * https://www.bamboohr.com/g/
  * https://recruitee.com/
  * https://www.pipefy.com/
* Definir el reto técnico y aplicar (remoto o presencial)
* Bsucar personas que:
  * Escuchen
  * Sean responsables
  * Muestren su lado vulnerable o reconozca sus defectos
  * Trabajen en equipo
* Estudiar salarios del mercado.
  * Algunas herramientas:
    - LinkedIn salary
    - Payscale
    - glassdoor
* Buscar recomendaciones cuando el proceso no sea confidencial.
* Definir un onBoarding.  Checklist de lo que debe hacer una persona cuando entre nuevo al team.

### Definir esquema de lideres.
* Los equipos son el reflejo del lider.
* Promover una capa de lideres que hagan sinergia + quimica.


## Ruta técnica
* Ojo: las personas altamente tenicas no son siempre buenos lideres.
* Se miden por las victorias tempranas en las mejoras técnicas.
* Necesitan un objetivo claro hacia donde vamos.
  * Entiende la parte técnica pero entiende más a las personas.
* Influye a través de las personas.

## Ruta de gerencia
* Trabaja con las personas.
* Se miden por la comunicación, el delivery y por el liderazgo de las personas.

## Promociones
* Hay que hacerlas cuando las personas estén listas y las finanzas lo permitan.
* Hay que definir una ruta clara de desarrollo y crecimiento.
* No es un trabajo solo de RRHH, es del lider.
* Hay que hacer público las promociones, hacer reconocimientos.


## Cuellos de botella y burocracia
* El objetivo es tener equipo auto gestionados en todo lo que controlan.
* Disminuir o eliminar dependencias.
* Automatizar.


## Innersource
* Aplicar principios de opensource en equipos.
* El team o la persona que necesita algo lo hace. Bajo los estándares definidos se hace pull request y se hacen las cosas.

## Ingenería hacia la izquierda
* Desde el principio de un feature, fix, proyecto, involucrar a todas las áreas que posiblemente se vean involucradas (_finanzas, operación, rrhh, seguridad_)
* Prevenir desde el principio es ser agil.


## La burocracia
* ¿Las reglas y procesos están optimizados?
* Hay que entender el por que existe el proceso, la regla, el lineamiento.
  * Opción 1: Una vez entendido, puede comunicarlo al team.
  * Opción 2: Si se puede optimizar hay que hacerlo.
  * Opción 3: Si no se puede cambiar u opitmizar entonces hay que automatizarlo.
* Hay que ser disruptivo sin llegar a ser rebelde. Tener en cuenta saber decir las cosas, saber vender. Influenciando de manera positiva en la organización.
 

## Cultura
* Promover los debates abiertos sin importar quien sea.
* Cuando se tomen desiciones se deben ejecutar.
* Estar abierto a las tecnologias nuevas. (_Los estandares pueden cambiar_)
* Respetar el tiempo de los demás. (_Entre equipos, lideres y demás_)
* Promover el feedback. hacer 1 on 1 entre todos.
* Enfocarse en: Personas -> Producto -> Retorno. (En ese orden!)
* Evita el deflecting. Es el exceso de re-dirección. Resolver el problema.
* "Estoy en desacuerdo contigo, pero me sumo a lo que dices". Disagree by commit.


## Rol del lider

### Motivación
* Los equipos deben saber cual es su misión, meta, objetivos.
* Los equipos deben tener todas las herramientas para desarrollar su trabajo.
* Habilitar y/o permitir que los equipos se empoderen, fallen, aprendan.

### Creando lideres
* ser y crear lideres por reconocimiento y no por posición.
* No se puede ser lider cuando no se es buena persoona.

### Desición
* Opción 1: Tomar desición basada en data
* Opción 2: Tomar desición en equipo.
* Opción 3: Instinto.

### Seguimientos
* El liderazgo no se trata de control.
* En Agile se puede conocer status mediante las herramientas.

## Operación
* La calidad de las estimaciones es directamente proporcional a la calidad de su definición.
* Las historias de usuario se deben refinar (groooming) antes de estimarlas.
* La capacidad de los equipos no se conocen cuando son equipos nuevos.

**Definition Of Done**
* Pruebas unitarias.
* Código revisado
* Criterios de aceptación OK.
* Pruebas funcionales OK.
* Requistos no funcionales OK.

**Capacidad vs Velocidad => Estimation accuracy**
* Es bueno buscar comparar las dos métricas.
* El rendimiento de la capacidad y velocidad debe acercarse lo que más se pueda a 100%.
* La velocidad no es un objetivo pero si hay que medirlo.

**Frecuencia de deploys en producción**
* Hay que buscar la frecuencia de despliegues.
* La mejor práctica es un despliegue x historia de usuario. El riesgo es menor, las pruebas son más rápidas y se entrega valor.

**Uptime**
* uptime = tiempo_disponible / (tiempo_disponible + tiempo_no_disponible)
* Chevere medirlo por minutos al mes. (dias al mes * 24 horas * 60 minutos)
* Ideal que el uptime sea de 100%
* Se puede medir por microservicios, servicios, aplicaciones.

## Clima laboral
* Hay que medirlo periodicamente. Con encuestas.

## Agile
* El objetivo no es hacer agile, el objetivo es oobtener valor. Adaptar herramientas para ser mejor.
* Hay que tener embajadores de agile en los equipos.


## Otros
* Plan orugas y semillas.
* Retrospectivas.
* 1 on 1
* Gestión de desempeño.
* Desarrollo y crecimiento personal y profesional.
* Pausas activas reminder.


## 📚 Recursos recomendados
* Articulo: [caos-report](https://www.projectsmart.co.uk/white-papers/chaos-report.pdf)
* Libro: Lean Startup
* Plantilla: [Deck](https://www.canva.com/templates/EADrOnpuH7Y-green-and-blue-illustrative-technology-pitch-deck-presentation/)
* Plantilla: [startup-picth-deck](https://slidebean.com/templates/startup-pitch-deck-template)
* Libro: Domain-Driven Design

