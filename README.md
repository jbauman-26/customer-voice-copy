# Copy-Jake: a copywriting skill for Claude

Claude can write fluent sentences about anyone. The copy only lands when it knows who the reader
is, what hurts, and the words they use for it. This skill makes Claude do that thinking before it
writes, then strips out the lines that sound like AI.

Built by [Jake Bauman](https://www.linkedin.com/in/jake-bauman-marketing/).

## What it does

1. **Thinks first.** The 6 Ps: People, Positioning, Promise, Proof, Priority, Process. It asks
   for real customer words (reviews, tickets, calls) and marks gaps instead of inventing them.
2. **Writes the hook five ways** and scores each one: Benefit x Relevance x Credibility, divided
   by Perceived Effort. It keeps the winner.
3. **Edits in a fixed order.** The three-question line test, the 5 Cs (clear, concise, concrete,
   conversational, cadence), a voice pass and a kill pass for AI phrasing and em dashes.
4. **Handles cold outreach** reader first: their finding, the fix, a gift, then one short ask.

## Install

Claude Code, for every project:

```bash
git clone https://github.com/jbauman-26/copy-jake.git /tmp/copy-jake && cp -r /tmp/copy-jake/copy-jake ~/.claude/skills/
```

One project only: copy the `copy-jake` folder into `.claude/skills/` in that project.

Claude.ai or the Claude desktop app: zip the `copy-jake` folder and upload it under
Settings > Capabilities > Skills.

## Use it

Ask in plain words: "write a LinkedIn post about our new returns policy", "rewrite this
email", "give me 5 hooks for this ad". Or name it: "use copy-jake". Paste in real customer
reviews or comments for the best results. The skill will ask for them if you don't.

## Credits

The ideas are other people's. The wording here is ours.
- **Jay Yang**: the 6 Ps, the 5 Cs, the hook score, What Why How, But Therefore, and the CTA
  shape. [Copywriting masterclass](https://www.youtube.com/watch?v=OP_eMk_RCWg)
- **Harry Dry**, Marketing Examples: the three-question line test, the competitor swap test and
  the line rules. [Interview](https://www.youtube.com/watch?v=TUMjnmfsPeM)
- **Seth Godin**: the smallest viable audience.
- **Alex Hormozi**: the value equation.

## License

MIT. Use it, change it, share it.
