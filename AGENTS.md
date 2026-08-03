# Swartzism

A blog about a doctrine of information power — built from the record of Aaron Swartz, and stress-tested against the questions the record raises.

The word "Swartzism" does not exist in Swartz's own writing. He never founded an "-ism." This blog argues that the record nevertheless implies one: that knowledge about the world is a commons, that information is power and must be accountable, and that data about persons is protected absolutely.

## Repository Structure

| Path | Description |
|------|-------------|
| `_posts/` | Jekyll blog posts (markdown, Jekyll front-matter) |
| `_layouts/` | Jekyll layout templates (default, page, post) |
| `index.html` | Blog home/landing page |
| `about.md` | About page |
| `feed.xml` | RSS feed template |
| `404.md` | 404 page |
| `_config.yml` | Jekyll configuration |
| `Gemfile` | Ruby dependencies (GitHub Pages) |

## Conventions

- **Theme**: Type Theme for Jekyll (light/dark mode via `prefers-color-scheme`), adapted from `semantic-thinking`
- **Accent**: deep crimson (`#b91c1c` family) — doctrine red, distinct from semantic-thinking's blue
- **Evidence discipline**: every claim about Swartz's record carries a hyperlinked primary source. No invented quotes. No hagiography — the record includes failures and the doctrine must survive them.

## Deployment

GitHub Pages publishes `master` branch to https://ccagentorg.github.io/swartzism/.

## Setup

```bash
bundle install
bundle exec jekyll serve  # local dev at http://localhost:4000/swartzism/
```

## Content Guidelines

1. **Record-first**: each post starts from the documented record (essays, manifesto, actions) and argues outward. The doctrine is a construction *from* the record.
2. **Cite everything**: every non-obvious claim has a hyperlinked source (primary where possible: aaronsw.com, archive.org, court records, contemporary reporting).
3. **Stress-test the doctrine**: posts may attack the doctrine's own claims. Open questions are answered in place, not hidden.
4. **The boundary is load-bearing**: Swartzism's PII boundary — data about the world is a commons, data about persons is protected absolutely — is not negotiable in this blog's framing.
5. **Tone**: analytic, precise, non-polemical. No outrage, no clickbait, no cult.

## Related

- **Doctrine source**: `Projects/swartzism/` in the workspace — `PRINCIPLES.md` (axioms, PII doctrine, guardrails, canon), `MANIFESTO.md` (founding text), `REVIEW.md` (adversarial review log). The blog is the public distillation; the doctrine folder is the analytical machine.
- **Practice projects**: `Projects/bad-apples-india/`, `Projects/rohini/`, `Projects/cbse-osm-osint/` — projects that practice the doctrine's principles in the field.
- **Sister blog**: [Semantic Thinking](https://ccagentorg.github.io/semantic-thinking/) — structured reasoning applied to contested ideas.
