# Remotion Video Production

**Turn natural language briefs into rendered MP4s using Claude Code and Remotion — covers project setup, composition generation, and the render/iterate loop.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Produce software product demos, feature-announcement videos, and marketing animations without a video editor or motion-design background. Three skills that work in sequence — Remotion Setup scaffolds a project wired for Claude Code Agent Skills, Remotion Compose turns a natural-language brief into a complete React/TypeScript composition, and Remotion Render handles export plus the feedback-and-re-render loop — and each is independently useful once a project is underway. Built for developers, product teams, and solo founders who want to describe a video and get a rendered MP4 back.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/remotion-video-production](https://skillme.dev/pack/remotion-video-production) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/remotion-video-production`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Remotion Setup](skills/remotion-setup/SKILL.md)** — Scaffolds a new Remotion video project wired for Claude Code Agent Skills — Node check, create-video scaffold, skills install, folder conventions, Google Fonts, and a smoke-test render.
- **[Remotion Compose](skills/remotion-compose/SKILL.md)** — Turns a natural-language video brief into a complete Remotion composition (.tsx) — scene plan plus animated React/TypeScript components using useCurrentFrame, interpolate, spring, AbsoluteFill, and Sequence.
- **[Remotion Render](skills/remotion-render/SKILL.md)** — Renders a Remotion composition to MP4 and runs the iterate loop — CLI render command, 1080p/4K/9:16 presets, --concurrency tuning, surgical edit-and-re-render cycles, batch variants from a JSON data file, and Lambda for cloud rendering.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
