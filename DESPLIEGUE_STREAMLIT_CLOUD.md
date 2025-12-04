# ✅ Código Subido a GitHub

El código ya está en: https://github.com/andresriosinfo/alarm_flood

## 🚀 Pasos para Desplegar en Streamlit Cloud

### 1. Acceder a Streamlit Cloud
- Ve a: https://share.streamlit.io/
- Inicia sesión con tu cuenta de GitHub

### 2. Crear Nueva App
1. Haz clic en **"New app"**
2. Selecciona el repositorio: `andresriosinfo/alarm_flood`
3. Branch: `master` (o `main` si cambiaste el nombre)
4. Main file path: `app.py`
5. Haz clic en **"Deploy"**

### 3. Configuración Adicional (Opcional)

Si necesitas datos o el modelo:
- Ve a **Settings** → **Secrets**
- Agrega variables de entorno si es necesario
- O sube el modelo `.pkl` al repositorio (si es pequeño)

### 4. Acceder a tu App

Una vez desplegada, tendrás una URL como:
`https://alarm-flood.streamlit.app`

## 📝 Notas Importantes

- El dashboard funcionará con datos de ejemplo si no encuentra el CSV
- Para producción, modifica `load_data()` en `app.py` para conectar con tu fuente de datos
- El modelo `.pkl` no está incluido (muy grande), agrégalo si es necesario

## ✅ Estado Actual

- ✅ Código en GitHub
- ⏳ Pendiente: Desplegar en Streamlit Cloud
- ⏳ Pendiente: Conectar con datos reales (opcional)

