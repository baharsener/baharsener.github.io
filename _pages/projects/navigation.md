---
layout: single
title: "Iterative Design of a Cross-Age Virtual Navigation Game"
permalink: /projects/navigation/
description: "A Unity-based research tool that works across childhood and adulthood, refined through iterative pilot testing with kids."
---

*A Unity-based research tool that works across childhood and adulthood, refined through iterative pilot testing with kids.*

**Role:** Co-designer and co-lead (with [Alice Smaniotto Aizza](https://www.linkedin.com/in/alice-smaniotto-aizza-61a590166/))
**Context:** Academic research, Language, Cognition and Development Lab, University of Washington (cognitive offloading across development)
**Methods:** Behavioral observation, post-session parent and child debrief, parent surveys (video game and keyboard experience), adapted think-aloud, iterative pilot testing
**Tools:** Unity (self-taught), open-source assets

## Context

We know little about how children spontaneously use strategies to reduce internal memory load by relying on external cues (i.e., cognitive offloading). This is especially true for navigation tasks, for which adults often offload information to maps and landmarks. The substantive research goal was to characterize how those strategies develop across age. The methodological problem was that no existing paradigm let us do that cleanly in a computer task.

## Situation

We had two options on the shelf and neither worked. Real-world navigation tasks have ecological validity but no experimental control: the environment changes between participants, you cannot manipulate the cue structure cleanly, and kids and adults move through space differently in ways that are hard to standardize. Traditional computerized maze tasks have control but are difficult to modify for specific task demands we want to adapt.

We needed a paradigm that was a real game (engaging enough to keep a 6-year-old to the end), with a controlled environment (so we could compare directly across ages), and with mechanics that could scale in complexity without changing methodology. There was no budget and no Unity expertise on our team.

## Task

Alice and I were charged with delivering a navigation game in Unity that could be used as a study paradigm across the full age range. The must-haves were that it had to be usable across ages 6 to adult, fun enough that kids finished it, and scalable in complexity without forking the methodology between age groups. The failure case would have been needing a different task for kids than for adults; that would have made cross-age comparison impossible.

## Action

We learned Unity from YouTube tutorials and built the environment using free assets. We tested with kids and adults using essentially the same protocol, but the iteration cycle was driven by what we observed in kids. The reasoning was that adults can absorb complexity that kids cannot; if you design for the harder case first, adults inherit a working version. If you design for adults first, you have no idea which parts will fail with kids until you test, and by then you have already committed to design decisions.

![Iterative design loop showing the four-stage build-test-observe-revise cycle and three real iterations](/assets/images/navigation.png)

The pilot loop produced three substantive design changes:

**Iteration 1: Goal clarity.** The youngest children could not complete the navigation task. Post-session debriefs with parents made clear that the issue was not navigation skill; the kids did not understand the goal (collect targets quickly). We extended the practice phase and wrapped the task in a storyline: the items they were collecting were ingredients for a potion. After this change, the youngest children engaged with the task and completed it.

**Iteration 2: Input device.** Even after the goal was clear, kids varied wildly in how comfortable they were with arrow keys. Parent surveys on video game and keyboard experience confirmed the variation was about prior exposure, not ability. We swapped the arrow keys for a joystick. This removed the input-device confound across ages.

**Iteration 3: Time pressure.** Kids ignored the verbal time limit. Saying "you have 4 minutes" is not useful for a 6-year-old; the constraint did not register, then suddenly the time was up and they were upset. Adults accepted the verbal limit but reported wanting a visual aid. We added an on-screen countdown timer. After the change, time pressure became a motivating element rather than a frustrating one.

A note on the diagnostic challenge: when a child takes a long time on a task, it is not always obvious whether the slowdown is input-related (the keyboard is awkward) or comprehension-related (they are unsure what the goal is) or motivation-related (they have lost interest). You can only tell by changing one thing at a time and watching what moves. This is why the iterative design loop was load-bearing rather than a nice-to-have.

## Result

The current state of the environment includes three different virtual environments with matched mechanics across age groups. The age range it actually works for spans 6 to adult. The environment was tested with 78 participants across three cohorts (n = 28 ages 6-8, n = 20 ages 9-12, n = 30 adults).

The tool will be made openly available to other researchers, both as a usable paradigm and as a methodological case study in how to build cross-age developmental research instruments.

## User segment and method fit

The two user segments here are children (roughly 6 to 12) and adults. The mechanism is identical across them; what differs is the size and complexity of the environment (children's maps are smaller with fewer items to remember) and the surface design (storyline framing, joystick input, visual time aid).

The kid-specific methodological adaptation worth highlighting: we did not ask children "how did you play this game?" because they would say "I played." Instead we asked, "if another kid was going to play this game, what would you tell them about how to play?" This indirect framing surfaced strategy use that direct introspection could not. It draws on a broader principle in research with children, where indirect or third-person framings often elicit more useful data than first-person retrospection.

Iterative pilot testing was the right choice, rather than a one-shot validation, because issues with kid-tested research instruments are unpredictable. You cannot tell from theory whether arrow keys are an obstacle or whether a 4-minute verbal time limit will register. You have to test, observe, and change one thing at a time. Each iteration removed an interpretive ambiguity from the data, not just a usability barrier.

## Broader contribution

This work is partly a tool other researchers can adopt and partly a methodological case study in cross-age research design. The principle that surfaces clearly: design for the harder population (kids) first, and adults will inherit the working version. The reverse design path leaves you stuck.

[← Back to all projects](/projects/)
