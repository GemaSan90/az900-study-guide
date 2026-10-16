# Guía de estudio AZ-900

Manuales en español para preparar el examen **AZ-900: Microsoft Azure Fundamentals**, módulo a módulo. Cada concepto se traduce al mundo ASIR, se acompaña de las frases que caen en el examen y se contrasta con Microsoft Learn.

## Manuales

| Módulo | Tema | Manual |
| --- | --- | --- |
| 1 | Informática en la nube, responsabilidad compartida, modelos de nube y consumo | [modulo-1.html](modulo-1.html) |
| 2 | Ventajas de usar servicios en la nube | [modulo-2.html](modulo-2.html) |
| 3 | Tipos de servicio en la nube: IaaS, PaaS y SaaS | [modulo-3.html](modulo-3.html) |

Los tres módulos cubren el bloque "Describir los conceptos de la nube", que pesa entre el 25 y el 30 % del examen según la [guía de estudio oficial](https://learn.microsoft.com/credentials/certifications/resources/study-guides/az-900).

## Verlo en el navegador

La portada es `index.html`. Para verla publicada con GitHub Pages:

1. En el repositorio, abre **Settings** y entra en **Pages**.
2. En **Build and deployment**, elige **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.

Pasados uno o dos minutos, GitHub muestra en esa misma pantalla la dirección de la web. Añádela aquí cuando la tengas.

## Estructura del repositorio

```text
.
├── index.html      Portada con una tarjeta por manual
├── modulo-1.html   Manual del Módulo 1
├── modulo-2.html   Manual del Módulo 2
├── modulo-3.html   Manual del Módulo 3
└── README.md
```

Cada manual es un único archivo HTML. Las fuentes se cargan desde Google Fonts y el resto funciona sin instalar nada. Admite modo claro y oscuro según el navegador.

## Añadir un módulo nuevo

1. Guarda el manual como `modulo-N.html` en la raíz del repositorio.
2. Añade su tarjeta en la sección "Manuales" de `index.html`.
3. Añade su fila en la tabla de este README.

## Fuentes

- [Guía de estudio del examen AZ-900](https://learn.microsoft.com/credentials/certifications/resources/study-guides/az-900)
- [Módulo "Describe cloud service types"](https://learn.microsoft.com/training/modules/describe-cloud-service-types/)
- [Módulo "Describe the benefits of using cloud services"](https://learn.microsoft.com/training/modules/describe-benefits-use-cloud-services/)
- [Responsabilidad compartida en la nube](https://learn.microsoft.com/azure/security/fundamentals/shared-responsibility)

## Aviso

Es material de estudio personal. Se ha contrastado con Microsoft Learn y con la guía de estudio del examen, pero no es contenido oficial de Microsoft ni está afiliado a Microsoft. Antes de examinarte, consulta siempre la guía de estudio vigente.
