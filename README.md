# SmartBudget – Landing Page  
Proyecto Frontend Trainee – Módulo 3  
Autor: **Cristian Hernández**

## 1. Descripción del Proyecto  
SmartBudget es una landing page creada como parte del Módulo 3 del curso Frontend Trainee.  
El objetivo del proyecto es implementar una interfaz web responsiva aplicando buenas prácticas de HTML5, CSS3, SASS, metodología BEM y Bootstrap 4.

La página incluye un header responsivo, sección hero, características del sistema, explicación de funcionamiento, planes disponibles y un formulario de contacto.

---

## 2. Tecnologías Utilizadas  
- **HTML5**  
- **CSS3**  
- **SASS** (estructura 7-1)  
- **Metodología BEM** para organización clara de clases  
- **Bootstrap 4** para componentes reutilizables  
- **Flexbox** y **media queries**  
- **JavaScript mínimo** (solo lo incluido por Bootstrap)

---

## 3. Estructura del Proyecto  
El proyecto sigue la arquitectura recomendada para SASS (7-1):

sass/
│
├── abstracts/ → variables, mixins
├── base/ → resets, tipografías, estilos base
├── components/ → botones, hero, features, planes, formularios
├── layout/ → header, footer, grid
├── pages/ → estilos específicos por página (home.scss)
├── themes/ → temas opcionales (default)
├── vendors/ → estilos externos
│
└── main.scss → archivo principal que importa todo


El compilado final se genera en:



---

## 4. Metodología CSS (BEM)  
Se utilizó la metodología **BEM (Block, Element, Modifier)** para mantener los estilos organizados y evitar conflictos.

Ejemplos usados en el proyecto:

- **Bloque:** `hero`, `feature-card`, `plan-card`  
- **Elemento:** `hero__title`, `feature-card__icon`, `plan-card__price`  
- **Modificador:** `plan-card--highlight`  

Esto facilita la lectura, escalabilidad y mantenimiento del CSS.

---

## 5. Compilación SASS  
Para compilar SASS se utilizó **Live Sass Compiler** desde Visual Studio Code.

La configuración utilizada guarda automáticamente el resultado en la carpeta `/css`.

---

## 6. Diseño Responsivo  
La landing page es completamente responsiva:

- Navbar diseñado con **BEM + Bootstrap**, adaptado para móviles  
- Secciones con Flexbox  
- Ajustes específicos en breakpoints móviles  
- Botones y formularios adaptados a pantallas pequeñas

---

## 7. Capturas 
listado de capturas realizadas de la web vista en: "ventana de herramientas de desarrollador"

Capturas vista desktop:
docs\capturas\screenshot-desktop(1).png
docs\capturas\screenshot-desktop(2).png
docs\capturas\screenshot-desktop(3).png
docs\capturas\screenshot-desktop(4).png
Capturas vista móvil:
docs\capturas\screenshot-mobile(1).png
docs\capturas\screenshot-mobile(2).png
docs\capturas\screenshot-mobile(3).png
docs\capturas\screenshot-mobile(4).png
docs\capturas\screenshot-mobile(5).png

