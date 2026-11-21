---
title: "How it works"
slug: "how-it-works"
description: "The request, the menu and the bill: what actually happens between an agent and an MDF site."
order: 10
nav: "How it works"
layout: page
status: draft
---

This page will walk through one request end to end: the agent sends `Accept: text/markdown`
to a URL a browser would also load, the site answers with markdown and `Vary: Accept`, and
a priced page answers with a bill instead of a body until the agent pays. It is a draft
because the walk-through needs a real request and response pair pasted from the reference
server, not a paraphrase of one.
