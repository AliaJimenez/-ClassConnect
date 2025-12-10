<p align="center">
  <img src="https://img.shields.io/badge/ClassConnect-Student%20Manager-blue?style=for-the-badge" />
</p>

<h1 align="center">ClassConnect</h1>

<p align="center">
  <b>Gestor estudiantil para mejorar la comunicación entre padres y maestros.</b><br>
  <i>Proyecto académico desarrollado en Java + MySQL.</i>
</p>

---

## Sobre el proyecto

**ClassConnect** es una aplicación que digitaliza la comunicación entre **padres**, **maestros** y **estudiantes**.  
Permite el envío de mensajes, visualización de información académica y una gestión clara de usuarios.

---

## Características principales
- 🧪 Comunicación directa padre–maestro  
- 👨‍🏫 Gestión de estudiantes, profesores y padres  
- 📩 Sistema de mensajes internos  
- 💾 Conexión con base de datos MySQL  
- 🖥️ Interfaz construida en Java  

---

## Tecnologías utilizadas
| Tecnología | Descripción |
|-----------|-------------|
|  **Java** | Lógica de la aplicación |
|  **Java Swing** | Interfaces Gráficas |
|  **MySQL** | Base de datos principal |
|  **Maven** | Gestión de dependencias |
|  **JDBC (MySQL Connector/J)** | Conexión Java ↔ MySQL |

---

## Requisitos previos

Asegúrate de tener instalado:

- ✔ Java 8+ / 11 / 17  
- ✔ MySQL 8.0  
- ✔ Maven  
- ✔ Driver JDBC (mysql-connector-j)

---

## Base de Datos

Dentro de la carpeta, Scrips
se encuentran las tablas utilizadas por el sistema.

Para importarlas en MySQL:

```sql
SOURCE ruta/del/archivo/create_tables.sql;
```

---

## Cómo ejecutar el proyecto

Configura tu conexión JDBC en el código.

Compila el proyecto con Maven:
```
mvn clean install
```
Ejecuta la aplicación:
```
java -jar target/ClassConnect.jar
```

<table> <tr> <td>👤 Aliandy Jimenez</td> </tr> <tr> <td>👤 Liss Espiritu</td> </tr> <tr> <td>👤 Robert Leon</td> </tr> <tr> <td>👤 Cesar Hernandez</td> </tr> </table>



Este proyecto está bajo la licencia MIT.
