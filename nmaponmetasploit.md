# usodenmapenmetasploit
📋 Tutorial: Usar Nmap dentro de Metasploit Framework

# 🔧 Paso 1: Iniciar la base de datos de Metasploit
Primero, asegúrate de que la base de datos de Metasploit esté iniciada. Esto te permitirá almacenar y gestionar los resultados de tus escaneos.

```bash
# Iniciar la base de datos
msfdb start

# Inicializar la base de datos (solo si es la primera vez)
msfdb init

# Verificar el estado de la base de datos
msfdb status
```

# 🚀 Paso 2: Ejecutar Metasploit
Una vez que la base de datos esté en funcionamiento, inicia Metasploit con el siguiente comando:

```bash
msfconsole
```

![image](https://github.com/user-attachments/assets/79a87a7f-1fe1-4893-9062-aee8cba2539a)


# 🔍 Paso 3: Usar Nmap dentro de Metasploit
Dentro de la consola de Metasploit, puedes usar Nmap para realizar escaneos. Utiliza el comando db_nmap para asegurarte de que los resultados se almacenen en la base de datos de Metasploit.

```bash
# Escaneo básico de una IP
db_nmap <ip>

# Escaneo completo de todos los puertos de una IP
db_nmap -p 1-65535 <ip>
```

# 📊 Paso 4: Ver los resultados del escaneo
Después de realizar un escaneo con Nmap, puedes ver los servicios descubiertos utilizando el comando services.

```bash
services
```

![ef2fd700-b0fd-4810-83cd-668e914690a9](https://github.com/user-attachments/assets/86a70421-2533-45c8-a785-94e22db9efd9)

Esto proporciona una guía paso a paso clara y profesional sobre cómo usar Nmap dentro de Metasploit, con cada sección claramente separada y explicada.


