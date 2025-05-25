## Quick Start
### 1️⃣ Get an API key

Click the button below (Stripe test mode, use card **4242 4242 4242 4242**):

[![Buy Key](https://img.shields.io/badge/Buy%20API%20Key-£5-blue)](javascript:fetch('/create_checkout').then(r=>r.json()).then(j=>location=j.checkout_url))

### 2️⃣ Call the endpoint

```bash
curl -H "Content-Type: application/json" \
     -H "X-API-KEY: YOUR_KEY_HERE" \
     -d '{"plain_text":"Hello!"}' \
     https://zapgpt.fly.dev/parse_email
