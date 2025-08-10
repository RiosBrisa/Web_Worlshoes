# Web_Worldshoes

**Web_Worldshoes** es una aplicación web responsive de e-commerce de calzado, desarrollada como trabajo práctico integrador para la materia *Taller de Programación II* de la Universidad Nacional del Nordeste (UNNE). Utiliza el framework PHP CodeIgniter 4 y está diseñada para ofrecer una experiencia de compra moderna y funcional.

---

## 🚀 Características

- Interfaz responsive para dispositivos móviles y escritorio  
- Gestión de productos con categorías, precios y novedades  
- Carrito de compras funcional  
- Registro y autenticación de usuarios con roles (cliente y administrador)  
- Panel de administración para gestionar productos, usuarios y pedidos  
- Base de datos MySQL para almacenamiento de información  

---

## 🛠 Tecnologías utilizadas

- PHP 8.x  
- CodeIgniter 4  
- HTML5, CSS3, JavaScript (jQuery)  
- MySQL  
- Servidor local Apache mediante XAMPP  

---

## 📦 Instalación y configuración

Para usar este proyecto, seguí estos pasos:

1. **Instalar XAMPP**  
   Descargá e instalá XAMPP desde [https://www.apachefriends.org/es/index.html](https://www.apachefriends.org/es/index.html).  
   Luego, iniciá los servicios de **Apache** y **MySQL** desde el panel de control de XAMPP.

2. **Instalar CodeIgniter 4**  
   Descargá CodeIgniter 4 desde [https://codeigniter.com/download](https://codeigniter.com/download) y configuralo según su documentación oficial.  
   Este proyecto está basado en CodeIgniter 4, por lo que necesitás tenerlo instalado para su correcto funcionamiento.

3. **Copiar la carpeta del proyecto**  
   Copiá la carpeta `Web_Worldshoes` (que contiene el proyecto) dentro de la carpeta `htdocs` de tu instalación de XAMPP.  
   La ruta típica es:   C:/xampp/htdocs/Web_Worldshoes

4. **Configurar la base de datos**  
- Importá el archivo `database.sql` (incluido en el repositorio) a MySQL usando phpMyAdmin o línea de comandos.  
- Editá el archivo `app/Config/Database.php` para ajustar las credenciales de conexión a tu base de datos local.

5. **Acceder a la aplicación**  
Abrí tu navegador y visitá: http://localhost/Web_Worldshoes

---

## 🧪 Uso

- **Usuarios no registrados:**  
  Pueden navegar y ver todos los productos y secciones públicas del sitio, pero **no pueden realizar compras ni agregar productos al carrito**.

- **Clientes registrados:**  
  Pueden registrarse, iniciar sesión, agregar productos al carrito y realizar pedidos.

- **Administrador:**  
  Tiene acceso al panel de administración para gestionar productos, usuarios y pedidos.
---

## 🔗 Recursos útiles

- [Documentación oficial de CodeIgniter 4](https://codeigniter4.github.io/userguide/)  
- [XAMPP](https://www.apachefriends.org/es/index.html)  
- [phpMyAdmin para gestionar MySQL](https://www.phpmyadmin.net/)  
