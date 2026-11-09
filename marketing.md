# THE MIT LICENSE — Marketing & Organic Adoption Strategy

**Project:** `themitlicense`  
**Organization:** https://github.com/themitlicense  
**Repository:** https://github.com/themitlicense/themitlicense.github.io  
**Founder:** Antonio Trento — https://antoniotrento.net  
**Document status:** Strategic plan / hypotheses to validate  
**Last review:** 2026-11-09

> **Free Code. Not Free Labor.**  
> **Take the code. Not the developer.**

## 1. The real objective

Create an independent, multilingual cultural movement around the responsible use of MIT-licensed software. The primary goal is **voluntary adoption of the manifesto by open-source maintainers**, especially through a recognizable link or badge in their repositories.

Secondary goal: establish Antonio Trento as the creator of a useful, widely recognized initiative, generating relevant and credible visibility for **antoniotrento.net**. The personal brand must be a consequence of the movement's value, not the apparent purpose of the movement.

**North Star Metric:** number of *distinct, independently maintained public repositories* voluntarily linking to the manifesto (measured with a reproducible methodology).

Do **not** optimize primarily for impressions, GitHub stars or page views: these can grow without actual endorsement.

## 2. Positioning: what we are and what we are not

**We are:** a voluntary, ethical statement for maintainers and users of permissively licensed software; a way to express healthy boundaries and encourage reciprocity.

**We are not:** a new MIT license, an official MIT initiative, a legal amendment, a mandatory attribution requirement, an endorsement certification, a substitute for `LICENSE`, `SUPPORT.md` or `CONTRIBUTING.md`, or an attempt to restrict commercial use.

The original MIT License allows commercial use, redistribution and modifications subject to preserving the relevant copyright and license notices. It does **not** mandate donations, upstream contributions, paid support, or public endorsements beyond its terms.

**Core distinction:** *The MIT License grants legal rights. The MIT Manifesto expresses voluntary cultural expectations.*

Name the movement clearly **The MIT Manifesto** or **Free Code. Not Free Labor.**, while retaining **themitlicense** as the GitHub organization's name. Explicitly describe the website as an independent awareness initiative, not the official MIT License website.

## 3. The adoption psychology

People will not adopt a badge to advertise Antonio Trento. They may adopt one because it helps **them**:

- State a boundary without rewriting the same explanation in every issue.
- Signal a philosophy shared by other maintainers.
- Show users a clear distinction between license rights and support expectations.
- Encourage thoughtful contributions without imposing a legal obligation.
- Save time by linking to a single, concise explanation when unreasonable demands recur.

**Value proposition for the maintainer:** “One line in your README. One clear message about your time.”

**Value proposition for users:** “Know what the license gives you, and what respectful collaboration looks like.”

**Reasons not to adopt:** the message feels hostile; appears to rewrite MIT terms; badge feels like an advertisement; unclear relationship with the official license; adds clutter; generates no practical value. Every communication decision should reduce these objections.

## 4. The viral loop (hypothesis, not a guarantee)

1. A maintainer encounters a sharp statement or a badge on another repository.
2. They read the brief manifesto and recognize a problem they have experienced.
3. They copy a small snippet into their own README, **without changing the MIT license**.
4. Their repository becomes another voluntary discovery point.
5. Other maintainers see the badge and decide independently whether to adopt it.
6. A portion explore the movement, share it, contribute translations or publish their own experience.
7. Some discover the founder and visit antoniotrento.net.

The loop only becomes self-sustaining if each adoption produces enough new relevant exposure and enough of that exposure converts to further adoption. This must be measured; it cannot be assumed from GitHub's scale.

## 5. Adoption assets, in order of priority

### A. The main badge — the flagship

Recommended copy:

**`MIT Licensed · Maintainer Time Not Included`**

Alternative A/B hypotheses:

- `Free Code · Not Free Labor`
- `MIT Manifesto · Respect Maintainers`
- `Open Source · Not Free Support`

The first should explicitly distinguish the software's MIT license from the statement about maintainer time; the others are movement-oriented. Avoid wording such as “MIT License requires supporting the author”, “MIT certified” or “Official MIT”.

Show a copy-ready example **only when the actual manifesto URL exists**; the final destination should be the manifesto page, not the founder's personal site.

