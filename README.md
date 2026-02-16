# Landing Page - Gimnasia Cerebral para Adultos 50+

## 📋 Descripción
Landing page optimizada para conversión dirigida a adultos mayores de 50 años interesados en gimnasia cerebral.

## 🚀 Deployment a Vercel

### Opción 1: Deploy desde GitHub (Recomendado)

1. **Crear repositorio en GitHub:**
   - Ve a github.com y crea un nuevo repositorio
   - Sube todos estos archivos al repositorio

2. **Conectar con Vercel:**
   - Ve a vercel.com e inicia sesión
   - Click en "Add New Project"
   - Selecciona "Import Git Repository"
   - Autoriza a Vercel para acceder a tu GitHub
   - Selecciona el repositorio que acabas de crear

3. **Configurar proyecto:**
   - Project Name: `gimnasia-cerebral-adultos` (o el que prefieras)
   - Framework Preset: Other
   - Root Directory: `./`
   - No necesitas modificar Build & Output Settings
   - Click en "Deploy"

4. **Listo!** 
   - Vercel te dará una URL tipo: `gimnasia-cerebral-adultos.vercel.app`
   - Puedes configurar un dominio personalizado después

### Opción 2: Deploy con Vercel CLI

1. **Instalar Vercel CLI:**
```bash
npm i -g vercel
```

2. **Login a Vercel:**
```bash
vercel login
```

3. **Deploy desde la carpeta:**
```bash
cd [carpeta-del-proyecto]
vercel
```

4. **Seguir las instrucciones:**
   - Set up and deploy? Yes
   - Which scope? [Tu cuenta]
   - Link to existing project? No
   - Project name? gimnasia-cerebral-adultos
   - In which directory is your code located? ./
   - Want to override settings? No

5. **Production deploy:**
```bash
vercel --prod
```

### Opción 3: Drag & Drop (Más simple)

1. **Preparar archivos:**
   - Comprime toda la carpeta en un .zip
   - O ten todos los archivos listos

2. **Deploy manual:**
   - Ve a vercel.com/new
   - Arrastra la carpeta completa o el .zip
   - Vercel automáticamente lo deployará
   - Te dará una URL en segundos

## 📁 Estructura de archivos

```
/
├── index.html          # Página principal
├── vercel.json         # Configuración de Vercel
├── assets/             # Carpeta de imágenes
│   ├── logo-evolucione-1-scaled.png
│   ├── Maria.jpg
│   ├── roberto.jpg
│   ├── claudia.jpg
│   ├── ema_milena_4.png
│   ├── EMA_BENEFICIOS__1_.png
│   └── ...
└── README.md          # Este archivo
```

## 🔗 Links importantes

- **Video YouTube:** https://youtu.be/0edke-GiNw8
- **Checkout Hotmart:** https://pay.hotmart.com/C103235667V?checkoutMode=10
- **WhatsApp:** +52 33 1113 8538 (EMA Adultos)

## ⚙️ Configuración del timer

- **Duración del video:** 3:48 (228 segundos)
- **Aparición del contenido:** 10 segundos después de iniciar video
- **Botón Skip:** Aparece a los 30 segundos
- **Popup automático:** Al finalizar el video o al hacer skip

## 🎨 Personalización

Para modificar precios o textos, busca en `index.html`:
- **Precio actual:** Línea con `$300`
- **Precio anterior:** Línea con `$2,200`
- **Ahorro:** Línea con `$1,900`
- **Lugares disponibles:** Variable `c=6` en el script

## 📱 WhatsApp

Todos los enlaces de WhatsApp tienen el identificador "EMA Adultos" para diferenciarlo del curso de docentes.

## 🎯 Optimizaciones incluidas

✅ Mobile-first responsive
✅ Lazy loading de imágenes
✅ Optimización de fuentes
✅ Timer countdown funcional
✅ Popup con urgencia y escasez
✅ WhatsApp flotante
✅ Sticky CTA
✅ Skip button con animación
✅ Contador de viewers en vivo
✅ Progress bar visual

## 🔧 Soporte

Para modificaciones o dudas técnicas, contacta al equipo de desarrollo.

---
© 2025 Evolucione - Gimnasia Cerebral
