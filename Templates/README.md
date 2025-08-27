# 📂 Plantillas Zabbix

En esta sección encontrarás las plantillas disponibles para ser importadas en **Zabbix**, listas para su uso o adaptación según las necesidades de tu infraestructura.  

Actualmente se incluye:

## 🖥️ Lenovo R630 – Server Monitoring (SNMPv3)
Plantilla diseñada para el monitoreo del servidor **Lenovo ThinkSystem R630** utilizando **SNMPv3**.  
Permite obtener métricas clave de hardware y estado general del equipo, sin necesidad de instalar agentes en el servidor.  

### ⚙️ Requisitos básicos
Para utilizar esta plantilla es necesario:  
- Tener habilitado **SNMPv3** en el servidor Lenovo R630.  
- Configurar en Zabbix las credenciales de acceso SNMPv3 (usuario, autenticación y cifrado).  
- Contar con Zabbix versión **5.0 o superior** (recomendado).  

### 📥 Importación en Zabbix
1. Ingresar a la interfaz web de Zabbix.  
2. Ir a **Configuration → Templates**.  
3. Hacer clic en **Import**.  
4. Seleccionar el archivo `.xml` de la plantilla Lenovo R630.  
5. Asignar la plantilla al host correspondiente y configurar los parámetros de SNMPv3.  

### 🔍 Métricas disponibles
- Estado de CPU, memoria y almacenamiento.  
- Sensores de temperatura y voltaje.  
- Estado de ventiladores y energía.  
- Información general del hardware vía SNMP.  

---

⚡ Próximamente se añadirán más plantillas para distintos servicios, dispositivos y aplicaciones.
