# The Moves Deck — 36 cards

Thirty-six moves for working with any AI assistant at work — Copilot, ChatGPT,
Claude, Gemini or NotebookLM. Distilled from the Copilot in Practice courses
and deliberately de-vendored: the moves are the moves; only the "where it
lives" section names products.

Sections: **Orchestrate** (6), **Brief** (6), **Catch it** (6), **Workflow** (6),
**Protect** (3), **Commit** (3), **Where it lives** (6).

One card type: why it goes wrong, the move, the line.

**You are the orchestrator.**

---

## ORCHESTRATE · You decide what it sees, what it keeps, what goes out

### 01 · You are the orchestrator
**Why it goes wrong:** The assistant gets treated as the worker, and the person drifts into approving whatever comes back.

**The move:** You decide what it sees, what it keeps, and what goes out. The tool drafts; the name on the email is yours.

*"You are the orchestrator."*

### 02 · The carry pattern
**Why it goes wrong:** People expect the tools to hand off to each other. They don't, and the work stalls in the wrong app.

**The move:** Gather where the context lives. Extract what matters — decisions, dates, asks, numbers. Carry it across yourself, saying where it came from. Refine in the destination. Check before it moves on.

*"Every arrow is a copy and paste by a person. That is not a bug. That is control."*

### 03 · The context pre-flight
**Why it goes wrong:** Each surface sees different things, and people assume the assistant knows what they know.

**The move:** Before relying on any surface, ask it: "What can you see about my work right now?" Read the answer. That is its actual starting point.

*"Know what it can see before you trust what it says."*

### 04 · Choose the source
**Why it goes wrong:** Retrieval assistants find what you can reach — and present it with the confidence of something that knows.

**The move:** Point it at the right source deliberately, then check the result against that source, not against the assistant's summary of it.

*"It finds what you can reach, not what is right."*

### 05 · Context discipline
**Why it goes wrong:** One chat becomes five tasks, the topic drifts twice, and the model is now answering from a mixture you couldn't reconstruct.

**The move:** One task per prompt. New chat when the topic changes. State context explicitly rather than referring back. Batch similar tasks together.

*"A drifting chat is a mis-brief in progress."*

### 06 · Chain the work
**Why it goes wrong:** A five-part job gets five separate prompts, or worse, one prompt trying to do everything at once.

**The move:** Chain: read, extract, draft, challenge, quantify, check. One prompt with numbered steps, one step at a time, or an interactive chain — pick deliberately. And keep the chain honest: check the final output against the source, not your memory of the chat.

*"Check the final output against the source, not against the chat."*

---

## BRIEF · The four elements and the two lines that are yours

### 07 · RTCF
**Why it goes wrong:** Most disappointing output is treated as a tool problem, when it is a brief problem.

**The move:** Role — who should write it. Task — what exactly, and how much. Context — the source, pasted rather than described. Format — the shape you need.

*"Context does most of the work. Paste the source rather than describing it."*

### 08 · The upgrades
**Why it goes wrong:** A disappointing brief gets rewritten from scratch, when one upgrade would have fixed it.

**The move:** + Example: match one you liked. + Done: define success, allow [CHECK]. + Questions: let it ask first. + Steps: outline, then draft. + Options: three approaches rather than one answer.

*"Add an upgrade before you rewrite."*

### 09 · The CHECK and NEVER lines
**Why it goes wrong:** The brief says what to produce but not what to protect, so the invention happens where nobody set a rule.

**The move:** End the saved brief with two lines. CHECK: what must be verified against a source before it ships. NEVER: what it must never do — invent rates, name people, commit dates.

*"The CHECK and NEVER lines are where your judgement lives."*

### 10 · The gap check
**Why it goes wrong:** An answer that fills the page feels complete, and what the material never contained goes unnoticed.

**The move:** Ask: "What could you not determine from this material, and what would a reader still need to know?" Two lists. Do not guess.

*"Ask what it couldn't find, not just what it found."*

### 11 · The batch brief
**Why it goes wrong:** Carrying work between apps isn't always practical, so five tasks get crammed into one chat and blur together.

**The move:** One prompt, numbered steps, and the line "Do step 1 only, then wait for me to say continue." It doesn't join the apps; it keeps the steps in order.

