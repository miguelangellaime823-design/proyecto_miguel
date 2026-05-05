# 🎬 [Pelis de miguel]
<img width="931" height="1011" alt="image" src="https://github.com/user-attachments/assets/15899452-8ffe-4bd3-9eab-67e1e88b0489" />

<!-- Imagen principal: He puesto una de cine de ejemplo, puedes cambiar la URL por tu logo si tienes uno -->
<img src="https://images.unsplash.com/photo-1485846234645-a62644f84728?auto=format&fit=crop&q=80&w=300" alt="Logo de la web de pelis" width="300">

Objetivo
El objetivo de este proyecto es ofrecer una plataforma visual e intuitiva para que los amantes  puedan explorar estrenos, consultar fichas técnicas y organizar sus películas favoritas. Este repositorio contiene el código fuente del portal web desarrollado íntegramente por mí.

### Funcionalidades
*   **Buscador avanzado**: Filtra películas por género, año o director.
*   **Fichas detalladas**: Información completa, sinopsis y puntuación de la crítica.
*   **Reproductor integrado**: Capacidad de visualizar tráilers en alta definición.

### Alcance y Usuarios Potenciales
El alcance abarca desde el diseño de la interfaz (UI) hasta la gestión de la base de datos de películas. Los **usuarios potenciales** son críticos de cine y cualquier persona que busque recomendaciones de entretenimiento.

---

## 🗺️ Menú de Navegación Principal
Nuestra web se organiza de la siguiente manera:
*    Inicio
*    Cartelera
*    Próximos Estrenos
*    Suscribirse / Contacto

---

## 👥 Equipo de Desarrollo
| Nombre | Apellidos | Rol |
| :--- | :--- | :--- |
| [Tu Nombre] | [Tus Apellidos] | Full Stack Developer |

---

## 💻 Estructura HTML de una Película
Aquí tienes el fragmento de código que utilizo para mostrar cada película en la cuadrícula:

```html
<article class="movie-card">
  <img src="poster.jpg" alt="Título de la peli">
  <h3>Título de la Película</h3>
  <button onclick="verTrailer()">Ver Tráiler</button>
</article>
