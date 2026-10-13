# Whop Quick Scaler and Launcher (unofficial)

**Skip the Whop docs. Install the working system.**

By Major. Unofficial. Not affiliated with or endorsed by Whop. Free and open source.

Describe what you sell. Your AI agent turns it into a Whop store you can trust: product, price, payment link and sales page, each one previewed, approved, saved and read back.

Built by Major. Nothing here is theory: it is the setup path, the traps and the playbooks we use on real stores.

## What you get

| | |
|---|---|
| **A guided setup** | Diagnose, frame the offer, prepare, apply after your approval, then a receipt of what was really saved. |
| **Field traps** | The mistakes that cost hours on real stores, each with its cause and its fix. |
| **Offer and pricing** | One-time or subscription, offers after purchase, discounts that actually show on the page. |
| **Sales page** | Structure, copy and image formats for a Whop page that sells. |
| **7-day launch** | What to publish, when, and what to ask your audience. |
| **Acquisition** | SEO articles with a team of agents, newsletter, social posts, product affiliates. |
| **Whop Partners** | How to earn on the businesses you bring to Whop, on 2 levels. |
| **Agent operations** | Running a business with AI agents: roles, approvals, checks before claiming success. |
| **Customer replies** | Failed payment, missing access, refund, double charge. |

Your agent never changes your Whop account without showing you the change first. No password or API key goes into the chat.

## Install

**Hermes Agent**

```bash
hermes skills install MAJOR-AGV/whop-quick-scaler-launcher/skills/whop-quick-scaler-launcher
```

Your agent now uses this skill whenever you talk about Whop. Want it to act on your store too? Add the plugin, which connects the official Whop MCP server:

```bash
hermes plugins install https://github.com/MAJOR-AGV/whop-quick-scaler-launcher
hermes plugins enable whop-quick-scaler-launcher
hermes mcp login whop
```

**OpenClaw (ClawHub)**

```bash
openclaw skills install @major-agv/whop-quick-scaler-launcher
```

**Claude Code, Codex, Cursor and other agents (skills.sh)**

```bash
npx skills add MAJOR-AGV/whop-quick-scaler-launcher
```

## New to Whop?

[Create your Whop account through Major's partner link](https://whop.com/start/?code=GITHUB). Already on Whop? Keep your account, everything works the same.

Disclosure: Major is a Whop Verified Partner and earns a commission from Whop (not from you) when businesses sign up through this link. After signup, the Whop partner team may contact you to help improve your offer and review your fees. No specific fee terms are guaranteed.

## FAQ

**Is this an official Whop product?** No. It is an independent tool by Major, built on Whop's official MCP server, CLI and documentation.

**Will it change my store without asking?** No. Every change is previewed and needs your approval. New offers stay hidden until you open them.

**Does it cost anything?** No. It is free and open source (MIT-0).

**Which Whop tools does it use?** The official hosted MCP (`https://mcp.whop.com/mcp`, OAuth sign-in), the official Whop CLI, and the Whop docs MCP.

## About Major

Major (Anthony Gonnet Vandepoorte) builds and runs businesses with AI agents.

[YouTube](https://www.youtube.com/@major-agv) · [Instagram](https://www.instagram.com/major_agv) · [X](https://x.com/majoragv) · [LinkedIn](https://www.linkedin.com/in/anthonygonnetvandepoorte)

If this saved you time, **star the repo**. It helps other sellers find it.

---

The Whop name and logo belong to Whop. This project is independent and not affiliated with or endorsed by Whop.
