# ResumePro — Operations Guide

## Overview

This document covers everything you need to run the service day-to-day: order workflow, email templates, revision handling, and how to scale toward $2,500–$5,000/month.

---

## Order workflow (per client)

### Step 1 — Client submits intake form
- They fill in `intake-form.html` (hosted on your domain or Carrd/Webflow)
- You receive a notification (set up email forwarding from your form tool — Tally, Typeform, or Jotform)
- Acknowledge receipt within 2 hours during business hours

### Step 2 — Process the order
1. Open `processor-tool.html` in your browser
2. Copy intake details from the form submission into the sidebar fields
3. Select the correct output mode (Resume / LinkedIn / Cover letter)
4. Click **Generate** — takes 30–60 seconds
5. Review the output + Editor's Notes
6. Spend 15–20 minutes personalizing:
   - Fix any robotic-sounding phrases
   - Verify all facts match the intake
   - Add one specific personal detail Claude missed
   - Check formatting looks clean in Google Docs

### Step 3 — Deliver
- Paste the final resume into a new Google Doc
- Set sharing to "Anyone with the link can view"
- Send the delivery email (template below)
- Log the order as "delivered" in your tracker (Notion, Airtable, or a simple spreadsheet)

### Step 4 — Revision (if requested)
- Client replies to delivery email with feedback
- Open the processor tool, paste the previous output + revision notes, re-run
- Deliver revised version within 24 hours

---

## Email templates

### 1. Order confirmation (send immediately)

**Subject:** Your ResumePro order is confirmed — expect delivery in 48 hours

Hi [Name],

Got it — your order is in and I'm getting started.

Here's what to expect:
- **Delivery:** Your rewritten [resume / resume + LinkedIn] will arrive in a Google Doc within 48 hours
- **Revisions:** You have [1 / 2 / unlimited] revision(s) — just reply to this email with feedback
- **Questions:** Reply here anytime

One quick thing: if you haven't already, it helps a lot to paste in a specific job description you're targeting. If you have one handy, just reply with it.

Talk soon,
[Your name]
ResumePro

---

### 2. Delivery email

**Subject:** Your rewritten resume is ready — [Name]

Hi [Name],

Your documents are ready. Here's what I've sent:

**[Resume / Career Bundle / Job Seeker Pro]**
→ [Google Doc link]

**What I focused on:**
- Rewrote every bullet to lead with action verbs and quantified results
- Mirrored keywords from [company/role] throughout so it reads as a strong match
- Tightened the summary to position you clearly as a [target role]
[Add 1–2 specifics from the Editor's Notes]

**To request a revision:** Reply to this email with specific feedback and I'll turn it around within 24 hours.

**To download:** File → Download → PDF or Word (.docx) in Google Docs.

Good luck with your search — let me know how it goes.

[Your name]
ResumePro

---

### 3. Revision received

**Subject:** Re: Your rewritten resume is ready — [Name]

Hi [Name],

On it — I'll have the revised version back to you within 24 hours.

[Your name]

---

### 4. Check-in (send 2 weeks after delivery)

**Subject:** Quick check-in — how's the job search going?

Hi [Name],

Hope things are moving well. Just checking in — have you had any interviews since the resume went out?

If you're targeting a specific new role and want a tailored version of the resume for it, I offer that as a quick add-on ($39). Just reply if you're interested.

Either way, rooting for you.

[Your name]

---

## Pricing and payments

| Package | Price | What to use |
|---|---|---|
| Resume refresh | $79 | Gumroad or Stripe link |
| Career bundle | $149 | Gumroad or Stripe link |
| Job seeker pro | $249 | Gumroad or Stripe link |
| Rush delivery add-on | +$30 | Add to any order at checkout |
| Job-specific tailoring add-on | $39 | Upsell after delivery |

**Payment flow:** Client pays via your Gumroad or Stripe checkout link *before* you begin work. After payment, they fill in the intake form. Do not start work without confirmed payment.

---

## Tools and setup

| Tool | Purpose | Cost |
|---|---|---|
| Tally.so | Intake form hosting | Free |
| Google Docs | Document delivery | Free |
| Gumroad or Stripe | Payments | 3–5% transaction fee |
| Notion or Airtable | Order tracking | Free tier sufficient |
| Claude (claude.ai Pro) | Powers the processor tool | $20/mo |
| Loom | Async revision feedback | Free tier |

**Total monthly overhead:** ~$20–25

---

## Finding your first 10 clients

**Week 1–2: Free (community)**
- Post on r/resumes — offer 3 free critiques publicly, mention you do paid rewrites
- Do the same on r/jobs and r/cscareerquestions
- Post a LinkedIn article: "5 resume mistakes that cost you interviews" — add your intake link at the end

**Week 2–4: Fiverr / Upwork**
- Create a Fiverr gig: "I will professionally rewrite your resume for ATS and hiring managers"
- Use before/after examples in your gig images
- Set starting price at $49 to get first 5 reviews, then raise to $79

**Month 2+: Partnerships**
- Email 10 local coding bootcamps offering 20% referral commissions
- Reach out to university career centers with a student discount ($59 for students)
- Find LinkedIn coaches and offer white-label or referral partnerships

---

## Math to $2,500/month

| Target | Orders needed | Notes |
|---|---|---|
| $2,500/mo | 17 Career Bundles ($149) | ~4 per week |
| $2,500/mo | 32 Resume Refreshes ($79) | ~8 per week |
| $5,000/mo | 34 Career Bundles | ~8 per week |

**Time per order (once systematized):**
- Intake review: 2 min
- Running processor tool: 2 min
- Human review + polish: 15–20 min
- Delivery email: 3 min
- **Total: ~25 min per order**

At 17 orders/month, that's roughly 7 hours of actual work. The rest of your time goes to client communication and finding new clients.

---

## Scaling beyond $2,500/month

When volume exceeds what you can handle alone:
1. **Hire a VA** to handle intake processing and first-pass reviews ($10–15/hr on Upwork)
2. **Build a Notion SOP** so the VA can run the processor tool independently
3. **Raise prices** — at 30+ orders/month with strong reviews, $179/$249/$349 is defensible
4. **Add LinkedIn coaching calls** as a premium tier ($350–500 for async review + 30-min call)

---

## Notes on quality

The processor tool produces 80–85% of the final output. Your 15–20 minute review is what separates a generic AI output from a professional deliverable clients pay for and refer others to.

The single highest-leverage thing you can do during review: **add one specific, personal detail that Claude couldn't infer from the intake**. This makes the resume feel human and tailored, not templated.

Always send the "What I focused on" bullet points in the delivery email. Clients who understand why their resume was changed rarely ask for revisions and are much more likely to refer friends.
