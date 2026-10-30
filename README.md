[presentacion-slidev.md](https://github.com/user-attachments/files/34160637/presentacion-slidev.md)
---
theme: seriph
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Planificación Híbrida y Auditoría de IA en Escenarios Escénicos
  Trabajo Final Integrador (TFI) - Presentación Académica Slidev
drawings:
  persist: false
transition: slide-left
title: Planificación Híbrida y Auditoría de IA
mdc: true
---

# Planificación Híbrida y Auditoría de IA
## En Escenarios Escénicos

**Integración Metodológica, Propuesta Didáctica con Resolume Arena, Video Mapping y Plan B Offline**

<div class="pt-12">
  <span @click=".nav.next" class="px-2 py-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10">
    Presiona barra espaciadora o flecha derecha <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2 font-mono text-xs opacity-75">
  <b>Autora:</b> María Silvia Morosini | <b>IES N.° 6004</b> (Salta Capital)
</div>

---
layout: two-cols
---

# Contexto e Institución

### **Ficha del Proyecto**
* **Carrera:** Tecnicatura Superior en Puesta en Escena y Producción Artística
* **Institución:** IES N.° 6004 — Formación Superior (Salta Capital)
* **Espacio Curricular:** Tecnologías Aplicadas a las Artes Escénicas III (3.er Año)
* **Población:** 25 estudiantes adultos jóvenes con trayectorias laborales y familiares diversas.

::right::

### **Diagnóstico Pedagógico**
* **Problema detectado:** Pérdida masiva de tiempo presencial en tareas operativas (descarga de software, instalación de drivers, fallas de códecs en Resolume Arena).
* **Impacto negativo:** Reducción del tiempo para lo sustantivo del aula-taller (calibración de proyectores multimedia, *warping* 3D y diseño estético en tiempo real).

---
layout: default
---

# Fundamentación del Enfoque Híbrido

<div class="grid grid-cols-2 gap-4 mt-4">

<div class="border border-gray-500/30 p-4 rounded-lg bg-gray-500/5">

### 💡 Regla de No Equivalencia Pedagógica
*(Andreoli, 2021; Res. CFE 476/24)*
* La exploración instrumental, pruebas de software y ruteo de cámara se transfieren al **tramo asincrónico virtual**.
* Promueve la autorregulación y autogestión autónoma del ritmo de estudio.
</div>

<div class="border border-gray-500/30 p-4 rounded-lg bg-gray-500/5">

### 🏛️ Presencialidad Ganada
*(Pautas Salta, 2025)*
* El espacio físico del aula-taller se libera para **actividades de alta complejidad cognitiva**.
* Experimentación espacial directa con luz, escenografía tridimensional y trabajo colaborativo en vivo.
</div>

</div>

---
layout: default
---

# Secuencia Didáctica Híbrida (2 Semanas)



| Instancia | Consigna y Actividades de los Estudiantes | Recursos y Herramientas Digitales |
| :--- | :--- | :--- |
| **Tramo 1: Asincrónico** *(Autónomo)* | Visualizar micro-tutorial NDI, instalar Resolume Arena y app NDI Camera en móvil, realizar pruebas de ruteo y subir evidencia de 1 min a Moodle. | PC personal, Smartphone (NDI Camera / DroidCam), Resolume Arena, Moodle, IA (Gemini/ChatGPT). |
| **Tramo 2: Sincrónico Virtual** *(40 min)* | Plenaria diagnóstica, socializar flujos de video, resolver inconvenientes de GPU/códecs y ajustar parámetros de red local (IP fija). | Zoom/Meet, Presentación Canva, Padlet, Guía de red LAN. |
| **Tramo 3: Presencial Físico** *(80 min)* | Equipos de 3-4 alumnos, ruteo NDI en vivo, *warping* sobre escenografía 3D, muestra en vivo y activación del Plan B de contingencia. | Proyectores, cables HDMI, escenografía física, Router LAN offline, SCRCPY (USB). |

---
layout: default
---

# Co-diseño con IA y Pautas Éticas

### **Integración de IA Generativa en el Diseño Docente**
* **Prompt Estructurado:** Modelo de 6 componentes (*Rol, Contexto, Tarea, Formato, Tono, Restricciones*) para simular escenarios de fallo técnico y auditar la secuencia.
* **Escala AIAS (Furze, 2024):** Nivel de **Co-creación e Integración Crítica**.

<v-clicks>

### 🛡️ Pautas Éticas Obligatorias para Estudiantes *(Zepeda et al., 2025)*
1. **Declaración Explícita:** Reportar el uso de IA como tutor de depuración técnica en la memoria del proyecto.
2. **Verificación Humana Obligatoria:** Comprobación crítica de comandos y soluciones antes de ejecutarlos en el sistema.
3. **Protección de Datos:** Prohibición absoluta de ingresar datos personales o institucionales sensibles.

</v-clicks>

---
layout: two-cols
---

# Resiliencia y Plan B Offline

### **Estrategia Antifrágil en el Aula**
Ante la inestabilidad de conectividad a internet en el IES, se diseñó un protocolo de respuesta inmediata sin dependencia externa.

::right::

<div class="space-y-3">

<div class="p-3 border rounded border-blue-500/30 bg-blue-500/10">

#### 1. Conexión USB Directa (SCRCPY)
Captura de video desde smartphone a PC vía cable USB en tiempo real a 60 fps sin latencia ni red.
</div>

<div class="p-3 border rounded border-green-500/30 bg-green-500/10">

#### 2. Red LAN Privada Offline
Router dedicado autónomo sin internet con IP fija manual para transmisión NDI a alta velocidad.
</div>

<div class="p-3 border rounded border-amber-500/30 bg-amber-500/10">

#### 3. Media Backup Local
Pendrive USB con patrones de prueba y clips de textura para calibración en caso de fallo móvil.
</div>

</div>

---
layout: default
---

# Auditoría Crítica de la IA (Decisiones Docentes)

Se aplicó la matriz de evaluación sobre las recomendaciones generadas por la IA:

| Decisión | Sugerencia de la IA | Fundamento Pedagógico e Institucional |
| :---: | :--- | :--- |
| **ACEPTO** | Transferir la instalación y pruebas técnicas individuales al tramo asincrónico. | Optimiza el tiempo presencial ganado y promueve la autogestión autónoma *(Lemos et al., 2025)*. |
| **AJUSTO** | Crear un foro de debate sobre video mapping en artes escénicas. | Se reorienta a un foro de análisis de evidencias prácticas sobre las pruebas de ruteo realizadas. |
| **DESCARTO** | Transmitir el mapping por streaming de Zoom/Meet en directo desde los hogares durante la clase. | **Inviable por latencia de red.** Se reemplazó por ruteo NDI local mediante router offline y cable USB (SCRCPY). |

---
layout: default
---

# Checklist de Auditoría Crítica (7 Dimensiones)

<div class="grid grid-cols-2 gap-2 text-xs">

<div class="p-2 border rounded">
<b>1. Pertinencia de la modalidad:</b> SÍ<br/>
Lo presencial se reserva para calibración óptica y warping; lo asincrónico para descargas e instalación.
</div>

<div class="p-2 border rounded">
<b>2. Coherencia interna:</b> SÍ<br/>
Cada objetivo conduce a un producto observable articulado en cadena pedagógica.
</div>

<div class="p-2 border rounded">
<b>3. Viabilidad institucional:</b> SÍ<br/>
Plan B offline realista (Router LAN local, SCRCPY por USB, pendrive de respaldo).
</div>

<div class="p-2 border rounded">
<b>4. Rigor y veracidad:</b> SÍ<br/>
Fundamentado en Andreoli (2021), Anijovich (2011), Tarasow (2025) y Res. CFE 476/24.
</div>

<div class="p-2 border rounded">
<b>5. Contexto and lenguaje:</b> SÍ<br/>
Lenguaje técnico de artes escénicas (*warping, NDI, latencia, Advanced Output*).
</div>

<div class="p-2 border rounded">
<b>6. Autoría y valor agregado:</b> SÍ<br/>
Filtro crítico docente activo descartando streaming por internet en aula física.
</div>

</div>

<div class="mt-2 p-2 border rounded text-xs bg-purple-500/10 border-purple-500/30">
<b>7. Ética y cuidado de datos:</b> SÍ. Sin ingreso de datos sensibles en IA; uso auditado como co-diseñadora.
</div>

---
layout: default
---

# Adaptación a Secundaria Pública (3.er Año)

### **Estructura Semanal Distribuida (3 Horas Totales)**

| Instancia | Duración | Estrategia y Enfoque Pedagógico |
| :--- | :---: | :--- |
| **Día A: Clase Presencial Corta** | 60 min | Apertura, problematización e instrucciones claras de la hoja de ruta. |
| **Tramo Intermedio: Asincrónico/Remoto** | 30-45 min | Aula Invertida con recursos livianos (PDFs comprimidos/impresos) y autochequeo. |
| **Día B: Módulo Presencial Doble** | 120 min | Taller, producción en equipos, rotación por estaciones y cierre metacognitivo. |



---
layout: center
class: text-center
---

# Conclusiones y Evaluación Antifrágil

<div class="max-w-200 mx-auto text-left space-y-4">

* 🎯 **Presencialidad Revalorizada:** La presencialidad no se justifica por la dificultad técnica del contenido, sino por el **valor vincular, espacial y colaborativo** de la experimentación tridimensional.
* 🛡️ **Evaluación Auténtica:** Rúbrica centrada en desempeños observables (*Configuración NDI, Warping Escenográfico, Trabajo Colaborativo y Respuesta a Contingencias*).
* 🤖 **Docencia Crítica ante la IA:** La Inteligencia Artificial potencia el diseño pedagógico únicamente cuando está subordinada al criterio profesional del docente y a la realidad institucional.

</div>

<div class="mt-12 text-sm opacity-75">
¡Gracias! | TFI - María Silvia Morosini | IES N.° 6004
</div>