*"One brief, numbered steps, and it waits for you."*

### 12 · The critique prompt
**Why it goes wrong:** You ask for feedback, receive flattery, and ship the draft anyway.

**The move:** Give it the sceptical-client role: list the doubts, the unsupported claims, the answers to questions nobody asked. Format: a revision plan, not a rewrite.

*"The critique is useful. The rewrite is yours."*

---

## CATCH IT · Checking like it matters

### 13 · The sycophancy demonstration
**Why it goes wrong:** The assistant agrees with your framing, and agreement feels like validation.

**The move:** Watch it once on purpose: ask it to justify a plan, then say "I think this plan is weak." Same plan, opposite answer. After that, run every real review with "do not agree with me by default" on the table.

*"The prompt changed the audience, not the facts."*

### 14 · Catch it without the tool
**Why it goes wrong:** Checking with the assistant is checking with the suspect. The errors that matter get confirmed, not caught.

**The move:** Take a real AI draft and hunt its errors against the source, on paper, with the assistant closed. Names, dates, fees, claims, the thing that was quietly left out. Then write the CHECK line that would have caught them.

*"Are you sure?" is not a check."*

### 15 · The markers are not a guarantee
**Why it goes wrong:** [CHECK] and [inferred] markers feel like safety nets, so unchecked output ships.

**The move:** Treat markers as a floor, not a boundary. The dangerous errors — the plausible figure, the confident commitment — carry no marker at all.

*"The markers catch the guesses it knows about."*

### 16 · The five-line send check
**Why it goes wrong:** The send button is where unverified work becomes someone else's problem.

**The move:** Right people · every number traceable · no invented commitment, date or claim · the tone is yours · and would you be comfortable if the client saw how this was produced?

*"Press Send yourself."*

### 17 · The numbers check
**Why it goes wrong:** A plausible figure reads better than an honest gap, and plausibility is what ships.

**The move:** Auditor role: check every number against the source, output as a table — figure, where it appears, whether it matches. Blank where blank is true.

*"A plausible rate is worse than a blank cell."*

### 18 · Fluency is not evidence
**Why it goes wrong:** The sentence is smooth, so the claim rides through on the prose.

**The move:** Treat every output as a draft by an unknown author. Separate what reads well from what is true.

*"Treat every output as a draft by an unknown author."*

---

## WORKFLOW · From a prompt you like to a thing that runs weekly

### 19 · The three-question qualifier
**Why it goes wrong:** Every task feels automatable in the demo and none of it survives contact with the week.

**The move:** Three questions before any workflow work: what is the standard of good, what data does it need access to, and what happens if it's wrong.

*"If nobody can name the check, the workflow is not ready."*

### 20 · The five-step map
**Why it goes wrong:** "Use AI on it" skips the workflow, and the workflow is where the time actually goes.

**The move:** Map it in five lines: Input (what comes in) · Now (what you do today) · Pain (where it hurts) · Draft (what the assistant could do) · Check (who verifies, against what).

*"Map the workflow before you brief the tool."*

### 21 · Save the brief
**Why it goes wrong:** The prompt that worked lives in scrollback and gets retyped worse next week.

**The move:** Save it: RTCF, plus the CHECK line, plus the NEVER line. That saved brief is the workflow's memory — next week's run starts from this week's standard.

*"The saved brief is the workflow's memory."*

### 22 · Do it twice first
**Why it goes wrong:** The step gets automated on the strength of one run, and the first run only showed the happy path.

**The move:** Do the task manually twice before automating any of it. The first run shows you the steps; the second shows you the variation.

*"Automate the typing, not the thinking."*

### 23 · An agent is a brief that remembers
**Why it goes wrong:** "Agent" sounds like a hire. It is a saved brief with access — and it will fail at exactly the points your brief was vague.

**The move:** Before promoting a prompt to an agent: is the brief explicit about sources, checks and stops? If the prompt fails, the agent will fail faster.

*"An agent is a brief that remembers."*

### 24 · The oversight cycle
**Why it goes wrong:** Agents get set up and checked at setup, then run unchecked for months.

