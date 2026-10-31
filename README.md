# Portfolio profesional · Santiago Morandi

Sitio personal con experiencia, formación y proyectos de integración de sistemas, automatización y análisis de datos.

[Ver portfolio](https://morandisantiago.github.io/Porfolio/) · [Perfil de GitHub](https://github.com/MorandiSantiago)

## Alcance

Presenta la trayectoria de Ingeniero Industrial y consultor tecnológico, con el objetivo de desarrollarse como AI Integration Engineer. Cada proyecto distingue su estado: código público, prueba de concepto, documentación pendiente o trabajo privado de cliente.

No incluye credenciales, datos de clientes ni código interno. La descripción de una experiencia no implica que exista una implementación pública.

## Ejecutar localmente

Sitio estático HTML/CSS/JavaScript, sin compilación. Con Python 3:

```sh
python -m http.server 8091 --bind 127.0.0.1
```

Abrir [http://127.0.0.1:8091](http://127.0.0.1:8091). GitHub Pages publica la rama principal desde la raíz.

## Estructura

- [index.html](./index.html): presentación, experiencia, proyectos, formación y contacto.
- [styles.css](./styles.css): diseño responsive y preferencia de movimiento reducido.
- [scripts.js](./scripts.js): inicialización opcional de animaciones.
- El [laboratorio frontend](https://github.com/MorandiSantiago/proyectos-para-porfolio) se mantiene como proyecto independiente de aprendizaje; se eliminó su código duplicado de este sitio.

## Recursos externos

Las fuentes, los iconos, AOS y el reproductor Lottie se cargan desde CDN; la animación se obtiene de lottie.host. El contenido profesional principal es HTML y puede leerse sin JavaScript. Las animaciones y los iconos dependen de la disponibilidad de esos terceros. Los recursos visuales heredados no se atribuyen como creaciones propias.

## Revisión de 2026

- Perfil actualizado con estados de publicación explícitos.
- Laboratorio separado y enlazado.
- Documentación de ejecución y estructura.
- Comprobación en navegador a ancho de escritorio y móvil.
- Sin formularios que capturen datos ni integraciones autenticadas en el navegador.

Para actualizar el contenido, editar las secciones HTML; evitar agregar tecnologías que no se hayan utilizado o presentar una prueba de concepto como producto de producción.
