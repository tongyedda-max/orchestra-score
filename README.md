# 🎼 Orchestra Stand

> A free digital music stand for amateur orchestras and school ensembles.
> Put your sheet music in the cloud, scan a QR code, and every member reads on
> their phone, tablet, or laptop. Section leaders draw bowings right on the
> score — everyone sees them instantly. One person turns pages, everyone follows.

**🆓 Open source (non-commercial license) · Free backend (Supabase Free Tier) · Free hosting (GitHub Pages) · $0/month**

---

**Why password-based roles instead of user accounts?** Orchestras are small and
trust-based. Three shared passwords keep the UX frictionless — no sign-ups, no
email verification, works instantly on any device — while every write goes
through a `SECURITY DEFINER` RPC that validates the password server-side, and
RLS keeps all tables read-only for the public.

---

## 🔒 Security Notes

- The anon key in the HTML is **public by design** (that's how Supabase
  client-side apps work); security comes from RLS + password-checked RPCs.
- Never put a password in your display name — the app blocks names that
  contain a password.
- For sensitive material, note that the PDF storage bucket is publicly
  readable by URL; gate access to the site itself, not the file URLs.

---

## 📜 License — Open Source, Non-Commercial

This project is **open source** and free for the community, under the
**Orchestra Stand Non-Commercial License v1.0** (in the spirit of
[PolyForm Noncommercial 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/)):

- ✅ **You MAY** freely use, copy, modify, merge, and redistribute this project
  for any **non-commercial** purpose — your orchestra, school, community
  ensemble, personal study, teaching, or a fork for your own group.
- ✅ Modifications and forks are welcome and encouraged. Please keep this
  license notice and credit in your copy.
- ❌ **Commercial use is PROHIBITED.** You may not sell this software, offer it
  as a paid hosted service, bundle it into a paid product or subscription, or
  otherwise use it to generate revenue — directly or indirectly.
- 🙏 Attribution is appreciated: a link back to this repository in your fork's
  README is enough.

> **The short version:** share it, remix it, use it with your ensemble — just
> don't charge money for it.

Copyright (c) 2026 — released for the global community orchestra movement. 🎻
> gh repo clone tongyedda-max/orchestra-score






# orchestra-score
-> If you see this page, it means someone is editing the website. 
-> Just come here later, thanks (maybe go practice first?)

-> this website link:
https://tongyedda-max.github.io/orchestra-score/
