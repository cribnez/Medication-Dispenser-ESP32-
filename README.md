# Sistema Asistido para el Control de Medicación en Adultos Mayores

Este repositorio contiene toda la documentación, firmware, hardware y software de la aplicación móvil para el "Prototipo de Sistema Asistido para el Control de Medicación en Adultos Mayores", un proyecto desarrollado en la **Universidad Politécnica de Chiapas**.

El sistema busca mejorar la adherencia terapéutica en adultos mayores mediante un dispensador inteligente que organiza la toma de medicamentos con alarmas visuales y sonoras, y permite el monitoreo remoto a través de una aplicación móvil conectada por Bluetooth.

## 🌟 Características Principales

* **Dispensador Físico:** Compartimentos controlados por servomotores que se abren a la hora programada.
* **Alarmas Multisensoriales:** Alertas visuales (LED) y sonoras (buzzer) para notificar al usuario.
* **Reloj en Tiempo Real (RTC):** Mantiene la hora exacta incluso sin energía para no perder las alarmas.
* **Control por App Móvil:** Una aplicación para Android, desarrollada en MIT App Inventor, permite configurar las alarmas y monitorear la toma de forma remota vía Bluetooth.
* **Diseño Abierto:** Se incluyen los archivos `.STL` para la impresión 3D de la carcasa.

## 📂 Contenido del Repositorio

* **/firmware**: Contiene el código fuente (`.ino`) para el microcontrolador ESP32 que controla la lógica del dispensador.
* **/hardware**: Incluye los archivos de diseño `.STL` para la impresión 3D y el diagrama del circuito.
* **/mobile_app**: Contiene el archivo fuente (`.aia`) del proyecto en MIT App Inventor y la documentación de los bloques.
* **/docs**: Documentación académica del proyecto, incluyendo la presentación y el resumen técnico.

## 📲 Aplicación Android (.apk)

La aplicación compilada (`.apk`) para instalar en dispositivos Android se puede descargar desde la sección de **[Releases](https://github.com/tu-usuario/Medication-Dispenser-ESP32-UPChiapas/releases)** de este repositorio.

## 📄 Licencia

Este proyecto se distribuye bajo la Licencia MIT.
