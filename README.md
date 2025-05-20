# DVWA en WSL2: Configuración rápida

Este repositorio proporciona los scripts y la documentación necesarios para:

1. Habilitar WSL2 en Windows y usar Kali Linux.
2. Crear un entorno LAMP (Apache, PHP, MariaDB).
3. Instalar y configurar DVWA (Damn Vulnerable Web App).

## Flujo rápido de implementación

1. **PowerShell (Admin)** ➔ `scripts/setup_wsl.sh`
2. **Terminal WSL** ➔ `scripts/setup_php_mariadb.sh`
3. **Terminal WSL** ➔ `scripts/setup_dvwa.sh`
4. Navegador ➔ `http://localhost/DVWA/setup.php`, pulsa "Crear/Restablecer base de datos".
5. Login en DVWA: 
   - Usuario: `admin`
   - Contraseña: `password`

¡Ya puedes practicar vulnerabilidades web (SQLi, XSS, CSRF, File Inclusion, etc.)!
