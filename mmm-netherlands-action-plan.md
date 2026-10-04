# Marketing Mix Modeling (MMM), Netherlands: Landscape + 8-Week Action Plan
Window: Mon 5 Oct to Fri 27 Nov 2026. Research done 4 Oct 2026.

## 1. Landscape (what the research found)

**Trends**
- MMM is having a comeback because of signal loss, privacy rules and AI-driven ad buying. Attribution alone isn't enough, so teams use MMM plus incrementality tests plus attribution ("triangulation").
- Newer themes: calibrating models with experiments, scenario planning and forecasting, and faster refresh cycles.
- Netherlands: Marketing Tribune (Jul 2026) reports MMM becoming faster and cheaper, with Validators quoting a first analysis from about €7,500 in about 3 weeks. I couldn't open the article, so this comes from a search snippet.

**Tools**
- Open source: Google Meridian (Bayesian, geo-level, replaced LightweightMMM), PyMC-Marketing (Bayesian), Meta Robyn (ML-based, R/Python).
- Search snippets claim Meridian v2.0 (Sep 2026) added geo-experiments and auto-calibration. Verify on the Meridian GitHub.
- SaaS and vendors: Objective Platform (Amsterdam), Recast, Measured, Sellforte, Ekimetrics, Mutinex, LiftLab, plus Amazon Ads MMM reporting.

**Organisations in NL to follow**
- Objective Platform (Amsterdam MMM SaaS, founded 2014, founder Willem vander Weide).
- Artefact Amsterdam (certified Google Meridian partner).
- Validators (Dutch MMM provider).
- Cloud Nine Digital (writes on attribution and MMM).
- Emerce (published "veelvoorkomende valkuilen bij marketing mix modeling").
- Big agency data teams and in-house roles (ING "Data Analytics Expert", media effectiveness specialists, Harnham client-facing data scientist roles).

**People**
- Verified in search: Willem vander Weide (Objective Platform), and Prof. Koen Pauwels (Northeastern; adjunct at VU Amsterdam and Groningen).
- Not verified: I couldn't find named MMM leads at the other firms. Find them via each company's LinkedIn "People" tab (task W1-Tue).
- Global voices worth following: PyMC Labs / PyMC-Marketing maintainers (e.g. Juan Orduz), Google Meridian team, Recast, Meta Marketing Science.

**Events**
- MeasureSummit, 7-8 Oct 2026, free and virtual, with an MMM + incrementality session.
- ANA measurement summit, 17 Nov 2026 (members-only, looks US-based, so low priority).
- No dedicated Amsterdam MMM meetup found. Check Meetup.com and LinkedIn Events for "PyData Amsterdam", "Amsterdam Marketing Analytics" and "Measurement" (W1-Wed).

**Learning**
- Meridian docs and Colab notebooks (developers.google.com/meridian).
- PyMC-Marketing docs and example notebooks (GitHub).
- Towards Data Science: "Mastering Marketing Mix Modelling in Python".
- Paper: "Open-Source Media and Marketing Mix Modeling" (ResearchGate).
- Improvado, Measured and Ekimetrics 2026 guides (vendor-biased, so cross-check).

## 2. Daily template (reuse every day; about 5 hrs focused, so shift the times to suit you)
| Slot | Time | Purpose |
|---|---|---|
| A | 09:00-09:30 | News scan (timebox hard) |
| B | 09:30-11:00 | Deep learning block |
| C | 11:15-11:45 | Network micro-task |
| D | 13:00-14:30 | Hands-on build |
| E | 14:45-15:15 | Outreach / content |
| F | 16:30-16:45 | Log + plan tomorrow |

**Recurring micro-tasks**
- **A:** LinkedIn search "MMM" / "marketing mix", plus Emerce, Marketing Tribune, Marketing Report NL and Google Alerts. Save 3 links to your log.
- **F:** Write 3 bullets in your log, "learned / person / next".
- **Weekly:** 5 new LinkedIn follows and 5 connection requests with a personalised note.

## 3. Weekly plan

### Week 1 (5-9 Oct): Map the landscape
| Day | B (90m) | C (30m) | D (90m) | E (30m) |
|---|---|---|---|---|
| Mon | Read Ekimetrics 2026 MMM guide, with notes | Create a tracking sheet: people, orgs, events, resources | Install Python env; clone PyMC-Marketing | Update LinkedIn headline/About for MMM |
| Tue | Read Meridian "basics" docs | List 10 NL orgs; find 2 people at each via LinkedIn | Run the PyMC-Marketing quickstart notebook | Follow 5 people |
| Wed | Read PyMC-Marketing MMM intro | Search Meetup/LinkedIn Events for NL events | Register for MeasureSummit sessions | Connect with 5 people (note: "following your MMM work") |
| Thu | MeasureSummit live, MMM + incrementality session (take notes) | Note speakers; follow 3 | Re-run the notebook on your own tweaks | Post a 3-line takeaway on LinkedIn |
| Fri | MeasureSummit day 2 | Thank/connect with 3 speakers | Write a 1-page "MMM in 1 page" summary | Weekly review (30m): update tracking sheet |

