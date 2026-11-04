# Signal Intelligence: Agent Insight Scenario

**Purpose:** Replace the Agent insight (UC-4) content in the demo. Design and layout stay as they are. Only text, numbers, and list contents change.

**Status:** Demo scenario. All Citi dollar figures below are illustrative, built from public data and stated assumptions. They are not Citi forecasts.

**Demo ends at Approve in the Decision Queue.** The IPDLC pipeline is mentioned out loud only.

**Rules for all copy:**
- No em dashes, en dashes, or hyphens used as dashes. Hyphens are fine in number ranges and compound words.
- Do not change any number without updating the number model in Section 10.
- Plain language first. Card terms only where this audience already uses them.

---

## 1. Today's Insights card

| Field | Current | New |
|---|---|---|
| Domain tag | Agent | Agent (no change) |
| Title | Agent-Initiated Checkout | $385B in AI Purchases by 2030. Which Card Wins? |
| Signals chip | 4 signals | 8 signals |
| Projects chip | 3 projects | 6 projects |
| Sources chip | 4 sources | 8 sources |
| Header count | 19 signals | 23 signals, if the app sums insight signals |
| Button | Review | Review (no change) |

**Check:** The title is longer than the others. Confirm it wraps cleanly on the card. The Competitor title already wraps to two lines.

---

## 2. Review loading screen

| Element | Current | New |
|---|---|---|
| Heading | Reviewing Agent · Agent-Initiated Checkout | Reviewing Agent · $385B in AI Purchases by 2030 |
| Top right status | Calling LLM | Building the read |
| Step 1 | Fetching signals... | Gathering signals... |
| Step 2 | Grounding in USCC policy... | Checking USCC policy... |
| Step 3 | Calling LLM... | Building the read... |
| Step 4 | Parsing use case... | Preparing the brief... |
| Section label | USCC POLICY GROUNDING | USCC POLICY GROUNDING (no change) |
| Policy rows | USCC-FRD-05, USCC-DSP-02, USCC-TPR-01 | Keep. Placeholder IDs. Confirm they read as demo content. |
| Row status | GROUNDED | GROUNDED (no change) |
| Footer | FRED · BLS · CFPB · EDGAR · USCC Policy Docs · LLM | Network releases · Company filings · Market research · USCC Policy Docs |

---

## 3. Brief and benefit vs waiting

| Field | Current | New |
|---|---|---|
| Back button | Today's Insights | No change |
| Breadcrumb | Agent · Agent-Initiated Checkout | Agent · $385B in AI Purchases by 2030 |
| Brief label | BRIEF SYNTHESIS, AGENT, LIVE | No change |
| Brief title | Agent-Initiated Checkout | $385B in AI Purchases by 2030. Which Card Wins? |
| Section label | BENEFIT OF ACTING VS. WAITING | No change |

**Brief body**

> AI agents are starting to shop for customers. Agent purchases are still tiny today, and only 9% of consumers are open to fully autonomous shopping. But the rails are live, Muse reached 10M users in six weeks, and forecasts reach up to $385B in US spend by 2030. Up to $770M a year of Citi interchange, before rewards, could run through these agents. So we need to decide now how Citi shows up.

**Benefit of acting**

> A $16-31M pilot puts Citi's own controls in place, keeps customers in charge, and protects up to $75M a year by 2030. Adding trust and a new offer brings the total to $31-61M and protects up to $120M a year.

**Cost of waiting**

> Your AI buys the wrong thing on your card. You call Citi, not the AI. Without our own controls, we take that call on rules others wrote, with up to $8B in spend and $150M a year in interchange at risk by 2030.

**Small print under both cards, if the layout allows:** Demo figures. Illustrative, before rewards.

---

## 4. Proposed projects

**Helper text:** Tick a project to add it to the decision queue (no change).

