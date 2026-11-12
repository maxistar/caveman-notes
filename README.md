# caveman-notes

Many words in. Clear note out. Less noise. Same meaning.

AI skill for messy transcripts and dictated notes. Cut fillers. Drop repeats.
Keep facts, questions, decisions, conditions. Output compact Markdown.

## Keep meaning

- Same language as input.
- Names, numbers, dates, units stay.
- “Maybe” stays maybe. “Don't” stays don't.
- Unclear stays unclear. No guessing.
- No invented facts. No surprise decisions.
- Already short? Leave mostly alone.

## Install in Codex

Ask Codex:

```text
$skill-installer Install the skill from https://github.com/maxistar/caveman-notes/tree/main. Skill lives at repo root. Name: caveman-notes.
```

Or use terminal. Git needed. macOS / Linux. Available across projects:

```sh
mkdir -p ~/.agents/skills
git clone https://github.com/maxistar/caveman-notes.git ~/.agents/skills/caveman-notes
```

Skill missing? Restart Codex.
More: [Codex skills guide](https://learn.chatgpt.com/docs/build-skills).

## Use

Installed in Codex? Ask `$caveman-notes` and paste transcript text.

Other assistant? Give it [SKILL.md](SKILL.md) and transcript text.
Ask: “Make a Caveman note.”

Transcript in. Note out. Audio needs transcription first.

## Example

Before:

> Uh, maybe we could try a local model, you know, but only if it works well in
> English. And don't delete the original recordings yet.

After:

```markdown
- Idea: try local model if English quality is good.
- Keep original recordings for now.
```

Short words. Whole thought.
