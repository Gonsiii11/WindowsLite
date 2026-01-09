# WindowsLite 

**WindowsLite** es una configuración de instalación desatendida de Windows optimizada para ofrecer un sistema operativo ligero, rápido y centrado en la privacidad, eliminando el "bloatware" y servicios innecesarios de telemetría.

## ⚙️ Características de la Instalación
* **Proceso Desatendido:** Instalación automatizada para ahorrar tiempo.
* **Usuario Local:** Creación automática de la cuenta `LocalUser`.
* **Control de Disco:** El instalador permite elegir y particionar el disco manualmente para mayor flexibilidad.

---

## 🛡️ Privacidad y Optimización
Se han eliminado o desactivado componentes que afectan el rendimiento y la privacidad del usuario:

* **Telemetría:** Desactivación de *Allow Telemetry*, recolección de escritura (Typed/Written text) y envío de información a Microsoft.
* **Asistentes:** Eliminación total de **Cortana** y sus botones en la barra de tareas.
* **Interfaz:** Desactivación de animaciones del escritorio, widgets de la barra de tareas y recomendaciones en el menú de inicio.
* **Servicios en la Nube:** Desactivación de **OneDrive** y servicios de geolocalización.
* **Actualizaciones:** Windows Update desactivado por defecto para evitar cambios no deseados.

---

## 🛠️ Servicios Desactivados
Para reducir el consumo de RAM y CPU, se han deshabilitado los siguientes servicios:


 **Virtualización**  Todos los servicios de Hyper-V (Data Exchange, Guest Service, Heartbeat, etc.) 
 
 **Gaming & Xbox** Xbox Live (Auth, Game Server, Networking) y Accessory Management. 
 **Conectividad**  Bluetooth Support, Bluetooth Audio Gateway, Phone Service y Telephony.
 **Búsqueda**  Windows Search e historial de búsqueda local. 
 **Telemetría**  Connected User Experiences y Telemetry. 

---

## 📦 Componentes y Apps Removidas
Se ha realizado una limpieza profunda de aplicaciones preinstaladas:

* **Multimedia:** Photos, Movies & TV, Windows Media Player, Paint, Camera y Voice Recorder.
* **Productividad:** Office, To-Do, Notepad, Mail and Calendar, Sticky Notes y Calculator.
* **Navegación y Web:** **Microsoft Edge**, Web Media Extensions y Web Experience Pack.
* **Utilidades:** Quick Assist, Remote Desktop, Feedback Hub, Get Help, Tips y Sniping Tool.
* **Gaming:** Xbox App, Game Bar y Game UI.
* **Avanzado:** Windows Subsystem for Linux (WSL), Telnet Client y TFTP Client.

---

## 🚀 Integraciones Post-Setup
El sistema incluye una fase de post-instalación para dejar el equipo listo para trabajar:

1.  **Archivos:** Instalación automática de **WinRAR** , **7-Zip** y el Emulador **RetroArch con dos juegos**.
2.  **Navegador:** Instalación de **Brave Browser** como navegador predeterminado.
3.  **Personalización:** * Aplicación de un fondo de pantalla personalizado.
    * Creación de accesos directos en el escritorio para las aplicaciones instaladas.
      
-----
      
