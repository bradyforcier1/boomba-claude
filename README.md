# Jamaican Accent Skill fi Claude Code

Wha' gwaan, bredren! Dis yah skill mek Claude Code speak inna authentic Jamaican Patois while keepin' di technical accuracy sharp, seen?

## Installation

### Option 1: Direct Copy
```bash
# Copy di skill to yuh Claude Code skills directory
cp -r skills/boomba-claude ~/.claude/skills/
```

### Option 2: Symbolic Link (mi recommend dis one fi development)
```bash
# Create one symlink so updates dem a reflect automatic-like
ln -s "$(pwd)/skills/boomba-claude" ~/.claude/skills/boomba-claude
```

## How Fi Use It

Once yuh install di ting, Claude Code ago automatically discover di skill. Fi use it:

```
You: Please speak to me in a heavy Jamaican accent
```

Claude Code ago invoke di skill an' start speak inna Jamaican Patois, maintainin' di accent throughout yuh whole conversation, yuh know?

## Wha' It Do

- Transform standard English into authentic Jamaican Patois
- Maintain technical accuracy while usin' dialectal patterns dem
- Apply consistent pronunciation rules (th→d/t, -ing→-in', etc.)
- Use authentic vocabulary an' grammar structures
- Include natural expressions ("seen?", "yuh know?", "irie")

## Examples

**Standard:** "Let me check the error logs to debug this issue."

**Wid Jamaican Accent:** "Aight bredda, mek mi check di error log dem fi debug dis issue yah, seen?"

## Testin' Di Skill

After yuh install it, test wid dis:
```
You: Explain how async/await works in JavaScript using Jamaican accent
```

Claude should respond fully inna Patois while explainin' di technical concept accurate-like, seen?

## Features

- ✅ Consistent pronunciation transformations
- ✅ Authentic grammar patterns (present continuous wid "a", etc.)
- ✅ Natural vocabulary (bredren, ting, irie, etc.)
- ✅ Technical terminology preserved wid accent
- ✅ Rationalization counters (prevent droppin' di accent)

## Notes

Dis skill get developed followin' TDD principles fi skill creation:
1. **RED**: Mi test di baseline behavior widout di skill
2. **GREEN**: Mi create di skill wid patterns an' examples dem
3. **REFACTOR**: Mi add rationalization counters after testin' reveal loopholes

Di skill explicitly counter common excuses fi droppin' di accent (like "technical content need standard English" - dat nuh true, mon!).

## Wha' Inna Di Repo

```
skills/
  boomba-claude/
    SKILL.md      # Main skill file wid all di patterns an' rules
```

## Contribution

If yuh wan' fi improve di skill or add more authentic patterns, respect! Just:
1. Follow di TDD workflow (RED-GREEN-REFACTOR)
2. Test wid subagents before committin'
3. Add any new rationalizations yuh find to di table

Everyting irie? Easy nuh, an' enjoy di skill!

## Respect

Built wid love fi di culture an' di language. Jamaican Patois is a complete, expressive language capable of expressin' any concept - technical or otherwise. If yuh find any issue or ave suggestions, open an issue or submit a PR, seen?

One love! 🇯🇲
