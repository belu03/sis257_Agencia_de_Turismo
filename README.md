# sis257_Agencia_de_Turismo
Agencia de Turismo - Plataforma Web

Descripción del Negocio

Somos una agencia de turismo que ofrece una plataforma web donde los usuarios pueden explorar, comparar y reservar viajes, paseos y paquetes turísticos a diferentes destinos de Bolivia. El sistema permitirá una gestión eficiente de reservas, brindando una experiencia accesible, segura y fácil de usar.

Objetivo del Sistema

Desarrollar una página web que permita gestionar la oferta de paquetes turísticos y facilitar la reserva de viajes dentro de Bolivia.

Funcionalidades Principales

- Registro e inicio de sesión de usuarios
- Visualización de destinos turísticos
- Búsqueda y filtrado de paquetes turísticos
- Reserva de paquetes
- Historial de reservas
- Sistema de reseñas
- Panel de administración

Entidades del Sistema (8 tablas)

1. Usuario

- id_usuario
- nombre
- apellido
- correo
- contraseña
- rol

2. Destino

- id_destino
- nombre
- descripcion
- ubicacion
- imagen

3. PaqueteTuristico

- id_paquete
- nombre
- descripcion
- precio
- duracion
- capacidad_maxima
- id_destino

4. Reserva

- id_reserva
- fecha
- estado
- cantidad_personas
- id_usuario
- id_paquete

5. Pago

- id_pago
- monto
- fecha
- metodo_pago
- id_reserva

6. GuiaTuristico

- id_guia
- nombre
- telefono
- correo
- idioma

7. Transporte

- id_transporte
- tipo
- capacidad
- empresa
- id_paquete

8. Reseña

- id_reseña
- comentario
- calificacion
- fecha
- id_usuario
- id_paquete

Alcance del Proyecto

El sistema permitirá gestionar reservas de paquetes turísticos dentro de Bolivia, dirigido a usuarios que deseen planificar viajes de manera rápida y sencilla.
