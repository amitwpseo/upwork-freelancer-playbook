---
name: upwork-freelancer-playbook
description: Write and check a freelancer's Upwork work: job vetting, proposals, profile, portfolio, Project Catalog, consultations and boost messages, within Upwork's rules and limits.
---

# Upwork Freelancer Playbook

Use this for any Upwork task: deciding whether to apply to a job, writing a proposal, editing the profile, adding a portfolio item, building a Project Catalog listing or consultation, or writing a boost/ad message. Every field must be paste-ready, within Upwork's limits, and true.

## 1. Hard rules (check these first, every time)

1. **Stay on Upwork before a contract.** Upwork requires all pre-contract talk (scope, price, deadlines, skills, payment terms) to happen in Upwork Messages or Upwork video calls. Suggesting contact outside Upwork breaks the Terms of Service.
   - Do not email, phone, text or LinkedIn-pitch a client about a job they posted on Upwork.
   - Do not search for a client's personal email, phone or social accounts to reach them off-platform. Decline and offer the Upwork proposal instead.
   - If the user insists on a LinkedIn connection, it may only be a plain networking note: no mention of the job, Upwork, price or scope, and any reply about the job goes back to Upwork.
2. **No contact or payment details** in the profile, proposals, catalog titles, tiers, add-ons, descriptions, steps, FAQ, requirements, images or boost messages (Upwork reviews all of these for it).
3. **Accuracy.** Only claim what is true and provable. No inflated numbers, no fake reviews, no "guaranteed rankings", no claim that a tool does something it does not (for example, do not say an AI tool "connects to the client's account" unless a real connection exists).
4. **Client privacy.** No client names, domains, logos or identifying screenshots in portfolio items, catalog images or proposals unless the client allowed it. Describe work by type ("a seasonal home-services company with multiple locations").
5. **Exact quotes stay exact.** When quoting a review, copy it verbatim, typos included, with the correct month.
6. **Count characters with code, not by eye.** Run a short Python `len()` check on every limited field before giving it to the user, and show the count in brackets.

## 2. Field limits (verify against the live form counter, which always wins)

| Field | Limit | Status |
|---|---|---|
| Profile title | 70 chars | widely reported |
| Profile overview | 5,000 chars | widely reported |
| Skills shown | up to 20 (order matters, first ones weigh most) | observed |
| Portfolio title | 40-70 (sources conflict, use 40-60 to be safe) | third-party |
| Portfolio description | 300-600 (sources conflict, aim for 300) | third-party |
| Portfolio image alt text | under 140 chars | observed in form |
| Project Catalog title | 75 chars, min 7 words; some sources say the fixed "You will get" prefix counts toward 75, so check the counter | third-party + form |
| Catalog search tags | max 5, chosen from Upwork's fixed list | form |
| Catalog tier title / tier description | 30 / 80 chars | form |
| Catalog project summary | 120 min, 1,200 max | form |
| Catalog requirement | 10 min, 250 max each, at least 1 | form |
| Catalog step | title 3-75, description up to 250 | form |
| Catalog FAQ | up to 5 questions, keep answers under 250 | form |
| Catalog gallery | 4:3, export 1200x900 | observed |
| Consultation requirements | up to 250 chars each | observed |
| Boost / "write a message to boost" | 500 chars incl. subject + body | observed |

Tag fields only accept items from Upwork's list. If a term is missing (for example a newer product name), use the nearest real tag, avoid developer-only tags and outdated version names; prefer the plain brand name over old versions.

## 3. Connects and job vetting

- Connects cost about $0.15 each. Each job shows its own Connects price before you apply; boosting is an optional extra bid, and only the extra bid can be refunded if you do not win a boosted slot and the client never engages.
- Before recommending "apply", check: payment verified, hire rate, total spend, average hourly paid, reviews and how other freelancers rated the client, job age, proposals count, interviews/invites, and whether the budget matches the scope.
- Flag new clients (joined days ago, 0% hire rate) as modest risk, not a reason to skip if payment is verified and they are active.
- If the budget is too low for the scope, say so and offer two routes: trim the scope to the budget, or keep the scope and propose a higher fixed price with the same milestones.
- Skip or flag: jobs asking for work outside the freelancer's offered services (see section 7), "test tasks" that are real work for free, and anything asking to move off Upwork.

## 4. Proposal (cover letter) workflow

1. Read the full job post and answer every question the client listed, in their order.
2. Open with the client's problem in one line, then proof (a matching result with numbers, no client name).
3. Give a short, concrete plan (3-5 steps or milestones) that matches their scope.
4. State price and timeline clearly; if adjusting the budget, say which items change.
5. End with one easy question that invites a reply.
6. Default to short and American-style plain English (150-250 words) unless the client asks for detail. Use the client's first name if it appears on the job.
7. Mention AI honestly: "I use an AI assistant for fast analysis and review every finding by hand."

## 5. Profile workflow