| # | Project | Type | Scope | Cost / trade |
|---|---|---|---|---|
| 1 | Agent credential provisioning | Build | Set Citi's controls in Visa and Mastercard agent programs, including when a purchase needs customer step-up. | $8-15M. Keeps approve and decline control. |
| 2 | Liability and dispute playbook | Decision | Define who pays when an agent gets it wrong, and how the customer is made whole. | $2-4M. Reduces dispute loss and complaints. |
| 3 | Auth rate and false positive monitoring | Build | Track agent spend as its own channel, including declines and complaints. | $1-2M. Catches friction early. |
| 4 | Agent Controls in the Citi Mobile App | Build | Let customers see their agents, set limits, and turn them off. | $5-10M. Gives customers control and builds trust. |
| 5 | Consumer trust campaign | Campaign | Make Citi the card people trust when an AI buys for them. | $10-20M. Builds preference while adoption is early. |
| 6 | Agent-ready card offer | Partnership | Test a new offer with a partner to earn the top spot in agent wallets. | $5-10M, before rewards. Gives customers a reason to choose Citi. |

**Roll-up:** Projects 1-4 total $16-31M (Pilot). Projects 1-6 total $31-61M (Full enablement).

**Layout check:** The app showed 3 rows. Confirm 6 rows render. The Type column is new. If it can't be added, put the type in the small PROJECT label above each name. If 6 rows can't fit, the priority order is 1, 2, 4, 5, 3, 6.

---

## 5. What-if vs do nothing

| Element | Current | New |
|---|---|---|
| Section title | What-if · vs. do nothing | No change |
| Helper text | Projection only. Nothing changes until you approve. | No change |
| Slider title | ISSUER AGENT-CREDENTIAL ENABLEMENT (OFF / PILOT / FULL) | ISSUER CONTROLS ON AGENT PURCHASES (OFF / PILOT / FULL) |
| Slider status | current Off · proposed Pilot | No change |
| Legend 1 | Loss trajectory | Spend at risk |
| Legend 2 | Trajectory (with band) | Protected spend |
| Legend 3 | Do nothing (baseline) | Do nothing |
| Snap button | Snap to Signal Intelligence proposal | Set to recommended |

**Why the slider title changes:** Citi was publicly named an early Mastercard Agent Pay pilot. "Off" must mean Citi has not set its own controls, not that Citi has no agent capability.

**Scenario table**

| Scenario | Assumption | Impact by 2030 | Action |
|---|---|---|---|
| Watch | Others set the rules. Citi loses 10-20% of its agent spend. | Up to $8B spend and $150M a year in interchange at risk | Monitor pilot results |
| Pilot | Citi sets its own controls for a limited cohort and protects about half of that loss. | $16-31M to protect up to $4B spend and $75M a year | Run with step-up rules |
| Full enablement | Citi's controls scale, plus trust and offers. Protects about 80% of that loss. | $31-61M to protect up to $6B spend and $120M a year | Scale after the pilot |

**Slider behavior, inferred from screenshots. Other agent: confirm in the code.**

| Position | Maps to | Highlighted row | Effect card heading | Effect card body | Action line |
|---|---|---|---|---|---|
| Off | current state | Watch | Watch | Up to $8B spend and $150M a year in interchange at risk. | Action: Monitor pilot results |
| Middle | proposed | Pilot | Pilot | $16-31M to protect up to $4B spend and $75M a year. | Action: Run with step-up rules |
| Full | future | Full enablement | Full enablement | $31-61M to protect up to $6B spend and $120M a year. | Action: Scale after the pilot |

**Effect card footer, all positions:** Trades project cost and control against spend, customer trust, and dispute exposure.

**Set to recommended** moves the slider to the middle position (Pilot).

**Chart:** Keep it as a shape only. No dollar axis or year labels unless the values tie to Section 10. Off should show the widest risk band at the right edge, Pilot about half, and Full about one fifth. If the chart does not respond to the slider today, leave it static and flag it.

---

## 6. Key signals

**Header helper:** Metric · illustrative value · trigger threshold becomes Signal · latest · what would change our read

These merge the app's four signals with the new ones. Stripe Agentic Commerce Suite folds into signal 4. ACP/AP2 folds into signal 8.

