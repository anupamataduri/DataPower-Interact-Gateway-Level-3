# Lab Guide Style Guide

This document defines the formatting conventions used in IBM Technical Sales Level 3 lab guides built with MkDocs Material. Follow these patterns consistently across every page.

---

## Page Structure

Every demo script page follows this structure, in order:

```
# Part N: [Part Title]

## Narration — [Descriptor]        ← opening narration (blockquote)

## Step N — [Step Title]           ← action steps

## Narration — [Descriptor]        ← mid-section narration (optional)

## Step N — [Step Title]           ← more steps

## Wrap-up                         ← closing narration (blockquote)

Previous / Next navigation         ← nav footer
```

---

## Narration Blocks

All narration text uses `>` blockquote syntax. Never use plain paragraphs for narration.

```markdown
## Narration — The Business Challenge

> ZillaForge, a fictional global manufacturer, is expanding its use of AI...
>
> As AI adoption grows, the company faces a new challenge...
>
> To address these challenges, ZillaForge adopts IBM DataPower Interact Gateway.
```

**Rules:**
- Section heading must be `## Narration — <descriptor>` where the descriptor is 2–5 words
- Every paragraph inside the blockquote must be separated by `>`
- No bold or heading formatting inside narration blocks
- The opening narration introduces the section; the Wrap-up closes it

---

## Step Blocks

```markdown
## Step 3 — Open the ZFmcp Project

**Action:** Click the project **ZFmcp**.

![](https://colony-recorder.s3....)

**Action:** In the Assembly flow, click the **Invoke** node.

![](https://colony-recorder.s3....)
```

**Rules:**
- Heading: `## Step N — <descriptor>`
- Every user action starts with `**Action:**`
- UI element names are bold: click **Submit**, click **API View**
- One screenshot per distinct action
- Screenshots use bare `![]()` — no alt text needed

---

## Copyable Values

Any value the learner needs to type or paste must be in a fenced code block so MkDocs renders a copy button.

````markdown
**Action:** In the Name field, type:

```text
DataPower Interact Gateway L3
```

**Action:** Copy and paste the following into the request body.

```json
{
  "model": "openai.gpt-oss-120b",
  "messages": [{"role": "user", "content": "Hello"}],
  "max_tokens": 512
}
```
````

**Rules:**
- Use ` ```text ``` ` for plain strings (URLs, names, single values)
- Use ` ```json ``` ` for JSON bodies
- Use ` ```yaml ``` ` for YAML content
- Never put copyable values inline in bold — always use a code block

---

## Admonition Boxes

Use MkDocs Material admonitions for callouts. Never use plain bold paragraphs for warnings or notes.

```markdown
!!! tip "Important"
    Once you open the project, use the view selector to switch to AI view.

!!! note "Note to Learners"
    This action could take up to **15–20 minutes**.

!!! warning "Disclaimer"
    Please be careful to stay within the demo path.

!!! info "Read-Only Experience"
    The experience is **read-only** and follows a structured stand-and-deliver format.
```

**Available types:** `tip`, `note`, `warning`, `info`, `danger`, `success`, `question`

---

## External Links

All external links must open in a new tab. Never use standard markdown `[text](url)` for external links.

```markdown
<!-- ✅ Correct -->
<a href="https://techzone.ibm.com" target="_blank">https://techzone.ibm.com</a>

<!-- ❌ Wrong -->
[IBM TechZone](https://techzone.ibm.com)
```

**Exception:** Internal page-to-page links (nav footer, cross-references) use standard markdown links.

---

## Navigation Footer

Every demo script page ends with a nav footer. The last demo script page links to `../conclusion.md` (one level up).

```markdown
---

**Previous:** [← Part 2: Explore Governed MCP Tools](part2.md) | **Next:** [Part 4 - Discover AI Assets →](part4.md)
```

**Rules:**
- Always on the last line, after a `---` divider
- `←` before Previous link text, `→` after Next link text
- Previous uses `Part N: Full Title` format; Next uses `Part N - Short Title →` format
- The first page (Architecture) has only **Next**, no **Previous**
- The last demo page links to `../conclusion.md` (not `conclusion.md`)
- `conclusion.md` links back to `demo-script/partN.md` (not `partN.md`)

---

## Wrap-up Section

Every part ends with a `## Wrap-up` section using blockquote text.

```markdown
## Wrap-up

> We've seen how ZillaForge reused existing enterprise APIs, applied governance
> policies, and published the resulting MCP tools through the Interact Gateway.
>
> By following this approach, organizations can safely make enterprise capabilities
> available to AI assistants and agents while maintaining security and control.
```

**Rules:**
- Always `## Wrap-up` — no descriptor suffix
- 2–3 sentences summarising what was demonstrated
- 1 sentence bridging to the next section (except on the last part)
- Use blockquote `>` format, same as Narration blocks

---

## File & Folder Structure

```
docs/
├── index.md                  ← Introduction / Welcome
├── prerequisites.md
├── overview.md               ← Product overview
├── scenario.md               ← About the fictional company
├── environment.md            ← TechZone reservation steps
├── demo-guidelines.md        ← Use case intro + demo overview
├── conclusion.md             ← Conclusion (in docs/ root)
└── demo-script/
    ├── architecture.md       ← Overview & Architecture (no Part number)
    ├── part1.md
    ├── part2.md
    └── part3.md              ← Links to ../conclusion.md
```

**Key rule:** `conclusion.md` lives in `docs/` (not `docs/demo-script/`). This means:
- Last demo-script page → `../conclusion.md`
- `conclusion.md` previous link → `demo-script/partN.md`

---

## GitHub Actions Deployment

The `.github/workflows/deploy.yml` file handles automatic deployment to GitHub Pages on every push to `main`. Copy it unchanged from this repo — no modifications needed.

```yaml
# .github/workflows/deploy.yml
name: Deploy MkDocs to GitHub Pages
on:
  push:
    branches:
      - main
jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
        with:
          fetch-depth: 0
      - uses: actions/setup-python@v4
        with:
          python-version: '3.x'
      - run: pip install mkdocs-material
      - run: git config user.name "github-actions[bot]"
      - run: git config user.email "github-actions[bot]@users.noreply.github.com"
      - run: mkdocs gh-deploy --force
```
