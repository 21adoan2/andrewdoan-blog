---
title: "The hardest industry to design for"
author: "Andrew Doan"
source: "https://medium.com/@21adoan2/the-hardest-industry-to-design-for-47cf16b41ca3"
date: "2026-02-20"
retrieved: "2026-05-09"
---
After talking with a coworker the other day, I’m now convinced: design at Anduril *might* just be the hardest thing to design.

We often talk about “hard” problems in design as if they are a monolith. Usually, that means navigating complex business logic or untangling a messy legacy codebase. But at Anduril, the difficulty is multiplied.

To understand why, you have to look at the Venn diagram of modern design challenges. Most industries deal with one or two of these variables. We are designing for all of them, simultaneously:

-   **High-pressure:** A soldier could be out in the field getting shot at while flying a drone with their ATAK device or in the tight quarters of a moving tank, attempting to command and control their assets with a rusty laptop.
-   **Time-sensitive:** Decisions are made in seconds, not sprint cycles. The battlefield can change at any time; the ability to quickly respond is key.
-   **Classified**: At times, you might not even know the real scenarios or real data. Imagination and feedback are your best bet.
-   **Collaborative**: Often involves teams with role-based control working in tandem. Chains of command require robust approval and auditing features, but never at the expense of mission-critical timing.
-   **Hardware-centric:** We aren’t just moving pixels; we are moving robots. The software must be a seamless extension of physical machines.
-   **Autonomous robots**: We are designing for a fundamental shift in human agency. The user is no longer a “pilot” controlling a joystick; they are a “commander” directing intent.
-   **Adversarial in nature:** This is a **red versus blue** reality. You aren’t just designing a tool for a user; you are designing a tool to be used against a real, unpredictable opponent who is actively trying to thwart the mission.
-   **Massive scale:** We aren’t just managing a single asset. We are building systems that allow a human to command and control hundreds, even thousands, of autonomous robots at once.
-   **Critical software**: This is not a social media app or design tool. Mistakes can lead to the loss of human life. A common tech quote I’ve heard used at Meta is: “We aren’t saving babies.” In this case, the stakes are *actually* just as high as that.

To put into perspective, let’s discuss some adjacents.

[](/plans?source=promotion_paragraph---post_body_banner_unlock_stories_blocks--47cf16b41ca3---------------------------------------)

**Gaming** is perhaps the closest relative. If you’ve ever played a high-stakes competitive strategy game, you know the feeling: it’s high-pressure, tactical, and deeply **adversarial**. It checks almost every box. But there is a ceiling to the comparison. In a game, if the interface fails or the “unit” is lost, you hit restart. In our world, the “critical” element isn’t a mechanic — it’s the mission.

**Healthcare** is the other logical comparison. An ER management suite is certainly critical and time-sensitive. It involves life-saving hardware and intense collaboration. But even in the highest-stakes medical environment, the “adversary” isn’t a human agent. The disease isn’t watching your screen, looking for a UI vulnerability to exploit so it can counter-move.

This is what makes this work the hardest thing I’ve ever designed for. It is the intersection of the **criticality** of healthcare with the **adversarial** friction of a “red versus blue” engagement, all while managing a robotic fleet at a scale that was science fiction a decade ago.

In this environment, “good design” isn’t about making things pretty or about solving for one variable. It’s a huge, messy ontology of a problem. We are building the interface for a new kind of autonomy — one where the stakes are absolute, and the problems are never-ending.
