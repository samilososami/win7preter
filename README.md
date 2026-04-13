<div align="center">

# Win7preter

Suite de automatización para el despliegue y recepción de sesiones Meterpreter específicamente optimizada para sistemas Windows 7 (32-bit).

<br>

<img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" />
<img src="https://img.shields.io/badge/Metasploit-000000?style=for-the-badge&logo=metasploit&logoColor=white" alt="Metasploit" />

</div>

---

### ✦ Características

*   **Generación de Payloads**: Automatiza la creación de ejecutables maliciosos compatibles con arquitecturas de 32 bits mediante `msfvenom`.
*   **Gestión de Listeners**: Configura automáticamente los handlers de Metasploit para recibir las conexiones entrantes.
*   **Simplificación de Flujo**: Reduce procesos complejos a tres comandos directos.
*   **Instalación Intuitiva**: Script de `setup.sh` para la gestión automática de todas las dependencias necesarias.

### ✦ Uso Rápido

1.  Instale las dependencias:
    ```bash
    ./setup.sh
    ```
2.  Genere el payload:
    ```bash
    ./shell
    ```
3.  Inicie el listener:
    ```bash
    ./listener
    ```
4.  Ejecute el archivo generado en el host objetivo.

---

> [!CAUTION]
> Herramienta para uso exclusivo en laboratorios de seguridad controlados o bajo autorización previa.