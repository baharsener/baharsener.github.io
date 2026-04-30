---
layout: page
title: "Optimizing Remote Research for Young Children"
permalink: /projects/remote-research/
description: "Redesigning a study of children's mental models of time as a self-running animated protocol; same sample, a fraction of the time."
---

*Redesigning a study of children's mental models of time as a self-running animated protocol; same sample, a fraction of the time.*

**Role:** Lead designer of the remote redesign
**Dates:** 2020 to 2021 (started pre-pandemic, conducted during)n
**Methods:** Iterative pilot testing, asynchronous protocol design, custom stimulus delivery, attention-friendly pacing, parent-light interaction model
**Tools:** Qualtrics, custom JavaScript, narrated and animated video stimuli
**Collaborators:** Language, Cognition and Development Lab, University of Washington

## Context

The study examined how 5-year-olds represent time, an extension of developmental work on children's mental models of temporal order. The first round of data collection used a researcher-administered protocol delivered synchonously over Zoom, one family at a time. The second round was an opportunity to redesign the protocol for speed, scale, and inclusivity without compromising what was being measured.

## Situation

The original 9-month timeline broke down into three real bottlenecks. Recruitment relied on university participant lists, which take time and money to access and only include families in the area. Scheduling required syncing researcher and parent availability around school hours, naps, and parent work schedules. Testing volume was capped by researcher time, since each child needed a 1-on-1 session. The result was n=65 collected over 9 months, with 14% attrition (i.e., data collection was incomplete).

## Task

The brief was to redesign the protocol for the second round so that it would collect comparable data faster, with a more diverse sample, and with low enough parent burden that families would sign up willingly and feel the time was meaningful. The structure of the study otherwise could not change, to allow comparisons with the original sample. 

## Action

I started where most researchers in this position start: by trying to move the researcher's role to the parent. I recorded training videos that walked parents through how to administer the task. The first few pilot families revealed three problems. 1) Parent time commitment was high enough to deter sign-ups, 2) delivery was inconsistent across families in ways that could impact the data, and 3) children's engagement decreased because delivery felt unnatural, due to parents navigating an unfamiliar task.

I changed approach. Instead of training parents to be experimenters, I built an animated pseudo-experimenter. Narrated, animated video stimuli delivered task instructions, modeled the response procedure, and provided contingent feedback during practice trials (i.e., a different video played when a child got a practice question right than when they got it wrong). The whole protocol ran in Qualtrics with custom JavaScript handling the conditional logic, video playback, response capture, and even free-form answers. Parents only had to press play and, if their child could not use the mouse, click the child's answer.

I supported parents with a short instruction page rather than a training session, and added a debrief at the end with links to scientific articles related to the study. Parents could see what they had contributed to and why it mattered. This was a low-cost design choice that made parents more willing to sign up for future studies, which compounds across a research program.

I tested the redesigned protocol with a formal pilot cohort before launching at scale. Kid-specific design choices preserved from the in-person version: a fun, friendly, interactive format with direct feedback on practice questions. Adapted for asynchronous delivery: age-appropriate stimuli, attention-friendly pacing, frequent breaks, and inserted "fun breaks" (such as finding a picture of a cat among owls) that gave kids a reset between blocks without breaking the protocol.

![Before and after timeline showing the 9-month researcher-administered protocol collapsing to a 2-week asynchronous animated protocol](/assets/remote_research.png)

## Result

The redesigned protocol collected the same n=65 in 2 weeks, against 9 months for the original. Attrition dropped from 14% to 8%; more kids finished the study. The data replicated the in-person findings, which was the credibility check that mattered most.

Recruitment moved from university lists to an existing online research panel. The geographic reach expanded beyond the area near the university to families across the country. Specific demographic numbers are not mine to share, but the sample was broader on the dimensions that university-area-only recruitment systematically narrows.

The custom JavaScript code and the animated video-stimulus methods I built have since been adopted in two other studies in the lab. The reusability was not the original goal but a second-order outcome.

## User segment and method fit

There were two user segments: 5-year-olds and parents. They needed different things and the design had to serve both.

For the children, the surface had to be fun, easy enough to understand, and not so easy that it became boring. The methods preserved from the in-person version were the ones that did this work in the first place: clear interactive feedback on practice trials and age-appropriate stimuli. The asynchronous format added the constraint that there was no researcher to recover when something went wrong (e.g., confusion about a task).

For parents, the goal was to keep the burden minimal while still treating their participation as meaningful. They needed to know what they were contributing to (the article-linked debrief) because there was no researcher to debrief them.

## Trade-off reflection

The honest trade-off in moving from researcher-administered to a asynchronous protocol: researcher work moves to the back end. With a researcher present, problems get handled in real time. For example, a confused participant can be re-engaged, a misunderstood instruction can be rephrased, an attention dip can be paced around. With an asynchronous protocol, none of that is available, which means the work shifts to reviewing recordings and answers afterward to confirm the session went well.

The constraint is that you need enough pilot data to know which scenarios to design for, and enough investment in the stimulus design to handle them automatically. With those in place, the asynchronous protocol becomes more inclusive (it crosses time zones, school schedules, and geography), more parallel (data collection scales without scaling researcher hours), and lower-friction for families.

What this project taught me about rigor at speed: operational efficiency and methodological rigor are not always in tension, but they trade off differently across phases. The asynchronous protocol takes more effort upfront and during piloting, and less effort during collection. For a research program that runs many studies, the upfront investment compounds across reuse. For a one-off study, it might not.

[← Back to all projects](/projects/)
