# Angel Body - landing page

Landing page estática para desplegar en EasyPanel desde GitHub.

## Archivos
- `index.html`: web responsive con servicios faciales, corporales y contacto.
- `Dockerfile`: sirve la web con Nginx.

## Personalizar antes de publicar
1. Reemplazar `51999999999` en los dos enlaces `wa.me` por el WhatsApp real (código de país + número, solo dígitos).
2. Confirmar los nombres exactos y técnicas de los servicios ofrecidos.
3. Agregar dirección, ciudad, horarios, precios, redes sociales y fotografías autorizadas.
4. Confirmar qué servicio se denomina “lipopada”; en esta versión figura provisionalmente como “tratamiento de papada”.

## EasyPanel
1. Crear proyecto independiente `angelbody`.
2. Crear servicio App `web`.
3. Source: GitHub; repositorio `TU_USUARIO/angelbody-web`; branch `main`; Build Path `/`.
4. Build method: Dockerfile; Dockerfile path `Dockerfile`.
5. Deploy. Target port: `80`.
6. Agregar el subdominio en Domains y apuntar su DNS al VPS.
7. Activar HTTPS y Auto Deploy.

No modificar puertos, redes, volúmenes ni configuración de n8n, Evolution API, PostgreSQL o Redis.
