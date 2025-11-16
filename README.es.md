# Frontend Mentor – Solución de Browser Extensions Manager UI

Esta es mi solución para el desafío **Browser Extensions Manager UI** en [Frontend Mentor](https://www.frontendmentor.io/).  
El desafío me ayudó a mejorar mis habilidades en **HTML, CSS y JavaScript** construyendo una interfaz interactiva inspirada en el diseño de un gestor de extensiones de navegador.

---

## Tabla de Contenidos
- [Descripción General](#descripción-general)  
- [El Desafío](#el-desafío)  
- [Diseño](#diseño)  
- [Enlaces](#enlaces)  
- [Mi Proceso](#mi-proceso)  
- [Tecnologías Usadas](#tecnologías-usadas)  
- [Lo Que Aprendí](#lo-que-aprendí)  

---

## Descripción General
Este proyecto es una **interfaz interactiva de gestión de extensiones de navegador** que muestra varias secciones, incluyendo un panel de resumen y tarjetas que representan las extensiones instaladas.  
Cuenta con un diseño limpio y responsive que se adapta a diferentes tamaños de pantalla, botones interactivos para simular acciones de instalación y gestión, **modo oscuro**, estados hover y focus, y almacenamiento persistente en la memoria del navegador.

---

## El Desafío
Los usuarios deberían poder:

- Explorar las tarjetas de extensiones e interactuar con los botones.  
- Ver la disposición de la UI según el ancho de pantalla de su dispositivo.  
- Experimentar estados hover y focus en elementos interactivos.  
- Cambiar entre **modo claro y oscuro**, con la preferencia guardada en la memoria del navegador.  
- Seleccionar extensiones instaladas y almacenar esa selección en la memoria del navegador.  
- Leer datos dinámicos de extensiones obtenidos de un **archivo JSON**.  
- Acceder a la información de manera clara gracias a un layout semántico y estructurado.

---

## Diseño
### Diseño de Escritorio  
![Diseño de Escritorio](./design/desktop-design-light.jpg)

### Escritorio Hover
![Diseño Hover](./design/desktop-design-light-hover.jpg)

### Escritorio Focus
![Diseño Focus](./design/desktop-design-light-focus.jpg)

### Escritorio Activo
![Diseño Activo](./design/desktop-design-light-active.jpg)

### Escritorio Inactivo
![Diseño Inactivo](./design/desktop-design-light-inactive.jpg)

### Diseño Móvil
<img src="./design/mobile-design-light.jpg" width="200px" alt="Diseño móvil en modo claro con hover">

### Escritorio Modo Oscuro
![Diseño Oscuro](./design/desktop-design-dark.jpg)

### Escritorio Oscuro Hover
![Diseño Oscuro Hover](./design/desktop-design-dark-hover.jpg)

### Escritorio Oscuro Focus
![Diseño Oscuro Focus](./design/desktop-design-dark-focus.jpg)

### Escritorio Oscuro Activo
![Diseño Oscuro Activo](./design/desktop-design-dark-active.jpg)

### Escritorio Oscuro Inactivo
![Diseño Oscuro Inactivo](./design/desktop-design-dark-inactive.jpg)

### Móvil Modo Oscuro
<img src="./design/mobile-design-dark.jpg" width="200px" alt="Diseño móvil en modo oscuro con hover">

---

## Enlaces
- **URL de la Solución:** [Repositorio en GitHub](https://github.com/mlopezl/my-version-of-browser-extensions-manager-ui-main-challenge)  
- **URL del Sitio en Vivo:** [Demo en Vivo](https://mlopezl.github.io/my-version-of-browser-extensions-manager-ui-main-challenge/)

---

## Mi Proceso
1. Estructuré la UI con secciones HTML semánticas.  
2. Usé **Flexbox y CSS Grid** para alinear y organizar todos los componentes.  
3. Apliqué estados hover y focus para una interfaz más pulida e interactiva.  
4. Implementé **modo oscuro** y guardé la preferencia del usuario usando `localStorage`.  
5. Guardé las selecciones de extensiones en la memoria del navegador para mantener el estado persistente.  
6. Cargué contenido dinámico desde un **archivo JSON** para poblar las tarjetas de extensiones.  
7. Implementé responsividad usando unidades relativas, escalado y ajustes en los breakpoints.  
8. Organicé los archivos para mantener HTML, CSS y assets limpios y modulares.

---

## Tecnologías Usadas
- HTML5  
- CSS3  
- Flexbox  
- CSS Grid  
- JavaScript  
- JSON  

---

## Lo Que Aprendí
- Cómo estructurar una UI multi-sección de forma limpia usando HTML y CSS.  
- Cómo combinar **Flexbox + Grid** para layouts flexibles y escalables.  
- Cómo añadir efectos hover y focus para mejorar la experiencia de usuario.  
- Cómo implementar y mantener **modo oscuro** usando `localStorage`.  
- Cómo guardar las selecciones de UI en la memoria del navegador para mantener el estado persistente.  
- Cómo importar y renderizar datos de extensiones dinámicamente desde un archivo JSON.  
- Cómo adaptar la interfaz a dispositivos móviles sin sacrificar legibilidad ni espaciado.
