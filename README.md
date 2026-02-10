# OpusBot - Términos y Condiciones

Página de términos y condiciones para la plataforma OpusBot con estilo cyberpunk.

## Redes Sociales Incluidas
- TikTok (Upload API)
- Instagram/Reels (Graph API)
- YouTube/Shorts (Data API v3)
- Facebook Watch (Video API)

## Secciones
- §1: Aceptación de Términos
- §2: Descripción del Servicio
- §3: Cuenta de Usuario y Conexiones (Bloqueo/Anclado)
- §4: Programación y Planificación de Contenido
- §5: Propiedad Intelectual
- §6: Limitación de Responsabilidad
- §7: Modificaciones del Servicio
- §8: Políticas de Plataformas de Terceros
- §9: Privacidad y Protección de Datos
- §10: Jurisdicción
- §11: Información de Contacto

## Despliegue en GitHub Pages

1. Crea un nuevo repositorio en GitHub llamado `terminos-conditions`
2. Sube estos archivos:
   ```bash
   cd terminos-conditions
   git init
   git add .
   git commit -m "Initial commit: Términos y Condiciones"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/terminos-conditions.git
   git push -u origin main
   ```

3. En GitHub: Settings → Pages → Source: "main" → Save

4. La URL será: `https://TU_USUARIO.github.io/terminos-conditions/`

## URL para OpusBot
Una vez desplegado, actualiza el enlace en `LoginScreen.tsx` línea 131:
```jsx
<a href="https://TU_USUARIO.github.io/terminos-conditions/" target="_blank" className="hover:text-gray-400 transition-colors">Términos</a>
```

## Versión
- v2.5 - 2026-02-10
