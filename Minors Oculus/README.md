# 📱 MINORS OCULUS

## *Ciberseguridad Infantil Impulsada por IA*

---

## 📋 Tabla de Contenidos

- [¿Qué Aplicación Desarrollaron?](#qué-aplicación-desarrollaron)
- [¿Qué Necesidad Resuelve?](#qué-necesidad-resuelve)
- [Público Objetivo](#público-objetivo)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Problema Identificado](#problema-identificado)
- [Situación Actual](#situación-actual)
- [Justificación del Desarrollo](#justificación-del-desarrollo)
- [Objetivos Específicos](#objetivos-específicos)
- [Nombre de la Aplicación](#nombre-de-la-aplicación)
- [Funcionalidades Principales](#funcionalidades-principales)
- [Usuarios a Quien Va Dirigida](#usuarios-a-quien-va-dirigida)
- [Alcance del Proyecto](#alcance-del-proyecto)
- [Requerimientos No Funcionales](#requerimientos-no-funcionales)
- [Requerimientos Funcionales](#requerimientos-funcionales)
- [Herramientas Utilizadas](#herramientas-utilizadas)
- [Arquitectura General de la Aplicación](#arquitectura-general-de-la-aplicación)
- [Modelo de Datos (Base de Datos)](#modelo-de-datos-base-de-datos)
- [¿Qué Funcionalidades se Lograron Implementar por Completo?](#qué-funcionalidades-se-lograron-implementar-por-completo)
- [¿Qué Dificultades se Encontraron en el Proceso de Desarrollo?](#qué-dificultades-se-encontraron-en-el-proceso-de-desarrollo)
- [¿Qué Mejoras Podrían Agregarse a la Aplicación?](#qué-mejoras-podrían-agregarse-a-la-aplicación)
- [Referencias y Citas](#referencias-y-citas)
- [Modelo de IA](#modelo-de-ia)

---

## ¿Qué Aplicación Desarrollaron?

La aplicación desarrollada se llama **Minors Oculus**.

Es una herramienta de ciberseguridad infantil diseñada para el monitoreo y protección de menores en entornos digitales, utilizando inteligencia artificial (TutelIQ AI) para analizar comunicaciones en tiempo real y detectar riesgos como grooming, ciberbullying y sextorsión.

| **Aspecto** | **Detalle** |
|-------------|-------------|
| **Nombre de la Aplicación** | Minors Oculus |
| **Tipo** | Herramienta de Ciberseguridad Infantil |
| **Motor de IA** | TutelIQ AI |
| **Plataforma** | Android |
| **Enfoque** | Monitoreo y Protección en Tiempo Real |

---

## ¿Qué Necesidad Resuelve?

Minors Oculus resuelve la necesidad crítica de protección y vigilancia proactiva en el entorno digital para menores de edad, abordando específicamente los riesgos que los padres o tutores no pueden supervisar manualmente las 24 horas del día.

### 1. Detección Temprana de Ciberdelitos Complejos

La mayoría de los filtros parentales tradicionales se basan en "palabras prohibidas". Minors Oculus resuelve la necesidad de identificar la intención detrás de los mensajes. Gracias a su integración con la IA de TutelIQ, la app puede detectar patrones de comportamiento asociados a delitos graves que un ojo no experto podría pasar por alto:

| **Ciberdelito** | **Descripción** |
|-----------------|-----------------|
| **Grooming** | Identifica cuando un adulto intenta ganarse la confianza de un niño con fines malintencionados |
| **Sextorsión y Sexting** | Detecta solicitudes de contenido íntimo o amenazas basadas en imágenes |
| **ESCNNA** | Ayuda a prevenir la Explotación Sexual Comercial de Niños, Niñas y Adolescentes |

### 2. Supervisión sin Invasión Excesiva de la Privacidad

Resuelve el dilema de los padres que quieren proteger a sus hijos pero no desean leer cada una de sus conversaciones privadas (lo cual puede dañar la confianza). La app actúa como un filtro inteligente:

- Solo alerta al tutor cuando se detecta un nivel de riesgo alto o sospechoso
- Si la comunicación es inofensiva, el sistema la procesa silenciosamente, permitiendo que el menor mantenga su espacio digital mientras el tutor tiene la tranquilidad de que hay un "guardián" activo

### 3. Respuesta Inmediata ante el Ciberbullying

El acoso digital suele ocurrir en silencio y de forma persistente. La app resuelve la necesidad de visibilidad inmediata para el tutor. Al clasificar mensajes de odio, exclusión o acoso, el padre recibe una notificación en tiempo real, lo que permite intervenir antes de que el daño psicológico sea mayor.

### 4. Brecha de Conocimiento Tecnológico de los Padres

Muchos padres no están familiarizados con los nuevos términos y peligros del internet (como la radicalización, el reclutamiento mula o las estafas románticas). La app resuelve esta falta de información mediante:

- **Veredictos claros:** Traduce datos técnicos a niveles de riesgo (Rojo, Amarillo, Verde)
- **Diccionario de Seguridad:** Provee una base de conocimientos integrada que educa al tutor sobre qué significa cada amenaza detectada

### 5. Consolidación de la Seguridad en un solo Panel

En lugar de revisar cada red social o aplicación de mensajería por separado, Minors Oculus centraliza la seguridad. Resuelve la fragmentación de la información al monitorear todas las notificaciones entrantes del dispositivo vinculado y presentarlas en un Dashboard organizado con estadísticas de seguridad, contactos frecuentes y un puntaje de protección actualizado.

> **En resumen:** La app transforma la seguridad infantil de un modelo reactivo (actuar después de que el problema ocurrió) a un modelo proactivo y determinista, donde la tecnología identifica el peligro en el momento exacto en que llega al dispositivo del menor.

---

## Público Objetivo

### 1. Padres de Familia y Tutores Legales (Usuario Principal)

Es el grupo central al que se dirige la aplicación. Específicamente:

| **Perfil** | **Características** |
|------------|---------------------|
| **Padres con hijos que reciben su primer dispositivo móvil** | Aquellos que sienten temor o incertidumbre ante los riesgos desconocidos del internet |
| **Padres preocupados por el Ciberacoso** | Familias que buscan herramientas para detectar si su hijo está siendo víctima de bullying sin tener que invadir agresivamente su privacidad |
| **Tutores con poco conocimiento tecnológico** | Gracias a su interfaz simplificada y al uso de un "semáforo de riesgo", la app es ideal para adultos que no entienden terminología técnica compleja pero desean mantener a sus hijos seguros |

### 2. Niños y Adolescentes (Beneficiario Directo)

Aunque no son los que operan el panel de control (Dashboard), son el foco de la protección. La app está diseñada para:

| **Perfil** | **Características** |
|------------|---------------------|
| **Menores en etapa escolar (7 a 17 años)** | Quienes son más vulnerables a tácticas de grooming, retos virales peligrosos o exposición a contenido inapropiado en redes sociales y apps de mensajería |
| **Nativos digitales** | Que utilizan activamente WhatsApp, Instagram, Messenger y otras plataformas de comunicación de forma intensiva |

### 3. Instituciones Educativas y Psicólogos Infantiles

Aunque el diseño actual es de uso familiar, el público objetivo también incluye:

- **Centros educativos:** Que buscan recomendar herramientas de prevención a las asociaciones de padres de familia
- **Especialistas en bienestar infantil:** Que pueden utilizar los registros de alertas capturados por la app para entender el contexto de una situación de acoso o trauma digital en un menor bajo su cuidado

### 4. Familias que buscan el equilibrio entre Privacidad y Seguridad

A diferencia de otras apps que permiten ver todo el historial del teléfono, el público objetivo de Minors Oculus son padres que valoran la confianza, ya que la app solo interviene y notifica cuando la IA detecta un patrón de riesgo real, respetando las interacciones normales e inofensivas del menor.

---

## Tecnologías Utilizadas

Para el desarrollo de Minors Oculus, se utilizó un ecosistema robusto de tecnologías modernas para garantizar seguridad, velocidad y precisión en el análisis.

### Lenguajes y Entorno de Desarrollo

| **Tecnología** | **Descripción** |
|----------------|-----------------|
| **Android Studio** | IDE oficial utilizado para la construcción y depuración de la aplicación |
| **Kotlin** | Lenguaje principal de programación, aprovechando características modernas como Corrutinas para procesos asíncronos y Flow para datos en tiempo real |
| **Java** | Presente en componentes base y compatibilidad de librerías |

### Inteligencia Artificial y Análisis

| **Tecnología** | **Descripción** |
|----------------|-----------------|
| **TutelIQ API** | El "cerebro" de la app, encargado del análisis heurístico y determinista de mensajes para detectar grooming, sexting y otras amenazas |
| **RiskEngine (Custom)** | Motor de lógica propio desarrollado para clasificar los niveles de riesgo (Peligrosa, Sospechosa, Inofensiva) basados en la respuesta de la IA |

### Servicios de Google y Backend

| **Tecnología** | **Descripción** |
|----------------|-----------------|
| **Firebase Authentication** | Gestión de acceso y registro seguro de usuarios |
| **Firebase Realtime Database** | Almacenamiento y sincronización de datos de los menores y configuración en la nube |
| **Firebase Analytics** | Monitoreo del rendimiento y uso de la aplicación |
| **Google Play Services** | Soporte para notificaciones y servicios base de Android |

### Persistencia y Datos Locales

| **Tecnología** | **Descripción** |
|----------------|-----------------|
| **Room Persistence Library** | Base de datos local (SQLite) para almacenar el historial de alertas y notificaciones capturadas directamente en el dispositivo |
| **KSP (Kotlin Symbol Processing)** | Utilizado para la generación de código eficiente de la base de datos Room |
| **SharedPreferences** | Para el almacenamiento de sesiones y preferencias rápidas del usuario |

### Networking (Comunicación con el Servidor)

| **Tecnología** | **Descripción** |
|----------------|-----------------|
| **Retrofit** | Librería para convertir la API de TutelIQ en una interfaz de Kotlin de forma segura |
| **OkHttp** | Cliente HTTP para gestionar las peticiones, tiempos de espera (timeouts) y seguridad en la transferencia de datos |
| **Gson** | Para la conversión de datos JSON recibidos de la API en objetos manejables por la app |

### Interfaz de Usuario (UI/UX)

| **Tecnología** | **Descripción** |
|----------------|-----------------|
| **Material Design 3** | Implementación de componentes visuales modernos (Cards, Chips, Material Buttons) |
| **Android XML Layouts** | Estructura de vistas utilizando ConstraintLayout y CoordinatorLayout para interfaces adaptables y complejas |
| **Vector Assets** | Uso de gráficos vectoriales para asegurar nitidez en cualquier resolución de pantalla |

### Sistema y Arquitectura

| **Tecnología** | **Descripción** |
|----------------|-----------------|
| **NotificationListenerService** | Tecnología nativa de Android para la intercepción y lectura de notificaciones entrantes de otras aplicaciones (WhatsApp, Instagram, etc.) |
| **Lifecycle Runtime KTX** | Gestión automática del ciclo de vida de las pantallas para evitar fugas de memoria y optimizar el consumo de batería |
| **Gradle (Kotlin DSL)** | Sistema de automatización de compilación y gestión de dependencias |

---

## Problema Identificado

El problema central identificado que impulsó el desarrollo de Minors Oculus fue la vulnerabilidad crítica de los menores ante los peligros invisibles de las comunicaciones digitales modernas.

| **Problema** | **Descripción** |
|--------------|-----------------|
| **1. Ineficiencia de los Métodos de Control Tradicionales** | Los filtros parentales convencionales suelen basarse en listas estáticas de "palabras prohibidas". El problema es que los depredadores digitales (groomers) y acosadores utilizan un lenguaje manipulativo, sutil y cambiante que estos filtros no logran detectar, dejando a los niños desprotegidos ante intenciones maliciosas disfrazadas de conversaciones normales |
| **2. Aumento de Ciberdelitos Infantiles Complejos** | Se identificó un incremento alarmante en delitos como el Grooming, la Sextorsión, el Ciberbullying y el Reclutamiento para actividades ilícitas a través de aplicaciones de mensajería (WhatsApp, Instagram, etc.). Estos problemas suelen ocurrir en "silencio", sin que el menor sepa que está en riesgo hasta que es demasiado tarde |
| **3. La Brecha de Supervisión y Privacidad** | Muchos padres se enfrentan al dilema de querer proteger a sus hijos pero no tener el tiempo para revisar miles de mensajes manualmente, o no querer invadir la privacidad de sus hijos rompiendo la confianza. El problema era la falta de un "guardián inteligente" que solo interviniera cuando existiera un peligro real |
| **4. Falta de Alertas en Tiempo Real** | En situaciones de acoso o manipulación, el tiempo es vital. Sin una herramienta como Minors Oculus, los padres suelen enterarse de los problemas semanas o meses después de que iniciaron. Existía la necesidad de un sistema que detectara la amenaza en el segundo exacto en que la notificación llega al celular del menor |
| **5. Desconocimiento de los Nuevos Riesgos Digitales** | Muchos tutores no están familiarizados con nuevas tácticas como la Ingeniería Social, el Radicalismo o el Fraude en Aplicaciones. La app resuelve el problema de la "desinformación del tutor" traduciendo comportamientos digitales complejos en veredictos de riesgo claros y educativos |

> **En conclusión:** El problema identificado fue la indefensión de los menores en el ecosistema digital debido a la velocidad, sofisticación y naturaleza privada de las comunicaciones móviles actuales.

---

## Situación Actual

La situación actual del problema que resuelve Minors Oculus es de vulnerabilidad creciente y evolución de amenazas, lo que hace que la existencia de la app sea más relevante que nunca.

| **Punto Clave** | **Descripción** |
|-----------------|-----------------|
| **1. Sofisticación mediante Inteligencia Artificial Generativa** | El problema ya no se limita a mensajes de texto simples. La situación actual incluye el uso de Deepfakes y voces sintéticas para suplantar identidad o crear contenido de abuso (MASNNA). Como se observa en la base de conocimientos de la app, existe una necesidad urgente de detectar "Pornografía Infantil Generativa" y "Detección Sintética", amenazas que antes no existían |
| **2. "Ceguera" de los Padres ante el Cifrado** | Actualmente, aplicaciones como WhatsApp e Instagram dominan la comunicación infantil. Al ser plataformas cerradas y cifradas, los padres se encuentran en una situación de "ceguera digital". La situación actual es que el control parental basado en "revisar el historial" es obsoleto, ya que los mensajes pueden borrarse o desaparecer, haciendo que la intercepción en tiempo real de notificaciones (que es lo que hace Minors Oculus) sea la única forma efectiva de supervisión |
| **3. Normalización del Inicio Temprano en Redes Sociales** | La edad promedio en la que un menor recibe su primer dispositivo sigue bajando (actualmente entre los 8 y 10 años). Esto ha creado una situación donde niños con poca madurez emocional están expuestos a tácticas de Ingeniería Social y Grooming muy avanzadas. El problema actual es que el agresor ya no busca un encuentro físico inmediato, sino que busca la manipulación psicológica de largo plazo, algo que solo una IA como TutelIQ puede identificar analizando el contexto de la charla |
| **4. Fragmentación de Riesgos (Nuevas Dimensiones)** | El problema ha mutado de solo "extraños hablando con niños" a riesgos multifacéticos que la app ya contempla en su código:<br>• **Radicalización:** Uso de redes para captar menores en ideologías extremas<br>• **Apuestas Digitales:** Acceso fácil a juegos de azar desde el móvil<br>• **Fraude en Apps:** Estafas económicas dirigidas a la ingenuidad del menor |

> **En conclusión:** La situación actual es de una brecha de seguridad crítica. Mientras las herramientas de comunicación avanzan, la capacidad de supervisión humana se queda atrás. Minors Oculus se posiciona en esta situación no como una opción, sino como una capa de inteligencia necesaria para cerrar esa brecha y devolver el control a los tutores mediante la vigilancia determinista.

---

## Justificación del Desarrollo

La justificación del desarrollo de Minors Oculus (Ciberseguridad Infantil) se fundamenta en la urgente necesidad de cerrar la brecha entre la exposición digital masiva de los menores y la limitada capacidad de supervisión en tiempo real de los padres.

| **Pilar** | **Descripción** |
|-----------|-----------------|
| **1. Insuficiencia de los Métodos Tradicionales** | Los controles parentales convencionales se limitan a bloquear aplicaciones o filtrar palabras clave. Sin embargo, el lenguaje utilizado en delitos como el grooming o la sextorsión es sutil, manipulativo y cambia constantemente para evadir estos filtros. El desarrollo de esta app se justifica al introducir un análisis de intención mediante Inteligencia Artificial (TutelIQ), que entiende el contexto de la conversación, no solo las palabras aisladas |
| **2. El Factor Tiempo en la Prevención** | En la mayoría de los casos de acoso o abuso digital, los padres se enteran de la situación meses después de que el daño ha comenzado. Esta app se justifica al proporcionar una respuesta inmediata. Al capturar notificaciones en tiempo real, permite que el tutor intervenga en el "momento cero" de la detección, evitando que una conversación sospechosa se convierta en una tragedia |
| **3. Preservación del Vínculo de Confianza (Privacidad vs. Seguridad)** | Una de las mayores justificaciones es el equilibrio ético. Muchos padres evitan monitorear a sus hijos porque no quieren invadir su privacidad leyendo cada mensaje inofensivo. Minors Oculus justifica su existencia como un "vigilante silencioso": el sistema ignora las conversaciones seguras y solo rompe el anonimato cuando la IA confirma un riesgo. Esto permite proteger al menor sin destruir la confianza necesaria en la relación padre-hijo |
| **4. Empoderamiento y Educación del Tutor** | Existe una brecha generacional donde los niños navegan en plataformas que los padres no comprenden. La app justifica su desarrollo al actuar como un traductor de riesgos. No solo alerta sobre un peligro, sino que educa al padre a través de su Diccionario de Seguridad y clasificaciones claras (ESCNNA, Grooming, Radicalización), permitiendo que el tutor tome decisiones informadas y no solo basadas en el miedo |
| **5. Respuesta al Incremento de Ciberdelitos** | Estadísticamente, los delitos digitales contra menores han aumentado con la digitalización acelerada. La creación de una herramienta que utilice "Inteligencia Determinista" se justifica como una medida de defensa necesaria ante un ecosistema digital que, aunque ofrece muchas oportunidades educativas, se ha convertido en el principal vector de captación para depredadores y estafadores |

> **En conclusión:** El desarrollo de la aplicación se justifica no como una herramienta de espionaje, sino como un sistema de protección digital avanzado que devuelve a los responsables del menor la capacidad de actuar proactivamente en un entorno donde la supervisión humana manual es físicamente imposible.

---

## Objetivos Específicos

Para el proyecto Minors Oculus, se han definido los siguientes 5 objetivos específicos que garantizan la funcionalidad técnica y el propósito de protección de la aplicación:

| **Objetivo** | **Descripción** |
|--------------|-----------------|
| **1. Implementar un servicio de escucha activa en tiempo real** | Desarrollar un sistema basado en NotificationListenerService capaz de interceptar y procesar de manera inmediata todas las notificaciones de mensajería (WhatsApp, Messenger, Instagram, etc.) que llegan al dispositivo del menor |
| **2. Integrar análisis heurístico mediante Inteligencia Artificial** | Conectar la aplicación con la API de TutelIQ para realizar un análisis profundo del contexto e intención de los mensajes, permitiendo clasificar las comunicaciones en dimensiones de riesgo específicas como Grooming, Sexting, Ciberbullying o Radicalización |
| **3. Establecer un sistema de alertas críticas para el tutor** | Diseñar un mecanismo de notificaciones push de alta prioridad que informe al padre o tutor en el "momento cero" cuando se detecte un riesgo de nivel 🔴 PELIGROSA, incluyendo detalles del remitente y el tipo de amenaza identificada |
| **4. Centralizar la gestión de seguridad en un Dashboard interactivo** | Crear una interfaz de control para el padre que consolide estadísticas de protección, identifique contactos sospechosos y muestre un "Puntaje de Seguridad" dinámico basado en los hallazgos acumulados por la IA |
| **5. Proveer una base de conocimientos especializada (Diccionario de Seguridad)** | Integrar un módulo educativo dentro de la app que defina y explique términos técnicos de ciberdelitos infantiles (ESCNNA, Sextorsión, Ingeniería Social, etc.), empoderando al tutor con información para tomar decisiones preventivas informadas |

---

## Nombre de la Aplicación

**Minors Oculus**

---

## Funcionalidades Principales

Basado en el análisis de la arquitectura y el código fuente del proyecto, las funcionalidades principales de Minors Oculus son:

| **Funcionalidad** | **Descripción** |
|-------------------|-----------------|
| **1. Monitoreo de Notificaciones en Tiempo Real** | • Utiliza un servicio de escucha (NotificationListenerService) para interceptar mensajes entrantes de aplicaciones de mensajería como WhatsApp, Instagram y Messenger en el dispositivo del menor<br>• Extrae contenido crítico, remitente y metadatos de la comunicación sin necesidad de acceder directamente a la base de datos de las apps externas |
| **2. Análisis de Amenazas mediante IA (TutelIQ)** | • Integra un motor de riesgo (RiskEngine) que se comunica con la API de TutelIQ para realizar análisis deterministas<br>• Detecta intenciones maliciosas en 15 dimensiones de análisis, incluyendo: Grooming, Sexting, Ciberbullying, Radicalización, Ingeniería Social, Fraude, entre otros |
| **3. Clasificación Automática por Niveles de Riesgo** | Categoriza cada mensaje interceptado bajo un sistema de semáforo:<br>• 🔴 **PELIGROSA:** Riesgo crítico que requiere intervención inmediata<br>• 🟡 **SOSPECHOSA:** Patrones extraños que ameritan revisión del tutor<br>• 🟢 **INOFENSIVA:** Mensajes normales que no representan peligro |
| **4. Dashboard de Seguridad Inteligente** | • Presenta un panel central con un Puntaje de Seguridad (Safety Score) dinámico que se calcula en función de la cantidad y gravedad de las alertas detectadas<br>• Muestra estadísticas acumuladas de alertas, aplicaciones con mayor actividad de riesgo y cantidad de contactos monitoreados |
| **5. Centro de Alertas y Gestión de Riesgos** | Almacena un historial detallado de las detecciones críticas, permitiendo al padre ver quién envió el mensaje, a través de qué app llegó y cuál es el tipo de amenaza (categoría) identificada por la IA |
| **6. Panel de Experto TutelIQ (Análisis Manual)** | Permite al tutor seleccionar mensajes específicos del historial o ingresar texto manualmente para realizar un "Análisis Profundo" enfocado en una dimensión de seguridad particular (por ejemplo, analizar un mensaje sospechoso específicamente para detectar indicios de Grooming) |
| **7. Diccionario de Seguridad y Base de Conocimientos** | Módulo educativo integrado que define y explica los diferentes ciberdelitos (ESCNNA, Sextorsión, ASNIC, etc.), ayudando a cerrar la brecha de conocimiento tecnológico de los padres |
| **8. Gestión de Dispositivos y Menores** | Sistema de autenticación y vinculación para gestionar la protección de uno o más menores desde una única cuenta de tutor, con almacenamiento seguro de datos mediante Firebase y Room |

---

## Usuarios a Quien Va Dirigida

Minors Oculus está dirigida a un ecosistema de usuarios centrado en la protección del menor, dividiéndose principalmente en tres perfiles:

### 1. Padres de Familia y Tutores Legales (Usuarios de Control)

Es el público principal que instala y gestiona la aplicación. Se dirige especialmente a:

| **Perfil** | **Descripción** |
|------------|-----------------|
| **Padres con hijos que inician su vida digital** | Aquellos que han entregado el primer smartphone a sus hijos y buscan una red de seguridad proactiva |
| **Padres con poco tiempo o conocimientos técnicos** | La app está diseñada para adultos que no pueden supervisar manualmente cada mensaje y necesitan que una IA les "traduzca" comportamientos complejos a niveles de riesgo simples (Rojo, Amarillo, Verde) |
| **Tutores que valoran la privacidad** | Dirigida a quienes no desean invadir la intimidad de sus hijos leyendo todo el historial, sino que prefieren un "vigilante silencioso" que solo alerte cuando detecte un peligro real |

### 2. Niños y Adolescentes (Usuarios Protegidos)

Aunque no son quienes operan el panel de control, son los beneficiarios directos de la tecnología. El perfil incluye:

| **Perfil** | **Descripción** |
|------------|-----------------|
| **Menores de entre 7 y 17 años** | Rango de edad más vulnerable a tácticas de grooming, acoso escolar y manipulación en redes sociales |
| **Usuarios activos de redes sociales y mensajería** | Niños que utilizan cotidianamente WhatsApp, Instagram, Messenger y otras plataformas donde el anonimato facilita el acercamiento de depredadores |

### 3. Instituciones y Profesionales del Bienestar Infantil

| **Perfil** | **Descripción** |
|------------|-----------------|
| **Centros Educativos** | Colegios que desean fomentar el uso de herramientas preventivas entre sus asociaciones de padres |
| **Psicólogos y Consejeros** | Profesionales que pueden apoyarse en los registros de alertas capturados por la app para entender el contexto de una situación de riesgo o trauma digital que esté afectando al menor |

> **En resumen:** La aplicación va dirigida a familias modernas que buscan un equilibrio entre la libertad digital de sus hijos y una seguridad inteligente y no invasiva.

---

## Alcance del Proyecto

El alcance de Minors Oculus está diseñado para ser una solución integral de ciberseguridad en el ecosistema móvil, con una arquitectura que permite una escalabilidad significativa.

### Alcance Actual del Proyecto

En su fase actual, el proyecto abarca:

| **Área** | **Descripción** |
|----------|-----------------|
| **Intercepción Multi-plataforma** | Capacidad de monitorear notificaciones de las aplicaciones de mensajería y redes sociales más utilizadas (WhatsApp, Instagram, Facebook, Messenger, TikTok, Discord, etc.) |
| **Análisis Multidimensional** | Detección de 15 tipos de riesgos digitales, desde los más comunes como el Ciberbullying, hasta amenazas complejas como la Radicalización, Ingeniería Social y Reclutamiento Mula |
| **Gestión Centralizada** | Un panel de control para el tutor que permite supervisar múltiples aplicaciones y contactos desde un solo lugar, con estadísticas de seguridad en tiempo real |
| **Educación Preventiva** | Inclusión de una base de conocimientos técnica para empoderar a los padres ante los nuevos términos del cibercrimen |

### Miras de Expansión (Hoja de Ruta)

El proyecto ha sido estructurado pensando en una Versión 2.0 y superiores:

| **Expansión** | **Descripción** |
|---------------|-----------------|
| **1. Vinculación de Cuentas Oficiales** | Como se observa en los recursos de la app (btn_link_official_account), se planea ir más allá de las notificaciones para permitir una integración directa con las APIs oficiales de las redes sociales para obtener un historial más profundo |
| **2. Expansión a Nuevos Dispositivos (IoT)** | El alcance futuro contempla el monitoreo de otros dispositivos conectados que utilizan los menores, como consolas de videojuegos (PlayStation/Xbox) y tablets, donde el chat de voz y texto es frecuente |
| **3. Detección de Contenido Multimedia (Deep Learning)** | Evolucionar del análisis de texto al análisis de imágenes y videos en tiempo real para detectar automáticamente contenido inapropiado o deepfakes antes de que el menor los abra |
| **4. Gamificación para el Menor** | Incluir un módulo para el hijo que, en lugar de ser solo "vigilado", reciba micro-capacitaciones y recompensas por navegar de forma segura, convirtiendo la seguridad en un aprendizaje mutuo |
| **5. Reporte Automatizado a Autoridades** | Integrar un canal directo para que, ante una alerta de nivel 🔴 CRÍTICO (como un caso confirmado de Grooming o ESCNNA), los padres puedan generar un reporte técnico exportable para presentar ante la policía cibernética |

> **En conclusión:** El alcance actual es el de una herramienta de vigilancia determinista inteligente, pero sus miras de expansión apuntan a convertirse en un ecosistema completo de defensa y educación digital para la familia.

---

## Requerimientos No Funcionales

Los requerimientos no funcionales de Minors Oculus definen las cualidades del sistema, como su seguridad, rendimiento y confiabilidad.

| **Categoría** | **Requerimiento** | **Descripción** |
|---------------|-------------------|-----------------|
| **1. Seguridad y Privacidad** | Autenticación Robusta | El acceso a la plataforma debe estar protegido mediante Firebase Authentication, garantizando que solo el tutor autorizado pueda visualizar los datos del menor |
| | Privacidad de Datos | La aplicación debe procesar las notificaciones en tiempo real y solo almacenar永久mente aquellas que representen un riesgo real, respetando la privacidad de las comunicaciones inofensivas |
| | Integridad de la API | Todas las peticiones al motor de IA (TutelIQ) deben realizarse mediante protocolos seguros (HTTPS) y autenticación por Token (Bearer Token) para evitar la interceptación de datos sensibles |
| **2. Rendimiento y Eficiencia** | Procesamiento Asíncrono | El escaneo de mensajes no debe bloquear la interfaz de usuario. Para ello, se utilizan Kotlin Coroutines y Flow, asegurando que el análisis ocurra en segundo plano sin afectar la fluidez del dispositivo |
| | Bajo Consumo de Recursos | El servicio de escucha (NotificationListenerService) debe estar optimizado para tener un impacto mínimo en la batería y la memoria RAM del dispositivo del menor |
| | Latencia de Respuesta | Las peticiones a la API de riesgo deben tener un tiempo de espera (timeout) controlado (15 segundos configurados en OkHttp) para garantizar una respuesta rápida o una gestión de error eficiente si no hay conexión |
| **3. Disponibilidad y Persistencia** | Soporte Offline | Gracias a Room Database, la aplicación debe ser capaz de mostrar el historial de alertas y datos previamente capturados incluso si el dispositivo no tiene conexión a internet en ese momento |
| | Sincronización en la Nube | El estado de protección y los datos del perfil deben estar disponibles y sincronizados mediante Firebase Realtime Database, permitiendo la recuperación de información en caso de cambio de dispositivo |
| **4. Usability (Usabilidad)** | Diseño Intuitivo | La interfaz debe seguir las guías de Material Design 3, utilizando componentes visuales claros (como el sistema de semáforo de colores) para que padres sin conocimientos técnicos puedan interpretar los riesgos fácilmente |
| | Accesibilidad | La aplicación debe ser compatible con diferentes tamaños de pantalla y densidades de píxeles mediante el uso de layouts adaptables (ConstraintLayout) |
| **5. Compatibilidad** | Versatilidad de Android | La app debe ser compatible con dispositivos que utilicen desde Android 7.0 (API 24) hasta las versiones más recientes (API 35), cubriendo la gran mayoría de smartphones actuales en el mercado |
| | Integración con Terceros | El sistema debe ser capaz de interceptar notificaciones de una amplia variedad de aplicaciones externas (WhatsApp, TikTok, Instagram, etc.) sin requerir modificaciones en dichas apps |
| **6. Confiabilidad** | Robustez ante Errores | El motor de riesgo (RiskEngine) debe incluir bloques de manejo de excepciones (try-catch) para asegurar que un fallo en la respuesta del servidor de IA no provoque el cierre inesperado (crash) de la aplicación |

---

## Requerimientos Funcionales

Los requerimientos funcionales de Minors Oculus describen las acciones específicas que el sistema debe realizar para cumplir su propósito de protección.

| **Categoría** | **Requerimiento** | **Descripción** |
|---------------|-------------------|-----------------|
| **1. Gestión de Usuarios y Acceso** | Registro e Inicio de Sesión | El sistema debe permitir a los tutores crear una cuenta y autenticarse de forma segura utilizando correo y contraseña (vía Firebase) |
| | Gestión de Perfiles de Menores | El tutor debe poder registrar y vincular uno o más perfiles de menores para su supervisión individualizada |
| **2. Monitoreo de Comunicaciones (Core)** | Intercepción de Notificaciones | La app debe capturar en tiempo real las notificaciones entrantes de aplicaciones de mensajería externa (WhatsApp, Messenger, Instagram, TikTok, etc.) |
| | Extracción de Contenido | El sistema debe extraer automáticamente el texto del mensaje, el nombre del remitente y la aplicación de origen de cada notificación capturada |
| **3. Análisis de Riesgos con IA** | Análisis Determinista | El sistema debe enviar el texto capturado a la API de TutelIQ para evaluar la intención del mensaje en 15 dimensiones de riesgo (Grooming, Ciberbullying, Sexting, etc.) |
| | Clasificación por Niveles | La app debe asignar automáticamente un nivel de riesgo (Peligrosa, Sospechosa o Inofensiva) a cada comunicación basándose en el veredicto de la IA |
| **4. Sistema de Alertas y Notificaciones** | Alertas Críticas para el Tutor | El sistema debe generar notificaciones push de alta prioridad en el dispositivo del tutor cuando se detecte un mensaje de nivel 🔴 PELIGROSA |
| | Historial de Alertas | La app debe almacenar y mostrar una lista cronológica de todas las detecciones de riesgo, permitiendo al tutor revisar los detalles de cada mensaje y su categoría de amenaza |
| **5. Supervisión y Estadísticas (Dashboard)** | Cálculo de Safety Score | El sistema debe calcular un puntaje de seguridad dinámico (0-100%) para el menor, basado en la frecuencia y gravedad de las alertas detectadas |
| | Estadísticas de Uso | La app debe mostrar un resumen de las aplicaciones que generan más riesgos y la cantidad de contactos monitoreados |
| **6. Análisis Experto y Manual** | Consulta Profunda | El tutor debe poder ingresar texto de forma manual o seleccionar un mensaje del historial para realizar un análisis específico en una dimensión de seguridad elegida (ej. análisis enfocado solo en detectar Radicalización) |
| **7. Educación y Prevención** | Diccionario de Ciberdelitos | La app debe proporcionar una base de conocimientos integrada que defina términos como ESCNNA, Grooming y Sextorsión para educar al tutor |
| **8. Gestión de Datos y Persistencia** | Almacenamiento Local | El sistema debe guardar el historial de alertas en una base de datos local (Room) para permitir la consulta sin conexión a internet |
| | Sincronización en la Nube | Los datos de configuración y perfiles deben sincronizarse en tiempo real entre el dispositivo del menor y el del tutor |

---

## Herramientas Utilizadas

Para el desarrollo de Minors Oculus, se utilizó un conjunto de herramientas de vanguardia que abarcan desde el diseño y la programación hasta la inteligencia artificial y los servicios en la nube.

| **Categoría** | **Herramienta** | **Descripción** |
|---------------|-----------------|-----------------|
| **1. Entorno de Desarrollo y Lenguajes** | Android Studio | El IDE principal utilizado para la codificación, diseño de interfaces y depuración |
| | Kotlin | Lenguaje de programación principal (moderno, conciso y seguro) |
| | Java | Utilizado para la compatibilidad de ciertos componentes y actividades base |
| | Gradle (Kotlin DSL) | Herramienta para la automatización de la compilación y gestión de dependencias |
| **2. Inteligencia Artificial (El Cerebro)** | TutelIQ API | Herramienta fundamental para el análisis determinista y heurístico de los mensajes, permitiendo la detección de patrones de riesgo complejos |
| **3. Backend y Servicios en la Nube (Firebase)** | Firebase Authentication | Para la gestión segura de registros e inicios de sesión de los tutores |
| | Firebase Realtime Database | Para la sincronización de datos de menores y alertas en tiempo real entre dispositivos |
| | Firebase Analytics | Herramienta para medir el rendimiento y uso de la aplicación |
| | Google Services Plugin | Para la integración de todo el ecosistema de Google |
| **4. Persistencia y Gestión de Datos** | Room Persistence Library | Base de datos local (SQLite) que permite que la app funcione y guarde alertas incluso sin internet |
| | KSP (Kotlin Symbol Processing) | Herramienta de análisis de símbolos para generar código de Room de manera más rápida y eficiente |
| **5. Comunicación y Redes (Networking)** | Retrofit | Para convertir la API de TutelIQ en interfaces de código manejables |
| | OkHttp | Cliente HTTP para gestionar las peticiones de red y la seguridad de las transferencias |
| | Gson | Para la conversión de datos JSON recibidos de la API en objetos de programación |
| **6. Interfaz de Usuario (UI) y Diseño** | Material Design 3 (Material Components) | Para el uso de componentes visuales modernos (Cards, Chips, Buttons) |
| | ConstraintLayout & CoordinatorLayout | Herramientas de diseño XML para crear interfaces adaptables y animaciones fluidas |
| | Vector Asset Studio | Para la creación de iconos y gráficos escalables que no pierden calidad |
| **7. Tecnologías de Sistema Android** | NotificationListenerService | Herramienta nativa de Android crucial para la funcionalidad de interceptar y leer notificaciones de otras apps |
| | Android KTX | Extensiones de Kotlin que simplifican el uso de las APIs de Android |
| **8. Diseño y Prototipado** | Figma | Utilizado para la concepción visual, creación de prototipos de alta fidelidad y definición de la experiencia de usuario (UX) |

---

## Arquitectura General de la Aplicación

La arquitectura de Minors Oculus sigue los principios modernos de desarrollo de Android, enfocándose en la separación de responsabilidades, la reactividad y el procesamiento en segundo plano. Se puede definir como una arquitectura **MVVM (Model-View-ViewModel)** adaptada para el procesamiento de flujos de datos en tiempo real.

### Capas de la Arquitectura

| **Capa** | **Componentes** | **Responsabilidad** |
|----------|-----------------|----------------------|
| **1. Capa de Presentación (UI)** | • Activities (Vistas): DashboardActivity, AlertsActivity, AiTuteliqActivity<br>• Adapters: AlertAdapter | Su única responsabilidad es renderizar la interfaz de usuario y reaccionar a las interacciones del tutor |
| **2. Capa de Servicios y Procesamiento (Background)** | • NotificationMonitorService: Servicio persistente que hereda de NotificationListenerService<br>• Corrutinas y Flows | Funciona como un "sensor" que intercepta notificaciones del sistema Android, extrae el texto y lo envía al motor de análisis. Se utiliza lifecycleScope y CoroutineScope para asegurar que el procesamiento de mensajes ocurra en hilos secundarios |
| **3. Capa de Dominio / Lógica de Negocio** | • RiskEngine (Motor de Riesgo)<br>• Modelos de Datos: AlertEntity, RiskLevel | Actúa como el orquestador del análisis. Decide qué datos enviar a la IA, cómo interpretar los niveles de riesgo devueltos y cómo categorizar las amenazas |
| **4. Capa de Datos (Data Layer)** | • Persistencia Local (Room): AppDatabase, AlertDao<br>• Red / Cloud (Retrofit & Firebase) | Gestiona dos fuentes de datos: almacenamiento local SQLite para historial de alertas (acceso rápido y offline) y comunicación con API externa de TutelIQ para análisis de IA, además de autenticación y sincronización en la nube |

### Flujo de Datos (Arquitectura de Seguridad)

| **Paso** | **Acción** | **Componente Involucrado** |
|----------|------------|----------------------------|
| **1. Entrada** | El sistema Android recibe una notificación | Sistema Operativo |
| **2. Captura** | NotificationMonitorService extrae el texto | NotificationListenerService |
| **3. Análisis** | El texto viaja al RiskEngine, que consulta a la IA de TutelIQ vía Retrofit | RiskEngine + Retrofit |
| **4. Decisión** | El resultado se clasifica y se guarda en Room | RiskEngine + Room Database |
| **5. Notificación** | Si es crítico, se dispara una notificación push al tutor | Firebase + Sistema de Notificaciones |
| **6. Observación** | La UI (Dashboard) observa los cambios en la base de datos y se actualiza automáticamente | LiveData/Flow + Dashboard |

> **En resumen:** Es una arquitectura desacoplada y reactiva, diseñada para ser robusta ante fallos de red y eficiente en el consumo de recursos, garantizando que el monitoreo sea constante y no intrusivo.

---

## Modelo de Datos (Base de Datos)

El modelo de datos de Minors Oculus utiliza un enfoque híbrido que combina una base de datos relacional local para el historial y una estructura NoSQL en la nube para la sincronización en tiempo real.

### 1. Modelo de Datos Local (SQL - Room/SQLite)

La aplicación utiliza la librería Room para gestionar una base de datos SQLite interna. El modelo principal es la entidad **AlertEntity**:

| **Campo** | **Tipo** | **Descripción** |
|-----------|----------|-----------------|
| **id** | Long | Clave primaria autogenerada |
| **appPackage** | String | Nombre del paquete de la aplicación donde se originó la alerta (ej. com.whatsapp) |
| **sender** | String | Nombre del remitente del mensaje |
| **message** | String | Contenido textual interceptado |
| **timestamp** | Long | Fecha y hora exacta de la captura en milisegundos |
| **riskLevel** | String | Nivel de riesgo asignado por la IA (PELIGROSA, SOSPECHOSA, INOFENSIVA) |
| **categories** | String | Lista de amenazas detectadas (ej. "Grooming, Sexting") almacenada como una cadena separada por comas |

### 2. Modelo de Datos en la Nube (NoSQL - Firebase Realtime Database)

Para la gestión de usuarios y la vinculación entre el dispositivo del tutor y el del menor, la app organiza los datos en una estructura de árbol (JSON):

| **Nodo** | **Descripción** |
|----------|-----------------|
| **users/** | Almacena el perfil del tutor (nombre, correo, ID único) |
| **minors/** | Contiene la información de los hijos registrados, incluyendo su nombre, edad y el estado de protección actual |
| **configurations/** | Ajustes de monitoreo específicos que el tutor define para cada dispositivo vinculado |

### 3. Modelo de Análisis de Amenazas (Data Classes)

Para el intercambio de información con la API de TutelIQ y el procesamiento lógico interno:

| **Clase** | **Descripción** |
|-----------|-----------------|
| **DetectionRequest** | Contiene el texto a analizar y el contexto (análisis profundo vs. rápido) |
| **ThreatDataset** | Estructura que organiza las categorías de amenazas, niveles y palabras clave para el motor de búsqueda interna |
| **ThreatCategory** | Define cada tipo de riesgo con su nombre, nivel de severidad y patrones asociados |

### 4. Modelo de Sesión (SharedPreferences)

Para datos volátiles y de acceso rápido:

| **Clave** | **Descripción** |
|-----------|-----------------|
| **user_prefs** | Almacena el estado de la sesión (is_logged_in), el nombre del usuario actual y tokens de acceso temporales |

> **En resumen:** La organización de datos es determinista y estructurada. Utiliza SQL para garantizar que el historial de seguridad no se pierda (persistencia local) y NoSQL para permitir que las alertas y cambios de configuración se reflejen instantáneamente entre el teléfono del hijo y el del padre.

---

## ¿Qué Funcionalidades se Lograron Implementar por Completo?

Basado en el análisis técnico del código fuente y los módulos desarrollados en el proyecto Minors Oculus, estas son las funcionalidades que se lograron implementar por completo:

| **Funcionalidad** | **Descripción** |
|-------------------|-----------------|
| **1. Escaneo de Comunicaciones en Tiempo Real** | • **Intercepción Determinista:** Implementación exitosa del NotificationMonitorService, que captura notificaciones entrantes de aplicaciones externas (WhatsApp, Instagram, Messenger, TikTok, etc.) sin interferir con el uso del dispositivo<br>• **Extracción de Metadatos:** El sistema extrae con precisión el remitente, el cuerpo del mensaje (incluyendo textos largos y mensajes de chat estructurados) y la aplicación de origen |
| **2. Integración con Inteligencia Artificial (TutelIQ)** | • **Motor de Análisis (RiskEngine):** Conexión funcional con la API de TutelIQ mediante Retrofit para realizar análisis heurísticos de intención<br>• **Dimensiones de Riesgo:** Capacidad de clasificar mensajes en 15 categorías específicas, tales como Grooming, Ciberbullying, Sextorsión, Radicalización y Fraude |
| **3. Sistema de Clasificación y Semáforo de Riesgo** | Implementación de una lógica que traduce los resultados de la IA en niveles visuales:<br>• 🔴 **PELIGROSA:** Dispara alertas de alta prioridad<br>• 🟡 **SOSPECHOSA:** Registro para revisión manual<br>• 🟢 **INOFENSIVA:** Procesamiento silencioso |
| **4. Dashboard de Control para el Tutor** | • **Safety Score Dinámico:** Algoritmo que calcula el puntaje de seguridad del menor (0-100%) basándose en la gravedad de las alertas detectadas en tiempo real<br>• **Estadísticas de Protección:** Visualización del conteo de alertas críticas, aplicaciones con mayor actividad de riesgo y número de contactos monitoreados |
| **5. Persistencia y Gestión de Datos Local** | • **Base de Datos Room:** Almacenamiento local del historial de alertas que permite al tutor consultar detecciones pasadas, incluso sin conexión a internet<br>• **Gestión de Alertas:** Funcionalidad para visualizar el detalle de cada amenaza y eliminar registros del historial |
| **6. Centro de Análisis Experto (TutelIQ AI Panel)** | **Análisis Manual:** Interfaz que permite al tutor seleccionar una notificación específica o ingresar texto manualmente para realizar un escaneo profundo enfocado en una dimensión de seguridad particular (ej. detectar específicamente "Ingeniería Social") |
| **7. Seguridad y Permisos Avanzados** | • **Gestión de Permisos Críticos:** Flujo de usuario implementado para solicitar y verificar el acceso a notificaciones y contactos, esenciales para el funcionamiento del "guardián"<br>• **Autenticación:** Sistema de inicio de sesión y registro vinculado a Firebase para asegurar que solo el tutor tenga acceso al panel de control |
| **8. Base de Conocimientos (Diccionario de Seguridad)** | **Módulo Educativo:** Implementación completa de una guía que define términos de ciberdelincuencia (ESCNNA, Grooming, Sexting), ayudando a los padres a comprender los riesgos detectados por la IA |

---

## ¿Qué Dificultades se Encontraron en el Proceso de Desarrollo?

Durante el desarrollo de Minors Oculus, se enfrentaron varios retos técnicos y arquitectónicos significativos para lograr que una aplicación de seguridad fuera efectiva sin comprometer el rendimiento del dispositivo.

| **Dificultad** | **Descripción** |
|----------------|-----------------|
| **1. Gestión de Permisos Críticos y Sensibles** | Uno de los mayores retos fue la implementación del NotificationListenerService. Android impone restricciones estrictas por motivos de seguridad:<br>• **Permiso Manual:** No es posible activar la escucha de notificaciones mediante código; el usuario debe ser guiado a un menú profundo de los ajustes del sistema. Lograr una UX (Experiencia de Usuario) clara para que un padre no técnico complete este paso fue complejo<br>• **Ciclo de Vida del Servicio:** Garantizar que el servicio de monitoreo no fuera cerrado por el sistema para ahorrar batería requirió la implementación de una notificación persistente (Foreground Service) y una lógica de reconexión robusta |
| **2. Sincronización entre el Código y la Interfaz (XML vs. Kotlin)** | Durante la expansión de las capacidades de la IA, surgió una dificultad técnica importante al mantener la coherencia entre los archivos:<br>• **Referencias No Resueltas:** La actividad de análisis (AiTuteliqActivity) creció rápidamente para soportar 15 dimensiones de riesgo (Grooming, Radicalización, etc.), lo que generó errores de compilación cuando los IDs del diseño XML no coincidían exactamente con las referencias en el código Kotlin<br>• **Complejidad de la UI:** Diseñar una interfaz que albergara tantos elementos interactivos (Chips, Spinners, Inputs) en una sola pantalla sin saturar al usuario requirió el uso intensivo de NestedScrollView y ChipGroups horizontales |
| **3. Conflicto de Duplicidad de Lenguajes (Java y Kotlin)** | El proyecto muestra una transición de lenguaje que presentó dificultades técnicas en la compilación:<br>• **Archivos Duplicados:** Se detectó la coexistencia de archivos .java y .kt para las mismas actividades (como MainActivity). Esto causó conflictos de duplicidad y errores en el procesador de símbolos de Room (KSP)<br>• **Solución en Gradle:** Se tuvo que configurar específicamente el archivo build.gradle.kts para ignorar los directorios de Java y priorizar Kotlin, resolviendo así los errores de compilación cruzada |
| **4. Procesamiento de Datos en Tiempo Real (Background vs. UI)** | • **Latencia de la IA:** La comunicación con la API de TutelIQ depende de la conexión a internet. Gestionar tiempos de espera (timeouts) y asegurar que el dispositivo del menor no se ralentizara mientras se analizaba un mensaje en segundo plano fue un reto de optimización<br>• **Actualización del Dashboard:** Lograr que el "Puntaje de Seguridad" en el teléfono del tutor se actualizara instantáneamente cuando el servicio de monitoreo detectaba algo en el teléfono del hijo requirió una integración precisa entre Room, BroadcastReceivers y flujos de datos reactivos (Flows) |
| **5. Extracción Exhaustiva de Mensajes** | Las aplicaciones de mensajería modernas (especialmente WhatsApp) organizan las notificaciones de forma compleja:<br>• **Mensajes Agrupados:** Fue difícil extraer solo el último mensaje recibido sin capturar textos anteriores ya procesados<br>• **Compatibilidad:** Cada aplicación (Telegram, Instagram, Messenger) estructura sus "extras" de notificación de forma distinta, lo que obligó a desarrollar una lógica de extracción multiformato dentro del NotificationMonitorService |
| **6. Equilibrio Ético: Privacidad vs. Seguridad** | Técnicamente, fue un desafío programar un sistema que fuera capaz de "leer" todo para poder analizarlo, pero que al mismo tiempo fuera diseñado para "olvidar" o no reportar aquello que la IA clasificara como inofensivo, garantizando que el sistema no se convirtiera en una herramienta de espionaje invasivo |

---

## ¿Qué Mejoras Podrían Agregarse a la Aplicación?

Para potenciar el impacto y la eficacia de Minors Oculus, se podrían integrar las siguientes mejoras técnicas y funcionales en futuras versiones:

| **Mejora** | **Descripción** |
|------------|-----------------|
| **1. Análisis de Contenido Multimedia (IA Visual)** | Actualmente, la app se centra en el texto de las notificaciones. Una mejora crítica sería integrar Computer Vision para:<br>• **Detección de Imágenes Inapropiadas:** Analizar miniaturas de fotos o videos recibidos para detectar desnudez, violencia o armas<br>• **Detección de Deepfakes:** Herramientas para identificar si un video recibido por el menor ha sido manipulado con IA generativa, una amenaza creciente en el grooming moderno |
| **2. Gamificación y Educación para el Menor** | Transformar la app de una herramienta de "vigilancia" a una de "aprendizaje mutuo":<br>• **Modo Compañero:** Una interfaz para el menor donde reciba "Escudos de Seguridad" o recompensas al completar micro-lecciones sobre cómo navegar seguro<br>• **Cuestionarios de Riesgo:** Pruebas cortas que enseñen al niño a identificar cuándo una conversación se está volviendo sospechosa, fomentando el pensamiento crítico |
| **3. Geolocalización Inteligente (Geofencing)** | Añadir una capa de seguridad física vinculada a la digital:<br>• **Zonas Seguras:** Notificar al padre si el menor sale de un perímetro definido (casa, escuela)<br>• **SOS de Emergencia:** Un botón de pánico en el dispositivo del hijo que envíe la ubicación en tiempo real y grabe 30 segundos de audio ambiente en caso de sentirse amenazado |
| **4. Vinculación Directa mediante APIs Oficiales** | Dado que el monitoreo actual depende de las notificaciones, una mejora sería la integración mediante SDKs oficiales (si las plataformas lo permiten) para:<br>• **Historial Retroactivo:** Analizar mensajes antiguos, no solo los que llegan como notificaciones nuevas<br>• **Recuperación de Mensajes Borrados:** Detectar si un agresor está obligando al menor a borrar evidencia de la conversación |
| **5. Gestión de Tiempo de Pantalla (Digital Wellbeing)** | Integrar controles de uso para un equilibrio saludable:<br>• **Bloqueo por Horarios:** Desactivar aplicaciones de entretenimiento o redes sociales durante horas de estudio o sueño, manteniendo activas solo las llamadas de emergencia<br>• **Límites por Categoría:** Establecer un máximo de tiempo diario para juegos o apps de redes sociales |
| **6. Reportes Exportables para Autoridades** | Facilitar la acción legal en casos críticos:<br>• **Generador de PDF Forense:** Una función que permita exportar el historial de una alerta roja con sellos de tiempo, remitente y análisis de la IA en un formato válido para presentar ante la Policía Cibernética o fiscalías especializadas |
| **7. Análisis de Sentimientos y Bienestar Emocional** | Evolucionar la detección de delitos hacia el cuidado de la salud mental:<br>• **Detección de Depresión o Ansiedad:** Utilizar la IA para identificar patrones lingüísticos que sugieran ideación suicida, autolesiones o trastornos alimenticios, permitiendo una intervención psicológica temprana |
| **8. Soporte Multidispositivo (IoT)** | Extender la protección más allá del smartphone:<br>• **Consolas de Videojuegos:** Monitorear chats de voz y texto en plataformas como Roblox, Discord o Fortnite, que son vectores comunes de captación de menores<br>• **Smartwatches:** Recibir alertas simplificadas directamente en el reloj del tutor |

---

## Referencias y Citas

Para el desarrollo del proyecto Minors Oculus, las fuentes de información se dividen en documentación técnica oficial para la arquitectura de software y marcos normativos/técnicos sobre ciberseguridad infantil.

### Documentación Técnica y Herramientas de Desarrollo

| **Fuente** | **Referencia** |
|------------|----------------|
| Android Developers | Android Developers. (2024). *Documentación oficial de Android: Guía del desarrollador*. Google. https://developer.android.com/docs |
| Firebase | Firebase. (2024). *Documentación de Firebase: Servicios de autenticación y bases de datos en tiempo real*. Google. https://firebase.google.com/docs |
| Material Design | Google. (2024). *Material Design 3: Guide to adaptable interfaces*. https://m3.material.io/ |
| Kotlin | Kotlin Foundation. (2024). *Kotlin documentation: Coroutines and Flows*. https://kotlinlang.org/docs/home.html |
| Retrofit | Square, Inc. (2024). *Retrofit: A type-safe HTTP client for Android and Java*. https://square.github.io/retrofit/ |

### Inteligencia Artificial y Ciberseguridad Infantil

| **Fuente** | **Referencia** |
|------------|----------------|
| TutelIQ | TutelIQ. (2024). *Manual de referencia de la API TutelIQ: Detección heurística de ciberdelitos contra menores*. https://api.tuteliq.com/docs |
| UNICEF | UNICEF. (2021). *Manual de protección de la infancia en línea: Guía para entornos digitales seguros*. Fondo de las Naciones Unidas para la Infancia. https://www.unicef.org/es/proteccion-infantil-linea |
| IWF | Internet Watch Foundation (IWF). (2023). *Terminología y clasificación de MASNNA (Material de Abuso Sexual de Niños, Niñas y Adolescentes)*. https://www.iwf.org.uk/ |
| Interpol | Interpol. (2023). *Estrategias globales contra el grooming y la explotación sexual infantil en línea*. https://www.interpol.int/es/Delitos/Delitos-contra-menores/Explotacion-sexual-de-menores |

### Marcos Legales y Glosario de Términos

| **Fuente** | **Referencia** |
|------------|----------------|
| Convención sobre los Derechos del Niño | Convención sobre los Derechos del Niño. (1989). *Protocolo facultativo relativo a la venta de niños, la prostitución infantil y la utilización de niños en la pornografía infantil*. Naciones Unidas |
| INHOPE | INHOPE. (2024). *Best practices for online reporting of child sexual abuse material*. International Association of Internet Hotlines. https://www.inhope.org |

---

## Modelo de IA

El modelo de Inteligencia Artificial utilizado en la aplicación es **TutelIQ AI**, integrado a través de su API oficial.

### 1. Modelo de IA Utilizado: TutelIQ AI

La aplicación utiliza el motor de Inteligencia Artificial de TutelIQ, un modelo especializado en procesamiento de lenguaje natural (NLP) con un enfoque determinista y heurístico diseñado específicamente para la detección de riesgos en comunicaciones digitales infantiles.

### 2. Justificación de su Elección

| **Justificación** | **Descripción** |
|-------------------|-----------------|
| **Especialización en Ciberdelincuencia** | El modelo ha sido entrenado específicamente para identificar patrones de Grooming, Sextorsión, ESCNNA y Ciberbullying, reconociendo el lenguaje manipulativo que suele evadir los filtros tradicionales |
| **Eficiencia en Dispositivos Móviles** | Al ser una IA basada en la nube (vía API), permite que la aplicación sea ligera y no consuma los recursos de procesamiento (CPU/RAM) del dispositivo del menor, lo cual es crítico para no afectar el rendimiento del teléfono |
| **Contextualización de Riesgo** | A diferencia de una búsqueda por "palabras prohibidas", TutelIQ analiza la intención. Puede distinguir entre una conversación normal y un intento de captación, reduciendo drásticamente los falsos positivos |

### 3. Forma de Integración

| **Componente** | **Descripción** |
|----------------|-----------------|
| **Capa de Red (Retrofit & OkHttp)** | Se implementó una interfaz de servicio (TutelIQApi.kt) que define los endpoints de la API. Se configuró OkHttp con protocolos de seguridad (Bearer Tokens) y tiempos de respuesta controlados |
| **Motor de Riesgo (RiskEngine.kt)** | Se desarrolló un objeto Singleton que actúa como puente. Este recibe el texto capturado por el servicio de notificaciones, lo empaqueta y realiza la petición a la API de TutelIQ |
| **Procesamiento Asíncrono (Coroutines)** | El envío y la recepción de datos de la IA se gestionan mediante Kotlin Coroutines, asegurando que el análisis ocurra en segundo plano sin congelar la interfaz de usuario |
| **Mapeo de Resultados** | La respuesta JSON de la IA se convierte automáticamente en objetos de Kotlin (Gson) para ser procesados por la lógica de la app |

### 4. Función dentro de la Aplicación

La IA de TutelIQ cumple tres funciones vitales en Minors Oculus:

| **Función** | **Descripción** |
|-------------|-----------------|
| **1. Clasificación en Tiempo Real** | Analiza cada notificación entrante (WhatsApp, Messenger, etc.) y le asigna un Nivel de Riesgo (Verde: Inofensivo, Amarillo: Sospechoso, Rojo: Peligroso) |
| **2. Categorización de Amenazas** | Identifica la naturaleza específica del peligro entre 15 dimensiones de análisis (ej. detectar si un mensaje es específicamente un intento de Ingeniería Social o Radicalización) |
| **3. Análisis Experto Manual** | En la pantalla "TutelIQ AI Expert", permite al tutor realizar consultas profundas sobre textos específicos, proporcionando un veredicto detallado basado en su amplia base de conocimientos sobre ciberdelitos |

> **En conclusión:** TutelIQ AI actúa como el "cerebro analítico" que transforma una simple lectura de mensajes en un sistema de defensa inteligente y proactivo.