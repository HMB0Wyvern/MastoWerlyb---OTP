# 🎮 Werlyb - Tracker "10 Partidas OTP"

¡Bienvenido al repositorio oficial del rastreador de la serie **10 Partidas OTP** de Werlyb!

Esta página web estática sirve como un panel visual interactivo donde la comunidad puede seguir el progreso, las estadísticas (victorias/derrotas), los coaches invitados y acceder rápidamente a los vídeos de esta épica serie.

🔗 **[VER LA WEB EN DIRECTO AQUÍ](https://hmb0wyvern.github.io/MastoWerlyb---OTP/)**

---

## ✨ Características

* **Diseño Hextech:** Interfaz oscura, moderna y fluida basada en el universo de League of Legends.
* **Datos Dinámicos:** Toda la información se carga en tiempo real desde un sencillo archivo JSON, sin necesidad de tocar el código base.
* **Filtros Inteligentes:** Encuentra rápidamente a los campeones por su estado (Todos, Completados, En Progreso, Pendientes).
* **Estadísticas Globales:** Cálculo automático de Winrate general y conteo de retos completados.
* **100% Responsive:** Se ve perfecto tanto en PC como en dispositivos móviles.

---

## 🛠️ Tecnologías Utilizadas (JAMstack)

* **HTML5 & CSS3**
* **JavaScript (Vanilla)** para la lógica de filtros y renderizado dinámico.
* **Tailwind CSS** para un estilizado rápido y utilitario (vía CDN).
* **Riot Games Data Dragon API** para las imágenes en alta calidad de los más de 160 campeones.

---

## 📝 ¿Cómo actualizar los datos? (Guía para Mods/Werlyb)

La principal ventaja de esta web es que no necesitas saber programar para actualizarla. Toda la "base de datos" vive en el archivo `data.json`.

Para añadir o modificar el progreso de un campeón, sigue estos pasos:

1. Ve al archivo `data.json` en este repositorio.
2. Haz clic en el icono del lápiz (**Editar**) arriba a la derecha.
3. Usa la combinación `Ctrl + F` (o `Cmd + F` en Mac) para buscar el nombre del campeón (ej. *"Gwen"*).
4. Modifica sus valores. Ejemplo de un campeón completado:

---

## 📋 Estados permitidos:

Asegúrate de escribir el estado exactamente igual a las siguientes opciones para que la web aplique los colores correctos:

1. "Pendiente" (Aparecerá en gris)
2. "En progreso" (Aparecerá en azul con un borde brillante)
3. "Completado" (Aparecerá a todo color con estadísticas completas)

Ve al final de la página y pulsa el botón verde "Commit changes".

¡La web se actualizará automáticamente en un par de minutos!

---

## 👨‍💻 Contribuir

Si eres desarrollador y quieres proponer una mejora (nuevas animaciones, refactorización de código, etc.), siéntete libre de hacer un Fork del repositorio y enviar un Pull Request.

## ⚠️ Proyecto creado por y para la comunidad. No afiliado directamente con Riot Games.
