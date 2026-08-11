# RABON Phase 7 — Admin Image Upload + Public Store

What changed:
- `/` is now the public RABON store.
- `/account` contains customer Login/Register.
- Admin product page can upload a product image to the `product-images` Supabase Storage bucket.
- Uploaded image URL is saved in `product_images`.
- Store automatically displays live active products and their first image.
- Product search, categories and cart foundation remain available.
- Admin can edit/delete products.

Important:
- The Phase 6 SQL must already have been run.
- Use only the Supabase publishable key in frontend code. Never use service-role/secret keys.
- Before real orders/payments, we still need a server-side order flow and stronger checkout validation.

Next phase: customer checkout, order tables, COD, admin order management, and then Bangladesh payment gateway integration.
