# Aura Capital Partners — sitio web inicial

Primera versión estática construida con Astro, pensada para desplegarse en Netlify.

## Requisitos
- Node.js 20.3.0 o superior (recomendado).

## Ejecutar en tu computador
1. Instala Node.js desde https://nodejs.org/ si todavía no lo tienes.
2. Abre una terminal dentro de esta carpeta.
3. Ejecuta `npm install`.
4. Ejecuta `npm run dev` y abre la dirección local que te indique la terminal.
5. Para comprobar la versión de publicación, ejecuta `npm run build`.

## Publicar en Netlify
1. Sube esta carpeta a un repositorio de GitHub.
2. Entra a https://app.netlify.com/ y conecta el repositorio.
3. Netlify normalmente detecta Astro. Usa `npm run build` como comando de build y `dist` como directorio de publicación.
4. Publica usando el subdominio gratuito que ofrece Netlify.
5. Revisa los límites vigentes del plan gratuito antes de usarlo comercialmente.

## Configuración pendiente
- En `src/pages/index.astro`, cambia `whatsappNumber` por el número comercial con código de país, solo dígitos (ejemplo de formato chileno: `56912345678`).
- Reemplaza o confirma los textos y servicios según lo que Aura realmente ofrecerá.
- Agrega datos de contacto reales cuando estén definidos.
- La web no incluye todavía un formulario que almacene o envíe datos; por ahora los botones de contacto llevan a la sección de contacto si no se configura WhatsApp.
- El diseño carga Google Fonts desde internet; si prefieres no depender de ello, podemos cambiar a fuentes del sistema.

## Notas
Esta es una base visual inicial. Antes de usarla como sitio comercial definitivo, verifica textos, alcance de servicios, privacidad y datos corporativos. No se incluyen testimonios, certificaciones ni resultados inventados.
