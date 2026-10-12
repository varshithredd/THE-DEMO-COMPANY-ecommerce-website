# The Demo Company — E-commerce Website

A static storefront interface built with HTML, CSS, Bootstrap 4.5.3, and Font Awesome. The pages illustrate product browsing and a checkout interface.

## Pages

| Page | Purpose |
| --- | --- |
| `index.html` | Storefront home |
| `product.html` / `product_detail.html` | Product listing and details |
| `category.html` | Category browsing |
| `search.html` | Search interface |
| `cart.html` | Shopping cart interface |
| `checkout.html` / `order_confirmation.html` | Checkout and confirmation screens |
| `about.html` / `contact.html` | Company information and contact interface |

## Preview locally

```bash
git clone https://github.com/varshithredd/THE-DEMO-COMPANY-ecommerce-website.git
cd THE-DEMO-COMPANY-ecommerce-website
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. Internet access is required for the CDN-hosted libraries.

## Current limitations

The home page references stylesheet and image files under `../assets/`, but that directory is absent from the repository root listing. Some styling and images may therefore be missing in a local preview.

This repository presents frontend screens. A working payment service, backend order processing, and persistent cart are not established by the reviewed files.

## Development opportunities

Add the missing assets, align stylesheet paths with the repository structure, replace placeholder content, and document any implemented interactive behavior.