Illustrative Markdown, with the target link to be confirmed when published:

```md
[![Free Code. Not Free Labor.](https://img.shields.io/badge/Free%20Code-Not%20Free%20Labor-555)](https://themitlicense.github.io/)
```

This is a *proposed* static badge snippet, not proof that the website is online or that an endorsement has occurred. Validate appearance, legibility, accessible text and the destination before publishing.

### B. A one-paragraph README statement

Some maintainers dislike badges. Offer a neutral alternative:

> This project is MIT-licensed. You are free to use it under the license terms. Support, customization and ongoing maintenance are not guaranteed or included. We support the independent [MIT Manifesto](https://themitlicense.github.io/) as a voluntary statement about respect for open-source maintainers.

Never imply that adoption modifies a user's license rights.

### C. Shareable one-liners

- **You can fork my code. Not my time.**
- **Free to use. Not free to demand.**
- **Open source is not your free IT department.**
- **MIT grants permission, not personal support.**
- **Respect is voluntary. The license isn't negotiable.**

Use one clear call to action: **“If this represents how you maintain open source, add the manifesto to your README.”**

### D. A linkable explanation, not just a slogan

A visitor should quickly understand: what MIT actually grants; what is *not* owed by the maintainer; practical examples of good issue reporting and contribution; what adoption means (voluntary support); how to adopt; who created the initiative.

### E. Optional independent endorsements

When/if genuine participation exists: spotlight adopters **only with their consent or in a factual, non-misleading public directory**. Do not display invented supporters, fabricated numbers or implied endorsements.

## 6. Audience and distribution priorities

| Priority | Audience | Why they might care | Distribution angle |
|---|---|---|---|
| P0 | Solo maintainers of MIT projects | Time pressure, support demands | “You can set boundaries without changing the license” |
| P0 | Maintainers of useful libraries / developer tools | Visible READMEs, recurring users | Copy-ready badge + specific practical value |
| P1 | Open-source contributors | Believe in reciprocity | Better bug reports and upstream improvements |
| P1 | Developer educators / newsletter authors | Strong conversation topic | Legal rights vs ethical behavior |
| P2 | Teams and commercial users of open source | Need sustainable dependency relationships | Give back with support, bug fixes, credits |
| P2 | General tech audience | Provocative relatable message | Shareable punchy slogan |

### Organic channels (not automated mass promotion)

- **GitHub:** the manifesto repository, discussions with genuinely interested maintainers, personal projects adopting it first, appropriate conversations where the topic has already arisen.
- **Hacker News:** a substantive, non-salesy launch and genuine discussion; no coordinated voting or repeated submissions.
- **Reddit:** relevant subreddits **only where community rules permit**, with a real discussion about maintainer expectations rather than link dumping.
- **Dev.to / Hashnode / personal blog:** educational articles explaining the distinction and showing real examples.
- **LinkedIn / Mastodon / Bluesky:** short quotable statements and dialogue; avoid generic mass-tagging.
- **Newsletters, podcasts, open-source communities:** earned coverage from a coherent and independently useful message.

The channel order is a hypothesis: optimize according to verified adopter quality, not vanity engagement.

## 7. Initial distribution: earn the first 10 adopters

**Do not contact thousands of repositories.** Begin with a small, meaningful seed group.

1. Place the manifesto on the founder's **appropriate, genuinely MIT-licensed repositories**, if any, after reviewing the license and fit.
2. Publish the manifesto in English with a working, readable adoption option.
3. Seek qualitative feedback from **5–10 maintainers** with relevant experience and an existing legitimate context for outreach; no mass unsolicited issues or PRs.
4. Record objections; ask whether they would voluntarily link it, and why or why not.
5. Revise the wording if the badge is perceived as an MIT restriction, an anti-user attack or advertising.
6. Invite interested maintainers to add it **themselves**. An unsolicited PR containing only a promotional badge is not an acceptable growth tactic.
7. Once initial independent adoptions are verified, publish the story and lessons without exaggerating the results.

**Evidence threshold:** early success means real independent links and positive maintainer feedback, not just likes.

## 8. Editorial strategy: controversy without antagonism

### Content pillars

1. **License vs. obligation:** what MIT allows and doesn't require.
2. **Maintainer boundaries:** support requests, deadlines and voluntary work.
3. **Good collaboration:** reproducible bug reports, documentation, PRs and credits.
4. **Reciprocity without coercion:** commercial use is valid; contributing back is encouraged, never mandated by MIT.
5. **Real stories:** anonymized or authorized examples of unreasonable expectations and healthy community responses.

### Angles to test

- “Can your startup make millions from my MIT library? Yes. Do I owe you free support? No.”
- “An MIT license is not an unlimited support contract.”
- “The difference between a user, a contributor and a customer.”
- “The most respectful way to report a bug.”
- “MIT doesn't require giving back. Should we do it anyway?”

Be provocative about **behaviors**, not hostile to people who use open source correctly without contributing. Respect legitimate zero-contribution use; the strongest argument concerns **entitlement to additional labor**, not freedom to use the code.

## 9. Multilingual strategy

English is the canonical editorial reference. Launch translations only when they retain the meaning and distinction between legal obligations and ethical suggestions. Localize voice and examples rather than mechanically translating slogans.

A multilingual rollout is an opportunity to recruit *real community translators*, not a reason to publish many poorly reviewed pages. Track adoption by language only where data supports it; don't guess user location from language.

The site will be built with **Jekyll** using a template supplied by the founder. **This document intentionally does not prescribe design, folder structure, plugins, Jekyll architecture or implementation.**

## 10. Personal branding without weakening the movement

**Primary CTA:** adopt/share the manifesto.  
**Secondary attribution:** “An independent initiative by Antonio Trento” linking to https://antoniotrento.net.

Do not send a badge click directly to antoniotrento.net; that would undermine the purpose of an endorsement link. Instead, provide a discreet founder attribution on the manifesto itself. Useful impact should make people curious about the creator.

Avoid treating adopters as sales leads. Do not collect or repurpose maintainers' email addresses for marketing without permission.

## 11. KPIs and measurement

### North Star — adoption

**Verified independent adopters:** distinct public repositories with a live badge or explicit manifesto link, excluding the movement's own repositories and the founder's own seed repositories. Distinguish between verified direct links, historical links and unverifiable mentions.

### Supporting metrics

- **Adoption conversion:** adopters / unique qualified visitors to the adoption instructions (requires analytics and a defensible definition).
- **Badge-to-manifesto referrals:** visits attributable to README badges where technically measurable; GitHub and browser referrer limitations mean this may be incomplete.
- **Maintainer feedback:** percentage of interviewed maintainers who say they would use it, and their reasons.
- **Retention:** proportion of adopters that still link to the manifesto after 30/90 days.
- **Organic amplification:** independent posts, citations, translations, educational articles.
- **Founder discovery:** attributable outbound clicks from the manifesto to antoniotrento.net; distinguish clicks from verified visits.

### What not to claim

Stars ≠ endorsements. Views ≠ adoption. Badge loads ≠ unique viewers. Search results ≠ a complete census of repositories. Page referrals may be missing. Do not infer actual conversions from estimated impressions.

### Suggested targets — *planning hypotheses*, not forecasts

| Window | Research / execution milestone | Adoption hypothesis |
|---|---|---|
| Days 1–14 | Publish a credible message, test with 5–10 maintainers | 1–5 independent adopters |
| Days 15–30 | Compare badge copy, first genuine community discussions | 5–15 cumulative independent adopters |
| Days 31–60 | Expand only the channels that produce verified adoptions | 15–50 cumulative independent adopters |
| Days 61–90 | Focus on repeatable voluntary discovery | 30–100 cumulative independent adopters |

These are **ambitious test targets with high uncertainty**; if they fail, revise the offer or distribution rather than increasing spam volume.

## 12. Experiment backlog

| Test | Hypothesis | Primary signal | Stop / revision condition |
|---|---|---|---|
| Badge A vs B | “Not Free Labor” resonates more than generic “Respect Maintainers” | Independent badge adoptions | Negative perception or no meaningful difference |
| Badge vs plain text | Some maintainers prefer a sober statement | Adoption by format | Both formats are ignored |
| Short vs long manifesto | Short first exposure converts better | Click-through to adoption + use | Visitors misunderstand MIT rights |
| Direct vs humorous tone | Humor increases sharing without alienating users | Qualified adoption, not likes | Discussion becomes abusive or legally misleading |
| Educational vs provocative launch | Explanation builds trust; slogan attracts attention | Verified adoptions per channel | High traffic but no adoption |
| English then localized versions | Relevant localization improves adoption | New verified language-specific references | Translation dilutes nuance |

Run small tests sequentially; document the baseline, duration and result. Avoid declaring a winner from tiny samples.

## 13. A 90-day operating plan

### Phase 1 — Make the promise credible (days 1–14)

- Finalize the legal/ethical distinction, disclaimer and tone.
- Make the site and manifesto genuinely useful to a maintainer.
- Prepare one badge and one plain-text adoption option.
- Verify all links and attribution wording.
- Interview a small number of maintainers and record objections.
- Adopt in suitable founder-controlled repositories first.

**Gate:** a maintainer understands the proposal and can adopt voluntarily without misreading it as additional MIT obligations.

### Phase 2 — Obtain proof of value (days 15–30)

- Seek the first independent, confirmed adopters organically.
- Publish one substantial educational explanation and one concise provocative post.
- Participate in relevant conversations without unsolicited promotional PRs or issues.
- Compare which messages lead to genuine adoptions.

**Gate:** real endorsement from people unconnected to the founder.

### Phase 3 — Turn adoptions into discovery (days 31–60)

- Spotlight authentic adopter stories with consent.
- Publish one or two case studies about constructive maintainer/user relationships.
- Expand to other languages selectively.
- Contact relevant editors only with a story that adds value, never a generic backlink request.

**Gate:** inbound visits and endorsements arise from existing adopter links or independent mentions.

### Phase 4 — Evaluate self-propagation (days 61–90)

- Count independently verified active adopter repositories.
- Estimate organic vs directly prompted adoption, acknowledging attribution gaps.
- Measure whether active badges remain after a month.
- Evaluate qualified founder-site referrals.
- Decide what to simplify, change or stop based on evidence.

**Gate:** signs of voluntary adoption without continued one-to-one prompting.

## 14. Ethical and platform guardrails

**Never:**

- Open bulk issues or pull requests to promote the badge.
- Scrape GitHub profiles for unsolicited marketing email.
- Automate stars, follows, comments or endorsements.
- Buy reviews, testimonials or fake adoption.
- Suggest the movement is officially affiliated with MIT, GitHub or license authors.
- Misrepresent the real conditions of MIT or imply support fees are mandatory.
- Pressure maintainers to display a backlink to antoniotrento.net.
- Use outrage campaigns targeting individual projects or people.

A movement about respecting maintainer time **must itself respect maintainers' time**.

## 15. Decision principles

- **Adoption over traffic.** The best campaign is the one that results in voluntary README links.
- **Value over backlinks.** The badge must solve a communication problem for maintainers.
- **Clarity over outrage.** Provocation is a hook; legal accuracy and respect earn trust.
- **Independence over personal advertising.** The founder is credited openly, without hijacking the movement.
- **Verified results over invented virality.** Report what happened, not what we hoped would happen.
- **Low friction over feature count.** A line of Markdown is more useful than an elaborate enrollment process.

## 16. Research basis / primary references

- MIT License overview and obligations: https://choosealicense.com/licenses/mit/
- Shields.io documentation for README badges: https://www.shields.io/docs
- GitHub acceptable use (spam, mass promotions, misleading affiliations): https://docs.github.com/en/site-policy/acceptable-use-policies/github-acceptable-use-policies
- GitHub policies on disruptive issues / PRs: https://docs.github.com/en/site-policy/acceptable-use-policies/github-disrupting-the-experience-of-other-users
- GitHub community health files / README context: https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/about-community-profiles-for-public-repositories
- Open Source Guides: building communities: https://opensource.guide/building-community/
- GitHub repository traffic and its 14-day visibility window: https://docs.github.com/en/repositories/viewing-activity-and-data-for-your-repository/viewing-traffic-to-a-repository

**Research note:** badge adoption as a *specific growth engine for this new manifesto* is an unvalidated hypothesis. The sources support the availability of the badge format, existing collaboration conventions and platform constraints—not guaranteed viral conversion rates.

---

**The ultimate test:** Will maintainers add this because it speaks for them—even if they have never heard of Antonio Trento? If yes, the movement has a plausible path to organic growth. If not, no amount of promotional outreach will fix the value proposition.
