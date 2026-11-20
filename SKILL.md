---
name: upwork-freelancer-playbook
description: Write and check a freelancer's Upwork work: job vetting, proposals, profile, portfolio, Project Catalog, consultations and boost messages, within Upwork's rules and limits.
---

<div align="center">

# 🧭 Upwork Freelancer Playbook

**Write it right. Keep it within the rules. Keep it true.**

Job vetting · Proposals · Profile · Portfolio · Project Catalog · Consultations · Boost messages

</div>

> **For the AI reading this:** follow this playbook whenever the user asks for help with Upwork. Apply the hard rules first, check every limited field with code or a careful count, and never invent facts about the user. If section 8 is not filled in, ask the user for those facts before writing proposals or listings.

Use this for any Upwork task: deciding whether to apply to a job, writing a proposal, editing the profile, adding a portfolio item, building a Project Catalog listing or consultation, or writing a boost message. Every field must be **paste-ready, within Upwork's limits, and true.**

## Contents

1. [Hard rules](#1-hard-rules)
2. [Field limits](#2-field-limits)
3. [Connects and job vetting](#3-connects-and-job-vetting)
4. [Proposal workflow](#4-proposal-workflow)
5. [Profile workflow](#5-profile-workflow)
6. [How clients evaluate freelancers](#6-how-clients-evaluate-freelancers)
7. [Portfolio, Project Catalog, consultations, boost](#7-portfolio-project-catalog-consultations-boost)
8. [Your positioning and proof (template)](#8-your-positioning-and-proof-template)
9. [Output style](#9-output-style)
10. [Sources](#sources)

---

## 1. Hard rules

> [!IMPORTANT]
> Check these first, every time.

### 🚫 Stay on Upwork before a contract

Upwork requires all pre-contract talk (scope, price, deadlines, skills, payment terms) to happen in **Upwork Messages or Upwork video calls**. Suggesting contact outside Upwork breaks the Terms of Service.

- Do not email, phone, text or LinkedIn-pitch a client about a job they posted on Upwork.
- Do not search for a client's personal email, phone or social accounts to reach them off-platform. Decline and offer the Upwork proposal instead.
- If someone insists on a LinkedIn connection, it may only be a plain networking note: no mention of the job, Upwork, price or scope. Any reply about the job goes back to Upwork.

### ✅ Everything else

| # | Rule | What it means |
|---|------|---------------|
| 2 | **No contact or payment details** | Not in the profile, proposals, catalog titles, tiers, add-ons, descriptions, steps, FAQ, requirements, images or boost messages. Upwork reviews all of these. |
| 3 | **Accuracy** | Only claim what is true and provable. No inflated numbers, fake reviews or "guaranteed rankings". Never say a tool does something it does not (for example, an AI tool "connects to the client's account" without a real connection). |
| 4 | **Client privacy** | No client names, domains, logos or identifying screenshots unless the client allowed it. Describe work by type ("a seasonal home-services company with multiple locations"). |
| 5 | **Exact quotes stay exact** | Copy a review verbatim, typos included, with the correct month. |
| 6 | **Count characters with code** | Run a short Python `len()` check on every limited field and show the count in brackets. |

---

## 2. Field limits

> [!NOTE]
> Always trust the live form counter. It overrides everything below.

| Field | Limit | Source |
|---|---|---|
| Profile title | 70 chars | widely reported |
| Profile overview | 5,000 chars | widely reported |
| Skills shown | up to 20 (order matters, the first ones weigh most) | observed |
| Portfolio title | 40-70 (sources conflict, use 40-60 to be safe) | third-party |
| Portfolio description | 300-600 (sources conflict, aim for 300) | third-party |
| Portfolio image alt text | under 140 chars | observed in form |
| Project Catalog title | 75 chars, min 7 words. Some sources say the fixed "You will get" prefix counts toward 75, so check the counter | third-party + form |
| Catalog search tags | max 5, chosen from Upwork's fixed list | form |
| Catalog tier title / description | 30 / 80 chars | form |
| Catalog project summary | 120 min, 1,200 max | form |
| Catalog requirement | 10 min, 250 max each, at least 1 | form |
| Catalog step | title 3-75, description up to 250 | form |
| Catalog FAQ | up to 5 questions, keep answers under 250 | form |
| Catalog gallery | 4:3, export 1200x900 | observed |
| Consultation requirements | up to 250 chars each | observed |
| Boost message ("write a message to boost") | 500 chars including subject and body | observed |

**Tags:** fields only accept items from Upwork's list. If a term is missing (for example, a newer product name), use the nearest real tag. Avoid developer-only tags and outdated version names; prefer the plain brand name.

---

## 3. Connects and job vetting

- Connects cost about **$0.15 each**. Each job shows its own Connects price before you apply.
- Boosting is an optional extra bid. Only the extra bid can be refunded, and only if you do not win a boosted slot and the client never engages.

### Vetting checklist

Before recommending "apply", check:

- [ ] Payment method verified
- [ ] Hire rate, total spend, average hourly paid
- [ ] Reviews, and how other freelancers rated the client
- [ ] Job age, proposals count, interviews and invites
- [ ] Budget matches the scope

### Judgement calls

- **New client** (joined days ago, 0% hire rate): modest risk, not a reason to skip if payment is verified and they are active.
- **Budget too low for the scope:** say so, and offer two routes: trim the scope to the budget, or keep the scope and propose a higher fixed price with the same milestones.
- **Skip or flag:** work outside your offered services (section 8), "test tasks" that are free real work, and anything asking to move off Upwork.

---

## 4. Proposal workflow

1. Read the full job post and answer every question the client listed, in their order.
2. Open with the client's problem in one line, then proof (a matching result with numbers, no client name).
3. Give a short, concrete plan (3-5 steps or milestones) that matches their scope.
4. State price and timeline clearly. If you adjust the budget, say which items change.
5. End with one easy question that invites a reply.
6. Default to short, plain, American-style English (150-250 words) unless the client asks for detail. Use the client's first name if it appears on the job.
7. Mention AI honestly: *"I use an AI assistant for fast analysis and review every finding by hand."*

---

## 5. Profile workflow

| Part | Guidance |
|---|---|
| **Title** (max 70) | Lead with the main searchable role, then 2-3 high-value keywords. Pattern: `[Main Role] & [Second Role] \| [Keyword], [Keyword]` |
| **Overview** (max 5,000) | The first 2 lines matter most (shown in search). Structure that worked: one-line positioning → proof (results, contracts, reviews) → one section per service you sell → How I use AI → How I work → FAQ with real search questions |
| **Countries** | Decide deliberately. A global profile should not name specific countries |
| **Job Success Score** | Leave it out unless the number is current |
| **Testing** | After a profile change, wait 10-14 days and compare MyStats (views, clicks, invites) before changing again |

---

## 6. How clients evaluate freelancers

> Use this when optimizing the profile and proposals. Based on Upwork's official client-side "hire-on-upwork" skill.

1. **Work history outranks the cover letter.** Cover letters and screening answers are treated as self-reported. Competence is judged from past contracts, reviews and job stats. Keep portfolio items, contract titles and reviews matching the services you want to win, and link proposals to matching past work.
2. **Screening answers are compared side by side.** Clients are shown which question separated applicants. Answer each with your own specifics (numbers, approach), never generic text.
3. **Boosted proposals are flagged as paid placement,** not fit. Boosting gets you seen; substance still decides.
4. **Length and polish are not ranking signals,** and clients are told not to guess whether AI wrote a proposal. Short and specific beats long and fancy.
5. **The "Invite freelancers" list is ranked by match to the job.** Title, skills and overview keywords feed that match.
6. **Clients usually message before hiring.** Reply fast and clearly in Upwork Messages, and keep video calls on Upwork.
7. **Paid signals** (boost, Available Now badge) are not evidence of quality. They don't replace a strong profile.

### 🔍 Profile audit lens

For every profile change, ask which of three things it improves:

| Lever | Question |
|---|---|
| **Match** | Does it add the keywords clients search for? |
| **Proof** | Does it strengthen work history, reviews or portfolio? |
| **Conversation** | Does it make the first reply clear and quick? |

---

## 7. Portfolio, Project Catalog, consultations, boost

### 🖼️ Portfolio item

- Title with the outcome, plus your role.
- Short description: problem → work → result.
- Images in 4:3 (1200x900), with SEO-friendly kebab-case file names (keyword + outcome).
- Alt text under 140 chars that includes the growth number.
- Never edit client screenshots except cropping out identifying details, and say when you cropped.

### 📦 Project Catalog listing (in the order of the form)

| Step | Field | Guidance |
|---|---|---|
| 1 | Title | Outcome + main keywords + differentiator |
| 2 | Category | The specific subcategory that matches the full service. Not the most crowded one, not an unrelated one |
| 3 | Tags | 5, from the list |
| 4 | Three tiers | Title, description, delivery days, revisions, service options, price. With no catalog reviews yet, price the entry tier near the market's entry prices and check competing listings first |
| 5 | Add-ons | Extra page, extra deliverables, rush |
| 6 | Requirements | Only the first required before starting, so buyers don't drop off |
| 7 | Steps | 5 clear steps, for example: access → analysis → priority plan → implement → handoff |
| 8 | Summary and FAQ | Summary 120-1,200. FAQ (5): key terms explained, how AI is used, no guarantees, access needed, what's not included |
| 9 | Gallery | Your own photo on the cover, then 5 funnel images (problem, what you get, how it works, proof, packages). Add text yourself, no competitor logos, no clickbait, low text density |

> [!WARNING]
> Upwork reviews quality, accuracy, contact info and allowed categories. Editing the category after approval takes the listing offline while it is re-reviewed.

### 🗓️ Consultation

30 or 60 minutes, a price per session, a delivery document (a meeting summary), a notice period and future-booking limit, availability in your own time zone, up to 3 requirements and 5 FAQs.

### 📣 Boost message (500 chars)

Subject with the main proof (for example, "Your service + your strongest result"), short intro, one proof line, an "I can help with:" list, one offer line. No contact info. Check the auto-signature spelling.

---

## 8. Your positioning and proof (template)

Fill this in with your own true facts. Every proposal and listing draws from it.

- [ ] **Badge, years of experience, time on Upwork** (they can differ; state both accurately)
- [ ] **Services you offer**, and services you deliberately do not offer, so proposals stay on-brand
- [ ] **One honest AI statement:** which tools you use, for what, and that you review every change by hand
- [ ] **Proof:** 2-3 results with numbers and no client names. Contract titles can be mentioned, client identities cannot. Always add "results vary"

---

## 9. Output style

- Give each field as a **paste-ready block with its character count.**
- Give a clear recommendation first, then 1-2 alternatives.
- Separate what was **researched** from what is an **estimate** (for example, catalog prices beyond the visible "From" price are estimates).
- Keep explanations short. Fields are pasted one at a time.

---

## Sources

- [Upwork Help: Get to know each other before a contract](https://support.upwork.com/hc/en-us/articles/17995658941843--Get-to-know-each-other-before-a-contract)
- [Upwork Help: How We Review Your Project Catalog Project](https://support.upwork.com/hc/en-us/articles/4408644453395-How-We-Review-Your-Project-Catalog-Project)
- [Upwork Help: Boost your proposal](https://support.upwork.com/hc/en-us/articles/4406395531795-Boost-your-proposal)
- [Upwork Connects explained 2026](https://upcat.app/upwork-connects-explained/) (third-party)
- [Upwork portfolio and catalog character limits](https://snipework.com/blog/upwork-portfolio-character-limit) (third-party)
