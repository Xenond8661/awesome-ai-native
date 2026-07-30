# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms.

## What belongs on this list

This list is about **AI-native** products and resources. The bar is deliberately high to keep it useful and free of marketing noise.

A product qualifies if:

- Its core value depends on an LLM, diffusion model, or modern ML system. Remove that model and the product stops working.
- For legacy products that rebuilt around AI: the AI experience must be the defining one today (think Attio-class CRM), not a chat panel bolted onto an otherwise unchanged workflow.
- It is shipping and usable by humans daily (consumer or practitioner). No research demos, no vaporware, no "coming soon".

A resource (blog, podcast, event, person) qualifies if it is useful for people building or running AI-native work.

## What does not belong

- "AI-powered" or "AI-first" products where the AI is a sidebar, a summarize button, or a semantic search add-on.
- Products that rebranded around AI without changing the underlying product.
- Dead or abandoned projects, no matter how influential they were.
- Your own project unless you genuinely believe it clears the bar. If you are unsure, open an issue and ask first.

## How to add an entry

1. Fork the repository and create a branch.
2. Add your entry to the appropriate section, in alphabetical order within that section.
3. Follow the exact entry format:

   ```
   - [Name](https://example.com) - Short description ending with a period.
   ```

   - One line per entry.
   - No trailing slash on URLs.
   - Description is one sentence, ends with a period, and explains what the tool actually does, not what it claims.
4. The URL should point at the product itself, not a blog post or a marketing landing page, unless the product lives inside a larger site.
5. Update the Table of Contents if you added a new section.
6. Open a pull request. In the PR description, explain briefly why the entry clears the criteria above. One or two sentences is fine.

## Quality checklist

Before you open a PR, check:

- [ ] The entry is in the right section.
- [ ] The section is still alphabetical.
- [ ] The link works and points to the expected page.
- [ ] The description is a single sentence ending with a period.
- [ ] You have read the *What does not belong* section above.

## Removing entries

Entries can be removed if a product shuts down, pivots away from AI, or turns out to be BS. Open an issue or a PR and explain the reason.

## Running the linter locally

This list is checked with [awesome-lint](https://github.com/sindresorhus/awesome-lint). You can run it yourself:

```
npx awesome-lint
```

The CI workflow will run it on every pull request.
