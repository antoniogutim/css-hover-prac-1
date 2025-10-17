# CSS Hover – Práctica 1

Pequeña demo para practicar efectos **hover** en CSS con un botón sencillo.

---

## 🖥️ Demo / Preview

**URL pública:** https://antoniogutim.github.io/css-hover-prac-1/

---

## 📁 Estructura

css-hover-prac-1/
├─ index.html
└─ styles.css


- `index.html`: documento principal que incluye el botón.
- `styles.css`: estilos del botón y el efecto `:hover`.

---

## 🚀 Cómo ejecutar / editar

**Local**
1. Clona o descarga el repositorio.
2. Abre `index.html` en tu navegador.

**VS Code + Live Server (recomendado)**
1. Abre la carpeta del proyecto en **VS Code**.
2. Instala la extensión **Live Server**.
3. Clic derecho en `index.html` → **Open with Live Server**.
4. Edita `styles.css` y verás los cambios en vivo.

---

## 🔧 Personalización rápida

```css
button {
  background-color: grey;     /* color base */
  color: white;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
  transition: all .2s ease;   /* transición suave */
}
button:hover {
  background-color: blue;     /* color al pasar el ratón */
  transform: scale(1.03);
}
```
---
## 🌐 GitHub Pages

En Settings → Pages:

Source: Deploy from a branch

Branch: main y / (root)

Guarda y espera 1–2 minutos.

Tu sitio quedará en: https://<tu-usuario>.github.io/<repo>/
Para este repo: https://antoniogutim.github.io/css-hover-prac-1/

## 📝 Notas

Mantén index.html en la raíz del repo.

Para actualizar el sitio:

```
git add .
git commit -m "Mejora estilos del botón"
git push
```
## 📄 Licencia

AGM © 2025
