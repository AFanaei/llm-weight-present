---
theme : "night"
transition: "slide"
highlightTheme: "monokai"
slideNumber: false
title: "Open-Weight"
---

## LLMs Openness

---

### About Me

<div style="display:flex;">
<div style="flex-grow: 1">
<ul>
<li>Ahmad Fanaei</li>
<li>Programmer since 2006</li>
<li>CTO at Torob since 2017</li>
<li>We are hiring! <a href="https://jobs.torob.com/">jobs.torob.com</a></li>
</ul>
</div>
<div>
<img src="./photo.jpg" width="100px">
<br/>
<img src="./logo.png">
</div>
</div>

---

### Agenda
- Introduction
- Why Openness Matter
- Open source and LLMs
- Open-weight
- Other gotchas

---

<!-- .slide: data-transition="slide" data-background="#b5533c" -->
## Introduction

---

<figure>
    <img data-src="./tweet.png" alt="tweet">
    <figcaption><a href="https://twitter.com/ylecun/status/1681336284453781505">link</a></figcaption>
</figure>

---

<figure>
    <img data-src="./not-open.png" alt="not-open">
    <figcaption><a href="https://blog.opensource.org/metas-llama-2-license-is-not-open-source/">link</a></figcaption>
</figure>

--

> Additional Commercial Terms. If, on the Llama 2 version release date, the 
monthly active users of the products or services made available by or for Licensee, 
or Licensee's affiliates, is greater than 700 million monthly active users in the 
preceding calendar month, you must request a license from Meta, which Meta may 
grant to you in its sole discretion, and you are not authorized to exercise any of the 
rights under this Agreement unless or until Meta otherwise expressly grants you 
such rights.

--

1. Violate the law or others’ rights.
2. Engage in, promote, incite, facilitate, or assist in the planning or development of activities that present a risk of death or bodily harm to individuals.
3. Intentionally deceive or mislead others.
4. Fail to appropriately disclose to end users any known dangers of your AI system.

<a href="https://ai.meta.com/llama/use-policy/">use-policy</a>

---

### neural network (NN)
- Training (data) -> (weights)
- Inference (weights) -> (result)

--

<img data-src="./train.gif" alt="train">

--

### Components
- Data
- Model weights
- Source code

---

### Large Language Model
- very large NN
- trained on all available written data

--

<img data-src="./gpt.gif" alt="train">

---

### Review
- NN
- LLMs
- Components of NN

---

<!-- .slide: data-transition="slide" data-background="#b5533c" -->
## Why Openness Matter

---

### AI Safety and the Age of Dislightenment
- Power imbalance
- Maybe opensource is the key
- Security through obscurity


<a href="https://www.fast.ai/posts/2023-11-07-dislightenment.html#open-source-and-a-new-era-of-ai-enlightenment">link</a>

---

### We Have No Moat, And Neither Does OpenAI

- Things we consider “major open problems” are solved and in people’s hands today
- They are doing things with 13B params that we struggle with 540B
- Who would pay for a Google product with usage restrictions if there is a free, high quality alternative without them?

<a href="https://www.semianalysis.com/p/google-we-have-no-moat-and-neither">link</a>

---

<!-- .slide: data-transition="slide" data-background="#b5533c" -->
## open source and LLMs

---

### Why Ai licensing is complex
- AI has multiple components that are licensed differently.
- AI also poses socio-ethical consequences

--

### NNWs is not Source Code
- The software community created the open source concept as a means to make source code available to anyone for use, modification, and distribution
- NNWs are different. They represent the 'knowledge' an artificial neural network has learned and are often stored as large matrices of numbers.

---

<!-- .slide: data-transition="slide" data-background="#b5533c" -->
## Open-Weight

---

- allow all recipients to use for any purpose.
- allow all recipients to modify for any purpose.
- The license must not discriminate against any user, industry, or purpose.
- The model must be provided along with access to the NNWs.
- The software used to train the model must be provided under an open source license
- The license must allow all recipients to provide the model, or modifications of the model, to others.
- The license must allow any license notices or NNWs to be provided via an online reference.

<a href="https://github.com/Open-Weights/Definition">link</a>
---

<figure>
    <img data-src="./sidsibrandy.png" alt="not-open">
    <figcaption><a href="https://opencoreventures.com/blog/2023-06-27-ai-weights-are-not-open-source/">link</a></figcaption>
</figure>

---

### why its not good

The question is whether or not open weights are enough for a model to be called open source; a software analogy would be a project releasing its binaries without the source code to re-build it from scratch.

---

<figure>
    <img data-src="./open-part1.png" alt="not-open">
    <figcaption><a href="https://opening-up-chatgpt.github.io/">link</a></figcaption>
</figure>

--

<figure>
    <img data-src="./open-part2.png" alt="not-open">
    <figcaption><a href="https://opening-up-chatgpt.github.io/">link</a></figcaption>
</figure>

---

<!-- .slide: data-transition="slide" data-background="#b5533c" -->
## Other Gotchas

---

### What is the licence of AI output

- if you use photoshop to create a photo, that photo is belong to you
- what if you use stable diffusion to create an image, to whom the generated photo blongs
  - the original content creator whose work was used to train ai
  - the company who created the ai model
  - the person who used the model to create a photo

---

### Plligrism or Copyright Infringement
- Github-copilot: emmits non-permissive license code <a href="https://codeium.com/blog/copilot-trains-on-gpl-codeium-does-not">link</a>

---

## thank you
