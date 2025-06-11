DNS-over-HTTPS Proxy on Cloudflare Pages
A minimalist DNS-over-HTTPS (DoH) proxy built to run effortlessly on Cloudflare Pages.

🚀 Quick Start
Clone this Repository

Fork or clone this repo to your own GitHub account.
Deploy to Cloudflare Pages

Sign up for a free Cloudflare Pages account.
Create a new project and connect it to your cloned GitHub repository.
Deploy your project with the default settings.
Customize Your DoH Endpoint

You can change the doh variable in index.js to any DNS-over-HTTPS server.
Confirmed to work with Cloudflare and Google DNS.
💡 Why Use This?
Bypass ISP Blocks: If ISPs start blocking known DoH providers, run your own proxy.
Custom Domain Support: Use your own domain (Cloudflare or any other provider) to further evade censorship.
Minimal Setup: Deploy in minutes—no server management required.
🔗 Related Projects
Based on doh-cf-workers.
Note: The Workers version doesn’t require a GitHub account, but custom domain support is only available with Cloudflare.
📝 License
MIT License
