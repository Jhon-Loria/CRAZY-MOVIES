# Crazy-Movies
Pagina de Películas
La página web CRAZY MOVIES es una tienda virtual interactiva para la venta de películas, diseñada con un estilo moderno, visual llamativo y funciones avanzadas. Está pensada para que los usuarios puedan explorar, ver trailers, comprar películas y revisar su historial de compras. También cuenta con un panel de administración para agregar o gestionar títulos fácilmente.

Pantalla de bienvenida
Cuando se carga la página, se muestra una pantalla de presentación con el logo y una barra de carga animada:


<div id="intro-screen" class="intro-screen">
  <h1 class="intro-logo">CRAZY MOVIES</h1>
  <div class="loading-bar-container">
    <div id="loading-bar" class="loading-bar"></div>
  </div>
</div>

Encabezado (Header)
Incluye:

El logo animado.

Una barra de búsqueda interactiva para encontrar películas.

Botones para ingresar como usuario, ver el carrito, historial o entrar al panel admin.

<header>
  <div class="logo-search-container">
    <h1 class="logo">CRAZY MOVIES</h1>
    <div class="search-container">
      <input type="text" id="search-input" placeholder="Buscar películas...">
      <span class="search-icon">🔍</span>
    </div>
  </div>
  <div class="nav-buttons">
    <button class="nav-button">🛒 Carrito</button>
    <button class="nav-button">👤 Iniciar Sesión</button>
  </div>
</header>

Carrusel (Slider de películas)
Un carrusel de ancho completo muestra las películas más destacadas con imágenes, título, descripción y botones de acción como “▶ Reproducir” o “ℹ Más información”.


<div class="carousel">
  <div class="carousel-slide active">
    <img src="img/dune.jpg" alt="Dune">
    <div class="carousel-content">
      <h3>Dune</h3>
      <p>Descripción de la película...</p>
    </div>
  </div>
</div>

Pestañas por categoría
Permiten filtrar películas por género: Estrenos, Acción, Comedia, Ciencia Ficción, Terror, etc.


<div class="tabs">
  <button data-category="action">Películas Acción</button>
  <button data-category="comedy">Películas Comedia</button>
</div>

Tarjetas de Películas
Cada película se muestra como una “card” con imagen, título, precio, calificación, botones para ver el trailer o añadir al carrito.


<div class="movie-card">
  <div class="movie-image"><img src="img/bat.jpg" alt="Batman"></div>
  <div class="movie-info">
    <div class="movie-title">Batman</div>
    <div class="price">$17.99</div>
  </div>
</div>

Carrito de compras
Al hacer clic en el ícono de carrito, se abre una barra lateral con los productos agregados. Puedes ver el total, eliminar productos y completar la compra.


<div id="cart-sidebar">
  <div class="cart-header">Tu Carrito</div>
  <div class="cart-content">Películas añadidas...</div>
</div>

Historial de compras
Permite revisar compras anteriores filtrando por nombre de usuario.

Panel de administración
Sólo accesible para el administrador. Permite:

Agregar nuevas películas.

Gestionar la lista de películas.

Cargar imágenes, trailers, descripción, precio, etc.


<div id="admin-panel">
  <form>
    <input type="text" placeholder="Título">
    <textarea placeholder="Descripción"></textarea>
    <input type="file" accept="image/*">
    <button type="submit">Añadir Película</button>
  </form>
</div>

Diseño (CSS)
Toda la página está personalizada con un diseño moderno:

Paleta de colores en morado y azul.

Animaciones suaves (glow, hover, transiciones).

Totalmente responsiva: funciona bien en móviles y escritorio.

Este proyecto está muy completo y visualmente trabajado. Es ideal como prototipo funcional para una tienda de películas. Además, puedes ampliarlo fácilmente con base de datos o backend en el futuro (por ejemplo con Firebase, Node.js o PHP).
