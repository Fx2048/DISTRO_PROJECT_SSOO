
---

# I. INTRODUCCIÓN

El presente proyecto tiene como finalidad construir un sistema operativo funcional basado en **Linux From Scratch (LFS)**, siguiendo las pautas del curso y aplicando metodologías ágiles para su desarrollo. A través de la división por fases y tareas concretas, se busca entregar un producto operativo, personalizado, y documentado, que refleje el aprendizaje técnico adquirido por el equipo.

---

# II. METODOLOGÍA

## II.A EQUIPO SCRUM

*(código de imagen aquí para el organigrama del equipo)*

📌 **Brigitte** - *Product Owner*

🔹 Define objetivos y revisa entregables.

🔹 Coordina personalización del sistema.

🔹 Supervisa tiempos y calidad.

🔹 Valida cumplimiento de requisitos funcionales.

📌 **Frank** - *Scrum Master & Desarrollo Técnico*

🔹 Facilita la comunicación y seguimiento.

🔹 Responsable de la compilación del toolchain (Binutils, GCC, Glibc).

🔹 Documenta errores y soluciones rápidas.

🔹 Asegura la integración fluida de herramientas.

📌 **Jorge** - *Desarrollo Técnico*

🔹 Encargado de la compilación del sistema base (Capítulos 6–8).

🔹 Implementa scripts de arranque y configuración.

🔹 Instala y configura GRUB.

🔹 Ejecuta pruebas funcionales en entorno virtual.

📌 **Matías** - *Desarrollo Técnico*

🔹 Instala y compila paquetes esenciales del sistema.

🔹 Verifica estabilidad y rendimiento.

🔹 Apoya en la integración del gestor GRUB.

🔹 Realiza pruebas en chroot.



## II.B CRONOGRAMA

*(código de imagen aquí para la línea de tiempo del proyecto)*

---

# III. DESARROLLO TÉCNICO

## Objetivo General del Proyecto

Construir un sistema operativo funcional basado en Linux From Scratch, completamente personalizado, con documentación técnica detallada y funcionalidad mínima según especificaciones del curso.


## 🗂️ Objetivos Específicos  
1️⃣ **Configurar el Toolchain** → Compilar herramientas temporales como **Binutils, GCC y Glibc**, asegurando un entorno estable para la construcción del sistema base.  
2️⃣ **Construir el sistema base** → Implementar desde fuentes los paquetes esenciales en un entorno **chroot**, garantizando la correcta integración y funcionamiento del sistema.  
3️⃣ **Configurar el gestor de arranque** → Instalar y ajustar **GRUB** para permitir el arranque autónomo del sistema desde un disco virtual.  
4️⃣ **Integrar una interfaz gráfica básica** → Instalar **Xorg y un gestor de ventanas ligero** (Fluxbox, XFCE) para mejorar la usabilidad del sistema.  
5️⃣ **Implementar aplicaciones esenciales** → Agregar **navegador, editor de texto y terminal gráfica**, asegurando funcionalidades mínimas para el usuario final.  
6️⃣ **Documentar el proceso de desarrollo** → Generar **bitácoras técnicas y una presentación en LaTeX y Word**, detallando pasos clave y soluciones aplicadas.  
7️⃣ **Validar la estabilidad y funcionalidad** → Realizar **pruebas de ejecución** del sistema operativo en un entorno virtual antes de la entrega final.  



---

## 🗂️ FASE 1: Preparación y Entorno de Desarrollo

**🎯 Hito 1: Entorno Virtual Establecido**
🔧 Responsable: *Matías*

**Objetivo:** Tener una VM Ubuntu operativa con herramientas instaladas.
**Tiempo:** 2 días

**Subtareas:**

* Crear VM (VirtualBox).
* Instalar build-essential, wget, etc.
* Crear estructuras: `/mnt/lfs`, `/sources`, `/tools`.
* Descargar guía LFS.
* Verificar conectividad y entorno limpio.

✔ *Entrega esperada:* Captura funcional del entorno y logs.

---

## 🗂️ FASE 2: Construcción del Sistema Base

**🎯 Hito 2: Toolchain Temporal**
🔧 Responsable: *Frank*

