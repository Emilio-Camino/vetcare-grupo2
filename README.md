# VetCare - Clínica Veterinaria Huellitas

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
- `listado-propietarios.html`
- `registrar-propietario.html`
- `editar-propietario.html`
- `listado-mascotas.html`
- `registrar-mascota.html`
- `editar-mascota.html`

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
- `catalogo-servicios.html`
- `registrar-servicio.html`
- `editar-servicio.html`

Capacidades: consultar, buscar, registrar, editar y dar de baja a los veterinarios de la clínica, así como consultar, buscar, registrar, editar y dar de baja los servicios del catálogo junto con sus precios, además de cerrar sesión desde el encabezado superior.

## Integrantes del Grupo 2

- Mateo Aguirre
- Adrian Camino
- Gissel Dávila
- Karen Mosquera
