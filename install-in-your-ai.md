# Install It in Your AI Agents

## Memory, not an attachment

A manual you paste into one conversation helps that conversation. A manual your AI agents hold helps every one after it, across every agent you run. The difference is where you put the file, and it takes about five minutes.

This is the half most people skip, and it's the half that compounds.

---

## Why the honesty standard matters more here

Your team corrects for an inaccurate manual. Quietly, and over time, but they do it. Someone reads "bring me the recommendation, not the problem," watches you interrupt three recommendations in a row to ask for the raw data, and updates their private model of you without ever saying so.

Your AI agents won't do that. They have no private model to update. Each one reads what you wrote, takes it as fact, and operates as that leader in every draft it produces. Write that you want brevity when you actually want the reasoning shown, and you'll get clipped summaries forever, each one technically compliant with a document you wrote about someone you aren't.

So the aspirational manual is survivable in a team and corrosive in a model. Run the aspiration sweep in [`template.md`](template.md) before you install, not after.

---

## The four surfaces

Install it in as many of these as apply to you. They do different jobs.

### 1. Memory

The durable one. Your manual becomes standing context in every new conversation, with nothing to attach and nothing to remember.

Paste the manual, then say:

> Add this User Manual to memory and use it as context in every future interaction. When you draft, decide, or prioritize on my behalf, operate from it.

Then verify it took. Start a fresh conversation and ask what it knows about how you make decisions. If it comes back generic, the write didn't land and you should check your tool's memory settings.

**What this changes.** Drafts arrive closer to right. Priorities line up with how you actually operate rather than with a composite of what a leader sounds like.

### 2. Project or workspace instructions

Where you want the manual applied to one body of work rather than everything. A project for board material, a workspace for a specific team, a custom assistant you built for one job.

Paste the manual into the project's instructions or knowledge, and add one line above it naming the job:

> Everything below is how I think, decide, and communicate. Apply it to every output in this project.

**What this changes.** Scoped consistency. Useful when you want one register for board communication and a different one for internal drafting.

### 3. A file in the repo

If your team works in a codebase, or in any repository where agents read a standing instruction file, the manual belongs there as a file the agents load. Depending on your tooling, that's `CLAUDE.md`, `AGENTS.md`, or whatever your stack reads at startup.

Put a short pointer at the top of the instruction file and the manual in its own file beside it. Pointer, not paste, so the manual stays a single source you update in one place.

**What this changes.** Every agent operating in that repo inherits your standard, including the ones you didn't configure yourself.

### 4. Agent system prompts

Any agent acting on your behalf, and this is the category that's growing: a scheduled automation that writes your weekly summary, an agent that triages your inbox, a tool that drafts replies. Each one has a system prompt, and most of them are running on nothing but a task description.

The manual goes in, or a pointer to it does. Emphasize the sections that govern the agent's actual job. An inbox triage agent needs your communication standards and your triggers far more than it needs your feedback philosophy.

**What this changes.** The agent stops making decisions a generic assistant would make and starts making the ones you would.

*Platform specifics move fast. The instructions above are deliberately written to survive that, but memory features, project structures, and instruction-file conventions all changed during 2026 and will change again. Accurate as of September 2026. Check your tool's current documentation for where the memory setting lives.*

---

## The test that tells you whether it worked

Everything above is easy to claim and easy to fake. Here's a test that can actually fail.

1. Before you install, pick one real piece of work you'd normally hand off. A message you have to send, a document that needs a first pass, a decision that needs framing. Ask your AI for it. Keep the output.
2. Install the manual.
3. Ask for the same thing, in a fresh conversation, with the same request.
4. Now pick three specific triggers or standards from your own manual and check both outputs against them. Not "does it feel more like me." Three named things. If your manual says don't bury the lede, look at where the ask sits. If it says name the tradeoffs, count them. If it says never escalate without a recommendation, see whether one is there.

If the second output moves on all three, it took. If it moves on none, the manual is too abstract to operate from, and the fix is in the document rather than the install. Go back and put a behavior next to every principle.

That last failure is the common one, and it's diagnostic. A manual an AI can't act on is usually a manual your team couldn't act on either. You just found out faster.

---

## Then hand it to your team

The other destination, and the sequence matters. Give it to one person first and run the recognition test in [`template.md`](template.md). Fix what they tell you. Then send it wider, with one line about what it's for and an explicit invitation to tell you where it's wrong.

The strongest version of this isn't your manual reaching everyone. It's each leader who reports to you writing their own, for the team that reports to them. One document makes you legible. A layer of them makes the organization legible, and that's a different order of return.

---

*[Storied](https://storiedinc.com)*
