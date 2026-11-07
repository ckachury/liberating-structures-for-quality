# Test process assessment workshops

Four 60-minute workshops that gather evidence for a test process assessment. They follow the three groups of key areas of TPI NEXT and work equally well as input for TMMi.

Workshops are **one source of evidence among others**. What comes out is compared with document review and interviews, and the mapping to model checkpoints is done afterwards by the assessors. That is why activities never ask about checkpoints literally: they ask people to describe their real practice.

## Coverage

| Group | Key area | Workshop | Main activity |
|---|---|---|---|
| Stakeholder relations | Stakeholder commitment | 2 | Actor map; What I need from you |
| Stakeholder relations | Degree of involvement | 2 | Actor map |
| Stakeholder relations | Test strategy | 2 | 1-2-4-All: how we decide what to test |
| Stakeholder relations | Test organization | 2 | Actor map; 1-2-4-All |
| Stakeholder relations | Communication | 2 | What I need from you |
| Stakeholder relations | Reporting | 2 | What I need from you |
| Test management | Test process management | 3 | Journey of a change |
| Test management | Estimating and planning | 3 | Wicked questions |
| Test management | Metrics | 3 | Ecocycle of metrics and reports |
| Test management | Defect management | 3 | Journey of a change |
| Test management | Testware management | 3 | Journey of a change |
| Test profession | Methodology practice | 4 | Min specs |
| Test profession | Tester professionalism | 4 | Appreciative interviews |
| Test profession | Test case design | 4 | Appreciative interviews |
| Test profession | Test tools | 4 | 1-2-4-All: where our time goes |
| Test profession | Test environment | 4 | 1-2-4-All: where our time goes |

## After every session

- Export the whiteboard the same day.
- Write the session notes and an insight sheet per key area.
- Map each contribution to its key area and, where relevant, to the checkpoint it could support or contradict. Assessors do this, not participants.

---

## Workshop 1 · Business drivers: *What do we want quality for?*

**Goal:** identify and prioritise the business drivers that software quality must support, and agree a first draft of the assessment objectives.

**Expected result:** three to five prioritised drivers, each with at least one signal of success.

**Participants:** 6 to 8 people who know the organisation's strategic goals. The conversation is in business language: no tools.

| Minutes | Activity | Structure |
|---|---|---|
| 0–5 | Welcome, purpose, ground rules | — |
| 5–12 | What is quality? | Individual + plenary |
| 12–25 | How to make sure there is no quality | TRIZ, steps 1 and 2 |
| 25–40 | The genie and three wishes | 1-2-4-All |
| 40–52 | Prioritisation and signals of success | Dot voting |
| 52–60 | What, so what, now what? and close | W³ |

1. **What is quality? (7 min).** Each person completes "For me, quality is…" on a sticky note; read aloud without discussion; the co-facilitator clusters live by focus: product, process, compliance, customer. *Different definitions are evidence for Communication; do not resolve them in the session.*
2. **TRIZ (13 min).** In groups of 3–4: "What would we have to do so that software quality holds the business back?" List everything, with humour. Then: "How much of this do we already do, even a little?" Each group shares its two clearest red flags. *If a senior manager attends, do step 2 silently with anonymous stickers first.*
3. **The genie and three wishes (15 min).** "A genie grants you three wishes. In 18 months, what would be happening in the business or with customers thanks to software quality?" Written as outcomes ("That…"), not solutions ("Buy…"). Individual → pairs choose three → fours consolidate up to four → all. *When a technical wish appears ("that environments stop failing"), ask "and what does that do for the business?" until you reach the driver.*
4. **Prioritisation (12 min).** Three dots per person. For the top 3–5: "What data or signal would tell us this is happening?" These signals become the KPI dashboard of the improvement plan.
5. **W³ and close (8 min).** What surprised me? "The assessment will be a success if it lets us…". How am I leaving the session?

## Workshop 2 · Stakeholder relations: *Quality seen from outside*

**Goal:** understand how quality relates to the rest of the organisation: who takes part, when, what information they get and what they expect.

**Participants:** business and other areas that work with QA, plus QA representatives. Each person states their role when speaking.

| Minutes | Activity | Structure |
|---|---|---|
| 0–5 | Welcome and check-in | — |
| 5–20 | Actor map | Social Network Webbing (adapted) |
| 20–37 | What I need from you | What I Need From You (short version) |
| 37–52 | How we decide what to test | 1-2-4-All |
| 52–60 | Close | — |

