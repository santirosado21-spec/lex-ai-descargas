# LEX AI — descargas

Instalador de **LEX AI**, espacio de trabajo jurídico local para despachos mexicanos (macOS, Apple Silicon).

**Versión experimental 0.4.2.** No está validada por profesionales del derecho; toda respuesta requiere revisión profesional. No sustituye asesoría jurídica.

## Requisitos
- Mac con Apple Silicon (M1 o posterior), macOS reciente.
- 8 GB de RAM como mínimo (recomendado cerrar otras apps al consultar) y ~3 GB libres en disco.
- Internet solo la primera vez: «Preparar LEX AI» descarga ~1.95 GB de componentes del asistente. Después tus documentos y consultas se procesan en tu equipo.

## Instalar
1. Descarga `LEX-AI-0.4.2-arm64.dmg` desde la sección *Releases*.
2. Ábrelo y arrastra **LEX AI** a *Aplicaciones*.
3. Primera apertura: clic derecho sobre LEX AI → **Abrir** → Abrir (la app no está notarizada por Apple).
4. En *Configuración* pulsa **Preparar LEX AI**.

Verifica la integridad con `shasum -a 256 LEX-AI-0.4.2-arm64.dmg` y compara con el archivo `.sha256` del release.

Este repositorio solo distribuye binarios; el código fuente es privado.
