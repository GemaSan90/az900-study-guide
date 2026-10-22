# Guía de estudio AZ-900

Manuales por módulos para preparar el examen **AZ-900: Microsoft Azure Fundamentals**, en español. Cada manual está contrastado con Microsoft Learn y con la guía de estudio oficial del examen.

**Ver la guía publicada:** https://gemasan90.github.io/az900-study-guide

## Módulos

| Módulo | Tema | Estado | Archivo |
| --- | --- | --- | --- |
| 1 | Descripción de la informática en la nube | Unidades 1 a 6 | `modulo-1.html` |
| 2 | Ventajas de usar servicios en la nube | Completo | `modulo-2.html` |
| 3 | Tipos de servicio en la nube (IaaS, PaaS y SaaS) | Completo | `modulo-3.html` |
| 4 | Componentes arquitectónicos principales de Azure | Completo: 7 unidades | `modulo-4.html` |
| 5 | Servicios de proceso en Azure | Parte de proceso: 9 temas | `modulo-5.html` |
| 6 | Redes y conectividad en Azure | Completo: 10 temas | `modulo-6.html` |
| 7 | Almacenamiento en Azure | Versión resumida: 5 temas | `modulo-7.html` |
| 8 | Identidad, acceso y seguridad en Azure | Versión resumida: 9 temas | `modulo-8.html` |

El Módulo 4 cubre la infraestructura física (regiones, zonas de disponibilidad, pares de regiones y regiones soberanas) y la de administración (recursos, grupos de recursos, suscripciones y grupos de administración).

El Módulo 5 cubre la parte de proceso del módulo *Describe Azure compute and networking services*: máquinas virtuales, Scale Sets, conjuntos de disponibilidad, Azure Virtual Desktop, contenedores (ACI, Container Apps y AKS), Azure Functions y App Service. Incluye una ampliación de IA e IoT y un repaso de examen. Las redes de ese módulo de Learn, ahora un módulo propio, están en el Módulo 6.

El Módulo 6 cubre las redes: redes virtuales y subredes, puntos de conexión públicos y privados, NSG y rutas, VNet Peering, VPN Gateway (tipos y alta disponibilidad), ExpressRoute y Azure DNS. Incluye repaso de examen y relación con el AZ-104.

El Módulo 7 cubre el almacenamiento: cuentas de almacenamiento, los servicios Blob, Files, Queues, Tables y Disks, la redundancia (LRS, ZRS, GRS, RA-GRS, GZRS y RA-GZRS), los niveles de acceso de Blob (Hot, Cool, Cold y Archive) y las herramientas de migración y movimiento de datos (Azure Migrate, Data Box, AzCopy, Storage Explorer y Azure File Sync). Es una versión resumida, más corta que los módulos anteriores, con repaso de examen y relación con el AZ-104.

El Módulo 8 cubre identidad, acceso y seguridad: Microsoft Entra ID (con Entra Connect y Domain Services), SSO, MFA y passwordless (Windows Hello, Authenticator y FIDO2), identidades externas (B2B, B2B direct connect y External ID), Acceso condicional, RBAC, Zero Trust, defensa en profundidad, cifrado con Key Vault y Defender for Cloud. Es una versión resumida, con repaso de examen y relación con el AZ-104.

## Cómo encajan en el examen

| Bloque del examen | Peso | Manuales |
| --- | --- | --- |
| Conceptos cloud | 25–30 % | Módulos 1, 2 y 3 |
| Arquitectura y servicios de Azure | 35–40 % | Módulos 4 (componentes arquitectónicos), 5 (servicios de proceso), 6 (redes), 7 (almacenamiento) y 8 (identidad, acceso y seguridad) |
| Administración y gobierno | 30–35 % | Pendiente |

Pesos según la guía de estudio de Microsoft (habilidades medidas desde el 20 de julio de 2026).

## Qué incluye cada manual

- Idea principal de cada unidad y diagramas rehechos en español.
- Cuadros de **traducción ASIR** para relacionar Azure con lo que ya conoces.
- Frases de examen, errores frecuentes y trucos para memorizar.
- Preguntas de repaso desplegables y una lista de comprobación que se guarda en el navegador.
- Una sección final de **contraste con Microsoft Learn** con las correcciones hechas.

## Estructura del repositorio

```
az900-study-guide/
├── index.html      Portada con los módulos
├── modulo-1.html
├── modulo-2.html
├── modulo-3.html
├── modulo-4.html
├── modulo-5.html
├── modulo-6.html
├── modulo-7.html
├── modulo-8.html
└── README.md
```

Cada página es un único archivo HTML autocontenido. Solo carga las fuentes desde Google Fonts, así que se puede abrir directamente en el navegador.

## Publicar los cambios

1. Copia los archivos actualizados a la carpeta del repositorio.
2. Súbelos:

   ```
   git add index.html modulo-8.html README.md
   git commit -m "Añade el Módulo 8 (identidad, acceso y seguridad) y actualiza la portada"
   git push
   ```

3. GitHub Pages republica el sitio en uno o dos minutos.

## Fuentes

Los contenidos se contrastan con [Microsoft Learn](https://learn.microsoft.com/training/) y con la [guía de estudio del AZ-900](https://learn.microsoft.com/credentials/certifications/resources/study-guides/az-900). Los ejemplos, las analogías y los escenarios de práctica son material didáctico propio, no datos de Microsoft.

---

Gema San · Sueña. Aprende. Crece.
