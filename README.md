# retodocker
# 🌐 Implementación de la Web Corporativa: WordPress + Docker

## 1. Introducción
Como parte de mi contribución al **Reto 2**, voy a usar wordpress.

## 2. ¿Por qué WordPress para una web moderna?

* **Ecosistema de Diseño:** Permite el uso de constructores visuales.
* **SEO Friendly:** Su estructura está optimizada para que el campus sea fácilmente indexable por buscadores.
* **Escalabilidad:** Gracias a su sistema de plugins, podemos añadir funcionalidades futuras.

## 3. Infraestructura Tecnológica
Para garantizar la portabilidad y la eficiencia en el despliegue, la web corporativa se basa en la contenedorización:

* **Motor Web:** WordPress (Imagen oficial basada en PHP-Apache).
* **Base de Datos:** MariaDB (Para una gestión eficiente de los datos y configuración del sitio).
* **Despliegue:** Docker Compose (Orquestación de servicios).
* **Persistencia:** Volúmenes de Docker para asegurar que los cambios de diseño y archivos multimedia no se pierdan al reiniciar los contenedores.