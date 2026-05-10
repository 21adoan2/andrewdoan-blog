---
title: "How can AI be designed to be more human-centric?"
date: "2024-03-21"
author: "Andrew Doan"
source: "https://medium.com/@21adoan2/on-the-design-of-ai-how-can-ai-be-designed-to-be-more-human-centric-5ab7bfaf4587"
retrieved: "2026-05-09"
---


*Artificial Intelligence (AI) tools, ranging from virtual assistants to complex machine learning applications, have revolutionized how we interact with technology. Yet, user experience and interface design of AI fall short of maximizing their potential. Why are AI tools often designed and perceived as assistants? In what ways is AI revolutionizing the way humans interact with technology? I intend to explore these questions, and more, in hopes of starting a conversation amongst designers on how we should improve the design of AI tools.*

## What does AI currently look like?

When we think of modern AI, we think of ChatGPT or Google’s Gemini AI, both chatbots. We might also think of Spotify’s AI DJ, a personal DJ for your music taste. There’s also hardware-centric AI like Google Assistant or Amazon Alexa. Or the often-overlooked classic: Apple’s Siri. For simplicity, I’ll focus on the design of chatbots.

![Splashes of popular AI tools including ChatGPT, Google Assistant, Spotify DJ, Amazon Alexa, and Apple’s Siri](https://miro.medium.com/v2/resize:fit:1400/1*u6ln_UZ_UZZs_1Oez0K4LA.png)

AI, nowadays, typically takes the form of “assistants;” this is the [dominant mental model](https://www.nngroup.com/articles/mental-model-ai-assistants/) that people, especially new users, associate AI with, according to [Nielsen Norman Group](https://www.nngroup.com/) (NNG). By definition, an assistant is a general helper meant to support a higher authority.

## Effects of Portraying AI as an Assistant

Portraying AI as an assistant has a few implications for how users interact with this technology: (1) it primes users for intent-based outcome specification, (2) it personifies AI technology, and (3) it places the user above technology.

1.  Jakob Nielsen claims AI is the [third paradigm shift](https://www.nngroup.com/articles/ai-paradigm/) (and the first in 60 years) in UI history. AI will shift human-computer interaction from command-based interaction to intent-based outcome specification. This means that with AI, rather than the user telling the computer *what to do*, the user tells the computer *what they want*, a small but important distinction. Designing AI as an “assistant” primes users to tell AI what they want rather than what to do, just like how a boss would tell their assistant what they want (i.e. “I need this week’s reports by EOD”).
2.  The way AI is currently designed primes users to project and attach human qualities to the new technology, even going as far as forming relationships with AI. NNG defines [4 degrees of AI personification](https://www.nngroup.com/articles/anthropomorphism/). Viewing AI as a human can lead to misunderstandings because users may adopt unrealistic expectations of the new technology.

![](https://miro.medium.com/v2/resize:fit:1400/1*KsczlTSiLjgcDg9nF38pVA.png)
*NN/G describes 4 degrees of the personification of AI*

3\. Assistive AI portrays to users that they are ultimately in control of AI. While AI might know more than users, this dynamic primes users to use and view AI as a tool (on top of dispelling dystopian images of sentient AI taking over).

## What problems do users have with the design of current AI tools?

The caveat of designing AI as an assistant is that users expect the assistant to converse in human ways. However, AI has a low tolerance for ambiguity and cannot preserve context to carry on conversations. According to [NNG](https://www.nngroup.com/articles/mental-model-ai-assistants/), users are frustrated by AI misinterpretation and inability to pick up and retain context.

### Low Tolerance for Ambiguity

As an example, if a user asks ChatGPT, “Write me a thank-you email template,” it likely won’t give a satisfactory response, because the request is not specific enough. What’s the occasion for the thank-you email? Who is the sender and who is the recipient? What should the tone of the email be? These are all important questions that AI tools fail to prepare users to consider in their requests. For instance, ChatGPT’s suggested prompts are not specific enough to yield ideal AI responses.

![](https://miro.medium.com/v2/resize:fit:1400/1*uviVRMYquTyzoLTqPYlo-A.png)
*ChatGPT’s suggested prompts*

Google’s Gemini AI offers more specific prompts.

[](/download-app?source=promotion_paragraph---post_body_banner_surround_blocks--5ab7bfaf4587---------------------------------------)

![](https://miro.medium.com/v2/resize:fit:1400/1*wUH2XHCYUEU7nSnuFaQL5g.png)
*Google Gemini AI’s suggested prompts*

Despite more thorough suggestions, the time and effort it takes to craft such a specific response remains a pain point for users, especially when they already expect AI to converse in human ways.

### Inability to Preserve Context

When users interact with AI assistants, they expect to be able to ask follow-up questions. Current AI design leaves little room for users to build upon previous requests and have meaningful discussions. From [NNG’s article on mental models of AI assistants](https://www.nngroup.com/articles/mental-model-ai-assistants/), a user mentions:

> “I have learned that \[Siri\] is bad at staying on track with what I’m currently talking about. For instance, I asked her about local movie times for local movie theaters; she listed the movies that were showing, so I said ‘what times does ‘Incredibles’ have.’ She told me the times, then I said ‘how about Jurassic park?’; she then pulled up something completely unrelated to movie times.”

This is a common problem among assistive AI chatbot users, as well. Although ChatGPT and Gemini organize requests by “chats” that retain chat history and context, misunderstandings still arise.

![](https://miro.medium.com/v2/resize:fit:1400/1*kOyCdA6JHeWh14qHXapTjQ.png)
*Gemini AI (left) and ChatGPT (right) Chat History Features*

## As designers, how might we address these frustrations and design AI interfaces & experiences?

While I recognize that real solutions require user testing and research to confirm, here are a few spitball ideas:

-   **Organize by user intentions:** Design experiences that require users to define their context and goals. Imagine a “study” or “work” mode that tailors responses to these social environments.
-   **Context-aware interactions:** Design interfaces that dynamically adapt to the user’s current context, including previous interactions, location, and ongoing tasks.
-   **Context building:** Incorporate features that allow users to build upon previous conversations and make follow-up requests.
-   **Prompt suggestions:** Train users to make specific requests that AI can adequately respond to.
-   **Clear and consistent communication:** Employ feedback mechanisms to keep users informed about the assistant’s understanding and actions. Allow users to see how AI responses are generated.
-   **Customizability**: Allow users to customize the AI’s personality, tone, level of detail, interface capabilities, etc.

## What will the future of AI look like?

As AI continues to grow and scale, I expect the design of AI to move away from chatbots and assistants to more abstract designs that mimic GUIs yet mask much more complex capabilities. AI is already beginning to do more than just answer questions; there are image generators, coders, and video editors on the rise. Future AI designs will seamlessly incorporate all of these new functionalities “under the hood,” while retaining an intent-based interaction model. Eventually, I imagine that AI will pave the way for a future where apps will no longer exist; instead, there will be a personal tool that can do it all.

![](https://miro.medium.com/v2/resize:fit:1400/0*gvIuIW3n_twOBPDL.png)
*Natural AI by Brain Technologies is already ideating for this future!*
