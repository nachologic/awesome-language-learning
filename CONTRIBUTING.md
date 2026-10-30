# Contribution Guidelines

Thank you for your interest in improving Awesome Language Learning. Every suggestion is reviewed by hand, so following these guidelines is the fastest way to get your contribution merged.

## What belongs on the list

- Resources directly related to language learning: apps, websites, courses, blogs, books, podcasts, newsletters or tools.
- The link must work and point to the official site of the resource.
- Free, freemium and paid resources are all welcome, as long as they provide real value to learners.
- No affiliate or referral links.
- No pirated or otherwise illegal content.
- Abandoned projects and dead sites are removed when noticed.

## Self-promotion

Submitting your own project is allowed, but you must disclose your affiliation in the pull request description. Submissions are tested before merging and are not guaranteed a spot on the list.

## Format

- One resource per line, using exactly this format:

  ```markdown
  - [Name](https://example.com/) - Short description ending with a period.
  ```

- The name is the product name only, no taglines.
- The description is factual and concise. No marketing language, no superlatives like "the best" or "revolutionary", no emojis.
- Add new entries at the end of the relevant section.

## Placement

- Platforms that work across many languages go in **General Tools** in the main [README.md](README.md).
- Blogs, newsletters and advice about how to learn go in **Language Learning Tips** in the main README.
- Language-specific resources go in that language's folder at `languages/<language>/README.md`, under the correct skill heading (Courses, Vocabulary, Grammar, Pronunciation, Listening, Reading & Writing, Practice & Immersion, Guides & Tips). Start with plain skill headings; once a section holds several entries, split it into CEFR levels (A0-A1, A2-B1, B2-C2) following the [English section](languages/english/README.md).
- If a language is missing from the list, you may add its folder following the same structure and link it from the Languages section of the main README.
- If you are unsure where something belongs, say so in the pull request and we will figure it out together.

## How to submit

1. Fork the repository and create a branch named `add-<resource-name>`.
2. Make your change. For simple additions, only `README.md` should be touched.
3. Open a pull request with a short description: what the resource is, why it belongs on the list, and your affiliation if you have one.
4. Complete the checklist in the pull request template.

## Review process

- Links are checked automatically by CI on every pull request.
- A maintainer may try out the resource before merging, so reviews can take a little time.
- The maintainer may adjust the wording or placement of your entry. You keep full credit for the contribution.
