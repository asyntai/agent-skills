# Asyntai AI Chatbot skills for coding agents

Agent skills that add an [Asyntai AI chatbot](https://asyntai.com) to any
website and run it from your coding agent. They work with Claude Code, Codex,
Cursor, GitHub Copilot, Gemini CLI, OpenCode, Windsurf and the other agents
that read `SKILL.md` files.

## Install

```bash
npx skills add asyntai/agent-skills
```

Or install one skill:

```bash
npx skills add asyntai/agent-skills --skill add-ai-chatbot
```

## Skills

| Skill | What it does |
| --- | --- |
| `add-ai-chatbot` | Adds the Asyntai AI chatbot to a website or web app. It finds the stack (HTML, React, Next.js, Vue, Nuxt, SvelteKit, Angular, Astro, Laravel, Django, Rails and more) and puts the widget in the right layout file. For hosted platforms (WordPress, Shopify, Wix, Webflow, Squarespace and 100 more), it gives the matching install guide. |
| `manage-ai-support-agent` | Connects the Asyntai MCP server and runs the agent from chat: add knowledge, crawl a site, edit instructions, change the widget look, read conversations and leads, and reply live to visitors. |

## Try it

After the install, ask your agent:

- "Add an AI support chatbot to this site."
- "Add the pages of example.com to my Asyntai chatbot and test it."
- "Show me what visitors asked my chatbot this week."

## About Asyntai

Asyntai is an AI customer support agent for websites. It answers visitors from
your own content in more than 80 languages, collects leads and lets your team
take over a chat at any time. Create a free account at
[asyntai.com](https://asyntai.com).

Docs for these skills: [asyntai.com/documentation/integrations/agent-skills](https://asyntai.com/documentation/integrations/agent-skills/)

Install guides: [asyntai.com/documentation/installation](https://asyntai.com/documentation/installation/)

## License

MIT
