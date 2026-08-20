# Cathy's Care — Founding-Waitlist Landing Page

**The $100k Part-Time Care Business Plan · Your Complete Step-by-Step Journey**

A single-page marketing site for the **Cathy's Care** course — built to *prove demand* for a new online course before we invest in full production, and to build a warm list of founding customers.

> Hosted live at: **https://cathymacf.github.io/Cathy_Macfarlane-/** (GitHub Pages)
> Landing page source: `index.html` · This document: `README.md`

---

## 1. What this is

This is the **founding-waitlist landing page** for an online course teaching women — mostly in rural/regional Australia — how to launch a profitable, part-time, **non-clinical** support business in the NDIS and Support at Home (aged care) sectors. The course business is **Cathy's Care** (ASIC-registered), the product name is *"Cathy's Care: The $100k Part-Time Care Business Plan."*

The page is deliberately **honest and warm, not salesy** — matching the course's brand and audience. It asks visitors to join a **founding waitlist** (email + first name) for early, discounted access.

---

## 2. Why this page exists — the business case

We are building the course **only if the market will pay for it.** This page is the demand-validation vehicle. Its job is to answer one question with evidence:

> **Will enough of our target audience hand over money (or commit to a waitlist) before we build the full product?**

### Why validate demand first
- The full course is **43 videos** plus a **59-resource library**. Producing it is a large time and cost investment.
- A poll, survey, or "great idea!" feedback is **not proof** — people say yes for free and don't pay. The only honest signals are **emails on a waitlist** and **paid founding seats / deposits**.
- By collecting **commitments before production**, we de-risk the project: strong signal → build to meet demand; weak signal → learn *why* (price, messaging, audience) before sinking more in.

### The opportunity (why we expect demand)
- **Ageing population, staying home longer** — demand for in-home support is structural and growing for decades.
- **Two growing, government-funded sectors** — the **NDIS** (disability) and **Support at Home** (aged care). Government funding gives **continuity** that most businesses don't have.
- **Worker shortage** — the care workforce is one of the most in-demand in the country.
- **Service-gap structural opportunity** — the big care providers are everywhere, but they run on rosters and rotation; clients see a different face each week. What people actually want is one consistent, local, reliable person they can trust in their home. An independent local provider brings that — and clients and families are eager to pay for it. *"The big providers are everywhere, but people are searching for someone consistent, local, and reliable."*
- **Future-proof, human, non-offshorable** — you can't automate sitting with someone or offshore a helping hand.
- **Low barrier to entry** — no clinical qualifications needed to start non-clinical; the "university of life" (years of caring for family) is the real qualification.

### Target market
- Warm, caring women — mums, carers, and those with a big heart — most in **rural/regional Australia**.
- Often with real life experience caring for a loved one, but no business skills or formal care qualifications.
- Wanting meaningful, well-paid, part-time work that **fits around family**, without a boss or a large investment.

### Revenue model (the course product)
- **Course price:** ~$997 one-time (launch special ~$897, or 3 × ~$333). 14–30 day refund.
- **Tier 2 membership** (ongoing): confirmed as a "goer" — recurring monthly revenue (~$29–49/mo).
- **Affiliate income** (disclosed honestly): MYOB (invoicing), a trusted RTO (Cert III), an insurer.
- **Founding group** is the validation offer: discounted founding price + a real say in shaping the course, in exchange for early, honest commitment.

### Success targets for validation
- **Waitlist:** 25–50+ organic email signups (from Cathy's own network + local community groups) indicates real pull.
- **Paid founding seats / deposits:** 10–15+ indicates willingness to actually pay.
- These are the gates that decide whether to commit to full production.

---

## 3. What's on the page (sections)

1. **Hero** — value promise + primary CTA. "Build a $100k part-time care business that fits around your family."
2. **"Is this you?"** — the six personas (mum, carer, in the country, ready for more, no clinical skills, honest work).
3. **The honest promise** — real money teaching with verified numbers (e.g. $58–73/hr as your own business vs ~$35–40 as an employee; gross, not take-home).
4. **Founder story** — Cathy's real journey (regional Tasmania, caring for her mum, "university of life").
5. **How the founding group works** — join → founding access → learn & shape it.
6. **Waitlist form** — captures email + first name.
7. **FAQ** — honest answers to the common objections.
8. **Footer** — socials (Facebook, Instagram), cathys.care, and the legal disclaimer.

### Deliberate design choice: we do NOT give away the toolkit
The course's **59-resource library** is the paid product's value. The page deliberately frames the toolkit as **drip-fed within the paid course** ("new tools unlocked as you progress"), and the only free lead magnet is a **short training video + a spot in line** — so nobody can grab everything of value and leave. This protects the paid product's worth.

---

## 4. How to run / deploy

### Local preview
```bash
# from this directory
python3 -m http.server 8000
# open http://localhost:8000
```

### Deploy (GitHub Pages — already enabled)
The repo is configured for **GitHub Pages** from the `main` branch root. Pushing to `main` updates the live site automatically:
```bash
git add -A && git commit -m "update" && git push origin main
```
Live URL: `https://cathymacf.github.io/Cathy_Macfarlane-/`

### Connecting the form (to-do before launch)
The waitlist form currently shows a client-side thank-you. To actually **collect emails**, connect it to a form/email service (e.g. Formspree, a Google Form, or a mail provider) by replacing the placeholder `action`/submit handler in `index.html`.

---

## 5. Roadmap / next steps

- [ ] Connect the waitlist form to capture emails for real
- [ ] Drive traffic: Cathy's own network + 2–3 local Facebook community groups
- [ ] Conduct the 5 founder interviews to refine offer & messaging
- [ ] Hit the validation targets (waitlist + paid founding seats) → commit to full production
- [ ] Build out the course module by module (drip to founders)
- [ ] Enable the full course on the platform (cathys.care)

---

## 6. Disclaimer

Information on this page is general in nature and **not** financial, legal, or tax advice. Figures (e.g. rates) change — always verify the current official information with the **NDIS**, **My Aged Care** and the **ATO**, and see your accountant. This is not an offer of clinical services.

---

*© Cathy's Care · A real business, built with care. · Founder: Cathy Macfarlane*
