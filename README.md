# NextGen Query Fan-Out Generator

**See the hidden searches AI search runs behind your topic, then write the blog post that answers them all.**

**[Open the tool](https://msilviasanti.github.io/query-fan-out-generator/)** · Free · No sign-up · Works with any AI chat

---

## What is query fan-out?

When someone asks Google AI Mode, AI Overviews, ChatGPT, Claude or Perplexity a question, the engine doesn't run just that one search. It breaks the question into many smaller searches, reads the best passages from each, and writes a single answer from them.

Google calls this **query fan-out**. In its own words, AI Mode works by "breaking down your question into subtopics and issuing a multitude of queries simultaneously on your behalf", and Deep Search "can issue hundreds of searches" ([Google, May 2025](https://blog.google/products-and-platforms/products/search/google-search-ai-mode-update/)).

Those hidden searches decide which pages get quoted. No engine shows them to you. This tool predicts them.

## Who it's for

Content marketers and copywriters who write blog posts and want them to show up in AI answers, without needing to know SEO jargon.

## What it does

| Step | What you get |
|---|---|
| **1. Type your topic** | Choose where it should show up (Google AI Overviews, AI Mode, ChatGPT, Claude, Perplexity), plus the language and market. |
| **2. See the hidden searches** | The searches AI is likely to run, grouped by what readers want and ranked *Must answer*, *Should answer* or *Nice to have*, each with the best format to answer it (table, steps, direct answer…). |
| **3. Get a blog outline** | A suggested title and an H2/H3 structure in reading order, showing which searches each section answers. Copy it as Markdown or download it. |
| **4. Check your draft** | Paste your text to get a coverage score, a *covered / partial / missing* status for every search, and the three fixes that matter most. |

### The seven search types

| Type | What it means for your post |
|---|---|
| Hidden needs | What readers want to know but didn't type |
| Related questions | The next questions people ask on the same topic |
| Comparisons | This vs that, alternatives, which is better |
| Names & places to mention | Brands, places, products and people AI expects to see named |
| Specific situations | The same topic for a budget, a group, a season or a location |
| Fresh & timely | What's new, changed or current this year |
| Other ways to ask | Same need, different wording: answer once, use the wording |

### Native phrasing per market

Queries are written the way people in each market actually search, not translated from English. Supported: English (global, UK, US), Italian, Dutch (Netherlands, Belgium), German, French and Spanish.

## How this version of NextGen Query Fan-Out Generator works

This is the **static version**: a single HTML page with no server and no API key.

1. You fill in your topic and click **Get my prompt**.
2. Copy the prompt into any AI chat (ChatGPT, Claude, Gemini, Copilot; a free account works).
3. Paste the answer back. The page turns it into the grouped searches, the outline and the coverage check.

The page sends nothing anywhere. Your last result stays in your own browser.

## Honest by design

AI search engines don't publish their fan-out queries, and they vary from user to user. These results are **informed predictions** made by an AI model reasoning the way AI search does, not data pulled from Google or any AI assistant. Use them to plan sections, FAQs and internal links, then confirm demand in Google Search Console or your keyword tool.

## Run it yourself

It's one file. Download `index.html` and open it in your browser, or fork this repository and turn on GitHub Pages (Settings → Pages → Deploy from branch → `main`).

## License

MIT. Use it, fork it, adapt it.