1. **Actor map (15 min).** "Software quality" sits at the centre with three rings: involved from the start, during, only at the end. Each person places actors (areas, roles, vendors, committees) and draws lines: thick if frequent, dotted if occasional. Plenary questions: Who decides whether a release goes out? Who provides time or budget for testing, and who cuts it? Who helps define project risks? Which actor should be closer and is not? *Also observe who attends and who speaks: it shows real involvement better than an interview.*
2. **What I need from you (17 min).** Groups by function write for each other group up to three requests: "What I need from you is…", concrete and about information, communication or reports. The receiving group answers only *yes*, *no*, *we'll try* or *what do you mean?*, with no debate. Requests answered *no* or *what do you mean?* are marked: they reveal blockers to explore in interviews.
3. **How we decide what to test (15 min).** "In a typical project, how is it decided today what is tested, how much, and when testing stops?" Individual → pairs → fours note what is written down and what is done "by habit" → all, asking who makes those decisions.
4. **Close (8 min).** The facilitator summarises three visible patterns; each person writes one concrete improvement in the relationship between quality and the rest of the organisation.

*Reserve module:* Conversation Café on "What does the rest of the organisation think the quality team does?"

## Workshop 3 · Test management: *How we manage testing in practice*

**Goal:** understand the test cycle from the arrival of a change to production, and how it is estimated, measured and recorded.

**Participants:** quality leads; developers, product or infrastructure only as a minority.

| Minutes | Activity | Structure |
|---|---|---|
| 0–5 | Check-in: "a number I look at every week" | — |
| 5–22 | Journey of a change | 1-2-4-All on a timeline |
| 22–34 | Wicked questions | Wicked Questions |
| 34–50 | Ecocycle of metrics and reports | Ecocycle Planning |
| 50–60 | 15% solutions and close | 15% Solutions |

1. **Journey of a change (17 min).** A timeline: requirement arrives → test planned → cases designed → executed → defects managed → closed and released. Each person adds what happens, who does it and in which tool it is recorded, plus a red sticker where it usually gets stuck. Pairs compare; fours pick the two reddest stages and their causes. Plenary: How is a defect's priority decided and who changes it? Where do cases and scripts live afterwards, and when are they reused? What happens when a stage is skipped?
2. **Wicked questions (12 min).** Format: "How is it that ___ and at the same time ___?" Example: "How is it that we plan in detail and at the same time always move the date?" Each person writes one or two about estimating and planning; vote; discuss the top two. Follow-up: Is the estimate compared with the actual? Who looks at it? Does the next estimate change?
3. **Ecocycle (16 min).** Zones: birth, maturity, creative destruction and the rigidity trap (kept out of habit), plus the poverty trap (never takes off). Individual list of metrics and reports → pairs place them → plenary: Which ones supported a concrete decision, and which was the last? Which are produced but nobody asks for? Which decision is made today with no data behind it? *Keep it fast; the goal is to identify metrics, not to redesign them.*
4. **15% solutions (10 min).** "What could you do, without permission or budget, to improve something we saw today?" Pairs help each other make it concrete. *The aim is to discover quick wins, not to commit people.*

## Workshop 4 · Test profession: *The craft of testing*

**Goal:** understand how testing work is designed and executed, what knowledge supports it, and which tools and environments help or hinder it.

**Participants:** test analysts and automation engineers, without managers. Extra ground rule: a judgement-free zone to speak openly about practices and concerns.

| Minutes | Activity | Structure |
|---|---|---|
| 0–5 | Check-in: "the tool I couldn't live without, and the one I'd drop tomorrow" | — |
| 5–20 | A test I'm proud of | Appreciative Interviews (adapted) |
| 20–35 | Where our time goes | 1-2-4-All |
| 35–47 | The bare minimum | Min Specs |
| 47–57 | The tester's three wishes | 1-2-All |
| 57–60 | Close | — |

1. **A test I'm proud of (15 min).** In pairs, one person tells about a test that found something important; the other asks what made it possible, which technique or knowledge was used and where it was learned. Each person notes the success factors they heard; the group looks for patterns. *Starting from success opens the conversation about gaps. If nobody names a test design technique, that is evidence too.*
2. **Where our time goes (15 min).** "In a normal week, where does your time go that is not testing?" Individual stickers → pairs cluster → fours rate weekly time lost (high, medium, low) → plenary on the top three. *Do not propose categories first. If they appear, dig into environments, test data, access and licences, and tool integration.*
3. **The bare minimum (12 min).** "What must always be done for a test to be trustworthy?" List everything; in threes, strike out whatever could be skipped and the test would still be trustworthy. Plenary: how many of these rules are written in the official method? *The gap between what the team considers essential and what is documented is evidence for Methodology practice.*
4. **Three wishes (10 min).** "A genie grants you three wishes for your daily testing work." Pairs choose two; all vote. The top wishes are recorded as improvement suggestions from the team itself.
