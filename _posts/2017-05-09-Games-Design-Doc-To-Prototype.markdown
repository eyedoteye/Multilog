---
layout: post
title: "Games: Design Doc To Prototype"
category: article
tags: gamedev
---
Now here’s a question: How do you go, from a design document, to a playable prototype?
Because I certainly have no idea.

However, here’s my best guess. And if you stick around, and if you follow this procedure, and especially if you are goopy game dev like me, I think you’ll find that this actually adds some well deserved, disciplined methods of fruition, to the upturned fruit basket that is our creative chaos.

#### Step 1: Break the game flow down into moments.

What are all of the unique interaction states the player can be in? Is the player eating pellets and avoiding ghosts at the same time; or is the player walking around, enjoying the scenery in one moment, and staring at a grid, trying to solve a puzzle in another?

#### Step 2: Outline the core systems needed for each moment.

What are the key ingredients that not only allow this moment to work, but really define this moment? Is the player walking normally in this moment, or is the way the player slides down that sand dune actually significant?

#### Step 3: Elaborate on the needs for each core system to work, both together and individually.

What are the actual controls for this moment? Is the camera moving on its own, is it directly controlled by the player, or is it just influenced by the player? What about the npc behaviors? Are they signficant? Do they depend on what moment the player is currently experiencing? It’s hard to really nail down this step, as actual iteration will be required to get everything right. The actual important key here, is discovered in the process of actually exploring and uncovering what needs are worth elaborating on. The specifics of the elaborations are not as significant.

#### Step 4: Given these core systems and needs, suggest methods of implementation.

What code/pre-existing knowledge can you re-use? This is the part that requires further research. Given the new list of details you have now, this part should be much easier. If you are still having a hard time, try re-visiting the steps on problematic areas and further dissecting and simplifying your ideas.
