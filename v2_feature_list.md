## Features we already have in V2

### Marketplace
- Manage marketplace store with rich filters (brands, parent categories, categories, colors, materials, sizes, price, shipping)
- Add, view, and analyze marketplace products (detail, analysis modal, disconnect)
- Auto-transfer categories (checkout, filtered product count, save)
- Manage marketplace banners, latest, current-offer, and best‑selling products
- Transfer products to DRM (bulk and single) and to analysis; filter average price
- Channel management (list, terms, add/edit/delete shops, auto‑transfer toggle)

### Core Products
- Full product management (create, quick edit, detail, bulk actions, tax rate, categories)
- Product translation workflow (calc step, translate, payment initiation, preview)
- EAN manager (index, unused count)
- Universal product feeds per country (create/get/save/delete/sync)
- Shop product management (detail/update/category/status, assets upload, magic autocomplete)
- Shop universal feeds with DT auto‑sync
- Shop calculations (create, edit, update fields)
- Advanced product import pipeline (initialize, mapping, templates, finalization)
- Temporary import product curation (update/delete, term replace, EAN assign, process)
- Import filters (list/options/save/delete)

### Orders
- Orders: list/detail/update, history, bulk/status/document/payment notify
- Order creation/preview and helpers (stock products, shop list by country, feature list)
- Order tracking and parcels (create/update/remove, Shipcloud token/labels, MP returns)
- Order status and status color management
- Order widgets (tax/sale/proforma)
- Sales pipeline (deals, history, stages, files, bulk status)

### Customers
- Customers: CRUD, quick/column edit, tags and tag cloud, import, bulk actions, messages, campaign history

### Droptienda (DT)
- Droptienda shop integrations (iframe share setting, variant management)
- Public DT embed product page (rate‑limited)

### Suppliers
- Supplier management and feed sync (create/edit, feed sync, allow‑new/auto‑sync)

### Protected Shops
- Protected Shops workflow at shop level (questions/answers/files)

### Payments
- Payments: Stripe/Paypal user keys, cards, purchase, coupons, subscriptions, callbacks

### APIs and Auth
- API: Stripe/Paypal webhooks registered; auth/broadcasting via Sanctum
- API: Marketplace (categories/products/EAN search, stock, tracking, add order)
- API: Droptienda product/category CRUD


---

## Features we still need to implement in V2 [Estimated Timeline: 40 - 50 working days]

### Marketplace - (10 - 14 days)
- Manage and import marketplace collections
- Add and manage marketplace products (public embeddables + disconnect flow)
- Manage parent and subcategories (public store access + filters)
- Handle marketplace API connections (TWM/BikeApi endpoints and schedulers)
- Manage marketplace store banners (admin banner CRUD + display)
- Provide public marketplace widgets and search (JS embed + search APIs)

### Core Products - (5 days)
- Import UVP prices and customer reviews (competitive analysis sync)
- Manage product brand data (brand import/update CSV and assets)

### Droptienda (DT) - (5 days)
- Manage Droptienda chat and templates (chat, opt-in, editor templates)
- Payment success relays for DT (Stripe/Paypal invoice success forwarding)
- Test and finalize DT <> DRM sync

### Dropcampus - (2 days)
- Run Dropcampus sync and tariff checks (customer/transaction sync, validity APIs)

### Customers - (2 days)
- Supplier/customer public registration flows (frames, T&C/policy pages)

### APIs and Webhooks (7 days)
- Handle Zapier integrations (order creation, tags, customer leads)
- Receive Mailgun events and email tracking (open/fail webhooks, tracking links)

### Finance Export Module - (3 days)
- Develop Finace Export Module in V2

### Mirakl Channels - (2 days)
- Add Missing Channels in Dropmatix V2

### Orders and Trackings - (7 days)
- Transfer Order and tracking sync module in V2