| # | Signal label | Headline | Trigger |
|---|---|---|---|
| 1 | Agent checkout reality | OpenAI pulled back in-chat checkout. Visa calls agent volume tiny. | A major platform reports agent orders above 1% of total |
| 2 | Consumer trust | Only 9% are open to fully autonomous shopping | Trust at payment moves toward 40% |
| 3 | AI shopping demand | Shopify AI orders up 3.3x. AI traffic converts 90% better. | Holiday AI traffic beats the +130% forecast |
| 4 | Agent wallets | Stripe Link and Shop Pay now work inside personal agents | A wallet becomes the default in a major agent |
| 5 | Personal agents | Muse hit 10M users in six weeks. Amazon blocked it on Sept 20. | Amazon signs an agent access deal |
| 6 | Mastercard Agent Pay | Citi named an early pilot. Agent probability score now in US testing. | Agent spend reported at scale |
| 7 | Visa Intelligent Commerce | Connect launched Apr 2026. OpenAI partnership announced Jun 2026. | Live agent volume on Citi cards |
| 8 | Who pays when agents err | No US rule yet. Amex covers registered agents. Shop Pay puts in-budget mistakes on the consumer. | Visa or Mastercard publishes an agent dispute rule |

---

## 7. Sources

Keep the existing tag, title, subtitle, and access/refresh format.

| Tag | Title | Subtitle | Access · Refresh | URL |
|---|---|---|---|---|
| Morgan Stanley | Here Come the Shopping Bots | Agent spend forecast | Free · As published | https://morganstanley.com/insights/articles/agentic-commerce-market-impact-outlook |
| Citi | 3Q26 Financial Supplement | USCC spend | Free · Quarterly | https://www.citigroup.com/rcs/citigpa/storage/public/Earnings/Q32026/2026fsqtr3rslt.pdf |
| Nilson | Issuers by purchase volume | Citi share estimate | Free summary · Annual | https://wtop.com/news/2026/03/8-biggest-u-s-credit-card-companies-this-year |
| Mastercard | Agent Pay pilot and rollout | Citi named pilot, Sept 2025 | Free · As announced | https://www.bankingexchange.com/news-feed/item/10413-citi-u-s-bank-to-pilot-mastercard-s-ai-payments-service |
| Visa | Intelligent Commerce Connect | Launch and pilot | Free · As announced | https://www.paymentsjournal.com/visa-unveils-agentic-commerce-platform-for-merchants/ |
| Meta | Muse users and shopping | Q3 earnings coverage | Free · As reported | https://fortune.com/2026/10/22/mark-zuckerberg-meta-muse-stripe-credit-limit-shopping/ |
| Stripe | Sessions 2026 | Link wallet and suite | Free · As released | https://stripe.com/blog/everything-we-announced-at-sessions-2026 |
| FIDO Alliance | AP2 donation | Agent payment standards | Free · As updated | https://fidoalliance.org/google-donates-agent-payments-protocol-to-fido-alliance/ |

**Other agent:** The primer's items for Accenture 9%, Shopify 3.3x, Adobe +90%, Amazon's Muse block, Visa "tiny", Amex protection, and Shop Pay terms need their direct URLs added or confirmed. Use the links in primer Section 17.

---

## 8. Decision Queue

| Element | Behavior | Text |
|---|---|---|
| Empty state | No projects ticked | Decisions appear here. |
| Group title | Project ticked | $385B in AI Purchases by 2030 |
| Tag | Each item | PROPOSED PROJECT · AGENT |
| Item | Each ticked project | Project name, scope line, Status: pending |
| Count | Live | Matches the number ticked |
| Approve / Reject | Applies to the group | No change |

**Demo path:** Tick projects 1-4 (Pilot), then Approve. Stop there.

**Check:** Confirm Approve doesn't jump into the IPDLC screen during the demo, or that the presenter knows it does.

---

## 9. IPDLC handoff text

Not demoed. Update so the data still ties if anyone clicks through.

**Problem statement:** Agents are starting to buy for customers, but customers cannot see which agents can use their Citi card, set limits, or turn them off.

