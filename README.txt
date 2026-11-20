ZonaDeporte - prototipo v2

Qué incluye:
- Diseño responsive, categorías, buscador y filtros.
- Titulares desde varios feeds RSS: BBC Sport, Google News (búsquedas deportivas) y feed oficial de Formula 1.
- RSS se consulta vía rss2json (intermediario de terceros); requiere conexión y puede fallar/limitarse. No es una arquitectura de producción.
- Actualización automática cada 10 minutos, sin resultados deportivos inventados.
- Cada titular enlaza al original; se muestran extractos breves.
- Espacios de anuncios vacíos (no hay anuncios ni AdSense integrado).
- Páginas legales de plantilla: completar y revisar antes de publicar.

Para probar:
1. Extraer el ZIP.
2. Abrir index.html en navegador con Internet. (Puede haber limitaciones del navegador con peticiones cross-origin; probar alojada en un hosting estático).

Pendiente para versión producción:
- Sustituir rss2json por un backend/función serverless propia que obtenga y cachee RSS, valide feeds y evite dependencia externa.
- Revisar términos/licencias y políticas de cada fuente. El feed ESPN, por ejemplo, advierte contra integrar publicidad en su contenido RSS; no se usa en esta versión.
- Integrar API licenciada de resultados/calendarios (sin clave no se conectó ninguna).
- Añadir artículos originales y páginas de contenido evergreen para SEO; no confiar solo en titulares agregados.
- Completar aviso legal, privacidad y cookies con datos reales; consentimiento CMP antes de activar anuncios/analítica no esencial.
- Dominio, hosting, Search Console, sitemap.xml, robots.txt, iconos, canonical y política de contenido.
- Solicitar AdSense solo después de revisar los requisitos vigentes y publicar contenido original suficiente.
