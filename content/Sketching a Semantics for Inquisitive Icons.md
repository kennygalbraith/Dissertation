
## The Case
Consider the following as apparent inquisitive icon:

![[II1.png|377]]
(Fig.1)

The rough idea here is that this '8-bit'(not actually 8-bit) representation of a fruit has inquisitive content. As a low-resolution depiction, the information it carries is ultimately *ambiguous*. Like other bistable perceptual phenomena (e.g., Duck-Rabbits and Necker cubes), this 8-bit representation has the content to support multiple alternative representations. Intuitively, with a better resolution (say, a 64-bit depiction) the resulting representation might resolve to a representation of an apple or a mango. However,  unlike other multi-stable percepts, we are *not* 'forced to see' the fruit as any particular way as it is represented in this 8-bit format. That is, we don't necessarily see an apple, or a mango, in the same way that we must necessarily see a duck or rabbit when viewing duck-rabbits; rather, what represented is simply an ambiguous fruit.

For now, it is important to note that the claim that this representation has inquisitive content is just to claim that the semantic content of the representation *typically or normally* supports an inquisitive force or function. In other words, the semantic content of the 8-bit fruit has features that, when typically employed *in a context*, gives rise to an inquisitive function. Meaning, when employed in a communicative context, the representation may acquire a question-asking force; and in non-communicative contexts, it supports general *information-seeking* behavior. (N.B., in my more specific view these representation serve as the content of [[Curiosity]].)

To really clarify the way in which the content 8-bit fruit supports alternative representation, we can think of the 8-bit representation as an information state plotted along a more general information structure, whereby information states are ordered by their resolution --- that is, how many 'bits' they contain. For instance, ... 8-bit &rarr; 16-bit &rarr; 24-bit &rarr; 32-bit &rarr; 64-bit .... At some point in the ordering, say 64-bit, the information states carries enough information to support a representation of a mango *or* an apple, but *not the other*:  

![[II2.png|384]]
(Fig.2)

## Formal-*Ish*

With this in mind, we can sketch a semantics for Fig.1 that captures  the fact that it supports multiple representations in Fig. 2. For, the information structure gestured at in the previous section give rise to a natural interpretation in terms of standard *possible-world semantics*.

That  is, we can model each information state as a set of worlds, where each world represents a fully specified way the object could be (e.g., an apple or a mango, with all relevant features). So,  an $n$-bit representation can be thought of as imposing a set of constraints on this space of worlds, thereby restricting which worlds remain possible.

For instance, the information state corresponding to our 8-bit fruit, $i_8$, is the set of all worlds compatible with a coarse set of constraints (e.g., *fruit-shape*, *has-a-stem*, *fruit-coloring*). These constraints represent  the object as some kind of fruit, but they are not fine-grained enough to distinguish between an apple and a mango. Consequently, as resolution increases, further constraints are imposed, resulting in smaller information states: $i_8 \supseteq i_{16} \supseteq i_{32} \supseteq i_{64}$

Stated a bit more formally,
- We have a set of worlds, $W= \{ w_{1}...w_{n} \}$ 
- Where information states, $i_{n}$, are subsets of $W$: 
	- $i_{n} \subseteq W$ 

More concretely,  suppose that $i_{8} = \{w_{1}....w_{8}\}$, then we can think of smaller information states with higher-resolutions as singleton sets of worlds the fully represent the fruit as being *a mango* or *an apple*: respectively, $i_{64m} = \{ w_{1}\}$ and $i_{64a} = \{ w_{2}\}$

![[II3.png|452]]
$i_8 \supseteq i_{16} \supseteq i_{32} \supseteq i_{64a}$
(Fig. 3)

From this,  we can more perspicuously represent the fact that the resolution ordering terminates into two branching information states that maximally specify the fruit as either a mango ($w_{1}$) or an apple ($w_{2}$):
$i_8 \supseteq i_{16} \supseteq i_{32} \supseteq  \begin{cases}  i_{64m} \\  i_{64a}  \end{cases}$

Loosely following inquisitive semantics, we can demonstrate the inquisitive content of $i_{8}$ given that it supports multiple *alternatives*:

>DEF. **Alternatives**: maximally informative information states within $i_n$.
		$Alt(i_n) = \{\, i \subseteq i_n \mid \neg \exists i' \subseteq i_n \; (i \subset i') \,\}$

Thus, 

$Alt (i_{8}) = \{ i_{64m},i_{64a}\}$

## Take-Aways

To note, this sketch is not an iconic semantic analysis of Fig. 1 ---- nothing in the metalanguage seems to iconically encode the content of the representation. Rather, the foregoing analysis is merely a proof of concept demonstrating that iconic representations  can be modeled with inquisitive content, even if that content is modeled or defined symbolically. 

That said, steps towards a more iconic analysis seem somewhat straight-forward: the crucial thought is that we want some way of iconically encoding the information structure corresponding to the resolution-ordering,$i_8\supseteq i_{16} \supseteq i_{32} \supseteq i_{64}$. This seems feasible in a modal-semantics, where we map bits or pixels to binary partitions in logical space (though encoding color might prove too unwieldy).

Nonetheless, the main takeaway of this write-up is to demonstrate how inquisitive icons represent uncertainty. The foregoing case is exceptional in this respect: it is one in which uncertainty is represented through conventions governing resolution. In this respect, the information structure of the representation encodes uncertainty synchronically: that is, the initial ambiguous fruit represents uncertainty between two alternatives within a single representation.

However, as I will argue, the key to understanding many other cases of inquisitive icons is that the information structures underlying them (such as the resolution ordering) exploit continuous relations, often relations that also carry information about _time_, to represent uncertainty between alternatives. In this respect, inquisitive icons exploit informational structures that represent uncertainty diachronically.