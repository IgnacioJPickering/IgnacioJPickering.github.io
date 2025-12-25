---
title: Entropy and the size of stuff
description: Does entropy do much more than measuring the size of physical systems?
date: 2025-12-24
tags: physics entropy
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
the "Boltzmann" entropy and the "Gibbs / Shannon" entropy.

Boltzmann entropy is clearly the easiest to understand and reason about. It is the
logarithm of the number of possible states in a system. Suppose you can break a system
$V$ apart into indivisible subsystems, $v$. In this case the Boltzmann entropy is "just"
the size of the system (in terms of these subsystems). This is easy to see, since $W =
v^N$ where $N$ is the size of the system, and since $S_{B} = N \ln v$, the Boltzmann
entropy is, up to a constant, equal to $N$, so it just measures how large the system is.
The easiest example of this is when the system is a number with a given length, the
entropy is then "just" the number of digits.

Although this definition and interpretation is pretty reasonable, its not satisfactory
to me. Logarithms are kind of weird, and I don't think I can make total sense of them
intuitively. If anything, entropy is one of the ways in which logarithms can be made to
make the most sense, or have the most "contact" with something physical (measuring size)
to the point where I wonder if the flow of understanding should be the other way around,
from entropy to logarithms.
