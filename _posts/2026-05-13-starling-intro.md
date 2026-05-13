---
title: 'Introducing Starling'
date: 2026-05-13
permalink: /posts/2026/05/starling-intro/
tags:
  - Starling
---

# Introducing Starling

> “Look between the stars for what you need. The untraceable black of the possible...What does it mean to listen darkly?” (Healing Justice Lineages)

## Other Formats

* I gave a talk about Starling which you can watch on [Vimeo](https://vimeo.com/1190846080).

* The writing in this post is also available in a the format of a [zine](https://github.com/starlinglang/zines/blob/main/starling.pdf).

## Why another proof assistant?

I was in a [directed reading program](https://www.ams.org/opportunities/view/listing?listing_id=493237) for number theory which opened my eyes to the importance of proofs in mathematical discovery. 

What do the proofs of the future look like?  Can computer-aided proofs answer questions that pen-and-paper proofs are unable to answer?

## Philosophy

I believe that new types of proofs make new kinds of knowledge possible.  

For example, the invention of diagonalization proofs enabled a slew of monumental results in the 19th and 20th centuries such as Godel’s incompleteness theorem.  Late in the twentieth century, a computer enabled the first ever proof of the four color theorem. 

Will computer-aided proofs define the 21st century in the way that diagonalization proofs defined the 20th?

## How does it work? 

Starling can be seen as a surface language for the existing language [Metamath](https://us.metamath.org/). Starling compiles to Metamath, inheriting its [library](https://github.com/metamath/set.mm) of verified proofs, as well as the [Metamath proof verifier(s)](https://github.com/metamath/set.mm/blob/develop/verifiers.md). [Starling’s compiler](https://github.com/starlinglang/starling) is written in JavaScript.

## Why Metamath?

I was particularly interested in Metamath because of its agnosticism toward different object logics. This enables you to write Metamath proofs whose theorems are derived from the axioms of quantum logic, for example.

## Can I get involved?

I'm interested in designing this language to be as user-friendly as possible, so I am looking to interview people about their experiences [using Starling](https://starling-lang.org/editor/index.html). If that seems interesting to you, [please talk to me](https://calendly.com/nam10114-nyu/30min)!

## Why even try something like this?

> “If you find yourself inside a dimming world, remember it was always this dark inside the body.”  (Ocean Vuong)

> “The future is dark, which is the best thing the future can be, I think.” (Virginia Woolf)