- **Title (max 70):** lead with the main searchable role, then 2-3 high-value keywords. Example pattern: "[Main Role] & [Second Role] | [Keyword], [Keyword]".
- **Overview (max 5,000):** first 2 lines matter most (shown in search). Structure that worked: one-line positioning -> proof section (results, contracts, reviews) -> one section per service you sell -> How I use AI -> How I work -> FAQ with real search questions.
- Decide deliberately whether to list target countries; a global profile should not name specific ones.
- Do not use an outdated Job Success Score number; leave it out unless it is current.
- After a profile change, wait 10-14 days and compare MyStats (views, clicks, invites) before changing again.

## 5b. How clients evaluate freelancers (use this when optimizing the profile and proposals)

Source: Upwork's official client-side "hire-on-upwork" skill.

1. **Work history outranks the cover letter.** Cover letters and screening answers are treated as self-reported. Competence is judged from past contracts, reviews and job stats. Keep portfolio items, contract titles and reviews matching the services you want to win, and link proposals to matching past work.
2. **Screening answers are compared side by side.** Clients are shown which question separated applicants. Answer each question with your own specifics (numbers, approach), never generic text.
3. **Boosted proposals are flagged as paid placement**, not fit. Boosting gets seen; substance still decides.
4. **Length and polish are not ranking signals**, and clients are told not to guess whether AI wrote a proposal. Short and specific beats long and fancy.
5. **The "Invite freelancers" list is ranked by match to the job.** Title, skills and overview keywords feed that match, so profile keywords matter for invitations.
6. **Clients usually message before hiring.** Reply fast and clearly in Upwork Messages; keep video calls on Upwork.
7. **Paid signals** (boost, Available Now badge) are not evidence of quality. Do not rely on them in place of a strong profile.
8. **Profile audit lens:** for each profile change, ask: does it help the match ranking (keywords), the proof (work history, reviews, portfolio) or the conversation (clear first reply)?

## 6. Portfolio items, Project Catalog, consultations, boost

**Portfolio item:** title with the outcome, role, a short description (problem -> work -> result), skills, images in 4:3 (1200x900), SEO-friendly file names (kebab-case, keyword + outcome), alt text under 140 chars that includes the growth number. Never edit client screenshots except cropping out identifying details, and say when you cropped.

**Project Catalog listing (order of the form):**
1. Title (outcome + main keywords + differentiator).
2. Category: pick the specific subcategory that matches the full service, not the most crowded one and not an unrelated one.
3. Tags (5 from the list).
4. Three tiers: title, description, delivery days, revisions, service options, price. With no catalog reviews yet, price the entry tier near the market's entry prices and check competing listings first.
5. Add-ons (extra page, extra deliverables, rush).
6. Requirements (only the first one required before starting, so buyers don't drop off).
7. Steps (5 clear steps, for example: access -> analysis -> priority plan -> implement -> handoff).
8. Summary (120-1,200) and FAQ (5: key terms explained, how AI is used, no guarantees, access needed, what's not included).
9. Gallery: your own photo on the cover; 5 funnel images (problem, what you get, how it works, proof, packages). Add text yourself, no competitor logos, no clickbait, low text density.
Upwork reviews quality, accuracy, contact info and allowed categories; editing the category after approval takes the listing offline while it is re-reviewed.

**Consultation:** 30 or 60 min, price per session, a delivery document (Meeting summary), notice period and future-booking limit, availability in your own time zone, up to 3 requirements, 5 FAQs.

**Boost / ad message (500 chars):** subject with the main proof (for example, "Your service + your strongest result"), short intro, one proof line, "I can help with:" list, one offer line. No contact info. Check the auto-signature spelling.

## 7. Positioning and proof (fill in with your own true facts)

- Badge, years of experience and time on Upwork (they can differ; say both accurately).
- Services you offer, and services you deliberately do not offer (list them so proposals stay on-brand).
- One honest AI statement: which tools you use, for what, and that you review every change by hand.
- Proof: 2-3 results with numbers, no client names. Contract titles can be mentioned, client identities cannot. Always add "results vary".

## 8. Output style

- Give each field as a paste-ready block with its character count.
- Give a clear recommendation first, then 1-2 alternatives.
- Separate what is researched from what is an estimate (for example, catalog prices beyond the visible "From" price are estimates).
- Keep explanations short; the user pastes field by field.

## Sources

- Upwork Help: Get to know each other before a contract - https://support.upwork.com/hc/en-us/articles/17995658941843--Get-to-know-each-other-before-a-contract
- Upwork Help: How We Review Your Project Catalog Project - https://support.upwork.com/hc/en-us/articles/4408644453395-How-We-Review-Your-Project-Catalog-Project
- Upwork Help: Boost your proposal - https://support.upwork.com/hc/en-us/articles/4406395531795-Boost-your-proposal
- Upwork Connects explained 2026 (third-party) - https://upcat.app/upwork-connects-explained/
- Upwork portfolio and catalog character limits (third-party) - https://snipework.com/blog/upwork-portfolio-character-limit
