---
title: Entropy and the size of stuff
description: Does entropy do much more than measuring the size of physical systems?
date: 2025-12-24
tags: entropy
---

I'll start with some ramblings on entropy, which is always an interesting topic for me
to think about.

Entropy, to me, is a strange beast. When people describe it they use words that are
closer to the realm of pseudoscience than what they use for many other physical
quantities: "disorder", "chaos", "information", etc. Even when trying to make statements
as precise as possible, these words creep into definitions. I can't shake the feeling
that there is something fishy about it.

Still, it is undeniably super useful in the physical sciences, and it has been super
effective in statistics and machine learning.

There are different quantities that people associate with the name "entropy". Most of
them are related enough that they can be lumped together into two main expressions:
the "Boltzmann" entropy and the "Gibbs / Shannon" entropy. Although in thermodynamics
and statistical mechanics entropy is conventionally given units through the constant
$k_{B}$, this is arbitrary, and I believe it is conceptually clearer to avoid units
altogether (use a dimensionless entropy).

The Boltzmann entropy is $S_{B} = \ln W$, where $W$ is the number of states a system can
be in, subject to some constratints. Many times people talk about the number of
"microstates", but I think this is a bit misleading, since it makes you think there is
something special about these states that makes them "micro", and states that don't have
this "micro" quality don't count somehow, when the truth is that states are just states.
In its origin, this entropy is clearly tied to physical systems, but there is no reason
why it couldn't be applied in other contexts, if it was useful.

Boltzmann entropy is, for me, the easiest to understand and reason about. Suppose you
can break a system $V$ apart into indivisible subsystems, $v$. This is something you can
usually do for systems that are "large enough", in such a way that the subsystems
interact "very weakly" (lets say short-range coupling / interactions dominate). In this
case the Boltzmann entropy is "just" proportional to the size of the system (in terms of
these subsystems). This is easy to see, since $W = v^N$ where $N$ is the size of the
system, and since $S_{B} = N \ln v$, the Boltzmann entropy is, up to a constant, equal
to $N$, so it measures how large the system is. The easiest example of this is
when the system is a number with a given length, the entropy is then "just" the number
of digits.

Although this definition and interpretation is pretty reasonable, its not satisfactory
to me. Logarithms are kind of weird, and I don't think I can make total sense of them
intuitively. If anything, entropy is one of the ways in which logarithms can be made to
make sense, or have the most "contact" with something physical (measuring size) to the
point where I wonder if the flow of understanding should be the other way around, from
entropy to logarithms.
