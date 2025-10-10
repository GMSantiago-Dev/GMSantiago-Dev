# 🐍 Configuración de Contribution Snake

## 📋 Pasos para activar la animación de la serpiente

### 1️⃣ Crear el repositorio en GitHub

1. Ve a https://github.com/new
2. **Nombre del repositorio**: `GMSantiago-Dev` (exactamente tu username)
3. Marca como **Public**
4. **NO** agregues README (ya lo tienes)
5. Crea el repositorio

### 2️⃣ Subir los archivos

Abre tu terminal en la carpeta `e:/resumen` y ejecuta:

```bash
git init
git add .
git commit -m "Initial commit: Gaming style README with Snake animation"
git branch -M main
git remote add origin https://github.com/GMSantiago-Dev/GMSantiago-Dev.git
git push -u origin main
```

### 3️⃣ Activar GitHub Actions

1. Ve a tu repositorio en GitHub
2. Haz clic en la pestaña **"Actions"**
3. GitHub te pedirá que habilites las Actions
4. Haz clic en **"I understand my workflows, go ahead and enable them"**

### 4️⃣ Ejecutar la Action manualmente (primera vez)

1. En la pestaña **Actions**
2. Selecciona el workflow **"Generate Snake Animation"** en el menú lateral
3. Haz clic en **"Run workflow"** → **"Run workflow"**
4. Espera 1-2 minutos a que se complete

### 5️⃣ Verificar que funcionó

1. Ve a la pestaña **"Code"** de tu repositorio
2. Cambia de rama a **"output"** (selector de ramas arriba a la izquierda)
3. Deberías ver 3 archivos SVG:
   - `github-contribution-grid-snake.svg`
   - `github-contribution-grid-snake-dark.svg`
   - `github-contribution-grid-snake-light.svg`

### 6️⃣ ¡Listo! 🎉

La serpiente ahora aparecerá en tu README y se actualizará automáticamente cada 12 horas.

---

## 🔄 Actualizaciones automáticas

La GitHub Action está configurada para ejecutarse:
- ✅ Cada 12 horas automáticamente
- ✅ Cada vez que hagas push a la rama `main`
- ✅ Manualmente cuando quieras desde la pestaña Actions

---

## 🎨 Características de la serpiente

- 🌙 **Modo oscuro** - Se adapta al tema del navegador
- ☀️ **Modo claro** - También disponible
- 🎮 **Animación** - La serpiente "come" tus contribuciones
- 🔄 **Actualización automática** - Siempre muestra tus últimas contribuciones

---

## ❓ Solución de problemas

### La serpiente no aparece
- Espera 2-3 minutos después de ejecutar la Action
- Verifica que la Action se completó exitosamente (sin errores rojos)
- Asegúrate de que la rama `output` existe

### Error en la Action
- Verifica que el nombre del repositorio sea exactamente tu username
- Asegúrate de que el repositorio sea público
- Revisa los logs de la Action para ver el error específico

### La imagen no se actualiza
- Limpia el caché de tu navegador
- Espera a que se ejecute la próxima actualización automática (cada 12 horas)
- Ejecuta manualmente la Action desde la pestaña Actions

---

## 📝 Notas adicionales

- La serpiente solo mostrará contribuciones del último año
- Necesitas tener al menos algunas contribuciones para que se vea bien
- La animación es un SVG, por lo que es ligera y rápida de cargar
- Funciona en modo claro y oscuro automáticamente

---

¡Disfruta tu nueva serpiente de contribuciones! 🐍✨
