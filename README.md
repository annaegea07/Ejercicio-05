# Ejercicio-05
Objetivo

Crea una página web que se parezca lo máximo posible a la imagen de referencia, partiendo del código base proporcionado.
👉 Puedes añadir clases e IDs cuando lo necesites.

Materiales
Archivos base en ./starter/
Hoja de estilos en ./starter/css/
Imágenes en ./starter/img/

Requisitos
Solo implementa la navegación horizontal (nav) mostrada en la imagen.
Utiliza Flexbox para posicionar y alinear los elementos siempre que sea posible
(en algún caso podrás complementar con margin).
Centra el contenido de los span dentro de cada enlace a, vertical y horizontalmente.
En el elemento li del logo, aplica margin-right para separarlo del resto del menú:
no uses un número, usa una palabra (p. ej., auto).
✅ Mantén una estructura HTML semántica y ordena el CSS de forma clara (reset → variables → layout → componentes).

Pistas técnicas (opcionales)
/* Contenedor del menú */
nav ul {
  display: flex;
  align-items: center;   /* Alineación vertical */
  gap: 1rem;             /* Separación uniforme (si procede) */
  list-style: none;
  padding: 0;
  margin: 0;
}

/* Logo separado del resto */
nav li.logo {
  margin-right: auto;    /* Usa palabra, no número */
}

/* Centrado del texto dentro de los enlaces */
nav a span {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}

ADVANCED LEVEL
Añade el código necesario para que el nav vertical también se vea igual que en la imagen de referencia.
Deberás ajustar su estructura y disposición usando Flexbox.

Tips de recomendaciones:
Utiliza border: 1px solid var(--fourth-color); par ten un poco de control de lo que ocupan los bloques y tmabien utiliza /* Para organizarte */ en el css

