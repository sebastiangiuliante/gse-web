# Giuliante Soluciones Energéticas (GSE) — Landing Page Oficial

Sitio web institucional y comercial de alta conversión para **Giuliante Soluciones Energéticas (GSE)**, empresa líder en ingeniería eléctrica e instalaciones solares fotovoltaicas en San Miguel de Tucumán y todo el NOA.

---

## 🚀 Características del Proyecto

- **Diseño Fiel a Figma:** Paleta corporativa oscura (#0D0E12 / #15171E) con acentos en amarillo solar (#F5A623) y tipografía técnica (*Montserrat* e *Inter*).
- **100% Responsive:** Adaptado para celulares, tablets y monitores de escritorio.
- **Ultra Liviano y Rápido:** Carga instantánea, sin dependencias complejas ni configuración de servidor.
- **Enfoque Comercial & Conversión:**
  - Botón flotante directo de WhatsApp con mensaje predeterminado.
  - Formulario de cotización inteligente que redirige la consulta formateada directamente al WhatsApp oficial (+54 381 300-5341).
  - Presencia destacada de proyectos ancla institucionales (**Maternidad de Tucumán 300 kWp**, **Laboratorio Catamarca 40 kWp**, etc.).
  - Corrección de ortografía, textos comerciales y testimonios expresados en porcentajes de ahorro.

---

## 💻 Cómo probarlo en tu computadora

Simplemente hacé doble clic en el archivo [`index.html`](index.html) y se abrirá en tu navegador favorito (Chrome, Edge, etc.).

---

## 📦 Paso a Paso: Subir a GitHub y Publicar con tu Dominio

### Paso 1: Crear el repositorio en GitHub
1. Entrá a [github.com](https://github.com) e iniciá sesión con tu cuenta.
2. Hacé clic en el botón verde **"New"** para crear un nuevo repositorio.
3. Poné de nombre al repositorio: `gse-web` (o `giuliante-web`), dejalo **Público** y no marques ninguna casilla adicional. Hacé clic en **"Create repository"**.
4. Copiá la URL de tu nuevo repositorio (ej: `https://github.com/tu-usuario/gse-web.git`).

### Paso 2: Subir el código desde la terminal
Abrí una terminal en esta carpeta (`C:\Users\sebas\.gemini\antigravity\scratch\gse-landing`) y ejecutá:

```bash
git init
git add .
git commit -m "feat: landing page inicial GSE basada en diseño de Figma"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/gse-web.git
git push -u origin main
```

*(Reemplazá `TU-USUARIO` por tu usuario real de GitHub).*

---

### Paso 3: Desplegar gratis en Vercel (Recomendado)

1. Entrá en [vercel.com](https://vercel.com) y elegí **"Sign Up"** (o "Log in") con tu cuenta de **GitHub**.
2. Hacé clic en **"Add New..." > "Project"**.
3. Seleccioná el repositorio `gse-web` y hacé clic en **"Import"**.
4. En la configuración dejá todo por defecto y presioná **"Deploy"**.
5. ¡En menos de 30 segundos tu web ya estará online en una URL pública con certificado SSL (HTTPS)!

---

### Paso 4: Conectar tu Dominio Propio

1. Dentro de tu proyecto en **Vercel**, andá a **Settings > Domains**.
2. Escribí tu dominio (ej: `giuliante.com.ar` o `www.giuliante.com.ar`) y hacé clic en **Add**.
3. Vercel te mostrará los registros DNS que tenés que cargar:
   - Para el dominio raíz: Un registro **A** apuntando a `76.76.21.21`.
   - Para el subdominio www: Un registro **CNAME** apuntando a `cname.vercel-dns.com`.
4. Ingresá al panel donde compraste tu dominio (ej: Nic.ar, DonWeb, Hostinger, GoDaddy, etc.) y agregá esos dos registros en la zona DNS.
5. ¡Listo! En unas horas (tiempo de propagación habitual de DNS) tu sitio estará funcionando bajo tu dominio con candado de seguridad verde.
