# Customer Voice Copy: a copywriting skill for Claude

Claude can write fluent sentences about anyone. The copy only lands when it knows who the reader
is, what hurts, and the words they use for it. This skill makes Claude do that thinking before it
writes, then strips out the lines that sound like AI.

Built by [Jake Bauman](https://www.linkedin.com/in/jake-bauman-marketing/).

## What it does

1. **Finds and maps the reader.** It pulls your reviews and customer talk on its own, then
   maps today, frustrations, fears and dreams in your customers' own words.
2. **Thinks first.** The 6 Ps: People, Positioning, Promise, Proof, Priority, Process. It finds
   real customer words itself (reviews, tickets, calls) and marks gaps instead of inventing them.
3. **Writes the hook five ways** and scores each one: Benefit x Relevance x Credibility, divided
   by Perceived Effort. It keeps the winner.
4. **Edits in a fixed order.** The three-question line test, the 5 Cs (clear, concise, concrete,
   conversational, cadence), a voice pass and a kill pass for AI phrasing and em dashes.
5. **Handles cold outreach** reader first: their finding, the fix, a gift, then one short ask.

## Install

Claude Code, for every project:

```bash
git clone https://github.com/jbauman-26/customer-voice-copy.git /tmp/customer-voice-copy && cp -r /tmp/customer-voice-copy/customer-voice-copy ~/.claude/skills/
```

One project only: copy the `customer-voice-copy` folder into `.claude/skills/` in that project.

Claude.ai or the Claude desktop app: zip the `customer-voice-copy` folder and upload it under
Settings > Capabilities > Skills.

## Use it

Ask in plain words: "write a LinkedIn post about our new returns policy", "rewrite this
email", "give me 5 hooks for this ad". Or name it: "use customer voice copy". Paste in real customer
reviews or comments if you have them. If you don't, the skill goes and finds them: your
project files, connected tools, your site and public reviews. Connect
[Firecrawl](https://www.firecrawl.dev) and it also searches Reddit and community forums for
the pain points your customers keep repeating.

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
