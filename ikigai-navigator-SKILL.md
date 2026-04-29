---
name: ikigai-navigator
description: Guide the user through building a personal Ikigai map — the Japanese concept of life purpose found at the intersection of what you love, what you're good at, what the world needs, and what you can be paid for. Use this skill whenever the user mentions ikigai, life purpose, career clarity, personal mission, meaning of work, values alignment, or wants to discover their "why". Also trigger when the user asks for self-discovery exercises, purpose-finding frameworks, or wants to visualise their professional and personal identity on a single canvas. Outputs a structured Ikigai profile in Markdown with a visual chart prompt and actionable next steps.
---

# Ikigai Navigator Skill

This skill guides the creation of a personal Ikigai map — a Japanese framework for discovering life purpose at the intersection of four fundamental dimensions.

## What is Ikigai?

Ikigai (生き甲斐) literally means "reason for being." It sits at the centre of four overlapping circles:

| Circle | Core Question |
|--------|--------------|
| **Love** | What do you love doing so much you lose track of time? |
| **Good At** | What skills, talents, and expertise do you possess? |
| **World Needs** | What problems or gaps in the world do you want to address? |
| **Paid For** | What can (or do) people pay you for? |

The four intersections also have names:
- Love ∩ Good At = **Passion**
- Good At ∩ Paid For = **Profession**
- Paid For ∩ World Needs = **Vocation**
- World Needs ∩ Love = **Mission**
- All four = **Ikigai**

---

## Skill Workflow

### Phase 1 — Questionnaire
Run the user through a structured questionnaire across all four dimensions. Use open-ended prompts grouped by circle. Aim for 5–8 answers per dimension before proceeding.

**Love (心)** — Prompt examples:
- What activities make you lose track of time?
- What topics do you read about without being asked?
- What did you love doing as a child that you still enjoy?
- When do you feel most alive and energised?

**Good At (得意)** — Prompt examples:
- What do people consistently ask your help with?
- What skills have you built deliberately over 10+ years?
- What comes easily to you that others find hard?
- What achievements are you most proud of?

**World Needs (必要)** — Prompt examples:
- What problems in the world frustrate or sadden you most?
- What change would make the world measurably better?
- Who do you most want to serve — what community or audience?
- What would you fix if you had unlimited resources?

**Paid For (報酬)** — Prompt examples:
- What have you been paid to do (or could be paid to do)?
- What value do others recognise in your work?
- What would someone hire you for before anyone else?
- What skills are scarce + valuable in your industry?

---

### Phase 2 — Intersection Analysis
Once answers are collected, identify:

1. **Overlapping themes** — words, topics, or domains that appear in 2+ circles
2. **Tension points** — things in "Love" but not "Paid For" (passion without income), or "Paid For" but not "Love" (golden handcuffs)
3. **Blind spots** — circles with thin answers that need more exploration
4. **Ikigai candidates** — 1–3 synthesis statements that sit at the centre

#### Synthesis Template
```
My Ikigai is: [active verb] + [who I serve] + [through what method] + [toward what outcome]

Example: "Helping marketing leaders in regulated industries build ethical AI systems 
that grow their business while protecting people."
```

---

### Phase 3 — Output: Ikigai Profile (Markdown)

Produce a structured `.md` file with:

```markdown
# [Name]'s Ikigai Map
*Generated: [date]*

## The Four Circles

### ❤️ What I Love
- [bullet list from questionnaire answers]

### 💪 What I'm Good At
- [bullet list]

### 🌍 What the World Needs
- [bullet list]

### 💰 What I Can Be Paid For
- [bullet list]

---

## The Four Intersections

| Intersection | Description |
|---|---|
| **Passion** (Love + Good At) | [sentence] |
| **Mission** (Love + World Needs) | [sentence] |
| **Vocation** (World Needs + Paid For) | [sentence] |
| **Profession** (Good At + Paid For) | [sentence] |

---

## ✨ My Ikigai Statement

> [1–2 sentence synthesis]

---

## Overlapping Themes
[3–5 recurring themes across circles]

## Tension Points to Resolve
[Honest notes on gaps or conflicts]

## Next Steps
- [ ] [Action 1]
- [ ] [Action 2]
- [ ] [Action 3]
```

---

### Phase 4 — Optional: Visual Chart
If the user wants a visual:
- Build an interactive Ikigai chart as a React artifact with four overlapping SVG circles
- Use the user's actual answers as labels
- Highlight the centre (Ikigai zone) distinctly

---

## Quality Checks

Before delivering the Ikigai profile, verify:
- [ ] All four circles have at least 5 substantive answers
- [ ] Intersections are described in concrete, specific language (not generic)
- [ ] The Ikigai statement is actionable and personal (not vague platitudes)
- [ ] Tension points are named honestly — avoid toxic positivity
- [ ] Next steps are specific and time-bound where possible

---

## Notes on Facilitation

- **Don't rush Phase 1.** Shallow answers produce generic Ikigai. Push for specificity.
- **Probe for the unexpected.** Often the most important answers come on the 3rd or 4th follow-up.
- **The centre is rare.** If the user expects Ikigai to be obvious, explain it typically takes weeks of reflection — this is a starting map, not a final answer.
- **Honour ambiguity.** Multiple Ikigai candidates are valid. A person can have a professional Ikigai and a creative Ikigai.
- **Revisit annually.** Ikigai shifts as life context changes. Recommend saving the `.md` file and reviewing it every 12 months.

---

## Example Ikigai Statements (for reference, not templates)

- "Building AI-powered marketing systems for EU-regulated industries that help brands grow ethically."
- "Teaching children in underserved communities to code through storytelling and creative projects."
- "Designing sustainable supply chains for fashion brands that want to be honest about their impact."
