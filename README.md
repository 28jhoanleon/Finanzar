# 💰 FinanzasAR — Guía de instalación

## ¿Qué tiene esta app?

- ✅ **Datos reales** — tus gastos, ingresos y metas se guardan en el celu
- ✅ **Gráficos** — evolución patrimonial y comparativo mensual
- ✅ **Gamificación** — XP, niveles, rachas y logros
- ✅ **Modo disciplina** — recompensas y alertas de comportamiento
- ✅ **Calculadora de inflación** — cuánto vale tu plata en el tiempo
- ✅ **Anti-impulso** — calculá el costo real en horas de trabajo
- ✅ **IA real** — consejos personalizados con Claude (necesitás API key)
- ✅ **PWA** — instalable como app en Android e iPhone

---

## Opción 1 — Subir a Vercel (recomendado)

### Paso 1: Crear cuenta en GitHub
1. Andá a **github.com**
2. Hacé clic en "Sign up"
3. Creá tu cuenta gratis

### Paso 2: Crear repositorio
1. En GitHub, hacé clic en el **+** arriba a la derecha → "New repository"
2. Nombre: `finanzas-ar`
3. Dejalo en **Public**
4. Clic en "Create repository"

### Paso 3: Subir los archivos
1. En la página del repositorio, clic en "uploading an existing file"
2. Arrastrá **todos los archivos** de esta carpeta
3. Clic en "Commit changes"

### Paso 4: Conectar Vercel
1. Andá a **vercel.com**
2. Clic en "Sign up" → elegí "Continue with GitHub"
3. Clic en "Add New Project"
4. Buscá tu repositorio `finanzas-ar` y clic en "Import"
5. En "Root Directory" escribí: `public`
6. Clic en **Deploy**

### Paso 5: ¡Listo!
- Vercel te da una URL tipo `finanzas-ar.vercel.app`
- Abrila desde el celular

---

## Opción 2 — Solo el HTML (sin Vercel)

1. Bajate el archivo `public/index.html`
2. Subilo a **tiiny.host** (gratis, sin registro)
3. Te dan un link para compartir

---

## Instalar como app en el celular (PWA)

### iPhone:
1. Abrí la URL en Safari
2. Tocá el botón **compartir** (cuadrado con flecha ↑)
3. Scroll abajo → **"Agregar a pantalla de inicio"**
4. Clic en "Agregar"

### Android:
1. Abrí la URL en Chrome
2. Tocá los **tres puntitos** ⋮
3. Tocá **"Agregar a pantalla de inicio"** o **"Instalar app"**
4. Confirmá

---

## Conectar la IA (opcional)

1. Andá a **console.anthropic.com**
2. Creá una cuenta gratis
3. En "API Keys" → "Create Key"
4. Copiá la key (empieza con `sk-ant-...`)
5. En la app, andá a la pestaña **🤖 IA**
6. Pegá tu key y clic en "Conectar IA"

La IA va a leer tus datos reales y darte consejos personalizados.

---

## Estructura de archivos

```
finanzas-ar/
├── public/
│   ├── index.html      ← La app completa
│   └── manifest.json   ← Para instalar como PWA
├── vercel.json         ← Configuración de Vercel
└── README.md           ← Esta guía
```

---

## ¿Querés actualizar la app?

Cuando tengas cambios:
1. Subí el archivo actualizado a GitHub
2. Vercel se actualiza **automáticamente** en segundos

---

*Hecho con ❤️ para Argentina*
