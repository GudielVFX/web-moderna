
<img src="https://www.webfx.com/wp-content/uploads/2023/08/38_modern_web_design-1024x462.png" alt="image of a clean desktop">

# WEB MODERNA


## Autor
- **Nombre Completo:** Jhonatan Prado
- **Nombre del Curso:** CODE 201

## Sobre el Proyecto
La web moderna es como una versión mucho más dinámica y poderosa de la web que conocíamos hace unos años. Piensa en ella como una ciudad digital en constante evolución, llena de nuevas posibilidades y experiencias.

**Aquí hay algunas de las características clave de la web moderna:**

- **Interactividad:** 
La web ya no es solo un lugar para leer información. Ahora podemos interactuar con ella de formas increíbles. Podemos jugar juegos, comprar productos, ver videos en streaming, participar en chats en tiempo real y mucho más.

- **Visualización:** La web moderna se basa en imágenes, videos y animaciones para crear experiencias más atractivas y envolventes. Los sitios web son más visuales y atractivos que nunca.

- **Movilidad:** La web moderna está diseñada para ser accesible desde cualquier dispositivo, ya sea un teléfono inteligente, una tableta o una computadora. Podemos navegar por la web sin importar dónde estemos.

- **Conectividad:** La web moderna nos permite conectarnos con personas de todo el mundo. Podemos compartir información, ideas y experiencias con facilidad.

- **Inteligencia artificial:** La inteligencia artificial (IA) está transformando la web moderna. La IA se utiliza para personalizar contenido, mejorar la búsqueda, traducir idiomas y mucho más.

**En resumen, la web moderna es un espacio digital dinámico, interactivo, visual, móvil y conectado que nos permite explorar, crear y conectar con el mundo de formas nunca antes imaginadas.**

## .eslintrc

### 1. La sección: "env":
```
"env": {
  "browser": true,
  "es2021": true
}
```

- **La sección "env":** Define el entorno donde se ejecutará tu código
- **browser: true** indica que el código se ejecutará en navegadores web
- **es2021: true** permite usar características de JavaScript del año 2021

### 2. La sección: "extends"
```
"extends": ["eslint:recommended"]
```

- Hereda las reglas recomendadas por defecto de ESLint
- Son un conjunto de reglas básicas consideradas buenas prácticas

### 3. La sección: "parserOptions":

```
"parserOptions": {
  "ecmaVersion": "latest",
  "sourceType": "module"
}
```
- `ecmaVersion: "latest"` permite usar la última versión de JavaScript
- `sourceType: "module"` indica que usas módulos ES6 (import/export)

### 4. La sección: "rules"
```
"rules": {
  "indent": ["error", 2],
  "linebreak-style": ["error", "unix"],
  "quotes": ["error", "single"],
  "semi": ["error", "always"],
  "no-unused-vars": "warn",
  "no-console": "warn"
}
```

### Aquí se definen reglas específicas:

- `"indent": ["error", 2]:` Obliga a usar 2 espacios para la indentación
- `"linebreak-style": ["error", "unix"]`: Fuerza el uso de saltos de línea estilo Unix (\n)
- `"quotes": ["error", "single"]`: Obliga a usar comillas simples
- `"semi": ["error", "always"]`: Requiere punto y coma al final de cada declaración
- `"no-unused-vars": "warn"`: Advierte sobre variables declaradas pero no usadas
- `"no-console": "warn"`:Advierte cuando se usa console.log()

### Los niveles de severidad en las reglas son:

- `"error"`: Marca un error y hace fallar la verificación
- `"warn"`: Solo muestra una advertencia sin hacer fallar la verificación

## ESLint in a nutshell

ESLint, una herramienta que ayuda a mantener la calidad y consistencia del código JavaScript.

En resumen, este código:

- **Establece reglas de estilo:** Define cómo debe escribirse el código, incluyendo la sangría, el uso de comillas y el punto y coma.
- **Detecta errores comunes:** Busca errores de sintaxis, variables no utilizadas, etc.
Mejora la legibilidad: Ayuda a que el código sea más fácil de leer y entender.
- **Asegura la compatibilidad:** Verifica que el código sea compatible con diferentes navegadores y versiones de JavaScript.

En esencia, este código ayuda a que el código JavaScript sea más limpio, consistente y libre de errores.

## Despliegue

💻 **[Mi repositorio](https://github.com/GudielVFX/web-moderna)** 💻

