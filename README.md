# snippets-vs-code

# 📌 Descripción del Proyecto

Este repositorio contiene una colección de snippets personalizados para Visual Studio Code, diseñados para agilizar el desarrollo con HTML y CSS. 

## ¿Qué son los snippets?
Los snippets en VS Code son fragmentos de código predefinidos que puedes insertar rápidamente mediante un atajo de teclado. Son especialmente útiles para evitar escribir estructuras repetitivas y mejorar la productividad.

## ¿Por qué los creé?
Mientras trabajaba en un proyecto, me di cuenta de que existen atajos en VS Code, como `rfce` en React, y me pregunté: 

> *¿Puedo crear mis propios snippets para escribir código HTML y CSS de manera más eficiente y con mejores prácticas?*

Después de investigar, descubrí que era posible. Así que diseñé estos snippets con un enfoque modular, creando pequeños componentes reutilizables con clases estandarizadas para facilitar la composición de estructuras más grandes. 

Estos snippets permiten generar elementos semánticos como formularios, imágenes, videos, tablas y tarjetas con un solo comando, y también incluyen sus respectivos estilos CSS con soporte para temas claro y oscuro.

💡 **Beneficios:**
- Ahorra tiempo escribiendo código repetitivo.
- Garantiza estructuras semánticas correctas.
- Permite personalizar fácilmente los estilos.
- No requiere instalar librerías externas.

¡Espero que estos snippets te ayuden a desarrollar más rápido y con mejor organización! 🚀

---

# ⚙️ Cómo instalarlos

Para agregar estos snippets a tu Visual Studio Code, sigue estos pasos:

1. **Abrir la configuración de snippets**
   - En VS Code, presiona `Ctrl + Shift + P` (`Cmd + Shift + P` en macOS).
   - Escribe `Preferences: Configure User Snippets` y selecciónalo.

2. **Seleccionar el tipo de snippets**
   - En la ventana emergente, elige `html.json` para snippets de HTML o `css.json` para snippets de CSS.

3. **Copiar los snippets personalizados**
   - Abre los archivos JSON de este repositorio.
   - Copia y pega el contenido en el archivo correspondiente (`html.json` o `css.json`).

4. **Guardar y probar**
   - Guarda los cambios (`Ctrl + S` o `Cmd + S` en macOS).
   - Ahora puedes escribir el atajo del snippet en cualquier archivo HTML o CSS y presionar `Tab` para insertarlo automáticamente.

✅ **Ejemplo:**
Si escribes `addCard` en un archivo HTML y presionas `Tab`, se generará automáticamente la estructura de una tarjeta semántica. Del mismo modo, al escribir `addCardCSSLight` en un archivo CSS, se insertarán los estilos correspondientes para el tema claro.

---

¡Así de fácil! Ahora puedes aprovechar estos snippets para escribir código más rápido y organizado. 🚀

---

# 💻 Ejemplos de uso




---

# 📜 Lista de snippets


---

# 💡 Cómo contribuir

¡Las contribuciones son bienvenidas! Si tienes ideas para nuevos snippets o mejoras en los existentes, sigue estos pasos para colaborar:

1. **Haz un fork del repositorio**
   - Presiona el botón de *Fork* en GitHub para crear tu propia copia del proyecto.

2. **Clona el repositorio**
   ```sh
   git clone https://github.com/tu-usuario/tu-repo.git
   ```

3. **Crea una nueva rama**
   ```sh
   git checkout -b nueva-funcionalidad
   ```

4. **Añade tus snippets**
   - Edita los archivos JSON y agrega tus nuevos snippets siguiendo el formato existente.

5. **Guarda y sube los cambios**
   ```sh
   git add .
   git commit -m "Añadir nuevo snippet para [descripción corta]"
   git push origin nueva-funcionalidad
   ```

6. **Crea un Pull Request**
   - Ve a la página de tu fork en GitHub y haz clic en *New Pull Request*.
   - Explica brevemente qué mejoras hiciste y envía la solicitud.

🚀 **Gracias por contribuir!** Cada nuevo snippet ayuda a hacer este repositorio más útil para la comunidad. 😊
