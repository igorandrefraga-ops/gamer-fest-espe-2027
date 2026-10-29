# Gamer Fest ESPE 2027

Landing page responsiva del evento gamer universitario Gamer Fest ESPE 2027. Es un caso de estudio académico para la asignatura de Programación Web (ERS-GF-2027). El evento, las fechas, los premios y los auspiciantes son datos demostrativos.

## Tecnologías

- HTML5
- Bootstrap 5.3 (archivos locales)
- JavaScript del lado del cliente, sin backend

## Cómo ejecutarlo

1. Clona el repositorio:
   ```
   git clone https://github.com/igorandrefraga-ops/gamer-fest-espe-2027.git
   ```
2. Abre `index.html` en el navegador (Chrome o Firefox actualizados).
3. Bootstrap está incluido en el proyecto. Solo el mapa de Google Maps necesita conexión a Internet.

## Estructura del proyecto

```
gamer-fest-espe-2027/
├── index.html
├── css/            (bootstrap.min.css)
├── js/             (bootstrap.bundle.min.js)
├── img/            (logo, hero, categorías y auspiciantes)
├── diseno-movil.png
├── diseno-escritorio.png
└── README.md
```

## Secciones de la página

Encabezado con navbar colapsable, hero con llamada a la acción, categorías de competencia, premios, auspiciantes, mapa de ubicación, formulario de inscripción y pie de página con redes sociales.

## Diseño responsivo

Se diseñó primero para móvil (Mobile First) y se adapta con los breakpoints de Bootstrap. Las vistas de referencia son 375 px y 1440 px, y el cambio de distribución ocurre desde `lg` (992 px). Los wireframes están en `diseno-movil.png` y `diseno-escritorio.png`.

## Limitaciones

- Las cuentas de Instagram, Facebook y TikTok son enlaces demostrativos.
- Los logos de auspiciantes son ficticios.
- Las pruebas se hicieron solo con datos ficticios.

## Autor

- Nombre: Igor [Fraga]
- Asignatura: Programación Web, ESPE
- NRC / Paralelo: [37792]
- Docente: [Edgar Montaluisa]