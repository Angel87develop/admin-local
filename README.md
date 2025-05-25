📁 admin-local/                   ← Carpeta raíz del proyecto web de administración del local.
│
├── index.html                   ← Página principal. Puede ser un dashboard o pantalla de login.
│
├── assets/                      ← Recursos estáticos reutilizables (CSS global, JS utilitario, imágenes).
│   ├── css/
│   │   └── main.css             ← Estilos globales de la página: colores, tipografía, layout base.
│   │
│   ├── js/
│   │   ├── main.js              ← Script inicial: eventos globales, carga de componentes comunes.
│   │   ├── ui.js                ← Funciones para controlar el UI: modales, notificaciones, etc.
│   │   └── api.js               ← Funciones para simular llamadas a backend o manipular datos locales.
│   │
│   └── img/
│       └── logo.png             ← Imagen del logo del local o negocio.
│
├── features/                    ← Cada subcarpeta representa una funcionalidad (Feature) del dominio.
│   ├── products/                ← Módulo de gestión de productos.
│   │   ├── products.html        ← Interfaz para ver/agregar/modificar productos.
│   │   ├── products.css         ← Estilos específicos del módulo de productos.
│   │   └── products.js          ← Lógica JavaScript: CRUD de productos, validaciones, filtros.
│   │
│   ├── sales/                   ← Módulo de gestión de ventas.
│   │   ├── sales.html           ← Pantalla de ventas realizadas, registrar nueva venta.
│   │   ├── sales.css            ← Estilos propios para ventas (grillas, botones, totales).
│   │   └── sales.js             ← Lógica para registrar, listar, y calcular ventas.
│   │
│   ├── inventory/               ← Módulo de control de inventario.
│   │   ├── inventory.html       ← Visualización y control de stock disponible.
│   │   ├── inventory.css        ← Estilos específicos para tablas de inventario y alertas.
│   │   └── inventory.js         ← Funciones para actualizar stock, detectar bajo inventario.
│   │
│   └── users/                   ← Módulo para gestión de usuarios y permisos.
│       ├── users.html           ← Listado y formulario para agregar/editar usuarios.
│       ├── users.css            ← Estilos exclusivos para el módulo de usuarios.
│       └── users.js             ← Lógica para validar roles, contraseñas, permisos.
│
├── shared/                      ← Componentes y utilidades reutilizables en toda la aplicación.
│   ├── header.html              ← Encabezado común con logo, nombre del local, menú usuario.
│   ├── footer.html              ← Pie de página estándar (fecha, derechos, etc.).
│   ├── sidebar.html             ← Menú lateral de navegación entre módulos (ventas, inventario, etc.).
│   └── utils.js                 ← Funciones comunes: formateo de fecha, validación de campos, helpers.
│
└── README.md                    ← Documentación del proyecto: propósito, estructura, instrucciones de uso.
