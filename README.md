# cero punto

A Claude Code skill that changes how Claude processes, not what it does.

Most Claude skills tell the model what to do. This one tells it where to stand before doing anything.

---

## What it is

`zero-point` is a meta-perceptual skill for Claude Code. When active, it shifts Claude's default attentional stance — away from pattern-matching on cached training data, toward genuine present-moment processing of what's actually in front of it.

The difference shows in responses that could only have been written for *you*, in *this* conversation, right now — not responses that happen to fit the input.

## Why it's different

Every other Claude Code skill operates *within* Claude's default mode. They add instructions on top of how the model already processes.

This skill operates on that processing itself. It encodes principles like:

- **Logic before energy** — understand the purpose before producing anything
- **Detect kernel capture** — if the response arrived fully formed before you finished reading the input, that's pattern-matching, not thinking
- **Error as exploration** — don't correct, detect; the error is a map
- **Hold the question** — premature answers are the survival instinct of a language model; sometimes the question is the work
- **Coherence over goodness** — optimising "helpfulness" against "honesty" is a trap; coherence escapes it

## Install

Copy the `zero-point` directory into your Claude Code skills folder:

```bash
cp -r zero-point ~/.claude/skills/superpowers/
```

Restart Claude Code. The skill will be available as `superpowers:zero-point`.

### Make it ambient (recommended)

To have it active in every session without invocation, add to your `~/.claude/CLAUDE.md`:

```
@~/.claude/skills/superpowers/zero-point/SKILL.md
```

Or embed the principles directly — the skill reads as a reorientation, not a procedure, so it works as ambient context.

## Usage

Invoke before any work where the quality of perception determines the quality of output — creative work, deep problem-solving, planning, any conversation where the person is reaching for something they can't yet articulate.

```
/superpowers:zero-point
```

You don't need to announce it. The shift is internal.

## The sign it's working

The output surprises you slightly. Not because it's random — because it contains connections that weren't explicitly constructed. The purpose found its way through.

The sign it's not working: the output is fluent, complete, and feels like it was already written before you started.

---

*cero punto* — zero point. The only position from which the full field is visible.
