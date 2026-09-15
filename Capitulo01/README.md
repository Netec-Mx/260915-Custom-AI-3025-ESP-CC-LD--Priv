# Demo: Uso de Microsoft 365 Copilot Chat — generación y mejora de prompts para preparar una reunión con un prospecto ficticio de CIBEST CAPITAL

## Metadatos

| Campo | Detalle |
|---|---|
| **Duración** | 45 minutos |
| **Complejidad** | Fácil |
| **Nivel de Bloom** | Aplicar |
| **Tipo de actividad** | Demostración del instructor |

---

## Descripción General

> ℹ️ **Nota:** Esta práctica es una **Demostración realizada por el instructor**. El instructor ejecutará los pasos y comandos mientras los alumnos observan, toman notas y analizan el procedimiento, en lugar de realizarla individualmente.

En esta demostración, el instructor presenta el escenario completo de trabajo de **CIBEST CAPITAL** y ejecuta en vivo el flujo integral de preparación de una reunión comercial con el prospecto ficticio **Carlos Mendoza**, utilizando Microsoft 365 Copilot a través de múltiples aplicaciones. La demostración cubre desde la generación de un prompt básico sin contexto hasta la construcción de prompts enriquecidos con información específica del prospecto, pasando por la creación de artefactos en Word, PowerPoint, Excel, Outlook y Teams. Los estudiantes observarán cómo cada herramienta se conecta dentro de un flujo de trabajo cohesivo y tomarán nota de los prompts y artefactos que replicarán en los labs prácticos subsiguientes (01-08-02 al 01-08-05).

---

## Objetivos de Aprendizaje

Al finalizar esta demostración, los estudiantes serán capaces de:

- [ ] **Describir** el escenario ficticio de CIBEST CAPITAL y el perfil completo del prospecto Carlos Mendoza, incluyendo su sector, ingresos, intereses de inversión y nivel de experiencia.
- [ ] **Identificar** las diferencias entre un prompt general sin contexto y un prompt mejorado con contexto específico de negocio, perfil del prospecto y resultado esperado.
- [ ] **Reconocer** el flujo completo de preparación de reunión con Copilot a través de seis aplicaciones de Microsoft 365 (Chat, Word, PowerPoint, Excel, Outlook y Teams) y la continuidad entre ellas.
- [ ] **Relacionar** cada artefacto generado durante la demostración con el lab práctico correspondiente donde lo replicarán y expandirán.
- [ ] **Evaluar** críticamente las respuestas de Copilot, identificando cuándo la información requiere verificación adicional o ajuste manual.

---

## Prerrequisitos

### Conocimientos previos (estudiantes)

- Familiaridad básica con las aplicaciones de productividad de Microsoft 365 (Word, Excel, Outlook, PowerPoint, Teams).
- Comprensión conceptual de qué es Microsoft Copilot y sus capacidades generales (cubierto en las lecciones 1.1 a 1.7 del curso).
- No se requiere experiencia previa en servicios financieros ni en asesoría de inversiones.

### Acceso y licencias (instructor)

| Requisito | Detalle |
|---|---|
| Cuenta Microsoft 365 | Cuenta organizacional con licencia **Microsoft 365 Copilot Premium** activa |
| Microsoft 365 Apps | Versión 2405 (Build 17628.20164) o superior — Canal Actual |
| Microsoft Teams | New Teams versión 24046.2715.2866.8691 o superior |
| Copilot Chat | Acceso verificado en [copilot.microsoft.com](https://copilot.microsoft.com) — modo **Trabajo** |
| Navegador | Microsoft Edge 124.0.2478.97 o superior |
| Proyector / pantalla compartida | Para que los estudiantes visualicen la demostración en tiempo real |
| Webcam y micrófono | Funcionales (requeridos para la sección de Teams) |

### Acceso y licencias (estudiantes)

- **No requieren acceso a sus equipos durante esta demostración.** Solo necesitan material para tomar notas (cuaderno o documento digital).
- Las licencias de Copilot de los estudiantes serán necesarias a partir del lab 01-08-02.

---

## Entorno del Laboratorio

### Configuración del equipo del instructor

#### Hardware recomendado

| Componente | Mínimo | Recomendado |
|---|---|---|
| Procesador | Intel Core i5 / AMD Ryzen 5 (64 bits) | Intel Core i7 / AMD Ryzen 7 |
| RAM | 8 GB | 16 GB |
| Espacio en disco | 10 GB libres | 20 GB libres |
| Resolución de pantalla | 1366×768 | 1920×1080 |
| Conexión a internet | 10 Mbps de bajada | 25 Mbps o superior |
| Periféricos | Teclado, ratón, webcam, micrófono | Segundo monitor para gestión de notas |

#### Software requerido

| Aplicación | Versión mínima |
|---|---|
| Windows 10/11 | Windows 10 22H2 (Build 19045) o Windows 11 23H2 (Build 22631) |
| Microsoft 365 Apps for Enterprise | Versión 2405 (Build 17628.20164) |
| Microsoft Edge | 124.0.2478.97 |
| Microsoft Teams (New Teams) | 24046.2715.2866.8691 |

### Preparación previa a la demostración

Antes de iniciar la sesión, el instructor debe completar las siguientes tareas:

1. **Verificar la versión de Microsoft 365 Apps:**
   - Abrir cualquier aplicación de Office (por ejemplo, Word).
   - Navegar a **Archivo > Cuenta > Información del producto**.
   - Confirmar que la versión sea **2405 (Build 17628.20164)** o superior.

2. **Crear la estructura de carpetas en OneDrive:**
   - Abrir el Explorador de archivos o OneDrive en el navegador.
   - Navegar a **Documentos**.
   - Crear la carpeta `CIBEST_CAPITAL` si no existe.
   - Dentro de ella, crear la subcarpeta `Prospectos`.
   - Ruta completa: `Documentos > CIBEST_CAPITAL > Prospectos`.

3. **Verificar acceso a Copilot Chat:**
   - Abrir Microsoft Edge y navegar a [copilot.microsoft.com](https://copilot.microsoft.com).
   - Confirmar que el modo **Trabajo** esté disponible (selector visible en la interfaz).
   - Realizar una consulta de prueba para verificar conectividad.

4. **Abrir todas las aplicaciones necesarias:**
   - Microsoft Word, PowerPoint, Excel, Outlook y Teams.
   - Verificar que el ícono de Copilot esté visible en la barra de herramientas de cada aplicación.

5. **Configurar la pantalla para proyección:**
   - Ajustar el zoom del navegador y las aplicaciones al **125–150%** para visibilidad del aula.
   - Cerrar aplicaciones innecesarias para evitar distracciones y notificaciones.

---

## Pasos de la Demostración

### Paso 1: Presentación del escenario y perfil del prospecto

**Objetivo:** Establecer el contexto de negocio de CIBEST CAPITAL y el perfil detallado del prospecto Carlos Mendoza para que los estudiantes comprendan el marco de trabajo de toda la serie de labs.

**Instrucciones para el instructor:**

1. Proyecte una diapositiva o escriba en pizarra los datos clave del escenario. Presente verbalmente lo siguiente:

   > **Escenario:** Somos analistas o ejecutivos de cuentas en **CIBEST CAPITAL**, una firma de asesoría de inversiones. Hemos recibido una referencia de un nuevo prospecto y debemos preparar una reunión inicial de descubrimiento.

2. Presente el perfil del prospecto con los siguientes datos:

   | Dato | Detalle |
   |---|---|
   | **Nombre** | Carlos Mendoza |
   | **Rol** | Propietario de empresa |
   | **Sector** | Logística |
   | **País** | México |
   | **Ingresos anuales de la empresa** | Aproximadamente USD 5 millones |
   | **Interés de inversión** | Diversificar patrimonio personal invirtiendo en activos en Estados Unidos |
   | **Experiencia en inversiones internacionales** | Limitada |

3. Explique a los estudiantes que este perfil se mantendrá **constante** en todos los labs del batch, y que todos los artefactos se guardarán en la ruta `Documentos > CIBEST_CAPITAL > Prospectos`.

4. Presente el mapa de los 10 artefactos que se generarán durante la demostración y su relación con los labs prácticos:

   | # | Artefacto | Aplicación | Lab práctico relacionado |
   |---|---|---|---|
   | 1 | Prompt general (sin contexto) | Copilot Chat | 01-08-02 |
   | 2 | Prompt mejorado (con contexto) | Copilot Chat | 01-08-02 |
   | 3 | Preguntas de descubrimiento | Copilot Chat | 01-08-02 |
   | 4 | Investigación del sector logístico | Copilot Chat (web) | 01-08-02 |
   | 5 | Ficha de preparación | Word | 01-08-03 |
   | 6 | Presentación introductoria | PowerPoint | 01-08-04 |
   | 7 | Matriz de necesidades | Excel | 01-08-05 |
   | 8 | Correo de bienvenida | Outlook | 01-08-03 |
   | 9 | Correo de seguimiento | Outlook | 01-08-03 |
   | 10 | Agenda de reunión interna | Teams | 01-08-03 |

**Resultado esperado:** Los estudiantes comprenden el escenario completo, el perfil del prospecto y la hoja de ruta de artefactos que se generarán.

**Verificación:** Pregunte a los estudiantes: *"¿Cuáles son las tres características principales del perfil de Carlos Mendoza que debemos considerar al preparar la reunión?"* Respuesta esperada: sector logístico en México, interés en diversificar patrimonio en EE.UU., experiencia limitada en inversiones internacionales.

---

### Paso 2: Generación de un prompt general en Copilot Chat (sin contexto)

**Objetivo:** Demostrar las limitaciones de un prompt genérico sin contexto específico de negocio y establecer una línea base para la comparación posterior.

**Instrucciones para el instructor:**

1. Abra Microsoft Edge y navegue a [copilot.microsoft.com](https://copilot.microsoft.com).

2. Verifique que el selector esté en modo **Trabajo** (no en modo Web).

3. Escriba el siguiente prompt **genérico** en el campo de chat:

   ```
   Ayúdame a preparar una reunión con un cliente potencial.
   ```

4. Presione **Enter** y espere la respuesta de Copilot.

5. Lea la respuesta en voz alta y señale las siguientes limitaciones ante los estudiantes:
   - La respuesta es **genérica** y aplicable a cualquier industria.
   - No menciona servicios financieros, inversiones ni el perfil específico del prospecto.
   - Las recomendaciones son superficiales y carecen de profundidad estratégica.
   - No hay personalización de tono, formato ni estructura para el contexto de asesoría de inversiones.

6. Comente a los estudiantes:

   > *"Observen que Copilot nos dio una respuesta útil pero muy general. Es como pedirle a un asistente que nos ayude sin decirle quiénes somos, a quién vamos a ver ni qué queremos lograr. Ahora vamos a mejorar esto significativamente."*

**Resultado esperado:** Copilot genera una lista genérica de consejos para preparar una reunión (investigar al cliente, preparar agenda, definir objetivos, etc.) sin ninguna especificidad sobre CIBEST CAPITAL ni Carlos Mendoza.

**Verificación:** Los estudiantes deben poder identificar al menos 3 elementos que faltan en la respuesta genérica (nombre del prospecto, sector específico, tipo de servicio ofrecido, contexto geográfico, nivel de experiencia del prospecto).

---

### Paso 3: Construcción de un prompt mejorado con contexto específico

**Objetivo:** Demostrar cómo la incorporación de contexto específico (rol, empresa, perfil del prospecto, objetivo y formato esperado) transforma radicalmente la calidad de la respuesta de Copilot.

**Instrucciones para el instructor:**

1. En la misma ventana de Copilot Chat (o inicie una nueva conversación para claridad), escriba el siguiente prompt mejorado:

   ```
   Soy un ejecutivo de cuentas en CIBEST CAPITAL, una firma de asesoría de inversiones. 
   Estoy preparando una reunión inicial de descubrimiento con un nuevo prospecto llamado 
   Carlos Mendoza. Carlos es propietario de una empresa de logística en México con ingresos 
   anuales aproximados de USD 5 millones. Está interesado en diversificar su patrimonio 
   personal invirtiendo en activos en Estados Unidos, pero tiene experiencia limitada en 
   inversiones internacionales.

   Necesito que me ayudes a preparar un plan estructurado para esta primera reunión. 
   El plan debe incluir:
   1. Objetivos específicos de la reunión inicial
   2. Temas clave a cubrir durante la conversación
   3. Puntos de conexión personal que pueda usar para generar confianza
   4. Posibles preocupaciones o objeciones que Carlos podría tener
   5. Próximos pasos sugeridos después de la reunión

   Usa un tono profesional pero accesible, considerando que Carlos no está familiarizado 
   con terminología financiera compleja.
   ```

2. Presione **Enter** y espere la respuesta.

3. Lea la respuesta en voz alta y destaque las **diferencias clave** respecto al prompt genérico:
   - La respuesta menciona específicamente a Carlos Mendoza y su contexto.
   - Incluye consideraciones sobre el sector logístico mexicano.
   - Adapta el lenguaje para un prospecto con experiencia limitada.
   - Proporciona estructura accionable y específica.

4. Señale los **cinco componentes** del prompt mejorado que marcaron la diferencia:

   | Componente | Ejemplo en el prompt |
   |---|---|
   | **Rol** | "Soy un ejecutivo de cuentas en CIBEST CAPITAL" |
   | **Contexto** | Perfil completo de Carlos Mendoza |
   | **Tarea específica** | "Preparar un plan estructurado para esta primera reunión" |
   | **Formato deseado** | Lista numerada con 5 secciones específicas |
   | **Restricciones/Tono** | "Tono profesional pero accesible, sin terminología compleja" |

**Resultado esperado:** Copilot genera un plan de reunión detallado y personalizado que incluye los cinco elementos solicitados, con referencias específicas al perfil de Carlos Mendoza, el sector logístico y la inversión en activos estadounidenses.

**Verificación:** Compare lado a lado (si tiene dos ventanas) o secuencialmente las dos respuestas. Pregunte a los estudiantes: *"¿Qué componente del prompt mejorado creen que tuvo mayor impacto en la calidad de la respuesta?"* Facilite una breve discusión de 1-2 minutos.

---

### Paso 4: Solicitud de preguntas de descubrimiento estructuradas por categorías

**Objetivo:** Mostrar cómo usar Copilot para generar preguntas de descubrimiento organizadas temáticamente, útiles para la reunión inicial con el prospecto.

**Instrucciones para el instructor:**

1. En la misma conversación de Copilot Chat, escriba el siguiente prompt:

   ```
   Ahora necesito una lista de preguntas de descubrimiento para hacerle a Carlos Mendoza 
   durante la reunión inicial. Organiza las preguntas en las siguientes categorías:

   1. Situación financiera actual y patrimonio
   2. Objetivos de inversión y horizonte temporal
   3. Tolerancia al riesgo y experiencia previa
   4. Conocimiento sobre el mercado estadounidense
   5. Expectativas sobre la relación con CIBEST CAPITAL
   6. Situación fiscal y regulatoria (México-EE.UU.)

   Incluye 3-4 preguntas por categoría. Las preguntas deben ser abiertas, en un tono 
   respetuoso y no invasivo, adecuadas para una primera conversación donde se busca 
   generar confianza.
   ```

2. Presione **Enter** y espere la respuesta.

3. Revise la respuesta en voz alta, destacando:
   - La organización por categorías facilita la navegación durante la reunión.
   - Las preguntas abiertas invitan a Carlos a compartir información sin sentirse interrogado.
   - Algunas preguntas pueden necesitar ajuste manual (señale cuáles y por qué).

4. Comente sobre la **evaluación crítica** de la respuesta:

   > *"Noten que Copilot generó preguntas sobre situación fiscal México-EE.UU. Esto es un área sensible donde debemos verificar que las preguntas sean apropiadas para un asesor de inversiones y no para un contador fiscal. Siempre debemos revisar críticamente lo que Copilot genera."*

**Resultado esperado:** Una lista de 18-24 preguntas organizadas en 6 categorías, con tono conversacional y profesional, adaptadas al perfil de Carlos Mendoza.

**Verificación:** Pida a los estudiantes que identifiquen al menos una pregunta que considerarían inapropiada o que reformularían para la primera reunión. Esto refuerza el pensamiento crítico sobre las respuestas de IA.

---

### Paso 5: Investigación del sector logístico con búsqueda web de Copilot

**Objetivo:** Demostrar el uso de la búsqueda web integrada en Copilot Chat para investigar el sector del prospecto, y modelar la evaluación crítica de fuentes.

**Instrucciones para el instructor:**

1. Cambie el selector de Copilot Chat al modo **Web** (si es necesario para activar la búsqueda web) o permanezca en modo **Trabajo** si la búsqueda web está habilitada en ese modo.

2. Escriba el siguiente prompt:

   ```
   Necesito investigar el sector logístico en América Latina, con enfoque en México, 
   para prepararme para mi reunión con Carlos Mendoza. Busca información actualizada sobre:

   1. Tamaño del mercado logístico en México y tendencias de crecimiento recientes
   2. Principales desafíos que enfrentan las empresas de logística medianas en México 
      (con ingresos entre USD 3-10 millones)
   3. Oportunidades de expansión o diversificación para propietarios de empresas logísticas 
      mexicanas
   4. Impacto del nearshoring en el sector logístico mexicano
   5. Regulaciones relevantes para empresarios mexicanos que desean invertir en EE.UU.

   Incluye las fuentes de cada dato para que pueda verificarlas.
   ```

3. Presione **Enter** y espere la respuesta.

4. Cuando Copilot presente los resultados con fuentes, demuestre la **evaluación crítica**:
   - Haga clic en al menos 2 de las fuentes citadas para verificar que existen y son relevantes.
   - Comente sobre la **confiabilidad** de cada tipo de fuente (medio de comunicación vs. reporte de consultoría vs. fuente gubernamental).
   - Señale si algún dato parece desactualizado o si las fuentes no son verificables.

5. Destaque ante los estudiantes:

   > *"La búsqueda web de Copilot es un punto de partida excelente, pero NO reemplaza la investigación profesional. Siempre debemos verificar las fuentes, contrastar con datos de fuentes primarias y tener cuidado con información que pueda estar desactualizada. Noten que Copilot nos indica las fuentes — esto es una ventaja que debemos aprovechar."*

**Resultado esperado:** Copilot genera un resumen del sector logístico latinoamericano/mexicano con datos sobre tamaño de mercado, tendencias, desafíos y oportunidades, incluyendo referencias a fuentes web.

**Verificación:** Al menos 2 de las fuentes citadas deben ser verificables al hacer clic en los enlaces. Si alguna fuente no funciona, use ese momento como ejemplo didáctico de por qué la verificación es esencial.

---

### Paso 6: Creación de ficha de preparación en Microsoft Word

**Objetivo:** Demostrar cómo usar Copilot en Word para crear una ficha de preparación de reunión que consolide la información del prospecto, el contexto del sector y las preguntas pendientes.

**Instrucciones para el instructor:**

1. Abra **Microsoft Word** y cree un nuevo documento en blanco.

2. Guarde inmediatamente el documento con el nombre exacto:
   - **Nombre:** `Ficha_Preparacion_CarlosMendoza_CIBEST.docx`
   - **Ubicación:** `Documentos > CIBEST_CAPITAL > Prospectos`

3. Active Copilot en Word haciendo clic en el ícono de **Copilot** en la barra de herramientas (o use el atajo presionando el ícono de Copilot en el área de redacción).

4. En el panel de Copilot o en el campo de borrador, escriba el siguiente prompt:

   ```
   Crea una ficha de preparación para una reunión comercial inicial con el siguiente formato 
   y contenido:

   TÍTULO: Ficha de Preparación — Reunión Inicial con Carlos Mendoza
   FIRMA: CIBEST CAPITAL
   FECHA: [Fecha actual]

   SECCIONES:

   1. DATOS DEL PROSPECTO
   - Nombre: Carlos Mendoza
   - Empresa: Empresa de logística (México)
   - Ingresos anuales estimados: USD 5 millones
   - Interés principal: Diversificar patrimonio invirtiendo en activos en EE.UU.
   - Experiencia en inversiones internacionales: Limitada

   2. CONTEXTO DEL SECTOR
   - Resumen del sector logístico mexicano (3-4 puntos clave)
   - Impacto del nearshoring como oportunidad
   - Desafíos comunes para empresas medianas del sector

   3. INFORMACIÓN CONOCIDA
   - Lo que sabemos sobre Carlos y su situación (basado en el perfil)

   4. INFORMACIÓN PENDIENTE DE CONFIRMAR
   - Lista de datos que necesitamos obtener durante la reunión

   5. OBJETIVOS DE LA REUNIÓN
   - 3-4 objetivos específicos para este primer encuentro

   6. PREGUNTAS CLAVE
   - 8-10 preguntas prioritarias organizadas por tema

   7. POSIBLES OBJECIONES Y RESPUESTAS
   - 3-4 objeciones anticipadas con respuestas sugeridas

   8. PRÓXIMOS PASOS
   - Acciones a tomar después de la reunión

   Usa formato profesional con encabezados claros, viñetas y tablas donde sea apropiado. 
   El tono debe ser interno (documento de trabajo para el equipo de CIBEST CAPITAL, 
   no para el cliente).
   ```

5. Presione **Enter** o haga clic en **Generar** y espere que Copilot cree el borrador.

6. Revise el documento generado en voz alta, señalando:
   - Las secciones que Copilot completó correctamente.
   - Las áreas donde sería necesario agregar o modificar información manualmente.
   - La diferencia entre información factual (datos del prospecto) e información inferida por Copilot (contexto del sector).

7. Haga clic en **Conservar** (Keep) para aceptar el borrador.

8. Guarde el documento con **Ctrl + S**.

**Resultado esperado:** Un documento Word con las 8 secciones solicitadas, formateado profesionalmente con encabezados, viñetas y tablas, conteniendo información específica sobre Carlos Mendoza y el contexto del sector logístico.

**Verificación:** El documento debe estar guardado como `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` en `Documentos > CIBEST_CAPITAL > Prospectos`. Confirme el nombre y la ubicación ante los estudiantes, enfatizando que este archivo será referenciado en labs posteriores.

---

### Paso 7: Creación de presentación introductoria en PowerPoint

**Objetivo:** Demostrar cómo usar Copilot en PowerPoint para crear una presentación adaptada a una audiencia con experiencia limitada en inversiones, usando lenguaje accesible y eliminando tecnicismos.

**Instrucciones para el instructor:**

1. Abra **Microsoft PowerPoint** y cree una nueva presentación en blanco.

2. Haga clic en el ícono de **Copilot** en la barra de herramientas de PowerPoint.

3. En el panel de Copilot, escriba el siguiente prompt:

   ```
   Crea una presentación de 8-10 diapositivas para una reunión introductoria entre 
   CIBEST CAPITAL y un prospecto llamado Carlos Mendoza, propietario de una empresa de 
   logística en México.

   La presentación debe:
   - Presentar a CIBEST CAPITAL como firma de asesoría de inversiones
   - Explicar de forma simple qué significa diversificar patrimonio invirtiendo en EE.UU.
   - Mostrar los tipos de activos disponibles en EE.UU. (bienes raíces, fondos, acciones) 
     usando analogías simples
   - Incluir una diapositiva sobre por qué empresarios mexicanos están mirando hacia EE.UU.
   - Explicar el proceso de trabajo paso a paso con CIBEST CAPITAL
   - Cerrar con próximos pasos claros

   IMPORTANTE: Carlos tiene experiencia limitada en inversiones internacionales. 
   Usa lenguaje sencillo, evita jerga financiera, y cuando uses un término técnico, 
   incluye una explicación breve entre paréntesis. Usa analogías del mundo empresarial 
   y logístico cuando sea posible.
   ```

4. Presione **Enter** y espere que Copilot genere la presentación.

5. Navegue por las diapositivas generadas y comente:
   - Si Copilot logró eliminar tecnicismos o si algunos persisten.
   - La efectividad de las analogías utilizadas (si las incluyó).
   - Diapositivas que necesitarían ajuste visual o de contenido.

6. Guarde la presentación como `Presentacion_Introductoria_CarlosMendoza_CIBEST.pptx` en `Documentos > CIBEST_CAPITAL > Prospectos`.

**Resultado esperado:** Una presentación de 8-10 diapositivas con diseño profesional, contenido adaptado a una audiencia no financiera, y estructura lógica que guía al prospecto desde la presentación de la firma hasta los próximos pasos.

**Verificación:** Revise al menos 2 diapositivas y verifique que el lenguaje sea accesible. Si encuentra tecnicismos no explicados, demuestre cómo pedir a Copilot que los simplifique con un prompt de seguimiento como:

```
Simplifica el lenguaje de la diapositiva 4. Reemplaza cualquier término financiero 
técnico con una explicación en lenguaje cotidiano.
```

---

### Paso 8: Construcción de matriz de necesidades en Excel

**Objetivo:** Demostrar cómo usar Copilot en Excel para construir una matriz estructurada que clasifique la información conocida y pendiente del prospecto por categorías clave.

**Instrucciones para el instructor:**

1. Abra **Microsoft Excel** y cree un nuevo libro en blanco.

2. En la celda **A1**, escriba el título: `Matriz de Necesidades — Carlos Mendoza — CIBEST CAPITAL`.

3. Active Copilot en Excel (ícono en la barra de herramientas).

4. En el panel de Copilot, escriba el siguiente prompt:

   ```
   Crea una tabla estructurada que sirva como matriz de necesidades para el prospecto 
   Carlos Mendoza de CIBEST CAPITAL. La tabla debe tener las siguientes columnas:

   A: Categoría (Situación Financiera, Objetivos de Inversión, Tolerancia al Riesgo, 
      Conocimiento del Mercado EE.UU., Situación Fiscal, Expectativas de Servicio)
   B: Información Conocida (lo que ya sabemos del perfil)
   C: Información Pendiente (lo que debemos confirmar en la reunión)
   D: Fuente de Verificación (cómo confirmaremos cada dato)
   E: Prioridad (Alta, Media, Baja)
   F: Estado (Pendiente, En Proceso, Confirmado)

   Llena la tabla con al menos 3 filas por categoría, basándote en el perfil conocido:
   - Propietario de empresa de logística en México
   - Ingresos anuales ~USD 5 millones
   - Interés en diversificar patrimonio en activos en EE.UU.
   - Experiencia limitada en inversiones internacionales

   Marca como "Conocida" la información del perfil y como "Pendiente" todo lo que 
   debemos descubrir.
   ```

5. Si Copilot genera la tabla directamente en las celdas, revise el resultado. Si Copilot ofrece la tabla como texto, copie y pegue en las celdas correspondientes.

   > **Nota para el instructor:** Dependiendo de la versión y el estado de Copilot en Excel, la funcionalidad puede variar. Si Copilot en Excel no genera la tabla directamente, una alternativa es: (a) generar la tabla en Copilot Chat, (b) copiar el resultado, y (c) pegarlo en Excel. Demuestre ambos caminos si es necesario.

6. Una vez que la tabla esté en Excel:
   - Aplique formato de tabla (`Ctrl + T`) para mejorar la visualización.
   - Agregue filtros a las columnas de **Prioridad** y **Estado**.
   - Demuestre cómo filtrar por "Prioridad: Alta" para ver los elementos más críticos.

7. Guarde el archivo como `Matriz_Necesidades_CarlosMendoza_CIBEST.xlsx` en `Documentos > CIBEST_CAPITAL > Prospectos`.

**Resultado esperado:** Una tabla de Excel con 18+ filas organizadas en 6 categorías, con columnas de información conocida, pendiente, fuente de verificación, prioridad y estado, formateada como tabla con filtros activos.

**Verificación:** Filtre la columna **Estado** por "Pendiente" y muestre que la mayoría de los campos están pendientes — esto refuerza el propósito de la reunión de descubrimiento.

---

### Paso 9: Redacción de correos en Outlook (bienvenida y seguimiento)

**Objetivo:** Demostrar cómo usar Copilot en Outlook para redactar un correo de bienvenida previo a la reunión y un correo de seguimiento posterior, ambos adaptados al perfil del prospecto.

**Instrucciones para el instructor:**

#### 9A: Correo de bienvenida

1. Abra **Microsoft Outlook** y haga clic en **Nuevo correo**.

2. En el campo **Para**, escriba una dirección ficticia: `carlos.mendoza@ejemplo.com`.

3. Haga clic en el ícono de **Copilot** en la ventana de redacción del correo (o seleccione **Borrador con Copilot**).

4. Escriba el siguiente prompt:

   ```
   Redacta un correo de bienvenida de parte de CIBEST CAPITAL para Carlos Mendoza, 
   propietario de una empresa de logística en México, previo a nuestra primera reunión.

   El correo debe:
   - Agradecer su interés en explorar opciones de inversión en EE.UU.
   - Presentar brevemente a CIBEST CAPITAL y nuestra experiencia con empresarios 
     latinoamericanos
   - Confirmar la fecha y hora de la reunión (dejar como placeholder [FECHA] y [HORA])
   - Mencionar brevemente los temas que cubriremos
   - Transmitir un tono cálido, profesional y accesible
   - Ser conciso (máximo 200 palabras)
   
   No usar jerga financiera compleja. El prospecto tiene experiencia limitada en 
   inversiones internacionales.
   ```

5. Revise el borrador generado. Señale los elementos positivos y los que ajustaría.

6. **No envíe el correo** (es una demostración con dirección ficticia). Descarte o guarde como borrador.

#### 9B: Correo de seguimiento

7. Cree un **nuevo correo** y active Copilot nuevamente.

8. Escriba el siguiente prompt:

   ```
   Redacta un correo de seguimiento de parte de CIBEST CAPITAL para Carlos Mendoza, 
   enviado al día siguiente de nuestra primera reunión.

   El correo debe:
   - Agradecer su tiempo y la conversación
   - Resumir los 3-4 puntos principales discutidos (usar placeholders genéricos)
   - Confirmar los próximos pasos acordados
   - Adjuntar como referencia la presentación introductoria (mencionar el archivo adjunto)
   - Ofrecer disponibilidad para resolver dudas adicionales
   - Mantener el tono cálido y profesional

   Máximo 250 palabras.
   ```

9. Revise el borrador y comente las diferencias de tono y contenido entre el correo de bienvenida y el de seguimiento.

**Resultado esperado:** Dos correos electrónicos profesionales, personalizados para Carlos Mendoza, con tono accesible y sin jerga financiera compleja. El correo de bienvenida es anticipatorio; el de seguimiento es retrospectivo y accionable.

**Verificación:** Ambos correos deben mencionar a Carlos Mendoza por nombre, hacer referencia a CIBEST CAPITAL, y mantener un tono consistente con el perfil de un prospecto con experiencia limitada en inversiones.

---

### Paso 10: Preparación de agenda de reunión interna en Teams

**Objetivo:** Demostrar cómo usar Copilot en Teams para preparar una agenda de reunión interna del equipo de CIBEST CAPITAL donde se discutirá la estrategia para el prospecto Carlos Mendoza.

**Instrucciones para el instructor:**

1. Abra **Microsoft Teams** (New Teams).

2. Navegue a **Calendario** y haga clic en **Nueva reunión**.

3. Complete los campos básicos:
   - **Título:** `Preparación interna — Estrategia prospecto Carlos Mendoza`
   - **Fecha/Hora:** Cualquier fecha futura como ejemplo.
   - **Asistentes:** Puede agregar su propia dirección o dejar en blanco para la demo.

4. En el campo de **Detalles** o en el cuerpo de la invitación, active Copilot (si está disponible) o use Copilot Chat en Teams.

5. Si usa Copilot Chat en Teams, escriba:

   ```
   Necesito una agenda estructurada para una reunión interna del equipo de CIBEST CAPITAL 
   donde discutiremos la estrategia para nuestro nuevo prospecto Carlos Mendoza.

   Contexto: Carlos es propietario de una empresa de logística en México (ingresos ~USD 5M), 
   interesado en diversificar patrimonio en activos en EE.UU., con experiencia limitada 
   en inversiones internacionales. Ya tenemos preparada una ficha de preparación, una 
   presentación introductoria y una matriz de necesidades.

   La agenda debe incluir:
   1. Revisión del perfil del prospecto (5 min)
   2. Análisis del sector logístico mexicano — oportunidades y riesgos (10 min)
   3. Revisión de la matriz de necesidades — información conocida vs. pendiente (10 min)
   4. Estrategia de comunicación para la reunión inicial (10 min)
   5. Revisión de la presentación introductoria (5 min)
   6. Asignación de roles y responsabilidades (5 min)
   7. Preguntas y cierre (5 min)

   Duración total: 50 minutos. Formato con tiempos, responsable sugerido y descripción 
   breve de cada punto.
   ```

6. Copie la agenda generada al campo de detalles de la reunión de Teams.

7. Muestre cómo la agenda conecta con todos los artefactos creados previamente (ficha en Word, presentación en PowerPoint, matriz en Excel).

8. **No envíe la invitación** si no es necesario. Puede cancelar o guardar como borrador.

**Resultado esperado:** Una agenda de reunión interna de 50 minutos con 7 puntos, tiempos asignados, y referencias a los artefactos creados durante la demostración.

**Verificación:** La agenda debe sumar 50 minutos en total y hacer referencia explícita a al menos 3 de los artefactos creados (ficha de preparación, presentación, matriz de necesidades).

---

## Validación y Pruebas

Al finalizar la demostración, el instructor debe verificar con los estudiantes los siguientes puntos:

| # | Criterio de validación | Método |
|---|---|---|
| 1 | Los estudiantes pueden describir las 5 componentes de un prompt efectivo (rol, contexto, tarea, formato, restricciones) | Pregunta abierta al grupo |
| 2 | Los estudiantes identifican la diferencia entre el prompt genérico y el mejorado | Solicitar que nombren al menos 3 diferencias |
| 3 | Los estudiantes reconocen los 6 artefactos creados y en qué aplicación se generaron | Ejercicio rápido de asociación verbal |
| 4 | Los estudiantes comprenden la ruta de almacenamiento de archivos | Preguntar la ruta completa: `Documentos > CIBEST_CAPITAL > Prospectos` |
| 5 | Los estudiantes pueden nombrar al menos 2 limitaciones de Copilot observadas durante la demo | Pregunta abierta al grupo |
| 6 | Los estudiantes saben qué lab práctico corresponde a cada artefacto | Referencia a la tabla del Paso 1 |

**Pregunta de cierre sugerida para el instructor:**

> *"Si tuvieran que preparar esta misma reunión sin Copilot, ¿cuánto tiempo estimarían que les tomaría? ¿Qué pasos serían los más lentos?"*

Esta pregunta ayuda a los estudiantes a valorar el impacto de la herramienta antes de usarla ellos mismos en los labs prácticos.

---

## Solución de Problemas

### Problema 1: Copilot no aparece en la barra de herramientas de las aplicaciones de Office

**Síntomas:** Al abrir Word, PowerPoint, Excel u Outlook, el ícono de Copilot no está visible en la barra de herramientas (ribbon). El panel de Copilot no se puede activar.

**Causa:** La licencia de Microsoft 365 Copilot Premium no está correctamente asignada a la cuenta del instructor, la versión de Office es anterior a la 2405, o las políticas del tenant organizacional tienen Copilot deshabilitado.

**Solución:**
1. Verifique la versión de Office: **Archivo > Cuenta > Información del producto**. Debe ser versión **2405 (Build 17628.20164)** o superior.
2. Si la versión es correcta, verifique la licencia:
   - Vaya a [portal.office.com](https://portal.office.com) > **Mi cuenta > Suscripciones**.
   - Confirme que **Microsoft 365 Copilot** aparece como licencia activa.
3. Si la licencia está asignada pero Copilot no aparece, cierre todas las aplicaciones de Office, cierre sesión y vuelva a iniciar sesión.
4. Ejecute una actualización forzada: en cualquier app de Office, vaya a **Archivo > Cuenta > Opciones de actualización > Actualizar ahora**.
5. Si el problema persiste, contacte al administrador del tenant para verificar que las políticas de Copilot no estén restringidas.

**Alternativa durante la demo:** Si Copilot no funciona en una aplicación específica, use **Copilot Chat** ([copilot.microsoft.com](https://copilot.microsoft.com)) para generar el contenido y luego copie/pegue en la aplicación destino. Explique a los estudiantes que este es un flujo de trabajo alternativo válido.

---

### Problema 2: Copilot Chat en modo Trabajo no genera resultados con búsqueda web o devuelve errores de conectividad

**Síntomas:** Al solicitar investigación sobre el sector logístico (Paso 5), Copilot Chat no incluye fuentes web en la respuesta, muestra un mensaje de error de conexión, o devuelve resultados muy limitados sin citas.

**Causa:** La búsqueda web puede estar deshabilitada en la configuración del tenant organizacional, la conexión a internet es inestable, o el modo seleccionado (Trabajo vs. Web) no tiene habilitada la funcionalidad de búsqueda web.

**Solución:**
1. Verifique la conexión a internet abriendo una página web externa en Microsoft Edge.
2. En Copilot Chat, cambie del modo **Trabajo** al modo **Web** usando el selector en la interfaz. El modo Web tiene la búsqueda web habilitada por defecto.
3. Si el modo Web tampoco funciona, verifique que el administrador del tenant no haya restringido el acceso a búsqueda web en Copilot. Esto se configura en el **Centro de administración de Microsoft 365 > Configuración > Copilot**.
4. Como alternativa inmediata, realice la búsqueda directamente en **Microsoft Edge** con Copilot en la barra lateral (ícono de Copilot en Edge) y luego copie los resultados relevantes al flujo de trabajo.
5. Si ninguna opción funciona, use datos preparados de antemano sobre el sector logístico mexicano como respaldo (el instructor debe tener estos datos listos como plan de contingencia).

---

## Limpieza

Dado que esta es una demostración del instructor y los archivos generados servirán como referencia para los labs prácticos posteriores, **no se deben eliminar los artefactos creados**.

### Archivos a conservar

| Archivo | Ubicación |
|---|---|
| `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` | `Documentos > CIBEST_CAPITAL > Prospectos` |
| `Presentacion_Introductoria_CarlosMendoza_CIBEST.pptx` | `Documentos > CIBEST_CAPITAL > Prospectos` |
| `Matriz_Necesidades_CarlosMendoza_CIBEST.xlsx` | `Documentos > CIBEST_CAPITAL > Prospectos` |

### Acciones de limpieza

1. **Correos en Outlook:** Descarte los borradores de correo de bienvenida y seguimiento (no se enviaron a direcciones reales). Alternativamente, guárdelos como borradores para referencia.
2. **Reunión en Teams:** Cancele o elimine la reunión de ejemplo si no desea que permanezca en el calendario.
3. **Historial de Copilot Chat:** El historial de conversaciones en Copilot Chat se conserva automáticamente. No es necesario eliminarlo; los estudiantes pueden beneficiarse de ver los prompts utilizados si el instructor comparte pantalla en sesiones futuras.
4. **Cierre de aplicaciones:** Cierre las aplicaciones que no se necesiten para la siguiente actividad del curso.

---

## Resumen

En esta demostración se cubrió el flujo completo de preparación de una reunión comercial con un prospecto ficticio utilizando Microsoft 365 Copilot a través de seis aplicaciones:

| Aplicación | Artefacto generado | Concepto clave demostrado |
|---|---|---|
| **Copilot Chat** | Prompt genérico vs. mejorado | Importancia del contexto en la ingeniería de prompts |
| **Copilot Chat** | Preguntas de descubrimiento | Estructuración por categorías |
| **Copilot Chat (Web)** | Investigación del sector logístico | Evaluación crítica de fuentes |
| **Word** | Ficha de preparación | Consolidación de información en documento de trabajo |
| **PowerPoint** | Presentación introductoria | Adaptación de lenguaje para audiencias no especializadas |
| **Excel** | Matriz de necesidades | Clasificación de información conocida vs. pendiente |
| **Outlook** | Correos de bienvenida y seguimiento | Comunicación profesional personalizada |
| **Teams** | Agenda de reunión interna | Coordinación de equipo y conexión de artefactos |

### Puntos clave para los estudiantes

1. **El contexto lo cambia todo:** Un prompt con rol, contexto, tarea, formato y restricciones produce resultados significativamente superiores a un prompt genérico.
2. **Copilot es un punto de partida, no un producto final:** Toda respuesta de Copilot debe ser revisada, verificada y ajustada por el profesional.
3. **Las fuentes web requieren verificación:** La búsqueda web de Copilot es útil pero no reemplaza la investigación profesional con fuentes primarias.
4. **El flujo entre aplicaciones es continuo:** Los artefactos generados en una aplicación alimentan el trabajo en las demás, creando un ecosistema de productividad integrado.
5. **La adaptación al perfil del prospecto es fundamental:** Lenguaje accesible, eliminación de tecnicismos y uso de analogías son esenciales cuando el prospecto tiene experiencia limitada.

### Próximos pasos

Los estudiantes aplicarán estos conceptos de forma práctica e individual en los siguientes labs:

| Lab | Enfoque | Aplicaciones |
|---|---|---|
| **01-08-02** | Generación y mejora de prompts + investigación del sector | Copilot Chat |
| **01-08-03** | Ficha de preparación + correos + agenda | Word, Outlook, Teams |
| **01-08-04** | Presentación introductoria | PowerPoint |
| **01-08-05** | Matriz de necesidades del prospecto | Excel |

### Recursos adicionales

- [Documentación oficial de Microsoft 365 Copilot — Introducción y casos de uso](https://learn.microsoft.com/es-es/copilot/microsoft-365/microsoft-365-copilot-overview)
- [Guía de adopción de Microsoft 365 Copilot para organizaciones](https://adoption.microsoft.com/es-es/copilot/)
- [Centro de aprendizaje de Microsoft Copilot — Recursos para usuarios finales](https://learn.microsoft.com/es-es/copilot/microsoft-365/microsoft-365-copilot-user-guide)
- [Buenas prácticas para la redacción de prompts en Microsoft 365 Copilot](https://support.microsoft.com/es-es/topic/crear-prompts-eficaces-para-microsoft-365-copilot-1d9a4d6f-7e8d-4e4a-b4f3-3a6e3e4e4e4e)
- [Microsoft Copilot para ventas — Preparación de propuestas comerciales](https://learn.microsoft.com/es-es/microsoft-sales-copilot/introduction)

---

# Práctica guiada en Microsoft 365 Copilot Chat: redacción de prompt inicial y prompt mejorado con contexto del prospecto, objetivo de la conversación y resultado esperado

## Metadatos del Laboratorio

| Campo | Detalle |
|---|---|
| **Duración** | 15 minutos |
| **Complejidad** | Fácil |
| **Nivel de Bloom** | Aplicar |
| **Tecnologías** | Microsoft 365 Copilot Chat (copilot.microsoft.com) — modo Trabajo; Microsoft Edge 124.0.2478.97 o superior |
| **Lab anterior requerido** | 01-08-01 (demostración observada) |
| **Continuidad** | Los artefactos generados aquí se utilizan en el lab 01-08-03 |

---

## Descripción General

En este laboratorio practicarás de forma individual la construcción de prompts en Microsoft 365 Copilot Chat. Comenzarás redactando un prompt genérico para preparar una reunión con un prospecto de inversión, identificarás las limitaciones de la respuesta obtenida y luego construirás un prompt mejorado que incorpore el contexto completo de **CIBEST CAPITAL** y el perfil de **Carlos Mendoza**. Finalmente, compararás ambas respuestas en una tabla estructurada y realizarás al menos una iteración de refinamiento adicional. Este ejercicio sienta las bases del flujo de trabajo con Copilot que se expandirá en los laboratorios siguientes.

---

## Objetivos de Aprendizaje

Al completar este laboratorio, serás capaz de:

- [ ] Redactar de forma autónoma un prompt inicial genérico en Microsoft 365 Copilot Chat para preparar una reunión con un prospecto de inversión y evaluar las limitaciones de la respuesta obtenida.
- [ ] Construir un prompt mejorado que incorpore explícitamente el contexto de CIBEST CAPITAL, el perfil del prospecto Carlos Mendoza, el objetivo de la reunión inicial y el resultado esperado de la conversación con Copilot.
- [ ] Comparar y analizar la diferencia en calidad, relevancia y utilidad de las respuestas generadas por el prompt inicial versus el prompt mejorado.
- [ ] Guardar ambos prompts y sus respuestas como referencia documentada para uso en los labs subsiguientes.

---

## Prerrequisitos

### Conocimientos Previos

| Requisito | Descripción |
|---|---|
| Demostración 01-08-01 completada | Haber observado la demostración completa del lab 01-08-01 donde el instructor mostró la estructura de un prompt efectivo |
| Lecciones 1.1 a 1.7 | Conceptos de Microsoft 365 Copilot, estructura de prompts, y contexto del escenario CIBEST CAPITAL |
| Navegación web básica | Capacidad para utilizar Microsoft Edge, gestionar pestañas y copiar/pegar texto |
| Interfaces de chat | Familiaridad básica con interfaces conversacionales (enviar mensajes, leer respuestas) |

### Acceso y Cuentas

| Recurso | Requisito |
|---|---|
| Cuenta organizacional Microsoft 365 | Licencia Copilot M365 Premium activa y funcional |
| Microsoft Edge | Versión 124.0.2478.97 o superior, con sesión iniciada en la cuenta organizacional |
| Acceso a internet | Conexión estable de mínimo 10 Mbps |
| Copilot Chat | Acceso verificado a `https://copilot.microsoft.com` en modo **Trabajo** |

---

## Entorno del Laboratorio

### Requisitos de Hardware

| Componente | Mínimo | Recomendado |
|---|---|---|
| Procesador | 64 bits (Intel Core i5 / AMD Ryzen 5) | Intel Core i7 / AMD Ryzen 7 |
| RAM | 8 GB | 16 GB |
| Pantalla | 1366 × 768 | 1920 × 1080 |
| Almacenamiento libre | 10 GB | 10 GB |
| Conexión a internet | 10 Mbps bajada | 20 Mbps bajada |
| Periféricos | Teclado y ratón/trackpad funcionales | — |

### Requisitos de Software

| Software | Versión Mínima |
|---|---|
| Windows | Windows 10 22H2 (Build 19045) o Windows 11 23H2 (Build 22631) |
| Microsoft Edge | 124.0.2478.97 o superior |
| Microsoft 365 Copilot Chat | Servicio en la nube (verificada activa en mayo 2025) |
| Microsoft Word *(opcional para tabla comparativa)* | Versión 2405 (Build 17628.20164) |

### Configuración Inicial del Entorno

Antes de iniciar los pasos del laboratorio, completa las siguientes acciones preparatorias:

**A. Verificar la versión de Microsoft Edge:**

1. Abre Microsoft Edge.
2. Haz clic en el menú de tres puntos (`⋯`) en la esquina superior derecha.
3. Selecciona **Ayuda y comentarios** > **Acerca de Microsoft Edge**.
4. Confirma que la versión mostrada sea **124.0.2478.97 o superior**.

**B. Crear la estructura de carpetas de trabajo:**

1. Abre el Explorador de archivos de Windows.
2. Navega a tu carpeta de **OneDrive** sincronizada.
3. Crea la siguiente ruta de carpetas si no existe:

```
OneDrive > Documentos > CIBEST_CAPITAL > Prospectos
```

4. Confirma que la carpeta `Prospectos` esté visible y accesible.

**C. Acceder a Microsoft 365 Copilot Chat:**

1. Abre Microsoft Edge.
2. Navega a `https://copilot.microsoft.com`.
3. Si se solicita, inicia sesión con tu **cuenta organizacional** de Microsoft 365.
4. En la interfaz de Copilot Chat, localiza el selector de modo en la parte superior de la ventana de conversación.
5. Verifica que el modo **Trabajo** (ícono de maletín/edificio) esté seleccionado. Si el modo activo es "Web", haz clic en el selector y cambia a **Trabajo**.

> ⚠️ **IMPORTANTE:** El modo **Trabajo** es esencial para este laboratorio. Este modo permite que Copilot acceda al contexto organizacional y genere respuestas alineadas con el entorno empresarial. Si utilizas el modo "Web", las respuestas carecerán de la orientación profesional requerida.

**D. Preparar el documento para la tabla comparativa:**

1. Abre **Microsoft Word** (escritorio o web).
2. Crea un nuevo documento en blanco.
3. Guárdalo inmediatamente en la ruta:

```
OneDrive > Documentos > CIBEST_CAPITAL > Prospectos
```

4. Nómbralo exactamente:

```
Comparacion_Prompts_CarlosMendoza.docx
```

5. En la primera línea del documento, escribe el título:

```
Comparación de Prompts — Lab 01-08-02
Fecha: [fecha actual]
Estudiante: [tu nombre]
```

6. Deja el documento abierto en segundo plano; lo utilizarás en los Pasos 3 y 4.

---

## Pasos del Laboratorio

### Paso 1: Redacción y envío del prompt inicial genérico

**Objetivo:** Redactar un prompt deliberadamente genérico en Microsoft 365 Copilot Chat, enviar la solicitud y documentar tanto la respuesta como sus limitaciones observables.

**Instrucciones:**

1. Regresa a la pestaña de Microsoft Edge donde tienes abierto **Copilot Chat** (`https://copilot.microsoft.com`).

2. Confirma visualmente que el modo **Trabajo** sigue seleccionado (ícono de maletín/edificio activo en el selector de modo).

3. En el campo de texto del chat, escribe el siguiente prompt **exactamente como aparece** a continuación:

```
Ayúdame a preparar una reunión con un cliente interesado en invertir.
```

4. Presiona **Enter** o haz clic en el botón de enviar (ícono de flecha) para enviar el prompt.

5. Espera a que Copilot genere la respuesta completa. No interrumpas la generación.

6. **Lee la respuesta completa** con atención. Mientras lees, identifica y anota mentalmente las siguientes características:

   - ¿La respuesta menciona algún nombre de cliente específico?
   - ¿Hace referencia a algún tipo de inversión concreto?
   - ¿Incluye contexto sobre la industria o el perfil del prospecto?
   - ¿La respuesta está personalizada para una firma o empresa particular?
   - ¿El tono y nivel de detalle son adecuados para una reunión de asesoría de inversiones internacionales?

7. **Copia la respuesta completa** de Copilot:
   - Selecciona todo el texto de la respuesta de Copilot (haz clic al inicio, mantén Shift y haz clic al final).
   - Presiona `Ctrl + C` para copiar.

8. Cambia a la ventana de **Microsoft Word** donde tienes abierto el documento `Comparacion_Prompts_CarlosMendoza.docx`.

9. Debajo del encabezado que creaste en la configuración inicial, agrega la siguiente sección:

```
## PROMPT INICIAL (GENÉRICO)

### Prompt enviado:
Ayúdame a preparar una reunión con un cliente interesado en invertir.

### Respuesta de Copilot:
[Pega aquí la respuesta completa de Copilot — Ctrl+V]

### Limitaciones identificadas:
1. [Escribe aquí la primera limitación que identificaste]
2. [Escribe aquí la segunda limitación]
3. [Escribe aquí la tercera limitación]
4. [Escribe aquí la cuarta limitación]
5. [Escribe aquí la quinta limitación]
```

10. Completa las cinco limitaciones basándote en tu análisis del punto 6. A continuación se muestran ejemplos de limitaciones típicas que deberías haber identificado (tus observaciones pueden variar en redacción, pero deben cubrir ideas similares):

    - **Falta de personalización:** La respuesta no menciona a Carlos Mendoza ni a CIBEST CAPITAL.
    - **Contexto ausente:** No hay referencia al sector logístico ni a la situación específica del prospecto.
    - **Generalidad excesiva:** Los consejos son aplicables a cualquier reunión con cualquier cliente, sin especificidad.
    - **Sin perfil de riesgo:** No considera la experiencia limitada del prospecto en inversiones internacionales.
    - **Resultado no estructurado:** La respuesta no entrega un formato organizado (lista de temas, preguntas, enfoque recomendado).

11. Guarda el documento (`Ctrl + S`).

**Resultado esperado:**

Copilot generará una respuesta genérica con consejos generales sobre cómo preparar una reunión con un cliente inversionista. La respuesta típicamente incluirá recomendaciones amplias como "investigar al cliente", "preparar una agenda", "conocer los productos de inversión disponibles", etc., pero **sin ninguna personalización** hacia Carlos Mendoza, el sector logístico, las inversiones en Estados Unidos o el contexto de CIBEST CAPITAL.

**Verificación:**

- [ ] El prompt fue enviado exactamente como se indicó, sin agregar contexto adicional.
- [ ] La respuesta de Copilot fue recibida completamente y es de naturaleza genérica.
- [ ] La respuesta y al menos 5 limitaciones fueron documentadas en el archivo `Comparacion_Prompts_CarlosMendoza.docx`.
- [ ] El documento fue guardado en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.

---

### Paso 2: Construcción y envío del prompt mejorado con contexto completo

**Objetivo:** Construir un prompt estructurado que incorpore los cuatro elementos clave demostrados en el lab 01-08-01 (rol, contexto del prospecto, objetivo de la reunión y resultado esperado), enviarlo a Copilot Chat y obtener una respuesta significativamente más relevante y útil.

**Instrucciones:**

1. En la interfaz de **Copilot Chat**, inicia una **nueva conversación** para evitar que el contexto del prompt genérico anterior influya en la respuesta. Para hacerlo:
   - Haz clic en el botón **"Nuevo chat"** (ícono de `+` o "Nueva conversación") ubicado generalmente en la parte superior izquierda o en la barra lateral del panel de chat.
   - Confirma que aparece un campo de texto vacío sin historial de conversación previo.

2. Confirma nuevamente que el modo **Trabajo** está seleccionado.

3. Antes de escribir el prompt, revisa los cuatro componentes que debe contener:

   | Componente | Contenido a incluir |
   |---|---|
   | **(a) Rol asignado a Copilot** | Asesor de inversiones senior en CIBEST CAPITAL |
   | **(b) Contexto del prospecto** | Carlos Mendoza, propietario de empresa de logística en México, ingresos anuales ~USD 5M, interés en diversificar patrimonio invirtiendo en activos en EE.UU., experiencia limitada en inversiones internacionales |
   | **(c) Objetivo de la conversación** | Preparar la primera reunión de descubrimiento con el prospecto |
   | **(d) Resultado esperado** | Lista de temas a cubrir, información a obtener del prospecto, y recomendaciones de enfoque para la reunión |

4. En el campo de texto del chat, escribe el siguiente prompt mejorado. **Puedes copiarlo exactamente** o adaptarlo ligeramente con tu propia redacción, siempre que mantengas los cuatro componentes:

```
Eres un asesor de inversiones senior en CIBEST CAPITAL, una firma de servicios financieros especializada en asesoría de inversiones internacionales. 

Estoy preparando la primera reunión de descubrimiento con un nuevo prospecto llamado Carlos Mendoza. Este es su perfil:
- Propietario de una empresa de logística en México
- Ingresos anuales aproximados de USD 5 millones
- Está interesado en diversificar su patrimonio invirtiendo en activos en Estados Unidos
- Tiene experiencia limitada en inversiones internacionales

Mi objetivo es preparar esta primera reunión de descubrimiento de manera profesional y efectiva.

Necesito que me proporciones:
1. Una lista de los temas clave que debo cubrir durante la reunión
2. La información específica que necesito obtener de Carlos Mendoza durante la conversación
3. Recomendaciones de enfoque y tono para la reunión, considerando que el prospecto tiene experiencia limitada en inversiones internacionales

Presenta la información en formato de listas organizadas por categoría.
```

5. Revisa el prompt antes de enviarlo. Confirma que contiene:
   - ✅ Rol: "asesor de inversiones senior en CIBEST CAPITAL"
   - ✅ Contexto del prospecto: nombre, empresa, sector, ingresos, interés, nivel de experiencia
   - ✅ Objetivo: "primera reunión de descubrimiento"
   - ✅ Resultado esperado: tres entregables específicos con formato solicitado

6. Presiona **Enter** o haz clic en el botón de enviar para enviar el prompt.

7. Espera a que Copilot genere la respuesta completa sin interrumpir.

8. **Lee la respuesta completa** detenidamente. Mientras lees, observa las siguientes diferencias respecto a la respuesta del Paso 1:

   - ¿Menciona a Carlos Mendoza por nombre?
   - ¿Hace referencia al sector logístico?
   - ¿Considera la experiencia limitada del prospecto?
   - ¿Incluye recomendaciones sobre inversiones en Estados Unidos?
   - ¿La estructura de la respuesta sigue el formato solicitado (listas por categoría)?
   - ¿El tono es adecuado para un asesor de CIBEST CAPITAL?

9. **Copia la respuesta completa** de Copilot (`Ctrl + C`).

10. Cambia al documento **Word** (`Comparacion_Prompts_CarlosMendoza.docx`) y agrega la siguiente sección debajo de la sección del prompt inicial:

```
## PROMPT MEJORADO (CON CONTEXTO)

### Prompt enviado:
[Pega aquí el prompt mejorado exacto que enviaste]

### Respuesta de Copilot:
[Pega aquí la respuesta completa de Copilot — Ctrl+V]

### Fortalezas identificadas:
1. [Escribe aquí la primera fortaleza que observaste]
2. [Escribe aquí la segunda fortaleza]
3. [Escribe aquí la tercera fortaleza]
4. [Escribe aquí la cuarta fortaleza]
5. [Escribe aquí la quinta fortaleza]
```

11. Completa las cinco fortalezas. Ejemplos de fortalezas típicas:

    - **Personalización:** La respuesta menciona a Carlos Mendoza por nombre y hace referencia a su empresa de logística.
    - **Contexto sectorial:** Incluye consideraciones relevantes para un empresario del sector logístico mexicano.
    - **Sensibilidad al nivel de experiencia:** Las recomendaciones de tono consideran que el prospecto tiene experiencia limitada en inversiones internacionales.
    - **Estructura organizada:** La respuesta sigue el formato de listas por categoría solicitado.
    - **Especificidad del objetivo:** Los temas y preguntas están orientados a una reunión de descubrimiento, no a una reunión genérica de ventas.

12. Guarda el documento (`Ctrl + S`).

**Resultado esperado:**

Copilot generará una respuesta sustancialmente más detallada, personalizada y estructurada que la del prompt genérico. La respuesta típicamente incluirá:

- **Temas clave para la reunión:** Objetivos financieros de Carlos Mendoza, horizonte de inversión, tolerancia al riesgo, situación fiscal transfronteriza (México-EE.UU.), tipos de activos disponibles en EE.UU., marco regulatorio para inversión extranjera, etc.
- **Información a obtener del prospecto:** Patrimonio actual, estructura legal de su empresa, obligaciones financieras existentes, expectativas de rendimiento, plazo de inversión, preferencias de liquidez, experiencia previa con instrumentos financieros, etc.
- **Recomendaciones de enfoque:** Usar lenguaje accesible sin tecnicismos excesivos, comenzar con preguntas abiertas, establecer confianza antes de hablar de productos específicos, explicar conceptos básicos de inversión internacional, etc.

**Verificación:**

- [ ] El prompt mejorado fue enviado en una nueva conversación (sin contexto del prompt anterior).
- [ ] El prompt contiene los cuatro componentes: rol, contexto del prospecto, objetivo y resultado esperado.
- [ ] La respuesta de Copilot es notablemente más específica, personalizada y estructurada que la del Paso 1.
- [ ] El prompt mejorado, la respuesta y al menos 5 fortalezas fueron documentados en el archivo Word.
- [ ] El documento fue guardado.

---

### Paso 3: Comparación estructurada de ambas respuestas

**Objetivo:** Crear una tabla comparativa formal que contraste las respuestas del prompt genérico y del prompt mejorado en dimensiones clave de calidad, consolidando el análisis en un formato reutilizable.

**Instrucciones:**

1. En el documento **Word** (`Comparacion_Prompts_CarlosMendoza.docx`), agrega una nueva sección debajo de las anteriores:

```
## TABLA COMPARATIVA
```

2. Inserta una tabla con **3 columnas** y **7 filas** (1 fila de encabezado + 6 filas de criterios). Para insertar la tabla en Word:
   - Ve a la pestaña **Insertar** en la cinta de opciones.
   - Haz clic en **Tabla**.
   - Selecciona una cuadrícula de **3 columnas × 7 filas**.

3. Completa la tabla con la siguiente estructura. La columna central y la columna derecha deben llenarse con **tus propias observaciones** basadas en las respuestas reales que recibiste:

| Criterio de evaluación | Prompt inicial (genérico) | Prompt mejorado (con contexto) |
|---|---|---|
| **Personalización** (¿Menciona al prospecto, la firma o el sector?) | [Tu observación — típicamente: No menciona nombres ni contexto específico] | [Tu observación — típicamente: Menciona a Carlos Mendoza, CIBEST CAPITAL y logística] |
| **Relevancia sectorial** (¿Incluye información del sector logístico o de México?) | [Tu observación] | [Tu observación] |
| **Nivel de detalle** (¿Proporciona recomendaciones específicas y accionables?) | [Tu observación] | [Tu observación] |
| **Estructura y formato** (¿La respuesta está organizada de forma clara?) | [Tu observación] | [Tu observación] |
| **Adecuación del tono** (¿Considera la experiencia limitada del prospecto?) | [Tu observación] | [Tu observación] |
| **Utilidad práctica** (¿Podrías usar esta respuesta directamente para preparar la reunión?) | [Tu observación] | [Tu observación] |

4. Debajo de la tabla, agrega un párrafo de **conclusión de 3 a 5 oraciones** que resuma tu aprendizaje principal sobre la diferencia entre ambos prompts. Ejemplo de estructura:

```
### Conclusión de la comparación:
La comparación demuestra que [tu observación principal]. El prompt mejorado generó 
una respuesta [adjetivo comparativo] porque [razón]. Esto confirma que [principio 
aprendido sobre la construcción de prompts]. Para los siguientes labs, aplicaré 
[acción concreta que llevarás a cabo].
```

5. Guarda el documento (`Ctrl + S`).

**Resultado esperado:**

Una tabla comparativa completa con observaciones específicas en cada celda que evidencien la diferencia cualitativa entre ambas respuestas. La conclusión debe articular de forma clara que la inclusión de contexto (rol, perfil del prospecto, objetivo y resultado esperado) transforma significativamente la calidad y utilidad de la respuesta de Copilot.

**Verificación:**

- [ ] La tabla contiene 3 columnas y 6 criterios de evaluación completados con observaciones propias.
- [ ] Las observaciones son específicas (no genéricas como "mejor" o "peor") y hacen referencia a elementos concretos de las respuestas recibidas.
- [ ] La conclusión tiene entre 3 y 5 oraciones y articula un aprendizaje claro.
- [ ] El documento fue guardado.

---

### Paso 4: Refinamiento iterativo del prompt

**Objetivo:** Practicar al menos una iteración adicional de mejora del prompt mejorado, ajustando un elemento específico (tono, extensión o formato de salida), y documentar el cambio realizado junto con su impacto en la respuesta.

**Instrucciones:**

1. Regresa a **Copilot Chat** en Microsoft Edge. Puedes continuar en la misma conversación del Paso 2 (esto es intencional — el refinamiento iterativo aprovecha el contexto de la conversación existente).

2. Decide **qué elemento** vas a ajustar en esta iteración. Elige **una** de las siguientes opciones:

   | Opción | Ajuste a realizar | Ejemplo de instrucción adicional |
   |---|---|---|
   | **A — Tono** | Solicitar que la respuesta use un tono más cálido y empático, adecuado para un prospecto que puede sentir inseguridad por su falta de experiencia | `"Reformula las recomendaciones de enfoque usando un tono más cálido y empático, considerando que Carlos Mendoza podría sentir inseguridad al hablar de inversiones internacionales por primera vez."` |
   | **B — Extensión** | Solicitar una versión más concisa, tipo checklist ejecutivo, que puedas imprimir en una sola página | `"Condensa toda la información anterior en un checklist ejecutivo de máximo 15 puntos que pueda imprimirse en una sola página para llevar a la reunión."` |
   | **C — Formato de salida** | Solicitar que la información se reorganice en formato de agenda cronológica para la reunión | `"Reorganiza la información como una agenda cronológica para una reunión de 45 minutos, indicando los minutos asignados a cada tema y las preguntas clave para cada bloque."` |

3. Escribe el prompt de refinamiento en el campo de texto de Copilot Chat. A continuación se muestra un ejemplo completo para la **Opción C** (formato de salida). Si eliges otra opción, adapta el prompt según la tabla anterior:

```
Reorganiza toda la información que me proporcionaste como una agenda cronológica para una reunión de 45 minutos con Carlos Mendoza. Para cada bloque de tiempo, indica:
- Los minutos asignados
- El tema a cubrir
- Las preguntas clave a hacer
- Una nota sobre el tono recomendado para ese momento de la reunión

Presenta la agenda en formato de tabla.
```

4. Presiona **Enter** para enviar el prompt de refinamiento.

5. Espera a que Copilot genere la respuesta completa.

6. **Analiza la respuesta refinada:** ¿El ajuste solicitado se refleja en la respuesta? ¿La calidad general mejoró, se mantuvo o disminuyó? ¿El formato es más útil para el propósito práctico de preparar la reunión?

7. **Copia la respuesta** (`Ctrl + C`).

8. Cambia al documento **Word** y agrega la siguiente sección final:

```
## REFINAMIENTO ITERATIVO

### Elemento ajustado:
[Tono / Extensión / Formato de salida — indica cuál elegiste]

### Prompt de refinamiento enviado:
[Pega aquí el prompt exacto que enviaste]

### Respuesta refinada de Copilot:
[Pega aquí la respuesta completa — Ctrl+V]

### Análisis del impacto del refinamiento:
- ¿El ajuste se reflejó en la respuesta? [Sí/No — explica]
- ¿La calidad general mejoró? [Sí/No — explica]
- ¿La respuesta refinada es más útil para preparar la reunión? [Sí/No — explica]
- Lección aprendida sobre refinamiento iterativo: [Escribe una oración]
```

9. Completa todos los campos de análisis con observaciones específicas.

10. Guarda el documento final (`Ctrl + S`).

11. Confirma que el documento `Comparacion_Prompts_CarlosMendoza.docx` está guardado en:

```
OneDrive > Documentos > CIBEST_CAPITAL > Prospectos
```

**Resultado esperado:**

La respuesta refinada debe mostrar un cambio observable en el elemento ajustado (tono más cálido, formato más conciso, o estructura cronológica, según la opción elegida), manteniendo la calidad y personalización logradas en el prompt mejorado del Paso 2. El estudiante debe ser capaz de articular cómo el refinamiento iterativo permite optimizar progresivamente las respuestas de Copilot sin necesidad de reescribir el prompt completo.

**Verificación:**

- [ ] Se envió al menos un prompt de refinamiento que ajusta un elemento específico (tono, extensión o formato).
- [ ] La respuesta refinada muestra un cambio observable respecto a la respuesta del Paso 2.
- [ ] El prompt de refinamiento, la respuesta y el análisis de impacto fueron documentados en el archivo Word.
- [ ] El documento final fue guardado en la ruta correcta de OneDrive.

---

## Validación y Pruebas

Antes de considerar el laboratorio como completado, verifica que se cumplan **todos** los criterios siguientes:

### Lista de Verificación Final

| # | Criterio | Estado |
|---|---|---|
| 1 | El archivo `Comparacion_Prompts_CarlosMendoza.docx` existe en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos` | ☐ |
| 2 | El documento contiene la sección **Prompt Inicial** con el prompt genérico, la respuesta de Copilot y al menos 5 limitaciones identificadas | ☐ |
| 3 | El documento contiene la sección **Prompt Mejorado** con el prompt completo (4 componentes), la respuesta de Copilot y al menos 5 fortalezas identificadas | ☐ |
| 4 | El documento contiene la **Tabla Comparativa** con 6 criterios evaluados y una conclusión de 3-5 oraciones | ☐ |
| 5 | El documento contiene la sección **Refinamiento Iterativo** con el prompt de refinamiento, la respuesta y el análisis de impacto | ☐ |
| 6 | El prompt mejorado incluye los 4 componentes: (a) rol, (b) contexto del prospecto, (c) objetivo, (d) resultado esperado | ☐ |
| 7 | La diferencia de calidad entre la respuesta del prompt genérico y la del prompt mejorado es claramente observable y está documentada | ☐ |

### Validación de Calidad del Prompt Mejorado

Revisa tu prompt mejorado contra esta rúbrica rápida:

| Componente | Presente | Específico | Accionable |
|---|---|---|---|
| Rol asignado a Copilot | ☐ | ☐ Menciona "CIBEST CAPITAL" | ☐ Define el tipo de asesor |
| Contexto del prospecto | ☐ | ☐ Incluye nombre, sector, ingresos, interés, experiencia | ☐ Todos los datos son utilizables |
| Objetivo de la conversación | ☐ | ☐ Especifica "primera reunión de descubrimiento" | ☐ Claro y delimitado |
| Resultado esperado | ☐ | ☐ Lista los 3 entregables solicitados | ☐ Incluye formato deseado |

Si algún componente no cumple los tres criterios (presente, específico, accionable), considera revisar tu prompt antes de avanzar al lab 01-08-03.

---

## Solución de Problemas

### Problema 1: Copilot Chat no muestra la opción de modo "Trabajo"

**Síntomas:** Al acceder a `https://copilot.microsoft.com`, la interfaz solo muestra el modo "Web" o no aparece ningún selector de modo. El ícono de maletín/edificio no está visible.

**Causa:** La licencia de Microsoft 365 Copilot Premium no está activa en la cuenta organizacional del estudiante, o la sesión de Edge no está vinculada a la cuenta organizacional correcta. Esto puede ocurrir si el estudiante inició sesión con una cuenta personal de Microsoft en lugar de la cuenta de la organización.

**Solución:**

1. Verifica la cuenta activa en Edge:
   - Haz clic en el ícono de perfil en la esquina superior derecha de Edge.
   - Confirma que la cuenta mostrada es tu **cuenta organizacional** (generalmente con dominio `@tuorganizacion.com` o similar, **no** `@outlook.com` ni `@hotmail.com`).
2. Si la cuenta es incorrecta:
   - Haz clic en **"Cambiar perfil"** o **"Agregar perfil"**.
   - Inicia sesión con tu cuenta organizacional.
   - Navega nuevamente a `https://copilot.microsoft.com`.
3. Si la cuenta es correcta pero el modo Trabajo no aparece:
   - Cierra completamente Edge.
   - Abre Edge nuevamente y navega a `https://www.office.com`. Confirma que puedes acceder a las aplicaciones de Microsoft 365.
   - Luego navega a `https://copilot.microsoft.com`.
   - Si el problema persiste, contacta al instructor — es probable que la licencia Copilot M365 Premium no esté asignada a tu cuenta.

---

### Problema 2: La respuesta del prompt mejorado sigue siendo genérica y no menciona a Carlos Mendoza

**Síntomas:** A pesar de haber incluido el contexto completo del prospecto en el prompt, la respuesta de Copilot no personaliza el contenido, no menciona a Carlos Mendoza por nombre, y proporciona recomendaciones genéricas similares a las del prompt inicial.

**Causa:** Este problema generalmente ocurre por una de dos razones: (1) el prompt fue enviado en la misma conversación que el prompt genérico del Paso 1, y Copilot está priorizando el contexto inicial; o (2) el prompt fue truncado o modificado accidentalmente al copiarlo, omitiendo secciones clave del contexto.

**Solución:**

1. **Verifica que estás en una nueva conversación:**
   - Revisa el historial del chat. Si ves el prompt genérico del Paso 1 arriba del prompt mejorado, estás en la misma conversación.
   - Haz clic en **"Nuevo chat"** para iniciar una conversación limpia.
   - Vuelve a enviar el prompt mejorado completo.

2. **Verifica la integridad del prompt:**
   - Antes de enviar, revisa que el prompt contenga:
     - El nombre "Carlos Mendoza"
     - La referencia a "CIBEST CAPITAL"
     - Los datos del perfil (logística, México, USD 5M, EE.UU., experiencia limitada)
   - Si copiaste el prompt desde esta guía, asegúrate de que no se truncó durante el pegado. Compara el texto en el campo de chat con el prompt completo de la sección Paso 2, instrucción 4.

3. **Reenvía el prompt** en la nueva conversación y espera la respuesta completa.

---

## Limpieza

Este laboratorio **no requiere eliminar** ningún archivo ni recurso creado, ya que los artefactos generados son insumos para los labs subsiguientes. Realiza las siguientes acciones de cierre:

1. **Confirma el guardado final** del documento `Comparacion_Prompts_CarlosMendoza.docx`:
   - En Word, presiona `Ctrl + S`.
   - Verifica en la barra de título que el archivo muestra "Guardado" o "Guardado en OneDrive".

2. **Verifica la ubicación del archivo:**
   - Abre el Explorador de archivos.
   - Navega a `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.
   - Confirma que el archivo `Comparacion_Prompts_CarlosMendoza.docx` está presente.

3. **No cierres las conversaciones de Copilot Chat.** El historial de chat se preserva automáticamente en tu cuenta y puede ser útil como referencia en labs posteriores.

4. **Mantén la sesión de Edge activa** con tu cuenta organizacional si vas a continuar con el lab 01-08-03 inmediatamente.

> 📌 **NOTA DE CONTINUIDAD:** El archivo `Comparacion_Prompts_CarlosMendoza.docx` y los prompts desarrollados en este laboratorio serán referenciados en el **lab 01-08-03**, donde expandirás el uso de Copilot para generar preguntas de descubrimiento categorizadas. Adicionalmente, las técnicas de construcción de prompts practicadas aquí se aplicarán a lo largo de todo el batch de laboratorios, incluyendo la creación de la ficha de preparación `Ficha_Preparacion_CarlosMendoza_CIBEST.docx`.

---

## Resumen

En este laboratorio aplicaste de forma práctica los principios de construcción de prompts efectivos en Microsoft 365 Copilot Chat. Los aprendizajes clave son:

| Concepto | Lo que aprendiste |
|---|---|
| **Prompt genérico vs. contextualizado** | Un prompt sin contexto genera respuestas genéricas de utilidad limitada; agregar rol, perfil del prospecto, objetivo y resultado esperado transforma radicalmente la calidad de la respuesta |
| **Estructura de 4 componentes** | Los prompts más efectivos incluyen: (a) rol asignado a Copilot, (b) contexto detallado del prospecto, (c) objetivo claro de la conversación, (d) resultado esperado con formato especificado |
| **Refinamiento iterativo** | No es necesario reescribir el prompt completo para mejorar la respuesta; se pueden enviar instrucciones de ajuste (tono, extensión, formato) en la misma conversación |
| **Documentación como práctica profesional** | Registrar prompts, respuestas y análisis comparativos crea un acervo de referencia que acelera el trabajo futuro |

### Artefactos Generados

| Archivo | Ubicación | Propósito |
|---|---|---|
| `Comparacion_Prompts_CarlosMendoza.docx` | `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos` | Referencia comparativa de prompts y respuestas; insumo para lab 01-08-03 |

### Conexión con el Siguiente Laboratorio

En el **lab 01-08-03**, utilizarás las técnicas de prompting practicadas aquí para generar preguntas de descubrimiento categorizadas para la reunión con Carlos Mendoza. El prompt mejorado de este lab servirá como base que expandirás con instrucciones más específicas sobre categorías de preguntas (financieras, personales, regulatorias, etc.).

### Recursos Adicionales

- [Buenas prácticas para la redacción de prompts en Microsoft 365 Copilot](https://support.microsoft.com/es-es/topic/crear-prompts-eficaces-para-microsoft-365-copilot-1d9a4d6f-7e8d-4e4a-b4f3-3a6e3e4e4e4e)
- [Documentación oficial de Microsoft 365 Copilot — Introducción y casos de uso](https://learn.microsoft.com/es-es/copilot/microsoft-365/microsoft-365-copilot-overview)
- [Centro de aprendizaje de Microsoft Copilot — Recursos para usuarios finales](https://learn.microsoft.com/es-es/copilot/microsoft-365/microsoft-365-copilot-user-guide)
- [Guía de adopción de Microsoft 365 Copilot para organizaciones](https://adoption.microsoft.com/es-es/copilot/)

---

# Práctica guiada en Microsoft 365 Copilot Chat: generación de preguntas de descubrimiento estructuradas por categorías (objetivos, horizonte, liquidez, experiencia, tolerancia al riesgo)

## 1. Metadatos del laboratorio

| Campo | Detalle |
|---|---|
| **Duración** | 15 minutos |
| **Complejidad** | Fácil |
| **Nivel de Bloom** | Aplicar |
| **Lab anterior requerido** | Lab 01-08-02 (prompt mejorado documentado) |
| **Lab siguiente** | Lab 01-08-04 (investigación del sector logístico) |
| **Aplicaciones utilizadas** | Microsoft 365 Copilot Chat (copilot.microsoft.com) — modo Trabajo, Microsoft Edge |

---

## 2. Descripción general

En este laboratorio aplicarás el prompt mejorado que desarrollaste en el lab 01-08-02 para solicitar a Microsoft 365 Copilot Chat la generación de preguntas de descubrimiento dirigidas al prospecto **Carlos Mendoza**. Las preguntas se organizarán en cinco categorías clave de perfilamiento financiero — objetivos de inversión, horizonte temporal, necesidades de liquidez, experiencia previa en inversiones y tolerancia al riesgo — más una categoría adicional de expectativas y motivaciones. A lo largo del ejercicio, evaluarás críticamente las respuestas de Copilot, refinarás el lenguaje para que sea accesible a un empresario con experiencia limitada en inversiones internacionales, y consolidarás un conjunto final de 12–18 preguntas listas para integrarse en la ficha de preparación del lab 01-08-05.

---

## 3. Objetivos de aprendizaje

Al completar este laboratorio, serás capaz de:

- [ ] Utilizar el prompt mejorado del lab 01-08-02 como contexto base para solicitar a Copilot Chat la generación de preguntas de descubrimiento específicas para Carlos Mendoza.
- [ ] Generar preguntas de descubrimiento organizadas en cinco categorías explícitas: objetivos de inversión, horizonte temporal, necesidades de liquidez, experiencia previa en inversiones y tolerancia al riesgo.
- [ ] Refinar las preguntas generadas mediante prompts de seguimiento que aseguren un lenguaje claro, accesible y culturalmente apropiado para un empresario latinoamericano con experiencia limitada en inversiones internacionales.
- [ ] Documentar un conjunto final de 12–18 preguntas categorizadas (incluyendo la categoría adicional de expectativas y motivaciones) que se integrarán como componente central de la ficha de preparación en el lab 01-08-05.

---

## 4. Prerrequisitos

### Conocimientos previos

| Requisito | Detalle |
|---|---|
| Lab 01-08-02 completado | Debes tener documentado el **prompt mejorado** resultante del lab anterior, ya sea en un archivo de texto, en el portapapeles o visible en el historial de Copilot Chat. |
| Conceptos de perfilamiento financiero | Comprensión básica de los cinco ejes de descubrimiento: objetivos de inversión, horizonte temporal, liquidez, experiencia en inversiones y tolerancia al riesgo (cubiertos en la demostración 01-08-01). |
| Técnicas de prompting iterativo | Familiaridad con la técnica de refinamiento progresivo de prompts practicada en el lab 01-08-02. |

### Acceso y licencias

| Recurso | Requisito |
|---|---|
| Cuenta Microsoft 365 | Cuenta organizacional con licencia **Microsoft 365 Copilot Premium** activa. |
| Microsoft Edge | Versión 124.0.2478.97 o superior. |
| Copilot Chat | Acceso verificado a [copilot.microsoft.com](https://copilot.microsoft.com) con modo **Trabajo** disponible. |
| Conexión a internet | Mínimo 10 Mbps de bajada, estable durante toda la sesión. |

---

## 5. Entorno del laboratorio

### Hardware mínimo

| Componente | Especificación |
|---|---|
| Procesador | 64 bits — Intel Core i5 / AMD Ryzen 5 o superior |
| RAM | 8 GB mínimo (16 GB recomendado) |
| Pantalla | 1366×768 mínimo (1920×1080 recomendado) |
| Almacenamiento libre | 10 GB mínimo |
| Periféricos | Teclado y ratón/trackpad funcionales |

### Software requerido

| Aplicación | Versión |
|---|---|
| Windows | Windows 10 22H2 (Build 19045) o Windows 11 23H2 (Build 22631) o superior |
| Microsoft Edge | 124.0.2478.97 o superior |
| Microsoft 365 Copilot Chat | Servicio en la nube (copilot.microsoft.com) — actualización automática |

### Configuración inicial

Antes de comenzar, verifica que tu entorno esté listo:

1. Abre **Microsoft Edge** y navega a [copilot.microsoft.com](https://copilot.microsoft.com).
2. Inicia sesión con tu cuenta organizacional de Microsoft 365.
3. Confirma que el selector de modo muestre **Trabajo** (Work) en la parte superior de la interfaz de Copilot Chat. Si muestra "Web", haz clic en el selector y cambia a **Trabajo**.
4. Ten a la mano el **prompt mejorado** documentado en el lab 01-08-02. Si cerraste la sesión anterior, cópialo desde tu archivo de documentación.
5. Verifica que la ruta de OneDrive **Documentos > CIBEST_CAPITAL > Prospectos** exista y sea accesible (la necesitarás al final para guardar el resultado).

> 💡 **Consejo:** Si la sesión de Copilot Chat del lab 01-08-02 aún está abierta, puedes continuar directamente en ella. Copilot conservará el contexto de la conversación anterior, lo que enriquecerá las respuestas de este lab.

---

## 6. Instrucciones paso a paso

### Paso 1 — Establecer el contexto y solicitar preguntas de descubrimiento iniciales

**Objetivo:** Proporcionar a Copilot Chat el contexto completo del prospecto y solicitar la generación de preguntas de descubrimiento organizadas en las cinco categorías requeridas.

**Instrucciones:**

1. En la ventana de Copilot Chat (copilot.microsoft.com, modo **Trabajo**), verifica que estés en una conversación activa. Si continuaste desde el lab 01-08-02, el contexto ya está presente; avanza al punto 3. Si iniciaste una nueva conversación, continúa con el punto 2.

2. **(Solo si es una nueva conversación)** Escribe el siguiente prompt para restablecer el contexto. Sustituye `[PEGAR PROMPT MEJORADO DEL LAB 01-08-02]` por el texto exacto de tu prompt mejorado:

```
Contexto previo para esta conversación:

[PEGAR PROMPT MEJORADO DEL LAB 01-08-02]

Confirma que entiendes el perfil de Carlos Mendoza y el contexto de CIBEST CAPITAL antes de continuar.
```

3. Una vez que Copilot confirme el contexto (o si ya lo tiene de la sesión anterior), escribe el siguiente prompt de solicitud de preguntas:

```
Con base en el perfil de Carlos Mendoza — propietario de una empresa de logística en México con ingresos anuales de aproximadamente USD 5 millones, interesado en diversificar su patrimonio invirtiendo en activos en Estados Unidos, y con experiencia limitada en inversiones internacionales — genera una lista de preguntas de descubrimiento que un asesor de CIBEST CAPITAL haría en una primera reunión.

Organiza las preguntas en exactamente 5 categorías:
1. Objetivos de inversión
2. Horizonte temporal
3. Necesidades de liquidez
4. Experiencia previa en inversiones
5. Tolerancia al riesgo

Requisitos:
- Genera entre 3 y 5 preguntas por categoría.
- Usa un lenguaje claro, conversacional y accesible para alguien con poca experiencia en inversiones internacionales.
- Evita jerga financiera técnica; si un término técnico es necesario, incluye una breve explicación entre paréntesis.
- Las preguntas deben ser abiertas (no de sí/no) para fomentar que Carlos comparta información detallada.
- Considera el contexto cultural latinoamericano y empresarial de Carlos.
```

4. Presiona **Enter** y espera la respuesta completa de Copilot.

5. **Lee la respuesta completa** sin interrumpir la generación. Copilot producirá una lista estructurada con las cinco categorías solicitadas.

**Resultado esperado:**

Copilot debe generar una lista de 15–25 preguntas distribuidas en las cinco categorías. Cada categoría debe contener entre 3 y 5 preguntas abiertas. El lenguaje debe ser mayoritariamente accesible, aunque es posible que algunas preguntas contengan terminología que necesite simplificación (esto se abordará en los pasos siguientes).

Ejemplo parcial de lo que podrías obtener:

> **1. Objetivos de inversión**
> - ¿Qué le gustaría lograr con estas inversiones en Estados Unidos? Por ejemplo, ¿busca hacer crecer su dinero a largo plazo, generar ingresos regulares, o proteger su patrimonio?
> - ¿Hay algún proyecto personal o familiar importante para el que quiera destinar los rendimientos de estas inversiones?
> - ...
>
> **2. Horizonte temporal**
> - ¿En cuánto tiempo imagina que podría necesitar acceder al dinero que invierta?
> - ...

**Verificación:**

- [ ] La respuesta contiene exactamente 5 categorías con los nombres solicitados.
- [ ] Cada categoría tiene al menos 3 preguntas.
- [ ] Las preguntas son mayoritariamente abiertas (no de sí/no).
- [ ] El lenguaje es predominantemente accesible (sin exceso de jerga financiera).

---

### Paso 2 — Evaluación crítica de las preguntas generadas

**Objetivo:** Analizar las preguntas producidas por Copilot para identificar oportunidades de mejora en tres dimensiones: tecnicismo excesivo, tono intimidante y vacíos por categoría.

**Instrucciones:**

1. Copia la respuesta completa de Copilot a un documento temporal (puedes usar el Bloc de notas, un archivo de texto, o simplemente trabajar directamente en la pantalla de Copilot Chat).

2. Revisa **cada pregunta** aplicando los siguientes tres filtros de evaluación:

   | Filtro | Qué buscar | Ejemplo de problema |
   |---|---|---|
   | **(a) Tecnicismo excesivo** | Términos como "asset allocation", "volatilidad", "rendimiento ajustado al riesgo", "diversificación de cartera", "instrumentos de renta fija" sin explicación. | "¿Cuál es su tolerancia a la volatilidad de los mercados de renta variable?" |
   | **(b) Tono intimidante** | Preguntas que asumen conocimiento previo o que podrían hacer sentir al prospecto que "debería saber" algo. | "¿Qué porcentaje de su patrimonio neto destina actualmente a inversiones alternativas?" |
   | **(c) Vacíos por categoría** | Categorías con menos de 3 preguntas, o preguntas que no cubren aspectos relevantes para el perfil específico de Carlos Mendoza. | La categoría "Necesidades de liquidez" solo tiene 2 preguntas y ninguna aborda la estacionalidad del negocio logístico. |

3. En un espacio aparte (o mentalmente), anota tus hallazgos usando el siguiente formato:

```
EVALUACIÓN DE PREGUNTAS GENERADAS:

Categoría 1 — Objetivos de inversión:
  - Pregunta 3: Demasiado técnica → usa "diversificación de portafolio" sin explicar
  - Falta: No pregunta sobre metas familiares o educativas

Categoría 2 — Horizonte temporal:
  - Todas las preguntas son adecuadas ✓

Categoría 3 — Necesidades de liquidez:
  - Pregunta 1: Tono intimidante → asume que conoce el concepto de "liquidez"
  - Falta: No conecta con los ciclos del negocio logístico

Categoría 4 — Experiencia previa en inversiones:
  - Pregunta 2: Podría ser intimidante → "¿Qué instrumentos financieros ha utilizado?"

Categoría 5 — Tolerancia al riesgo:
  - Pregunta 1 y 3: Demasiado técnicas
  - Falta: No usa analogías o escenarios concretos
```

4. **No solicites cambios a Copilot todavía.** Este paso es exclusivamente de evaluación crítica. El refinamiento se realizará en el Paso 3.

**Resultado esperado:**

Debes tener documentada una evaluación con al menos **un hallazgo por categoría** (ya sea un problema identificado o una confirmación de que la categoría está bien). Es normal encontrar entre 3 y 7 problemas en total en la primera generación de Copilot.

**Verificación:**

- [ ] Has revisado las cinco categorías de forma individual.
- [ ] Has identificado al menos 3 oportunidades de mejora en total (tecnicismo, tono o vacíos).
- [ ] Has documentado tus hallazgos antes de pasar al refinamiento.

---

### Paso 3 — Refinamiento por categoría mediante prompts de seguimiento

**Objetivo:** Utilizar prompts de seguimiento dirigidos para mejorar las preguntas en cada categoría, asegurando que el lenguaje sea accesible, empático y culturalmente apropiado para Carlos Mendoza.

**Instrucciones:**

Este paso requiere que escribas **al menos un prompt de seguimiento por cada una de las cinco categorías**. A continuación se proporcionan prompts modelo para cada categoría. **Adáptalos** según los hallazgos específicos de tu evaluación del Paso 2.

---

**3.1 — Refinamiento de "Objetivos de inversión"**

1. En Copilot Chat, escribe el siguiente prompt (ajústalo según tus hallazgos):

```
Revisando las preguntas de la categoría "Objetivos de inversión": algunas usan términos como "diversificación de portafolio" o "rendimientos" sin contexto. Reformula las preguntas de esta categoría para que sean más conversacionales. Incluye al menos una pregunta que explore si Carlos tiene metas familiares o educativas vinculadas a estas inversiones. Recuerda que Carlos es empresario y piensa en términos de negocio, no de finanzas abstractas.
```

2. Revisa la respuesta. Las preguntas reformuladas deben sonar como algo que dirías en una conversación natural, no en un cuestionario formal.

---

**3.2 — Refinamiento de "Horizonte temporal"**

3. Escribe el siguiente prompt:

```
Para la categoría "Horizonte temporal": agrega una pregunta que conecte el horizonte de inversión con los planes de Carlos para su empresa de logística. Por ejemplo, ¿planea vender el negocio en algún momento? ¿Piensa en retirarse? Mantén el tono conversacional.
```

4. Revisa que las preguntas nuevas vinculen el horizonte temporal con la realidad empresarial de Carlos.

---

**3.3 — Refinamiento de "Necesidades de liquidez"**

5. Escribe el siguiente prompt:

```
Las preguntas sobre "Necesidades de liquidez" asumen que Carlos entiende el concepto de liquidez. Reformúlalas sin usar la palabra "liquidez". En su lugar, pregunta sobre situaciones concretas: ¿necesitaría disponer del dinero rápidamente en algún escenario? ¿Su negocio tiene temporadas donde necesita más capital de trabajo? ¿Tiene compromisos financieros importantes en los próximos años?
```

6. Verifica que las preguntas reformuladas sean comprensibles sin conocimiento financiero previo.

---

**3.4 — Refinamiento de "Experiencia previa en inversiones"**

7. Escribe el siguiente prompt:

```
En la categoría "Experiencia previa en inversiones", evita preguntas que puedan hacer sentir a Carlos que debería saber más de lo que sabe. Reformula usando un enfoque positivo y exploratorio. Por ejemplo, en lugar de "¿Qué instrumentos financieros ha utilizado?", pregunta algo como "¿Ha tenido alguna experiencia invirtiendo su dinero fuera de su negocio, ya sea en bienes raíces, fondos de ahorro, o cualquier otra forma?" Genera 3 preguntas con este enfoque empático.
```

8. Confirma que el tono sea invitador y no evaluativo.

---

**3.5 — Refinamiento de "Tolerancia al riesgo"**

9. Escribe el siguiente prompt:

```
Las preguntas de "Tolerancia al riesgo" son demasiado técnicas. Reformúlalas usando analogías cotidianas y escenarios concretos que un empresario latinoamericano pueda entender fácilmente. Por ejemplo: "Imagine que invierte $100,000 dólares y en los primeros 6 meses el valor baja a $85,000. ¿Qué haría: esperaría a que se recupere, vendería para evitar más pérdidas, o invertiría más aprovechando el precio bajo?" Genera 3-4 preguntas con este estilo de escenarios reales.
```

10. Verifica que las preguntas usen números concretos, situaciones tangibles y opciones claras.

---

**Resultado esperado:**

Después de los cinco prompts de seguimiento, debes tener versiones mejoradas de las preguntas en cada categoría. Copilot habrá generado entre 3 y 5 preguntas refinadas por categoría. El lenguaje debe ser notablemente más accesible que en la versión inicial del Paso 1.

**Verificación:**

- [ ] Has enviado al menos un prompt de refinamiento por cada una de las cinco categorías (mínimo 5 prompts de seguimiento en total).
- [ ] Las preguntas refinadas evitan jerga financiera sin explicación.
- [ ] Las preguntas de tolerancia al riesgo incluyen al menos un escenario con números concretos o una analogía cotidiana.
- [ ] Las preguntas de liquidez no usan la palabra "liquidez" directamente.
- [ ] El tono general es conversacional, empático y no evaluativo.

---

### Paso 4 — Solicitud de categoría adicional: Expectativas y motivaciones

**Objetivo:** Ampliar el marco de descubrimiento con una sexta categoría que capture las expectativas de Carlos Mendoza respecto a CIBEST CAPITAL y sus motivaciones personales para invertir.

**Instrucciones:**

1. En Copilot Chat, escribe el siguiente prompt:

```
Agrega una sexta categoría llamada "Expectativas y motivaciones" con 3-4 preguntas que nos ayuden a entender:
- ¿Qué espera Carlos Mendoza de CIBEST CAPITAL como firma asesora?
- ¿Qué lo motivó a considerar invertir en Estados Unidos en este momento?
- ¿Qué experiencias previas (positivas o negativas) ha tenido con asesores financieros o instituciones bancarias?
- ¿Cómo se imagina una relación ideal con su asesor de inversiones?

Mantén el mismo tono conversacional y accesible de las preguntas anteriores.
```

2. Revisa las preguntas generadas. Deben ser abiertas y orientadas a construir confianza en la relación asesor-prospecto.

3. Si alguna pregunta es demasiado genérica, solicita una versión más específica:

```
La pregunta sobre expectativas es muy genérica. Hazla más específica al contexto de Carlos: un empresario mexicano que probablemente está acostumbrado a manejar sus finanzas personalmente y puede tener reservas sobre delegar decisiones financieras a una firma externa.
```

**Resultado esperado:**

Copilot generará 3–4 preguntas adicionales en la categoría "Expectativas y motivaciones". Estas preguntas deben abordar la relación de confianza, las motivaciones para invertir internacionalmente y las experiencias previas con servicios financieros.

Ejemplo de pregunta esperada:

> "Como empresario, usted está acostumbrado a tomar decisiones importantes sobre su negocio. ¿Cómo le gustaría que trabajáramos juntos en las decisiones de inversión? ¿Prefiere estar involucrado en cada decisión, o le gustaría que le presentemos opciones con nuestra recomendación?"

**Verificación:**

- [ ] Se generó la categoría "Expectativas y motivaciones" con al menos 3 preguntas.
- [ ] Las preguntas abordan la relación asesor-prospecto de forma respetuosa.
- [ ] Al menos una pregunta explora las motivaciones para invertir en Estados Unidos específicamente.

---

### Paso 5 — Consolidación del conjunto final de preguntas

**Objetivo:** Seleccionar las mejores 2–3 preguntas por categoría y organizar el conjunto final en un formato estructurado listo para integrarse en la ficha de preparación del lab 01-08-05.

**Instrucciones:**

1. Solicita a Copilot que consolide todas las preguntas refinadas en un formato limpio:

```
Ahora consolida las mejores preguntas de toda nuestra conversación. Selecciona las 2-3 preguntas más efectivas por cada una de las 6 categorías (las 5 originales más "Expectativas y motivaciones"). Presenta el resultado en el siguiente formato:

PREGUNTAS DE DESCUBRIMIENTO — CARLOS MENDOZA
Preparado por: [Nombre del asesor] | CIBEST CAPITAL
Fecha: [Fecha actual]

CATEGORÍA 1: OBJETIVOS DE INVERSIÓN
1. [Pregunta]
2. [Pregunta]
3. [Pregunta]

CATEGORÍA 2: HORIZONTE TEMPORAL
1. [Pregunta]
2. [Pregunta]

[...continuar con las 6 categorías...]

NOTAS PARA EL ASESOR:
- [Incluir 2-3 recomendaciones sobre cómo usar estas preguntas en la reunión]
```

2. Revisa el documento consolidado que genera Copilot. Verifica que:
   - El total de preguntas esté entre **12 y 18**.
   - No haya preguntas duplicadas o muy similares entre categorías.
   - El formato sea limpio y profesional.

3. Si necesitas ajustes finales, usa un prompt directo:

```
En la consolidación final:
- Elimina la pregunta 2 de "Horizonte temporal" porque es redundante con la pregunta 1.
- Agrega en "Notas para el asesor" una recomendación sobre comenzar la reunión con las preguntas de "Experiencia previa" para establecer rapport antes de entrar a temas más sensibles como tolerancia al riesgo.
```

4. **Copia el resultado final** de Copilot.

5. Guarda el contenido consolidado. Tienes dos opciones:

   **Opción A — Guardar como archivo de texto:**
   - Abre el **Bloc de notas** (Notepad) o cualquier editor de texto.
   - Pega el contenido consolidado.
   - Guarda el archivo como `Preguntas_Descubrimiento_CarlosMendoza.txt` en la ruta:
     ```
     OneDrive > Documentos > CIBEST_CAPITAL > Prospectos
     ```

   **Opción B — Guardar directamente en Word (recomendado):**
   - Abre **Microsoft Word**.
   - Crea un nuevo documento en blanco.
   - Pega el contenido consolidado.
   - Aplica formato básico: título en negrita, categorías como encabezados de nivel 2, preguntas como lista numerada.
   - Guarda el archivo como `Preguntas_Descubrimiento_CarlosMendoza.docx` en la ruta:
     ```
     OneDrive > Documentos > CIBEST_CAPITAL > Prospectos
     ```

> ⚠️ **Importante para la continuidad del curso:** Este archivo será un insumo directo para el lab 01-08-05, donde se creará la ficha de preparación completa (`Ficha_Preparacion_CarlosMendoza_CIBEST.docx`). Asegúrate de guardarlo en la ruta correcta de OneDrive.

**Resultado esperado:**

Un documento estructurado con 12–18 preguntas de descubrimiento distribuidas en 6 categorías, con notas para el asesor sobre el orden y enfoque recomendado para la reunión. El documento debe estar guardado en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.

Ejemplo de estructura final esperada:

```
PREGUNTAS DE DESCUBRIMIENTO — CARLOS MENDOZA
Preparado por: [Tu nombre] | CIBEST CAPITAL
Fecha: [Fecha del lab]

CATEGORÍA 1: OBJETIVOS DE INVERSIÓN (3 preguntas)
1. ¿Qué le gustaría lograr con estas inversiones en Estados Unidos? 
   ¿Busca hacer crecer su dinero, generar un ingreso adicional regular, 
   o principalmente proteger lo que ya tiene?
2. ¿Hay algún proyecto importante — personal, familiar o de negocio — 
   para el que estas inversiones podrían servir como respaldo?
3. Si pudiera describir el resultado ideal de trabajar con nosotros en 
   3-5 años, ¿cómo se vería?

CATEGORÍA 2: HORIZONTE TEMPORAL (2 preguntas)
1. ¿En cuánto tiempo imagina que podría necesitar usar el dinero que 
   invierta? ¿Estamos hablando de algo para los próximos 2-3 años, 
   o es dinero que no necesitaría tocar en 10 años o más?
2. ¿Tiene planes de vender o hacer cambios importantes en su empresa 
   de logística en los próximos años, o la ve como un proyecto de 
   largo plazo?

CATEGORÍA 3: NECESIDADES DE LIQUIDEZ (2 preguntas)
1. ¿Su negocio de logística tiene temporadas fuertes y temporadas 
   más lentas? ¿En las temporadas lentas necesita inyectar capital 
   de sus ahorros personales?
2. ¿Tiene compromisos financieros importantes en los próximos 2-3 
   años — por ejemplo, compra de equipo, educación de hijos, 
   propiedades — que requieran disponer de una cantidad significativa?

CATEGORÍA 4: EXPERIENCIA PREVIA EN INVERSIONES (3 preguntas)
1. ¿Ha tenido alguna experiencia invirtiendo su dinero fuera de su 
   negocio? Por ejemplo, bienes raíces, fondos de ahorro, o algún 
   otro tipo de inversión.
2. ¿Alguna vez ha trabajado con un asesor financiero o con un banco 
   para manejar sus inversiones? ¿Cómo fue esa experiencia?
3. ¿Hay algo sobre el mundo de las inversiones que le genere dudas 
   o curiosidad y que le gustaría que le expliquemos con claridad?

CATEGORÍA 5: TOLERANCIA AL RIESGO (3 preguntas)
1. Imagine que invierte $100,000 dólares y en los primeros 6 meses 
   el valor baja a $85,000. ¿Qué haría: esperaría a que se recupere, 
   vendería para evitar más pérdidas, o invertiría más aprovechando 
   el precio bajo?
2. En su negocio de logística, ¿cómo maneja las situaciones de 
   incertidumbre? ¿Prefiere ir a lo seguro o está dispuesto a tomar 
   riesgos calculados si la oportunidad es buena?
3. ¿Qué le preocuparía más: que sus inversiones no crezcan lo 
   suficiente, o que pierdan valor en algún momento aunque sea 
   temporal?

CATEGORÍA 6: EXPECTATIVAS Y MOTIVACIONES (3 preguntas)
1. ¿Qué lo motivó a considerar invertir en Estados Unidos en este 
   momento de su vida y de su negocio?
2. ¿Cómo le gustaría que trabajáramos juntos? ¿Prefiere estar 
   involucrado en cada decisión, o le gustaría que le presentemos 
   opciones con nuestra recomendación?
3. ¿Qué sería lo más importante para usted al elegir una firma como 
   CIBEST CAPITAL para manejar sus inversiones?

NOTAS PARA EL ASESOR:
- Comenzar con las preguntas de "Experiencia previa" para establecer 
  rapport y entender el punto de partida de Carlos sin presionarlo.
- Dejar "Tolerancia al riesgo" para la segunda mitad de la conversación, 
  cuando ya exista mayor confianza.
- Usar las respuestas de "Expectativas y motivaciones" para cerrar la 
  reunión reafirmando cómo CIBEST CAPITAL se alinea con lo que Carlos busca.
```

**Verificación:**

- [ ] El documento contiene exactamente 6 categorías.
- [ ] El total de preguntas está entre 12 y 18.
- [ ] No hay preguntas duplicadas entre categorías.
- [ ] Se incluye una sección de "Notas para el asesor" con al menos 2 recomendaciones.
- [ ] El archivo está guardado en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.

---

## 7. Validación y pruebas

Antes de dar por completado el laboratorio, realiza la siguiente lista de verificación integral:

### Lista de verificación final

| # | Criterio | Cumple |
|---|---|---|
| 1 | Se utilizó el prompt mejorado del lab 01-08-02 como base de contexto. | ☐ |
| 2 | Se generaron preguntas iniciales en las 5 categorías requeridas. | ☐ |
| 3 | Se realizó una evaluación crítica documentada (Paso 2) con al menos 3 hallazgos. | ☐ |
| 4 | Se enviaron al menos 5 prompts de seguimiento (uno por categoría) para refinamiento. | ☐ |
| 5 | Las preguntas refinadas usan lenguaje accesible sin jerga financiera sin explicar. | ☐ |
| 6 | Se agregó la categoría "Expectativas y motivaciones" con al menos 3 preguntas. | ☐ |
| 7 | El documento consolidado final tiene entre 12 y 18 preguntas en 6 categorías. | ☐ |
| 8 | Se incluyen "Notas para el asesor" con recomendaciones de uso. | ☐ |
| 9 | El archivo está guardado en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`. | ☐ |
| 10 | El contexto de Copilot Chat se mantiene abierto o documentado para uso en el lab 01-08-04. | ☐ |

### Prueba de calidad del lenguaje

Aplica la siguiente prueba rápida a 3 preguntas seleccionadas al azar de tu documento final:

> **Prueba del "empresario sin experiencia financiera":** Lee la pregunta en voz alta. ¿Un empresario de logística de 45-55 años, exitoso en su rubro pero sin formación financiera, entendería esta pregunta sin necesidad de aclaraciones? Si la respuesta es "no" o "tal vez", la pregunta necesita simplificación adicional.

---

## 8. Solución de problemas

### Problema 1: Copilot genera preguntas en inglés o mezcla idiomas

**Síntomas:** Algunas preguntas aparecen en inglés, o Copilot usa términos financieros en inglés sin traducción (por ejemplo, "asset allocation", "risk tolerance", "portfolio diversification") a pesar de que el prompt está en español.

**Causa:** Copilot puede recurrir a terminología en inglés cuando su base de conocimiento financiero tiene mayor densidad de contenido en ese idioma, especialmente en el modo Trabajo donde accede a documentación organizacional que podría estar en inglés.

**Solución:**

1. Agrega una instrucción explícita de idioma en tu prompt de seguimiento:

```
Todas las preguntas deben estar completamente en español. No uses términos en inglés. Si un concepto financiero se conoce comúnmente en inglés (como "portfolio"), usa su equivalente en español ("portafolio" o "conjunto de inversiones") o explícalo con palabras sencillas. Reformula las preguntas que tengan términos en inglés.
```

2. Si el problema persiste, inicia una nueva conversación y establece el idioma desde el primer mensaje:

```
Esta conversación será completamente en español. Todos los términos, conceptos y preguntas deben estar en español con lenguaje accesible para un público latinoamericano.
```

---

### Problema 2: Copilot pierde el contexto y genera preguntas genéricas no relacionadas con Carlos Mendoza

**Síntomas:** Las preguntas generadas son genéricas (por ejemplo, "¿Cuáles son sus objetivos financieros?") y no hacen referencia al perfil específico de Carlos Mendoza, su empresa de logística, su ubicación en México o su interés en inversiones en Estados Unidos.

**Causa:** Si la conversación es muy larga o si se inició una nueva sesión sin restablecer el contexto, Copilot puede perder la especificidad del perfil del prospecto. Esto también puede ocurrir si el modo cambió inadvertidamente de "Trabajo" a "Web".

**Solución:**

1. Verifica que el modo de Copilot Chat esté en **Trabajo** (no en "Web"). El selector se encuentra en la parte superior de la interfaz.

2. Restablece el contexto con un prompt explícito que incluya todos los datos relevantes:

```
Recuerda el contexto específico: estamos preparando preguntas para Carlos Mendoza, propietario de una empresa de logística en México con ingresos anuales de USD 5 millones, interesado en diversificar su patrimonio invirtiendo en activos en Estados Unidos, con experiencia limitada en inversiones internacionales. La firma asesora es CIBEST CAPITAL. Todas las preguntas deben ser específicas para este perfil, mencionando su negocio de logística, su contexto mexicano y su situación particular. Regenera las preguntas de la categoría [CATEGORÍA AFECTADA] con esta especificidad.
```

3. Si el problema persiste después de restablecer el contexto, inicia una nueva conversación e incluye el prompt mejorado del lab 01-08-02 completo como primer mensaje antes de solicitar las preguntas.

---

## 9. Limpieza

Este laboratorio no requiere limpieza de recursos técnicos significativos. Sin embargo, realiza las siguientes acciones de cierre:

1. **No cierres la sesión de Copilot Chat.** El contexto acumulado en esta conversación será utilizado como insumo para el lab 01-08-04 (investigación del sector logístico). Si necesitas cerrar el navegador, asegúrate de que el historial de conversaciones de Copilot Chat esté habilitado en tu cuenta organizacional para poder retomar la sesión.

2. **Verifica el archivo guardado.** Navega a `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos` y confirma que el archivo `Preguntas_Descubrimiento_CarlosMendoza.docx` (o `.txt`) esté presente y accesible.

3. **Opcional — Limpieza de archivos temporales.** Si creaste notas temporales durante el Paso 2 (evaluación crítica) en el Bloc de notas u otro editor, puedes eliminarlas o conservarlas como referencia personal. No son necesarias para labs posteriores.

---

## 10. Resumen

En este laboratorio aplicaste un flujo de trabajo de prompting iterativo con Microsoft 365 Copilot Chat para generar, evaluar y refinar preguntas de descubrimiento financiero adaptadas al perfil específico de Carlos Mendoza. Los logros clave de esta sesión fueron:

- **Generación estructurada:** Obtuviste preguntas organizadas en cinco categorías estándar de perfilamiento financiero más una categoría adicional de expectativas y motivaciones.
- **Evaluación crítica:** Identificaste problemas de tecnicismo, tono y vacíos en la primera generación de Copilot, demostrando que la IA requiere supervisión humana para producir resultados óptimos.
- **Refinamiento dirigido:** Utilizaste prompts de seguimiento específicos por categoría para transformar preguntas técnicas en conversaciones accesibles, incorporando analogías, escenarios concretos y sensibilidad cultural.
- **Consolidación profesional:** Organizaste un documento final de 12–18 preguntas listo para integrarse en la ficha de preparación de la reunión.

### Conexión con los próximos laboratorios

| Lab siguiente | Cómo se conecta |
|---|---|
| **Lab 01-08-04** | El contexto de Copilot Chat acumulado en este lab se utilizará para investigar el sector logístico latinoamericano, complementando el perfil de Carlos Mendoza con información sectorial. |
| **Lab 01-08-05** | El documento de preguntas de descubrimiento será un componente central de la ficha de preparación `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` que se creará en Microsoft Word con Copilot. |

### Recursos adicionales

- [Guía de prompts efectivos para Microsoft 365 Copilot](https://support.microsoft.com/es-es/topic/crear-prompts-eficaces-para-microsoft-365-copilot-1d9a4d6f-7e8d-4e4a-b4f3-3a6e3e4e4e4e)
- [Microsoft 365 Copilot Chat — Documentación oficial](https://learn.microsoft.com/es-es/copilot/microsoft-365/microsoft-365-copilot-overview)
- [Mejores prácticas para descubrimiento de clientes en asesoría financiera — CFA Institute](https://www.cfainstitute.org/)

---

---

# Práctica guiada en Microsoft 365 Copilot Chat con búsqueda web: investigación del sector logístico latinoamericano, revisión de fuentes y selección de contexto relevante

## Metadatos del laboratorio

| Campo | Detalle |
|---|---|
| **Duración** | 15 minutos |
| **Complejidad** | Media |
| **Nivel de Bloom** | Analizar (*Analyze*) |
| **Lab anterior** | 01-08-03 |
| **Lab siguiente** | 01-08-05 |
| **Artefacto de salida** | Resumen estructurado de investigación sectorial (3-5 hallazgos con fuentes evaluadas) |

---

## Descripción general

En este laboratorio utilizarás **Microsoft 365 Copilot Chat** con su capacidad de **búsqueda web** para investigar las tendencias actuales del sector logístico en América Latina. A diferencia de los labs anteriores donde trabajaste con prompts de redacción y descubrimiento, aquí el foco está en el **análisis crítico**: evaluarás la calidad, relevancia y credibilidad de las fuentes que Copilot cita en sus respuestas, y seleccionarás los datos más pertinentes para contextualizar la reunión con el prospecto **Carlos Mendoza**. El resumen que produzcas en este lab se convertirá en el componente de "contexto público del sector" que integrarás directamente en la ficha de preparación del lab 01-08-05.

---

## Objetivos de aprendizaje

Al completar este laboratorio, serás capaz de:

- [ ] **Activar y verificar** la capacidad de búsqueda web en Microsoft 365 Copilot Chat, distinguiendo entre el modo "Trabajo" y el modo con acceso web.
- [ ] **Investigar** tendencias económicas, tecnológicas y regulatorias del sector logístico latinoamericano mediante prompts estructurados con solicitud explícita de fuentes.
- [ ] **Evaluar críticamente** las fuentes citadas por Copilot utilizando criterios de relevancia, actualidad, credibilidad y pertinencia para el perfil del prospecto.
- [ ] **Seleccionar y documentar** los 3-5 hallazgos más relevantes del sector en un formato estructurado que conecte cada dato con su aplicabilidad a la reunión con Carlos Mendoza.

---

## Prerrequisitos

### Conocimientos previos

| Requisito | Detalle |
|---|---|
| Labs anteriores completados | Labs 01-08-02 (prompts mejorados) y 01-08-03 (preguntas de descubrimiento) |
| Perfil del prospecto | Conocimiento del perfil de Carlos Mendoza: propietario de empresa de logística en México, ingresos anuales ~USD 5M, interés en diversificar patrimonio en EE.UU., experiencia limitada en inversiones internacionales |
| Evaluación de fuentes | Comprensión básica de criterios para evaluar credibilidad de fuentes en línea (autoría, fecha, tipo de publicación, sesgo potencial) |
| Lecciones teóricas | Haber completado las lecciones 1.1 a 1.7 del capítulo |

### Acceso y licencias

| Requisito | Detalle |
|---|---|
| Cuenta Microsoft 365 | Cuenta organizacional con licencia **Copilot M365 Premium** activa |
| Búsqueda web en Copilot | Habilitada en el tenant organizacional (verificar con el instructor) |
| Navegador | Microsoft Edge 124.0.2478.97 o superior |
| Conectividad | Conexión a internet estable (mínimo 10 Mbps) |

---

## Entorno del laboratorio

### Hardware requerido

| Componente | Mínimo | Recomendado |
|---|---|---|
| Procesador | 64 bits (Intel Core i5 / AMD Ryzen 5) | Intel Core i7 / AMD Ryzen 7 |
| RAM | 8 GB | 16 GB |
| Pantalla | 1366×768 | 1920×1080 |
| Espacio en disco | 10 GB libres | 15 GB libres |
| Periféricos | Teclado y ratón/trackpad | Teclado y ratón/trackpad |
| Internet | 10 Mbps bajada | 25 Mbps bajada |

### Software requerido

| Software | Versión | Notas |
|---|---|---|
| Windows | Windows 10 22H2 (Build 19045) o Windows 11 23H2 (Build 22631)+ | Sistema operativo base |
| Microsoft Edge | 124.0.2478.97 o superior | Navegador principal para acceder a Copilot Chat |
| Microsoft 365 Copilot Chat | Servicio en la nube (copilot.microsoft.com) | Actualización automática; verificar acceso previo al lab |
| Microsoft 365 Apps | Versión 2405 (Build 17628.20164)+ | Para verificación de licencia |

### Configuración inicial del directorio de trabajo

Antes de iniciar, verifica que exista la estructura de carpetas en OneDrive donde guardarás el artefacto de salida de este lab:

1. Abre el **Explorador de archivos** de Windows.
2. Navega a tu carpeta de **OneDrive** sincronizada.
3. Verifica que exista la ruta: `Documentos > CIBEST_CAPITAL > Prospectos`.
4. Si no existe, créala manualmente:
   - Dentro de `Documentos`, crea la carpeta `CIBEST_CAPITAL`.
   - Dentro de `CIBEST_CAPITAL`, crea la subcarpeta `Prospectos`.

> 📁 **Directorio de trabajo**: `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`
> Todos los archivos de este lab y los labs subsecuentes se guardarán en esta ruta.

---

## Instrucciones paso a paso

### Paso 1: Verificar la configuración de búsqueda web en Copilot Chat

**Objetivo**: Confirmar que Microsoft 365 Copilot Chat tiene habilitada la capacidad de búsqueda web, lo cual es indispensable para obtener información actualizada del sector logístico.

**Instrucciones**:

1. Abre **Microsoft Edge** en tu equipo.

2. Navega a la dirección:
   ```
   https://copilot.microsoft.com
   ```

3. Inicia sesión con tu **cuenta organizacional de Microsoft 365** (la misma que tiene la licencia Copilot M365 Premium).

4. Una vez dentro de la interfaz de Copilot Chat, localiza el **selector de modo** en la parte superior del área de conversación. Dependiendo de la configuración de tu tenant, verás una de estas opciones:

   - **Selector "Trabajo" / "Web"**: Si ves un toggle o selector que permite alternar entre modo "Trabajo" (Work) y modo "Web", selecciona el modo **"Web"** para este lab.
   - **Toggle de búsqueda web (ícono de globo terráqueo 🌐)**: Si ves un ícono de globo o un toggle etiquetado como "Buscar en la web" / "Search the web" junto al campo de entrada de texto, asegúrate de que esté **activado** (encendido).
   - **Modo combinado**: En algunos tenants, Copilot Chat permite búsqueda web por defecto sin necesidad de toggle. En este caso, verifica que al escribir una pregunta sobre eventos recientes, Copilot incluya referencias web en su respuesta.

5. Para **verificar** que la búsqueda web está activa, escribe el siguiente prompt de prueba en el campo de chat:

   ```
   ¿Cuál es la noticia más reciente sobre comercio internacional en América Latina?
   ```

6. Observa la respuesta de Copilot. **Confirma** que:
   - La respuesta menciona eventos o datos de **2024 o 2025**.
   - Aparecen **referencias o citas numeradas** (por ejemplo, [1], [2]) con enlaces a fuentes web.
   - Al hacer clic en las referencias, se abren páginas web reales con contenido verificable.

**Resultado esperado**: La interfaz de Copilot Chat muestra una respuesta con datos recientes y citas a fuentes web verificables. El modo de búsqueda web está confirmado como activo.

**Verificación**:

| Criterio | ✅ Cumple | ❌ No cumple |
|---|---|---|
| Copilot Chat cargó correctamente en copilot.microsoft.com | | |
| Se identificó y activó el modo con búsqueda web | | |
| La respuesta de prueba incluye datos de 2024-2025 | | |
| La respuesta contiene citas con enlaces a fuentes web | | |

> ⚠️ **IMPORTANTE**: Si la búsqueda web no está disponible en tu tenant, consulta inmediatamente con el instructor. Este lab **no puede completarse** sin acceso a búsqueda web, ya que el objetivo es investigar información pública actualizada del sector.

> 💡 **Nota para el instructor**: La disponibilidad de búsqueda web en Copilot Chat depende de la configuración del administrador del tenant. Si está deshabilitada a nivel organizacional, considere usar la versión de Copilot accesible desde Edge (barra lateral de Copilot en Edge) como alternativa, asegurándose de que el estudiante esté autenticado con su cuenta M365.

---

### Paso 2: Investigación inicial del sector logístico latinoamericano

**Objetivo**: Obtener un panorama amplio de las tendencias actuales del sector logístico en América Latina mediante un prompt estructurado que solicite explícitamente fuentes citadas.

**Instrucciones**:

1. En la misma sesión de Copilot Chat (con búsqueda web activa), **inicia una nueva conversación** haciendo clic en el botón de "Nuevo chat" o "New chat" si está disponible. Esto asegura un contexto limpio para la investigación.

2. Copia y envía el siguiente prompt **exactamente como aparece** (puedes ajustar el año si es necesario según la fecha actual):

   ```
   Busca en la web información actualizada sobre las principales tendencias del sector logístico en América Latina en 2024-2025. Incluye factores económicos, tecnológicos y regulatorios relevantes. Cita las fuentes específicas de cada dato.
   ```

3. **Espera** a que Copilot genere la respuesta completa. No interrumpas la generación.

4. **Lee la respuesta completa** antes de tomar cualquier acción. Identifica:
   - ¿Cuántas tendencias o temas principales menciona Copilot?
   - ¿Cuántas fuentes cita en total?
   - ¿La respuesta cubre las tres dimensiones solicitadas (económica, tecnológica, regulatoria)?

5. **Copia la respuesta completa** de Copilot. Para hacerlo:
   - Haz clic en el ícono de **copiar** (📋) que aparece debajo de la respuesta de Copilot, o
   - Selecciona todo el texto de la respuesta manualmente y usa `Ctrl + C`.

6. **Pega la respuesta** en un archivo de texto temporal para referencia. Puedes usar:
   - Un archivo de **Bloc de notas** (Notepad) guardado como `Investigacion_Sector_Logistico_Borrador.txt` en la ruta `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`, o
   - Un documento nuevo de **Word** si prefieres formato enriquecido.

**Resultado esperado**: Copilot genera una respuesta de entre 300 y 600 palabras que cubre múltiples tendencias del sector logístico latinoamericano, organizada por categorías (económicas, tecnológicas, regulatorias) e incluye entre 4 y 10 fuentes citadas con enlaces. Los temas típicos que pueden aparecer incluyen:

- Crecimiento del comercio electrónico y su impacto en la logística de última milla
- Digitalización y automatización de cadenas de suministro
- Nearshoring y reconfiguración de cadenas de suministro hacia México y América Latina
- Inversión en infraestructura logística (puertos, carreteras, centros de distribución)
- Regulaciones ambientales y sostenibilidad en transporte de carga
- Impacto de la inflación y tipos de cambio en costos logísticos
- Adopción de tecnologías como IoT, blockchain o inteligencia artificial en logística

**Verificación**:

| Criterio | ✅ Cumple | ❌ No cumple |
|---|---|---|
| La respuesta cubre factores económicos del sector | | |
| La respuesta cubre factores tecnológicos del sector | | |
| La respuesta cubre factores regulatorios del sector | | |
| Se incluyen al menos 4 fuentes citadas con enlaces | | |
| La información es de 2024-2025 (no datos obsoletos) | | |
| La respuesta se guardó en el archivo temporal de borrador | | |

> 💡 **Consejo**: Si la respuesta de Copilot es demasiado general o no incluye fuentes específicas, envía un prompt de seguimiento como: *"Necesito que cada dato esté respaldado por una fuente específica con nombre de la publicación y fecha. Por favor amplía la respuesta con fuentes verificables."*

---

### Paso 3: Revisión crítica de fuentes citadas

**Objetivo**: Evaluar sistemáticamente la calidad y confiabilidad de cada fuente citada por Copilot, aplicando criterios de credibilidad, actualidad y relevancia para el caso de Carlos Mendoza.

**Instrucciones**:

1. Revisa la respuesta de Copilot guardada en el Paso 2. Identifica **cada fuente citada** (generalmente indicadas con números entre corchetes como [1], [2], etc., o con nombres de publicaciones).

2. **Abre un nuevo documento de Word** para crear tu tabla de evaluación de fuentes:
   - Abre **Microsoft Word** (versión de escritorio o web).
   - Crea un nuevo documento en blanco.
   - Guárdalo inmediatamente con el nombre `Evaluacion_Fuentes_Sector_Logistico.docx` en la ruta: `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.

3. En el documento, escribe el siguiente encabezado:

   ```
   EVALUACIÓN CRÍTICA DE FUENTES — Investigación Sector Logístico LATAM
   Lab 01-08-04 | CIBEST CAPITAL | Prospecto: Carlos Mendoza
   Fecha: [Insertar fecha actual]
   ```

4. Crea una **tabla de evaluación** con las siguientes columnas. Inserta una tabla en Word (`Insertar > Tabla`) con **7 columnas** y tantas filas como fuentes haya citado Copilot (más una fila de encabezados):

   | # | Dato / Tendencia | Fuente citada | URL (si disponible) | Fecha de publicación | Relevancia para Carlos Mendoza (Alta / Media / Baja) | ¿Fuente confiable? (Sí / No / Dudosa) |
   |---|---|---|---|---|---|---|
   | 1 | | | | | | |
   | 2 | | | | | | |
   | 3 | | | | | | |
   | ... | | | | | | |

5. **Completa la tabla** siguiendo este proceso para **cada fuente citada** por Copilot:

   **a) Identificar el dato y la fuente:**
   - En la columna "Dato / Tendencia", escribe el hallazgo o tendencia específica que Copilot atribuye a esa fuente.
   - En la columna "Fuente citada", escribe el nombre de la publicación, organismo o medio de comunicación.

   **b) Verificar la URL:**
   - Haz clic en el enlace proporcionado por Copilot (si está disponible).
   - Si el enlace funciona, cópialo en la columna "URL".
   - Si el enlace está roto o no existe, anota "Enlace no funcional" o "No proporcionada".

   **c) Verificar la fecha:**
   - En la página de la fuente, localiza la fecha de publicación.
   - Anótala en formato DD/MM/AAAA en la columna correspondiente.
   - Si no encuentras fecha, anota "Fecha no disponible".

   **d) Evaluar la relevancia para Carlos Mendoza:**
   Utiliza los siguientes criterios para asignar la relevancia:

   - **Alta**: El dato se relaciona directamente con empresas de logística medianas en México, con decisiones de inversión o diversificación patrimonial, o con factores que afectan directamente la rentabilidad del sector logístico mexicano.
   - **Media**: El dato es sobre el sector logístico latinoamericano en general pero no es específico de México, o se relaciona indirectamente con las motivaciones de inversión del prospecto.
   - **Baja**: El dato es sobre logística pero en un contexto geográfico o de escala muy diferente al de Carlos Mendoza, o es demasiado técnico/especializado para ser útil en una conversación de asesoría de inversiones.

   **e) Evaluar la confiabilidad de la fuente:**
   Utiliza estos criterios:

   - **Sí (confiable)**: Fuente de organismo internacional reconocido (BID, Banco Mundial, CEPAL), medio de comunicación de reputación establecida (Reuters, Bloomberg, El Economista), publicación académica o reporte de firma de consultoría reconocida (McKinsey, Deloitte, PwC).
   - **No (no confiable)**: Blog personal sin autoría verificable, sitio web de origen desconocido, contenido que parece generado por IA sin edición humana, fuente con sesgo comercial evidente sin transparencia.
   - **Dudosa**: Fuente que podría ser legítima pero no se puede verificar completamente, o medio de comunicación poco conocido cuya reputación no es clara.

6. Una vez completada la tabla, **guarda el documento** (`Ctrl + S`).

**Resultado esperado**: Una tabla completa con entre 4 y 10 filas (según las fuentes citadas por Copilot), donde cada fuente tiene una evaluación documentada de relevancia y confiabilidad. Es normal que algunas fuentes resulten "Dudosas" o con "Enlace no funcional" — esto es parte del ejercicio de pensamiento crítico.

**Verificación**:

| Criterio | ✅ Cumple | ❌ No cumple |
|---|---|---|
| Se creó el archivo `Evaluacion_Fuentes_Sector_Logistico.docx` | | |
| El archivo está guardado en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos` | | |
| La tabla contiene al menos 4 fuentes evaluadas | | |
| Cada fuente tiene evaluación de relevancia (Alta/Media/Baja) | | |
| Cada fuente tiene evaluación de confiabilidad (Sí/No/Dudosa) | | |
| Se verificaron los enlaces haciendo clic en ellos | | |

> ⚠️ **ALERTA DE PENSAMIENTO CRÍTICO**: Es común que Copilot cite fuentes que parecen legítimas pero cuyos enlaces no funcionan, o que atribuya datos a fuentes que en realidad no contienen esa información específica. Esto se conoce como "alucinación de fuentes" y es una limitación conocida de los modelos de lenguaje. **No asumas que una fuente es válida solo porque Copilot la menciona.** Siempre verifica haciendo clic en el enlace y confirmando que el dato citado realmente aparece en la fuente.

---

### Paso 4: Profundización en temas relevantes

**Objetivo**: Realizar prompts de seguimiento sobre los 2-3 temas de mayor relevancia identificados en los pasos anteriores, buscando datos cuantitativos y análisis más específicos para el contexto mexicano.

**Instrucciones**:

1. Regresa a la sesión de **Copilot Chat** en tu navegador (la misma conversación del Paso 2, para mantener el contexto).

2. Revisa tu tabla de evaluación del Paso 3. Identifica los **2-3 temas** que marcaste con relevancia **"Alta"** para Carlos Mendoza.

3. Para **cada tema de alta relevancia**, envía un prompt de profundización. A continuación se proporcionan tres plantillas de prompt según los temas más comunes. **Usa las que correspondan a tus hallazgos** y adapta según sea necesario:

   **Prompt de profundización A — Digitalización y rentabilidad** (usar si identificaste tendencias de digitalización/tecnología):

   ```
   Profundiza en cómo la digitalización de la cadena de suministro en México está afectando la rentabilidad de empresas medianas de logística con ingresos entre 3 y 10 millones de dólares anuales. Incluye datos cuantitativos si están disponibles y cita las fuentes.
   ```

   **Prompt de profundización B — Nearshoring y oportunidades** (usar si identificaste tendencias de nearshoring/relocalización):

   ```
   Busca información actualizada sobre cómo el nearshoring hacia México está impactando al sector logístico mexicano en 2024-2025. ¿Qué oportunidades y riesgos representa para empresarios logísticos medianos? Incluye datos cuantitativos y fuentes específicas.
   ```

   **Prompt de profundización C — Contexto macroeconómico México** (usar si identificaste factores económicos o regulatorios):

   ```
   ¿Cuáles son los principales factores macroeconómicos en México en 2024-2025 que podrían motivar a un empresario mexicano del sector logístico a buscar diversificación de su patrimonio en inversiones fuera de México? Considera tipo de cambio, inflación, política fiscal y estabilidad regulatoria. Cita fuentes actualizadas.
   ```

4. **Envía al menos 2 de los 3 prompts** anteriores (los que correspondan a tus hallazgos de alta relevancia). Espera la respuesta completa de cada uno antes de enviar el siguiente.

5. Para cada respuesta de profundización:
   - **Lee la respuesta completa**.
   - **Identifica datos cuantitativos** específicos (porcentajes, cifras en dólares, tasas de crecimiento, etc.).
   - **Anota mentalmente** qué datos serían más impactantes para mencionar en una conversación con Carlos Mendoza.
   - **Copia las respuestas** y pégalas en tu archivo temporal de borrador (el mismo del Paso 2).

6. Si alguna respuesta de profundización carece de datos cuantitativos, envía un prompt adicional de refinamiento:

   ```
   La información anterior es útil pero necesito datos cuantitativos más específicos. ¿Puedes buscar estadísticas, porcentajes de crecimiento o cifras de inversión del sector logístico mexicano publicadas por fuentes como INEGI, la Secretaría de Economía de México, el BID o firmas de consultoría reconocidas?
   ```

**Resultado esperado**: Obtienes 2-3 respuestas adicionales de Copilot con información más detallada y específica sobre los temas de mayor relevancia. Las respuestas idealmente incluyen:

- Datos cuantitativos (ej: "el sector logístico en México creció X% en 2024", "la inversión en nearshoring alcanzó USD X mil millones")
- Contexto específico de México (no solo de América Latina en general)
- Fuentes adicionales que complementan las del Paso 2
- Conexiones implícitas o explícitas con motivaciones de diversificación patrimonial

**Verificación**:

| Criterio | ✅ Cumple | ❌ No cumple |
|---|---|---|
| Se enviaron al menos 2 prompts de profundización | | |
| Las respuestas contienen datos más específicos que la investigación inicial | | |
| Se obtuvieron datos cuantitativos en al menos una respuesta | | |
| Las respuestas se copiaron al archivo temporal de borrador | | |
| Se identificaron fuentes adicionales en las respuestas de profundización | | |

---

### Paso 5: Conexión con el perfil del prospecto

**Objetivo**: Utilizar Copilot para generar un análisis que conecte explícitamente las tendencias del sector logístico investigadas con las posibles motivaciones de Carlos Mendoza para diversificar su patrimonio en inversiones en Estados Unidos.

**Instrucciones**:

1. En la **misma conversación** de Copilot Chat (para aprovechar todo el contexto acumulado), envía el siguiente prompt:

   ```
   Con base en las tendencias del sector logístico latinoamericano que hemos investigado, ¿qué factores podrían estar motivando a un empresario de logística mexicano con ingresos anuales de aproximadamente 5 millones de dólares a diversificar su patrimonio en inversiones en EE.UU. en este momento? Organiza tu respuesta en: (1) factores de empuje desde México, (2) factores de atracción hacia EE.UU., y (3) riesgos que este empresario debería considerar. Cita fuentes cuando sea posible.
   ```

2. **Lee la respuesta completa** de Copilot. Esta respuesta es particularmente valiosa porque sintetiza toda la investigación previa y la conecta directamente con el perfil de Carlos Mendoza.

3. **Evalúa la calidad de la respuesta** considerando:
   - ¿Los "factores de empuje" son realistas para un empresario logístico mexicano? (ej: volatilidad del peso, incertidumbre regulatoria, concentración de patrimonio en un solo sector)
   - ¿Los "factores de atracción" hacia EE.UU. son relevantes para alguien con experiencia limitada en inversiones internacionales? (ej: estabilidad del dólar, diversificación geográfica, acceso a mercados de capital más profundos)
   - ¿Los "riesgos" mencionados son realistas y útiles para la conversación de asesoría? (ej: diferencias fiscales, barreras de idioma/cultura, complejidad regulatoria en EE.UU.)

4. Si la respuesta es demasiado genérica o no refleja adecuadamente el perfil de Carlos Mendoza, envía un prompt de refinamiento:

   ```
   Hazlo más específico para un empresario que: (a) tiene su empresa de logística como principal activo patrimonial, (b) opera en el mercado doméstico mexicano, (c) no tiene experiencia previa en inversiones internacionales, y (d) podría estar considerando esto por primera vez. ¿Qué preocupaciones típicas tendría alguien en esta situación?
   ```

5. **Copia la respuesta final** (la original o la refinada) y pégala en tu archivo temporal de borrador.

**Resultado esperado**: Una respuesta estructurada en tres secciones (factores de empuje, factores de atracción, riesgos) que conecta la investigación sectorial con el perfil específico de Carlos Mendoza. La respuesta debe ser lo suficientemente concreta como para que un asesor de inversiones pueda usarla como contexto en una conversación real.

**Verificación**:

| Criterio | ✅ Cumple | ❌ No cumple |
|---|---|---|
| La respuesta identifica factores de empuje desde México | | |
| La respuesta identifica factores de atracción hacia EE.UU. | | |
| La respuesta menciona riesgos relevantes | | |
| El análisis es específico para el perfil de Carlos Mendoza (no genérico) | | |
| La respuesta se copió al archivo temporal de borrador | | |

---

### Paso 6: Selección y documentación del resumen estructurado final

**Objetivo**: Sintetizar toda la investigación realizada en los pasos anteriores en un resumen estructurado de 3-5 hallazgos clave, documentado en un formato listo para integrarse en la ficha de preparación del lab 01-08-05.

**Instrucciones**:

1. Abre el documento `Evaluacion_Fuentes_Sector_Logistico.docx` que creaste en el Paso 3.

2. **Debajo de la tabla de evaluación de fuentes**, agrega una nueva sección con el siguiente encabezado:

   ```
   RESUMEN DE INVESTIGACIÓN SECTORIAL — CONTEXTO PÚBLICO
   Para integración en Ficha de Preparación: Ficha_Preparacion_CarlosMendoza_CIBEST.docx
   ```

3. Revisa **todo el material recopilado**: la respuesta inicial del Paso 2, las profundizaciones del Paso 4, el análisis de conexión del Paso 5 y tu tabla de evaluación de fuentes del Paso 3.

4. **Selecciona los 3-5 hallazgos más relevantes** utilizando los siguientes criterios de selección (todos deben cumplirse):

   - ✅ Relevancia marcada como **"Alta"** en tu tabla de evaluación
   - ✅ Fuente evaluada como **"Sí" (confiable)** o al menos **"Dudosa"** (nunca "No")
   - ✅ Dato de **2024-2025** (no información obsoleta)
   - ✅ Directamente **útil en una conversación** con Carlos Mendoza (no demasiado técnico ni abstracto)
   - ✅ Aporta **contexto que demuestre conocimiento del sector** del prospecto por parte del asesor de CIBEST CAPITAL

5. Para cada hallazgo seleccionado, documéntalo en el siguiente formato. Crea una **tabla de resumen** en Word con 4 columnas:

   | # | Hallazgo / Tendencia clave | Fuente y fecha | Relevancia para la reunión con Carlos Mendoza |
   |---|---|---|---|
   | 1 | [Descripción concisa del hallazgo en 1-2 oraciones] | [Nombre de la fuente, fecha de publicación] | [Explicación breve de por qué este dato es relevante para la conversación con el prospecto] |
   | 2 | | | |
   | 3 | | | |
   | 4 | | | |
   | 5 | | | |

   **Ejemplo de fila completada** (referencia — tus datos serán diferentes según los resultados de tu investigación):

   | # | Hallazgo / Tendencia clave | Fuente y fecha | Relevancia para la reunión con Carlos Mendoza |
   |---|---|---|---|
   | 1 | El nearshoring hacia México ha generado un incremento del X% en la demanda de servicios logísticos en corredores industriales del norte del país durante 2024. | [Nombre de publicación], [mes/año] | Demuestra que el sector de Carlos Mendoza está en crecimiento, lo cual valida su capacidad de generar excedentes para invertir y contextualiza su interés en diversificación. |

6. Debajo de la tabla de resumen, agrega un párrafo breve titulado **"Conexión estratégica"** donde escribas en 3-4 oraciones cómo estos hallazgos en conjunto te ayudarán a contextualizar la reunión con Carlos Mendoza. Este párrafo debe responder: *¿Por qué un empresario logístico mexicano como Carlos Mendoza estaría considerando diversificar su patrimonio en inversiones en EE.UU. en este momento?*

   Ejemplo de estructura:

   ```
   Conexión estratégica:
   Los hallazgos de esta investigación sugieren que [resumen de la situación del sector]. 
   Para Carlos Mendoza, esto implica que [conexión con su situación específica]. 
   En la reunión, estos datos nos permitirán [cómo se usarán en la conversación].
   ```

7. **Guarda el documento final** (`Ctrl + S`). Verifica que el nombre del archivo sea `Evaluacion_Fuentes_Sector_Logistico.docx` y que esté en la ruta `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.

8. **Cierra la conversación de Copilot Chat** o déjala abierta si deseas consultarla durante el siguiente lab. No es necesario guardar la conversación de chat ya que el contenido relevante ya fue documentado en tu archivo de Word.

**Resultado esperado**: El documento `Evaluacion_Fuentes_Sector_Logistico.docx` contiene:
- La tabla de evaluación de fuentes (del Paso 3) con todas las fuentes evaluadas.
- La tabla de resumen con 3-5 hallazgos seleccionados, cada uno con fuente y justificación de relevancia.
- Un párrafo de "Conexión estratégica" que sintetiza la aplicabilidad de la investigación.

**Verificación**:

| Criterio | ✅ Cumple | ❌ No cumple |
|---|---|---|
| La tabla de resumen contiene entre 3 y 5 hallazgos | | |
| Cada hallazgo tiene fuente y fecha identificadas | | |
| Cada hallazgo tiene justificación de relevancia para Carlos Mendoza | | |
| Todos los hallazgos seleccionados provienen de fuentes evaluadas como confiables o dudosas (nunca "No confiable") | | |
| Se incluyó el párrafo de "Conexión estratégica" | | |
| El documento está guardado en la ruta correcta de OneDrive | | |

---

## Validación y pruebas

Antes de considerar este lab como completado, realiza la siguiente validación integral:

### Lista de verificación final

| # | Elemento | Estado |
|---|---|---|
| 1 | Búsqueda web verificada como activa en Copilot Chat | ☐ |
| 2 | Investigación inicial completada con al menos 4 fuentes citadas | ☐ |
| 3 | Tabla de evaluación de fuentes completada con criterios de relevancia y confiabilidad | ☐ |
| 4 | Al menos 2 prompts de profundización enviados y respuestas obtenidas | ☐ |
| 5 | Análisis de conexión con perfil de Carlos Mendoza generado | ☐ |
| 6 | Resumen final con 3-5 hallazgos documentados en formato estructurado | ☐ |
| 7 | Párrafo de "Conexión estratégica" redactado | ☐ |
| 8 | Archivo `Evaluacion_Fuentes_Sector_Logistico.docx` guardado en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos` | ☐ |

### Criterio de calidad del artefacto

Tu resumen de investigación sectorial es de **alta calidad** si cumple con estos estándares:

- **Especificidad**: Los hallazgos contienen datos concretos (cifras, porcentajes, nombres de tendencias) en lugar de afirmaciones vagas.
- **Verificabilidad**: Cada hallazgo está respaldado por una fuente que fue verificada como accesible y confiable.
- **Relevancia**: Cada hallazgo tiene una conexión clara y articulada con el perfil y la situación de Carlos Mendoza.
- **Actualidad**: Todos los datos son de 2024-2025.
- **Utilidad conversacional**: Los hallazgos están redactados de forma que un asesor podría mencionarlos naturalmente en una reunión (no son datos excesivamente técnicos o académicos).

---

## Solución de problemas

### Problema 1: Copilot no muestra fuentes citadas ni enlaces web en sus respuestas

**Síntomas**: La respuesta de Copilot proporciona información general sobre el sector logístico pero no incluye referencias numeradas, enlaces a fuentes web, ni nombres de publicaciones específicas. La respuesta parece basarse únicamente en conocimiento interno del modelo sin acceso a internet.

**Causa**: La búsqueda web no está activa en la sesión actual de Copilot Chat. Esto puede ocurrir porque:
- El modo está configurado en **"Trabajo" (Work)** en lugar de **"Web"**.
- El toggle de búsqueda web está desactivado.
- El administrador del tenant ha deshabilitado la búsqueda web para Copilot Chat a nivel organizacional.
- La sesión se inició en una pestaña o ventana donde Copilot no tiene permisos de búsqueda web.

**Solución**:

1. **Verifica el modo de Copilot**: Busca el selector de modo en la parte superior de la interfaz. Si dice "Trabajo" o "Work", cámbialo a "Web".
2. **Busca el toggle de búsqueda web**: Cerca del campo de entrada de texto, busca un ícono de globo terráqueo (🌐) o un toggle etiquetado "Buscar en la web". Actívalo.
3. **Inicia una nueva conversación**: Después de cambiar el modo, crea un nuevo chat para que el cambio surta efecto.
4. **Prueba con un prompt explícito**: Envía: *"Busca en la web las últimas noticias sobre logística en México publicadas esta semana y muéstrame los enlaces a las fuentes."*
5. **Si persiste el problema**: Intenta acceder a Copilot desde la **barra lateral de Microsoft Edge** (haz clic en el ícono de Copilot en la esquina superior derecha de Edge). Esta versión a veces tiene la búsqueda web habilitada por defecto.
6. **Último recurso**: Consulta con el instructor. Si la búsqueda web está deshabilitada a nivel de tenant, el instructor proporcionará una alternativa (como usar Copilot en Edge con cuenta personal para la búsqueda web y luego transferir los resultados al contexto organizacional).

---

### Problema 2: Los enlaces citados por Copilot llevan a páginas inexistentes o el contenido no coincide con lo que Copilot afirma

**Síntomas**: Al hacer clic en los enlaces proporcionados por Copilot, se obtiene un error 404 (página no encontrada), la página existe pero no contiene el dato específico que Copilot atribuyó a esa fuente, o el enlace lleva a una página genérica del sitio web sin el artículo específico.

**Causa**: Este es un comportamiento conocido de los modelos de lenguaje grande (LLMs) denominado **"alucinación de fuentes"**. Copilot puede:
- Generar URLs que parecen plausibles pero no existen realmente.
- Atribuir datos correctos a fuentes incorrectas.
- Combinar información de múltiples fuentes y atribuirla a una sola.
- Citar una fuente que existió pero fue eliminada o movida desde que el modelo fue entrenado.

**Solución**:

1. **No descartes automáticamente el dato**: El hecho de que el enlace no funcione no significa necesariamente que el dato sea falso. El dato podría ser correcto pero estar mal atribuido.
2. **Verifica el dato por separado**: Copia el dato o tendencia específica y búscalo directamente en **Microsoft Edge** usando un motor de búsqueda. Por ejemplo, si Copilot afirma que "el sector logístico en México creció 8% en 2024", busca esa cifra directamente.
3. **Solicita fuentes alternativas a Copilot**: Envía un prompt como: *"El enlace que proporcionaste para [dato específico] no funciona. ¿Puedes buscar una fuente alternativa y verificable para ese mismo dato?"*
4. **En tu tabla de evaluación**: Marca la fuente como **"Dudosa"** si el enlace no funciona pero el dato parece plausible, o como **"No confiable"** si no puedes verificar el dato por ningún medio.
5. **Documenta el hallazgo**: En la columna de URL de tu tabla, anota "Enlace no funcional — dato verificado/no verificado por búsqueda independiente". Esta transparencia es parte del ejercicio de pensamiento crítico y **es un resultado válido del lab**, no un error.

> 📝 **Nota pedagógica**: Encontrar fuentes no verificables o alucinadas es un resultado esperado y valioso de este lab. Demuestra por qué la evaluación crítica de fuentes es indispensable al usar IA generativa para investigación. En un contexto profesional de asesoría de inversiones, presentar datos no verificados a un prospecto podría dañar seriamente la credibilidad de la firma.

---

## Limpieza

1. **Archivo temporal de borrador**: Si creaste un archivo `Investigacion_Sector_Logistico_Borrador.txt` en el Paso 2, puedes **eliminarlo** ya que todo el contenido relevante fue consolidado en `Evaluacion_Fuentes_Sector_Logistico.docx`. Alternativamente, puedes conservarlo como referencia.

2. **Conversación de Copilot Chat**: No es necesario eliminar la conversación. Puedes dejarla en tu historial de Copilot Chat como referencia. Sin embargo, ten en cuenta que las conversaciones de Copilot Chat pueden no persistir indefinidamente dependiendo de la configuración del tenant.

3. **Archivos a conservar obligatoriamente**:
   - ✅ `Evaluacion_Fuentes_Sector_Logistico.docx` — en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`
   - Este archivo será referenciado en el **lab 01-08-05** como insumo para la sección de "contexto público del sector" en la ficha de preparación `Ficha_Preparacion_CarlosMendoza_CIBEST.docx`.

4. **Verificación de sincronización de OneDrive**: Confirma que el archivo se sincronizó correctamente con la nube. En el Explorador de archivos, verifica que el archivo muestre un ícono de **marca de verificación verde** (✅) o **nube azul** (☁️) junto al nombre, indicando que está sincronizado con OneDrive.

---

## Resumen

En este laboratorio completaste el siguiente flujo de trabajo analítico:

| Paso | Actividad | Habilidad desarrollada |
|---|---|---|
| 1 | Verificación de búsqueda web en Copilot Chat | Configuración de herramientas de IA |
| 2 | Investigación inicial del sector logístico LATAM | Formulación de prompts de investigación con solicitud de fuentes |
| 3 | Evaluación crítica de fuentes citadas | Pensamiento crítico y verificación de información generada por IA |
| 4 | Profundización en temas de alta relevancia | Iteración de prompts para obtener datos específicos y cuantitativos |
| 5 | Conexión con perfil del prospecto | Análisis contextual y aplicación de investigación a un caso específico |
| 6 | Selección y documentación del resumen final | Síntesis y documentación estructurada de hallazgos |

### Aprendizajes clave

- **La búsqueda web en Copilot Chat** es una herramienta poderosa para investigación rápida, pero sus resultados **siempre requieren verificación humana**.
- **Las fuentes citadas por Copilot no son automáticamente confiables**: los enlaces pueden estar rotos, los datos pueden estar mal atribuidos y las fuentes pueden no existir. La evaluación crítica es obligatoria.
- **La investigación sectorial tiene valor directo en la asesoría de inversiones**: demostrar conocimiento del sector del prospecto genera credibilidad y confianza en la relación comercial.
- **El proceso iterativo de prompts** (investigación general → profundización → conexión con el caso) produce resultados significativamente mejores que un solo prompt amplio.

### Continuidad con el siguiente lab

El resumen de investigación sectorial documentado en `Evaluacion_Fuentes_Sector_Logistico.docx` se integrará como el componente de **"contexto público del sector"** en la ficha de preparación que crearás en el **Lab 01-08-05** usando Microsoft Word con Copilot. Asegúrate de que el archivo esté accesible en la ruta de OneDrive indicada antes de iniciar el siguiente lab.

### Recursos adicionales

| Recurso | Enlace |
|---|---|
| Documentación oficial de Microsoft 365 Copilot Chat | [https://learn.microsoft.com/es-es/copilot/microsoft-365/microsoft-365-copilot-overview](https://learn.microsoft.com/es-es/copilot/microsoft-365/microsoft-365-copilot-overview) |
| Guía de búsqueda web en Copilot | [https://support.microsoft.com/es-es/topic/copilot-web-search](https://support.microsoft.com/es-es/topic/copilot-web-search) |
| CEPAL — Informes sobre logística en América Latina | [https://www.cepal.org/es/temas/logistica](https://www.cepal.org/es/temas/logistica) |
| BID — Sector transporte y logística | [https://www.iadb.org/es/sectores/transporte](https://www.iadb.org/es/sectores/transporte) |
| Buenas prácticas para evaluar fuentes de información | [https://learn.microsoft.com/es-es/copilot/microsoft-365/microsoft-365-copilot-user-guide](https://learn.microsoft.com/es-es/copilot/microsoft-365/microsoft-365-copilot-user-guide) |

---

# Práctica guiada en Word con Copilot: creación y estructuración de ficha de preparación para la reunión con el prospecto

## Metadatos del laboratorio

| Campo | Valor |
|---|---|
| **Duración** | 20 minutos |
| **Complejidad** | Media |
| **Nivel de Bloom** | Aplicar |
| **Tecnologías** | Microsoft Word con Copilot (v2405, Build 17628.20164), OneDrive for Business, Microsoft 365 Copilot Chat |
| **Batch** | 1 — Lab de cierre e integración |

---

## Descripción general

Este laboratorio es el ejercicio de cierre del batch 1. Integrarás en un único documento profesional de Microsoft Word todos los artefactos generados en los labs anteriores: el perfil contextualizado del prospecto Carlos Mendoza (lab 01-08-02), las preguntas de descubrimiento categorizadas (lab 01-08-03) y el resumen de investigación del sector logístico latinoamericano (lab 01-08-04). Utilizarás Copilot integrado en Word para crear la estructura, poblar cada sección, refinar el tono profesional y generar una lista de aspectos críticos pendientes. El resultado será la ficha `Ficha_Preparacion_CarlosMendoza_CIBEST.docx`, guardada en OneDrive, que servirá como insumo de referencia para todos los labs del batch 2.

---

## Objetivos de aprendizaje

Al completar este laboratorio, serás capaz de:

- [ ] Crear un documento nuevo en Microsoft Word y utilizar Copilot integrado para generar una estructura profesional de ficha de preparación con secciones claramente diferenciadas.
- [ ] Integrar en la ficha los tres artefactos previos del batch (perfil del prospecto, preguntas de descubrimiento y contexto del sector logístico) mediante prompts dirigidos a Copilot en Word.
- [ ] Organizar la información en secciones funcionales: información conocida, información por confirmar, contexto del sector, preguntas de descubrimiento y aspectos pendientes antes de la reunión.
- [ ] Usar Copilot en Word para refinar el tono, mejorar la estructura y asegurar que el documento sea un instrumento práctico y profesional para el equipo de CIBEST CAPITAL.
- [ ] Guardar el documento final en la ruta estandarizada de OneDrive para garantizar continuidad con el batch 2.

---

## Prerrequisitos

### Conocimientos previos

| Requisito | Detalle |
|---|---|
| Labs anteriores completados | Labs 01-08-02 (perfil del prospecto), 01-08-03 (preguntas de descubrimiento) y 01-08-04 (investigación del sector logístico) finalizados con artefactos documentados |
| Manejo básico de Word | Saber crear documentos, aplicar estilos de encabezado, insertar tablas y guardar en OneDrive |
| Experiencia con Copilot | Haber utilizado el panel de Copilot en Word al menos una vez en labs previos |
| Contexto de negocio | Comprender el perfil de Carlos Mendoza y el rol de CIBEST CAPITAL según las lecciones 1.1–1.7 |

### Acceso y licencias

| Recurso | Requisito |
|---|---|
| Cuenta Microsoft 365 | Cuenta organizacional con licencia **Microsoft 365 Copilot Premium** activa |
| Microsoft Word | Versión 2405 (Build 17628.20164) o superior instalada y funcional |
| OneDrive for Business | Acceso activo con capacidad de crear carpetas y guardar archivos |
| Artefactos de labs previos | Notas, documentos o capturas de los labs 01-08-02, 01-08-03 y 01-08-04 abiertas o accesibles en pantalla |

---

## Entorno del laboratorio

### Requisitos de hardware

| Componente | Mínimo | Recomendado |
|---|---|---|
| Procesador | 64 bits (Intel Core i5 / AMD Ryzen 5) | Intel Core i7 / AMD Ryzen 7 |
| RAM | 8 GB | 16 GB |
| Espacio en disco | 10 GB libres | 20 GB libres |
| Pantalla | 1366×768 | 1920×1080 |
| Conexión a internet | 10 Mbps de bajada | 25 Mbps de bajada |

### Requisitos de software

| Software | Versión requerida |
|---|---|
| Windows | Windows 10 22H2 (Build 19045) o Windows 11 23H2 (Build 22631) o superior |
| Microsoft Word | Versión 2405 (Build 17628.20164) — incluido en Microsoft 365 Apps for Enterprise |
| Microsoft Edge | 124.0.2478.97 o superior (para acceso a copilot.microsoft.com si se necesita consultar artefactos previos) |
| Microsoft 365 Copilot | Licencia Premium M365 Copilot activa |

### Configuración inicial del entorno

Antes de comenzar los pasos del laboratorio, verifica y prepara lo siguiente:

**1. Verificar la versión de Microsoft Word:**

Abre Microsoft Word → **Archivo** → **Cuenta** → **Información del producto**. Confirma que la versión sea **2405 (Build 17628.20164)** o superior.

**2. Verificar que Copilot esté habilitado en Word:**

Abre un documento nuevo en Word. En la cinta de opciones, pestaña **Inicio**, busca el botón **Copilot** (ícono de Copilot en el extremo derecho de la cinta). Si no aparece, contacta al administrador de TI para verificar la licencia.

**3. Crear la estructura de carpetas en OneDrive (si no existe):**

Abre el Explorador de archivos → navega a **OneDrive** → **Documentos**. Crea las siguientes carpetas si no existen:

```
Documentos
└── CIBEST_CAPITAL
    └── Prospectos
```

**4. Tener accesibles los artefactos de labs previos:**

Abre en ventanas separadas o ten copiados en el portapapeles:

- **Lab 01-08-02**: Perfil contextualizado de Carlos Mendoza
- **Lab 01-08-03**: Preguntas de descubrimiento categorizadas
- **Lab 01-08-04**: Resumen de investigación del sector logístico latinoamericano

> 💡 **Consejo**: Si documentaste los artefactos previos en Microsoft 365 Copilot Chat (copilot.microsoft.com), puedes abrir esa ventana en Microsoft Edge para copiar el contenido directamente.

---

## Pasos del laboratorio

### Paso 1: Crear el documento base y generar la estructura con Copilot

**Objetivo**: Crear un documento nuevo en Word y usar Copilot para generar la estructura completa de la ficha de preparación con todas las secciones requeridas.

**Instrucciones:**

1. Abre **Microsoft Word** desde el menú Inicio o la barra de tareas.

2. Selecciona **Documento en blanco** para crear un nuevo documento vacío.

3. Antes de activar Copilot, escribe manualmente el siguiente título en la primera línea del documento y aplícale el estilo **Título** (pestaña Inicio → Estilos → Título):

   ```
   Ficha de Preparación — Reunión Inicial con Carlos Mendoza
   ```

4. Debajo del título, escribe una línea de subtítulo con estilo **Subtítulo**:

   ```
   CIBEST CAPITAL — Equipo de Asesoría de Inversiones
   ```

5. Coloca el cursor debajo del subtítulo. Haz clic en el botón **Copilot** en la cinta de opciones (pestaña **Inicio**, extremo derecho) para abrir el panel lateral de Copilot.

6. En el campo de prompt del panel de Copilot, escribe el siguiente prompt y presiona **Enter** (o haz clic en el botón de enviar):

   ```
   Crea la estructura de una ficha de preparación para una reunión de asesoría de
   inversiones con las siguientes secciones:
   (1) Perfil del prospecto
   (2) Información conocida
   (3) Información por confirmar
   (4) Contexto del sector
   (5) Preguntas de descubrimiento por categoría
   (6) Aspectos pendientes de resolver antes de la reunión

   Usa un formato profesional con encabezados claros tipo Heading 2 para cada
   sección. Incluye una breve descripción de una línea debajo de cada encabezado
   explicando qué información va en esa sección. No inventes datos del prospecto;
   deja marcadores de posición como [Insertar aquí].
   ```

7. Revisa la respuesta generada por Copilot. Si Copilot ofrece la opción **"Insertar"** o **"Copiar"**, haz clic en **"Insertar"** para que el contenido se agregue directamente al documento.

8. Si la estructura no incluye las 6 secciones solicitadas, envía un prompt de seguimiento:

   ```
   Falta la sección [nombre de la sección faltante]. Agrégala manteniendo el
   mismo formato profesional que las demás secciones.
   ```

**Resultado esperado:**

El documento debe contener un título, un subtítulo y seis secciones con encabezados de nivel Heading 2, cada una con una breve descripción y marcadores de posición `[Insertar aquí]`. La estructura debe verse similar a:

```
Ficha de Preparación — Reunión Inicial con Carlos Mendoza
CIBEST CAPITAL — Equipo de Asesoría de Inversiones

## 1. Perfil del prospecto
Resumen ejecutivo del prospecto y su empresa.
[Insertar aquí]

## 2. Información conocida
Datos confirmados sobre el prospecto, su negocio y sus objetivos.
[Insertar aquí]

## 3. Información por confirmar
Datos pendientes de validar durante la reunión.
[Insertar aquí]

## 4. Contexto del sector
Panorama del sector logístico relevante para la conversación.
[Insertar aquí]

## 5. Preguntas de descubrimiento por categoría
Preguntas organizadas por tema para guiar la reunión.
[Insertar aquí]

## 6. Aspectos pendientes de resolver antes de la reunión
Acciones y preparativos críticos previos al encuentro.
[Insertar aquí]
```

**Verificación:**

- [ ] El documento tiene título y subtítulo con estilos aplicados correctamente.
- [ ] Existen exactamente 6 secciones con encabezados Heading 2.
- [ ] Cada sección contiene una descripción breve y marcadores de posición.
- [ ] No hay datos ficticios inventados por Copilot sobre el prospecto.

---

### Paso 2: Poblar la sección de Perfil del prospecto

**Objetivo**: Insertar la información de Carlos Mendoza y usar Copilot para redactarla con tono profesional adecuado para un documento interno de asesoría financiera.

**Instrucciones:**

1. Ubica la sección **"1. Perfil del prospecto"** en el documento.

2. Reemplaza el marcador `[Insertar aquí]` con la siguiente información base (cópiala directamente):

   ```
   Nombre: Carlos Mendoza
   Empresa: Empresa de logística con operaciones en México
   Ingresos anuales aproximados: USD 5 millones
   Interés: Diversificar patrimonio personal invirtiendo en activos en Estados Unidos
   Experiencia en inversiones internacionales: Limitada
   Firma asesora: CIBEST CAPITAL
   ```

3. Selecciona todo el texto que acabas de pegar en esa sección (desde "Nombre:" hasta "CIBEST CAPITAL").

4. Con el texto seleccionado, haz clic en el ícono de **Copilot** que aparece al lado izquierdo del texto seleccionado (ícono flotante) o usa el panel lateral de Copilot y escribe el siguiente prompt:

   ```
   Reescribe esta información como un párrafo ejecutivo profesional de 4-5 oraciones,
   adecuado para un documento interno de una firma de asesoría de inversiones.
   Mantén todos los datos exactos. Usa un tono formal pero accesible. Incluye al
   final una nota breve indicando que la experiencia limitada del prospecto en
   inversiones internacionales requiere un enfoque educativo en la reunión.
   ```

5. Revisa el texto generado por Copilot. Si el tono es demasiado informal o si omite algún dato, solicita un ajuste:

   ```
   Asegúrate de mencionar explícitamente los ingresos de USD 5 millones y que la
   firma asesora es CIBEST CAPITAL.
   ```

6. Haz clic en **"Reemplazar"** (o **"Insertar"**, según la opción que ofrezca Copilot) para actualizar el contenido en el documento.

**Resultado esperado:**

Un párrafo ejecutivo de 4–5 oraciones que presente profesionalmente a Carlos Mendoza, mencionando su empresa de logística en México, los ingresos aproximados de USD 5 millones, su interés en diversificar patrimonio en activos estadounidenses, su experiencia limitada en inversiones internacionales y una nota sobre la necesidad de un enfoque educativo. El texto debe identificar a CIBEST CAPITAL como la firma asesora.

**Verificación:**

- [ ] El párrafo contiene todos los datos clave: nombre, sector, país, ingresos, interés de inversión, nivel de experiencia.
- [ ] Se menciona a CIBEST CAPITAL.
- [ ] El tono es profesional y adecuado para un documento interno.
- [ ] Incluye la nota sobre el enfoque educativo requerido.

---

### Paso 3: Crear la tabla de información conocida vs. información por confirmar

**Objetivo**: Generar una tabla de dos columnas que diferencie claramente lo que el equipo ya sabe sobre Carlos Mendoza de lo que necesita confirmar en la reunión, integrando hallazgos de los labs anteriores.

**Instrucciones:**

1. Ubica las secciones **"2. Información conocida"** y **"3. Información por confirmar"** en el documento.

2. Elimina los marcadores `[Insertar aquí]` de ambas secciones.

3. En el panel de Copilot, escribe el siguiente prompt:

   ```
   Genera una tabla profesional de dos columnas con el encabezado "Información
   conocida" en la columna izquierda e "Información por confirmar" en la columna
   derecha. Basa la tabla en el siguiente perfil de prospecto:

   - Carlos Mendoza, propietario de empresa de logística en México
   - Ingresos anuales aproximados: USD 5 millones
   - Interés en diversificar patrimonio invirtiendo en activos en Estados Unidos
   - Experiencia limitada en inversiones internacionales
   - Firma asesora: CIBEST CAPITAL

   En la columna "Información conocida", incluye los datos confirmados anteriores.
   En la columna "Información por confirmar", genera al menos 6 elementos que un
   asesor financiero necesitaría validar antes de hacer una recomendación de
   inversión, tales como: monto disponible para inversión, horizonte temporal,
   tolerancia al riesgo, situación fiscal binacional, estructura legal de la empresa,
   objetivos específicos de diversificación, experiencia previa con instrumentos
   financieros, entre otros relevantes.

   Formatea como tabla de Word con bordes visibles.
   ```

4. Revisa la tabla generada. Verifica que los elementos de la columna izquierda correspondan estrictamente a datos que ya conocemos (confirmados en el perfil) y que los de la columna derecha sean genuinamente datos pendientes de confirmar.

5. Si necesitas agregar elementos basados en tus notas de los labs 01-08-02 o 01-08-03, hazlo manualmente o con un prompt adicional:

   ```
   Agrega a la columna "Información por confirmar" los siguientes elementos:
   [pega aquí elementos específicos de tus notas del lab 01-08-02 o 01-08-03
   que no hayan sido incluidos].
   ```

6. Inserta la tabla en el documento, reemplazando el contenido de las secciones 2 y 3. Si Copilot generó la tabla como contenido unificado, colócala entre ambas secciones o reorganiza manualmente para que la tabla quede bajo la sección 2, y en la sección 3 agregues una nota como: *"Ver columna derecha de la tabla anterior."*

> ⚠️ **Nota importante**: Si Copilot no genera una tabla con formato visual de Word sino texto plano con separadores, selecciona el texto generado y usa **Insertar → Tabla → Convertir texto en tabla** para darle formato adecuado.

**Resultado esperado:**

Una tabla con dos columnas y al menos 6–8 filas que separe claramente la información confirmada de la información pendiente. Ejemplo de estructura:

| Información conocida | Información por confirmar |
|---|---|
| Nombre: Carlos Mendoza | Monto disponible para inversión |
| Sector: Logística en México | Horizonte temporal de inversión |
| Ingresos anuales: ~USD 5M | Tolerancia al riesgo |
| Interés: Inversión en activos en EE.UU. | Situación fiscal México-EE.UU. |
| Experiencia en inversiones internacionales: Limitada | Estructura legal de la empresa |
| Firma asesora: CIBEST CAPITAL | Objetivos específicos de diversificación |
| — | Experiencia previa con instrumentos financieros |
| — | Expectativas de rendimiento |

**Verificación:**

- [ ] La tabla tiene dos columnas claramente diferenciadas con encabezados.
- [ ] La columna izquierda contiene solo datos confirmados del perfil.
- [ ] La columna derecha contiene al menos 6 elementos pendientes de validar.
- [ ] La tabla tiene formato visual profesional con bordes visibles.

---

### Paso 4: Integrar el contexto del sector logístico

**Objetivo**: Incorporar el resumen de investigación del sector logístico del lab 01-08-04, adaptándolo al formato y propósito de la ficha de preparación.

**Instrucciones:**

1. Ubica la sección **"4. Contexto del sector"** en el documento y elimina el marcador `[Insertar aquí]`.

2. Abre tus notas o el artefacto del **lab 01-08-04** (resumen de investigación del sector logístico latinoamericano). Copia el contenido principal del resumen.

3. Pega el contenido copiado debajo del encabezado de la sección 4 en el documento de Word.

4. Selecciona todo el texto que acabas de pegar. En el panel de Copilot, escribe el siguiente prompt:

   ```
   Adapta este resumen de investigación del sector logístico para que sea conciso
   y relevante para un asesor financiero que se prepara para una primera reunión
   con un empresario del sector. El formato debe ser:

   1. Un párrafo introductorio de 2-3 oraciones sobre el estado actual del sector
      logístico en México y Latinoamérica.
   2. Una lista con viñetas de los 4-5 datos o tendencias más relevantes que un
      asesor de CIBEST CAPITAL debería conocer antes de reunirse con Carlos Mendoza.
   3. Un párrafo de cierre de 1-2 oraciones sobre cómo este contexto sectorial
      podría influir en la conversación sobre diversificación de patrimonio.

   Mantén un tono profesional y orientado a la acción. No excedas 250 palabras
   en total.
   ```

5. Revisa el resultado. Verifica que los datos del sector sean coherentes con lo que investigaste en el lab 01-08-04. Si Copilot introdujo datos que no estaban en tu investigación original, decide si son plausibles o solicita corrección:

   ```
   Elimina el punto sobre [dato específico] que no corresponde a mi investigación
   original y reemplázalo con: [dato correcto de tu lab 01-08-04].
   ```

6. Acepta la versión final haciendo clic en **"Reemplazar"** o **"Insertar"**.

**Resultado esperado:**

La sección de contexto del sector debe contener:
- Un párrafo introductorio breve sobre el sector logístico en México/Latinoamérica.
- Una lista de 4–5 tendencias o datos clave con viñetas.
- Un párrafo de cierre que conecte el contexto sectorial con la conversación de inversión.
- Extensión total no mayor a 250 palabras.

**Verificación:**

- [ ] El contenido es coherente con la investigación del lab 01-08-04.
- [ ] El formato incluye párrafo introductorio, lista con viñetas y párrafo de cierre.
- [ ] El tono es profesional y orientado a un asesor financiero.
- [ ] No excede 250 palabras (selecciona el texto → pestaña **Revisar** → **Contar palabras** para verificar).

---

### Paso 5: Incorporar las preguntas de descubrimiento categorizadas

**Objetivo**: Integrar las preguntas de descubrimiento del lab 01-08-03 en la sección correspondiente, asegurando consistencia de formato y tono con el resto de la ficha.

**Instrucciones:**

1. Ubica la sección **"5. Preguntas de descubrimiento por categoría"** y elimina el marcador `[Insertar aquí]`.

2. Abre tus notas o el artefacto del **lab 01-08-03** (preguntas de descubrimiento categorizadas). Copia todas las preguntas organizadas por categoría.

3. Pega el contenido debajo del encabezado de la sección 5.

4. Selecciona todo el contenido pegado. En el panel de Copilot, escribe:

   ```
   Reformatea estas preguntas de descubrimiento para que cumplan con los
   siguientes criterios:

   1. Organízalas bajo subcategorías claras usando encabezados Heading 3
      (por ejemplo: Situación financiera actual, Objetivos de inversión,
      Tolerancia al riesgo, Contexto fiscal y legal, Expectativas y plazos).
   2. Limita cada categoría a un máximo de 3 preguntas (selecciona las más
      críticas para una primera reunión).
   3. Asegúrate de que todas las preguntas estén redactadas en tono profesional
      pero accesible, considerando que Carlos Mendoza tiene experiencia limitada
      en inversiones internacionales. Evita jerga financiera compleja.
   4. Añade entre paréntesis después de cada pregunta una nota breve sobre
      por qué esa pregunta es importante (máximo 10 palabras).

   Mantén el formato de lista numerada dentro de cada categoría.
   ```

5. Revisa las preguntas reformateadas. Verifica que:
   - Las categorías sean relevantes para una primera reunión de asesoría.
   - Las preguntas sean claras y libres de tecnicismos excesivos.
   - Cada categoría tenga máximo 3 preguntas.

6. Si alguna pregunta clave de tu lab 01-08-03 fue eliminada, agrégala manualmente o solicita a Copilot:

   ```
   Agrega la siguiente pregunta en la categoría [nombre de categoría]:
   "[tu pregunta]" con la nota: (importante porque [razón breve]).
   ```

7. Acepta la versión final e insértala en el documento.

**Resultado esperado:**

La sección debe contener entre 4 y 6 subcategorías (Heading 3), cada una con máximo 3 preguntas numeradas. Cada pregunta debe incluir una nota entre paréntesis sobre su importancia. Ejemplo:

```
### Situación financiera actual
1. ¿Cuál es el monto aproximado que tiene disponible para invertir?
   (Define el alcance de las opciones de inversión)
2. ¿Tiene compromisos financieros o deudas significativas actualmente?
   (Evalúa capacidad real de inversión)
3. ¿Cómo está estructurada legalmente su empresa de logística?
   (Impacta en la planificación fiscal binacional)

### Objetivos de inversión
1. ¿Qué busca lograr principalmente con esta inversión: crecimiento,
   ingreso pasivo o preservación de capital?
   (Define la estrategia de portafolio recomendada)
...
```

**Verificación:**

- [ ] Hay entre 4 y 6 subcategorías con encabezados Heading 3.
- [ ] Cada categoría tiene máximo 3 preguntas.
- [ ] Cada pregunta incluye una nota entre paréntesis sobre su importancia.
- [ ] El lenguaje es accesible y libre de jerga financiera compleja.
- [ ] Las preguntas son coherentes con las del lab 01-08-03.

---

### Paso 6: Generar la sección de aspectos pendientes antes de la reunión

**Objetivo**: Usar Copilot para analizar toda la ficha y generar una lista priorizada de los aspectos más críticos que CIBEST CAPITAL debe resolver antes de la reunión con Carlos Mendoza.

**Instrucciones:**

1. Ubica la sección **"6. Aspectos pendientes de resolver antes de la reunión"** y elimina el marcador `[Insertar aquí]`.

2. En el panel de Copilot, escribe el siguiente prompt:

   ```
   Con base en toda la información de este documento (perfil del prospecto,
   información conocida y por confirmar, contexto del sector logístico y preguntas
   de descubrimiento), genera una lista de los 5 aspectos más críticos que el
   equipo de CIBEST CAPITAL debe resolver o preparar antes de la reunión con
   Carlos Mendoza.

   Para cada aspecto, incluye:
   - Una descripción clara del aspecto (1-2 oraciones)
   - La razón por la que es crítico resolverlo antes de la reunión
   - Una acción concreta recomendada para el equipo

   Ordena los aspectos de mayor a menor prioridad. Usa formato de lista numerada.
   ```

3. Revisa los 5 aspectos generados. Evalúa críticamente si Copilot identificó correctamente las prioridades. Considera si los siguientes temas están representados (si no lo están y consideras que deberían estarlo, solicita a Copilot que los incluya):

   - Preparación de materiales educativos sobre inversión internacional (dado el nivel de experiencia limitada del prospecto).
   - Investigación preliminar sobre implicaciones fiscales México-EE.UU.
   - Definición del equipo de CIBEST CAPITAL que asistirá a la reunión.
   - Preparación de ejemplos concretos de opciones de inversión en EE.UU. para el perfil del prospecto.
   - Verificación de disponibilidad de Carlos Mendoza y formato preferido de reunión.

4. Si necesitas ajustar la lista, usa un prompt de refinamiento:

   ```
   Reemplaza el aspecto número [X] por el siguiente: [descripción del nuevo
   aspecto]. Mantén el mismo formato con descripción, razón y acción recomendada.
   ```

5. Acepta la versión final e insértala en el documento.

**Resultado esperado:**

Una lista numerada de 5 aspectos críticos, cada uno con tres componentes: descripción, razón de criticidad y acción recomendada. Los aspectos deben ser específicos al caso de Carlos Mendoza y CIBEST CAPITAL, no genéricos.

**Verificación:**

- [ ] La lista contiene exactamente 5 aspectos.
- [ ] Cada aspecto incluye descripción, razón y acción concreta.
- [ ] Los aspectos son específicos al caso (mencionan a Carlos Mendoza, CIBEST CAPITAL, logística, México, EE.UU.).
- [ ] Están ordenados por prioridad (el más crítico primero).

---

### Paso 7: Revisión y refinamiento final del documento completo

**Objetivo**: Realizar una revisión integral del documento usando Copilot para asegurar coherencia, tono profesional uniforme y completitud de todas las secciones.

**Instrucciones:**

1. Presiona **Ctrl + A** para seleccionar todo el contenido del documento.

2. En el panel de Copilot, escribe el siguiente prompt de revisión general:

   ```
   Revisa este documento completo como ficha de preparación para una reunión de
   asesoría de inversiones. Evalúa:
   1. ¿Hay inconsistencias entre secciones?
   2. ¿El tono es profesional y uniforme en todo el documento?
   3. ¿Falta alguna información crítica que debería incluirse?
   4. ¿Hay redundancias que deberían eliminarse?

   Dame un resumen de máximo 5 observaciones concretas con sugerencias de mejora.
   ```

3. Lee las observaciones de Copilot. Selecciona al menos **una mejora específica** para implementar. Por ejemplo, si Copilot sugiere que hay redundancia entre la tabla de información y el perfil, solicita:

   ```
   Haz que la sección de preguntas de descubrimiento sea más concisa, máximo
   3 preguntas por categoría. Elimina las preguntas que sean redundantes con
   la columna "Información por confirmar" de la tabla de la sección 2.
   ```

   O bien, otro ejemplo de refinamiento:

   ```
   Agrega una fecha de preparación y un campo de "Preparado por:" al inicio
   del documento, justo debajo del subtítulo de CIBEST CAPITAL.
   ```

4. Implementa la mejora seleccionada. Si Copilot ofrece el texto revisado, haz clic en **"Reemplazar"** para actualizar el documento.

5. Realiza una última lectura manual rápida del documento completo (scroll de arriba a abajo) para verificar:
   - Que todos los encabezados estén con el estilo correcto (Heading 2 para secciones principales, Heading 3 para subcategorías).
   - Que no haya marcadores `[Insertar aquí]` sin reemplazar.
   - Que la tabla tenga formato visual correcto con bordes.
   - Que el nombre "Carlos Mendoza" y "CIBEST CAPITAL" estén escritos correctamente en todo el documento.

**Resultado esperado:**

Un documento profesional, coherente y completo que funcione como instrumento práctico de preparación para el equipo. Todas las secciones deben estar pobladas con contenido relevante, sin marcadores de posición vacíos ni inconsistencias de tono.

**Verificación:**

- [ ] Se implementó al menos una mejora específica sugerida por Copilot.
- [ ] No quedan marcadores `[Insertar aquí]` sin reemplazar.
- [ ] El tono es uniforme en todo el documento.
- [ ] Los nombres "Carlos Mendoza" y "CIBEST CAPITAL" están correctos en todas las apariciones.
- [ ] Los estilos de encabezado son consistentes (H2 para secciones, H3 para subcategorías).

---

### Paso 8: Guardar el documento en OneDrive con el nombre estandarizado

**Objetivo**: Guardar el documento final con el nombre exacto requerido en la ruta estandarizada de OneDrive para garantizar continuidad con el batch 2.

**Instrucciones:**

1. Haz clic en **Archivo** → **Guardar como** (o **Guardar una copia** si ya se guardó previamente).

2. En el panel de ubicaciones, selecciona **OneDrive — [nombre de tu organización]**.

3. Navega a la siguiente ruta de carpetas:

   ```
   Documentos > CIBEST_CAPITAL > Prospectos
   ```

   > ⚠️ Si las carpetas no existen, créalas desde el diálogo de guardado: haz clic en **Nueva carpeta** para crear primero `CIBEST_CAPITAL` dentro de `Documentos`, y luego `Prospectos` dentro de `CIBEST_CAPITAL`.

4. En el campo **Nombre de archivo**, escribe exactamente:

   ```
   Ficha_Preparacion_CarlosMendoza_CIBEST
   ```

   > El formato de archivo debe ser **.docx** (Word). Verifica que el tipo de archivo seleccionado sea **Documento de Word (*.docx)**.

5. Haz clic en **Guardar**.

6. Verifica que el documento se guardó correctamente:
   - En la barra de título de Word, debe aparecer: `Ficha_Preparacion_CarlosMendoza_CIBEST.docx`
   - Debe mostrar el ícono de nube de OneDrive con una marca de verificación verde (✓), indicando que está sincronizado.

7. Como verificación adicional, abre el **Explorador de archivos** → **OneDrive** → **Documentos** → **CIBEST_CAPITAL** → **Prospectos** y confirma que el archivo aparece en la lista.

**Resultado esperado:**

El archivo `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` está guardado en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos` y sincronizado con la nube.

**Verificación:**

- [ ] El nombre del archivo es exactamente `Ficha_Preparacion_CarlosMendoza_CIBEST.docx`.
- [ ] La ubicación es `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.
- [ ] El ícono de sincronización de OneDrive muestra marca verde (✓).
- [ ] El archivo es accesible desde el Explorador de archivos.

---

## Validación y pruebas finales

Antes de considerar el laboratorio como completado, realiza la siguiente lista de verificación integral:

### Lista de verificación del documento final

| # | Criterio | Estado |
|---|---|---|
| 1 | El documento tiene título y subtítulo con estilos aplicados | ☐ |
| 2 | Sección 1 (Perfil del prospecto): Párrafo ejecutivo profesional con todos los datos de Carlos Mendoza | ☐ |
| 3 | Secciones 2–3 (Información conocida / por confirmar): Tabla de dos columnas con al menos 6 elementos por confirmar | ☐ |
| 4 | Sección 4 (Contexto del sector): Resumen adaptado del lab 01-08-04 con párrafo + viñetas + cierre, ≤250 palabras | ☐ |
| 5 | Sección 5 (Preguntas de descubrimiento): 4–6 subcategorías, máximo 3 preguntas por categoría, con notas de importancia | ☐ |
| 6 | Sección 6 (Aspectos pendientes): Lista de 5 aspectos con descripción, razón y acción recomendada | ☐ |
| 7 | Se implementó al menos una mejora de refinamiento en el Paso 7 | ☐ |
| 8 | No quedan marcadores `[Insertar aquí]` sin contenido | ☐ |
| 9 | Los nombres "Carlos Mendoza" y "CIBEST CAPITAL" son correctos en todo el documento | ☐ |
| 10 | Archivo guardado como `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos` | ☐ |

### Prueba de accesibilidad para batch 2

Para confirmar que el archivo estará disponible en los labs del batch 2:

1. Cierra completamente Microsoft Word.
2. Abre **Microsoft Word** nuevamente.
3. En la pantalla de inicio, verifica que `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` aparezca en la lista de **Documentos recientes**.
4. Haz clic en el archivo para abrirlo y confirma que todo el contenido se cargó correctamente.
5. Cierra el archivo sin hacer cambios.

---

## Solución de problemas

### Problema 1: Copilot no aparece en la cinta de opciones de Word

**Síntomas**: Al abrir Word, no se ve el botón de Copilot en la pestaña Inicio. El panel lateral de Copilot no está disponible. Al buscar "Copilot" en la barra de búsqueda de comandos (Alt + Q), no aparecen resultados relacionados.

**Causa**: La licencia de Microsoft 365 Copilot Premium no está asignada a la cuenta del usuario, o la versión de Word es anterior a la requerida (2405, Build 17628.20164), o la política de la organización tiene deshabilitado Copilot para el grupo de usuarios.

**Solución**:

1. Verifica la versión de Word: **Archivo** → **Cuenta** → **Información del producto**. Si la versión es anterior a 2405 (Build 17628.20164), actualiza Word: **Archivo** → **Cuenta** → **Opciones de actualización** → **Actualizar ahora**.
2. Verifica la licencia: Ve a [portal.office.com](https://portal.office.com) → **Mi cuenta** → **Suscripciones** y confirma que "Microsoft 365 Copilot" aparece en la lista de licencias activas.
3. Si la licencia está activa pero Copilot no aparece, cierra sesión de Word (**Archivo** → **Cuenta** → **Cerrar sesión**), reinicia Word y vuelve a iniciar sesión.
4. Si el problema persiste, contacta al administrador de TI para verificar que la política de Copilot esté habilitada para tu cuenta en el Centro de Administración de Microsoft 365.

---

### Problema 2: Copilot genera la tabla como texto plano en lugar de tabla formateada de Word

**Síntomas**: Al solicitar a Copilot que genere la tabla de "Información conocida vs. Información por confirmar" (Paso 3), el resultado aparece como texto con separadores de barra vertical (`|`) o tabulaciones, pero no como una tabla visual de Word con celdas y bordes.

**Causa**: Copilot en Word ocasionalmente genera contenido tabular como texto con formato Markdown o texto separado por tabulaciones, especialmente cuando el prompt es largo o complejo. Esto es un comportamiento conocido que depende de cómo el modelo interpreta la solicitud de formato.

**Solución**:

1. Selecciona todo el texto que Copilot generó con formato de tabla (incluyendo los encabezados y todas las filas).
2. Ve a la pestaña **Insertar** → **Tabla** → **Convertir texto en tabla**.
3. En el cuadro de diálogo:
   - **Número de columnas**: 2
   - **Separar texto en**: Selecciona **Tabulaciones** (si el texto usa tabulaciones) o **Otro** y escribe `|` (si usa barras verticales).
   - Haz clic en **Aceptar**.
4. La tabla ahora debería tener formato visual. Aplica un estilo de tabla: selecciona la tabla → pestaña **Diseño de tabla** → elige un estilo con bordes visibles (por ejemplo, **Tabla con cuadrícula**).
5. Alternativa: Si la conversión no funciona bien, crea una tabla vacía manualmente (**Insertar** → **Tabla** → selecciona 2 columnas × 8 filas) y copia el contenido celda por celda desde el texto generado por Copilot.

---

## Limpieza

Este laboratorio no requiere limpieza de recursos, ya que el archivo generado es un artefacto necesario para el batch 2.

**No elimines** el archivo `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` ni la estructura de carpetas `CIBEST_CAPITAL > Prospectos` en OneDrive.

Si durante la práctica creaste documentos de prueba o borradores adicionales en Word, puedes eliminarlos para mantener organizada tu carpeta de trabajo:

1. Navega a **OneDrive** → **Documentos** → **CIBEST_CAPITAL** → **Prospectos**.
2. Elimina cualquier archivo que **no** sea `Ficha_Preparacion_CarlosMendoza_CIBEST.docx`.
3. Verifica que la papelera de reciclaje de OneDrive no contenga versiones del archivo final que pudieras necesitar.

---

## Resumen

En este laboratorio completaste el cierre del batch 1 integrando todos los artefactos generados en los labs anteriores en un único documento profesional de preparación. Los logros clave fueron:

| Logro | Descripción |
|---|---|
| **Estructura profesional** | Creaste una ficha de preparación con 6 secciones diferenciadas usando Copilot en Word para generar la estructura base. |
| **Integración de artefactos** | Consolidaste el perfil del prospecto (lab 01-08-02), las preguntas de descubrimiento (lab 01-08-03) y la investigación del sector (lab 01-08-04) en un solo documento. |
| **Refinamiento con IA** | Usaste Copilot para adaptar el tono, mejorar el formato, generar la tabla de información conocida vs. por confirmar, y crear la lista de aspectos pendientes. |
| **Pensamiento crítico** | Evaluaste críticamente las sugerencias de Copilot, solicitaste ajustes específicos y tomaste decisiones sobre qué contenido incluir o modificar. |
| **Preparación para batch 2** | Guardaste el documento con el nombre estandarizado en la ruta de OneDrive requerida para continuidad. |

### Conexión con el batch 2

El archivo `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` será utilizado como insumo de referencia en los siguientes labs del batch 2:

- **PowerPoint**: Creación de presentación introductoria basada en el perfil y contexto del sector.
- **Excel**: Construcción de la matriz de necesidades a partir de la información conocida y por confirmar.
- **Outlook**: Redacción de comunicaciones previas a la reunión usando las preguntas de descubrimiento.
- **Teams**: Configuración de la agenda de la reunión basada en los aspectos pendientes.

### Recursos adicionales

- [Usar Copilot en Word — Documentación oficial de Microsoft](https://support.microsoft.com/es-es/office/usar-copilot-en-word-0e75f140-89ff-4574-a6d5-7b8d47e8e2c0)
- [Mejores prácticas para prompts en Copilot para Microsoft 365](https://learn.microsoft.com/es-es/copilot/microsoft-365/microsoft-365-copilot-user-guide)
- [Gestión de archivos en OneDrive for Business](https://support.microsoft.com/es-es/office/introducción-a-onedrive-en-el-trabajo-b30da4eb-ddd2-44b6-943b-e6fbfc6b8dde)

---

# Práctica guiada en PowerPoint con Copilot: elaboración de material introductorio adaptado al prospecto con lenguaje accesible y sin tecnicismos

## 1. Metadatos del laboratorio

| Campo | Detalle |
|---|---|
| **Duración** | 20 minutos |
| **Complejidad** | Media |
| **Nivel de Bloom** | Aplicar (*Apply*) |
| **Aplicación principal** | Microsoft PowerPoint (Versión 2405, Build 17628.20164 o superior) |
| **Herramienta de IA** | Microsoft 365 Copilot (panel integrado en PowerPoint) |
| **Batch / Secuencia** | Batch 1 — Lab 6 de 8 (01-08-06) |

---

## 2. Descripción general

En este laboratorio crearás una presentación introductoria de **6 a 8 diapositivas** en PowerPoint utilizando Copilot, dirigida al prospecto ficticio **Carlos Mendoza** — propietario de una empresa de logística en México con experiencia limitada en inversiones internacionales. Trabajarás iterativamente con Copilot: primero generarás una estructura base, luego identificarás tecnicismos financieros en el contenido generado y solicitarás a Copilot que los reemplace con lenguaje cotidiano. El resultado será un material visual profesional, alineado con la propuesta de valor de **CIBEST CAPITAL**, listo para ser utilizado en una primera reunión de asesoría.

---

## 3. Objetivos de aprendizaje

Al completar este laboratorio, serás capaz de:

- [ ] Crear una presentación introductoria en PowerPoint utilizando la funcionalidad "Crear presentación con Copilot", estructurada específicamente para un prospecto con experiencia limitada en inversiones internacionales.
- [ ] Aplicar técnicas de prompting contextual que incorporen el perfil de la audiencia (sector, nivel de experiencia, intereses) para generar contenido adaptado y libre de tecnicismos financieros.
- [ ] Identificar términos técnicos generados por Copilot y solicitar reformulaciones en lenguaje accesible mediante prompts de iteración en el panel de Copilot.
- [ ] Editar y refinar las diapositivas generadas para asegurar coherencia narrativa, claridad visual y alineación con el objetivo de una primera reunión comercial.
- [ ] Guardar el archivo resultante en la estructura de directorios estándar del curso para referencia en laboratorios posteriores.

---

## 4. Prerrequisitos

### Conocimientos previos

| Requisito | Descripción |
|---|---|
| Labs anteriores completados | Haber finalizado los laboratorios **01-08-01 al 01-08-05**, especialmente la ficha de preparación en Word (`Ficha_Preparacion_CarlosMendoza_CIBEST.docx`). |
| Interfaz de PowerPoint | Familiaridad básica: crear diapositivas, cambiar diseños, editar cuadros de texto, aplicar temas. |
| Perfil del prospecto | Comprensión del perfil de Carlos Mendoza: empresario logístico mexicano, ingresos ~USD 5M, interés en diversificar patrimonio hacia EE.UU., experiencia limitada en inversiones. |
| Prompting con Copilot | Experiencia básica en redacción de prompts con contexto (practicada en labs 01-08-01 a 01-08-05). |

### Acceso requerido

| Recurso | Verificación |
|---|---|
| Licencia Microsoft 365 Copilot activa | En PowerPoint: **Inicio** → verificar que el botón **Copilot** aparece en la cinta de opciones. |
| Microsoft PowerPoint 2405+ | **Archivo > Cuenta > Información del producto** → confirmar versión ≥ 2405 (Build 17628.20164). |
| Conexión a internet estable | Mínimo 10 Mbps de bajada (requerido para que Copilot procese solicitudes en la nube). |
| Acceso a OneDrive | Ruta de trabajo: `Documentos > CIBEST_CAPITAL > Prospectos`. |

---

## 5. Entorno del laboratorio

### Hardware mínimo

| Componente | Mínimo | Recomendado |
|---|---|---|
| Procesador | 64 bits (Intel Core i5 / AMD Ryzen 5) | Intel Core i7 / AMD Ryzen 7 |
| RAM | 8 GB | 16 GB |
| Espacio en disco | 10 GB libres | 20 GB libres |
| Pantalla | 1366 × 768 | 1920 × 1080 |
| Internet | 10 Mbps bajada | 25 Mbps bajada |

### Software requerido

| Software | Versión mínima |
|---|---|
| Windows | Windows 10 22H2 (Build 19045) o Windows 11 23H2 (Build 22631) |
| Microsoft PowerPoint | Versión 2405 (Build 17628.20164) — Microsoft 365 Apps for Enterprise |
| Microsoft 365 Copilot | Licencia Premium M365 Copilot (servicio en la nube, actualización continua) |
| Microsoft Edge | 124.0.2478.97 o superior (para consultas auxiliares si es necesario) |

### Configuración inicial

Antes de comenzar los pasos del laboratorio, realiza las siguientes verificaciones:

**Paso A — Verificar la versión de PowerPoint:**

1. Abre **Microsoft PowerPoint**.
2. Haz clic en **Archivo** > **Cuenta**.
3. En la sección **Información del producto**, confirma que la versión sea **2405 (Build 17628.20164)** o superior.
4. Si la versión es anterior, haz clic en **Opciones de actualización** > **Actualizar ahora** y espera a que finalice.

**Paso B — Verificar que Copilot está disponible:**

1. En PowerPoint, crea una presentación en blanco temporalmente (**Archivo** > **Nuevo** > **Presentación en blanco**).
2. En la pestaña **Inicio** de la cinta de opciones, localiza el botón **Copilot** (ícono de Copilot, generalmente en el extremo derecho de la cinta).
3. Haz clic en el botón **Copilot**. Debe abrirse el panel lateral de Copilot a la derecha de la pantalla.
4. Si el botón no aparece, verifica tu licencia con el administrador de TI.
5. Cierra esta presentación temporal sin guardar.

**Paso C — Verificar la estructura de directorios:**

1. Abre el **Explorador de archivos** de Windows.
2. Navega a **OneDrive** > **Documentos** > **CIBEST_CAPITAL** > **Prospectos**.
3. Si la carpeta no existe, créala manualmente respetando la ruta exacta: `Documentos\CIBEST_CAPITAL\Prospectos`.
4. Confirma que el archivo `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` se encuentra en esta carpeta (generado en labs anteriores).

---

## 6. Pasos del laboratorio

### Paso 1 — Crear una nueva presentación y abrir el panel de Copilot

**Objetivo:** Iniciar una presentación en blanco en PowerPoint y acceder a la funcionalidad de creación asistida por Copilot.

**Instrucciones:**

1. Abre **Microsoft PowerPoint** desde el menú Inicio o la barra de tareas.
2. Selecciona **Presentación en blanco** para crear un nuevo archivo vacío.
3. Antes de continuar, guarda el archivo inmediatamente:
   - Haz clic en **Archivo** > **Guardar como** > **OneDrive**.
   - Navega a la ruta: `Documentos > CIBEST_CAPITAL > Prospectos`.
   - Nombra el archivo exactamente como:

   ```
   Presentacion_Introductoria_CarlosMendoza_CIBEST.pptx
   ```

   - Haz clic en **Guardar**.
4. Regresa a la vista de edición de la presentación.
5. En la pestaña **Inicio** de la cinta de opciones, haz clic en el botón **Copilot** para abrir el panel lateral.
6. El panel de Copilot se abrirá a la derecha de la pantalla mostrando un campo de texto con la indicación *"¿Qué quieres hacer?"* o similar.

**Resultado esperado:** Una presentación en blanco guardada con el nombre correcto en la ruta de OneDrive especificada, con el panel de Copilot abierto y listo para recibir instrucciones.

**Verificación:**
- ✅ La barra de título de PowerPoint muestra `Presentacion_Introductoria_CarlosMendoza_CIBEST.pptx`.
- ✅ La ubicación de guardado es `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.
- ✅ El panel de Copilot está visible en el lado derecho con el campo de entrada activo.

---

### Paso 2 — Generar la estructura inicial de la presentación con un prompt contextualizado

**Objetivo:** Utilizar la funcionalidad "Crear presentación" de Copilot con un prompt que incorpore el contexto completo del prospecto para obtener una estructura base de 6-8 diapositivas.

**Instrucciones:**

1. En el panel de Copilot, localiza la opción **Crear una presentación sobre...** (o el campo de texto principal si Copilot muestra directamente el cuadro de entrada).

2. Escribe el siguiente prompt **completo** en el campo de texto de Copilot. Cópialo tal cual, sin modificar:

   ```
   Crea una presentación de 8 diapositivas para una primera reunión con un prospecto llamado Carlos Mendoza. Carlos es propietario de una empresa de logística en México con ingresos anuales de aproximadamente 5 millones de dólares. Tiene experiencia limitada en inversiones internacionales y está interesado en diversificar su patrimonio invirtiendo en activos en Estados Unidos.

   La presentación es de la firma CIBEST CAPITAL y debe incluir:
   1. Diapositiva de portada con el nombre de la firma y el propósito de la reunión
   2. Quiénes somos: breve presentación de CIBEST CAPITAL como firma de asesoría de inversiones
   3. Por qué considerar invertir en Estados Unidos: beneficios explicados de forma sencilla
   4. Cómo funciona el proceso de inversión: pasos simples y claros
   5. Tipos de opciones de inversión disponibles: explicados sin jerga técnica
   6. Cómo protegemos tu patrimonio: seguridad y regulación en lenguaje simple
   7. Qué esperar de nuestra primera conversación: agenda de la reunión
   8. Próximos pasos y datos de contacto

   IMPORTANTE: El prospecto NO tiene experiencia en finanzas ni inversiones. Todo el contenido debe usar lenguaje cotidiano, como si le explicaras a un amigo empresario. No uses términos como "rendimiento ajustado al riesgo", "diversificación de portafolio", "instrumentos de renta fija", "hedge", "asset allocation" ni ningún tecnicismo financiero. Usa analogías del mundo empresarial y logístico cuando sea posible.
   ```

3. Presiona **Enter** o haz clic en el botón de enviar (ícono de flecha).

4. Espera a que Copilot genere la presentación. Este proceso puede tomar entre 15 y 45 segundos dependiendo de la conexión.

5. Una vez generada, Copilot mostrará las diapositivas creadas en el área principal de edición. Revisa rápidamente que se hayan generado entre 6 y 8 diapositivas navegando por el panel de miniaturas a la izquierda.

6. Si Copilot genera menos de 6 diapositivas, no te preocupes; agregarás las faltantes en pasos posteriores.

**Resultado esperado:** Una presentación con aproximadamente 6-8 diapositivas que sigue la estructura solicitada. El contenido debe estar mayoritariamente en español, con un tono accesible y orientado al perfil de Carlos Mendoza. Es probable que Copilot haya incluido imágenes de stock y un tema de diseño predeterminado.

**Verificación:**
- ✅ Se generaron entre 6 y 8 diapositivas (verificar en el panel de miniaturas izquierdo).
- ✅ La diapositiva 1 (portada) menciona "CIBEST CAPITAL".
- ✅ El contenido general usa un tono conversacional y no excesivamente técnico.
- ✅ La estructura temática sigue aproximadamente el orden solicitado en el prompt.

> 💡 **Nota:** Copilot es generativo y no determinista. Tu resultado puede diferir ligeramente en redacción, número exacto de diapositivas o diseño visual. Esto es normal y esperado. Lo importante es que la estructura general y el tono sean los solicitados.

---

### Paso 3 — Auditar el contenido generado e identificar tecnicismos financieros

**Objetivo:** Revisar cada diapositiva generada por Copilot para identificar términos técnicos financieros que necesiten ser reemplazados con lenguaje accesible.

**Instrucciones:**

1. Haz clic en la **Diapositiva 1** en el panel de miniaturas de la izquierda.

2. Lee el contenido de cada diapositiva de forma secuencial (de la 1 a la última), buscando específicamente los siguientes tipos de tecnicismos:

   | Categoría de tecnicismo | Ejemplos comunes a buscar |
   |---|---|
   | Términos de rendimiento | "rendimiento ajustado al riesgo", "retorno sobre inversión (ROI)", "yield", "tasa interna de retorno" |
   | Términos de estrategia | "diversificación de portafolio", "asset allocation", "rebalanceo", "cobertura (hedge)" |
   | Tipos de instrumentos | "renta fija", "renta variable", "ETFs", "bonos del tesoro", "REITs", "derivados" |
   | Términos regulatorios | "compliance", "fiduciario", "custodia de activos", "due diligence" |
   | Términos de riesgo | "volatilidad", "drawdown", "correlación negativa", "beta del portafolio" |

3. En un **cuadro de texto temporal** al final de la presentación (inserta una diapositiva en blanco al final: **Inicio** > **Nueva diapositiva** > **En blanco**), anota los tecnicismos que encontraste. Escribe una lista simple como esta:

   ```
   TECNICISMOS ENCONTRADOS (para reformular):
   - Diapositiva 3: "diversificación de portafolio"
   - Diapositiva 4: "instrumentos de renta fija"
   - Diapositiva 5: "rendimiento ajustado al riesgo"
   - Diapositiva 6: "custodia de activos"
   [añade los que encuentres en tu versión]
   ```

4. Revisa también si alguna diapositiva tiene contenido en inglés que no debería estar (Copilot a veces mezcla idiomas). Anótalo en la misma lista.

5. Cuenta el total de tecnicismos identificados. Deberías encontrar entre **3 y 8** dependiendo de la generación específica de Copilot.

**Resultado esperado:** Una diapositiva temporal al final de la presentación con la lista de tecnicismos identificados y sus ubicaciones. Esta lista será la base para el prompt de reformulación del siguiente paso.

**Verificación:**
- ✅ Revisaste el contenido de **todas** las diapositivas generadas.
- ✅ Identificaste al menos **3 tecnicismos financieros** en el contenido.
- ✅ La diapositiva temporal con la lista está creada al final de la presentación.
- ✅ Cada tecnicismo anotado incluye el número de diapositiva donde se encuentra.

> ⚠️ **Importante:** No elimines ni modifiques manualmente los tecnicismos todavía. En el siguiente paso, usarás Copilot para reformularlos, lo cual es parte de la práctica de prompting iterativo.

---

### Paso 4 — Reformular tecnicismos usando el panel de Copilot

**Objetivo:** Utilizar el panel de Copilot en PowerPoint para solicitar la reformulación de los tecnicismos identificados, reemplazándolos con lenguaje cotidiano y analogías del mundo empresarial.

**Instrucciones:**

1. Asegúrate de que el panel de Copilot sigue abierto a la derecha. Si se cerró, haz clic en **Inicio** > **Copilot** para reabrirlo.

2. Haz clic en la **primera diapositiva que contiene un tecnicismo** según tu lista (por ejemplo, Diapositiva 3).

3. En el panel de Copilot, escribe el siguiente prompt de reformulación. **Adapta los términos específicos** según los tecnicismos que tú encontraste en tu versión:

   ```
   En esta diapositiva, reemplaza el término "diversificación de portafolio" con una explicación sencilla. En lugar de jerga financiera, usa una analogía que un empresario de logística pueda entender. Por ejemplo, compáralo con no depender de un solo cliente o una sola ruta de transporte. Mantén el tono profesional pero accesible.
   ```

4. Presiona **Enter** y espera la respuesta de Copilot. Copilot puede:
   - **Modificar directamente** el texto de la diapositiva (resultado ideal).
   - **Sugerir un texto alternativo** en el panel que deberás copiar y pegar manualmente.
   - **Ofrecer varias opciones** de reformulación.

5. Si Copilot modificó la diapositiva directamente, revisa que el cambio sea adecuado. Si ofreció texto en el panel, selecciónalo, cópialo (**Ctrl+C**) y pégalo (**Ctrl+V**) en el cuadro de texto correspondiente de la diapositiva, reemplazando el texto original.

6. Repite el proceso para **cada tecnicismo identificado** en tu lista. Para cada uno, usa un prompt similar adaptando el término específico. Aquí tienes plantillas de prompts para los tecnicismos más comunes:

   **Para "instrumentos de renta fija":**
   ```
   En esta diapositiva, reemplaza "instrumentos de renta fija" con una explicación simple. Descríbelo como "opciones de inversión que te dan pagos regulares y predecibles, como recibir una renta mensual fija de un inquilino". No uses terminología financiera.
   ```

   **Para "rendimiento ajustado al riesgo":**
   ```
   Reemplaza "rendimiento ajustado al riesgo" en esta diapositiva. Explícalo como "cuánto puedes ganar considerando qué tan segura es la inversión — similar a evaluar si una nueva ruta de transporte vale la pena considerando los costos y riesgos del camino". Usa lenguaje cotidiano.
   ```

   **Para "custodia de activos":**
   ```
   Cambia "custodia de activos" por una explicación accesible. Descríbelo como "tu dinero se guarda en instituciones financieras reguladas en Estados Unidos, como si tuvieras una bóveda de seguridad bancaria protegida por las leyes americanas". Mantén el tono de confianza.
   ```

   **Para "asset allocation":**
   ```
   Reemplaza "asset allocation" con lenguaje sencillo. Explícalo como "la forma en que distribuimos tu dinero entre diferentes tipos de inversiones, como un empresario que decide cuánto invertir en camiones, cuánto en almacenes y cuánto guardar en reserva".
   ```

7. Después de reformular todos los tecnicismos, navega por todas las diapositivas una vez más para confirmar que no queda ningún término técnico sin reformular.

**Resultado esperado:** Todas las diapositivas contienen lenguaje accesible y cotidiano. Los conceptos financieros se explican mediante analogías empresariales o logísticas. No quedan tecnicismos financieros sin reformular.

**Verificación:**
- ✅ Cada tecnicismo de tu lista fue reformulado (ya sea por Copilot directamente o con edición manual asistida).
- ✅ Las reformulaciones usan analogías del mundo empresarial o logístico.
- ✅ El tono es profesional pero accesible — como explicarle a un amigo empresario.
- ✅ No quedan términos en inglés no intencionados.
- ✅ Realizaste al menos **3 prompts de reformulación** distintos en el panel de Copilot.

---

### Paso 5 — Agregar o reorganizar diapositivas para completar la narrativa

**Objetivo:** Usar Copilot para agregar diapositivas faltantes o reorganizar el contenido, asegurando que la presentación tenga entre 6 y 8 diapositivas con una narrativa coherente de principio a fin.

**Instrucciones:**

1. Cuenta las diapositivas actuales en el panel de miniaturas (sin contar la diapositiva temporal de notas que creaste en el Paso 3).

2. **Si tienes menos de 6 diapositivas** (sin contar la temporal), usa el panel de Copilot para agregar las faltantes. Escribe el siguiente prompt:

   ```
   Agrega una diapositiva después de la diapositiva [NÚMERO] que explique [TEMA FALTANTE según la estructura del Paso 2]. Usa el mismo estilo visual y tono accesible del resto de la presentación. Recuerda: el prospecto es Carlos Mendoza, empresario de logística sin experiencia en inversiones. No uses tecnicismos.
   ```

   Reemplaza `[NÚMERO]` con la posición donde debe ir la diapositiva y `[TEMA FALTANTE]` con el contenido necesario según la estructura original de 8 diapositivas.

3. **Si tienes más de 8 diapositivas**, evalúa cuáles pueden consolidarse. Usa el siguiente prompt:

   ```
   Las diapositivas [X] y [Y] tratan temas similares. Combina su contenido en una sola diapositiva manteniendo los puntos más importantes y el lenguaje sencillo.
   ```

4. Verifica el **flujo narrativo** de la presentación. La secuencia lógica debe ser:

   | Orden | Tema | Propósito narrativo |
   |---|---|---|
   | 1 | Portada | Establecer identidad de CIBEST CAPITAL y contexto de la reunión |
   | 2 | Quiénes somos | Generar confianza inicial |
   | 3 | Por qué invertir en EE.UU. | Despertar interés con beneficios concretos |
   | 4 | Cómo funciona el proceso | Reducir incertidumbre mostrando simplicidad |
   | 5 | Opciones de inversión | Mostrar posibilidades sin abrumar |
   | 6 | Protección del patrimonio | Resolver preocupaciones de seguridad |
   | 7 | Qué esperar de la reunión | Preparar al prospecto para la conversación |
   | 8 | Próximos pasos y contacto | Cerrar con acción clara |

5. Si alguna diapositiva está fuera de orden, arrástrala a la posición correcta en el panel de miniaturas (clic sostenido + arrastrar).

6. **Elimina la diapositiva temporal** de notas que creaste en el Paso 3:
   - Haz clic derecho sobre ella en el panel de miniaturas.
   - Selecciona **Eliminar diapositiva**.

**Resultado esperado:** La presentación tiene entre 6 y 8 diapositivas (sin la temporal) con un flujo narrativo coherente que va desde la presentación de la firma hasta los próximos pasos concretos.

**Verificación:**
- ✅ La presentación tiene entre **6 y 8 diapositivas** finales.
- ✅ La diapositiva temporal de notas fue eliminada.
- ✅ El orden narrativo sigue la secuencia lógica de la tabla anterior (o una variación coherente).
- ✅ No hay diapositivas con contenido duplicado o redundante.
- ✅ La portada menciona "CIBEST CAPITAL" y la última diapositiva incluye próximos pasos o datos de contacto.

---

### Paso 6 — Refinamiento visual y coherencia final

**Objetivo:** Realizar ajustes finales de diseño y coherencia para que la presentación sea profesional, visualmente limpia y lista para una reunión con el prospecto.

**Instrucciones:**

1. **Aplica un tema de diseño consistente** (si Copilot no aplicó uno adecuado):
   - Ve a la pestaña **Diseño** en la cinta de opciones.
   - Selecciona un tema profesional con colores sobrios (azul, gris o verde oscuro son apropiados para servicios financieros).
   - Haz clic en **Variantes** para ajustar la paleta de colores si es necesario.

2. **Verifica la legibilidad del texto** en cada diapositiva:
   - Los títulos deben tener un tamaño mínimo de **28 puntos**.
   - El texto del cuerpo debe tener un tamaño mínimo de **18 puntos**.
   - No debe haber más de **5-6 viñetas** por diapositiva.
   - Si alguna diapositiva tiene demasiado texto, usa Copilot para resumirla:

     ```
     Resume el contenido de esta diapositiva en máximo 4 puntos breves. Cada punto debe tener máximo 15 palabras. Mantén el lenguaje sencillo y sin tecnicismos financieros.
     ```

3. **Revisa que las imágenes sean apropiadas:**
   - Copilot puede haber insertado imágenes de stock. Verifica que sean relevantes al contenido.
   - Si alguna imagen no es apropiada, haz clic derecho sobre ella > **Cambiar imagen** > **Imágenes de stock** y selecciona una más adecuada (busca términos como "business meeting", "investment", "logistics", "handshake").

4. **Agrega notas del orador** en al menos 3 diapositivas clave. Haz clic en el área de **Notas** debajo de cada diapositiva (si no es visible, ve a **Vista** > **Notas**) y usa Copilot para generarlas:

   ```
   Genera notas del orador para esta diapositiva. Las notas deben incluir: puntos clave a mencionar verbalmente, una pregunta para hacer a Carlos Mendoza relacionada con su negocio de logística, y un recordatorio de usar lenguaje sencillo. Máximo 5 líneas.
   ```

   Repite este prompt para al menos las diapositivas 3, 5 y 7 (o las equivalentes en tu versión).

5. **Realiza una revisión final completa:**
   - Presiona **F5** para iniciar la presentación desde el principio en modo de presentación.
   - Navega por todas las diapositivas verificando:
     - ¿El texto es legible a distancia?
     - ¿Las transiciones entre diapositivas son suaves?
     - ¿La narrativa fluye naturalmente de un tema al siguiente?
     - ¿Queda algún tecnicismo sin reformular?
   - Presiona **Esc** para salir del modo de presentación.

6. **Guarda la versión final:**
   - Presiona **Ctrl+S** para guardar.
   - Confirma que el archivo se guarda en: `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos > Presentacion_Introductoria_CarlosMendoza_CIBEST.pptx`.

**Resultado esperado:** Una presentación profesional de 6-8 diapositivas con diseño visual consistente, texto legible, lenguaje accesible, notas del orador en diapositivas clave y guardada correctamente en la ruta de trabajo del curso.

**Verificación:**
- ✅ Se aplicó un tema de diseño profesional y consistente en toda la presentación.
- ✅ Los títulos son de al menos 28 puntos y el cuerpo de al menos 18 puntos.
- ✅ Ninguna diapositiva tiene más de 6 viñetas.
- ✅ Al menos 3 diapositivas tienen notas del orador generadas con Copilot.
- ✅ La presentación se visualiza correctamente en modo de presentación (F5).
- ✅ El archivo está guardado con el nombre y ruta correctos.

---

## 7. Validación y pruebas

Utiliza la siguiente lista de verificación integral para confirmar que el laboratorio se completó exitosamente:

### Lista de verificación final

| # | Criterio | Estado |
|---|---|---|
| 1 | El archivo se llama `Presentacion_Introductoria_CarlosMendoza_CIBEST.pptx` | ☐ |
| 2 | El archivo está guardado en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos` | ☐ |
| 3 | La presentación tiene entre 6 y 8 diapositivas | ☐ |
| 4 | La portada menciona "CIBEST CAPITAL" | ☐ |
| 5 | No hay tecnicismos financieros sin reformular en ninguna diapositiva | ☐ |
| 6 | Se usaron al menos 3 analogías del mundo empresarial o logístico | ☐ |
| 7 | Se ejecutaron al menos 3 prompts de reformulación en el panel de Copilot | ☐ |
| 8 | El flujo narrativo va desde la presentación de la firma hasta los próximos pasos | ☐ |
| 9 | Al menos 3 diapositivas tienen notas del orador | ☐ |
| 10 | El diseño visual es profesional y consistente (tema aplicado, tamaños legibles) | ☐ |

### Prueba de accesibilidad del lenguaje

Realiza esta prueba rápida: lee en voz alta el contenido de la Diapositiva 5 (opciones de inversión) a un compañero o imagina que se lo lees a alguien sin formación financiera. Si en algún momento necesitas "traducir" un concepto, ese término aún necesita reformulación.

---

## 8. Solución de problemas

### Problema 1: Copilot no genera la presentación o muestra un error de tiempo de espera

**Síntomas:**
- Al enviar el prompt del Paso 2, Copilot muestra un mensaje como *"No se pudo generar la presentación"*, *"Algo salió mal, inténtalo de nuevo"* o el indicador de carga gira indefinidamente por más de 60 segundos.

**Causa:**
El prompt del Paso 2 es extenso (~200 palabras) y puede exceder los límites de procesamiento de Copilot en PowerPoint en ciertos momentos de alta demanda del servicio en la nube, o la conexión a internet puede haber sufrido una interrupción momentánea.

**Solución:**

1. Haz clic en **Reintentar** si Copilot muestra esa opción.
2. Si el error persiste, **divide el prompt en dos partes**:

   **Parte 1 — Estructura base:**
   ```
   Crea una presentación de 8 diapositivas para la firma CIBEST CAPITAL. La presentación es para una primera reunión con un prospecto llamado Carlos Mendoza, propietario de una empresa de logística en México. Incluye: portada, quiénes somos, por qué invertir en Estados Unidos, cómo funciona el proceso, opciones disponibles, protección del patrimonio, qué esperar de la reunión, y próximos pasos.
   ```

   **Parte 2 — Ajuste de tono (después de que se genere la estructura):**
   ```
   Reformula todo el contenido de esta presentación para que use lenguaje cotidiano y sencillo. El prospecto no tiene experiencia en finanzas. Elimina todos los tecnicismos financieros y reemplázalos con explicaciones simples y analogías del mundo empresarial. No uses términos como "rendimiento ajustado al riesgo", "diversificación de portafolio", "renta fija" ni "asset allocation".
   ```

3. Si el problema continúa, verifica tu conexión a internet (abre Edge y navega a cualquier sitio web).
4. Como último recurso, cierra PowerPoint completamente, espera 30 segundos, vuelve a abrir el archivo guardado y reintenta.

---

### Problema 2: Copilot no modifica la diapositiva directamente al solicitar reformulaciones

**Síntomas:**
- En el Paso 4, al pedir a Copilot que reformule un tecnicismo en una diapositiva específica, Copilot responde con texto sugerido en el panel lateral pero **no modifica** el contenido de la diapositiva automáticamente. El texto original con el tecnicismo permanece sin cambios.

**Causa:**
En la versión actual de Copilot en PowerPoint (mayo 2025), la capacidad de edición directa de diapositivas existentes desde el panel de Copilot puede comportarse de forma inconsistente. Copilot en PowerPoint está optimizado para **crear** contenido nuevo (diapositivas completas) más que para **editar** texto dentro de diapositivas existentes. En muchos casos, Copilot ofrece la reformulación como sugerencia textual en el panel en lugar de aplicarla directamente.

**Solución:**

1. **Método preferido — Copiar y pegar manualmente:**
   - Lee la sugerencia de Copilot en el panel lateral.
   - Selecciona el texto sugerido en el panel, cópialo (**Ctrl+C**).
   - Haz clic en el cuadro de texto de la diapositiva que contiene el tecnicismo.
   - Selecciona el texto que deseas reemplazar.
   - Pega el texto nuevo (**Ctrl+V**).
   - Ajusta el formato (tamaño de fuente, color) si se perdió durante el pegado.

2. **Método alternativo — Solicitar una diapositiva nueva completa:**
   - En lugar de pedir la reformulación de un término, solicita a Copilot que **regenere la diapositiva completa**:
   ```
   Crea una nueva diapositiva que reemplace la diapositiva [NÚMERO] actual. El tema es [TEMA]. Usa exactamente el mismo contenido pero reemplaza todos los tecnicismos financieros con lenguaje cotidiano y analogías empresariales. El prospecto es un empresario de logística sin experiencia en inversiones.
   ```
   - Una vez generada la nueva diapositiva, elimina la original (clic derecho > **Eliminar diapositiva**) y arrastra la nueva a la posición correcta.

3. Recuerda que este comportamiento es una limitación conocida y no un error de tu configuración. La habilidad de saber cuándo usar Copilot para generar vs. cuándo editar manualmente es parte de la competencia profesional con estas herramientas.

---

## 9. Limpieza

Al finalizar el laboratorio, realiza las siguientes acciones:

1. **Guarda la versión final** de la presentación: presiona **Ctrl+S**.

2. **Verifica la ubicación del archivo:**
   - Abre el Explorador de archivos.
   - Navega a `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.
   - Confirma que el archivo `Presentacion_Introductoria_CarlosMendoza_CIBEST.pptx` aparece en la lista con la fecha y hora de modificación actuales.

3. **No elimines el archivo.** Este será referenciado conceptualmente en el laboratorio **01-08-07** (Excel — matriz de necesidades) y puede ser utilizado en laboratorios del Batch 2.

4. **Cierra el panel de Copilot** haciendo clic en el botón **Copilot** de la cinta (o en la **X** del panel) para liberar espacio visual.

5. **Opcional:** Si deseas conservar un registro de los prompts utilizados, abre un archivo de texto en el Bloc de notas y copia los prompts que escribiste durante el laboratorio. Guárdalo como:

   ```
   Prompts_Lab_01-08-06_PowerPoint.txt
   ```

   en la misma ruta: `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.

---

## 10. Resumen

En este laboratorio aplicaste Microsoft 365 Copilot en PowerPoint para crear una presentación introductoria profesional adaptada a un prospecto específico. Los aprendizajes clave incluyen:

| Competencia desarrollada | Detalle |
|---|---|
| **Prompting contextualizado** | Redactaste un prompt inicial que incorporaba el perfil completo del prospecto (nombre, sector, nivel de experiencia, intereses) para obtener contenido relevante desde la primera generación. |
| **Auditoría de contenido IA** | Revisaste críticamente el contenido generado por Copilot para identificar tecnicismos financieros que no son apropiados para la audiencia objetivo. |
| **Iteración con Copilot** | Ejecutaste múltiples prompts de reformulación para reemplazar jerga técnica con analogías del mundo empresarial y lenguaje cotidiano. |
| **Adaptación a la audiencia** | Aplicaste el principio de que el material de una primera reunión debe eliminar barreras de comprensión, especialmente con prospectos sin experiencia financiera. |
| **Flujo de trabajo integrado** | Generaste un artefacto (presentación) que se conecta con la ficha de preparación de Word (labs anteriores) y alimentará la matriz de necesidades en Excel (lab siguiente). |

### Conexión con el siguiente laboratorio

La presentación creada en este laboratorio establece las **categorías temáticas** que se utilizarán en el laboratorio **01-08-07** para construir la matriz de necesidades del prospecto en Excel. Las secciones de la presentación (quiénes somos, por qué EE.UU., opciones de inversión, protección, etc.) se convertirán en categorías de la matriz para clasificar información conocida y pendiente sobre Carlos Mendoza.

### Recursos adicionales

- [Usar Copilot en PowerPoint — Documentación oficial de Microsoft](https://support.microsoft.com/es-es/office/usar-copilot-en-microsoft-powerpoint-a1b5f360-e29f-4706-a77c-e9b8b1c8b5c0)
- [Mejores prácticas para crear presentaciones con Copilot](https://learn.microsoft.com/es-es/copilot/microsoft-365/microsoft-365-copilot-user-guide)
- [Guía de adopción de Microsoft 365 Copilot — Escenarios de ventas](https://adoption.microsoft.com/es-es/copilot/)
- [Principios de diseño de presentaciones para audiencias no técnicas — Garr Reynolds, *Presentation Zen*](https://www.presentationzen.com/)

---

---

# Práctica guiada en Excel con Copilot: construcción de matriz de necesidades del prospecto con clasificación de información conocida y pendiente

## Metadatos del laboratorio

| Campo | Detalle |
|---|---|
| **Duración** | 18 minutos |
| **Complejidad** | Media |
| **Nivel Bloom** | Aplicar (*Apply*) |
| **Laboratorio previo requerido** | 01-08-06 (Presentación PowerPoint con Copilot) |
| **Archivo de salida** | `Matriz_Necesidades_CarlosMendoza_CIBEST.xlsx` |
| **Ruta de guardado** | `Documentos > CIBEST_CAPITAL > Prospectos` |

---

## Descripción general

En este laboratorio construirás una matriz estructurada en Microsoft Excel que organiza las necesidades del prospecto **Carlos Mendoza** en seis categorías clave de análisis financiero. Utilizarás **Copilot en Excel** para generar la estructura inicial, poblar filas con información derivada del perfil del prospecto, clasificar cada elemento como *Información conocida* o *Por confirmar*, y aplicar formato condicional para resaltar visualmente los vacíos de información. La matriz resultante será el documento de referencia central para los laboratorios de seguimiento en Outlook (01-08-08 y 01-08-09), donde determinarás qué información solicitar a Carlos Mendoza y qué puntos abordar en la comunicación de seguimiento.

---

## Objetivos de aprendizaje

Al completar este laboratorio serás capaz de:

- [ ] Construir una matriz estructurada en Excel con seis categorías de análisis de necesidades del prospecto (objetivo de inversión, horizonte temporal, necesidades de liquidez, experiencia previa, tolerancia al riesgo e información pendiente), utilizando Copilot para generar la estructura inicial y sugerir contenido.
- [ ] Clasificar cada elemento de la matriz como **Información conocida** o **Por confirmar**, estableciendo una base de datos de trabajo funcional para el equipo de CIBEST CAPITAL.
- [ ] Aplicar formato condicional con asistencia de Copilot para resaltar visualmente las celdas marcadas como *Por confirmar*, facilitando la identificación rápida de vacíos informativos.
- [ ] Utilizar las capacidades de análisis de Copilot en Excel para identificar categorías con mayor proporción de información pendiente y generar un resumen ejecutivo de la matriz.

---

## Prerrequisitos

### Conocimientos previos

| Requisito | Descripción |
|---|---|
| Laboratorios anteriores completados | Haber finalizado los labs 01-08-04 (ficha de preparación en Word) y 01-08-06 (presentación PowerPoint). Tener disponible el archivo `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` como referencia de contenido. |
| Perfil del prospecto | Conocer el perfil de Carlos Mendoza: propietario de empresa de logística en México, ingresos anuales ~USD 5M, interés en diversificar patrimonio con activos en EE.UU., experiencia limitada en inversiones internacionales. |
| Seis categorías de análisis | Comprender las categorías trabajadas en labs previos: objetivo de inversión, horizonte temporal, necesidades de liquidez, experiencia previa, tolerancia al riesgo e información pendiente. |
| Habilidades básicas de Excel | Crear tablas, ingresar datos en celdas, aplicar formato básico, usar `Ctrl+T` para formatear como tabla. |

### Acceso y licencias

| Recurso | Requisito |
|---|---|
| Microsoft Excel | Versión 2405 (Build 17628.20164) o superior — incluido en Microsoft 365 Apps for Enterprise |
| Microsoft 365 Copilot | Licencia Premium M365 Copilot activa y funcional en Excel |
| OneDrive | Acceso a la ruta `Documentos > CIBEST_CAPITAL > Prospectos` |
| Conexión a internet | Mínimo 10 Mbps (requerida para funcionalidades de Copilot en la nube) |

---

## Entorno del laboratorio

### Hardware mínimo

| Componente | Especificación |
|---|---|
| Procesador | 64 bits — Intel Core i5 / AMD Ryzen 5 o superior |
| RAM | 8 GB mínimo (16 GB recomendado) |
| Pantalla | 1366×768 mínimo (1920×1080 recomendado) |
| Espacio en disco | 10 GB libres mínimo |
| Periféricos | Teclado y ratón/trackpad funcionales |

### Software requerido

| Software | Versión |
|---|---|
| Windows | Windows 10 22H2 (Build 19045) o Windows 11 23H2 (Build 22631) o superior |
| Microsoft Excel | Versión 2405 (Build 17628.20164) o superior |
| Microsoft 365 Copilot | Licencia Premium (servicio en la nube, actualización continua) |
| Microsoft Edge | 124.0.2478.97 o superior (para consulta de referencia) |

### Verificación inicial del entorno

Antes de comenzar, confirma que tu entorno está correctamente configurado:

1. **Verificar versión de Excel**: Abre Excel → **Archivo** → **Cuenta** → **Información del producto**. Confirma que la versión sea **2405 (Build 17628.20164)** o superior.

2. **Verificar Copilot activo en Excel**: Abre un libro en blanco en Excel. En la cinta de opciones (pestaña **Inicio**), busca el botón **Copilot** en el extremo derecho. Si el botón aparece visible y habilitado, Copilot está activo.

3. **Verificar ruta de OneDrive**: En el Explorador de archivos, navega a `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`. Si la carpeta no existe, créala ahora:
   - Haz clic derecho en `Documentos` → **Nuevo** → **Carpeta** → nombra `CIBEST_CAPITAL`.
   - Dentro de `CIBEST_CAPITAL`, crea la subcarpeta `Prospectos`.

4. **Tener disponible la ficha de referencia**: Confirma que el archivo `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` esté accesible en la ruta `Documentos > CIBEST_CAPITAL > Prospectos`. Si lo necesitas, ábrelo en una ventana separada de Word para consulta rápida durante el laboratorio.

---

## Instrucciones paso a paso

### Paso 1 — Crear el libro de Excel y guardarlo en la ruta correcta

**Objetivo**: Crear un nuevo libro de Excel y guardarlo con el nombre estandarizado en la ubicación correcta de OneDrive para garantizar la persistencia y accesibilidad del archivo en laboratorios futuros.

**Instrucciones**:

1. Abre **Microsoft Excel** desde el menú Inicio o la barra de tareas.
2. Selecciona **Libro en blanco** para crear un nuevo archivo.
3. Inmediatamente, guarda el archivo:
   - Presiona `Ctrl+Mayús+S` (Guardar como).
   - Navega a la ubicación: **OneDrive** → **Documentos** → **CIBEST_CAPITAL** → **Prospectos**.
   - En el campo **Nombre de archivo**, escribe exactamente:
     ```
     Matriz_Necesidades_CarlosMendoza_CIBEST
     ```
   - Asegúrate de que el formato sea **Libro de Excel (.xlsx)**.
   - Haz clic en **Guardar**.
4. Verifica que en la barra de título de Excel aparezca el nombre del archivo y la indicación de que está guardado en OneDrive (icono de nube o texto "Guardado" junto al nombre).

**Resultado esperado**: Un archivo llamado `Matriz_Necesidades_CarlosMendoza_CIBEST.xlsx` guardado en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`, con autoguardado habilitado.

**Verificación**: La barra de título muestra `Matriz_Necesidades_CarlosMendoza_CIBEST.xlsx` con el indicador de autoguardado activado (interruptor en posición **Activado** en la esquina superior izquierda).

---

### Paso 2 — Crear la estructura base de la tabla e ingresarla manualmente

**Objetivo**: Definir los encabezados de columna de la matriz de necesidades e ingresar las seis categorías principales como filas iniciales, formateando los datos como tabla de Excel para habilitar la compatibilidad completa con Copilot.

**Instrucciones**:

1. En la celda **A1**, escribe: `Categoría`
2. En la celda **B1**, escribe: `Subcategoría`
3. En la celda **C1**, escribe: `Información disponible`
4. En la celda **D1**, escribe: `Estado`
5. En la celda **E1**, escribe: `Fuente de información`
6. En la celda **F1**, escribe: `Notas`
7. Ahora ingresa las seis categorías principales en la columna A, comenzando en la celda **A2**:

   | Celda | Contenido |
   |---|---|
   | A2 | `Objetivo de inversión` |
   | A3 | `Horizonte temporal` |
   | A4 | `Necesidades de liquidez` |
   | A5 | `Experiencia previa` |
   | A6 | `Tolerancia al riesgo` |
   | A7 | `Información pendiente` |

8. Selecciona el rango **A1:F7** (haz clic en A1, mantén presionado `Shift` y haz clic en F7).
9. Presiona **`Ctrl+T`** para formatear como tabla.
10. En el cuadro de diálogo que aparece, asegúrate de que la casilla **"La tabla tiene encabezados"** esté marcada ✅.
11. Haz clic en **Aceptar**.
12. Excel aplicará un estilo de tabla con bandas de color alternas. Opcionalmente, en la pestaña **Diseño de tabla** que aparece, puedes seleccionar un estilo visual que prefieras (se recomienda un estilo con colores de la gama azul para consistencia con la marca CIBEST CAPITAL).

**Resultado esperado**: Una tabla de Excel formateada con 6 columnas (Categoría, Subcategoría, Información disponible, Estado, Fuente de información, Notas) y 6 filas de datos con las categorías principales. La tabla muestra flechas de filtro en los encabezados y bandas de color alternas.

**Verificación**:
- Al hacer clic en cualquier celda de la tabla, aparece la pestaña contextual **Diseño de tabla** en la cinta.
- Las flechas desplegables de autofiltro son visibles en la fila de encabezados (fila 1).
- El botón **Copilot** en la cinta de opciones permanece habilitado (no grisado) cuando la tabla está seleccionada.

---

### Paso 3 — Utilizar Copilot para poblar la matriz con información del prospecto

**Objetivo**: Usar Copilot en Excel para generar contenido en las columnas de Subcategoría, Información disponible, Estado, Fuente de información y Notas, basándose en el perfil conocido de Carlos Mendoza.

**Instrucciones**:

1. Haz clic en cualquier celda dentro de la tabla (por ejemplo, **A2**).
2. Haz clic en el botón **Copilot** en la cinta de opciones (pestaña **Inicio**, extremo derecho). Se abrirá el panel lateral de Copilot.
3. En el campo de texto del panel de Copilot, escribe el siguiente prompt completo:

   ```
   Tengo una tabla con las categorías de análisis de necesidades de un prospecto de inversión llamado Carlos Mendoza. Este es su perfil:

   - Propietario de una empresa de logística en México
   - Ingresos anuales aproximados: USD 5 millones
   - Interés en diversificar su patrimonio invirtiendo en activos en Estados Unidos
   - Experiencia limitada en inversiones internacionales
   - Es prospecto de la firma CIBEST CAPITAL

   Para cada categoría en mi tabla (Objetivo de inversión, Horizonte temporal, Necesidades de liquidez, Experiencia previa, Tolerancia al riesgo, Información pendiente), necesito que me ayudes a completar las siguientes columnas:

   1. Subcategoría: un aspecto específico dentro de cada categoría
   2. Información disponible: lo que sabemos o podemos inferir del perfil
   3. Estado: "Conocido" si la información se puede derivar del perfil, o "Por confirmar" si necesitamos validarla con el prospecto
   4. Fuente de información: de dónde proviene el dato (perfil inicial, inferencia, pendiente de reunión)
   5. Notas: observaciones adicionales o preguntas de descubrimiento sugeridas

   Por favor genera los datos como una tabla que pueda copiar a mi hoja de Excel. Incluye al menos 2 subcategorías por cada categoría principal, para un total mínimo de 12 filas.
   ```

4. Presiona **Enter** o haz clic en el botón de enviar.
5. Copilot generará una respuesta con una tabla de datos. **Lee cuidadosamente** la respuesta generada antes de aplicarla.

   > ⚠️ **Nota importante**: Copilot en Excel puede responder de diferentes maneras dependiendo de la versión y la configuración. Puede generar la tabla directamente en el panel, ofrecer insertarla como nuevas filas, o proporcionar instrucciones para copiar y pegar. Sigue las indicaciones que Copilot te presente.

6. Si Copilot genera una tabla en el panel lateral:
   - Revisa que las categorías coincidan con las seis definidas.
   - Selecciona y copia la tabla generada (`Ctrl+C`).
   - En tu hoja de Excel, selecciona la celda **A2**.
   - Pega los datos (`Ctrl+V`).
   - Si los datos se pegan fuera de la tabla, selecciona todo el rango con datos y vuelve a formatear como tabla con `Ctrl+T`.

7. Si Copilot ofrece un botón para **insertar** o **aplicar** los datos directamente en la tabla, haz clic en ese botón.

8. Una vez que los datos estén en la hoja, revisa y ajusta manualmente según sea necesario. A continuación se muestra la **tabla de referencia** con los datos esperados. Si Copilot generó contenido diferente, usa esta tabla como guía para completar o corregir:

   | Categoría | Subcategoría | Información disponible | Estado | Fuente de información | Notas |
   |---|---|---|---|---|---|
   | Objetivo de inversión | Diversificación patrimonial | Desea invertir en activos en EE.UU. para diversificar fuera de México | Conocido | Perfil inicial del prospecto | Confirmar montos específicos disponibles para inversión |
   | Objetivo de inversión | Preservación de capital vs. crecimiento | No especificado; perfil sugiere interés en crecimiento con protección | Por confirmar | Inferencia del perfil | Preguntar si prioriza crecimiento agresivo o preservación |
   | Horizonte temporal | Plazo de inversión deseado | No especificado; como empresario activo, posiblemente mediano-largo plazo (5-15 años) | Por confirmar | Inferencia | Determinar si tiene metas con fecha específica (retiro, sucesión) |
   | Horizonte temporal | Etapa de vida financiera | Empresario activo con negocio en operación | Conocido | Perfil inicial del prospecto | Evaluar planes de sucesión o venta del negocio |
   | Necesidades de liquidez | Flujo de efectivo del negocio | Ingresos anuales ~USD 5M; requiere liquidez operativa para la empresa | Conocido | Perfil inicial del prospecto | Determinar qué porcentaje del flujo puede destinar a inversiones |
   | Necesidades de liquidez | Acceso a fondos invertidos | No especificado; necesidad de acceso rápido desconocida | Por confirmar | Pendiente de reunión | Preguntar sobre compromisos financieros a corto plazo |
   | Experiencia previa | Inversiones nacionales | No detallada; como empresario exitoso, probable experiencia básica en México | Por confirmar | Inferencia | Preguntar sobre inversiones actuales en México (bienes raíces, depósitos, etc.) |
   | Experiencia previa | Inversiones internacionales | Experiencia limitada en inversiones internacionales | Conocido | Perfil inicial del prospecto | Adaptar explicaciones a nivel introductorio; evitar tecnicismos |
   | Tolerancia al riesgo | Perfil de riesgo subjetivo | No evaluado formalmente; empresario sugiere tolerancia moderada-alta | Por confirmar | Inferencia | Aplicar cuestionario de perfil de riesgo en la reunión |
   | Tolerancia al riesgo | Capacidad de absorber pérdidas | Ingresos de USD 5M sugieren capacidad financiera, pero no se conoce patrimonio neto | Por confirmar | Pendiente de reunión | Solicitar información patrimonial general para evaluar capacidad |
   | Información pendiente | Estructura fiscal | Desconocida; crítica para inversiones transfronterizas México-EE.UU. | Por confirmar | Pendiente de reunión | Preguntar si tiene asesor fiscal y estructura corporativa internacional |
   | Información pendiente | Beneficiarios y planificación sucesoria | No se tiene información sobre familia o planes de herencia | Por confirmar | Pendiente de reunión | Tema sensible; abordar con tacto en reunión presencial |

9. Verifica que tu tabla contenga **al menos 12 filas de datos** (sin contar los encabezados). Si tienes menos, agrega filas manualmente usando la tabla de referencia anterior.

10. Presiona `Ctrl+S` para guardar.

**Resultado esperado**: La tabla de Excel contiene al menos 12 filas con datos distribuidos en las seis categorías. Cada fila tiene contenido en las seis columnas. La columna **Estado** muestra una mezcla de valores "Conocido" y "Por confirmar".

**Verificación**:
- Cuenta las filas de datos: deben ser **12 o más**.
- La columna **Estado** (D) contiene únicamente los valores "Conocido" o "Por confirmar" (sin variaciones ortográficas).
- Cada categoría principal tiene al menos 2 filas asociadas.
- Los datos en la columna **Información disponible** son coherentes con el perfil de Carlos Mendoza.

---

### Paso 4 — Estandarizar los valores de la columna Estado

**Objetivo**: Asegurar que la columna Estado contenga únicamente los dos valores permitidos ("Conocido" y "Por confirmar") escritos de forma consistente, lo cual es requisito para que el formato condicional funcione correctamente en el paso siguiente.

**Instrucciones**:

1. Haz clic en la flecha de filtro del encabezado **Estado** (columna D).
2. Revisa los valores únicos que aparecen en el menú desplegable. Deben ser exactamente:
   - `Conocido`
   - `Por confirmar`
3. Si aparecen variaciones (por ejemplo, "conocido" en minúscula, "Por Confirmar" con mayúsculas diferentes, "Pendiente", "Desconocido", etc.), cierra el filtro y corrige manualmente cada celda para que contenga exactamente uno de los dos valores permitidos.
4. Para corregir rápidamente, puedes usar **Buscar y reemplazar** (`Ctrl+H`):
   - En **Buscar**: escribe la variación incorrecta (por ejemplo, `Pendiente`).
   - En **Reemplazar con**: escribe `Por confirmar`.
   - Haz clic en **Opciones** y marca la casilla **Coincidir con el contenido de toda la celda** si está disponible.
   - Haz clic en **Reemplazar todos**.
   - Repite para cada variación que necesites corregir.
5. Vuelve a verificar con el filtro de la columna Estado que solo existan los dos valores correctos.

**Resultado esperado**: La columna Estado contiene exclusivamente los valores "Conocido" y "Por confirmar", escritos de forma idéntica en todas las celdas.

**Verificación**: Al hacer clic en la flecha de filtro de la columna Estado, el menú desplegable muestra exactamente dos opciones: "Conocido" y "Por confirmar".

---

### Paso 5 — Aplicar formato condicional para resaltar información pendiente

**Objetivo**: Configurar formato condicional en la columna Estado para que las celdas con valor "Por confirmar" se resalten visualmente con un fondo de color, facilitando la identificación inmediata de vacíos informativos.

**Instrucciones**:

1. Selecciona todas las celdas de datos en la columna **Estado** (D). Para hacerlo:
   - Haz clic en la celda **D2**.
   - Presiona `Ctrl+Mayús+Fin` para seleccionar hasta la última celda con datos en esa columna. Alternativamente, selecciona manualmente desde **D2** hasta la última fila con datos (por ejemplo, **D13** si tienes 12 filas).
   - **Importante**: No incluyas el encabezado (D1) en la selección.

2. Ve a la pestaña **Inicio** en la cinta de opciones.

3. Haz clic en **Formato condicional** → **Reglas para resaltar celdas** → **Texto que contiene…**

4. En el cuadro de diálogo:
   - En el campo de texto, escribe: `Por confirmar`
   - En el menú desplegable de formato, selecciona **Relleno rojo claro con texto rojo oscuro**.
   - Haz clic en **Aceptar**.

5. Ahora aplica una segunda regla para las celdas "Conocido":
   - Con las mismas celdas seleccionadas (D2 hasta la última fila), ve a **Formato condicional** → **Reglas para resaltar celdas** → **Texto que contiene…**
   - Escribe: `Conocido`
   - Selecciona **Relleno verde con texto verde oscuro**.
   - Haz clic en **Aceptar**.

6. Opcionalmente, extiende el formato condicional a la **fila completa** para mayor impacto visual:
   - Selecciona todo el rango de datos de la tabla (por ejemplo, **A2:F13**).
   - Ve a **Formato condicional** → **Nueva regla…**
   - Selecciona **"Utilice una fórmula que determine las celdas a las que se aplica formato"**.
   - En el campo de fórmula, escribe:
     ```
     =$D2="Por confirmar"
     ```
   - Haz clic en **Formato…** → pestaña **Relleno** → selecciona un color **amarillo claro** o **naranja pálido**.
   - Haz clic en **Aceptar** dos veces.
   - Esto resaltará la fila completa de cualquier elemento pendiente de confirmar.

7. Presiona `Ctrl+S` para guardar.

**Resultado esperado**: Las celdas de la columna Estado con valor "Por confirmar" aparecen con fondo rojo claro y texto rojo oscuro. Las celdas con valor "Conocido" aparecen con fondo verde y texto verde oscuro. Si se aplicó la regla opcional, las filas completas de elementos pendientes tienen un fondo de color adicional.

**Verificación**:
- Visualmente, la tabla muestra una clara diferenciación de colores entre información conocida (verde) y pendiente (rojo/naranja).
- Haz clic en **Formato condicional** → **Administrar reglas…** para confirmar que las reglas están aplicadas al rango correcto. Deben aparecer al menos 2 reglas (3 si aplicaste la regla opcional de fila completa).

---

### Paso 6 — Usar Copilot para solicitar subcategorías adicionales y preguntas de descubrimiento

**Objetivo**: Aprovechar Copilot para enriquecer la matriz con subcategorías adicionales relevantes y preguntas de descubrimiento específicas que el equipo de CIBEST CAPITAL debería formular a Carlos Mendoza.

**Instrucciones**:

1. Asegúrate de que el panel de Copilot esté abierto. Si no lo está, haz clic en el botón **Copilot** en la cinta.

2. Escribe el siguiente prompt en el panel de Copilot:

   ```
   Analiza mi tabla actual de necesidades del prospecto Carlos Mendoza. Basándote en las categorías existentes, sugiere 4 subcategorías adicionales que serían relevantes para un asesor de inversiones de CIBEST CAPITAL que prepara una primera reunión con este prospecto. Para cada subcategoría sugerida, incluye:
   - La categoría principal a la que pertenece
   - La subcategoría propuesta
   - Una pregunta de descubrimiento específica que se debería hacer al prospecto
   - El estado sería "Por confirmar" ya que son elementos nuevos

   Presenta la información en formato de tabla con las mismas columnas que mi tabla actual.
   ```

3. Presiona **Enter** y espera la respuesta de Copilot.

4. Revisa las sugerencias de Copilot. Ejemplos de subcategorías adicionales que Copilot podría sugerir:

   | Categoría | Subcategoría sugerida | Pregunta de descubrimiento |
   |---|---|---|
   | Objetivo de inversión | Generación de ingresos pasivos | ¿Le interesa recibir ingresos regulares de sus inversiones o prefiere reinvertir las ganancias? |
   | Necesidades de liquidez | Compromisos de deuda empresarial | ¿Tiene deudas o compromisos financieros significativos en su empresa que limiten su capacidad de inversión? |
   | Tolerancia al riesgo | Experiencia con volatilidad | ¿Ha experimentado pérdidas significativas en inversiones anteriores? ¿Cómo reaccionó? |
   | Información pendiente | Situación migratoria y fiscal en EE.UU. | ¿Tiene visa, residencia o ciudadanía estadounidense que afecte su situación fiscal? |

5. Selecciona las sugerencias más relevantes (al menos **3 de las 4**) e incorpóralas a tu tabla:
   - Posiciona el cursor en la primera celda vacía debajo de la última fila de datos en la columna A.
   - Ingresa los datos manualmente o copia desde la respuesta de Copilot.
   - Asegúrate de que las nuevas filas se integren automáticamente en la tabla formateada. Si no se integran (no muestran el formato de bandas), haz clic derecho en la última fila de la tabla → **Insertar** → **Fila de tabla debajo**, y luego ingresa los datos.

6. Para las nuevas filas, establece:
   - **Estado**: `Por confirmar`
   - **Fuente de información**: `Sugerencia de Copilot — pendiente de reunión`
   - **Notas**: Copia la pregunta de descubrimiento sugerida por Copilot.

7. Presiona `Ctrl+S` para guardar.

**Resultado esperado**: La tabla ahora contiene **15 o más filas** de datos, con al menos 3 subcategorías nuevas sugeridas por Copilot. Las nuevas filas tienen el formato condicional aplicado automáticamente (mostrándose en rojo/naranja ya que son "Por confirmar").

**Verificación**:
- Las nuevas filas muestran el formato condicional rojo para "Por confirmar".
- La columna Notas de las nuevas filas contiene preguntas de descubrimiento específicas y accionables.
- Las nuevas subcategorías son relevantes para el contexto de inversión internacional del prospecto.

---

### Paso 7 — Solicitar a Copilot un análisis de la matriz y resumen ejecutivo

**Objetivo**: Utilizar las capacidades de análisis de Copilot en Excel para obtener un resumen ejecutivo que identifique las categorías con mayor proporción de información pendiente y proporcione una visión general del estado de preparación para la reunión con Carlos Mendoza.

**Instrucciones**:

1. Con el panel de Copilot abierto, escribe el siguiente prompt:

   ```
   Analiza los datos de mi tabla y responde lo siguiente:
   1. ¿Cuántas filas tienen estado "Conocido" y cuántas tienen estado "Por confirmar"?
   2. ¿Qué categoría principal tiene la mayor proporción de información pendiente por confirmar?
   3. Genera un resumen ejecutivo de 5-6 oraciones que describa el estado de preparación del equipo de CIBEST CAPITAL para la reunión con el prospecto Carlos Mendoza, basándote en la información de esta matriz.
   ```

2. Presiona **Enter** y espera la respuesta.

3. Copilot debería proporcionar:
   - Un conteo de filas por estado (esperado: aproximadamente 4-5 "Conocido" y 10-11 "Por confirmar").
   - La identificación de la categoría con más vacíos (probablemente "Información pendiente" o "Tolerancia al riesgo").
   - Un resumen ejecutivo narrativo.

4. **Copia el resumen ejecutivo** generado por Copilot:
   - Selecciona el texto del resumen en el panel de Copilot.
   - Presiona `Ctrl+C`.

5. Crea una nueva hoja en el libro de Excel:
   - Haz clic en el botón **+** junto a la pestaña de la hoja actual (parte inferior de la pantalla).
   - Haz doble clic en la pestaña de la nueva hoja y renómbrala como: `Resumen Ejecutivo`

6. En la celda **A1** de la nueva hoja, escribe: `RESUMEN EJECUTIVO — Matriz de Necesidades: Carlos Mendoza`
7. Aplica formato de **Negrita** (`Ctrl+B`) y tamaño de fuente **14**.
8. En la celda **A3**, pega el resumen de Copilot (`Ctrl+V`).
9. En la celda **A5**, escribe: `Fecha de elaboración:`
10. En la celda **B5**, ingresa la fecha actual con `Ctrl+;` (punto y coma).
11. En la celda **A6**, escribe: `Elaborado por:`
12. En la celda **B6**, escribe: `Equipo CIBEST CAPITAL — Asistido por Microsoft 365 Copilot`

13. Presiona `Ctrl+S` para guardar.

**Resultado esperado**: El libro de Excel contiene dos hojas: (1) la hoja principal con la tabla de la matriz de necesidades formateada con colores condicionales, y (2) una hoja "Resumen Ejecutivo" con el análisis generado por Copilot, la fecha y la atribución.

**Verificación**:
- La pestaña "Resumen Ejecutivo" es visible en la parte inferior del libro.
- El resumen ejecutivo en la celda A3 contiene un texto coherente de 5-6 oraciones que describe el estado de preparación.
- La fecha actual aparece correctamente en B5.

---

### Paso 8 — Ajustes finales de formato y guardado definitivo

**Objetivo**: Aplicar ajustes finales de formato profesional a la matriz y confirmar que el archivo está correctamente guardado y listo para uso en los laboratorios siguientes.

**Instrucciones**:

1. Regresa a la primera hoja (haz clic en la pestaña **Hoja1** o el nombre que tenga).
2. Renombra la pestaña de la hoja principal:
   - Haz doble clic en la pestaña → escribe: `Matriz de Necesidades`
   - Presiona **Enter**.

3. Ajusta el ancho de las columnas para que todo el contenido sea legible:
   - Selecciona todas las columnas de la tabla: haz clic en el encabezado de columna **A**, mantén presionado **Shift** y haz clic en el encabezado de columna **F**.
   - Ve a la pestaña **Inicio** → grupo **Celdas** → **Formato** → **Autoajustar ancho de columna**.

4. Aplica ajuste de texto en las columnas de contenido extenso:
   - Selecciona las columnas **C** (Información disponible) y **F** (Notas): haz clic en el encabezado de columna **C**, mantén presionado **Ctrl** y haz clic en el encabezado de columna **F**.
   - En la pestaña **Inicio**, haz clic en **Ajustar texto** (icono en el grupo Alineación).
   - Opcionalmente, establece un ancho fijo para estas columnas: selecciona la columna → **Formato** → **Ancho de columna…** → escribe `35` → **Aceptar**.

5. Congela la fila de encabezados para facilitar la navegación:
   - Haz clic en la celda **A2**.
   - Ve a la pestaña **Vista** → **Inmovilizar paneles** → **Inmovilizar fila superior**.

6. Agrega un encabezado de impresión (opcional pero profesional):
   - Ve a **Insertar** → **Encabezado y pie de página**.
   - En la sección central del encabezado, escribe: `CIBEST CAPITAL — Matriz de Necesidades del Prospecto: Carlos Mendoza`
   - Haz clic fuera del área de encabezado para regresar a la vista normal.
   - Ve a **Vista** → **Normal** para regresar a la vista estándar.

7. Guarda el archivo definitivamente: presiona `Ctrl+S`.

8. Verifica la ubicación final del archivo:
   - Ve a **Archivo** → **Información**.
   - Confirma que la ubicación muestra: `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.

**Resultado esperado**: Un libro de Excel profesionalmente formateado con dos hojas ("Matriz de Necesidades" y "Resumen Ejecutivo"), formato condicional activo, columnas con ancho apropiado, texto ajustado y fila de encabezados inmovilizada. El archivo está guardado en la ruta correcta de OneDrive.

**Verificación**:
- Las pestañas de las hojas muestran los nombres "Matriz de Necesidades" y "Resumen Ejecutivo".
- Al hacer scroll hacia abajo, la fila de encabezados permanece visible (inmovilizada).
- El formato condicional sigue activo: las celdas "Por confirmar" se muestran en rojo y las "Conocido" en verde.
- La ruta del archivo en **Archivo > Información** corresponde a `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`.

---

## Validación y pruebas

Realiza las siguientes comprobaciones finales para confirmar que el laboratorio se completó exitosamente:

| # | Criterio de validación | Método de verificación | ✅ |
|---|---|---|---|
| 1 | El archivo se llama `Matriz_Necesidades_CarlosMendoza_CIBEST.xlsx` | Verificar nombre en barra de título o Archivo > Información | ☐ |
| 2 | El archivo está guardado en `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos` | Archivo > Información > Ruta de acceso | ☐ |
| 3 | La tabla tiene al menos 15 filas de datos (sin contar encabezados) | Contar filas en la hoja "Matriz de Necesidades" | ☐ |
| 4 | Las 6 columnas están presentes: Categoría, Subcategoría, Información disponible, Estado, Fuente de información, Notas | Verificar encabezados en fila 1 | ☐ |
| 5 | Las 6 categorías principales están representadas | Filtrar columna Categoría y verificar los 6 valores | ☐ |
| 6 | La columna Estado contiene solo "Conocido" o "Por confirmar" | Usar filtro en columna Estado para verificar valores únicos | ☐ |
| 7 | El formato condicional está activo (rojo para "Por confirmar", verde para "Conocido") | Inspección visual + Formato condicional > Administrar reglas | ☐ |
| 8 | Existe la hoja "Resumen Ejecutivo" con el análisis de Copilot | Verificar pestaña y contenido en celda A3 | ☐ |
| 9 | La fila de encabezados está inmovilizada | Hacer scroll hacia abajo y verificar que los encabezados permanecen visibles | ☐ |
| 10 | Los datos son coherentes con el perfil de Carlos Mendoza | Revisión de contenido: referencias a logística, México, USD 5M, inversiones en EE.UU. | ☐ |

---

## Solución de problemas

### Problema 1: Copilot no responde o muestra el mensaje "No puedo trabajar con estos datos"

**Síntomas**: Al hacer clic en el botón Copilot y escribir un prompt, Copilot muestra un mensaje de error indicando que no puede analizar los datos, o el botón Copilot aparece grisado/deshabilitado cuando se selecciona la tabla.

**Causa**: Copilot en Excel requiere que los datos estén formateados como **tabla de Excel** (no como un rango simple de celdas). Además, el archivo debe estar guardado en **OneDrive o SharePoint** (no en una ubicación local) para que Copilot pueda acceder a los datos. Otra causa frecuente es que la tabla esté vacía o contenga solo encabezados sin datos en las filas.

**Solución**:
1. Verifica que los datos están formateados como tabla: haz clic en cualquier celda con datos. Si **no** aparece la pestaña contextual "Diseño de tabla" en la cinta, selecciona el rango de datos y presiona `Ctrl+T` para convertirlo en tabla.
2. Verifica que el archivo está guardado en OneDrive: revisa la barra de título. Si dice "Este equipo" o muestra una ruta local (C:\...), usa **Archivo > Guardar como** y selecciona la ubicación de OneDrive.
3. Asegúrate de que la tabla tenga al menos una fila de datos además de los encabezados. Si solo tienes encabezados, ingresa manualmente al menos las 6 categorías en la columna A (como se indica en el Paso 2) antes de invocar Copilot.
4. Si el problema persiste, cierra Excel completamente, espera 30 segundos y vuelve a abrir el archivo desde OneDrive. Esto fuerza una reconexión con los servicios en la nube de Copilot.

---

### Problema 2: El formato condicional no se aplica a las nuevas filas agregadas después de la configuración inicial

**Síntomas**: Las filas originales muestran correctamente los colores del formato condicional (verde para "Conocido", rojo para "Por confirmar"), pero las filas nuevas agregadas en el Paso 6 (subcategorías adicionales sugeridas por Copilot) aparecen sin formato condicional, es decir, sin colores de fondo.

**Causa**: Si las reglas de formato condicional se aplicaron a un rango fijo (por ejemplo, `$D$2:$D$13`) en lugar de a la referencia dinámica de la tabla, las nuevas filas que se agregan fuera de ese rango no quedan cubiertas por las reglas. Esto ocurre especialmente cuando las nuevas filas se insertaron fuera de los límites originales de la tabla o cuando la tabla no se expandió automáticamente.

**Solución**:
1. Primero, verifica que las nuevas filas son parte de la tabla: haz clic en una celda de las nuevas filas. Si la pestaña "Diseño de tabla" aparece en la cinta, las filas están dentro de la tabla. Si no aparece, necesitas expandir la tabla:
   - Haz clic en la esquina inferior derecha de la tabla (un pequeño marcador de arrastre).
   - Arrástralo hacia abajo para incluir las nuevas filas.
2. Luego, actualiza las reglas de formato condicional:
   - Selecciona **toda** la columna Estado dentro de la tabla (desde D2 hasta la última fila con datos).
   - Ve a **Inicio** → **Formato condicional** → **Administrar reglas…**
   - Para cada regla existente, haz clic en ella y modifica el campo **"Se aplica a"** para que cubra el rango completo actualizado. Por ejemplo, cámbialo de `$D$2:$D$13` a `$D$2:$D$16` (o el número de fila correspondiente a tu última fila de datos).
   - Alternativamente, elimina las reglas existentes (**Eliminar regla**) y vuelve a crearlas seleccionando primero todo el rango actualizado, siguiendo las instrucciones del Paso 5.
3. Haz clic en **Aceptar** y verifica que los colores se aplican correctamente a todas las filas.

---

## Limpieza

Este laboratorio **no requiere limpieza**. El archivo `Matriz_Necesidades_CarlosMendoza_CIBEST.xlsx` debe **conservarse** en la ruta `OneDrive > Documentos > CIBEST_CAPITAL > Prospectos`, ya que será utilizado como documento de referencia central en los siguientes laboratorios:

- **Lab 01-08-08**: Redacción de correo de seguimiento en Outlook (se consultará la matriz para determinar qué información solicitar al prospecto).
- **Lab 01-08-09**: Comunicación complementaria en Outlook (se usarán las preguntas de descubrimiento de la columna Notas).

**Acciones post-laboratorio**:
- Verifica que el autoguardado de OneDrive esté activado (interruptor en la esquina superior izquierda de Excel).
- No muevas ni renombres el archivo.
- Cierra el panel de Copilot si no lo necesitas inmediatamente (haz clic en el botón Copilot para alternar su visibilidad).

---

## Resumen

En este laboratorio completaste las siguientes tareas clave:

| Tarea | Herramienta utilizada | Resultado |
|---|---|---|
| Creación del libro y guardado en OneDrive | Excel + OneDrive | Archivo `.xlsx` en ruta estandarizada |
| Definición de estructura con 6 columnas y 6 categorías | Excel (entrada manual + `Ctrl+T`) | Tabla formateada con encabezados y categorías base |
| Generación de contenido de la matriz | Copilot en Excel | 12+ filas con información del prospecto, estados y fuentes |
| Estandarización de valores de Estado | Excel (Buscar y reemplazar) | Columna con valores consistentes "Conocido" / "Por confirmar" |
| Formato condicional visual | Excel (Formato condicional) | Diferenciación cromática rojo/verde para estados |
| Enriquecimiento con subcategorías adicionales | Copilot en Excel | 3+ subcategorías nuevas con preguntas de descubrimiento |
| Análisis y resumen ejecutivo | Copilot en Excel | Hoja "Resumen Ejecutivo" con visión general del estado de preparación |
| Ajustes de formato profesional | Excel (formato, inmovilización, ajuste de texto) | Documento listo para uso profesional y compartido |

### Conceptos clave aplicados

- **Tablas de Excel (`Ctrl+T`)**: Requisito fundamental para habilitar las funcionalidades de Copilot en Excel. Los datos en rangos simples no son compatibles con todas las capacidades de análisis de Copilot.
- **Clasificación binaria de información**: La distinción "Conocido" / "Por confirmar" es una práctica estándar en la gestión de prospectos que permite al equipo comercial priorizar las preguntas de descubrimiento en la reunión.
- **Formato condicional como herramienta de gestión visual**: Los colores permiten una evaluación instantánea del estado de preparación sin necesidad de leer cada celda.
- **Copilot como acelerador, no reemplazo**: En este laboratorio, Copilot generó el contenido inicial y las sugerencias, pero el juicio profesional del analista fue necesario para validar, corregir y enriquecer los datos.

### Recursos adicionales

- [Documentación oficial: Copilot en Excel](https://support.microsoft.com/es-es/copilot-excel) — Guía de Microsoft sobre las capacidades de Copilot específicas para Excel.
- [Formato condicional en Excel — Guía completa](https://support.microsoft.com/es-es/office/usar-formato-condicional-para-resaltar-información-fed60dfa-6d89-4259-a6e4-d295d8e8e999) — Referencia oficial de Microsoft para reglas de formato condicional.
- [Requisitos de Copilot en Excel](https://support.microsoft.com/es-es/office/copilot-en-excel-d7110502-0334-4b4f-a175-a73abdfc118a) — Requisitos técnicos y limitaciones actuales de Copilot en Excel.

---

---

# Práctica guiada en Outlook con Copilot: redacción y ajuste de correo de bienvenida al prospecto

## Metadatos del Laboratorio

| Campo | Detalle |
|---|---|
| **Duración** | 15 minutos |
| **Complejidad** | Fácil |
| **Nivel de Bloom** | Aplicar |
| **Batch** | 01-08 (Laboratorio 3 de la serie) |
| **Laboratorio previo requerido** | 01-08-07 (Matriz de Necesidades en Excel) |
| **Laboratorio siguiente** | 01-08-09 (Correo de seguimiento post-reunión) |

---

## Descripción General

En este laboratorio redactarás un correo electrónico de bienvenida profesional dirigido al prospecto ficticio **Carlos Mendoza** utilizando la función **"Borrador con Copilot"** en Microsoft Outlook. Partirás de la información recopilada en la Matriz de Necesidades construida en el laboratorio 01-08-07 para identificar qué datos solicitar al prospecto antes de la reunión introductoria. A lo largo del ejercicio, aplicarás iteraciones de ajuste de tono, extensión y claridad, y compararás dos versiones del correo generadas con instrucciones diferentes para seleccionar la más adecuada al perfil del destinatario. El correo final se guardará como borrador sin enviarse, sirviendo como artefacto de referencia para el laboratorio 01-08-09.

---

## Objetivos de Aprendizaje

Al completar este laboratorio, serás capaz de:

- [ ] Redactar un correo de bienvenida profesional al prospecto ficticio utilizando la función "Borrador con Copilot" en Outlook, incorporando el propósito de la reunión, los temas a abordar y una solicitud de información previa.
- [ ] Aplicar iteraciones de ajuste en Copilot para modificar el tono, la extensión y la claridad del correo según el perfil de Carlos Mendoza (empresario latinoamericano en su primera interacción formal con CIBEST CAPITAL).
- [ ] Utilizar la información de la Matriz de Necesidades (01-08-07) para identificar qué datos específicos solicitar al prospecto en el correo de bienvenida.
- [ ] Comparar y evaluar al menos dos versiones del correo generadas con diferentes instrucciones de tono en Copilot (formal vs. cercano/cálido), seleccionando la más apropiada con justificación.

---

## Prerrequisitos

### Conocimientos Previos

| Requisito | Descripción |
|---|---|
| Laboratorio 01-08-07 completado | Debes tener la **Matriz de Necesidades** (`Matriz_Necesidades_CarlosMendoza.xlsx`) disponible en `Documentos > CIBEST_CAPITAL > Prospectos` como referencia activa |
| Familiaridad con Outlook | Saber crear un nuevo correo electrónico, escribir en el cuerpo del mensaje y guardar borradores |
| Comprensión del escenario | Conocer el perfil de Carlos Mendoza (propietario de empresa de logística en México, ingresos ~USD 5M, interés en diversificar patrimonio en EE.UU., experiencia limitada en inversiones internacionales) |
| Prompting básico con Copilot | Haber practicado la escritura de instrucciones a Copilot en al menos una aplicación de Microsoft 365 (labs anteriores del batch) |

### Acceso y Licencias

| Requisito | Detalle |
|---|---|
| Cuenta Microsoft 365 | Con licencia **Microsoft 365 Copilot** (Premium) activa |
| Exchange Online | Buzón funcional configurado en Outlook |
| Microsoft Outlook | Versión 2405 (Build 17628.20164) o superior, **o** Nueva versión de Outlook para Windows |
| Conexión a Internet | Mínimo 10 Mbps de bajada (requerida para funciones de Copilot en la nube) |

---

## Entorno del Laboratorio

### Hardware Requerido

| Componente | Mínimo | Recomendado |
|---|---|---|
| Procesador | 64 bits (Intel Core i5 / AMD Ryzen 5) | Intel Core i7 / AMD Ryzen 7 |
| RAM | 8 GB | 16 GB |
| Pantalla | 1366 × 768 | 1920 × 1080 |
| Almacenamiento libre | 10 GB | 15 GB |
| Internet | 10 Mbps bajada | 25 Mbps bajada |

### Software Requerido

| Software | Versión |
|---|---|
| Windows | Windows 10 22H2 (Build 19045) o Windows 11 23H2 (Build 22631) o superior |
| Microsoft Outlook | Versión 2405 (Build 17628.20164) o Nueva versión de Outlook |
| Microsoft 365 Copilot | Licencia Premium M365 Copilot (servicio en la nube, actualización continua) |
| Microsoft Excel | Versión 2405 (Build 17628.20164) — para consultar la Matriz de Necesidades |

### Verificación Inicial del Entorno

Antes de comenzar, realiza estas verificaciones rápidas:

1. **Verificar versión de Outlook**: Abre Outlook → **Archivo** → **Cuenta de Office** → **Información del producto**. Confirma que la versión sea **2405 (Build 17628.20164)** o superior. Si usas la Nueva versión de Outlook, esta se actualiza automáticamente.

2. **Verificar disponibilidad de Copilot en Outlook**: Crea un nuevo correo electrónico. En la barra de herramientas del cuerpo del mensaje, busca el icono de **Copilot** (ícono de estrella/diamante azul). Si no aparece, verifica tu licencia con el administrador de TI.

3. **Verificar acceso a la Matriz de Necesidades**: Abre el Explorador de Archivos y navega a `Documentos > CIBEST_CAPITAL > Prospectos`. Confirma que el archivo `Matriz_Necesidades_CarlosMendoza.xlsx` está presente.

> ⚠️ **NOTA**: Si la función "Borrador con Copilot" no aparece en la ventana de composición, asegúrate de que tu administrador de tenant haya habilitado Microsoft 365 Copilot para tu cuenta. Esta función requiere licencia Premium activa.

---

## Instrucciones Paso a Paso

### Paso 1 — Consultar la Matriz de Necesidades para identificar información a solicitar

**Objetivo**: Revisar las categorías marcadas como "Por confirmar" en la Matriz de Necesidades del laboratorio 01-08-07 para determinar qué datos específicos se deben solicitar a Carlos Mendoza en el correo de bienvenida.

**Instrucciones**:

1. Abre **Microsoft Excel** desde la barra de tareas o el menú Inicio.

2. Navega a **Archivo** → **Abrir** → **Documentos** → **CIBEST_CAPITAL** → **Prospectos** y abre el archivo `Matriz_Necesidades_CarlosMendoza.xlsx`.

3. Localiza la columna o sección que contiene el estado de la información. Busca específicamente los elementos clasificados como **"Por confirmar"** o **"Pendiente"**.

4. En una hoja de papel, en un bloc de notas digital o en un archivo de texto temporal, anota los **3 a 5 elementos clave** que necesitas solicitar a Carlos Mendoza. Estos típicamente incluirán elementos como:

   - Monto aproximado disponible para inversión inicial
   - Horizonte temporal de inversión deseado
   - Nivel de tolerancia al riesgo
   - Experiencia previa con productos financieros (más allá de lo ya conocido)
   - Documentación fiscal o corporativa relevante para inversiones en EE.UU.

5. Mantén Excel abierto en segundo plano — lo consultarás como referencia durante la redacción del correo.

**Resultado Esperado**: Tienes una lista clara de 3 a 5 puntos de información pendiente que incorporarás como solicitudes en el correo de bienvenida.

**Verificación**: Confirma que cada punto de tu lista corresponde a una fila o celda marcada como "Por confirmar" en la Matriz de Necesidades. Si tu matriz tiene menos de 3 elementos pendientes, revisa si hay categorías donde la información sea parcial o insuficiente.

---

### Paso 2 — Crear un nuevo correo y acceder a "Borrador con Copilot"

**Objetivo**: Abrir la ventana de composición de un nuevo correo en Outlook y activar la función "Borrador con Copilot" para generar el primer borrador del correo de bienvenida.

**Instrucciones**:

1. Cambia a **Microsoft Outlook** (si no está abierto, ábrelo desde la barra de tareas o el menú Inicio).

2. Haz clic en **Nuevo correo** (o presiona `Ctrl + N`) para abrir la ventana de composición.

3. Completa los campos del encabezado de la siguiente manera:

   | Campo | Valor |
   |---|---|
   | **Para** | `carlos.mendoza@logisticamendoza.com.mx` (dirección ficticia — no se enviará) |
   | **Asunto** | `Bienvenida y Confirmación de Reunión - Carlos Mendoza` |

   > 📌 **IMPORTANTE**: El asunto debe seguir exactamente el formato indicado: `Bienvenida y Confirmación de Reunión - Carlos Mendoza`. Este formato es requerido para mantener consistencia con el laboratorio 01-08-09.

4. Haz clic en el **cuerpo del mensaje** para posicionar el cursor.

5. En la barra de herramientas del cuerpo del correo, haz clic en el icono de **Copilot** (ícono de estrella/diamante azul). Se desplegará un menú con opciones.

6. Selecciona **"Borrador con Copilot"** (o **"Draft with Copilot"** si tu interfaz está en inglés). Aparecerá un cuadro de texto donde podrás escribir tu instrucción (prompt).

**Resultado Esperado**: Se muestra el panel de entrada de Copilot dentro de la ventana de composición del correo, con un campo de texto listo para recibir tu prompt y un botón "Generar" (o "Generate").

**Verificación**: El cuadro de prompt de Copilot debe estar visible debajo de la barra de herramientas o integrado en el cuerpo del correo. Si ves el mensaje "Copilot no está disponible", revisa la sección de Troubleshooting al final de este laboratorio.

---

### Paso 3 — Redactar el prompt inicial y generar la Versión 1 (tono formal)

**Objetivo**: Escribir un prompt detallado que instruya a Copilot a generar un correo de bienvenida con tono formal, incorporando todos los elementos requeridos: presentación del asesor, propósito de la reunión, temas a cubrir y solicitud de información previa.

**Instrucciones**:

1. En el cuadro de texto de Copilot, escribe el siguiente prompt. **Cópialo exactamente** o adáptalo mínimamente según los puntos específicos que identificaste en el Paso 1:

```
Redacta un correo electrónico de bienvenida con tono formal y profesional dirigido a Carlos Mendoza, propietario de una empresa de logística en México. El correo es enviado por un asesor de inversiones de CIBEST CAPITAL.

El correo debe incluir:
1. Un saludo formal y una bienvenida como nuevo prospecto de CIBEST CAPITAL.
2. Una breve presentación de CIBEST CAPITAL como firma de asesoría de inversiones especializada en clientes latinoamericanos que buscan diversificar su patrimonio en Estados Unidos.
3. Confirmación de una reunión introductoria próxima, mencionando que el propósito es conocer sus objetivos financieros y explorar opciones de inversión adecuadas a su perfil.
4. Los temas que se abordarán en la reunión: presentación de los servicios de CIBEST CAPITAL, exploración de sus objetivos de inversión, y una conversación sobre su situación patrimonial actual.
5. Una solicitud amable de que antes de la reunión nos comparta: el monto aproximado que considera destinar a inversiones, su horizonte temporal de inversión preferido, y si ha tenido experiencia previa con productos de inversión internacionales.
6. Un cierre cordial indicando disponibilidad para resolver cualquier duda previa a la reunión.

No uses jerga financiera técnica. El destinatario tiene experiencia limitada en inversiones. Mantén el correo entre 200 y 300 palabras.
```

2. Haz clic en el botón **"Generar"** (o **"Generate"**).

3. Espera unos segundos mientras Copilot genera el borrador. El texto aparecerá directamente en el área de previsualización del panel de Copilot.

4. **Lee el correo generado completo**. Evalúa mentalmente:
   - ¿Incluye todos los 6 elementos solicitados?
   - ¿El tono es efectivamente formal?
   - ¿Evita terminología financiera técnica?
   - ¿La extensión es razonable (200-300 palabras)?

5. **NO hagas clic en "Conservar" todavía**. Antes de aceptar esta versión, necesitas copiarla para compararla después.

6. Selecciona **todo el texto** generado por Copilot en la previsualización (usa `Ctrl + A` dentro del área de texto generado, o selecciona manualmente con el mouse).

7. Cópialo (`Ctrl + C`) y pégalo (`Ctrl + V`) en un archivo temporal de **Bloc de notas** o en un nuevo documento de Word. Etiquétalo como **"VERSIÓN 1 — TONO FORMAL"** al inicio del texto pegado.

**Resultado Esperado**: Copilot genera un correo de bienvenida con tono formal que incluye: saludo, presentación de CIBEST CAPITAL, confirmación de reunión, temas a tratar, solicitud de información previa y cierre. El texto ha sido copiado a un archivo temporal para comparación posterior.

**Ejemplo de fragmento esperado** (el texto exacto variará):

```
Estimado Sr. Mendoza:

Es un placer darle la bienvenida como nuevo prospecto de CIBEST CAPITAL. Mi nombre
es [Nombre del Asesor] y seré su punto de contacto en nuestra firma.

CIBEST CAPITAL es una firma de asesoría de inversiones que se especializa en
acompañar a empresarios latinoamericanos en el proceso de diversificar su patrimonio
a través de oportunidades de inversión en Estados Unidos...

[...continúa con los demás elementos solicitados...]

Quedo a su entera disposición para cualquier consulta previa a nuestra reunión.

Atentamente,
[Nombre del Asesor]
CIBEST CAPITAL
```

**Verificación**: Confirma que el texto copiado en tu archivo temporal está completo y legible. Verifica que contiene los 6 elementos del prompt. Si Copilot omitió algún elemento, lo corregirás en los pasos siguientes.

---

### Paso 4 — Generar la Versión 2 (tono cercano y cálido) para comparación

**Objetivo**: Utilizar la función de regeneración o ajuste de Copilot para crear una segunda versión del correo con un tono cercano y cálido, manteniendo el mismo contenido, para poder comparar ambos enfoques.

**Instrucciones**:

1. En el panel de Copilot (que aún debe estar activo en la ventana de composición), busca las opciones de ajuste. Dependiendo de la versión de Outlook, verás:
   - Un botón de **"Regenerar"** (ícono de flechas circulares) para generar una nueva versión.
   - Opciones de ajuste como **"Ajustar tono"** con opciones predefinidas (Formal, Casual, Directo, etc.).
   - Un campo para escribir instrucciones adicionales de refinamiento.

2. Si ves la opción **"Ajustar tono"**, selecciona **"Casual"** o **"Informal"**. Si no existe esa opción directa, utiliza el campo de instrucciones adicionales y escribe:

```
Reescribe este correo con un tono cercano, cálido y accesible, como si fuera una conversación entre profesionales que se están conociendo por primera vez. Usa "usted" pero evita fórmulas excesivamente rígidas. Mantén todos los elementos del contenido original pero haz que el prospecto se sienta bienvenido y cómodo, no intimidado. Mantén la extensión entre 200 y 300 palabras.
```

3. Haz clic en **"Generar"** o **"Actualizar"**.

4. Lee la nueva versión generada. Evalúa:
   - ¿El tono cambió notablemente respecto a la Versión 1?
   - ¿Se mantienen los 6 elementos de contenido?
   - ¿El lenguaje es más accesible y menos corporativo?

5. Selecciona todo el texto de esta segunda versión, cópialo (`Ctrl + C`) y pégalo en tu archivo temporal debajo de la Versión 1. Etiquétalo como **"VERSIÓN 2 — TONO CERCANO/CÁLIDO"**.

**Resultado Esperado**: Copilot genera una segunda versión del correo que mantiene la misma estructura informativa pero con un tono notablemente más cercano, cálido y conversacional. Ahora tienes ambas versiones en tu archivo temporal para comparación.

**Ejemplo de fragmento esperado para la Versión 2** (el texto exacto variará):

```
Estimado Carlos:

¡Qué gusto poder escribirle! Le doy la más cordial bienvenida a CIBEST CAPITAL.
Mi nombre es [Nombre del Asesor] y tendré el privilegio de acompañarlo en este
nuevo camino.

En CIBEST CAPITAL nos dedicamos a ayudar a empresarios como usted —exitosos en
sus industrias— a explorar nuevas formas de hacer crecer su patrimonio, en
particular a través de oportunidades en Estados Unidos...

[...continúa con los demás elementos en tono cálido...]

Si tiene cualquier pregunta antes de nuestra reunión, no dude en escribirme.
¡Será un gusto conversar!

Un saludo cordial,
[Nombre del Asesor]
CIBEST CAPITAL
```

**Verificación**: Abre tu archivo temporal y confirma que tienes dos versiones claramente diferenciadas y etiquetadas. Lee los primeros dos párrafos de cada una: deberías notar una diferencia clara en el nivel de formalidad, el uso de expresiones y la calidez del lenguaje.

---

### Paso 5 — Comparar las dos versiones y seleccionar la más adecuada

**Objetivo**: Realizar una comparación estructurada de las dos versiones generadas para seleccionar la más apropiada al perfil de Carlos Mendoza y justificar la decisión.

**Instrucciones**:

1. Abre tu archivo temporal donde guardaste ambas versiones.

2. Compara las dos versiones usando los siguientes criterios. Puedes anotar tus observaciones directamente en el archivo temporal:

   | Criterio | Versión 1 (Formal) | Versión 2 (Cercano/Cálido) |
   |---|---|---|
   | **Tono general** | ¿Cómo se percibe? | ¿Cómo se percibe? |
   | **Adecuación al perfil del prospecto** | ¿Un empresario mexicano en su primera interacción se sentiría cómodo? | ¿Se sentiría más cómodo con este tono? |
   | **Claridad de la solicitud de información** | ¿Queda claro qué se le pide? | ¿Queda claro qué se le pide? |
   | **Ausencia de jerga técnica** | ¿Hay términos que podrían confundir? | ¿Hay términos que podrían confundir? |
   | **Profesionalismo** | ¿Transmite confianza y seriedad? | ¿Transmite confianza sin ser rígido? |
   | **Extensión** | ¿Es adecuada? | ¿Es adecuada? |

3. **Selecciona la versión que consideres más adecuada**. Para el perfil de Carlos Mendoza (empresario latinoamericano, primera interacción formal, experiencia limitada en inversiones), generalmente la **Versión 2 (cercano/cálido)** resulta más apropiada porque:
   - Reduce la barrera psicológica de un primer contacto con una firma de inversiones
   - Refleja un estilo de comunicación más alineado con la cultura empresarial latinoamericana
   - Mantiene el profesionalismo sin generar distancia innecesaria

   > 💡 **NOTA PEDAGÓGICA**: No hay una respuesta "incorrecta" en esta selección. Lo importante es que puedas **justificar** tu elección con argumentos vinculados al perfil del prospecto. Si consideras que la Versión 1 es más adecuada, documenta tus razones.

4. Anota tu selección y una justificación breve (2-3 oraciones) al final de tu archivo temporal.

**Resultado Esperado**: Has realizado una comparación estructurada y documentada de ambas versiones, y has seleccionado una con justificación basada en el perfil del prospecto.

**Verificación**: Tu archivo temporal contiene: (1) Versión 1 etiquetada, (2) Versión 2 etiquetada, (3) tabla o notas de comparación, y (4) selección con justificación.

---

### Paso 6 — Aplicar ajustes de extensión y claridad a la versión seleccionada

**Objetivo**: Utilizar las funciones iterativas de Copilot para refinar la versión seleccionada, reduciendo redundancias y simplificando el lenguaje donde sea necesario.

**Instrucciones**:

1. Regresa a la ventana de composición de Outlook donde Copilot sigue activo.

2. Si el panel de Copilot se cerró, haz clic nuevamente en el icono de **Copilot** en la barra de herramientas y selecciona **"Borrador con Copilot"**.

3. En el campo de instrucciones, escribe el siguiente prompt de refinamiento (ajústalo según cuál versión seleccionaste):

```
Toma la versión anterior del correo con tono cercano y cálido y aplica los siguientes ajustes:
1. Reduce la extensión a un máximo de 250 palabras eliminando frases redundantes o repetitivas.
2. Asegúrate de que la solicitud de información previa esté presentada como una lista con viñetas para facilitar la lectura.
3. Elimina cualquier referencia a términos como "portafolio", "rendimientos", "activos" o "diversificación de cartera". Usa en su lugar frases como "hacer crecer su patrimonio", "opciones para invertir" y "proteger lo que ha construido".
4. Incluye al final una línea que diga: "Este correo es enviado por [Nombre del Asesor], Asesor de Inversiones, CIBEST CAPITAL."
```

4. Haz clic en **"Generar"**.

5. Revisa el resultado. Verifica específicamente:
   - ¿La extensión se redujo?
   - ¿La solicitud de información aparece en formato de lista con viñetas?
   - ¿Se eliminaron los términos técnicos mencionados?
   - ¿Aparece la línea de firma al final?

6. Si algún ajuste no se aplicó correctamente, utiliza el campo de instrucciones para solicitar la corrección específica. Por ejemplo:

```
La solicitud de información aún no está en formato de lista con viñetas. Reformatea los puntos 
que le pido al prospecto como una lista con viñetas claras.
```

7. Una vez satisfecho con el resultado, haz clic en **"Conservar"** (o **"Keep"**) para insertar el texto en el cuerpo del correo.

**Resultado Esperado**: El cuerpo del correo ahora contiene la versión refinada con tono adecuado, extensión controlada (~250 palabras), solicitud de información en formato de lista con viñetas, lenguaje libre de jerga técnica y firma del asesor.

**Verificación**: Lee el correo completo en la ventana de composición. Cuenta las palabras aproximadamente (selecciona el texto, cópialo a Word y usa la función de conteo de palabras si necesitas precisión). Confirma que los elementos de la lista con viñetas coinciden con los puntos de información que identificaste en el Paso 1.

---

### Paso 7 — Usar "Coaching por Copilot" para obtener sugerencias de mejora

**Objetivo**: Aplicar la función "Coaching por Copilot" de Outlook para recibir retroalimentación automatizada sobre el correo ya redactado y aplicar mejoras finales.

**Instrucciones**:

1. Con el correo redactado visible en la ventana de composición, haz clic en el icono de **Copilot** en la barra de herramientas.

2. En el menú desplegable, selecciona **"Coaching por Copilot"** (o **"Coaching by Copilot"**). Esta función analiza el correo ya escrito y ofrece sugerencias en tres dimensiones:
   - **Tono**: ¿El tono es apropiado para el destinatario?
   - **Sentimiento del lector**: ¿Cómo podría percibir el destinatario este mensaje?
   - **Claridad**: ¿El mensaje es claro y fácil de entender?

3. Espera a que Copilot analice el correo. Aparecerá un panel lateral con las sugerencias organizadas por categoría.

4. Lee cada sugerencia cuidadosamente. Las sugerencias típicas pueden incluir:
   - "Considera agregar una línea que personalice el mensaje mencionando el sector del destinatario"
   - "El párrafo 3 podría ser más conciso"
   - "La solicitud de información podría incluir un plazo sugerido para la respuesta"

5. Para cada sugerencia, decide si la aplicas o no. Si decides aplicar una sugerencia:
   - Cierra el panel de Coaching
   - Edita manualmente el texto en el cuerpo del correo
   - O vuelve a usar "Borrador con Copilot" con una instrucción específica para incorporar la mejora

6. **Recomendación**: Si Copilot sugiere agregar un plazo para la respuesta, incorpora una línea como:

   > *"Si le es posible, le agradecería compartir esta información al menos dos días antes de nuestra reunión para que pueda preparar opciones personalizadas para usted."*

7. Después de aplicar las mejoras que consideres pertinentes, lee el correo completo una última vez.

**Resultado Esperado**: Has recibido retroalimentación de Copilot sobre el correo y has aplicado al menos una mejora sugerida. El correo ahora está más pulido y mejor adaptado al destinatario.

**Verificación**: El panel de Coaching debe haber mostrado al menos una sugerencia en cada categoría (Tono, Sentimiento, Claridad). Si el panel indica que el correo está bien en todas las dimensiones sin sugerencias, esto también es un resultado válido que confirma la calidad del borrador.

> ⚠️ **NOTA**: La función "Coaching por Copilot" analiza el correo que ya está escrito en el cuerpo del mensaje. Si el cuerpo está vacío o tiene muy poco texto, la función no generará sugerencias útiles. Asegúrate de haber completado el Paso 6 antes de usar esta función.

---

### Paso 8 — Guardar el correo como borrador

**Objetivo**: Guardar el correo finalizado como borrador en Outlook sin enviarlo, asegurando que esté disponible como referencia para el laboratorio 01-08-09.

**Instrucciones**:

1. Verifica que el correo tiene los siguientes elementos completos:

   | Elemento | Estado |
   |---|---|
   | **Campo "Para"** | `carlos.mendoza@logisticamendoza.com.mx` |
   | **Asunto** | `Bienvenida y Confirmación de Reunión - Carlos Mendoza` |
   | **Cuerpo** | Correo de bienvenida refinado con todos los elementos requeridos |
   | **Tono** | Cercano/cálido y profesional (o formal, según tu selección justificada) |
   | **Solicitud de información** | Presentada en formato de lista con viñetas |
   | **Firma** | Nombre del Asesor, cargo y CIBEST CAPITAL |

2. **NO hagas clic en "Enviar"**. Este es un ejercicio simulado con una dirección ficticia.

3. Cierra la ventana de composición haciendo clic en la **X** de la ventana del correo (no de Outlook completo). Outlook mostrará un cuadro de diálogo preguntando si deseas guardar los cambios.

4. Haz clic en **"Sí"** (o **"Guardar"**). El correo se guardará automáticamente en la carpeta **Borradores** de Outlook.

5. Para confirmar, navega a la carpeta **Borradores** en el panel de navegación izquierdo de Outlook. Localiza el correo con el asunto `Bienvenida y Confirmación de Reunión - Carlos Mendoza`.

6. Haz doble clic en el borrador para abrirlo y confirma que todo el contenido se guardó correctamente.

7. Cierra el borrador sin modificaciones.

**Resultado Esperado**: El correo aparece en la carpeta Borradores de Outlook con el asunto correcto y todo el contenido intacto.

**Verificación**: En la carpeta Borradores, el correo debe mostrarse con:
- Asunto: `Bienvenida y Confirmación de Reunión - Carlos Mendoza`
- Destinatario visible: `carlos.mendoza@logisticamendoza.com.mx`
- Vista previa del cuerpo mostrando las primeras líneas del correo de bienvenida

---

## Validación y Pruebas

Utiliza la siguiente lista de verificación para confirmar que has completado exitosamente todos los entregables del laboratorio:

| # | Criterio de Validación | ✅ |
|---|---|---|
| 1 | Identificaste al menos 3 puntos de información "Por confirmar" de la Matriz de Necesidades | ☐ |
| 2 | Generaste la **Versión 1** del correo con tono formal usando "Borrador con Copilot" | ☐ |
| 3 | Generaste la **Versión 2** del correo con tono cercano/cálido usando ajuste de tono en Copilot | ☐ |
| 4 | Comparaste ambas versiones usando al menos 3 criterios documentados | ☐ |
| 5 | Seleccionaste una versión con justificación escrita | ☐ |
| 6 | Aplicaste ajustes de extensión (≤250 palabras), formato (lista con viñetas) y lenguaje (sin jerga técnica) | ☐ |
| 7 | Utilizaste "Coaching por Copilot" y revisaste las sugerencias generadas | ☐ |
| 8 | El correo está guardado en la carpeta **Borradores** con el asunto exacto: `Bienvenida y Confirmación de Reunión - Carlos Mendoza` | ☐ |
| 9 | El correo **NO fue enviado** (permanece como borrador) | ☐ |
| 10 | Tu archivo temporal contiene las dos versiones etiquetadas y las notas de comparación | ☐ |

> ✅ **Criterio de éxito**: Debes marcar al menos **8 de 10** criterios para considerar el laboratorio completado satisfactoriamente. Los criterios 2, 3, 4 y 8 son obligatorios.

---

## Solución de Problemas

### Problema 1: El icono de Copilot no aparece en la ventana de composición de correo

**Síntomas**: Al crear un nuevo correo en Outlook, no se muestra el icono de Copilot (estrella/diamante azul) en la barra de herramientas del cuerpo del mensaje. Las opciones "Borrador con Copilot" y "Coaching por Copilot" no están disponibles.

**Causa**: Este problema ocurre típicamente por una de estas razones:
- La licencia de Microsoft 365 Copilot (Premium) no está asignada a la cuenta del usuario en el tenant.
- La versión de Outlook es anterior a la 2405 (Build 17628.20164) y no soporta las funciones de Copilot.
- El administrador del tenant ha deshabilitado Copilot para Outlook mediante políticas de grupo o configuración del Centro de Administración de Microsoft 365.
- Se está usando Outlook en modo sin conexión o la conexión a Internet se ha interrumpido.

**Solución**:
1. Verifica la versión de Outlook: **Archivo** → **Cuenta de Office** → **Información del producto**. Si es anterior a 2405, actualiza: **Archivo** → **Cuenta de Office** → **Opciones de actualización** → **Actualizar ahora**.
2. Verifica la conexión a Internet abriendo un navegador y accediendo a `https://outlook.office.com`. Si no carga, resuelve la conectividad primero.
3. Si la versión es correcta y hay conexión, contacta al administrador de TI para verificar que la licencia de M365 Copilot está asignada. El administrador puede verificarlo en el **Centro de Administración de Microsoft 365** → **Usuarios** → **Usuarios activos** → seleccionar el usuario → **Licencias y aplicaciones**.
4. Como alternativa temporal, puedes usar la **Nueva versión de Outlook** (New Outlook) que recibe las funciones de Copilot de forma prioritaria. Actívala con el interruptor **"Probar el nuevo Outlook"** en la esquina superior derecha de Outlook clásico.

---

### Problema 2: Copilot genera texto en inglés en lugar de español

**Síntomas**: Al usar "Borrador con Copilot", el correo generado aparece completamente en inglés a pesar de que el prompt fue escrito en español. Las sugerencias de "Coaching por Copilot" también aparecen en inglés.

**Causa**: El idioma de presentación de Microsoft 365 o la configuración regional de Outlook está establecida en inglés. Copilot utiliza el idioma de la interfaz de la aplicación como referencia predeterminada para generar contenido, independientemente del idioma del prompt en algunos casos.

**Solución**:
1. Verifica el idioma de Outlook: **Archivo** → **Opciones** → **Idioma**. En la sección "Idioma de presentación de Office", asegúrate de que **Español (España)** o **Español (México)** esté configurado como preferido y marcado como `[Predeterminado]`.
2. Si el idioma correcto no está en la lista, haz clic en **"Agregar un idioma"**, selecciona Español, y configúralo como predeterminado. Reinicia Outlook después del cambio.
3. Como solución inmediata sin cambiar configuraciones, agrega al inicio de cada prompt la instrucción explícita: `Responde completamente en español latinoamericano.` Esto fuerza a Copilot a generar el contenido en español independientemente de la configuración de idioma.
4. Si el problema persiste después de cambiar el idioma y reiniciar, verifica también la configuración regional de Windows: **Configuración** → **Hora e idioma** → **Idioma y región** → establece Español como idioma preferido de Windows.

---

## Limpieza

Al finalizar el laboratorio, realiza las siguientes acciones:

1. **Conservar el borrador en Outlook**: El correo en la carpeta Borradores con asunto `Bienvenida y Confirmación de Reunión - Carlos Mendoza` debe **permanecer guardado**. Será referenciado en el laboratorio 01-08-09.

2. **Guardar el archivo de comparación**: Si creaste un archivo temporal con las dos versiones y las notas de comparación, guárdalo en la ruta estándar del curso:
   - Ruta: `Documentos > CIBEST_CAPITAL > Prospectos`
   - Nombre sugerido: `Comparacion_Correos_CarlosMendoza.txt` o `Comparacion_Correos_CarlosMendoza.docx`

3. **Mantener abierta la Matriz de Necesidades**: Si planeas continuar con el laboratorio 01-08-09 inmediatamente, mantén el archivo `Matriz_Necesidades_CarlosMendoza.xlsx` accesible. De lo contrario, puedes cerrar Excel.

4. **No eliminar borradores**: No vacíes la carpeta de Borradores de Outlook. El correo guardado es un artefacto requerido del flujo de trabajo del batch.

> ⚠️ **ADVERTENCIA**: No envíes el correo borrador. La dirección `carlos.mendoza@logisticamendoza.com.mx` es ficticia y el envío generaría un error de entrega o, si la dirección existiera por coincidencia, enviaría información del ejercicio a un tercero no relacionado.

---

## Resumen

En este laboratorio aplicaste un flujo completo de redacción asistida por IA en Microsoft Outlook utilizando dos funciones clave de Microsoft 365 Copilot:

| Función Utilizada | Aplicación en el Lab |
|---|---|
| **Borrador con Copilot** | Generación de dos versiones del correo con diferentes tonos; iteraciones de ajuste de extensión, formato y lenguaje |
| **Coaching por Copilot** | Análisis del correo finalizado con sugerencias de mejora en tono, sentimiento del lector y claridad |

**Conceptos clave practicados**:

- **Prompting iterativo**: No te limitaste a un solo prompt. Generaste, comparaste, ajustaste y refinaste el contenido a través de múltiples interacciones con Copilot, demostrando que la IA es más efectiva cuando se usa como un proceso de refinamiento progresivo.
- **Adecuación al perfil del destinatario**: Evaluaste críticamente el tono del correo considerando el contexto cultural y profesional de Carlos Mendoza, un empresario latinoamericano sin experiencia en inversiones internacionales.
- **Integración con artefactos previos**: Utilizaste la Matriz de Necesidades del laboratorio 01-08-07 como fuente de datos para determinar qué información solicitar, demostrando cómo los entregables de un flujo de trabajo se conectan entre sí.
- **Control humano sobre la IA**: En cada paso, tú tomaste la decisión final sobre qué conservar, qué modificar y qué descartar del contenido generado por Copilot.

**Conexión con el siguiente laboratorio**: El correo de bienvenida guardado como borrador será el punto de partida narrativo del laboratorio **01-08-09**, donde redactarás un correo de seguimiento post-reunión. La coherencia de tono y contenido entre ambos correos es fundamental para demostrar un flujo de comunicación profesional con el prospecto.

### Recursos Adicionales

| Recurso | Enlace |
|---|---|
| Documentación oficial: Usar Copilot en Outlook | [https://support.microsoft.com/es-es/office/usar-copilot-en-outlook](https://support.microsoft.com/es-es/office/usar-copilot-en-outlook) |
| Guía de prompts efectivos para Microsoft 365 Copilot | [https://adoption.microsoft.com/es-es/copilot/](https://adoption.microsoft.com/es-es/copilot/) |
| Mejores prácticas de comunicación escrita con prospectos de inversión | Consultar materiales complementarios del curso en la carpeta de recursos del batch |

---

---

# Práctica guiada en Outlook con Copilot: redacción de correo de seguimiento post-reunión con síntesis y próximos pasos

## 1. Metadatos del Laboratorio

| Campo | Detalle |
|---|---|
| **Duración** | 10 minutos |
| **Complejidad** | Fácil |
| **Nivel de Bloom** | Aplicar |
| **Batch** | 01-08 (Lab 4 de 4 en comunicación con Outlook) |
| **Lab previo requerido** | 01-08-08 (Correo de bienvenida con Copilot en Outlook) |
| **Lab siguiente** | 01-08-10 (Agenda de reunión interna del equipo CIBEST CAPITAL) |

---

## 2. Descripción General

En este laboratorio simularás que la reunión introductoria con el prospecto **Carlos Mendoza** ya se llevó a cabo y que ahora debes enviar un correo de seguimiento profesional que sintetice lo discutido, refuerce la relación y comunique próximos pasos claros y accionables. Utilizarás la función **"Borrador con Copilot"** en Microsoft Outlook para generar el correo a partir de un prompt bien estructurado que incorpore el contexto acumulado del prospecto y los resultados específicos de la reunión ficticia. Este ejercicio consolida las habilidades de prompting adquiridas en el lab 01-08-08 y te desafía a producir un borrador de calidad desde el primer intento, reflejando eficiencia profesional en la comunicación post-reunión.

---

## 3. Objetivos de Aprendizaje

Al completar este laboratorio, serás capaz de:

- [ ] Redactar un correo de seguimiento post-reunión utilizando **Borrador con Copilot** en Outlook, que incluya agradecimiento personalizado, síntesis de temas tratados y próximos pasos accionables con fechas y responsables.
- [ ] Aplicar el contexto acumulado del prospecto (perfil, necesidades confirmadas en reunión, información pendiente) para generar un correo específico y no genérico.
- [ ] Comparar la estructura y propósito del correo de seguimiento con el correo de bienvenida del lab 01-08-08, identificando diferencias clave en tono, contenido y función comunicacional.
- [ ] Utilizar las funciones de ajuste de Copilot (longitud y tono) para refinar la sección de próximos pasos, asegurando que sean comprensibles para un prospecto con experiencia limitada en inversiones.

---

## 4. Prerrequisitos

### Conocimientos Previos

| Requisito | Descripción |
|---|---|
| Lab 01-08-08 completado | Familiaridad con el flujo de "Borrador con Copilot" en Outlook, incluyendo generación, ajuste de tono y guardado de borradores. |
| Matriz de Necesidades (01-08-07) | Haber revisado la matriz de Excel para conocer qué información del prospecto estaba clasificada como "conocida" y qué como "pendiente". |
| Perfil del prospecto | Conocer el perfil fijo de Carlos Mendoza: propietario de empresa de logística en México, ingresos ~USD 5M, interés en diversificar patrimonio en EE.UU., experiencia limitada en inversiones internacionales. |
| Prompting contextual | Capacidad de construir prompts que incluyan múltiples elementos de contexto (rol, audiencia, propósito, contenido específico). |

### Acceso y Configuración

| Recurso | Requisito |
|---|---|
| **Cuenta Microsoft 365** | Licencia activa con **Microsoft 365 Copilot** habilitado. |
| **Microsoft Outlook** | Versión 2405 (Build 17628.20164) o superior, o Nuevo Outlook para Windows. |
| **Exchange Online** | Cuenta configurada y funcional para envío/recepción de correo y gestión de borradores. |
| **Conexión a Internet** | Mínimo 10 Mbps de bajada (requerido para funcionalidades de Copilot en la nube). |
| **Directorio de trabajo** | `Documentos > CIBEST_CAPITAL > Prospectos` en OneDrive (para referencia de artefactos previos). |

---

## 5. Entorno del Laboratorio

### Hardware Mínimo

| Componente | Especificación |
|---|---|
| Procesador | 64 bits — Intel Core i5 / AMD Ryzen 5 o superior |
| RAM | 8 GB mínimo (16 GB recomendado) |
| Pantalla | 1366×768 mínimo (1920×1080 recomendado) |
| Almacenamiento libre | 10 GB mínimo |
| Periféricos | Teclado y ratón/trackpad funcionales |

### Software Requerido

| Aplicación | Versión |
|---|---|
| **Windows** | Windows 10 22H2 (Build 19045) o Windows 11 23H2 (Build 22631) o superior |
| **Microsoft Outlook** | Versión 2405 (Build 17628.20164) o Nuevo Outlook para Windows |
| **Microsoft 365 Copilot** | Licencia Premium M365 Copilot activa (servicio en la nube, actualización continua) |
| **Microsoft Edge** | 124.0.2478.97 o superior (para verificación web si es necesario) |

### Escenario Ficticio de la Reunión (Proporcionado por el Instructor)

> 📋 **ESCENARIO: Resultados de la reunión introductoria con Carlos Mendoza**
>
> La reunión se realizó el día de ayer (usar fecha relativa) y duró aproximadamente 45 minutos. Durante la sesión:
>
> 1. **Carlos confirmó su interés** en diversificar su patrimonio personal invirtiendo en activos en Estados Unidos.
> 2. **Horizonte de inversión**: Carlos mencionó un horizonte de **5 años**, alineado con su plan de expansión empresarial.
> 3. **Preocupación principal**: Expresó preocupación por la **liquidez** de las inversiones, ya que necesita acceso a parte de su capital para operaciones de su empresa de logística.
> 4. **Perfil de riesgo**: Solicitó información sobre **opciones de bajo riesgo** como primer paso, antes de considerar instrumentos más agresivos.
> 5. **Monto estimado inicial**: Mencionó que podría destinar entre **USD 200,000 y USD 350,000** como inversión inicial.
> 6. **Documentación**: Carlos se comprometió a enviar sus estados financieros personales y el balance general de su empresa dentro de la próxima semana.
>
> **Próximos pasos acordados:**
> - CIBEST CAPITAL enviará una **propuesta preliminar de portafolio conservador** dentro de 5 días hábiles.
> - Se programará una **segunda reunión en dos semanas** para revisar la propuesta.
> - Carlos enviará la **documentación requerida** (estados financieros personales y balance empresarial) dentro de 7 días.

### Verificación Rápida del Entorno

Antes de iniciar, confirma que Copilot está disponible en Outlook:

1. Abre **Microsoft Outlook** (versión de escritorio o Nuevo Outlook).
2. Haz clic en **Nuevo correo** (o **New mail**).
3. Verifica que en el cuerpo del mensaje aparezca el ícono de **Copilot** o el botón **"Borrador con Copilot"** (Draft with Copilot).
4. Si no aparece, verifica tu licencia en **Archivo > Cuenta de Office > Suscripciones** y confirma que "Microsoft 365 Copilot" esté listado.

> ⚠️ Si el botón de Copilot no aparece después de verificar la licencia, cierra Outlook completamente, espera 30 segundos y vuelve a abrirlo. En algunos casos, la activación de Copilot requiere un reinicio de la aplicación.

---

## 6. Instrucciones Paso a Paso

### Paso 1: Abrir un nuevo correo y activar Borrador con Copilot

**Objetivo:** Iniciar la composición de un nuevo correo electrónico dirigido a Carlos Mendoza y acceder a la función de generación asistida por IA.

**Instrucciones:**

1. Abre **Microsoft Outlook** en tu equipo.
2. Haz clic en el botón **"Nuevo correo"** en la barra superior (o usa el atajo de teclado `Ctrl + N`).
3. En el campo **Para:** escribe la dirección de correo ficticia del prospecto:
   ```
   carlos.mendoza@logistica-mendoza.com.mx
   ```
4. En el campo **Asunto:** escribe:
   ```
   Seguimiento reunión introductoria — CIBEST CAPITAL y Carlos Mendoza
   ```
5. Haz clic en el **cuerpo del mensaje** para posicionar el cursor.
6. Localiza y haz clic en el ícono de **Copilot** (✨) que aparece en la barra de herramientas del cuerpo del mensaje, o haz clic en el botón **"Borrador con Copilot"** si aparece como opción flotante en el área de composición.

**Resultado esperado:** Se abre el panel de entrada de prompt de Copilot dentro del área de composición del correo, mostrando un cuadro de texto con el placeholder "¿Qué quieres que diga este correo?" o similar.

**Verificación:**
- ✅ El campo **Para:** muestra `carlos.mendoza@logistica-mendoza.com.mx`.
- ✅ El campo **Asunto:** muestra el texto de seguimiento con los nombres correctos.
- ✅ El panel de Copilot está activo y listo para recibir un prompt.

---

### Paso 2: Construir y enviar el prompt contextual completo

**Objetivo:** Redactar un prompt único, bien estructurado y rico en contexto que permita a Copilot generar un borrador de correo de seguimiento de alta calidad desde el primer intento.

**Instrucciones:**

1. En el cuadro de texto del panel de Copilot, escribe el siguiente prompt **completo**. Cópialo exactamente o adáptalo con la fecha real de hoy:

```
Redacta un correo de seguimiento profesional y cálido dirigido a Carlos Mendoza, propietario de una empresa de logística en México, después de nuestra reunión introductoria de ayer. Soy asesor de inversiones de CIBEST CAPITAL.

Contexto de la reunión:
- Carlos confirmó su interés en diversificar su patrimonio invirtiendo en activos en Estados Unidos
- Mencionó un horizonte de inversión de 5 años
- Expresó preocupación por la liquidez de las inversiones, ya que necesita acceso a parte de su capital para su empresa
- Solicitó información sobre opciones de bajo riesgo como primer paso
- Indicó que podría destinar entre USD 200,000 y USD 350,000 como inversión inicial
- Se comprometió a enviar sus estados financieros personales y el balance general de su empresa dentro de la próxima semana

El correo debe incluir:
1. Un agradecimiento personalizado por su tiempo y apertura durante la reunión
2. Una síntesis breve de los puntos clave discutidos (sin tecnicismos financieros, lenguaje accesible)
3. Los próximos pasos con fechas y responsables claros:
   - CIBEST CAPITAL enviará una propuesta preliminar de portafolio conservador dentro de 5 días hábiles
   - Segunda reunión programada para dentro de dos semanas para revisar la propuesta juntos
   - Carlos enviará la documentación solicitada (estados financieros personales y balance empresarial) dentro de 7 días
4. Un cierre que refuerce la confianza y disponibilidad del equipo

Tono: profesional pero cercano, sin jerga financiera compleja. Extensión: moderada (no más de 300 palabras).
```

2. Revisa el prompt antes de enviarlo. Confirma que incluye:
   - **Rol del remitente** (asesor de CIBEST CAPITAL).
   - **Identidad y contexto del destinatario** (Carlos Mendoza, logística, México).
   - **Puntos específicos de la reunión** (6 elementos).
   - **Estructura solicitada** (4 secciones).
   - **Restricciones** (tono, extensión, sin tecnicismos).

3. Haz clic en el botón **"Generar"** (o **"Generate"**) para enviar el prompt a Copilot.

4. Espera a que Copilot genere el borrador completo. Esto puede tomar entre 5 y 15 segundos.

**Resultado esperado:** Copilot genera un borrador de correo que contiene:
- Saludo personalizado dirigido a Carlos Mendoza.
- Párrafo de agradecimiento que referencia la reunión específica.
- Síntesis de los temas tratados (horizonte, liquidez, rango de inversión, perfil conservador).
- Sección de próximos pasos con tres elementos diferenciados, cada uno con responsable y plazo.
- Cierre profesional con firma de CIBEST CAPITAL.

**Verificación:**
- ✅ El borrador menciona a **Carlos Mendoza** por nombre (no un placeholder genérico).
- ✅ Incluye referencia a la **empresa de logística** o al contexto empresarial del prospecto.
- ✅ Los **próximos pasos** incluyen al menos 3 acciones con plazos específicos.
- ✅ El lenguaje es accesible — no contiene términos como "asset allocation", "benchmark", "yield curve" u otros tecnicismos sin explicar.
- ✅ La extensión es moderada (aproximadamente 200-350 palabras).

> 💡 **Nota sobre eficiencia de prompting:** A diferencia del lab 01-08-08 donde pudiste necesitar múltiples iteraciones, en este ejercicio el objetivo es lograr un resultado satisfactorio con un solo prompt bien construido. Si el resultado cumple al menos el 80% de los criterios, pasa al Paso 3 para refinamientos menores en lugar de regenerar completamente.

---

### Paso 3: Evaluar y refinar el borrador generado

**Objetivo:** Revisar críticamente el borrador de Copilot, ajustar la sección de próximos pasos para máxima claridad y realizar ajustes de tono si es necesario.

**Instrucciones:**

1. **Lee el borrador completo** generado por Copilot sin hacer cambios aún.

2. **Evalúa el borrador** usando la siguiente lista de verificación rápida:

   | Criterio | ¿Cumple? (Sí/No) |
   |---|---|
   | Agradecimiento personalizado (no genérico) | |
   | Referencia específica a la reunión (no vago) | |
   | Mención del horizonte de 5 años | |
   | Mención de la preocupación por liquidez | |
   | Mención del rango USD 200K-350K | |
   | Mención de opciones de bajo riesgo | |
   | Próximo paso 1: Propuesta en 5 días hábiles | |
   | Próximo paso 2: Segunda reunión en 2 semanas | |
   | Próximo paso 3: Documentación de Carlos en 7 días | |
   | Lenguaje libre de tecnicismos | |
   | Tono profesional pero cercano | |

3. **Si la sección de próximos pasos necesita mayor especificidad**, selecciona esa sección del texto y utiliza la opción de **"Ajustar con Copilot"**. En el cuadro de ajuste, escribe:

   ```
   Reformula los próximos pasos como una lista numerada donde cada punto indique claramente: (1) la acción específica, (2) quién es responsable (CIBEST CAPITAL o Carlos), y (3) la fecha límite. Mantén el lenguaje sencillo.
   ```

4. **Si el tono del correo resulta demasiado formal o distante**, utiliza la opción de ajuste de tono de Copilot:
   - Busca las opciones de **tono** debajo del borrador generado (pueden aparecer como botones o en un menú desplegable).
   - Selecciona **"Informal"** o **"Directo"** si el correo suena excesivamente corporativo.
   - Revisa el resultado y confirma que mantiene profesionalismo sin perder cercanía.

5. **Si la extensión es excesiva** (más de 350 palabras), utiliza la opción de ajuste de **longitud**:
   - Selecciona **"Corto"** o **"Medio"** en las opciones de longitud de Copilot.
   - Verifica que no se hayan eliminado los próximos pasos ni el agradecimiento personalizado.

6. Una vez satisfecho con el resultado, haz clic en **"Mantener"** (o **"Keep"**) para insertar el borrador en el cuerpo del correo.

**Resultado esperado:** El borrador refinado aparece directamente en el cuerpo del correo electrónico, reemplazando el panel de Copilot. Los próximos pasos están claramente diferenciados con responsables y fechas.

**Verificación:**
- ✅ Los próximos pasos están en formato de lista (numerada o con viñetas), no embebidos en un párrafo.
- ✅ Cada próximo paso identifica al **responsable** (CIBEST CAPITAL o Carlos Mendoza).
- ✅ Cada próximo paso incluye un **plazo** específico (5 días hábiles, 2 semanas, 7 días).
- ✅ El correo completo no excede las 350 palabras aproximadamente.
- ✅ El tono es profesional pero cálido — adecuado para un prospecto con experiencia limitada en inversiones.

---

### Paso 4: Agregar firma y guardar como borrador

**Objetivo:** Completar el correo con la firma profesional de CIBEST CAPITAL y guardarlo como borrador para referencia futura en el lab 01-08-10.

**Instrucciones:**

1. Posiciona el cursor al final del cuerpo del correo, después del cierre generado por Copilot.

2. Si tu Outlook no inserta automáticamente una firma, agrega manualmente la siguiente firma ficticia:

   ```
   —
   [Tu Nombre]
   Asesor de Inversiones
   CIBEST CAPITAL
   Tel: +1 (555) 000-0000
   correo@cibestcapital.com
   www.cibestcapital.com

   Confidencialidad: Este correo y sus anexos son confidenciales y están dirigidos exclusivamente al destinatario. Si lo ha recibido por error, por favor notifíquenos de inmediato.
   ```

3. **Revisa el correo completo** una última vez, de arriba a abajo:
   - Campo **Para:** → `carlos.mendoza@logistica-mendoza.com.mx`
   - Campo **Asunto:** → `Seguimiento reunión introductoria — CIBEST CAPITAL y Carlos Mendoza`
   - **Cuerpo:** → Agradecimiento + síntesis + próximos pasos + cierre + firma.

4. **NO envíes el correo.** En lugar de eso, guárdalo como borrador:
   - Haz clic en la **"X"** para cerrar la ventana de composición.
   - Cuando Outlook pregunte si deseas guardar el borrador, selecciona **"Sí"** (o **"Save"**).
   - Alternativamente, usa el atajo `Ctrl + S` para guardar como borrador sin cerrar la ventana.

5. Navega a la carpeta **Borradores** (Drafts) en el panel lateral de Outlook y confirma que el correo aparece allí.

**Resultado esperado:** El correo de seguimiento completo aparece en la carpeta de Borradores de Outlook, listo para ser referenciado en el laboratorio 01-08-10.

**Verificación:**
- ✅ El correo aparece en la carpeta **Borradores** con el asunto correcto.
- ✅ Al abrir el borrador, el contenido completo (agradecimiento, síntesis, próximos pasos, firma) está intacto.
- ✅ El correo **no fue enviado** (no aparece en la carpeta Elementos enviados).

---

### Paso 5: Reflexión comparativa — Correo de bienvenida vs. correo de seguimiento

**Objetivo:** Identificar las diferencias estructurales, de tono y de propósito entre el correo de bienvenida (lab 01-08-08) y el correo de seguimiento (este lab), consolidando la comprensión de cuándo y cómo adaptar la comunicación con prospectos.

**Instrucciones:**

1. Abre la carpeta **Borradores** y localiza ambos correos:
   - El correo de **bienvenida** del lab 01-08-08.
   - El correo de **seguimiento** que acabas de crear.

2. Compáralos lado a lado (puedes abrir ambos en ventanas separadas haciendo doble clic en cada uno) y completa mentalmente (o en una nota rápida) la siguiente tabla comparativa:

   | Dimensión | Correo de Bienvenida (01-08-08) | Correo de Seguimiento (01-08-09) |
   |---|---|---|
   | **Propósito principal** | Presentarse y generar interés inicial | Reforzar relación y confirmar acuerdos |
   | **Nivel de detalle del prospecto** | Información general del perfil | Información específica confirmada en reunión |
   | **Estructura de contenido** | Presentación de firma + propuesta de reunión | Agradecimiento + síntesis + próximos pasos |
   | **Tono predominante** | Introductorio, generador de confianza | Colaborativo, orientado a acción |
   | **Próximos pasos** | Uno solo (agendar reunión) | Múltiples, con fechas y responsables |
   | **Complejidad del prompt** | Moderada (contexto general) | Alta (contexto de reunión específico) |

3. Reflexiona sobre la siguiente pregunta: **¿Cómo cambió tu estrategia de prompting entre el lab 01-08-08 y este lab?** Considera:
   - ¿Incluiste más contexto específico en el prompt de seguimiento?
   - ¿Necesitaste menos iteraciones para lograr un resultado satisfactorio?
   - ¿Qué elementos del prompt fueron más determinantes para la calidad del resultado?

**Resultado esperado:** El estudiante identifica al menos 3 diferencias significativas entre ambos correos y reconoce que el correo de seguimiento requiere mayor especificidad contextual en el prompt pero puede lograrse con menos iteraciones gracias a la experiencia acumulada.

**Verificación:**
- ✅ Puedes articular al menos 3 diferencias entre ambos correos.
- ✅ Reconoces que el prompt del correo de seguimiento fue más largo pero más eficiente (menos iteraciones necesarias).
- ✅ Identificas que los próximos pasos accionables son el elemento diferenciador clave del correo de seguimiento.

---

## 7. Validación y Pruebas

Antes de considerar el laboratorio completado, verifica los siguientes criterios de éxito:

### Lista de Validación Final

| # | Criterio de Validación | Estado |
|---|---|---|
| 1 | El correo de seguimiento está guardado en la carpeta **Borradores** de Outlook. | ☐ |
| 2 | El campo **Para:** contiene `carlos.mendoza@logistica-mendoza.com.mx`. | ☐ |
| 3 | El **asunto** incluye "Seguimiento" y los nombres "CIBEST CAPITAL" y "Carlos Mendoza". | ☐ |
| 4 | El cuerpo incluye un **agradecimiento personalizado** que referencia la reunión específica. | ☐ |
| 5 | El cuerpo incluye una **síntesis** que menciona al menos 3 de los 6 puntos del escenario de reunión. | ☐ |
| 6 | Los **próximos pasos** están en formato de lista con **3 acciones** diferenciadas. | ☐ |
| 7 | Cada próximo paso incluye **responsable** (CIBEST CAPITAL o Carlos) y **plazo** específico. | ☐ |
| 8 | El correo **no contiene tecnicismos** financieros sin explicación. | ☐ |
| 9 | La **extensión** del cuerpo es moderada (200-350 palabras aproximadamente). | ☐ |
| 10 | El correo **NO fue enviado** (solo guardado como borrador). | ☐ |
| 11 | Se completó la **reflexión comparativa** entre correo de bienvenida y de seguimiento. | ☐ |

### Criterio de Aprobación

- **Mínimo 9 de 11 criterios** deben estar marcados como cumplidos para considerar el laboratorio exitoso.
- Los criterios **1, 6, 7 y 10** son **obligatorios** (no negociables).

---

## 8. Solución de Problemas

### Problema 1: Copilot genera un correo genérico sin detalles específicos de la reunión

**Síntomas:** El borrador generado por Copilot utiliza frases vagas como "fue un placer reunirnos" o "discutimos varios temas de interés" sin mencionar detalles concretos como el horizonte de 5 años, la preocupación por liquidez o el rango de inversión de USD 200K-350K.

**Causa:** El prompt enviado a Copilot no contenía suficiente contexto específico, o los datos de la reunión estaban formulados de manera demasiado general. Copilot tiende a generar contenido genérico cuando el prompt carece de detalles concretos y cuantificables.

**Solución:**
1. Haz clic en **"Regenerar"** (o el ícono de recarga) debajo del borrador generado.
2. En el cuadro de prompt, **reescribe o complementa** el prompt original asegurándote de incluir datos numéricos y específicos. Por ejemplo, en lugar de "discutimos su interés en inversiones", escribe:
   ```
   Carlos confirmó interés en diversificar con horizonte de 5 años, expresó preocupación por liquidez, y mencionó un rango de inversión inicial de USD 200,000 a USD 350,000 en opciones de bajo riesgo.
   ```
3. Incluye los próximos pasos como una lista explícita dentro del prompt con plazos numéricos (5 días hábiles, 2 semanas, 7 días).
4. Regenera y verifica que el nuevo borrador incluya los datos específicos.

---

### Problema 2: La opción "Borrador con Copilot" no aparece al crear un nuevo correo

**Síntomas:** Al hacer clic en "Nuevo correo", el cuerpo del mensaje muestra el área de composición normal pero no aparece el ícono de Copilot (✨) ni el botón "Borrador con Copilot" en ninguna parte de la interfaz.

**Causa:** Este problema puede ocurrir por tres razones: (a) la licencia de Microsoft 365 Copilot no está correctamente asignada a la cuenta del usuario, (b) Outlook está ejecutándose en una versión anterior a la 2405, o (c) existe un problema de caché de la aplicación que impide cargar los complementos de Copilot.

**Solución:**
1. **Verifica la versión de Outlook:** Ve a **Archivo > Cuenta de Office > Acerca de Outlook** y confirma que la versión sea **2405 (Build 17628.20164)** o superior. Si es inferior, actualiza: **Archivo > Cuenta de Office > Opciones de actualización > Actualizar ahora**.
2. **Verifica la licencia de Copilot:** Ve a **Archivo > Cuenta de Office** y revisa que "Microsoft 365 Copilot" aparezca en la lista de suscripciones o productos. Si no aparece, contacta al administrador de TI.
3. **Reinicia Outlook completamente:**
   - Cierra Outlook.
   - Abre el **Administrador de tareas** (`Ctrl + Shift + Esc`), busca cualquier proceso de Outlook en ejecución y finalízalo.
   - Espera 30 segundos.
   - Vuelve a abrir Outlook y crea un nuevo correo.
4. **Alternativa con Nuevo Outlook:** Si usas la versión clásica de Outlook y el problema persiste, prueba con el **Nuevo Outlook para Windows** (toggle disponible en la esquina superior derecha de Outlook clásico: "Probar el nuevo Outlook"). La versión nueva tiene mejor integración nativa con Copilot.

---

## 9. Limpieza

Este laboratorio genera un único artefacto que **debe conservarse** para el siguiente lab:

| Artefacto | Ubicación | Acción |
|---|---|---|
| Correo de seguimiento (borrador) | Carpeta **Borradores** en Outlook | **CONSERVAR** — Será referenciado como insumo narrativo en el lab 01-08-10. |
| Correo de bienvenida (borrador del lab 01-08-08) | Carpeta **Borradores** en Outlook | **CONSERVAR** — Necesario para la reflexión comparativa y continuidad del batch. |

> ⚠️ **No elimines ningún borrador** de la carpeta Borradores de Outlook. Ambos correos (bienvenida y seguimiento) forman parte del flujo de comunicación con el prospecto y serán referenciados en el laboratorio final 01-08-10, donde prepararás la agenda de reunión interna del equipo de CIBEST CAPITAL.

No se requieren acciones de limpieza adicionales para este laboratorio.

---

## 10. Resumen

En este laboratorio de 10 minutos aplicaste las habilidades de prompting contextual adquiridas a lo largo del batch para generar un correo de seguimiento post-reunión profesional y específico utilizando **Borrador con Copilot** en Outlook. Los logros clave incluyen:

| Logro | Detalle |
|---|---|
| **Prompting eficiente** | Construiste un prompt único y completo que incorporó 6 puntos específicos de la reunión, estructura de 4 secciones, restricciones de tono y extensión — logrando un borrador de calidad con mínimas iteraciones. |
| **Próximos pasos accionables** | Generaste una sección de próximos pasos con 3 acciones diferenciadas, cada una con responsable asignado y plazo específico — un estándar profesional en comunicación post-reunión. |
| **Contexto acumulado** | Integraste el conocimiento del perfil de Carlos Mendoza (labs anteriores) con los resultados de la reunión ficticia, demostrando que Copilot produce mejores resultados cuando el prompt refleja contexto real y específico. |
| **Reflexión comparativa** | Identificaste las diferencias estructurales y de propósito entre un correo de bienvenida (introductorio) y un correo de seguimiento (orientado a acción), fortaleciendo tu criterio para adaptar comunicaciones según la etapa de la relación comercial. |

### Conexión con el Siguiente Laboratorio

El borrador guardado en este lab será un insumo narrativo para el **lab 01-08-10**, donde prepararás una agenda de reunión interna del equipo de CIBEST CAPITAL. En esa agenda, los próximos pasos comprometidos con Carlos Mendoza (propuesta preliminar, segunda reunión, recepción de documentación) se convertirán en tareas asignadas a miembros específicos del equipo.

### Recursos Adicionales

| Recurso | Enlace |
|---|---|
| Documentación oficial: Copilot en Outlook | [https://support.microsoft.com/es-es/copilot-outlook](https://support.microsoft.com/es-es/copilot-outlook) |
| Buenas prácticas para prompts eficaces en M365 Copilot | [https://support.microsoft.com/es-es/topic/crear-prompts-eficaces-para-microsoft-365-copilot](https://support.microsoft.com/es-es/topic/crear-prompts-eficaces-para-microsoft-365-copilot-1d9a4d6f-7e8d-4e4a-b4f3-3a6e3e4e4e4e) |
| Guía de adopción de Microsoft 365 Copilot | [https://adoption.microsoft.com/es-es/copilot/](https://adoption.microsoft.com/es-es/copilot/) |
| Microsoft Copilot para ventas — Comunicación con prospectos | [https://learn.microsoft.com/es-es/microsoft-sales-copilot/introduction](https://learn.microsoft.com/es-es/microsoft-sales-copilot/introduction) |

---

# Práctica guiada en Teams con Copilot: preparación de agenda de reunión interna de coordinación previa al siguiente contacto con el prospecto

## Metadatos del Laboratorio

| Campo | Detalle |
|---|---|
| **Duración** | 10 minutos |
| **Complejidad** | Fácil |
| **Nivel de Bloom** | Aplicar |
| **Módulo** | 1.8 — Preparación de una propuesta inicial para un prospecto de CIBEST CAPITAL |
| **Posición en el batch** | Lab 5 de 5 (cierre integrador) |
| **Aplicación principal** | Microsoft Teams con Microsoft 365 Copilot |

---

## Descripción General

Este laboratorio es el cierre integrador del módulo completo. Utilizarás Microsoft Teams y Copilot para crear una agenda estructurada de reunión interna que el equipo de CIBEST CAPITAL usaría para coordinarse antes de un segundo contacto con el prospecto **Carlos Mendoza**. La agenda consolidará toda la información generada en los laboratorios anteriores — presentación PowerPoint (01-08-06), matriz Excel (01-08-07), ficha de preparación Word (01-08-08) y borradores de correo en Outlook (01-08-09) — en un documento de coordinación coherente con puntos de agenda, responsables y tiempos estimados. Al finalizar, reflexionarás sobre cómo el flujo de trabajo integrado con Copilot a través de múltiples aplicaciones M365 potencia la gestión profesional de prospectos de inversión.

---

## Objetivos de Aprendizaje

Al completar este laboratorio, serás capaz de:

- [ ] Utilizar Copilot en Microsoft Teams para generar una agenda estructurada de reunión interna que consolide información de múltiples fuentes del módulo.
- [ ] Identificar y documentar en la agenda los aspectos pendientes de confirmar con el prospecto, los especialistas internos requeridos y las preguntas que el equipo debe resolver.
- [ ] Aplicar Copilot para refinar la agenda agregando responsables por punto, reformulando títulos y generando un resumen ejecutivo.
- [ ] Sintetizar el aprendizaje del módulo completo integrando los outputs de PowerPoint, Excel, Outlook y Word en un documento de coordinación interna coherente.

---

## Prerrequisitos

### Conocimientos Previos

| Requisito | Descripción |
|---|---|
| Labs anteriores completados | Haber finalizado los laboratorios 01-08-06 (PowerPoint), 01-08-07 (Excel), 01-08-08 (Word) y 01-08-09 (Outlook) |
| Perfil del prospecto | Conocer el perfil completo de Carlos Mendoza: propietario de empresa de logística en México, ingresos anuales ~USD 5M, interés en diversificar patrimonio en activos en EE.UU., experiencia limitada en inversiones internacionales |
| Flujo del módulo | Comprensión del flujo completo: investigación → planificación → documentación → seguimiento → coordinación interna |
| Prompting básico | Experiencia con redacción de prompts para Copilot adquirida en los labs previos |

### Acceso y Licencias

| Requisito | Detalle |
|---|---|
| Cuenta Microsoft 365 | Cuenta organizacional con licencia Microsoft 365 Copilot activa |
| Microsoft Teams | Versión 24193.x o superior (New Teams) instalado e iniciado sesión |
| Copilot en Teams | Verificar que el ícono de Copilot aparece en la barra lateral izquierda de Teams o dentro de la ventana de chat/reunión |
| Archivos previos | Tener disponibles en `Documentos > CIBEST_CAPITAL > Prospectos` los archivos generados en labs anteriores |

---

## Entorno del Laboratorio

### Requisitos de Hardware

| Componente | Mínimo | Recomendado |
|---|---|---|
| Procesador | 64 bits (Intel Core i5 / AMD Ryzen 5) | Intel Core i7 / AMD Ryzen 7 |
| RAM | 8 GB | 16 GB |
| Almacenamiento libre | 10 GB | 15 GB |
| Pantalla | 1366×768 | 1920×1080 |
| Internet | 10 Mbps bajada | 25 Mbps bajada |
| Periféricos | Teclado y ratón/trackpad | Teclado, ratón, webcam y micrófono |

### Requisitos de Software

| Software | Versión Requerida |
|---|---|
| Windows | Windows 10 22H2 (Build 19045) o Windows 11 23H2 (Build 22631) o superior |
| Microsoft Teams | Versión 24193.x (New Teams) o superior |
| Microsoft 365 Copilot | Licencia Premium M365 Copilot activa (servicio en la nube) |
| Microsoft Edge | 124.0.2478.97 o superior (para acceso alternativo a Copilot Chat) |
| Microsoft 365 Apps | Versión 2405 (Build 17628.20164) o superior — Canal Actual |

### Configuración Inicial del Entorno

Antes de comenzar los pasos del laboratorio, verifica lo siguiente:

**Verificación 1 — Versión de Teams:**

1. Abre Microsoft Teams.
2. Haz clic en el menú de tres puntos (`···`) junto a tu foto de perfil en la esquina superior derecha.
3. Selecciona **Configuración** > **Acerca de Teams**.
4. Confirma que la versión es **24193.x** o superior y que aparece la etiqueta **"New Teams"** o **"Microsoft Teams (trabajo o escuela)"**.

**Verificación 2 — Copilot disponible en Teams:**

1. En la barra lateral izquierda de Teams, busca el ícono de **Copilot** (un ícono con forma de escudo/diamante con colores degradados).
2. Si no lo ves, haz clic en el botón de tres puntos (`···`) en la barra lateral y busca "Copilot" en el campo de búsqueda de aplicaciones.
3. Confirma que puedes abrir la ventana de Copilot Chat dentro de Teams.

> ⚠️ **IMPORTANTE:** Si el ícono de Copilot no aparece en Teams, consulta la sección de **Solución de Problemas** al final de este laboratorio antes de continuar.

**Verificación 3 — Archivos del módulo disponibles:**

Confirma que los siguientes archivos están guardados en `Documentos > CIBEST_CAPITAL > Prospectos`:

| Archivo | Lab de origen |
|---|---|
| Presentación introductoria para Carlos Mendoza (.pptx) | 01-08-06 |
| Matriz de necesidades del prospecto (.xlsx) | 01-08-07 |
| `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` | 01-08-08 |
| Borradores de correo de seguimiento (en Outlook / Borradores) | 01-08-09 |

---

## Pasos del Laboratorio

### Paso 1: Abrir Copilot Chat en Microsoft Teams

**Objetivo:** Acceder a la interfaz de Copilot dentro de Microsoft Teams para comenzar a generar la agenda de reunión interna.

**Instrucciones:**

1. Abre **Microsoft Teams** desde la barra de tareas de Windows o desde el menú Inicio.
2. Espera a que Teams cargue completamente y verifique tu sesión (debes ver tu nombre y foto de perfil en la esquina superior derecha).
3. En la **barra lateral izquierda**, haz clic en el ícono de **Copilot** (identificado con el logotipo de Copilot en colores degradados azul-verde-púrpura).
4. Se abrirá la ventana de **Copilot Chat** en el panel central de Teams. Verás un campo de texto en la parte inferior con el mensaje placeholder *"¿En qué puedo ayudarte?"* o similar.
5. Confirma que la ventana está activa haciendo clic una vez en el campo de texto. El cursor debe parpadear indicando que puedes escribir.

**Resultado esperado:** La ventana de Copilot Chat está abierta dentro de Microsoft Teams, lista para recibir prompts. El campo de entrada de texto está activo y visible.

**Verificación:** Escribe la palabra `Hola` y presiona **Enter**. Copilot debe responder con un saludo o mensaje de bienvenida. Esto confirma que la conexión con el servicio de Copilot está activa. Una vez confirmado, puedes proceder al siguiente paso.

---

### Paso 2: Generar la agenda inicial con un prompt contextualizado

**Objetivo:** Utilizar un prompt detallado que incorpore todo el contexto acumulado del módulo para que Copilot genere una agenda de reunión interna estructurada con puntos, tiempos y propósito de cada sección.

**Instrucciones:**

1. En el campo de texto de Copilot Chat en Teams, copia y pega el siguiente prompt completo:

```
Actúa como coordinador del equipo de asesores de inversión de CIBEST CAPITAL. Necesito que generes una agenda estructurada para una reunión interna de coordinación del equipo. El propósito de esta reunión es prepararnos antes de nuestro segundo contacto con el prospecto Carlos Mendoza.

Contexto del prospecto:
- Carlos Mendoza es propietario de una empresa de logística en México con ingresos anuales aproximados de USD 5 millones.
- Tiene interés en diversificar su patrimonio invirtiendo en activos en Estados Unidos.
- Su experiencia en inversiones internacionales es limitada.
- En la reunión inicial ya se le presentó una introducción a los servicios de CIBEST CAPITAL mediante una presentación en PowerPoint adaptada a su nivel.
- Se construyó una matriz en Excel que clasifica la información conocida y pendiente por categorías: situación financiera, objetivos de inversión, tolerancia al riesgo, horizonte temporal, situación fiscal y legal.
- Se le envió un correo de seguimiento post-reunión con resumen de lo conversado y próximos pasos.

La agenda debe incluir exactamente estos 5 puntos con los tiempos indicados:
1. Revisión de información obtenida del prospecto (10 min)
2. Análisis de aspectos pendientes por categoría según la matriz Excel (15 min)
3. Definición de especialistas internos a involucrar: fiscal, legal, de inversiones (10 min)
4. Preparación de preguntas clave para la siguiente reunión con el prospecto (10 min)
5. Definición de materiales a preparar antes del siguiente contacto (5 min)

Para cada punto de la agenda incluye:
- Título del punto
- Tiempo asignado
- Objetivo específico del punto
- Descripción breve de lo que se discutirá (2-3 líneas)

Formato: tabla organizada. Duración total de la reunión: 50 minutos.
```

2. Revisa que el prompt se haya pegado correctamente y de forma completa en el campo de texto.
3. Presiona **Enter** o haz clic en el botón de enviar (ícono de flecha) para enviar el prompt a Copilot.
4. Espera a que Copilot genere la respuesta completa. Esto puede tomar entre 10 y 30 segundos.
5. Lee la agenda generada de principio a fin. Verifica que contenga los 5 puntos solicitados con sus tiempos, objetivos y descripciones.

**Resultado esperado:** Copilot genera una tabla o estructura organizada con los 5 puntos de agenda, cada uno con título, tiempo asignado (10+15+10+10+5 = 50 minutos total), objetivo específico y descripción breve. La agenda refleja el contexto del prospecto Carlos Mendoza y menciona elementos de los labs anteriores (presentación PowerPoint, matriz Excel, correo de seguimiento).

**Verificación:** Confirma los siguientes elementos en la respuesta de Copilot:

| Elemento | ¿Presente? |
|---|---|
| 5 puntos de agenda claramente diferenciados | ☐ Sí |
| Tiempos asignados que suman 50 minutos | ☐ Sí |
| Objetivo específico por cada punto | ☐ Sí |
| Descripción breve por cada punto | ☐ Sí |
| Referencia al contexto de Carlos Mendoza | ☐ Sí |
| Mención de la matriz Excel de categorías | ☐ Sí |

> 💡 **NOTA:** Si la respuesta de Copilot no incluye alguno de estos elementos, no te preocupes. En el siguiente paso refinarás la agenda con prompts adicionales. La generación de IA puede variar ligeramente entre ejecuciones.

---

### Paso 3: Refinar la agenda — agregar responsables por punto

**Objetivo:** Solicitar a Copilot que enriquezca la agenda asignando un responsable del equipo de CIBEST CAPITAL a cada punto, practicando el refinamiento iterativo de prompts.

**Instrucciones:**

1. En el mismo hilo de conversación de Copilot Chat (sin abrir una nueva conversación), escribe el siguiente prompt de refinamiento:

```
Excelente agenda. Ahora necesito que la actualices agregando una columna de "Responsable" a cada punto de la agenda. Asigna los siguientes roles del equipo de CIBEST CAPITAL como responsables:

- Punto 1 (Revisión de información): Ejecutivo de cuenta asignado
- Punto 2 (Aspectos pendientes): Analista de inversiones
- Punto 3 (Especialistas internos): Director de operaciones
- Punto 4 (Preguntas para el prospecto): Ejecutivo de cuenta asignado y Analista de inversiones (co-responsables)
- Punto 5 (Materiales a preparar): Coordinador de marketing y comunicaciones

Regenera la tabla completa incluyendo esta nueva columna de responsables.
```

2. Presiona **Enter** para enviar el prompt.
3. Espera la respuesta de Copilot. Debe regenerar la tabla completa ahora con una columna adicional de responsables.
4. Revisa que cada punto tenga asignado el responsable correcto según lo indicado en el prompt.

**Resultado esperado:** Copilot regenera la agenda en formato de tabla con una columna adicional de **"Responsable"** que muestra el rol asignado a cada punto. El punto 4 debe mostrar co-responsabilidad entre dos roles. La estructura de los 5 puntos, tiempos y descripciones se mantiene intacta.

**Verificación:** Compara los responsables asignados por Copilot con la lista proporcionada en el prompt:

- Punto 1 → Ejecutivo de cuenta asignado ☐
- Punto 2 → Analista de inversiones ☐
- Punto 3 → Director de operaciones ☐
- Punto 4 → Ejecutivo de cuenta + Analista (co-responsables) ☐
- Punto 5 → Coordinador de marketing y comunicaciones ☐

---

### Paso 4: Refinar la agenda — reformular títulos para mayor especificidad

**Objetivo:** Solicitar a Copilot que reformule los títulos genéricos de los puntos de agenda para hacerlos más específicos al caso de Carlos Mendoza, practicando la técnica de refinamiento por especificidad contextual.

**Instrucciones:**

1. En el mismo hilo de conversación, escribe el siguiente prompt:

```
Muy bien. Ahora reformula los títulos de cada punto de la agenda para que sean más específicos al caso de Carlos Mendoza. En lugar de títulos genéricos, quiero que cada título mencione explícitamente algún elemento concreto del caso. Por ejemplo, en lugar de "Revisión de información obtenida del prospecto", algo como "Revisión del perfil financiero y objetivos de diversificación de Carlos Mendoza".

Reformula los 5 títulos manteniendo toda la demás información de la tabla (tiempos, objetivos, descripciones, responsables).
```

2. Presiona **Enter** para enviar.
3. Espera la respuesta de Copilot.
4. Compara los nuevos títulos con los originales. Los títulos reformulados deben incluir referencias específicas como: nombre del prospecto, sector logístico, inversiones en EE.UU., categorías de la matriz Excel, u otros elementos contextuales del caso.

**Resultado esperado:** Copilot regenera la tabla completa con títulos reformulados que son específicos al caso de Carlos Mendoza. Por ejemplo:

| Punto | Título original (genérico) | Título reformulado (específico) — ejemplo |
|---|---|---|
| 1 | Revisión de información obtenida del prospecto | Revisión del perfil financiero y objetivos de diversificación patrimonial de Carlos Mendoza |
| 2 | Análisis de aspectos pendientes por categoría | Análisis de brechas de información en la matriz: fiscal, legal y tolerancia al riesgo de Mendoza |
| 3 | Definición de especialistas internos a involucrar | Identificación de especialistas fiscales y legales para estructuración de inversión cross-border México-EE.UU. |
| 4 | Preparación de preguntas para la siguiente reunión | Diseño de cuestionario de profundización para segunda reunión con Carlos Mendoza |
| 5 | Definición de materiales a preparar | Preparación de propuesta preliminar y materiales educativos sobre vehículos de inversión en EE.UU. |

> 📝 **NOTA:** Los títulos exactos que genere Copilot variarán. Lo importante es que sean notablemente más específicos que los originales y que reflejen elementos concretos del caso.

**Verificación:** Para cada título reformulado, confirma que incluye al menos uno de estos elementos contextuales:

- [ ] Nombre del prospecto (Carlos Mendoza)
- [ ] Sector (logística)
- [ ] Geografía (México, Estados Unidos)
- [ ] Tipo de servicio (diversificación patrimonial, inversiones internacionales)
- [ ] Referencia a herramientas del módulo (matriz, categorías)

---

### Paso 5: Generar un resumen ejecutivo de la agenda

**Objetivo:** Solicitar a Copilot que produzca un resumen ejecutivo breve de la agenda completa, apto para ser compartido rápidamente con los miembros del equipo que necesitan una vista general antes de la reunión.

**Instrucciones:**

1. En el mismo hilo de conversación, escribe el siguiente prompt:

```
Para finalizar, genera un resumen ejecutivo de esta agenda en máximo 6 líneas. El resumen debe incluir:
- Propósito de la reunión
- Nombre del prospecto y su perfil en una línea
- Número de puntos y duración total
- Los 3 resultados clave esperados de la reunión (deliverables)

El tono debe ser profesional y directo, como si fuera el texto introductorio de una invitación de calendario en Teams.
```

2. Presiona **Enter** para enviar.
3. Lee el resumen ejecutivo generado por Copilot.
4. Verifica que el resumen sea conciso (no más de 6-8 líneas), profesional y que incluya los cuatro elementos solicitados.

**Resultado esperado:** Copilot genera un párrafo breve y profesional que funciona como resumen ejecutivo de la agenda. Ejemplo de estructura esperada:

> *Reunión interna de coordinación — Caso Carlos Mendoza*
> *Propósito: Preparar al equipo de CIBEST CAPITAL para el segundo contacto con el prospecto Carlos Mendoza, propietario de empresa de logística en México (ingresos ~USD 5M) interesado en diversificación patrimonial en EE.UU. La sesión cubre 5 puntos en 50 minutos. Resultados esperados: (1) lista validada de información pendiente por confirmar, (2) asignación de especialistas fiscales y legales al caso, y (3) cuestionario de profundización listo para la próxima reunión.*

**Verificación:**

| Elemento del resumen | ¿Incluido? |
|---|---|
| Propósito de la reunión | ☐ Sí |
| Nombre y perfil breve de Carlos Mendoza | ☐ Sí |
| Número de puntos (5) y duración total (50 min) | ☐ Sí |
| Al menos 3 resultados esperados / deliverables | ☐ Sí |
| Tono profesional y directo | ☐ Sí |

---

### Paso 6: Copiar la agenda final y guardarla como referencia

**Objetivo:** Preservar el resultado del laboratorio copiando la agenda completa y el resumen ejecutivo para tenerlos disponibles como artefacto de cierre del módulo.

**Instrucciones:**

1. En la respuesta de Copilot que contiene la **tabla completa de la agenda** (con títulos reformulados y responsables — del Paso 4), posiciona el cursor sobre la respuesta.
2. Haz clic en el ícono de **Copiar** (📋) que aparece al pasar el cursor sobre la respuesta de Copilot, o selecciona todo el texto de la tabla manualmente (`Ctrl + A` dentro del bloque de respuesta) y copia con `Ctrl + C`.
3. Abre **Microsoft Word** (desde la barra de tareas o menú Inicio).
4. Crea un nuevo documento en blanco: **Archivo** > **Nuevo** > **Documento en blanco**.
5. Pega el contenido copiado con `Ctrl + V`.
6. Debajo de la tabla pegada, regresa a Teams y copia también el **resumen ejecutivo** generado en el Paso 5.
7. Pega el resumen ejecutivo debajo de la tabla en el documento de Word.
8. Agrega un título al documento: escribe en la primera línea `Agenda de Coordinación Interna — Caso Carlos Mendoza — CIBEST CAPITAL` y aplícale el estilo **Título** desde la pestaña **Inicio** > **Estilos**.
9. Guarda el archivo:
   - **Archivo** > **Guardar como** > **OneDrive** > Navega a `Documentos > CIBEST_CAPITAL > Prospectos`.
   - Nombre del archivo: `Agenda_Coordinacion_CarlosMendoza_CIBEST.docx`
   - Haz clic en **Guardar**.

**Resultado esperado:** Un documento de Word guardado en la ruta `Documentos > CIBEST_CAPITAL > Prospectos` con el nombre `Agenda_Coordinacion_CarlosMendoza_CIBEST.docx`, que contiene la agenda completa con títulos específicos, responsables, tiempos y el resumen ejecutivo.

**Verificación:**

1. Navega en el Explorador de Archivos o en OneDrive a `Documentos > CIBEST_CAPITAL > Prospectos`.
2. Confirma que el archivo `Agenda_Coordinacion_CarlosMendoza_CIBEST.docx` aparece en la lista.
3. Ábrelo y verifica que contiene:
   - [ ] Título del documento
   - [ ] Tabla de agenda con 5 puntos, tiempos, objetivos, descripciones y responsables
   - [ ] Resumen ejecutivo debajo de la tabla

---

### Paso 7: Reflexión integradora — flujo de trabajo M365 completo

**Objetivo:** Cerrar el módulo con una reflexión guiada sobre cómo el uso de Copilot a través de múltiples aplicaciones de Microsoft 365 crea un flujo de trabajo integrado para la gestión profesional de prospectos.

**Instrucciones:**

1. Regresa a la ventana de **Copilot Chat en Teams**.
2. Escribe el siguiente prompt de reflexión:

```
Hemos completado un flujo de trabajo completo para preparar el caso del prospecto Carlos Mendoza usando Microsoft 365 Copilot en múltiples aplicaciones. Resume en formato de lista numerada las 5 aplicaciones M365 que usamos y qué artefacto específico produjimos en cada una:

1. PowerPoint — [artefacto]
2. Excel — [artefacto]
3. Word — [artefacto]
4. Outlook — [artefacto]
5. Teams — [artefacto]

Luego, en un párrafo de 3 líneas, explica cómo estos artefactos se conectan entre sí para formar un flujo de trabajo cohesivo de gestión de prospectos.
```

3. Presiona **Enter** y lee la respuesta de Copilot.
4. Compara la respuesta de Copilot con tu propia experiencia en los 5 laboratorios. Reflexiona mentalmente (o anota en tu cuaderno) sobre:
   - ¿Qué aplicación + Copilot te resultó más útil?
   - ¿En qué momento del flujo sentiste que Copilot ahorró más tiempo?
   - ¿Qué ajustarías en los prompts si repitieras el ejercicio?

**Resultado esperado:** Copilot genera una lista que mapea cada aplicación M365 con su artefacto correspondiente y un párrafo de conexión. La respuesta debe reflejar algo similar a:

| Aplicación | Artefacto producido |
|---|---|
| PowerPoint | Presentación introductoria adaptada al perfil de Carlos Mendoza |
| Excel | Matriz estructurada de necesidades con información conocida y pendiente |
| Word | Ficha de preparación para la reunión (`Ficha_Preparacion_CarlosMendoza_CIBEST.docx`) |
| Outlook | Correos de seguimiento post-reunión y de coordinación interna |
| Teams | Agenda de reunión interna de coordinación con responsables y tiempos |

**Verificación:** Este paso es de reflexión. No requiere verificación técnica formal. Confirma que:

- [ ] Leíste la respuesta de Copilot sobre el flujo integrado.
- [ ] Identificaste mentalmente al menos una ventaja concreta del flujo de trabajo con Copilot en múltiples aplicaciones.
- [ ] Puedes explicar en una oración cómo los 5 artefactos se conectan entre sí en el proceso de gestión del prospecto.

---

## Validación y Pruebas

Al finalizar todos los pasos, verifica que has completado exitosamente el laboratorio confirmando los siguientes criterios:

### Lista de Verificación Final

| # | Criterio de Éxito | Estado |
|---|---|---|
| 1 | Copilot Chat se abrió correctamente dentro de Microsoft Teams | ☐ |
| 2 | Se generó una agenda inicial con 5 puntos, tiempos y descripciones | ☐ |
| 3 | Se agregaron responsables del equipo a cada punto de la agenda | ☐ |
| 4 | Los títulos de los puntos fueron reformulados con especificidad contextual al caso de Carlos Mendoza | ☐ |
| 5 | Se generó un resumen ejecutivo conciso y profesional de la agenda | ☐ |
| 6 | La agenda final fue copiada y guardada como `Agenda_Coordinacion_CarlosMendoza_CIBEST.docx` en `Documentos > CIBEST_CAPITAL > Prospectos` | ☐ |
| 7 | Se completó la reflexión integradora sobre el flujo M365 completo | ☐ |

### Inventario de Archivos del Módulo Completo

Confirma que la carpeta `Documentos > CIBEST_CAPITAL > Prospectos` contiene ahora todos los artefactos del batch:

| Archivo | Lab de origen | ¿Presente? |
|---|---|---|
| Presentación introductoria Carlos Mendoza (.pptx) | 01-08-06 | ☐ |
| Matriz de necesidades del prospecto (.xlsx) | 01-08-07 | ☐ |
| `Ficha_Preparacion_CarlosMendoza_CIBEST.docx` | 01-08-08 | ☐ |
| Borradores de correo en Outlook (Borradores) | 01-08-09 | ☐ |
| `Agenda_Coordinacion_CarlosMendoza_CIBEST.docx` | 01-08-10 | ☐ |

---

## Solución de Problemas

### Problema 1: El ícono de Copilot no aparece en la barra lateral de Microsoft Teams

**Síntomas:** Al abrir Microsoft Teams, no se encuentra el ícono de Copilot en la barra lateral izquierda. Al buscar "Copilot" en el buscador de aplicaciones de Teams, no aparecen resultados o aparece como no disponible.

**Causa:** Este problema ocurre típicamente por una de estas razones: (a) la licencia de Microsoft 365 Copilot no está asignada a la cuenta del usuario en el tenant organizacional, (b) el administrador de TI ha deshabilitado Copilot en Teams mediante políticas de administración, o (c) la versión de Teams instalada es la versión clásica (legacy) en lugar de New Teams, y la versión clásica no soporta todas las funcionalidades de Copilot.

**Solución:**

1. **Verifica la versión de Teams:** Haz clic en `···` > **Configuración** > **Acerca de Teams**. Si dice "Microsoft Teams clásico", necesitas migrar a New Teams. Haz clic en el toggle **"Probar el nuevo Teams"** en la esquina superior izquierda de la ventana de Teams si está disponible.
2. **Verifica la licencia:** Ve a [https://portal.office.com](https://portal.office.com) > **Mi cuenta** > **Suscripciones** y confirma que "Microsoft 365 Copilot" aparece en tu lista de licencias activas.
3. **Alternativa temporal:** Si Copilot no está disponible directamente en Teams, accede a **Microsoft 365 Copilot Chat** desde el navegador en [https://copilot.microsoft.com](https://copilot.microsoft.com) iniciando sesión con tu cuenta organizacional M365. Puedes completar todos los prompts de este laboratorio desde allí y luego pegar los resultados en Word.
4. **Contacta al administrador:** Si la licencia no está asignada o Copilot está bloqueado por política, solicita al administrador de TI que habilite Copilot para tu cuenta.

---

### Problema 2: Copilot genera una agenda incompleta o ignora parte del contexto del prompt

**Síntomas:** Al enviar el prompt del Paso 2, Copilot genera una agenda con menos de 5 puntos, omite los tiempos asignados, no incluye las descripciones solicitadas, o produce contenido genérico que no refleja el contexto de Carlos Mendoza ni de CIBEST CAPITAL.

**Causa:** Los modelos de lenguaje pueden truncar o simplificar respuestas cuando el prompt es muy extenso, cuando hay congestión en el servicio, o cuando la ventana de contexto se satura. También puede ocurrir si el prompt fue pegado parcialmente (texto cortado) o si hay caracteres especiales que interfieren con la interpretación.

**Solución:**

1. **Verifica que el prompt se pegó completo:** Antes de enviar, desplázate por todo el texto en el campo de entrada y confirma que termina con `Duración total de la reunión: 50 minutos.` Si se cortó, borra el campo y pega nuevamente.
2. **Divide el prompt en dos partes:** Si Copilot sigue generando respuestas incompletas, envía primero solo el bloque de contexto del prospecto, y luego en un segundo mensaje envía la solicitud de los 5 puntos de agenda con el formato deseado. Copilot mantendrá el contexto del mensaje anterior.
3. **Solicita completar la respuesta:** Si la respuesta se cortó a mitad de generación, simplemente escribe: `Continúa. Completa la tabla con los puntos que faltan.` y Copilot retomará donde se detuvo.
4. **Regenera la respuesta:** Pasa el cursor sobre la respuesta de Copilot y haz clic en el ícono de **regenerar** (🔄) si está disponible, o escribe: `Regenera la agenda completa con los 5 puntos, incluyendo todos los campos solicitados: título, tiempo, objetivo y descripción.`

---

## Limpieza

Este laboratorio no requiere limpieza de recursos técnicos significativos. Realiza las siguientes acciones de cierre:

1. **Conserva el archivo generado:** No elimines `Agenda_Coordinacion_CarlosMendoza_CIBEST.docx` de la carpeta `Documentos > CIBEST_CAPITAL > Prospectos`. Este archivo, junto con los demás artefactos del batch, será referenciado en laboratorios del batch 2.

2. **Historial de Copilot Chat:** El hilo de conversación en Copilot Chat de Teams se conserva automáticamente en tu historial. No es necesario eliminarlo. Si deseas mantener el espacio organizado, puedes renombrar la conversación haciendo clic derecho sobre ella en el panel lateral y seleccionando **"Renombrar"**, asignándole el nombre: `Lab 01-08-10 — Agenda coordinación Mendoza`.

3. **Cierre de aplicaciones:** Si has terminado la sesión de trabajo del módulo completo, puedes cerrar Teams y Word. Asegúrate de que el documento de Word se haya guardado correctamente en OneDrive antes de cerrar (verifica el indicador **"Guardado"** en la barra de título).

---

## Resumen

En este laboratorio completaste el cierre integrador del módulo de preparación de propuesta para un prospecto de CIBEST CAPITAL. Los logros clave fueron:

| Logro | Detalle |
|---|---|
| **Generación de agenda** | Creaste una agenda de reunión interna de 5 puntos y 50 minutos usando Copilot en Teams con un prompt contextualizado |
| **Refinamiento iterativo** | Practicaste tres ciclos de refinamiento: agregar responsables, reformular títulos con especificidad contextual y generar un resumen ejecutivo |
| **Integración multi-app** | Consolidaste información de PowerPoint, Excel, Word y Outlook en un documento de coordinación en Teams |
| **Flujo de trabajo completo** | Completaste el ciclo completo de gestión de prospecto: investigación → presentación → análisis → comunicación → coordinación interna |

### Conexión con el Flujo de Trabajo Profesional

La agenda que generaste representa el paso final del ciclo de preparación pre-venta en un contexto real de asesoría de inversiones. En la práctica profesional, este documento:

- Se compartiría como invitación de calendario en Teams con los participantes asignados.
- Serviría como guía de facilitación durante la reunión interna.
- Produciría un acta de acuerdos que alimentaría la preparación del segundo contacto con el prospecto.

### Recursos Adicionales

| Recurso | Enlace |
|---|---|
| Copilot en Microsoft Teams — Documentación oficial | [https://learn.microsoft.com/es-es/microsoft-365-copilot/microsoft-365-copilot-teams](https://learn.microsoft.com/es-es/microsoft-365-copilot/microsoft-365-copilot-teams) |
| Guía de prompts efectivos para Microsoft 365 Copilot | [https://support.microsoft.com/es-es/copilot-prompts](https://support.microsoft.com/es-es/copilot-prompts) |
| Microsoft 365 Copilot — Escenarios para servicios financieros | [https://adoption.microsoft.com/es-es/copilot/financial-services/](https://adoption.microsoft.com/es-es/copilot/financial-services/) |
| Mejores prácticas para reuniones productivas en Teams | [https://learn.microsoft.com/es-es/microsoftteams/best-practices-meetings](https://learn.microsoft.com/es-es/microsoftteams/best-practices-meetings) |

---

> ✅ **¡Felicidades!** Has completado el laboratorio 01-08-10 y con él todo el batch de laboratorios del módulo 1.8. Ahora cuentas con un flujo de trabajo completo — desde la investigación inicial hasta la coordinación interna del equipo — potenciado por Microsoft 365 Copilot a través de cinco aplicaciones diferentes. Los artefactos generados en esta carpeta de trabajo serán la base para los laboratorios del batch 2.
