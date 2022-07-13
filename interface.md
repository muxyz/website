---
permalink: /interface
layout: default
title: "Interface"
---

Human computer language interface

## Overview

Micro is taking a new approach to interface development that builds on a living breathing environment.
The Micro development model has been proven out over a number of years using the [Go](https://go.dev) based programming language and
supplementary client libraries which enable broad access to developers. Consumption of services without programming however will
require a completely different method.

We propose the development of a client interface to compliment the development model which focuses on the end consumer. Where developers
and operators will focus on the infrastructure and programming, the client interface will enable anyone to access services via web or mobile.
Ideally using existing well known constructs like messaging and voice.

## Design

Micro theorises of a human computer interface built on the foundations of real world services rather than any
sort of formally defined spec. It is firstly not a replacement for any existing programming language 
such as Go, java, ruby or python and does not attempt to be comparable to current programming models.

The goal is to lay the foundation for an emergent language where the keywords are 
services and all we attempt to do is define a grammar to associate these services 
in a cohesive way that then lets us perform actions at a higher level. This allows 
our language to naturally evolve and become more powerful over time.

The assumption is that we can steal from the likes of bash while creating something 
purely human readable or with a fixed type set for interop between services. We 
should also include the ability to save new programs as the aggregate of many 
others but in lazy loaded fashion as with haskell execution.

```
# a service call to the store
# [service] [method] [input] [value]
> store write foo bar

# retrieve the output
> store read foo

# storing the output of such a command
> save result = store read foo

# evaluating the output
> exec result

# passing the output to an input
> input result into broker publish values
```

## Potential

The longer term potential for such a language is that it becomes a higher level form of consumption for services. 
At a given point when enough services have been written, they become building blocks capable of being combined 
to perform other forms of actions. Continuing to use existing programming languages to orchestrate these 
services becomes wasteful. Dynamic languages do not currently exist to perform operations on services.

By escaping the current programming boundaries we can elevate to a new intermediary representation that can 
either be leveraged by human beings more easily, spoken as commands or used for other purposes.

## Outcome

The goal is to serve as a new command & control system driven through messaging and voice. Micro looks to 
be human user friendly and integrate into the daily lives of people. The only way this is possible is 
to focus on the user interaction in a way we're already comfortable with. Operations are defined in 
real world language not programming centric models closer to human than machine.

## Environment

When we talk about a living breathing environment what we're really saying is a system that's growing and 
evolving. Traditionally programming languages are based on fixed source code and implementations that are 
static. Whereas human languages have emerged in an evolving environment we know as space and time. 

A cloud can be thought of as a growing and evolving environment yet largely controlled by singular entities. 
Rather, a network, is one in which anyone participates and evolves and morphs through that 
participation.
Micro's interface will be backed by an open [Network](/network) of services, using a protocol based on web3 technologies. 
A living, breathing environment that continues to grow and evolve to service the needs of Micro's users. One that's 
crowdsourced rather than controlled by any single company.

## Consumption

Micro should be consumable on web, mobile, desktop and voice devices along with whatever emerges in future. This likely 
means starting with a focus on commands via messaging and then moving into speech to text and NLP in the longer term. 

## References 

- [Real World Programming](https://www.researchgate.net/publication/221045770_Real-world_programming)
- [Low-Code and the Democratization of Programming](https://www.oreilly.com/radar/low-code-and-the-democratization-of-programming/)
- [Just in time compilation](https://en.wikipedia.org/wiki/Just-in-time_compilation)
- [Micro Services Network](https://mu.network)
- [Fourth Generation Programming Language](https://en.m.wikipedia.org/wiki/Fourth-generation_programming_language)
- [Natural Language Interface](https://en.m.wikipedia.org/wiki/Natural-language_user_interface#:~:text=Natural%2Dlanguage%20user%20interface%20(LUI,modifying%20data%20in%20software%20applications.))

