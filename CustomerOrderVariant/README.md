# CustomerOrderVariant

## Español 🇪🇸

Tener un histórico de lo que ha comprado el cliente y ha que pedido va asociado es fundamental para correcta experiencia de usuario especialmente en entornos headless. Con la query **CustomerOrderVariant** podrás identificar todas las variantes de un producto asociadas a un pedido.

- **Connection: Customer** — representa al cliente de la tienda.
- **Object: Order** — representa la solicitud de compra y conecta cliente, productos, pagos y fulfillment.
- **Connection: LineItem** — representa una línea concreta del pedido.
- **Field: ProductVariant** — identifica la variante comprada.
- **Field: Product** — identifica el producto al que pertenece la variante.
- **Scopes:** `read_customers`, `read_orders`, `read_marketplace_orders`, `read_quick_sale`, `read_products`.
- **URL del objeto elegido:** [Order](https://shopify.dev/docs/api/admin-graphql/2026-04/objects/Order)

## English 🏴󠁧󠁢󠁥󠁮󠁧󠁿

Having a record of what the customer has purchased and the associated orders is essential for a good user experience, particularly in headless environments. With the **CustomerOrderVariant** query, you can identify all the product variants associated with an order.

- **Connection: Customer** — represents the shop’s customer.
- **Object: Order** — represents the purchase order and links the customer, products, payments and fulfilment.
- **Connection: LineItem** — represents a specific line item in the order.
- **Field: ProductVariant** — identifies the variant purchased.
- **Field: Product** — identifies the product to which the variant belongs.
* **Scopes:** `read_customers`, `read_orders`, `read_marketplace_orders`, `read_quick_sale`, `read_products`.
* **URL of the selected object:** [Order](https://shopify.dev/docs/api/admin-graphql/2026-04/objects/Order)

## Sigueme / Follow me

Instagram: **antoniopaez_blacksmithdev**
BlueSky: **@apaez-blacksmith.bsky.social**
X: **@apaezblacksmith**