### Week 2 (12-16 Oct): Fundamentals
| Day | B | C | D | E |
|---|---|---|---|---|
| Mon | Adstock + saturation concepts | Follow Objective Platform; read its blog | Implement adstock in a notebook | Comment on 2 MMM posts |
| Tue | Bayesian priors in MMM | Read the Emerce "valkuilen" article; note 5 pitfalls | Fit a PyMC-Marketing model on the sample data | Connect with 5 people |
| Wed | Calibration with lift tests | Check for NL events again | Add a lift-test calibration step | Share the pitfalls list as a post |
| Thu | Read the open-source MMM overview paper | Follow Prof. Pauwels; skim his recent work | Run diagnostics: R-hat, residuals | Draft 2 outreach messages |
| Fri | Budget optimisation | Review the week's contacts | Run a budget optimisation | Weekly review |

### Week 3 (19-23 Oct): Meridian + tool comparison
| Day | B | C | D | E |
|---|---|---|---|---|
| Mon | Meridian pre-modeling guide | Find Artefact Amsterdam MMM staff | Install Meridian; run the Colab | Connect with 3 Artefact people |
| Tue | Meridian applied modeling | Find Validators and Cloud Nine Digital staff | Fit a Meridian model on demo data | Comment on 2 posts |
| Wed | Meridian post-modeling | Read Meridian's GitHub issues for pain points | Compare PyMC-Marketing vs Meridian | Post a comparison |
| Thu | Read Robyn docs | Look at Meta Marketing Science's updates | Run a Robyn demo (if R is available) | Send 2 outreach messages |
| Fri | Check whether Meridian v2.0 matches the claims | Review the week | Write a "Tool comparison" table | Weekly review |

### Week 4 (26-30 Oct): Vendors + market
| Day | B | C | D | E |
|---|---|---|---|---|
| Mon | Read Recast's blog | Follow vendor accounts (Recast, Measured, Sellforte, Mutinex) | Replicate one Recast tutorial | Comment |
| Tue | Read Sellforte/Measured on MMM demand | Search NL job postings (MMM, media effectiveness) | Collect the skills from 10 postings | Connect with 5 people |
| Wed | Incrementality / geo-test design | Find 3 NL practitioners via post comments | Design a geo-test on paper | Post on triangulation |
| Thu | Triangulation (MMM + MTA + tests) | Request 2 intro chats (15 min) | Rehearse your 2-minute intro | Send the requests |
| Fri | Month-1 retrospective | Update the tracking sheet | Pick a portfolio project topic | Weekly review |

### Weeks 5-6 (2-13 Nov): Portfolio project + conversations
Build one public MMM project (own repo, README, notebook) using open data.

| Day (each week) | B | C | D | E |
|---|---|---|---|---|
| Mon | Define scope and data (W5) / add calibration (W6) | Follow-up on outreach | Build data prep | Comment on 2 posts |
| Tue | Model spec and priors | Take a 15-min chat if booked | Fit the model | Connect with 5 people |
| Wed | Diagnostics | Check events | Validate and stress-test | Post progress |
| Thu | Scenario planning | Take chats | Budget optimisation + scenarios | Send 2 outreach messages |
| Fri | Write-up (W5) / polish and publish (W6) | Thank-you notes | Final README | Weekly review; share on LinkedIn (W6) |

Also: use the 5 Nov Amsterdam startup meetup only if you're in the area and it fits.

### Weeks 7-8 (16-27 Nov): Convert to opportunities
| Day (each week) | B | C | D | E |
|---|---|---|---|---|
| Mon | Study a gap area from your log | Follow-up messages | Improve the project from feedback | Comment |
| Tue | Interview-style Q&A prep on MMM | Request 2 more chats | Write a case study | Connect with 5 people |
| Wed | Read 1 recent paper | Check events and webinars | Case study draft 2 | Post |
| Thu | Mock explain: "MMM to a CMO" in 5 minutes | Take chats | Apply to 2-3 relevant roles or pitch collaborations | Send outreach |
| Fri | Final retrospective | Update the tracking sheet | Set Dec goals | Weekly review |

## 4. Caveats
- Search results were thin on named Dutch practitioners. The names above are the verified ones.
- Marketing Tribune was blocked, so the Validators price figure is unconfirmed.
- Check every event date and the Meridian v2.0 claim before relying on them.
