
---
layout: default
title: Ejemplo Completo de Renderizado
---

# Ejemplo Completo de Renderizado

Este archivo muestra todas las opciones de renderizado disponibles en GitHub Pages con la configuración actual, incluyendo MathJax para fórmulas matemáticas.

---

## 1. Encabezados

Los encabezados se escriben usando `#`:

# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

---

## 2. Texto Formateado

- **Negrita**: Usa `**texto**` o `__texto__`. Ejemplo: **Este texto está en negrita**.
- *Itálica*: Usa `*texto*` o `_texto_`. Ejemplo: *Este texto está en itálica*.
- ***Negrita e Itálica***: Usa `***texto***`. Ejemplo: ***Este texto está en negrita e itálica***.
- ~~Tachado~~: Usa `~~texto~~`. Ejemplo: ~~Este texto está tachado~~.

---

## 3. Listas

### Listas No Ordenadas
Usa `-`, `*`, o `+` para crear listas no ordenadas:
- Elemento 1
- Elemento 2
  - Subelemento 2.1
  - Subelemento 2.2
- Elemento 3

### Listas Ordenadas
Usa números seguidos de `.` para crear listas ordenadas:
1. Primer elemento
2. Segundo elemento
   1. Subelemento 2.1
   2. Subelemento 2.2
3. Tercer elemento

---

## 4. Enlaces e Imágenes

### Enlaces
Para crear enlaces, usa `[texto](url)`:
- [Enlace a Google](https://www.google.com)
- [Enlace interno a prueba001](prueba/prueba001.html)

### Imágenes
Para insertar imágenes, usa `![alt-text](url)`:
![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

---

## 5. Bloques de Código

### Código en Línea
Para insertar código en línea, usa `` `código` ``. Ejemplo: `console.log("Hola, mundo!");`

### Bloques de Código
Para bloques de código, usa tres backticks (\`\`\`) y especifica el lenguaje para resaltar la sintaxis:

```python
def suma(a, b):
    return a + b

print(suma(2, 3))  # Salida: 5
```

```javascript
function saludar() {
    console.log("¡Hola, mundo!");
}
saludar();
```

---

## 6. Citas

Para citas, usa `>`:
> Esto es una cita. Puedes usarlo para destacar información importante o para citar a alguien.

---

## 7. Tablas

Las tablas se crean usando `|` y `-`:

| Nombre      | Edad | Ciudad       |
|-------------|------|--------------|
| Juan        | 25   | Buenos Aires |
| María       | 30   | Madrid       |
| Carlos      | 22   | Santiago     |

---

## 8. Fórmulas Matemáticas con MathJax

### Fórmulas en Línea
Usa `$...$` o `\( ... \)` para fórmulas en línea:
- La derivada de $ f(x) = x^2 $ es $ f'(x) = 2x $.
- Una fracción simple: \( \frac{a}{b} \).

### Fórmulas en Bloque
Usa `$$ ... $$` para fórmulas centradas:
La integral de \( f(x) \) se define como:
$$
\int_a^b f(x) \, dx
$$

Una matriz \( 2 \times 2 \):
$$
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
$$

---

## 9. Líneas Horizontales

Para líneas horizontales, usa tres guiones (`---`), asteriscos (`***`), o guiones bajos (`___`):

---

Esto es una línea horizontal.

---

## 10. Notas Adicionales

- Si necesitas escapar caracteres especiales (como `_` o `*`), usa una barra invertida (`\`). Ejemplo: Usar \_ en lugar de _ dentro de ecuaciones.
- Asegúrate de que tus archivos Markdown tengan un encabezado YAML válido, como el que está al principio de este archivo.

---

¡Espero que este ejemplo te sea útil para explorar todas las opciones de renderizado en tu sitio de GitHub Pages!
```

---

### **Cómo Funciona Cada Sección**
1. **Encabezados:** Muestra cómo usar diferentes niveles de títulos.
2. **Texto Formateado:** Demuestra cómo aplicar negrita, itálica, tachado, etc.
3. **Listas:** Incluye ejemplos de listas ordenadas y no ordenadas.
4. **Enlaces e Imágenes:** Muestra cómo insertar enlaces e imágenes.
5. **Bloques de Código:** Ejemplos de código en línea y bloques de código con resaltado de sintaxis.
6. **Citas:** Cómo usar bloques de citas.
7. **Tablas:** Ejemplo de una tabla simple.
8. **Fórmulas Matemáticas:** Incluye ejemplos de fórmulas en línea y en bloque usando MathJax.
9. **Líneas Horizontales:** Muestra cómo separar secciones con líneas horizontales.

---

### **Resultado Final**
Guarda este archivo como `ejemplo-completo.md` en tu repositorio (por ejemplo, en la carpeta `prueba/`). Después de subirlo a GitHub y esperar unos minutos, ve a la URL correspondiente en tu sitio de GitHub Pages para ver cómo se renderiza cada elemento.

Por ejemplo:
```
https://<tu-usuario>.github.io/apunte-de-estudio/prueba/ejemplo-completo.html
