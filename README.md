# learn

A claude code skill that teaches you a subject without giving you the answer.

To protect myself against AI-induced cognitive decline, I created this simple skill for learning about new subjects. 

Claude asks questions, gives hints, works through analogous examples and builds toy examples. 
You do the thinking. 

I mostly use it for mathematics and computer science topics, and I find it really enjoyable. It reminds me of my undergraduate semesters, staring for hours at problems that seemed unsolvable (they weren't!). And then this big great feeling of joy when it finally clicks.
## Install

```bash
git clone git@github.com:tomlouisklein/learn.git ~/.claude/skills/learn
```

## Usage

- `/learn <topic or question>` starts a session.
- `/learn reveal` tells you the solution. This is the only way to get it. Claude first asks for your best guess.
- `/learn stop` ends the session with a short recap of what you worked out.

## Note: disable prompt suggestions

Claude Code suggests your next prompt, which results to it answering its own questions.
Turn it off: run `/config` and set **Prompt suggestions** to `false`.