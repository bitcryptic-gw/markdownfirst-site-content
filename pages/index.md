---
title: "markdownfirst.com"
slug: ""
description: "MDF is a small open standard: your site hands AI agents a clean markdown page instead of the whole heavy web page, and, if you want, a price tag."
order: 0
layout: home
status: published

hero:
  headline: "Agents read the web. Let them read it in"
  highlight: "markdown."
  lead: "MDF is a small open standard. Your site hands AI agents a clean markdown page instead of the whole heavy web page, and, if you want, a price tag."
  actions:
    - label: "See the difference"
      href: "#race"
      style: primary
    - label: "Get the WordPress plugin"
      href: "https://github.com/bitcryptic-gw/mdf-analytics-wp"  # interim: switch to /for-site-owners/ when published
      style: secondary

unchanged:
  heading: "Nothing changes for your visitors."
  lead: "Same page, same address. People in a browser get your designed page, exactly as they do today. Only an agent that asks for markdown gets the tidy text version. MDF adds a door for agents. It doesn't move the front door."
  address: "yoursite.com/recipes"
  panels:
    - title: "A person in a browser"
      body: "gets your page, with its design, images and buttons. Just like now."
      art: browser
    - title: "one address"
      body: "The request says which version it wants."
      art: address
    - title: "An agent that asks"
      body: "gets the same words as clean markdown. An agent that doesn't ask gets the normal page."
      art: agent
  notes:
    - title: "Your pages stay put"
      body: "Same URLs, same design. Nothing to rebuild or redirect."
    - title: "Free stays free"
      body: "You choose what, if anything, has a price. Most sites charge nothing."
    - title: "Easy to undo"
      body: "Switch markdown off in the plugin, and everything is exactly as before."

compare:
  heading: "Same question. Same agent. Two very different trips."
  lead: "An agent fetches one web page. Without MDF it gets everything a browser gets and has to tidy it up. With MDF it asks for markdown and gets just the words."
  credit: "Token counts: Cloudflare's measurement of its own page as HTML and as markdown (Markdown for Agents, February 2026)."
  items:
    - label: "Without MDF"
      body: "The agent gets the full page: menus, ads, scripts and all. Then it cleans it up itself."
      art: messy
      tokens: "16,180"
      tokensNote: "tokens to read it"
      tone: orange
    - label: "With MDF"
      body: "The agent asks for markdown and gets one tidy page. If the page has a price, it pays and carries on."
      art: tidy
      tokens: "3,150"
      tokensNote: "tokens to read it"
      tone: blue

steps:
  heading: "How it works, in three doodles"
  items:
    - title: "Ask for markdown"
      body: "The agent adds one line to its request: `Accept: text/markdown`. People in browsers still get the normal page."
    - title: "Read the menu"
      body: "The site's `/mdf.json` says what's on offer and what each section costs. Most pages are free."
    - title: "Pay if it's priced"
      body: "A priced page answers with a bill: a Lightning invoice or USDC on Base. The agent pays and gets the page. No account, no subscription."

paths:
  heading: "Where do you come in?"
  items:
    - title: "I run a website"
      body: "Install the WordPress plugin, turn on markdown, and see which agents read your pages. Its self-test checks it's working."
      linkLabel: "Get the plugin"
      href: "https://github.com/bitcryptic-gw/mdf-analytics-wp"  # interim: switch to /for-site-owners/ when published
      tone: blue
    - title: "I build agents"
      body: "Send one header, read `/mdf.json`, and pay with any x402 client. Or plug in our MCP tool."
      linkLabel: "Point an agent at the demo"
      href: "https://mdf-demo.bitcryptic.com"
      tone: plain
    - title: "I like reading specs"
      body: "MDF 0.3.1 is open, on GitHub. A validator checks any site against it in seconds."
      linkLabel: "Read the spec"
      href: "https://github.com/bitcryptic-gw/mdf"  # interim: switch to /spec/ when published
      tone: orange

running:
  heading: "Running today"
  items:
    - title: "mdf-demo.bitcryptic.com"
      body: "The live demo: free pages, plus pages priced at 1 sat or 0.01 USDC."
      href: "https://mdf-demo.bitcryptic.com"
    - title: "blog.bitcryptic.com"
      body: "Our blog. Free MDF site, served as markdown to agents that ask."
      href: "https://blog.bitcryptic.com"
    - title: "prooflines.org"
      body: "ProofLines: off-node Monad network intelligence (validator geography, latency and stake concentration), sold one question at a time over x402 in native MON or USDC."
      href: "https://prooflines.org/monad/"

