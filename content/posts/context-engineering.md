+++
author = "Mark Barta"
title = "My Context Engineering Workflow"
date = "2026-06-21"
description = "Forks, branches, and scratchpads.  Does claude know I'm awkward?"
tags = [
    "AI Engineering",
    "Context Engineering",
    "Engineering Leadership",
]
categories = []
aliases = ["/posts/my-context-workflow/"]
draft = false
+++



I spend more time iterating with Claude on our plans than anything.  As I read blog posts and reddit threads, it seems like that's common. We're all iterating over markdown files and trying to setup our agents for success.

My process looks something like this:
1) Define the outcome clearly
    - Allow users to log in via a form.
2) If I know something ahead of time, I'll list that requirement out
    - Make it a veritcal form and include SSO at the bottom
3) Claude will identify gaps and offer suggestions

On larger projects and code bases, you repeat this quite a few times.  As you break down the project and explore, new questions come up.  I'll wind up having 5-10 sessions open to drill into different repos or to investigate a question.  Some people probably use subagents for this, but that feels clunky to me and not something easy to manage.  When I saw [cmux](https://github.com/manaflow-ai/cmux), I thought it was the perfect tool to manage all my sessions, but I think we need to go past terminal management.

So I wrote my own this weekend.

![context-manager](/img/context-manager.png)

- Clear forking/branching in the UI.  As I drill into problems, I can spawn a new session with the same conversation.  With the UI, I don't have the mental overhead of what session is what.
- Consolidating agent responses.  Move a child session's response to the parent and continue.  As you make more decisions, this can help build context.
- Context scratchpad.  Move agent responses to a scratchpad.  Spawn a session with the content from the scratchpad.  This helps start sessions grounded in truth.
- Group sessions by working directory aka projects.
- Each session checkpoints the file system.  Go back and forth, rewind and branch without commiting to your changes.

This definitely leans into my process. Now, it's easy for me to take parts of a claude session that I've reviewed and incorporate that into larger decisions.  Each one building on each other until I have a clear, accurate picture of the work.  For larget work, I can compose the plan in the scratchpad and kick off new sessions with that context already.