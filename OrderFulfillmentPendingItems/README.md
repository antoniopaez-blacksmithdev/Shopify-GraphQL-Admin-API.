# OrderFulfillmentPendingItems

## Español 🇪🇸

Tener preparados los productos a tiempo para cumplir con el envío es fundamental si no quieres perder ventas y mantener tu reputación con los clientes. La query **OrderFulfillmentPendingItems** te perite tener un listado cada vez que lo necesites de los pedidos que hay que preparar o enviar.

- **Connection: Order** — contiene la compra y su ciclo de vida.
- **Object: FulfillmentOrder** — representa el trabajo de fulfillment previsto para el pedido.
- **Connection: FulfillmentOrderLineItem** — representa una línea que debe prepararse o enviarse.
- **Field: LineItem** — conserva la línea original del pedido.
- **Field: ProductVariant** — identifica la variante relacionada.
- **Scopes:** `read_orders`, `read_marketplace_orders`, `read_quick_sale`, `read_assigned_fulfillment_orders`, `read_merchant_managed_fulfillment_orders`, `read_third_party_fulfillment_orders`, `read_marketplace_fulfillment_orders`, `read_products`.
- **URL del objeto elegido:** [FulfillmentOrder](https://shopify.dev/docs/api/admin-graphql/2026-04/objects/FulfillmentOrder)

## English 🏴󠁧󠁢󠁥󠁮󠁧󠁿

Having products ready on time to meet dispatch deadlines is essential if you want to avoid losing sales and maintain your reputation with customers. The **OrderFulfillmentPendingItems** query allows you to generate a list, whenever you need it, of the orders that need to be prepared or dispatched.

- **Connection: Order** — contains the order and its lifecycle.
- **Object: FulfillmentOrder** — represents the fulfilment work scheduled for the order.
- **Connection: FulfillmentOrderLineItem** — represents a line item that needs to be prepared or dispatched.
- **Field: LineItem** — retains the original order line item.
- **Field: ProductVariant** — identifies the related variant.
- **Scopes:** `read_orders`, `read_marketplace_orders`, `read_quick_sale`, `read_assigned_fulfillment_orders`, `read_merchant_managed_fulfillment_orders`, `read_third_party_fulfillment_orders`, `read_marketplace_fulfillment_orders`, `read_products`.
* **URL of the selected object:** [FulfillmentOrder](https://shopify.dev/docs/api/admin-graphql/2026-04/objects/FulfillmentOrder)

## Sigueme / Follow me

* Web: **[Ironforgecode](https://ironforgecode.com)**
* Instagram: **antoniopaez_blacksmithdev**
* BlueSky: **@apaez-blacksmith.bsky.social**
* X: **@apaezblacksmith**