**Solution:** This project will deliver Agent Controls in the Citi Mobile App. Customers see connected agents, set limits, and revoke access. Cost: $5-10M, illustrative.

**Note:** This is the clearest IPDLC project. Project 2 is a decision and project 5 is a campaign, so neither should imply a software build.

---

## 10. Number model

| Step | Low | High | Basis | Confidence |
|---|---|---|---|---|
| US agent spend, 2030 | $190B | $385B | Morgan Stanley forecast | Forecast |
| Citi share of card spend | 10% | 10% | $600B+ of about $6T, Nilson data | Our estimate |
| Citi spend at stake | $19B | $38B | Math | Illustrative |
| Interchange rate | 2% | 2% | Our assumption. Merchants pay about 2.36% total. | Assumption |
| Interchange at stake | $380M | $770M | Math, before rewards | Illustrative |
| Share at risk if we wait | 10% | 20% | Our assumption | Assumption |
| Spend at risk | $2B | $8B | Rounded | Illustrative |
| Interchange at risk | $40M | $150M | Rounded | Illustrative |
| Pilot protects 50% | $1B, $20M | $4B, $75M | Assumption, rounded | Illustrative |
| Full protects 80% | $1.5B, $30M | $6B, $120M | Assumption, rounded | Illustrative |
| Pilot cost, projects 1-4 | $16M | $31M | Our estimates, one time | Illustrative |
| Full cost, projects 1-6 | $31M | $61M | Our estimates, one time | Illustrative |

**Sanity check using a lower forecast:** eMarketer has AI platform attributed US retail sales at about $21B in 2026 and $144B by 2029. Citi's 10% and 2% on $144B is about $290M a year. That's a conservative floor to have ready.

**Do not:**
- Compare one-time project costs to annual interchange as a simple payback.
- Say $770M is lost. It's exposed.
- Say agents are already buying at scale. They aren't.

---

## 11. Corrections from the Nov 4 primer

| Item | Old | Now |
|---|---|---|
| Shopify growth | 13x in Q1 | 3.3x YoY, the latest Q3 figure |
| Trust stat | 55% uncomfortable (Riskified) | 9% open to full autonomy (Accenture, 25,590 people). Riskified stays as backup. |
| Standards | ACP and AP2 both live | UCP is the default. ACP has been quiet since July. |
| Shopify merchants | "About a dozen on ChatGPT" | About a dozen across ChatGPT, Gemini, and Copilot. Use with care. |
| CFPB advisory | Dispute rights survive delegation | Do not use. No primary source was found. |
| Bain forecast | Used as support | Tagged soft in the primer. Morgan Stanley stays as the headline. Be ready to give the eMarketer floor. |

---

## 12. Verification checklist for the other agent

**Numbers**
- [ ] Recalculate every row in Section 10.
- [ ] Confirm the same numbers appear in the Brief, Benefit, Cost of Waiting, Scenario table, and Effect card.
- [ ] Confirm project costs sum to $16-31M and $31-61M.

**Facts**
- [ ] Open each source and confirm the claim.
- [ ] Confirm Citi's current Agent Pay status. Public source is from Sept 2025.
- [ ] Confirm Visa Intelligent Commerce Connect's latest status and July European transactions.
- [ ] Confirm the Muse 10M and shopping claims.
- [ ] Add direct URLs for primer-sourced items.

**App behavior**
- [ ] Confirm which file holds the UC-4 content.
- [ ] Confirm slider states, row highlighting, and the Effect card mapping.
- [ ] Confirm what the chart reads, and whether it moves.
- [ ] Confirm chips and the 19 total are data driven.
- [ ] Confirm 6 projects and 8 signals render with no clipping.
- [ ] Confirm Queue count, Approve, and Reject still work.
- [ ] Confirm the other three insights are untouched.

**Copy**
- [ ] Scan for em dashes, en dashes, and hyphens used as dashes.
- [ ] Remove every remaining "Calling LLM", "Parsing use case", and "Snap to Signal Intelligence proposal".
- [ ] Remove every remaining "Agent · Agent-Initiated".

**Report back:** List anything that couldn't be applied, why, and what was changed instead.
