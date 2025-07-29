Este programa es un sistema de gestión de productos de un supermercado, escrito en Java. Te permite:

➕ **Agregar productos:** Guarda detalles como nombre, precio, cantidad, fecha de caducidad y más.

👀 **Mostrar productos:** Lista todos los productos que tienes registrados.

✏️ **Modificar productos:** Actualiza la información de un producto existente.

🗑️ **Eliminar productos:** Borra un producto del sistema.


✨ **Características Principales.**
📦 **Gestión de Productos**
El corazón del programa es un HashMap (productos) que almacena todos tus productos. Cada producto se identifica con un ID único.

➕ **Agregar un Producto (Opción 1)**
Cuando agregas un producto, el programa te pide varios datos. ¡Mira cómo maneja la caducidad! 🗓️
☝️ Si un producto tiene fecha de caducidad y le quedan 3 o más días para vencer, ¡automáticamente le resta 1 unidad a la cantidad en bodega! Esto ayuda a gestionar el inventario de productos perecederos. 🍎

👀 **Mostrar Productos (Opción 2)**
Este bucle recorre cada producto y muestra su ID y todos sus detalles. La función capitalize se encarga de que los nombres de los campos (como "nombre", "precioUnitario") se muestren bonitos ("Nombre", "Precio Unitario"). 🌟

✏️ **Modificar Producto (Opción 3)**
Solo puedes modificar el nombre, precio unitario y cantidad en bodega de un producto existente. Si el ID no se encuentra, ¡te avisará! ⚠️

🗑️ **Eliminar Producto (Opción 4)**
Simple y directo: si el ID existe, el producto se elimina. Si no, ¡no hay nada que eliminar! 🤷‍♀️

¡Y listo! Ya puedes empezar a gestionar tus productos. 💻

Muchas gracias por tu visita👍
