# online-dating-protocol

An Agent Skill that turns Claude into an evidence-based online dating coach: it audits a dating-app profile, plans the photos, writes the bio and prompts, sets up the app, scripts the messaging from match to second date, rebuilds Instagram, and runs a weekly KPI review.

Every recommendation is labelled by evidence tier (research, platform data, aggregated user data, practitioner advice, unverified), with sources.

## What's inside

`SKILL.md` is self-contained:

1. How the apps rank you (Tinder's official factors, why Elo is outdated, 2026 features)
2. Reset protocol (when to delete and how long to wait)
3. Photos: research findings, a 5-criterion scorecard, six photo slots, hard rules, photographer brief
4. Bio, prompts and structured fields (what to fill, what to leave empty, and why)
5. App settings, daily discipline, what to pay for
6. Messaging: benchmarks, the short match-to-date sequence, icebreakers, reading interest, first and second dates, what to do when things go wrong
7. Instagram
8. Small markets, reputation and professional boundaries
9. Timeline, KPI dashboard and weekly review
10. Evidence base (25+ studies and datasets) with limits

## Install

**Claude Code:** copy the folder to `~/.claude/skills/online-dating-protocol/` (personal) or `.claude/skills/online-dating-protocol/` in a project.

**Claude apps:** zip the `online-dating-protocol` folder and upload it as a custom skill in your settings (skills must be enabled for your account).

Then ask things like "audit my Tinder profile", "write my Hinge prompts", "what do I reply to this match?" or "build me a 12-week dating plan".

## Scope and caveats

- Built and tested for men seeking women on Tinder and Instagram, where most of the published data comes from. It adapts to other apps and audiences, but numbers from one population don't always transfer.
- Most studies use students and lab-rated photos; platform figures are correlations published by companies. Your own weekly data beats everything in here.
- Not legal, medical or therapeutic advice.

## Credits

Research and data sources are listed at the end of `SKILL.md`. Some practitioner frameworks (profile as landing page, photo scorecard, four-part bio, short texting sequence) are adapted and rewritten from dating-coach material by Dating By Blaine. This project is not affiliated with or endorsed by Dating By Blaine, Tinder, Hinge, Bumble, Match Group or any other company mentioned.

## License

MIT, see `LICENSE`.
