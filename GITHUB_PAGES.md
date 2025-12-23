# 🌐 Cómo Activar GitHub Pages

## Pasos Rápidos:

1. **Ve a Settings del repositorio:**
   https://github.com/estebanmtzsevilla-gif/taxdown-report/settings/pages

2. **En la sección "Source":**
   - Selecciona: **"Deploy from a branch"**
   - Branch: **"main"**
   - Folder: **"/ (root)"**
   - Click en **"Save"**

3. **Espera 1-2 minutos** mientras GitHub procesa el sitio

4. **Tu sitio estará disponible en:**
   ```
   https://estebanmtzsevilla-gif.github.io/taxdown-report/
   ```

## ✅ Estado Actual:

- ✅ `index.html` configurado (renombrado desde TaxDown_claude.html)
- ✅ `styles.css` enlazado correctamente
- ✅ `.nojekyll` agregado (para servir HTML estático)
- ✅ Código pusheado a GitHub

## 🔄 Actualizar el Sitio:

Cada vez que hagas cambios:

```bash
git add .
git commit -m "Descripción de los cambios"
git push origin main
```

Los cambios se reflejarán en GitHub Pages en 1-2 minutos automáticamente.

