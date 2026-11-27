<!--
Maintained by hand for the GitHub repository page. The site (https://effectdrop.com) is the source of truth
for effects, prices and limits; update this file when those change.
-->

# EffectDrop — AI Effect Videos From One Photo

[![Website](https://img.shields.io/badge/Website-effectdrop.com-0ea5e9)](https://effectdrop.com)
[![Effects](https://img.shields.io/badge/Effects-3-6b675e)](https://effectdrop.com/#effects)
[![Languages](https://img.shields.io/badge/Languages-English%20%2F%20Chinese-10b981)](https://effectdrop.com/zh)

**EffectDrop** (also called EffectDrop AI) turns a photo into a short AI effect video that follows a trending meme's shots and timing. Pick an effect, add one or two photos, choose the quality, and get an MP4. No filming, no prompt, no editing.

- **Website**: https://effectdrop.com
- **Effects**: https://effectdrop.com/#effects
- **Pricing**: https://effectdrop.com/pricing
- **Blog / trend guides**: https://effectdrop.com/blog
- **Chinese site**: https://effectdrop.com/zh
- **Community**: [Discord](https://discord.gg/AdThZJjVxN) · [Reddit](https://www.reddit.com/r/EffectDropAI/)
- **Contact**: support@effectdrop.com

---

## Effects

| Effect | Input | Output | Page |
| --- | --- | --- | --- |
| **Tiny Desk AI** | 1 photo | 15 s · 9:16 | https://effectdrop.com/tiny-desk-ai |
| **Hotel Lobby AI** | 2 photos | 5–15 s · 16:9 or 9:16 | https://effectdrop.com/hotel-lobby-ai |
| **Dime Dime Baby AI** | 1 photo | 10 s · 16:9 | https://effectdrop.com/dime-dime-baby-ai |

Hotel Lobby and Dime Dime Baby also have Chinese pages (`/zh/hotel-lobby-ai`, `/zh/dime-dime-baby-ai`). Tiny Desk is English only.

Each effect page has its own studio, real example clips and an explanation of the trend, so you can see the result before spending credits.

---

## How it works

1. **Pick an effect.** Every effect has its own page with examples, the studio and the trend explained.
2. **Add your photo.** One clear photo of one person, or one per person for a two-person effect. There is no prompt to write.
3. **Choose the quality.** Pick the model, resolution and length (5, 10 or 15 s where the effect offers it). The credit price updates on the Generate button before you start.
4. **Generate.** The video follows the trend's shots and timing; an automated safety review runs before delivery.
5. **Download the MP4.** Leave an email and you get a notification when it is ready.

---

## What you get

- **A browser studio** — nothing to install, no editing timeline to learn.
- **Real examples** for each effect, made from photos rather than filmed footage.
- **Quality controls** — model, resolution and length, with the price shown before you commit.
- **Credits** — one-time packs or monthly / yearly plans.
- **Email notification** when a generation finishes.
- **A private library** — finished videos are visible only in your account.
- **Trend guides** — blog posts that explain the meme, the song and the CapCut-template alternatives.

---

## Pricing

All videos are paid with credits; there are no free credits. The exact price for the selected model, resolution and length is shown on the Generate button before you start.

**One-time packs**

| Pack | Price (USD) | Credits |
| --- | --- | --- |
| Single | $9.90 | 15 |
| Creator Pack | $29.90 | 50 |
| Crew Pack | $59.90 | 110 |
| Studio Pack | $129 | 250 |
| Label Pack | $299 | 700 |

**Subscriptions**

| Plan | Monthly | Yearly | Credits |
| --- | --- | --- | --- |
| Basic | $29.90/mo | $299/yr | 60/mo (720/yr) |
| Pro | $49.90/mo | $499/yr | 120/mo (1,440/yr) |
| Studio | $99.90/mo | $999/yr | 300/mo (3,600/yr) |

Prices are in USD and may change. **https://effectdrop.com/pricing is the source of truth.** Credits are charged per video; a generation that fails before the paid step is refunded automatically. Cancel a subscription from the account page at any time.

---

## Guides and trend pages

- [Hotel Lobby CapCut template](https://effectdrop.com/blog/hotel-lobby-capcut-template)
- [Tiny Desk AI trend](https://effectdrop.com/blog/tiny-desk-ai-trend)
- [Dime Dime Baby trend](https://effectdrop.com/blog/dime-dime-baby-trend)
- [November AI video trends](https://effectdrop.com/blog/ai-video-trends)
- [All guides (English)](https://effectdrop.com/blog) · [Chinese guides](https://effectdrop.com/zh/blog)
- [Spanish guide: Dime Dime Baby](https://effectdrop.com/es/blog/dime-dime-baby)

---

## Privacy and safety

- **Photos are used only for the video you start.** They are deleted when the job is done — at most 7 days for a job that needs a manual check.
- **Photos are never used to train AI models.**
- **Videos are private to your account.** Download links are unguessable and can be revoked.
- **A safety review runs before delivery.** Flagged videos fail and the credits are refunded.
- **Payments** are handled by our Merchant of Record; see the [Terms of Service](https://effectdrop.com/terms-of-service).
- **Analytics** record categories, never photo content or personal data.

Only upload photos you have the right to use. Do not upload celebrities, public figures or children.

---

## Technology

- **Frontend / server**: TanStack Start (React SSR) + Vite, deployed on Cloudflare Workers.
- **Data**: Cloudflare D1 for accounts, sessions, credits and job records; Cloudflare R2 for generated media.
- **Auth**: Better Auth — email/password and Google sign-in; email verification is offered but not required.
- **Email**: Resend for verification, password reset, generation-ready and support notifications.
- **Payments**: hosted checkout with credit packs and subscriptions; webhook-driven credit grants.
- **Analytics**: Plausible and consent-based GA4; first-touch attribution is stored with each checkout.
- **Accounts (optional)**: a guest can try the studio; signing in merges guest credits into the account.

---

## FAQ

**What is EffectDrop?**
EffectDrop is an AI effect-video generator. You pick a trending effect, add a photo and get a short video that follows the trend's shots and timing — no filming, prompts or editing.

**Is it free?**
No. Every effect is paid with credits, and there are no free credits. The price of your selection is shown on the Generate button before you start.

**What photo should I upload?**
One clear, front-facing photo of one person; two-person effects take one photo per person. Avoid group photos, heavy filters, sunglasses or photos where the face is small.

**How long are the videos?**
5–15 seconds depending on the effect (Hotel Lobby 5–15 s, Dime Dime Baby 10 s, Tiny Desk 15 s), at the resolution you choose.

**What do I get?**
An MP4 you can download and post, plus a private copy in your account. Notification email is optional.

**Can I use someone else's photo?**
Only with their permission. Do not upload celebrities, public figures or children.

**What languages does the site support?**
English and Chinese (`/zh/*`), plus one Spanish guide at `/es/blog/dime-dime-baby`.

**What is the refund policy?**
See https://effectdrop.com/refund-policy. Failed generations before the paid step are refunded automatically; other cases are handled through support.

---

<!--
Suggested GitHub repository settings (not rendered):

Description:
Turn one photo into a trending AI effect video. Pick an effect, add your photo, get an MP4.

Topics:
ai-video, ai-video-generator, image-to-video, ai-effects, video-generation, tiktok-trends, hotel-lobby-ai, tiny-desk-ai, dime-dime-baby, cloudflare-workers, tanstack-start
-->
