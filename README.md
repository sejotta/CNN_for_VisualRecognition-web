# CNN for Visual Recognition — web pública

Sitio público del proyecto **CNN for Visual Recognition**: clasificación de seis
monumentos con transfer learning en PyTorch + timm, evaluación sobre un test de
95 imágenes y exportación a ONNX para CPU / Raspberry Pi.

- **Web:** https://sejotta.github.io/CNN_for_VisualRecognition-web/
- **Contacto:** [WhatsApp](https://wa.me/qr/PXTMUZ4FCBSRP1)
- **Documentación pública:** [`docs/PIPELINE.md`](docs/PIPELINE.md),
  [`docs/RESULTS.md`](docs/RESULTS.md), [`docs/DEPLOYMENT.md`](docs/DEPLOYMENT.md)

## Qué contiene este repositorio

Este repositorio público contiene **solo la web y su documentación**:

```text
.
├── index.html
├── assets/                 # figuras, QR de contacto
├── docs/                   # pipeline, resultados, deploy
├── LICENSE
├── README.md
└── .nojekyll
```

No contiene el código fuente, los tests, el checkpoint ni la configuración del
proyecto. El código y el checkpoint se comparten **bajo solicitud** a través de
la sección de contacto de la web.

## Ejecutar en local

Desde la raíz de este repositorio:

```bash
python -m http.server 8000
```

Abre `http://localhost:8000/`.

También puedes abrir `index.html` directamente en el navegador; las rutas de
`assets/` son relativas.

## Despliegue

GitHub Pages sirve este repositorio desde `main` y la carpeta raíz (`/`). El
archivo `.nojekyll` evita que Pages procese el sitio con Jekyll.

## Licencia y créditos

El proyecto se desarrolló como la práctica P3 de **Computer Vision** en la
**Escuela de Ingeniería y Arquitectura (EINA), Universidad de Zaragoza**, bajo
la supervisión y corrección de sus profesores. Su guía hizo posible este
trabajo; el crédito académico de esa dirección pertenece al equipo docente.

El sitio y la documentación se publican bajo la **Academic Portfolio License**
(ver [`LICENSE`](LICENSE)). El código y el checkpoint se comparten bajo
solicitud; su reutilización, redistribución o uso comercial requiere permiso y
atribución, conforme a la licencia.

Las imágenes del dataset no se distribuyen y no están cubiertas por la licencia.

## Contacto

Si necesitas ayuda con el código, quieres comentar el proyecto o pedir permiso
de uso:

**https://wa.me/qr/PXTMUZ4FCBSRP1**

No se publican números de teléfono ni correos electrónicos en este repositorio.
