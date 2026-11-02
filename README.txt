AUREX storefront prototype

Files:
- index.html
- assets/ (the six product photos supplied in chat)

Current catalogue and prices:
- Ladies Purse ₹599, stock 10
- Premium Watch ₹2,500, stock 10
- Black X Perfume ₹599, stock 10
- Perfume Collection ₹599, stock 9
- Anklet Design 1 ₹399, stock 3
- Anklet Design 2 ₹399, stock 3
- Belts: stock 6 noted, but product photo and selling price not yet supplied.

Shipping rules configured in the prototype:
- 0–80 km: ₹100
- 81–500 km: ₹200
- Above 500 km: ₹250
Dispatch origin: Karnal, Haryana.

IMPORTANT:
This is a visual/front-end prototype only. Admin inventory and demo orders use browser localStorage and are not secure or shared between devices. The displayed temporary demo password is NOT production security.
Do not accept real customer orders or online payments yet. Before launch, connect:
1. A real database + server-side admin authentication (e.g. Supabase/Firebase).
2. Secure image storage and product management.
3. Payment gateway (Razorpay or another approved provider) with server-side payment verification.
4. WhatsApp Business Platform/template messaging for automatic order confirmation. A normal wa.me link cannot automatically send messages.
5. Verified return/refund policy and delivery-distance calculation/serviceability.
6. HTTPS domain hosting and privacy/terms pages.

To preview: open index.html in a browser. To deploy on GitHub Pages, upload index.html and the entire assets folder to the repository root.