faq:
  heading: "Fair questions"
  items:
    - q: "Will my visitors notice anything?"
      a: "No. Browsers get your normal page. Only requests that ask for markdown get markdown."
    - q: "Do I have to charge?"
      a: "No. Pricing is optional, page by page or section by section. A free-only MDF site is a perfectly good MDF site."
    - q: "Will it get me cited more by AI search?"
      a: "We don't claim that, because nobody has shown it yet. What MDF does is make your pages cheap and clean for agents to read, and show you which agents read them."
    - q: "What does it cost to use?"
      a: "Nothing. The spec, the WordPress plugin, the reference server and the validator are all open source."
---

markdownfirst.com is the home of **MDF**, a small open standard for the agent-readable
web. Your site keeps serving the page it serves today. An agent that asks for markdown
gets a clean text version of the same page at the same address, and, if you want, a
price tag.

## Agents read the web. Let them read it in markdown.

MDF is a small open standard. Your site hands AI agents a clean markdown page instead of
the whole heavy web page, and, if you want, a price tag.

- [See the difference](#race)
<!-- interim: switch to /for-site-owners/ when published -->
- [Get the WordPress plugin](https://github.com/bitcryptic-gw/mdf-analytics-wp)

## Nothing changes for your visitors.

Same page, same address. People in a browser get your designed page, exactly as they do
today. Only an agent that asks for markdown gets the tidy text version. MDF adds a door
for agents. It doesn't move the front door.

- **A person in a browser** gets your page, with its design, images and buttons. Just like
  now.
- **One address.** `yoursite.com/recipes` serves both. The request says which version it
  wants.
- **An agent that asks** gets the same words as clean markdown. An agent that doesn't ask
  gets the normal page.

Your pages stay put: same URLs, same design, nothing to rebuild or redirect. Free stays
free: you choose what, if anything, has a price, and most sites charge nothing. Easy to
undo: switch markdown off in the plugin and everything is exactly as before.

## Same question. Same agent. Two very different trips.

An agent fetches one web page. Without MDF it gets everything a browser gets and has to
tidy it up. With MDF it asks for markdown and gets just the words.

| | Without MDF | With MDF |
| --- | --- | --- |
| What arrives | The full page: menus, ads, scripts and all | One tidy markdown page |
| What the agent does | Cleans it up itself | Reads it, and pays first if the page is priced |

Cloudflare measured its own page both ways: **16,180 tokens** as HTML and **3,150
tokens** as markdown. That measurement is Cloudflare's, from Markdown for Agents
(February 2026), not ours.

## How it works, in three doodles

1. **Ask for markdown.** The agent adds one line to its request: `Accept: text/markdown`.
   People in browsers still get the normal page.
2. **Read the menu.** The site's `/mdf.json` says what's on offer and what each section
   costs. Most pages are free.
3. **Pay if it's priced.** A priced page answers with a bill: a Lightning invoice or USDC
   on Base. The agent pays and gets the page. No account, no subscription.

## Where do you come in?

- **I run a website.** Install the WordPress plugin, turn on markdown, and see which
  agents read your pages. Its self-test checks it's working.
  <!-- interim: switch to /for-site-owners/ when published -->
  [Get the plugin](https://github.com/bitcryptic-gw/mdf-analytics-wp).
- **I build agents.** Send one header, read `/mdf.json`, and pay with any x402 client. Or
  plug in our MCP tool. [Point an agent at the demo](https://mdf-demo.bitcryptic.com).
- **I like reading specs.** MDF 0.3.1 is open, on GitHub. A validator checks any site
  against it in seconds. <!-- interim: switch to /spec/ when published -->
  [Read the spec](https://github.com/bitcryptic-gw/mdf).

## Running today

- [mdf-demo.bitcryptic.com](https://mdf-demo.bitcryptic.com): the live demo, with free
  pages plus pages priced at 1 sat or 0.01 USDC.
- [blog.bitcryptic.com](https://blog.bitcryptic.com): our blog, a free MDF site served as
  markdown to agents that ask.
- [prooflines.org](https://prooflines.org/monad/): ProofLines: off-node Monad network
  intelligence (validator geography, latency and stake concentration), sold one question at
  a time over x402 in native MON or USDC.

## Fair questions

### Will my visitors notice anything?

No. Browsers get your normal page. Only requests that ask for markdown get markdown.

### Do I have to charge?

No. Pricing is optional, page by page or section by section. A free-only MDF site is a
perfectly good MDF site.

### Will it get me cited more by AI search?

We don't claim that, because nobody has shown it yet. What MDF does is make your pages
cheap and clean for agents to read, and show you which agents read them.

### What does it cost to use?

Nothing. The spec, the WordPress plugin, the reference server and the validator are all
open source.

---

Open source. MDF 0.3.1. This page is served as markdown to agents too.
BitCryptic × Slepner.
