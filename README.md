# VetCare - Clínica Veterinaria Huellitas

**Sitio desplegado en GitHub Pages:** https://emilio-camino.github.io/vetcare-grupo2/

## Integrantes del Grupo 2

- Mateo Aguirre
- Adrian Camino
- Gissel Dávila
- Karen Mosquera

# Descripción
VetCare es un sistema web pensado para organizar la atención diaria de la Clínica Veterinaria Huellitas. Con esta aplicación se llevan en orden las citas médicas, los datos de los propietarios, el registro de sus mascotas, los historiales clínicos, el registro de los veterinarios y el catálogo de servicios.

Para construir este proyecto se usó HTML y CSS.

## Estructura del proyecto

- `index.html`: ventana de inicio de sesión.
- `pages/`: carpeta con todas las pantallas internas del sistema.
- `css/`: carpeta con las hojas de estilo `style.css` y `login.css` que dan el diseño a toda la interfaz.
- `img/`: carpeta con las imágenes utilizadas en las pantallas.
- `docs/`: carpeta reservada para los documentos del proyecto.
- `README.md`: archivo con la descripción básica del proyecto.

## Pantallas y capacidades para cada rol

### Ventana de inicio de sesión

Es una pantalla común para todo el personal.

- `index.html`: permite ingresar el correo electrónico y la contraseña para entrar al sistema eligiendo si se accede como recepcionista, veterinario o administrador.

### Recepcionista

Pantallas que le pertenecen:

- `listado-citas.html`
- `agendar-cita.html`
- `reprogramar-cita.html`
- `cancelar-cita`
- `listado-propietarios.html`
- `registrar-propietario.html`
- `editar-propietario.html`
- `eliminar-propietario`
- `listado-mascotas.html`
- `registrar-mascota.html`
- `editar-mascota.html`
- `eliminar-mascota`

Las pantallas que no llevan extensión `.html` son ventanas emergentes de confirmación integradas dentro de sus respectivos listados.

Capacidades: consultar y buscar citas registradas, agendar nuevas citas médicas, reprogramar citas existentes y cancelarlas indicando un motivo. También puede consultar, buscar, registrar, editar y dar de baja tanto a los propietarios como a las mascotas de la clínica, además de cerrar sesión desde el encabezado superior.

### Veterinario

Pantallas que le pertenecen:

- `agenda-medica.html`
- `registrar-atencion-medica.html`
- `historial-clinico.html`

Capacidades: consultar la agenda médica por fecha para ver sus citas programadas, revisar el historial clínico con las atenciones médicas anteriores de una mascota y registrar la atención médica de una mascota en particular anotando su peso actual, diagnóstico y tratamiento, además de cerrar sesión desde el encabezado superior.

### Administrador

Pantallas que le pertenecen:

- `gestion-veterinario.html`
- `registrar-veterinario.html`
- `editar-veterinario.html`
- `eliminar-veterinario`
- `catalogo-servicios.html`
- `registrar-servicio.html`
- `editar-servicio.html`
- `eliminar-servicio`

Las pantallas que no llevan extensión `.html` son ventanas emergentes de confirmación integradas dentro de sus respectivos listados.

Capacidades: consultar, buscar, registrar, editar y dar de baja a los veterinarios de la clínica, así como consultar, buscar, registrar, editar y dar de baja los servicios del catálogo junto con sus precios, además de cerrar sesión desde el encabezado superior.

## Reparto del trabajo

### Entregables en PDF (3.1 – 3.5)

Todos los documentos fueron elaborados y revisados inicialmente en conjunto por el equipo. La subida del PDF al repositorio estuvo a cargo de Adrian Camino.

### Pantallas implementadas en HTML5 y CSS (3.6)

- **Adrian Camino** — *Login y Propietarios:* `index.html`, `listado-propietarios.html`, `registrar-propietario.html`, `editar-propietario.html`
- **Karen Mosquera** — *Mascotas y Atención:* `listado-mascotas.html`, `registrar-mascota.html`, `editar-mascota.html`, `registrar-atencion-medica.html`, `historial-clinico.html`
- **Gissel Dávila** — *Citas y Agenda:* `listado-citas.html` (con sus popovers), `agendar-cita.html`, `reprogramar-cita.html`, `agenda-medica.html`
- **Mateo Aguirre** — *Administrador:* `gestion-veterinario.html`, `registrar-veterinario.html`, `editar-veterinario.html`, `catalogo-servicios.html`, `registrar-servicio.html`, `editar-servicio.html`
