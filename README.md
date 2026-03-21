# Reto-01---RA2---UT4

**Proyecto: Preparación de PC de Oficina - Valentin Andriyash Andriiash**

**Ejercicio 1: Entorno Virtual**<br>
Hipervisor: VirtualBox.<br>
Recursos: 4GB RAM / 2 CPUs / 50GB Disco (Justificado por los 8GB del host).<br>
SO: Windows 11 Home.<br>
![ram y cpu](retos/emg/e1/cap1-2.PNG)<br>

**Ejercicio 2: Software de Oficina**<br>
Google Chrome: Navegador principal para Google. <br>
7-Zip: Gestión de archivos comprimidos.<br>
Adobe Reader: Lector de PDF.<br>
![ram y cpu](retos/emg/e2/capgoogle.PNG)<br>
![ram y cpu](retos/emg/e2/capzip.PNG)<br>
![ram y cpu](retos/emg/e2/cappdf.PNG)<br>
**Ejercicio 3: Seguridad y Mantenimiento**<br>
Antivirus: Microsoft Defender.<br>
Mantenimiento: Instalación de Guest Additions para rendimiento óptimo. Tambien utilio HWMonitor para ver las temperaturas y voltajes de la CPU virtual.<br>
Pruebas: Verificación de acceso a Gmail y Google Docs.<br>
![ram y cpu](retos/emg/e3/capseg.PNG)<br>
![ram y cpu](retos/emg/e3/capact.PNG)<br>

**Pruebas realizadas:**
Creacion de doc
Meter ese mismo doc a carpeta y comprimirla en 7zip

**Registro de Incidencias:**
Fallo de arranque: Error VERR_PATH_NOT_FOUND. Solución: Se eliminó el archivo .viso

**Mejoras Futuras**<br>
Ampliación de RAM: Subir a 8GB en la VM para mejorar la multitarea pesada.<br>
Automatización: Configurar tareas de limpieza de archivos temporales cada semana.<br>
Backup: Implementar una copia de seguridad automática de la unidad a un servidor externo.<br>

**Los pasos seguidos para instalar Windows:**<br>
1.Instalar .iso de w11<br>
2.Meter .iso en virtualbox y configurar ram, cpus y almacenamiento<br>
3.Abrir y configurar todo desde w11<br>

**Conclusión Final**<br>
El equipo ha sido configurado siguiendo los requerimientos de la empresa. Despues de las pruebas, se confirma que el sistema es estable, seguro y permite trabajar de forma fluida con las herramientas de Google.
