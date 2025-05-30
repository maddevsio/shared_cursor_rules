Configure a strict Content Security Policy (CSP) for the project:
- Define CSP headers to control sources for scripts, styles, images, fonts, and other resources.
- Ensure CSP works seamlessly with external resources and inline scripts/styles if necessary. 
- Ensure CSP takes values from .env that override default settings 
- Implement CSP either via HTTP headers (e.g., in server config or framework middleware) or via meta tags in the HTML.
