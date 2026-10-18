# Terramar Brands API — wsTerramarV2

Especificación OpenAPI 3.1 del servicio WCF `wsTerramarV2 (Service1.svc)` de Terramar Brands México: el carrito y el portal de consultoras.

- **Servicio:** <https://terramarbrands.mx/wsTerramarV2/Service1.svc>
- **Versión de la especificación:** 1.0.0 (OpenAPI 3.1.0)
- **Cobertura:** 40 operaciones en 12 grupos

## Contenido

| Archivo | Descripción |
| --- | --- |
| `openapi.json` | Especificación OpenAPI 3.1 completa del API |

## Grupos de operaciones

`Sesión`, `Catálogo público`, `Carrito`, `Perfil de consultora`, `Premios y bonos`, `Pedidos y facturación`, `Linaje`, `Atenciones`, `Viaje`, `Certificados`, `Pagos`, `Producto`

## Uso

- **Explorar el API:** importa `openapi.json` en [Redoc](https://redocly.github.io/redoc/), [Swagger UI](https://petstore.swagger.io/) o tu cliente favorito (Postman, Insomnia, Bruno).
- **Validar la especificación:**

  ```bash
  REDOCLY_TELEMETRY=off npx @redocly/cli lint openapi.json
  ```
