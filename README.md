# websaytim.uz

Websaytim veb-studiyasi sayti. Cloudflare Workers'da ishlaydi.

- `public/` — sayt fayllari
- `src/worker.js` — `/api/send` → Telegram bot
- Sozlamalar (Cloudflare → Settings → Variables and Secrets): `BOT_TOKEN`, `CHAT_ID`