**Objetivo:** Compilar herramientas temporales del Cap. 5
**Tiempo:** 1 semana

**Subtareas:**

* Crear usuario `lfs`.
* Descargar paquetes con `wget-list`.
* Compilar herramientas temporales.
* Documentar errores comunes.
* Validar PATH con `$LFS/tools/bin`.

✔ *Entrega esperada:* Bitácora detallada y entorno validado.

---

**🎯 Hito 3: Construcción del Sistema LFS (Cap. 6–8)**
🔧 Responsable: *Jorge*

**Objetivo:** Construir sistema base en entorno chroot
**Tiempo:** 1.5 semanas

**Subtareas:**

* Entrar a `chroot`.
* Compilar todos los paquetes base.
* Crear scripts de arranque.
* Instalar y configurar GRUB.
* Verificar arranque autónomo.

✔ *Entrega esperada:* Video o prueba corriendo desde disco virtual.

---

## 🗂️ FASE 3: Personalización del Sistema

**🎯 Hito 4: Interfaz y Aplicaciones**
🔧 Responsable: *Brigitte*

**Objetivo:** Añadir entorno gráfico y apps útiles
**Tiempo:** 1 semana

**Subtareas:**

* Consultar BLFS sobre instalación de Xorg.
* Instalar gestor de ventanas (ej. Fluxbox).
* Añadir apps: navegador, editor, terminal.
* Crear script automático.

✔ *Entrega esperada:* Capturas de GUI y scripts funcionales.

---

**🎯 Hito 5: Seguridad, Optimización y Personalización Avanzada**
🔧 Responsables: *Trabajo en pares*

**Objetivo:** Añadir características únicas y de seguridad
**Tiempo:** 5 días

**Subtareas:**

* Login personalizado (`/etc/passwd`, getty).
* Configurar firewall básico (iptables).
* Optimizar scripts de arranque.
* Gestión y rotación de logs.

✔ *Entrega esperada:* Bitácora, capturas funcionales y código fuente.

---

## 🗂️ FASE 4: Documentación y Empaquetado

**🎯 Hito 6: Manual Técnico y Live USB**
🔧 Responsables: *Todos (por secciones)*
**Tiempo:** 5 días

**Objetivo:** Crear guía final y empaquetar sistema
**Subtareas:**

* Redactar manual con capturas y decisiones técnicas.
* Crear Live ISO con Linux Live Kit o mkdistro.
* Probar en VM o USB físico.

✔ *Entrega esperada:* Manual PDF, ISO funcional y guía de uso.

---

# IV. RESULTADOS

*(código de imágenes de resultados: capturas de compilación, entorno, sistema arrancando, GUI, ISO ejecutándose, etc.)*

---

# V. CONCLUSIONES

## ✔️ Logros Principales

* Se logró construir un sistema funcional desde cero siguiendo los principios de Linux From Scratch.
* Cada integrante cumplió con su rol, permitiendo una integración fluida y un producto estable.
* El sistema cuenta con entorno gráfico, aplicaciones esenciales, scripts personalizados y documentación clara.

## 🧠 Lecciones Aprendidas

* La documentación constante es clave para resolver errores recurrentes.
* El uso de entornos virtuales aislados y bien configurados previene pérdidas críticas.
* La planificación por hitos facilita la entrega de resultados concretos en tiempos limitados.

## 🚀 Siguientes Pasos

* Evaluar la portabilidad del sistema a arquitecturas ARM.
* Mejorar la interfaz de usuario con otros gestores gráficos.
* Automatizar todo el proceso con un script completo `make-lfs.sh`.

---

# 🗂️ GESTIÓN SEMANAL

| Semana | Fase                | Hito   | Responsable(s)   |
| ------ | ------------------- | ------ | ---------------- |
| 1      | Preparación         | Hito 1 | Matías           |
| 2      | Toolchain           | Hito 2 | Frank            |
| 3      | Sistema base        | Hito 3 | Jorge            |
| 4      | GUI y apps          | Hito 4 | Brigitte         |
| 5      | Personalización     | Hito 5 | Todos (en pares) |
| 6      | Documentación final | Hito 6 | Todos            |

---