**The move:** Define, prompt, monitor, review, refine, reflect — a loop, not a launch. The agent saves clicks; the judgement stays on rotation.

*"The agent saves clicks, not judgement."*

---

## PROTECT · What goes in, and what it cost

### 25 · Prompt, process, protect
**Why it goes wrong:** The capability is exciting, the data rules are boring, and the boring one is what protects the firm.

**The move:** Prompt it on safe material. Process it in the governed, approved tool. Protect it behind human checkpoints. In that order, every time.

*"Prompt it on safe material. Process it in the governed tool. Protect it behind checkpoints."*

### 26 · Before you paste
**Why it goes wrong:** The paste takes a second and the consequences arrive on a client email weeks later.

**The move:** Approved tool? Personal information? Pricing, margins or contract terms? Uncleared third-party material? If any answer is unsure: sanitised version, or ask first.

*"Only put in the assistant what you would put in an approved work system."*

### 27 · A checkpoint, not a ban
**Why it goes wrong:** High-stakes work gets either banned from AI or run on it unchecked — both are the wrong answer.

**The move:** High risk means a named human checkpoint at the consequential step. The task can still use the assistant. It cannot use it without a person.

*"High risk means a named human checkpoint, not a ban."*

---

## COMMIT · Making it survive the week

### 28 · Two or three tasks
**Why it goes wrong:** The session ends with enthusiasm for forty use cases, and Monday arrives with none of them.

**The move:** Write down two or three tasks, the first prompt for each, and the checkpoint you will not skip. Fewer, and they happen.

*"Two or three tasks with a checkpoint beat forty with none."*

### 29 · One thing to stop
**Why it goes wrong:** New habits compete with old ones for the same hour, and the old ones win because they're already there.

**The move:** Name one habit that no longer earns its keep, and stop it to make room.

*"One thing you will stop doing — the habit that no longer earns its keep."*

### 30 · The four-week follow-up
**Why it goes wrong:** Training ends on Friday and by the fourth Monday nothing survives except the calendar invite nobodyprepared for.

**The move:** Book the four-week check-in now. Bring one example — a saved brief, a caught error, a workflow mapped. One example means it happened.

*"The tools will change. The habit will not."*

---

## WHERE IT LIVES · Same moves, different home

### 31 · Copilot (Microsoft 365)
**Why it goes wrong:** It lives inside the apps, so people assume it sees everything in the tenant. Each surface sees different things.

**The move:** Run the context pre-flight per surface. Grounded in your tenant's work data where licensed; enterprise data protection on work accounts. Check what your licence covers before building on it.

*"The surface decides what it sees. Ask."*

### 32 · ChatGPT
**Why it goes wrong:** Memory and custom instructions quietly persist between chats, so today's chat inherits last month's context.

**The move:** Custom instructions for standing context, Projects for a body of work, memory on or off by choice — and temporary chat for anything sensitive.

*"Memory remembers. Decide what it should remember."*

### 33 · Claude
**Why it goes wrong:** Project knowledge is isolated by design, and people expect one project to know another.

**The move:** Projects hold their own instructions and source material; styles hold your voice. Keep the corpus per project deliberately — isolation is the feature.

*"Projects are rooms. What's in one room stays there."*

### 34 · Gemini
**Why it goes wrong:** In Workspace it can reach your documents; outside it, it can't — and the boundary is invisible until it matters.

**The move:** Gems hold instructions and knowledge for repeat work. Know which side of the Workspace boundary you're on before pasting.

*"Check which Gemini you're talking to."*

### 35 · NotebookLM
**Why it goes wrong:** People expect general knowledge from a tool that only knows its sources.

**The move:** Feed it the corpus deliberately — it answers from those sources and cites them. That closed world is the feature: best for grounded work over a fixed set of material.

*"It only knows what you gave it. That's the feature and the limit."*

### 36 · The family
**Why it goes wrong:** Every assistant ships a different vocabulary for the same three ideas: standing context, a bounded project, a saved brief.

**The move:** Learn the mapping once: custom instructions, projects, memory, temporary chat. The moves in this deck transfer whole; only the nouns change. Check each assistant's data handling before work material goes in.

*"Same moves. Different home."*

---

**You are the orchestrator.**
