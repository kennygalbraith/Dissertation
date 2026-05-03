**Abstract**:  
This paper challenges the standard view that questions cannot be represented in iconic formats. Early foundational theorizing about the semantics of questions, and their implementation in formal systems, assumes that inquisitive content can only be represented _symbolically_. On this view, the content of questions are conceptualized as _decisions among alternatives_, with uncertainty/ignorance represented in terms of those _alternatives_. Yet, given the _all-at-once_, or uniform, nature of iconic formats, it follows that such formats cannot represent inquisitive content.

This paper, however, argues that this assumption is mistaken. By turning to iconic systems in the mind --- namely perception --- I argue that their are strong reasons for thinking that inquisitive are iconicly represented. In particular, a core assumption underlying theorizing about perceptual processing is that these processes are best characterized as a form of inquiry --- .e.g, addressing questions like _Is that X or Y_. By turning to models of perception, I claim we gain insight into how inquisitive content may be represented iconicly.

Ultimately, I argue that the distinction between inquisitive icons and symbolic representations hinges on how _uncertainty or ignorance_ is represented. Whereas, in symbolic systems, uncertainty is represented as discrete alternatives, iconic systems represent uncertainty in a graded and holistic manner, often exploiting mechanisms that carry information over time.

Having developed an account of inquisitive content in perception, I argue that a central payoff of this account is its ability to make sense of a variety of inquisitive icons in _communication_. That is, there are a variety of inquisitive that pervade iconic communication, yet, pace the standard view, have gone unappreciated. By identifying inquisitive icons in perception, the account is able to vindicate these intuitive communicative instances, while providing a more principled account. In the end, the resulting account maintains important tenets from the standard semantics of questions while rejecting the assumptions about their format. Thus, it expands the scope of theorizing about inquisitive content beyond language and symbolic formats.

**Major Argumentative Moves/Upshots**

Distinguishing between _Force_ and _Content_:

- While there might be intuitive instances of inquisitive icons in communication, the fact that they are genuinely inquisitive can be doubted.
    - Instances of inquisitive icons can always be re-described as instances without inquisitive content: one might claim that the content of such _icons_ aren't genuinely inquisitive, but may acquire _question-asking functions_ in particular contexts of use.
    - Call this, the **_force view_**:
        - There are no inquisitive icons, but some iconic representations can be used with a question-asking function
    - This view pairs nicely with the thought that iconic systems don't different representations similar to those of major clause types.
    - For instance, consider _pointing_ (Though probably not iconic, yet certainly not symbolic). The content of gestural pointing _alone_ doesn't appear to have a typical force, though it can be used to function similar to assertive, directives, and inquisitive
- Consequently, showing that an iconic representation is genuinely inquisitive requires careful analysis of its semantic content, rather than its force or function: that is, determining whether its _procedural_ or _intensional_ role within the representational system is inherently question-like, rather than merely acquiring a question-asking function in context.

Inquisitives in Perception:

- It is widely held that the representations employed in perceptual processing are iconic.
- Furthermore, following _Helmholtz_, perceptual processing is often explained in terms of inferences, involving a transition from sensory input to representations of external causes.
- This inferential process is frequently interpreted as having an inquisitive structure:
    - _How do we get from raw sensory input to a representation of its most plausible external cause?_
- In this way, perceptual processing can be fruitfully modeled as addressing questions about the environment:
    - For instance, in object recognition: _What is X? Is it Y?
- Ultimately, I take this as _prima facie_ motivation for the fact that there are inquisitive representations, but full more certain motivation let's turn to the semantics underlying models of perception.
- Crucially, there is a wide variety of frameworks employed to model perceptual processing, which operate at differing levels of explanation.
    - For instance, there is a large family of models that employ probabilistic frameworks for perception (e.g., Bayesian accounts and active inference).
- However, these models assume the _computational role_ of uncertainty, often by defining uncertainty representations as probability distributions
    - Yet, the aim of this project is to understand _how uncertainty is implemented_ at the algorithmic level: these models can be seen as characterizing the broad computational role of uncertainty, but not the mechanisms by which it is realized in perceptual processing.
    - To this end, a broad class of algorithms—namely _sequential sampling models_—are particularly instructive.
        - They are compatible with probabilistic models and can closely approximate Bayesian updating.
        - They explain how uncertainty arises through the accumulation of noisy sensory evidence over time.
    - Ultimately, a key insight from this class of models is that uncertainty is represented _dynamically_.
        - As decision-making models, they produce categorical outcomes (e.g., via threshold crossing or winner-take-all dynamics).
        - Consequently, alternative representations are not jointly maintained at the point of decision.
        - However, uncertainty is expressed over time through noise and variability in the accumulation process.

Communicative Instances:  
**Upshot**: I argue that the way that uncertainty is represented in SSMs helps explain instances of inquisitive icons in communicative systems.
- Here, I start [[Sketching a Semantics for Inquisitive Icons]]
- Like SSMs, uncertainty between alternatives often exploits relations carrying information about _time_.
    - However, while they _typically_ exploit time, not all instances are limited to it: more generally, it is shown that uncertainty in inquisitive icons must exploit *continuous relations.
	