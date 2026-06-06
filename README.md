# Demo web - El Asador de Salamanca

Demo estática para restaurante asador en Leganés.

## Datos usados

- Teléfono confirmado por el usuario: `669 90 92 37`.
- Horario confirmado por captura del usuario:
  - Lunes a viernes: `9:00-18:00`.
  - Sábado y domingo: `13:00-18:00`.
- Dirección y especialidades tomadas de fuentes públicas revisables:
  - Av. de los Pinos, 2, 28914 Leganés, Madrid.
  - Asador, carnes a la brasa, cochinillo, cordero, entrecot y chuletón.

## Pendiente para versión final

- Confirmar si se mantiene el teléfono `916 93 37 08` como secundario o se elimina.
- Sustituir imágenes públicas representativas por fotos propias o autorizadas del local.
- Confirmar horarios definitivos antes de publicar.
- Añadir redes sociales, enlace de reservas o aviso legal si existen.

## Publicación

El sitio es HTML estático. Incluye un workflow de GitHub Actions en `.github/workflows/deploy.yml` para publicar en GitHub Pages desde la rama `main`.

Para que se publique:

1. Crear un repositorio llamado, por ejemplo, `asador-salamanca-demo`.
2. Subir estos archivos a la raíz del repositorio.
3. En GitHub, abrir `Settings > Pages` y elegir `GitHub Actions` como fuente de despliegue.
4. Hacer un push a `main` o ejecutar manualmente el workflow `Deploy static site to GitHub Pages`.
