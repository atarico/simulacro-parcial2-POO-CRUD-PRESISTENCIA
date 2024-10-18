<h1 align="center">POO-CRUD-PERSISTENCIA</h1>

## Teoría

### Analiza cada caso y responde.

<h3>Problema 1:</h3>

**_Gestión de Inscripciones para un Gimnasio_**

_Un gimnasio necesita gestionar las inscripciones de sus miembros. Cada miembro tiene un nombre, una fecha de inscripción y un plan de suscripción (mensual o anual). El gimnasio también tiene una lista de clases disponibles, pero los miembros no se inscriben a clases directamente._

**Pregunta:**

¿Es necesario utilizar persistencia para las clases disponibles en el gimnasio?

**Pregunta:**

¿Se debe usar un Diccionario para los miembros del gimnasio?

<h3>Problema 2:</h3>

**_Sistema de Gestión de Mascotas en una Veterinaria_**

_Una veterinaria necesita gestionar sus mascotas. Cada mascota tiene un nombre, una especie (perro, gato, etc.) y su historial médico. Los dueños de las mascotas no tienen cuentas individuales ni se les asigna un número de cliente._

**Pregunta:**

¿Es necesario aplicar encapsulamiento en la clase Mascota?

**Pregunta:**

¿Es necesario implementar persistencia para los dueños de las mascotas?

<h3>Problema 3:</h3>

**_Sistema de Reservas de Canchas Deportivas_**

_Un club deportivo permite a los socios reservar canchas de tenis o fútbol por un número limitado de horas. Cada reserva debe incluir el nombre del socio, el tipo de cancha y la duración de la reserva. No hay tarifas ni precios asociados a la reserva._

**Pregunta:**

¿Se requiere el uso de un Enum para los tipos de cancha?

**Pregunta:**

¿Es necesario usar una colección de tipo Pila para gestionar las reservas?

<h3>Problema 4:</h3>

**_Biblioteca Pública con Préstamos de Libros_**

_Una biblioteca pública gestiona el préstamo de libros a sus usuarios. Cada libro tiene un título, autor, número de páginas y fecha de publicación. Los usuarios pueden prestar varios libros a la vez, y deben devolverlos en un plazo de dos semanas._

**Pregunta:**

¿Deberías utilizar un Array para gestionar los libros prestados por cada usuario?

**Pregunta:**

¿Se requiere persistencia para almacenar la información de los libros disponibles en la biblioteca?

### Bonus:

¿Cuál es la diferencia entre clase Abstracta y una Interfaz?

---

## Práctica

_Juan está emocionado con la idea de modernizar su tienda de videojuegos. Hace un tiempo, el mercado de videojuegos se ha expandido mucho y los clientes buscan siempre las mejores ofertas. A veces Juan se confunde con los precios o pierde el control del inventario, lo que le <h3>usado problemas con algunos clientes que buscan juegos que ya no tiene o con precios mal actualizados. Además, su cuaderno está tan </h3>lleno de tachones que no sabe cuántas unidades tiene de cada juego._

_Por esta razón, le pide a un programador amigo que lo ayude a crear un sistema sencillo pero efectivo para automatizar el proceso de gestión de su tienda. "Necesito que este sistema me permita agregar, eliminar, actualizar y mostrar los videojuegos de mi catálogo de manera fácil y rápida", explica Juan._

**Al implementar este sistema, Juan podrá dejar atrás el cuaderno y usar su computadora para gestionar los juegos, asegurándose de que siempre tendrá la información correcta a mano. Además, la persistencia en un archivo le permitirá que, aunque se apague la computadora o haya un fallo, su catálogo esté siempre guardado y pueda recuperarse al instante.**

#### Funcionalidades Principales:

1. `Agregar Videojuego:` Juan quiere poder añadir un nuevo videojuego al catálogo con el nombre, la plataforma (que solo puede ser PlayStation, Xbox o PC), el precio y la cantidad de unidades en stock.
2. `Mostrar el Catálogo:` Juan debe poder ver toda la lista de juegos disponibles con sus detalles.
3. `Actualizar Videojuego:` Si el precio cambia o recibe más stock, debe poder modificar la información del juego existente.
4. `Eliminar Videojuego:` Si decide dejar de vender un juego, debe poder quitarlo del catálogo.
5. `Guardado en Archivo:` Todo debe quedar registrado en un archivo para que, si el sistema se reinicia, no pierda la información.

**_Este sistema debe ser sencillo de usar para alguien como Juan, que no tiene experiencia con computadoras avanzadas, pero efectivo para llevar el control de su inventario sin errores._**
