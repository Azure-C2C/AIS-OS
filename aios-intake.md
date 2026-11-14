# AIS-OS Intake

This is the source-of-truth file for your AIOS. Fill it in by typing, voice-pasting (Wispr Flow / OS dictation), or running `/onboard` for a guided conversation. Whichever mode, this file is what `/onboard` reads to scaffold your Day-1 setup.

**Hard cap: 7 questions.** Each answerable in under 60 seconds. Don't overthink — you can edit and re-run `/onboard` any time.

---

## Q1 — Who are you, what do you sell, who do you sell it to?

Identity, offer, ICP. One paragraph each is fine.

```
CONFIRMED 2026-11-14 (offer details from claude/holiday-2026-plan.md):
- Who: Wulan, owner of Angel Coffee Company (angelcoffeecompany.co). This AIOS is Wulan's
  (operator = Wulan; set up with help from Brian, C2C Strategy). Drafts speak in Wulan's voice.
- Offer: online coffee shop on Shopify. 74 products. Hero items: three $26.99 sample packs,
  holiday flavors (Pecan Pie, Turtle), Wulan's Favorites. Free shipping on every order.
- ICP: People who love coffee and use it to connect with others and explore cultures
  through coffee. Ideally people who love to share their coffee with others. US-based for
  now, any US region, no age limit. Everyone from coffee connoisseurs to coffee novices.
```

---

## Q2 — Paste 1-2 things you've written recently. Don't edit them.

An email, a LinkedIn post, a DM, a doc — anything that sounds like you when you're not trying. **Paste verbatim.** Do not type these mid-conversation with Claude — chat-shaped samples are worse than no samples (voice contamination).

```
My name is Mentari Tri Wulansari, but I am known as Wulan.
My parents gave me a name shaped by meaning and care: Mentari, the sun; Tri, three—balance and continuity; Wulan, the moon; and Sari, beauty and essence. I carry light and calm, day and night, movement and pause.
```

```
Coffee, in Indonesian culture, lives in that same rhythm.
In Indonesia, coffee is not something you rush. It is an invitation. When someone says “Mari minum kopi”—let’s have coffee—they are not offering only a drink. They are offering time, attention, and presence. In homes, roadside warung kopi, and village kitchens, coffee marks the moment when strangers become guests, and guests become friends. A cup of coffee is permission to sit, to talk, and to stay a little longer.
```
(Samples 1 and 2 are consecutive parts of the same piece, pasted 2026-11-14.)

---

## Q3 — What are your 2-3 biggest priorities for the next 90 days?

Quarterly priorities. Not yearly aspirations. Things that, if not done by July, would make you say "I wasted Q2."

```
1. Reach 1,000 Instagram followers (@angelcoffeecompany) by Feb 15, 2027.
2. Reach $300/month in sales by Feb 15, 2027.
```

---

## Q4 — Where does revenue actually land, and where is it tracked?

Multiple answers OK. Stripe? Skool? GoHighLevel? QuickBooks? A spreadsheet?

```
CONFIRMED 2026-11-14: Shopify only (Basic plan, admin handle wuuangel). Revenue lands and is
tracked in Shopify. 27 total orders to date; last order Oct 29, 2026.
```

---

## Q5 — Where do you talk to customers, your team, and the outside world day-to-day?

Email (which one — Gmail / Outlook)? Slack? Teams? DMs (Skool / Discord / iMessage)? Phone?

```
CONFIRMED 2026-11-14:
- Main channels: Instagram (@angelcoffeecompany) and Facebook (facebook.com/angelcoffeecompany).
- Email: Outlook. Customer marketing emails via Shopify Email (14 past buyers).
- Friends/personal network: WhatsApp and social media.
- Word of mouth is a major channel.
- Calendar (inferred from Outlook): Outlook Calendar [confirm at scaffold].
```

---

## Q6 — Where do meeting recordings, notes, and important docs live?

Granola? Otter? Fireflies? Google Drive? Notion? Dropbox? A folder on your desktop you keep meaning to organize?

```
CONFIRMED 2026-11-14: OneDrive (documents, notes, business files).
```

---

## Q7 — What's the one task that eats your week, and where do you currently track work?

The single biggest time-suck or recurring drudgery. Plus where tasks/projects live (ClickUp / Asana / Linear / Notion / a notebook).

```
CONFIRMED 2026-11-14: Top pain = creating Instagram content and making website (Shopify) updates.
Task tracking: not specified [to confirm; no formal tool named].
```

---

When this file is filled, run `/onboard` (or re-run it) and the wizard will scaffold your Day-1 file set: `context/`, `references/voice.md`, populated `connections.md`, and a filled `CLAUDE.md`.
