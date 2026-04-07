# Chat Crafter

**The first lightweight web tool that truly understands chat fiction — from group chat POV switching to message quoting, so writers can focus on storytelling.**

> Used by fanfiction writers in China to create "捡手机文学" (pick-up-phone stories) — fictional narratives told entirely through chat screenshots.

![POV Switch Demo](assets/pov-switch-demo.gif)

**[Try it live →](https://www.chatcrafter.top/)**

---

## What Is This?

On China social media, there's a wildly popular fanfiction format called **"捡手机文学"** (pick-up-phone literature) — stories told entirely through fake chat screenshots, as if you picked up someone's phone and scrolled through their conversations.

Writers build these scenes message by message: choosing who says what, when, and from whose perspective — then export the result as a long image to post on social media (Rednote, Weibo, LOFTER).

**Chat Crafter is a visual editor for building these scenes.** Think of it as a screenplay editor, but the output looks like a real chat app.

![App UI Screenshot](assets/app-ui.png)

---

## What Makes It Different?

There are a few chat screenshot tools out there. None of them were built for fiction writers. Here's what Chat Crafter does that they can't:

### POV Switch — One tap, everything flips
Switch whose phone you're looking at. All bubbles swap sides, and contact names update to match that character's address book. Works in **both single chat and group chat**.

> No existing tool supports group chat POV switching. The closest competitor only handles single chat.

![POV Switch](assets/pov-switch.gif)

### Message Quoting — Nested reply bubbles
Characters can quote-reply to earlier messages, just like in a real chat. This is essential for realistic group conversations — and **zero competitors support it**.

![Message Quoting](assets/quote-reply.gif)

### Timestamp Cascade — Edit one, shift all
Change a message's timestamp, and all subsequent timestamps shift to stay in order. No more manually fixing 50 messages because you moved one scene earlier.

![Timestamp Cascade](assets/timestamp-cascade.gif)

### Plain Text Import — Paste a script, get a scene
Paste your script in `Character: Dialogue` format and it parses into message cards instantly. Writers draft in notes apps first — this bridges the gap.

![Text Import](assets/text-import.gif)

### Long Image Export — One tap, ready to post
Export your entire conversation as a paginated long image — the exact format readers expect on Rednote and Weibo. On iOS, saves directly to Photos via Web Share API.

![Long Image Export](assets/long-export.gif)

### Story Management — Organize by fandom, not by chat
Group conversations into stories and fandoms. Because writers think in narratives, not chat logs.

![Story Management](assets/story-management.gif)

### Mobile-First — Built for how writers actually work
Inspiration strikes at midnight on your phone. Chat Crafter is a lightweight web app — open it in any browser, no download, no app store. Desktop works too.

![Mobile Responsive](assets/mobile-responsive.gif)

### ...and the basics done right
- **Undo** (20 steps per conversation)
- **Bulk select** — copy text, reorder, delete multiple messages
- **Local auto-save** — IndexedDB persistence, never lose your work

---

## Real Users, Real Stories

Chat Crafter isn't a portfolio toy — writers are using it to publish real works.

<!-- Replace with your actual Rednote post screenshot showing likes/saves -->
![Rednote Post](assets/rednote-post.png)

<!-- Add more examples as you collect them -->
<!-- ![User Work Example](assets/user-work-1.png) -->

---

## Built with Vibe Coding

I'm a data scientist, not a frontend developer. I built Chat Crafter using **Claude Code** as my coding partner. I made every product and architecture decision, Claude wrote the code, and I reviewed every line.

The interesting part isn't the React code. It's the product thinking:

- **User research first** — interviewed real fanfiction writers, analyzed 170+ comments of current fanfiction writers, mapped every pain point before writing the code
- **Real competitive analysis** — tested the top 3 most popular existing tools (微截图, Talkmaker, 真言截图) hands-on, identified the gaps no one was filling

This is a product built on research, not vibes.

---

**[Try it live →](https://www.chatcrafter.top/)**

